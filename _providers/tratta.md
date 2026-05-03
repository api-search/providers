---
api_count: 1
api_specs:
- filename: tratta-openapi.yml
  format: yaml
  label: Tratta API
  slug: tratta
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/openapi/tratta-openapi.yml
apis:
- description: REST API for Tratta's debt collection and payment platform. Enables programmatic management of debt accounts, payment plans, transactions, charges, customers, and webhooks for collections workflows.
  name: Tratta API
  slug: tratta
capabilities:
- description: 'Workflow capability for debt collection and payment recovery operations. Enables collections teams and system integrators to manage the full debt collection lifecycle: importing debt accounts, creatin'
  name: Tratta Debt Collection Workflow
  slug: debt-collection-workflow
common:
- title: ''
  type: Website
  url: https://www.tratta.io/
- title: ''
  type: Documentation
  url: https://docs.tratta.io/
- title: ''
  type: Sign Up
  url: https://www.tratta.io/
created: '2025-02-24'
description: Tratta is a debt collection and payment experience platform that provides REST APIs and webhooks for integrating payment plans, billing, customer session management, and collections workflows into existing tech stacks. The platform supports OAuth 2.0 / bearer token authentication and offers sandbox and production environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Tratta Context
  property_count: 0
  slug: tratta-context
layout: provider
modified: '2026-05-03'
name: Tratta
rules:
- name: Tratta API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 8
  slug: tratta-rules
skills: []
slug: tratta
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tratta\nname: Tratta\ndescription: >-\n  Tratta is a debt collection and payment experience platform that provides\n  REST APIs and webhooks for integrating payment plans, billing, customer\n  session management, and collections workflows into existing tech stacks.\n  The platform supports OAuth 2.0 / bearer token authentication and offers\n  sandbox and production environments.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Billing\n  - Collections\n  - Payments\n  - Debt Collection\n  - Fintech\ncreated: '2025-02-24'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tratta:tratta\n    name: Tratta API\n    description: >-\n      REST API for Tratta's debt collection and payment platform. Enables\n      programmatic management of debt accounts, payment plans,\
  \ transactions,\n      charges, customers, and webhooks for collections workflows.\n    humanURL: https://docs.tratta.io/\n    baseURL: https://api.tratta.io\n    tags:\n      - Billing\n      - Collections\n      - Payments\n      - Debt Collection\n      - Fintech\n    properties:\n      - type: Documentation\n        url: https://docs.tratta.io/api.html\n      - type: OpenAPI\n        url: openapi/tratta-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tratta-payment-plan-schema.json\n      - type: JSONSchema\n        url: json-schema/tratta-debt-account-schema.json\n      - type: JSONStructure\n        url: json-structure/tratta-payment-plan-structure.json\n      - type: JSONLD\n        url: json-ld/tratta-context.jsonld\n      - type: SpectralRules\n        url: rules/tratta-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/debt-collection-workflow.yaml\n      - type: Vocabulary\n        url: vocabulary/tratta-vocabulary.yml\n    x-resources:\n\
  \      - Customers\n      - Debt Accounts\n      - Payment Plans\n      - Payment Methods\n      - Charges\n      - Transactions\n      - Webhooks\n      - Customer Sessions\n      - Bulk Operations\n      - Tickets\n    x-authentication:\n      type: Bearer Token\n      description: Bearer token in Authorization header; OAuth 2.0 / API Key security\n    x-rate-limits:\n      default: 300 requests per minute\n    x-integrations:\n      - StratusPay\n      - Cogent\n      - Artiva\n      - Snowflake\ncommon:\n  - type: Website\n    url: https://www.tratta.io/\n  - type: Documentation\n    url: https://docs.tratta.io/\n  - type: Sign Up\n    url: https://www.tratta.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/apis.yml
tags:
- Billing
- Collections
- Payments
- Debt Collection
- Fintech
url: https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/apis.yml
use_cases: []
---
