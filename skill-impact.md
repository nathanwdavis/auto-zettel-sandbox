# Skill impact tracker

Every child-skill proposal is recorded here with its metadata, target skill,
unified diff, A/B scores, and the Accepted/Rejected outcome with a reason
(FR-36). Rejected proposals stay listed so they are not re-proposed.

The knowledge layer is never rolled back, whatever a proposal's outcome (FR-33).

| date | proposal | target skill | outcome | reason |
|------|----------|--------------|---------|--------|
| 2026-09-01 | 202609011101 | source-access-triage | proposed | Codify the repeatedly re-invented procedure for sources that exist but cannot be read: legitimate access ladder, abstract-only grounding tiers, the two-witness excerpt cross-check, and durable INBOX gap records. Motivated by the Hick/Volf, Tachin/Vroom, Housel, Ahrens, and Bogardus & Urban traces (see PURPOSE.md). |
| 2026-09-01 | 202609011101 | source-access-triage | trial | with=0.92 without=0.963 (n=3) |

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
