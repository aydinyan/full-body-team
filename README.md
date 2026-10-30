# Full Body Team Hub

Training hub for the Full Body Team: the Aug – Oct 2026 block results, the team dashboard, and the periodised
Nov 2026 – Jan 2027 program with animated exercise cards, per-member weights and English / Armenian text.

Live: https://aydinyan.github.io/full-body-team/

## Install on a phone

- **iPhone:** open the link in Safari → Share → **Add to Home Screen**.
- **Android:** open the link in Chrome → menu → **Install app** / **Add to Home screen**.

It opens full-screen with its own icon and works offline after the first visit.

## Files

- `index.html` – the whole app in one file (no build step).
- `manifest.webmanifest`, `icons/` – home-screen name, colours and icons.
- `sw.js` – offline support. Bump `VERSION` in it when the icons or manifest change.

## Updating

Edit `index.html` and push to `main`; GitHub Pages republishes within a minute and installed apps pick it up on next open.
