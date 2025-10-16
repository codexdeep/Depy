# Depy Music

A simple, privacy-friendly YouTube-powered music player with a local Library and Playlists. Paste a YouTube link, save it, organize into playlists, and control playback with custom UI.

## Features
- Paste-and-play any YouTube link (watch/shorts/share/ID), saved in Library with title + channel [YouTube IFrame API].
- Custom controls: play/pause, seekbar with time, ±10s/±30s skip, volume, mute, keyboard shortcuts.
- Playlists: create, add from Library, reorder, remove, auto-advance, showcase grid.
- Data persistence via `localStorage` (per browser/device).

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
