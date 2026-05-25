# Cellulant (cellulant)

Cellulant is a pan-African payments platform headquartered in Nairobi, Kenya, operating across 35 African countries. Its flagship product **Tingg** is a single API that lets businesses collect online and offline payments, disburse to mobile money wallets and bank accounts, vend airtime and data, pay bills, and engage customers by SMS — interoperably across 350+ banks, mobile network operators, and card networks. Cellulant processes more than 4.5 million transactions per day for 2,000+ enterprise merchants and powers payments for ~220 million consumers.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/cellulant/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Payments, Mobile Money, Checkout, Payouts, Disbursement, Africa, Pan-African, Fintech, Bank Transfer, Cards, Airtime, Bill Payment, SMS, OTP, Tingg

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## Reach (vendor-published)

| Metric | Value |
|---|---|
| Countries (payouts) | 35 |
| Countries (collections) | 25+ |
| Payment methods | 283+ |
| Bank / MNO / card integrations | 350+ |
| Enterprise merchants | 2,000+ |
| Daily transactions processed | 4.5M+ |
| Consumers reachable | ~220M |

## APIs

### Cellulant Tingg Checkout API

Tingg Checkout 3.0 — a single integration to collect payments across 25+ African markets via Express Checkout (hosted/modal), Custom Checkout (host-to-host), and the Direct Card API (3DS / 3DS-less / 2D). Supports mobile money, cards, direct bank transfer, and 283+ payment methods.

**Human URL:** [docs.tingg.africa/docs/introduction](https://docs.tingg.africa/docs/introduction)

- [Documentation — Introduction](https://docs.tingg.africa/docs/introduction)
- [Documentation — Express Checkout](https://docs.tingg.africa/docs/checkout-v3-express-checkout)
- [Documentation — Custom Checkout](https://docs.tingg.africa/docs/checkout-v3-custom-checkout)
- [Documentation — Direct Card](https://docs.tingg.africa/docs/checkout-v3-direct-card)
- [Documentation — Acknowledge Payments](https://docs.tingg.africa/reference/acknowledge-payments)
- [Webhook — Implement via Callback URL](https://docs.tingg.africa/reference/4-implement-webhook-via-callback-url-1)
- [OpenAPI](openapi/cellulant-checkout-api-openapi.yml)
- [JSON Schema — Checkout Request](json-schema/cellulant-checkout-request-schema.json)
- [JSON-LD](json-ld/cellulant-context.jsonld)
- [Example — Create Express Checkout](examples/cellulant-create-express-checkout-example.json)
- [Naftiko Capability — Checkout](capabilities/checkout-checkout.yaml)

### Cellulant Tingg Payouts API

Tingg Payouts (Beep) — a single global JSON endpoint that dispatches `BEEP.postPayment`, `BEEP.queryPayment`, `BEEP.validateAccount`, `BEEP.getBill`, `BEEP.getBalance`, and `BEEP.refundPayment` for mobile-money B2C, bulk disbursement, cross-border bank transfers, airtime/data vending, and bill payments (DSTV, GOTV, electricity, water) across 35 African countries.

**Human URL:** [docs.tingg.africa/docs/payouts-get-started](https://docs.tingg.africa/docs/payouts-get-started)

- [Documentation — Get Started](https://docs.tingg.africa/docs/payouts-get-started)
- [Documentation — Post a Payment](https://docs.tingg.africa/reference/postpayment)
- [OpenAPI](openapi/cellulant-payouts-api-openapi.yml)
- [JSON Schema — Payout Packet](json-schema/cellulant-payout-packet-schema.json)
- [Example — Post Payment](examples/cellulant-post-payment-example.json)
- [Naftiko Capability — Payouts](capabilities/payouts-payments.yaml)

### Cellulant Tingg Engage API

Tingg Engage — single global entry point for transactional alerts. Queue OTP, transactional, and standard SMS with templated parameters and receive per-message delivery callbacks.

**Human URL:** [docs.tingg.africa/reference/engagement-service-api-v2](https://docs.tingg.africa/reference/engagement-service-api-v2)

- [Documentation — Engagement Service v2](https://docs.tingg.africa/reference/engagement-service-api-v2)
- [Documentation — Engagement APIs](https://docs.tingg.africa/reference/engagement-apis)
- [OpenAPI](openapi/cellulant-engage-api-openapi.yml)
- [Example — Send SMS](examples/cellulant-send-engagement-example.json)
- [Naftiko Capability — Engagement](capabilities/engage-engagement.yaml)

## Common Properties

- [Website — cellulant.io](https://www.cellulant.io)
- [Product — tingg.africa](https://tingg.africa)
- [Developer Portal — developer.tingg.africa](https://developer.tingg.africa)
- [Documentation — docs.tingg.africa](https://docs.tingg.africa)
- [Documentation — API Reference](https://docs.tingg.africa/reference)
- [Getting Started — Checkout 3.0](https://docs.tingg.africa/docs/checkout-v3-getting-started)
- [Sandbox — app.sandbox.tingg.africa](https://app.sandbox.tingg.africa)
- [Pricing](https://tingg.africa/pricing/)
- [Checkout](https://tingg.africa/checkout/)
- [Payouts](https://tingg.africa/payouts/)
- [Payment Gateway](https://tingg.africa/payment-gateway/)
- [Payment Pages](https://tingg.africa/payment-pages/)
- [Payment Infrastructure](https://www.cellulant.io/business-offerings/payment-infrastructure/)
- [GitHub Organization — CellulantCorp](https://github.com/CellulantCorp)
- [LinkedIn](https://www.linkedin.com/company/cellulant-corporation)
- [Twitter / X — @cellulant](https://twitter.com/cellulant)
- [YouTube](https://www.youtube.com/@CellulantCorp)
- [Careers](https://www.cellulant.io/careers/)
- [Contact](https://www.cellulant.io/contact-us/)

### SDKs and Plugins

| Language / Platform | Package |
|---|---|
| PHP | [packagist.org/packages/tingg/checkout](https://packagist.org/packages/tingg/checkout) |
| Python | [pypi.org/project/Tingg](https://pypi.org/project/Tingg/) |
| Node.js | [npmjs.com/package/@tingg-sdk/checkout](https://www.npmjs.com/package/@tingg-sdk/checkout) |
| .NET | [nuget.org/packages/Tingg.Checkout.Net](https://www.nuget.org/packages/Tingg.Checkout.Net) |
| JS (Browser) | [cdn.cellulant.africa/js/tingg-checkout-library.js](https://cdn.cellulant.africa/js/tingg-checkout-library.js) |
| PHP (source) | [CellulantCorp/Express-Checkout-PHP-Client](https://github.com/CellulantCorp/Express-Checkout-PHP-Client) |
| Python (source) | [CellulantCorp/express-checkout-python](https://github.com/CellulantCorp/express-checkout-python) |
| Node.js (source) | [CellulantCorp/express-checkout-nodejs](https://github.com/CellulantCorp/express-checkout-nodejs) |
| C# (source) | [CellulantCorp/express-checkout-c-sharp](https://github.com/CellulantCorp/express-checkout-c-sharp) |
| WooCommerce | [CellulantCorp/cellulant-tingg-payment-gateway](https://github.com/CellulantCorp/cellulant-tingg-payment-gateway) |
| WordPress.org | [wordpress.org/plugins/cellulant-tingg-checkout](https://wordpress.org/plugins/cellulant-tingg-checkout/) |
| WordPress (Mula) | [CellulantCorp/mula-wordpress-plugin](https://github.com/CellulantCorp/mula-wordpress-plugin) |

## Artifacts

Machine-readable specifications organized by format.

### OpenAPI

- [Cellulant Tingg Checkout API](openapi/cellulant-checkout-api-openapi.yml)
- [Cellulant Tingg Payouts API](openapi/cellulant-payouts-api-openapi.yml)
- [Cellulant Tingg Engage API](openapi/cellulant-engage-api-openapi.yml)

### JSON Schema

- [Checkout Request](json-schema/cellulant-checkout-request-schema.json)
- [Payout Packet](json-schema/cellulant-payout-packet-schema.json)

### JSON-LD

- [Cellulant Tingg Context](json-ld/cellulant-context.jsonld)

### Capabilities (Naftiko)

- [Checkout](capabilities/checkout-checkout.yaml)
- [Payouts](capabilities/payouts-payments.yaml)
- [Engagement](capabilities/engage-engagement.yaml)

### Examples

- [Create Express Checkout](examples/cellulant-create-express-checkout-example.json)
- [Post Payment (Beep)](examples/cellulant-post-payment-example.json)
- [Send Engagement SMS](examples/cellulant-send-engagement-example.json)

### Spectral Rules

- [cellulant-rules.yml](rules/cellulant-rules.yml)

### Vocabulary

- [cellulant-vocabulary.yml](vocabulary/cellulant-vocabulary.yml)

### Commercial Artifacts

- [Plans / Pricing](plans/cellulant-plans-pricing.yml)
- [Rate Limits](rate-limits/cellulant-rate-limits.yml)
- [FinOps Definition](finops/cellulant-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
