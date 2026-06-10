# RingRing.now — The Open Room (static demo)

A self-contained, single-file prototype of **RingRing.now** — a real-time multilingual web conferencing concept where each person speaks their own language and is understood live, ideally in their own voice.

This is the **"The Open Room"** UI direction: a bright, human-centred dashboard application (not a marketing site) with a circular-bubble live workspace, a trust-first pre-call ceremony, and dual-language verification.

## What this is
- A static `index.html` (HTML + CSS + vanilla JS, no build step).
- A **demo / prototype** — there is no real backend, media, or translation engine.
- All people, recents, scheduled rooms, and transcript text are **illustrative placeholders**. No real metrics, accuracy scores, or compliance claims are made.

## Screens
- **Dashboard** — Workspace, Current Room, Readiness, and Scheduled cards.
- **Pre-Call Studio** — device check, language mirror, voice mode, readiness (Join is open in this demo).
- **Voice Consent** — affirmative, unbundled, revocable.
- **Live Workspace** — circular bubbles, breathing "translating" pulse, dual-language transcript (with transcript-forward mode), language dock, participants, chat.
- **Trust & Settings.**

## Run locally
Open `index.html` directly, or serve the folder:
```
python3 -m http.server 3000
```

## Deployment
Deploys to GitHub Pages via `.github/workflows/deploy.yml` on push to `main`.
