# Claude Games

Browser games built with Claude, published as a GitHub Pages site.

**Play:** https://garchomp67.github.io/claude-games/

| Game | Folder |
|---|---|
| Wildgrove Tamers | [`wildgrove-tamers/`](wildgrove-tamers/) |

## How the site is laid out

```
index.html              landing page that lists every game
.nojekyll               tells GitHub Pages to serve files as-is
wildgrove-tamers/
  index.html            the game (one self-contained file)
  thumbnail.png         1200x630 card image
  README.md
```

## Adding a new game

1. Make a folder named after the game, e.g. `my-new-game/`, with an `index.html` inside.
2. Add a `thumbnail.png` (1200x630) to that folder.
3. Add an entry to the `GAMES` list near the bottom of the root `index.html`:
   ```js
   { path: 'my-new-game/', title: 'My New Game', blurb: 'One or two sentences.', tags: ['Puzzle'], thumb: 'my-new-game/thumbnail.png' }
   ```
4. Commit and push. GitHub Pages redeploys in about a minute.

## Turning on GitHub Pages (one time)

Repo **Settings → Pages → Build and deployment**: Source **Deploy from a branch**, Branch **main**, folder **/ (root)**, then Save.
Note: Pages on a private repository needs a paid GitHub plan; on a free plan, make the repo public first.

## Saves

Each game saves progress in the browser's localStorage, keyed to the site's address. Progress from the claude.ai version does not carry over to the Pages site.
