---
api_count: 2
api_specs:
- filename: truelayer-payments-openapi.yml
  format: yaml
  label: TrueLayer Payments API
  slug: payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/openapi/truelayer-payments-openapi.yml
apis:
- description: The TrueLayer Payments API v3 enables creation and management of open banking payments, payouts, refunds, and variable recurring payment mandates. Supports closed-loop pay-ins, single external payment
  name: TrueLayer Payments API
  slug: payments-api
- description: The TrueLayer Data API provides access to bank account data including account information, balances, transactions, identity verification, and standing orders. Used for account verification, affordabil
  name: TrueLayer Data API
  slug: data-api
capabilities:
- description: 'Workflow capability for open banking payment operations via TrueLayer. Covers the full payment lifecycle: creating payments and mandates, handling payouts, processing refunds, and monitoring merchant '
  name: TrueLayer Open Banking Payments
  slug: open-banking-payments
common:
- title: ''
  type: Website
  url: https://truelayer.com/
- title: ''
  type: Documentation
  url: https://docs.truelayer.com/
- title: ''
  type: API Reference
  url: https://docs.truelayer.com/reference
- title: ''
  type: GitHub Organization
  url: https://github.com/TrueLayer
- title: ''
  type: Console
  url: https://console.truelayer.com/
- title: ''
  type: Sandbox
  url: https://console.truelayer-sandbox.com/
- title: ''
  type: SDKs
  url: https://docs.truelayer.com/docs/client-libraries
- title: ''
  type: Changelog
  url: https://docs.truelayer.com/changelog
- title: ''
  type: Blog
  url: https://truelayer.com/blog/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/truelayer/
- title: ''
  type: Twitter
  url: https://twitter.com/TrueLayer
created: '2026-03-27'
description: TrueLayer is Europe's leading open banking platform providing unified access to bank data, payments, payouts, refunds, and variable recurring payments across the UK and EU. TrueLayer connects to 69+ financial institutions and enables instant bank payments, data enrichment, and account verification through a single API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Truelayer Context
  property_count: 5
  slug: truelayer-context
layout: provider
modified: '2026-05-03'
name: TrueLayer
rules:
- name: TrueLayer API Rules
  rule_count: 11
  severity_counts:
    error: 6
    hint: 3
    info: 0
    warn: 2
  slug: truelayer-rules
skills: []
slug: truelayer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: truelayer\nname: TrueLayer\ndescription: >-\n  TrueLayer is Europe's leading open banking platform providing unified access\n  to bank data, payments, payouts, refunds, and variable recurring payments\n  across the UK and EU. TrueLayer connects to 69+ financial institutions and\n  enables instant bank payments, data enrichment, and account verification\n  through a single API.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data API\n  - Financial Services\n  - Open Banking\n  - Payments\n  - PSD2\n  - UK Banking\n  - VRP\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: truelayer:payments-api\n    name: TrueLayer Payments API\n    description: >-\n      The TrueLayer Payments API v3 enables creation and management of open\n      banking payments, payouts, refunds, and variable\
  \ recurring payment\n      mandates. Supports closed-loop pay-ins, single external payments, VRP\n      mandates, merchant account management, and full webhook event coverage\n      across UK and EU markets.\n    humanURL: https://docs.truelayer.com/docs/payments-api-basics\n    baseURL: https://api.truelayer.com\n    tags:\n      - Open Banking\n      - Payments\n      - Payouts\n      - Refunds\n      - VRP\n    properties:\n      - type: Documentation\n        url: https://docs.truelayer.com/docs/payments-api-basics\n      - type: Getting Started\n        url: https://docs.truelayer.com/docs/create-a-payment\n      - type: Webhooks\n        url: https://docs.truelayer.com/docs/payments-api-webhook-reference\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/openapi/truelayer-payments-openapi.yml\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/rules/truelayer-rules.yml\n\
  \      - type: NaftikoCapabilities\n        url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/capabilities/open-banking-payments.yaml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/json-schema/truelayer-payment-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/json-ld/truelayer-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/vocabulary/truelayer-vocabulary.yml\n  - aid: truelayer:data-api\n    name: TrueLayer Data API\n    description: >-\n      The TrueLayer Data API provides access to bank account data including\n      account information, balances, transactions, identity verification,\n      and standing orders. Used for account verification, affordability\n      assessments, and financial data enrichment.\n    humanURL: https://docs.truelayer.com/docs/data-api-basics\n\
  \    baseURL: https://api.truelayer.com\n    tags:\n      - Account Data\n      - Bank Data\n      - Data API\n      - Identity Verification\n      - Open Banking\n    properties:\n      - type: Documentation\n        url: https://docs.truelayer.com/docs/data-api-basics\n      - type: Reference\n        url: https://docs.truelayer.com/reference\ncommon:\n  - type: Website\n    url: https://truelayer.com/\n  - type: Documentation\n    url: https://docs.truelayer.com/\n  - type: API Reference\n    url: https://docs.truelayer.com/reference\n  - type: GitHub Organization\n    url: https://github.com/TrueLayer\n  - type: Console\n    url: https://console.truelayer.com/\n  - type: Sandbox\n    url: https://console.truelayer-sandbox.com/\n  - type: SDKs\n    url: https://docs.truelayer.com/docs/client-libraries\n  - type: Changelog\n    url: https://docs.truelayer.com/changelog\n  - type: Blog\n    url: https://truelayer.com/blog/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/truelayer/\n\
  \  - type: Twitter\n    url: https://twitter.com/TrueLayer\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/apis.yml
tags:
- Data API
- Financial Services
- Open Banking
- Payments
- PSD2
- UK Banking
- VRP
url: https://raw.githubusercontent.com/api-evangelist/truelayer/refs/heads/main/apis.yml
use_cases: []
---
