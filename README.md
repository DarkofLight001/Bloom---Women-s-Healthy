# Bloom — Women's Exercise Library

Equipment-free strength, bone health, balance, mobility and pelvic floor training for women, in English and Arabic (full right-to-left support). Installable on phones and works offline.

## Live app

Hosted with GitHub Pages:
**https://darkoflight001.github.io/Bloom---Women-s-Healthy/**

Open the link on your phone, then:
- **iPhone (Safari):** Share → *Add to Home Screen* (open it once while online so it saves itself for offline use)
- **Android (Chrome):** menu ⋮ → *Install app* / *Add to Home screen*

## What's inside

- **105 illustrated exercises** with animated demonstrations, in 10 categories and 4 levels, no equipment needed
- **Routines (23):** quick routines, full sessions, cycle-friendly sessions, lower-body and pelvic floor routines, and 7 weekly plans
  - Swap any exercise in seconds (swipe or ‹ ›), browse alternatives by level, matched to the same movement
  - Favourites, save your own versions, rename, duplicate, reset to original
  - Adapt a whole routine to a target level
  - Workout mode with set tracking, rest timer and history
- **Your cycle and exercise:** evidence-rated guidance for each phase, what often helps or feels worse for each symptom, an optional daily check-in that can lighten today's routine, and when to see a doctor
- **Find your starting point:** profile answers (pregnancy, osteoporosis, falls, pelvic symptoms…) hide unsuitable exercises
- **Guide and safety** pages with 72 cited references

All progress, favourites and saved routines stay on the device; nothing is sent anywhere.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole app (layout, content, logic) |
| `sw.js` | Service worker for offline use |
| `manifest.webmanifest` | App name, colours and icons for installing |
| `icon-*.png`, `apple-touch-icon.png` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Updating the app

Replace `index.html`, then bump the cache version in `sw.js` (currently `bloom-v2` → `bloom-v3`) so installed copies pick up the change.

## Disclaimer

General education for adult women, not individual medical advice.
