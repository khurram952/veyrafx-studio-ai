# Simulon Studio AI — Browser VFX MVP 0.1

A free, static browser prototype for basic 3D compositing.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser with internet access.
3. For best module-loading support, run a local static server:
   - Python: `python -m http.server 8000`
   - Then open `http://localhost:8000`

## Included in MVP 0.1
- Add cube and sphere primitives
- Import GLB/GLTF models
- Upload a video or image background
- Orbit/zoom/pan the 3D camera
- Adjust object position, scale and rotation
- Adjust ambient and key lighting
- Export PNG screenshot
- Record the stage as WebM (browser support varies)

## Current limitations
- This is a starter VFX editor, not a full Simulon replacement.
- No automatic image-to-3D or text-to-3D generation yet.
- No automatic camera tracking, ground-plane detection, shadow catcher, or AI relighting yet.
- AR camera mode and cloud rendering are not included.
- The Three.js libraries load from jsDelivr, so internet access is needed.
- Video export is WebM and may be demanding on phones.

## Next development milestones
1. Add transform gizmos and a timeline.
2. Add camera tracking / match-moving workflow.
3. Add shadow catcher and environment lighting.
4. Connect open-source image-to-3D inference where free compute is available.
5. Add WebXR AR preview on supported Android devices.
6. Add project save/load and asset library.

## Hosting free
Deploy the folder as a static site on GitHub Pages or Cloudflare Pages. No paid backend is required for this MVP.
