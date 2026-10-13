# RESPONSE — THE WORLD IS SILENT

Free Phaser 3 browser-based dystopian isometric idle/life-survival game prototype.

**Playtest:** https://pck9880.github.io/RESPONSE/

## Current build
- Phase 003: 12×5 abandoned subway-car isometric scene with 11 independently loadable transparent PNG assets under `assets/pixel/`.
- Existing choice buttons (`주변 살피기`, `휴대폰 확인`, `일어나기`) and legacy `response_save_v1` localStorage retained.
- Tap car facilities for preview descriptions. Detailed survival mechanics are *planned*, not currently playable.
- `assets/layout.json`: asset dimensions/anchors and planned waypoints.
- `docs/DEVELOPMENT_STATE.md`: **source of truth for planned systems and development continuity**. Read first when resuming in another chat.

## Deploy
Push to `main` triggers `.github/workflows/pages.yml` (GitHub Pages). Phaser loaded from a CDN.

## License
Prototype art/assets were created for the RESPONSE project. Third-party Phaser retains its own license.
