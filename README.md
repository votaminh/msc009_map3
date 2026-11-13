# msc009_map3

Map tiles for PiloOS mini apps (PiloMap), part 3 (the largest countries): one folder per country under `tiles/<iso3>/`, each with `<iso3>.json` (pieces + bbox) and `<iso3>-NN.pmtiles` pieces. Cut from the daily planet build of Protomaps (https://maps.protomaps.com/builds/). Parts 1 and 2 are `votaminh/msc011_map` and `votaminh/msc009_map2`.

Map data © OpenStreetMap contributors (ODbL, https://www.openstreetmap.org/copyright). Basemap schema: Protomaps (BSD-3-Clause).

Read by byte range with the `pmtiles` JS library, e.g. `https://raw.githubusercontent.com/votaminh/msc009_map3/main/tiles/<iso3>/<iso3>-NN.pmtiles`.
