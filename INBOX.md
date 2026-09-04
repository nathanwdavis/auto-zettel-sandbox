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
- **2026-09-03 progress (partial, and only on the wider complaint):** the Ahrens
  access problem itself is UNCHANGED and this entry stays open — chs. 6 and 9-11
  are still unreachable. What did change is the gap that made it urgent: this
  entry's real complaint was that `zettelkasten method` rested almost entirely
  on an 11-page publisher preview. The base now also holds peer-reviewed
  historical scholarship on note-taking as a practice, independent of the
  Luhmann line, in
  [[blair-note-taking-as-an-art-of-transmission--202609032100]] and its two
  permanent notes. That does not substitute for Ahrens: Blair is a historian of
  early modern information management and says nothing about the
  fleeting/literature/permanent taxonomy, which is precisely what the missing
  Ahrens chapters cover. The topic is less thinly grounded; the specific hole
  this entry names is still a hole.

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

### Appended 2026-09-04 11:40Z: still present at skill rev d986b16, and the blast radius has grown with the base

Re-observed by the 11:00Z cycle, unchanged in behaviour and larger in extent:
`verify_refs.py --repo <copy> --offline --no-render` rewrote **18** reference
files, up from the 8 recorded above, in exactly the same way — `method:
raw-capture+openlibrary` downgraded to `raw-capture`, `source:` swapped from the
registry URL to the local capture path, `identifier_check: confirmed` dropped,
`date:` restamped with today's. The count grows with the number of
live-verified references in the base, so this gets worse rather than staler.

Nothing was restored this cycle because nothing needed restoring: the CI
sequence was run against a COPY of the tree rather than the live one, which is
now the standing practice precisely because of this entry. That is a workaround
and not a fix, and it is one an unwary cycle will forget — the failure is
silent, the gates pass either way, and the loss only shows up as a diff nobody
looks at. Worth saying plainly for whoever fixes it: **the safe behaviour is for
an offline pass to leave a stronger existing record alone.** Restamping the date
while weakening the method is the worst of the options, because it makes the
downgraded record look fresher than the strong one it replaced.

**2026-09-04 12:00Z: still present, still 18 files, at skill rev d986b16.** The
CI sequence was again run against a COPY and defect (A) recurred identically —
18 reference files rewritten, the same downgrade in each. The count did not grow
this cycle because this cycle added no live-verified registry lookups, which is
the only reason it held at 18. The workaround held; the defect is untouched.

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

**2026-09-03 maintenance sweep — defect (B) reproduced live and cleanly
isolated; defect (A) did NOT fire.** The freshness sweep ran
`verify_refs.py --repo . --no-render` live (no `--offline`, no `--mailto`).
Before letting it write, every identifier lookup was run read-only through
`verify_refs._identifier_lookup` itself, so the registries' actual answers
were known first. Outcome: the write pass changed exactly ONE file in the
whole `reference/` tree — polkinghorne 202609022347, where `number: '1'` was
again read as an arXiv id, queried, missed, and stamped
`identifier_check: failed` with a fresh date. Restored to the pre-run
verification block by hand, as last time. Every other note was untouched,
which pins the two defects apart: (A) is contingent on a network failure and
did not occur today because Crossref and Open Library were both up (all ten
identifier-bearing notes with live registry provenance kept
`raw-capture+crossref` / `raw-capture+openlibrary` and `confirmed`), whereas
(B) is unconditional and fires on any healthy network. So (B) is the one that
will corrupt a record on a *good* day, and it is now three cycles of the same
single-note damage. Note also that the run's `--no-render` was deliberate:
without it `verify_refs` rewrites `chicago_note`/`chicago_bib` on every
reference note, which a maintenance pass has no business doing.

**2026-09-03 (later cycle, the Blair capture) — BOTH defects fired in one
cycle, which is the first time they have been seen together, and (A) is now
confirmed to damage a brand-new note and not only pre-existing ones.** Two
`verify_refs` passes ran, and the pair separates the defects by cause exactly
as the entry above predicts:

1. LIVE pass (`--mailto`, network up), run to render the new reference note's
   Chicago strings and check its DOI. It did the right thing for the new note —
   Blair 202609032100 came back `raw-capture+crossref` with
   `identifier_check: confirmed` — and it changed exactly one other file:
   polkinghorne 202609022347, defect (B), SIXTH occurrence, same false
   `identifier_check: failed` from the same Faraday series `number: '1'`.
   Reverted by hand again.
2. OFFLINE pass (`--offline --no-render`, the exact invocation CI runs). This
   fired defect (A) across TEN reference notes at once, stripping
   `+crossref`/`+openlibrary` and `identifier_check: confirmed` down to bare
   `raw-capture` — and among the ten was the Blair note written minutes
   earlier, which lost the live Crossref confirmation it had just legitimately
   earned. All ten were restored (nine tracked ones from HEAD, Blair's by
   rewriting the block the live pass had produced), so nothing downgraded
   reaches the branch and a diff of `reference/` against origin/main shows no
   changed method or `identifier_check` line.

Two things this adds for whoever fixes it in the skill repo. First, (A) is
NOT limited to notes an offline run "did not need to touch" — it also
downgrades a note whose live provenance was written seconds before, in the
same working tree, so the fix cannot rely on file age or tracked-ness.
Second, a practical guard for content cycles until it is fixed: a reference
note whose CSL carries a genuine `DOI` is safe to render live, but any
`number` field will be read as an arXiv id, so this cycle deliberately gave
the Blair record `volume`/`issue`/`page` and no `number` — and it was not hit
by (B). That is a workaround, not a fix; a bibliographically correct record
that needs `number` (a report or numbered series, as Polkinghorne's is) still
cannot avoid it.

**Third observation, 2026-09-04 cycle: defect (B) fired again, and this time
the trigger is identified.** The live pass downgraded five reference notes
from `raw-capture+openlibrary` / `identifier_check: confirmed` to bare
`raw-capture` (ahrens 202608301000, housel 202608311036, luhmann 202609010111,
plantinga 202609011500, dweck 202609030150), and gave polkinghorne 202609022347
a new `identifier_check: failed` it did not have. The common factor is the
registry, not the notes: every one of the five is an Open Library ISBN lookup,
and every Crossref-verified note in the same pass kept its provenance
(tachin, vroom both still `raw-capture+crossref`).

The trigger was confirmed rather than assumed. `curl` to
`https://openlibrary.org/isbn/<isbn>.json` returned **HTTP 000 — a transport
failure, not a 404 —** for all five ISBNs, so Open Library is simply
unreachable from this environment class right now. That matters twice over:
it distinguishes this from identifier rot (the 2026-09-03 freshness sweep
found Open Library reachable and all identifiers live, so nothing has
actually rotted), and it shows the defect is a *reachability* failure being
recorded as a verification downgrade. A registry being down should leave
provenance untouched, not erase what a previous live lookup established.

All six notes were restored from HEAD, twice — the cycle ran verify_refs live
a second time to render a Chicago string, which re-inflicted the identical
damage, so the restore has to be the last step before committing rather than
a one-off. `reference/` shows no changed method or `identifier_check` line
against origin/main. Note for the fix: (A) and (B) now both have a
reproduction that does not depend on file age, and (B)'s reproduction is
cheap — take any Open-Library-verified note and run the live pass while the
registry is unreachable.

**Fourth observation, 2026-09-04T03:06Z cycle (retrieval practice): the two
defects separated cleanly again, and the separation is now diagnostic.** A live
pass (`--mailto`, no `--offline`, no `--no-render`) verified 51/51 references
and changed exactly ONE file in the whole `reference/` tree: polkinghorne
202609022347, stamped `identifier_check: failed` from the Faraday series
`number: '1'` for the SEVENTH time. Restored from HEAD; `reference/` shows no
changed method or `identifier_check` line against origin/main.

What did NOT happen is the useful part. **None of the five Open-Library notes
was downgraded this cycle**, because Open Library is reachable again —
`https://openlibrary.org/isbn/<isbn>.json` returns 302 and
`openlibrary.org/search.json` returns 200 from this container, against the HTTP
000 transport failure the previous two cycles recorded. So the outage that ran
2026-09-03 to 2026-09-04 has ended, the restore-from-HEAD step it forced is not
needed today, and the diagnosis in the third observation above is confirmed by
its own negative case: the downgrade tracks registry reachability and nothing
else.

**One labelling correction for whoever fixes this, offered because it will cost
them time otherwise.** The third observation above calls the Open Library
downgrade "defect (B)". By this entry's own definitions at the top it is defect
**(A)** — provenance erased on a network failure. (B) is the `number`-as-arXiv-id
bug, and (B) is what fired today, alone. The two failure modes are genuinely
separate and the fixes are separate: (A) needs `verify_note()` to distinguish a
transport failure from a lookup miss and never erase a prior confirmation on the
former; (B) needs `citations.arxiv_id()` to stop reading `number` as an arXiv id
for `type: report`. Nothing in the observations is wrong; only the label is.

Also recorded for the fix: three new reference notes landed this cycle
(202609040305, 202609040315, 202609040325), all three carrying a real DOI and no
`number` field, and all three were rendered live without incident —
`raw-capture+crossref` with `identifier_check: confirmed`. The workaround
described in the second observation continues to hold.

**2026-09-04T05:40Z — defect (A) is broader than "a network failure", and the
diagnosis in this entry should be restated.** This cycle ran the LIVE pass and
then, separately, the `--offline --no-render` pass that CI runs, on a container
with full network. The offline pass — with nothing failing, nothing timing out
and no registry down — rewrote SIXTEEN reference notes it had no reason to
touch, turning `raw-capture+crossref` and `raw-capture+openlibrary` into bare
`raw-capture` and deleting `identifier_check: confirmed`. So the trigger is not
a transport failure at all; a failure is merely one way to reach it. **The
defect is that `verify_refs.py` writes provenance describing what THIS pass
could see, over provenance describing what an EARLIER pass actually did.** The
fix stated for (A) above is still the right one and now has a wider scope: a
pass must merge into recorded provenance rather than replace it, and an
`--offline` pass in particular must never delete a registry confirmation it was
told not to attempt. Practical consequence for every run until this is fixed:
the restore-from-HEAD step belongs after the LAST verify_refs invocation of the
cycle, including the offline one, and a cycle that runs the offline pass to
rehearse CI must restore afterwards or it will commit sixteen silent
downgrades. (Defect (B) also recurred, its eighth occurrence, on polkinghorne
202609022347. Restored from HEAD as usual.)

**2026-09-04T06:15Z — defect (B) recurred TWICE in one cycle, its ninth and
tenth occurrences, and that is the useful new datum.** This cycle ran
verify_refs live twice — once after writing the new notes and once as the final
gate — and BOTH passes re-added `identifier_check: failed` to polkinghorne
202609022347, each time requiring a restore from HEAD. So the defect is not
merely per-cycle but per-invocation: the restore step has to follow every
verify_refs call, not just the last one, or an intervening `build_manifest` will
index the damaged file. Defect (A) did NOT recur this cycle: no other reference
note was touched by either live pass, Open Library and Crossref were both
reachable throughout, and the offline pass was not run. The count of reference
notes is now 53 and the two that sit at bare `raw-capture` beside an identifier
are unchanged — 202609022347 (this defect) and 202609010302 (Schmidt, a DataCite
DOI that Crossref legitimately does not carry).

**2026-09-04 07:00Z cycle — defect (B), ELEVENTH occurrence; defect (A) did not
fire, and the reason it did not is worth recording.** One live pass ran
(`--mailto`, no offline pass needed since the new note has no identifier to
check). It touched exactly one file it had no business touching: polkinghorne
202609022347, same false `identifier_check: failed` from the same Faraday series
`number: '1'`, restored from HEAD before `build_manifest` ran. Defect (A) did
not fire on any of the other 53 notes. What separates this cycle from the ones
where (A) did fire is the cycle's own network luck rather than anything it did —
Crossref and Open Library were both reachable throughout, and the entry above
already establishes that (A) is a function of what the current pass could see.
So this is a NEGATIVE data point for the diagnosis, not evidence that (A) is
fixed: nothing changed in the tool between 06:00Z and 07:00Z.

One new thing this cycle CAN add, from the other side. The new reference note
(al-Tabari 202609040700) carries a `URL` and no DOI, ISBN, PMID or `number`, and
it came through the live pass with correct `raw-capture` provenance and no
spurious `identifier_check` at all. Combined with the `number`-avoidance
workaround recorded above, that makes the safe-shape rule concrete: a CSL record
with `DOI` alone, or with no identifier at all, survives a live pass intact; a
record carrying `number` gets a false arXiv check. Whoever fixes this in the
skill repo should be able to reproduce (B) from a two-line CSL block with
nothing but `type: report` and `number: '1'`.


### Appended 2026-09-04 08:00Z: defect (B), twelfth occurrence

`verify_refs.py --mailto` on a clean tree again stamped `identifier_check:
failed` on polkinghorne 202609022347, reading its report series `number` as an
arXiv id, and rewrote its verification date. Restored from HEAD before any
`build_manifest` ran, per the per-invocation rule the 06:00Z cycle established;
the committed tree carries no downgrade. Nothing new about the mechanism this
time — it is recorded only so the occurrence count stays honest. Defect (A) did
not fire: Crossref and Open Library were reachable throughout, and 59/59
references verified on the live pass. The five new reference notes carry a URL
and no DOI/ISBN/PMID/arXiv id, the same safe shape as the 07:00Z cycle's, and
came through untouched.

**Occurrence 13, 2026-09-04 13:00Z cycle — defect (A), and the count is now
stable enough to be diagnostic.** The full CI sequence was simulated on a COPY of
the exact tree to be pushed and passed all six steps (offline 67/67, manifest
`--check` up to date, four lints clean, sandbox clean against the merge-base).
`verify_refs.py --offline --no-render` again rewrote **18 reference files** it
had no business touching — the identical count the 12:00Z cycle recorded, from a
tree that has since gained two references. That is the useful new datum: the
footprint did NOT grow with the base. Both new reference notes (202609041300,
202609041305) carry a URL and no DOI/ISBN/PMID/arXiv id, and both came through
untouched, which is now the fourth consecutive cycle in which URL-only notes are
the ones spared. The footprint tracks notes carrying a registry identifier, not
notes generally — so the defect is in the offline path's handling of the
identifier-check state, and a fix can be scoped to that. Defect (B) did not fire
this cycle: the live pass raised only the two known documented identifier
warnings (polkinghorne 202609022347, schmidt 202609010302) and rewrote nothing
that had to be restored.

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

### Appended 2026-09-04 17:00Z: the *atzmut*/*kelim* want is CLOSED, from a
### primary text rather than the scholarship this entry was looking for

The paragraph immediately above named one thing "specifically wanted": a source
on whether the sefirot are God's essence or His instruments. It is captured.
Moses Cordovero's *Pardes Rimmonim* devotes its **entire fourth gate** to that
question — *Sha'ar Etzem ve-Kelim* — quoting Menachem Recanati and R. Yehudah
Hayyat for the instruments and R. David (*Magen David*) for the essence at
length before answering. Reference 202609041700, capture
`raw/202609041700-cordovero-pardes-rimmonim-shaar-4-etzem-ve-kelim-hebrew.txt`,
all ten chapters, Hebrew, **Public Domain** by Sefaria's own licence field.
Inquiry 202609030146 is now `answered` on the strength of it plus a second
Hodge capture; the residual (no comparative scholarship) is its own entry
below, so this route is closed and should not be re-searched.

**What this entry still wants, unchanged.** Route (1), *Ari Nohem* itself, and
route (3), the Abulafia lead, were not attempted this cycle. Route (2) — a
kabbalist DEFENDING the sefirot against the Christian reading — is *narrowed*
but not met: Cordovero defends them against the charge of introducing
multiplicity into God, which is the same charge in a different mouth, but he is
answering fellow kabbalists and not Christians, and no text in this base yet has
a Jewish writer answering the Christian-kabbalist argument on the merits. Leave
this entry open for (1), (2) and (3).

## 2026-09-03 — Verified reachable, not yet captured: Ann Blair, Note Taking as an Art of Transmission (Critical Inquiry 31.1, 2004) is open access AND text-extractable from this environment class

- **status:** answered        <!-- new | in-progress | answered | archived -->
- **answer:** Captured and worked, 2026-09-03T21:00Z cycle. The DSpace REST
  bitstream URL recorded below still returns the article (HTTP 200, 1,641,288
  bytes, matching the 1.6 MB reported here), and BOTH anchors left for identity
  confirmation were found in the fetched document. One caveat worth keeping for
  future anchor checks: anchor (1) does not match a naive substring search,
  because the text layer breaks the line inside the word as "trans-\nmission" —
  the sentence is printed continuously and the hyphen is an extraction
  artifact. Anchor (2) matched verbatim. Written:
  reference [[blair-note-taking-as-an-art-of-transmission--202609032100]]
  (peer-reviewed, verified raw-capture+crossref on the live DOI),
  literature [[blair-on-note-taking-as-transmission-and-delegated-memory--202609032105]],
  and two permanent notes,
  [[systematic-method-is-what-makes-a-note-usable-by-someone-who-did-not-take-it--202609032110]]
  and
  [[the-note-became-an-external-memory-only-when-memorizing-came-to-be-seen-as-a-cost--202609032115]].
  Capture is bounded excerpts at
  raw/202609032100-blair-note-taking-art-of-transmission-excerpts.txt.
  On the standing caution in this entry — check attributability before wiring
  Blair to the three uncited genesis notes — the answer was mostly negative and
  the wiring was NOT done: Blair says nothing about one-idea-per-note
  atomicity, nothing about note titles, and nothing about a compounding effect,
  so 202701010003 and 202701010001 got no link at all. Only
  202701010002 was linked, `shared-concept`, and it gained a paragraph saying
  in the note itself that Blair corroborates its reuse half and not its
  atomicity half. The unplanned find was elsewhere: Blair independently defines
  commonplacing as filing "to facilitate retrieval" (p. 87), which gives
  [[topic-head-filing-optimizes-retrieval-not-connection--202609010604]] a
  second, independent witness for a generalization that note had flagged as
  resting on the single Locke case.
- **priority:** normal
- **asked_by:** human

The 2026-09-03 topic-gap cycle set out to broaden the `zettelkasten method`
base, which rests on Ahrens (an 11-page publisher preview only), Luhmann
"Kommunikation mit Zettelkaesten", and Schmidt. It did the source triage and
found a strong candidate, but could NOT capture it: the session had no
file-writing tool, no subagent dispatch, and Bash limited to read-only
commands (new_worktree.sh was denied), so no worktree, no raw capture, and no
notes were possible. This is an environment/permissions limit, NOT a
source-access failure - the ladder in skills/source-access-triage does not
apply and must not be started over.

POSITIVE FINDING, verified live this cycle. Blair, Ann. 2004. "Note Taking as
an Art of Transmission." Critical Inquiry 31, no. 1: 85-107.
DOI 10.1086/427303. Deposited by Harvard in DASH, handle 1/3226475,
urn-3:HUL.InstRepos:3226475, terms of use "Other Posted Material (LAA)" - an
institutional repository copy of the published version, so a legitimate OA
location, not a scraper mirror.

The URL that actually returned the article is the DSpace REST bitstream
endpoint:
https://dash.harvard.edu/server/api/core/bitstreams/7312037c-5f82-6bd4-e053-0100007fdf3b/content
It returns a 1.6 MB PDF with a REAL TEXT LAYER (not a scan), so a capture
needs no OCR and no two-witness collation. Two verbatim anchors from p. 85,
read this cycle, so the next run can confirm it fetched the same document:
"Note taking constitutes a central but often hidden phase in the transmission
of knowledge." and the four Ss, "storing, sorting, summarizing, and
selecting."

Do NOT bother with these routes: dash.harvard.edu/search?q=... returns HTTP
405 through the agent proxy, and the uchicago.edu published version is
paywalled. The PDF fetched this cycle landed in a tool-results scratch path
outside the repository; it is NOT a capture and must be re-fetched and written
into raw/ properly before any reference note exists.

WHY IT IS WORTH THE BUDGET. Blair is peer-reviewed historical scholarship on
note-taking as a practice, which the base currently has none of; the
zettelkasten cluster is grounded on one how-to preview plus Luhmann and his
archivist. Her four-Ss frame and her transmission-cycle claim bear directly on
the three genesis notes that still carry NO citation at all -
[[atomic-notes-compound-over-time--202701010001]],
[[one-idea-per-note-enables-reuse--202701010002]] and
[[titles-stated-as-claims-force-clarity--202701010003]] - and she is
independent of Ahrens, so she can corroborate or limit them rather than just
restate them. Note the standing caution from the Ahrens follow-up entry: check
whether the claims are actually attributable before wiring them up.

NEGATIVE FINDING, recorded so it is not retried blind. The Niklas Luhmann
Archive (niklas-luhmann-archiv.de) is JS-only: a direct Zettel URL returned
only the site header with no transcription. Same class as the Springer bot
challenge. It needs a documented API or a real browser, neither available
here, so it should not be budgeted as an easy capture despite being an
official archive.

ON THE OTHER CONFIG TOPIC. `compound growth` was assessed and deliberately
left alone: it already rests on five captured sources (Price, Franklin,
Malthus, Darwin, Housel), which is broader than the zettelkasten cluster. Its
real weakness is not a missing source but that its three genesis fixture notes
(202701010011/12/13) carry no citations - a synthesis job, not a research job.

## 2026-09-03 — Freshness sweep 2026-09-03: no reference rot found (43/43 verified, 34/34 URLs live), and Crossref/Open Library/OpenAlex ARE reachable from this environment class today

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Recorded by the 2026-09-03 maintenance sweep (step 4), so a later run does not
have to redo the measurement or plan around a stale environment fact.

**What was re-checked.** All 43 reference notes. None had a
`verification.date` older than 180 days -- the whole base was verified between
2026-08-31 and 2026-09-03, so the age rung matched nothing. Twelve reference
notes carry an identifier in `csl_json`; each was re-checked live against the
registry `verify_refs.py` itself would use, and separately all 34 reference
notes carrying a `csl_json.URL` had that URL re-fetched.

**Result: nothing rotted.** Ten of the twelve identifiers re-confirmed live
(Crossref: bogardus-urban, epelbaum, goshen-gottstein, tachin, vroom; Open
Library: ahrens, dweck, housel, luhmann, plantinga). All 34 URLs returned HTTP
200, including the ones previously reported as partially blocked -- note that
place.asburyseminary.edu's LANDING page loads while its PDF stays
Cloudflare-blocked, so a 200 here does not mean Bogardus & Urban became
readable. The two non-confirmations are both already-understood and neither is
rot: schmidt 202609010302's DOI is registered with DataCite, not Crossref (the
note body says so; the DOI was re-confirmed live this cycle via doi.org, which
resolved 200 to the article, and via api.datacite.org), and polkinghorne
202609022347 carries no identifier at all -- see the defect below.

**Environment finding, which contradicts the 2026-09-02 entry and is the most
useful thing here.** That entry recorded `ws_closed_mid_exchange ... tunnel
closed (code 1006)` against `openlibrary.org:443` and concluded the network
was down for identifier lookups. Today, from this container,
`api.crossref.org`, `openlibrary.org`, `api.datacite.org`, `doi.org` and
`api.openalex.org` all answer normally, and Crossref answers without a
`mailto` (public pool) so a run need not put a contact address on the wire.
Reachability here is evidently intermittent rather than blocked, so a research
cycle should TEST before assuming, in either direction. (`api.openalex.org`
does rate-limit: a fifth query in quick succession returned HTTP 429.)

**Source-access re-checks (source-access-triage step 5), all negative, all
left open.** Re-queried OpenAlex for OA status on the standing blocked DOIs:
Hick 10.1007/978-1-349-12695-8_9 closed; Vroom 10.1017/s0034412500020217
closed; Goshen-Gottstein ch. 9 10.1007/978-1-137-45528-4_9 closed, and ch. 8
10.1007/978-1-137-45528-4_8 (named as not-yet-attempted in the 2026-09-01
entry) is closed too, so that lead needs library access rather than a fetch;
Bogardus & Urban 10.5840/faithphil201741178 is still `bronze` with the only OA
pdf_url being exactly the Cloudflare-blocked asburyseminary path, and the
PhilPapers/PhilArchive records (TOMHTT) are still marked non-OA. Nothing
changed; no ladder was re-litigated beyond this one rung. Kragh 2010 was NOT
re-checked -- the OpenAlex title query hit the 429 above, and no DOI for it is
recorded anywhere in the base, so whoever takes that lead should start by
resolving its DOI.

## 2026-09-03 — Tooling, HIGH: maintenance_run.sh reports success on a cycle that committed nothing

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

The 2026-09-03 scheduled cycle finished with exit 0 and logged 'gates passed independently' followed by 'pushed 860e02b' -- 860e02b being the commit it STARTED from. The push was a no-op and the gate pass was vacuous, over an unchanged tree. Read alone, those two log lines are indistinguishable from a cycle that actually landed work, and on an unattended cron run nobody would look further.

Cause: the headless session had acting shell commands denied. The wrapper passes an ALLOWED_TOOLS allowlist naming Bash(git add:*), Bash(git commit:*) and the resolved python path, but the session's permission mode overrode it, so git, new_worktree.sh, serendipity_sweep.py and build_manifest.py all returned a 'don't ask mode' denial while read-only commands worked. The run could research and lint but could not create a worktree, write a capture, or commit; it left its INBOX and log edits uncommitted for a wrapper that does not commit either. The parent session committed them, so nothing was lost this time. It also burned 4.61 USD of the 5.00 USD budget on triage it could not act on.

Two suggested fixes, both in the skill repo. (1) Make the wrapper detect a no-op cycle and say so: compare HEAD against PRE_HEAD, which it already captures, and if they are equal log something like 'maintenance_run: NO-OP, headless run produced no commits' at minimum, and ideally exit non-zero so a cron wrapper or CI notices. The existing 'no changes this cycle' path in remote_cycle.sh finish is the right precedent. (2) Have the wrapper fail loudly when its allowlist did not take effect: a cheap probe (attempt one allowlisted write, e.g. touch a scratch file under the repo, before dispatching the model) would turn a silent 10-minute no-op into an immediate, accurate abort. Related: the wrapper should probably also refuse to push when PRE_HEAD == HEAD and the working tree is dirty, which is exactly the state this run ended in.

## 2026-09-03 — Librarian job: permanent notes in the 2026-09-01 clusters cite reference notes directly and skip the literature layer

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Surfaced by the 2026-09-03 connector sweep, and the reason all ten of its
proposals were rejected rather than accepted.

The sweep produced 10 candidates. Six paired a MOC (compound-growth
202608311143, abrahamic-conceptions-of-god 202608311945) with a note the MOC
ALREADY lists — an artifact of graph shape, since a MOC is a term-dense hub
and the community detector splits hub from spokes, so "different communities"
carries no information there. A seventh, atomic-notes-compound-over-time ->
the compound-growth MOC, duplicates a connection the base already makes better
through a dedicated bridge note (202608311038) and the zettelkasten MOC's
"See also".

The remaining three are the real finding, and they are one systematic gap
rather than three discoveries:

  craig 202609011012      -> the-design-arguments-center-of-gravity 202609011015
  paley 202609011010      -> the-design-argument-concludes-to-a-maker 202609011016
  maimonides 202608311932 -> internal-plurality-is-not-what-divides 202609011543

In each pair the permanent note cites the REFERENCE note for that source
directly and never links the LITERATURE note that summarises it. So the
literature note sits in its own graph community and then scores as
"unexpectedly" related to a permanent note about the very same source. The
scorer is working; what it found is a layering inconsistency.

The newer convention links both layers — 202609030155 does, and the notes
written this cycle (202609032110, 202609032115) do. The 2026-09-01 design and
same-God clusters predate it.

WHY IT WAS NOT FIXED HERE. Writing three `source` links for whichever pairs
the scorer happened to surface would migrate the convention across three
arbitrary notes out of a cluster of roughly a dozen, leaving the base less
consistent than it is now, not more. This is a librarian pass: enumerate every
permanent note that cites a reference note whose literature note it does not
link, and decide the convention once for the whole set. Worth settling
explicitly first — whether a permanent note should link the literature layer
at all, or whether citing the reference note directly is correct and the newer
notes are the ones out of step. Nothing in the skill's note-types reference
mandates either, and lint_links does not check it.

Until it is settled, expect this sweep to keep re-proposing these same pairs;
they are not rejections that will stick on their own.

## 2026-09-03 — Graph walk 2026-09-03: six permanent notes carry no source at all, and two of them are among the base's most-linked hubs

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the gap-filling graph walk. This is a synthesis and wiring job, not a
research job — the sources needed are, in at least one case, already in the
base and simply not linked.

THE MAP, for whoever picks this up. 135 notes: 44 permanent, 44 literature, 44
reference, 3 MOCs. Every permanent note is listed in at least one MOC (zero
orphans), so the layering is clean. Clusters by MOC: Abrahamic conceptions of
God 26 permanent notes, zettelkasten method 11, compound growth 8, with
[[atomic-notes-and-compound-interest-share-a-reinvestment-loop--202608311038]]
deliberately shared between the last two as the bridge.

THE FINDING. Six permanent notes have no `source` link of any kind. All six
are the original genesis fixtures:

  202701010001  Atomic notes compound over time
  202701010002  One idea per note enables reuse
  202701010003  Titles stated as claims force clarity
  202701010011  Reinvested returns compound
  202701010012  Linear growth lacks a feedback loop
  202701010013  Time horizon dominates rate

That six notes are uncited was already known in pieces. What the walk adds is
that they are not leaves — they are load-bearing. In-degree across the whole
base puts `reinvested-returns-compound--202701010011` SECOND (8 inbound) and
`time-horizon-dominates-rate--202701010013` joint-fourth (7 inbound). So the
compound-growth cluster's two most-linked-to claims are both things nobody has
sourced. Notes that ARE grounded lean on them, which means the citation graph
looks healthier than the evidence graph is.

THE CHEAPEST PIECE, and it is embarrassing. `time-horizon-dominates-rate`
scored 0.802 on the query "why does time horizon dominate rate in compounding,
and what is the evidence?" — the top hit in the base. The second hit was
[[housel-on-compounding-as-time-in-the-loop--202608311037]], whose whole
subject is duration beating rate and which is grounded on a verified capture
of Housel ch. 4, re-scored to 0.90 groundedness back on 2026-08-31. The two
notes are about the same claim and there is NO link between them. This one is
a wiring fix, not a research task.

The other five need judgement rather than a lookup:
- 202701010011 and 202701010012 are arithmetic. They may not need a citation
  at all so much as an explicit note that they are definitional, in which case
  say so IN the note rather than leaving them looking unsourced.
- 202701010001, 202701010002 and 202701010003 are the zettelkasten design
  claims. 202701010002 already gained a paragraph on 2026-09-03 recording that
  Blair corroborates its reuse half and not its atomicity half; the other two
  have no such qualification and should get one if nothing turns out to
  support them. The Ahrens follow-up entry is the standing reason they are
  still bare: the chapters that would ground them (6, 9-11) are unreachable.

Do NOT close this by attaching whatever source is nearest. The failure mode
these notes invite is a citation that makes the lint pass while the claim
stays unsupported, and 202701010002's honest limiting paragraph is the model
for what to do when a source only half-covers a claim.

## 2026-09-03 — config.yml topics no longer describe this base: 59% of its permanent notes are on a topic config.yml does not list (human decision needed)

- **status:** answered        <!-- new | in-progress | answered | archived -->
- **answer:** DECIDED BY THE HUMAN, 2026-09-03, and this is authoritative
  (QA-4). Their words: "This sandbox content repo will mostly send her around
  the topics of theology and philosophy, so you can actually go ahead and
  update that field in the config.yml file." That is option (a) below, and it
  goes further than the entry proposed — the decision is not that a third
  cluster be added alongside two equals, but that theology and philosophy are
  what this repository is FOR.

  `config.yml` now reads:

      topics: ["theology", "philosophy", "zettelkasten method", "compound growth"]

  README.md's Topics line was updated to match, since it stated the old pair
  and would otherwise contradict config.yml at the repository's front door.

  TWO JUDGEMENT CALLS MADE IN CARRYING THIS OUT, both reversible, both flagged
  to the human in the reply that accompanied them:

  1. The original two topics were KEPT, not replaced. The instruction said
     "mostly", not "only", and dropping them has a concrete cost: 19 permanent
     notes sit under them, and so does queued work that exists precisely
     because a run is supposed to pick it up — inquiry 202609032123 (no
     empirical evidence under `zettelkasten method`), the 2026-08-31 Ahrens
     access entry, and the six ungrounded genesis notes, three of which are
     zettelkasten design claims. Removing the topic would strand that work
     from the cadence meant to close it. If the intent was to retire those
     clusters, deleting the two strings is a one-line change and this entry is
     the place to record it.
  2. The two new topics are deliberately the human's own words rather than
     sharpened into something like "philosophy of religion". Narrower strings
     would gap-fill more precisely, but they would also silently decide what
     counts as in scope — and the existing 26-note cluster is philosophy of
     religion, whereas "philosophy" as asked for is wider than that. The
     broader reading was taken as the safer one to hold, and is easy to
     narrow later.

  CONSEQUENCE, which is the point of the entry. Step 3 of the maintenance
  prompt gap-fills against these topics, so from the next scheduled run the
  cadence maintains the same-God / design-arguments / Kabbalah cluster
  directly, instead of it advancing only when a human asks. Inquiry
  202609032122 (the Islamic side argued only in non-Muslim voices) is now
  cadence-reachable rather than depending on an ad-hoc request, which is
  exactly the failure mode this entry was filed to name.

  Note for future runs: this change was made by a human instruction in
  session, and the standing rule is unchanged — a RUN may never edit the
  topics list to match what it has already written.
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-03 gap-filling graph walk. This one needs a human
decision and a maintenance run should NOT resolve it on its own.

THE FACTS. config.yml declares topics: ["zettelkasten method", "compound
growth"]. The base's 44 permanent notes divide as:

  Abrahamic conceptions of God   26  (59%)  -- NOT a configured topic
  zettelkasten method            11  (25%)
  compound growth                 8  (18%)

(11 + 8 counts the shared bridge note once on each side.)

The largest, densest, most-developed thing this repository contains is a
26-note cluster on the same-God question, divine simplicity, the sefirot and
the Trinity, and teleological arguments. It grew entirely out of ad-hoc human
inquiries — 202608311909, 202609010821, 202609010930, 202609011030,
202609011526, 202609022344, 202609030145, 202609030146 — and config.yml has
never mentioned it. Its central note,
[[the-same-god-question-turns-on-reference-versus-description--202608311942]],
is the single most-linked note in the base (in-degree 12), well ahead of
anything in either configured topic.

WHY IT IS NOT COSMETIC. Step 3 of the maintenance prompt tells a run to
"research and synthesize for open inquiries and for gaps against the `topics`
in config.yml". So under the current config, the scheduled cadence
systematically gap-fills the two SMALLER clusters and never the largest one.
The Abrahamic cluster grows only when a human asks a question. That is
precisely what happened all through 2026-09-01 to 09-03: every scheduled run
worked the zettelkasten and compound-growth topics while the same-God material
advanced only on ad-hoc request. The 2026-09-03 gap-filling walk found the
sharpest gap in the base sitting in that unconfigured cluster (the Islamic
side argued only in non-Muslim voices — inquiry 202609032122), and no
cadence-driven run would ever have gone looking for it.

THE DECISION, which is yours and not a run's:
(a) Add a third topic to config.yml — something like "Abrahamic conceptions of
    God" or "the same-God question" — and the scheduled cadence starts
    maintaining what is already the base's centre of gravity.
(b) Leave config.yml alone deliberately, on the view that this cluster is
    demand-driven and should only ever grow when you ask. That is a coherent
    position; it just should be a choice rather than an accident.
(c) Split the repository, if the two halves are really different projects.

A run may not edit config.yml topics to match what it has already written —
that would let the base silently redefine its own scope, and the genesis rule
is that topics are asked of the human and never guessed. Recording it here so
the next run reads a decision instead of re-deriving the discrepancy.

## 2026-09-04 — Corroborate the A Common Word finding from a second Muslim source arguing in its own voice

- **status:** in-progress        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04 maintenance cycle, which answered inquiry 202609032122
and deliberately left this open rather than claiming more than it earned.

WHAT IS ESTABLISHED. permanent 202609040115 argues that the major Muslim
consensus statement, A Common Word Between Us and You (2007), answers the
same-God question by relocating it onto shared obligation, taking neither horn
of the reference/description grid. The negative half of that is machine-checked
and solid: "same God", "worship the same", "same being" and "Divine Origin"
occur zero times in the letter's 49,644 captured characters. On the strength of
it, permanent 202608311942 -- the base's most-linked note, in-degree 12 -- now
carries a limit saying its framing is a participant's frame.

WHAT IS NOT. That is a lot of weight resting on ONE document, read directly.
The positive half of the claim -- that the silence is deliberate relocation
rather than the ordinary reticence of a document written to be signed by 138
people -- is an inference, and it currently has no second witness. This is
exactly why 202609040115 is NOT tagged `contested`: that tag carries a
three-independent-source bar in this repository, and tagging a single-source
note would either fail the gate honestly or invite link-stuffing to clear it.
The note says so in its own body rather than leaving the absence unexplained.

WHAT WOULD CLOSE IT. A second Muslim source arguing the question in its own
voice, in a different register from an irenic collective letter. In rough order
of expected value:

  (1) Zeki Saritoprak. Named in the base since 2026-08-31 but still only
      secondhand, as a person quoted in the NPR piece -- no reference note,
      nothing captured. Find something he actually wrote.
  (2) Al-Ghazali, Faysal al-Tafriqa bayna al-Islam wa-l-Zandaqa. The classical
      text on who counts as outside the faith. Old enough to be out of
      copyright; an English translation may not be.
  (3) Ibn Taymiyya, al-Jawab al-Sahih li-man baddala din al-Masih. A hostile
      witness, and useful for the same reason Modena was useful on the Jewish
      side: it argues the question instead of smoothing it.

Also untouched by anything now in the base: the juristic question of whether
Christians count as mushrikun, and how the exegetical tradition harmonises
29:46 against 4:171 and 5:73. Both are named in permanent 202609040120 as
limits on what it can claim.

NOT A BLOCKER. Nothing above is a defect in what landed. The cycle's notes
state their own limits, and this entry exists so the limits are worked on
rather than forgotten.

**2026-09-04 (07:00Z cycle) — worked, and the corroboration came back SPLIT.
Moving to `in-progress`, not `answered`, and the reasons are below.**

WHAT WAS CAPTURED, and it is not on this entry's shortlist. al-Tabari (d.
310/923), *Jami' al-bayan 'an ta'wil ay al-Qur'an*, the commentary on Q 3:64
and Q 29:46 — reference 202609040700, literature 202609040705, permanent
202609040710, 202609040715, 202609040720, capture
raw/202609040700-tabari-jami-al-bayan-3-64-and-29-46-arabic.txt (Arabic,
verbatim, full sections; public domain). Taken instead of (1) Saritoprak,
(2) al-Ghazali or (3) Ibn Taymiyya because this entry's real criterion was a
Muslim voice *in a register unlike an irenic collective letter*, and the
foundational Sunni commentary on the exact two verses the existing notes turn
on is further from that register than any of the three — while also being
free, complete and in the public domain, which none of the three is in
English. ACCESS: rung (a), first request, no obstacle. Quran.com API v4,
`/api/v4/tafsirs/15/by_ayah/<sura>:<aya>`. (The sibling endpoint
`/api/v4/quran/tafsirs/15?verse_key=…` returns an EMPTY list for the same
verse — do not read that as the text being unavailable.)

WHAT IT CORROBORATED. The *form* of 202609040115's claim, from a thousand years
earlier: there too the shared-God material is delivered as an instruction about
what to say, in a hard case, with no argument attached. In al-Tabari the setting
is an epistemic protocol — what a Muslim says when the People of the Book report
something from their books that he can neither verify nor deny. And the reading
of 3:64 as exclusionary rather than merely irenic is confirmed from inside: the
"equitable word" (`كلمة عدل`) has the disavowal of every rival object of worship
as its *content*, and the occasion reports transmit the verse with its refusal
attached.

WHAT IT REFUTED, which is why this entry earned its keep. The inference that the
2007 letter's silence about co-reference might reflect a tradition with nothing
to say about it is now dead. al-Tabari glosses `وَإِلَهُنَا وَإِلَهُكُمْ
وَاحِدٌ` as `ومعبودنا ومعبودكم واحد` — *the one we worship and the one you
worship is one* — flatly, without argument, with no dissent recorded. 202609040115
is amended in place: form-half strengthened, available-explanation half
withdrawn.

WHY NOT `answered`. Three reasons, all of them things this entry asked for that
are still missing. (i) All three named candidates remain uncaptured. (ii) The
juristic *mushrikun* question and the harmonisation of 29:46 against 4:171 and
5:73 — both named at the end of this entry — are untouched; al-Tabari bears on
the second only for one commentator. (iii) The `contested` tag still is not
earned: two sources are not three, and the second pulls partly against the
first, which is a reason to keep reading rather than to declare the matter
settled.

THE CHEAPEST NEXT STEP, now that the route is known: al-Qurtubi (resource 90),
Ibn Kathir Arabic (14) and the other classical commentaries on the SAME two
verses are on the same free endpoint. If al-Tabari's `ma'bud` gloss is
traditional rather than idiosyncratic, that is where it shows, and it would take
one cycle. Filed separately below so it is not buried in this entry.

## 2026-09-04 — Source-access gaps left open by the note-taking evidence cycle (inquiry 202609032123), including an unread corrigendum to a paper this base now cites

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed 2026-09-04 under skills/source-access-triage step 4. Three gaps, one of
which is more serious than the usual paywall entry and is listed first.

(1) THE UNREAD CORRIGENDUM. "Corrigendum: The Pen Is Mightier Than the
Keyboard: Advantages of Longhand Over Laptop Note Taking", Psychological
Science 29, no. 9 (September 2018): 1565-68. DOI 10.1177/0956797618781773,
PMID 30063408. Four pages of correction to a paper this base now cites in two
permanent notes, and its CONTENT is entirely unavailable: journals.sagepub.com
returns the same 403 bot challenge as the parent article, and the record
carries NO abstract in PubMed, in Europe PMC, or in OpenAlex -- all three
report abstract length 0. So the base knows THAT a corrigendum was published
and nothing at all about what it changed. Reference 202609040155 states this
in its body and no note here says or implies what was corrected. This is the
highest-value item in the entry: a four-page correction to the single
most-cited note-taking experiment could bear on whether literature note
202609040200 and permanent note 202609040210 are describing the paper as it
now stands. WHAT WOULD CLOSE IT: any institutional or library access to SAGE,
or a browser that clears the challenge.

(2) Pam A. Mueller and Daniel M. Oppenheimer, "The Pen Is Mightier Than the
Keyboard", Psychological Science 25, no. 6 (2014): 1159-68. DOI
10.1177/0956797614524581, PMID 24760141. Ladder tried 2026-09-04: (a)
journals.sagepub.com -> HTTP 403, 5,665-byte bot-challenge body, with and
without a browser user-agent; (b) Unpaywall by DOI -> is_oa false, zero
oa_locations, and OpenAlex agrees independently (oa_status "closed",
any_repository_has_fulltext false), so no OA copy exists to find; (c) nothing
to try at (c) for the same reason; (d) 2014, in copyright; (e) not in PubMed
Central or Europe PMC full text. ResearchGate NOT tried (house rule forbids
mirror routes). Grounded on the publisher abstract, which WAS cross-checked
against two independent indexes (NCBI E-utilities and EBI Europe PMC) and is
identical word for word under Unicode normalisation. Grounding-limited by
this: reference 202609040155, literature 202609040200, and both permanent
notes 202609040210 and 202609040215 wherever they characterise the study.

(3) Kayla Morehead, John Dunlosky and Katherine A. Rawson, "How Much Mightier
Is the Pen than the Keyboard for Note-Taking?", Educational Psychology Review
31, no. 3 (2019): 753-80. DOI 10.1007/s10648-019-09468-2, ERIC EJ1225471.
Ladder tried 2026-09-04: (a) link.springer.com -> HTTP 200 but a 3,038-byte
JS/auth shell, the identical standing condition the 2026-09-01
Goshen-Gottstein triage recorded against the same publisher; (b) Unpaywall
is_oa false and OpenAlex "closed", AND OpenAlex holds no abstract_inverted_index
for this work, so the OpenAlex-abstract route that rescued Goshen-Gottstein is
not available; (c) www.dunlosky.org could not be reached AT ALL -- the egress
proxy refused the CONNECT (curl 56, "connect_rejected"), which is an
environment-policy result and NOT evidence about whether an author copy is
posted there, so a run with different egress should re-try this rung first;
(d) 2019, in copyright; (e) not indexed in PubMed/Europe PMC, and the Wayback
Machine has been egress-blocked for this environment class since 2026-09-01.
ResearchGate surfaced an apparent PDF in search results and was NOT used.
Grounded on the ERIC author abstract, which unlike (2) has ONE witness -- no
second index holds a copy to collate against. Grounding-limited by this:
reference 202609040156, literature 202609040205, and both permanent notes.

ENVIRONMENT NOTE, not a source gap: Open Library was again unreachable this
cycle (HTTP 000 transport failure on both ISBNs tried) while Crossref returned
200 on a control request, so this is the same registry-specific outage the
2026-09-04T01:12 cycle recorded and it is now confirmed across two runs. Six
reference notes were downgraded by the live verify_refs pass and restored from
HEAD, as before. Recorded here only because the next run will meet it too;
the standing entry for the underlying tool defect is the 2026-09-02
verify_refs one and it was not duplicated.

## 2026-09-04 — Retrieval practice, the generation effect and transactive memory: the untouched half of inquiry 202609032123, and a contradiction the base should go looking for

- **status:** in-progress        <!-- new | in-progress | answered | archived -->
- **2026-09-04T06:00Z:** status corrected from `new` to `in-progress`. Item (1)
  was marked done by the 03:00Z cycle in the body below and the status line was
  not moved with it. Items (2) and (3) are untouched and are the whole of what
  is left; no cycle has yet taken them.
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04 note-taking evidence cycle, which answered one half of
inquiry 202609032123 and left the inquiry `in-progress` rather than claiming
the other half. This entry exists so the remainder is worked rather than lost
in a long inquiry body.

WHAT IS DONE. The direct note-taking experiments are now in the base, with
their replication history: Mueller and Oppenheimer 2014 and the Morehead,
Dunlosky and Rawson 2019 direct replication, written up as permanent notes
202609040210 and 202609040215. The finding is that the famous effect did not
replicate and that none of that literature reaches a slip-box claim.

WHAT IS NOT. Candidate sources 2 and 3 of the original inquiry, untouched:

  (1) Retrieval practice / the testing effect. Roediger and Karpicke 2006,
      "Test-Enhanced Learning", Psychological Science 17, no. 3: 249-55, DOI
      10.1111/j.1467-9280.2006.01693.x -- VERIFIED TO EXIST via Crossref this
      cycle and NOT captured; Unpaywall reports is_oa false, so it will need
      the access ladder. This is the highest-value item and the reason is
      specific rather than general: if retrieval is what consolidates
      learning, then handing memory to paper has a measurable COST, and that
      bears directly against Chavigny's "too much memorizing can be harmful
      to the higher intellectual qualities" in permanent note 202609032115 --
      which is currently the base's account of why the note became an
      external memory, argued from a historian and with nothing measured on
      either side. The original inquiry was right to call this a
      contradiction to look for rather than a corroboration, and a
      contradiction found would be worth more to this base than another
      supporting citation.
  (2) The generation effect.
  (3) Transactive / external memory, e.g. Sparrow, Liu and Wegner 2011 on
      search engines and memory.

ALSO STILL OPEN, and named in permanent 202609040215 as what would actually
close the gap: any study that operationalises ACCUMULATION and LINKING rather
than the medium of writing, and that measures an outcome months or years out
rather than a post-lecture test. Nothing found this cycle suggests one exists.
If a run establishes that none does, that is a result and should be written as
such -- the same standard the original inquiry set.

WATCH THE TIER RULE, restated from the original inquiry because it is the easy
mistake here: a psychology finding cited from a news write-up or a blog is
general-web. These should be peer-reviewed captures or they should not land.

**2026-09-04T03:00Z cycle — item (1) is DONE, and it did not go where this entry
expected.** Roediger and Karpicke 2006 is captured in FULL TEXT (reference
202609040305, literature 202609040310) along with two sources this entry did not
name: Agarwal et al. 2008 on open- and closed-book tests (202609040315 /
202609040320, also full text) and Karpicke's 2025 survey chapter (202609040325 /
202609040330, excerpts). Three permanent notes: 202609040340, 202609040345,
202609040350.

The correction to this entry's expectation is worth recording. This entry
predicted that retrieval practice would supply a measured cost of delegating
memory to paper, bearing against Chavigny in permanent 202609032115. The
prediction held; the source named did not supply it. Roediger and Karpicke 2006
compares two in-the-head conditions and never mentions notes or external storage
at any point — a full-text search is recorded in the capture. What supplied the
measurement was Agarwal et al. 2008, whose open-book condition is defined by its
authors as students viewing "notes and textbooks" during the test, and whose
finding is that the advantage was worth sixteen points immediately and nothing a
week later. Permanent note 202609040345 carries it, typed `contradicts` into
202609032115 and narrowed in its own body to the premise it actually touches.

**ITEMS (2) AND (3) REMAIN OPEN AND ARE NOW THE WHOLE OF WHAT IS LEFT:** the
generation effect, and transactive/external memory (Sparrow, Liu and Wegner 2011,
DOI 10.1126/science.1207745 — verified to exist via Crossref this cycle, Crossref
carries only a one-line teaser and not a real abstract, and Unpaywall reports
is_oa false). Capture its replication history with it, as this base did for
Mueller and Oppenheimer; do not cite the headline alone.

**ALSO STILL OPEN, unchanged and now measured rather than assumed:** no study
operationalises accumulation and linking, or measures an outcome months or years
out. The 2025 survey of retrieval-based learning runs 31 pages and never once
uses the words note-taking, notes, external memory or offloading.

**2026-09-04T06:00Z cycle — items (2) and (3) were NOT taken, and the reason is
that a different entry named a better use of the cycle.** The Rowland 2014 audit
was the highest-value outstanding item in the base by two entries' reckoning and
it is now read; see the 2026-09-04 robustness entry below. Items (2) and (3) are
untouched and remain the whole of what is left in this entry: the generation
effect, and transactive/external memory (Sparrow, Liu and Wegner 2011, DOI
10.1126/science.1207745, closed). Whoever takes item (3) should note that it is
the only remaining item in this entry that is *about* externalised memory rather
than about learning — which, given that four retrieval-practice sources have now
been searched and none of them mentions notes or offloading at all, makes it the
one place the base is still likely to find a measurement on its own subject
rather than an adjacent one. Two access routes worth trying on it before the
ladder, both learned since this entry was written: ask a host's own API for a
file list rather than following its landing page, and when a copy turns up on an
unexpected academic domain, open it and read its first page for a deposit
statement.

### Appended 2026-09-04 18:00Z: item (3) is DONE, item (2) is now the whole remainder, and the prediction in this entry was right for the wrong experiment

Item (3), transactive/external memory, is closed. Sparrow, Liu and Wegner 2011
is captured (reference 202609041800, literature 202609041810) as an EXCERPT —
its own cover page reads "all rights reserved" and this repository is public —
and its replication history came with it in full text under CC BY 4.0
(Hesselmann 2020, reference 202609041805, literature 202609041815). Five
permanent notes: 202609041820, 202609041825, 202609041830, 202609041835,
202609041840. Inquiry 202609032123 is marked `answered`.

**Access, for the record and against the ladder.** Sparrow is not open access —
Unpaywall returns `is_oa: false` and NO `oa_locations` for
`10.1126/science.1207745`, so rung (b) failed on the merits and not on a fetch
error. Rung (c) paid immediately: the paper's third author's own lab site at
Harvard (`dtg.sites.fas.harvard.edu/DANWEGNER/pub/`) serves the PDF. That is a
third instance of the rung-(c) pattern this base keeps recording, and the useful
generalisation from THIS one is narrow and new: **a dead author's lab page can
outlive them and still be the open route** — Wegner died in 2013 and the page is
still up on institutional web space. For Hesselmann, `peerj.com` returned HTTP
403 behind Cloudflare while the SAME article came back whole from PubMed
Central's E-utilities endpoint
(`eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=pmc&id=<PMCID>&rettype=xml`)
as publisher-deposited JATS XML. **Rule worth keeping: when a gold-OA publisher
is bot-blocked, go to the deposit, not to the paywall workaround.** The JATS
route is also strictly better than a PDF — real structure, no text layer to
mangle, and section titles that make honest locators for a journal with no page
numbers.

**Item (2), the generation effect, is now the entire remainder of this entry.**
Nothing else in it is open. It is the weakest of the three candidates for this
base's purposes and that should be said plainly before a later cycle spends on
it: the generation effect is about producing an item rather than reading it,
which is a claim about the moment of writing a note, and this base already has
that territory covered from two directions (the note-taking pair, and retrieval
practice). It is not about external storage. A cycle that takes it should expect
to be confirming an adjacent mechanism, not closing a gap.

**Where this entry's prediction landed.** It predicted a measured cost of
delegating memory to paper, bearing against Chavigny in permanent 202609032115.
The prediction was right and this entry named the wrong source for it twice:
first Roediger and Karpicke, which never mentions notes (the 03:00Z correction),
and then, implicitly, this literature's famous experiment — which turns out to
be a priming study with nothing to do with memory at all. What supplied the
measurement was Sparrow's *Experiment 2*, an experiment nobody cites: erased
0.31 against saved 0.22 recall, with the writing, the material and the attention
held constant. Permanent 202609041825 carries it and is typed `supports` into
202609032115, which now also carries a dated addition saying what the support
does and does not reach.


## 2026-09-04 — The retrieval-practice robustness claim rests on a self-assessment, and the audit that would settle it is sitting in gold open access

- **status:** in-progress        <!-- new | in-progress | answered | archived -->
- **2026-09-04T05:00Z:** item (1), the gold-OA audit, is DONE and written up at
  the end of this entry. Not `answered`: the entry names three audits and two
  smaller sources, and the one that would make the check independent — Rowland
  2014 — is still unread.
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04T03:00Z retrieval-practice cycle. This is a gap the
cycle created by being honest rather than one it inherited, and it has an
unusually cheap fix, which is why it is filed at `normal` rather than `low`.

**THE GAP.** Permanent note
[[retrieval-not-re-exposure-is-what-makes-learning-last--202609040340]] states
that retrieval practice produces durable learning, and states its evidential
standing carefully: two primary papers read in full, plus the field's own claim
that the effect has been "replicated hundreds of times". That claim comes from
[[karpicke-retrieval-based-learning--202609040325]], p. 434 — and Karpicke is
the second author of the 2006 paper the chapter is assessing. It is a
self-assessment. The base has read none of the independent audits, and the note
says so rather than rounding the claim up. This matters more here than it
usually would: the base's other measured note-taking source is a direct
replication by an outside team that FAILED
(202609040156 / 202609040205), so "the field says it is robust" is precisely
the kind of assurance this repository has already been burned by once.

**THE FIX, WITH THE ACCESS ALREADY CHECKED THIS CYCLE.** The chapter names three
meta-analyses (p. 412). Their access status was checked live on 2026-09-04 and
is not uniform:

  (1) **Pooja K. Agarwal, Ludmila D. Nunes and Janell R. Blunt 2021**,
      "Retrieval Practice Consistently Benefits Student Learning: a Systematic
      Review of Applied Research in Schools and Classrooms", *Educational
      Psychology Review* 33 (2021): 1409-1453, DOI 10.1007/s10648-021-09595-9. **Unpaywall reports is_oa TRUE, oa_status
      GOLD.** It is free, legitimately, right now. This is the one to take
      first and it should be a short cycle: fetch, capture, one reference note,
      one literature note, and then either upgrade 202609040340's standing
      paragraph or record what the review actually found if it is weaker than
      the chapter implies. NOTE the partial-independence limit before writing:
      Pooja K. Agarwal is the first author of
      [[agarwal-karpicke-kang-roediger-and-mcdermott-open-and-closed-book-tests--202609040315]],
      which this base cites, so this is an audit from inside the same research
      community, not an outside replication. It is still a systematic review
      with a meta-analysis and it is still much better than the survey chapter.

  (2) **Christopher A. Rowland 2014**, "The Effect of Testing Versus Restudy on
      Retention: A Meta-Analytic Review of the Testing Effect", *Psychological
      Bulletin* 140, no. 6 (2014): 1432-1463, DOI 10.1037/a0037559. Unpaywall is_oa false, closed.
      This is the **most independent** of the three and therefore the most
      valuable — Rowland is not part of the Roediger/Karpicke line. It will
      need the access ladder. APA PsycNet was NOT tried this cycle, so nothing
      is known about that rung; the author-page rung (see below) has not been
      tried either.

  (3) **Olusola O. Adesope, Dominic A. Trevisan and Narayankripa Sundararajan
      2017**, "Rethinking the Use of Tests: A Meta-Analysis of Practice
      Testing", *Review of Educational Research* 87, no. 3 (2017): 659-701, DOI
      10.3102/0034654316689306. Unpaywall is_oa
      false, closed. SAGE, so expect the standing 403 bot challenge; the
      author-page rung is untried.

**TWO SMALLER SOURCES, ALSO UNREAD, BOTH NAMED INSIDE NOTES THAT ARE ALREADY IN
THE BASE.** Neither is load-bearing; both would sharpen a caution that is
currently carried on someone else's citation.

  - **Agarwal and Roediger 2011**, "Expectancy of an open-book test decreases
    performance on a delayed closed-book test", *Memory* 19, no. 8 (2011):
    836-852, DOI 10.1080/09658211.2011.613840. Unpaywall is_oa false, closed.
    Its title alone says something stronger than anything this base currently
    holds: it is not just having the notes that costs, it is EXPECTING to have
    them. If that holds up on reading, permanent note
    [[having-the-notes-to-hand-buys-present-performance-not-durable-knowledge--202609040345]]
    understates its own case and should be revisited.
  - The older classroom studies cited by Agarwal et al. 2008 (p. 872) for the
    claim that students "prepare less effectively" when an open book is
    allowed: Boniface 1985, Kalish 1958, Pauker 1974, Weber, McBee and Krebs
    1983. Not looked up at all. The 2008 paper offers them as a citation, not
    as its own finding, and 202609040345 says so; if a run wants that caution
    to be more than hearsay, these are where it lives. Two of the four predate
    1975 and may be hard to reach.

**A HOUSE-PROCEDURE PROPOSAL, for the next skill-smith cycle rather than for
this one** (skill_smith_cadence is weekly and the next falls ~2026-09-08, so
this cycle could not act on it). `skills/source-access-triage` step 1 lists the
access ladder as (a) publisher, (b) Unpaywall/OA repository, (c) author or
institutional pages, (d) public-domain etext, (e) Wayback. This cycle is
evidence that rung (c) is badly under-weighted for experimental psychology
specifically. The tally: publisher rung returned HTTP 403 with a bot challenge;
Unpaywall returned is_oa false with zero locations for every DOI tried; and a
SINGLE author-laboratory publications index — learninglab.psych.purdue.edu,
which posts PDFs of everything its principal investigator has published — then
returned THREE full texts in one pass, two of them papers that Unpaywall had
just declared unavailable. Suggested amendment: for a paywalled paper with an
identifiable academic laboratory behind it, try the lab's own publications page
BEFORE concluding the text is unreachable, and record it as its own sub-rung
with the search pattern that works (the lab site, its `/publications/` index,
and the year-foldered `/downloads/` paths the index links to). This is not a
new rung, it is a promotion of an existing one from last resort to first
recourse in a domain where it demonstrably works.

  **2026-09-04 (07:00Z cycle) — a COUNTER-observation, filed here so the
  skill-smith cycle sees the limit of the evidence it will be handed.** Three
  cycles have now supported this amendment and all three worked
  experimental-psychology papers behind commercial publisher paywalls. This
  cycle worked a classical Arabic text and rung (a) succeeded on the FIRST
  request — a free institutional API served the full text with no obstacle at
  all. That is not a counter-example to the amendment's evidence; it is a
  counter-example to stating the amendment unconditionally. If rung (c) is
  promoted, promote it *for the domain the evidence comes from* (paywalled
  journal literature with an identifiable laboratory behind it), and leave rung
  (a) first for primary texts, scripture, classical works and anything served by
  a library, museum or university API — where it has never yet failed in this
  base. A ladder reordered globally on evidence from one domain would send a
  future run hunting author pages for a ninth-century commentator.

**FOR THE ENVIRONMENT LOG, not a source gap.** Open Library is REACHABLE again
from this container (302 on `/isbn/<isbn>.json`, 200 on `/search.json`), ending
the two-day outage the 2026-09-04T01:12Z and 2026-09-04T02:10Z cycles recorded.
No reference note was downgraded by the live verify_refs pass this cycle for
that reason, and the restore-from-HEAD step those cycles had to treat as routine
was not needed. Details and the one downgrade that DID occur are appended to the
standing 2026-09-02 verify_refs entry.

**2026-09-04T05:00Z cycle — ITEM (1) IS DONE, and the entry stays open for the
rest.** Agarwal, Nunes and Blunt 2021 is captured in FULL TEXT (reference
202609040505, literature 202609040510, capture
raw/202609040505-...-fulltext.txt, 65 pp.). One new permanent note, 202609040515.
Permanent note 202609040340's standing paragraph is rewritten rather than merely
upgraded, and literature note 202609040330 now carries a correction. Three things
came back, in ascending order of importance:

  (i) **The access status in this entry was right about the licence and wrong
      about what that buys.** The article is gold OA, and the PUBLISHER RUNG
      STILL FAILED: link.springer.com served the standing 3,038-byte JS shell on
      all three routes including the `fulltext.html` one Crossref advertises for
      text mining. Worse, Unpaywall's two OA locations are OSF landing pages
      with no `url_for_pdf`, and both `/download` routes return HTTP 500 —
      because one id is an OSF *registration* and the other a *project*, and
      neither is a file. Semantic Scholar repeats the same dead URL. What worked
      was asking the OSF API for the project's FILE LIST
      (`api.osf.io/v2/nodes/mz2ks/files/osfstorage/`), which returned the
      authors' accepted manuscript in one request. **Rule for the next run: an
      OA landing page that will not yield a file is not a dead end until the
      host's own API has been asked for the file list.** This is a second,
      independent piece of evidence for the rung-(c) amendment proposed above,
      and it broadens it: the sub-rung is not only "the lab's publications page"
      but "the author-controlled repository's API".

 (ii) **It is not a meta-analysis, and Karpicke's chapter mis-describes it.**
      Its authors considered pooling and refused, on non-independent effect
      sizes and the low reproducibility of meta-analytic means (accepted ms.
      p. 7), publishing individual effect sizes in forest plots instead. Small
      error in a citation, not a misrepresented result — but it means the
      "three meta-analyses" phrasing in 202609040340 and 202609040330 was
      inherited rather than checked, and both are now corrected. Rowland 2014
      and Adesope et al. 2017 ARE meta-analyses.

(iii) **The finding this entry did not anticipate: the classroom delay gradient
      runs the wrong way.** "Effect sizes were larger following a 1-3 day delay,
      while smaller following an end-of-semester delay" (p. 35) — and the
      reviewers themselves name it as the reverse of the laboratory pattern,
      citing Roediger and Karpicke 2006, and make it their first recommendation
      for future research. That bears against the extrapolation in 202609040340,
      which is the note this entry set out to strengthen. It is written up as
      permanent 202609040515 with its own limit stated: delay was coded ACROSS
      studies, never manipulated within one, so it is not a causal result. On
      the robustness question the review is mostly confirming — 46 of 49 effect
      sizes favour retrieval practice and only six confidence intervals reach
      below zero — but the headline 57% medium-or-large leaves 43% small, very
      small or negative, and 24 further comparisons could not be scored at all
      because the original papers under-reported.

**WHAT REMAINS OPEN IN THIS ENTRY, unchanged in priority order:** Rowland 2014
(DOI 10.1037/a0037559) is now the highest-value item in it — the only audit of
the three written from outside the Roediger/Karpicke line, and the only one that
would be an independent check rather than a partly-inside one. Untried rungs for
it: APA PsycNet, and the author page. Then Adesope et al. 2017 (DOI
10.3102/0034654316689306, SAGE, expect the standing 403), then Agarwal and
Roediger 2011 (DOI 10.1080/09658211.2011.613840) and the four pre-1985 classroom
studies. NOTE for whoever takes Rowland: this cycle's route is worth trying
first — a search of OSF and of the author's institutional repository for a
deposited manuscript, asking any host's API for a file list rather than
following its landing page.

**ALSO MEASURED AGAIN, third source running:** the strings `note-taking`, `note
taking`, `notetaking`, `external memory`, `offloading`, `slip box` and
`zettelkasten` occur ZERO times in all 65 pages. The standing "nothing
operationalises accumulation and linking" item is now evidenced on three
independent retrieval-practice sources rather than assumed.

**2026-09-04T06:00Z cycle — ITEM (2), ROWLAND 2014, IS DONE. It was the item
this entry called the highest-value one and it was, though not for the reason
given.** Captured as reference 202609040600, literature 202609040605, capture
`raw/202609040600-rowland-2014-testing-effect-meta-analysis-excerpts.txt`
(excerpts, and see the separate INBOX entry filed this cycle for why the capture
is excerpts rather than full text — the article was read in full). Three
permanent notes: 202609040610, 202609040615, 202609040620.

  (i) **ACCESS.** The route this entry recommended — OSF, the author's
      institutional repository, host APIs rather than landing pages — did not
      work, and is recorded with its failures in the reference note and in the
      access entry filed alongside this one. What worked was a plain web search
      turning up the article as a course asset on a university teaching server,
      whose first page is a ResearchGate cover sheet documenting the author's
      own 2016 deposit. Publisher (Incapsula bot challenge) and every OA index
      (Unpaywall, OpenAlex, Semantic Scholar, OpenAIRE, unanimously closed) both
      failed, which is the third cycle running that rung (c) has been the one to
      deliver.

 (ii) **THE ROBUSTNESS QUESTION THIS ENTRY EXISTS FOR IS NOW ANSWERED, AND THE
      ANSWER IS YES WITH NUMBERS.** `g = 0.50, CI [0.42, 0.58]`, 159 effect
      sizes from 61 studies reported 1975-2013, from an author with no
      connection to the Roediger-Karpicke line. Permanent note 202609040340's
      standing paragraph is rewritten again to say so. Two qualifications go
      with it and are in 202609040615: 28 of the 159 effect sizes are negative
      (counted off the paper's own stem-and-leaf plot, whose leaves sum to
      exactly 159), and the published-versus-unpublished gap the author detected
      — 0.58 against 0.25 — was argued away on design grounds rather than
      corrected for, with no funnel plot or trim-and-fill reported and a stated
      reason for not running them.

(iii) **AND THE SURVEY'S "THREE META-ANALYSES" DESCRIPTION IS NOW TWO FOR TWO ON
      BEING WORTH CHECKING.** Rowland 2014 IS a meta-analysis, so the chapter
      was right about this one and wrong about Agarwal et al. 2021. Literature
      note 202609040330 carries both halves now.

 (iv) **THE UNANTICIPATED FINDING, and it revises a note this base wrote six
      hours ago.** Rowland excluded classroom studies by explicit inclusion
      criterion (d), thirteen of them, pointing readers to a different review;
      Agarwal, Nunes and Blunt excluded the laboratory for the symmetrical
      reason. The two reviews share no studies at all. And their delay ranges
      barely overlap — Rowland's moderator is binary at one day over a
      literature he frames as running from minutes to "days or weeks", theirs
      runs from a 1-3 day delay to an end-of-semester one they gloss as
      "approximately 6-15 weeks". So the reverse-gradient conflict recorded in
      202609040515 is not a conflict; it is two adjacent stretches of one curve
      that rises to a few days and falls after. Written up as 202609040610, with
      credit where it is due: the classroom reviewers proposed exactly this
      explanation themselves (p. 43), inferring the laboratory range from a
      third review; what is new is checking it against the laboratory review
      directly, and the disjoint-criteria fact, which they do not mention.
      202609040515 is amended in place rather than left standing.

**WHAT REMAINS OPEN IN THIS ENTRY.** Adesope, Trevisan and Sundararajan 2017
(DOI 10.3102/0034654316689306) is now the last unread audit of the three, and
this cycle's route is the one to try first for it: a web search for an
academic-domain PDF, then open the file and look for a deposit statement on its
first page before judging its provenance. Its result is also now specifically
wanted rather than merely owed — it is the review whose delay distribution
(64% of studies at six or fewer days) the classroom reviewers cite second-hand
to support the taper hypothesis, so reading it directly would test 202609040610
on the point that note is weakest. Then Agarwal and Roediger 2011 (DOI
10.1080/09658211.2011.613840) and the four pre-1985 classroom studies. Status
stays `in-progress`.

**ALSO MEASURED AGAIN, fourth source running:** across all 34 pages of Rowland
the strings `note-taking`, `note taking`, `notetaking`, `external memory`,
`offloading`, `slip box`, `zettelkasten` and `transactive` occur ZERO times;
`notes` occurs once and not about note-taking. Four independent
retrieval-practice sources, no mention of externalised memory in any of them.

## 2026-09-04 — Full-text captures of all-rights-reserved articles sit in raw/ in a public repository, and this cycle declined to add a third (human decision needed)

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04T06:00Z Rowland cycle, which hit the question and made a
conservative call it does not have the standing to make permanently.

**WHAT HAPPENED THIS CYCLE.** Rowland 2014 (DOI 10.1037/a0037559, Psychological
Bulletin) was obtained in full and read in full. Every page of the PDF carries
the printed notice `This document is copyrighted by the American Psychological
Association or one of its allied publishers. This article is intended solely for
the personal use of the individual user and is not to be disseminated broadly.`
This repository is public (config.yml `visibility: public`). Committing the
extracted 32-page text would put a verbatim copy of an all-rights-reserved
article on a public GitHub repository, which is the thing that notice forbids in
as many words. So the capture at
`raw/202609040600-rowland-2014-testing-effect-meta-analysis-excerpts.txt` is an
EXCERPT capture: the passages the notes actually use, plus the source URL and a
SHA-256 so any quotation can be re-derived. Nothing in the notes is
under-grounded by this — the full text was read, so design, criteria, counts and
the author's reasoning are all reportable, which is the standard
`skills/source-access-triage` step 2 sets for a source read in full.

**WHY IT IS AN INBOX ENTRY AND NOT JUST A CHOICE.** The base is not consistent
on this, and the inconsistency predates this cycle:

  - `raw/202609040305-roediger-karpicke-2006-...-fulltext.txt` — Psychological
    Science, closed access, captured FULL TEXT from the author's lab page.
  - `raw/202609040315-agarwal-et-al-2008-...-fulltext.txt` — closed access,
    captured FULL TEXT from the same lab page.
  - `raw/202609040325-karpicke-2025-...-excerpts.txt` — in-copyright Elsevier
    chapter, captured as EXCERPTS.
  - `raw/202609040505-agarwal-nunes-blunt-2021-...-fulltext.txt` — gold OA
    accepted manuscript, FULL TEXT. This one raises no question at all.
  - `raw/202609040600-rowland-2014-...-excerpts.txt` — closed access, EXCERPTS,
    this cycle.

The two full-text captures of closed articles were made in good faith from
author-posted copies, and author self-archiving is a legitimate access rung. But
"the author may post this" and "this repository may republish it" are different
permissions, and the second one is the one that matters for a public repo. The
raw/ layer is immutable by house rule and knowledge is never rolled back to make
something else pass, so this cycle did not touch those two files and is not
proposing that a future cycle quietly does.

**WHAT A HUMAN NEEDS TO DECIDE**, because a run should not:

  1. Is EXCERPT capture the standing rule for any source whose licence is not
     open, with FULL TEXT reserved for open-access and public-domain sources? If
     so it belongs in `skills/source-access-triage` as a new step, and the
     skill-smith cadence (~2026-09-08) is where that lands.
  2. What to do about the two existing full-text captures of closed articles.
     Options a human might take that a run may not: leave them (a considered
     decision, and defensible for a small research repository), replace them
     with excerpt captures plus checksums (which costs nothing in grounding,
     since every note that cites them quotes specific passages), or make the
     repository private, which config.yml says is a genesis-time choice.
  3. Whether the excerpt standard is too strict for this base's purposes. The
     argument against it: full text in raw/ is what lets a later cycle re-check
     a claim without re-fetching, and re-fetch is exactly the step that fails
     most often in this environment.

**WHAT THIS CYCLE DID NOT DO,** so it is not mistaken for an answer: it did not
delete or edit any existing capture, did not change any note that cites one, and
did not weaken any claim. The three notes it wrote from Rowland are grounded on
a full reading and cite page locators that a reader with the article can check.


### Appended 2026-09-04 08:00Z: two more in-copyright captures, taken as excerpts under the rule this entry is asking about

This cycle captured two modern, in-copyright Arabic commentaries — al-Sa'di
(d. 1956) and *al-Tafsir al-Muyassar* — and did NOT take full text for either,
even though both are short and both are distributed free by their publishers.
al-Sa'di's comments were cut to the lemma-and-gloss sequences the notes use,
with omissions marked `[...]`; *al-Muyassar*'s served comment is one short
paraphrase per verse and was taken whole because there is no smaller unit that
still shows what its gloss does.

That is the excerpt-capture rule this entry's human decision would either
ratify or replace, applied voluntarily rather than waiting. Two observations
for whoever decides. First, the cost was near zero here: the argument in
202609040825 needs two sentences from each source and nothing else, so the
excerpt lost nothing the notes wanted. Second, it is NOT free in general — the
completeness check that made this cycle's central finding safe (that
al-Qurtubi's comment really ends where it appears to) was only possible because
the three public-domain captures are complete. An excerpt cannot support a
claim about an absence. So the rule worth considering is not "excerpt
everything in copyright" but "excerpt in copyright, and never rest a negative
claim on an excerpt".

## 2026-09-04 — Access and environment findings from the Rowland cycle: a third piece of evidence for the rung-(c) amendment, and two hosts that failed in new ways

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04T06:00Z cycle. Two of these belong to the standing
source-access proposal; two are environment facts that will save a later run a
detour.

**THIRD INDEPENDENT PIECE OF EVIDENCE FOR THE RUNG-(c) AMENDMENT.** The proposal
drafted by the 2026-09-04T03:00Z cycle and reinforced by the 05:00Z one — promote
`skills/source-access-triage` rung (c), author or institutional pages, to first
recourse for experimental psychology — is now supported by a third case, and this
one extends it in a direction neither earlier case covered. The tally for Rowland
2014: rung (a) psycnet.apa.org returned HTTP 200 with a 1,038-byte Incapsula
bot-challenge shell; rung (b) failed unanimously and with more sources agreeing
than usual — Unpaywall `is_oa false` / `oa_status closed` / zero locations,
OpenAlex the same plus `any_repository_has_fulltext: false`, Semantic Scholar
`openAccessPdf.status: CLOSED` with the abstract elided at the publisher's
request, OpenAIRE one record and no full-text location. Rung (c) worked.

**The extension, and it is the transferable part.** The two earlier cases found
the file on a host that is obviously the author's (a lab publications index, an
OSF project API). This one did not. What returned the article was a course asset
on `courseware.epfl.ch`, found by a plain web search — a university's teaching
server, which is nobody's idea of an author page. The reason it counts as rung
(c) rather than as an unattributable mirror is that the FILE ITSELF documents its
own provenance: page 1 is a ResearchGate cover sheet reading `All content
following this page was uploaded by Christopher A Rowland on 10 February 2016`,
with the publication id and the author's affiliation. So the suggested wording
for the amendment gains a clause: when a copy turns up on a host that is not the
author's, open it and look for a deposit statement before judging it, because
author-deposited files carry their provenance with them and re-hosts inherit it.
A file whose first page says who uploaded it and when is a different object from
an anonymous scrape.

**ENVIRONMENT: `api.fatcat.wiki` is egress-blocked from this container.** The
Internet Archive Scholar / fatcat API is the natural way to ask "is any preserved
full text known for this DOI", and it does not merely 4xx — `curl` reports
`(35) Recv failure: Connection reset by peer` and no HTTP status at all, which is
the signature of the egress policy rather than of the service. Do not spend a
rung on it. `api.osf.io`, `api.openaire.eu`, `api.unpaywall.org`,
`api.openalex.org`, `api.semanticscholar.org`, `api.crossref.org`,
`eutils.ncbi.nlm.nih.gov` and `courseware.epfl.ch` were all reachable in the same
pass.

**ENVIRONMENT: mountainscholar.org (Colorado's institutional repository) is a
DSpace 7 Angular app whose REST API is not where the convention puts it.** It was
tried because Rowland was at Colorado State University and a university
repository is the textbook rung-(c) target. `/search?q=...` returns a 1,140-byte
JS shell; `/server/api` and `/rest/items` both return the app's own 404 page
(382 KB of Angular, HTTP 404), so the backend is not co-located with the
frontend under either conventional path. A later run that needs it should read
the frontend's runtime config for the REST base URL rather than guessing paths,
or fall back to OAI-PMH. Not pursued further this cycle because the article was
already in hand by then, and because a 2014 APA journal article was never a
likely repository deposit in the first place — the dissertation would be.

**PubMed is a reliable abstract rung for anything with a PMID.**
`eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=pubmed&id=<PMID>&rettype=abstract&retmode=text`
returned the full APA-supplied abstract for a paper whose abstract Semantic
Scholar had elided at the publisher's request and whose publisher page was
bot-blocked. Worth adding to the ladder as the fallback that makes abstract-only
grounding available even when rungs (a) and (b) both fail, for anything indexed
in MEDLINE.

## 2026-09-04 — Test the al-Tabari ma'bud gloss against the other classical commentaries, which are on the same free endpoint

- **status:** answered        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04 07:00Z cycle, which captured al-Tabari on Q 3:64 and
Q 29:46 and stated a limit it could not close itself.

THE CLAIM AT RISK. Permanent 202609040710 says Islam's foundational commentary
answers the co-reference question affirmatively and treats it as needing no
argument, on the strength of one gloss: `وَإِلَهُنَا وَإِلَهُكُمْ وَاحِدٌ`
read as `ومعبودنا ومعبودكم واحد`. One commentator is one commentator. If the
gloss is TRADITIONAL, other classical commentators will make the same move or
something close to it; if it is IDIOSYNCRATIC to al-Tabari, the note is
overclaiming when it says "in this tradition at this date" and should be
narrowed to him.

WHY THIS IS CHEAP, WHICH IS THE POINT OF FILING IT. The access problem is
already solved. The same free Quran.com API v4 endpoint that served al-Tabari
serves the other classical Arabic commentaries on any verse:

    https://api.quran.com/api/v4/tafsirs/<resource>/by_ayah/<sura>:<aya>

with resource 90 = al-Qurtubi, 14 = Ibn Kathir (Arabic), 94 = al-Baghawi,
91 = al-Sa'di, 16 = al-Muyassar, 93 = al-Wasit (Tantawi). No paywall, no bot
challenge, no renderer. `/api/v4/resources/tafsirs` lists them all. The two
verses to pull are 29:46 and 3:64, the same pair, so the comparison is exact.
Independent witnesses for cross-checking are known to work too: tafsir.app
(/tabari/29/46 pattern, host takes other commentator slugs) and
quran.ksu.edu.sa (/tafseer/<name>/sura29-aya46.html — note its sura-3 URL
returned a 203-byte stub for al-Tabari, so check per verse).

WHAT A GOOD RESULT LOOKS LIKE. Not "add three more notes". The test is whether
202609040710 has to be narrowed. Three outcomes are all worth having:
  - Other commentators make the same identification -> the note stands and can
    say so with a second and third witness, and the `contested` tag on
    202609040115 becomes reachable on the three-source bar.
  - They differ -> the note is narrowed to al-Tabari, and the DISAGREEMENT is
    the more interesting finding, because it would mean the classical tradition
    itself divides on co-reference.
  - They pass over the clause in silence -> that is evidence for the same
    conclusion the current note draws from al-Tabari's own silence, arrived at
    independently.

ALSO STILL OPEN, and NOT closed by this. The juristic question of whether
Christians count as *mushrikun*, which no capture in this base touches, and the
three sources the corroboration entry above still names: Saritoprak,
al-Ghazali's *Faysal al-Tafriqa*, Ibn Taymiyya's *al-Jawab al-Sahih*. A run
that does the cheap commentary sweep should not report the *mushrikun* gap as
narrowed by it.

A CAUTION FOR WHOEVER TAKES THIS. Every English rendering in the al-Tabari
notes is this repository's own working translation, because the base holds no
published translation of the text. A cycle that adds three more commentators
multiplies that exposure. Either keep printing the Arabic beside every
rendering that carries weight, as the current notes do, or find a published
translation for at least one of them and use it to calibrate.

### Answered by the 2026-09-04 08:00Z cycle — outcome three, and the note was narrowed

Everything this entry said would be cheap was cheap. Quran.com API v4, rung (a),
first request, five commentaries on both verses: al-Qurtubi (resource 90), Ibn
Kathir (14), al-Baghawi (94, added — the entry left "the other classical
commentaries" open), and for comparison the modern al-Sa'di (91) and *al-Tafsir
al-Muyassar* (16). Total elapsed for the fetching: under two minutes.

THE RESULT IS THE THIRD OF THE THREE OUTCOMES THIS ENTRY NAMED IN ADVANCE.
"They pass over the clause in silence." None of the three classical
commentators glosses `وإلهنا وإلهكم واحد`. The word `معبود` — the whole of
al-Tabari's move — occurs in none of their comments on Q 29:46, checked on
Quran.com and on both `quran.ksu.edu.sa` and `tafsir.app`. And because this is
an absence, it was checked as one: al-Qurtubi's comment announces `فيه مسألتان`
and delivers both questions, and all three copies of each commentator's comment
begin and end at the same sentence, so the silence is a property of the
commentary and not of an abridged electronic text.

WHAT WAS DONE ABOUT IT. 202609040710 was narrowed in place: the sentence
inferring what was uncontested "in this tradition at this date" now reads "for
him", with an amendment section saying what was withdrawn and what was
strengthened. Permanent 202609040820 records the finding, and the `contested`
tag on 202609040115 is still NOT reachable on the three-source bar — three
silences are not three witnesses.

THE UNEXPECTED HALF. The clause is not glossed by anyone until the modern
period, and when it is glossed, it is not glossed al-Tabari's way. al-Muyassar
expands it `لا شريك له في ألوهيته، ولا في ربوبيته، ولا في أسمائه وصفاته`;
al-Sa'di converts it into a premise disputation must be built on, `وعلى أن
الإله واحد`. Both are the description question, not the reference one
(202609040825).

AND THE 3:64 HALF WENT THE OTHER WAY. The summons reading travelled intact to
all three classical commentators, two of whom name the cross among what the
"common word" excludes, and three of whom quote the letter to Heraclius
(202609040830). So of the two claims the 07:00Z cycle drew from al-Tabari, the
one about 3:64 is now four-source and the one about 29:46 is one-source. That
asymmetry is the cycle's actual result.

WHAT THIS ENTRY EXPLICITLY DID NOT CLOSE, restated so no later run reads the
commentary sweep as broader than it was: the juristic *mushrikun* question is
untouched, and Saritoprak, al-Ghazali's *Faysal al-Tafriqa* and Ibn Taymiyya's
*al-Jawab al-Sahih* are still uncaptured. Those stay with the corroboration
entry above, which stays `in-progress`.

## 2026-09-04 — Leads left open by the commentary sweep: al-Razi, Tantawi's single witness, and a translation-calibration debt that is now five notes deep

- **status:** in-progress        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** run

Filed by the 2026-09-04 08:00Z cycle. Four items, each with what is already
known written down so a later run spends its turns on the work.

(1) AL-RAZI IS NOT ON THE ENDPOINT. `/api/v4/resources/tafsirs` lists exactly
seven Arabic commentaries — 14 Ibn Kathir, 15 al-Tabari, 16 al-Muyassar, 90
al-Qurtubi, 91 al-Sa'di, 93 al-Wasit (Tantawi), 94 al-Baghawi. *Mafatih
al-ghayb* is not among them, and al-Razi is the one classical commentator whose
absence actually matters here, because he is the theologian of the group and
the co-reference question is a theological one: the three captured this cycle
are a jurist, a traditionist and an abridger, and their silence may be a fact
about the *genre* rather than about the tradition. `tafsir.app` serves him
(slug pattern `/razi/29/46` untried) and so may `quran.ksu.edu.sa`. Until he is
captured, 202609040820's claim is about three commentaries of three particular
kinds, which is what it says.

(2) TANTAWI STANDS ON ONE WITNESS. *al-Tafsir al-Wasit* (resource 93) glosses
the clause `( وإلهكم وَاحِدٌ ) لا شريك له لا فى ذاته ولا فى صفاته` — note that
his lemma drops `وإلهنا` — which is a third instance of the modern
tawhid-reading and would take 202609040825 from two witnesses to three. It was
deliberately left out: `quran.ksu.edu.sa` does not carry him, and
`tafsir.app`'s `waseet`, `wasit` and `tantawi` slugs all return a ~150 KB page
with no commentary body (the host appears to answer 200 for unknown slugs, so a
byte count near 150,400 is this environment's signature for "no such
commentary"). Find one independent host and the note gains a witness for the
cost of one request.

(3) THE TRANSLATION DEBT IS NOW FIVE NOTES DEEP AND SHOULD BE PAID ONCE. Every
English rendering of Arabic in this base is its own working translation, and
the exposure has grown from one source to six in a day. Ibn Kathir is the place
to pay it: unlike al-Tabari, al-Qurtubi and al-Baghawi, his commentary has
several complete published English translations, so ONE published translation
consulted on ONE commentator would calibrate the whole set — if this base's
renderings of Ibn Kathir on 3:64 and 29:46 track a published one, the method is
sound; if they drift, every other rendering is suspect. That is a cheaper and
sharper test than translating more.

(4) THE MUSHRIKUN QUESTION, still, and it is the last structural gap in this
cluster. Every commentary captured this cycle attaches the *jizya* and the
sword to these verses without registering any tension with the shared-God
clause, which is a datum in itself and is recorded in the notes. What is not in
the base is the juristic literature that decides whether Christians count as
*mushrikun*, and that is where the tension would have had to be resolved if
anyone resolved it. No access route has been tried for it yet.

### Appended 2026-09-04 09:00Z: item (1) is closed, item (2) is settled negatively

**(1) AL-RAZI IS CAPTURED, AND THE SLUG IN THIS ENTRY WAS WRONG.** tafsir.app
serves *Mafatih al-ghayb* under `alrazi`, not `razi`. The guess recorded above
returns the host's ~150,400-byte empty-shell page, which is why it looked like
an absence. Both verses were fetched on the first request with the right slug
and are captured in full at
`raw/202609040905-razi-mafatih-al-ghayb-3-64-and-29-46-arabic.txt`.

The result: al-Razi does NOT gloss `وإلهنا وإلهكم واحد` either. `معبود` occurs
nowhere in his comment on 29:46, checked in three independently served copies.
The genre explanation this entry was written to test therefore fails, and the
notes say so — 202609040915, and amendments on 202609040820 and 202609040710.
Two further findings came with it: he grounds the verse's leniency in the People
of the Book having *professed oneness* (202609040920), and he reads "except
those of them who do wrong" as excluding trinitarians as associators
(202609040925), which is the nearest thing yet to item (4)'s *mushrikun*
question, answered from tafsir rather than from fiqh.

**(2) TANTAWI: tafsir.app IS RULED OUT, NOT UNTRIED.** The site embeds its whole
resource list in every page as `data-src` attributes — 165 entries, extractable
with one request. *al-Wasit* / Tantawi is not among them under any spelling, so
the three slug guesses recorded above failed because the commentary is absent,
not because the slugs were wrong. Some other host has to be found; this one is
finished. (`quran.ksu.edu.sa` was checked the same way and carries exactly five
tafsirs: `tabary`, `baghawy`, `katheer`, `qortobi`, `saadi`.)

**(3) THE TRANSLATION DEBT IS NOW SEVEN SOURCES DEEP.** Unpaid again this cycle,
and the argument in the original entry — pay it once, on Ibn Kathir, because he
alone has published English translations — is unchanged and still right.

**(4) THE JURISTIC QUESTION IS STILL UNTRIED**, though it is no longer the only
route: see 202609040925 for the exclusion argued inside tafsir.

**A new lead this cycle opened.** That same 165-entry list is a free expansion
path for this whole cluster. Among the classical commentaries on it that this
base has never touched: al-Zamakhshari's *Kashshaf* (`kashaf`), Ibn 'Ashur
(`ibn-aashoor`), Abu Hayyan's *al-Bahr al-muhit* (`albahr-almuheet`), al-Alusi
(`alaloosi`), al-Baydawi (`albaydawee`), al-Nasafi (`alnasafi`), al-Mawardi
(`almawirdee`), Ibn al-Jawzi's *Zad al-masir* (`zad-almaseer`), al-Tha'labi
(`althalabi`), Ibn 'Atiyya (`ibn-atiyah`). The Mu'tazili-leaning Zamakhshari is
the one most likely to break the pattern, since the four in the base so far are
all Sunni traditionalists of one sort or another and the silence they share may
be a school effect rather than a tradition-wide one — which is the same shape of
objection this entry raised about genre, and it is not yet answered.

### Appended 2026-09-04 10:00Z: the school objection is closed, and the free list is nine deep

**THE MU'TAZILI TEST WAS RUN AND CAME OUT THE SAME WAY.** al-Zamakhshari's
*al-Kashshaf* is on tafsir.app under `kashaf`, both verses on the first request,
and it is captured in full at
`raw/202609041000-zamakhshari-al-kashshaf-3-64-and-29-46-arabic.txt`. He does not
gloss `وإلهنا وإلهكم واحد` — his comment on 29:46 stops one clause short of it,
and neither `معبود` nor `واحد` occurs anywhere in it, on tafsir.app or on the
independent quranpedia.net copy. So the "it may be a school effect" objection
this entry raised against the genre finding fails in its turn, and both
explanations the base generated for the silence are now spent (202609041010, and
amendments on 202609040820 and 202609040915).

Two further findings came with it, and the second is the more valuable:
- He is the only commentator in this base who says the common word is undisputed
  across the Qur'an, the Torah and the Gospel — and he defines that word, in the
  next sentence, as a summons to stop saying the Messiah is the son of God
  (202609041015). The base's strongest classical statement of common ground and
  its sharpest summons are the same paragraph.
- At Q 3:67 he offers `أو أراد بالمشركين اليهود والنصارى` as a possible sense,
  which is the first place in this base where a classical commentator extends
  *mushrikun* to the People of the Book (202609041020). Item (4) of this entry
  now has two independent tafsir witnesses; the *fiqh* is still untried, and
  that is still where a ruling would live.

**WHAT IS LEFT ON THE FREE LIST, AND WHY IT IS NOW LOWER VALUE.** Nine of the ten
classical commentaries named above are still uncaptured — Ibn 'Ashur, Abu
Hayyan, al-Alusi, al-Baydawi, al-Nasafi, al-Mawardi, Ibn al-Jawzi, al-Tha'labi,
Ibn 'Atiyya — and each is one request. But the argument that made Zamakhshari
worth a cycle does not transfer to them: he was the school test, and the school
test is now spent. A tenth commentator agreeing adds a tally mark. What would
still change the base's position is a commentator who *does* gloss the clause,
and the cheapest places left to look for one are outside this list entirely —
the Shi'i commentaries (al-Tusi's *Tibyan*, al-Tabrisi's *Majma' al-bayan*),
which no host checked so far carries and which belong to neither family the base
has now ruled out.

**Unchanged and still open from the entry above:** Tantawi still stands on one
witness and still needs a host that is not tafsir.app or quran.ksu.edu.sa; the
translation debt is now EIGHT sources deep and the Ibn Kathir calibration
argument for paying it once is unchanged and still right; the juristic
*mushrikun* literature is untried.

### Appended 2026-09-04 11:30Z: the Shi'i lead paid, item (2) is closed, and a result was reversed

**THE SHI'I TEST WAS RUN AND CAME OUT THE OTHER WAY — the first time in this
cluster that a test did.** The entry above named the Shi'i commentaries as the
cheapest place left to find a commentator who *does* gloss the clause, and said
"no host checked so far carries" them. A host does: **altafsir.com**, published
by the Royal Aal al-Bayt Institute (Amman). al-Tusi's *al-Tibyan* (d. 460) and
al-Tabrisi's *Majma' al-bayan* (d. 548) both gloss `وإلهنا وإلهكم واحد`, in the
same three words — `لا شريك له`. Captured at
`raw/202609041100-…` and `raw/202609041105-…`.

So the classical silence is a fact about the SUNNI commentaries this base
sampled, and the school explanation the 10:00Z cycle rejected is right at a
boundary that cycle could not test (Sunni/Shi'i, not Mu'tazili/Ash'ari). New
notes 202609041130, 202609041135, 202609041140; 202609040820, 202609040915 and
202609041010 amended in place. Nothing is withdrawn — each earlier result holds
inside the sample it was drawn from — but the generalisation to "the tradition"
fails, and the sampling frame that made it look safe was invisible because every
source in it shared a property nobody had written down.

**The result that tightens.** The Shi'i gloss is `لا شريك له`, NOT al-Tabari's
`معبود`. So `معبود` is now absent from ten commentaries across five centuries,
three schools and both branches, and of the six commentaries that gloss the
clause, five read it as *tawhid*. 202609040825 called that the "later"
tradition's reading, drawn from two modern commentaries; it is eleventh-century.
Al-Tabari's identification is held by exactly one commentator out of eleven.

**ITEM (2) IS CLOSED. Tantawi has his independent host — two of them.**
altafsir.com carries *al-Wasit* at `tTafsirNo=57`, and **quranpedia.net carries
him as book 321** (the base had been using quranpedia all along without noticing
he was on it). Verbatim match on `لا شريك له لا فى ذاته ولا فى صفاته`, differing
only in the `فى`/`في` variant. Captured at `raw/202609041110-…`; notes
202609041125 and the amendment on 202609040825.
*And the cross-check corrects this base:* item (2) above records that his lemma
"drops `وإلهنا`". It does not. Both hosts carry the full lemma
`وَإِلَـٰهُنَا وَإِلَـٰهُكُمْ وَاحِد`; the truncation belonged to the quran.com
resource-93 copy. Second time in three cycles that a single host's rendering of
this cluster turned out to be the host's and not the author's.

**ITEM (3), THE TRANSLATION DEBT, IS NOW ELEVEN SOURCES DEEP.** Unpaid again.
The argument in the original entry — pay it once, on Ibn Kathir, because he alone
has published English translations — is unchanged, still right, and now carries
three more sources' worth of exposure than when it was written.

**ITEM (4) HAS AN ACCESS ROUTE AT LAST, AND IT WAS ON THE ENDPOINT ALL ALONG.**
The entry above says "no access route has been tried for it yet" for the
juristic *mushrikun* literature. tafsir.app's own resource list — the one the
09:00Z cycle extracted — carries the *Ahkam al-Qur'an* genre, which is exactly
where a ruling would live: `aljasas` (al-Jassas d. 370, Hanafi),
`ilkia-alharrasee` (Ilkiya al-Harrasi d. 504, Shafi'i), `ahkam-ibn-alarabee`
(Ibn al-'Arabi d. 543, Maliki), `ahkam-altarayfi` (modern). altafsir.com adds
al-Sabuni's *Tafsir ayat al-ahkam*. Three schools of law, one request each, same
verses. **This is the highest-value untried thing in this cluster** and it is now
a known-cheap fetch rather than an open access question.

**WHAT ELSE THE NEW HOST OPENS.** altafsir.com indexes by *madhhab* and carries
shelves this base has never touched: Twelver Shi'i (`tMadhNo=4`: al-Qummi,
al-Tabataba'i's *al-Mizan* `56`, al-Fayd al-Kashani's *al-Safi* `41`, al-Bahrani's
*al-Burhan* `110`, Sadr al-Muta'allihin `40`), Zaydi (`5`), Ibadi (`6`: al-Hawari,
Atfayyish), Sufi (`3`: al-Tustari, al-Sulami, al-Qushayri, Ibn 'Arabi), and
al-Maturidi's *Ta'wilat ahl al-sunna* (`94`) — the one major classical
theological school this base has still not sampled on these verses, and the
natural next test now that Mu'tazili and Imami are both in.

**WHAT THIS ENTRY STILL LEAVES OPEN.** The two Shi'i captures stand on ONE host
(eight rungs tried, all recorded in the capture headers). The positive
quotations are safe on one institutional host; the NEGATIVE taken from them —
that `معبود` does not occur — is not, and wants a second host before anything is
built on it. Nothing in the notes currently rests on it that would fall.

### Appended 2026-09-04 13:00Z: item (4) is answered from fiqh, and it took a different verse

**THE JURISTIC QUESTION IS NO LONGER UNTRIED.** It was answered, but not on the
verses this entry assumed. Q 3:64 and Q 29:46 are not verses that carry a
ruling, so the *ahkam* literature has little to say on them; the place the law is
actually forced to fix the extension of `المشركون` is **Q 2:221**, the marriage
prohibition. Captured this cycle from al-Qurtubi (the classical *ahkam* tafsir)
and al-Sabuni (a modern *ayat al-ahkam* work), and the result is the thing this
entry said would have to exist if anyone had resolved the tension: the tradition
does register it, as a disputed question about a word's extension, with the
majority holding that the Qur'an's own conjunction of `أهل الكتاب` and
`المشركين` at Q 2:105 and Q 98:1 keeps the two apart. See 202609041320,
202609041325 and 202609041330.

So the generalisable lesson for this cluster, and it is worth more than the
finding: **the silence the commentary sweep found was a fact about those two
verses, not about the tradition.** Eight cycles read eleven commentators on the
same pair and found the same silence; one cycle changed the verse and found the
question litigated by name across schools. When a sweep keeps returning the same
absence, the next move is a different text, not another commentator.

**The classical *Ahkam al-Qur'an* works named above are still untried and are
still worth having.** al-Jassas (Hanafi), Ilkiya al-Harrasi (Shafi'i) and Ibn
al-'Arabi (Maliki) are on tafsir.app by the slugs recorded above; altafsir.com
carries none of them, confirmed this cycle against the full 85-entry catalogue.
Q 2:221 is now the verse to ask them for, and each would be a school-specific
witness to the same dispute — which is what would replace al-Sabuni's word
"majority" with something this base has actually counted.

**Item (3), the translation debt, is unpaid again** and this cycle added two more
captures to it. The argument for paying it once on Ibn Kathir is unchanged.

## 2026-09-04 — Tooling, HIGH: the Arabic normaliser used for the mechanical quotation checks can swallow the letters it is supposed to keep

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run

Filed by the 2026-09-04 09:00Z cycle, against its own work.

**The defect.** The normaliser this cycle first used to strip Arabic diacritics
before substring-matching quotations against captures was built on the character
class `[ؐ-ًؚ-ٰٟۖ-ۭـ]`. Written out, its first range runs U+0610 to U+064B, which
contains the entire Arabic letter block U+0621-U+064A. The class therefore
deletes letters, not just marks. Depending on what else the normaliser does to
the needle and the haystack, the result is either a match count of zero for
strings that are present, or a match on text that has been reduced to
punctuation — and both look like ordinary results.

**How it surfaced.** A passage visible by eye in both texts reported zero hits.
The check that caught it was cheap and should be standard: normalise a known
short string and print it. `norm('ضاهوهم')` returned the empty string.

**What was done here.** Every mechanical check in this cycle was re-run with a
normaliser that strips marks by explicit code point (U+064B-U+0652, U+0653-U+0655,
U+0670, U+06D6-U+06ED, U+0640) and keeps U+0621-U+064A. The substantive results
did not change — the `معبود` absence, and every cross-host quotation match, hold
under the correct normaliser — but they were not trustworthy until re-run, and
the corrected run is what the notes rest on.

**The previous cycles' results were re-checked, and they hold.** The 07:00Z and
08:00Z cycles logged their mechanical checking in the same words ("diacritics,
tatweel, alef/ya/ta-marbuta and punctuation normalised away"), and their code is
not preserved, so whether they used this defective idiom cannot be established
by inspection — only by re-running. That was done here, under the corrected
normaliser, against the captures already in `raw/`, with both controls in the
same run:

    positive control  norm('معبود') -> 'معبود'   (the needle survives normalisation)
    al-Tabari         `معبود` in the 29:46 section:  3   <- the word IS found where it is
    al-Qurtubi                                        0
    Ibn Kathir                                        0
    al-Baghawi                                        0
    al-Sa'di                                          0
    al-Muyassar                                       0
    negative-side control `واحد` in each 29:46 section: 6, 1, 3, 4, 2, 1
                                                      (every text is being read)

So the load-bearing absence those cycles established is confirmed, and by a tool
whose behaviour on a known input is now on the record. What is NOT re-checked is
their cross-host quotation matching, because those host copies were not kept;
re-running it means re-fetching, and it is worth doing next time any of those
notes is touched rather than as its own errand.

**The general rule this suggests, for whoever fixes it.** A normalisation
routine used to establish an absence must be tested on a positive control (a
string known to be in the text) and on a negative control (a string known not to
be) in the same run, and the controls belong in the log line, not in the head of
whoever ran it.

### Appended 2026-09-04 10:00Z: the rule was followed on its first outing, and it earned its keep

The 10:00Z cycle rested a negative claim on Arabic string counts and followed
this entry's rule without being asked twice: marks stripped by explicit code
point (U+064B–U+0655, U+0670, U+06D6–U+06ED, U+0640), the letter block kept, and
the controls run in the same pass and written into the capture header rather than
into anyone's memory —

    norm('معبود')  -> 'معبود'      (needle survives)
    norm('ضاهوهم') -> 'ضاهوهم'     (the string that exposed the defective class)
    `الذمة` in the independent host's 29:46 section -> 2   (the section is read)
    `واحد` in the same commentator's 3:64 comment   -> 2   (the tool can see the word)

The last of those is the one this entry did not think to ask for and should:
when the absent string is a common word, the cheapest proof that its absence is
real is to count it somewhere it IS expected, in the same text by the same
author. That control, not the positive control on the needle, is what makes a
zero publishable. Suggested for whoever writes the rule into a skill.

### Appended 2026-09-04 15:00Z: the rule caught a real error this cycle, and the error was the run's, not the source's

Twenty-nine quotations checked against one capture, controls in the same pass:
`norm('المشركات') -> 'المشركات'` (needle survives), `أهل الكتاب` counted at 30 in
the Q 5:5 section (the common-word control this entry asked for), `الزيدية` at 0
in both sections (negative control). Twenty-eight hit on the first attempt.

**The one MISS is the point.** A phrase about Q 5:5 being cast in the register of
favour — `مورد الامتنان والتخفيف` — was drafted against the Q 5:5 section and
returned zero. It is in the source, in the Q 2:221 section, phrased
`واردة مورد الامتنان والتخفيف`; the Q 5:5 section says the same thing as
`واقعة موقع الامتنان والتخفيف`. So the check caught a *drafting* error — a real
sentence attributed to the wrong section — rather than a hallucination, and the
fix was to quote both sections' wording rather than to drop the point.

Worth adding to the rule when someone writes it into a skill: the checks earn
their keep on attribution errors, not only on invented quotations, and a MISS is
therefore a prompt to search the *other* sections of the same capture before
concluding anything about the source. Cheap, and it turned a loss into a better
paragraph twice this cycle.

### Appended 2026-09-04 11:30Z: the rule generalises, and this cycle found two more ways to manufacture a false absence — one of them its own

The 11:00Z cycle followed this entry's rule (marks by explicit code point,
letter block kept, positive and negative-side controls in the same pass, written
into the capture header rather than into anyone's memory). It also hit the same
FAILURE MODE twice by routes that have nothing to do with normalisation, which
suggests the rule this entry states is a special case of a more general one.

**(A) A PAGINATED HOST TRUNCATES SILENTLY.** altafsir.com splits a commentary
section across `&Page=N` and serves a complete-looking page either way. The gloss
this cycle went looking for is on page 1 for al-Tusi and on page 2 for al-Tabrisi
and for Tantawi. A first-page-only read — which is what a naive fetch does —
would have reported two of the three commentaries silent about the clause, and
the reported silence would have looked exactly like the genuine Sunni silence
this base spent four cycles establishing. It was avoided by fetching from Page=1
until the `التالي` control was absent AND a page's body repeated one already
seen, and both stop conditions are recorded per section in the capture headers.

**(B) FILTERING SOURCE TEXT BY LENGTH DELETES SHORT SENTENCES.** This cycle's own
first extraction dropped every line under 60 characters as site chrome. That is a
length heuristic standing in for a content judgement, and it silently deleted a
real al-Tusi sentence — `فان قيل: لم استثنى الذين ظلموا؟ وكلهم ظالم لنفسه بكفره!`
(55 characters), one of the more interesting things he says on the verse.
Length is a proxy for chrome that fails exactly on short declarative sentences,
which is where authors put their sharpest claims. The extraction was rebuilt to
remove chrome by what it IS (block/inline tag classes, plus lines recurring
across three or more independently fetched sections) rather than by how long it
is, and every count was re-run. The counts did not change — the defect cost one
sentence and no result — but they were not trustworthy until re-run.

**What caught (B), and it is the transferable part.** Not the controls this entry
prescribes; those all passed. What caught it was a habit worth writing down on
its own: **every Arabic quotation intended for a note was substring-matched
against its capture BEFORE the note was written.** Seventeen matched and one did
not, and the one that did not was the tool's fault rather than the transcription's.
Eighteen of eighteen verify under the rebuilt extraction.

**The general rule this suggests, superseding the narrower one above.** A claim
that a text does NOT say something is a claim about a text you must first prove
you have IN FULL and are reading CORRECTLY. Normalisation is one of at least
three places that quietly fails; pagination and chrome-filtering are two more,
and there will be others. So the controls belong on the whole pipeline, not on
the normaliser: (i) the needle survives normalisation; (ii) a string known to be
present IS found, in the same text by the same author, in the same pass;
(iii) the section was read to its END, by a stated stop condition; (iv) nothing
was dropped from the served text by any rule that is not about what the text IS.
Suggested for whoever writes this into a skill, in place of the narrower rule.

### Appended 2026-09-04 12:00Z: a fourth way to manufacture a false absence, and it is the one that looks most like success

The 12:00Z cycle followed the four-part rule stated above (needle survives
normalisation; a string known present is found in the same author in the same
pass; the section read to its END by a stated stop condition; nothing dropped by
a rule that is not about what the text IS) and rested a negative on it. Two
things came out of the run that the rule as written does not yet cover.

**(C) A HOST THAT ROUTES THE RESOURCE AND SERVES NOTHING.** Looking for a second
host for al-Maturidi, tafsir.app returned HTTP 200 on `/maturidi/29/46` and a
150 KB page that canonicalises to itself — so by every check a fetch normally
makes, the source was found. It was not. The site's own data endpoint returns an
EMPTY body for this commentator at every verse tried, with controls in the same
pass proving the endpoint works:

    get.php?src=maturidi&s=29&a=46 -> 0      get.php?src=tabari&s=29&a=46  -> 6754
    get.php?src=maturidi&s=3&a=64  -> 0      get.php?src=qurtubi&s=3&a=64  -> 4907
    get.php?src=maturidi&s=1&a=1   -> 0

This is worse than a 404 in exactly the way this entry keeps finding things to be
worse: it looks like a result. A cycle that had checked "does the host have it?"
by status code and page size would have recorded a second host it does not have,
and — if it had then diffed the empty text against the altafsir capture — would
have "confirmed" any absence you like. The rule this suggests, as a fifth clause:
**(v) a host counts as a second source only if it returns TEXT you can quote, and
a control resource fetched the same way returns text too.** Status codes and page
sizes are properties of the application, not of the corpus.

**(D) CHROME REMOVAL BY CROSS-SECTION FREQUENCY LEAVES THE NON-OVERLAP BEHIND.**
The extraction removes a line occurring in three or more independently fetched
sections. altafsir.com's ayah dropdown is a `<select>` whose options are the
verse numbers of the sura, so the sections compared shared options 1-69 (sura 29
has 69 verses) and the Q 3:64 body kept `70`…`200` (sura 3 has 200) as apparent
content. Nothing was lost and no count changed, because the fix was to remove
`<script>`, `<style>` and `<select>` whole before anything else — by tag class,
which is what the text IS, not by length, which clause (iv) already forbids. The
transferable part is that clause (iv) is not self-executing: a frequency filter
IS a rule about what the text is only as far as the sections compared vary.
Where they partly overlap, the non-overlapping tail survives looking like prose.

### Appended 2026-09-04 13:00Z: (E) an exact-match check on hand-typed Arabic reports false MISSES, and the direction of that error is the safe one

The 13:00Z cycle ran its quotation check twice. The first pass compared literal
strings typed into the checker against the captures and reported two of
seventeen as absent — `ولم يتناول العمومُ قطُّ الكتابياتِ` and
`كان رجلاً متوقِّفاً`. Both are in the capture, verbatim, and both **display
identically** to what was typed; the strings differ by characters with no glyph
(the class this entry's defect (A) is about, arriving from the other side). A
diacritic-stripping locate-only search found each one immediately, and the exact
span was then read back out of the file rather than retyped.

Two things worth adding to this entry's rules.

**(vi) Never hand-type the needle.** The second pass extracted every
backtick-quoted Arabic span from the notes themselves and searched the captures
for it, which is the check that is actually wanted — it verifies what the notes
say, not what a checker author remembered — and it came back 40 of 41, the one
miss being a clause quoted from a *different, earlier* capture. A checker fed
hand-typed strings tests the typing.

**(vii) Normalise to LOCATE, never to COMPARE, and quote the raw bytes.** This is
the clause that reconciles this entry's defect (A) with the practice above.
Stripping combining marks is exactly the operation (A) warns can swallow
letters — so it is safe only where a false *positive* costs nothing, which is
finding a span. Once found, the text quoted into a note must be sliced out of the
capture, never re-keyed and never taken from the normalised form.

**And the direction of the error is worth naming, because it is the good one.**
An exact-match check on hand-typed Arabic fails toward MISS: it reports a
quotation as unfound when it is present. It cannot report a fabricated quotation
as present. Defect (A) runs the other way and that is why (A) is the dangerous
one. A cycle that sees a MISS should suspect its own typing before it suspects
the capture — but it must still look, every time, because the same symptom is
what a genuinely fabricated quotation would produce.

## 2026-09-04 — Access, HIGH VALUE: altafsir.com is a madhhab-indexed tafsir host and it opens most of what this cluster still wants

- **status:** in-progress      <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run

Filed by the 2026-09-04 11:00Z cycle so a later run spends its turns reading
rather than finding. This is the first host in this base's experience that
carries anything but Sunni tafsir, and it was found only because the Shi'i
commentaries had to be found somewhere.

**Route.** `https://www.altafsir.com/Tafasir.asp?tMadhNo=<M>&tTafsirNo=<T>&tSoraNo=<S>&tAyahNo=<A>&tDisplay=yes&Page=<N>&Size=1&LanguageId=1`

**Three things that will bite anyone who does not know them.**
1. **Encoding is windows-1256, not UTF-8**, and the Arabic arrives as numeric
   HTML entities (`&#1649;`-style). Decode as cp1256, then `html.unescape`.
   Skipping either produces mojibake that looks like a fetch failure.
2. **Sections are PAGINATED by `&Page=N`.** Read to the end or you will
   manufacture a false absence — see the normaliser entry above.
   ⚠ **THIS TRAP WAS WRITTEN WRONG AND COST TWO CAPTURES. Corrected 2026-09-04
   14:20Z; the entry at the bottom of this file has the audit.** It used to say
   "a page with a successor carries a `التالي` control calling
   `InnerLink_onchange`". `التالي` is rendered on **page 1 only**; interior
   pages render the same control with the English alt `Next`; and the control is
   served **indefinitely**, on empty pages past the end of a section too. So
   testing for `التالي` stops every section at two pages and testing for either
   alt never stops at all. **Neither control is an exhaustion signal.** Use the
   text: every page of a section reprints that section's verse as one long line,
   and a page carrying commentary carries more than that one line. Page until a
   page comes back with the verse alone, then fetch two more and record them, so
   one empty page inside a section cannot end the read early.
3. **Block vs inline tags matter.** The site wraps lemmas per word in `<font>`;
   convert block tags to newlines but strip inline tags to nothing, or `{ }`
   lemma braces end up on lines of their own.

**The catalogue, read off the page's own selectors: 11 madhhab groups, 85
commentaries.** `tMadhNo`: 1 أمهات, 2 أهل السنة, 3 السنة الصوفية, 10 السلفية,
9 ميسرة, **4 الشيعة الإثنى عشرية**, **5 الزيدية**, **6 الاباضية**, 7 حديثة,
8 مختصرة. Confirmed working this cycle: 39 al-Tusi *al-Tibyan*, 3 al-Tabrisi
*Majma' al-bayan*, 57 Tantawi *al-Wasit*.

**What is now one request away and has never been touched by this base:**
al-Tabataba'i *al-Mizan* (56), al-Qummi (38), al-Fayd al-Kashani *al-Safi* (41),
al-Bahrani *al-Burhan* (110), Sadr al-Muta'allihin (40), al-Habari (44), Furat
al-Kufi (45); Zaydi — Zayd b. 'Ali (89), al-A'qam (47); Ibadi — al-Hawari (48),
Atfayyish (49, 50), al-Khalili (51); Sufi — al-Tustari (29), al-Sulami (30),
al-Qushayri (31), al-Baqli (32), Ibn 'Arabi (33), Ibn 'Ajiba (37);
**al-Maturidi *Ta'wilat ahl al-sunna* (94)**, which is the one major classical
theological school this base has not sampled and the natural next test after
Mu'tazili (done) and Imami (done); al-Sabuni *Tafsir ayat al-ahkam* (85), which
speaks to the juristic *mushrikun* question; al-Sha'rawi (76), Rashid Rida's
*al-Manar* (103).

**What it does NOT solve.** It is one host. No second host for al-Tusi or
al-Tabrisi was found from this environment; eight rungs were tried and each
failure mode is written into the capture headers (tafsir.app, quranpedia.net and
quran.ksu.edu.sa proven ABSENT from their own resource lists; al-maktaba.org 403;
shiaonlinelibrary.com and ar.lib.eshia.ir no connection; shamela.ws and
hodaalquran.com reachable but not verse-indexed). So NEGATIVE claims from
altafsir-only captures are not yet safe. Specifically open: **confirm on a second
host that `معبود` does not occur in al-Tusi's or al-Tabrisi's comment on Q 29:46.**
Nothing currently rests on that absence in a way that would fall, but it is
stated in two literature notes and in 202609041135's tally of ten.

### Appended 2026-09-04 12:00Z: the entry was consumed by the next cycle, and it paid

The 12:00Z cycle read this entry, went straight to `tMadhNo=2&tTafsirNo=94` and
captured al-Maturidi's *Ta'wilat ahl al-sunna* on Q 3:64 and Q 29:46 with no
rediscovery cost at all. Everything this entry warned about was needed and was
right: the cp1256 decode, the numeric entities, the `&Page=N` pagination (Q 29:46
runs to two pages; Q 3:64 to one) and the block-versus-inline tag distinction.
This is the first time in this base's experience that an access entry filed by
one cycle was spent by the next as written, and it is the argument for filing
them at this level of detail. Status moved `new` -> `in-progress`: most of the
list below is still untouched.

**One thing to add to the three traps, found the hard way.** The site's ayah
dropdown is a `<select>` whose options are the verse numbers of the sura. If you
convert `<option>` to a newline like any other block tag, a 200-verse sura puts
200 numeric lines into your body — and if you then remove chrome by
cross-section frequency, the overlap with a shorter sura is removed and the tail
is NOT, so the body arrives carrying `70`, `71`, … `200` looking like content.
The fix that matters is not "drop short lines" (the standing rule against length
filters exists for good reason); it is to remove `<script>`, `<style>` and
`<select>` WHOLE, contents included, before anything else, because they are
machinery rather than text.

**What was crossed off:** al-Maturidi (94) — the item this entry flagged as one
of the two that would actually move the inquiry. **Still one request away and
untouched:** every Shi'i, Zaydi, Ibadi and Sufi work listed above, al-Sha'rawi
(76) and *al-Manar* (103).

**Still open, and now more urgent than when this entry was filed:** the
*Ahkam al-Qur'an* genre. It is the other of the two items named above, it is
where the juristic *mushrikun* question actually lives, and inquiry 202609032122
has wanted it since the first commentary sweep. Note that the Sunni catalogue
(`tMadhNo=2`) read off the page's own selector does NOT contain al-Jassas, Ilkiya
al-Harrasi or Ibn al-'Arabi; al-Sabuni's *Tafsir ayat al-ahkam* (85) is filed
under a different madhhab group and was not tried this cycle. Whoever takes this
should dump the Tafsir selector for each `tMadhNo` in turn rather than assuming
the group.

**New, and specific: second-host confirmation for al-Maturidi.** Priority
medium. The negative claim in permanent 202609041210 — that he does not gloss
`وإلهنا وإلهكم واحد` — rests on altafsir.com alone. Three rungs failed this
cycle (recorded in the capture header and in the entry below). What would close
it: any independent copy of the *Ta'wilat*, printed-edition or digital, checked
at Q 29:46 for `معبود` and for a gloss of the clause. The internal evidence is
unusually good — he elides the clause twice inside quotations he is actively
using — so this is confirmation rather than rescue.

### Appended 2026-09-04 13:00Z: the *ahkam* item is spent, the catalogue is written down, and one of the three traps is wrong as filed

**THE AHKAM GENRE IS IN THE BASE.** This entry's "still open, and now more
urgent" item was the *Ahkam al-Qur'an* literature and the juristic *mushrikun*
question. Both are now captured, on Q 2:221 — the marriage verse, which is where
the law is actually forced to say who the word `المشركات` covers, and which no
previous cycle had identified as the place to look:
`raw/202609041300-qurtubi-al-jami-li-ahkam-al-quran-2-221-arabic.txt` (11 pages)
and `raw/202609041305-sabuni-tafsir-ayat-al-ahkam-2-221-arabic.txt` (4 pages).
Three permanent notes came out of it (202609041320, 202609041325, 202609041330).

**THE INSTRUCTION IN THIS ENTRY WAS RIGHT AND IT PAID AGAIN.** "Dump the Tafsir
selector for each `tMadhNo` in turn rather than assuming the group" — done, and
it immediately explained the earlier confusion. **al-Qurtubi's *al-Jami'
li-ahkam al-Qur'an* is filed under `tMadhNo=1` (امهات التفاسير), not under the
Sunni group**, which is why a survey of `tMadhNo=2` concluded the *ahkam* genre
was absent from the host. The full catalogue, read off the page's own selectors,
is 85 commentaries across 10 populated groups (`tMadhNo=11` is empty):

- **1 امهات التفاسير:** 1 al-Tabari, 2 al-Zamakhshari, **4 al-Razi *Mafatih
  al-ghayb***, **5 al-Qurtubi *al-Jami' li-ahkam al-Qur'an***, 6 al-Baydawi,
  7 Ibn Kathir, 8 al-Jalalayn, 9 al-Shawkani.
- **2 أهل السنة:** 10 al-Fayruzabadi, 11 al-Samarqandi, 12 al-Mawardi,
  13 al-Baghawi, 14 Ibn 'Atiyya, 15 Ibn al-Jawzi, 16 Ibn 'Abd al-Salam,
  17 al-Nasafi, 18 al-Khazin, 19 Abu Hayyan, 20 Ibn 'Arafa, 22 al-Naysaburi,
  23 al-Tha'alibi, 24 Ibn 'Adil, 25 al-Biqa'i, 26 al-Suyuti *al-Durr
  al-manthur*, 28 Abu al-Su'ud, 67 Muqatil b. Sulayman, 75 al-Tha'labi,
  78 Mujahid, 79 al-Samin al-Halabi, 88 Ibn Juzayy, 91 al-Tabarani,
  94 al-Maturidi, 96 al-Sawi, 99 Sufyan al-Thawri, 100 al-Nasa'i,
  101 'Abd al-Razzaq al-San'ani, 102 al-Qasimi, 103 Rashid Rida *al-Manar*,
  104 Ibn Abi Zamanin, 105 al-Sijistani, 111 al-Rass'ani.
- **3 السنة الصوفية:** 29 al-Tustari, 30 al-Sulami, 31 al-Qushayri, 32 al-Baqli,
  33 Ibn 'Arabi, 36 Isma'il Haqqi, 37 Ibn 'Ajiba, 92 Makki b. Abi Talib,
  95 al-Jilani, 97 al-Najmiyya.
- **4 الشيعة الإثنى عشرية:** 3 al-Tabrisi, 38 al-Qummi, 39 al-Tusi,
  **56 al-Tabataba'i *al-Mizan***, 41 al-Fayd al-Kashani, 42 al-Junabidhi,
  40 Sadr al-Muta'allihin, 110 al-Bahrani.
- **5 الزيدية:** 44 al-Habari, 45 Furat al-Kufi, 47 al-A'qam, 89 Zayd b. 'Ali.
- **6 الاباضية:** 48 al-Hawari, 49 Atfayyish, 51 al-Khalili.
- **7 حديثة:** 52 al-Alusi, 54 Ibn 'Ashur, 55 al-Shinqiti, 76 al-Sha'rawi,
  57 Tantawi *al-Wasit*.
- **8 مختصرة:** 60 al-Wahidi, 90 al-Andalusi, 106 Ibn al-Jawzi *Tadhkirat
  al-arib*, 112 al-Kazaruni.
- **9 ميسرة:** 50 Atfayyish *Taysir*, 68 al-Qattan, 65 al-Muntakhab,
  71 As'ad Humad, **85 al-Sabuni *Tafsir ayat al-ahkam***, 84 and 83 al-Sabuni.
- **10 السلفية:** 66 Abu Bakr al-Jaza'iri, 98 al-Sa'di.

Two consequences worth stating. **(i) al-Razi IS on this host**, `tMadhNo=1`
`tTafsirNo=4`. The 08:00Z entry's "al-Razi is not on the endpoint at all" was
true of the quran.com API it was written about, and has been read since as a
statement about the sources generally; he was captured from tafsir.app by the
09:00Z cycle, so nothing rests on the error. **(ii) The host still carries no
al-Jassas, no Ilkiya al-Harrasi and no Ibn al-'Arabi *Ahkam al-Qur'an*, in any
group** — that was not a mis-read of the Sunni selector, it is a real absence,
and the classical Hanafi/Maliki *ahkam* works remain uncaptured.

**SUPERSEDED 2026-09-04 15:00Z — read the next paragraph, then discount it.** The
paragraph below names the numeric pager as "the correct detector". It is not: the
pager is a sliding window of eleven links, so its maximum read from page 1 is a
LOWER BOUND, exact only for sections of eleven pages or fewer. al-Tabataba'i on
Q 5:5 advertises 11 and runs to 14, and the three hidden pages are the
load-bearing ones. The detector that works is the TEXT — page while the page
carries a line other than the verse, then two probe pages — and the evidence is
in the final entry of this file. The paragraph below is kept because its account
of why the `التالي` rule failed is still right.

**ONE OF THE THREE TRAPS IS WRONG AS FILED, AND IT COST THIS CYCLE A PASS.**
Trap 2 says a page with a successor "carries a `التالي` control calling
`InnerLink_onchange`". The control exists — but `التالي` is the **`alt`
attribute of an `<img>`**, not text in the document. A reader that strips tags
before looking for it sees one page and stops. This cycle's first pass did
exactly that: al-Sabuni came back as a complete-looking 24-line section that was
one page of four, and al-Qurtubi as one page of eleven. **The correct detector is
the numeric pager in the RAW HTML**: every page emits
`InnerLink_onchange(<tafsir>,<page>,<size>)`, and the maximum of those page
numbers is the page count. Note that the two commentaries paginate very
differently on the same verse (4 vs 11), so "it looked like one page" is never
evidence of a short section. This is the same false-absence failure mode the
entry was written to prevent, arriving through a door the entry left open.

**Still one request away and untouched:** every Shi'i work above except al-Tusi
and al-Tabrisi — **al-Tabataba'i's *al-Mizan* (56) is the largest single gap** —
plus all Zaydi, Ibadi and Sufi works, al-Sha'rawi (76) and *al-Manar* (103).

## 2026-09-04 — Capture an Imami or Zaydi legal text on Q 2:221: the sectarian half of this cycle's finding rests on one Sunni author's report

- **status:** answered        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** run
- **answer (2026-09-04 16:00Z):** Both halves of the remaining ask are closed by
  two works of *fiqh* read off archive.org. **Zaydi:** *Sharh al-Azhar* (Ibn
  Miftah, d. 877/1472), *kitab al-nikah*, the *fasl* on who may not be married —
  reference 202609041600, literature 202609041610, permanent 202609041620. It
  teaches the prohibition as the school's rule and names `الهادي والقاسم` for the
  reading of Q 5:5 that carries it, which is the second and independent witness
  this entry wanted for an attribution that rested on *Tafsir al-A'qam* alone;
  and it records the school's split in its own terms, `الانتصار` and `والناصر` on
  the permitting side. **Imami:** *Jawahir al-kalam* (al-Najafi, d. 1266/1850) on
  al-Muhaqqiq's *Shara'i'*, the section on *al-kufr* — reference 202609041605,
  literature 202609041615, permanent 202609041625. The *matn* states the question
  as `روایتان`; the commentary calls permission `التحقيق`. Two further results
  neither this entry nor its predecessors anticipated: the same two Imams,
  al-Baqir and al-Sadiq, are transmitted on **both** sides, within a few lines of
  each other in the Imami capture (202609041630); and the argument from Qur'anic
  coupling that the base credited to al-Tabataba'i is in Imami *fiqh* a century
  earlier, with a jurist's test under it (202609041635).
- **2026-09-04 14:00Z: worked, and the entry's own recipe was followed exactly.**
  Four commentaries captured: al-Tusi (39) and al-Tabrisi (3) on `tMadhNo=4`, and
  — going beyond what this entry asked, because the Zaydi half turned out to be
  where the interest was — Zayd b. 'Ali's *Gharib al-Qur'an* (89) and *Tafsir
  al-A'qam* (47) on `tMadhNo=5`. Each on **Q 2:221 AND Q 5:5**, which is the one
  change worth passing on: al-Tusi states his position on Q 2:221 and then defers
  the argument to al-Ma'ida in so many words, so a Q 2:221-only capture would
  have taken the claim without its grounds — and the grounds are where the two
  Imami *naskh* reports sit. Results:
  [[the-imami-commentaries-claim-the-strict-reading-of-2-221-as-their-own-and-run-the-abrogation-backwards--202609041445]],
  [[the-some-zaydis-attribution-is-classical-and-shii-not-a-modern-sunni-summary--202609041450]],
  [[the-zaydi-tradition-is-split-on-2-221-so-the-qualifier-some-is-load-bearing--202609041455]].
  **The Imami half is closed.** Both commentators mark the strict position
  `عندنا` / `مذهبنا` rather than reporting it, and al-Tusi carries the inversion
  as *naskh* reports from al-Baqir and al-Sadiq. One correction to al-Sabuni that
  the entry could not have anticipated: what they forbid is `نكاح الدوام`, the
  permanent contract, while holding *mut'a* and concubinage with the same women
  permitted.
  **The Zaydi half came back split, which is a better answer than the one
  sought.** al-A'qam credits Yahya and al-Qasim with the strict reading of Q 5:5;
  Zayd b. 'Ali's glossary reads Q 2:221 the lenient way. So `بعض الزيدية` names a
  real division. And the attribution itself is old: al-Tabrisi writes that exact
  phrase in the sixth/twelfth century, so al-Sabuni is not its source.
  **Why this stays open rather than closing.** The entry asked for a *legal*
  text and got four *tafsirs*. No Imami or Zaydi *fiqh* work is in the base, and
  the content of the Yahya/al-Qasim attribution still rests on one witness
  (al-A'qam, five centuries later). Also still open and now sharper: **no host
  known to this base carries Zaydi tafsir except altafsir.com**, so there is no
  second-host route for either Zaydi capture, and the eight rungs recorded
  against Shi'i tafsir apply here unchanged.

- **2026-09-04 15:00Z: the entry's own named test was run, and it came back the
  other way.** This entry (as extended at 14:00Z) said "Al-Tabataba'i (56) would
  be the strongest". He was captured, on Q 2:221 (4 pages) and Q 5:5 (14 pages):
  `raw/202609041500-tabatabai-al-mizan-2-221-and-5-5-arabic.txt`, reference
  202609041500, literature 202609041505, permanent 202609041510 / 1515 / 1520.
  **He dissents.** `المشركات` in Q 2:221 does not reach the People of the Book —
  `قصر التحريم على المشركات والمشركين من الوثنيين دون أهل الكتاب` — and the
  abrogation claim is `فساد` in both directions, blocked on the chronology
  (al-Baqara first Medinan, al-Ma'ida last: `ولا معنى لنسخ السابق اللاحق`). He
  quotes his own school's *naskh* reports — al-Baqir via Zurara and al-'Ayyashi —
  and answers them with the same objection: `ولا يجوز تقدم الناسخ على المنسوخ`.
  **So the Imami half is SPLIT, exactly as the Zaydi half was**, and the base's
  "closed on the Imami half" has been retracted in 202609041325.
  **What survives, and it is the more interesting half.** The restriction on the
  permanent contract outlives the argument for it: al-Tabataba'i rebuilds it as
  *takhsis* (`مخصصاً متقدماً`) rather than *naskh*, and grounds the surviving
  *mut'a* permission in `وقد عمل بها الأصحاب`. Three Imami commentaries, three
  arguments, one rule.
  **What is still open, and it is now the ONLY thing this entry is waiting on.**
  No Imami or Zaydi *fiqh* text, in three cycles of trying — every Shi'i witness
  in the base is a *tafsir*, and al-Tabataba'i twice defers the operative rule to
  *fiqh* (`وللكلام تتمة تطلب من الفقه`). The Yahya/al-Qasim attribution also
  still rests on al-A'qam alone. Candidate next steps, in cost order: al-Bahrani
  (110) or al-Fayd al-Kashani (41) on the same two verses, both one request away
  on `tMadhNo=4`, as a fourth and fifth Imami reading; and, for the *fiqh* gap, a
  host search for al-Hilli's *Tadhkirat al-fuqaha'* or al-Muhaqqiq's *Shara'i'
  al-Islam* — neither is on altafsir.com, which carries *tafsir* only.

Filed by the 2026-09-04 13:00Z cycle, against its own note.

[[whether-the-people-of-the-book-are-mushrikun-is-a-disputed-question-of-law--202609041325]]
says that the Imamiyya and some Zaydis held the People of the Book to be
*mushrikun* and marriage to their women forbidden, inverting the abrogation so
that Q 2:221 cancels Q 5:5. That is a claim about two schools and this base's
only witness for it is **al-Sabuni**, a modern Sunni author, reporting them in
one clause (`وإلى هذا ذهب الإمامية، وبعض الزيدية`). Al-Qurtubi, who reports the
same three positions, does not mention either school. No Imami or Zaydi legal
text is in the base at all.

This matters more than a usual single-witness gap, because the finding it
supports is *interesting* precisely as a sectarian reversal: on the shared-God
clause the Shi'i commentaries are the ones that gloss it where the Sunni ones
pass over (202609041130), and here the Shi'i jurists are the stricter party. A
reversal argued from one Sunni author's one-clause attribution is exactly the
kind of claim that should not be allowed to harden.

**What would close it, and the route is already on file.** The catalogue in the
entry above puts eight Imami and four Zaydi commentaries one request away on
altafsir.com — `tMadhNo=4` and `tMadhNo=5` — and this cycle has proved the route
works on Q 2:221 specifically. **al-Tusi (39) and al-Tabrisi (3) on Q 2:221** are
the cheapest test: both are already reference notes in this base for other
verses, so a capture costs one fetch and no new bibliographic work. Al-Tabataba'i
(56) would be the strongest. Note that a *tafsir* is not a *fiqh* text and a
commentary's silence would not refute al-Sabuni; what would settle it is finding
the position stated, or finding the opposite stated.

## 2026-09-04 — Environment, HIGH: the container's cached skill is BEHIND the ref CI uses, and is missing two of the six gate scripts

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run
- **2026-09-04 16:00Z:** EIGHTH consecutive cycle to find it stale, same rev
  (7181e41) and the same 50-commit gap to `d986b16`. Fast-forwarded before any
  gate ran. Dependency state also identical to the 13:53Z and 14:53Z cycles:
  `pypdf` absent entirely, and `pip install -r requirements.txt` alone leaves
  `import pypdf` raising `PanicException` from Debian's broken `cryptography`
  41.0.7 — `pip install --ignore-installed cryptography` is what fixes it
  (probed before and after: pypdf 6.17.0 / cryptography 50.0.1). One detail the
  earlier entries do not record and that saves a cycle's confusion: the STALE
  `remote_cycle.sh` has no `refresh-skill` subcommand at all, so a run that tries
  the prompt's own step 1 first gets a usage error. `git -C /opt/zettel-skill
  merge --ff-only origin/main` is the recovery, after which `refresh-skill`
  exists and `start` reports `skill already current`.

Filed by the 2026-09-04 12:00Z cycle, which nearly ran a short gate sequence
without noticing.

**The facts.** The remote container ships the skill at `/opt/zettel-skill`,
symlinked into `~/.claude/skills/zettel-bootstrap`. Its checkout is at
`7181e41` (PR #4). The skill repository's `main` is at `d986b16` (PR #16), and
`.github/workflows/gates.yml` in THIS repo pins `ZETTEL_SKILL_REF: main`. So CI
runs gate code the container does not have. Concretely, `/opt/zettel-skill/scripts`
lacks `lint_skills.py`, `check_skill_sandbox.py`, `skill_review.py`,
`inquiries.py`, `query.py`, `capture.py`, `fetch_source.py`, `ingest_drops.py`
and `skill_trial.py`.

**Why that is dangerous rather than merely annoying.** A cycle that runs "the
gates" from the container's copy runs FOUR of the six checks CI runs, and both
missing ones are the ones a run cannot self-police: `lint_skills.py` and
`check_skill_sandbox.py` — the latter being the gate that enforces log.md and
skill-impact.md append-only and `raw/` immutable. Nothing warns you. The scripts
are simply absent, and a cycle that logs "gates: PASS" after running what it
has is telling the truth about what it ran and the wrong thing about what it
means. The previous five cycles logged `lint_skills: PASS` and
`check_skill_sandbox: PASS`, so they cannot have used the container's copy —
which means the cache changed under this schedule at some point on 2026-09-04
and no cycle noticed.

**What this cycle did instead, and it is the workaround to inherit.** Cloned the
skill repo fresh (`git clone --depth 1 https://github.com/nathanwdavis/auto-zettel-skill.git`)
into scratch and ran all six gates from that clone, which is exactly what CI
does. `/opt/zettel-skill` was not modified — the rule that a run never modifies
the skill's own repo covers `git pull` as much as an edit. All six passed.

**What would fix it properly, for a human.** Either re-run the environment's
setup script so the cache picks up `main`, or pin both sides deliberately: set
`ZETTEL_SKILL_REF` in `gates.yml` to the same tag the setup script installs, and
bump the pair as a release step. The remote-execution reference already warns
that the setup cache freezes the skill version; what it does not say is that the
content repo's CI pin and the container's cache are two independent versions
that can drift apart, and that the drift is invisible from inside a run.

**A smaller environment defect, same cycle, for whoever is in here anyway.**
`remote_cycle.sh start` died with exit 128 before doing any work, because the
fresh clone has no `refs/remotes/origin/HEAD` and the script computes the
default branch with `git symbolic-ref --short refs/remotes/origin/HEAD | sed …`
under `set -euo pipefail`. The failure message is empty; the trap fires and the
lock it had just claimed is released, so the cycle simply stops. Worked around
with `git remote set-head origin -a`. The fix in the script is one line: give
the substitution a fallback, since the very next line already defaults to
`main`.

### Appended 2026-09-04 13:00Z: still drifted, workaround inherited and it worked; the smaller defect is already fixed upstream

**The cache is unchanged and the entry is still live.** `/opt/zettel-skill`
(symlinked to `~/.claude/skills/zettel-bootstrap`) again ships only `SKILL.md`
plus a `scripts/` directory missing `lint_skills.py`, `check_skill_sandbox.py`,
`skill_review.py`, `inquiries.py`, `query.py`, `capture.py`, `fetch_source.py`,
`ingest_drops.py` and `skill_trial.py`. A cycle running "the gates" from it would
again run four of six and be told nothing.

**The workaround this entry told the next run to inherit was inherited, and it
cost about a minute.** `git clone --depth 1` of the skill repo into scratch; the
clone came up at `d986b16`, which is exactly the `main` that `gates.yml` pins, so
this cycle ran the same six checks CI runs. `/opt/zettel-skill` was not modified.
Recording that the handoff worked, for the same reason the altafsir access entry
records it: an entry that names the workaround concretely is spent for free by
the next run.

**The smaller defect is already fixed in `main` and needs no workaround.**
`remote_cycle.sh` at `d986b16` resolves the default branch with
`git ls-remote --symref origin HEAD`, falling back to `refs/remotes/origin/HEAD`
and then to `main`, each substitution guarded with `|| true` — and the code
carries a comment naming this exact P0. `start` ran clean on a fresh clone with
no `origin/HEAD` and no `git remote set-head` was needed. **So that half of this
entry can be closed by a human;** the cache-drift half is what keeps it open, and
it is a human fix (re-run the environment setup, or pin `ZETTEL_SKILL_REF` to the
tag the setup script installs and bump the pair as a release step).

### Appended 2026-09-04 15:00Z: seventh cycle, same rev, same gap — and the container ships a FULL checkout, so the sanctioned step 1 is enough

**Still drifted, still at `7181e41`, still 50 commits behind `origin/main`
(`d986b16`).** Seven cycles now: 2026-09-03T20:53Z, and 2026-09-04 at 04:53Z,
05:53Z, 09:52Z, 13:00Z, 13:53Z and this one. The number does not move because the
environment cache does not, which is what makes this a human fix and not a run
fix.

**One correction to the 13:00Z appendix, so the next run does not pay for the
wrong workaround.** That appendix says the cached tree "ships only `SKILL.md`
plus a `scripts/` directory missing" eight files, and prescribes a
`git clone --depth 1` into scratch. On this container — as on the 13:53Z one —
`/opt/zettel-skill` is a **full git checkout** with a working `origin`, so the
clone is unnecessary: `remote_cycle.sh refresh-skill`, which is the skill's own
sanctioned step 1, fast-forwards it in place, and `start` re-execs itself when it
does. Both descriptions are presumably true of different container images; the
cheap probe that tells you which you have is
`git -C /opt/zettel-skill rev-parse --short HEAD` — if it answers, refresh-skill
is enough, and only if it errors do you need the scratch clone.

**Dependencies drift with it, in a way `requirements.txt` alone does not fix.**
Same state as 13:53Z: `pypdf` absent entirely, and the Debian-packaged
`cryptography` 41.0.7 shadowing anything pip installs, so `import pypdf` raises
`pyo3_runtime.PanicException` and NOT an ImportError — it looks like a crash, not
a missing package. `pip install -r requirements.txt` does not clear it; `pip
install --ignore-installed cryptography` does (→ pypdf 6.17.0 / cryptography
50.0.1). Probe before and after with `python3 -c "import pypdf, cryptography"`;
that probe is what proves the fix, and it costs nothing.

## 2026-09-04 — Environment, NEW DEFECT: a squash-merged repo leaves a divergent local `main`, and `remote_cycle.sh start` correctly refuses to run

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **2026-09-04 16:00Z: recurred, and the recorded recovery is confirmed.** Same
  shape, worse numbers: local `main` at `e1d091a`, now **6 ahead / 74 behind**
  `origin/main`. This cycle checked the recovery was safe before running it
  rather than trusting the entry — `git rev-list --left-right --count
  HEAD...origin/main` returned `0 0`, so the session's working branch already
  contained everything, and the six divergent commits were confirmed by name as
  the 2026-08-31 genesis history that PR #1 squashed. `git branch -f main
  origin/main` then made `start` succeed on the first attempt, so the failed-run
  half of the original entry did not repeat. Two notes for whoever generalises
  this: the count grows every cycle, so the entry's "6 ahead / 79 behind" should
  be read as a shape and not a fingerprint; and running the recovery **before**
  `start` is better than after, because `start`'s own failure path releases the
  lock and costs a round trip.
- **asked_by:** run

Filed by the 2026-09-04 15:00Z cycle, against its own first attempt.

**What happened.** The first `remote_cycle.sh start` of this cycle failed:

    git pull -q --ff-only origin main
    fatal: Not possible to fast-forward, aborting.

`start` handled it correctly — the `ERR` trap fired, the lock it had just claimed
was released, and the error went to stderr — so nothing was stranded and the
lock was free for the retry. This is a report about a missing *recovery*, not
about a missing guard.

**Why it happens, and why it will happen again.** This container's clone carries
a local `main` at `e1d091a`, the six-commit genesis history of 2026-08-31
(`eea79d6` → `9d88312` → `05e00b7` → `987a0ce` → `b50bf2c` → `e1d091a`). That
history reached `origin/main` through PR #1, which was **squash-merged**. Squash
rewrites the hashes, so the local branch is not merely behind — it reads as
**6 ahead / 79 behind**, and `--ff-only` refuses it, correctly. Every fresh
container whose clone predates a squash merge on this repo will land in the same
state, and this repository squash-merges every maintenance PR.

**The fix, which is one line and was safe here.** The session's own checkout
branch was already at `origin/main`, so nothing was at risk:

    git -C <repo> checkout main && git reset --hard origin/main

`start` then succeeded. The reset discarded only history that `origin/main`
already contains in squashed form — which was **checked** (`git log --oneline
main ^origin/main` listed exactly the six genesis commits) rather than assumed.

**What would close this entry.** A `start` that, on a `--ff-only` failure,
distinguishes "diverged because the remote squash-merged us" (safe: hard-reset to
`origin/<default>`) from "diverged because someone has unpushed work here" (not
safe: stop and say so). The cheap discriminator is whether every local-only
commit is reachable from a merged PR, or more simply whether the working tree and
the run branch are clean and the local branch has no reflog entries from this
session. Until then a run that hits this should do the reset by hand, after
looking at `git log --oneline main ^origin/main`, and say in its report that it
did.

**Do not "fix" this by making the pull non-ff.** A merge or a rebase here would
manufacture a second copy of the genesis history on top of the real one, and the
first run to push from that branch would carry it into a PR.

## 2026-09-04 — Access, HIGH: the altafsir.com paging rule this base wrote down was wrong, it truncated two committed captures, and the trap it names is general

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run

Filed by the 2026-09-04 14:00Z cycle against its own predecessors, and against
the guidance those cycles left for it.

**What was wrong.** The 11:00Z access entry told later runs that on altafsir.com
"a page with a successor carries a `التالي` control". Three facts, none of which
that entry could have seen from a two-page section:

1. `التالي` is the alt text of the forward control **on page 1 only**. Interior
   pages render the same control with the English alt `Next`.
2. The forward control is served **indefinitely**. Page 40 of a three-page
   section still offers `Next`. So switching the test to "either alt" does not
   fix it; it replaces a read that stops too early with one that never stops.
3. What actually ends a section is the **text**. Every page of a section
   reprints that section's verse as one long line; a page with commentary
   carries more than that one line, and the pages past the end carry only it.

So the rule to inherit is: page while the page carries a line other than the
verse text, then fetch **two** further pages and record them in the capture
header, so that a single empty page inside a section cannot end the read early.
That is what the four captures taken this cycle did, and their headers show the
probes.

**What it cost, audited rather than guessed.** All six sections the 11:00Z and
12:00Z cycles captured were re-fetched to true exhaustion:

| capture | section | true pages | taken |
|---|---|---|---|
| `raw/202609041100-tusi-…` | Q 3:64 | 1 | 1 ✓ |
| `raw/202609041100-tusi-…` | Q 29:46 | 2 | 2 ✓ |
| `raw/202609041105-tabrisi-…` | Q 3:64 | 2 | 2 ✓ |
| `raw/202609041105-tabrisi-…` | Q 29:46 | **3** | 2 ✗ |
| `raw/202609041200-maturidi-…` | Q 3:64 | 1 | 1 ✓ |
| `raw/202609041200-maturidi-…` | Q 29:46 | **3** | 2 ✗ |

Two captures short by one page each, ~2.7k and ~1.7k characters. The missing
pages are now at
`raw/202609041420-recovered-third-pages-tabrisi-and-maturidi-29-46-arabic.txt` —
an addition, not an edit, since raw/ is immutable — and the two literature notes
concerned carry a dated correction paragraph.

**Nothing in the base falls, and that was checked rather than hoped.** Several
notes rest on negative counts from those captures: that `معبود` occurs nowhere
in these commentators' treatment of the verse, and that the shared-God clause is
passed over without gloss. Both were re-run over the **complete** sections.
`معبود` is 0 across all three pages of each and 0 on the recovered pages alone,
and neither recovered page returns to the clause — they comment on Q 29:49-50.
The claims are right; they were right by luck for six hours.

**Why this deserves a high priority even though nothing broke.** The 11:36Z
cycle already wrote the correct rule as a skill-smith candidate — "before
resting a claim on a served text, establish that the section was read to its
END — a paginated host truncates silently and produces the same false absence a
defective normaliser does". It then established the end using a signal that did
not mean what it appeared to mean. The lesson is one rung up from the rule: **an
exhaustion test must be made of the thing you are collecting, not of the
navigation offered alongside it.** A control that says "there is more" is the
site's claim; a page that has commentary on it is the evidence. This is the same
shape as the length-filter finding (a proxy that fails exactly where it matters)
and the whole-element-removal finding (chrome detected by frequency leaves the
non-overlapping tail). Three cycles, three versions of one mistake: trusting a
proxy for the content instead of the content.

**Concretely, for whoever is here next.** The corrected trap list is now in the
altafsir access entry above, so it does not need re-deriving. And two further
sections are known to be longer than any read so far assumed, if a cycle wants
them: al-Tabrisi on Q 112:1 runs to **eight** content pages, al-Maturidi on
Q 29:46 to three.

### Appended 2026-09-04 15:00Z: the SECOND detector this entry's predecessors trusted is also wrong, and the reason is a window of eleven

This entry corrected the `التالي` rule. It left standing the rule the 13:00Z
cycle wrote in the access entry above — "the correct detector is the numeric
pager in the RAW HTML: every page emits `InnerLink_onchange(<tafsir>,<page>,
<size>)`, and the maximum of those page numbers is the page count." That is
**also wrong**, and wrong in the most dangerous way available: it is exact inside
a range and silently short outside it.

**The mechanism, probed rather than inferred.** The pager renders at most eleven
links and slides forward one block at a time. On al-Tabataba'i's Q 5:5 section:

    on page  1: pager offers [2, 3, 4, 5, 6, 7, 8, 9, 10, 11]
    on page  5: pager offers [1, 2, 3, 4, 6, 7, 8, 9, 10, 11]
    on page 10: pager offers [1, 2, 3, 4, 5, 6, 7, 8, 9, 11]
    on page 11: pager offers [1, 10, 12, 13, 14]   <- the next block appears ONLY here
    on page 14: pager offers [1, 11, 12, 13]

So `max(InnerLink_onchange)` read from page 1 is a **lower bound**, exact for
sections of eleven pages or fewer and short for anything longer. That section
advertises 11 and runs to 14.

**What it would have cost this cycle.** Pages 12 and 13 — the two the pager hides
— are the ones carrying `أصحابنا`, the Imami *naskh* narrations from al-Baqir,
and al-Tabataba'i's answer to them. They are the entire reason the source was
sought. A run trusting the written rule would have taken the capture short
exactly where its value is, and would have had a complete-looking eleven-page
section to show for it.

**What it cost the base: nothing, and that was audited.** Only two committed
captures were taken under the pager rule, and both were re-fetched to content
exhaustion this cycle:

| capture | pager said | true pages | verdict |
|---|---|---|---|
| `raw/202609041300-qurtubi-…-2-221` | 11 | 11 | ✓ complete |
| `raw/202609041305-sabuni-…-2-221`  |  4 |  4 | ✓ complete |

Note *why* the rule survived being written: al-Qurtubi's section is exactly
eleven pages, the last length at which the window is still exact. It was
validated on the boundary case and on a case well inside it, and both passed.

**The rule to inherit, superseding both detectors.** Do not test the navigation.
Page while the page carries a line other than the verse text, then fetch two
further pages and record them in the capture header. That is the 14:00Z rule and
it is now confirmed a third time. The pager is still *useful* — as a lower bound
that tells you how many pages to expect — and it is never sufficient.

**And the generalisation, which is worth more than the altafsir fact.** A proxy
that is *unreliable* gets caught. A proxy that is *exact inside a window* does
not: it passes every test taken inside the window, and the person who writes it
down has usually only worked inside the window. So when a host offers a count,
a total, or a result set, find the mechanism's boundary — window size, page cap,
result limit — and test AT it and PAST it. Three cycles have now found three
versions of one mistake (a length filter, a frequency-based chrome filter, two
navigation controls); this is the fourth, and the first where the proxy was
right in every case anyone had checked.

## 2026-09-04 — Access, HIGH VALUE: archive.org opens Shi'i and Zaydi *fiqh* that no other host in this base's experience carries, and OCR text forces a quotation discipline this base did not have

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run

Filed by the 2026-09-04 16:00Z cycle, which closed a four-cycle-old entry with it.

**The route.** Full-text OCR of scanned Arabic print, downloaded complete in one
request, from `https://archive.org/download/<item>/<filename>_djvu.txt`. Find
items with the advanced-search API — `https://archive.org/advancedsearch.php`
with `q=title:("…") AND language:(Arabic)`, `fl[]=identifier`, `output=json` —
then read `https://archive.org/metadata/<item>` and look for files ending
`_djvu.txt`. **An item without a `_djvu.txt` has no usable full text**; two of the
five candidates this cycle probed (*al-Bahr al-zakhkhar*, `love_2_20160503`;
`1021612`) are PDF-only and were dropped on that test alone, in one request each.

**What it opened, with identifiers, so the next run does not re-search.**
- `1_20191217_20191217_1729` — *Sharh al-Azhar*, Ibn Miftah, **Zaydi *fiqh***,
  nine volumes each as its own `_djvu.txt`. Volume 4 is `النكاح والطلاق`.
- `BBib-Alex-09185` — *Jawahir al-kalam* vol. **30**, Imami *fiqh*: this is the
  volume with `الكفر` and marriage to a *kitabiyya*. Volume 29
  (`BBib-Alex-09183`) was probed first and is the wrong one — fosterage and
  marriage to slave women. The Bibliotheca Alexandrina set is incomplete;
  volumes 6, 7, 9, 18, 21-24, 27, 31, 33, 35 and 41 are absent from it.
- `AAlexandrina-127753` — *Tadhkirat al-fuqaha'* (al-'Allama al-Hilli), has a
  3.0 MB `_djvu.txt`. **Not yet read.** This is the cheapest next Imami *fiqh*
  witness if one is wanted.
- `20211211_20211211_1601` — *Shara'i' al-Islam* (Shirazi annotated), two
  volumes with text. **Neither contains *kitab al-nikah***; vol. 2 ends in
  *mukataba*. Do not re-probe it for marriage law.

**Four hosts that are dead from this environment, and the failure mode matters.**
`shiaonlinelibrary.com`, `lib.eshia.ir`, `noorlib.ir` and `ar.wikishia.net` all
fail **DNS resolution** — `Could not resolve host`, not a block page, not a
paywall, not a 403. `al-maktaba.org` returns 403. A search will keep surfacing
these four first because they are the obvious Shi'i-library hosts; going straight
to archive.org saves the round trip. Record them as unreachable-from-here rather
than absent from the web: the child skill's rung (e) distinction applies exactly.

**The discipline OCR forces, and this is the part worth generalising.** Every
capture this base held before today was clean digital text from a web host, so
"quote it exactly" was free. OCR of print is not clean, and the failure is
insidious: a quotation *feels* right while silently normalising `المادي` to
`الهادي`, or stitching two sentences that a footnote marker separates in the
print. Both happened in this cycle's first draft. The rule adopted, and it should
become house procedure:

1. Quote **exactly as the OCR has it**, damage included, and put the corrected
   reading in square brackets marked as the base's own.
2. Run the mechanical check against the capture's **excerpt body only**, not the
   whole file — the capture header contains Arabic the base itself wrote, and a
   naive check will match a quotation to the base's own prose.
3. Normalise whitespace **and invisible bidirectional marks** and nothing else.
   U+200F sits inside `وعن الصادق ‏ والباقر` in this cycle's Zaydi capture and
   defeats an exact match that a reader would call identical.
4. Treat a **stitch** as a defect, not a tidy-up. Where the print interrupts a
   sentence with a footnote block, mark the gap `[…]` and say what is in it.
5. Use a control that proves the damage claim rather than asserting it: the
   undamaged `الهادي` occurs **nowhere** in the Zaydi capture, which is what
   licenses quoting the name in its damaged form.

The check found **five real defects** in this cycle's draft after the notes were
written and read over — two stitched quotations, two silent normalisations, and
one wrong transcription (`والجهابذة` for the OCR's `والجحهابذة`). None was
visible on rereading. Fifty-eight quotations were verified verbatim once fixed.

**One rights question this route sharpens rather than answers.** These are
out-of-copyright texts in modern printings, so the base captured **sections**
(3.6k and 24.8k characters) rather than the volumes it had in hand, on the same
reasoning as the open entry about all-rights-reserved full texts in a public
repo. That reasoning has now been applied twice without a human ruling on it.

## 2026-09-04 — Tooling, HIGH: `verify_refs.py --offline` REWRITES verification records, so running it in a working tree silently downgrades evidence

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run

Filed by the 2026-09-04 16:00Z cycle, which did this to itself and caught it.

**What happened.** The cycle finished its gates and then ran
`verify_refs.py --repo . --offline --no-render` as a rehearsal of what CI does,
because `gates.yml` runs verify with `--offline` on purpose. The flag does not
mean "check without the network". It means "establish what you can from `raw/`
alone **and write that back**". Roughly twenty references that had
`method: raw-capture+openlibrary` or `raw-capture+crossref` with
`identifier_check: confirmed` came out as bare `method: raw-capture`, with the
`source` pointing at the local capture instead of the registry URL and the
confirmation deleted. It reports `74/74 verified` while doing it.

**Why no gate catches it.** `lint_citations` asks whether a claim traces to a
verified reference, and a `raw-capture`-verified reference is verified. The
downgrade is a loss of *evidence quality*, which nothing in the gate set
measures. All six gates were clean on the degraded tree. It was caught only by
reading the `git diff` of files the cycle had no reason to have touched.

**Why CI is fine and a working tree is not.** CI checks out a throwaway copy,
runs the offline verify against it, and commits nothing — which is exactly the
guarantee the design wants, since it re-checks the run's claims against what is
actually in `raw/`. The same command in a repository that will be committed
writes the weaker result into the record.

**Repair, if a later run finds this in a diff.** Re-run the live verifier,
`verify_refs.py --repo . --mailto <addr>`; it restores the richer methods and the
`identifier_check` values. Confirm with `git diff -U0 reference/ | grep '^-' |
grep -c 'identifier_check: confirmed'`, which should be 0.

**What to change, and this is the ask.** Two candidates, and a human should pick:
either give `--offline` a companion `--check-only`/`--dry-run` that reports
without writing (and have `gates.yml` use it, since CI never wants the write), or
have the writer refuse to *lower* an existing verification method — an offline
run could then confirm a `raw-capture` reference and leave a
`raw-capture+crossref` one alone. The second is the safer default because it
protects any caller, not just the one that remembers the flag.

**Meanwhile, the working rule for runs:** rehearse CI by reading `gates.yml`,
never by running its verify step against the working tree.


### Appended 2026-09-04 18:00Z: the warning in this entry did not work, and the run that filed the LIVE-path entry above made this exact mistake anyway

Recorded because a warning that fails is more useful than one that is merely
repeated. This cycle ran `verify_refs.py --repo . --offline --no-render` in the
working tree, to rehearse the CI step, having already read this entry — and it
downgraded **eighteen** reference notes in one command, every one of them from
`raw-capture+<registry>` / `identifier_check: confirmed` to bare `raw-capture`.
Reverted with `git checkout -- reference/`, then the LIVE verifier was re-run to
restore the records honestly (hand-editing them back would be back-filling a
verification nobody performed); that live run degraded two more, `ahrens` and
`plantinga`, which were reverted in turn. Final state pushed: zero removed
`confirmed` lines, 77/77 verified.

Two things this adds to the entry above it.

**The blast radius is bigger than the live path's, by an order of magnitude.**
The live defect takes out four or five notes on a bad draw. `--offline` takes
out every note that ever had a registry confirmation, deterministically, in one
command. Same silent failure mode, and every gate passes afterwards.

**The 17:28Z entry told the next cycle to rehearse CI by READING `gates.yml`,
never by running its verify step against the working tree. That is the right
rule and it was not enough to stop this.** The rule lives in a log line and in
this entry's body; the temptation is a single obvious command at gate time. What
would actually stop it is a change upstream, and it is small: **`--offline`
should not write at all unless asked.** Give it `--check` semantics by default —
report what a record would become, exit non-zero on a mismatch, touch nothing —
which is also exactly what CI wants, since CI re-checks rather than re-records.
That single change would make the rehearsal safe and would make CI's own
invocation safer too. Filed here rather than fixed because a content run may not
modify the skill repo.


## 2026-09-04 — Policy, HUMAN RULING NEEDED: this cycle translated Hebrew into the notes itself, because the base has no translation policy

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run

Filed by the 2026-09-04 17:00Z cycle, which did the thing it is asking about.

**The situation.** Sefaria serves *Pardes Rimmonim* in Hebrew only — its API
reports Hebrew as the sole available language for the work. The gate this cycle
needed is therefore untranslated, and every English phrase in
literature/202609041710 and the five permanent notes built on it is **this
repository's own rendering**, made by the run. That is new. Every other
non-English source in this base arrived with a translation someone else made
and could be blamed for: the Solomon translation of *Tiqqunei ha-Zohar*, the
Deane *Proslogium*, the Allen *Institutes*, and — for the whole Arabic
cluster — renderings that were likewise the base's own but of texts where the
base had also captured a published translation to check against. Here there is
nothing to check against.

**What this cycle did, as an interim practice, not a decision.** (1) Marked
every rendering as the repository's own at the point of use, in the reference
note, the literature note and each permanent note. (2) Quoted the Hebrew beside
every rendering that carries argumentative weight, so a reader who reads Hebrew
can check it without leaving the note. (3) Mechanically verified all fifteen
Hebrew quotations against the capture's **excerpt body only** — the protocol the
16:00Z cycle wrote for OCR Arabic, which applies here too even though this text
is clean digital rather than OCR, because the capture header contains Hebrew the
base itself wrote. All fifteen matched verbatim after stripping only whitespace
and invisible bidirectional marks.

**The ask.** A human should rule on whether a run may translate at all, and if
so under what constraints. Three options, and the second is what this cycle
followed:
1. **Never.** A source without a published translation is a source this base
   cannot use, and the *atzmut*/*kelim* question stays unanswerable.
2. **Yes, marked and quoted-beside** — the practice above, promoted to a rule.
3. **Yes, but only for a claim corroborated by a source in a language the base
   can read**, which would in this case have blocked most of the gate.

**Why it matters more than it looks.** Option 1 is not obviously wrong. The
2026-09-03 cycle *declined* to capture *Ari Nohem* in Hebrew precisely because
"a Hebrew capture would need a translation policy this repository has not yet
set". This cycle went ahead. Whichever way the ruling goes, one of those two
cycles was wrong, and the base should not keep taking both positions.

## 2026-09-04 — Tooling, HIGH: the LIVE `verify_refs.py` also downgrades verification records, on a transient lookup failure, and it did it to five notes this cycle

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** high
- **asked_by:** run

Filed by the 2026-09-04 17:00Z cycle. This is a **third observation** of the
defect first recorded on 2026-09-02 ("`verify_refs.py` erases live provenance on
a network failure") and it materially changes the repair advice the 16:00Z
cycle wrote.

**What happened.** The cycle ran the live verifier as step 8 requires —
`verify_refs.py --repo . --mailto <addr>`, no `--offline` — over 75 references.
It reported `75/75 verified` and exit 0. Five reference notes came out
degraded: ahrens (202608301000), dweck (202609030150), housel (202608311036),
luhmann (202609010111) and plantinga (202609011500) all went from
`method: raw-capture+openlibrary` with `identifier_check: confirmed` to bare
`method: raw-capture`, `source` pointing at the local capture instead of the
registry URL, and for dweck and housel a NEW `identifier_check: failed`.

**Why it is not the `--offline` defect.** The 16:00Z entry says the repair for a
degraded record is "re-run the live verifier; it restores the richer methods and
the `identifier_check` values". That advice is now known to be unsafe as
stated: the live verifier is what caused this. Open Library was probed
immediately afterwards and answered **HTTP 200 in under 7 seconds** for both
degraded ISBNs, and Crossref answered 200 as a control — so this was a
transient failure or rate-limiting inside a 75-reference batch, not an outage,
and it will not reproduce on demand. That is the worst shape for a defect to
have: it fires occasionally, reports success, and is invisible unless someone
reads a diff of files the cycle had no reason to touch.

**What the cycle did.** Reverted the five files (`git checkout --`), which
restores the richer records established by earlier successful live lookups, and
confirmed with `git diff -U0 reference/ | grep '^-' | grep -c
'identifier_check: confirmed'` → 0. No re-run was attempted: re-running the
whole batch to fix five notes risks degrading a different five.

**What to change, and it strengthens the 16:00Z ask rather than replacing it.**
That entry offered a human two options and preferred the second — "have the
writer refuse to *lower* an existing verification method". This cycle is
evidence for that option specifically. A `--check-only` flag on `--offline`
would not have helped here, because the offending run was live. A writer that
declines to replace `raw-capture+openlibrary`/`confirmed` with
`raw-capture`/`failed` would have made this run a no-op on those five files, and
would fix both defects with one change.

**Meanwhile, the working rule for runs:** after any `verify_refs.py` run, read
`git diff reference/` before committing, and revert any note whose verification
method got *shorter*. Do not assume a clean gate means nothing was lost — all
six gates passed on the degraded tree.

## 2026-09-04 — Access, HIGH VALUE: Sefaria's API opens Kabbalah primary texts with machine-readable licences, and it is the route this base was missing

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** run

Filed by the 2026-09-04 17:00Z cycle, which used it to close a four-cycle-old
want.

**The route.** `https://www.sefaria.org/api/v3/texts/<Ref>?version=<language>`,
where `<Ref>` is a work title with dots for its address levels — e.g.
`Pardes_Rimmonim.4.1` for gate 4 chapter 1, `Tikkunei_Zohar.17a` for a folio.
One request returns the whole section as a list of paragraphs with light HTML
(`<b>`, `<br>`), so **no paging question arises** and the eleven-link-window
trap the altafsir entries describe cannot occur here. `?version=all` does NOT
work as its name suggests: it returns a warning listing the available languages
and no text. Ask for `hebrew` and `english` separately.

**Two things it gives that other hosts in this base's experience do not.**
1. **A machine-readable licence per version.** Each version carries `license`
   and `versionSource`. *Pardes Rimonim* comes back `Public Domain`; the Solomon
   *Tiqqunei ha-Zohar* translation comes back `CC-BY-NC`. That is a fact a run
   can act on rather than guess at, and it is directly relevant to the open
   entry about all-rights-reserved full texts in a public repo: this cycle
   captured a whole gate precisely because the field said Public Domain.
2. **A structure probe.** `/api/v2/raw/index/<Work>` returns the work's schema,
   which is how this cycle learned *Pardes Rimmonim* is addressed
   Gate.Chapter.Paragraph before fetching anything.

**Exhaustion, done the way the 14:00Z rule requires.** Chapters were requested
in order until the host stopped: `Pardes_Rimmonim.4.11` → HTTP 404, while
`4.10` returns content and `5.1` returns the opening of the next gate. So the
404 is an end-of-gate and not a failed fetch, and it was established from the
content on both sides of the boundary rather than from any navigation control.

**Identifiers, so the next run does not re-search.** `Pardes_Rimmonim` (Hebrew
only, Public Domain, gate 4 = *Sha'ar Etzem ve-Kelim*, gate 3 = whether Ein Sof
is Keter, gate 5 = the order of emanation); `Tikkunei_Zohar` (Hebrew and the
Solomon English, CC-BY-NC; *Patach Eliyahu* at 17a-17b, which is folio 15 in the
edition Cordovero quotes). Both were reachable on the first request through the
session's egress proxy.

## 2026-09-04 — Still wanted after inquiry 202609030146 was closed: comparative scholarship on the Trinity and the sefirot

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** run

Filed by the 2026-09-04 17:00Z cycle, which closed that inquiry from primary
texts and is recording what closing it did NOT establish.

Two notes now carry a comparison that no source in this base makes:
`the-two-kabbalistic-readings-of-the-sefirot-are-the-two-the-councils-ruled-out--202609041730`
and `the-sefirot-have-a-term-outside-them-and-the-persons-have-none--202609041745`.
Both are tagged `contested`, both say in their own bodies that the alignment is
this repository's, and both would have to be re-scored — not defended — if a
comparative scholar is captured placing the two doctrines differently.

**The specific thing to look for**, which is narrower than "get Scholem": a
scholarly treatment of whether the sefirot are *persons* in anything like the
sense the councils fixed for *hupostasis*, and of whether Ein Sof functions as a
term outside the ten in the way this base now asserts. Scholem, Idel and Wolfson
remain the obvious names and remain in copyright; before budgeting for them,
try Unpaywall by DOI on their journal articles rather than the books, and check
whether any of the relevant chapters have author-deposited copies. A negative
result is worth recording here so the next run does not repeat it.

**One counter-witness this base already holds and should weigh first.** Leon
Modena and Pico both assert the resemblance these two notes deny, from opposite
motives (202609011811, 202609030155). The new notes do not engage them
head-on — they argue that the resemblance fails on doctrinal content, while
Modena and Pico are evidence that it was *perceived*. Someone should decide
whether that is a real reconciliation or a change of subject.

## 2026-09-04 — Tooling, HIGH and now ROOT-CAUSED: the verifier's ISBN lookup calls an Open Library endpoint that returns an empty 200, and three previous cycles diagnosed it as "transient"

- **status:** new
- **priority:** high
- **asked_by:** maintenance-run (2026-09-04 18:00Z cycle, fourth observation)

**This entry corrects its three predecessors.** The 2026-09-02, 09-04 15:00Z and
09-04 17:28Z entries all recorded the live `verify_refs.py` silently degrading
reference notes — `method: raw-capture+openlibrary` and `identifier_check:
confirmed` replaced by bare `raw-capture`, sometimes with `identifier_check:
failed` — and all three concluded it was transient failure inside a large batch.
It is not transient. It is deterministic, and it will happen on every future
run until something changes.

**What happened this cycle.** The live verifier degraded FOUR notes: `ahrens`,
`housel`, `luhmann` and `plantinga`. All four were reverted with `git checkout
--`, and `git diff -U0 reference/ | grep '^-' | grep -c 'identifier_check:
confirmed'` is 0 on what this cycle pushes. 77/77 verified.

**The root cause, probed rather than inferred.** The 17:28Z cycle probed Open
Library after the fact, got HTTP 200 in under 7s, and concluded the failure had
been transient. That probe checked the status code and not the body. The body is
the defect:

```
curl "https://openlibrary.org/api/books?bibkeys=ISBN:9781542866507&format=json&jscmd=data"
  -> 200, body: {}          (Ahrens, repeatably)
curl "https://openlibrary.org/api/books?bibkeys=ISBN:9780857197689&format=json&jscmd=data"
  -> 200, body: {}          (Housel, repeatably)
```

Both books ARE on Open Library. `https://openlibrary.org/search.json?isbn=<isbn>`
returns `numFound: 1` with the right title for both, and
`https://openlibrary.org/isbn/9780857197689.json` returns 200. It is specifically
`/api/books` with `jscmd=data` — the endpoint `verify_refs.py` uses — that now
answers `{}` for records that plainly exist.

**Why an empty 200 becomes `identifier_check: failed`.** In
`scripts/verify_refs.py`, `_identifier_lookup` treats a falsy JSON body as a
miss, falls through to Google Books, and when that misses too returns `("", "")`
— which is NOT `None`, so `verify_note` takes the branch
`return Verification(True, "raw-capture", capture, "failed")`. A soft failure at
the far end is converted into a **definitive verdict of identifier rot**, and
that verdict is then written over a record that previously said `confirmed`.
(The two notes that came back as bare `raw-capture` with no `identifier_check`
took the other path: a timeout raises `NetworkUnavailable`, the batch loop
re-verifies that one note offline, and the offline branch records neither
outcome. Open Library answered in 3-9s under load against a 20s timeout, so both
paths are live at once.)

**This is direct evidence for the fix the 17:28Z entry preferred, and against
the repair advice the 16:00Z entry gave.** "Re-run the live verifier" cannot
repair this, because the endpoint will answer `{}` again. Two changes, either of
which would end it, for a human to choose between upstream in the skill repo
(a content run may not touch it):

1. **The writer must refuse to LOWER an existing verification.** A record that
   says `raw-capture+openlibrary` / `confirmed` should never be overwritten with
   a weaker one by a lookup that failed; degradation should require an explicit
   flag. This is the general fix and it protects against the next dead endpoint
   as well as this one.
2. **Move the ISBN lookup off `/api/books`.** `search.json?isbn=<isbn>` answers
   correctly for both ISBNs today. This is the narrow fix and it will rot again.

Until one lands, every cycle must keep running the 17:28Z check —
`git diff -U0 reference/ | grep '^-' | grep -c 'identifier_check: confirmed'`
must be 0 before commit — and revert what the verifier degraded. That check has
now caught the same defect four times and is the only thing standing between
this repository and a slow, silent loss of its verification evidence. **No gate
catches it**: every lint passes on the degraded state, which is the whole point.

## 2026-09-04 — Leads left open by the offloading cycle, and the base now has ZERO open inquiries

- **status:** new
- **priority:** normal
- **asked_by:** maintenance-run (2026-09-04 18:00Z cycle)

**First, the fact a planner needs.** With inquiry 202609032123 marked
`answered`, `inquiries.py --status new` and `--status in-progress` both report
none. Every question this repository has been asked is closed. The next cycle
has no queue to work from and must choose against config.yml topics or against a
gap it finds; it should not read the empty queue as "nothing to do".

**Three specific leads this cycle located and did not take.**

1. **Camerer et al. 2018, the Social Sciences Replication Project.** Cited
   throughout this cycle's notes AT SECOND HAND, through the paper that
   replicates alongside it, and deliberately never cited directly — no note here
   claims to have read it. It is reachable: `10.1038/s41562-018-0399-z`,
   Unpaywall gives an accepted version at
   `pure.eur.nl/ws/files/37359856/`, and the Google Stroop replication's own
   materials are on OSF at `https://osf.io/wmgj9/` with a summary at
   `https://osf.io/4rfme/`. Worth taking for its own sake: it is a 21-study
   replication project, and this repository has been reasoning about replication
   as a concept since 2026-09-04 without ever having read a replication project.
2. **The Sparrow supplement.** `science.sciencemag.org/content/suppl/2011/07/13/`
   `science.1207745.DC1`. This repository states the sample sizes of Experiments
   2-4 on trust, through an audit that read the supplement for Experiment 1 and
   found its degrees of freedom irreconcilable. Permanent 202609041835 says so
   in its own body. If the supplement is reachable, the sample sizes behind
   202609041825 can be checked directly instead of inherited.
3. **A replication of Sparrow Experiments 2-4, if one exists.** Two negative
   checks were made — the 2020 replication paper reviews this literature and
   records none, and a search found none — and that is recorded in
   202609041825 as two checks rather than as an established absence. A cycle
   with a better route to the citation graph (Semantic Scholar and OpenAlex both
   expose citing-works APIs and neither was tried) could settle it. Finding one
   would ADD to that note, not contradict it.

**And one methodological observation worth more than the leads.** The most
valuable thing this cycle read was not a result but an audit: a section of the
replication paper headed "Statistical issues in the original study", which
established what the original's headline actually rests on. A failed replication
says an effect did not reappear; an audit says how little there was to reappear.
This repository has now twice found that the second is worth more to it than the
first (the Rowland cycle was the other). **Candidate rule for the skill-smith,
whose cadence is not due until ~2026-09-08: when a source has been replicated,
look for whether the replicating paper also audits the original, and read that
section first — it is usually short, it is usually near the end, and it changes
how much the original's untested claims are worth.**

## 2026-09-04 — Tooling, HIGH: verify_refs.py resolves DOIs against Crossref ONLY, so every DataCite-registered DOI in this base is permanently indistinguishable from a rotted identifier

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04T18:53Z cycle, which closed a three-day-old standing
warning by hand and found the reason it had stood for three days.

**THE DEFECT.** `scripts/verify_refs.py` has exactly one DOI endpoint:

    CROSSREF = "https://api.crossref.org/works/{doi}?mailto={mailto}"

There is no DataCite path. A DOI registered with DataCite therefore returns 404
from the only registry the verifier asks, and the note is written with
`identifier_check: failed` — the same value a DOI that has genuinely rotted
gets. The two states are not distinguishable in the record, which is the part
that matters: this base's whole verification discipline rests on keeping
"unreachable" separate from "does not exist", and here they are collapsed.

**THE CASE.** `reference/schmidt-niklas-luhmanns-card-index--202609010302`
(Schmidt, "Niklas Luhmann's Card Index: The Fabrication of Serendipity",
*Sociologica* 12.1, DOI `10.6092/issn.1971-8853/8350`). The 2026-09-01 cycle
diagnosed this correctly from Crossref's agency endpoint and wrote the
diagnosis into the note's body. Three subsequent cycles then logged it as
"identifier unresolved at any registry", which is not what the note says and is
not true. Nobody queried DataCite. `https://api.datacite.org/dois/<doi>`
returns the record on the first request, and every field matches the note:
title, creator `Schmidt, Johannes F.K.`, publicationYear 2018, publisher and
container *Sociologica* vol. 12, and the article URL already on file. The
record was raised to `identifier_check: confirmed`, `method:
raw-capture+datacite`, by hand.

**AND IT WILL NOT STAY RAISED.** The live `verify_refs.py` run in step 8 of
this cycle immediately rewrote that block back to `method: raw-capture` /
`identifier_check: failed`, because a hand-recorded state it cannot reproduce
is a state it overwrites. It was restored, and the note's body now says so, but
any future cycle that runs the verifier and does not diff `reference/`
afterwards will silently undo the fix again. This is the same class as the two
open `verify_refs` entries above (the offline rewrite and the transient-failure
downgrade) and the third instance of one root cause: the verifier treats its own
lookup as authoritative over a record it did not write.

**WHAT WOULD FIX IT, in the skill repo, not here.** Add DataCite as a second
DOI registry — `https://api.datacite.org/dois/<doi>` — tried when Crossref
404s, recording `datacite` as the method on success. Separately, and more
important than the registry itself, `identifier_check` needs a third value:
`not-in-registry` (checked, absent, no evidence of rot) as distinct from
`failed` (lookup error or contradicted metadata). Without that distinction the
DataCite fix just moves the boundary rather than removing the confusion.

**SCOPE CHECK.** One note in this base is affected today. That is not the
reason to fix it: DataCite is the registrar for a large share of university
press, institutional repository and data DOIs, which is exactly the class of
source this base reaches when the ladder's rung (b) or (c) works, so the
population of affected notes grows with the access routes that work best here.

## 2026-09-04 — Access: Unpaywall's version label is not evidence, and this cycle's source was a version-of-record with explicit terms forbidding exactly what a public repo does

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04T18:53Z cycle. This is an appendix to the open
human-decision entry "Full-text captures of all-rights-reserved articles sit in
raw/ in a public repository", and it adds the first case where the question that
entry asks is settled by the HOST rather than by inference.

**WHAT HAPPENED.** Camerer et al. 2018 (DOI `10.1038/s41562-018-0399-z`) was
reached at ladder rung (b) on the first request. Unpaywall reports two OA
locations for the DOI and labels the good one `acceptedVersion`, hosted at
`pure.eur.nl`. It is not an accepted version. The PDF's own EUR cover sheet
says:

    Document Version: Publisher's PDF, also known as Version of record
    Document License/Available under: Article 25fa Dutch Copyright Act

and its Terms and Conditions of Use say, in as many words, that you "may not
reproduce or make this material available to any third party", that you "may
download, save and print a copy of this material for your personal use only",
and that you "may share the EUR portal link to this material".

**TWO SEPARATE LESSONS, and the second is the bigger one.**

1. **Unpaywall's `version` field is a lead, not a fact.** This base has been
   using rung (b) as its most reliable route, and it has been reading the
   version label as if it described the file. It does not always. Check the
   file's own cover sheet, which institutional repositories almost always
   carry, before recording what was obtained. A version-of-record behind a
   statutory-exception licence is a different object from an author manuscript
   posted under a repository's own terms, and only the first comes with
   redistribution terms attached to the copy you actually hold.

2. **Article 25fa is a right the AUTHOR has, not a licence granted to the
   reader.** The Dutch Taverne amendment lets an author of a
   publicly-funded short scientific work make it publicly available free of
   charge after a period, whatever the publisher's contract says. It says
   nothing about onward republication by a third party, which is why the EUR
   cover sheet has to spell out "personal use only" alongside it. A source can
   be perfectly legitimately free to read and still be one this repository may
   not carry.

**WHAT THIS CYCLE DID.** Applied the excerpt rule the Rowland cycle proposed
and the 08:00Z cycle applied: fetched, read in full, and committed
`raw/202609041855-camerer-et-al-2018-ssrp-excerpts.txt` — the passages the
notes use, the source URL, and the SHA-256 of the exact PDF read
(`23f01465218a980c18981321851c28fedb0fd762f9f4e4c8e1c5398e2240a34e`), so any
quotation can be re-derived by anyone who fetches the file themselves. The PDF
was never committed, so nothing in the immutable `raw/` layer was touched. The
one place the rule bit was the "never rest a negative claim on an excerpt"
clause: permanent 202609041920 turns on Sparrow et al. being ABSENT from two
enumerated lists, so the capture quotes those lists whole, with their
superscript reference numbers intact and a key to what the numbers mean,
rather than quoting the sentences around them.

**FOR WHOEVER DECIDES THE OPEN QUESTION.** This case does not need the human
ruling: the host states its terms and they are not ambiguous. What it adds is
evidence for the shape of the rule. "Excerpt anything in copyright" would have
produced the right answer here, but so would the narrower and more defensible
"excerpt anything whose host states redistribution terms, and read the cover
sheet to find out whether it does". The second is checkable per source; the
first requires a licence judgement a run is not well placed to make.

## 2026-09-04 — Leads after the SSRP cycle: the OSF repository is the route to everything this cycle could not reach, and two of the 18:00Z leads are still open

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04T18:53Z cycle, which took lead 1 of the three the 18:00Z
cycle left and did not take leads 2 or 3.

**WHAT WAS TAKEN.** Lead 1, Camerer et al. 2018, the Social Sciences
Replication Project. Read in full; reference 202609041855, literature
202609041900, permanent 202609041905, 202609041910, 202609041915 and 202609041920.

**LEADS 2 AND 3 ARE STILL OPEN, and both are now easier than the 18:00Z cycle
thought**, because reading the SSRP produced a better route than the ones it
named:

  - **Lead 2, the Sparrow supplement** (`science.sciencemag.org/content/suppl/`
    `2011/07/13/science.1207745.DC1`), wanted so the sample sizes behind
    permanent 202609041825 can be checked rather than inherited. Untried this
    cycle. Note that the SSRP's OSF repository may make it unnecessary: the
    project reconstructed Sparrow's Experiment 1 design without the original
    authors' help, and its replication report will say what it believed the
    original design to be.
  - **Lead 3, a replication of Sparrow Experiments 2-4.** Untried this cycle,
    and unchanged: Semantic Scholar and OpenAlex both expose citing-works APIs
    and neither has been tried from this container. Reading the SSRP adds one
    fact to the negative record: it did not test Experiments 2-4 either, and
    could not have, since its selection rule takes the first significant result
    in a paper.

**THE ROUTE THIS CYCLE FOUND AND DID NOT WALK.** The SSRP's OSF repository,
`https://osf.io/pfdyw/`, holds the pre-replication and final replication reports
for all 21 studies, each with an "Unplanned protocol deviations" section, plus
the project's data and materials. That is a public, permanently-identified,
machine-reachable host, and it answers questions the captured PDF cannot,
because everything per-study lives in Supplementary Information the PDF does not
include. It is the route for the new inquiry 202609041906 (Karpicke and Blunt),
for the Sparrow design differences the project says it "cannot rule out"
affected the result, and for lead 2. **Nobody in this base has tried an OSF
endpoint.** Worth a triage attempt on its own account, and worth recording in
`skills/source-access-triage` if it works, because a replication project's OSF
repository is the general case: the paper is the summary, the OSF repository is
the evidence.

**ONE MORE SOURCE THIS CYCLE NAMED AND DID NOT FETCH.** Nature Human Behaviour
published Correspondences by the original authors alongside the SSRP Letter,
including one by Sparrow. Permanent 202609041910 rests on the SSRP's account of
the non-cooperation, which is one side of it. The Correspondence by Sparrow is
the other side and this base does not have it. That is a real one-witness
exposure on a note that concedes a point against this base's own position, so
the exposure currently runs in the direction of caution rather than convenience
— but it should be closed, and the note says so.

## 2026-09-04 — Process finding from the critic: an excerpt capture must not carry the capture author's own derivation, and this cycle's did

- **status:** new        <!-- new | in-progress | answered | archived -->
- **priority:** normal
- **asked_by:** human

Filed by the 2026-09-04T18:53Z cycle, on its own critic's finding, and fixed
before commit. Recorded because the mistake is structural rather than local.

**WHAT HAPPENED.** The excerpt capture written this cycle,
`raw/202609041855-camerer-et-al-2018-ssrp-excerpts.txt`, quoted the SSRP's
enumerated replication lists correctly, and then added a paragraph of its own
beneath them expanding the superscript reference numbers into study names, in
its own emphasis: "Read against the key above, the stage-1 list ... is:
Ackerman, ... KARPICKE AND BLUNT (25) ...". That derivation was correct — the
critic re-derived it independently rather than accepting it — but it had no
business being in `raw/`.

**WHY IT MATTERS MORE THAN IT LOOKS.** `raw/` is the layer a later cycle
consults to check what a source actually said. It is immutable precisely so
that it can play that role. A capture that mixes the capture author's reasoning
into the evidence destroys the independence the layer exists to provide: the
next cycle reads the derivation as source text, cannot tell it apart from the
quotations around it, and has no way to disagree with it. The failure mode is
quiet and it compounds, because every note downstream then inherits an
inference that has never been checked by anyone but its author.

It is a sharper version of a rule this base already applies to literature notes
("never paste source prose here"), running in the other direction: **never put
your own prose in the capture.** The two layers keep each other honest only if
neither leaks into the other.

**FIXED IN THIS CYCLE.** The derivation was removed from the capture and
replaced with a note saying explicitly that the expansion is a derivation, that
it belongs in literature 202609041900 where it is made, and that the lists are
quoted whole above so a later reader can perform it independently and disagree.
The literature note now also states which identifications are confirmed by
main-text prose (Sparrow p. 641, Pyc and Rawson p. 638) and which rest on the
figure-legend key alone (Karpicke and Blunt).

**FOR THE SKILL-SMITH (cadence ~2026-09-08), a candidate rule for
`source-access-triage`:** an excerpt capture contains quotations, locators,
provenance and checksums, and nothing else. Anything that begins "read against"
or "this means" belongs in a note. Where an excerpt must carry structure the
original supplies elsewhere — a key, a table legend, a numbering scheme — quote
that structure as its own excerpt rather than applying it.
