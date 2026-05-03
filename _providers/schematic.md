---
api_count: 1
api_specs:
- filename: schematic-openapi.yml
  format: yaml
  label: Schematic API
  slug: schematic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/openapi/schematic-openapi.yml
apis:
- description: The Schematic REST API enables programmatic management of features, flags, plans, companies, users, entitlements, billing credits, and webhooks. Authentication uses API keys sent in the X-Schematic-Ap
  name: Schematic API
  slug: schematic-api
capabilities:
- description: 'Unified capability for managing customer companies, users, event tracking, and billing integrations in Schematic. Enables SaaS teams to sync customers from CRM and billing systems, track usage events '
  name: Schematic Customer Management
  slug: customer-management
- description: Unified capability for managing product features, feature flags, and entitlements in Schematic. Enables product and engineering teams to define features, create flags with rule-based evaluation, assig
  name: Schematic Feature Management
  slug: feature-management
common:
- title: ''
  type: Website
  url: https://schematichq.com/
- title: ''
  type: Documentation
  url: https://docs.schematichq.com/
- title: ''
  type: API Reference
  url: https://docs.schematichq.com/api-reference
- title: ''
  type: Blog
  url: https://schematichq.com/blog
- title: ''
  type: GitHub Organization
  url: https://github.com/SchematicHQ
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/schematichq
- title: ''
  type: Pricing
  url: https://schematichq.com/pricing
- title: ''
  type: Changelog
  url: https://schematichq.com/changelog
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/vocabulary/schematic-vocabulary.yml
- title: ''
  type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/examples/schematic-check-flag-example.json
created: '2026-03-27'
description: Schematic is a feature and entitlement management platform for SaaS companies, providing pricing, packaging, and metering capabilities. It enables engineering and product teams to manage feature flags, define subscription plans, track feature usage, and control customer entitlements without code changes. Schematic raised $6.5M in April 2026 and launched an official Stripe App for entitlement management as a first-class billing primitive. Customers include Plotly, Automox, Florence, Blackcloak, Sema4.ai, and Pagos.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 29
  name: Schematic Context
  property_count: 4
  slug: schematic-context
layout: provider
modified: '2026-05-02'
name: Schematic
rules:
- name: Schematic API Rules
  rule_count: 11
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 8
  slug: schematic-rules
skills: []
slug: schematic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: schematic\nname: Schematic\ndescription: >-\n  Schematic is a feature and entitlement management platform for SaaS companies,\n  providing pricing, packaging, and metering capabilities. It enables engineering\n  and product teams to manage feature flags, define subscription plans, track\n  feature usage, and control customer entitlements without code changes. Schematic\n  raised $6.5M in April 2026 and launched an official Stripe App for entitlement\n  management as a first-class billing primitive. Customers include Plotly, Automox,\n  Florence, Blackcloak, Sema4.ai, and Pagos.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Billing\n  - Entitlements\n  - Feature Flags\n  - Feature Management\n  - FinOps\n  - Metering\n  - Pricing\n  - SaaS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: schematic:schematic-api\n    name: Schematic API\n    description: >-\n      The Schematic REST API enables programmatic management of features, flags,\n      plans, companies, users, entitlements, billing credits, and webhooks.\n      Authentication uses API keys sent in the X-Schematic-Api-Key header.\n      Supports production, staging, and development environments with\n      environment-scoped API keys (sch_prod, sch_stag, sch_dev prefixes).\n    humanURL: https://schematichq.com/\n    tags:\n      - Billing\n      - Entitlements\n      - Feature Flags\n      - Feature Management\n      - Metering\n      - Plans\n      - SaaS\n    properties:\n      - type: Documentation\n        url: https://docs.schematichq.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/openapi/schematic-openapi.yml\n      - type: API Reference\n        url: https://docs.schematichq.com/api-reference\n      - type:\
  \ Authentication\n        url: https://docs.schematichq.com/api-reference/authentication.mdx\n      - type: Getting Started\n        url: https://docs.schematichq.com/\n      - type: GitHub Repository\n        url: https://github.com/SchematicHQ\n      - type: SDK Python\n        url: https://github.com/SchematicHQ/schematic-python\n      - type: SDK Node\n        url: https://github.com/SchematicHQ/schematic-node\n      - type: SDK Go\n        url: https://github.com/SchematicHQ/schematic-go\n      - type: SDK Ruby\n        url: https://github.com/SchematicHQ/schematic-ruby\n      - type: SDK Java\n        url: https://github.com/SchematicHQ/schematic-java\n      - type: SDK PHP\n        url: https://github.com/SchematicHQ/schematic-php\n      - type: SDK C#\n        url: https://github.com/SchematicHQ/schematic-csharp\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/rules/schematic-rules.yml\n      - type:\
  \ NaftikoCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/capabilities/feature-management.yaml\n      - type: NaftikoCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/capabilities/customer-management.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/json-schema/schematic-company-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/json-schema/schematic-feature-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/json-schema/schematic-plan-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/json-structure/schematic-api-structure.json\n\
  \      - type: JSONLd\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/json-ld/schematic-context.jsonld\ncommon:\n  - type: Website\n    url: https://schematichq.com/\n  - type: Documentation\n    url: https://docs.schematichq.com/\n  - type: API Reference\n    url: https://docs.schematichq.com/api-reference\n  - type: Blog\n    url: https://schematichq.com/blog\n  - type: GitHub Organization\n    url: https://github.com/SchematicHQ\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/schematichq\n  - type: Pricing\n    url: https://schematichq.com/pricing\n  - type: Changelog\n    url: https://schematichq.com/changelog\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/vocabulary/schematic-vocabulary.yml\n  - type: Examples\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/examples/schematic-check-flag-example.json\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/apis.yml
tags:
- Billing
- Entitlements
- Feature Flags
- Feature Management
- FinOps
- Metering
- Pricing
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/schematic/refs/heads/main/apis.yml
use_cases: []
---
