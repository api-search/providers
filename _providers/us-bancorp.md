---
api_count: 11
api_specs:
- filename: us-bank-corporate-account-information-openapi.yml
  format: yaml
  label: US Bank Corporate Account Information API
  slug: us-bank-corporate-account-information
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-corporate-account-information-openapi.yml
- filename: us-bank-rtp-openapi.yml
  format: yaml
  label: US Bank RTP Real-Time Payments API
  slug: us-bank-rtp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-rtp-openapi.yml
- filename: us-bank-ach-originations-openapi.yml
  format: yaml
  label: US Bank ACH Originations API
  slug: us-bank-ach-originations
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-ach-originations-openapi.yml
- filename: us-bank-positive-pay-openapi.yml
  format: yaml
  label: US Bank Positive Pay API
  slug: us-bank-positive-pay
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-positive-pay-openapi.yml
- filename: us-bank-push-to-card-openapi.yml
  format: yaml
  label: US Bank Push to Card API
  slug: us-bank-push-to-card
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-push-to-card-openapi.yml
apis:
- description: The Corporate Account Information API provides access to U.S. Bank deposit account balances and transaction data for corporate customers. It enables retrieval of current-day and previous-day account b
  name: US Bank Corporate Account Information API
  slug: us-bank-corporate-account-information
- description: 'The RTP Real-Time Payments API enables 24/7/365 real-time payment origination through The Clearing House RTP network. Supports credit transfer messages, request for payment (RFP), and RTP eligibility '
  name: US Bank RTP Real-Time Payments API
  slug: us-bank-rtp
- description: The ACH Originations API enables origination of ACH (Automated Clearing House) payments from U.S. Bank corporate accounts. Supports standard ACH credit and debit transactions for payroll, vendor payme
  name: US Bank ACH Originations API
  slug: us-bank-ach-originations
- description: The Positive Pay API helps detect check fraud by electronically matching checks to issued items. Enables retrieval of exception items (checks that don't match issued items), submission of pay/return d
  name: US Bank Positive Pay API
  slug: us-bank-positive-pay
- description: The Push to Card API enables instant fund disbursements directly to Visa and Mastercard debit cards. Ideal for disbursements, refunds, and payouts up to $125,000 per transaction. Transactions are irre
  name: US Bank Push to Card API
  slug: us-bank-push-to-card
- description: The Wire Transfers API enables domestic and international wire transfer origination from U.S. Bank corporate accounts for large-value, time-sensitive payments.
  name: US Bank Wire Transfers API
  slug: us-bank-wire-transfers
- description: The Data Toolbox API provides access to U.S. Bank retail banking consumer account data including checking, savings, credit card, mortgage, and brokerage account information. Used to build personalized
  name: US Bank Data Toolbox API
  slug: us-bank-data-toolbox
- description: The Voyager Fleet API suite provides fleet management capabilities for the Voyager network, enabling access to fleet transaction data, vehicle management, account information, and reporting for corpor
  name: US Bank Voyager Fleet API
  slug: us-bank-voyager
- description: The Freight Payment API suite provides freight audit and payment processing capabilities, enabling freight shippers to submit and receive transaction data through a single API and manage freight payme
  name: US Bank Freight Payment API
  slug: us-bank-freight-payment
- description: The Instant Payments API enables instant payment origination supporting FedNow and RTP payment rails for real-time settlement.
  name: US Bank Instant Payments API
  slug: us-bank-instant-payments
- description: The Bank Holidays API provides information about U.S. Bank processing holidays and Federal Reserve banking holidays, useful for payment scheduling and clearing house availability calculations.
  name: US Bank Holidays API
  slug: us-bank-bank-holidays
capabilities:
- description: 'Unified payments capability composing US Bank RTP, Push to Card, and Positive Pay APIs. Used by payments teams and corporate finance for real-time payment origination, instant card disbursements, and '
  name: US Bank Payments
  slug: payments
- description: Unified treasury management capability composing US Bank Corporate Account Information and RTP Real-Time Payments APIs. Used by corporate treasury teams, ERP systems, and financial operations for acco
  name: US Bank Treasury Management
  slug: treasury-management
common: []
created: '2024-11-21'
description: U.S. Bancorp is the parent company of U.S. Bank National Association, one of the largest commercial banks in the United States. U.S. Bank provides a developer portal at developer.usbank.com offering APIs for corporate banking, payments, and treasury management including RTP, ACH, Positive Pay, corporate account information, data toolbox, fleet management (Voyager), freight payment, and push-to-card capabilities. Authentication uses OAuth MFA with SinglePoint credentials.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Us Bancorp Context
  property_count: 5
  slug: us-bancorp-context
layout: provider
modified: '2026-05-03'
name: US Bancorp
rules:
- name: US Bancorp API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: us-bank-rules
skills: []
slug: us-bancorp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-bancorp\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/apis.yml\napis:\n  - aid: us-bancorp:us-bank-corporate-account-information\n    name: US Bank Corporate Account Information API\n    tags:\n      - Banking\n      - Corporate Banking\n      - Account Information\n      - Treasury Management\n      - Finance\n      - Fortune 500\n    humanURL: https://developer.usbank.com/solution-areas/treasury-management-apis\n    baseURL: https://api.usbank.com\n    properties:\n      - url: https://developer.usbank.com/solution-areas/treasury-management-apis\n        type: Documentation\n      - url: https://developer.usbank.com/\n        type: DeveloperPortal\n      - url: https://developer.usbank.com/getting-started-with-our-apis\n        type: GettingStarted\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-corporate-account-information-openapi.yml\n        type: OpenAPI\n    \
  \  - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-schema/us-bank-account-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-schema/us-bank-transaction-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-ld/us-bancorp-context.jsonld\n        type: JSONLDContext\n    description: >-\n      The Corporate Account Information API provides access to U.S. Bank deposit account balances\n      and transaction data for corporate customers. It enables retrieval of current-day and\n      previous-day account balances (available, ledger, and collected), transaction history\n      up to 60 days (with optional 12 or 24-month retention), and deposit account statements.\n      Authentication uses OAuth MFA with SinglePoint credentials.\n  - aid: us-bancorp:us-bank-rtp\n    name: US Bank RTP Real-Time Payments\
  \ API\n    tags:\n      - Payments\n      - Real-Time Payments\n      - RTP\n      - Banking\n      - Treasury Management\n      - Finance\n    humanURL: https://developer.usbank.com/solution-areas/corporate-payment-apis\n    properties:\n      - url: https://developer.usbank.com/solution-areas/corporate-payment-apis\n        type: Documentation\n      - url: https://developer.usbank.com/products/rtp-credit-transfer-message/v1\n        type: CreditTransferDocs\n      - url: https://developer.usbank.com/product-suites/rtp-api-product-suite\n        type: ProductSuite\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-rtp-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/capabilities/treasury-management.yaml\n        type: NaftikoCapability\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/capabilities/payments.yaml\n  \
  \      type: NaftikoCapability\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/rules/us-bank-rules.yml\n        type: SpectralRuleset\n    description: >-\n      The RTP Real-Time Payments API enables 24/7/365 real-time payment origination through\n      The Clearing House RTP network. Supports credit transfer messages, request for payment (RFP),\n      and RTP eligibility verification. Transactions settle instantly and are irrevocable once sent.\n  - aid: us-bancorp:us-bank-ach-originations\n    name: US Bank ACH Originations API\n    tags:\n      - Payments\n      - ACH\n      - Banking\n      - Corporate Payments\n      - Finance\n    humanURL: https://developer.usbank.com/products/ach-originations/v1\n    properties:\n      - url: https://developer.usbank.com/products/ach-originations/v1\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-ach-originations-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The ACH Originations API enables origination of ACH (Automated Clearing House) payments\n      from U.S. Bank corporate accounts. Supports standard ACH credit and debit transactions\n      for payroll, vendor payments, and customer collections.\n  - aid: us-bancorp:us-bank-positive-pay\n    name: US Bank Positive Pay API\n    tags:\n      - Payments\n      - Fraud Prevention\n      - Check Management\n      - Treasury Management\n      - Banking\n    humanURL: https://developer.usbank.com/products/positive-pay/v1\n    properties:\n      - url: https://developer.usbank.com/products/positive-pay/v1\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-positive-pay-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Positive Pay API helps detect check fraud by electronically matching checks to\n      issued items. Enables retrieval of exception\
  \ items (checks that don't match issued items),\n      submission of pay/return decisions, and access to exception history. Exceptions are\n      available 9am-3pm local processing time.\n  - aid: us-bancorp:us-bank-push-to-card\n    name: US Bank Push to Card API\n    tags:\n      - Payments\n      - Disbursements\n      - Debit Card\n      - Banking\n      - Finance\n    humanURL: https://developer.usbank.com/products/push-to-card/v1\n    properties:\n      - url: https://developer.usbank.com/products/push-to-card/v1\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-push-to-card-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Push to Card API enables instant fund disbursements directly to Visa and Mastercard\n      debit cards. Ideal for disbursements, refunds, and payouts up to $125,000 per transaction.\n      Transactions are irrevocable once sent and provide immediate fund access\
  \ to recipients.\n  - aid: us-bancorp:us-bank-wire-transfers\n    name: US Bank Wire Transfers API\n    tags:\n      - Payments\n      - Wire Transfers\n      - Banking\n      - Treasury Management\n      - Finance\n    humanURL: https://developer.usbank.com/products/wire-transfers/v1\n    properties:\n      - url: https://developer.usbank.com/products/wire-transfers/v1\n        type: Documentation\n    description: >-\n      The Wire Transfers API enables domestic and international wire transfer origination\n      from U.S. Bank corporate accounts for large-value, time-sensitive payments.\n  - aid: us-bancorp:us-bank-data-toolbox\n    name: US Bank Data Toolbox API\n    tags:\n      - Banking\n      - Account Data\n      - Retail Banking\n      - Finance\n      - Open Banking\n    humanURL: https://developer.usbank.com/products/data-toolbox/v1\n    properties:\n      - url: https://developer.usbank.com/products/data-toolbox/v1\n        type: Documentation\n      - url: https://developer.usbank.com/products/data-toolbox-accounts/v1\n\
  \        type: AccountsDocs\n      - url: https://developer.usbank.com/solution-areas/retail-banking-apis\n        type: RetailBankingAPIs\n    description: >-\n      The Data Toolbox API provides access to U.S. Bank retail banking consumer account data\n      including checking, savings, credit card, mortgage, and brokerage account information.\n      Used to build personalized financial management experiences and enable embedded banking.\n  - aid: us-bancorp:us-bank-voyager\n    name: US Bank Voyager Fleet API\n    tags:\n      - Fleet Management\n      - Transportation\n      - Banking\n      - Finance\n      - Corporate Payments\n    humanURL: https://developer.usbank.com/product-suites/voyager-api-product-suite\n    properties:\n      - url: https://developer.usbank.com/product-suites/voyager-api-product-suite\n        type: Documentation\n      - url: https://developer.usbank.com/products/voyager-transactions/v2\n        type: TransactionsDocs\n      - url: https://developer.usbank.com/products/voyager-vehicles/v1\n\
  \        type: VehiclesDocs\n      - url: https://developer.usbank.com/products/voyager-accounts/v1\n        type: AccountsDocs\n    description: >-\n      The Voyager Fleet API suite provides fleet management capabilities for the Voyager\n      network, enabling access to fleet transaction data, vehicle management, account information,\n      and reporting for corporate fleet card customers.\n  - aid: us-bancorp:us-bank-freight-payment\n    name: US Bank Freight Payment API\n    tags:\n      - Freight Payment\n      - Transportation\n      - Banking\n      - Finance\n      - Supply Chain\n    humanURL: https://developer.usbank.com/product-suites/freight-payment-api-product-suite\n    properties:\n      - url: https://developer.usbank.com/product-suites/freight-payment-api-product-suite\n        type: Documentation\n      - url: https://developer.usbank.com/products/freight-payment-transactions/v1\n        type: TransactionsDocs\n      - url: https://developer.usbank.com/products/freight-payment-user-management/v1\n\
  \        type: UserManagementDocs\n    description: >-\n      The Freight Payment API suite provides freight audit and payment processing capabilities,\n      enabling freight shippers to submit and receive transaction data through a single API\n      and manage freight payment users.\n  - aid: us-bancorp:us-bank-instant-payments\n    name: US Bank Instant Payments API\n    tags:\n      - Payments\n      - Instant Payments\n      - Banking\n      - Finance\n    humanURL: https://developer.usbank.com/products/instant-payments/v2\n    properties:\n      - url: https://developer.usbank.com/products/instant-payments/v2\n        type: Documentation\n    description: >-\n      The Instant Payments API enables instant payment origination supporting FedNow and\n      RTP payment rails for real-time settlement.\n  - aid: us-bancorp:us-bank-bank-holidays\n    name: US Bank Holidays API\n    tags:\n      - Banking\n      - Holidays\n      - Reference Data\n      - Finance\n    humanURL: https://developer.usbank.com/products/bank-holidays/v1\n\
  \    properties:\n      - url: https://developer.usbank.com/products/bank-holidays/v1\n        type: Documentation\n    description: >-\n      The Bank Holidays API provides information about U.S. Bank processing holidays and\n      Federal Reserve banking holidays, useful for payment scheduling and clearing house\n      availability calculations.\nname: US Bancorp\ntags:\n  - Banking\n  - Finance\n  - Fortune 500\n  - Corporate Banking\n  - Payments\n  - Open Banking\n  - Treasury Management\n  - Consumer Banking\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-21'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  U.S. Bancorp is the parent company of U.S. Bank National Association, one of the largest\n  commercial banks in the United States. U.S. Bank provides a developer portal at\n  developer.usbank.com offering APIs for corporate banking, payments, and treasury management\n  including\
  \ RTP, ACH, Positive Pay, corporate account information, data toolbox, fleet management\n  (Voyager), freight payment, and push-to-card capabilities. Authentication uses OAuth MFA\n  with SinglePoint credentials.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/apis.yml
tags:
- Banking
- Finance
- Fortune 500
- Corporate Banking
- Payments
- Open Banking
- Treasury Management
- Consumer Banking
url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/apis.yml
use_cases: []
---
