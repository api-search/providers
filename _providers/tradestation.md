---
api_count: 2
api_specs:
- filename: tradestation-api-openapi.yml
  format: yaml
  label: TradeStation API
  slug: tradestation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/openapi/tradestation-api-openapi.yml
- filename: tradestation-streaming-asyncapi.yml
  format: yaml
  label: TradeStation Streaming API
  slug: tradestation-streaming
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/asyncapi/tradestation-streaming-asyncapi.yml
apis:
- description: The TradeStation REST API provides brokerage and market data services for building trading applications. Covers account management, order placement and execution, real-time and historical market data,
  name: TradeStation API
  slug: tradestation-api
- description: 'The TradeStation Streaming API provides real-time HTTP streaming endpoints using chunked transfer encoding with newline-delimited JSON for market data and brokerage events. Streams deliver live quote '
  name: TradeStation Streaming API
  slug: tradestation-streaming
asyncapis:
- description: The TradeStation Streaming API provides real-time HTTP streaming endpoints for market data and brokerage events. Streams use HTTP chunked transfer encoding with newline-delimited JSON objects. Each st
  name: TradeStation Streaming API
  slug: tradestation-streaming-asyncapi
capabilities:
- description: Unified trading and market data workflow combining account management, order execution, real-time quotes, historical bar data, and options analysis. Used by algorithmic traders and application develop
  name: TradeStation Trading and Market Data
  slug: trading-and-market-data
common:
- title: ''
  type: Website
  url: https://www.tradestation.com
- title: ''
  type: Developer
  url: https://developer.tradestation.com
- title: ''
  type: Documentation
  url: https://api.tradestation.com/docs/
- title: ''
  type: Authentication
  url: https://api.tradestation.com/docs/fundamentals/authentication/
- title: ''
  type: GitHub
  url: https://github.com/tradestation
- title: ''
  type: RateLimiting
  url: https://api.tradestation.com/docs/fundamentals/rate-limiting/
- title: ''
  type: TermsOfService
  url: https://www.tradestation.com/important-information/
created: '2026-03-24'
description: TradeStation is a financial brokerage and trading platform offering a collection of RESTful brokerage and market data services for building trading applications for stocks, options, futures, and cryptocurrency. The API provides endpoints for account management, order placement and execution, real-time and historical market data, option chains, symbol information, and HTTP streaming for live market feeds. TradeStation supports advanced order types including bracket, OCO, OSO, and multi-leg options orders with OAuth2 authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Tradestation Context
  property_count: 8
  slug: tradestation-context
layout: provider
modified: '2026-05-03'
name: TradeStation
rules:
- name: TradeStation API Rules
  rule_count: 11
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 5
  slug: tradestation-rules
skills: []
slug: tradestation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tradestation\nname: TradeStation\ndescription: >-\n  TradeStation is a financial brokerage and trading platform offering a\n  collection of RESTful brokerage and market data services for building trading\n  applications for stocks, options, futures, and cryptocurrency. The API\n  provides endpoints for account management, order placement and execution,\n  real-time and historical market data, option chains, symbol information, and\n  HTTP streaming for live market feeds. TradeStation supports advanced order\n  types including bracket, OCO, OSO, and multi-leg options orders with OAuth2\n  authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Brokerage\n  - Cryptocurrency\n  - Finance\n  - Futures\n  - Market Data\n  - Options\n  - Stocks\n  - Trading\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: tradestation:tradestation-api\n    name: TradeStation API\n    description: >-\n      The TradeStation REST API provides brokerage and market data services\n      for building trading applications. Covers account management, order\n      placement and execution, real-time and historical market data, option\n      chains, symbol information, and reference data. Supports stocks, options,\n      futures, and cryptocurrency with OAuth2 authentication.\n    humanURL: https://api.tradestation.com/docs/\n    baseURL: https://api.tradestation.com\n    tags:\n      - Accounts\n      - Brokerage\n      - Cryptocurrency\n      - Market Data\n      - Options\n      - Order Execution\n      - Stocks\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://api.tradestation.com/docs/\n      - type: OpenAPI\n        url: openapi/tradestation-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/tradestation-streaming-asyncapi.yml\n      -\
  \ type: JSONSchema\n        url: json-schema/tradestation-order-schema.json\n      - type: JSONStructure\n        url: json-structure/tradestation-order-structure.json\n      - type: JSONLd\n        url: json-ld/tradestation-context.jsonld\n      - type: SpectralRules\n        url: rules/tradestation-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/trading-and-market-data.yaml\n      - type: Vocabulary\n        url: vocabulary/tradestation-vocabulary.yml\n      - type: GitHubOrg\n        url: https://github.com/tradestation\n      - type: APISpecification\n        url: https://tradestation.github.io/api-docs/\n  - aid: tradestation:tradestation-streaming\n    name: TradeStation Streaming API\n    description: >-\n      The TradeStation Streaming API provides real-time HTTP streaming\n      endpoints using chunked transfer encoding with newline-delimited JSON\n      for market data and brokerage events. Streams deliver live quote\n      updates, bar chart data, and\
  \ order status changes with minimal latency.\n    humanURL: https://api.tradestation.com/docs/\n    baseURL: https://api.tradestation.com\n    tags:\n      - Bar Charts\n      - Cryptocurrency\n      - Market Data\n      - Options\n      - Order Status\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://api.tradestation.com/docs/\n      - type: AsyncAPI\n        url: asyncapi/tradestation-streaming-asyncapi.yml\ncommon:\n  - type: Website\n    url: https://www.tradestation.com\n  - type: Developer\n    url: https://developer.tradestation.com\n  - type: Documentation\n    url: https://api.tradestation.com/docs/\n  - type: Authentication\n    url: https://api.tradestation.com/docs/fundamentals/authentication/\n  - type: GitHub\n    url: https://github.com/tradestation\n  - type: RateLimiting\n    url: https://api.tradestation.com/docs/fundamentals/rate-limiting/\n  - type: TermsOfService\n    url: https://www.tradestation.com/important-information/\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/apis.yml
tags:
- Brokerage
- Cryptocurrency
- Finance
- Futures
- Market Data
- Options
- Stocks
- Trading
url: https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/apis.yml
use_cases: []
---
