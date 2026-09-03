---
id: '202609022347'
key: polkinghorne-the-science-and-religion-debate--202609022347
slug: polkinghorne-the-science-and-religion-debate
aliases:
- '202609022347'
type: reference
title: 'Polkinghorne, The Science and Religion Debate: An Introduction'
tags: []
source_tier: primary-text
scripture: false
csl_json:
  id: '202609022347'
  type: report
  title: The Science and Religion Debate - an Introduction
  author:
  - family: Polkinghorne
    given: John
  collection-title: Faraday Papers
  number: '1'
  publisher: The Faraday Institute for Science and Religion
  publisher-place: Cambridge
  page: 1-4
  URL: https://www.faraday.cam.ac.uk/wp-content/uploads/resources/Faraday%20Papers/Faraday%20Paper%201%20Polkinghorne_EN.pdf
  issued:
    date-parts:
    - - 2007
      - 4
chicago_note: John Polkinghorne, The Science and Religion Debate - an Introduction,
  no. 1, Faraday Papers (The Faraday Institute for Science and Religion, 2007), 1–4,
  https://www.faraday.cam.ac.uk/wp-content/uploads/resources/Faraday%20Papers/Faraday%20Paper%201%20Polkinghorne_EN.pdf.
chicago_bib: Polkinghorne, John. The Science and Religion Debate - an Introduction.
  No. 1. Faraday Papers. The Faraday Institute for Science and Religion, 2007. https://www.faraday.cam.ac.uk/wp-content/uploads/resources/Faraday%20Papers/Faraday%20Paper%201%20Polkinghorne_EN.pdf.
citation_renderer: pandoc
verification:
  method: raw-capture
  source: raw/202609022347-polkinghorne-faraday-paper-1-natural-theology.txt
  verified: true
  date: '2026-09-03T01:48:20Z'
raw_capture: raw/202609022347-polkinghorne-faraday-paper-1-natural-theology.txt
links: []
created: '2026-09-02'
updated: '2026-09-02'
---

Bibliographic record. The first of the Faraday Institute's numbered papers,
written by the particle physicist turned Anglican priest whose "new natural
theology" the base cites here. Tiered `primary-text` on the same reasoning as
the Calvin and Hodge references: this is cited as Polkinghorne's own statement
of what contemporary natural theology is *for*, not as secondary scholarship
about somebody else's position. The Faraday Papers are edited institutional
publications for a general readership, not refereed articles, so
`peer-reviewed` would overstate the tier.

Published by the Faraday Institute for Science and Religion, St Edmund's
College, Cambridge, and offered as a free download from the Institute's own
site; the paper's colophon carries the publication date (April 2007) and the
Institute's copyright. Capture is bounded excerpts: the summary, the "Natural
Theology" section entire, and the paragraph opening p. 3.

No `identifier_check` is recorded here, deliberately: this paper has no DOI,
ISBN, PMID or arXiv id to check. A live `verify_refs.py` run stamps
`identifier_check: failed` on it anyway, because `citations.arxiv_id()` reads
the CSL `number` field as an arXiv identifier and a Faraday Paper's `number` is
its series number — the run queries arXiv for `id_list=1`, finds nothing, and
records a rot that does not exist. The false line was removed rather than the
correct `number: '1'`, which is real bibliographic data; the offline check CI
runs does not re-add it. Logged in INBOX for the skill-smith.

Provenance worth knowing: the PDF is born-digital and both extractors agree on
the words, but **not on reading order**. pdfminer.six spliced the two columns of
p. 2, which would have placed the multiverse paragraph on p. 2 and inverted the
two halves of the natural-theology paragraph. Pages 1-3 were rendered to images
and read to fix the true order and the page each passage sits on; poppler's
order proved correct. The locators in the literature note are the verified ones.
