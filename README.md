# Depy Music

Depy Music is a lightweight, privacy-friendly YouTube-powered music player that runs entirely in the browser. Paste any YouTube link (watch/shorts/share/ID) to add it to your Library, organize tracks into Playlists, and control playback with a clean custom UI. No backend or API keys are required—data is stored locally via the browser’s storage, so your saved links and playlists persist on the same device.
## Features
- Paste-and-play: Add YouTube links or IDs; titles and channels are fetched on the fly.
- Custom controls: play/pause, seekbar with time, ±10s/±30s skip, volume, mute, keyboard shortcuts.
- Library: Search, sort (newest, oldest, A–Z, Z–A), quick play, and remove actions.
- Playlists: Create, add from Library, reorder, remove, and auto-advance; showcase grid to jump in fast.
- Local persistence: Uses browser storage for Library and Playlists; no accounts or servers.
- Minimal YouTube chrome: Uses parameters to reduce branding and related content while staying compliant.
- Keyboard shortcuts: Space/K play-pause, J/L or ←/→ seek ±10s, Shift+←/→ ±30s, ↑/↓ volume.

## Getting started
- Local development: Serve the folder with any static server (for example, a simple HTTP server) and open index.html in your browser.
- Usage: Paste a YouTube link → Add → Play. Use the right panel to manage Library and Playlists.

## Notes
- Autoplay with sound requires a user interaction due to modern browser policies.
- YouTube branding and related content can be minimized but not removed entirely by design.

## Quick start
- Local server:
  - Node: `npx http-server . -p 8080` → http://localhost:8080
  - Python: `python -m http.server 8080` → http://localhost:8080
- Open `index.html`, paste a YouTube link, click Add.

## Deploy to GitHub Pages
1. Create a repo on GitHub, e.g., `depy-music`. Initialize with a README.
2. Upload `index.html` (and this README, LICENSE).
3. Repo → Settings → Pages → Source: `main` branch → Save.
4. Wait for deploy, then open: `https://<username>.github.io/depy-music/`.

## Notes
- Autoplay with sound requires user interaction per modern browser policy.
- YouTube branding/related content is minimized (rel=0, modestbranding=1), not fully removable.

## License
MIT

