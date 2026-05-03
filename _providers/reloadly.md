---
api_count: 2
api_specs:
- filename: reloadly-gift-cards-openapi.yml
  format: yaml
  label: Reloadly Gift Cards API
  slug: gift-cards
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/openapi/reloadly-gift-cards-openapi.yml
- filename: reloadly-airtime-openapi.yml
  format: yaml
  label: Reloadly Airtime API
  slug: airtime
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/openapi/reloadly-airtime-openapi.yml
apis:
- description: Order and manage digital gift cards across 3,000+ global brands including Amazon, Apple, Netflix, Spotify, and Uber. Supports 14,000+ products in 140+ countries with multi-currency payouts and real-ti
  name: Reloadly Gift Cards API
  slug: gift-cards
- description: Send mobile airtime top-ups and data bundles to phones across 170+ countries and 800+ mobile operators. Supports auto-detection of mobile operators from phone numbers with real-time fulfillment and FX
  name: Reloadly Airtime API
  slug: airtime
capabilities:
- description: Unified workflow capability combining Reloadly Gift Cards and Airtime APIs for building digital rewards, loyalty programs, and employee incentive platforms. Enables program managers and marketing team
  name: Reloadly Digital Rewards
  slug: digital-rewards
common:
- title: ''
  type: Website
  url: https://www.reloadly.com
- title: ''
  type: Documentation
  url: https://docs.reloadly.com
- title: ''
  type: Authentication
  url: https://auth.reloadly.com/oauth/token
- title: ''
  type: Dashboard
  url: https://dashboard.reloadly.com
- title: ''
  type: GitHub Organization
  url: https://github.com/reloadly
- title: ''
  type: Support
  url: https://support.reloadly.com
- title: ''
  type: Pricing
  url: https://www.reloadly.com/pricing
- title: ''
  type: Sign Up
  url: https://www.reloadly.com/register
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/reloadly
- title: ''
  type: Twitter
  url: https://twitter.com/reloadly
created: '2025-02-08'
description: Reloadly is a global digital rewards and payments platform providing APIs for sending digital gift cards, airtime top-ups, and data bundles worldwide. The platform connects businesses to 3,000+ gift card brands across 14,000+ products in 140+ countries and 800+ mobile operators in 170+ countries. Reloadly's REST APIs use OAuth 2.0 client credentials authentication with separate sandbox and production environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Reloadly Context
  property_count: 17
  slug: reloadly-context
layout: provider
modified: '2026-05-02'
name: Reloadly
rules:
- name: Reloadly API Rules
  rule_count: 10
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 4
  slug: reloadly-rules
skills: []
slug: reloadly
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: reloadly\nname: Reloadly\ndescription: >-\n  Reloadly is a global digital rewards and payments platform providing APIs\n  for sending digital gift cards, airtime top-ups, and data bundles worldwide.\n  The platform connects businesses to 3,000+ gift card brands across 14,000+\n  products in 140+ countries and 800+ mobile operators in 170+ countries.\n  Reloadly's REST APIs use OAuth 2.0 client credentials authentication with\n  separate sandbox and production environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Gift Cards\n  - Payments\n  - Airtime\n  - Mobile Top-Up\n  - Rewards\n  - Incentives\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/apis.yml\ncreated: '2025-02-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: reloadly:gift-cards\n    name: Reloadly Gift Cards API\n    description: >-\n      Order and manage digital gift cards across\
  \ 3,000+ global brands including\n      Amazon, Apple, Netflix, Spotify, and Uber. Supports 14,000+ products\n      in 140+ countries with multi-currency payouts and real-time fulfillment.\n    humanURL: https://www.reloadly.com/products/gift-card-api\n    baseURL: https://giftcards.reloadly.com\n    tags:\n      - Gift Cards\n      - Rewards\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://docs.reloadly.com/gift-cards\n      - type: OpenAPI\n        url: openapi/reloadly-gift-cards-openapi.yml\n      - type: Authentication\n        url: https://docs.reloadly.com/gift-cards/tag/Authentication\n\n  - aid: reloadly:airtime\n    name: Reloadly Airtime API\n    description: >-\n      Send mobile airtime top-ups and data bundles to phones across 170+\n      countries and 800+ mobile operators. Supports auto-detection of mobile\n      operators from phone numbers with real-time fulfillment and FX conversion.\n    humanURL: https://www.reloadly.com/products/airtime-api\n\
  \    baseURL: https://topups.reloadly.com\n    tags:\n      - Airtime\n      - Mobile Top-Up\n      - Data Bundles\n    properties:\n      - type: Documentation\n        url: https://docs.reloadly.com/airtime\n      - type: OpenAPI\n        url: openapi/reloadly-airtime-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.reloadly.com\n  - type: Documentation\n    url: https://docs.reloadly.com\n  - type: Authentication\n    url: https://auth.reloadly.com/oauth/token\n  - type: Dashboard\n    url: https://dashboard.reloadly.com\n  - type: GitHub Organization\n    url: https://github.com/reloadly\n  - type: Support\n    url: https://support.reloadly.com\n  - type: Pricing\n    url: https://www.reloadly.com/pricing\n  - type: Sign Up\n    url: https://www.reloadly.com/register\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/reloadly\n  - type: Twitter\n    url: https://twitter.com/reloadly\nfeatures:\n  - name: OAuth 2.0 Authentication\n    description: Client credentials\
  \ grant with separate sandbox and production tokens\n  - name: Sandbox Environment\n    description: Full sandbox for development with test credentials\n  - name: Multi-Currency Support\n    description: Payouts in USD, EUR, CAD, and GBP\n  - name: Real-Time Fulfillment\n    description: Instant gift card delivery and airtime top-up processing\n  - name: Global Coverage\n    description: Gift cards in 140+ countries, airtime in 170+ countries\n  - name: SDK Support\n    description: Official SDKs for Node.js, PHP, Python, Go, Java, C#\nsolutions:\n  - name: Employee Rewards\n    description: >-\n      Send digital gift cards as employee recognition rewards and incentives\n      across a global distributed workforce.\n  - name: Customer Loyalty Programs\n    description: >-\n      Power loyalty point redemption with instant digital gift card delivery\n      to customers in 140+ countries.\n  - name: Crypto Exchange Utilities\n    description: >-\n      Enable cryptocurrency holders to convert\
  \ digital assets to airtime\n      or gift cards for real-world utility.\n  - name: Remittance Alternatives\n    description: >-\n      Provide mobile airtime top-ups as a remittance alternative for\n      supporting family members in emerging markets.\n  - name: Bulk Gifting Campaigns\n    description: >-\n      Run large-scale gifting campaigns with bulk gift card orders for\n      marketing, promotions, and B2B incentive programs.\nuseCases:\n  - name: Gift Card Order Automation\n    description: >-\n      Automate gift card delivery for loyalty programs, employee rewards,\n      and customer promotions via REST API.\n  - name: Airtime Top-Up Service\n    description: >-\n      Build mobile wallet applications or remittance services that send\n      airtime top-ups to phones worldwide.\n  - name: Digital Rewards Platform\n    description: >-\n      Integrate Reloadly into an existing rewards platform to offer global\n      gift card and airtime redemption options.\nintegrations:\n \
  \ - name: WordPress Plugin\n    description: Gift card integration for WordPress e-commerce sites\n  - name: Shopify Plugin\n    description: Gift card integration for Shopify stores\n  - name: WooCommerce Plugin\n    description: Gift card integration for WooCommerce-powered stores\n  - name: Node.js SDK\n    description: Official Node.js client library\n  - name: PHP SDK\n    description: Official PHP client library\n  - name: Python SDK\n    description: Official Python client library\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/apis.yml
tags:
- Gift Cards
- Payments
- Airtime
- Mobile Top-Up
- Rewards
- Incentives
url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/apis.yml
use_cases: []
---
