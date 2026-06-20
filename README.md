# PacMAGA

A ten-level political-satire arcade game built on the bones of classic Pac-Man.
Single self-contained `index.html` — HTML + Canvas 2D + WebAudio, no build step,
no external assets, no network calls.

## Play locally
Open `index.html` in any modern browser (or serve the folder over a static HTTP
server, e.g. `python3 -m http.server`).

## Deploy (Netlify)
This is a zero-build static site. In Netlify:
- **Build command:** _(none)_
- **Publish directory:** `.` (repo root)

`netlify.toml` already encodes those settings, so connecting this repo to Netlify
deploys it as-is. `index.html` at the root is served directly.

## Controls
Arrow keys / WASD to move · `P` pause · `M` mute.
