# Singularity (singularity-energy)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
