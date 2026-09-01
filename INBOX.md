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

**2026-09-01 ~09:00 attempt (maintenance-run, browser-equipped remote
session):** this container ships pinned Chromium + Playwright, so the
"browser access" path was tried directly — and it cannot work from this
environment class: the session's egress proxy closes the tunnel on
Chromium's TLS ClientHello for EVERY https host (ws_closed_mid_exchange;
disabling the post-quantum key share did not help), so the browser never
completes a single handshake. Fallbacks all hit Cloudflare 403: curl on
place.asburyseminary.edu/cgi/viewcontent.cgi (landing page loads,
article=2450 PDF blocked), PhilPapers/PhilArchive mirrors (correct
archive id is TOMHTT, not BOGHTT), the r.jina.ai reader relay, and the
server-side WebFetch tool. Semantic Scholar and OpenAlex both confirm
the only OA locations are exactly these blocked ones (oa_status bronze,
no repository fulltext). Conclusion: not obtainable from remote-session
environments at all; needs the laptop path (real browser on a real
network), library/institutional access, or a purchased copy. Left open.

## 2026-09-01 — Follow-up: teleological-arguments ranking rests on Craig plus the SEP survey; broaden the evangelical-assessment base

- **status:** in-progress        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** maintenance-run (2026-09-01 cycle, inquiry 202609010930)
- **2026-09-01 ~14:00 cycle progress:** the Behe-specific irreducible-complexity
  capture flagged by the ~13:00 cycle is done — Behe's own overview essay
  "Molecular Machines: Experimental Support for the Design Inference"
  (discovery.org/a/54, dated 1998-03-01; the page's Editor's Note describes it
  as an overview of *Darwin's Black Box*) captured as bounded excerpts to
  raw/202609011400, with [[behe-molecular-machines--202609011400]],
  [[behe-grounds-the-design-inference-in-irreducible-molecular-complexity--202609011405]],
  and
  [[the-irreducible-complexity-argument-denies-selection-a-continuum-of-function--202609011410]];
  inquiry 202609010930's rank-3 caveat updated in place. Still open: Plantinga
  ("Two Dozen (or so) Theistic Arguments" or *Where the Conflict Really Lies*),
  McGrath (*A Fine-Tuned Universe*), and Collins (Blackwell Companion chapter),
  all likely paywalled; and the BioLogos web critiques remain 429-blocked from
  remote sessions. Entry stays in-progress.
- **2026-09-01 ~13:00 cycle progress:** the remote-capturable candidate is done —
  the BioLogos-versus-Discovery-Institute exchange is captured as the published
  PSCF pair (both PDFs served openly by the ASA itself): Venema, "Seeking a
  Signature" (PSCF 62.4, 2010) and Meyer, "Of Molecules and (Straw) Men" (PSCF
  63.3, 2011), with [[venema-seeking-a-signature--202609011310]],
  [[meyer-of-molecules-and-straw-men--202609011311]], two literature notes, and
  [[the-information-design-argument-turns-on-where-selection-begins--202609011320]];
  the inquiry's rank-3 "direct captures still lacking" caveat is updated in
  place. Note: biologos.org itself hard-blocks this environment class (HTTP 429
  on every path tried, with backoff), so the irreducible-complexity-specific
  BioLogos web articles (e.g. Venema's flagellum series) were NOT capturable;
  the PSCF exchange — same critic, same opposing institution, peer-edited — is
  the accessible instance of the requested debate. Still open: Plantinga,
  McGrath, Collins (likely paywalled), a Behe-specific irreducible-complexity
  capture (discovery.org is reachable from remote sessions; a Behe essay there
  is a candidate for a future cycle), and revisiting ranks 3-5 on the broader
  base. Entry stays in-progress.
- **2026-09-01 (later cycle) progress:** the easiest candidate is done — Aquinas,
  Summa Theologiae I q.2 a.3 (Fifth Way) captured complete in the public-domain
  1920 Dominican translation from two independent digitizations (Project
  Gutenberg #17611 anchor + New Advent cross-check) to
  raw/202609011201-aquinas-summa-i-q2-existence-of-god.txt, with
  [[aquinas-summa-theologiae-i-q2--202609011201]],
  [[aquinas-makes-god-demonstrable-only-from-effects--202609011206]], and
  [[the-fifth-way-infers-a-director-from-regularity-not-contrivance--202609011211]];
  the inquiry's rank-4 "no primary Aquinas capture yet" caveat is updated in
  place. Still open: Plantinga, McGrath, the BioLogos-vs-Discovery exchange
  (capturable from a remote session), and Collins (likely paywalled); ranks 3-5
  not yet revisited on a broader base, so the entry stays open.

The answer to inquiry 202609010930 ranks the top design arguments in
evangelical natural theology on three captured sources: Paley (primary),
the SEP survey (Ratzsch & Koperski 2023), and Craig 1990 (the one directly
captured evangelical endorsement). A future run should capture a broader
base of named evangelical assessments and revisit ranks 3-5 in
particular: candidates include Plantinga ("Two Dozen (or so) Theistic
Arguments" or Where the Conflict Really Lies), McGrath (A Fine-Tuned
Universe), a BioLogos-versus-Discovery-Institute exchange on irreducible
complexity (both sides publish openly on the web, so this should be
capturable from a remote session), Robin Collins's fine-tuning chapter in
the Blackwell Companion to Natural Theology (likely paywalled), and a
primary Aquinas capture (Summa Theologiae I q.2 a.3, public-domain 1920
Dominican translation, easily capturable) to ground the Fifth Way lineage
now cited only via the SEP.

## 2026-09-01 — User request (2026-09-01, recorded by the knowability ad-hoc cycle): run the connector (serendipity sweep + adjudication) and the skill-smith (one proposal + A/B trial) in this cycle, running both regardless of their configured cadences for this run only. [Correction, same cycle, critic finding: config.yml currently sets connector_cadence=daily and skill_smith_cadence=weekly, not the weekly/monthly this entry first claimed - the values were quoted from a stale read of config.yml before another cycle changed them.] Cadences in config.yml are unchanged by this run. Skill-smith promotion remains human-only (FR-36): any proposal is left for the user to promote or reject via scripts/skill_review.py.

- **status:** answered        <!-- new | in-progress | answered | archived -->
- **answer:** Fulfilled by the cycle that recorded it (branch
  zettel/run-20260901103000, merged as PR #22). log.md for that cycle records
  both: the connector ran the serendipity sweep (10 proposals) and adjudicated
  them (7 accepted with reciprocal typed links written into both notes, 3
  rejected as MOC-membership bookkeeping), and the skill-smith proposed
  source-access-triage (202609011101) with its A/B trial run and honestly
  recorded as a loss (with=0.92, without=0.963, n=3) in skill-impact.md. The
  proposal awaits the human promote/reject decision via
  scripts/skill_review.py (FR-36); nothing further for a maintenance run to
  do here.
- **priority:** normal
- **asked_by:** human

(no further detail)
