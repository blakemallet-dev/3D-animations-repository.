# 3D Animations Repository

Web-ready 3D models (glTF binary `.glb`), generated from photo sets with 3D AI Studio and finished in Blender.

## Models

| File | Size | Description |
|------|------|-------------|
| `topiary-logo-leafy-web.glb` | ~15 MB | Green logo built from real 3D leaves, ferns, and wildflowers |
| `green-logo-flowers-web.glb` | ~6.5 MB | Green plant-and-flower logo |
| `floral-letter-web.glb` | ~6.2 MB | Floral arrangement forming a letter |

All three are decimated and texture-optimized for mobile web (2K textures). Full-resolution masters are kept separately.

## Using a model

Drop a `<model-viewer>` onto any page:

```html
<script type="module" src="https://cdn.jsdelivr.net/npm/@google/model-viewer@3.5.0/dist/model-viewer-umd.min.js"></script>

<model-viewer
  src="topiary-logo-leafy-web.glb"
  alt="3D logo"
  camera-controls auto-rotate
  style="width:100%;height:600px;background:transparent;">
</model-viewer>
```

`index.html` in this repo previews all three with a slow spin and drag-to-rotate.
