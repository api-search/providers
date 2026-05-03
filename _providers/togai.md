---
api_count: 1
api_specs:
- filename: togai-openapi.yml
  format: yaml
  label: Togai API
  slug: togai-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/openapi/togai-openapi.yml
apis:
- description: The Togai API provides full programmatic access to the Togai usage-based billing platform. Resources include customers, accounts, event schemas, usage meters, price plans, pricing rules, invoices, cre
  name: Togai API
  slug: togai-api
capabilities:
- description: 'Unified capability for managing the full usage-based billing lifecycle with Togai. Covers customer onboarding, account management, usage event ingestion, price plan configuration, invoice generation, '
  name: Togai Usage-Based Billing
  slug: usage-based-billing
common:
- title: ''
  type: Website
  url: https://www.togai.com/
- title: ''
  type: Developer Portal
  url: https://docs.togai.com/
- title: ''
  type: Documentation
  url: https://docs.togai.com/docs
- title: ''
  type: API Reference
  url: https://docs.togai.com/api-reference/getting-started
- title: ''
  type: Sign Up
  url: https://app.togai.com/auth/signup
- title: ''
  type: Pricing
  url: https://www.togai.com/pricing/
- title: ''
  type: Blog
  url: https://www.togai.com/blog/
- title: ''
  type: Changelog
  url: https://docs.togai.com/changelog/change-log
- title: ''
  type: GitHub Organization
  url: https://github.com/TogaiHQ
- title: ''
  type: Sandbox
  url: https://sandbox-api.togai.com/
- title: ''
  type: Postman Collection
  url: https://docs.togai.com/api-reference/getting-started
created: '2025-02-10'
description: Togai is a metering and billing platform for software and SaaS products, purpose-built for consumption-based and usage-based pricing models. The Togai API provides programmatic access to customers, accounts, event ingestion, usage meters, price plans, invoices, credits, entitlements, and financial reporting. Supports real-time billing orchestration across cloud infrastructure, generative AI services, and SaaS applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Togai Context
  property_count: 6
  slug: togai-context
layout: provider
modified: '2026-05-03'
name: Togai
rules:
- name: Togai API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: togai-rules
skills: []
slug: togai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: togai\nname: Togai\ndescription: >-\n  Togai is a metering and billing platform for software and SaaS products, purpose-built\n  for consumption-based and usage-based pricing models. The Togai API provides programmatic\n  access to customers, accounts, event ingestion, usage meters, price plans, invoices,\n  credits, entitlements, and financial reporting. Supports real-time billing orchestration\n  across cloud infrastructure, generative AI services, and SaaS applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Billing\n  - Metering\n  - Usage-Based Pricing\n  - Revenue Management\n  - SaaS\n  - Fintech\ncreated: '2025-02-10'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: togai:togai-api\n    name: Togai API\n    description: >-\n      The Togai API\
  \ provides full programmatic access to the Togai usage-based\n      billing platform. Resources include customers, accounts, event schemas, usage\n      meters, price plans, pricing rules, invoices, credits, entitlements, wallet,\n      licenses, and reports. Supports both production and sandbox environments.\n    humanURL: https://docs.togai.com/api-reference/getting-started\n    baseURL: https://api.togai.com\n    tags:\n      - Billing\n      - Metering\n      - Usage-Based Pricing\n      - Revenue Management\n      - Customers\n      - Invoices\n    properties:\n      - type: Documentation\n        url: https://docs.togai.com/api-reference/getting-started\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/openapi/togai-openapi.yml\n      - type: Getting Started\n        url: https://docs.togai.com/docs/introduction\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/json-schema/togai-customer-schema.json\n\
  \      - type: NaftikoCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/capabilities/usage-based-billing.yaml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/rules/togai-rules.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/vocabulary/togai-vocabulary.yml\nfeatures:\n  - Usage-based metering and rating\n  - Price plan creation and management\n  - Customer and account lifecycle management\n  - Invoice generation and management\n  - Credits and wallet management\n  - Entitlements and feature gating\n  - Metrics and financial reporting\n  - Webhook notifications\n  - Price experimentation\n  - Sandbox environment\nuseCases:\n  - Cloud infrastructure metering\n  - Generative AI usage billing\n  - SaaS consumption pricing\n  - API monetization\n  - Enterprise billing automation\n\
  solutions:\n  - Revenue operations\n  - Developer platform monetization\n  - Usage-based pricing transformation\nintegrations:\n  - Stripe\n  - Salesforce\n  - QuickBooks\n  - NetSuite\n  - HubSpot\n  - Chargebee\n  - Zuora\ncommon:\n  - type: Website\n    url: https://www.togai.com/\n  - type: Developer Portal\n    url: https://docs.togai.com/\n  - type: Documentation\n    url: https://docs.togai.com/docs\n  - type: API Reference\n    url: https://docs.togai.com/api-reference/getting-started\n  - type: Sign Up\n    url: https://app.togai.com/auth/signup\n  - type: Pricing\n    url: https://www.togai.com/pricing/\n  - type: Blog\n    url: https://www.togai.com/blog/\n  - type: Changelog\n    url: https://docs.togai.com/changelog/change-log\n  - type: GitHub Organization\n    url: https://github.com/TogaiHQ\n  - type: Sandbox\n    url: https://sandbox-api.togai.com/\n  - type: Postman Collection\n    url: https://docs.togai.com/api-reference/getting-started\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/apis.yml
tags:
- Billing
- Metering
- Usage-Based Pricing
- Revenue Management
- SaaS
- Fintech
url: https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/apis.yml
use_cases: []
---
