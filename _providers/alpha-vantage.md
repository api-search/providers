---
api_count: 1
api_specs:
- filename: alpha-vantage-openapi.yml
  format: yaml
  label: Alpha Vantage Market Data API
  slug: market-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alpha-vantage/refs/heads/main/openapi/alpha-vantage-openapi.yml
apis:
- description: 'Real-time and historical stock market data API supporting time series, global quotes, symbol search, fundamental data, technical indicators, forex/crypto exchange rates, economic indicators, and news '
  name: Alpha Vantage Market Data API
  slug: market-data-api
capabilities:
- description: ''
  name: Financial Data Analytics
  slug: financial-data-analytics
common:
- title: ''
  type: Website
  url: https://www.alphavantage.co/
- title: ''
  type: Documentation
  url: https://www.alphavantage.co/documentation/
- title: ''
  type: Support
  url: https://www.alphavantage.co/support/#support
- title: ''
  type: SignUp
  url: https://www.alphavantage.co/support/#api-key
- title: ''
  type: Pricing
  url: https://www.alphavantage.co/premium/
- title: ''
  type: SpectralRules
  url: rules/alpha-vantage-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/alpha-vantage-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/financial-data-analytics.yaml
created: '2024-11-07'
description: Alpha Vantage is a financial data platform providing real-time and historical market data for stocks, options, cryptocurrencies, forex, commodities, and economic indicators. The API supports 50+ technical indicators, fundamental data, Alpha Intelligence sentiment analysis, and earnings data, all accessed through a single query endpoint using function-based routing.
features:
- description: Intraday (1min to 60min), daily, weekly, and monthly OHLCV stock price data for 20+ years of history with compact and full output modes.
  name: Stock Time Series
- description: Global quote endpoint for latest price, volume, change, and change percentage for any listed equity symbol.
  name: Real-Time Quotes
- description: 50+ technical analysis functions including SMA, EMA, MACD, RSI, Bollinger Bands, Stochastic, ADX, OBV, and more.
  name: Technical Indicators
- description: Company overview with financial ratios, earnings, income statements, balance sheets, cash flow, and ETF holdings data.
  name: Fundamental Data
- description: AI-powered news sentiment analysis for stocks, crypto, and forex with bearish/bullish scoring on recent and historical articles.
  name: Alpha Intelligence Sentiment
- description: Real-time and historical exchange rates for 100+ currencies and cryptocurrencies including intraday, daily, weekly, and monthly data.
  name: Forex and Crypto
- description: US macroeconomic data including Real GDP, CPI, unemployment, federal funds rate, treasury yields, nonfarm payroll, and retail sales.
  name: Economic Indicators
- description: Real-time options chains, put-call ratios, and volume-to-OI ratios for US equity options markets.
  name: Options Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Python integration using alpha_vantage library or direct requests to the REST API with pandas DataFrame support.
  name: Python
- description: Node.js and browser JavaScript integration for real-time market data in web applications and trading dashboards.
  name: JavaScript
- description: Google Sheets and Excel integration via Alpha Vantage spreadsheet add-ons for non-technical financial analysis.
  name: Spreadsheets
jsonld:
- class_count: 0
  name: Alpha Vantage Context
  property_count: 35
  slug: alpha-vantage-context
layout: provider
modified: '2026-04-19'
name: Alpha Vantage
rules:
- name: Alpha Vantage API Rules
  rule_count: 15
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 6
  slug: alpha-vantage-spectral-rules
skills: []
slug: alpha-vantage
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: alpha-vantage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/alpha-vantage/refs/heads/main/apis.yml\nname: Alpha Vantage\ntags:\n  - Financial\n  - Market Data\n  - Stocks\n  - Technical Indicators\n  - Economic Data\n  - Sentiment Analysis\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Alpha Vantage is a financial data platform providing real-time and historical\n  market data for stocks, options, cryptocurrencies, forex, commodities, and\n  economic indicators. The API supports 50+ technical indicators, fundamental\n  data, Alpha Intelligence sentiment analysis, and earnings data, all accessed\n  through a single query endpoint using function-based routing.\ncreated: '2024-11-07'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: alpha-vantage:market-data-api\n    name: Alpha Vantage Market Data API\n    description: >-\n      Real-time and historical stock market data\
  \ API supporting time series,\n      global quotes, symbol search, fundamental data, technical indicators,\n      forex/crypto exchange rates, economic indicators, and news sentiment\n      analysis via function-based query parameter routing.\n    humanURL: https://www.alphavantage.co/documentation/\n    baseURL: https://www.alphavantage.co\n    tags:\n      - Financial\n      - Market Data\n      - Stocks\n      - Technical Indicators\n      - Economic Data\n      - Sentiment Analysis\n    properties:\n      - type: Documentation\n        url: https://www.alphavantage.co/documentation/\n      - type: Portal\n        url: https://www.alphavantage.co/\n      - type: OpenAPI\n        url: openapi/alpha-vantage-openapi.yml\n      - type: JSONSchema\n        url: json-schema/alpha-vantage-global_quote-schema.json\n      - type: JSONStructure\n        url: json-structure/alpha-vantage-global_quote-structure.json\n      - type: JSONLD\n        url: json-ld/alpha-vantage-context.jsonld\n    \
  \  - type: Example\n        url: examples/alpha-vantage-global_quote-example.json\n      - type: NaftikoCapability\n        url: capabilities/shared/market-data.yaml\n\ncommon:\n  - url: https://www.alphavantage.co/\n    type: Website\n  - url: https://www.alphavantage.co/documentation/\n    type: Documentation\n  - url: https://www.alphavantage.co/support/#support\n    type: Support\n  - url: https://www.alphavantage.co/support/#api-key\n    type: SignUp\n  - url: https://www.alphavantage.co/premium/\n    type: Pricing\n  - url: rules/alpha-vantage-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/alpha-vantage-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/financial-data-analytics.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Stock Time Series\n        description: >-\n          Intraday (1min to 60min), daily, weekly, and monthly OHLCV stock price\n          data for 20+ years of history with compact and full output modes.\n\
  \      - name: Real-Time Quotes\n        description: >-\n          Global quote endpoint for latest price, volume, change, and change\n          percentage for any listed equity symbol.\n      - name: Technical Indicators\n        description: >-\n          50+ technical analysis functions including SMA, EMA, MACD, RSI,\n          Bollinger Bands, Stochastic, ADX, OBV, and more.\n      - name: Fundamental Data\n        description: >-\n          Company overview with financial ratios, earnings, income statements,\n          balance sheets, cash flow, and ETF holdings data.\n      - name: Alpha Intelligence Sentiment\n        description: >-\n          AI-powered news sentiment analysis for stocks, crypto, and forex with\n          bearish/bullish scoring on recent and historical articles.\n      - name: Forex and Crypto\n        description: >-\n          Real-time and historical exchange rates for 100+ currencies and\n          cryptocurrencies including intraday, daily, weekly, and\
  \ monthly data.\n      - name: Economic Indicators\n        description: >-\n          US macroeconomic data including Real GDP, CPI, unemployment, federal\n          funds rate, treasury yields, nonfarm payroll, and retail sales.\n      - name: Options Data\n        description: >-\n          Real-time options chains, put-call ratios, and volume-to-OI ratios\n          for US equity options markets.\n  - type: UseCases\n    data:\n      - name: Algorithmic Trading\n        description: >-\n          Build quantitative trading systems using real-time price feeds,\n          technical indicators, and sentiment signals from Alpha Vantage.\n      - name: Portfolio Analytics\n        description: >-\n          Analyze portfolio holdings using fundamental data, earnings estimates,\n          and historical price data for investment decision support.\n      - name: Financial Application Development\n        description: >-\n          Integrate market data into fintech apps, wealth management\
  \ platforms,\n          or stock screeners using the Alpha Vantage API.\n      - name: Macro Economic Research\n        description: >-\n          Monitor US economic indicators for investment thesis development and\n          macroeconomic trend analysis.\n  - type: Integrations\n    data:\n      - name: Python\n        description: >-\n          Python integration using alpha_vantage library or direct requests\n          to the REST API with pandas DataFrame support.\n      - name: JavaScript\n        description: >-\n          Node.js and browser JavaScript integration for real-time market data\n          in web applications and trading dashboards.\n      - name: Spreadsheets\n        description: >-\n          Google Sheets and Excel integration via Alpha Vantage spreadsheet\n          add-ons for non-technical financial analysis.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alpha-vantage/refs/heads/main/apis.yml
tags:
- Financial
- Market Data
- Stocks
- Technical Indicators
- Economic Data
- Sentiment Analysis
url: https://raw.githubusercontent.com/api-evangelist/alpha-vantage/refs/heads/main/apis.yml
use_cases:
- description: Build quantitative trading systems using real-time price feeds, technical indicators, and sentiment signals from Alpha Vantage.
  name: Algorithmic Trading
- description: Analyze portfolio holdings using fundamental data, earnings estimates, and historical price data for investment decision support.
  name: Portfolio Analytics
- description: Integrate market data into fintech apps, wealth management platforms, or stock screeners using the Alpha Vantage API.
  name: Financial Application Development
- description: Monitor US economic indicators for investment thesis development and macroeconomic trend analysis.
  name: Macro Economic Research
---
