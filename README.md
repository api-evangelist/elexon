# Elexon

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

Elexon is the UK's Balancing and Settlement Code (BSC) Company, responsible for administering the electricity balancing and settlement arrangements in Great Britain. As the operator of the Balancing Mechanism Reporting Service (BMRS), Elexon publishes a publicly accessible REST API — the Insights Solution API — that provides free, no-key access to real-time and historical data from the UK electricity market. The API covers balancing mechanism dynamic and physical data per Balancing Mechanism Unit (BMU), bid-offer acceptances, balancing services adjustments, physical notifications, generation availability forecasts, settlement reports, meter readings, and UK market transparency data mandated under European legislation. All data is returned in JSON, XML, or CSV format. A companion near-real-time push service (IRIS — Insights Real-time Information Service) streams the same datasets over WebSocket/STOMP for latency-sensitive consumers. The API is freely accessible to industry participants and the public with no registration or API key required, and data may be reused with attribution ("Contains BMRS data © Elexon Limited copyright and database right").

**Areas:** Electricity · Energy · UK Energy Market · Balancing Mechanism · Settlement · Meter Readings · Market Transparency · BMRS · Electricity Grid · Power Generation · United Kingdom

## Elexon on APIs.io

Everything profiled for Elexon is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/elexon/](https://apis.io/providers/elexon/)** — or go straight to one of the APIs or properties below.

### APIs (32)

- [Elexon Balancing Mechanism Dynamic API](https://apis.io/apis/elexon/elexon-balancing-mechanism-dynamic-api/) — Dynamic data.
- [Elexon Balancing Mechanism Physical API](https://apis.io/apis/elexon/elexon-balancing-mechanism-physical-api/) — Physical data consists of PN, QPN, MILS, & MELS.
- [Elexon Balancing Services Adjustment - Disaggregated API](https://apis.io/apis/elexon/elexon-balancing-services-adjustment-disaggregated-api/) — Adjustment actions (DISBSAD) for a given settlement period, or summarised by settlement period over a time range.
- [Elexon Balancing Services Adjustment - Net API](https://apis.io/apis/elexon/elexon-balancing-services-adjustment-net-api/) — Net balancing services adjustment data (NETBSAD), provided as a time series or filtered to events.
- [Elexon Bid-Offer Acceptances API](https://apis.io/apis/elexon/elexon-bid-offer-acceptances-api/) — Bid-offer acceptance data (BOALF).
- [Elexon Bid-Offer API](https://apis.io/apis/elexon/elexon-bid-offer-api/) — Bid-offer data.
- [Elexon BMRS Datasets API](https://apis.io/apis/elexon/elexon-bmrs-datasets-api/) — Raw datasets as received from the National Grid, with associated metadata. The output in JSON format matches IRIS, and can be used interchangeably with IRIS…
- [Elexon Credit Default Notice API](https://apis.io/apis/elexon/elexon-credit-default-notice-api/) — Credit Default Notice data.
- [Elexon Data Status API](https://apis.io/apis/elexon/elexon-data-status-api/) — The number of datapoints ingested for a dataset in a given period of time, grouped by settlement period.
- [Elexon Demand API](https://apis.io/apis/elexon/elexon-demand-api/) — GB electricity demand, including historic.
- [Elexon Demand Forecast API](https://apis.io/apis/elexon/elexon-demand-forecast-api/) — Current or historic demand forecasts.
- [Elexon Generation API](https://apis.io/apis/elexon/elexon-generation-api/) — GB electricity generation output, including historic.
- [Elexon Generation Forecast API](https://apis.io/apis/elexon/elexon-generation-forecast-api/) — Current or historic generation forecasts.
- [Elexon Health Check API](https://apis.io/apis/elexon/elexon-health-check-api/) — Provides an endpoint to check the health of the Insights API service.
- [Elexon Indicated Forecast API](https://apis.io/apis/elexon/elexon-indicated-forecast-api/) — Day-and-day-ahead indicated forecast, categorized as Indicated Generation (INDGEN), Indicated Demand (INDDEM), Imbalance (IMBALNGC) and Margin (MELNGC).
- [Elexon Indicative Imbalance Settlement API](https://apis.io/apis/elexon/elexon-indicative-imbalance-settlement-api/) — Data related to the settlement process.
- [Elexon Legacy API](https://apis.io/apis/elexon/elexon-legacy-api/) — The Legacy API from Elexon — 2 operation(s) for legacy.
- [Elexon Load Shape API](https://apis.io/apis/elexon/elexon-load-shape-api/) — Load shape period data and load shape totals data as calculated by the Load Shaping Service
- [Elexon Loss of Load Probability and De-rated Margin API](https://apis.io/apis/elexon/elexon-loss-of-load-probability-and-de-rated-margin-api/) — Loss of load probability and de-rated margin forecast data.
- [Elexon Margin Forecast API](https://apis.io/apis/elexon/elexon-margin-forecast-api/) — Generating Plant Operating Margin forecast data, including historical views of data by publish time or forecast date.
- [Elexon Market Index API](https://apis.io/apis/elexon/elexon-market-index-api/) — Market Index prices filtered by time.
- [Elexon Non-BM STOR API](https://apis.io/apis/elexon/elexon-non-bm-stor-api/) — Short Term Operating Reserves (STOR) data, provided as a time series or filtered to events.
- [Elexon Non-BM Volumes API](https://apis.io/apis/elexon/elexon-non-bm-volumes-api/) — Balancing services volume data, filtered by BM Unit and time range.
- [Elexon Reference API](https://apis.io/apis/elexon/elexon-reference-api/) — Reference data which can be used to filter other API requests.
- [Elexon REMIT API](https://apis.io/apis/elexon/elexon-remit-api/) — REMIT messages, including previous revisions.
- [Elexon Rolling System Demand API](https://apis.io/apis/elexon/elexon-rolling-system-demand-api/) — The Rolling System Demand API from Elexon — 1 operation(s) for rolling system demand.
- [Elexon SAA Datasets API](https://apis.io/apis/elexon/elexon-saa-datasets-api/) — Datasets received from the Settlement Administration Agent (SAA)
- [Elexon SO-SO Prices API](https://apis.io/apis/elexon/elexon-so-so-prices-api/) — SO-SO Prices (SOSO) data, filtered by start time.
- [Elexon Surplus Forecast API](https://apis.io/apis/elexon/elexon-surplus-forecast-api/) — Generating Plant Operating Surplus forecast data, including historical views of data by publish time or forecast date.
- [Elexon System API](https://apis.io/apis/elexon/elexon-system-api/) — Transmission System data.
- [Elexon System forecast API](https://apis.io/apis/elexon/elexon-system-forecast-api/) — Transmission System forecasts
- [Elexon Temperature API](https://apis.io/apis/elexon/elexon-temperature-api/) — Daily average & reference temperatures.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Elexon Agentic Access](https://apis.io/agentic-access/elexon/elexon-agentic-access/)

#### JSON Schema (295)

The data models the API reads and writes.

- [Insights.Api.LegacyInteroperability.LegacyRemitDetailBody](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitDetailBody/)
- [Insights.Api.LegacyInteroperability.LegacyRemitDetailItem](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitDetailItem/)
- [Insights.Api.LegacyInteroperability.LegacyRemitDetailList](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitDetailList/)
- [Insights.Api.LegacyInteroperability.LegacyRemitDetailMetadata](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitDetailMetadata/)
- [Insights.Api.LegacyInteroperability.LegacyRemitDetailResponse](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitDetailResponse/)
- [Insights.Api.LegacyInteroperability.LegacyRemitListItem](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitListItem/)
- [Insights.Api.LegacyInteroperability.LegacyRemitListMetadata](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitListMetadata/)
- [Insights.Api.LegacyInteroperability.LegacyRemitListResponse](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitListResponse/)
- [Insights.Api.LegacyInteroperability.LegacyRemitListResponseBody](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitListResponseBody/)
- [Insights.Api.LegacyInteroperability.LegacyRemitOutageProfile](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitOutageProfile/)
- [Insights.Api.LegacyInteroperability.LegacyRemitOutageProfileSegment](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitOutageProfileSegment/)
- [Insights.Api.LegacyInteroperability.LegacyRemitResponseList](https://apis.io/schemas/elexon/Insights.Api.LegacyInteroperability.LegacyRemitResponseList/)
- [Insights.Api.Models.Data.Entities.LoadShapePeriodData](https://apis.io/schemas/elexon/Insights.Api.Models.Data.Entities.LoadShapePeriodData/)
- [Insights.Api.Models.Data.Entities.LoadShapeTotalsData](https://apis.io/schemas/elexon/Insights.Api.Models.Data.Entities.LoadShapeTotalsData/)
- [Insights.Api.Models.Metadata.ApiResponseSourceMetadata](https://apis.io/schemas/elexon/Insights.Api.Models.Metadata.ApiResponseSourceMetadata/)
- [Insights.Api.Models.Metadata.RemitApiResponseSourceMetadata](https://apis.io/schemas/elexon/Insights.Api.Models.Metadata.RemitApiResponseSourceMetadata/)
- [Insights.Api.Models.Requests.DataStatus.RemitDataSource](https://apis.io/schemas/elexon/Insights.Api.Models.Requests.DataStatus.RemitDataSource/)
- [Insights.Api.Models.Responses.Balancing.BalancingServicesVolume](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.BalancingServicesVolume/)
- [Insights.Api.Models.Responses.Balancing.BidOfferAcceptancesResponse](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.BidOfferAcceptancesResponse/)
- [Insights.Api.Models.Responses.Balancing.BidOfferResponse](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.BidOfferResponse/)
- [Insights.Api.Models.Responses.Balancing.CreditDefaultNoticeResponse](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.CreditDefaultNoticeResponse/)
- [Insights.Api.Models.Responses.Balancing.DatasetRows.BalancingServicesVolumeData](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.DatasetRows.BalancingServicesVolumeData/)
- [Insights.Api.Models.Responses.Balancing.DatasetRows.BidOfferAcceptanceLevelDatasetResponse](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.DatasetRows.BidOfferAcceptanceLevelDatasetResponse/)
- [Insights.Api.Models.Responses.Balancing.DatasetRows.BidOfferDatasetResponse](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.DatasetRows.BidOfferDatasetResponse/)
- [Insights.Api.Models.Responses.Balancing.DatasetRows.CreditDefaultNoticeDatasetResponse](https://apis.io/schemas/elexon/Insights.Api.Models.Responses.Balancing.DatasetRows.CreditDefaultNoticeDatasetResponse/)
- …and 270 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Api Context](https://apis.io/jsonld/elexon/api/)
- [context Context](https://apis.io/jsonld/elexon/context/)

#### Examples (20)

Example requests and responses.

- [Get_Balancing_Acceptances_200](https://apis.io/examples/elexon/get_balancing_acceptances_200/)
- [Get_Balancing_Acceptances_Acceptancenumber_200](https://apis.io/examples/elexon/get_balancing_acceptances_acceptanceNumber_200/)
- [Get_Balancing_Acceptances_All_200](https://apis.io/examples/elexon/get_balancing_acceptances_all_200/)
- [Get_Balancing_Acceptances_All_Latest_200](https://apis.io/examples/elexon/get_balancing_acceptances_all_latest_200/)
- [Get_Balancing_Bid Offer_200](https://apis.io/examples/elexon/get_balancing_bid-offer_200/)
- [Get_Balancing_Bid Offer_All_200](https://apis.io/examples/elexon/get_balancing_bid-offer_all_200/)
- [Get_Balancing_Dynamic_200](https://apis.io/examples/elexon/get_balancing_dynamic_200/)
- [Get_Balancing_Dynamic_All_200](https://apis.io/examples/elexon/get_balancing_dynamic_all_200/)
- [Get_Balancing_Dynamic_Rates_200](https://apis.io/examples/elexon/get_balancing_dynamic_rates_200/)
- [Get_Balancing_Dynamic_Rates_All_200](https://apis.io/examples/elexon/get_balancing_dynamic_rates_all_200/)
- [Get_Balancing_Nonbm_Disbsad_Details_200](https://apis.io/examples/elexon/get_balancing_nonbm_disbsad_details_200/)
- [Get_Balancing_Nonbm_Disbsad_Summary_200](https://apis.io/examples/elexon/get_balancing_nonbm_disbsad_summary_200/)
- [Get_Balancing_Nonbm_Netbsad_200](https://apis.io/examples/elexon/get_balancing_nonbm_netbsad_200/)
- [Get_Balancing_Nonbm_Netbsad_Events_200](https://apis.io/examples/elexon/get_balancing_nonbm_netbsad_events_200/)
- [Get_Balancing_Physical_200](https://apis.io/examples/elexon/get_balancing_physical_200/)
- [Get_Balancing_Physical_All_200](https://apis.io/examples/elexon/get_balancing_physical_all_200/)
- [Get_Datasets_Nonbm_200](https://apis.io/examples/elexon/get_datasets_NONBM_200/)
- [Get_Datasets_Nonbm_Stream_200](https://apis.io/examples/elexon/get_datasets_NONBM_stream_200/)
- [Get_Datasets_Pn_200](https://apis.io/examples/elexon/get_datasets_PN_200/)
- [Get_Datasets_Pn_Stream_200](https://apis.io/examples/elexon/get_datasets_PN_stream_200/)

#### Collections (32)

Postman and Open Collection request collections.

- [Insights.Api Balancing Mechanism Dynamic API](https://apis.io/collections/elexon/open-elexon-balancing-mechanism-dynamic-api/)
- [Insights.Api Balancing Mechanism Dynamic Balancing Mechanism Physical API](https://apis.io/collections/elexon/open-elexon-balancing-mechanism-physical-api/)
- [Insights.Api Balancing Mechanism Dynamic Balancing Services Adjustment - Disaggregated API](https://apis.io/collections/elexon/open-elexon-balancing-services-adjustment-disaggregated-api/)
- [Insights.Api Balancing Mechanism Dynamic Balancing Services Adjustment - Net API](https://apis.io/collections/elexon/open-elexon-balancing-services-adjustment-net-api/)
- [Insights.Api Balancing Mechanism Dynamic Bid-Offer Acceptances API](https://apis.io/collections/elexon/open-elexon-bid-offer-acceptances-api/)
- [Insights.Api Balancing Mechanism Dynamic Bid-Offer API](https://apis.io/collections/elexon/open-elexon-bid-offer-api/)
- [Insights.Api Balancing Mechanism Dynamic BMRS Datasets API](https://apis.io/collections/elexon/open-elexon-bmrs-datasets-api/)
- [Insights.Api Balancing Mechanism Dynamic Credit Default Notice API](https://apis.io/collections/elexon/open-elexon-credit-default-notice-api/)
- [Insights.Api Balancing Mechanism Dynamic Data Status API](https://apis.io/collections/elexon/open-elexon-data-status-api/)
- [Insights.Api Balancing Mechanism Dynamic Demand API](https://apis.io/collections/elexon/open-elexon-demand-api/)
- [Insights.Api Balancing Mechanism Dynamic Demand Forecast API](https://apis.io/collections/elexon/open-elexon-demand-forecast-api/)
- [Insights.Api Balancing Mechanism Dynamic Generation API](https://apis.io/collections/elexon/open-elexon-generation-api/)
- [Insights.Api Balancing Mechanism Dynamic Generation Forecast API](https://apis.io/collections/elexon/open-elexon-generation-forecast-api/)
- [Insights.Api Balancing Mechanism Dynamic Health Check API](https://apis.io/collections/elexon/open-elexon-health-check-api/)
- [Insights.Api Balancing Mechanism Dynamic Indicated Forecast API](https://apis.io/collections/elexon/open-elexon-indicated-forecast-api/)
- [Insights.Api Balancing Mechanism Dynamic Indicative Imbalance Settlement API](https://apis.io/collections/elexon/open-elexon-indicative-imbalance-settlement-api/)
- [Insights.Api Balancing Mechanism Dynamic Legacy API](https://apis.io/collections/elexon/open-elexon-legacy-api/)
- [Insights.Api Balancing Mechanism Dynamic Load Shape API](https://apis.io/collections/elexon/open-elexon-load-shape-api/)
- [Insights.Api Balancing Mechanism Dynamic Loss of Load Probability and De-rated Margin API](https://apis.io/collections/elexon/open-elexon-loss-of-load-probability-and-de-rated-margin-api/)
- [Insights.Api Balancing Mechanism Dynamic Margin Forecast API](https://apis.io/collections/elexon/open-elexon-margin-forecast-api/)
- [Insights.Api Balancing Mechanism Dynamic Market Index API](https://apis.io/collections/elexon/open-elexon-market-index-api/)
- [Insights.Api Balancing Mechanism Dynamic Non-BM STOR API](https://apis.io/collections/elexon/open-elexon-non-bm-stor-api/)
- [Insights.Api Balancing Mechanism Dynamic Non-BM Volumes API](https://apis.io/collections/elexon/open-elexon-non-bm-volumes-api/)
- [Insights.Api Balancing Mechanism Dynamic Reference API](https://apis.io/collections/elexon/open-elexon-reference-api/)
- [Insights.Api Balancing Mechanism Dynamic REMIT API](https://apis.io/collections/elexon/open-elexon-remit-api/)
- …and 7 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Elexon — jsonschema rules](https://apis.io/rules/elexon/elexon-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Elexon Domain Security](https://apis.io/security/elexon/elexon-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Elexon Plans Pricing](https://apis.io/plans/elexon/elexon-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Elexon Rate Limits](https://apis.io/rate-limits/elexon/elexon-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Elexon Finops](https://apis.io/finops/elexon/elexon-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://elexon.co.uk)
- [Documentation](https://bmrs.elexon.co.uk/api-documentation/guidance)
- [Blog](https://www.elexon.co.uk/news-insights/)
- [Terms of service](https://www.elexon.co.uk/bsc/data/balancing-mechanism-reporting-agent/copyright-licence-bmrs-data/)
- [Status](https://status.elexon.co.uk/)

## API Evangelist rating

**Kin Score 32.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 50.3 |
| Contract governance | 9.8 |
| Operational transparency | 28.9 |
| Developer ergonomics | 26.2 |
| Access clarity | 15.8 |

**Agent readiness 23.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 12.3** — Energy & Utilities

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/elexon/](https://apis.io/providers/elexon/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Elexon: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/elexon/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
