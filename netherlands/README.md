# 🇳🇱 Basisregistratie Adressen en Gebouwen 🇳🇱

Download a full dump of the data in GeoPackage format with the following command:

```bash
curl https://service.pdok.nl/lv/bag/atom/downloads/bag-light.gpkg > bag-light.gpkg
```

Decompress and produce a CSV export using an SQLite tool (e.g. [DB Browser](https://sqlitebrowser.org/)). The [SpatiaLite library](https://www.gaia-gis.it/fossil/libspatialite/index) can be used as an extension of SQLite to extract and transform geospatial parameters.
