# Elexon (elexon)

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
