# Neon Dash 3D

A self-contained, mobile-friendly endless runner prototype made with HTML Canvas, CSS, and vanilla JavaScript. No external libraries or assets required.

## Play locally
Open `index.html` in a modern browser.

## Controls
- Desktop: `←` / `→` to switch lanes, `↑` / `Space` to jump, `P` / `Esc` to pause.
- Mobile: use the on-screen buttons; swipe left/right to change lanes and tap the upper playfield to jump.

## Publish free
### GitHub Pages
1. Create a public GitHub repository, e.g. `neon-dash-3d`.
2. Upload `index.html` (and optionally this README) to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for the build and open the URL shown in the Pages section.

### itch.io
1. Zip the contents of this folder with `index.html` at the root of the ZIP.
2. Create a project on itch.io and set **Kind of project** to **HTML**.
3. Upload the ZIP, mark it playable in the browser, and enable mobile-friendly if desired.

## Prototype notes
- Scores and best score are stored in the browser's local storage on that device.
- This prototype has no server, online leaderboard, ads, purchases, or account system yet.
- It is a 3D-style perspective game drawn on a 2D canvas, not a full 3D engine build.
