---
api_count: 4
api_specs:
- filename: stonex-payments-openapi.yml
  format: yaml
  label: StoneX Payments API
  slug: stonex-payments
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-payments-openapi.yml
- filename: stonex-clearing-openapi.yml
  format: yaml
  label: StoneX Clearing API
  slug: stonex-clearing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-clearing-openapi.yml
apis:
- description: The StoneX Payments REST API enables cross-border payment processing in 140+ currencies with local currency acceptance and settlement. Uses Bearer token authentication over HTTPS with TLS 1.3. Availab
  name: StoneX Payments API
  slug: stonex-payments
- description: The StoneX Clearing REST API provides programmatic access to accounts, trading, and document management for clearing clients. Supports OAuth 2.0 authentication with JWT tokens. Available in UAT (api.c
  name: StoneX Clearing API
  slug: stonex-clearing
- description: The StoneX GF (GAIN Futures) API provides institutional-grade access to futures trading including market data, order management, account and position tracking, margin calculations, contract lookup, an
  name: StoneX GF Futures API
  slug: stonex-gf-api
- description: The StoneX Developer Storefront provides access to all StoneX API products with subscription keys, documentation, and developer resources for integrating with StoneX financial services.
  name: StoneX Developer Portal
  slug: stonex-developer-portal
capabilities:
- description: Unified financial services workflow combining StoneX cross-border payments and institutional clearing operations. Enables financial institutions, corporate treasuries, and institutional traders to exe
  name: StoneX Financial Services
  slug: financial-services
common:
- title: ''
  type: Website
  url: https://www.stonex.com
- title: ''
  type: Developer Portal
  url: https://developer.stonex.com/
- title: ''
  type: Documentation
  url: https://developer.stonex.com/documentation
created: '2026-05-02'
description: StoneX Group is a global financial services organization that provides execution, risk management, market intelligence, and post-trade services across asset classes and markets to institutional, commercial, and retail clients. StoneX offers REST APIs for payments, clearing, and futures trading with OAuth 2.0 authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Stonex Context
  property_count: 0
  slug: stonex-context
layout: provider
modified: '2026-05-02'
name: StoneX
rules:
- name: StoneX API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 3
  slug: stonex-rules
skills: []
slug: stonex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stonex\nname: StoneX\ndescription: >-\n  StoneX Group is a global financial services organization that provides\n  execution, risk management, market intelligence, and post-trade services\n  across asset classes and markets to institutional, commercial, and retail\n  clients. StoneX offers REST APIs for payments, clearing, and futures trading\n  with OAuth 2.0 authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Finance\n  - Financial Services\n  - Payments\n  - Clearing\n  - Futures\n  - Trading\n  - Risk Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: stonex:stonex-payments\n    name: StoneX Payments API\n    description: >-\n      The StoneX Payments REST API enables cross-border payment processing\n      in 140+ currencies with local currency acceptance\
  \ and settlement.\n      Uses Bearer token authentication over HTTPS with TLS 1.3. Available\n      in sandbox and production environments.\n    humanURL: https://docs.payments.stonex.io/\n    tags:\n      - Payments\n      - Cross-Border Payments\n      - FX\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.payments.stonex.io/\n      - type: Getting Started\n        url: https://docs.payments.stonex.io/docs/quickstart-guide-1\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-payments-openapi.yml\n  - aid: stonex:stonex-clearing\n    name: StoneX Clearing API\n    description: >-\n      The StoneX Clearing REST API provides programmatic access to accounts,\n      trading, and document management for clearing clients. Supports\n      OAuth 2.0 authentication with JWT tokens. Available in UAT\n      (api.clearing.uat.stonex.com) and production (api.clearing.stonex.com).\n\
  \    humanURL: https://docs.clearing.stonex.com/\n    tags:\n      - Clearing\n      - Trading\n      - Accounts\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.clearing.stonex.com/docs\n      - type: Getting Started\n        url: https://docs.clearing.stonex.com/docs/getting-started/introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/openapi/stonex-clearing-openapi.yml\n  - aid: stonex:stonex-gf-api\n    name: StoneX GF Futures API\n    description: >-\n      The StoneX GF (GAIN Futures) API provides institutional-grade access to\n      futures trading including market data, order management, account and position\n      tracking, margin calculations, contract lookup, and real-time price feeds\n      for futures contracts.\n    humanURL: https://futures-media.stonex.com/gfapi/index.html\n    tags:\n      - Futures\n      - Trading\n      - Market Data\n      - Institutional\n\
  \    properties:\n      - type: Documentation\n        url: https://futures-media.stonex.com/gfapi/index.html\n  - aid: stonex:stonex-developer-portal\n    name: StoneX Developer Portal\n    description: >-\n      The StoneX Developer Storefront provides access to all StoneX API\n      products with subscription keys, documentation, and developer resources\n      for integrating with StoneX financial services.\n    humanURL: https://developer.stonex.com/\n    tags:\n      - Developer Portal\n      - API Management\n    properties:\n      - type: Documentation\n        url: https://developer.stonex.com/documentation\n      - type: Products\n        url: https://developer.stonex.com/products\ncommon:\n  - type: Website\n    url: https://www.stonex.com\n  - type: Developer Portal\n    url: https://developer.stonex.com/\n  - type: Documentation\n    url: https://developer.stonex.com/documentation\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/apis.yml
tags:
- Finance
- Financial Services
- Payments
- Clearing
- Futures
- Trading
- Risk Management
url: https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/apis.yml
use_cases: []
---
