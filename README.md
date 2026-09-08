# Clawdd Glas · Howey — 3D World Model

Photorealistic 3D world model of Clawdd Glas, Howey, near Llandrindod Wells, Powys, Wales (LD1 5PS).
Half-mile (805 m) radius. Live site: https://dylan10028guy-2045.github.io/howey-chapel-lane/

## What it is

- Real SRTM elevation terrain (1.1 km × 1.5 km, ~72 m of relief) draped with Esri World Imagery satellite tiles (zoom 17)
- 690 building footprints from OpenStreetMap: rendered/brick facades with windows, slate gable roofs on houses, slate caps on larger blocks
- ~230 reconstructed trees, country lanes in asphalt, draped onto the terrain
- HDR daylight (Poly Haven, CC0) + sun, three Blender cameras: overview, Greenbanks close-up, street level
- Interactive Three.js viewer: orbit, street-level walk (WASD), fly-around tour, Daylight / Late afternoon / Blue hour, Balanced / Ultra HD, 4K photo capture

## Files

| File | Purpose |
|------|---------|
| `index.html` + `viewer.js` + `style.css` | Interactive tower-style viewer (Three.js via CDN) |
| `assets/howey-terrain.glb` | Interactive 3D model with embedded PBR textures |
| `assets/howey-terrain.blend` | Original Blender project |
| `assets/site-info.json` | Building footprints (walk-mode collision), bounds, spawn |
| `assets/daylight.hdr` | Environment lighting (Poly Haven, CC0) |
| `assets/howey-ground.jpg` | Stitched satellite ground texture |
| `assets/overview.png/jpg`, `closeup.png/jpg`, `street.png/jpg` | Cycles renders + posters |

## Attribution

- Elevation: SRTM (public domain)
- Buildings & roads: © OpenStreetMap contributors, ODbL
- Imagery: Esri World Imagery
- Daylight HDR: Poly Haven (CC0)
- Built with Blender 5.2.1 (Cycles, OpenImageDenoise)
