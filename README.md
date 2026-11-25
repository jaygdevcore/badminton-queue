# Badminton Open Play Queue

A web app for running badminton open play and small tournaments with a group of friends.

**Live app:** https://jaygdevcore.github.io/badminton-queue/

## Features

- **Open play queue**: players with the fewest games go first, and teams are balanced by skill level (1–5).
- **Smart matching**: the app avoids putting the same partners together again and spreads out repeat opponents. There are three modes: balanced teams, same level together, and first come first play.
- **Courts board**: shows who is on each court, with a game timer and one-tap "A won / B won".
- **Up next queue**: reshuffle a match, swap players, or build a custom match.
- **Tournament mode**: doubles or singles, in three formats: round robin, round robin + playoffs, or a knockout bracket. Includes score entry, standings and a bracket view.
- **Extras**: Undo, TV display mode, copyable results, and backup/restore.
- **Works offline**: after the first load the app runs without internet, and it can be installed to the home screen.

## Install on iPhone / iPad

1. Open the link above in **Safari**.
2. Tap **Share** → **Add to Home Screen**.
3. Open it from the home screen icon.

## Install on Android

Open the link in Chrome, then tap **Install app** (or ⋮ → **Add to Home screen**).

## Data

All data is saved in the browser on the device that runs the queue. Use **Backup** / **Restore** in Settings to move a session to another device.

## Tech

This is a single `index.html` file (HTML, CSS and vanilla JavaScript). It also has `manifest.webmanifest` and `sw.js` for PWA install and offline use. No build step is needed.
