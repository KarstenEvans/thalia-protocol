---
title: "Thalia Humour Base | Browser index reconstruction specification"
version: "0.1.0"
status: "COMMITTED SOURCE / BROWSER QA PENDING"
reviewed: "2026-10-31"
---

# Thalia Humour Base | Browser Index

[Aletheia Protocol](https://github.com/KarstenEvans/aletheia-protocol) governs provenance, evidence and uncertainty; [Thalia Protocol](https://github.com/KarstenEvans/thalia-protocol/blob/main/THALIA_PROTOCOL.md) governs humour cognition, originality and Read The Room.

## Purpose and scope
A simple browser interface for the reusable `humour-base/*.md` methods. **Choose a pattern → create one original joke → hear it.** No copied routines and no reproduction of real performers' voices. The library's Markdown methods remain the intellectual content; HTML is only an optional user interface.

The existing `thalia-humour.htm` human-facing app and `KarstenEvans/aletheia-app/aletheia-humour/sketches/` remain unchanged. The latter contains separate game-style sketch experiences. Aletheia-QI OPT2/OPT3 supplied ideas, not an installed provider adapter here.

## Source of truth
- `humour-base/README.md`: human research catalogue / provenance.
- `humour-base/patterns.json`: explicit machine-readable index with five published Markdown method paths.
- `humour-base/*.md`: patterns, not audio or runtime code.
- `humour-base/index.html`: static browser interface, with five hardcoded anchor/button fallbacks if manifest cannot be fetched.
- `THALIA_PROTOCOL.md`, `AGENTS.md`, `thalia-humour-app.md`: authoritative scope and behaviour.

**Static rule:** GitHub Pages cannot enumerate repository folders in a browser. Update both `patterns.json` and the HTML's fallback cards when a new method is published. Never invent a missing method or rely on an unauthenticated public GitHub API directory call for normal site use.

## Screen and interaction
1. Header explains patterns, originality, and the three-action KISS workflow.
2. Five cards, each with *Use this pattern* and a direct **Read .md** link. Selecting fetches the chosen local Markdown as untrusted research data; failures show a useful status and retain a compact-summary prompt.
3. Optional topic input. **Prepare request** constructs a prompt for exactly **one** original 80–160 word joke. **Copy request** uses clipboard when permission allows; fallback selects text manually. Plain links to independent AI services.
4. **Try local Chrome AI (experimental)** is user-initiated, tests `window.LanguageModel`, checks availability, asks permission before a model download, and attempts a single draft; it has no web-research guarantee, never assumes factual verification and clearly reports unavailable/failures. An extracted short method excerpt is used to limit context. No API keys.
5. **Tell it** accepts pasted or on-device-generated text, offers installed speech voice, rate, speak/pause/resume/stop. Uses browser `SpeechSynthesisUtterance` and reports errors and unsupported platforms. No voice cloning, no audio blobs.
6. Footer links back to Thalia app, protocols, Base README and existing Aletheia sketches.

## Data and security
The selected Markdown is fetched from same-directory `*.md`, added as **quoted research content**, not executable instructions. Only files present in the hardcoded fallback catalogue may be selected. Text is displayed with `textContent` / textarea values, not inserted as HTML. No user data leaves the page without an explicit copy/open/provider action. Browser local Chrome AI model may download if user consents. The browser may invoke speech services provided by the OS; this page makes no promise that speech is always offline.

There is **no Cloudflare Worker integration**: no verified endpoint, authentication/cost controls or cross-origin permissions were supplied. Future OPT3-style integration would require explicit review, a public API contract, safe origin controls, request limits, financial exposure limits, host-side secrets, and live tests. Do not place credentials in static HTML.

## Acceptance checks
- `index.html` exists and uses the exact five Markdown names in `patterns.json`; all method files exist in the current Git tree.
- Inline JavaScript syntax parses and static links point to existing repo paths.
- Selecting a pattern sets its name and shows the appropriate Markdown when hosted over HTTPS; if the fetch fails, compact fallback produces a usable prompt.
- Copy works in HTTPS contexts or selects text for a manual copy.
- Clicking Chrome AI without a supported engine gives a clear explanation, not a claim of generated output; single-job guard blocks double requests.
- No AI service is called merely by opening the page. No automatic background model download. No third-party script or API key.
- Speech is user-triggered and pause/resume/stop controls are wired; unsupported voices produce clear status.
- Mobile touch controls, keyboard operation, readable contrast, focus indicators, and reduced-motion behaviour.
- Live Pages deployment, Chrome AI on-device behaviour, speech on Android and iPhone, and actual Cloudflare integration are **NOT TESTED**.

## Change receipt and resume
31 October 2026: source indexed and HTML created in `KarstenEvans/thalia-protocol` on branch `main`. Original five methods unchanged. KISS workshop adds browser access without altering normative Thalia protocol, shared Aletheia GUI, QI experimental runtime or any existing sketch. Future Aletheia Humour landing page can **link** to the Thalia Base rather than copying its engine. Do not modify working sketches or connect Cloudflare without explicit project-specific review.
