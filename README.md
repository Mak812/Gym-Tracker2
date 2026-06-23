# Logbook — Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. "logbook-app"), public.
2. Upload everything in this folder to the repo root — easiest via
   github.com → your repo → "Add file" → "Upload files", drag all of
   these in (keep the `icons/` folder structure intact):
   - index.html
   - manifest.json
   - sw.js
   - bundle.js
   - icons/ (the whole folder)
3. Repo Settings → Pages → Source: "Deploy from a branch" →
   Branch: main, folder: / (root) → Save.
4. Wait ~1 minute, then visit:
   https://YOUR-USERNAME.github.io/logbook-app/
5. On your phone, open that URL in Chrome.
6. Tap the ⋮ menu → "Add to Home screen" / "Install app".
7. Logbook now lives on your home screen as its own app icon —
   opens full-screen, no browser bar, works offline after first load.

Your data saves locally on your phone's browser storage. It's
separate from any version you used inside Claude — this is a fresh
start. Clearing your browser's site data for this URL will wipe it,
so don't clear site data/cache for this domain if you want to keep
your logs.
