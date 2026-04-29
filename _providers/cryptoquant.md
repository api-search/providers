---
api_count: 1
api_specs:
- filename: cryptoquant-openapi.yml
  format: yaml
  label: CryptoQuant API
  slug: cryptoquant-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/openapi/cryptoquant-openapi.yml
apis:
- description: 'The CryptoQuant API exposes on-chain, exchange flow, market, miner, and stablecoin metrics for major cryptocurrencies via a versioned REST interface. Authentication uses an API key passed as a bearer '
  name: CryptoQuant API
  slug: cryptoquant-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://cryptoquant.com/
- title: ''
  type: Documentation
  url: https://cryptoquant.com/docs
- title: ''
  type: Pricing
  url: https://cryptoquant.com/products/api
- title: ''
  type: OpenAPI
  url: openapi/cryptoquant-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/cryptoquant-timeseries-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/cryptoquant-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/cryptoquant-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/cryptoquant-vocabulary.yml
created: '2025-02-12'
description: CryptoQuant is a blockchain data analytics platform providing real-time and historical on-chain, exchange flow, miner, derivatives, and stablecoin metrics for Bitcoin, Ethereum, and other major cryptocurrencies. The API delivers time-series data used by traders, funds, and researchers to gauge market sentiment and capital flows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Cryptoquant Context
  property_count: 8
  slug: cryptoquant-context
layout: provider
modified: '2026-04-28'
name: CryptoQuant
rules:
- name: CryptoQuant API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: cryptoquant-rules
skills: []
slug: cryptoquant
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cryptoquant\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/apis.yml\nx-type: company\nname: CryptoQuant\ndescription: >-\n  CryptoQuant is a blockchain data analytics platform providing real-time and\n  historical on-chain, exchange flow, miner, derivatives, and stablecoin\n  metrics for Bitcoin, Ethereum, and other major cryptocurrencies. The API\n  delivers time-series data used by traders, funds, and researchers to gauge\n  market sentiment and capital flows.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Blockchain\n  - Cryptocurrency\n  - On-Chain Analytics\n  - Market Data\n  - Derivatives\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ncreated: '2025-02-12'\nmodified: '2026-04-28'\napis:\n  - aid: cryptoquant:cryptoquant-api\n    name: CryptoQuant API\n    description: >-\n      The CryptoQuant API exposes on-chain, exchange flow, market, miner,\
  \ and\n      stablecoin metrics for major cryptocurrencies via a versioned REST\n      interface. Authentication uses an API key passed as a bearer token.\n    humanURL: https://cryptoquant.com/docs\n    baseURL: https://api.cryptoquant.com/v1\n    tags:\n      - On-Chain Analytics\n      - Exchange Flows\n      - Miner Flows\n      - Market Data\n      - Stablecoins\n    properties:\n      - url: https://cryptoquant.com/docs\n        type: Documentation\n      - url: https://cryptoquant.com/products/api\n        type: Pricing\n      - url: openapi/cryptoquant-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cryptoquant-timeseries-schema.json\n        type: JSONSchema\n      - url: json-ld/cryptoquant-context.jsonld\n        type: JSONLDContext\nfeatures:\n  - name: Exchange Flows\n    description: Inflow, outflow, and reserve metrics for major exchanges (Binance, Coinbase, Kraken, etc.).\n  - name: Miner Flows\n    description: Miner reserve, outflow, and position index for\
  \ Bitcoin mining pools.\n  - name: Network Indicators\n    description: SOPR, MVRV, NVT, and other on-chain valuation indicators.\n  - name: Market and Derivatives\n    description: OHLCV, open interest, funding rate, and basis metrics.\n  - name: Stablecoin Metrics\n    description: Reserve, supply, and SSR metrics for USDT, USDC, DAI, BUSD.\n  - name: Multiple Resolutions\n    description: Time-series available at min, hour, day, and block-level windows.\n  - name: Bearer Token Auth\n    description: API key authentication via Authorization bearer header.\nuseCases:\n  - name: Trading Signals\n    description: Quantitative traders use exchange flow and SOPR data as inputs to trading models.\n  - name: Risk Management\n    description: Funds monitor exchange reserve trends to assess sell-pressure risk.\n  - name: Miner Behavior Analysis\n    description: Researchers track miner outflow and reserve trends to anticipate sell-side pressure.\n  - name: Macro Crypto Research\n    description:\
  \ Analysts publish reports based on stablecoin and on-chain valuation indicators.\n  - name: Compliance and Surveillance\n    description: Surveillance teams detect anomalies and suspicious flow patterns across exchanges.\ncommon:\n  - url: https://cryptoquant.com/\n    name: CryptoQuant Website\n    type: Website\n  - url: https://cryptoquant.com/docs\n    name: API Documentation\n    type: Documentation\n  - url: https://cryptoquant.com/products/api\n    name: API Plans\n    type: Pricing\n  - url: openapi/cryptoquant-openapi.yml\n    type: OpenAPI\n  - url: json-schema/cryptoquant-timeseries-schema.json\n    type: JSONSchema\n  - url: json-ld/cryptoquant-context.jsonld\n    type: JSONLDContext\n  - url: rules/cryptoquant-rules.yml\n    type: SpectralRules\n  - url: vocabulary/cryptoquant-vocabulary.yml\n    type: Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/apis.yml
tags:
- Blockchain
- Cryptocurrency
- On-Chain Analytics
- Market Data
- Derivatives
url: https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/apis.yml
use_cases: []
---
