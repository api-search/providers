---
api_count: 3
api_specs:
- filename: uniswap-trading-openapi.yaml
  format: yaml
  label: Uniswap Trading API
  slug: uniswap-trading-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/openapi/uniswap-trading-openapi.yaml
apis:
- description: The Uniswap Trading API provides REST endpoints for token swaps, bridges, liquidity management, and execution planning across 25+ blockchain networks. It supports swap quoting, gasless UniswapX orders
  name: Uniswap Trading API
  slug: uniswap-trading-api
- description: The Uniswap Subgraph API provides GraphQL endpoints for querying on-chain data across Uniswap protocol versions v1, v2, v3, and v4. Powered by The Graph Protocol decentralized network, it supports que
  name: Uniswap Subgraph API
  slug: uniswap-subgraph-api
- description: UniswapX is a gasless, auction-based ERC20 swap settlement protocol that routes orders through a competitive filler network. Swappers sign off-chain orders which are filled by fillers who compete to p
  name: UniswapX API
  slug: uniswap-x-api
capabilities:
- description: Unified DeFi trading workflow for swap execution, gasless orders, liquidity management, and token discovery. Used by DeFi developers, trading bots, and portfolio managers building on the Uniswap proto
  name: Uniswap DeFi Trading
  slug: defi-trading
common:
- title: ''
  type: Portal
  url: https://developers.uniswap.org/
- title: ''
  type: Documentation
  url: https://docs.uniswap.org/
- title: ''
  type: Login
  url: https://developers.uniswap.org/dashboard
- title: ''
  type: GitHubOrganization
  url: https://github.com/Uniswap
- title: ''
  type: Blog
  url: https://blog.uniswap.org/
- title: ''
  type: Discord
  url: https://discord.gg/FCfyBSbCU5
- title: ''
  type: X
  url: https://twitter.com/uniswap
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@uniswap/sdk-core
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@uniswap/v3-sdk
- title: ''
  type: SDK
  url: https://developers.uniswap.org/docs/sdks/v4/overview
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/rules/uniswap-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/vocabulary/uniswap-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/capabilities/defi-trading.yaml
- title: ''
  type: JSON-LD
  url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-ld/uniswap-context.jsonld
created: '2024-12-16'
description: Uniswap is the world's leading decentralized exchange (DEX) protocol, enabling permissionless token swaps on Ethereum and 25+ EVM-compatible blockchains through automated market making (AMM). The Uniswap Labs Trading API provides REST endpoints for quotes, swap execution, gasless UniswapX orders, liquidity provider (LP) position management, and wallet operations. Developers can build trading bots, portfolio managers, DeFi aggregators, and embedded swap UIs on top of the protocol.
features:
- description: Swap any ERC-20 token on 25+ EVM chains with optimal routing across Uniswap v2, v3, and v4 liquidity pools.
  name: Token Swaps
- description: Sign off-chain intent-based orders that are filled by competing fillers without requiring the swapper to pay gas fees directly.
  name: Gasless UniswapX Orders
- description: Create, increase, decrease, and manage concentrated liquidity positions on Uniswap v3 and v4 with fee tier and tick range control.
  name: Liquidity Provider Management
- description: Bridge tokens across EVM networks using the unified quote and swap APIs with automatic routing to the best bridge provider.
  name: Cross-Chain Bridging
- description: Submit limit orders that execute automatically when market conditions meet the specified price target.
  name: Limit Orders
- description: Native support for EIP-7702 delegated accounts, ERC-4337 account abstraction, and EIP-5792 wallet capabilities.
  name: Smart Wallet Support
- description: Create multi-step execution plans for complex DeFi workflows with step proofs for verification and tracking.
  name: Execution Plans
- description: Query historical and real-time on-chain data for pools, positions, swaps, and ticks via GraphQL subgraph endpoints.
  name: On-Chain Data via Subgraphs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Uniswap subgraphs are indexed and served by The Graph Protocol's decentralized network.
  name: The Graph Protocol
- description: Primary deployment network for Uniswap v2, v3, and v4 smart contracts.
  name: Ethereum
- description: Uniswap v3 deployed on Polygon PoS and zkEVM networks.
  name: Polygon
- description: Uniswap v3 deployed on Arbitrum One for low-cost swaps.
  name: Arbitrum
- description: Uniswap v3 deployed on Optimism for low-cost swaps.
  name: Optimism
- description: Uniswap v3 and v4 deployed on Base (Coinbase's L2 network).
  name: Base
- description: Third-party filler bots compete to fill UniswapX gasless orders for best execution.
  name: UniswapX Fillers
jsonld:
- class_count: 0
  name: Uniswap Context
  property_count: 25
  slug: uniswap-context
layout: provider
modified: '2026-05-03'
name: Uniswap
rules:
- name: Uniswap API Rules
  rule_count: 33
  severity_counts:
    error: 14
    hint: 0
    info: 4
    warn: 15
  slug: uniswap-spectral-rules
skills: []
slug: uniswap
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uniswap\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/apis.yml\napis:\n  - aid: uniswap:uniswap-trading-api\n    name: Uniswap Trading API\n    tags:\n      - Blockchain\n      - Cryptocurrency\n      - DeFi\n      - Liquidity\n      - Swaps\n    humanURL: https://developers.uniswap.org/\n    properties:\n      - url: https://developers.uniswap.org/\n        type: Documentation\n      - url: https://developers.uniswap.org/dashboard\n        type: SignUp\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/openapi/uniswap-trading-openapi.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-quote-request-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-quote-response-schema.json\n  \
  \      type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-create-swap-request-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-create-swap-response-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-order-request-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-order-response-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-get-swap-quote-example.json\n        type: Example\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-create-swap-transaction-example.json\n\
  \        type: Example\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-create-gasless-order-example.json\n        type: Example\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-create-lp-position-example.json\n        type: Example\n    description: >-\n      The Uniswap Trading API provides REST endpoints for token swaps, bridges,\n      liquidity management, and execution planning across 25+ blockchain networks.\n      It supports swap quoting, gasless UniswapX orders, LP position management,\n      wallet operations (EIP-7702, ERC-4337), and multi-step execution plans.\n      Authentication requires an API key passed in the x-api-key header.\n  - aid: uniswap:uniswap-subgraph-api\n    name: Uniswap Subgraph API\n    tags:\n      - Blockchain\n      - DeFi\n      - GraphQL\n      - On-Chain Data\n    humanURL: https://developers.uniswap.org/api/overview\n\
  \    properties:\n      - url: https://developers.uniswap.org/api/overview\n        type: Documentation\n    description: >-\n      The Uniswap Subgraph API provides GraphQL endpoints for querying on-chain\n      data across Uniswap protocol versions v1, v2, v3, and v4. Powered by The\n      Graph Protocol decentralized network, it supports queries for pools,\n      positions, swaps, ticks, and historical data. Requires an API key from\n      The Graph Studio.\n  - aid: uniswap:uniswap-x-api\n    name: UniswapX API\n    tags:\n      - Blockchain\n      - DeFi\n      - Gasless\n      - Intent Orders\n    humanURL: https://docs.uniswap.org/\n    properties:\n      - url: https://docs.uniswap.org/\n        type: Documentation\n    description: >-\n      UniswapX is a gasless, auction-based ERC20 swap settlement protocol that\n      routes orders through a competitive filler network. Swappers sign off-chain\n      orders which are filled by fillers who compete to provide the best execution.\n\
  \      The API supports order creation, retrieval, and status tracking.\nname: Uniswap\ntags:\n  - Blockchain\n  - Cryptocurrency\n  - DeFi\n  - Decentralized Exchange\n  - Liquidity\n  - Swaps\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-16'\nmodified: '2026-05-03'\nposition: Consuming\nsegments:\n  - DeFi\n  - Cryptocurrency\ndescription: >-\n  Uniswap is the world's leading decentralized exchange (DEX) protocol, enabling\n  permissionless token swaps on Ethereum and 25+ EVM-compatible blockchains through\n  automated market making (AMM). The Uniswap Labs Trading API provides REST endpoints\n  for quotes, swap execution, gasless UniswapX orders, liquidity provider (LP) position\n  management, and wallet operations. Developers can build trading bots, portfolio\n  managers, DeFi aggregators, and embedded swap UIs on top of the protocol.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  specificationVersion: '0.19'\ncommon:\n  - name: Uniswap Developer Portal\n    url: https://developers.uniswap.org/\n    type: Portal\n  - name: Uniswap Documentation\n    url: https://docs.uniswap.org/\n    type: Documentation\n  - name: Uniswap API Dashboard\n    url: https://developers.uniswap.org/dashboard\n    type: Login\n  - name: Uniswap GitHub Organization\n    url: https://github.com/Uniswap\n    type: GitHubOrganization\n  - name: Uniswap Blog\n    url: https://blog.uniswap.org/\n    type: Blog\n  - name: Uniswap Discord\n    url: https://discord.gg/FCfyBSbCU5\n    type: Discord\n  - name: Uniswap Twitter/X\n    url: https://twitter.com/uniswap\n    type: X\n  - name: Uniswap Core TypeScript SDK\n    url: https://www.npmjs.com/package/@uniswap/sdk-core\n    type: SDK\n  - name: Uniswap v3 TypeScript SDK\n    url: https://www.npmjs.com/package/@uniswap/v3-sdk\n    type: SDK\n  - name: Uniswap v4 TypeScript SDK\n    url: https://developers.uniswap.org/docs/sdks/v4/overview\n \
  \   type: SDK\n  - name: Uniswap Spectral Rules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/rules/uniswap-spectral-rules.yml\n    type: SpectralRules\n  - name: Uniswap Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/vocabulary/uniswap-vocabulary.yaml\n    type: Vocabulary\n  - name: Uniswap DeFi Trading Capability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/capabilities/defi-trading.yaml\n    type: NaftikoCapability\n  - name: Uniswap JSON-LD Context\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-ld/uniswap-context.jsonld\n    type: JSON-LD\n  - name: Uniswap Features\n    type: Features\n    data:\n      - name: Token Swaps\n        description: >-\n          Swap any ERC-20 token on 25+ EVM chains with optimal routing across\n          Uniswap v2, v3, and v4 liquidity pools.\n    \
  \  - name: Gasless UniswapX Orders\n        description: >-\n          Sign off-chain intent-based orders that are filled by competing fillers\n          without requiring the swapper to pay gas fees directly.\n      - name: Liquidity Provider Management\n        description: >-\n          Create, increase, decrease, and manage concentrated liquidity positions\n          on Uniswap v3 and v4 with fee tier and tick range control.\n      - name: Cross-Chain Bridging\n        description: >-\n          Bridge tokens across EVM networks using the unified quote and swap APIs\n          with automatic routing to the best bridge provider.\n      - name: Limit Orders\n        description: >-\n          Submit limit orders that execute automatically when market conditions\n          meet the specified price target.\n      - name: Smart Wallet Support\n        description: >-\n          Native support for EIP-7702 delegated accounts, ERC-4337 account\n          abstraction, and EIP-5792 wallet capabilities.\n\
  \      - name: Execution Plans\n        description: >-\n          Create multi-step execution plans for complex DeFi workflows with\n          step proofs for verification and tracking.\n      - name: On-Chain Data via Subgraphs\n        description: >-\n          Query historical and real-time on-chain data for pools, positions,\n          swaps, and ticks via GraphQL subgraph endpoints.\n  - name: Uniswap Use Cases\n    type: UseCases\n    data:\n      - name: Token Swap Integration\n        description: >-\n          Embed token swap functionality in wallets, DApps, and portfolio\n          managers using the Trading API's quote and swap endpoints.\n      - name: DeFi Aggregator\n        description: >-\n          Build a DEX aggregator that routes through Uniswap's liquidity\n          alongside other protocols for best execution.\n      - name: Liquidity Mining Bot\n        description: >-\n          Automate LP position management — create, rebalance, and close\n          positions\
  \ based on market conditions using LP management endpoints.\n      - name: On-Chain Analytics\n        description: >-\n          Power analytics dashboards with historical pool, swap, and liquidity\n          data from the Subgraph GraphQL API.\n      - name: Cross-Chain Bridge UI\n        description: >-\n          Build a bridge interface that quotes and executes cross-chain token\n          transfers using the swap/bridge endpoints.\n  - name: Uniswap Integrations\n    type: Integrations\n    data:\n      - name: The Graph Protocol\n        description: >-\n          Uniswap subgraphs are indexed and served by The Graph Protocol's\n          decentralized network.\n      - name: Ethereum\n        description: >-\n          Primary deployment network for Uniswap v2, v3, and v4 smart contracts.\n      - name: Polygon\n        description: >-\n          Uniswap v3 deployed on Polygon PoS and zkEVM networks.\n      - name: Arbitrum\n        description: >-\n          Uniswap v3 deployed\
  \ on Arbitrum One for low-cost swaps.\n      - name: Optimism\n        description: >-\n          Uniswap v3 deployed on Optimism for low-cost swaps.\n      - name: Base\n        description: >-\n          Uniswap v3 and v4 deployed on Base (Coinbase's L2 network).\n      - name: UniswapX Fillers\n        description: >-\n          Third-party filler bots compete to fill UniswapX gasless orders for\n          best execution.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/apis.yml
tags:
- Blockchain
- Cryptocurrency
- DeFi
- Decentralized Exchange
- Liquidity
- Swaps
url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/apis.yml
use_cases:
- description: Embed token swap functionality in wallets, DApps, and portfolio managers using the Trading API's quote and swap endpoints.
  name: Token Swap Integration
- description: Build a DEX aggregator that routes through Uniswap's liquidity alongside other protocols for best execution.
  name: DeFi Aggregator
- description: Automate LP position management — create, rebalance, and close positions based on market conditions using LP management endpoints.
  name: Liquidity Mining Bot
- description: Power analytics dashboards with historical pool, swap, and liquidity data from the Subgraph GraphQL API.
  name: On-Chain Analytics
- description: Build a bridge interface that quotes and executes cross-chain token transfers using the swap/bridge endpoints.
  name: Cross-Chain Bridge UI
---
