---
api_count: 2
api_specs:
- filename: charles-schwab-trader-api-openapi.yml
  format: yaml
  label: Charles Schwab Trader API
  slug: trader-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/openapi/charles-schwab-trader-api-openapi.yml
- filename: charles-schwab-market-data-api-openapi.yml
  format: yaml
  label: Charles Schwab Market Data API
  slug: market-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/openapi/charles-schwab-market-data-api-openapi.yml
apis:
- description: 'The Schwab Trader API provides authenticated access to retail brokerage accounts. Applications can list linked accounts, retrieve balances and positions, fetch and cancel orders, place new orders for '
  name: Charles Schwab Trader API
  slug: trader-api
- description: The Schwab Market Data API exposes real-time and historical quotes, option chains, price history, market hours, instrument metadata, and daily movers for the major US indices, supporting market analyt
  name: Charles Schwab Market Data API
  slug: market-data-api
common:
- title: ''
  type: Website
  url: https://www.schwab.com
- title: ''
  type: DeveloperPortal
  url: https://developer.schwab.com/
- title: ''
  type: Documentation
  url: https://developer.schwab.com/user-guides
- title: ''
  type: Authentication
  url: https://developer.schwab.com/user-guides/get-started/authenticate-with-oauth
- title: ''
  type: SignUp
  url: https://developer.schwab.com/register
- title: ''
  type: Dashboard
  url: https://developer.schwab.com/dashboard
- title: ''
  type: Support
  url: https://developer.schwab.com/contact-us
- title: ''
  type: TermsOfService
  url: https://developer.schwab.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.schwab.com/legal/online-privacy
- title: ''
  type: JSONLD
  url: json-ld/charles-schwab-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/charles-schwab-account-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/charles-schwab-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/charles-schwab-quote-schema.json
created: '2026-03-21'
description: Charles Schwab is a financial services company providing brokerage, banking, asset management, and financial advisory services to individual investors and independent investment advisors. The Schwab Developer Portal exposes Trader APIs that let registered applications access account balances, positions, and orders, place equity and option trades, and consume real-time and historical market data through OAuth 2.0-secured REST endpoints.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Charles Schwab Context
  property_count: 5
  slug: charles-schwab-context
layout: provider
modified: '2026-04-23'
name: Charles Schwab
skills: []
slug: charles-schwab
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: charles-schwab\nname: Charles Schwab\ndescription: >-\n  Charles Schwab is a financial services company providing brokerage, banking,\n  asset management, and financial advisory services to individual investors and\n  independent investment advisors. The Schwab Developer Portal exposes Trader\n  APIs that let registered applications access account balances, positions, and\n  orders, place equity and option trades, and consume real-time and historical\n  market data through OAuth 2.0-secured REST endpoints.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Accounts\n  - Banking\n  - Brokerage\n  - Financial Services\n  - Investing\n  - Market Data\n  - OAuth 2.0\n  - Orders\n  - Trading\ncreated: '2026-03-21'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid:\
  \ charles-schwab:trader-api\n    name: Charles Schwab Trader API\n    description: >-\n      The Schwab Trader API provides authenticated access to retail brokerage\n      accounts. Applications can list linked accounts, retrieve balances and\n      positions, fetch and cancel orders, place new orders for equities and\n      options, retrieve transactions, and stream account activity.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.schwab.com/products/trader-api--individual\n    baseURL: https://api.schwabapi.com/trader/v1\n    tags:\n      - Accounts\n      - Brokerage\n      - Orders\n      - Trading\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://developer.schwab.com/products/trader-api--individual\n      - type: GettingStarted\n        url: https://developer.schwab.com/user-guides/get-started\n      - type: Authentication\n        url: https://developer.schwab.com/user-guides/get-started/authenticate-with-oauth\n\
  \      - type: OpenAPI\n        url: openapi/charles-schwab-trader-api-openapi.yml\n      - type: Spectral\n        url: spectral/charles-schwab-spectral.yml\n  - aid: charles-schwab:market-data-api\n    name: Charles Schwab Market Data API\n    description: >-\n      The Schwab Market Data API exposes real-time and historical quotes,\n      option chains, price history, market hours, instrument metadata, and\n      daily movers for the major US indices, supporting market analytics and\n      trading decision tools.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.schwab.com/products/trader-api--individual\n    baseURL: https://api.schwabapi.com/marketdata/v1\n    tags:\n      - Equities\n      - Market Data\n      - Options\n      - Quotes\n    properties:\n      - type: Documentation\n        url: https://developer.schwab.com/products/trader-api--individual\n      - type: Authentication\n        url: https://developer.schwab.com/user-guides/get-started/authenticate-with-oauth\n\
  \      - type: OpenAPI\n        url: openapi/charles-schwab-market-data-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.schwab.com\n  - type: DeveloperPortal\n    url: https://developer.schwab.com/\n  - type: Documentation\n    url: https://developer.schwab.com/user-guides\n  - type: Authentication\n    url: https://developer.schwab.com/user-guides/get-started/authenticate-with-oauth\n  - type: SignUp\n    url: https://developer.schwab.com/register\n  - type: Dashboard\n    url: https://developer.schwab.com/dashboard\n  - type: Support\n    url: https://developer.schwab.com/contact-us\n  - type: TermsOfService\n    url: https://developer.schwab.com/terms\n  - type: PrivacyPolicy\n    url: https://www.schwab.com/legal/online-privacy\n  - type: JSONLD\n    url: json-ld/charles-schwab-context.jsonld\n  - type: JSONSchema\n    url: json-schema/charles-schwab-account-schema.json\n  - type: JSONSchema\n    url: json-schema/charles-schwab-order-schema.json\n  - type: JSONSchema\n\
  \    url: json-schema/charles-schwab-quote-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/apis.yml
tags:
- Accounts
- Banking
- Brokerage
- Financial Services
- Investing
- Market Data
- OAuth 2.0
- Orders
- Trading
url: https://raw.githubusercontent.com/api-evangelist/charles-schwab/refs/heads/main/apis.yml
use_cases: []
---
