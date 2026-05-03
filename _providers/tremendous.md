---
api_count: 1
api_specs:
- filename: tremendous-api-openapi.yml
  format: yaml
  label: Tremendous API
  slug: tremendous
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tremendous/refs/heads/main/openapi/tremendous-api-openapi.yml
apis:
- description: The Tremendous REST API enables businesses to programmatically send rewards, incentives, and payouts worldwide. The API covers orders, rewards, products, campaigns, funding sources, organizations, mem
  name: Tremendous API
  slug: tremendous
capabilities:
- description: 'Unified capability for sending and managing rewards, incentives, and payouts worldwide using the Tremendous platform. Enables businesses to send gift cards, prepaid cards, PayPal, bank transfers, and '
  name: Tremendous Rewards and Payouts
  slug: rewards-and-payouts
common:
- title: ''
  type: Website
  url: https://www.tremendous.com/
- title: ''
  type: Documentation
  url: https://developers.tremendous.com/
- title: ''
  type: Sign Up
  url: https://app.tremendous.com/auth/sign_up
- title: ''
  type: Sandbox
  url: https://testflight.tremendous.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/tremendous-rewards
- title: ''
  type: SDK
  url: https://github.com/tremendous-rewards/tremendous-node
- title: ''
  type: Changelog
  url: https://developers.tremendous.com/changelog
- title: ''
  type: JSONSchema
  url: json-schema/tremendous-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tremendous-product-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/tremendous-order-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/tremendous-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/tremendous-spectral-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/rewards-and-payouts.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tremendous-vocabulary.yml
created: '2025-02-08'
description: Tremendous allows businesses to send rewards, incentives, and payouts worldwide using their simple API and dashboard. Access 2000+ payout methods including US and global bank transfers, Amazon.com gift cards, Visa and Mastercard prepaid cards, PayPal, Venmo, and charity donations. Supports multi-product rewards (recipient choice) and single-product rewards.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Tremendous Context
  property_count: 16
  slug: tremendous-context
layout: provider
modified: '2026-05-03'
name: Tremendous
rules:
- name: Tremendous API Rules
  rule_count: 12
  severity_counts:
    error: 2
    hint: 0
    info: 4
    warn: 6
  slug: tremendous-spectral-rules
skills: []
slug: tremendous
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tremendous\nname: Tremendous\ndescription: >-\n  Tremendous allows businesses to send rewards, incentives, and payouts\n  worldwide using their simple API and dashboard. Access 2000+ payout methods\n  including US and global bank transfers, Amazon.com gift cards, Visa and\n  Mastercard prepaid cards, PayPal, Venmo, and charity donations. Supports\n  multi-product rewards (recipient choice) and single-product rewards.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Employee Incentives\n  - Global Payouts\n  - Incentives\n  - Market Research\n  - Payouts\n  - Rewards\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tremendous/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tremendous:tremendous\n    name: Tremendous API\n    description: >-\n      The Tremendous REST API enables businesses to\
  \ programmatically send\n      rewards, incentives, and payouts worldwide. The API covers orders,\n      rewards, products, campaigns, funding sources, organizations, members,\n      invoices, and webhooks. Authentication uses Bearer API keys or OAuth 2.0.\n      Rate limit: 30 requests per 30 seconds.\n    humanURL: https://developers.tremendous.com/\n    baseURL: https://testflight.tremendous.com/api/v2\n    tags:\n      - Employee Incentives\n      - Global Payouts\n      - Incentives\n      - Market Research\n      - Payouts\n      - Rewards\n    properties:\n      - type: Documentation\n        url: https://developers.tremendous.com/docs/introduction\n      - type: Reference\n        url: https://developers.tremendous.com/reference/api-endpoints-overview\n      - type: GitHubOrganization\n        url: https://github.com/tremendous-rewards\n      - type: GitHubRepository\n        url: https://github.com/tremendous-rewards/api-docs\n      - type: GitHubRepository\n        url: https://github.com/tremendous-rewards/tremendous-node\n\
  \      - type: OpenAPI\n        url: openapi/tremendous-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.tremendous.com/\n  - type: Documentation\n    url: https://developers.tremendous.com/\n  - type: Sign Up\n    url: https://app.tremendous.com/auth/sign_up\n  - type: Sandbox\n    url: https://testflight.tremendous.com\n  - type: GitHubOrganization\n    url: https://github.com/tremendous-rewards\n  - type: SDK\n    url: https://github.com/tremendous-rewards/tremendous-node\n  - type: Changelog\n    url: https://developers.tremendous.com/changelog\n  - type: JSONSchema\n    url: json-schema/tremendous-order-schema.json\n  - type: JSONSchema\n    url: json-schema/tremendous-product-schema.json\n  - type: JSONStructure\n    url: json-structure/tremendous-order-structure.json\n  - type: JSON-LD\n    url: json-ld/tremendous-context.jsonld\n  - type: SpectralRules\n    url: rules/tremendous-spectral-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/rewards-and-payouts.yaml\n\
  \  - type: Vocabulary\n    url: vocabulary/tremendous-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tremendous/refs/heads/main/apis.yml
tags:
- Employee Incentives
- Global Payouts
- Incentives
- Market Research
- Payouts
- Rewards
url: https://raw.githubusercontent.com/api-evangelist/tremendous/refs/heads/main/apis.yml
use_cases: []
---
