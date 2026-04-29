---
api_count: 3
api_specs:
- filename: coingecko-crypto-market-data-api-openapi.yml
  format: yaml
  label: CoinGecko Crypto Market Data API
  slug: crypto-market-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/openapi/coingecko-crypto-market-data-api-openapi.yml
- filename: coingecko-pro-api-openapi.yml
  format: yaml
  label: CoinGecko Pro API
  slug: pro-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/openapi/coingecko-pro-api-openapi.yml
- filename: coingecko-onchain-dex-api-openapi.yml
  format: yaml
  label: CoinGecko Onchain DEX API
  slug: onchain-dex-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/openapi/coingecko-onchain-dex-api-openapi.yml
apis:
- description: The CoinGecko Crypto Market Data API provides comprehensive and reliable cryptocurrency price and market data through RESTful JSON endpoints. It offers over 70 endpoints covering real-time and histori
  name: CoinGecko Crypto Market Data API
  slug: crypto-market-data-api
- description: 'The CoinGecko Pro API provides the same comprehensive cryptocurrency market data as the standard API but with enhanced performance, higher rate limits of up to 1,000 calls per minute, and faster data '
  name: CoinGecko Pro API
  slug: pro-api
- description: The CoinGecko Onchain DEX API, powered by GeckoTerminal, provides access to real-time decentralized exchange data across over 250 blockchain networks, 1,800 DEXes, and 30 million tokens. It offers mor
  name: CoinGecko Onchain DEX API
  slug: onchain-dex-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://www.coingecko.com/en/api
- title: ''
  type: Documentation
  url: https://docs.coingecko.com
- title: ''
  type: Pricing
  url: https://www.coingecko.com/en/api/pricing
- title: ''
  type: Website
  url: https://www.coingecko.com
- title: ''
  type: Blog
  url: https://blog.coingecko.com
- title: ''
  type: Support
  url: https://support.coingecko.com
- title: ''
  type: Login
  url: https://www.coingecko.com/en/developers/dashboard
- title: ''
  type: Status
  url: https://status.coingecko.com/
- title: ''
  type: Terms of Service
  url: https://www.coingecko.com/en/terms
- title: ''
  type: Privacy Policy
  url: https://www.coingecko.com/en/privacy
- title: ''
  type: JSONSchema
  url: json-schema/coingecko-coin-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/coingecko-pool-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/coingecko-context.jsonld
- title: ''
  type: Spectral Ruleset
  url: rules/coingecko-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/coingecko-capabilities.yml
created: '2026-03-20'
description: 'CoinGecko is a cryptocurrency data aggregator providing market data, analytics, and information on thousands of crypto assets, exchanges, derivatives, NFTs, and on-chain decentralized markets worldwide. The CoinGecko Developer Platform exposes three primary APIs: the public Crypto Market Data API (Demo plan and free tier), the commercial Pro API for higher rate limits and exclusive endpoints, and the Onchain DEX API powered by GeckoTerminal for decentralized exchange data across 250+ networks. Authentication uses x-cg-demo-api-key (Demo) or x-cg-pro-api-key (Pro) headers, with rate limits ranging from 30 calls per minute on Demo to 1,000 calls per minute on top Pro tiers.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Coingecko Context
  property_count: 7
  slug: coingecko-context
layout: provider
modified: '2026-04-28'
name: CoinGecko
rules:
- name: CoinGecko API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 5
  slug: coingecko-rules
skills: []
slug: coingecko
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coingecko\nurl: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/apis.yml\nname: CoinGecko\ntags:\n  - Aggregator\n  - Blockchain\n  - Cryptocurrency\n  - Decentralized Exchanges\n  - DeFi\n  - DEX\n  - Exchanges\n  - Liquidity Pools\n  - Market Data\n  - NFTs\n  - Onchain Data\n  - Prices\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  CoinGecko is a cryptocurrency data aggregator providing market data,\n  analytics, and information on thousands of crypto assets, exchanges,\n  derivatives, NFTs, and on-chain decentralized markets worldwide. The\n  CoinGecko Developer Platform exposes three primary APIs: the public Crypto\n  Market Data API (Demo plan and free tier), the commercial Pro API for higher\n  rate limits and exclusive endpoints, and the Onchain DEX API powered by\n\
  \  GeckoTerminal for decentralized exchange data across 250+ networks.\n  Authentication uses x-cg-demo-api-key (Demo) or x-cg-pro-api-key (Pro)\n  headers, with rate limits ranging from 30 calls per minute on Demo to 1,000\n  calls per minute on top Pro tiers.\napis:\n  - aid: coingecko:crypto-market-data-api\n    name: CoinGecko Crypto Market Data API\n    tags:\n      - Blockchain\n      - Cryptocurrency\n      - Exchanges\n      - Market Data\n      - NFTs\n      - Prices\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.coingecko.com/api/v3\n    humanURL: https://docs.coingecko.com\n    properties:\n      - url: https://docs.coingecko.com\n        type: Documentation\n      - url: https://www.coingecko.com/en/api/pricing\n        type: Pricing\n      - url: https://www.coingecko.com/en/api\n        type: Landing Page\n      - type: OpenAPI\n        url: openapi/coingecko-crypto-market-data-api-openapi.yml\n    description:\
  \ >-\n      The CoinGecko Crypto Market Data API provides comprehensive and reliable\n      cryptocurrency price and market data through RESTful JSON endpoints. It\n      offers over 70 endpoints covering real-time and historical prices,\n      trading volumes, market capitalization, OHLCV data, exchange\n      information, NFT metrics, derivatives data, and public treasury holdings\n      for over 18,000 coins.\n    x-features:\n      - 70+ REST endpoints in a single normalized API\n      - Real-time and historical price feeds\n      - OHLCV chart data for charting and analysis\n      - Exchange, derivatives, and NFT metrics\n      - Public company treasury holdings\n      - Demo plan free tier with x-cg-demo-api-key auth\n    x-use-cases:\n      - Power crypto pricing widgets and tickers\n      - Backtest strategies against historical OHLCV\n      - Display NFT collection floor prices\n      - Compute portfolio valuations across many assets\n  - aid: coingecko:pro-api\n    name: CoinGecko\
  \ Pro API\n    tags:\n      - Commercial\n      - Cryptocurrency\n      - Enterprise\n      - Market Data\n      - Prices\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://pro-api.coingecko.com/api/v3\n    humanURL: https://docs.coingecko.com/reference/introduction\n    properties:\n      - url: https://docs.coingecko.com/reference/introduction\n        type: Documentation\n      - url: https://www.coingecko.com/en/api/pricing\n        type: Pricing\n      - type: OpenAPI\n        url: openapi/coingecko-pro-api-openapi.yml\n    description: >-\n      The CoinGecko Pro API provides the same comprehensive cryptocurrency\n      market data as the standard API but with enhanced performance, higher\n      rate limits of up to 1,000 calls per minute, and faster data updates\n      with prices cached every 30 seconds. It includes exclusive endpoints\n      for advanced analytics, detailed market data, and historical granularity\n    \
  \  that are not available on the free Demo plan.\n    x-features:\n      - Up to 1,000 calls per minute (top Pro tier)\n      - 30-second price cache for fresher data\n      - Exclusive endpoints (e.g., circulating supply chart, hourly OHLC)\n      - Higher historical depth than Demo\n      - Authenticated via x-cg-pro-api-key\n      - Commercial usage allowed under Pro license\n    x-use-cases:\n      - Run commercial pricing engines and trading services\n      - Power exchange and brokerage dashboards\n      - Stream high-frequency analytics into BI tools\n      - Operate research products with full historical depth\n  - aid: coingecko:onchain-dex-api\n    name: CoinGecko Onchain DEX API\n    tags:\n      - Blockchain\n      - Decentralized Exchanges\n      - DeFi\n      - DEX\n      - Liquidity Pools\n      - Onchain Data\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.coingecko.com/api/v3/onchain\n    humanURL: https://www.coingecko.com/en/api/dex\n\
  \    properties:\n      - url: https://docs.coingecko.com/reference/endpoint-overview\n        type: Documentation\n      - url: https://www.coingecko.com/en/api/dex\n        type: Landing Page\n      - type: OpenAPI\n        url: openapi/coingecko-onchain-dex-api-openapi.yml\n    description: >-\n      The CoinGecko Onchain DEX API, powered by GeckoTerminal, provides access\n      to real-time decentralized exchange data across over 250 blockchain\n      networks, 1,800 DEXes, and 30 million tokens. It offers more than 20\n      endpoints for querying liquidity pools, token data by contract address,\n      OHLCV chart data, trending pools, and pool search functionality.\n    x-features:\n      - 250+ blockchain networks supported\n      - 1,800+ DEXes and 30M+ tokens\n      - Lookup tokens by contract address\n      - Trending and search endpoints for discovery\n      - Pool-level OHLCV chart data\n    x-use-cases:\n      - Track new and trending DEX pools\n      - Display on-chain prices\
  \ for long-tail tokens\n      - Analyze liquidity and volume across networks\n      - Monitor wallet exposure to DeFi pools\ncommon:\n  - type: Portal\n    url: https://www.coingecko.com/en/api\n  - type: Documentation\n    url: https://docs.coingecko.com\n  - type: Pricing\n    url: https://www.coingecko.com/en/api/pricing\n  - type: Website\n    url: https://www.coingecko.com\n  - type: Blog\n    url: https://blog.coingecko.com\n  - type: Support\n    url: https://support.coingecko.com\n  - type: Login\n    url: https://www.coingecko.com/en/developers/dashboard\n  - type: Status\n    url: https://status.coingecko.com/\n  - type: Terms of Service\n    url: https://www.coingecko.com/en/terms\n  - type: Privacy Policy\n    url: https://www.coingecko.com/en/privacy\n  - type: JSONSchema\n    url: json-schema/coingecko-coin-schema.json\n  - type: JSONSchema\n    url: json-schema/coingecko-pool-schema.json\n  - type: JSON-LD\n    url: json-ld/coingecko-context.jsonld\n  - type: Spectral Ruleset\n\
  \    url: rules/coingecko-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/coingecko-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/apis.yml
tags:
- Aggregator
- Blockchain
- Cryptocurrency
- Decentralized Exchanges
- DeFi
- DEX
- Exchanges
- Liquidity Pools
- Market Data
- NFTs
- Onchain Data
- Prices
url: https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/apis.yml
use_cases: []
---
