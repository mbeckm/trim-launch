# Trim launch board

Source of truth for getting **Trim Workout** on the App Store and turning on paid ads.

Live page: https://mbeckm.github.io/trim-launch/

## How to update
Edit `index.html`. Each row is a `<tr>` with `data-status="done|next|blocked|later"`.
Flip the status, keep the estimate honest, note blockers in the last cell.
Commit and push to `main`. Pages updates in about a minute.

Do not put secrets, API keys, or RevenueCat tokens here.
The iOS app itself stays local (`Documents/workout tracker app/mobile`) until Marvin says otherwise.

## Owners
- **Marvin** — Apple, tax, keys, device testing, ad accounts
- **Ventury** — this board, listing copy, legal site, monetization calls
- **Designy** — screenshots, paywall/onboarding visuals
