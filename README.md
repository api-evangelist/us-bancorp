# US Bancorp (us-bancorp)

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

U.S. Bancorp is the parent company of U.S. Bank National Association, one of the largest commercial banks in the United States. U.S. Bank provides a developer portal at developer.usbank.com offering APIs for corporate banking, payments, and treasury management including RTP, ACH, Positive Pay, corporate account information, data toolbox, fleet management (Voyager), freight payment, and push-to-card capabilities. Authentication uses OAuth MFA with SinglePoint credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Banking
- Finance
- Fortune 500
- Corporate Banking
- Payments
- Open Banking
- Treasury Management
- Consumer Banking

## Timestamps

- **Created:** 2024-11-21
- **Modified:** 2026-05-19

## APIs

### US Bank Corporate Account Information API

The Corporate Account Information API provides access to U.S. Bank deposit account balances and transaction data for corporate customers. It enables retrieval of current-day and previous-day account balances (available, ledger, and collected), transaction history up to 60 days (with optional 12 or 24-month retention), and deposit account statements. Authentication uses OAuth MFA with SinglePoint credentials.

- **Human URL:** [https://developer.usbank.com/solution-areas/treasury-management-apis](https://developer.usbank.com/solution-areas/treasury-management-apis)
- **Base URL:** `https://api.usbank.com`

#### Tags

- Banking
- Corporate Banking
- Account Information
- Treasury Management
- Finance
- Fortune 500

#### Properties

- [Documentation](https://developer.usbank.com/solution-areas/treasury-management-apis)
- [Developer Portal](https://developer.usbank.com/)
- [Getting Started](https://developer.usbank.com/getting-started-with-our-apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-corporate-account-information-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-schema/us-bank-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-schema/us-bank-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-ld/us-bancorp-context.jsonld)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank RTP Real-Time Payments API

The RTP Real-Time Payments API enables 24/7/365 real-time payment origination through The Clearing House RTP network. Supports credit transfer messages, request for payment (RFP), and RTP eligibility verification. Transactions settle instantly and are irrevocable once sent.

- **Human URL:** [https://developer.usbank.com/solution-areas/corporate-payment-apis](https://developer.usbank.com/solution-areas/corporate-payment-apis)

#### Tags

- Payments
- Real-Time Payments
- RTP
- Banking
- Treasury Management
- Finance

#### Properties

- [Documentation](https://developer.usbank.com/solution-areas/corporate-payment-apis)
- [Credit Transfer Docs](https://developer.usbank.com/products/rtp-credit-transfer-message/v1)
- [Product Suite](https://developer.usbank.com/product-suites/rtp-api-product-suite)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-rtp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Ruleset](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/rules/us-bank-rules.yml)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank ACH Originations API

The ACH Originations API enables origination of ACH (Automated Clearing House) payments from U.S. Bank corporate accounts. Supports standard ACH credit and debit transactions for payroll, vendor payments, and customer collections.

- **Human URL:** [https://developer.usbank.com/products/ach-originations/v1](https://developer.usbank.com/products/ach-originations/v1)

#### Tags

- Payments
- ACH
- Banking
- Corporate Payments
- Finance

#### Properties

- [Documentation](https://developer.usbank.com/products/ach-originations/v1)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-ach-originations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Positive Pay API

The Positive Pay API helps detect check fraud by electronically matching checks to issued items. Enables retrieval of exception items (checks that don't match issued items), submission of pay/return decisions, and access to exception history. Exceptions are available 9am-3pm local processing time.

- **Human URL:** [https://developer.usbank.com/products/positive-pay/v1](https://developer.usbank.com/products/positive-pay/v1)

#### Tags

- Payments
- Fraud Prevention
- Check Management
- Treasury Management
- Banking

#### Properties

- [Documentation](https://developer.usbank.com/products/positive-pay/v1)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-positive-pay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Push to Card API

The Push to Card API enables instant fund disbursements directly to Visa and Mastercard debit cards. Ideal for disbursements, refunds, and payouts up to $125,000 per transaction. Transactions are irrevocable once sent and provide immediate fund access to recipients.

- **Human URL:** [https://developer.usbank.com/products/push-to-card/v1](https://developer.usbank.com/products/push-to-card/v1)

#### Tags

- Payments
- Disbursements
- Debit Card
- Banking
- Finance

#### Properties

- [Documentation](https://developer.usbank.com/products/push-to-card/v1)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-push-to-card-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Wire Transfers API

The Wire Transfers API enables domestic and international wire transfer origination from U.S. Bank corporate accounts for large-value, time-sensitive payments.

- **Human URL:** [https://developer.usbank.com/products/wire-transfers/v1](https://developer.usbank.com/products/wire-transfers/v1)

#### Tags

- Payments
- Wire Transfers
- Banking
- Treasury Management
- Finance

#### Properties

- [Documentation](https://developer.usbank.com/products/wire-transfers/v1)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Data Toolbox API

The Data Toolbox API provides access to U.S. Bank retail banking consumer account data including checking, savings, credit card, mortgage, and brokerage account information. Used to build personalized financial management experiences and enable embedded banking.

- **Human URL:** [https://developer.usbank.com/products/data-toolbox/v1](https://developer.usbank.com/products/data-toolbox/v1)

#### Tags

- Banking
- Account Data
- Retail Banking
- Finance
- Open Banking

#### Properties

- [Documentation](https://developer.usbank.com/products/data-toolbox/v1)
- [Accounts Docs](https://developer.usbank.com/products/data-toolbox-accounts/v1)
- [Retail Banking A P Is](https://developer.usbank.com/solution-areas/retail-banking-apis)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Voyager Fleet API

The Voyager Fleet API suite provides fleet management capabilities for the Voyager network, enabling access to fleet transaction data, vehicle management, account information, and reporting for corporate fleet card customers.

- **Human URL:** [https://developer.usbank.com/product-suites/voyager-api-product-suite](https://developer.usbank.com/product-suites/voyager-api-product-suite)

#### Tags

- Fleet Management
- Transportation
- Banking
- Finance
- Corporate Payments

#### Properties

- [Documentation](https://developer.usbank.com/product-suites/voyager-api-product-suite)
- [Transactions Docs](https://developer.usbank.com/products/voyager-transactions/v2)
- [Vehicles Docs](https://developer.usbank.com/products/voyager-vehicles/v1)
- [Accounts Docs](https://developer.usbank.com/products/voyager-accounts/v1)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Freight Payment API

The Freight Payment API suite provides freight audit and payment processing capabilities, enabling freight shippers to submit and receive transaction data through a single API and manage freight payment users.

- **Human URL:** [https://developer.usbank.com/product-suites/freight-payment-api-product-suite](https://developer.usbank.com/product-suites/freight-payment-api-product-suite)

#### Tags

- Freight Payment
- Transportation
- Banking
- Finance
- Supply Chain

#### Properties

- [Documentation](https://developer.usbank.com/product-suites/freight-payment-api-product-suite)
- [Transactions Docs](https://developer.usbank.com/products/freight-payment-transactions/v1)
- [User Management Docs](https://developer.usbank.com/products/freight-payment-user-management/v1)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Instant Payments API

The Instant Payments API enables instant payment origination supporting FedNow and RTP payment rails for real-time settlement.

- **Human URL:** [https://developer.usbank.com/products/instant-payments/v2](https://developer.usbank.com/products/instant-payments/v2)

#### Tags

- Payments
- Instant Payments
- Banking
- Finance

#### Properties

- [Documentation](https://developer.usbank.com/products/instant-payments/v2)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Bank Holidays API

The Bank Holidays API provides information about U.S. Bank processing holidays and Federal Reserve banking holidays, useful for payment scheduling and clearing house availability calculations.

- **Human URL:** [https://developer.usbank.com/products/bank-holidays/v1](https://developer.usbank.com/products/bank-holidays/v1)

#### Tags

- Banking
- Holidays
- Reference Data
- Finance

#### Properties

- [Documentation](https://developer.usbank.com/products/bank-holidays/v1)
- [Postman Collection](collections/us-bank-corporate-account-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-corporate-account-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-positive-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-positive-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-push-to-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-push-to-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/us-bank-rtp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/us-bank-rtp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/usbank)
- [LinkedIn](https://www.linkedin.com/company/us-bank)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
