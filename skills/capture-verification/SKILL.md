---
name: capture-verification
description: House procedure for proving that a capture in raw/ actually contains what a note cites from it - search the bytes before citing, keep the capture header honest about extent, and machine-check every quoted span of every new or changed note against the captures it links before the critic gate.
---

# Capture verification

<!--
A self-authored child skill. Sandboxed under the CONTENT repo's /skills/ until
a human promotes it (FR-37). It must never modify the bootstrap skill repo.
-->

## When to use

Three moments in every cycle that writes or cites a capture:

- **before a note relies on a capture** for a passage, a page range, or a
  quotation, especially a capture written by an earlier cycle;
- **when writing a capture** whose extent is less than the whole source (an
  excerpt, a section page, a bounded set of segments);
- **after writing or amending any note**, before the critic gate (step 6 of
  the maintenance cycle), for every literature and permanent note touched.

Not for scoring groundedness (the critic's rubric) or for choosing sources
(source-access-triage). This skill answers one question only: does the file
in raw/ contain the words the note says it does?

## Procedure

1. **Search the bytes, never the size.** Before citing a passage from a
   capture, find the passage in the capture with a search that ignores case,
   HTML markup and whitespace. A 56 KB capture can hold a table of contents
   and opening sections and still lack the one section a note needs (the
   Athanasius cycle, 2026-09-05); a capture whose header says it runs to
   section 2 can end at section 1 (the SEP simplicity capture, found by the
   2026-09-05 critic). Byte count, file size and the header are not evidence
   that a passage is present. If the passage is not in the bytes, the capture
   does not ground the note: capture again (a new file; raw/ is immutable),
   or attach a new excerpt as `excerpt_captures` on the reference, and never
   cite from memory of the live page.

2. **Keep the header honest about extent.** A capture header states what was
   meant to be captured; only the bytes state what was. When writing an
   excerpt, list in the header exactly which sections, segments or pages are
   present and which are not, record the fetch as an ISO-8601 UTC instant or
   window, name the version and its licence as the host declares it, and put
   nothing of the capturer's own into the verbatim blocks: no derivations,
   no reconstructions presented as transcription, no silent changes to
   quotation marks (an export's typographic quotes were once converted to
   straight ones while the header claimed otherwise, 2026-09-06). If markup
   was stripped or whitespace normalised, say so in the header and say
   nothing else was changed.

3. **Machine-check every quoted span after writing.** For each new or changed
   literature or permanent note, extract every double-quoted span of twelve
   or more characters from the body and confirm each is a substring of a
   capture the note is entitled to cite: a literature note's one reference
   capture (plus that reference's `excerpt_captures`); a permanent note's
   every linked reference's captures. Normalise both sides the same way:
   Unicode NFKC, typographic quotes to straight, en, em and figure dashes to
   a hyphen, non-breaking spaces to spaces, whitespace runs to one space, and
   then drop quote characters on both sides so that a note's single quotes
   inside double quotes still match. For HTML captures strip tags twice, once
   to a space and once to nothing, and accept a match in either, because
   inline links split words on one strip and join punctuation on the other.
   Pair quotation marks sequentially, not by regular expression with a
   minimum length, or a short quoted word will pair a closing mark with the
   next opening one and report the prose between them as a miss. Split a
   span on an ellipsis and require every part. Run the check on the note
   files themselves, not on drafts.

4. **Treat every miss as the note's problem.** A span not found is fixed in
   the note, never by editing the capture: restore the source's exact
   wording and case (translations print lemmata in capitals), drop a
   quotation that came from a different reference than the one linked or
   link that reference too, and take this base's own phrases, the owner's
   words, and quotations of other notes out of double quotes (italics or
   plain attribution) so that double quotes in a note mean one thing only,
   the words of a captured source. Re-run until the count of misses is
   zero, and report the count of spans, the count of misses, and each
   correction in the cycle's critic log line.

5. **Know the normaliser's limits.** The Arabic normaliser used in earlier
   cycles can swallow the letters it should keep (INBOX 2026-09-04, HIGH);
   for Arabic, check spans with a normaliser that removes only tashkil and
   tatweel, or check by eye against the capture as well. Hebrew abbreviations
   written with an ASCII quote mark (as in הקב"ה) break sequential pairing:
   paraphrase them or quote around them. Footnote numbers embedded inline in
   a served text (Chavel, Rolt, Strickman-Silver) will sit inside a span that
   crosses them; choose spans that do not.

## Reference implementation

The check the 2026-09-15 and 2026-09-18 cycles ran, kept here so it is not
rewritten a sixth time. Run from the content repo root with the note paths as
arguments; exit status is informational, the miss lines are the finding.

```python
import sys, re, html, unicodedata, yaml, glob

def norm(s):
    s = unicodedata.normalize("NFKC", s)
    for a, b in (("“", '"'), ("”", '"'), ("‘", "'"), ("’", "'"),
                 ("—", "-"), ("–", "-"), ("‒", "-"), ("\xa0", " ")):
        s = s.replace(a, b)
    return re.sub(r"\s+", " ", s)

def letters(s):
    return re.sub(r"['\"`]", "", s)

def capture_texts(path):
    t = open(path, encoding="utf-8", errors="replace").read()
    if path.endswith((".html", ".htm")):
        t = re.sub(r"<script.*?</script>|<style.*?</style>", "", t, flags=re.S)
        return [letters(norm(html.unescape(re.sub(r"<[^>]+>", " ", t)))),
                letters(norm(html.unescape(re.sub(r"<[^>]+>", "", t))))]
    return [letters(norm(t))]

def load(p):
    t = open(p, encoding="utf-8").read()
    m = re.match(r"^---\n(.*?)\n---\n(.*)$", t, re.S)
    return yaml.safe_load(m.group(1)), m.group(2)

cache = {}
def captures(refkey):
    if refkey not in cache:
        m, _ = load(f"reference/{refkey}.md")
        paths = ([m["raw_capture"]] if m.get("raw_capture") else []) + list(m.get("excerpt_captures") or [])
        cache[refkey] = [t for p in paths for t in capture_texts(p)]
    return cache[refkey]

total = misses = 0
for notepath in sys.argv[1:]:
    m, body = load(notepath)
    refs = [m["reference"]] if m.get("type") == "literature" else \
           [l["target_id"] for l in m.get("links", []) if glob.glob(f"reference/{l['target_id']}.md")]
    caps = [c for r in refs for c in captures(r)]
    parts = norm(body).split('"')
    for span in parts[1::2]:
        if len(span) < 12:
            continue
        total += 1
        pieces = [p.strip(" .,;:") for p in re.split(r"\s*\.\.\.\s*", letters(span).strip(" .,;:")) if p.strip(" .,;:")]
        if not caps or not all(any(p in c for c in caps) for p in pieces):
            misses += 1
            print(f"MISS {notepath}: {span[:120]!r}")
print(f"checked {total} spans in {len(sys.argv) - 1} notes, {misses} misses")
```
