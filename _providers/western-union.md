---
api_count: 2
api_specs:
- filename: western-union-mass-payments-openapi.yml
  format: yaml
  label: Western Union Mass Payments API
  slug: mass-payments
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/openapi/western-union-mass-payments-openapi.yml
apis:
- description: The Western Union Mass Payments API enables financial institutions and enterprise customers to send up to 10,000 international payments in a single batch across 130+ currencies. The API supports payme
  name: Western Union Mass Payments API
  slug: mass-payments
- description: Western Union's PSD2-compliant Open Banking API enables Payment Service Providers to access account information (AIS) and initiate payments (PIS) in compliance with European Payment Services Directive
  name: Western Union Open Banking API
  slug: open-banking
capabilities:
- description: Workflow capability for international money transfer and batch payment processing via Western Union's global payment network. Covers FX rate quoting, batch creation, payment submission, and status tra
  name: Western Union International Payments
  slug: international-payments
common:
- title: ''
  type: Website
  url: https://www.westernunion.com
- title: ''
  type: BusinessSolutions
  url: https://business.westernunion.com
- title: ''
  type: Portal
  url: https://developer.westernunion.com
- title: ''
  type: GettingStarted
  url: https://developer.westernunion.com/getting-started.html
- title: ''
  type: Contact
  url: https://corporate.westernunion.com/fi-partnerships/solutions/
- title: ''
  type: PrivacyPolicy
  url: https://www.westernunion.com/us/en/privacy-statement.html
- title: ''
  type: TermsOfService
  url: https://www.westernunion.com/us/en/digital-service-agreement.html
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/western-union
created: ''
description: The Western Union Company is a global leader in cross-border, cross-currency money movement, providing money transfer, money order, and other financial services to consumers and businesses worldwide. Western Union's Partnership APIs enable financial institutions, fintech companies, and enterprise customers to integrate WU's global payment network for money transfers, batch payments, FX quotes, and account management across 200+ countries and territories in 130+ currencies. Authentication uses mTLS with client certificates.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Western Union Context
  property_count: 29
  slug: western-union-context
layout: provider
modified: '2026-05-03'
name: western-union
rules:
- name: western-union API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 6
  slug: western-union-rules
skills: []
slug: western-union
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: western-union\nurl: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/apis.yml\nmodified: '2026-05-03'\ndescription: >-\n  The Western Union Company is a global leader in cross-border, cross-currency\n  money movement, providing money transfer, money order, and other financial\n  services to consumers and businesses worldwide. Western Union's Partnership\n  APIs enable financial institutions, fintech companies, and enterprise\n  customers to integrate WU's global payment network for money transfers,\n  batch payments, FX quotes, and account management across 200+ countries and\n  territories in 130+ currencies. Authentication uses mTLS with client\n  certificates.\napis:\n  - aid: western-union:mass-payments\n    name: Western Union Mass Payments API\n    description: >-\n      The Western Union Mass Payments API enables financial institutions and\n      enterprise customers to send up to 10,000 international payments in a\n      single batch\
  \ across 130+ currencies. The API supports payment lifecycle\n      management including creating batches, adding individual payments,\n      committing batches, and tracking payment status. Authentication is via\n      mTLS (mutual TLS) with client certificates.\n    humanURL: https://developer.westernunion.com/api-money-transfer.html\n    baseURL: https://api.westernunion.com\n    tags:\n      - Money Transfer\n      - Payments\n      - International\n      - Batch Payments\n      - Financial Services\n    properties:\n      - type: Documentation\n        url: https://developer.westernunion.com/api-money-transfer.html\n      - type: Portal\n        url: https://developer.westernunion.com/getting-started.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/openapi/western-union-mass-payments-openapi.yml\n      - type: GettingStarted\n        url: https://developer.westernunion.com/getting-started.html\n    contact:\n\
  \      - FN: Western Union Partnership Program\n        url: https://developer.westernunion.com/getting-started.html\n        email: wuconnect@westernunion.com\n\n  - aid: western-union:open-banking\n    name: Western Union Open Banking API\n    description: >-\n      Western Union's PSD2-compliant Open Banking API enables Payment Service\n      Providers to access account information (AIS) and initiate payments (PIS)\n      in compliance with European Payment Services Directive 2 (PSD2). The API\n      supports Strong Customer Authentication (SCA) and integrates with the\n      WU Business Solutions global payment network.\n    humanURL: https://wu-priora.saltedge.com/\n    baseURL: https://wu-priora.saltedge.com\n    tags:\n      - Open Banking\n      - PSD2\n      - Account Information\n      - Payment Initiation\n      - Financial Services\n    properties:\n      - type: Portal\n        url: https://wu-priora.saltedge.com/\n      - type: Documentation\n        url: https://wu-priora.saltedge.com/\n\
  \    contact:\n      - FN: Western Union Business Solutions\n\ncommon:\n  - type: Website\n    url: https://www.westernunion.com\n  - type: BusinessSolutions\n    url: https://business.westernunion.com\n  - type: Portal\n    url: https://developer.westernunion.com\n  - type: GettingStarted\n    url: https://developer.westernunion.com/getting-started.html\n  - type: Contact\n    url: https://corporate.westernunion.com/fi-partnerships/solutions/\n  - type: PrivacyPolicy\n    url: https://www.westernunion.com/us/en/privacy-statement.html\n  - type: TermsOfService\n    url: https://www.westernunion.com/us/en/digital-service-agreement.html\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/western-union\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/apis.yml
use_cases: []
---
