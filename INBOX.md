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
- **2026-09-01 ~15:00 cycle progress:** the Plantinga capture is done -- of the
  two works the entry names, "Two Dozen (or so) Theistic Arguments" turned out
  to be openly accessible: the 2007 CUP publication (appendix to Baker, ed.,
  *Alvin Plantinga*, pp. 203-227) is served by the philosopher-maintained
  "Papers by Alvin Plantinga" archive (andrewmbailey.com/ap), a long-standing
  professional resource, not a scraper mirror -- though the archive states no
  explicit hosting permission, a residual recorded in the capture header.
  Captured as bounded excerpts (preface opening, the 1986 headnote, and the two
  teleological sections (E) and (F), complete) to raw/202609011500, every
  paragraph verified against two independent PDF extractors; with
  [[plantinga-two-dozen-theistic-arguments--202609011500]],
  [[plantinga-makes-theistic-arguments-probabilistic-helps-not-proofs--202609011505]],
  and [[design-arguments-can-confirm-belief-they-do-not-ground--202609011510]].
  Inquiry 202609010930 updated in place: rank-1 (fine-tuning) gains a second
  captured named endorsement, rank-5 (beauty/naive) gains a captured
  assessment agreeing with its placement, and the closing caveat now records
  Plantinga's cross-cutting confirmation-not-proof scale. Still open: McGrath
  (*A Fine-Tuned Universe*) and Collins (Blackwell Companion chapter), both
  still likely needing purchased/library access, and the BioLogos web
  critiques (429-blocked from remote sessions). Entry stays in-progress.
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

## 2026-09-01 — Source-access gap (source-access-triage step 4). Alon Goshen-Gottstein, "Shituf: Critical and Constructive Reflections", ch. 9 of Same God, Other god: Judaism, Hinduism, and the Problem of Idolatry (Palgrave Macmillan US, 2016), 93-106. DOI 10.1007/978-1-137-45528-4_9, ISBN 9781137455284. Ladder tried 2026-09-01: (a) link.springer.com chapter page -> 303 to idp.springer.com/authorize, and a cookie-jar retry with a browser user-agent returned only the 3 KB auth shell; (b) Unpaywall by DOI -> is_oa false, no OA location, and both published reviews (10.1086/703369 Journal of Religion, 10.1353/sho.2017.0017 Shofar) are closed as well; (c) the Elijah Interfaith Institute, which the author directs, does not post this chapter and its related 2021 PDF entered a redirect loop (curl error 47); (d) in copyright, so no etext; (e) Wayback egress-blocked in this environment. The publisher-deposited author abstract was recovered from OpenAlex's abstract_inverted_index and captured as raw/202609011533-goshen-gottstein-shituf-abstract.txt. Grounding-limited by this: reference 202609011533, literature 202609011538, and the closing paragraph of permanent 202609011542. What would close it: library or institutional access to the Palgrave volume, or a purchase. Also still open on the same subject and not yet attempted: ch. 8 of the same book (10.1007/978-1-137-45528-4_8, 'Shituf: Applying a Construct of Christianity to Hinduism').

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** maintenance-run (2026-09-01 ad-hoc cycle, inquiry 202609011526)

(no further detail)

## 2026-09-01 — Leads left open by the Kabbalah same-God cycle (inquiry 202609011526), for a later run. (1) The sefirot/Trinity comparison is drawn in permanent note 202609011543 as this repository's own inference and is flagged there as such; the actual historical debate is uncaptured -- the Christian kabbalists (Pico della Mirandola's Conclusiones, Reuchlin's De Arte Cabalistica) argued the sefirot conceal the Trinity, and Jewish polemicists answered. Capturing either side would let the note cite the dispute instead of constructing it; Reuchlin 1517 and Pico 1486 are old enough to be public domain. (2) The kabbalistic doctrine of gentile souls, and the Zohar's harsher passages about the nations, are not represented at all; the Ramban capture gives the tolerant reading (nations acknowledge the Most High) and the base currently has no counterweight from within the same tradition. (3) R. Jacob Emden's positive assessment of Christianity as a legitimate path for gentiles is frequently cited in this debate and was not sought this cycle. (4) Sefer Yetzirah and the main body of the Zohar remain uncaptured; only Tiqqunei ha-Zohar 17a-17b is in the base.

- **status:** in-progress        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** maintenance-run (2026-09-01 ad-hoc cycle, inquiry 202609011526)
- **2026-09-01 ~18:00 cycle progress (lead 1, half done):** the Christian side of
  the sefirot/Trinity dispute is captured. Pico della Mirandola's *Conclusiones
  cabalisticae numero LXXI, secundum opinionem propriam* (from the *Conclusiones
  sive Theses DCCCC*, Rome 1486, public domain) is captured COMPLETE -- not as
  excerpts -- to raw/202609011801-pico-conclusiones-cabalisticae.txt, collated
  thesis by thesis from two independent digitizations: Joseph H. Peterson's
  CC-BY 4.0 edition (esotericarchives.com) as base text and the Brown University
  CDS / University of Bologna Pico Project diplomatic transcription of the 1486
  editio princeps as cross-check witness. With
  [[pico-conclusiones-sive-theses-dccccc--202609011801]],
  [[pico-makes-kabbalah-compel-the-catholic-trinity--202609011806]], and
  [[christian-kabbalism-claimed-kabbalah-compels-the-trinity--202609011811]]. The
  closing caution of [[internal-plurality-is-not-what-divides-the-monotheisms--202609011543]]
  no longer says the dispute is uncaptured; it now points at Pico and marks his
  argument as going far beyond what that note claims.

  **One correction to this entry's own framing.** The entry says the Christian
  kabbalists "argued the sefirot conceal the Trinity". Pico's text does not
  quite do that. His thesis 5 claims that Kabbalah's *principles* compel assent
  to the Catholic Trinity exactly ("cogitur inevitabiliter concedere ... sine
  additione, diminutione, aut variatione"), and where he finally makes the
  mapping concrete, at thesis 6, the triad he assigns to the three persons is
  *sekhel* / *ha-maskil* / *ha-muskal* -- the intellect, the knower, the known --
  which is a philosophical triad and not among the ten sefirot at all. A future
  run should not assume the sefirot=Trinity form without checking which
  Christian kabbalist actually argued it; Reuchlin (*De Arte Cabalistica*, 1517,
  also public domain, uncaptured) is the obvious place to look next, and the
  Latin is served by Emory's Pitts Digital Collections.

  **Still open on lead (1):** Reuchlin 1517, and the whole Jewish-respondent
  side. Both Jewish polemics worth capturing -- Leon Modena's *Ari Nohem*
  (c. 1639) and Isaac of Troki's *Chizzuk Emunah* (c. 1593, Mocatta's 1851
  English translation being public domain) -- were checked against Sefaria's
  name API this cycle and Sefaria holds NEITHER, so the route that supplied
  Ramban and Tiqqunei ha-Zohar does not reach them; they need another
  digitization or a library copy. Until then the dispute is represented in this
  base from the Christian side only, and every note above says so.

  **Leads (2), (3), (4) not attempted this cycle.** One concrete finding for
  whoever takes lead (4): Sefaria *does* serve Sefer Yetzirah (confirmed live
  this cycle: "Sefer Yetzirah" and "Sefer Yetzirah Gra Version" both resolve),
  so that capture is straightforwardly available by the same route the Ramban
  and Tiqqunei ha-Zohar captures used.

- **2026-09-01 ~18:30 cycle progress (lead 4, the Sefer Yetzirah half done):**
  taken up on the previous cycle's finding. Chapter 1 -- the whole of the book's
  treatment of the ten *Sefirot Belimah* -- is captured complete to
  raw/202609011825-sefer-yetzirah-chapter-1.txt from four witnesses: two Hebrew
  digitizations collated verse by verse (Sefaria's Warsaw 1884 text from the NLI
  copy, and Hebrew Wikisource `ספר יצירה א` rev. 2870897, probably a different
  recension) and two independent English renderings (the Sefaria Community
  Translation, CC0, and Isidor Kalisch's published translation of 1877, public
  domain, Internet Archive `1877-kalisch-sepher-yezirah`). With
  [[sefer-yetzirah--202609011825]],
  [[sefer-yetzirah-counts-ten-from-the-spirit-out-to-the-six-directions--202609011830]],
  and [[the-sefirot-vocabulary-does-not-begin-as-articulation-within-god--202609011840]].

  **What it changed, which is not what was expected.** The capture does not
  corroborate this base's sefirot notes; it limits them. *Sefer Yetzirah*
  enumerates its ten as a descent -- God's spirit, then wind, water, fire, then
  the six directions -- under a Lord who "has no second" and who governs them
  "from His Holy Abode", that is, who is not one of them. Nine of the ten are
  elements, formed things, or dimensions of space. So the intra-divine reading
  of the sefirot that
  [[internal-plurality-is-not-what-divides-the-monotheisms--202609011543]] rests
  on is a later development of the vocabulary and cannot borrow the age of the
  word; 202609011543 now carries that limit in its closing paragraph. The
  translator of the version quoted says the same thing independently, refusing
  to gloss this book's ten by the Bahir's and the Zohar's.

  **Still open on lead (4):** the main body of the Zohar, and *Sefer ha-Bahir*,
  which this cycle's permanent note names as the obvious next capture since it
  is the missing link between Sefer Yetzirah's cosmogonic ten and the zoharic
  intra-divine ten. Neither was attempted. Leads (2) and (3) still not attempted.

  **One concrete finding for whoever takes lead (1)** (Reuchlin, *De Arte
  Cabalistica*, 1517): the Emory/Pitts route the last cycle suggested was not
  needed to establish availability -- the Internet Archive serves two Wellcome
  Collection scans of the 1517 Latin edition (identifiers `b13135004_0001` and
  `b13135004_0002`, 188 and 180 pages), each with a `_djvu.txt` OCR layer, and
  the 1983 English translation (`onartofkabbalahd0000reuc`) is there too but in
  copyright. Availability is therefore not the obstacle; OCR quality of 1517
  Latin type is, and a run taking this on should budget for collating the two
  scans against each other before quoting a single line, exactly as the Pico
  capture did with its two digitizations.

## 2026-09-01 — Tooling: `verify_refs.py --offline` silently downgrades verification provenance on notes it did not need to touch

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** maintenance-run (2026-09-01 ~18:00 cycle, critic finding)

A cycle that runs `verify_refs.py --repo . --offline` rewrites the
`verification:` block of EVERY reference note, not just the ones whose state
changed. Where a previous live run had recorded
`method: raw-capture+openlibrary`, the Open Library or Crossref URL in
`source:`, and `identifier_check: confirmed`, the offline pass replaces all
three with a bare `method: raw-capture` whose `source:` is the local capture
path, and stamps a fresh `date:`. The identifier check is not re-run and not
found wanting — its record is simply overwritten with the weaker fact that a
raw capture exists.

Hit this cycle on 8 notes (ahrens 202608301000, bogardus-urban 202609010833,
goshen-gottstein 202609011533, housel 202608311036, luhmann 202609010111,
plantinga 202609011500, tachin 202608311925, vroom 202608311926), all restored
from the pre-cycle commit before the branch was finished; nothing reached main
in the downgraded state. It is invisible to the gates, because a bare
raw-capture verification passes lint_citations perfectly well — which is what
makes it worth fixing rather than remembering.

Two things a future run should weigh. (1) The obvious workaround is to pass
`--mailto` and let the run verify live, but that trades a provenance
regression for a network dependency and puts a contact address into every
scheduled cycle; it does not fix the underlying behaviour. (2) The behaviour
looks wrong rather than merely inconvenient: an offline pass should either
leave an existing stronger verification record alone, or downgrade it
explicitly (e.g. keeping the prior method and marking it `stale`), so that
"verified offline today" stays distinguishable from "never checked against an
authority". Note that CI runs the same command with `--offline --no-render` on
a throwaway checkout, so CI never commits the downgrade — only a session does.
This is a `zettel-bootstrap` skill-repo issue, not a content-repo one, so it
needs a change in the skill repo (`scripts/verify_refs.py`) and is out of
scope for a content-repo maintenance cycle to fix itself.

## 2026-09-02 — Tooling: `verify_refs.py` erases live provenance on a network failure, and reads a report's series number as an arXiv id

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** agent

Two defects, both hit during the 2026-09-02 Hoyle-state cycle, both recorded
rather than worked around.

**(A) Recurrence of the 2026-09-01T18:10:09Z entry above, and worse than it
was filed there: the downgrade is not specific to `--offline`.** A *live* run
on this container replaced `method: raw-capture+openlibrary` /
`identifier_check: confirmed` with a bare `method: raw-capture` on housel
202608311036 and plantinga 202609011500. The cause is visible in the
environment rather than the notes: openlibrary.org is unreachable here, and
the agent proxy logged `ws_closed_mid_exchange ... tunnel closed (code 1006)`
against `openlibrary.org:443` at the same second as the run.
`verify_note()` builds a fresh verification dict and replaces the old one
wholesale, so a transport-level failure — which should raise
`NetworkUnavailable` and degrade, the behaviour `_raw()` documents for itself
at lines 137-141 — instead erases a confirmation an earlier live run had
established. Both notes were restored from HEAD; nothing downgraded reached the
branch. Suggested fix: distinguish a connection/TLS failure from a
200-with-no-match, and never let a *failed* lookup remove an
`identifier_check` that a previous run recorded.

**(B) New: `citations.arxiv_id()` reads the CSL `number` field as an arXiv
identifier unconditionally.** On the new reference polkinghorne 202609022347 —
a Faraday Paper whose `number` is its series number, `'1'` — this made
`verify_refs` query `https://export.arxiv.org/api/query?id_list=1`, find
nothing, and stamp a false `identifier_check: failed` on a record that carries
no DOI, ISBN, PMID or arXiv id at all. The false line was removed by hand and
the bibliographically correct `number` kept, which is the right way round: the
record is accurate and the tool is wrong. CI's offline check does not re-add
it, but the next live run will. Suggested fix: read `number` as an arXiv id
only when the item looks like a preprint (container-title, publisher or URL
naming arXiv), never for `type: report`.

Both are `zettel-bootstrap` skill-repo issues and out of scope for a
content-repo cycle to fix itself.

## 2026-09-02 — Lead: capture Kragh on the history of the carbon-12 resonance's anthropic reading

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** low
- **asked_by:** agent

Kragh, "An anthropic myth: Fred Hoyle's carbon-12 resonance level", *Archive
for History of Exact Sciences* 64 (2010): 721. Epelbaum et al. cite it as "a
thorough discussion of the history of this issue" but do not summarise its
thesis, so the base holds a **pointer only** — no note may attribute a claim
to Kragh on that basis, and none currently does.

Worth capturing directly. The title suggests it argues the anthropic reading
of Hoyle's 1953 prediction was retrofitted rather than contemporaneous. If that
holds it bears on permanent note 202609022355, and more sharply on the whole
Hoyle-state cluster: an anthropic reading applied after the fact is what a
confirmer looks like from the outside, which would corroborate the cluster's
claim from the history rather than from the physics. The Springer page is
paywalled; look for an author preprint or an accessible reprint before
budgeting a capture.

## 2026-09-03 — Source-access gaps left open by the Christian-kabbalism cycle (inquiries 202609030145 and 202609030146)

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** agent

Three routes, in the order they would most improve the base.

**(1) Leon Modena, *Ari Nohem* (Venice, 1639), the primary text.** The base
holds Modena's conclusion only as Dweck reports it (reference 202609030150,
literature 202609030152, permanent 202609030155), which is a strict limit
recorded in all three: nothing captured establishes HOW Modena argued from the
sefirot to the Trinity parallel, which sefirotic doctrine he examined, or
whether he answered Pico by name. Dweck's introduction names Pico as the
setting and does not say so. Not attempted this cycle: the Hebrew text on
HebrewBooks or Sefaria, and Dweck's own critical edition. The 1840 Leipzig
printing (ed. Fürst) would be out of copyright if it can be found; a Hebrew
capture would need a translation policy this repository has not yet set, so
consider that question part of the task.

**(2) A kabbalist's reply, as opposed to an anti-kabbalist's concession.**
Modena is a hostile witness to the doctrine he describes. What is still
uncaptured is anyone DEFENDING the sefirot against the Christian reading —
denying the resemblance, or distinguishing it. This is the remaining half of
the one-sidedness that note 202609011811 recorded, now narrowed rather than
closed, and it is the single most valuable capture on this subject.

**(3) Lead, ungrounded, do not cite until captured:** Abraham Abulafia is
reported to have attacked the sefirot in the thirteenth century as no better
than the Trinity — which, if it holds, puts a kabbalist on the record about the
parallel some four centuries before Modena, and from inside the tradition. This
surfaced only from a non-citable web source during the 202609030146 search and
is recorded here as a lead, not a finding. The route to grounding it is Moshe
Idel's Abulafia scholarship; check for open-access versions before budgeting.

**Why inquiry 202609030146 stays in-progress rather than answered.** A merits
comparison of the Trinity and the sefirot needs comparative scholarship the
cycle could not reach: Scholem, Idel and Wolfson are all in copyright, and an
open-access search returned only blogs, forums and encyclopaedia summaries —
`general-web` tier, below what this claim needs, and `lint_citations` would
require three distinct verified sources for a note tagged `contested` in any
case. Specifically wanted: a source addressing whether the sefirot are God's
essence (*atzmut*) or His instruments (*kelim*), since note 202609011543 says
the instrumentalist reading narrows the contrast with Maimonides sharply and no
captured source addresses it.

