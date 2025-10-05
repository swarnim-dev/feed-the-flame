# Feed A Flame

A small browser game about keeping torches lit and managing light. Open `index.html` in a modern browser to play.

## Overview
- **Genre**: 2D browser game
- **Platform**: Web (desktop)
- **Stack**: HTML, CSS, JavaScript (no build step)

## Gameplay
- Explore the map and interact with torches.
- Keep torches lit to extend visibility and survive longer.
- Light management is central to progression.

## How to Run
1. Clone or download this repository.
2. Open `index.html` directly in a modern browser (Chrome, Firefox, Edge, Safari).
   - macOS: right‑click `index.html` → Open With → your browser
   - Or start a local server (optional):
     - Python 3: `python3 -m http.server 8080`
     - Node: `npx http-server -p 8080`
3. The game uses static assets from the `assets/` directory.

## Controls
- Keyboard and mouse/trackpad. Specific bindings may be shown on a start/help screen or are inferred in‑game.

## Project Structure
```
/assets           // images, sprites, audio, fonts
index.html        // game entry point and scripts
```

## Development Notes
- No bundler required; edit files and refresh the browser.
- If `file://` asset loading is blocked by the browser, use a local HTTP server as shown above.

## Attribution
- The logic for the nearest torch calculation and torch sprite rendering was created with the assistance of AI.

## Contributing
- Issues and PRs are welcome. Please keep changes small and focused.

## License
- Unless otherwise noted in `assets/`, code is provided under the MIT License.
