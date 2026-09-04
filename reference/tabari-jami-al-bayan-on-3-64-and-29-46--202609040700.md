---
id: '202609040700'
key: tabari-jami-al-bayan-on-3-64-and-29-46--202609040700
slug: tabari-jami-al-bayan-on-3-64-and-29-46
aliases:
- '202609040700'
type: reference
title: al-Tabari, Jami' al-bayan 'an ta'wil ay al-Qur'an, on Q 3:64 and Q 29:46
tags: []
source_tier: primary-text
scripture: false
csl_json:
  id: '202609040700'
  type: book
  title: Jāmiʿ al-bayān ʿan taʾwīl āy al-Qurʾān
  author:
  - literal: Abū Jaʿfar Muḥammad ibn Jarīr al-Ṭabarī
  URL: https://api.quran.com/api/v4/tafsirs/15/by_ayah/29:46
  issued:
    date-parts:
    - - 923
chicago_note: Abū Jaʿfar Muḥammad ibn Jarīr al-Ṭabarī, Jāmiʿ Al-Bayān ʿan Taʾwīl Āy
  Al-Qurʾān (923 AD), https://api.quran.com/api/v4/tafsirs/15/by_ayah/29:46.
chicago_bib: Abū Jaʿfar Muḥammad ibn Jarīr al-Ṭabarī. Jāmiʿ Al-Bayān ʿan Taʾwīl Āy
  Al-Qurʾān. 923 AD. https://api.quran.com/api/v4/tafsirs/15/by_ayah/29:46.
citation_renderer: pandoc
verification:
  method: raw-capture
  source: raw/202609040700-tabari-jami-al-bayan-3-64-and-29-46-arabic.txt
  verified: true
  date: '2026-09-04T07:00:00Z'
raw_capture: raw/202609040700-tabari-jami-al-bayan-3-64-and-29-46-arabic.txt
links: []
created: '2026-09-04'
updated: '2026-09-04'
---

Bibliographic record for the two sections of al-Tabari's *Jami' al-bayan* that
this cycle captured: the commentary on Q 3:64 (the "common word" verse) and on
Q 29:46 ("our God and your God is one"). Arabic, verbatim, captured in full at
`raw/202609040700-tabari-jami-al-bayan-3-64-and-29-46-arabic.txt`.

**Why this source and not a modern one.** The INBOX entry this cycle worked
asked for a second Muslim source arguing the same-God question *in its own
voice*, in a register different from the irenic collective letter of 2007. This
is the foundational Sunni Qur'an commentary, written by a Muslim jurist and
historian for Muslims, with no Christian addressee and no ecumenical purpose —
about as far from a letter written to be signed by 138 people as the tradition
offers. It is also the commentary on the exact two verses the base's existing
notes turn on, which is why these two sections and no others were taken.

**Access, which was easy and is worth recording as such.** Rung (a) of the house
access ladder worked on the first attempt: the Quran.com API v4 serves the
Arabic text of tafsir resource 15 (`slug: ar-tafsir-al-tabari`) at
`/api/v4/tafsirs/15/by_ayah/<sura>:<aya>`. No paywall, no bot challenge, no
renderer needed. The parallel `/api/v4/quran/tafsirs/15?verse_key=…` endpoint
returns an empty list for the same verse and is the wrong one — recorded so a
later run does not read that emptiness as the text being unavailable.

**Public domain.** The author died in 310/923. The Arabic text is out of
copyright everywhere, which is why the capture holds the full sections rather
than excerpts and stands outside the excerpt-versus-full-text question the
2026-09-04 INBOX entry puts to a human about all-rights-reserved articles.

**Edition — what is NOT claimed.** The API does not name a printed edition.
The 3:64 section carries the served text's own volume–page markers (`&; 6-484
&;` through `&; 6-486 &;`); the 29:46 section carries none, which is consistent
with the two suras coming from different printed bases. This note therefore
claims no edition, and every locator built on this capture is by *sura:aya* —
the natural locator for a verse commentary, and the one that survives a change
of edition. `issued` is set to 923, the author's death year, as a conventional
terminus for a work whose completion date this capture cannot establish; it is
not an edition date.

**Independent cross-check, done mechanically rather than by eye.** Every Arabic
passage quoted anywhere in this repository from this capture was normalised
(diacritics, tatweel, alef/ya/ta-marbuta forms and punctuation removed) and
substring-matched against text served by hosts independent of Quran.com:
`quran.ksu.edu.sa` (King Saud University) and `tafsir.app`. The 29:46 passages
matched on **both** independent hosts; the 3:64 passages matched on
`tafsir.app` (the KSU URL for sura 3 returned a 203-byte stub and was not
counted as a witness). Nothing here is quoted on the strength of one host.

**Translation.** No published English translation of these sections was used.
English renderings in the literature and permanent notes are this repository's
own working translations of the Arabic in the capture, marked as such where
they appear. That is a real limit and is stated in the literature note as well:
the argumentative weight rests on Arabic that this base translated itself.
