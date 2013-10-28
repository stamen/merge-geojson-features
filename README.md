# merge-geojson-features

Merges GeoJSON Features and FeatureCollections.

## Usage

`1.json` and `2.json` may either be JSON files containing GeoJSON
`FeatureCollection`s or individual `Feature`s. The output will be
a `FeatureCollection` containing all features present in the files to be
merged.

```bash
merge-geojson-features 1.json 2.json > merged.json
```
