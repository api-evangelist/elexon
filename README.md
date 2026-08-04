# Elexon (elexon)

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

Elexon is the UK's Balancing and Settlement Code (BSC) Company, responsible for administering the electricity balancing and settlement arrangements in Great Britain. As the operator of the Balancing Mechanism Reporting Service (BMRS), Elexon publishes a publicly accessible REST API — the Insights Solution API — that provides free, no-key access to real-time and historical data from the UK electricity market. The API covers balancing mechanism dynamic and physical data per Balancing Mechanism Unit (BMU), bid-offer acceptances, balancing services adjustments, physical notifications, generation availability forecasts, settlement reports, meter readings, and UK market transparency data mandated under European legislation. All data is returned in JSON, XML, or CSV format. A companion near-real-time push service (IRIS — Insights Real-time Information Service) streams the same datasets over WebSocket/STOMP for latency-sensitive consumers. The API is freely accessible to industry participants and the public with no registration or API key required, and data may be reused with attribution ("Contains BMRS data © Elexon Limited copyright and database right").

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/elexon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/elexon/refs/heads/main/apis.yml)

## Tags

- Electricity
- Energy
- UK Energy Market
- Balancing Mechanism
- Settlement
- Meter Readings
- Market Transparency
- BMRS
- Electricity Grid
- Power Generation
- United Kingdom

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Elexon Insights Solution API

The Elexon Insights Solution API is a publicly accessible REST API providing free access to UK electricity balancing and settlement data. The API requires no authentication or API key and serves production-grade data continuously. Endpoints are grouped into Dataset Endpoints (raw published data, including superseded historical records), Opinionated Endpoints (specific use-case queries such as demand evolution or generation availability), Streaming Endpoints (JSON only, no paging restrictions), and Summary/Reference Data endpoints. Response formats include JSON, XML, and CSV. Core data domains include balancing mechanism dynamic and physical data per BMU, bid-offer data and acceptances, disaggregated and net balancing services adjustments (DISBSAD/NETBSAD), physical notifications (PN/QPN), non-BM STOR (NONBM), and 50+ BMRS datasets covering generation, demand, frequency, temperature, and market transparency. An interactive OpenAPI specification is published at https://data.elexon.co.uk/swagger/v1/swagger.json.

- **Human URL:** [https://developer.data.elexon.co.uk/](https://developer.data.elexon.co.uk/)
- **Base URL:** `https://data.elexon.co.uk/bmrs/api/v1`

#### Tags

- Balancing Mechanism
- Physical Notifications
- Bid-Offer
- Acceptances
- Balancing Services Adjustment
- Generation Forecasts
- Demand Data
- Settlement
- Market Transparency
- Meter Data
- Electricity

#### Properties

- [Documentation](https://developer.data.elexon.co.uk/)
- [Documentation](https://bmrs.elexon.co.uk/api-documentation/guidance)
- [OpenAPI](https://data.elexon.co.uk/swagger/v1/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Git Hub](https://github.com/elexon-data/insights-docs)

## Common Properties

- [Portal](https://developer.data.elexon.co.uk/)
- [Documentation](https://bmrs.elexon.co.uk/api-documentation/guidance)
- [OpenAPI](https://data.elexon.co.uk/swagger/v1/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Terms of Service](https://www.elexon.co.uk/bsc/data/balancing-mechanism-reporting-agent/copyright-licence-bmrs-data/)
- [Status Page](https://status.elexon.co.uk/)
- [Git Hub](https://github.com/elexon-data)
- [Git Hub](https://github.com/elexon-data/insights-docs)
- [Git Hub](https://github.com/elexon-data/insights-issues)
- [Git Hub](https://github.com/elexon-data/iris-clients)
- [Blog](https://www.elexon.co.uk/news-insights/)
- [Support](mailto:insightssupport@elexon.co.uk)
- [Plans](plans/elexon-plans-pricing.yml)
- [Rate Limits](rate-limits/elexon-rate-limits.yml)
- [Fin Ops](finops/elexon-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
