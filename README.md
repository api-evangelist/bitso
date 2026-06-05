# Bitso (bitso)

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
