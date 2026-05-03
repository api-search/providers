---
api_count: 2
api_specs:
- filename: tillo-gift-card-openapi.yml
  format: yaml
  label: Tillo Gift Card API
  slug: tillo-gift-card-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/openapi/tillo-gift-card-openapi.yml
- filename: tillo-gift-card-openapi.yml
  format: yaml
  label: Tillo Float Management API
  slug: tillo-float-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/openapi/tillo-gift-card-openapi.yml
apis:
- description: The Tillo Gift Card API enables businesses to issue digital and physical gift cards from 4,000+ global brands. Supports synchronous and asynchronous card issuance, balance checking, refunds, order sta
  name: Tillo Gift Card API
  slug: tillo-gift-card-api
- description: Manages Tillo float accounts including balance retrieval, payment transfer requests, and transfer status tracking.
  name: Tillo Float Management API
  slug: tillo-float-api
capabilities:
- description: Workflow capability for delivering gift card rewards and incentives at scale using Tillo. Combines brand discovery, card issuance, balance checking, and order management into a unified rewards workflo
  name: Tillo Gift Card Rewards
  slug: gift-card-rewards
common:
- title: ''
  type: Website
  url: https://www.tillo.io/
- title: ''
  type: Portal
  url: https://www.tillo.io/gift-card-api
- title: ''
  type: Documentation
  url: https://tillo.tech/v2_docs/
- title: ''
  type: Getting Started
  url: https://tillo.tech/v2_docs/getting_started.html
- title: ''
  type: Authentication
  url: https://tillo.tech/v2_docs/authentication.html
- title: ''
  type: GitHub Organization
  url: https://github.com/tilloops
- title: ''
  type: GitHub Repository
  url: https://github.com/tilloops/tillo
- title: ''
  type: Blog
  url: https://www.tillo.io/blog
- title: ''
  type: Contact
  url: https://www.tillo.io/contact
- title: ''
  type: Pricing
  url: https://www.tillo.io/pricing
- title: ''
  type: Terms of Service
  url: https://www.tillo.io/legal
- title: ''
  type: Postman Collection
  url: https://api.tillo.tech/
- title: ''
  type: Sign Up
  url: https://app.tillo.io/
- title: ''
  type: Use Cases
  url: https://www.tillo.io/
created: '2025-02-08'
description: Tillo is an award-winning gift card API platform connecting businesses to 4,000+ global brands across 37 markets and 16 currencies. The REST API supports digital and physical gift card issuance, balance checking, float management, and brand catalog access. Authentication uses HMAC-SHA256 signatures.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Tillo Context
  property_count: 0
  slug: tillo-context
layout: provider
modified: '2026-05-03'
name: Tillo
rules:
- name: Tillo API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 3
  slug: tillo-rules
skills: []
slug: tillo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tillo\nname: Tillo\ndescription: >-\n  Tillo is an award-winning gift card API platform connecting businesses to\n  4,000+ global brands across 37 markets and 16 currencies. The REST API\n  supports digital and physical gift card issuance, balance checking, float\n  management, and brand catalog access. Authentication uses HMAC-SHA256\n  signatures.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Finance\n  - Gift Cards\n  - Payments\n  - Rewards\n  - Incentives\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tillo:tillo-gift-card-api\n    name: Tillo Gift Card API\n    description: >-\n      The Tillo Gift Card API enables businesses to issue digital and physical\n      gift cards from 4,000+ global brands. Supports synchronous and\n  \
  \    asynchronous card issuance, balance checking, refunds, order status\n      checking, and brand catalog retrieval.\n    humanURL: https://www.tillo.io/gift-card-api\n    baseURL: https://app.tillo.io\n    tags:\n      - Finance\n      - Gift Cards\n      - Payments\n      - Rewards\n    properties:\n      - type: Documentation\n        url: https://tillo.tech/v2_docs/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/openapi/tillo-gift-card-openapi.yml\n  - aid: tillo:tillo-float-api\n    name: Tillo Float Management API\n    description: >-\n      Manages Tillo float accounts including balance retrieval, payment\n      transfer requests, and transfer status tracking.\n    humanURL: https://tillo.tech/v2_docs/floats.html\n    baseURL: https://app.tillo.io\n    tags:\n      - Finance\n      - Float\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://tillo.tech/v2_docs/floats.html\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/openapi/tillo-gift-card-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.tillo.io/\n  - type: Portal\n    url: https://www.tillo.io/gift-card-api\n  - type: Documentation\n    url: https://tillo.tech/v2_docs/\n  - type: Getting Started\n    url: https://tillo.tech/v2_docs/getting_started.html\n  - type: Authentication\n    url: https://tillo.tech/v2_docs/authentication.html\n  - type: GitHub Organization\n    url: https://github.com/tilloops\n  - type: GitHub Repository\n    url: https://github.com/tilloops/tillo\n  - type: Blog\n    url: https://www.tillo.io/blog\n  - type: Contact\n    url: https://www.tillo.io/contact\n  - type: Pricing\n    url: https://www.tillo.io/pricing\n  - type: Terms of Service\n    url: https://www.tillo.io/legal\n  - type: Postman Collection\n    url: https://api.tillo.tech/\n  - type: Sign Up\n    url: https://app.tillo.io/\n\
  \  - type: Use Cases\n    url: https://www.tillo.io/\n  - type: Integrations\n    url: https://www.tillo.io/partners\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/apis.yml
tags:
- Finance
- Gift Cards
- Payments
- Rewards
- Incentives
url: https://raw.githubusercontent.com/api-evangelist/tillo/refs/heads/main/apis.yml
use_cases: []
---
