# theloyaltrojan.github.io

My GitHub user site. Two jobs:

- **`index.html`** — a landing page for [Hardwood Legends](https://github.com/theloyaltrojan/hardwood):
  what it is, what you can play, how it was built, and the controls. Plain HTML and CSS, no build step,
  no dependencies. Screenshots in `img/` are captured straight from the game.
- **`ads.txt`** at the host root, which is the only place ad crawlers look for it. The game is a project
  site at [/hardwood](https://theloyaltrojan.github.io/hardwood/), so the copy in that repo never gets
  read — this one does. Keep the publisher id here in sync with `CONFIG.ads.client` in the game.
