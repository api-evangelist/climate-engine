# Climate Engine (climate-engine)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
