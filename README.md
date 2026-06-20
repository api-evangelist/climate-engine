# Climate Engine (climate-engine)

Climate Engine is a geospatial climate and remote-sensing data platform that runs on Google Earth Engine. Its commercial REST API (api.climateengine.org) provides on-demand processing of satellite and gridded climate datasets - Landsat, Sentinel, MODIS, GRIDMET, ERA5, CHIRPS and more - returning timeseries, map tiles, zonal statistics, and pre-built reports over points, polygons, and feature collections.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/climate-engine/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/climate-engine/refs/heads/main/apis.yml)

## Tags

- Climate
- Geospatial
- Remote Sensing
- Satellite
- Earth Observation

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Climate Engine Timeseries API

Generates native, interannual, standard-index, and regression time series for climate and remote-sensing datasets over point coordinates and GeoJSON feature collections, with optional forecast variants.

- **Human URL:** [https://api.climateengine.org/docs](https://api.climateengine.org/docs)
- **Base URL:** `https://api.climateengine.org`

#### Tags

- Timeseries
- Climate
- Remote Sensing

#### Properties

- [Documentation](https://support.climateengine.org/article/12-climate-engine-apis)
- [API Reference](https://api.climateengine.org/docs)
- [OpenAPI](openapi/climate-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climate-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climate-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Climate Engine Zonal Statistics API

Computes pixel counts, static- and temporal-dataset statistics, group-by aggregations, and category counts reduced over coordinates or feature-collection geometries.

- **Human URL:** [https://api.climateengine.org/docs](https://api.climateengine.org/docs)
- **Base URL:** `https://api.climateengine.org`

#### Tags

- Zonal Statistics
- Aggregation
- Geospatial

#### Properties

- [Documentation](https://support.climateengine.org/article/12-climate-engine-apis)
- [API Reference](https://api.climateengine.org/docs)
- [OpenAPI](openapi/climate-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climate-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climate-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Climate Engine Raster API

Returns Earth Engine map IDs for tile rendering and queues asynchronous raster export jobs across values, anomalies, percentiles, standard index, degree days, and Mann-Kendall trend products, including forecast variants.

- **Human URL:** [https://api.climateengine.org/docs](https://api.climateengine.org/docs)
- **Base URL:** `https://api.climateengine.org`

#### Tags

- Maps
- Raster
- Tiles
- Export

#### Properties

- [Documentation](https://support.climateengine.org/article/12-climate-engine-apis)
- [API Reference](https://api.climateengine.org/docs)
- [OpenAPI](openapi/climate-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climate-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climate-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Climate Engine Reports API

Produces pre-built site characterization, drought, and vegetation production reports over coordinates or feature collections.

- **Human URL:** [https://api.climateengine.org/docs](https://api.climateengine.org/docs)
- **Base URL:** `https://api.climateengine.org`

#### Tags

- Reports
- Drought
- Vegetation

#### Properties

- [Documentation](https://support.climateengine.org/article/12-climate-engine-apis)
- [API Reference](https://api.climateengine.org/docs)
- [OpenAPI](openapi/climate-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climate-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climate-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Climate Engine Dataset Catalog API

Exposes dataset metadata - available dates, variables, county names, and the percentile and statistic classifications used to color and classify raster products.

- **Human URL:** [https://api.climateengine.org/docs](https://api.climateengine.org/docs)
- **Base URL:** `https://api.climateengine.org`

#### Tags

- Metadata
- Catalog
- Datasets

#### Properties

- [Documentation](https://docs.climateengine.org)
- [API Reference](https://api.climateengine.org/docs)
- [OpenAPI](openapi/climate-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climate-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climate-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Climate Engine Account API

Validates API keys, reports key expiration, and returns the authenticated user's quota usage and limits.

- **Human URL:** [https://api.climateengine.org/docs](https://api.climateengine.org/docs)
- **Base URL:** `https://api.climateengine.org`

#### Tags

- Account
- API Key
- Quotas

#### Properties

- [Documentation](https://support.climateengine.org/article/144-api-quota-policy)
- [API Reference](https://api.climateengine.org/docs)
- [OpenAPI](openapi/climate-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climate-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climate-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/climate-engine)
- [Website](https://www.climateengine.com)
- [Documentation](https://docs.climateengine.org)
- [Plans](plans/climate-engine-plans-pricing.yml)
- [Rate Limits](rate-limits/climate-engine-rate-limits.yml)
- [Fin Ops](finops/climate-engine-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
