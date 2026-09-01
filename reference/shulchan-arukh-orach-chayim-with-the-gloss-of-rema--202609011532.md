---
id: '202609011532'
key: shulchan-arukh-orach-chayim-with-the-gloss-of-rema--202609011532
slug: shulchan-arukh-orach-chayim-with-the-gloss-of-rema
aliases:
- '202609011532'
type: reference
title: Shulchan Arukh, Orach Chayim, with the gloss of Rema
tags: []
source_tier: primary-text
scripture: false
csl_json:
  id: '202609011532'
  type: book
  title: Shulchan Arukh, Orach Chayim
  author:
  - family: Karo
    given: Joseph
  note: Cited here for OC 156:1 as printed with the gloss (Mappah) of Moses Isserles,
    Krakow, 1578, on Karo's base text, Venice, 1565.
  URL: https://www.sefaria.org/Shulchan_Arukh,_Orach_Chayim.156.1
  issued:
    date-parts:
    - - 1565
chicago_note: Joseph Karo, Shulchan Arukh, Orach Chayim (1565), https://www.sefaria.org/Shulchan_Arukh,_Orach_Chayim.156.1.
chicago_bib: Karo, Joseph. Shulchan Arukh, Orach Chayim. 1565. https://www.sefaria.org/Shulchan_Arukh,_Orach_Chayim.156.1.
citation_renderer: pandoc
verification:
  method: raw-capture
  source: raw/202609011532-shulchan-arukh-oc-156-1-rema-shituf.txt
  verified: true
  date: '2026-09-01T15:35:00Z'
raw_capture: raw/202609011532-shulchan-arukh-oc-156-1-rema-shituf.txt
links: []
created: '2026-09-01'
updated: '2026-09-01'
---

Bibliographic record for a single paragraph, Orach Chayim 156:1, captured
because the gloss printed into it is the sentence most often cited when Jewish
law is asked whether gentiles worship the God Jews worship.

**Two cautions about the word *shituf*.** It does not appear in the captured
translation, which renders the relevant terms as "partnering", "partnership"
and "associate"; and the capture's own header line calling the gloss "the
locus classicus for shituf" is this run's editorial identification, not source
text. The identification is standard, but it is uncaptured, so notes citing
this reference say what the gloss says rather than resting on the label.
Whether the ruling is about Christians specifically is likewise not in the
text -- the gloss says only "their foreign god" -- and is how it has been read
since.

The composite structure matters for citing it. The base text is Joseph Karo's
(Venice, 1565); the gloss is Moses Isserles' *Mappah* (Krakow, 1578), and the
sentence this repository turns on is the Rema's, not Karo's. The CSL record
therefore carries Karo and 1565 alone: listing Isserles as a contributor made
the rendered citation read "with Moses Isserles (1565)", which dates the gloss
thirteen years too early, and a single `issued` year cannot express a
composite. The two dates are held in the CSL `note` field and in this prose
instead, and every note citing the association sentence attributes it to the
Rema by name rather than to this citation string. The gloss names its
authorities -- the Ran on Avodah Zarah ch. 1, Rabbeinu Yerucham, and Tosafot
on Bekhorot ch. 1 -- as bare citation strings; none of those three was
captured, so nothing here reports what they argue.

The translation is Sefaria's community translation, released CC0.
