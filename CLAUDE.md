# India Trip Planner 2026 — Arakkal Family

## What this is
A single-file HTML/JS trip planner for a family India trip (23 Apr – 27 May 2026).
Deployed via GitHub Pages at: https://aara1602.github.io/India-2026-Trip-planner

## Stack
- Pure HTML/CSS/JS — single file: index.html
- Firebase Realtime Database for persistent storage (real-time sync across family devices)
- No build step, no npm, no frameworks — just the one file

## Firebase
- Project: india-2026
- Database path: trips/arakkal2026/plans/{dateKey}
- dateKey format: YYYY_M_D (e.g. 2026_3_23)
- API key is domain-restricted to github.io — do not log or expose it

## Deployment
- git push to main → GitHub Pages auto-deploys in ~2 mins
- Always commit with a clear message describing the UI change

## Preferences
- Keep everything in index.html — do not split into separate CSS/JS files
- Mobile-first — test that changes don't break the slide-up panel on small screens
- Preserve existing colour variables (--saffron, --navy, --teal, --gold)