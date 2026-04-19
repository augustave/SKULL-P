# SKULL-P · Mortem Archivum

A real-time WebGL studio that animates an archival photograph with churning storm clouds, pulsing ember eyes, lightning flashes, drifting dust, film grain, and vignette.

## Live

https://augustave.github.io/SKULL-P/

## Features

- **Drag-and-drop** any image to animate it
- **Click-to-place** storm center and ember eye points
- **8 effect sliders** — storm, turbulence, ember, lightning, dust, grain, vignette, eye size
- **Presets** saved to localStorage
- **PNG screenshot** + JSON settings export
- **Fullscreen**, play/pause, FPS meter
- **Keyboard shortcuts** (press `?` in-app)

## Keyboard

| Key | Action |
|-----|--------|
| Space | Play / pause |
| F | Fullscreen |
| S | Screenshot |
| M | Toggle markers |
| C | Place storm center |
| 1 / 2 | Place eye 1 / eye 2 |
| R | Reset to defaults |
| Esc | Cancel placement |

## Stack

Pure WebGL 1.0 + vanilla JS. No build step, no dependencies. Single self-contained HTML file with the default image embedded as base64.

## Files

- `index.html` — main studio app
- `skull_webgl_v2.html` — earlier single-shader version
- `mortem_archivum.html` — fully generative p5.js interpretation (no source image needed)
- `mortem_archivum.md` — algorithmic philosophy write-up
