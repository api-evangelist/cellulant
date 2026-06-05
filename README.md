# Cellulant (cellulant)

Cellulant is a pan-African payments platform headquartered in Nairobi, Kenya, operating across 35 African countries. Its flagship product Tingg is a single API that lets businesses collect online and offline payments, disburse to mobile money wallets and bank accounts, vend airtime and data, pay bills, and engage customers by SMS — interoperably across 350+ banks, mobile network operators, and card networks. Cellulant processes more than 4.5 million transactions per day for over 2,000 enterprise merchants and powers payments for ~220 million consumers. The Tingg platform exposes three primary developer-facing surfaces: Tingg Checkout 3.0 (Express, Custom and Direct Card), Tingg Payouts (the Beep global JSON endpoint), and Tingg Engage (transactional SMS). Cellulant ships official SDKs for PHP, Python, Node.js, .NET, JavaScript, plus a WooCommerce plugin.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cellulant/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cellulant/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Payments
- Mobile Money
- Checkout
- Payouts
- Disbursement
- Africa
- Pan-African
- Fintech
- Bank Transfer
- Cards
- Airtime
- Bill Payment
- SMS
- OTP
- Tingg

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Cellulant Tingg Checkout API

Tingg Checkout 3.0 — a single integration to collect payments across 25+ African markets via Express Checkout (hosted/modal), Custom Checkout (host-to-host), and the Direct Card API (3DS / 3DS-less / 2D). Supports mobile money, cards, direct bank transfer, and 283+ payment methods.

- **Human URL:** [https://docs.tingg.africa/docs/introduction](https://docs.tingg.africa/docs/introduction)

#### Tags

- Payments
- Checkout
- Mobile Money
- Cards
- Bank Transfer
- Africa

#### Properties

- [Documentation](https://docs.tingg.africa/docs/introduction)
- [Documentation](https://docs.tingg.africa/docs/checkout-v3-express-checkout)
- [Documentation](https://docs.tingg.africa/docs/checkout-v3-custom-checkout)
- [Documentation](https://docs.tingg.africa/docs/checkout-v3-direct-card)
- [Documentation](https://docs.tingg.africa/reference/acknowledge-payments)
- [Webhook](https://docs.tingg.africa/reference/4-implement-webhook-via-callback-url-1)
- [OpenAPI](openapi/cellulant-checkout-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cellulant-checkout-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cellulant-checkout-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cellulant-checkout-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cellulant-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cellulant-create-express-checkout-example.json)

### Cellulant Tingg Payouts API

Tingg Payouts (Beep) — a single global JSON endpoint that dispatches postPayment, queryPayment, validateAccount, getBill, getBalance, and refundPayment functions for mobile-money B2C, bulk disbursement, cross-border bank transfers, airtime/data vending, and bill payments (DSTV, GOTV, electricity, water) across 35 African countries.

- **Human URL:** [https://docs.tingg.africa/docs/payouts-get-started](https://docs.tingg.africa/docs/payouts-get-started)

#### Tags

- Payments
- Payouts
- Disbursement
- Mobile Money
- Bank Transfer
- Airtime
- Africa

#### Properties

- [Documentation](https://docs.tingg.africa/docs/payouts-get-started)
- [Documentation](https://docs.tingg.africa/reference/postpayment)
- [OpenAPI](openapi/cellulant-payouts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cellulant-payouts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cellulant-payouts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cellulant-payout-packet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/cellulant-post-payment-example.json)

### Cellulant Tingg Engage API

Tingg Engage — single global entry point for transactional alerts. Queue OTP, transactional, and standard SMS with templated parameters and receive per-message delivery callbacks.

- **Human URL:** [https://docs.tingg.africa/reference/engagement-service-api-v2](https://docs.tingg.africa/reference/engagement-service-api-v2)

#### Tags

- SMS
- OTP
- Notifications
- Engagement
- Africa

#### Properties

- [Documentation](https://docs.tingg.africa/reference/engagement-service-api-v2)
- [Documentation](https://docs.tingg.africa/reference/engagement-apis)
- [OpenAPI](openapi/cellulant-engage-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cellulant-engage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cellulant-engage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/cellulant-send-engagement-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.cellulant.io)
- [Product](https://tingg.africa)
- [Portal](https://developer.tingg.africa)
- [Documentation](https://docs.tingg.africa)
- [Documentation](https://docs.tingg.africa/docs/introduction)
- [Documentation](https://docs.tingg.africa/reference)
- [Getting Started](https://docs.tingg.africa/docs/checkout-v3-getting-started)
- [Sandbox](https://app.sandbox.tingg.africa)
- [Sign Up](https://app.sandbox.tingg.africa)
- [Pricing](https://tingg.africa/pricing/)
- [Checkout](https://tingg.africa/checkout/)
- [Payouts](https://tingg.africa/payouts/)
- [Payment Gateway](https://tingg.africa/payment-gateway/)
- [Payment Pages](https://tingg.africa/payment-pages/)
- [Payment Infrastructure](https://www.cellulant.io/business-offerings/payment-infrastructure/)
- [Blog](https://www.cellulant.io/category/blog/)
- [Blog](https://tingg.africa/blog/)
- [Press](https://www.cellulant.io/category/press-release/)
- [GitHub Organization](https://github.com/CellulantCorp)
- [SDK](https://packagist.org/packages/tingg/checkout)
- [SDK](https://pypi.org/project/Tingg/)
- [SDK](https://www.npmjs.com/package/@tingg-sdk/checkout)
- [SDK](https://www.nuget.org/packages/Tingg.Checkout.Net)
- [SDK](https://cdn.cellulant.africa/js/tingg-checkout-library.js)
- [SDK](https://github.com/CellulantCorp/Express-Checkout-PHP-Client)
- [SDK](https://github.com/CellulantCorp/express-checkout-python)
- [SDK](https://github.com/CellulantCorp/express-checkout-nodejs)
- [SDK](https://github.com/CellulantCorp/express-checkout-c-sharp)
- [Plugin](https://github.com/CellulantCorp/cellulant-tingg-payment-gateway)
- [Plugin](https://wordpress.org/plugins/cellulant-tingg-checkout/)
- [Plugin](https://github.com/CellulantCorp/mula-wordpress-plugin)
- [LinkedIn](https://www.linkedin.com/company/cellulant-corporation)
- [Twitter](https://twitter.com/cellulant)
- [YouTube](https://www.youtube.com/@CellulantCorp)
- [Careers](https://www.cellulant.io/careers/)
- [Contact](https://www.cellulant.io/contact-us/)
- [Terms of Service](https://www.cellulant.io/terms/)
- [Privacy Policy](https://www.cellulant.io/privacy-policy/)
- [Plans](plans/cellulant-plans-pricing.yml)
- [Rate Limits](rate-limits/cellulant-rate-limits.yml)
- [Fin Ops](finops/cellulant-finops.yml)
- [Vocabulary](vocabulary/cellulant-vocabulary.yml)
- [Spectral Rules](rules/cellulant-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
