# GeoJSON
=======

This is just a collection of info, tests and experiments dealing with GeoJSON, to include styling via MapBox symbol sets.

## Useful Resources:

- GeoJSON Project and Specifications: http://geojson.org/
- GeoJSON Lint - validator and previewer for GeoJSON: http://geojsonlint.com/

## Symbology tips:
- github allows symbology to be embedded - simply include as feature properties, for example "marker-symbol":"museum"
- MapBox Maki symbol set: http://www.mapbox.com/maki/ - note that not all symbols are supported in github; for example, land-use does not appear to work.  Also, note that for github, DO NOT use size combined with icon, i.e. "museum-18" to specify size - use "museum" and specify size separately.
