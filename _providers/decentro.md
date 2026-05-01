---
api_count: 4
api_specs:
- filename: decentro-kyc-api-openapi.yml
  format: yaml
  label: Decentro KYC & Onboarding API
  slug: kyc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-kyc-api-openapi.yml
- filename: decentro-payments-api-openapi.yml
  format: yaml
  label: Decentro Payments API
  slug: payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-payments-api-openapi.yml
- filename: decentro-virtual-accounts-api-openapi.yml
  format: yaml
  label: Decentro Virtual Accounts API
  slug: virtual-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-virtual-accounts-api-openapi.yml
- filename: decentro-ledger-api-openapi.yml
  format: yaml
  label: Decentro Ledger API
  slug: ledger-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/openapi/decentro-ledger-api-openapi.yml
apis:
- description: Identity verification, customer onboarding, DigiLocker integration, Aadhaar OTP, document classification, and face match.
  name: Decentro KYC & Onboarding API
  slug: kyc-api
- description: Collections, payouts, ENACH mandates, UPI Autopay, settlements, and refunds for the Indian banking system.
  name: Decentro Payments API
  slug: payments-api
- description: Create and manage virtual bank accounts, balances, statements, and remitter whitelisting for collections and reconciliation.
  name: Decentro Virtual Accounts API
  slug: virtual-accounts-api
- description: Double-entry accounting primitives for journals, ledger accounts, and transactions tied to Decentro virtual accounts and external counterparties.
  name: Decentro Ledger API
  slug: ledger-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://decentro.tech/
- title: ''
  type: Portal
  url: https://docs.decentro.tech/
- title: ''
  type: Reference
  url: https://docs.decentro.tech/reference
- title: ''
  type: Blog
  url: https://decentro.tech/blog/
- title: ''
  type: Pricing
  url: https://decentro.tech/pricing/
- title: ''
  type: JSON-LD
  url: json-ld/decentro-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/decentro-vocabulary.yml
created: '2025-02-24'
description: 'Decentro is a banking-as-a-service platform that provides businesses with seamless integration to Indian banking infrastructure - including payments (UPI, IMPS, NEFT, RTGS), virtual accounts, KYC, ledger primitives, and credit-bureau data. Decentro publishes a developer portal and Postman collection covering six API categories: KYC & Onboarding, Bytes (alternate data), Scanner (forensics), Payments, Virtual Accounts, and Ledger.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Decentro Context
  property_count: 8
  slug: decentro-context
layout: provider
modified: '2026-04-28'
name: Decentro
rules:
- name: Decentro API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: decentro-payments-api-rules
skills: []
slug: decentro
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: decentro\nname: Decentro\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/apis.yml\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Banking-as-a-Service\n  - FinTech\n  - India\n  - KYC\n  - Ledger\n  - Payments\n  - UPI\n  - Virtual Accounts\ncreated: '2025-02-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\ndescription: >-\n  Decentro is a banking-as-a-service platform that provides businesses\n  with seamless integration to Indian banking infrastructure - including\n  payments (UPI, IMPS, NEFT, RTGS), virtual accounts, KYC, ledger\n  primitives, and credit-bureau data. Decentro publishes a developer\n  portal and Postman collection covering six API categories: KYC &\n  Onboarding, Bytes (alternate data), Scanner (forensics), Payments,\n  Virtual Accounts, and Ledger.\napis:\n  - aid: decentro:kyc-api\n\
  \    name: Decentro KYC & Onboarding API\n    description: >-\n      Identity verification, customer onboarding, DigiLocker integration,\n      Aadhaar OTP, document classification, and face match.\n    humanURL: https://docs.decentro.tech/\n    baseURL: https://in.decentro.tech\n    tags:\n      - Aadhaar\n      - DigiLocker\n      - Forensics\n      - KYC\n      - Onboarding\n    properties:\n      - type: Documentation\n        url: https://docs.decentro.tech/\n      - type: OpenAPI\n        url: openapi/decentro-kyc-api-openapi.yml\n  - aid: decentro:payments-api\n    name: Decentro Payments API\n    description: >-\n      Collections, payouts, ENACH mandates, UPI Autopay, settlements,\n      and refunds for the Indian banking system.\n    humanURL: https://docs.decentro.tech/\n    baseURL: https://in.decentro.tech\n    tags:\n      - Collections\n      - Mandates\n      - Payouts\n      - Settlements\n      - UPI\n    properties:\n      - type: Documentation\n        url: https://docs.decentro.tech/\n\
  \      - type: OpenAPI\n        url: openapi/decentro-payments-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/decentro-payout.json\n      - type: Rules\n        url: rules/decentro-payments-api-rules.yml\n      - type: Capabilities\n        url: capabilities/decentro-payments-api-capabilities.yml\n  - aid: decentro:virtual-accounts-api\n    name: Decentro Virtual Accounts API\n    description: >-\n      Create and manage virtual bank accounts, balances, statements,\n      and remitter whitelisting for collections and reconciliation.\n    humanURL: https://docs.decentro.tech/\n    baseURL: https://in.decentro.tech\n    tags:\n      - Banking\n      - Reconciliation\n      - Virtual Accounts\n    properties:\n      - type: Documentation\n        url: https://docs.decentro.tech/\n      - type: OpenAPI\n        url: openapi/decentro-virtual-accounts-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/decentro-virtual-account.json\n  - aid: decentro:ledger-api\n\
  \    name: Decentro Ledger API\n    description: >-\n      Double-entry accounting primitives for journals, ledger\n      accounts, and transactions tied to Decentro virtual accounts\n      and external counterparties.\n    humanURL: https://docs.decentro.tech/\n    baseURL: https://in.decentro.tech\n    tags:\n      - Accounts\n      - Accounting\n      - Ledger\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://docs.decentro.tech/\n      - type: OpenAPI\n        url: openapi/decentro-ledger-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://decentro.tech/\n  - type: Portal\n    url: https://docs.decentro.tech/\n  - type: Reference\n    url: https://docs.decentro.tech/reference\n  - type: Blog\n    url: https://decentro.tech/blog/\n  - type: Pricing\n    url: https://decentro.tech/pricing/\n  - type: JSON-LD\n    url: json-ld/decentro-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/decentro-vocabulary.yml\nmaintainers:\n  - FN:\
  \ Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/apis.yml
tags:
- Banking
- Banking-as-a-Service
- FinTech
- India
- KYC
- Ledger
- Payments
- UPI
- Virtual Accounts
url: https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/apis.yml
use_cases: []
---
