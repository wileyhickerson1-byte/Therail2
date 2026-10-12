# The Rail — Home Game Poker Ledger

A standalone, installable, offline poker tracker for home games.
Your data is stored on your own device (never uploaded anywhere).

## Put it online (free, ~3 minutes) with GitHub Pages

1. On GitHub, create a new repository (e.g. `the-rail`). Public is fine.
2. Upload EVERY file and folder from this package to the repo root:
   index.html, app.js, manifest.webmanifest, service-worker.js, and the
   `icons` folder. (Drag them into the "Add file → Upload files" box, or
   `git add . && git commit && git push` if you use git.)
3. Repo → Settings → Pages → under "Build and deployment", set
   Source = "Deploy from a branch", Branch = `main`, folder = `/ (root)`. Save.
4. Wait a minute, then open the URL it gives you
   (https://<your-username>.github.io/the-rail/).

## Install on your iPhone

1. Open that URL in **Safari**.
2. Tap the Share button → **Add to Home Screen**.
3. Launch it from the home-screen icon. It now runs full-screen and works
   offline. Data lives on the phone.

## Moving data between devices

Settings → **Back up everything (JSON)** saves a file. On another device,
Settings → **Restore from backup** loads it. Do this occasionally as a safety net.
