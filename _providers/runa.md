---
api_count: 1
api_specs:
- filename: runa-payouts-api-openapi.yml
  format: yaml
  label: Runa Payouts API
  slug: runa-payouts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/openapi/runa-payouts-api-openapi.yml
apis:
- description: 'The Runa Payouts API (v2) enables digital reward and gift card distribution at scale. Core operations include creating orders (synchronous and asynchronous), retrieving order details, listing orders, '
  name: Runa Payouts API
  slug: runa-payouts-api
capabilities:
- description: Workflow capability for digital reward and gift card distribution using the Runa platform. Combines product discovery, order management, balance monitoring, and cost estimation for B2C payment, employ
  name: Runa Rewards Distribution
  slug: rewards-distribution
common:
- title: ''
  type: Portal
  url: https://developer.runa.io/
- title: ''
  type: Authentication
  url: https://developer.runa.io/docs/getting-an-api-key
- title: ''
  type: SignUp
  url: https://app.runa.io/
- title: ''
  type: Sandbox
  url: https://developer.runa.io/docs/playground
- title: ''
  type: TermsOfService
  url: https://runa.io/legal/
- title: ''
  type: PrivacyPolicy
  url: https://runa.io/privacy-policy/
- title: ''
  type: Blog
  url: https://runa.io/blog/
created: '2025-02-08'
description: Runa is a global digital payouts platform that enables businesses to automate digital reward and gift card distribution through a single API. The platform provides access to over 5,000 gift cards and payout options across 190+ countries, supporting B2C payments, employee rewards, customer incentives, and loyalty programs. The Runa API supports synchronous and asynchronous order modes, balance management, product catalog browsing, and webhook-based event notifications for order completions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Runa Context
  property_count: 14
  slug: runa-context
layout: provider
modified: '2026-05-02'
name: Runa
rules:
- name: Runa API Rules
  rule_count: 9
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 7
  slug: runa-spectral-rules
skills: []
slug: runa
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: runa\nname: Runa\ndescription: >-\n  Runa is a global digital payouts platform that enables businesses to\n  automate digital reward and gift card distribution through a single API.\n  The platform provides access to over 5,000 gift cards and payout options\n  across 190+ countries, supporting B2C payments, employee rewards, customer\n  incentives, and loyalty programs. The Runa API supports synchronous and\n  asynchronous order modes, balance management, product catalog browsing,\n  and webhook-based event notifications for order completions.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Gift Cards\n  - Rewards\n  - Payments\n  - Incentives\n  - Payouts\ncreated: '2025-02-08'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: runa:runa-payouts-api\n    name: Runa Payouts\
  \ API\n    description: >-\n      The Runa Payouts API (v2) enables digital reward and gift card\n      distribution at scale. Core operations include creating orders\n      (synchronous and asynchronous), retrieving order details, listing\n      orders, estimating order costs, managing account balances, browsing\n      the product catalog by category and country, and receiving order\n      completion and product update webhooks. Authentication uses the\n      X-Api-Key header. Idempotency is supported via X-Idempotency-Key.\n    humanURL: https://developer.runa.io/\n    baseURL: https://api.runa.io/v2\n    tags:\n      - Gift Cards\n      - Rewards\n      - Payments\n      - Incentives\n      - Payouts\n      - B2C\n    properties:\n      - type: Documentation\n        url: https://developer.runa.io/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/openapi/runa-payouts-api-openapi.yml\ncommon:\n  - type: Portal\n    url: https://developer.runa.io/\n\
  \  - type: Authentication\n    url: https://developer.runa.io/docs/getting-an-api-key\n  - type: SignUp\n    url: https://app.runa.io/\n  - type: Sandbox\n    url: https://developer.runa.io/docs/playground\n  - type: TermsOfService\n    url: https://runa.io/legal/\n  - type: PrivacyPolicy\n    url: https://runa.io/privacy-policy/\n  - type: Blog\n    url: https://runa.io/blog/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/apis.yml
tags:
- Gift Cards
- Rewards
- Payments
- Incentives
- Payouts
url: https://raw.githubusercontent.com/api-evangelist/runa/refs/heads/main/apis.yml
use_cases: []
---
