# Changelog

All notable pre-release design changes to Thalia are recorded here.

## v1.0 Draft — 24 August 2026

### Canonical protocol

- Kept the public protocol version at **v1.0 Draft / pre-release**.
- Preserved the core principle: **Jokes are examples. Humour patterns are the knowledge.**
- Clarified that Thalia is intended to help AI systems both understand humour and create new humour by mechanism transfer.
- Added/retained a practical generation loop, feedback loop and Read The Room behaviour.
- Kept daily scheduling, Help, Patreon and affiliate mechanics outside the canonical protocol.

### Human-facing app

- Renamed the standalone application to the permanent release-style stem:
  `thalia-humour-app.md`.
- On load, the app asks the AI to create a fresh joke itself rather than search for one.
- Added optional 1–10/user feedback.
- Kept the intended 08:00 local daily AI-created joke behaviour where the host genuinely supports scheduled tasks.
- Added safeguards against falsely claiming a scheduled task exists.
- Removed direct affiliate and Patreon links from the portable app.
- Added one permanent supporting-resource destination:
  `https://swindon.org.uk/resources/thalia-humour-app.htm`.

### Website/resource layer

- Confirmed `https://swindon.org.uk` as the website.
- Confirmed `https://swindon.org.uk/resources/` as the permanent resource root.
- Added `website-resources/thalia-humour-app.htm` as source for the matching public resource page.
- Kept tracked retailer URLs on the HTML resource page rather than in distributed Markdown.
- Added the current leading resource candidate, *A Blink of the Screen*, without inventing an affiliate tracking URL.

### Funding

- Kept Patreon outside the canonical protocol and portable app.
- Patreon remains available from README/support material and `.github/FUNDING.yml`.
- Patreon account: `KarstenE`.

### Assets

- Promotional images remain in the repository under `/assets/`.
- Images are not embedded in the canonical protocol or standalone app.
