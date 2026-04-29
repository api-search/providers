---
api_count: 6
apis:
- description: Retrieve real-time and historical OHLCV (Open, High, Low, Close, Volume) quote data for securities listed on the B3 Brazilian stock exchange. Supports bulk asset requests and returns standardized JSON
  name: brapi Quotes API
  slug: quotes-api
- description: Access structured financial statement data for Brazilian listed companies including balance sheets (BP), income statements (DRE), cash flow (DFC), and value added statements (DVA). Historical data ava
  name: brapi Fundamentals API
  slug: fundamentals-api
- description: Retrieve complete dividend and earnings distribution history for B3-listed securities, enabling portfolio yield analysis and income tracking.
  name: brapi Dividends API
  slug: dividends-api
- description: Access cryptocurrency prices denominated in Brazilian Reals (BRL), supporting investment analysis and portfolio management for Brazilian digital asset investors.
  name: brapi Cryptocurrency API
  slug: crypto-api
- description: Retrieve Brazilian Real (BRL) exchange rates against major global currencies, sourced from Banco Central do Brasil data.
  name: brapi Exchange Rates API
  slug: exchange-api
- description: Access Brazilian macroeconomic indicators including IPCA (consumer price index), IGPM (market general price index), INPC, and SELIC interest rate data published by Banco Central do Brasil.
  name: brapi Economic Indicators API
  slug: indicators-api
common:
- title: ''
  type: Website
  url: https://brapi.dev
- title: ''
  type: Documentation
  url: https://brapi.dev/docs
- title: ''
  type: Pricing
  url: https://brapi.dev/pricing
- title: ''
  type: Authentication
  url: https://brapi.dev/docs
- title: ''
  type: SignUp
  url: https://brapi.dev/register
created: '2025-03-01'
description: brapi.dev is a Brazilian financial data REST API aggregating public market data from B3 (stock exchange), CVM (securities commission), and Banco Central (central bank). It provides real-time and historical stock quotes, fundamentals, dividends, cryptocurrency prices in BRL, foreign exchange rates, and economic indicators such as IPCA, IGPM, and SELIC. With over 20,000 active developers, brapi.dev offers tiered subscription plans from free to Pro, with up to 500,000 requests per month and data updated every 5 minutes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: brapi
skills: []
slug: brapi
solutions: []
source_filename: apis.yml
source_yaml: "aid: brapi\nurl: https://raw.githubusercontent.com/api-evangelist/brapi/refs/heads/main/apis.yml\nname: brapi\ntags:\n  - Finance\n  - Brazilian Financial Data\n  - Stock Market\n  - Investments\n  - Economic Indicators\n  - Cryptocurrency\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  brapi.dev is a Brazilian financial data REST API aggregating public market data\n  from B3 (stock exchange), CVM (securities commission), and Banco Central (central\n  bank). It provides real-time and historical stock quotes, fundamentals, dividends,\n  cryptocurrency prices in BRL, foreign exchange rates, and economic indicators\n  such as IPCA, IGPM, and SELIC. With over 20,000 active developers, brapi.dev\n  offers tiered subscription plans from free to Pro, with up to 500,000 requests\n  per month and data updated every\
  \ 5 minutes.\napis:\n  - aid: brapi:quotes-api\n    name: brapi Quotes API\n    tags:\n      - Stock Quotes\n      - B3\n      - Real-Time Data\n      - Historical Data\n    humanURL: https://brapi.dev/docs\n    properties:\n      - url: https://brapi.dev/docs\n        type: Documentation\n    description: >-\n      Retrieve real-time and historical OHLCV (Open, High, Low, Close, Volume)\n      quote data for securities listed on the B3 Brazilian stock exchange. Supports\n      bulk asset requests and returns standardized JSON without web scraping.\n  - aid: brapi:fundamentals-api\n    name: brapi Fundamentals API\n    tags:\n      - Fundamentals\n      - Balance Sheet\n      - Income Statement\n      - Financial Statements\n    humanURL: https://brapi.dev/docs\n    properties:\n      - url: https://brapi.dev/docs\n        type: Documentation\n    description: >-\n      Access structured financial statement data for Brazilian listed companies\n      including balance sheets (BP), income\
  \ statements (DRE), cash flow (DFC),\n      and value added statements (DVA). Historical data available from 2009.\n  - aid: brapi:dividends-api\n    name: brapi Dividends API\n    tags:\n      - Dividends\n      - Distributions\n      - Corporate Actions\n    humanURL: https://brapi.dev/docs\n    properties:\n      - url: https://brapi.dev/docs\n        type: Documentation\n    description: >-\n      Retrieve complete dividend and earnings distribution history for B3-listed\n      securities, enabling portfolio yield analysis and income tracking.\n  - aid: brapi:crypto-api\n    name: brapi Cryptocurrency API\n    tags:\n      - Cryptocurrency\n      - BRL\n      - Digital Assets\n    humanURL: https://brapi.dev/docs\n    properties:\n      - url: https://brapi.dev/docs\n        type: Documentation\n    description: >-\n      Access cryptocurrency prices denominated in Brazilian Reals (BRL),\n      supporting investment analysis and portfolio management for Brazilian\n      digital asset\
  \ investors.\n  - aid: brapi:exchange-api\n    name: brapi Exchange Rates API\n    tags:\n      - Foreign Exchange\n      - Currency\n      - BRL\n    humanURL: https://brapi.dev/docs\n    properties:\n      - url: https://brapi.dev/docs\n        type: Documentation\n    description: >-\n      Retrieve Brazilian Real (BRL) exchange rates against major global currencies,\n      sourced from Banco Central do Brasil data.\n  - aid: brapi:indicators-api\n    name: brapi Economic Indicators API\n    tags:\n      - Inflation\n      - Interest Rates\n      - Economic Data\n      - SELIC\n    humanURL: https://brapi.dev/docs\n    properties:\n      - url: https://brapi.dev/docs\n        type: Documentation\n    description: >-\n      Access Brazilian macroeconomic indicators including IPCA (consumer price\n      index), IGPM (market general price index), INPC, and SELIC interest rate\n      data published by Banco Central do Brasil.\ncommon:\n  - type: Website\n    url: https://brapi.dev\n  -\
  \ type: Documentation\n    url: https://brapi.dev/docs\n  - type: Pricing\n    url: https://brapi.dev/pricing\n  - type: Authentication\n    url: https://brapi.dev/docs\n  - type: SignUp\n    url: https://brapi.dev/register\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/brapi/refs/heads/main/apis.yml
tags:
- Finance
- Brazilian Financial Data
- Stock Market
- Investments
- Economic Indicators
- Cryptocurrency
url: https://raw.githubusercontent.com/api-evangelist/brapi/refs/heads/main/apis.yml
use_cases: []
---
