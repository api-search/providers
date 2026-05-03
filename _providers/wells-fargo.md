---
api_count: 3
api_specs:
- filename: wells-fargo-gateway-api-openapi.yml
  format: yaml
  label: Wells Fargo Gateway API
  slug: gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/openapi/wells-fargo-gateway-api-openapi.yml
- filename: wells-fargo-account-transactions-api-openapi.yml
  format: yaml
  label: Wells Fargo Account Transactions API
  slug: account-transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/openapi/wells-fargo-account-transactions-api-openapi.yml
- filename: wells-fargo-ach-payments-api-openapi.yml
  format: yaml
  label: Wells Fargo ACH Payments API
  slug: ach-payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/openapi/wells-fargo-ach-payments-api-openapi.yml
apis:
- description: The Wells Fargo Gateway API is a comprehensive open banking platform launched in 2016, offering a growing catalog of plug-and-play APIs, SDKs, and webhooks for commercial customers and partners. The p
  name: Wells Fargo Gateway API
  slug: gateway-api
- description: The Wells Fargo Account Transactions API enables treasury management customers to search and retrieve transaction data from the current day through 180 days prior. The API supports ACH, Wire, and RTP/
  name: Wells Fargo Account Transactions API
  slug: account-transactions-api
- description: The Wells Fargo ACH Payments API enables commercial banking customers to initiate ACH credit and debit transactions, including same-day ACH, for payroll, vendor payments, and collections. The API inte
  name: Wells Fargo ACH Payments API
  slug: ach-payments-api
capabilities:
- description: Unified treasury management capability combining the Wells Fargo Gateway API, Account Transactions API, and ACH Payments API. Enables commercial banking customers, treasury managers, and ERP systems t
  name: Wells Fargo Commercial Banking Treasury
  slug: commercial-banking-treasury
common:
- title: ''
  type: Website
  url: https://www.wellsfargo.com
- title: ''
  type: DeveloperPortal
  url: https://developer.wellsfargo.com
- title: ''
  type: Documentation
  url: https://developer.wellsfargo.com/documentation
- title: ''
  type: GitHubOrg
  url: https://github.com/wells-fargo
- title: ''
  type: JSONLDContext
  url: json-ld/wells-fargo-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/wells-fargo-vocabulary.yml
created: ''
description: Wells Fargo is a diversified, community-based financial services company providing banking, investment, mortgage, and consumer and commercial finance through thousands of stores and digital channels. Wells Fargo operates a comprehensive developer portal at developer.wellsfargo.com offering open banking APIs for payments, account data, and treasury management. The Gateway API platform handles over 1.5 billion API calls annually and supports commercial banking customers with ACH, wire, RTP, FedNow, and data reporting capabilities.
features: []
image: ''
integrations: []
jsonld:
- class_count: 6
  name: Wells Fargo Context
  property_count: 28
  slug: wells-fargo-context
layout: provider
modified: '2026-05-03'
name: wells-fargo
rules:
- name: wells-fargo API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 1
    info: 0
    warn: 7
  slug: wells-fargo-rules
skills: []
slug: wells-fargo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wells-fargo\nurl: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/apis.yml\nmodified: '2026-05-03'\ndescription: >-\n  Wells Fargo is a diversified, community-based financial services company\n  providing banking, investment, mortgage, and consumer and commercial finance\n  through thousands of stores and digital channels. Wells Fargo operates a\n  comprehensive developer portal at developer.wellsfargo.com offering open\n  banking APIs for payments, account data, and treasury management. The Gateway\n  API platform handles over 1.5 billion API calls annually and supports\n  commercial banking customers with ACH, wire, RTP, FedNow, and data reporting\n  capabilities.\ncommon:\n  - type: Website\n    url: https://www.wellsfargo.com\n  - type: DeveloperPortal\n    url: https://developer.wellsfargo.com\n  - type: Documentation\n    url: https://developer.wellsfargo.com/documentation\n  - type: GitHubOrg\n    url: https://github.com/wells-fargo\n\
  \  - type: JSONLDContext\n    url: json-ld/wells-fargo-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/wells-fargo-vocabulary.yml\napis:\n  - aid: wells-fargo:gateway-api\n    name: Wells Fargo Gateway API\n    tags:\n      - Banking\n      - Financial Services\n      - Open Banking\n      - Payments\n      - Treasury Management\n      - Commercial Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.wellsfargo.com\n    humanURL: https://developer.wellsfargo.com/\n    properties:\n      - url: https://developer.wellsfargo.com/apis\n        type: Documentation\n      - url: openapi/wells-fargo-gateway-api-openapi.yml\n        type: OpenAPI\n      - url: examples/wells-fargo-gateway-api-listAccounts-example.json\n        type: Example\n      - url: examples/wells-fargo-gateway-api-createPayment-example.json\n        type: Example\n      - url: rules/wells-fargo-rules.yml\n        type: SpectralRuleset\n      -\
  \ url: capabilities/shared/gateway-api.yaml\n        type: NaftikoCapability\n    description: >-\n      The Wells Fargo Gateway API is a comprehensive open banking platform\n      launched in 2016, offering a growing catalog of plug-and-play APIs, SDKs,\n      and webhooks for commercial customers and partners. The platform supports\n      payments, real-time account information, and financial data integration\n      across commercial banking, mortgage, credit card, and brokerage services.\n      Built on RESTful principles with OAuth 2.0 authentication, the Gateway\n      handles over 1.5 billion API calls annually.\n  - aid: wells-fargo:account-transactions-api\n    name: Wells Fargo Account Transactions API\n    tags:\n      - Banking\n      - Financial Services\n      - Account Management\n      - Transactions\n      - Treasury Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.wellsfargo.com\n    humanURL: https://developer.wellsfargo.com/documentation/api-references/account-transactions/v3/transaction-detail-api-ref-v3\n\
  \    properties:\n      - url: https://developer.wellsfargo.com/documentation/api-references/account-transactions/v3/transaction-detail-api-ref-v3\n        type: Documentation\n      - url: openapi/wells-fargo-account-transactions-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/wells-fargo-transaction-schema.json\n        type: JSONSchema\n      - url: json-structure/wells-fargo-transaction-structure.json\n        type: JSONStructure\n      - url: examples/wells-fargo-account-transactions-api-listAccountTransactions-example.json\n        type: Example\n      - url: rules/wells-fargo-rules.yml\n        type: SpectralRuleset\n      - url: capabilities/shared/account-transactions-api.yaml\n        type: NaftikoCapability\n    description: >-\n      The Wells Fargo Account Transactions API enables treasury management\n      customers to search and retrieve transaction data from the current day\n      through 180 days prior. The API supports ACH, Wire, and RTP/Instant\n   \
  \   Payment transactions with unique transaction IDs, intraday and previous\n      day reporting, and pagination for high-volume transaction retrieval.\n  - aid: wells-fargo:ach-payments-api\n    name: Wells Fargo ACH Payments API\n    tags:\n      - Banking\n      - Financial Services\n      - Payments\n      - ACH\n      - Treasury Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.wellsfargo.com\n    humanURL: https://developer.wellsfargo.com/documentation/api-references/ach-payments/v2/ach-payments-api-ref-v2\n    properties:\n      - url: https://developer.wellsfargo.com/documentation/api-references/ach-payments/v2/ach-payments-api-ref-v2\n        type: Documentation\n      - url: openapi/wells-fargo-ach-payments-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/wells-fargo-ach-payment-schema.json\n        type: JSONSchema\n      - url: json-structure/wells-fargo-ach-payment-structure.json\n  \
  \      type: JSONStructure\n      - url: examples/wells-fargo-ach-payments-api-initiateAchPayment-example.json\n        type: Example\n      - url: rules/wells-fargo-rules.yml\n        type: SpectralRuleset\n      - url: capabilities/shared/ach-payments-api.yaml\n        type: NaftikoCapability\n    description: >-\n      The Wells Fargo ACH Payments API enables commercial banking customers to\n      initiate ACH credit and debit transactions, including same-day ACH, for\n      payroll, vendor payments, and collections. The API integrates with Wells\n      Fargo's intelligent payment routing that automatically selects the\n      optimal rail including RTP, FedNow, and ACH for each transaction.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/apis.yml
use_cases: []
---
