# 🇧🇪 BeSt Address 🇧🇪

Download a full dump of the data in GeoPackage format with the following command:

```bash
curl https://ac.ngi.be/remoteclient-open/GeoBePartners-open/BOSA/ca0fd5c0-8146-11e9-9012-482ae30f98d9_geopackage+sqlite3_3812.zip > belgium-addresses.zip
```

Decompress and produce a CSV export using an SQLite tool (e.g. [DB Browser](https://sqlitebrowser.org/)). The [SpatiaLite library](https://www.gaia-gis.it/fossil/libspatialite/index) can be used as an extension of SQLite to extract and transform geospatial parameters.
