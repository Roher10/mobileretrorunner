# NEON DASH

A retro-synthwave endless runner for mobile. One thumb, neon grid, arcade leaderboard.

![NEON DASH](screenshots/home.png)

## Play

- **Tap the JUMP pad** (or the top of the screen) to leap over magenta blocks.
- **Tap the SLIDE pad** (or the bottom of the screen) to duck under hanging beams.
- Grab diamonds for bonus points. Speed ramps up the longer you survive.
- Beat a top-8 run and enter your initials, arcade-style. Scores persist in your browser.

Keyboard also works: **Space / ↑** to jump, **↓** to slide.

## Run it

It's a single self-contained file — no build step, no dependencies.

```bash
# just open it
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy free on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, pick your `main` branch and `/ (root)`.
4. Save. Your game goes live at `https://<your-username>.github.io/<repo-name>/`.

Add it to your phone's home screen from the browser share menu for a fullscreen, app-like experience.

## Files

| File | What it is |
|------|------------|
| `index.html` | The game — fully bundled and offline-ready. **This is all you need to deploy.** |
| `Neon Dash.dc.html` | Editable source (Design Component). Re-bundle to `index.html` after editing. |

## Tweaks

The source supports three options: **Difficulty** (Chill / Normal / Hard), **Theme** (Synthwave / Acid / Ice), and a **Scanlines** toggle.
