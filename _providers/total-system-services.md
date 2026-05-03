---
api_count: 3
api_specs:
- filename: tsys-payment-gateway-openapi.yml
  format: yaml
  label: TSYS Payment Gateway
  slug: tsys-payment-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/openapi/tsys-payment-gateway-openapi.yml
- filename: tsys-issuing-openapi.yml
  format: yaml
  label: TSYS Issuing Platform
  slug: tsys-issuing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/openapi/tsys-issuing-openapi.yml
apis:
- description: TSYS Payment Gateway API enables merchants to process credit, debit, and prepaid card transactions. Supports authorization, capture, void, and refund operations for card-present and card-not-present p
  name: TSYS Payment Gateway
  slug: tsys-payment-gateway
- description: TSYS Issuing Platform provides an API-driven payment stack for financial institutions and fintechs to issue debit and credit cards, manage cardholder accounts, set spending controls, and handle transa
  name: TSYS Issuing Platform
  slug: tsys-issuing
- description: TSYS Merchant Services API provides merchant boarding, account management, reporting, and settlement services for acquirers and payment facilitators integrating with the TSYS acquiring platform.
  name: TSYS Merchant Services
  slug: tsys-merchant
capabilities:
- description: Workflow capability for financial institutions and fintechs to manage card programs via the TSYS Issuing Platform. Covers cardholder onboarding, card issuance, spending controls, transaction monitorin
  name: TSYS Card Issuing
  slug: card-issuing
- description: Unified workflow capability for merchant payment processing combining the TSYS Payment Gateway for transaction authorization, capture, void, and refund operations. Designed for merchants, ISVs, and pa
  name: TSYS Payment Processing
  slug: payment-processing
common:
- title: ''
  type: Website
  url: https://www.tsys.com/
- title: ''
  type: Developer
  url: https://developers.tsys.com/
- title: ''
  type: Documentation
  url: https://docs.tsysmerchant.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tsys
- title: ''
  type: Rules
  url: rules/tsys-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/total-system-services-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: json-ld/total-system-services-context.jsonld
created: '2026-03-24'
description: Total System Services (TSYS) was a leading global payment solutions provider offering payment processing services to financial and nonfinancial institutions before merging with Global Payments in 2019. TSYS provides an end-to-end payment stack spanning payment gateway services for merchants, card issuing for banks and fintechs, merchant acquiring and boarding, virtual card programs, and comprehensive reporting. The TSYS developer portal provides APIs for transaction processing, cardholder management, merchant services, and commercial virtual solutions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 45
  name: Total System Services Context
  property_count: 0
  slug: total-system-services-context
layout: provider
modified: '2026-05-03'
name: Total System Services
rules:
- name: Total System Services API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: tsys-spectral-rules
skills: []
slug: total-system-services
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: total-system-services\nurl: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/apis.yml\napis:\n  - aid: total-system-services:tsys-payment-gateway\n    name: TSYS Payment Gateway\n    tags:\n      - Payments\n      - Payment Processing\n      - Credit Card\n      - Transactions\n      - POS\n    humanURL: https://developers.tsys.com/\n    properties:\n      - url: https://developers.tsys.com/\n        type: Documentation\n      - url: openapi/tsys-payment-gateway-openapi.yml\n        type: OpenAPI\n    description: >-\n      TSYS Payment Gateway API enables merchants to process credit, debit, and\n      prepaid card transactions. Supports authorization, capture, void, and\n      refund operations for card-present and card-not-present payment scenarios.\n  - aid: total-system-services:tsys-issuing\n    name: TSYS Issuing Platform\n    tags:\n      - Payments\n      - Card Issuing\n      - Account Management\n      - Digital Payments\n\
  \      - Fintech\n    humanURL: https://www.tsys.com/platform\n    properties:\n      - url: https://www.tsys.com/platform\n        type: Documentation\n      - url: openapi/tsys-issuing-openapi.yml\n        type: OpenAPI\n    description: >-\n      TSYS Issuing Platform provides an API-driven payment stack for financial\n      institutions and fintechs to issue debit and credit cards, manage cardholder\n      accounts, set spending controls, and handle transaction disputes.\n  - aid: total-system-services:tsys-merchant\n    name: TSYS Merchant Services\n    tags:\n      - Payments\n      - Merchant Management\n      - Acquiring\n      - Boarding\n      - Settlement\n    humanURL: https://docs.tsysmerchant.com/\n    properties:\n      - url: https://docs.tsysmerchant.com/\n        type: Documentation\n      - url: openapi/tsys-merchant-openapi.yml\n        type: OpenAPI\n    description: >-\n      TSYS Merchant Services API provides merchant boarding, account management,\n      reporting,\
  \ and settlement services for acquirers and payment facilitators\n      integrating with the TSYS acquiring platform.\ncommon:\n  - type: Website\n    url: https://www.tsys.com/\n  - type: Developer\n    url: https://developers.tsys.com/\n  - type: Documentation\n    url: https://docs.tsysmerchant.com/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/tsys\n  - type: Rules\n    url: rules/tsys-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/total-system-services-vocabulary.yml\n  - type: JSONLDContext\n    url: json-ld/total-system-services-context.jsonld\nname: Total System Services\ntags:\n  - Payments\n  - Payment Processing\n  - Card Issuing\n  - Merchant Services\n  - Fintech\n  - Financial Services\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Total System Services (TSYS) was a leading global payment\
  \ solutions provider\n  offering payment processing services to financial and nonfinancial institutions\n  before merging with Global Payments in 2019. TSYS provides an end-to-end payment\n  stack spanning payment gateway services for merchants, card issuing for banks and\n  fintechs, merchant acquiring and boarding, virtual card programs, and comprehensive\n  reporting. The TSYS developer portal provides APIs for transaction processing,\n  cardholder management, merchant services, and commercial virtual solutions.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/apis.yml
tags:
- Payments
- Payment Processing
- Card Issuing
- Merchant Services
- Fintech
- Financial Services
url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/apis.yml
use_cases: []
---
