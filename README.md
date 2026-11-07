# Space Discovery Museum AR Project

A marker-based AR exhibit built with A-Frame and AR.js.

## Run locally
1. Extract the project folder.
2. Open a terminal in the folder.
3. Start a local web server (for example, `python -m http.server 8000`).
4. Open `http://localhost:8000` in Chrome and allow camera access.
5. Show a printed Hiro marker to the camera.

## Interactions
- Click/tap the pink sphere to cycle its colour.
- Click/tap the purple crystal to grow and shrink it.
- The gold beacon slides sideways, the rocket rises and falls, and the display ring rotates.

The cursor and raycaster are attached directly to the camera to improve desktop mouse picking and mobile pointer interaction.

## Model credit
`assets/explorer-rocket.glb` is an original low-poly model generated for this student project; it is not a third-party downloaded model.

## Publishing
Publish the project folder using GitHub Pages or Netlify so the page is served over HTTPS. Test camera permission and object interaction on a phone before submission.
