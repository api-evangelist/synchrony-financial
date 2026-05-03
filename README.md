# Synchrony Financial

Synchrony Financial is one of the nation's premier consumer financial services companies, providing a range of credit products through programs established with retailers, manufacturers, and merchants. Synchrony offers APIs enabling partners and retailers to integrate credit applications, authorizations, payments, loyalty, and account management into their digital commerce experiences.

**Type:** Company (Fortune 500)
**Developer Portal:** [developer.syf.com](https://developer.syf.com/)
**Website:** [synchrony.com](https://www.synchrony.com)

## APIs

### Credit Authorization API

The Synchrony Credit Authorization API allows merchants to perform credit card transactions including purchases, preauthorizations, completions, payments, refunds, and reversals. Supports payment tokens and full account numbers across web, mobile, and point-of-sale channels.

- **Documentation:** [developer.syf.com/our-products/credit-authorizations](https://developer.syf.com/our-products/credit-authorizations)
- **OpenAPI:** [openapi/synchrony-financial-credit-authorization-openapi.yml](openapi/synchrony-financial-credit-authorization-openapi.yml)

| Method | Path | Summary |
|--------|------|---------|
| POST | /v1/authorizations/purchases | Create Purchase Authorization |
| POST | /v1/authorizations/preauthorizations | Create Preauthorization |
| POST | /v1/authorizations/completions | Complete Preauthorization |
| POST | /v1/authorizations/payments | Submit Payment |
| POST | /v1/authorizations/refunds | Create Refund |
| POST | /v1/authorizations/reversals | Create Reversal |

### Quickscreen Apply API

Synchrony's Quickscreen preapproval engine offers instant credit decisions using only a customer's name and address via a soft credit check. The mApply feature enables mobile credit applications with instant decisions.

- **Documentation:** [developer.syf.com/our-products/quickscreen-apply](https://developer.syf.com/our-products/quickscreen-apply)
- **OpenAPI:** [openapi/synchrony-financial-quickscreen-apply-openapi.yml](openapi/synchrony-financial-quickscreen-apply-openapi.yml)

| Method | Path | Summary |
|--------|------|---------|
| POST | /v1/credit/preapproval | Submit Preapproval Request |
| POST | /v1/credit/applications | Submit Credit Application |
| GET | /v1/credit/applications/{applicationId} | Get Application Decision |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/credit-authorization.yaml](capabilities/shared/credit-authorization.yaml) | Credit Authorization API consumed definition |
| [capabilities/shared/quickscreen-apply.yaml](capabilities/shared/quickscreen-apply.yaml) | Quickscreen Apply API consumed definition |

### Workflow Capabilities

| Capability | Description | Tools |
|-----------|-------------|-------|
| [retail-credit.yaml](capabilities/retail-credit.yaml) | Unified retail credit workflow combining preapproval, authorization, and payments | 8 tools |

## Artifacts

| Type | File |
|------|------|
| OpenAPI | [openapi/synchrony-financial-credit-authorization-openapi.yml](openapi/synchrony-financial-credit-authorization-openapi.yml) |
| OpenAPI | [openapi/synchrony-financial-quickscreen-apply-openapi.yml](openapi/synchrony-financial-quickscreen-apply-openapi.yml) |
| Spectral Rules | [rules/synchrony-financial-rules.yml](rules/synchrony-financial-rules.yml) |
| JSON Schema | [json-schema/synchrony-financial-transaction-schema.json](json-schema/synchrony-financial-transaction-schema.json) |
| JSON Schema | [json-schema/synchrony-financial-credit-application-schema.json](json-schema/synchrony-financial-credit-application-schema.json) |
| JSON Structure | [json-structure/synchrony-financial-transaction-structure.json](json-structure/synchrony-financial-transaction-structure.json) |
| JSON-LD Context | [json-ld/synchrony-financial-context.jsonld](json-ld/synchrony-financial-context.jsonld) |
| Vocabulary | [vocabulary/synchrony-financial-vocabulary.yml](vocabulary/synchrony-financial-vocabulary.yml) |

## Examples

| File | Description |
|------|-------------|
| [examples/synchrony-financial-credit-authorization-createPurchase-example.json](examples/synchrony-financial-credit-authorization-createPurchase-example.json) | Purchase authorization request/response |
| [examples/synchrony-financial-quickscreen-apply-submitPreapproval-example.json](examples/synchrony-financial-quickscreen-apply-submitPreapproval-example.json) | Quickscreen preapproval request/response |

## Features

- Credit Authorization (Purchase, Preauth, Completion, Payment, Refund, Reversal)
- Quickscreen Preapproval Engine (Soft Pull, No Credit Impact)
- Mobile Credit Application (mApply)
- Payment Token Support
- Web, Mobile, and POS Channel Support
- Sandbox Environment

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
