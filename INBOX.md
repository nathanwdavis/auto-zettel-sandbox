# Inbox

Questions, corrections, and instructions for the knowledge base. Every
maintenance run reads this file FIRST and prioritises entries marked `new`.
Human feedback here is authoritative and overrides automated decisions (QA-4).

Statuses: `new` -> `in-progress` -> `answered` -> `archived`.

---

## 2026-08-31 — Spike: prove the remote cycle end-to-end

- **status:** answered
- **answer:** The shared mechanism is a reinvestment feedback loop — each
  period's output is fed back into the base that produces the next period's
  output. See
  [[atomic-notes-and-compound-interest-share-a-reinvestment-loop--202608311038]],
  grounded in the existing fixture notes plus one new verified source
  (Housel, *The Psychology of Money*, ref 202608311036, verified live via
  Open Library and captured to raw/).
- **priority:** normal
- **asked_by:** human

This is a small verification run. Answer from the notes already in this
repository plus at most ONE new source: what is the shared mechanism between
atomic note-taking and compound interest? If you research the one new source,
capture it into raw/ first and verify it. Keep the cycle small and finish
cleanly — the point is to exercise the full path (lock, branch, gates, PR),
not to grow the wiki.

## 2026-08-31 — Follow-up: strengthen grounding of Housel literature note

- **status:** answered
- **answer:** Full chapter text was not obtainable (Open Library/archive.org
  list the ebook as "restricted" availability, so it could not be fetched
  directly). Captured a small set of verbatim ch. 4 quotations instead —
  cross-checked word-for-word across two independent secondary sources
  before use — into
  raw/202608311119-housel-ch4-confounding-compounding-excerpt.txt, linked
  from the reference note's new `excerpt_captures` field. Re-scored
  [[housel-on-compounding-as-time-in-the-loop--202608311037]] at
  groundedness 0.90 (was 0.72): both propositional claims (duration over
  rate; outsized/counterintuitive result) now have a direct corroborating
  quote. This is a strong excerpt, not a complete-text verification — that
  residual gap is recorded in the literature note itself rather than
  hidden, in case a future run gets real chapter access.
- **priority:** low
- **asked_by:** maintenance-run (critic finding, 2026-08-31 cycle)

literature/housel-on-compounding-as-time-in-the-loop--202608311037 scored
groundedness 0.72 (FLAG): its raw capture is Open Library bibliographic
metadata only, which corroborates the locator (ch. 4, "Confounding
Compounding") but not the summary's propositional content. Capture actual
chapter text into raw/ and re-score before building further on this note.

## 2026-08-31 — Follow-up: literature/ahrens-on-the-slip-box-workflow only covers the Introduction and opening of Chapter 1

- **status:** new
- **priority:** low
- **asked_by:** maintenance-run (2026-08-31 cycle, gap-fill against topic 'zettelkasten method')
- **2026-08-31 (later cycle) attempt:** re-fetched the official takesmartnotes.com preview PDF
  (current URL redirects to a squarespace CDN copy) and confirmed it is the identical pp. 1-11
  Introduction/Ch.1-opening preview already captured — no wider preview has been published.
  Internet Archive holds a scan but it is lending-restricted (no full-text access without
  borrowing). No progress possible without a purchased or library copy. Left open.

This cycle replaced the note's content-free placeholder ("Own-words summary
of [[ref]].") with a real summary grounded in verbatim quotes captured from
the official author-published preview PDF of *How to Take Smart Notes*
(takesmartnotes.com) — see
raw/202608311141-ahrens-ch1-everything-you-need-to-know-excerpt.txt and
[[ahrens-on-the-slip-box-workflow--202608301100]]. The preview only reaches
the Introduction and the opening of Chapter 1 ("Everything You Need to
Know"), which covers *why* a trusted structure beats a plan, not yet the
fleeting-note/literature-note/permanent-note taxonomy itself — that content
is in Chapter 6 ("Simplicity Is Paramount", pp. 36-44) and Chapters 9-11
("Separate and Interlocking Tasks" / "Read for Understanding" / "Take Smart
Notes", pp. 55-104). A future run should capture that range (a library copy,
a different legitimate preview, or purchased access) and either extend this
literature note or write a second one, then ground the existing
atomicity/titles permanent notes
([[one-idea-per-note-enables-reuse--202701010002]],
[[titles-stated-as-claims-force-clarity--202701010003]]) to it if their
claims do turn out to be directly attributable to Ahrens rather than
independent synthesis.

## 2026-08-31 — Follow-up: two key same-God sources went uncited because they could not be read

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

The ad-hoc cycle for inquiry 202608311909 identified two sources directly on
point that were NOT used, because neither could be read and an unread source is
not a source:

- John Hick, 'Jews, Christians, Muslims: Do We All Worship the Same God?', in
  Disputed Questions in Theology and the Philosophy of Religion (Palgrave
  Macmillan, 1993), 146-63. DOI 10.1007/978-1-349-12695-8_9. Verified to exist
  via Crossref; Springer serves a JavaScript bot challenge, so neither full text
  nor abstract was retrievable.
- Miroslav Volf, Allah: A Christian Response (HarperOne, 2011),
  ISBN 9780061927072. Verified via Open Library. This is the most prominent
  book-length argument on the affirmative side and the base currently has no
  substantial 'yes' argument from a single named theologian - Nostra Aetate and
  Saritoprak carry that side alone.

Also: literature/tachin-makes-accepted-trinitarian-worship-the-test and
literature/vroom-finds-the-same-god-arguments-come-from-four-disciplines rest on
publisher abstracts only. Vroom's own conclusion is explicitly unknown to the
base. A future run with library or institutional access should capture the full
texts and re-score all three notes.

**2026-08-31 (later cycle) attempt:** re-checked all four sources for legitimate
open access. Hick's chapter is still behind Springer's bot challenge, no OA
mirror found. Volf's book is still lending-restricted on Internet Archive; the
Yale Center for Faith & Culture page found in search covers a different
multi-author volume, not Volf's own argument, so it does not substitute.
Tachin's article turned up on academia.edu but the page 403s without a login.
Vroom remains paywalled on Cambridge Core with no OA copy located. No
pirated/scraper mirrors were used (source-legitimacy norm). All four still
require institutional/library/purchased access; nothing changed this cycle.
Left open.

**2026-08-31 re-check (maintenance-run):** Re-tried Hick and Volf again in a
separate concurrent cycle. Hick's chapter is still paywalled at the Springer
DOI (no institutional access from this environment); a general web search
turned up no accessible mirror of the actual essay text. Volf's book on
Internet Archive (archive.org/details/isbn_9780061927072) is
`Access-restricted-item`: no download or full-text search, only a
controlled-digital-lending "borrow" that requires a logged-in account this
run does not have. Two review essays (The Gospel Coalition, Christian
Scholar's Review) quote short passages of Volf's own text with page numbers,
but their quoted wording didn't overlap enough between the two to
cross-verify any single sentence word-for-word (the standard this base held
to for the Housel excerpt) — so no literature/reference note was written
from them rather than risk an unverified "verbatim" quote. Both sources stay
open; they need either a library loan, institutional Springer access, or a
purchased copy.

## 2026-09-01 — Follow-up: Bogardus & Urban 2017 is grounded on its abstract only. The article (Faith and Philosophy 34.2, DOI 10.5840/faithphil201741178) is open access at place.asburyseminary.edu, but the PDF and its PhilPapers/PhilArchive mirrors sit behind a Cloudflare bot challenge this environment cannot pass, and the Wayback copy is blocked by the egress policy. A run with browser or library access should capture the full text and re-score literature/bogardus-and-urban-make-co-reference-turn-on-dossier-dominance--202609010838 (currently limited to the stated framework, two-part test, and 'it depends' conclusion). Same class of gap as the open Hick/Volf item from 2026-08-31.

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

(no further detail)
