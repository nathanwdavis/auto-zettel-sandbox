---
id: '202609041300'
key: qurtubi-al-jami-li-ahkam-al-quran-on-2-221--202609041300
slug: qurtubi-al-jami-li-ahkam-al-quran-on-2-221
aliases:
- '202609041300'
type: reference
title: al-Qurtubi, al-Jami' li-ahkam al-Qur'an, on Q 2:221
tags: []
source_tier: primary-text
scripture: false
csl_json:
  id: '202609041300'
  type: book
  title: al-Jāmiʿ li-aḥkām al-Qurʾān
  author:
  - literal: Abū ʿAbd Allāh Muḥammad ibn Aḥmad al-Qurṭubī
  URL: https://www.altafsir.com/Tafasir.asp?tMadhNo=1&tTafsirNo=5&tSoraNo=2&tAyahNo=221&tDisplay=yes
  issued:
    date-parts:
    - - 1273
verification:
  method: raw-capture
  source: raw/202609041300-qurtubi-al-jami-li-ahkam-al-quran-2-221-arabic.txt
  verified: true
  date: '2026-09-04T13:00:00Z'
raw_capture: raw/202609041300-qurtubi-al-jami-li-ahkam-al-quran-2-221-arabic.txt
links: []
created: '2026-09-04'
updated: '2026-09-04'
chicago_note: Abū ʿAbd Allāh Muḥammad ibn Aḥmad al-Qurṭubī, Al-Jāmiʿ Li-Aḥkām Al-Qurʾān
  (1273), https://www.altafsir.com/Tafasir.asp?tMadhNo=1&tTafsirNo=5&tSoraNo=2&tAyahNo=221&tDisplay=yes.
chicago_bib: Abū ʿAbd Allāh Muḥammad ibn Aḥmad al-Qurṭubī. Al-Jāmiʿ Li-Aḥkām Al-Qurʾān.
  1273. https://www.altafsir.com/Tafasir.asp?tMadhNo=1&tTafsirNo=5&tSoraNo=2&tAyahNo=221&tDisplay=yes.
citation_renderer: pandoc
---

Bibliographic record for the section of al-Qurtubi's *al-Jami' li-ahkam
al-Qur'an* on Q 2:221 — `وَلاَ تَنْكِحُواْ ٱلْمُشْرِكَاتِ حَتَّىٰ يُؤْمِنَّ`,
"do not marry the *mushrikat* until they believe". Arabic, verbatim, all eleven
served pages, at
`raw/202609041300-qurtubi-al-jami-li-ahkam-al-quran-2-221-arabic.txt`.

**Why this verse, and why it is not another tally mark.** This base already
holds al-Qurtubi on Q 3:64 and Q 29:46, captured by the 07:00Z cycle. Q 2:221
is a different question asked of the same author. Since the first commentary
sweep, inquiry 202609032122 has carried an unanswered structural item: every
commentary captured attaches the *jizya* and the sword to the shared-God verses
without registering any tension with `وإلهنا وإلهكم واحد`, and the juristic
literature that decides whether Christians count as *mushrikun* — where the
tension would have had to be resolved if anyone resolved it — was not in the
base and had no access route. The 11:00Z access entry called it "the last
structural gap in this cluster". Q 2:221 is where that question is actually
litigated, because the marriage prohibition forces the law to say who the word
covers.

**How the source was located.** The 11:00Z entry left an instruction: dump the
Tafsir selector for each `tMadhNo` rather than assuming the group. That was done
this cycle, and the eleven groups yield 85 commentaries. Two results matter
here. First, **al-Qurtubi is filed under `tMadhNo=1` (امهات التفاسير, "the
mother commentaries"), not under the Sunni group** — which is why the earlier
survey of `tMadhNo=2` found no *ahkam* work and concluded the genre was absent
from the host. Second, and correcting a claim this base has carried since the
08:00Z cycle: **al-Razi's *Mafatih al-ghayb* IS on altafsir.com**, as
`tMadhNo=1&tTafsirNo=4`. The INBOX entry that said "al-Razi is not on the
endpoint at all" was true of the *quran.com* API it was written about and has
been read since as if it were true of the sources generally; he was in the end
captured from tafsir.app by the 09:00Z cycle, so nothing rests on the error, but
the catalogue is now written down.

**Edition, stated honestly.** altafsir.com names no printed edition for this
section and the served body carries no page markers, so nothing keys the text to
a printed edition and none is claimed. Locators in the literature note are by
sura:aya and by al-Qurtubi's own numbering of the seven *masa'il*, which the
served text carries (`الأُولى`, `الثانية`, … `السابعة`).

**Access, and the single-host exposure.** altafsir.com answered on the first
request and served all eleven pages. A second host was not sought, and the
exposure that creates is weak here rather than strong: everything this base
takes from this capture is a **positive** quotation — al-Qurtubi reporting named
positions and their proofs — and a single host is a weak threat to a positive.
The earlier altafsir captures in this cluster carried negatives, which is why
second-host confirmation was filed for those and is not filed for this one.
`quran.ksu.edu.sa` serves al-Qurtubi as `qortobi` and remains available if a
later run wants the confirmation anyway.

**One capture trap, found the hard way, and it is a correction to the route as
this base wrote it down.** The 11:00Z entry says a page with a successor "carries
a `التالي` control calling `InnerLink_onchange`". True — but `التالي` is the
**`alt` attribute of an `<img>`**, not text in the document. A reader that strips
tags before looking for it sees a single page and stops. This cycle's first pass
did exactly that and produced a 24-line al-Sabuni section that looked complete
and was one page of four; al-Qurtubi looked like one page of eleven. The
pagination must be read out of the **raw HTML** — the numeric pager emits
`InnerLink_onchange(<tafsir>,<page>,<size>)` for every page, and its maximum is
the page count. This is the same false-absence failure mode the entry warned
about, arriving through a door the entry left open.
