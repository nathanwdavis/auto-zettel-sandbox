---
id: '202609041200'
key: maturidi-tawilat-ahl-al-sunna-on-3-64-and-29-46--202609041200
slug: maturidi-tawilat-ahl-al-sunna-on-3-64-and-29-46
aliases:
- '202609041200'
type: reference
title: al-Maturidi, Ta'wilat ahl al-sunna, on Q 3:64 and Q 29:46
tags: []
source_tier: primary-text
scripture: false
csl_json:
  id: '202609041200'
  type: book
  title: Taʾwīlāt ahl al-sunna
  author:
  - literal: Abū Manṣūr Muḥammad ibn Muḥammad al-Māturīdī
  URL: https://www.altafsir.com/Tafasir.asp?tMadhNo=2&tTafsirNo=94&tSoraNo=29&tAyahNo=46&tDisplay=yes
  issued:
    date-parts:
    - - 944
verification:
  method: raw-capture
  source: raw/202609041200-maturidi-tawilat-ahl-al-sunna-3-64-and-29-46-arabic.txt
  verified: true
  date: '2026-09-04T12:00:00Z'
raw_capture: raw/202609041200-maturidi-tawilat-ahl-al-sunna-3-64-and-29-46-arabic.txt
links: []
created: '2026-09-04'
updated: '2026-09-04'
chicago_note: Abū Manṣūr Muḥammad ibn Muḥammad al-Māturīdī, Taʾwīlāt Ahl Al-Sunna
  (944 AD), https://www.altafsir.com/Tafasir.asp?tMadhNo=2&tTafsirNo=94&tSoraNo=29&tAyahNo=46&tDisplay=yes.
chicago_bib: Abū Manṣūr Muḥammad ibn Muḥammad al-Māturīdī. Taʾwīlāt Ahl Al-Sunna.
  944 AD. https://www.altafsir.com/Tafasir.asp?tMadhNo=2&tTafsirNo=94&tSoraNo=29&tAyahNo=46&tDisplay=yes.
citation_renderer: pandoc
---

Bibliographic record for the two sections of Abu Mansur al-Maturidi's
*Ta'wilat ahl al-sunna* that this cycle captured: the commentary on Q 3:64 and
on Q 29:46 — the same pair captured from al-Tabari, al-Qurtubi, Ibn Kathir,
al-Baghawi, al-Sa'di, al-Muyassar, al-Razi, al-Zamakhshari, al-Tusi, al-Tabrisi
and Tantawi by the five cycles before it. Arabic, verbatim, in full, at
`raw/202609041200-maturidi-tawilat-ahl-al-sunna-3-64-and-29-46-arabic.txt`.

**Why this source, and what it was brought in to test.** The 11:30Z cycle closed
by naming exactly two things that would move inquiry 202609032122, and by
arguing against a third: "not another commentary agreeing; that is a tally
mark". The first of the two was al-Maturidi — the last major classical
theological school this base has not sampled, after Mu'tazili (al-Zamakhshari)
and Imami (al-Tusi, al-Tabrisi). He is the eponym of the school that, with
Ash'arism, Sunni orthodoxy is built on, so if the silence about
`وإلهنا وإلهكم واحد` belonged to a theological family rather than to the
tradition, this is the last Sunni place it could hide.

**And a second reason the 11:30Z cycle did not state, which turned out to be the
better one.** Al-Maturidi died in 333/944, twenty-three years after al-Tabari.
Every other commentator in this base's silent set writes a century or more after
the *Jami' al-bayan* — al-Qurtubi, Ibn Kathir, al-Baghawi, al-Razi,
al-Zamakhshari — which leaves open the reading that al-Tabari's `معبود`
identification was current in his own generation and was dropped later. This
capture closes that reading, because it puts a commentator inside al-Tabari's
own generation who does not make the identification.

**Access.** altafsir.com again, `tMadhNo=2` (تفاسير أهل السنة) `tTafsirNo=94`,
by the route the 11:30Z cycle wrote into INBOX so that a later run would spend
its turns reading rather than finding. It worked exactly as documented: the
windows-1256 decode, the entity unescaping, the `&Page=N` pagination and the
block/inline tag distinction were all needed, and all were known in advance.
This is the first time in this base's experience that an access entry filed by
one cycle was consumed by the next with no rediscovery cost, and it is worth
recording as such — the entry cost the previous cycle turns it could have spent
reading, and it bought them back here.

**Edition, stated honestly.** altafsir.com names no printed edition for these
sections and the served body carries no page markers, so nothing keys the text
to a printed edition and none is claimed; locators are by sura:aya. One further
caution specific to this work: the *Ta'wilat* reaches us through the recension of
al-Maturidi's student, and the captured Q 3:64 section carries two interjections
marked `قال الشيخ - رحمه الله -` which are the transmitter-editor's voice and not
al-Maturidi's. They are reproduced in the capture with that marker intact and
are not quoted as his words anywhere in the notes.

**One host only, and this time the exposure is real.** What this repository takes
from the previous altafsir captures was chiefly a positive quotation, against
which a single host is a weak threat. What it takes from this one is chiefly a
NEGATIVE — that al-Maturidi does not gloss the clause — and a single host is a
strong threat to a negative. Three rungs were tried for a second host and all
three failed; each failure mode is recorded in the capture header, including a
new one worth knowing: **tafsir.app routes the slug `maturidi` and returns a
200-status, 150 KB application shell, while its own data endpoint returns an
empty body for this commentator at every verse tried** — with al-Tabari and
al-Qurtubi returning 6,754 and 4,907 characters through the same endpoint in the
same pass, so the endpoint is working and the emptiness is the host's. A "hit"
that is really an absence is a harder failure to notice than a 404.

Two things reduce the exposure without removing it, and they are the reason the
notes state the finding rather than deferring it. The absence is not blank space
but a visible **elision**: al-Maturidi quotes the verse twice, both times
stopping at `وَأُنزِلَ إِلَيْكُمْ` and writing `إلى آخر ما ذكر` — "to the end of
what was mentioned" — and then comments on the following verses at length. A
truncated fetch does not produce that shape. And the section's stop condition
fired on the site's own successor control rather than on a guess. Second-host
confirmation is filed to INBOX all the same.
