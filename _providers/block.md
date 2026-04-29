---
api_count: 1
api_specs:
- filename: block-square-api-openapi.yaml
  format: yaml
  label: Square API
  slug: block-square-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/block/refs/heads/main/openapi/block-square-api-openapi.yaml
apis:
- description: RESTful API for building commerce applications on the Square platform. Provides payment processing, order management, catalog management, customer profiles, loyalty programs, invoicing, and merchant o
  name: Square API
  slug: block-square-api
capabilities:
- description: ''
  name: Block Square Commerce
  slug: block-square-commerce
common:
- title: ''
  type: Website
  url: https://www.block.xyz
- title: ''
  type: Documentation
  url: https://developer.squareup.com/docs
- title: ''
  type: GettingStarted
  url: https://developer.squareup.com/docs/get-started
- title: ''
  type: Pricing
  url: https://squareup.com/us/en/payments/our-rates
- title: ''
  type: StatusPage
  url: https://www.issquareup.com/
- title: ''
  type: Support
  url: https://developer.squareup.com/forums
- title: ''
  type: GitHubOrganization
  url: https://github.com/square
- title: ''
  type: TermsOfService
  url: https://squareup.com/us/en/legal/developer
- title: ''
  type: PrivacyPolicy
  url: https://squareup.com/us/en/legal/privacy
- title: ''
  type: Login
  url: https://developer.squareup.com/apps
- title: Square SDKs
  type: SDK
  url: https://developer.squareup.com/docs/sdks
- title: ''
  type: SpectralRules
  url: rules/block-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/block-square-commerce.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/block-vocabulary.yaml
created: '2024-09-27'
description: Block, Inc. is a global technology company building economic empowerment tools through a family of products including Square (commerce and payments), Cash App (personal finance and investing), Afterpay (buy now pay later), TIDAL (music streaming), and Spiral (open-source Bitcoin development). The Square API enables developers to build commerce applications with payment processing, order management, catalog, customer engagement, and business operations capabilities.
features:
- description: Accept card-present and card-not-present payments using Square hardware, web, or mobile SDKs with OAuth 2.0 or access token authentication.
  name: Payment Processing
- description: Create, update, and fulfill orders with line items, discounts, taxes, and service charges across online and in-person channels.
  name: Order Management
- description: Manage a unified product catalog with items, variations, modifiers, categories, taxes, and discounts synchronized across all locations.
  name: Catalog Management
- description: Build customer profiles, loyalty programs, gift cards, and marketing campaigns to drive repeat business and customer retention.
  name: Customer Engagement
- description: Manage multiple business locations with location-specific inventory, pricing, staff permissions, and reporting.
  name: Multi-Location Support
- description: Subscribe to real-time webhook events for payments, orders, inventory changes, customer activity, and subscription lifecycle events.
  name: Webhook Events
- description: Full sandbox environment with test card numbers, merchant accounts, and simulated hardware for development and testing.
  name: Sandbox Environment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Square extension for WooCommerce synchronizes inventory, products, and payments between WordPress stores and Square.
  name: WooCommerce
- description: Square integration for BigCommerce enables omnichannel selling with synchronized catalog and unified payment processing.
  name: BigCommerce
- description: Square-Xero integration automatically syncs sales transactions and payments to Xero accounting for reconciliation.
  name: Xero
- description: Square connector for QuickBooks Online syncs sales, refunds, and fees to QuickBooks for financial reporting.
  name: QuickBooks
jsonld:
- class_count: 35
  name: Block Context
  property_count: 0
  slug: block-context
layout: provider
modified: '2026-04-19'
name: Block
rules:
- name: Block API Rules
  rule_count: 29
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 15
  slug: block-spectral-rules
skills: []
slug: block
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: block\nurl: https://raw.githubusercontent.com/api-evangelist/block/refs/heads/main/apis.yml\nname: Block\ndescription: >-\n  Block, Inc. is a global technology company building economic empowerment tools\n  through a family of products including Square (commerce and payments), Cash App\n  (personal finance and investing), Afterpay (buy now pay later), TIDAL (music\n  streaming), and Spiral (open-source Bitcoin development). The Square API enables\n  developers to build commerce applications with payment processing, order management,\n  catalog, customer engagement, and business operations capabilities.\ntags:\n  - Commerce\n  - Cryptocurrency\n  - eCommerce\n  - Fintech\n  - Payments\n  - Point Of Sale\n  - Square\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-09-27'\nmodified: '2026-04-19'\nposition: Consuming\nspecificationVersion: '0.19'\napis:\n  - aid: block:block-square-api\n    name:\
  \ Square API\n    description: >-\n      RESTful API for building commerce applications on the Square platform. Provides\n      payment processing, order management, catalog management, customer profiles,\n      loyalty programs, invoicing, and merchant operations. Supports OAuth 2.0 and\n      personal access token authentication. Available in sandbox and production environments.\n    humanURL: https://developer.squareup.com/\n    tags:\n      - Commerce\n      - eCommerce\n      - Payments\n      - Point Of Sale\n      - Square\n    properties:\n      - type: Documentation\n        url: https://developer.squareup.com/docs\n      - type: OpenAPI\n        url: openapi/block-square-api-openapi.yaml\n      - type: NaftikoCapability\n        url: capabilities/block-square-commerce.yaml\n      - type: SpectralRules\n        url: rules/block-spectral-rules.yml\n      - type: Vocabulary\n        url: vocabulary/block-vocabulary.yaml\ncommon:\n  - type: Website\n    url: https://www.block.xyz\n\
  \  - type: Documentation\n    url: https://developer.squareup.com/docs\n  - type: GettingStarted\n    url: https://developer.squareup.com/docs/get-started\n  - type: Pricing\n    url: https://squareup.com/us/en/payments/our-rates\n  - type: StatusPage\n    url: https://www.issquareup.com/\n  - type: Support\n    url: https://developer.squareup.com/forums\n  - type: GitHubOrganization\n    url: https://github.com/square\n  - type: TermsOfService\n    url: https://squareup.com/us/en/legal/developer\n  - type: PrivacyPolicy\n    url: https://squareup.com/us/en/legal/privacy\n  - type: Login\n    url: https://developer.squareup.com/apps\n  - type: SDK\n    url: https://developer.squareup.com/docs/sdks\n    title: Square SDKs\n  - type: SpectralRules\n    url: rules/block-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/block-square-commerce.yaml\n  - type: Vocabulary\n    url: vocabulary/block-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Payment Processing\n\
  \        description: >-\n          Accept card-present and card-not-present payments using Square hardware,\n          web, or mobile SDKs with OAuth 2.0 or access token authentication.\n      - name: Order Management\n        description: >-\n          Create, update, and fulfill orders with line items, discounts, taxes,\n          and service charges across online and in-person channels.\n      - name: Catalog Management\n        description: >-\n          Manage a unified product catalog with items, variations, modifiers,\n          categories, taxes, and discounts synchronized across all locations.\n      - name: Customer Engagement\n        description: >-\n          Build customer profiles, loyalty programs, gift cards, and marketing\n          campaigns to drive repeat business and customer retention.\n      - name: Multi-Location Support\n        description: >-\n          Manage multiple business locations with location-specific inventory,\n          pricing, staff permissions,\
  \ and reporting.\n      - name: Webhook Events\n        description: >-\n          Subscribe to real-time webhook events for payments, orders, inventory\n          changes, customer activity, and subscription lifecycle events.\n      - name: Sandbox Environment\n        description: >-\n          Full sandbox environment with test card numbers, merchant accounts,\n          and simulated hardware for development and testing.\n  - type: UseCases\n    data:\n      - name: Point of Sale Integration\n        description: >-\n          Retailers and restaurants build custom POS applications using Square's\n          payment, catalog, and order APIs.\n      - name: eCommerce Checkout\n        description: >-\n          Online stores integrate Square's Web Payments SDK and Orders API to\n          accept payments and manage fulfillment.\n      - name: Marketplace Payments\n        description: >-\n          Multi-seller marketplaces use Square Connect to route payments to\n          sellers and\
  \ manage fees through the Payouts API.\n      - name: Subscription Billing\n        description: >-\n          SaaS and service businesses use Square Subscriptions API for automated\n          recurring billing and invoice management.\n      - name: Loyalty and Rewards\n        description: >-\n          Businesses implement custom loyalty programs using the Loyalty API to\n          track points, tiers, and reward redemptions.\n  - type: Integrations\n    data:\n      - name: WooCommerce\n        description: >-\n          Official Square extension for WooCommerce synchronizes inventory,\n          products, and payments between WordPress stores and Square.\n      - name: BigCommerce\n        description: >-\n          Square integration for BigCommerce enables omnichannel selling with\n          synchronized catalog and unified payment processing.\n      - name: Xero\n        description: >-\n          Square-Xero integration automatically syncs sales transactions and\n          payments\
  \ to Xero accounting for reconciliation.\n      - name: QuickBooks\n        description: >-\n          Square connector for QuickBooks Online syncs sales, refunds, and fees\n          to QuickBooks for financial reporting.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/block/refs/heads/main/apis.yml
tags:
- Commerce
- Cryptocurrency
- eCommerce
- Fintech
- Payments
- Point Of Sale
- Square
url: https://raw.githubusercontent.com/api-evangelist/block/refs/heads/main/apis.yml
use_cases:
- description: Retailers and restaurants build custom POS applications using Square's payment, catalog, and order APIs.
  name: Point of Sale Integration
- description: Online stores integrate Square's Web Payments SDK and Orders API to accept payments and manage fulfillment.
  name: eCommerce Checkout
- description: Multi-seller marketplaces use Square Connect to route payments to sellers and manage fees through the Payouts API.
  name: Marketplace Payments
- description: SaaS and service businesses use Square Subscriptions API for automated recurring billing and invoice management.
  name: Subscription Billing
- description: Businesses implement custom loyalty programs using the Loyalty API to track points, tiers, and reward redemptions.
  name: Loyalty and Rewards
---
