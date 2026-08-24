# Affiliate & Recommended Resource Guide

> **Status:** non-normative maintainer guide. Not part of the canonical Thalia Protocol.  
> **Public resource root:** `https://swindon.org.uk/resources/`

## Architecture rule

Do not place tracked retailer URLs in:

- `THALIA_PROTOCOL.md`; or
- the portable human-facing `thalia-humour-app.md`.

The app contains one permanent resource reference:

`https://swindon.org.uk/resources/thalia-humour-app.htm`

The matching HTML page contains the useful explanation, disclosure and one current tracked affiliate recommendation.

This lets the retailer, product or tracking URL change later without changing distributed copies of the Markdown app.

## UK-facing programme shortlist

Commission rates and programme terms change. Verify current terms in the official dashboard immediately before publication.

Current research candidates include:

1. **Bookshop.org UK** for suitable print books.
2. **Libro.fm** or **Bookshop.org audiobooks** when audio is the better fit.
3. **Amazon UK / Audible** as a broad-catalogue fallback.
4. **Kobo** or **Waterstones** where they provide the better match.

Do not invent tracking identifiers.

## Candidate Thalia resources

These are study/recommendation candidates, not normative protocol sources.

### Barker-Corbett

**The Two Ronnies: Comedy Classics**  
ISBN: `9780091894542`

**The Two Ronnies: It's Goodnight From Me**  
Audio ISBN: `9781405698498`

Relevant mechanisms: ambiguity, misheard meaning, escalating misunderstanding and verbal timing.

### Python

**The Complete Monty Python's Flying Circus**  
ISBN: `9780679726470`

Relevant mechanisms: absurdity, structural logic collapse and institutional nonsense.

### Chaplin

**My Autobiography — Charlie Chaplin**  
ISBN: `9780141011479`

Relevant mechanisms: visual humour, empathy, adversity, recovery and surprise.

### Pratchett

**A Blink of the Screen — Terry Pratchett**  
ISBN: `9781804995877`

**A Slip of the Keyboard — Terry Pratchett**  
ISBN: `9780552167727`

Relevant mechanisms: satire, observation, wordplay and truth disguised as humour.

## Recommended first resource for the generic Thalia app

The leading candidate for `thalia-humour-app.htm` is currently:

**A Blink of the Screen — Terry Pratchett**

Reason: it provides a broad bridge between comic construction, short-form writing, satire, observation and the study of why humour works.

Before publishing a tracked link:

1. confirm availability;
2. confirm the approved affiliate programme;
3. generate the tracking URL inside that programme's dashboard;
4. add one clear affiliate disclosure beside it;
5. add `rel="sponsored nofollow"` to the link;
6. test the public `swindon.org.uk` resource page.

If no approved affiliate link is available, keep the resource page useful and publish it without tracking until verification is complete.

## Disclosure

A plain disclosure near the tracked link should say substantially:

> This page contains an affiliate link. If you buy through it, the project may receive a commission at no extra cost to you.

If Amazon UK is used, also use Amazon's currently required Associate disclosure.

## Why one link?

The aim is not an affiliate shelf.

Each human-facing app should have one relevant supporting page and that page should normally have one primary recommendation. Fewer links make the relationship between the app, the resource and the recommendation clearer, while centralising maintenance.
