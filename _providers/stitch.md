---
api_count: 7
api_specs:
- filename: stitch-openapi.yml
  format: yaml
  label: Stitch GraphQL API
  slug: stitch-graphql
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/openapi/stitch-openapi.yml
apis:
- description: The core Stitch API using GraphQL, available at api.stitch.money/graphql. Follows the Relay Server Specification for pagination. Supports all Stitch products including pay-ins, payouts, bank account d
  name: Stitch GraphQL API
  slug: stitch-graphql
- description: Stitch Pay By Bank enables merchants to accept instant bank transfer payments directly from customers' bank accounts in South Africa and Nigeria.
  name: Stitch Pay By Bank
  slug: stitch-pay-by-bank
- description: Stitch integration with Capitec Bank's Capitec Pay payment method, enabling customers to pay via Capitec mobile banking.
  name: Stitch Capitec Pay
  slug: stitch-capitec-pay
- description: Stitch card payment processing enabling businesses to accept debit and credit card payments through the Stitch unified platform.
  name: Stitch Card Payments
  slug: stitch-card-payments
- description: Stitch DebiCheck integration providing authenticated debit orders for recurring payment collection in South Africa.
  name: Stitch DebiCheck
  slug: stitch-debicheck
- description: Stitch Manual EFT (Electronic Funds Transfer) enabling customers to pay via standard bank EFT with Stitch's streamlined reference management.
  name: Stitch Manual EFT
  slug: stitch-manual-eft
- description: Stitch Disbursements (Payouts) API enabling businesses to programmatically send funds to bank accounts, enabling mass payments, refunds, and marketplace disbursements.
  name: Stitch Disbursements
  slug: stitch-disbursements
capabilities:
- description: Unified open banking and payments workflow for African fintech applications. Combines pay-in payment initiation, bank account data access, and outbound disbursements into a single integration covering
  name: Stitch Open Banking and Payments
  slug: open-banking-payments
common:
- title: ''
  type: Website
  url: https://stitch.money/
- title: ''
  type: Documentation
  url: https://docs.stitch.money/
- title: ''
  type: GitHub Organization
  url: https://github.com/stitch-money
- title: ''
  type: Sign Up
  url: https://stitch.money/contact
- title: ''
  type: Status
  url: https://status.stitch.money/
created: '2026-03-27'
description: Stitch is an open banking and payments API platform providing unified access to financial data and payment rails across banks and financial institutions in Africa, primarily South Africa and Nigeria. Stitch enables businesses to accept payments via multiple channels, access bank account data, and issue disbursements through a single GraphQL API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Stitch Context
  property_count: 0
  slug: stitch-context
layout: provider
modified: '2026-05-02'
name: Stitch
rules:
- name: Stitch API Rules
  rule_count: 7
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 2
  slug: stitch-rules
skills: []
slug: stitch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stitch\nname: Stitch\ndescription: >-\n  Stitch is an open banking and payments API platform providing unified access\n  to financial data and payment rails across banks and financial institutions in\n  Africa, primarily South Africa and Nigeria. Stitch enables businesses to\n  accept payments via multiple channels, access bank account data, and issue\n  disbursements through a single GraphQL API.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Africa\n  - Financial Data\n  - Open Banking\n  - Payments\n  - Unified API\n  - South Africa\n  - Nigeria\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: stitch:stitch-graphql\n    name: Stitch GraphQL API\n    description: >-\n      The core Stitch API using GraphQL, available at api.stitch.money/graphql.\n      Follows the Relay Server\
  \ Specification for pagination. Supports all Stitch\n      products including pay-ins, payouts, bank account data, and payments.\n      Authentication uses OAuth 2.0 client credentials.\n    humanURL: https://docs.stitch.money/\n    tags:\n      - GraphQL\n      - Open Banking\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://docs.stitch.money/\n      - type: GraphQL\n        url: https://api.stitch.money/graphql\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/openapi/stitch-openapi.yml\n  - aid: stitch:stitch-pay-by-bank\n    name: Stitch Pay By Bank\n    description: >-\n      Stitch Pay By Bank enables merchants to accept instant bank transfer\n      payments directly from customers' bank accounts in South Africa and Nigeria.\n    humanURL: https://docs.stitch.money/\n    tags:\n      - Payments\n      - Bank Transfer\n      - Pay-ins\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.stitch.money/\n  - aid: stitch:stitch-capitec-pay\n    name: Stitch Capitec Pay\n    description: >-\n      Stitch integration with Capitec Bank's Capitec Pay payment method,\n      enabling customers to pay via Capitec mobile banking.\n    humanURL: https://docs.stitch.money/\n    tags:\n      - Payments\n      - Capitec\n      - South Africa\n    properties:\n      - type: Documentation\n        url: https://docs.stitch.money/\n  - aid: stitch:stitch-card-payments\n    name: Stitch Card Payments\n    description: >-\n      Stitch card payment processing enabling businesses to accept debit and\n      credit card payments through the Stitch unified platform.\n    humanURL: https://docs.stitch.money/\n    tags:\n      - Payments\n      - Card Payments\n      - Pay-ins\n    properties:\n      - type: Documentation\n        url: https://docs.stitch.money/\n  - aid: stitch:stitch-debicheck\n    name: Stitch DebiCheck\n    description: >-\n      Stitch DebiCheck integration\
  \ providing authenticated debit orders for\n      recurring payment collection in South Africa.\n    humanURL: https://docs.stitch.money/\n    tags:\n      - Payments\n      - DebiCheck\n      - Recurring Payments\n      - South Africa\n    properties:\n      - type: Documentation\n        url: https://docs.stitch.money/\n  - aid: stitch:stitch-manual-eft\n    name: Stitch Manual EFT\n    description: >-\n      Stitch Manual EFT (Electronic Funds Transfer) enabling customers to pay\n      via standard bank EFT with Stitch's streamlined reference management.\n    humanURL: https://docs.stitch.money/\n    tags:\n      - Payments\n      - EFT\n      - Bank Transfer\n    properties:\n      - type: Documentation\n        url: https://docs.stitch.money/\n  - aid: stitch:stitch-disbursements\n    name: Stitch Disbursements\n    description: >-\n      Stitch Disbursements (Payouts) API enabling businesses to programmatically\n      send funds to bank accounts, enabling mass payments, refunds,\
  \ and\n      marketplace disbursements.\n    humanURL: https://docs.stitch.money/\n    tags:\n      - Payouts\n      - Disbursements\n      - Bank Transfer\n    properties:\n      - type: Documentation\n        url: https://docs.stitch.money/\ncommon:\n  - type: Website\n    url: https://stitch.money/\n  - type: Documentation\n    url: https://docs.stitch.money/\n  - type: GitHub Organization\n    url: https://github.com/stitch-money\n  - type: Sign Up\n    url: https://stitch.money/contact\n  - type: Status\n    url: https://status.stitch.money/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/apis.yml
tags:
- Africa
- Financial Data
- Open Banking
- Payments
- Unified API
- South Africa
- Nigeria
url: https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/apis.yml
use_cases: []
---
