---
api_count: 3
apis:
- description: Normalized cryptocurrency market data covering more than 350 exchanges and 28,000+ assets. Provides trades, quotes, order books, OHLCV time series, exchange rates, and derivatives metrics (funding rat
  name: CoinAPI Market Data API
  slug: market-data-api
- description: CoinAPI's Execution Management System (EMS) is a unified, multi-exchange crypto trading API that lets institutional traders, market makers, and builders place, modify, and cancel orders across many co
  name: CoinAPI EMS Trading API
  slug: ems-trading-api
- description: The Indexes API aggregates data from many exchanges to compute reference rates and benchmark indexes that summarize broad market conditions for a given asset. Useful for derivatives settlement, NAV co
  name: CoinAPI Indexes API
  slug: indexes-api
common:
- title: ''
  type: Website
  url: https://www.coinapi.io/
- title: ''
  type: Documentation
  url: https://docs.coinapi.io/
- title: ''
  type: Pricing
  url: https://www.coinapi.io/pricing
- title: ''
  type: Changelog
  url: https://docs.coinapi.io/general/changelog/
- title: ''
  type: Status
  url: https://status.coinapi.io/
- title: ''
  type: GitHub
  url: https://github.com/coinapi
- title: ''
  type: Blog
  url: https://www.coinapi.io/blog
- title: ''
  type: Privacy Policy
  url: https://www.coinapi.io/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.coinapi.io/terms-of-service
created: '2025-03-01'
description: CoinAPI is a financial data and execution platform delivering normalized real-time and historical cryptocurrency market data and trade execution across more than 350 exchanges. Its product family covers a Market Data API (REST, WebSocket, FIX, and flat-file S3 delivery) for trades, quotes, order books, OHLCV, exchange rates, and derivatives metrics; an EMS Trading API (Execution Management System) that lets users place, manage, and route orders across multiple venues through one normalized REST/WebSocket/FIX interface; and Index and Metrics APIs that aggregate cross-exchange data into reference indexes and risk metrics. FIX endpoints (fix.coinapi.io) use GeoDNS to route to the nearest datacenter for low-latency connectivity.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: CoinAPI
skills: []
slug: coinapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coinapi\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/coinapi/refs/heads/main/apis.yml\nname: CoinAPI\ntags:\n  - Blockchain\n  - Crypto Indexes\n  - Crypto Metrics\n  - Cryptocurrency\n  - EMS\n  - Execution Management\n  - FIX\n  - Market Data\n  - Order Books\n  - REST\n  - WebSocket\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  CoinAPI is a financial data and execution platform delivering normalized\n  real-time and historical cryptocurrency market data and trade execution\n  across more than 350 exchanges. Its product family covers a Market Data API\n  (REST, WebSocket, FIX, and flat-file S3 delivery) for trades, quotes, order\n  books, OHLCV, exchange rates, and derivatives metrics; an EMS Trading API\n  (Execution Management System) that lets users place, manage, and route orders\n\
  \  across multiple venues through one normalized REST/WebSocket/FIX interface;\n  and Index and Metrics APIs that aggregate cross-exchange data into reference\n  indexes and risk metrics. FIX endpoints (fix.coinapi.io) use GeoDNS to route\n  to the nearest datacenter for low-latency connectivity.\napis:\n  - aid: coinapi:market-data-api\n    name: CoinAPI Market Data API\n    tags:\n      - Crypto Metrics\n      - Cryptocurrency\n      - Exchange Rates\n      - FIX\n      - Market Data\n      - OHLCV\n      - Order Books\n      - REST\n      - WebSocket\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.coinapi.io\n    humanURL: https://www.coinapi.io/products/market-data-api\n    properties:\n      - url: https://docs.coinapi.io/market-data/\n        type: Documentation\n      - url: https://www.coinapi.io/products/market-data-api\n        type: Landing Page\n      - url: https://www.coinapi.io/products/market-data-api/faq\n\
  \        type: FAQ\n      - url: https://www.coinapi.io/products/market-data-api/docs/fix\n        type: FIX Documentation\n    description: >-\n      Normalized cryptocurrency market data covering more than 350 exchanges\n      and 28,000+ assets. Provides trades, quotes, order books, OHLCV time\n      series, exchange rates, and derivatives metrics (funding rates, mark\n      prices, liquidations, open interest, volumes). Delivered through REST\n      for historical snapshots and lookups, WebSocket and FIX for real-time\n      streaming, and S3 flat files for bulk historical analysis.\n    x-features:\n      - REST, WebSocket, and FIX delivery channels\n      - S3 flat-file delivery for historical bulk data\n      - Normalized symbol IDs across all exchanges\n      - 350+ supported exchanges and 28,000+ assets\n      - Derivatives metrics (funding, mark prices, OI, liquidations)\n      - GeoDNS-routed FIX endpoints (fix.coinapi.io)\n      - API-key authentication via X-CoinAPI-Key header\n\
  \    x-use-cases:\n      - Power trading dashboards with live order book data\n      - Backtest strategies against full historical OHLCV\n      - Compute reference rates from cross-exchange quotes\n      - Monitor derivatives exposure (funding, OI) in real time\n      - Feed BI/data lakes via daily S3 flat-file drops\n  - aid: coinapi:ems-trading-api\n    name: CoinAPI EMS Trading API\n    tags:\n      - Cryptocurrency\n      - EMS\n      - Execution Management\n      - FIX\n      - Order Management\n      - REST\n      - Trading\n      - WebSocket\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.coinapi.io/products/ems-api\n    properties:\n      - url: https://www.coinapi.io/products/ems-api\n        type: Landing Page\n      - url: https://www.coinapi.io/products/ems-api/faq\n        type: FAQ\n      - url: https://www.coinapi.io/blog/maximize-trading-potential-ems-trading-api-guide\n        type: Guide\n    description:\
  \ >-\n      CoinAPI's Execution Management System (EMS) is a unified, multi-exchange\n      crypto trading API that lets institutional traders, market makers, and\n      builders place, modify, and cancel orders across many connected venues\n      from a single normalized interface. Available over REST, WebSocket, and\n      FIX, the EMS handles credential vaulting, order routing, position and\n      balance retrieval, and execution reporting.\n    x-features:\n      - Single normalized order schema across many exchanges\n      - REST, WebSocket, and FIX support\n      - Credential vault for per-exchange API keys\n      - Real-time order, fill, and position updates\n      - Suitable for high-frequency and algorithmic strategies\n    x-use-cases:\n      - Aggregate liquidity across exchanges in a single trading client\n      - Run smart-order-routing or arbitrage strategies\n      - Centralize execution reporting and TCA across venues\n      - Bridge legacy FIX trading systems to crypto\
  \ markets\n  - aid: coinapi:indexes-api\n    name: CoinAPI Indexes API\n    tags:\n      - Aggregation\n      - Benchmark\n      - Cryptocurrency\n      - Indexes\n      - Reference Rates\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.coinapi.io/products/indexes-api\n    properties:\n      - url: https://www.coinapi.io/products/indexes-api\n        type: Landing Page\n      - url: https://docs.coinapi.io/\n        type: Documentation\n    description: >-\n      The Indexes API aggregates data from many exchanges to compute reference\n      rates and benchmark indexes that summarize broad market conditions for a\n      given asset. Useful for derivatives settlement, NAV computation, and\n      research where a single, defensible price point is required across a\n      fragmented market.\n    x-features:\n      - Cross-exchange aggregation methodology\n      - Reference rates suitable for benchmarking and settlement\n   \
  \   - Real-time and historical index values\n    x-use-cases:\n      - Settle derivatives contracts against a defensible reference rate\n      - Compute fund NAV and accounting marks\n      - Provide retail apps with a single representative price\ncommon:\n  - type: Website\n    url: https://www.coinapi.io/\n  - type: Documentation\n    url: https://docs.coinapi.io/\n  - type: Pricing\n    url: https://www.coinapi.io/pricing\n  - type: Changelog\n    url: https://docs.coinapi.io/general/changelog/\n  - type: Status\n    url: https://status.coinapi.io/\n  - type: GitHub\n    url: https://github.com/coinapi\n  - type: Blog\n    url: https://www.coinapi.io/blog\n  - type: Privacy Policy\n    url: https://www.coinapi.io/privacy-policy\n  - type: Terms of Service\n    url: https://www.coinapi.io/terms-of-service\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coinapi/refs/heads/main/apis.yml
tags:
- Blockchain
- Crypto Indexes
- Crypto Metrics
- Cryptocurrency
- EMS
- Execution Management
- FIX
- Market Data
- Order Books
- REST
- WebSocket
url: https://raw.githubusercontent.com/api-evangelist/coinapi/refs/heads/main/apis.yml
use_cases: []
---
