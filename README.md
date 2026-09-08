# Howey · Chapel Lane — 3D World Model

3D terrain world model of Howey village, near Llandrindod Wells, Powys, Wales (LD1 5PS).

## What it is

- Real terrain from SRTM elevation data (~1.7 km × 1.1 km region, 150 m of relief sampled at ~4 m/cell)
- 690 building footprints from OpenStreetMap, extruded with estimated heights
- Satellite imagery (Esri World Imagery, zoom 17) draped over the terrain
- All 72 OSM roads in the area extruded, including Chapel Road and the Brynteg estate road
- Three Blender cameras: overview, close-up of the house at 52.220073, -3.388496, and street level

## Files

| File | Purpose |
|------|---------|
| `index.html` | Site page: interactive viewer + render gallery |
| `assets/howey-terrain.glb` | Interactive 3D model (model-viewer) |
| `assets/howey-terrain.blend` | Original Blender project |
| `assets/overview.png/jpg`, `closeup.png/jpg`, `street.png/jpg` | Photorealistic Cycles renders (4K) |

## Attribution

- Elevation: SRTM (public domain via AWS Open Data / Mapzen Skadi tiles)
- Buildings & roads: © OpenStreetMap contributors, ODbL
- Imagery: Esri World Imagery
- Built with Blender 5.2.1 (Cycles, OpenImageDenoise)touched
