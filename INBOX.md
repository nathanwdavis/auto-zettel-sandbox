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

- **status:** new        <!-- new | in-progress | answered | archived -->
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
