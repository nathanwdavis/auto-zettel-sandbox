# Skill impact tracker

Every child-skill proposal is recorded here with its metadata, target skill,
unified diff, A/B scores, and the Accepted/Rejected outcome with a reason
(FR-36). Rejected proposals stay listed so they are not re-proposed.

The knowledge layer is never rolled back, whatever a proposal's outcome (FR-33).

| date | proposal | target skill | outcome | reason |
|------|----------|--------------|---------|--------|
| 2026-09-01 | 202609011101 | source-access-triage | proposed | Codify the repeatedly re-invented procedure for sources that exist but cannot be read: legitimate access ladder, abstract-only grounding tiers, the two-witness excerpt cross-check, and durable INBOX gap records. Motivated by the Hick/Volf, Tachin/Vroom, Housel, Ahrens, and Bogardus & Urban traces (see PURPOSE.md). |
| 2026-09-01 | 202609011101 | source-access-triage | trial | with=0.92 without=0.963 (n=3) |
| 2026-09-01 | 202609011101 | source-access-triage | Accepted | Approved by the repository owner (Nathan Davis), 2026-09-01, who reviewed the proposal and directed promotion ('It looks good'). Accepted despite an A/B trial that did not favor the candidate (with=0.92 vs without=0.963, n=3): the trial's three questions are all same-God/teleology research questions whose sources were already captured, so none of them exercises the skill's actual subject -- what to do when a source cannot be read -- and the small-n delta (-0.043) is within noise for a judge rubric. The procedure it codifies is drawn from five real cycle traces (Hick/Volf, Tachin/Vroom, Housel, Ahrens, Bogardus & Urban) where it was re-invented each time. |
| 2026-09-18 | 202609182350 | capture-verification | proposed | Codify the capture-extent and quotation-span check that five cycles (2026-09-04, 09-05, 09-06, 09-15, 09-18) each rewrote from scratch, with the normaliser rules and the header-honesty rule the critic asked to have filed on 2026-09-05. |
| 2026-09-18 | 202609182350 | capture-verification | trial | with=0.85 without=0.852 (n=3) |

## 202609011101 proposed source-access-triage (2026-09-01)

- kind: create
- motivation: Codify the repeatedly re-invented procedure for sources that exist but cannot be read: legitimate access ladder, abstract-only grounding tiers, the two-witness excerpt cross-check, and durable INBOX gap records. Motivated by the Hick/Volf, Tachin/Vroom, Housel, Ahrens, and Bogardus & Urban traces (see PURPOSE.md).

````diff
diff --git a/skills/source-access-triage/PURPOSE.md b/skills/source-access-triage/PURPOSE.md
new file mode 100644
index 0000000..2ac0e77
--- /dev/null
+++ b/skills/source-access-triage/PURPOSE.md
@@ -0,0 +1,52 @@
+---
+skill: source-access-triage
+status: proposed
+proposal_id: '202609011101'
+kind: create
+proposed: '2026-09-01'
+decided: ''
+---
+# Purpose — source-access-triage
+
+<!-- FR-34: maps this child skill back to the motivating knowledge patterns.
+     status is proposed|approved only: a rejected skill's files are reverted,
+     so rejection lives solely in skill-impact.md (FR-36). -->
+
+## Origin
+
+Proposed by the 2026-09-01 knowability ad-hoc cycle (run
+zettel/run-20260901103000), running the skill-smith step off-cadence at the
+user's request. The smith read manifest.json (87 notes), the full
+skill-impact.md history (empty - this is the first proposal), and the run
+traces in log.md and INBOX.md from every cycle since 2026-08-31.
+
+## Patterns-Addressed
+
+The same failure pattern appears in at least five separate cycles, each time
+handled ad hoc and re-invented:
+
+- Hick 1993 and Volf 2011: identified as directly on point in the same-God
+  cycle, unusable (Springer bot challenge; lending-restricted scan); three
+  separate re-check attempts recorded in one INBOX thread (2026-08-31, twice
+  re-checked later the same day).
+- [[tachin-do-they-worship-the-same-god--202608311925]] and
+  [[vroom-do-all-religious-traditions-worship-the-same-god--202608311926]]:
+  abstract-only grounding invented mid-cycle; the caveat convention was
+  devised on the spot.
+- [[housel-on-compounding-as-time-in-the-loop--202608311037]]: the
+  two-independent-witness cross-check for excerpt quotes was devised for one
+  source and lives only in an INBOX answer.
+- [[ahrens-on-the-slip-box-workflow--202608301100]]: preview-only access,
+  chapters 6-11 still open (INBOX 2026-08-31).
+- [[bogardus-and-urban-make-co-reference-turn-on-dossier-dominance--202609010838]]:
+  open-access article behind a Cloudflare challenge; abstract-only grounding
+  reused from the Tachin precedent by analogy, ladder (Unpaywall -> OA repo ->
+  mirrors -> Wayback) improvised again (log.md, 2026-09-01 Anselm cycle).
+
+The procedure exists but only as folklore scattered across INBOX threads;
+this skill writes it down so a run follows it instead of re-deriving it.
+
+## Evolution-History
+| date | change | outcome |
+|------|--------|---------|
+| 2026-09-01 | proposed (create) | pending |
diff --git a/skills/source-access-triage/SKILL.md b/skills/source-access-triage/SKILL.md
new file mode 100644
index 0000000..639dbb7
--- /dev/null
+++ b/skills/source-access-triage/SKILL.md
@@ -0,0 +1,60 @@
+---
+name: source-access-triage
+description: House procedure for a source that exists but cannot be read from this environment - the legitimate access ladder, when to settle for abstract-only grounding, the excerpt cross-check standard, and how to record the gap so a later run can close it.
+---
+
+# Source access triage
+
+<!--
+A self-authored child skill. Sandboxed under the CONTENT repo's /skills/ until
+a human promotes it (FR-37). It must never modify the bootstrap skill repo.
+-->
+
+## When to use
+
+A source is directly on point and verifiably exists (Crossref/Open Library
+hit, or a publisher page), but the full text does not come back: paywall,
+Cloudflare bot challenge, lending-restricted scan, JS-only viewer. This skill
+decides what the run may claim from it and what it must record. An unread
+source is not a source (repo norm since the 2026-08-31 same-God cycle).
+
+## Procedure
+
+1. **Climb the access ladder before giving up, in this order.** (a) The
+   publisher's own page. (b) The journal's official OA repository, found via
+   Unpaywall by DOI (`api.unpaywall.org/v2/<DOI>?email=<mailto>`). (c) Author
+   or institutional pages (PhilArchive/arXiv-style archives, university
+   repositories). (d) A public-domain or author-published etext (Gutenberg,
+   CCEL, an official preview PDF). (e) The Wayback Machine. Never a
+   pirated/scraper mirror (source-legitimacy norm, INBOX 2026-08-31). Record
+   in the reference note which rungs failed and how - "unreachable" must stay
+   distinguishable from "does not exist".
+
+2. **Settle the grounding tier honestly.** Full text read -> normal notes.
+   Publisher abstract only -> reference note body opens with "**Abstract
+   only**", the literature note states in its first paragraph that it records
+   the stated framework/conclusion, not internal argumentation, and no note
+   quotes or paraphrases beyond the abstract (Tachin/Vroom/Bogardus pattern).
+   No abstract either -> no reference note at all; the source is mentioned
+   only in INBOX as an open item (Hick/Volf pattern).
+
+3. **Excerpt cross-check standard.** A verbatim quotation taken from a
+   secondary source (a review, a preview) may be captured and cited only if
+   the identical wording, with a locator, appears in at least two independent
+   secondary sources (the Housel ch. 4 standard, INBOX 2026-08-31). One
+   witness is not verification; near-matching wording is a reason to refuse,
+   not to harmonize.
+
+4. **Record the gap where the next run will see it.** One INBOX entry (via
+   `capture.py inbox`) naming the source, the DOI/ISBN, every access route
+   tried with its failure mode, which notes are grounding-limited by it, and
+   what access would close it (library loan, institutional access, purchase).
+   If an entry for the same source already exists, append the new attempt to
+   it rather than filing a duplicate.
+
+5. **Re-check, don't re-litigate.** A later run touching the same source
+   re-tries only rungs whose state could have changed (a new OA copy, a fixed
+   DOI), appends the attempt and date to the existing INBOX entry, and leaves
+   it open unless the text was actually obtained - then it captures the full
+   text, re-scores the affected literature notes, and marks the entry
+   answered.
````

## 202609011101 trial source-access-triage (2026-09-01)

- scores: with=0.92 without=0.963 (n=3)
- scores-file: trial-source-access-triage-20260901110839.json

## 202609011101 Accepted source-access-triage (2026-09-01)

- kind: create
- reason: Approved by the repository owner (Nathan Davis), 2026-09-01, who reviewed the proposal and directed promotion ('It looks good'). Accepted despite an A/B trial that did not favor the candidate (with=0.92 vs without=0.963, n=3): the trial's three questions are all same-God/teleology research questions whose sources were already captured, so none of them exercises the skill's actual subject -- what to do when a source cannot be read -- and the small-n delta (-0.043) is within noise for a judge rubric. The procedure it codifies is drawn from five real cycle traces (Hick/Volf, Tachin/Vroom, Housel, Ahrens, Bogardus & Urban) where it was re-invented each time.
- scores: with=0.92 without=0.963 (n=3)

## 202609182350 proposed capture-verification (2026-09-18)

- kind: create
- motivation: Codify the capture-extent and quotation-span check that five cycles (2026-09-04, 09-05, 09-06, 09-15, 09-18) each rewrote from scratch, with the normaliser rules and the header-honesty rule the critic asked to have filed on 2026-09-05.

````diff
diff --git a/skills/capture-verification/PURPOSE.md b/skills/capture-verification/PURPOSE.md
new file mode 100644
index 0000000..9df4546
--- /dev/null
+++ b/skills/capture-verification/PURPOSE.md
@@ -0,0 +1,76 @@
+---
+skill: "capture-verification"
+status: proposed
+proposal_id: "202609182350"
+kind: create
+proposed: "2026-09-18"
+decided: ""
+---
+# Purpose — capture-verification
+
+<!-- FR-34: maps this child skill back to the motivating knowledge patterns.
+     status is proposed|approved only: a rejected skill's files are reverted,
+     so rejection lives solely in skill-impact.md (FR-36). -->
+
+## Origin
+
+Proposed by the skill-smith step of the 2026-09-18 maintenance cycle
+(session-as-agent, run branch zettel/run-20260918232345, work carried on
+claude/hidden-knowledge-god-ucv4n1), the first skill-smith step run since
+2026-09-01 although the cadence is weekly. The smith read manifest.json (330
+notes after this cycle's additions), the whole of skill-impact.md (one prior
+proposal, source-access-triage, approved 2026-09-01), and the run traces in
+log.md and INBOX.md from 2026-09-04 to 2026-09-18.
+
+## Patterns-Addressed
+
+One procedure, re-invented from scratch in at least five cycles, and one
+failure it would have caught earlier each time:
+
+- **2026-09-04T01:12Z** (critic, same-God Islamic cycle): "Every quoted span
+  of 12+ characters across all six new notes was then machine-checked against
+  the captures under Unicode normalisation: all present, zero misses" -- the
+  first appearance of the check, written ad hoc. The INBOX entry of the same
+  day, "Tooling, HIGH: the Arabic normaliser used for the mechanical
+  quotation checks can swallow the letters it is supposed to keep", is the
+  first defect in an ad hoc implementation.
+- **2026-09-04** (INBOX, "Process finding from the critic: an excerpt capture
+  must not carry the capture author's own derivation, and this cycle's did")
+  -- the header-honesty half of the procedure, stated as a rule and not
+  encoded anywhere.
+- **2026-09-05T20:24Z** (critic, simplicity cycle): the SEP capture
+  raw/202609042072 "DOES NOT CONTAIN the passages three notes cite it for --
+  it ends at '1. Motivation' while its header claims it runs to the start of
+  section 2"; the log line itself asks for the rule "a header says what was
+  meant to be captured, only the bytes say what was" to be filed for the
+  skill-smith.
+- **2026-09-05** (fleeting note 202609052103, swept into INBOX on 2026-09-18):
+  "Byte count and file size are not evidence that a capture contains a given
+  passage" -- the same lesson, learned again on the NPNF hosts.
+- **2026-09-06T19:16Z** (critic, Grudem omniscience cycle): the check re-run
+  ("36/36 exact") and a capture found to have converted typographic quotation
+  marks while its header said otherwise.
+- **2026-09-15T19:40Z** (hidden-knowledge cycle): the check rewritten again,
+  "132 spans, 0 misses after four corrections"; its first version paired
+  quotes by regular expression and reported prose between short quotations as
+  misses, a defect fixed in the same session and encoded in step 3 here.
+- **2026-09-18** (this cycle): rewritten a fifth time; 44 spans, five
+  corrections, including two uppercase lemmata and a Hebrew abbreviation
+  containing an ASCII quote mark, both now in step 5.
+
+Notes whose grounding depended on the check: every literature and permanent
+note of the cycles above, among them
+[[the-knowledge-of-god-divides-into-what-he-has-revealed-and--202609151913]],
+[[five-jewish-witnesses-read-deuteronomy-29-28-as-a-partition--202609182340]]
+and [[deut-29-29-partitions-knowledge-and-grudem-partitions-will--202609081906]].
+
+A second candidate was considered and not taken, because one proposal is the
+limit: the 2026-09-04 offloading cycle's rule that when a source has been
+replicated, the replicating paper's audit of the original should be read
+first. It is recorded in the INBOX entry "Leads left open by the offloading
+cycle" and remains available to a later smith.
+
+## Evolution-History
+| date | change | outcome |
+|------|--------|---------|
+| 2026-09-18 | created (proposal 202609182350) | proposed |
diff --git a/skills/capture-verification/SKILL.md b/skills/capture-verification/SKILL.md
new file mode 100644
index 0000000..eb9b32e
--- /dev/null
+++ b/skills/capture-verification/SKILL.md
@@ -0,0 +1,148 @@
+---
+name: capture-verification
+description: House procedure for proving that a capture in raw/ actually contains what a note cites from it - search the bytes before citing, keep the capture header honest about extent, and machine-check every quoted span of every new or changed note against the captures it links before the critic gate.
+---
+
+# Capture verification
+
+<!--
+A self-authored child skill. Sandboxed under the CONTENT repo's /skills/ until
+a human promotes it (FR-37). It must never modify the bootstrap skill repo.
+-->
+
+## When to use
+
+Three moments in every cycle that writes or cites a capture:
+
+- **before a note relies on a capture** for a passage, a page range, or a
+  quotation, especially a capture written by an earlier cycle;
+- **when writing a capture** whose extent is less than the whole source (an
+  excerpt, a section page, a bounded set of segments);
+- **after writing or amending any note**, before the critic gate (step 6 of
+  the maintenance cycle), for every literature and permanent note touched.
+
+Not for scoring groundedness (the critic's rubric) or for choosing sources
+(source-access-triage). This skill answers one question only: does the file
+in raw/ contain the words the note says it does?
+
+## Procedure
+
+1. **Search the bytes, never the size.** Before citing a passage from a
+   capture, find the passage in the capture with a search that ignores case,
+   HTML markup and whitespace. A 56 KB capture can hold a table of contents
+   and opening sections and still lack the one section a note needs (the
+   Athanasius cycle, 2026-09-05); a capture whose header says it runs to
+   section 2 can end at section 1 (the SEP simplicity capture, found by the
+   2026-09-05 critic). Byte count, file size and the header are not evidence
+   that a passage is present. If the passage is not in the bytes, the capture
+   does not ground the note: capture again (a new file; raw/ is immutable),
+   or attach a new excerpt as `excerpt_captures` on the reference, and never
+   cite from memory of the live page.
+
+2. **Keep the header honest about extent.** A capture header states what was
+   meant to be captured; only the bytes state what was. When writing an
+   excerpt, list in the header exactly which sections, segments or pages are
+   present and which are not, record the fetch as an ISO-8601 UTC instant or
+   window, name the version and its licence as the host declares it, and put
+   nothing of the capturer's own into the verbatim blocks: no derivations,
+   no reconstructions presented as transcription, no silent changes to
+   quotation marks (an export's typographic quotes were once converted to
+   straight ones while the header claimed otherwise, 2026-09-06). If markup
+   was stripped or whitespace normalised, say so in the header and say
+   nothing else was changed.
+
+3. **Machine-check every quoted span after writing.** For each new or changed
+   literature or permanent note, extract every double-quoted span of twelve
+   or more characters from the body and confirm each is a substring of a
+   capture the note is entitled to cite: a literature note's one reference
+   capture (plus that reference's `excerpt_captures`); a permanent note's
+   every linked reference's captures. Normalise both sides the same way:
+   Unicode NFKC, typographic quotes to straight, en, em and figure dashes to
+   a hyphen, non-breaking spaces to spaces, whitespace runs to one space, and
+   then drop quote characters on both sides so that a note's single quotes
+   inside double quotes still match. For HTML captures strip tags twice, once
+   to a space and once to nothing, and accept a match in either, because
+   inline links split words on one strip and join punctuation on the other.
+   Pair quotation marks sequentially, not by regular expression with a
+   minimum length, or a short quoted word will pair a closing mark with the
+   next opening one and report the prose between them as a miss. Split a
+   span on an ellipsis and require every part. Run the check on the note
+   files themselves, not on drafts.
+
+4. **Treat every miss as the note's problem.** A span not found is fixed in
+   the note, never by editing the capture: restore the source's exact
+   wording and case (translations print lemmata in capitals), drop a
+   quotation that came from a different reference than the one linked or
+   link that reference too, and take this base's own phrases, the owner's
+   words, and quotations of other notes out of double quotes (italics or
+   plain attribution) so that double quotes in a note mean one thing only,
+   the words of a captured source. Re-run until the count of misses is
+   zero, and report the count of spans, the count of misses, and each
+   correction in the cycle's critic log line.
+
+5. **Know the normaliser's limits.** The Arabic normaliser used in earlier
+   cycles can swallow the letters it should keep (INBOX 2026-09-04, HIGH);
+   for Arabic, check spans with a normaliser that removes only tashkil and
+   tatweel, or check by eye against the capture as well. Hebrew abbreviations
+   written with an ASCII quote mark (as in הקב"ה) break sequential pairing:
+   paraphrase them or quote around them. Footnote numbers embedded inline in
+   a served text (Chavel, Rolt, Strickman-Silver) will sit inside a span that
+   crosses them; choose spans that do not.
+
+## Reference implementation
+
+The check the 2026-09-15 and 2026-09-18 cycles ran, kept here so it is not
+rewritten a sixth time. Run from the content repo root with the note paths as
+arguments; exit status is informational, the miss lines are the finding.
+
+```python
+import sys, re, html, unicodedata, yaml, glob
+
+def norm(s):
+    s = unicodedata.normalize("NFKC", s)
+    for a, b in (("“", '"'), ("”", '"'), ("‘", "'"), ("’", "'"),
+                 ("—", "-"), ("–", "-"), ("‒", "-"), ("\xa0", " ")):
+        s = s.replace(a, b)
+    return re.sub(r"\s+", " ", s)
+
+def letters(s):
+    return re.sub(r"['\"`]", "", s)
+
+def capture_texts(path):
+    t = open(path, encoding="utf-8", errors="replace").read()
+    if path.endswith((".html", ".htm")):
+        t = re.sub(r"<script.*?</script>|<style.*?</style>", "", t, flags=re.S)
+        return [letters(norm(html.unescape(re.sub(r"<[^>]+>", " ", t)))),
+                letters(norm(html.unescape(re.sub(r"<[^>]+>", "", t))))]
+    return [letters(norm(t))]
+
+def load(p):
+    t = open(p, encoding="utf-8").read()
+    m = re.match(r"^---\n(.*?)\n---\n(.*)$", t, re.S)
+    return yaml.safe_load(m.group(1)), m.group(2)
+
+cache = {}
+def captures(refkey):
+    if refkey not in cache:
+        m, _ = load(f"reference/{refkey}.md")
+        paths = ([m["raw_capture"]] if m.get("raw_capture") else []) + list(m.get("excerpt_captures") or [])
+        cache[refkey] = [t for p in paths for t in capture_texts(p)]
+    return cache[refkey]
+
+total = misses = 0
+for notepath in sys.argv[1:]:
+    m, body = load(notepath)
+    refs = [m["reference"]] if m.get("type") == "literature" else \
+           [l["target_id"] for l in m.get("links", []) if glob.glob(f"reference/{l['target_id']}.md")]
+    caps = [c for r in refs for c in captures(r)]
+    parts = norm(body).split('"')
+    for span in parts[1::2]:
+        if len(span) < 12:
+            continue
+        total += 1
+        pieces = [p.strip(" .,;:") for p in re.split(r"\s*\.\.\.\s*", letters(span).strip(" .,;:")) if p.strip(" .,;:")]
+        if not caps or not all(any(p in c for c in caps) for p in pieces):
+            misses += 1
+            print(f"MISS {notepath}: {span[:120]!r}")
+print(f"checked {total} spans in {len(sys.argv) - 1} notes, {misses} misses")
+```
````

## 202609182350 trial capture-verification (2026-09-18)

- scores: with=0.85 without=0.852 (n=3)
- scores-file: trial-capture-verification-20260918234633.json
