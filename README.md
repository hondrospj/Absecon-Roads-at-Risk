# Absecon Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Absecon municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01410510, Absecon
- PETSS / NOAA station: est4540
- NAVD88 thresholds: 3.19 ft minor, 4.19 ft moderate, 5.19 ft major
- MLLW thresholds: 5.6 ft minor, 6.6 ft moderate, 7.6 ft major
- MLLW = NAVD88 + 2.41 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Absecon boundary at 7.0-foot adaptive resolution.
