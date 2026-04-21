---
api_count: 1
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
