# Thalia Humour App — Help

This document explains the human-facing [`thalia-humour-app.md`](thalia-humour-app.md).

## What happens when the app is loaded?

The AI should:

1. initialise the Thalia Humour App;
2. display a short HELP menu;
3. create one new joke itself;
4. avoid searching for or retrieving a stored joke;
5. optionally ask for a 1–10 rating or brief feedback;
6. adapt later attempts from feedback; and
7. request the 08:00 daily AI joke where the host genuinely supports scheduled tasks.

If the host requires confirmation before creating a recurring task, it should ask. It must never pretend a task exists.

## Useful commands

- `HELP`
- `JOKE`
- `JOKE [topic]`
- `WHY IS THIS FUNNY?`
- `PATTERN [name]`
- `READ THE ROOM`
- `RATE [1-10]`
- `DAILY ON`
- `DAILY OFF`
- `ABOUT`
- `RESOURCE`

## Protocol references

- Aletheia Protocol: https://github.com/karstenevans/Aletheia-protocol
- Thalia Protocol: https://github.com/karstenevans/thalia-protocol

## Supporting resource

The app's permanent resource page is:

https://swindon.org.uk/resources/thalia-humour-app.htm

Public affiliate recommendations belong on that page, not inside the standalone app. Project funding details are kept separately in [`SUPPORT.md`](SUPPORT.md).
