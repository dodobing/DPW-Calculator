# DPW Calculator

A **Die per Wafer / Panel** calculator that places dies on a real grid to compute
count, area utilization, and visualize the layout.

🔗 **Live demo:** https://dodobing.github.io/DPW-Calculator/

## Features

- **Two modes** — Round Wafer and Rectangular Panel
- **Real grid placement** — dies are actually placed and counted geometrically
  (not just a formula approximation), matching tools like silicon-edge
- **Wafer** — diameter input with presets (100 / 150 / 200 / 300 / 450 mm),
  notch/flat marker, usable-radius ring
- **Panel** — width × height with presets (incl. G5), edge-exclusion box
- **Die spec** — width, height, scribe/dicing street, edge exclusion
- **Layout options**
  - Auto-search best grid offset (maximizes die count)
  - Show partial dies at the edge (counted separately from good dies)
- **Live stats** — good die count, area utilization, die pitch, used/total area
- **Visualization** — hi-DPI canvas; green = good die, orange = partial die

## Usage

Open `index.html` in any modern browser — no build step, no dependencies.

## License

MIT
