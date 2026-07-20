# NEON JACKPOT SCI-CALC 🎰🧮

A scientific calculator whose results are revealed through a neon casino jackpot show: roulette, slot reels, holographic result panels, particles, shockwaves, synthesized music, and zero house edge.

## Live site

`https://prefix9671.github.io/neon-jackpot-calculator/`

GitHub Pages must be configured once with **Settings → Pages → Deploy from a branch → main → /(root)**.

## Highlights

- Scientific calculator with a whitelist-based expression parser
- DEG/RAD modes, trigonometry, logarithms, factorials, memory, ANS, and history
- Jackpot result sequence with slot reels, roulette, coins, confetti, fireworks, and synthesized sound
- Fully client-side and static-hosting friendly
- No third-party music, images, fonts, or runtime CDN dependencies
- Responsive desktop, tablet, and mobile UI

## Deployment structure

- `index.html`: GitHub Pages entry point and verified package loader
- `bootstrap/payload-*.txt`: chunked static deployment ZIP
- `.nojekyll`: disables Jekyll processing
- `ASSET_LICENSE.md`: generated audio and asset declaration
- `.github/workflows/bootstrap-static-site.yml`: optional workflow that can reconstruct the original `index.html`, `styles.css`, and `app.js` files

The browser loader rebuilds the package locally, extracts the original HTML/CSS/JavaScript, and starts the calculator. No server-side runtime is required.

## Integrity

Static deployment ZIP SHA-256:

`4a5cb9cf3fc4a43bc90ca37ef1b6c49d4b6bc9720fc4642869356345ca585110`
