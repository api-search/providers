---
api_count: 7
apis:
- description: A set of JSON RESTful web service APIs that provide access to product and instrument reference data for CME Group, BrokerTec, EBS, hosted partners, and CME Group-cleared markets. Supports OAuth-secure
  name: CME Reference Data API
  slug: cme-reference-data-api
- description: Real-time market data API delivering futures and options price, volume, and open-interest information across CME Group markets. Available via REST and WebSocket on a monthly subscription basis from th
  name: Real-Time Futures and Options Data API
  slug: real-time-futures-options-api
- description: JSON-over-REST API delivering CME Term SOFR Reference Rates - the IOSCO-compliant forward-looking term Secured Overnight Financing Rate at 1-month, 3-month, 6-month, and 12-month tenors - with real-ti
  name: CME Term SOFR API
  slug: cme-term-sofr-api
- description: 'REST API exposing the data behind the CME FedWatch Tool: market-implied probabilities of FOMC rate-change decisions derived from 30-Day Fed Funds futures pricing.'
  name: CME FedWatch API
  slug: fedwatch-api
- description: REST API delivering CME-calculated option Greeks (delta, gamma, vega, theta, rho) and implied volatility surfaces for CME Group options markets. JSON payloads accessed via the Data Services self-servi
  name: Greeks and Implied Volatility API
  slug: greeks-iv-api
- description: JSON-over-REST API delivering the CME-administered EUR/USD Cross Currency Basis Index with real-time updates and full history.
  name: EUR/USD Cross Currency Basis Index API
  slug: eurusd-basis-api
- description: The CME ClearPort API enables electronic submission of bilaterally negotiated OTC trades for clearing through CME ClearPort. Used by brokers, exchanges, and trading systems to automate trade submissio
  name: CME ClearPort API
  slug: cme-clearport-api
common:
- title: ''
  type: Website
  url: https://www.cmegroup.com
- title: ''
  type: Portal
  url: https://www.cmegroup.com/market-data/market-data-api.html
- title: ''
  type: Portal
  url: https://dataservices.cmegroup.com/pages/CME-Data-Via-API
- title: ''
  type: Documentation
  url: https://cmegroupclientsite.atlassian.net/wiki/display/EPICSANDBOX
- title: ''
  type: GettingStarted
  url: https://www.cmegroup.com/tools-information/webhelp/data-services-portal/Content/Onboarding%20CME%20Group%20Cloud-Based%20Market%20Data%20APIs.html
- title: ''
  type: About
  url: https://www.cmegroup.com/markets.html
- title: ''
  type: About
  url: https://www.cmegroup.com/company/about-us.html
- title: ''
  type: Support
  url: https://www.cmegroup.com/contact-us.html
- title: ''
  type: TermsOfService
  url: https://www.cmegroup.com/disclaimer.html
- title: ''
  type: PrivacyPolicy
  url: https://www.cmegroup.com/privacy-policy.html
- title: ''
  type: Blog
  url: https://www.cmegroup.com/openmarkets.html
- title: ''
  type: X
  url: https://twitter.com/CMEGroup
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cme-group/
created: '2026-03-23'
description: CME Group is the world's largest derivatives exchange and operator of the CME, CBOT, NYMEX, and COMEX markets, offering futures and options across interest rates, equity indexes, foreign exchange, energy, agricultural products, and metals. CME Group exposes a portfolio of REST and streaming APIs through its Data Services Portal - including CME Reference Data API, Real-Time Futures and Options Data API, CME Term SOFR API, FedWatch API, Greeks and Implied Volatility API, EUR/USD Cross Currency Basis Index API, the CME ClearPort API for OTC trade submission, and iLink/MDP 3.0 connectivity to CME Globex for execution and market data.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CME Group
skills: []
slug: cme-group
solutions: []
source_filename: apis.yml
source_yaml: "aid: cme-group\nurl: https://raw.githubusercontent.com/api-evangelist/cme-group/refs/heads/main/apis.yml\nname: CME Group\nx-type: company\ntags:\n  - Capital Markets\n  - Derivatives\n  - Exchange\n  - Financial Markets\n  - Futures\n  - Market Data\n  - Options\n  - Reference Data\n  - Trading\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-23'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ndescription: >-\n  CME Group is the world's largest derivatives exchange and operator of the CME, CBOT,\n  NYMEX, and COMEX markets, offering futures and options across interest rates, equity\n  indexes, foreign exchange, energy, agricultural products, and metals. CME Group\n  exposes a portfolio of REST and streaming APIs through its Data Services Portal\n  - including CME Reference Data API, Real-Time Futures and Options Data API, CME\n  Term SOFR API, FedWatch API, Greeks and Implied Volatility\
  \ API, EUR/USD Cross\n  Currency Basis Index API, the CME ClearPort API for OTC trade submission, and\n  iLink/MDP 3.0 connectivity to CME Globex for execution and market data.\napis:\n  - aid: cme-group:cme-reference-data-api\n    name: CME Reference Data API\n    tags:\n      - Instruments\n      - OAuth\n      - Products\n      - Reference Data\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cmegroup.com/trading/market-tech-and-data-services/cme-reference-data-api.html\n    properties:\n      - url: https://www.cmegroup.com/trading/market-tech-and-data-services/cme-reference-data-api.html\n        type: Documentation\n      - url: https://cmegroupclientsite.atlassian.net/wiki/display/EPICSANDBOX/CME+Reference+Data+API+Version+3\n        type: Reference\n      - url: https://www.cmegroup.com/market-data/market-data-api.html\n        type: Portal\n    description: >-\n      A set of JSON RESTful web service\
  \ APIs that provide access to product and\n      instrument reference data for CME Group, BrokerTec, EBS, hosted partners,\n      and CME Group-cleared markets. Supports OAuth-secured access to product\n      definitions, instrument metadata, market segment information, and trading\n      hours used to power trading automation and risk systems.\n    x-features:\n      - name: Product Reference\n        description: Lookup of CME Group product definitions across asset classes.\n      - name: Instrument Reference\n        description: Detailed instrument-level data including expirations, contract specs, and tick sizes.\n      - name: Trading Hours\n        description: Authoritative trading hours and holiday calendars by venue.\n      - name: OAuth Authentication\n        description: OAuth 2.0 secured access to reference data endpoints.\n    x-useCases:\n      - name: Trading Automation\n        description: Hydrate algorithmic trading systems with current product and instrument metadata.\n\
  \      - name: Risk and Compliance\n        description: Drive risk and surveillance systems with authoritative reference data.\n      - name: Order Routing\n        description: Validate and route orders against the latest CME instrument definitions.\n  - aid: cme-group:real-time-futures-options-api\n    name: Real-Time Futures and Options Data API\n    tags:\n      - Futures\n      - Market Data\n      - Options\n      - Real-Time\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cmegroup.com/market-data/real-time-futures-and-options-data-api.html\n    properties:\n      - url: https://www.cmegroup.com/market-data/real-time-futures-and-options-data-api.html\n        type: Documentation\n      - url: https://www.cmegroup.com/market-data/market-data-api.html\n        type: Portal\n    description: >-\n      Real-time market data API delivering futures and options price, volume, and\n      open-interest information\
  \ across CME Group markets. Available via REST and\n      WebSocket on a monthly subscription basis from the CME Data Services portal.\n    x-features:\n      - name: Real-Time Quotes\n        description: Streaming real-time bid/ask, last trade, and volume.\n      - name: Options Chains\n        description: Full options chain data including strikes and expirations.\n      - name: REST + WebSocket\n        description: Choice of pull-based REST or push-based WebSocket delivery.\n    x-useCases:\n      - name: Trading Dashboards\n        description: Power proprietary trader and investor dashboards with live CME pricing.\n      - name: Algo Trading\n        description: Drive systematic strategies with real-time CME futures and options data.\n  - aid: cme-group:cme-term-sofr-api\n    name: CME Term SOFR API\n    tags:\n      - Benchmarks\n      - Interest Rates\n      - REST\n      - SOFR\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL:\
  \ https://www.cmegroup.com/market-data/cme-group-benchmark-administration/term-sofr.html\n    properties:\n      - url: https://www.cmegroup.com/market-data/cme-group-benchmark-administration/term-sofr.html\n        type: Documentation\n      - url: https://www.cmegroup.com/market-data/market-data-api.html\n        type: Portal\n    description: >-\n      JSON-over-REST API delivering CME Term SOFR Reference Rates - the IOSCO-compliant\n      forward-looking term Secured Overnight Financing Rate at 1-month, 3-month,\n      6-month, and 12-month tenors - with real-time updates and full history.\n    x-features:\n      - name: Term SOFR Tenors\n        description: 1M, 3M, 6M, and 12M Term SOFR reference rates.\n      - name: Historical Series\n        description: Full history of published Term SOFR fixings for backtesting and risk.\n    x-useCases:\n      - name: Loan Documentation\n        description: Embed Term SOFR fixings into loan and credit-agreement systems.\n      - name: Risk\
  \ Management\n        description: Drive interest-rate risk and valuation systems with the official benchmark.\n  - aid: cme-group:fedwatch-api\n    name: CME FedWatch API\n    tags:\n      - Fed Funds\n      - Market-Implied Probabilities\n      - Monetary Policy\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cmegroup.com/markets/interest-rates/cme-fedwatch-tool.html\n    properties:\n      - url: https://www.cmegroup.com/markets/interest-rates/cme-fedwatch-tool.html\n        type: Documentation\n      - url: https://www.cmegroup.com/market-data/market-data-api.html\n        type: Portal\n    description: >-\n      REST API exposing the data behind the CME FedWatch Tool: market-implied\n      probabilities of FOMC rate-change decisions derived from 30-Day Fed Funds\n      futures pricing.\n    x-features:\n      - name: FOMC Probabilities\n        description: Probabilities of rate moves at upcoming FOMC\
  \ meetings.\n      - name: Historical Probabilities\n        description: Time series of market-implied probabilities across meeting dates.\n    x-useCases:\n      - name: Macro Research\n        description: Embed Fed Funds expectations into research and macro newsletters.\n      - name: Risk Hedging\n        description: Inform interest-rate hedging programs with market-implied policy paths.\n  - aid: cme-group:greeks-iv-api\n    name: Greeks and Implied Volatility API\n    tags:\n      - Greeks\n      - Implied Volatility\n      - Options\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cmegroup.com/market-data/market-data-api.html\n    properties:\n      - url: https://www.cmegroup.com/market-data/market-data-api.html\n        type: Documentation\n    description: >-\n      REST API delivering CME-calculated option Greeks (delta, gamma, vega, theta,\n      rho) and implied volatility surfaces for CME Group\
  \ options markets. JSON\n      payloads accessed via the Data Services self-service API portal.\n    x-features:\n      - name: Greeks\n        description: Delta, gamma, vega, theta, and rho per option.\n      - name: Implied Volatility\n        description: Implied volatility per strike and expiry.\n    x-useCases:\n      - name: Option Pricing\n        description: Power option pricing and risk systems with CME-calculated Greeks.\n      - name: Risk Distribution\n        description: Distribute volatility-surface data into trading and analytics systems.\n  - aid: cme-group:eurusd-basis-api\n    name: EUR/USD Cross Currency Basis Index API\n    tags:\n      - FX\n      - Index\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cmegroup.com/market-data/market-data-api.html\n    properties:\n      - url: https://www.cmegroup.com/market-data/market-data-api.html\n        type: Documentation\n    description: >-\n\
  \      JSON-over-REST API delivering the CME-administered EUR/USD Cross Currency\n      Basis Index with real-time updates and full history.\n    x-features:\n      - name: Real-Time Index\n        description: Real-time EUR/USD cross-currency basis index values.\n      - name: Historical Series\n        description: Full history of index values for backtesting and benchmarking.\n    x-useCases:\n      - name: Cross-Currency Hedging\n        description: Drive cross-currency basis hedging strategies with the official index.\n  - aid: cme-group:cme-clearport-api\n    name: CME ClearPort API\n    tags:\n      - Clearing\n      - OTC\n      - Trade Submission\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cmegroup.com/clearport/clearport-api.html\n    properties:\n      - url: https://www.cmegroup.com/clearport/clearport-api.html\n        type: Documentation\n    description: >-\n      The CME ClearPort API enables electronic\
  \ submission of bilaterally negotiated\n      OTC trades for clearing through CME ClearPort. Used by brokers, exchanges,\n      and trading systems to automate trade submission and clearing workflows.\n    x-features:\n      - name: Trade Submission\n        description: Submit OTC trades for clearing programmatically.\n      - name: Block Trades\n        description: Submit block trades and EFRPs (Exchange For Related Position).\n    x-useCases:\n      - name: Broker Workflow Automation\n        description: Automate trade-capture-to-clearing workflows for OTC products.\ncommon:\n  - url: https://www.cmegroup.com\n    name: CME Group Website\n    type: Website\n  - url: https://www.cmegroup.com/market-data/market-data-api.html\n    name: Market Data APIs\n    type: Portal\n  - url: https://dataservices.cmegroup.com/pages/CME-Data-Via-API\n    name: CME Data Services Portal\n    type: Portal\n  - url: https://cmegroupclientsite.atlassian.net/wiki/display/EPICSANDBOX\n    name: CME Group\
  \ Client Systems Wiki\n    type: Documentation\n  - url: https://www.cmegroup.com/tools-information/webhelp/data-services-portal/Content/Onboarding%20CME%20Group%20Cloud-Based%20Market%20Data%20APIs.html\n    name: Onboarding CME Group Cloud-Based Market Data APIs\n    type: GettingStarted\n  - url: https://www.cmegroup.com/markets.html\n    name: Markets\n    type: About\n  - url: https://www.cmegroup.com/company/about-us.html\n    name: About CME Group\n    type: About\n  - url: https://www.cmegroup.com/contact-us.html\n    name: Contact Us\n    type: Support\n  - url: https://www.cmegroup.com/disclaimer.html\n    name: Disclaimer\n    type: TermsOfService\n  - url: https://www.cmegroup.com/privacy-policy.html\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.cmegroup.com/openmarkets.html\n    name: OpenMarkets Blog\n    type: Blog\n  - url: https://twitter.com/CMEGroup\n    name: CME Group on X\n    type: X\n  - url: https://www.linkedin.com/company/cme-group/\n\
  \    name: CME Group on LinkedIn\n    type: LinkedIn\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cme-group/refs/heads/main/apis.yml
tags:
- Capital Markets
- Derivatives
- Exchange
- Financial Markets
- Futures
- Market Data
- Options
- Reference Data
- Trading
url: https://raw.githubusercontent.com/api-evangelist/cme-group/refs/heads/main/apis.yml
use_cases: []
---
