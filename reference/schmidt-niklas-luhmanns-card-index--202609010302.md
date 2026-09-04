---
id: '202609010302'
key: schmidt-niklas-luhmanns-card-index--202609010302
slug: schmidt-niklas-luhmanns-card-index
aliases:
- '202609010302'
type: reference
title: Schmidt, Niklas Luhmann's Card Index
tags: []
source_tier: peer-reviewed
scripture: false
csl_json:
  id: '202609010302'
  type: article-journal
  title: 'Niklas Luhmann''s Card Index: The Fabrication of Serendipity'
  author:
  - family: Schmidt
    given: Johannes F.K.
  container-title: Sociologica
  volume: '12'
  issue: '1'
  page: 53-60
  DOI: 10.6092/issn.1971-8853/8350
  ISSN: 1971-8853
  URL: https://sociologica.unibo.it/article/view/8350
  issued:
    date-parts:
    - - 2018
      - 7
      - 26
chicago_note: 'Johannes F. K. Schmidt, “Niklas Luhmann’s Card Index: The Fabrication
  of Serendipity,” Sociologica 12, no. 1 (2018): 53–60, https://doi.org/10.6092/issn.1971-8853/8350.'
chicago_bib: 'Schmidt, Johannes F. K. “Niklas Luhmann’s Card Index: The Fabrication
  of Serendipity.” Sociologica 12, no. 1 (2018): 53–60. https://doi.org/10.6092/issn.1971-8853/8350.'
citation_renderer: pandoc
verification:
  method: raw-capture+datacite
  source: https://api.datacite.org/dois/10.6092/issn.1971-8853/8350
  verified: true
  identifier_check: confirmed
  date: '2026-09-04T19:05:00Z'
raw_capture: raw/202609010301-schmidt-luhmann-card-index-serendipity.txt
links: []
created: '2026-09-01'
updated: '2026-09-04'
---
Bibliographic record. The standard scholarly description of Luhmann's actual
card index, written by the coordinator of Bielefeld University's Luhmann
archive project ("Niklas Luhmann — A Passion for Theory", 2015–2030), who
works from the literary estate itself. It complements the base's primary
source [[luhmann-communicating-with-slip-boxes--202609010111]]: Luhmann
describes his method from the inside; Schmidt reports what the surviving file
physically contains (about 90,000 cards in two collections, reference counts,
index sizes) and analyzes why the design produces serendipity. The article is
open access (CC BY 4.0) and was captured complete from the journal's own HTML
galley; it is a revised, shortened version of Schmidt's 2016 chapter in
*Forgetting Machines* (Brill).

A note on the identifier: the DOI is registered with DataCite, not Crossref
(confirmed via Crossref's agency endpoint on 2026-09-01, when it also resolved
live via doi.org to the article page). `verify_refs.py` checks DOIs against
Crossref only, so this note carried `identifier_check: failed` for three days —
which recorded "not in Crossref", expected for a DataCite DOI, and not
identifier rot.

**Closed 2026-09-04.** The 2026-09-01 diagnosis was right and was never acted
on, because nobody queried the registry it named. `api.datacite.org/dois/` for
this DOI returns the record, and every field it carries matches this note:
title "Niklas Luhmann's Card Index: The Fabrication of Serendipity", creator
"Schmidt, Johannes F.K.", publication year 2018, publisher and container
*Sociologica* vol. 12, and the article URL already recorded above. So
`identifier_check` is now `confirmed` and the method is `raw-capture+datacite`,
recorded by hand because the verifier has no DataCite path to record it with.
A live `verify_refs.py` run will re-fail the Crossref lookup and may downgrade
this block again; that is the tooling defect filed in INBOX, not new evidence,
and the block should be restored rather than believed.
