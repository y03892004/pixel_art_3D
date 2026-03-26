# Pixel Art 3D

A lightweight 3D pixel-art sandbox you can run locally in a browser.

## Controls
- **Right click**: place a block
- **Left click**: remove hovered block
- **Mouse drag / wheel**: orbit + zoom (camera)
- **E**: line build mode (press once to start from hovered cell, move cursor, press again to confirm)
- **1–5**: select material
- **Ctrl+S**: save
- **L**: load
- **R**: reset

## Materials

- **Wood**
- **Brick**
- **Concrete**
- **Glass** (transparent)

## Structure presets

- **Wood Floor**: 5x5 wood floor tile
- **Wall**: 5x3 wood wall segment
- **Table**: simple wooden table
- **Chair**: simple wooden chair

## Run locally (Windows)

You need to serve the folder from a local web server (opening the file directly can break module imports).

### Option A: Python (recommended)

From the `pixel-art-3d` folder:

```powershell
py -m http.server 5173
```

Then open `http://localhost:5173/`.

### Option B: Node.js

```powershell
npx serve .
```

## Save data

Saves to `localStorage` under the key `pixel-art-3d:v1`.
