---
api_count: 6
api_specs:
- filename: stigg-openapi.yml
  format: yaml
  label: Stigg GraphQL API
  slug: stigg-graphql
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/openapi/stigg-openapi.yml
apis:
- description: The Stigg GraphQL API provides full access to customer provisioning, subscription management, entitlement checking, usage reporting, and pricing plan management. Authentication uses the X-API-KEY head
  name: Stigg GraphQL API
  slug: stigg-graphql
- description: The Stigg REST API (Beta) provides language-agnostic HTTP access to customer management, subscription operations, entitlement checks, and usage reporting. Supports TypeScript, Python, Go, Ruby, C#, an
  name: Stigg REST API
  slug: stigg-rest
- description: Official Node.js / TypeScript SDK for integrating Stigg entitlements, feature flags, and usage-based billing into backend services.
  name: Stigg Node.js SDK
  slug: stigg-node-sdk
- description: Official Python SDK for integrating Stigg entitlements and usage-based billing into Python backend services.
  name: Stigg Python SDK
  slug: stigg-python-sdk
- description: Official Go SDK for integrating Stigg entitlements and usage-based billing into Go backend services.
  name: Stigg Go SDK
  slug: stigg-go-sdk
- description: Official React frontend SDK for rendering pricing tables, entitlement gates, and usage meters in React applications.
  name: Stigg React SDK
  slug: stigg-react-sdk
capabilities:
- description: Unified pricing, subscription, and entitlement management workflow for SaaS products. Enables engineering teams to provision customers, manage subscription lifecycles, enforce feature access gates, an
  name: Stigg Pricing and Entitlements
  slug: pricing-and-entitlements
common:
- title: ''
  type: Website
  url: https://www.stigg.io/
- title: ''
  type: Documentation
  url: https://docs.stigg.io/
- title: ''
  type: Getting Started
  url: https://docs.stigg.io/getting-started
- title: ''
  type: GitHub Organization
  url: https://github.com/stiggio
- title: ''
  type: Sign Up
  url: https://app.stigg.io/
created: '2026-03-27'
description: Stigg is a pricing and packaging platform providing feature management, entitlements, and usage-based billing for SaaS and API products. It enables engineering teams to integrate once and allows product managers to iterate on pricing without additional engineering effort. Stigg provides advanced metering, entitlement checks, and subscription management via GraphQL and REST APIs with SDKs in multiple languages.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Stigg Context
  property_count: 0
  slug: stigg-context
layout: provider
modified: '2026-05-02'
name: Stigg
rules:
- name: Stigg API Rules
  rule_count: 7
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 2
  slug: stigg-rules
skills: []
slug: stigg
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stigg\nname: Stigg\ndescription: >-\n  Stigg is a pricing and packaging platform providing feature management,\n  entitlements, and usage-based billing for SaaS and API products. It enables\n  engineering teams to integrate once and allows product managers to iterate\n  on pricing without additional engineering effort. Stigg provides advanced\n  metering, entitlement checks, and subscription management via GraphQL and\n  REST APIs with SDKs in multiple languages.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - FinOps\n  - Pricing\n  - Billing\n  - Entitlements\n  - Usage-Based Billing\n  - SaaS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: stigg:stigg-graphql\n    name: Stigg GraphQL API\n    description: >-\n      The Stigg GraphQL API provides full access to customer provisioning,\n\
  \      subscription management, entitlement checking, usage reporting, and\n      pricing plan management. Authentication uses the X-API-KEY header with\n      a Full access key from the Stigg dashboard.\n    humanURL: https://docs.stigg.io/api-and-sdks/integration/backend/graphql\n    tags:\n      - GraphQL\n      - Entitlements\n      - Subscriptions\n      - Billing\n    properties:\n      - type: Documentation\n        url: https://docs.stigg.io/api-and-sdks/integration/backend/graphql\n      - type: GraphQL\n        url: https://api.stigg.io/graphql\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/openapi/stigg-openapi.yml\n  - aid: stigg:stigg-rest\n    name: Stigg REST API\n    description: >-\n      The Stigg REST API (Beta) provides language-agnostic HTTP access to\n      customer management, subscription operations, entitlement checks, and\n      usage reporting. Supports TypeScript, Python, Go, Ruby, C#,\
  \ and Java SDKs.\n    humanURL: https://docs.stigg.io/api-and-sdks/integration/overview\n    tags:\n      - REST\n      - Entitlements\n      - Subscriptions\n      - Billing\n    properties:\n      - type: Documentation\n        url: https://docs.stigg.io/api-and-sdks/integration/overview\n  - aid: stigg:stigg-node-sdk\n    name: Stigg Node.js SDK\n    description: >-\n      Official Node.js / TypeScript SDK for integrating Stigg entitlements,\n      feature flags, and usage-based billing into backend services.\n    humanURL: https://docs.stigg.io/api-and-sdks/integration/backend/nodejs\n    tags:\n      - Node.js\n      - TypeScript\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.stigg.io/api-and-sdks/integration/backend/nodejs\n  - aid: stigg:stigg-python-sdk\n    name: Stigg Python SDK\n    description: >-\n      Official Python SDK for integrating Stigg entitlements and usage-based\n      billing into Python backend services.\n    humanURL: https://docs.stigg.io/api-and-sdks/integration/backend/python\n\
  \    tags:\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.stigg.io/api-and-sdks/integration/backend/python\n  - aid: stigg:stigg-go-sdk\n    name: Stigg Go SDK\n    description: >-\n      Official Go SDK for integrating Stigg entitlements and usage-based\n      billing into Go backend services.\n    humanURL: https://docs.stigg.io/api-and-sdks/integration/backend/go\n    tags:\n      - Go\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.stigg.io/api-and-sdks/integration/backend/go\n  - aid: stigg:stigg-react-sdk\n    name: Stigg React SDK\n    description: >-\n      Official React frontend SDK for rendering pricing tables, entitlement\n      gates, and usage meters in React applications.\n    humanURL: https://docs.stigg.io/api-and-sdks/integration/frontend/react\n    tags:\n      - React\n      - Frontend\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.stigg.io/api-and-sdks/integration/frontend/react\n\
  common:\n  - type: Website\n    url: https://www.stigg.io/\n  - type: Documentation\n    url: https://docs.stigg.io/\n  - type: Getting Started\n    url: https://docs.stigg.io/getting-started\n  - type: GitHub Organization\n    url: https://github.com/stiggio\n  - type: Sign Up\n    url: https://app.stigg.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/apis.yml
tags:
- FinOps
- Pricing
- Billing
- Entitlements
- Usage-Based Billing
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/apis.yml
use_cases: []
---
