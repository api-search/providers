---
api_count: 1
api_specs:
- filename: tropic-openapi.yml
  format: yaml
  label: Tropic API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/openapi/tropic-openapi.yml
apis:
- description: The Tropic public REST API enables organizations to connect Tropic with other software in their stack. It supports managing contracts, suppliers, procurement requests, webhook subscriptions, and users
  name: Tropic API
  slug: rest-api
capabilities:
- description: Workflow capability for managing the full procurement lifecycle in Tropic — from intake and request approval through contract execution and supplier management. Used by procurement teams, finance mana
  name: Tropic Procurement Management
  slug: procurement-management
common:
- title: ''
  type: Website
  url: https://www.tropicapp.io/
- title: ''
  type: Documentation
  url: https://help.tropicapp.io/hc/en-us
- title: ''
  type: Blog
  url: https://www.tropicapp.io/blog
- title: ''
  type: Login
  url: https://app.tropicapp.io/portal/login
- title: ''
  type: Pricing
  url: https://www.tropicapp.io/pricing
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tropicapp
- title: ''
  type: Twitter
  url: https://x.com/tropicapp
created: '2026-03-16'
description: Tropic is an intelligent procurement platform that combines AI-powered spend management, supplier management, and benchmark data to help organizations find and capture savings opportunities. Tropic's AI agents track renewals, spot shadow spend, flag compliance issues, and automate manual procurement tasks with SKU-level price benchmarks from thousands of actual deals.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Tropic Context
  property_count: 8
  slug: tropic-context
layout: provider
modified: '2026-05-03'
name: Tropic
rules:
- name: Tropic API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 2
    info: 0
    warn: 4
  slug: tropic-rules
skills: []
slug: tropic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tropic\nname: Tropic\ndescription: >-\n  Tropic is an intelligent procurement platform that combines AI-powered spend\n  management, supplier management, and benchmark data to help organizations\n  find and capture savings opportunities. Tropic's AI agents track renewals,\n  spot shadow spend, flag compliance issues, and automate manual procurement\n  tasks with SKU-level price benchmarks from thousands of actual deals.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Benchmarking\n  - Contract Management\n  - Cost Optimization\n  - Procurement\n  - Renewals\n  - SaaS Management\n  - SaaS Procurement\n  - Spend Management\n  - Supplier Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tropic:rest-api\n    name: Tropic API\n    description: >-\n      The Tropic public\
  \ REST API enables organizations to connect Tropic with\n      other software in their stack. It supports managing contracts, suppliers,\n      procurement requests, webhook subscriptions, and users programmatically.\n      Authentication uses API keys via Bearer tokens issued from the Tropic\n      settings panel.\n    humanURL: https://help.tropicapp.io/hc/en-us/sections/31190632406171-API-and-Webhooks\n    baseURL: https://api.tropicapp.io/v1\n    tags:\n      - Contract Management\n      - Integrations\n      - Procurement\n      - Spend Management\n      - Supplier Management\n      - Webhooks\n    properties:\n      - url: https://help.tropicapp.io/hc/en-us/sections/31190632406171-API-and-Webhooks\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/openapi/tropic-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/rules/tropic-rules.yml\n        type:\
  \ SpectralRules\n      - url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/capabilities/procurement-management.yaml\n        type: NaftikoCapabilities\n      - url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/json-schema/tropic-contract-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/json-schema/tropic-supplier-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/json-ld/tropic-context.jsonld\n        type: JSONLDContext\n      - url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/vocabulary/tropic-vocabulary.yml\n        type: Vocabulary\ncommon:\n  - type: Website\n    url: https://www.tropicapp.io/\n  - type: Documentation\n    url: https://help.tropicapp.io/hc/en-us\n  - type: Blog\n    url: https://www.tropicapp.io/blog\n  - type: Login\n    url: https://app.tropicapp.io/portal/login\n\
  \  - type: Integrations\n    url: https://www.tropicapp.io/solutions/integrations\n  - type: Pricing\n    url: https://www.tropicapp.io/pricing\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/tropicapp\n  - type: Twitter\n    url: https://x.com/tropicapp\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/apis.yml
tags:
- Benchmarking
- Contract Management
- Cost Optimization
- Procurement
- Renewals
- SaaS Management
- SaaS Procurement
- Spend Management
- Supplier Management
url: https://raw.githubusercontent.com/api-evangelist/tropic/refs/heads/main/apis.yml
use_cases: []
---
