# meera-map-data

Open map data packages for offline maps. This repository holds map data and credits only.

## Regions
- kanpur: Kanpur and surroundings, bounding box 26.25 to 26.70 N, 80.10 to 80.60 E. Not a full-India map.

## Source and licence
Map data (c) OpenStreetMap contributors, available under the Open Database Licence (ODbL) 1.0.
https://www.openstreetmap.org/copyright
Extract of the Geofabrik India file (https://download.geofabrik.de/asia/india-latest.osm.pbf, data up to 2026-11-24), cut to the bounding box with osmium and converted to the mapsforge v3 map format with mapsforge-map-writer 0.25.0.
The map files in this repository are a derived database and are offered under ODbL 1.0. Anyone may download, copy and reuse them with credit to OpenStreetMap and its contributors.

## Package format
Each region zip contains region.map and manifest.json (SHA-256 of each file). index.json lists regions with the zip SHA-256.
