# ar-3dgs

AR viewer for the **angel with candlestick** model (made from a Gaussian splat, converted to a textured mesh).

One link works on every device:

| Device | What happens when you tap the AR button |
|---|---|
| iPhone / iPad | opens `angel.usdz` in AR Quick Look |
| Android | opens `angel.glb` in Google Scene Viewer |
| Desktop | 3D preview in the page (drag to orbit) |

This is handled automatically by Google's `<model-viewer>` (`src` = GLB, `ios-src` = USDZ).

## Files

- `index.html` – main AR page
- `room.html` – place the model on a photo of a room
- `room-depth.html` – same, with AI depth (occlusion) + shadow
- `depth-test.html` – depth-map test
- `angel.glb` – model for Android / web
- `angel.usdz` – model for iPhone
