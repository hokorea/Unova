# Unova — 3D Flight Prototype

A small, browser-based 3D flight experiment with a procedurally generated town, forest, river, and simple flying vehicle.

This is an **unofficial, non-commercial fan experiment**. No Pokémon/Nintendo character models, maps, music, or textures are included. This notice does not imply endorsement or grant any rights.

## Play

After GitHub Pages is enabled: https://hokorea.github.io/Unova/

## Controls

- **Desktop:** W/S or ↑/↓ to move forward/back; A/D or ←/→ to turn; E/Q to ascend/descend.
- **Mobile:** Left virtual joystick to move and turn; right buttons to ascend/descend.

## Local development

Serve this folder over HTTP (ES modules cannot reliably load from `file://`):

```bash
python -m http.server 8000
```

Then open http://localhost:8000. Internet access is required to load Three.js from jsDelivr.

## GitHub Pages

Go to **Settings → Pages → Build and deployment → Deploy from a branch**, choose **main** and **/(root)**, then save.

## Roadmap

- [x] Basic 3D environment
- [x] Third-person flight camera
- [x] Mobile touch controls
- [ ] Performance and collision improvements
- [ ] More detailed original environments
