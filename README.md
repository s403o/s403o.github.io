# s403o.github.io

Personal site of Eslam Adel — https://s403o.github.io

A single static page (`index.html`), no build step. `.nojekyll` tells GitHub Pages to serve files as-is. The "Recently active" section loads repositories from the GitHub API in the browser.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `master`. GitHub Pages publishes from the repository root.
