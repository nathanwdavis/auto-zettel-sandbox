---
skill: capture-verification
status: proposed
proposal_id: '202610061551'
kind: patch
proposed: '2026-10-06'
decided: ''
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
log.md and INBOX.md from 2026-09-04 to 2026-09-18. Approved by the owner on
2026-09-21 (proposal 202609182350).

**Patch, 2026-10-06 (proposal 202610061551).** Proposed by the skill-smith
step of the 2026-10-06 maintenance cycle (run zettel/run-20261006154005; the
smith worked in the isolated worktree zettel/smith-20261006 off c5619fa),
the first smith run since 2026-09-18 on a weekly cadence. The smith read
manifest.json (522 notes: 195 permanent, 169 literature, 155 reference, 3
MOC) and INDEX.md, the whole of skill-impact.md (two proposals, both
approved, none rejected), the log.md traces of 2026-09-18, the 2026-09-21
promotion session and maintenance cycle, 2026-09-23, the three 2026-10-03
runs and the open 2026-10-06 cycle, and the INBOX entries of 2026-09-18,
2026-09-21 and 2026-10-03. The patch makes the approved skill's reference
implementation agree with its own procedure. It changes no rule about what a
note may quote.

## Patterns-Addressed

### Created 2026-09-18

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

### Patched 2026-10-06

The first full-scope run of the approved skill found that its reference
implementation contradicts the skill's own procedure, and filed the fix for
this smith:

- **2026-09-21T21:09Z** (log, step 6 critic, first cycle after promotion):
  2,452 quoted spans across every literature and permanent note; "600 raw
  misses, reduced to 536 by fixing FOUR defects in the skill's own reference
  implementation -- no case folding (45 spans, and the skill's step 1 already
  requires a case-insensitive search ...), no markdown-emphasis stripping, no
  editorial-bracket handling ([W]e, [f]or), and no hyphenation joining across
  a capture's line wrapping." The INBOX entry of the same date, "HUMAN RULING
  NEEDED: the first full-scope capture-verification sweep, 536 flagged
  spans", names the four defects and files the patch here; the
  **2026-09-21T21:10Z** step 7 line defers it to this cycle.

Reproduced on 2026-10-06 with the approved code. On the 316 notes present on
2026-09-21 it gives exactly that sweep's baseline, 2,452 spans and 600
misses. On the whole base today it gives 2,804 spans and 623 misses. Each fix
was switched on alone, and every span it clears was read:

1. **Case** (44 spans): 29 differ only in a first letter capitalised or
   lowered at the quotation's start, as in
   [[the-shema-confesses-one-lord-with-a-live-translation-crux--202608311931]];
   15 differ further inside, chiefly
   [[tachin-makes-accepted-trinitarian-worship-the-test--202608311935]],
   whose captured abstract is in Title Case. Those 15 are now listed as CASE,
   not hidden, because step 4 still wants a lemma's capitals restored.
2. **Emphasis markers** (23): `*d*`, `**...**` and `*ad extra*` in
   [[agarwal-nunes-and-blunt-audited-the-classroom-half-and-declined-to-meta-analyse--202609040510]]
   and [[hodge-on-the-two-readings-the-councils-ruled-out--202609041715]].
3. **Editorial brackets** (8): `[W]e`, `[T]he`, `[f]or` in the Agarwal note
   and `o[f]` in
   [[luhmann-frames-the-slip-box-as-a-communication-partner--202609010112]],
   where the capture really reads "partner o communication", a typo in the
   published translation. That is why a bracket is treated as a gap, like an
   ellipsis, and not just unwrapped.
4. **Line-end hyphenation** (37 spans in 13 notes, each checked to contain
   a word its capture breaks at a line end): ten in
   [[van-horn-records-the-concession-and-argues-that-counterfactuals-can-be-natural-or-free-but-not-middle--202609111817]],
   nine in
   [[laing-argues-that-calvinist-middle-knowledge-is-caught-in-a-dilemma--202609111818]],
   four in
   [[ware-makes-exhaustive-foreknowledge-the-boundary-of-evangelicalism--202609111819]].
   One Ware span crosses both `un-` / `acceptable` and a real compound broken at
   a line end, `logically-` / `necessary`, so neither joining nor keeping the
   hyphen works for the whole capture. Hyphens and dashes are therefore
   dropped on both sides instead.

Three more checker false positives of the same kind turned up while
measuring the patch, and are fixed with it:

5. **Dash typography** (12): a note's ` -- ` against the capture's em dash, as
   in [[patach-eliyahu-names-the-sefirot-and-leaves-ein-sof-nameless--202609011536]]
   ("One -- but not in number").
6. **Space before punctuation** (3): the stored text capture raw/202609042070
   reads "cause , for", which
   [[aquinas-argues-simplicity-from-dependence-and-stops-short-of-the-attributes--202609042076]]
   quotes as "cause, for".
7. **JSON line breaks** (3): the bible-api captures hold the verse text with
   escaped `\n`, as in
   [[mark-6-1-6-at-nazareth-jesus-could-do-no-mighty-work-and--202609230045]]
   ("healed\nthem").

The 2026-10-03T21:20:59Z critic line's "two misses are New Advent anchor-tag
artifacts" did not reproduce under the approved code, because the double tag
strip already covers it. Nothing was changed for it.

Measured result: on the 2026-09-21 notes, 600 misses become 498 with the four
filed fixes and 483 with all seven, plus 15 CASE lines. The sweep's own
four-fix script, which gave 536, is not on file, so the two cannot be
compared span by span. On the whole base, 623 become 492, plus 15 CASE.
Negative controls on real references still report MISS for a fabricated
quotation, for numerals and wording altered behind a bracket and emphasis,
for wording altered after a bracket, and for wording altered across a
capture's line-end hyphen. Case-altered spans are reported as CASE. One
accepted leniency is new: a misplaced hyphen inside a word now passes.

Not addressed, deliberately: the questions the 2026-09-21 entry puts to the
owner. These are translations in double quotes, the base's own phrases in
double quotes, and gate enforcement. Most of the 492 remaining misses fall
under them. A few are real slips in notes that the skill already tells a run
to fix, such as a silently corrected OCR "beirg" in the Paley note and a long
s modernised from the OCR "fo" in the Price-based compounding note.

Considered and not taken, because one proposal is the limit: the INBOX entry
"Access: NPNF texts" (2026-09-18) asks for NPNF host notes in
source-access-triage. Its rule that bytes are evidence and size is not is
already step 1 here. The host notes, and the 2026-09-04 replication-audit
candidate above, remain available to a later smith.

## Evolution-History
| date | change | outcome |
|------|--------|---------|
| 2026-09-18 | created (proposal 202609182350) | proposed |
| 2026-09-21 | promoted | Accepted |
| 2026-10-06 | patched (proposal 202610061551): reference implementation's false positives fixed (case folding with CASE lines, emphasis markers, editorial brackets as gaps, hyphens and dashes dropped, no space before punctuation, JSON line breaks); steps 3 and 5 updated to match; note added that the 2026-09-21 ruling is pending | proposed |
