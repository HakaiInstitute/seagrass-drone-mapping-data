# Data

This folder contains the eelgrass (*Zostera marina*) extent geodatabase.

## File

| File | Description |
|------|-------------|
| `CentralCoast_SeasonalDroneEelgrassPolygons.gdb.zip` | Compressed Esri file geodatabase containing the eelgrass extent and AOI layers |

## Geodatabase Layers

| Layer name | Geometry | Coordinate system | Description |
|------------|----------|-------------------|-------------|
| `Eelgrass_Drone_Extents_AOIClipped` | Polygon | NAD83(CSRS) / BC Albers (EPSG:3153) | Eelgrass meadow extent at each monitoring site, one feature per survey, clipped to the site AOI |
| `Eelgrass_Drone_AOIs` | Polygon | NAD83(CSRS) / UTM zone 9N | Area-of-interest boundaries used to standardize survey extent across years, plus partial-coverage boundaries for Koeye 2019 and McMullin North 2022 |

Data dictionaries for each layer are in the `docs/` folder.
