---
api_count: 7
api_specs:
- filename: scotiabank-tranxact-openapi.yml
  format: yaml
  label: Scotia TranXact APIs
  slug: scotia-tranxact
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/openapi/scotiabank-tranxact-openapi.yml
apis:
- description: Scotia TranXact APIs provide corporate and commercial customers with programmatic access to Scotiabank's payments and cash management services. APIs support wire payments (domestic and international),
  name: Scotia TranXact APIs
  slug: scotia-tranxact
- description: Enables businesses to initiate secure, one-time wire transfers between accounts in the same currency (CAD or USD), domestically within Canada and the U.S., or internationally. Uses the SWIFT GPI-enabl
  name: Wire Payments API
  slug: wire-payments
- description: Provides fast payment capabilities for business transactions via INTERAC e-Transfer for business. Customers can send up to $25,000 per transaction in real time.
  name: Real-time Payments API
  slug: real-time-payments
- description: Supports creation and submission of Electronic Funds Transfers (EFTs), including inquiring on payment and file status, deleting, updating, and recalling or reversing payments.
  name: EFT Payment API
  slug: eft-payments
- description: Provides the ability to retrieve account balance for the current day or any prior day along with enriched transaction data for the two years prior, and view a list of eligible deposit accounts.
  name: Account Balance and Transactions API
  slug: account-balance-transactions
- description: Assists clients in determining the validity of an account number's format and indicates the likelihood of account ownership match for Scotiabank accounts.
  name: Account Validation API
  slug: account-validation
- description: Provides the capability to inquire on the status of wire payments using unique reference numbers, offering real-time payment tracking powered by SWIFT GPI.
  name: Payment Track and Trace API
  slug: payment-track-trace
capabilities:
- description: Unified capability for banking and payments workflows using Scotiabank's Scotia TranXact APIs. Enables corporate treasury teams, ERP systems, and financial applications to initiate wire payments, send
  name: Scotiabank Banking and Payments
  slug: banking-payments
common: []
created: '2026-05-02'
description: Scotiabank is one of Canada's leading financial institutions and a major international bank. Through its Scotia TranXact developer portal, Scotiabank provides APIs for corporate and commercial customers to integrate banking capabilities into their treasury management, ERP, and CRM systems. APIs cover wire payments, real-time payments via INTERAC e-Transfer, EFT payments, account balance and transaction data, account validation, and payment track and trace.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Scotiabank Context
  property_count: 16
  slug: scotiabank-context
layout: provider
modified: '2026-05-02'
name: Scotiabank
rules:
- name: Scotiabank API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: scotiabank-rules
skills: []
slug: scotiabank
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scotiabank\nname: Scotiabank\ndescription: >-\n  Scotiabank is one of Canada's leading financial institutions and a major\n  international bank. Through its Scotia TranXact developer portal,\n  Scotiabank provides APIs for corporate and commercial customers to\n  integrate banking capabilities into their treasury management, ERP, and\n  CRM systems. APIs cover wire payments, real-time payments via INTERAC\n  e-Transfer, EFT payments, account balance and transaction data, account\n  validation, and payment track and trace.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Finance\n  - Payments\n  - Canada\n  - Open Banking\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: scotiabank:scotia-tranxact\n    name: Scotia TranXact\
  \ APIs\n    description: >-\n      Scotia TranXact APIs provide corporate and commercial customers with\n      programmatic access to Scotiabank's payments and cash management services.\n      APIs support wire payments (domestic and international), real-time\n      INTERAC e-Transfer payments, EFT payment management, account balance\n      and transaction retrieval, account validation, and payment status tracking.\n    humanURL: https://developer.scotiabank.com/en.html\n    tags:\n      - Banking\n      - Payments\n      - Wire Transfer\n      - EFT\n      - Account Management\n    properties:\n      - type: Documentation\n        url: https://developer.scotiabank.com/en.html\n      - type: DeveloperPortal\n        url: https://developer.scotiabank.com/en.html\n      - type: GettingStarted\n        url: https://developer.scotiabank.com/content/scotiabank/developer/api/en/getting-started.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/openapi/scotiabank-tranxact-openapi.yml\n\
  \      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/rules/scotiabank-rules.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/json-schema/scotiabank-transaction-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/json-ld/scotiabank-context.jsonld\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/json-structure/scotiabank-wire-payment-structure.json\n      - type: Example\n        url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/examples/scotiabank-initiate-wire-payment-example.json\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/vocabulary/scotiabank-vocabulary.yml\n      - type: NaftikoCapabilities\n       \
  \ url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/capabilities/banking-payments.yaml\n  - aid: scotiabank:wire-payments\n    name: Wire Payments API\n    description: >-\n      Enables businesses to initiate secure, one-time wire transfers between\n      accounts in the same currency (CAD or USD), domestically within Canada\n      and the U.S., or internationally. Uses the SWIFT GPI-enabled network\n      with Unique End-to-End Transaction Reference (UETR) for real-time tracking.\n    humanURL: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n    tags:\n      - Wire Transfer\n      - Payments\n      - SWIFT\n      - Banking\n    properties:\n      - type: Documentation\n        url: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n  - aid: scotiabank:real-time-payments\n    name: Real-time Payments API\n    description:\
  \ >-\n      Provides fast payment capabilities for business transactions via\n      INTERAC e-Transfer for business. Customers can send up to $25,000\n      per transaction in real time.\n    humanURL: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n    tags:\n      - Real-Time Payments\n      - INTERAC\n      - Payments\n      - Banking\n    properties:\n      - type: Documentation\n        url: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n  - aid: scotiabank:eft-payments\n    name: EFT Payment API\n    description: >-\n      Supports creation and submission of Electronic Funds Transfers (EFTs),\n      including inquiring on payment and file status, deleting, updating,\n      and recalling or reversing payments.\n    humanURL: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n\
  \    tags:\n      - EFT\n      - Payments\n      - Banking\n      - ACH\n    properties:\n      - type: Documentation\n        url: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n  - aid: scotiabank:account-balance-transactions\n    name: Account Balance and Transactions API\n    description: >-\n      Provides the ability to retrieve account balance for the current day\n      or any prior day along with enriched transaction data for the two years\n      prior, and view a list of eligible deposit accounts.\n    humanURL: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n    tags:\n      - Account Management\n      - Transactions\n      - Banking\n      - Balance\n    properties:\n      - type: Documentation\n        url: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n  - aid: scotiabank:account-validation\n\
  \    name: Account Validation API\n    description: >-\n      Assists clients in determining the validity of an account number's\n      format and indicates the likelihood of account ownership match for\n      Scotiabank accounts.\n    humanURL: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n    tags:\n      - Account Validation\n      - Banking\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n  - aid: scotiabank:payment-track-trace\n    name: Payment Track and Trace API\n    description: >-\n      Provides the capability to inquire on the status of wire payments\n      using unique reference numbers, offering real-time payment tracking\n      powered by SWIFT GPI.\n    humanURL: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\n\
  \    tags:\n      - Payment Tracking\n      - Wire Transfer\n      - Banking\n      - SWIFT\n    properties:\n      - type: Documentation\n        url: https://developer.scotiabank.com/content/scotiabank/developer/api/en/products/Payments-and-Cash-Management-APIs.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/apis.yml
tags:
- Banking
- Finance
- Payments
- Canada
- Open Banking
url: https://raw.githubusercontent.com/api-evangelist/scotiabank/refs/heads/main/apis.yml
use_cases: []
---
