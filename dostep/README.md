# DoStep

Browser-based viewer for `.stp` / `.step` 3D models. Files are parsed locally in the browser with OpenCascade (occt-import-js); nothing is uploaded.

## Controls
- Left drag: rotate
- Right drag: pan
- Wheel: zoom
- F: fit model

## Files
- `index.html`: the viewer
- `occt-import-js.wasm`: OpenCascade STEP import engine (must stay next to index.html)
- `license.*.txt`: third-party licenses (OpenCascade is LGPL 2.1, keep these in the repo)

## Hosting
GitHub Pages: Settings > Pages > Deploy from a branch > `main` / root.
