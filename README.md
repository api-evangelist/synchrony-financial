# Synchrony Financial (synchrony-financial)

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

Synchrony Financial is one of the nation's premier consumer financial services companies, providing a range of credit products through programs established with retailers, manufacturers, and merchants. Synchrony offers APIs enabling partners and retailers to integrate credit applications, authorizations, payments, loyalty, and account management into their digital commerce experiences.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Credit
- Payments
- Consumer Finance
- Retail Finance

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Synchrony Credit Authorization API

The Synchrony Credit Authorization API allows merchants and retailers to perform credit card transactions including purchases, preauthorizations, completions, payments, refunds, and reversals. The API supports transactions via payment tokens or full account numbers across web, mobile, and point-of-sale channels.

- **Human URL:** [https://developer.syf.com/our-products/credit-authorizations](https://developer.syf.com/our-products/credit-authorizations)
- **Base URL:** `https://api.syf.com`

#### Tags

- Credit Authorization
- Payments
- Purchases
- Refunds
- Retail Finance

#### Properties

- [Documentation](https://developer.syf.com/our-products/credit-authorizations)
- [OpenAPI](openapi/synchrony-financial-credit-authorization-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/synchrony-financial-credit-authorization.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synchrony-financial-credit-authorization.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Synchrony Quickscreen Apply API

Synchrony's Quickscreen API is a preapproval engine that allows merchants to offer instant credit decisions using only a customer's name and address. It runs a soft credit check and returns a real-time decision, enabling seamless credit offering within the shopping experience.

- **Human URL:** [https://developer.syf.com/our-products/quickscreen-apply](https://developer.syf.com/our-products/quickscreen-apply)
- **Base URL:** `https://api.syf.com`

#### Tags

- Credit Application
- Preapproval
- Quickscreen
- Consumer Finance

#### Properties

- [Documentation](https://developer.syf.com/our-products/quickscreen-apply)
- [OpenAPI](openapi/synchrony-financial-quickscreen-apply-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/synchrony-financial-quickscreen-apply.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synchrony-financial-quickscreen-apply.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Synchrony Account Management API

The Synchrony Account Management API provides access to cardholder account information, enabling partners to retrieve account details, balance information, transaction history, and manage account servicing operations on behalf of customers.

- **Human URL:** [https://developer.syf.com/](https://developer.syf.com/)
- **Base URL:** `https://api.syf.com`

#### Tags

- Account Management
- Consumer Finance
- Credit Cards

#### Properties

- [Documentation](https://developer.syf.com/)
- [Postman Collection](collections/synchrony-financial-credit-authorization.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synchrony-financial-credit-authorization.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/synchrony-financial-quickscreen-apply.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synchrony-financial-quickscreen-apply.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/synchrony-financial)
- [Website](https://www.synchrony.com)
- [Developer Portal](https://developer.syf.com/)
- [Portal Products](https://developer.syf.com/our-products)
- [Terms of Service](https://developer.syf.com/terms-of-use)
- [Sandbox](https://developer.syf.com/)
- [J S O N L D Context](json-ld/synchrony-financial-context.jsonld)
- [Vocabulary](vocabulary/synchrony-financial-vocabulary.yml)
- [Integrations](https://www.synchrony.com/marketplace)
