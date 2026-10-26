# Cellulant (cellulant)

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
