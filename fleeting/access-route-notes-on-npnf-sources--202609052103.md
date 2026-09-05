---
id: '202609052103'
key: access-route-notes-on-npnf-sources--202609052103
slug: access-route-notes-on-npnf-sources
type: fleeting
tags: []
created: '2026-09-05'
updated: '2026-09-05'
---

# Access ladder for Athanasius NPNF texts — revised lessons

## Corrected findings

**CCEL (https://ccel.org/ccel/schaff/npnf204)**: Returns a page with inline JavaScript. The content div is empty (`<div class="book-content"></div>`), indicating text is loaded dynamically. This is a **true JavaScript shell** — not usable without a renderer.

**Catholic Library (https://catholiclibrary.org/library/view)**: Also uses JavaScript rendering. The capture (56KB for Discourse I) contains real HTML text — the table of contents and opening sections of the works, with full NPNF metadata and early material. However, the quoted passages (Discourse I.28, De Decretis 11 and 22) do NOT appear in the capture. This is not a shell; it is **truncated access** — the host returned part of the work but not the sections needed.

**Tertullian.org (https://www.tertullian.org/fathers2/NPNF2-04/)**: Returns usable HTML with text embedded in the page. No JavaScript required. This proved to be the best access route.

## Critical lesson for future runs

**Byte count and file size are not evidence that a capture contains a given passage.** A capture of 56KB or 30KB may contain substantial real text (as the Catholic Library captures did) but still lack the specific sections needed. Text presence must be verified by search within the capture, not by file size alone. This mistake cost this run time: the captures could have been examined for the key passages before attempting to use them as independent witnesses.

## Recommendations

1. For NPNF texts without JavaScript rendering configured: Try Tertullian.org first
2. If other hosts are tried: search them for the exact passages needed before accepting or relying on them
3. Archive.org PDFs are available but large; consider only if other routes fail
4. A single source that contains the needed passages is preferable to multiple incomplete sources

Only the Tertullian.org captures are linked to verified literature notes in this run.
