# Project N.O.M.A.D. Offline Maps - UK, Portugal, Spain and Netherlands

Additional offline PMTiles map packs for Project N.O.M.A.D.

Project N.O.M.A.D. currently does not include full global map coverage, so this repository provides additional regions that are missing from the default map catalogue.

Project N.O.M.A.D.:

https://github.com/Crosstalk-Solutions/project-nomad

---

# Available Maps

| Region | File | Status |
|---|---|---|
| United Kingdom | `https://github.com/p-souto/project-nomad-extra-maps/releases/download/v1/uk_20260510.pmtiles` | Available |
| Portugal | `https://github.com/p-souto/project-nomad-extra-maps/releases/download/v1/portugal_20260510.pmtiles` | Available |
| Spain | `` | Soon |
| Netherlands | `https://github.com/p-souto/project-nomad-extra-maps/releases/download/v1/netherlands_20260510.pmtiles` | Available |
| Switzerland | `https://github.com/p-souto/project-nomad-extra-maps/releases/download/v1/netherlands_20260510.pmtiles` | Available |


---

# Usage

In N.O.M.A.D., go to:

```text
Settings > Maps > Download a Custom Map File
```

Paste the download URL for the region you want.

---

# Map Source

The maps are generated from the Protomaps Basemap v4 dataset:

* https://docs.protomaps.com/basemaps

Current Regions used:

- United Kingdom
- Portugal
- Spain
- Netherlands

---

# Tooling

Regional extracts are generated using the go-pmtiles CLI tool:

* https://github.com/protomaps/go-pmtiles/releases

---

# Format

All maps are distributed in:

```text
.pmtiles
```

PMTiles is a single-file archive format designed for efficient offline and self-hosted map usage.

More information:

- https://protomaps.com/
- https://github.com/protomaps/PMTiles

---

# Notes

- These maps are vector tiles, not raster images.
- File sizes may vary significantly depending on zoom levels.
- OpenStreetMap attribution is required when redistributing map data.

---

# Attribution

© OpenStreetMap contributors

https://www.openstreetmap.org/copyright
