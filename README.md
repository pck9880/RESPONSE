# RESPONSE

Free browser-based Phaser 3 prototype for a dystopian idle exploration game.

## Play
Once GitHub Pages is enabled (Settings → Pages → Build and deployment → GitHub Actions):
https://pck9880.github.io/RESPONSE/

## Development
- `index.html`: Phaser 3 portrait prototype, modular isometric platform / terminal / player, dialogue choice buttons, local browser save.
- `.github/workflows/pages.yml`: deploys static site to GitHub Pages on every push to `main`.

Phaser is loaded from an online CDN. Browser localStorage is per device; this build does not include cloud saves.
