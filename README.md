# Magnets Studio — 3D Viewer

Static single-page 3D viewer. Deploy to GitHub Pages.

## Deploy

1. Create a GitHub repo
2. Drop both files in the root:
   - `index.html`
   - `Mercedes_House.glb`
3. Go to **Settings → Pages → Source: main / root**
4. Done — viewer is live at `https://yourusername.github.io/your-repo/`

## Controls

| Input | Action |
|---|---|
| Left drag | Orbit |
| Right drag | Pan |
| Middle drag | Pan |
| Scroll wheel | Zoom (proportional) |
| Pinch | Zoom |

## Loading a different model

Drop any `.glb` or `.gltf` onto the viewport, or use the **Load GLB** button in the sidebar.

To change the default model, rename your file to `Mercedes_House.glb` or edit the `loadURL` line in `index.html`:

```js
loadURL('Mercedes_House.glb', 'MERCEDES HOUSE');
```
