---
api_count: 3
api_specs:
- filename: tiktok-business-openapi.yml
  format: yaml
  label: TikTok API for Business
  slug: tiktok-business-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-business-openapi.yml
- filename: tiktok-shop-openapi.yml
  format: yaml
  label: TikTok Shop API
  slug: tiktok-shop-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-shop-openapi.yml
- filename: tiktok-data-portability-openapi.yml
  format: yaml
  label: TikTok Data Portability API
  slug: tiktok-data-portability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-data-portability-openapi.yml
apis:
- description: TikTok's advertising API enabling developers to create and manage ad campaigns, ad groups, creatives, audiences, and reporting for global advertisers on TikTok.
  name: TikTok API for Business
  slug: tiktok-business-api
- description: TikTok Shop Partner API enabling sellers and partners to manage product catalogs, process orders, handle logistics, and integrate with TikTok's commerce ecosystem.
  name: TikTok Shop API
  slug: tiktok-shop-api
- description: Allows users to export their TikTok data including activity, videos, and profile information to third-party services.
  name: TikTok Data Portability API
  slug: tiktok-data-portability-api
capabilities:
- description: Unified workflow capability for managing TikTok advertising campaigns. Combines the Business API to enable full campaign lifecycle management including campaign creation, ad group setup, creative publ
  name: TikTok Advertising Management
  slug: advertising-management
- description: Workflow capability for TikTok Shop e-commerce operations. Uses the TikTok Shop API to manage product catalogs, fulfill orders, track logistics, and monitor financial settlements. Designed for sellers
  name: TikTok Shop Operations
  slug: shop-operations
common:
- title: ''
  type: Website
  url: https://www.tiktok.com/
- title: ''
  type: Portal
  url: https://developers.tiktok.com/
- title: ''
  type: Documentation
  url: https://developers.tiktok.com/doc/overview
- title: ''
  type: Getting Started
  url: https://developers.tiktok.com/doc/overview
- title: ''
  type: Business API Portal
  url: https://business-api.tiktok.com/portal
- title: ''
  type: Shop Partner Portal
  url: https://partner.tiktokshop.com/
- title: ''
  type: Authentication
  url: https://developers.tiktok.com/doc/login-kit-manage-user-access-tokens
- title: ''
  type: GitHub Organization
  url: https://github.com/tiktok
- title: ''
  type: SDK
  url: https://github.com/tiktok/tiktok-business-api-sdk
- title: ''
  type: Change Log
  url: https://developers.tiktok.com/doc/changelog
- title: ''
  type: Blog
  url: https://developers.tiktok.com/blog
- title: ''
  type: Forum
  url: https://developers.tiktok.com/community
- title: ''
  type: Status
  url: https://status.tiktok.com/
- title: ''
  type: Terms of Service
  url: https://developers.tiktok.com/doc/tiktok-api-terms-of-service
- title: ''
  type: Privacy Policy
  url: https://developers.tiktok.com/doc/tiktok-api-data-privacy
- title: ''
  type: Sign Up
  url: https://developers.tiktok.com/
- title: ''
  type: Login
  url: https://developers.tiktok.com/login
created: '2025-08-14'
description: TikTok is a short-form social video platform offering developers REST APIs for advertising, e-commerce, content discovery, and platform integrations. Key products include the TikTok API for Business (advertising and campaign management), TikTok Shop API (seller product and order management), and the Data Portability API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Tiktok Context
  property_count: 0
  slug: tiktok-context
layout: provider
modified: '2026-05-03'
name: TikTok
rules:
- name: TikTok API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 2
  slug: tiktok-rules
skills: []
slug: tiktok
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tiktok\nname: TikTok\ndescription: >-\n  TikTok is a short-form social video platform offering developers REST APIs\n  for advertising, e-commerce, content discovery, and platform integrations.\n  Key products include the TikTok API for Business (advertising and campaign\n  management), TikTok Shop API (seller product and order management), and the\n  Data Portability API.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Advertising\n  - Commerce\n  - Content\n  - E-Commerce\n  - Social Media\n  - Video\ncreated: '2025-08-14'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tiktok:tiktok-business-api\n    name: TikTok API for Business\n    description: >-\n      TikTok's advertising API enabling developers to create and manage ad\n      campaigns, ad groups, creatives,\
  \ audiences, and reporting for global\n      advertisers on TikTok.\n    humanURL: https://business-api.tiktok.com/portal/docs\n    baseURL: https://business-api.tiktok.com\n    tags:\n      - Advertising\n      - Campaigns\n      - Marketing\n      - Social Media\n    properties:\n      - type: Documentation\n        url: https://business-api.tiktok.com/portal/docs\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-business-openapi.yml\n  - aid: tiktok:tiktok-shop-api\n    name: TikTok Shop API\n    description: >-\n      TikTok Shop Partner API enabling sellers and partners to manage product\n      catalogs, process orders, handle logistics, and integrate with TikTok's\n      commerce ecosystem.\n    humanURL: https://partner.tiktokshop.com/docv2/page/tts-api-concepts-overview\n    baseURL: https://open-api.tiktokglobalshop.com\n    tags:\n      - Commerce\n      - E-Commerce\n      - Products\n  \
  \    - Orders\n    properties:\n      - type: Documentation\n        url: https://partner.tiktokshop.com/doc/page/63fd743c715d622a338c4e54\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-shop-openapi.yml\n  - aid: tiktok:tiktok-data-portability-api\n    name: TikTok Data Portability API\n    description: >-\n      Allows users to export their TikTok data including activity, videos, and\n      profile information to third-party services.\n    humanURL: https://developers.tiktok.com/doc/data-portability-api-get-started\n    baseURL: https://open.tiktokapis.com\n    tags:\n      - Data Portability\n      - Privacy\n      - User Data\n    properties:\n      - type: Documentation\n        url: https://developers.tiktok.com/doc/data-portability-api-get-started\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-data-portability-openapi.yml\n\
  common:\n  - type: Website\n    url: https://www.tiktok.com/\n  - type: Portal\n    url: https://developers.tiktok.com/\n  - type: Documentation\n    url: https://developers.tiktok.com/doc/overview\n  - type: Getting Started\n    url: https://developers.tiktok.com/doc/overview\n  - type: Business API Portal\n    url: https://business-api.tiktok.com/portal\n  - type: Shop Partner Portal\n    url: https://partner.tiktokshop.com/\n  - type: Authentication\n    url: https://developers.tiktok.com/doc/login-kit-manage-user-access-tokens\n  - type: GitHub Organization\n    url: https://github.com/tiktok\n  - type: SDK\n    url: https://github.com/tiktok/tiktok-business-api-sdk\n  - type: Change Log\n    url: https://developers.tiktok.com/doc/changelog\n  - type: Blog\n    url: https://developers.tiktok.com/blog\n  - type: Forum\n    url: https://developers.tiktok.com/community\n  - type: Status\n    url: https://status.tiktok.com/\n  - type: Terms of Service\n    url: https://developers.tiktok.com/doc/tiktok-api-terms-of-service\n\
  \  - type: Privacy Policy\n    url: https://developers.tiktok.com/doc/tiktok-api-data-privacy\n  - type: Sign Up\n    url: https://developers.tiktok.com/\n  - type: Login\n    url: https://developers.tiktok.com/login\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/apis.yml
tags:
- Advertising
- Commerce
- Content
- E-Commerce
- Social Media
- Video
url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/apis.yml
use_cases: []
---
