# Bitso (bitso)

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

Bitso is one of Latin America's largest cryptocurrency exchanges and stablecoin-rail providers, serving Mexico, Argentina, Brazil, Colombia, and other LATAM markets. Bitso exposes a public REST trading API and a WebSocket feed at bitso.com/api/v3 for market data, order management, conversions, OTC / RFQ, and account operations; a Payouts & Pay-Ins API for cross-border crypto and fiat disbursements; and the Juno API for Mexican peso (MXN) rails and stablecoin programmable money. API and OpenAPI references are catalogued at docs.bitso.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bitso/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bitso/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- Cryptocurrency
- Exchange
- Trading
- Stablecoins
- Payouts
- Cross Border
- Latin America
- Mexico
- Fintech

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Bitso Trading REST API (v3)

Public and authenticated REST endpoints for Bitso's exchange - books, ticker, trades, candles, balance, order placement and cancellation, conversions, RFQ / OTC quoting and execution, account configuration, and (where available) margin trading. Authenticated calls are signed with API key, nonce, and HMAC.

- **Human URL:** [https://docs.bitso.com/bitso-api/docs](https://docs.bitso.com/bitso-api/docs)
- **Base URL:** `https://api.bitso.com/v3`

#### Tags

- Trading
- Exchange
- REST
- Market Data

#### Properties

- [Documentation](https://docs.bitso.com/bitso-api/docs)
- [OpenAPI](https://docs.bitso.com/llms.txt) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitso.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bitso WebSocket API

Real-time streaming channels for trades, order-book diffs, and full order-book snapshots. Used by trading clients and market-data consumers that need sub-second updates.

- **Human URL:** [https://docs.bitso.com/bitso-api/docs/general](https://docs.bitso.com/bitso-api/docs/general)
- **Base URL:** `wss://ws.bitso.com`

#### Tags

- WebSocket
- Streaming
- Market Data

#### Properties

- [Documentation](https://docs.bitso.com/bitso-api/docs/general)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/bitso/refs/heads/main/asyncapi/bitso-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/bitso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitso.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bitso Payouts and Pay-Ins API

Cross-border disbursement and collection API powered by stablecoin and LATAM rails. Lets businesses fund into Bitso, convert between assets and fiat, and pay out to destination accounts across supported countries.

- **Human URL:** [https://docs.bitso.com/bitso-payouts-funding/docs/getting-started](https://docs.bitso.com/bitso-payouts-funding/docs/getting-started)
- **Base URL:** `https://api.bitso.com`

#### Tags

- Payouts
- Pay-Ins
- Cross Border
- Stablecoins

#### Properties

- [Documentation](https://docs.bitso.com/bitso-payouts-funding/docs/getting-started)
- [Postman Collection](collections/bitso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitso.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Juno API

Juno is Bitso's programmable-money platform for Mexican peso (MXN) rails and stablecoin operations. The API supports account creation, SPEI funding, MXNB stablecoin mint / redeem and on-chain transfer, and destination payouts for fintechs operating in Mexico.

- **Human URL:** [https://docs.bitso.com/juno/docs/getting-started](https://docs.bitso.com/juno/docs/getting-started)
- **Base URL:** `https://api.bitso.com`

#### Tags

- Juno
- Stablecoin
- SPEI
- Mexico

#### Properties

- [Documentation](https://docs.bitso.com/juno/docs/getting-started)
- [Postman Collection](collections/bitso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitso.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://bitso.com/)
- [Business](https://bitso.com/business)
- [Documentation](https://docs.bitso.com/)
- [Open A P I  Index](https://docs.bitso.com/llms.txt)
- [LinkedIn](https://www.linkedin.com/company/bitso)
- [Git Hub](https://github.com/bitso)
- [Status](https://status.bitso.com/)

## Maintainers

**FN:** API Evangelist
**URL:** https://apievangelist.com
