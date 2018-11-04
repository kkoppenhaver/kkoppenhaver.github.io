Use `gulp serve` to run the site locally.

When you want to deploy:
  - `gulp`
  - `rm -r dist/images`
  - `cp -r app/images dist/images`
  - `rm index.html`
  - `cp dist/index.html index.html`
  - Find and replace `images/` with `/dist/images/` in index.html
  - Find and replace `styles/` with `/dist/styles/` in index.html
  - Find and replace `scripts/` with `/dist/scripts/` in index.html