# Wasteland Duel

A retro post-apocalyptic, PVP-style Tetris game that runs entirely in the browser. No build step, no dependencies.

## Play

- **Local 2-player:** two people share one keyboard.
- **vs CPU:** easy, normal or hard.

## Controls

| Action | Player 1 | Player 2 |
|---|---|---|
| Move | A / D | Left / Right |
| Rotate | W | Up |
| Rotate back | Q | / |
| Soft drop | S | Down |
| Hard drop | Space | Enter |
| Hold | E | Right Shift |

In vs CPU mode, you can use either set of keys. Esc returns to the menu.

## Rules

- Clearing lines sends garbage ("rubble") to your opponent: double = 1, triple = 2, quad = 4, plus combo and perfect-clear bonuses.
- Clearing lines while garbage is pending cancels it first.
- Gravity speeds up the longer a match runs.
- Last one standing wins.

## Deploy with GitHub Pages

1. Create a new repository and upload `index.html` and `README.md` to the root.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute your game will be live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- The pixel font ("Press Start 2P") loads from Google Fonts. Without internet it falls back to a monospace font.
- Online play is not implemented yet.
