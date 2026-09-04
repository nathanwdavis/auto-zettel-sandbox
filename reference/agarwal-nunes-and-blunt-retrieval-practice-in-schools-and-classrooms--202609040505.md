---
id: '202609040505'
key: agarwal-nunes-and-blunt-retrieval-practice-in-schools-and-classrooms--202609040505
slug: agarwal-nunes-and-blunt-retrieval-practice-in-schools-and-classrooms
aliases:
- '202609040505'
type: reference
title: Agarwal, Nunes and Blunt, Retrieval Practice in Schools and Classrooms
tags: []
source_tier: peer-reviewed
scripture: false
csl_json:
  id: '202609040505'
  type: article-journal
  title: 'Retrieval Practice Consistently Benefits Student Learning: a Systematic
    Review of Applied Research in Schools and Classrooms'
  author:
  - family: Agarwal
    given: Pooja K.
  - family: Nunes
    given: Ludmila D.
  - family: Blunt
    given: Janell R.
  container-title: Educational Psychology Review
  volume: '33'
  issue: '4'
  page: 1409-1453
  publisher: Springer
  DOI: 10.1007/s10648-021-09595-9
  issued:
    date-parts:
    - - 2021
      - 3
      - 14
chicago_note: 'Pooja K. Agarwal et al., “Retrieval Practice Consistently Benefits
  Student Learning: A Systematic Review of Applied Research in Schools and Classrooms,”
  Educational Psychology Review 33, no. 4 (2021): 1409–53, https://doi.org/10.1007/s10648-021-09595-9.'
chicago_bib: 'Agarwal, Pooja K., Ludmila D. Nunes, and Janell R. Blunt. “Retrieval
  Practice Consistently Benefits Student Learning: A Systematic Review of Applied
  Research in Schools and Classrooms.” Educational Psychology Review 33, no. 4 (2021):
  1409–53. https://doi.org/10.1007/s10648-021-09595-9.'
citation_renderer: pandoc
verification:
  method: raw-capture+crossref
  source: https://doi.org/10.1007/s10648-021-09595-9
  verified: true
  identifier_check: confirmed
  date: '2026-09-04T05:05:00Z'
raw_capture: raw/202609040505-agarwal-nunes-blunt-2021-retrieval-practice-classroom-review-fulltext.txt
links: []
created: '2026-09-04'
updated: '2026-09-04'
---

**Full text, in the accepted-manuscript version.** The whole 65-page peer-reviewed
article, not an abstract — so design, screening criteria, counts, effect sizes and
the authors' own reasoning are all reportable from it. What is *not* transferable
is pagination. The accepted manuscript runs pp. 1–65; the published article runs
pp. 1409–1453. Every locator this base takes from this source therefore reads
*accepted manuscript, p. N* and never a journal page, because the two cannot be
converted without the typeset copy, which this environment could not obtain.

Bibliographic record. This is the first of the three independent audits of the
retrieval-practice literature named in
[[karpickes-survey-vouches-for-the-effect-and-never-mentions-notes--202609040330]]
to be read by this base, and it was taken first for a boring reason that turned
out to matter: it is the only one of the three that is open access. What it
settles, and what it does not, is worked out in
[[agarwal-nunes-and-blunt-audited-the-classroom-half-and-declined-to-meta-analyse--202609040510]]
and in the two permanent notes it grounds.

**The description attached to this paper elsewhere in the base is wrong, and the
correction belongs here.** Karpicke's 2025 survey chapter lists this paper among
"three meta-analyses" of retrieval practice, and permanent note
[[retrieval-not-re-exposure-is-what-makes-learning-last--202609040340]] repeated
that description on the survey's authority before the paper itself could be read.
It is not a meta-analysis. Its authors considered one and refused: "we felt that
conditions across the 50 experiments included in the present review were too
varied for a meta-analytic approach" (accepted manuscript, p. 7), and they devote
two pages to why — non-independent effect sizes, the low reproducibility of
meta-analytic means, and inconsistent reporting in the prior reviews. What they
publish instead is every individual effect size with its confidence interval, in
forest plots and an appendix. That is arguably a better artefact for this base's
purposes than a pooled d would have been; it is simply not the thing the survey
called it.

Tiered `peer-reviewed`: *Educational Psychology Review* is a refereed Springer
journal (ISSN 1040-726X / 1573-336X), and this is the authors' accepted
manuscript of the article as published there — the version that passed review,
deposited by the authors themselves on the OSF project the published paper names
as its own materials repository.

**Independence, which is the whole reason this source was sought.** Only partial.
Pooja K. Agarwal is the first author of
[[agarwal-karpicke-kang-roediger-and-mcdermott-open-and-closed-book-tests--202609040315]],
which this base cites and which is a Roediger–Karpicke-line paper; her two
co-authors here are not from that line, and the review is of other people's
classroom studies rather than of her own. So it is an audit from inside the same
research community, one step further out than Karpicke assessing Karpicke, and
not the outside replication that
[[a-failed-replication-leaves-the-mechanism-standing-and-the-effect-unproven--202609040210]]
would count as decisive. Of the three audits, Rowland 2014 is the most
independent. *(Updated 2026-09-04T06:00Z: it has since been read —
[[rowland-the-effect-of-testing-versus-restudy-on-retention--202609040600]] — and
it turns out to complement this review rather than to check it, because the two
excluded each other's studies by explicit criterion. See
[[the-laboratory-and-classroom-evidence-were-separated-on-purpose--202609040610]].)*

Access and provenance, recorded in full in the capture header. The house ladder
(`skills/source-access-triage`) was climbed in order. (a) The publisher failed:
link.springer.com returned HTTP 200 with a 3,038-byte JavaScript shell for the
article page, the PDF route, and the `fulltext.html` route Crossref advertises
for text mining. That is worth stating plainly because Unpaywall and OpenAlex
both classify this article as **gold** open access — free at the publisher — and
the publisher is nonetheless the rung that failed. (b) Unpaywall's two OA
locations are OSF landing pages with no PDF URL, and both `/download` routes
return HTTP 500. (c) **Worked**: asking the OSF *API* for the project's file
list rather than following its landing page returned the accepted manuscript in
one request.

A finding worth carrying forward, and the second cycle running to produce one
about rung (c): an OA landing page that will not yield a file is not a dead end
until the host's own API has been asked for the file list. Unpaywall declared
this paper free and handed over two URLs that download nothing.
