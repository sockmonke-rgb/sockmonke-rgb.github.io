# sockmonke-rgb.github.io

The home page at **https://sockmonke-rgb.github.io**: a list of the games and tools in this account, each with a Play link to its own GitHub Pages site and a link to its source.

It's one hand-written `index.html` with no build step. `favicon.svg` is the capybara's helmeted head. `.nojekyll` tells GitHub Pages to serve the files as they are.

## Adding a game

1. Turn on GitHub Pages in the game's own repo (Settings → Pages), so it's playable at `https://sockmonke-rgb.github.io/<repo>/`.
2. In `index.html`, copy one `<article class="game">` block into the Games or Tools list and change its name, description, links and `--spine` colour (use the game's own accent colour; `--spine-dark` is optional, for dark mode when the colour is too dark to see).
   Each card has a screenshot: save a 16:9 one, 800×450 JPEG, as `thumbs/<repo>.jpg` and point the block's `<a class="thumb">` at it.
3. Update the date in the footer, and bump the version in `<div class="build">` (the small mark in the bottom corner), so you can tell at a glance whether your phone has the newest page.

Pushes to `main` go live within a few minutes.
