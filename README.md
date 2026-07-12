# IronGauge — offline training & nutrition tracker

A self-contained web app. No build step, no server, no database — your data
lives on your device in the browser's local storage. Works offline once
installed to your home screen.

## Files
- `index.html` — the whole app
- `manifest.webmanifest` — makes it installable to the home screen
- `sw.js` — service worker (offline caching)
- `icon-192.png`, `icon-512.png` — app icons


## Install on your phone
**Android (Chrome):** open the URL → menu (⋮) → **Add to Home screen / Install
app**. It lands on your home screen and opens like a normal app.

**iPhone (Safari):** open the URL → Share → **Add to Home Screen**.

After installing, it runs offline. Log whenever, close it, reopen — your data
stays.

## Backups
**Google Drive (recommended):** connect from Stats → Settings and the app keeps
timestamped backups in a hidden folder in *your own* Drive — private to your
account, and they survive reinstalls (especially on iPhone, where the system
can clear an unused app's storage).

**File:** Stats tab → **Export** saves all your data to a JSON file. **Import**
restores it. Works fully offline; export before any app update for safety.

## Credits
Display font: [Anton](https://fonts.google.com/specimen/Anton) by Vernon Adams, licensed under the [SIL Open Font License 1.1](https://scripts.sil.org/OFL) — see `FONT-LICENSE.txt`.
