# Singularity (singularity-energy)

Singularity Energy is a Boston-based grid decarbonization data company. Its Grid Carbon API delivers hourly, location-specific electricity emissions intelligence - generated, consumed, and marginal carbon intensity, fuel mix, generation events, interchange, and 48-hour emissions forecasts across ISOs and balancing authorities in the U.S. and Canada.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/singularity-energy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/singularity-energy/refs/heads/main/apis.yml)

## Tags

- Energy
- Carbon Emissions
- Grid
- Sustainability
- Carbon Intensity

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Singularity Carbon Intensity API

Generated, consumed, and marginal carbon-intensity (lbs/MWh) emission factors for regions and balancing authorities, plus on-demand intensity calculation from a supplied fuel mix and a catalog of emission factor sources.

- **Human URL:** [https://docs.singularity.energy/docs/singularity-api/grid-carbon-api](https://docs.singularity.energy/docs/singularity-api/grid-carbon-api)
- **Base URL:** `https://api.singularity.energy`

#### Tags

- Carbon Intensity
- Emissions
- Marginal Emissions

#### Properties

- [Documentation](https://docs.singularity.energy/docs/singularity-api/grid-carbon-api)
- [API Reference](https://docs.singularity.energy/docs/singularity-api/key-concepts)
- [OpenAPI](openapi/singularity-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/singularity-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singularity-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Singularity Forecasts API

Generated-emissions nowcasting and hourly forecasting up to 48 hours ahead, surfaced as forecast event types through the region events search and latest-events endpoints.

- **Human URL:** [https://docs.singularity.energy/docs/singularity-api/grid-carbon-api](https://docs.singularity.energy/docs/singularity-api/grid-carbon-api)
- **Base URL:** `https://api.singularity.energy`

#### Tags

- Forecasts
- Emissions
- Nowcasting

#### Properties

- [Documentation](https://docs.singularity.energy/docs/singularity-api/grid-carbon-api)
- [OpenAPI](openapi/singularity-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/singularity-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singularity-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Singularity Generation & Event Data API

Search, look up, and stream region events - generated/marginal/consumed fuel mix, carbon intensity, and interchange - by region or postal code, by time window, by deduplication key, or in bulk, with latest-event retrieval.

- **Human URL:** [https://docs.singularity.energy/docs/singularity-api/key-concepts](https://docs.singularity.energy/docs/singularity-api/key-concepts)
- **Base URL:** `https://api.singularity.energy`

#### Tags

- Generation
- Fuel Mix
- Events

#### Properties

- [Documentation](https://docs.singularity.energy/docs/singularity-api/key-concepts)
- [OpenAPI](openapi/singularity-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/singularity-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singularity-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Singularity Regions API

Region and balancing-authority coverage, postal-code resolution, and inter-region interchange (power flow) events including a latest-interchange endpoint, spanning 76 ISOs and balancing authorities across the U.S. and Canada.

- **Human URL:** [https://docs.singularity.energy/docs/singularity-api/region-flow](https://docs.singularity.energy/docs/singularity-api/region-flow)
- **Base URL:** `https://api.singularity.energy`

#### Tags

- Regions
- Balancing Authorities
- Interchange

#### Properties

- [Documentation](https://docs.singularity.energy/docs/singularity-api/region-flow)
- [OpenAPI](openapi/singularity-energy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/singularity-energy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singularity-energy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/singularity-energy)
- [LinkedIn](https://www.linkedin.com/company/singularity-energy)
- [Website](https://www.singularity.energy)
- [Documentation](https://docs.singularity.energy)
- [Plans](plans/singularity-energy-plans-pricing.yml)
- [Rate Limits](rate-limits/singularity-energy-rate-limits.yml)
- [Fin Ops](finops/singularity-energy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
