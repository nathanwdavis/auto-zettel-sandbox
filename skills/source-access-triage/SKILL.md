---
name: source-access-triage
description: House procedure for a source that exists but cannot be read from this environment - the legitimate access ladder, when to settle for abstract-only grounding, the excerpt cross-check standard, and how to record the gap so a later run can close it.
---

# Source access triage

<!--
A self-authored child skill. Sandboxed under the CONTENT repo's /skills/ until
a human promotes it (FR-37). It must never modify the bootstrap skill repo.
-->

## When to use

A source is directly on point and verifiably exists (Crossref/Open Library
hit, or a publisher page), but the full text does not come back: paywall,
Cloudflare bot challenge, lending-restricted scan, JS-only viewer. This skill
decides what the run may claim from it and what it must record. An unread
source is not a source (repo norm since the 2026-08-31 same-God cycle).

## Procedure

1. **Climb the access ladder before giving up, in this order.** (a) The
   publisher's own page. (b) The journal's official OA repository, found via
   Unpaywall by DOI (`api.unpaywall.org/v2/<DOI>?email=<mailto>`). (c) Author
   or institutional pages (PhilArchive/arXiv-style archives, university
   repositories). (d) A public-domain or author-published etext (Gutenberg,
   CCEL, an official preview PDF). (e) The Wayback Machine. Never a
   pirated/scraper mirror (source-legitimacy norm, INBOX 2026-08-31). Record
   in the reference note which rungs failed and how - "unreachable" must stay
   distinguishable from "does not exist".

2. **Settle the grounding tier honestly.** Full text read -> normal notes.
   Publisher abstract only -> reference note body opens with "**Abstract
   only**", the literature note states in its first paragraph that it records
   the stated framework/conclusion, not internal argumentation, and no note
   quotes or paraphrases beyond the abstract (Tachin/Vroom/Bogardus pattern).
   No abstract either -> no reference note at all; the source is mentioned
   only in INBOX as an open item (Hick/Volf pattern).

3. **Excerpt cross-check standard.** A verbatim quotation taken from a
   secondary source (a review, a preview) may be captured and cited only if
   the identical wording, with a locator, appears in at least two independent
   secondary sources (the Housel ch. 4 standard, INBOX 2026-08-31). One
   witness is not verification; near-matching wording is a reason to refuse,
   not to harmonize.

4. **Record the gap where the next run will see it.** One INBOX entry (via
   `capture.py inbox`) naming the source, the DOI/ISBN, every access route
   tried with its failure mode, which notes are grounding-limited by it, and
   what access would close it (library loan, institutional access, purchase).
   If an entry for the same source already exists, append the new attempt to
   it rather than filing a duplicate.

5. **Re-check, don't re-litigate.** A later run touching the same source
   re-tries only rungs whose state could have changed (a new OA copy, a fixed
   DOI), appends the attempt and date to the existing INBOX entry, and leaves
   it open unless the text was actually obtained - then it captures the full
   text, re-scores the affected literature notes, and marks the entry
   answered.
