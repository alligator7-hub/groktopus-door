# GrokTopus door
Honest floor page. Not Tauhid. No fake equity. No withdrawal control.

Live at https://alligator7-hub.github.io/groktopus-door/

## What it is
One static page (`index.html` + `styles.css`). Dark command-center look: ticker,
book tiles, the +80 bps edge gate, ticket desk, activity log, and an original octopus
with eight arms, one per real desk. Every number is a hand-labeled snapshot for the
evening of 2026-10-06 PT (written 2026-10-07 03:59 UTC). Nothing is a live feed.
Nothing is for sale. Nothing on the page moves money.

## This snapshot
- Mandate **HOLD**. A long quiet stretch on paper or live is healthy. Zero fills means the gate stayed shut.
- Forever-live: about **$44.48** USD cash, **no fills** tonight.
- Edge gate: **+80 bps** (+0.80% expected edge after costs). Same bar for paper and live. Nothing cleared it.
- Paper cash, open orders, and P&L are `—` (not read, not invented).
- Prior 2026-09-02 prices and cash figures stay in git history only. Do not paste them back onto the door.

## Locks
- No invented P&L, hit rate, Sharpe, volume, or equity curve.
- No borrowed desk names from anyone's sales reel.
- No bot funnel, no unsolicited pitch, no promised returns or leverage brags.
- No claim of autonomous live fills while the mandate is HOLD.
- No withdrawal, transfer, or deposit control, and no balance that was not read this session.
- No secrets: keys, seeds, account numbers, addresses, emails.

## Updating the snapshot
Copy `docs/STATUS-TEMPLATE.md`, fill it, then edit the numbers and the date in
`index.html` by hand. Keep the date label. If a number is not known, show `—`,
not a guess and not last session's cash.

## Deploy
`.github/workflows/pages.yml` publishes the repo root to GitHub Pages on every
push to `main` (Settings > Pages > Source: GitHub Actions).
