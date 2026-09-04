---
id: '202609040905'
key: razi-mafatih-al-ghayb-on-3-64-and-29-46--202609040905
slug: razi-mafatih-al-ghayb-on-3-64-and-29-46
aliases:
- '202609040905'
type: reference
title: al-Razi, Mafatih al-ghayb (al-Tafsir al-kabir), on Q 3:64 and Q 29:46
tags: []
source_tier: primary-text
scripture: false
csl_json:
  id: '202609040905'
  type: book
  title: Mafātīḥ al-ghayb
  author:
  - literal: Fakhr al-Dīn Muḥammad ibn ʿUmar al-Rāzī
  URL: https://tafsir.app/alrazi/29/46
  issued:
    date-parts:
    - - 1210
chicago_note: Fakhr al-Dīn Muḥammad ibn ʿUmar al-Rāzī, Mafātīḥ Al-Ghayb (1210), https://tafsir.app/alrazi/29/46.
chicago_bib: Fakhr al-Dīn Muḥammad ibn ʿUmar al-Rāzī. Mafātīḥ Al-Ghayb. 1210. https://tafsir.app/alrazi/29/46.
citation_renderer: pandoc
verification:
  method: raw-capture
  source: raw/202609040905-razi-mafatih-al-ghayb-3-64-and-29-46-arabic.txt
  verified: true
  date: '2026-09-04T09:05:00Z'
raw_capture: raw/202609040905-razi-mafatih-al-ghayb-3-64-and-29-46-arabic.txt
links: []
created: '2026-09-04'
updated: '2026-09-04'
---

Bibliographic record for the two sections of Fakhr al-Din al-Razi's *Mafatih
al-ghayb* (*al-Tafsir al-kabir*) that this cycle captured: the commentary on
Q 3:64 and on Q 29:46, the same pair captured from al-Tabari, al-Qurtubi, Ibn
Kathir, al-Baghawi, al-Sa'di and al-Muyassar by the two cycles before it.
Arabic, verbatim, in full, at
`raw/202609040905-razi-mafatih-al-ghayb-3-64-and-29-46-arabic.txt`.

**Why this source, and why it was the one still missing.** The commentary sweep
of the 08:00Z cycle established that al-Tabari's gloss of `وإلهنا وإلهكم واحد`
as a shared `معبود` is repeated by none of the three classical commentators it
captured. That cycle then filed the objection against its own result: al-Qurtubi
is a jurist, Ibn Kathir a traditionist and al-Baghawi an abridger, so their
silence might be a fact about the *genre* rather than about the tradition, and
al-Razi — the theologian of the group, writing the one classical commentary
organised around *kalam* questions — was the test that would separate the two.
He is also the one commentator whose absence from the Quran.com endpoint that
cycle recorded as blocking.

**Access.** tafsir.app, slug `alrazi`, first request for each verse. The
previous cycle's untried guess `/razi/29/46` returns the host's empty-shell page
(~150,400 bytes, this environment's signature for "no such commentary" on that
host); the site's own embedded resource list gives the correct slug. The
correction, and the byte-count signature that identifies the failure mode, are
written into the capture header and into INBOX so no later run re-spends the
turns.

**Public domain.** The author died in 606/1210, so the Arabic text is out of
copyright and the capture holds both sections in full rather than as excerpts.

**The completeness question, which is load-bearing here.** This note supports a
claim about what al-Razi does *not* say, and an absence can be an artefact of an
abridged electronic text. Three copies of each section were compared:
tafsir.app, `islamweb.net` (book 132, *al-Tafsir al-kabir*) and
`quran-tafsir.net`. The tafsir.app and islamweb.net copies begin and end on the
same sentences; the quran-tafsir.net copy of the 29:46 comment is TRUNCATED,
stopping at `فهو دليل مضيء` and dropping the closing third, which is recorded
because it is exactly the kind of defect that would otherwise manufacture a
false absence. The string `معبود` was searched, after normalisation, in all
three copies of the 29:46 comment and occurs in none of them — including the two
that are demonstrably complete.

**Independent cross-check, done mechanically.** Every Arabic passage this
repository quotes from this capture was normalised (diacritics, tatweel,
alef/ya/ta-marbuta forms and punctuation removed) and substring-matched against
the two hosts named above. Every quoted passage matched on islamweb.net; all but
one matched on quran-tafsir.net, the exception being carried only by the section
its copy truncates. No quotation in this repository rests on a single host.

**A tooling correction made during this check.** The normaliser first used in
this cycle stripped Arabic *letters* as well as diacritics, because the
character class `[ؐ-ً...]` spans U+0610–U+064B and so swallows the whole letter
block U+0621–U+064A. Every match reported by it was re-run under a normaliser
that strips marks by explicit code point. The substantive results did not
change, but they were not trustworthy until they were re-run, and the defect is
filed in INBOX because the same idiom appears in the checking done by earlier
cycles.

**Edition.** Neither host names a printed edition. Both carry the same page
markers — (p-٧٦) and (p-٧٧) in the 3:64 section, (p-٦٧) in the 29:46 section,
matching islamweb.net's `ص: 76`, `ص: 77` and `ص: 67` — which is evidence that
both are keyed to one printed edition, but that edition is named by neither, so
none is claimed. Locators are by *sura:aya*. `issued` is the author's death
year, a conventional terminus, not an edition date.

**Translation.** No published English translation was used. English renderings
in the literature and permanent notes are this repository's own working
translations of the captured Arabic, printed beside the Arabic wherever they
carry weight. This source takes the standing translation-calibration debt
(INBOX 2026-09-04) from six sources to seven; it does not pay it.
