# AGENTS.md — Thalia Protocol v1.0

## Repository roles

This repository deliberately separates protocol, application and funding/resource layers.

- `THALIA_PROTOCOL.md` — **canonical AI-facing protocol**.
- `thalia-humour-app.md` — **human-facing standalone Markdown app**.
- `website-resources/thalia-humour-app.htm` — source for the permanent supporting page at `https://swindon.org.uk/resources/thalia-humour-app.htm`.
- `AFFILIATES.md` and `SUPPORT.md` — non-normative maintainer/support material.

Do not confuse application behaviour with normative protocol behaviour.

## Canonical protocol

When analysing, implementing or testing Thalia, treat `THALIA_PROTOCOL.md` as normative.

The protocol teaches an AI to:

1. distinguish humorous content from the mechanism that makes it work;
2. identify Humour Gap, Vehicle, Engine and reconstruction;
3. use pattern families as mechanism labels rather than source material;
4. transfer mechanisms into new humour instead of merely retrieving jokes;
5. use audience feedback to improve later attempts;
6. apply Read The Room according to context, stress, sensitivity, culture and purpose;
7. explore AI-native humour as well as established human comic forms.

## Humour generation

When asked to create humour under Thalia:

- prefer original construction from mechanisms over joke retrieval;
- establish an expectation and create a reconstructable humour gap;
- preserve enough coherence for audience reconstruction;
- do not confuse randomness with humour;
- accept that a weak joke can still provide useful feedback;
- when useful, ask for a lightweight rating or what worked / failed;
- adapt later attempts rather than repeating the same pattern.

Pattern labels such as Barker-Corbett, Python, Chaplin and Pratchett are analytical shorthand. Do not reproduce substantial copyrighted source text or treat the labels as instructions to imitate a creator's exact style.

## Human-facing app

If the user explicitly loads or asks to run `thalia-humour-app.md`, follow that app's interaction instructions.

The app may include features that are **not protocol requirements**, including:

- a HELP menu;
- immediate original joke generation;
- optional joke rating / feedback;
- optional daily 08:00 joke scheduling where the host supports genuine scheduled tasks;
- one permanent supporting-resource link.

Never claim a recurring task was created unless the host actually created it.

## Resource-link invariant

The human-facing app uses:

- one Aletheia Protocol reference;
- one Thalia Protocol reference; and
- exactly one `swindon.org.uk/resources/` supporting-resource destination.

For the current app:

`https://swindon.org.uk/resources/thalia-humour-app.htm`

Do not insert direct Amazon, Bookshop.org, Libro.fm, Awin, Kobo, Waterstones or other tracked retailer links into the human-facing app.

Tracked affiliate URLs belong on the matching website resource page.

## Companion protocol

For persistent memory, evidence, provenance, claim/conflict tracking, decisions or handover, use Aletheia rather than inventing those functions inside Thalia:

https://github.com/karstenevans/Aletheia-protocol

## Commercial neutrality

Affiliate mechanics, sponsor links and Patreon are non-normative.

They may appear in repository README/support material, GitHub funding configuration and appropriate website resource/support pages, but must not alter `THALIA_PROTOCOL.md`, protocol definitions, test outcomes or analytical conclusions.

## Versioning

Keep the public version at **v1.0 Draft / pre-release** until the first release is intentionally issued.
