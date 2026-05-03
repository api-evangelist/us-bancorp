# US Bancorp

U.S. Bancorp is the parent company of U.S. Bank National Association, one of the largest commercial banks in the United States and a Fortune 500 company. U.S. Bank provides a developer portal at developer.usbank.com offering APIs for corporate banking, payments, and treasury management including RTP real-time payments, ACH originations, Positive Pay check fraud prevention, Push to Card disbursements, corporate account information, data toolbox, Voyager fleet management, and freight payment.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Banking, Finance, Fortune 500, Corporate Banking, Payments, Open Banking, Treasury Management, Consumer Banking

## Timestamps

- **Created:** 2024-11-21
- **Modified:** 2026-05-03

## APIs

### US Bank Corporate Account Information API

Programmatic access to deposit account balances and transaction data for corporate customers.

**Human URL:** [https://developer.usbank.com/solution-areas/treasury-management-apis](https://developer.usbank.com/solution-areas/treasury-management-apis)

#### Tags

- Banking, Corporate Banking, Account Information, Treasury Management, Finance, Fortune 500

#### Properties

- [Documentation](https://developer.usbank.com/solution-areas/treasury-management-apis)
- [Developer Portal](https://developer.usbank.com/)
- [OpenAPI](openapi/us-bank-corporate-account-information-openapi.yml)
- [JSON Schema (Account)](json-schema/us-bank-account-schema.json)
- [JSON Schema (Transaction)](json-schema/us-bank-transaction-schema.json)
- [JSON-LD Context](json-ld/us-bancorp-context.jsonld)

### US Bank RTP Real-Time Payments API

24/7/365 instant payment origination via The Clearing House RTP network.

**Human URL:** [https://developer.usbank.com/solution-areas/corporate-payment-apis](https://developer.usbank.com/solution-areas/corporate-payment-apis)

#### Tags

- Payments, Real-Time Payments, RTP, Banking, Treasury Management, Finance

#### Properties

- [Documentation](https://developer.usbank.com/solution-areas/corporate-payment-apis)
- [OpenAPI](openapi/us-bank-rtp-openapi.yml)
- [Treasury Management Capability](capabilities/treasury-management.yaml)
- [Payments Capability](capabilities/payments.yaml)
- [Spectral Rules](rules/us-bank-rules.yml)

### US Bank ACH Originations API

ACH payment origination for payroll, vendor payments, and customer collections.

**Human URL:** [https://developer.usbank.com/products/ach-originations/v1](https://developer.usbank.com/products/ach-originations/v1)

#### Properties

- [Documentation](https://developer.usbank.com/products/ach-originations/v1)

### US Bank Positive Pay API

Check fraud detection by matching presented checks against issued items.

**Human URL:** [https://developer.usbank.com/products/positive-pay/v1](https://developer.usbank.com/products/positive-pay/v1)

#### Properties

- [Documentation](https://developer.usbank.com/products/positive-pay/v1)
- [OpenAPI](openapi/us-bank-positive-pay-openapi.yml)

### US Bank Push to Card API

Instant disbursements to Visa and Mastercard debit cards up to $125,000.

**Human URL:** [https://developer.usbank.com/products/push-to-card/v1](https://developer.usbank.com/products/push-to-card/v1)

#### Properties

- [Documentation](https://developer.usbank.com/products/push-to-card/v1)
- [OpenAPI](openapi/us-bank-push-to-card-openapi.yml)

### US Bank Wire Transfers API

Domestic and international wire transfer origination.

**Human URL:** [https://developer.usbank.com/products/wire-transfers/v1](https://developer.usbank.com/products/wire-transfers/v1)

#### Properties

- [Documentation](https://developer.usbank.com/products/wire-transfers/v1)

### US Bank Data Toolbox API

Retail banking consumer account data for embedded banking experiences.

**Human URL:** [https://developer.usbank.com/products/data-toolbox/v1](https://developer.usbank.com/products/data-toolbox/v1)

#### Properties

- [Documentation](https://developer.usbank.com/products/data-toolbox/v1)
- [Accounts Docs](https://developer.usbank.com/products/data-toolbox-accounts/v1)

### US Bank Voyager Fleet API

Fleet management APIs for Voyager network transactions, vehicles, and accounts.

**Human URL:** [https://developer.usbank.com/product-suites/voyager-api-product-suite](https://developer.usbank.com/product-suites/voyager-api-product-suite)

#### Properties

- [Documentation](https://developer.usbank.com/product-suites/voyager-api-product-suite)
- [Transactions Docs](https://developer.usbank.com/products/voyager-transactions/v2)
- [Vehicles Docs](https://developer.usbank.com/products/voyager-vehicles/v1)

### US Bank Freight Payment API

Freight audit and payment processing for transportation companies.

**Human URL:** [https://developer.usbank.com/product-suites/freight-payment-api-product-suite](https://developer.usbank.com/product-suites/freight-payment-api-product-suite)

#### Properties

- [Documentation](https://developer.usbank.com/product-suites/freight-payment-api-product-suite)

### US Bank Instant Payments API

Instant payment origination supporting FedNow and RTP rails.

**Human URL:** [https://developer.usbank.com/products/instant-payments/v2](https://developer.usbank.com/products/instant-payments/v2)

#### Properties

- [Documentation](https://developer.usbank.com/products/instant-payments/v2)

### US Bank Holidays API

U.S. Bank processing and Federal Reserve banking holiday information.

**Human URL:** [https://developer.usbank.com/products/bank-holidays/v1](https://developer.usbank.com/products/bank-holidays/v1)

#### Properties

- [Documentation](https://developer.usbank.com/products/bank-holidays/v1)

## Artifacts

### OpenAPI

- [Corporate Account Information API](openapi/us-bank-corporate-account-information-openapi.yml)
- [RTP Real-Time Payments API](openapi/us-bank-rtp-openapi.yml)
- [Positive Pay API](openapi/us-bank-positive-pay-openapi.yml)
- [Push to Card API](openapi/us-bank-push-to-card-openapi.yml)

### Spectral Rules

- [US Bank API Rules](rules/us-bank-rules.yml)

### Capabilities

- [Treasury Management](capabilities/treasury-management.yaml)
- [Payments](capabilities/payments.yaml)
- [Shared: Corporate Account Information](capabilities/shared/corporate-account-information.yaml)
- [Shared: RTP Payments](capabilities/shared/rtp-payments.yaml)

### JSON Schema

- [US Bank Account Schema](json-schema/us-bank-account-schema.json)
- [US Bank Transaction Schema](json-schema/us-bank-transaction-schema.json)

### JSON Structure

- [US Bank Transaction Structure](json-structure/us-bank-transaction-structure.json)

### JSON-LD

- [US Bancorp Context](json-ld/us-bancorp-context.jsonld)

### Examples

- [RTP Initiate Credit Transfer](examples/us-bank-rtp-initiate-credit-transfer-example.json)
- [Get Current Day Balances](examples/us-bank-corporate-account-information-get-current-day-balances-example.json)

### Vocabulary

- [US Bancorp Vocabulary](vocabulary/us-bancorp-vocabulary.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
