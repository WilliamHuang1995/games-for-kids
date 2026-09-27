# Games for Kids

A collection of small, browser-based games I build for kids to learn through play. Each game is self-contained and runs in any modern web browser — no installs, no accounts, just open and play.

## Games

| Game | Description |
| --- | --- |
| [Quiet Express](index.html) | A gentle train game for young children. |

## Running locally

Each game is a standalone HTML file. Open it directly in a browser, or serve the folder:

```bash
npm install
npm start
```

Then visit `http://localhost:3000`.

## Deployment

The repo is set up to deploy as a static site on [Railway](https://railway.app):

- `npm start` runs [`serve`](https://www.npmjs.com/package/serve) and binds to Railway's `$PORT`.
- On Railway: **New Project → Deploy from GitHub repo → games-for-kids**, then generate a domain under **Settings → Networking**.

## Adding a new game

1. Drop a new self-contained `.html` file in the repo root.
2. Add a row to the Games table above.
3. Commit and push — Railway redeploys automatically.

## License

Made for fun and learning. Feel free to use and adapt.
