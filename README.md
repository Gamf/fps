# FPS — a Gamf genre

Published at <https://gamf.github.io/fps/>.

- `games.json` — the list of games in this genre (the hub reads this).
- `games/<slug>/` — one self-contained folder per game.
- `index.html` — this genre's own landing page.

FPS games use Three.js loaded from a CDN via an import map (no build step).
Touch controls: drag to look, tap to shoot. Copy
`../templates/template-3d-three/` to start. See `../docs/ADD-GAME.md`.
