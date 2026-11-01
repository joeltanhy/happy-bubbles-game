# HAPPY BUBBLES — Easy GitHub Upload Edition

All required game files are in **one folder** and use same-directory paths. No subfolders needed.

## Upload on GitHub
1. Create a public GitHub repository (e.g. `happy-bubbles`).
2. Open **Add file → Upload files**.
3. Open this unzipped folder, **select all 11 files inside** and upload them together, not the ZIP file. Ensure `index.html` is in the repository root.
4. Commit the changes.
5. Repository **Settings → Pages → Build and deployment → Deploy from a branch**, select branch `main`, folder `/(root)`, Save.
6. Your URL will typically be `https://YOUR-USERNAME.github.io/happy-bubbles/`.

## Controls
On mobile, drag the left virtual joystick to walk and press the right action button to collect cards or play selected cards. Walk into sick bubbles to begin a conversation. On desktop, use WASD/arrow keys and Space/Enter.

## Files
`index.html`, `styles.css`, `game.js`, and `dialogues.js` power the game. `card-*.webp` are the four card artworks; `icon.svg` is the icon; `manifest.webmanifest` enables standalone display.

All interactions come from the Happy Bubbles v2 workbook. Distress is an illustrative game mechanic, not a clinical scale.
