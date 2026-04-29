---
api_count: 2
apis:
- description: The Capital.com REST API provides programmatic access to positions, working orders, deal confirmations, account information, account switching, transaction history, preferences (leverage, hedging mode
  name: Capital.com REST API
  slug: capital-com-rest-api
- description: The Capital.com WebSocket API streams real-time market data, supporting up to 40 concurrent instruments and OHLC candlestick subscriptions for low-latency trading applications.
  name: Capital.com WebSocket API
  slug: capital-com-websocket-api
common:
- title: ''
  type: Website
  url: https://capital.com/
- title: ''
  type: Documentation
  url: https://open-api.capital.com
- title: ''
  type: Sandbox
  url: https://demo-api-capital.backend-capital.com/
- title: ''
  type: Privacy Policy
  url: https://capital.com/privacy-policy
- title: ''
  type: Terms of Service
  url: https://capital.com/terms-and-conditions
- title: ''
  type: Support
  url: https://capital.com/help
- title: ''
  type: Blog
  url: https://capital.com/news-and-analysis
created: '2024-12-03'
description: Capital.com is a European trading platform offering CFDs across shares, indices, commodities, forex, and cryptocurrencies. The Capital.com Public API provides direct access to the trading engine for automated strategies, giving programmatic control of positions, working orders, account preferences, and historical and streaming market data. A companion WebSocket API streams real-time prices and OHLC candles for up to 40 concurrent instruments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Capital.com Public API
skills: []
slug: capital-com-public-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: capital-com-public-api\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/capital-com-public-api/refs/heads/main/apis.yml\nname: Capital.com Public API\ndescription: >-\n  Capital.com is a European trading platform offering CFDs across\n  shares, indices, commodities, forex, and cryptocurrencies. The\n  Capital.com Public API provides direct access to the trading engine\n  for automated strategies, giving programmatic control of positions,\n  working orders, account preferences, and historical and streaming\n  market data. A companion WebSocket API streams real-time prices and\n  OHLC candles for up to 40 concurrent instruments.\ntype: Index\nx-type: company\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CFD\n  - Commodities\n  - Cryptocurrency\n  - Financial\n  - Forex\n  - Indices\n  - Market Data\n  - Shares\n  - Streaming\n  - Trading\n  - WebSocket\ncreated: '2024-12-03'\n\
  modified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: capital-com-public-api:capital-com-rest-api\n    name: Capital.com REST API\n    description: >-\n      The Capital.com REST API provides programmatic access to positions,\n      working orders, deal confirmations, account information, account\n      switching, transaction history, preferences (leverage, hedging mode),\n      market navigation, instrument details, historical prices, watchlists,\n      and client sentiment data. Authentication uses an API key plus login\n      credentials to create a session that returns CST and X-SECURITY-TOKEN\n      headers, which expire after 10 minutes of inactivity.\n    humanURL: https://open-api.capital.com\n    tags:\n      - CFD\n      - Financial\n      - Market Data\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://open-api.capital.com\n      - type: Base URL\n        url: https://api-capital.backend-capital.com/\n      - type: Sandbox\n\
  \        url: https://demo-api-capital.backend-capital.com/\n      - type: Authentication\n        url: https://open-api.capital.com\n    x-features:\n      - Session-based authentication with CST and X-SECURITY-TOKEN\n      - API key plus login credentials to create sessions\n      - 10-minute inactivity session expiry\n      - Position management (open, update, close)\n      - Working orders (limit and stop)\n      - Deal confirmations and execution tracking\n      - Account switching across multiple accounts\n      - Transaction and activity history\n      - Leverage and hedging-mode preferences\n      - Demo account balance adjustment for testing\n      - Market navigation hierarchy\n      - Instrument details and search\n      - Historical price data (OHLC)\n      - Client sentiment data\n      - Watchlist management\n    x-use-cases:\n      - Building automated CFD trading strategies\n      - Algorithmic execution across shares, forex, commodities, indices, and crypto\n      - Copy-trading\
  \ and signal-provider applications\n      - Portfolio and risk dashboards\n      - Backtesting against historical price data\n      - Sentiment-driven trading signals\n      - Demo-account integration testing before going live\n  - aid: capital-com-public-api:capital-com-websocket-api\n    name: Capital.com WebSocket API\n    description: >-\n      The Capital.com WebSocket API streams real-time market data,\n      supporting up to 40 concurrent instruments and OHLC candlestick\n      subscriptions for low-latency trading applications.\n    humanURL: https://open-api.capital.com\n    tags:\n      - Market Data\n      - Streaming\n      - Trading\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://open-api.capital.com\n    x-features:\n      - Real-time price streaming via WebSocket\n      - Up to 40 concurrent instrument subscriptions\n      - OHLC candlestick streaming\n      - Low-latency market data for trading systems\n    x-use-cases:\n      - Low-latency\
  \ automated trading execution\n      - Real-time market dashboards\n      - Streaming-data backtesting and replay\ncommon:\n  - type: Website\n    url: https://capital.com/\n  - type: Documentation\n    url: https://open-api.capital.com\n  - type: Sandbox\n    url: https://demo-api-capital.backend-capital.com/\n  - type: Privacy Policy\n    url: https://capital.com/privacy-policy\n  - type: Terms of Service\n    url: https://capital.com/terms-and-conditions\n  - type: Support\n    url: https://capital.com/help\n  - type: Blog\n    url: https://capital.com/news-and-analysis\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/capital-com-public-api/refs/heads/main/apis.yml
tags:
- CFD
- Commodities
- Cryptocurrency
- Financial
- Forex
- Indices
- Market Data
- Shares
- Streaming
- Trading
- WebSocket
url: https://raw.githubusercontent.com/api-evangelist/capital-com-public-api/refs/heads/main/apis.yml
use_cases: []
---
