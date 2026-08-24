# Thalia Resource-Link Architecture

**Status:** v1.0 Draft implementation rule  
**Website:** https://swindon.org.uk  
**Resource root:** https://swindon.org.uk/resources/

## Layer separation

### Canonical protocol
`THALIA_PROTOCOL.md`

AI-facing protocol only. No affiliate or Patreon mechanics. No daily-joke app behaviour.

### Human-facing app
`thalia-humour-app.md`

Interactive app for AI users. It may include HELP, joke generation, feedback and daily scheduling behaviour.

It contains:

1. one Aletheia Protocol reference;
2. one Thalia Protocol reference; and
3. exactly one supporting-resource destination.

It must not contain a tracked retailer URL.

### Matching website resource
`https://swindon.org.uk/resources/thalia-humour-app.htm`

Contains useful original explanatory content and may contain one disclosed tracked affiliate recommendation.

### Project support
Patreon may appear in GitHub profile/Funding, README, SUPPORT.md and appropriate website footer/support material:

https://www.patreon.com/KarstenE

## Filename invariant

```text
thalia-humour-app.md
        |
        | one stable resource reference
        v
https://swindon.org.uk/resources/thalia-humour-app.htm
```

The stem is permanent after public release. Versions belong inside document metadata, not in the filename.

## Affiliate maintenance rule

Changing retailer, recommendation or tracking URL should normally require editing only the matching HTML resource page.

Distributed Markdown copies continue pointing to the stable Swindon URL.
