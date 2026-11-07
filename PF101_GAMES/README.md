# PF101 Quiz Arena

A frontend-only programming fundamentals quiz game. It uses HTML, CSS, JavaScript, and browser `localStorage`—no server or dependencies required.

## Run on macOS

1. Open this `PF101_GAMES` folder in Visual Studio Code (`File` → `Open Folder`).
2. Open `index.html` in a modern browser. You may double-click it in Finder, or use the VS Code **Live Server** extension if installed.
3. Start a Solo Mission or a Local VS Battle. Scores remain on that browser/device.

## Files

- `index.html` — screens and accessible controls
- `style.css` — responsive neon esports design
- `script.js` — question bank, game state, timer, scoring, and local leaderboard

## Add questions

Add another object to the `questions` array in `script.js`. Supply question text (`q`), four choices (`a`), zero-based correct choice index (`c`), category (`cat`), difficulty (`d`), and explanation (`e`).
