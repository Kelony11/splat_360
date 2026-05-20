# Splat360 🫟

**Splat360** is a browser-based immersive graphics project built with **Three.js** and **3D Gaussian Splatting**. It features a 360 panorama viewer, 360 video playback on a sphere, custom UV mapping on a cube, and a hybrid splat scene with added colored geometry.

## Features
- 360 image viewer with sphere and box modes
- Adjustable tessellation for sphere quality comparison
- Custom cube UV mapping using a texture atlas
- 360 video playback with `THREE.VideoTexture`
- 3D Gaussian splatting truck scene
- Added hybrid geometry with colored cubes inside the scene
- Multiple render modes: Point, Ellipsoid, and Splat

## Tech Stack
- HTML
- JavaScript
- Three.js
- Gaussian Splatting

## Run
Use **Live Server** in VS Code and open:
- `hw3_360.html`
- `hw3_360_video.html`
- `hw3_3dgs.html`

## Project Structure
- `media/` → textures and video assets
- `output/` → splat scene file
- `docs/` → assignment prompt and report
- root HTML files → main interactive scenes

## Notes
This project explores immersive rendering techniques including equirectangular mapping, video texturing, UV layout correction, and hybrid rendering with Gaussian splats plus traditional mesh geometry.

### AUTHOR 
`Kelvin Ihezue`
