# Gardens & Heat

An interactive web map of New York City community gardens, land jurisdiction, and heat vulnerability (NYC Heat Vulnerability Index) across neighborhoods.

Built with MapLibre GL JS. Static site — no build step.

## Data
- Community gardens: archived GreenThumb, July 2026
- Heat Vulnerability Index: NYC Health, 2020 NTA geography
- Open space: NYC Planimetric Database
- Basemap: © OpenStreetMap contributors © CARTO

`prepare_data.py` and `prepare_open_space.mjs` generate the files in `data/`.

## Run locally
```
python3 -m http.server
```
then open http://localhost:8000
