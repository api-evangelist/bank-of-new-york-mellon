# BNY Mellon (bank-of-new-york-mellon)
BNY Mellon is a global investments company providing asset servicing, asset management, wealth management, treasury services, and clearance and collateral management for institutions and individuals. The BNY Mellon Marketplace provides Treasury Services APIs for corporate clients to automate payments, account management, and balance reporting.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bank-of-new-york-mellon/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Asset Servicing, Banking, Institutional Banking, Payments, Treasury, Wire Transfers

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### BNY Mellon Treasury Services API
The BNY Mellon Treasury Services API enables institutional clients to programmatically initiate and track payments (wire, ACH, SWIFT, CHIPS), access account balances and transaction history, and manage funds transfers across multiple currencies.

**Human URL:** [https://marketplace.bnymellon.com/treasury/api-central/](https://marketplace.bnymellon.com/treasury/api-central/)

#### Tags:

 - Accounts, Balances, Funds Transfers, Institutional Banking, Payments, Treasury, Wire Transfers

#### Properties

- [Documentation](https://marketplace.bnymellon.com/treasury/api-central/)
- [BNY Developer Marketplace](https://developer.bny.com/app/)
- [OpenAPI](openapi/bny-mellon-treasury-services-api-openapi.yml)

## Common Properties

- [Website](https://www.bnymellon.com/)
- [Treasury API Central](https://marketplace.bnymellon.com/treasury/api-central/)
- [BNY Developer Marketplace](https://developer.bny.com/app/)
- [PrivacyPolicy](https://www.bnymellon.com/us/en/disclaimers/privacy-notice.html)

## Features

| Name | Description |
|------|-------------|
| Account Management | Access institutional account details and metadata. |
| Balance Reporting | Real-time and intraday account balance queries. |
| Transaction History | Detailed transaction history with date range filtering. |
| Payment Initiation | Initiate wire, ACH, SWIFT, and CHIPS payments globally. |
| Funds Transfers | Internal account-to-account funds transfer management. |
| OAuth2 Security | Client credentials OAuth2 flow for secure API access. |
| Sandbox Environment | UAT sandbox for developer testing and integration validation. |
| Multi-Currency | Support for payments and balances across multiple currencies. |

## Use Cases

| Name | Description |
|------|-------------|
| Treasury Automation | Automate daily cash positioning, balance queries, and payment workflows. |
| Payment Processing | Initiate global wire, ACH, and SWIFT payments programmatically. |
| Liquidity Management | Real-time account balance visibility for institutional liquidity decisions. |
| Reconciliation | Automated transaction downloads for reconciliation and reporting. |
| ERP Integration | Connect SAP, Oracle, and other ERP/TMS systems to BNY Mellon treasury APIs. |
| Custody Operations | Integrate treasury APIs into asset servicing and custody workflows. |

## Artifacts

### OpenAPI

- [BNY Mellon Treasury Services API](openapi/bny-mellon-treasury-services-api-openapi.yml)

### JSON-LD

- [BNY Mellon JSON-LD Context](json-ld/bny-mellon-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Treasury Services API](capabilities/shared/treasury-services-api.yaml) — 9 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Treasury Operations](capabilities/treasury-operations.yaml) | Treasury Services | 6 | Corporate Treasurer, Treasury Analyst, Institutional Client |

## Vocabulary

- [BNY Mellon Vocabulary](vocabulary/bny-mellon-vocabulary.yaml) — 3 resources, 5 actions, 1 workflow, 3 personas

## Rules

- [BNY Mellon Spectral Rules](rules/bny-mellon-spectral-rules.yml) — 16 rules enforcing API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
