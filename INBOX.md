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

- **status:** new        <!-- new | in-progress | answered | archived -->
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
