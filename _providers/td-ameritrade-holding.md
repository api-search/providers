---
api_count: 1
api_specs:
- filename: td-ameritrade-accounts-trading-openapi.yml
  format: yaml
  label: TD Ameritrade Accounts and Trading API
  slug: accounts-and-trading
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/openapi/td-ameritrade-accounts-trading-openapi.yml
apis:
- description: The TD Ameritrade Accounts and Trading API provided programmatic access to account information, order management, watchlists, market data, and trading operations. Supported OAuth 2.0 authentication. D
  name: TD Ameritrade Accounts and Trading API
  slug: accounts-and-trading
capabilities:
- description: Workflow capability for automated brokerage trading and portfolio management using the TD Ameritrade API (historical - deprecated May 2024). Enables programmatic trading, account monitoring, market da
  name: TD Ameritrade Trading and Portfolio Management
  slug: trading-and-portfolio
common:
- title: ''
  type: Website
  url: https://www.tdameritrade.com
- title: ''
  type: Documentation
  url: https://developer.tdameritrade.com/
- title: ''
  type: Documentation
  url: https://developer.schwab.com
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/openapi/td-ameritrade-accounts-trading-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/vocabulary/td-ameritrade-vocabulary.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/json-schema/td-ameritrade-order-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/json-ld/td-ameritrade-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/rules/td-ameritrade-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/capabilities/trading-and-portfolio.yaml
- title: ''
  type: Authentication
  url: https://api.tdameritrade.com/v1/oauth2/token
created: '2026-03-24'
description: TD Ameritrade Holding Corporation was a brokerage firm that provided online brokerage and related services for individual investors. The company was acquired by Charles Schwab in 2020 and the TD Ameritrade platform was fully migrated to Charles Schwab in May 2024. TD Ameritrade offered a developer API for programmatic access to trading, account management, market data, and order management capabilities. The successor API is now the Charles Schwab Trader API at developer.schwab.com.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Td Ameritrade Context
  property_count: 0
  slug: td-ameritrade-context
layout: provider
modified: '2026-05-03'
name: TD Ameritrade Holding
rules:
- name: TD Ameritrade Holding API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 7
  slug: td-ameritrade-rules
skills: []
slug: td-ameritrade-holding
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: td-ameritrade-holding\nname: TD Ameritrade Holding\ndescription: >-\n  TD Ameritrade Holding Corporation was a brokerage firm that provided online brokerage\n  and related services for individual investors. The company was acquired by Charles\n  Schwab in 2020 and the TD Ameritrade platform was fully migrated to Charles Schwab\n  in May 2024. TD Ameritrade offered a developer API for programmatic access to trading,\n  account management, market data, and order management capabilities. The successor\n  API is now the Charles Schwab Trader API at developer.schwab.com.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Finance\n  - Brokerage\n  - Trading\n  - Market Data\n  - Investment\n  - Charles Schwab\n  - Deprecated\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: td-ameritrade-holding:accounts-and-trading\n    name: TD Ameritrade Accounts and Trading API\n    description: >-\n      The TD Ameritrade Accounts and Trading API provided programmatic access to account\n      information, order management, watchlists, market data, and trading operations.\n      Supported OAuth 2.0 authentication. Deprecated following the Charles Schwab\n      acquisition with full migration completed in May 2024. The successor API is the\n      Charles Schwab Trader API at developer.schwab.com.\n    humanURL: https://developer.tdameritrade.com/\n    baseURL: https://api.tdameritrade.com/v1\n    tags:\n      - Accounts\n      - Trading\n      - Orders\n      - Market Data\n      - Watchlists\n    properties:\n      - type: Documentation\n        url: https://developer.tdameritrade.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/openapi/td-ameritrade-accounts-trading-openapi.yml\n\
  \    contact:\n      - FN: Charles Schwab (Successor)\n        url: https://developer.schwab.com\ncommon:\n  - type: Website\n    url: https://www.tdameritrade.com\n  - type: Documentation\n    name: TD Ameritrade Developer Portal (Archived)\n    description: Original developer portal, now redirecting to Schwab.\n    url: https://developer.tdameritrade.com/\n  - type: Documentation\n    name: Charles Schwab Trader API (Successor)\n    description: The successor API following TD Ameritrade acquisition by Charles Schwab.\n    url: https://developer.schwab.com\n  - type: OpenAPI\n    name: TD Ameritrade Accounts and Trading OpenAPI Specification\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/openapi/td-ameritrade-accounts-trading-openapi.yml\n  - type: Vocabulary\n    name: TD Ameritrade Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/vocabulary/td-ameritrade-vocabulary.yml\n\
  \  - type: JSONSchema\n    name: Order Schema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/json-schema/td-ameritrade-order-schema.json\n  - type: JSONLDContext\n    name: TD Ameritrade JSON-LD Context\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/json-ld/td-ameritrade-context.jsonld\n  - type: SpectralRules\n    name: TD Ameritrade Spectral Rules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/rules/td-ameritrade-rules.yml\n  - type: NaftikoCapabilities\n    name: TD Ameritrade Trading and Portfolio Capability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/capabilities/trading-and-portfolio.yaml\n  - type: Authentication\n    name: OAuth 2.0\n    description: TD Ameritrade API used OAuth 2.0 token-based authentication.\n    url: https://api.tdameritrade.com/v1/oauth2/token\n\
  features:\n  - name: Account Management\n    description: Access account balances, positions, and account-level information.\n  - name: Order Management\n    description: Place, modify, cancel, and retrieve orders for brokerage accounts.\n  - name: Watchlist Management\n    description: Create, update, and manage stock and security watchlists.\n  - name: Market Data\n    description: Access real-time and historical market data, quotes, and price history.\n  - name: Options Chain\n    description: Retrieve option chains for optionable symbols.\n  - name: Instrument Search\n    description: Search for securities by symbol, CUSIP, or fundamental data.\n  - name: Transaction History\n    description: Access account transaction history and activity.\n  - name: Market Hours\n    description: Query market hours and status for different exchanges.\n  - name: Market Movers\n    description: Retrieve top movers by value or percentage for market indices.\n  - name: OAuth 2.0 Authentication\n    description:\
  \ Secure API access via OAuth 2.0 with offline access for refresh tokens.\nuseCases:\n  - name: Automated Trading\n    description: Build automated trading systems using order placement and market data APIs.\n  - name: Portfolio Monitoring\n    description: Track account balances, positions, and performance programmatically.\n  - name: Market Data Integration\n    description: Pull quotes and price history into custom analytics platforms.\n  - name: Options Trading\n    description: Access option chains for options strategy automation.\n  - name: Watchlist Automation\n    description: Programmatically manage and update stock watchlists.\nintegrations:\n  - name: Charles Schwab Trader API\n    description: Successor API following acquisition and migration completion in May 2024.\n    url: https://developer.schwab.com\nsolutions:\n  - name: Retail Brokerage Automation\n    description: Enabled retail investors to automate trading and account management workflows.\n  - name: Algorithmic Trading\n\
  \    description: Supported quantitative and algorithmic trading through market data and order APIs.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/apis.yml
tags:
- Finance
- Brokerage
- Trading
- Market Data
- Investment
- Charles Schwab
- Deprecated
url: https://raw.githubusercontent.com/api-evangelist/td-ameritrade-holding/refs/heads/main/apis.yml
use_cases: []
---
