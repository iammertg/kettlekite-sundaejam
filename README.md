# sundaejam.kettlekite.com

Site for Sundae Jam, a Kettlekite game. Served by GitHub Pages from `main` (domain in `CNAME`).

- `/` product page, `/support`, `/privacy`, `/terms` (the URLs App Store Connect uses).
- `assets/kk.css`, `game.css`, `game.js`, `kite.svg` and `assets/fonts/` are copied from `kettlekite-site` (`scripts/sync-shared.sh`); edit them there. `assets/theme.css` holds this game's colours.
- `assets/site.css` and `site.js` hold polish on top of the synced files (tap targets, press states, skip link, the hero film resting under reduced motion); they are the same on every game site and are not synced, so fold them into `kettlekite-site` when convenient.
- The game is out (App Store id 6824275538, from November 12, 2026): the hero carries Apple's badge (`assets/app-store-badge.svg`, the same file as kettlekite.com) and every page has the Smart App Banner meta.
- `assets/icon.png` is the app icon (`sundae-sort/unity/Assets/_Project/Art/Icon/AppIcon.png` at 256 px); `assets/media/` holds the page media: screenshots from the game's raw captures (1320 px phones, resized), the product renders as WebP and the hero recording.0.0 (5) screenshot.
- Keep `privacy.html` in step with the App Store privacy details (Data Not Collected): update it before a version that changes what the game handles ships.
