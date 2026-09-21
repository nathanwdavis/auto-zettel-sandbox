---
skill: capture-verification
status: approved
proposal_id: '202609182350'
kind: create
proposed: '2026-09-18'
decided: '2026-09-21'
---
# Purpose — capture-verification

<!-- FR-34: maps this child skill back to the motivating knowledge patterns.
     status is proposed|approved only: a rejected skill's files are reverted,
     so rejection lives solely in skill-impact.md (FR-36). -->

## Origin

Proposed by the skill-smith step of the 2026-09-18 maintenance cycle
(session-as-agent, run branch zettel/run-20260918232345, work carried on
claude/hidden-knowledge-god-ucv4n1), the first skill-smith step run since
2026-09-01 although the cadence is weekly. The smith read manifest.json (330
notes after this cycle's additions), the whole of skill-impact.md (one prior
proposal, source-access-triage, approved 2026-09-01), and the run traces in
log.md and INBOX.md from 2026-09-04 to 2026-09-18.

## Patterns-Addressed

One procedure, re-invented from scratch in at least five cycles, and one
failure it would have caught earlier each time:

- **2026-09-04T01:12Z** (critic, same-God Islamic cycle): "Every quoted span
  of 12+ characters across all six new notes was then machine-checked against
  the captures under Unicode normalisation: all present, zero misses" -- the
  first appearance of the check, written ad hoc. The INBOX entry of the same
  day, "Tooling, HIGH: the Arabic normaliser used for the mechanical
  quotation checks can swallow the letters it is supposed to keep", is the
  first defect in an ad hoc implementation.
- **2026-09-04** (INBOX, "Process finding from the critic: an excerpt capture
  must not carry the capture author's own derivation, and this cycle's did")
  -- the header-honesty half of the procedure, stated as a rule and not
  encoded anywhere.
- **2026-09-05T20:24Z** (critic, simplicity cycle): the SEP capture
  raw/202609042072 "DOES NOT CONTAIN the passages three notes cite it for --
  it ends at '1. Motivation' while its header claims it runs to the start of
  section 2"; the log line itself asks for the rule "a header says what was
  meant to be captured, only the bytes say what was" to be filed for the
  skill-smith.
- **2026-09-05** (fleeting note 202609052103, swept into INBOX on 2026-09-18):
  "Byte count and file size are not evidence that a capture contains a given
  passage" -- the same lesson, learned again on the NPNF hosts.
- **2026-09-06T19:16Z** (critic, Grudem omniscience cycle): the check re-run
  ("36/36 exact") and a capture found to have converted typographic quotation
  marks while its header said otherwise.
- **2026-09-15T19:40Z** (hidden-knowledge cycle): the check rewritten again,
  "132 spans, 0 misses after four corrections"; its first version paired
  quotes by regular expression and reported prose between short quotations as
  misses, a defect fixed in the same session and encoded in step 3 here.
- **2026-09-18** (this cycle): rewritten a fifth time; 44 spans, five
  corrections, including two uppercase lemmata and a Hebrew abbreviation
  containing an ASCII quote mark, both now in step 5.

Notes whose grounding depended on the check: every literature and permanent
note of the cycles above, among them
[[the-knowledge-of-god-divides-into-what-he-has-revealed-and--202609151913]],
[[five-jewish-witnesses-read-deuteronomy-29-28-as-a-partition--202609182340]]
and [[deut-29-29-partitions-knowledge-and-grudem-partitions-will--202609081906]].

A second candidate was considered and not taken, because one proposal is the
limit: the 2026-09-04 offloading cycle's rule that when a source has been
replicated, the replicating paper's audit of the original should be read
first. It is recorded in the INBOX entry "Leads left open by the offloading
cycle" and remains available to a later smith.

## Evolution-History
| date | change | outcome |
|------|--------|---------|
| 2026-09-18 | created (proposal 202609182350) | proposed |
| 2026-09-21 | promoted | Accepted |
