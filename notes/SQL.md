# SQL

**Summary**: Notes on SQL databases and query engines, including spatial SQL with PostGIS and DuckDB.
**Last updated**: 2026-11-18

---

- [PostGIS spatial joins, translated to DuckDB](https://www.geomermaids.com/cookbook/duckdb-spatial/): A Geomermaids cookbook that rewrites common PostGIS spatial joins for DuckDB and compares query plans and timings. Tips include one spatial predicate per join, explicit R-tree indexes, reprojecting before ST_DWithin, and spatially sorted GeoParquet (see [[Data]]). *Keywords*: DuckDB spatial, PostGIS, spatial joins, R-tree index, query optimization, GeoParquet
