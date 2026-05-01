---
api_count: 10
api_specs:
- filename: eodhd-eod-historical-data-openapi.yml
  format: yaml
  label: EODHD End-Of-Day Historical Data API
  slug: eod-historical-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/eodhd/refs/heads/main/openapi/eodhd-eod-historical-data-openapi.yml
apis:
- description: Returns end-of-day historical OHLCV data for stocks, ETFs, funds, indices, and currencies across global exchanges. Supports daily, weekly, and monthly periods with both raw and split/dividend-adjusted
  name: EODHD End-Of-Day Historical Data API
  slug: eod-historical-data-api
- description: Provides intraday historical OHLCV data at 1-minute, 5-minute, and 1-hour intervals for US stocks and other supported markets, with multi-year lookbacks depending on the resolution.
  name: EODHD Intraday Historical Data API
  slug: intraday-historical-data-api
- description: Returns live or 15-20 minute delayed stock quotes including last price, change, volume, and bid/ask data for stocks, ETFs, indices, and forex pairs across global exchanges.
  name: EODHD Live (Delayed) Stock Prices API
  slug: live-prices-api
- description: Streams real-time trade and quote updates over WebSockets for US stocks, forex, and cryptocurrencies, allowing low-latency consumption of live market data.
  name: EODHD WebSockets Real-Time API
  slug: websockets-api
- description: Provides company fundamentals including general info, financial statements (income statement, balance sheet, cash flow), earnings, valuation ratios, ETF holdings, and mutual fund details.
  name: EODHD Fundamental Data API
  slug: fundamental-data-api
- description: Returns US stock options chain data with strikes, expirations, bid/ask, open interest, implied volatility, and Greeks (delta, gamma, theta, vega).
  name: EODHD Stock Options API
  slug: options-data-api
- description: Computes common technical indicators server-side, including SMA, EMA, RSI, MACD, Bollinger Bands, ATR, and stochastic oscillators, on top of the EODHD historical price database.
  name: EODHD Technical Indicators API
  slug: technical-indicators-api
- description: Provides a global economic calendar of macroeconomic releases including country, event name, scheduled time, prior, forecast, and actual values.
  name: EODHD Economic Events Calendar API
  slug: economic-events-api
- description: Delivers financial news articles tagged by ticker symbol with sentiment scoring (positive, negative, neutral) for use in research, trading signals, and news-driven workflows.
  name: EODHD Financial News and Sentiment API
  slug: news-sentiment-api
- description: Lists supported exchanges and instruments with metadata including ticker, exchange code, name, type, and identifier mappings (CUSIP, ISIN, FIGI) to support symbol lookup and reference data workflows.
  name: EODHD Exchanges and Symbols API
  slug: exchanges-and-tickers-api
common:
- title: ''
  type: Website
  url: https://eodhd.com/
- title: ''
  type: Documentation
  url: https://eodhd.com/financial-apis/
- title: ''
  type: Pricing
  url: https://eodhd.com/pricing
- title: ''
  type: Marketplace
  url: https://eodhd.com/marketplace
- title: ''
  type: Blog
  url: https://eodhd.com/financial-apis-blog/
- title: ''
  type: Forums
  url: https://forum.eodhd.com/
- title: ''
  type: Affiliate
  url: https://eodhd.com/financial-apis/eodhd-affiliate-program
- title: ''
  type: PrivacyPolicy
  url: https://eodhd.com/financial-apis/privacy-policy
- title: ''
  type: TermsOfService
  url: https://eodhd.com/financial-apis/terms-conditions
created: '2025-02-24'
description: Access historical end-of-day stock prices, intraday data, US stock options, and real-time prices with free and advanced plans. EODHD provides financial data for 150,000+ tickers, including stocks, ETFs, funds, and currencies worldwide.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: EODHD
skills: []
slug: eodhd
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: eodhd\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/eodhd/refs/heads/main/apis.yml\nname: EODHD\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Financial\n  - Market Data\n  - Stock Options\n  - Stocks\naccess: 3rd-Party\ncreated: '2025-02-24'\nmodified: '2026-04-28'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  Access historical end-of-day stock prices, intraday data, US stock options,\n  and real-time prices with free and advanced plans. EODHD provides financial\n  data for 150,000+ tickers, including stocks, ETFs, funds, and currencies\n  worldwide.\napis:\n  - aid: eodhd:eod-historical-data-api\n    name: EODHD End-Of-Day Historical Data API\n    tags:\n      - End Of Day\n      - Financial\n      - Historical Data\n      - Stocks\n    humanURL: https://eodhd.com/financial-apis/api-for-historical-data-and-volumes\n    properties:\n      - url: openapi/eodhd-eod-historical-data-openapi.yml\n\
  \        type: OpenAPI\n      - url: https://eodhd.com/financial-apis/api-for-historical-data-and-volumes\n        type: Documentation\n    description: >-\n      Returns end-of-day historical OHLCV data for stocks, ETFs, funds, indices,\n      and currencies across global exchanges. Supports daily, weekly, and\n      monthly periods with both raw and split/dividend-adjusted close prices.\n  - aid: eodhd:intraday-historical-data-api\n    name: EODHD Intraday Historical Data API\n    tags:\n      - Financial\n      - Historical Data\n      - Intraday\n      - Stocks\n    humanURL: https://eodhd.com/financial-apis/intraday-historical-data-api\n    properties:\n      - url: https://eodhd.com/financial-apis/intraday-historical-data-api\n        type: Documentation\n    description: >-\n      Provides intraday historical OHLCV data at 1-minute, 5-minute, and 1-hour\n      intervals for US stocks and other supported markets, with multi-year\n      lookbacks depending on the resolution.\n  -\
  \ aid: eodhd:live-prices-api\n    name: EODHD Live (Delayed) Stock Prices API\n    tags:\n      - Financial\n      - Live Data\n      - Real Time\n      - Stocks\n    humanURL: https://eodhd.com/financial-apis/live-realtime-stocks-api\n    properties:\n      - url: https://eodhd.com/financial-apis/live-realtime-stocks-api\n        type: Documentation\n    description: >-\n      Returns live or 15-20 minute delayed stock quotes including last price,\n      change, volume, and bid/ask data for stocks, ETFs, indices, and forex\n      pairs across global exchanges.\n  - aid: eodhd:websockets-api\n    name: EODHD WebSockets Real-Time API\n    tags:\n      - Financial\n      - Real Time\n      - Streaming\n      - WebSockets\n    humanURL: https://eodhd.com/financial-apis/new-real-time-data-api-websockets\n    properties:\n      - url: https://eodhd.com/financial-apis/new-real-time-data-api-websockets\n        type: Documentation\n    description: >-\n      Streams real-time trade and quote\
  \ updates over WebSockets for US stocks,\n      forex, and cryptocurrencies, allowing low-latency consumption of live\n      market data.\n  - aid: eodhd:fundamental-data-api\n    name: EODHD Fundamental Data API\n    tags:\n      - Financial\n      - Fundamentals\n      - Stocks\n    humanURL: https://eodhd.com/financial-apis/stock-etfs-fundamental-data-feeds\n    properties:\n      - url: https://eodhd.com/financial-apis/stock-etfs-fundamental-data-feeds\n        type: Documentation\n    description: >-\n      Provides company fundamentals including general info, financial\n      statements (income statement, balance sheet, cash flow), earnings,\n      valuation ratios, ETF holdings, and mutual fund details.\n  - aid: eodhd:options-data-api\n    name: EODHD Stock Options API\n    tags:\n      - Derivatives\n      - Financial\n      - Options\n    humanURL: https://eodhd.com/financial-apis/stock-options-data\n    properties:\n      - url: https://eodhd.com/financial-apis/stock-options-data\n\
  \        type: Documentation\n    description: >-\n      Returns US stock options chain data with strikes, expirations, bid/ask,\n      open interest, implied volatility, and Greeks (delta, gamma, theta, vega).\n  - aid: eodhd:technical-indicators-api\n    name: EODHD Technical Indicators API\n    tags:\n      - Analytics\n      - Financial\n      - Technical Indicators\n    humanURL: https://eodhd.com/financial-apis/technical-indicators-api\n    properties:\n      - url: https://eodhd.com/financial-apis/technical-indicators-api\n        type: Documentation\n    description: >-\n      Computes common technical indicators server-side, including SMA, EMA,\n      RSI, MACD, Bollinger Bands, ATR, and stochastic oscillators, on top of\n      the EODHD historical price database.\n  - aid: eodhd:economic-events-api\n    name: EODHD Economic Events Calendar API\n    tags:\n      - Calendar\n      - Economic Data\n      - Financial\n    humanURL: https://eodhd.com/financial-apis/economic-events-data-api\n\
  \    properties:\n      - url: https://eodhd.com/financial-apis/economic-events-data-api\n        type: Documentation\n    description: >-\n      Provides a global economic calendar of macroeconomic releases including\n      country, event name, scheduled time, prior, forecast, and actual values.\n  - aid: eodhd:news-sentiment-api\n    name: EODHD Financial News and Sentiment API\n    tags:\n      - Financial\n      - News\n      - Sentiment\n    humanURL: https://eodhd.com/financial-apis/stock-market-financial-news-api\n    properties:\n      - url: https://eodhd.com/financial-apis/stock-market-financial-news-api\n        type: Documentation\n    description: >-\n      Delivers financial news articles tagged by ticker symbol with sentiment\n      scoring (positive, negative, neutral) for use in research, trading\n      signals, and news-driven workflows.\n  - aid: eodhd:exchanges-and-tickers-api\n    name: EODHD Exchanges and Symbols API\n    tags:\n      - Exchanges\n      - Financial\n\
  \      - Reference Data\n      - Symbols\n    humanURL: https://eodhd.com/financial-apis/list-supported-exchanges\n    properties:\n      - url: https://eodhd.com/financial-apis/list-supported-exchanges\n        type: Documentation\n    description: >-\n      Lists supported exchanges and instruments with metadata including ticker,\n      exchange code, name, type, and identifier mappings (CUSIP, ISIN, FIGI)\n      to support symbol lookup and reference data workflows.\ncommon:\n  - url: https://eodhd.com/\n    name: Website\n    type: Website\n  - url: https://eodhd.com/financial-apis/\n    name: API Documentation\n    type: Documentation\n  - url: https://eodhd.com/pricing\n    name: Pricing\n    type: Pricing\n  - url: https://eodhd.com/marketplace\n    name: Marketplace for the Global Financial Data APIs\n    type: Marketplace\n  - url: https://eodhd.com/financial-apis-blog/\n    name: Financial Blog | EODHD APIs\n    type: Blog\n  - url: https://forum.eodhd.com/\n    name: Financial\
  \ Data Forum\n    type: Forums\n  - url: https://eodhd.com/financial-apis/eodhd-affiliate-program\n    name: EODHD Affiliate Program\n    type: Affiliate\n  - url: https://eodhd.com/financial-apis/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://eodhd.com/financial-apis/terms-conditions\n    name: Terms and Conditions\n    type: TermsOfService\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/eodhd/refs/heads/main/apis.yml
tags:
- Financial
- Market Data
- Stock Options
- Stocks
url: https://raw.githubusercontent.com/api-evangelist/eodhd/refs/heads/main/apis.yml
use_cases: []
---
