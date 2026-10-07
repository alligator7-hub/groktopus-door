# GrokTopus door
Honest floor page. Not Tauhid. No fake equity.

Live at https://alligator7-hub.github.io/groktopus-door/

## What it is
One static page (`index.html` + `styles.css`). Dark command-center look: ticker,
book tiles, ETH ladder, ticket desk, activity log, and an original octopus with
eight arms, one per real desk. Every number is a hand-labeled snapshot dated
2026-09-02 PT. Nothing is a live feed. Nothing is for sale.

## Locks
- No invented P&L, hit rate, Sharpe, volume, or equity curve.
- No borrowed desk names from anyone's sales reel.
- No bot funnel, no unsolicited pitch, no promised returns or leverage brags.
- No claim of autonomous live fills. Mandate is SIT.

## Updating the snapshot
Edit the numbers and the date in `index.html` by hand. Keep the date label.
If a number is not known, show `—`, not a guess.

## Paper floor note
Hand stamp dated 2026-10-06 PT: **HOLD**, about **$44.48 USD**, gate **+80 bps**.
A HOLD wake stays quiet: no ping, no order. The dollar figure is rounded on purpose.
It is not exact cents, not a live balance, and not P&amp;L. This repo does not place
or change live orders. The 2026-09-02 sit book stays labeled as that date.

## Deploy
`.github/workflows/pages.yml` publishes the repo root to GitHub Pages on every
push to `main` (Settings > Pages > Source: GitHub Actions).
