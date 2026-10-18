# Bloom — Women's Exercise Library

Equipment-free strength, bone health, balance, mobility and pelvic floor training for women, in English and Arabic. Installable on phones and works offline.

## Live app

Hosted with GitHub Pages:
**https://darkoflight001.github.io/Bloom---Women-s-Healthy/**

Open the link on your phone, then:
- **iPhone (Safari):** Share → *Add to Home Screen*
- **Android (Chrome):** menu ⋮ → *Install app* / *Add to Home screen*

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole app (layout, content, logic) |
| `sw.js` | Service worker for offline use |
| `manifest.webmanifest` | App name, colours and icons for installing |
| `icon-*.png`, `apple-touch-icon.png` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Updating the app

Replace `index.html`, then bump the cache version in `sw.js` (`bloom-v1` → `bloom-v2`) so installed copies pick up the change.
