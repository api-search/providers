---
api_count: 1
api_specs:
- filename: zendit-api.yml
  format: yaml
  label: Zendit API
  slug: zendit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/openapi/zendit-api.yml
apis:
- description: The Zendit API provides programmatic access to the global prepaid ecosystem, enabling developers to offer mobile credit top-ups, data packages, digital gift cards, prepaid utility bill payments, and e
  name: Zendit API
  slug: zendit-api
capabilities:
- description: Unified workflow capability composing Zendit APIs.
  name: Zendit Workflow
  slug: zendit-workflow
common:
- title: ''
  type: Website
  url: https://zendit.io/
- title: ''
  type: Documentation
  url: https://zendit.io/user-guide/
- title: ''
  type: GettingStarted
  url: https://zendit.io/user-guide/getting-started/
- title: ''
  type: APIReference
  url: https://developers.zendit.io/api/
- title: ''
  type: Login
  url: https://console.zendit.io/login
- title: ''
  type: ChangeLog
  url: https://zendit.io/zendit-new-features/
- title: ''
  type: GitHubOrganization
  url: https://github.com/zenditplatform
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/rules/zendit-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/vocabulary/zendit-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/capabilities/zendit-workflow.yaml
created: '2025-02-08'
description: Zendit is a cloud-based Prepay-as-a-Service platform that provides API access to a global prepaid ecosystem. The API enables businesses to offer mobile top-ups, data packages, digital gift cards, prepaid utility bill payments, and eSIM products through a single integration.
features:
- description: Recharge prepaid mobile credit globally across thousands of carriers.
  name: Mobile Top-Ups
- description: Sell mobile data packages to subscribers worldwide.
  name: Data Bundles
- description: Offer eSIM plans for global travelers with QR-code activation.
  name: eSIM Products
- description: Distribute prepaid gift cards across major brands.
  name: Digital Gift Cards
- description: Process prepaid utility payments for electricity, water, and gas.
  name: Utility Bill Payments
- description: Identify carrier from phone number in E.164 format.
  name: Phone Number Lookup
- description: Receive event notifications for transaction completions.
  name: Webhooks
- description: Generate transaction reports as CSV files asynchronously.
  name: Async Reports
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Inbound webhook endpoints for transaction event notifications.
  name: Webhooks
- description: Bearer-token authenticated REST API over HTTPS.
  name: REST API
jsonld:
- class_count: 17
  name: Zendit Api Context
  property_count: 38
  slug: zendit-api-context
- class_count: 2
  name: Zendit Api Esim Context
  property_count: 4
  slug: zendit-api-esim-context
- class_count: 1
  name: Zendit Api Topup Context
  property_count: 4
  slug: zendit-api-topup-context
- class_count: 2
  name: Zendit Api Voucher Context
  property_count: 6
  slug: zendit-api-voucher-context
layout: provider
modified: '2026-05-03'
name: Zendit
rules:
- name: Zendit API Rules
  rule_count: 18
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 13
  slug: zendit-rules
skills: []
slug: zendit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zendit\nname: Zendit\ndescription: >-\n  Zendit is a cloud-based Prepay-as-a-Service platform that provides API access\n  to a global prepaid ecosystem. The API enables businesses to offer mobile\n  top-ups, data packages, digital gift cards, prepaid utility bill payments, and\n  eSIM products through a single integration.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - eSIM\n  - Gift Cards\n  - Mobile Top-Up\n  - Payments\n  - Prepaid\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: zendit:zendit-api\n    name: Zendit API\n    description: >-\n      The Zendit API provides programmatic access to the global prepaid ecosystem,\n      enabling developers to offer mobile credit top-ups, data packages, digital\n      gift cards, prepaid utility\
  \ bill payments, and eSIM products. The platform\n      supports self-onboarding, sandbox testing, and webhook notifications.\n    humanURL: https://zendit.io/\n    baseURL: https://api.zendit.io/v1\n    tags:\n      - eSIM\n      - Gift Cards\n      - Mobile Top-Up\n      - Prepaid\n    properties:\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/openapi/zendit-api.yml\n      - type: Documentation\n        url: https://zendit.io/\n      - type: APIReference\n        url: https://developers.zendit.io/api/\n      - type: GettingStarted\n        url: https://zendit.io/user-guide/getting-started/\n      - type: Authentication\n        url: https://developers.zendit.io/api/\n      - type: Guide\n        url: https://zendit.io/guide-to-integrating-zendits-api-into-your-projects/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-schema/\n      - type: JSONStructure\n\
  \        url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-structure/\n      - type: JSON-LD\n        url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-context.jsonld\n      - type: Example\n        url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/examples/\ncommon:\n  - url: https://zendit.io/\n    name: Zendit Website\n    type: Website\n  - url: https://zendit.io/user-guide/\n    name: User Guide\n    type: Documentation\n  - url: https://zendit.io/user-guide/getting-started/\n    name: Getting Started\n    type: GettingStarted\n  - url: https://developers.zendit.io/api/\n    name: Zendit API Reference\n    type: APIReference\n  - url: https://console.zendit.io/login\n    name: Zendit Console Login\n    type: Login\n  - url: https://zendit.io/zendit-new-features/\n    name: Zendit Releases\n    type: ChangeLog\n  - url: https://github.com/zenditplatform\n    name: Zendit GitHub\
  \ Organization\n    type: GitHubOrganization\n  - url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/rules/zendit-rules.yml\n    name: Zendit Spectral Ruleset\n    type: SpectralRules\n  - url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/vocabulary/zendit-vocabulary.yml\n    name: Zendit Vocabulary\n    type: Vocabulary\n  - url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/capabilities/zendit-workflow.yaml\n    name: Zendit Workflow Capability\n    type: NaftikoCapability\n  - data:\n      - name: Mobile Top-Ups\n        description: Recharge prepaid mobile credit globally across thousands of carriers.\n      - name: Data Bundles\n        description: Sell mobile data packages to subscribers worldwide.\n      - name: eSIM Products\n        description: Offer eSIM plans for global travelers with QR-code activation.\n      - name: Digital Gift Cards\n        description: Distribute prepaid gift cards across\
  \ major brands.\n      - name: Utility Bill Payments\n        description: Process prepaid utility payments for electricity, water, and gas.\n      - name: Phone Number Lookup\n        description: Identify carrier from phone number in E.164 format.\n      - name: Webhooks\n        description: Receive event notifications for transaction completions.\n      - name: Async Reports\n        description: Generate transaction reports as CSV files asynchronously.\n    name: Features\n    type: Features\n  - data:\n      - name: Telecom Resellers\n        description: Power top-up and data plan sales for MVNOs and resellers.\n      - name: Travel Apps\n        description: Embed eSIM purchases into travel booking flows.\n      - name: Gift Card Marketplaces\n        description: Aggregate digital gift card inventory across brands.\n      - name: Fintech Apps\n        description: Enable bill payment and prepaid services within wallets.\n      - name: Loyalty Programs\n        description: Reward\
  \ users with mobile top-ups, gift cards, or eSIM data.\n    name: UseCases\n    type: UseCases\n  - data:\n      - name: Webhooks\n        description: Inbound webhook endpoints for transaction event notifications.\n      - name: REST API\n        description: Bearer-token authenticated REST API over HTTPS.\n    name: Integrations\n    type: Integrations\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/apis.yml
tags:
- eSIM
- Gift Cards
- Mobile Top-Up
- Payments
- Prepaid
url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/apis.yml
use_cases:
- description: Power top-up and data plan sales for MVNOs and resellers.
  name: Telecom Resellers
- description: Embed eSIM purchases into travel booking flows.
  name: Travel Apps
- description: Aggregate digital gift card inventory across brands.
  name: Gift Card Marketplaces
- description: Enable bill payment and prepaid services within wallets.
  name: Fintech Apps
- description: Reward users with mobile top-ups, gift cards, or eSIM data.
  name: Loyalty Programs
---
