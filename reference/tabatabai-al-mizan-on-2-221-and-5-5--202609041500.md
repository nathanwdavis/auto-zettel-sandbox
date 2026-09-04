---
id: '202609041500'
key: tabatabai-al-mizan-on-2-221-and-5-5--202609041500
slug: tabatabai-al-mizan-on-2-221-and-5-5
aliases:
- '202609041500'
type: reference
title: al-Tabataba'i, al-Mizan fi tafsir al-Qur'an, on Q 2:221 and Q 5:5
tags: []
source_tier: primary-text
scripture: false
csl_json:
  id: '202609041500'
  type: book
  title: al-Mīzān fī tafsīr al-Qurʾān
  author:
  - literal: Muḥammad Ḥusayn al-Ṭabāṭabāʾī
  URL: https://www.altafsir.com/Tafasir.asp?tMadhNo=4&tTafsirNo=56&tSoraNo=2&tAyahNo=221&tDisplay=yes
  issued:
    date-parts:
    - - 1981
verification:
  method: raw-capture
  source: raw/202609041500-tabatabai-al-mizan-2-221-and-5-5-arabic.txt
  verified: true
  date: '2026-09-04T15:00:00Z'
raw_capture: raw/202609041500-tabatabai-al-mizan-2-221-and-5-5-arabic.txt
links: []
created: '2026-09-04'
updated: '2026-09-04'
citation_renderer: pandoc
chicago_note: Muḥammad Ḥusayn al-Ṭabāṭabāʾī, Al-Mīzān Fī Tafsīr Al-Qurʾān (1981),
  https://www.altafsir.com/Tafasir.asp?tMadhNo=4&tTafsirNo=56&tSoraNo=2&tAyahNo=221&tDisplay=yes.
chicago_bib: Muḥammad Ḥusayn al-Ṭabāṭabāʾī. Al-Mīzān Fī Tafsīr Al-Qurʾān. 1981. https://www.altafsir.com/Tafasir.asp?tMadhNo=4&tTafsirNo=56&tSoraNo=2&tAyahNo=221&tDisplay=yes.
---

Bibliographic record for the two sections of al-Tabataba'i's *al-Mizan* that this
cycle captured: the commentary on Q 2:221 and on Q 5:5. Arabic, verbatim, in
full, at `raw/202609041500-tabatabai-al-mizan-2-221-and-5-5-arabic.txt`.

**Why this source, and why it was named in advance.** The 13:00Z cycle attributed
to the Imamiyya the position that the People of the Book are *mushrikun* and that
Q 2:221 abrogates Q 5:5, on the sole witness of one clause in al-Sabuni, a modern
Sunni author. The 14:00Z cycle answered half of that from inside the tradition:
al-Tusi (d. 460/1067) and al-Tabrisi (d. 548/1153) do claim the strict reading as
their school's, with `عندنا` and `مذهبنا`. The INBOX entry that cycle left open
named the remaining test and named it precisely — "al-Tabataba'i (56) would be
the strongest." He is captured here, and he dissents, which is a more valuable
result than the confirmation the entry was hoping for.

**What the base may say about this work's standing, and what it may not.** That
*al-Mizan* is the best-known or most-read Imami commentary is a plausible
background belief for which this repository has **no source**, so nothing in
these notes rests on it. What the notes rest on is the date and the school, and
both are read off the host's own selected options: `الميزان في تفسير القرآن/
الطبطبائي (ت 1401 هـ)`, in the group `تفاسير الشيعة الإثنى عشرية`. Where the
notes need a description they use "the major twentieth-century Imami commentary",
whose only load-bearing part — twentieth-century, Imami — is what the selector
says, rather than a claim about readership. That it is *major* is this base's
working characterisation and is not, and should not be read as, a sourced claim.

**Why both verses.** For the same reason the 14:00Z captures took both:
al-Tabataba'i states his position on Q 2:221 and then defers the narrations —
`ستمرّ بك في تفسير الآية من سورة المائدة`, "they will pass before you in the
commentary on the verse of Sura al-Ma'ida." The Imami reports that carry the
inversion, and his answer to them, are in the Q 5:5 section, not the Q 2:221 one.
A Q 2:221-only capture would have taken his conclusion without the reports it is
answering.

**Access.** altafsir.com, `tMadhNo=4` (Twelver Shi'i), `tTafsirNo=56` — the route
this base has used since the 11:00Z cycle and the only host in its experience
that carries Shi'i tafsir at all. Both sections returned on the first request.
The madhhab group, work and author were read back from the served page's own
selected options rather than assumed from the numeric ids.

**Pagination, and a correction to this base's own written rule.** The 13:00Z
cycle recorded "the correct detector is the numeric pager in the RAW HTML …
the maximum of those page numbers is the page count." That is false for any
section longer than eleven pages: the pager is a **sliding window of eleven
links**, and the next block appears only once page 11 is actually fetched. Q 5:5
here advertises 11 and runs to **14**. The three hidden pages are not filler —
pages 12 and 13 carry `أصحابنا`, the Imami *naskh* narrations from al-Baqir, and
al-Tabataba'i's answer to them, which is the whole reason this source was sought.
Exhaustion was therefore established from the text, as the 14:00Z cycle's rule
requires: each section was read until a page returned the verse alone, and two
further pages were fetched and are recorded in the capture header. The pager
window is documented with its own probe table there.

**The two captures taken under the superseded rule were audited, not assumed.**
`raw/202609041300-qurtubi-…` (pager 11, true 11) and `raw/202609041305-sabuni-…`
(pager 4, true 4) were both re-fetched to content exhaustion this cycle and both
are complete. Nothing in the base is short. Al-Qurtubi's section sits exactly at
eleven pages, the last length at which the window is still exact — which is why
the rule passed its own test when it was written.

**Extraction.** Unlike the earlier altafsir captures, the commentary here was
taken by *bounded extraction* rather than by a cross-section frequency filter:
the served page marks its result block, and everything outside those two markers
was never read. A frequency filter is one more proxy for the content, with a
known failure mode — a non-overlapping tail survives it. The bounds are in the
capture header.

**Edition, stated honestly.** altafsir.com names no printed edition for these
sections and the served body carries no page markers, so nothing keys the text to
a printed edition and none is claimed. All locators are by sura:aya. *al-Mizan*
is in copyright; what the notes take is short quotation for comment and
criticism, and the capture exists so that those quotations are checkable.

**One host only.** No independent host for *al-Mizan* is reachable from this
environment; the eight access rungs tried against Shi'i tafsir and their failure
modes are recorded in
[[tusi-al-tibyan-on-3-64-and-29-46--202609041100]]'s capture and are unchanged.
What this repository takes here is positive quotation — positions al-Tabataba'i
states in his own voice — which a single institutional host threatens weakly.
