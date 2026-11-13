# Pew Pew Palace

The arcade at [pewpewpalace.net](https://pewpewpalace.net), games designed by Devin and friends.

## How this repo works

- `public/` is the live website. `public/index.html` is the arcade hub, and each game has its own folder.
- `wrangler.jsonc` tells Cloudflare to serve `public/`.
- `archive/` holds old versions. Nothing in it is published.

## Adding a game

1. Create a folder in `public/` (underscores, not spaces), and put the game's HTML file in it.
2. Add a card for it in `public/index.html`.
3. Commit to `main`. Cloudflare picks up the change and updates the site on its own.
