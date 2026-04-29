---
api_count: 8
api_specs:
- filename: coinbase-advanced-trade-openapi.yml
  format: yaml
  label: Coinbase Advanced Trade API
  slug: advanced-trade-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-advanced-trade-openapi.yml
- filename: coinbase-exchange-openapi.yml
  format: yaml
  label: Coinbase Exchange API
  slug: exchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-exchange-openapi.yml
- filename: coinbase-prime-openapi.yml
  format: yaml
  label: Coinbase Prime API
  slug: prime-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-prime-openapi.yml
- filename: coinbase-onramp-openapi.yml
  format: yaml
  label: Coinbase Onramp API
  slug: onramp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-onramp-openapi.yml
- filename: coinbase-commerce-openapi.yml
  format: yaml
  label: Coinbase Commerce API
  slug: commerce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-commerce-openapi.yml
apis:
- description: The Coinbase Advanced Trade API provides programmatic access to advanced trading features on the Coinbase platform. Developers can automate market, limit, and stop-limit orders, manage portfolios, ret
  name: Coinbase Advanced Trade API
  slug: advanced-trade-api
- description: The Coinbase Exchange API provides high-throughput access to real-time market data and order management for institutional and professional traders. It supports REST APIs, FIX protocol, and WebSocket f
  name: Coinbase Exchange API
  slug: exchange-api
- description: The Coinbase Prime API enables institutions to manage cryptocurrency trading and custody on behalf of their clients. It supports programmatic trading strategies, automated platform processes, portfoli
  name: Coinbase Prime API
  slug: prime-api
- description: The Coinbase Onramp API allows developers to integrate fiat-to-crypto purchasing directly into their applications. It provides a FundCard React component and REST APIs to create one-click-buy URLs tha
  name: Coinbase Onramp API
  slug: onramp-api
- description: The Coinbase Commerce API enables merchants and developers to accept cryptocurrency payments globally. It supports payment links, payouts, invoices, and checkout flows that can be integrated into webs
  name: Coinbase Commerce API
  slug: commerce-api
- description: The Coinbase Wallet SDK allows developers to integrate Coinbase Wallet connectivity into decentralized applications. It provides a streamlined interface for users to connect their wallets, sign transa
  name: Coinbase Wallet SDK
  slug: wallet-sdk
- description: The Coinbase Data API provides developers with access to cryptocurrency market data, blockchain analytics, and pricing information. It delivers real-time and historical data for a wide range of digita
  name: Coinbase Data API
  slug: data-api
- description: Coinbase AgentKit is a toolkit that enables AI agents to interact with blockchain networks through secure wallet management and comprehensive onchain capabilities. Built on the Coinbase Developer Plat
  name: Coinbase AgentKit
  slug: agentkit
asyncapis:
- description: The Coinbase Advanced Trade WebSocket API provides real-time market data streaming including heartbeats, ticker updates, candle data, market trades, level2 order book updates, and user order status ch
  name: Coinbase Advanced Trade WebSocket
  slug: coinbase-advanced-trade-asyncapi
- description: Coinbase Commerce sends webhook events to notify your application when charges are created, confirmed, delayed, pending, failed, or resolved. Each webhook event is signed with a SHA-256 HMAC signature
  name: Coinbase Commerce Webhooks
  slug: coinbase-commerce-webhooks-asyncapi
- description: The Coinbase Exchange WebSocket Feed provides real-time market data for the Exchange platform. It supports multiple channels including heartbeat, ticker, level2 order book, full order feed, and user o
  name: Coinbase Exchange WebSocket Feed
  slug: coinbase-exchange-asyncapi
capabilities: []
common:
- title: ''
  type: Developer Portal
  url: https://www.coinbase.com/developer-platform
- title: ''
  type: Documentation
  url: https://docs.cdp.coinbase.com/
- title: ''
  type: Website
  url: https://www.coinbase.com/
- title: ''
  type: Blog
  url: https://www.coinbase.com/blog
- title: ''
  type: GitHub
  url: https://github.com/coinbase
- title: ''
  type: Login
  url: https://login.coinbase.com/
- title: ''
  type: Support
  url: https://help.coinbase.com/
- title: ''
  type: Privacy Policy
  url: https://www.coinbase.com/legal/privacy
- title: ''
  type: Terms of Service
  url: https://www.coinbase.com/legal/user-agreement
- title: ''
  type: JSON-LD
  url: json-ld/coinbase-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/coinbase-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/coinbase-charge-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/coinbase-product-schema.json
- title: ''
  type: Spectral Ruleset
  url: rules/coinbase-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/coinbase-capabilities.yml
created: '2026-03-20'
description: Coinbase is a leading cryptocurrency platform providing trading, custody, and payment infrastructure for individuals, businesses, and institutions. The Coinbase Developer Platform (CDP) exposes a wide product surface across retail trading (Advanced Trade), professional and institutional trading (Exchange and Prime), merchant payments (Commerce), fiat onboarding (Onramp), developer wallet integration (Wallet SDK), market and on-chain data (Data API), and AI agent toolkits (AgentKit). Authentication is performed using API keys with HMAC-SHA256 signatures (Advanced Trade, Exchange) or JWT bearer tokens (Prime, CDP), with WebSocket and FIX feeds available for low-latency market data and order management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Coinbase Context
  property_count: 9
  slug: coinbase-context
layout: provider
modified: '2026-04-28'
name: Coinbase
rules:
- name: Coinbase API Rules
  rule_count: 12
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 5
  slug: coinbase-rules
skills: []
slug: coinbase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coinbase\nurl: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/apis.yml\nname: Coinbase\ntags:\n  - Blockchain\n  - Cryptocurrency\n  - Custody\n  - Exchange\n  - Onramp\n  - Payments\n  - Trading\n  - Wallet\n  - Web3\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Coinbase is a leading cryptocurrency platform providing trading, custody, and\n  payment infrastructure for individuals, businesses, and institutions. The\n  Coinbase Developer Platform (CDP) exposes a wide product surface across\n  retail trading (Advanced Trade), professional and institutional trading\n  (Exchange and Prime), merchant payments (Commerce), fiat onboarding (Onramp),\n  developer wallet integration (Wallet SDK), market and on-chain data (Data\n  API), and AI agent toolkits (AgentKit). Authentication\
  \ is performed using\n  API keys with HMAC-SHA256 signatures (Advanced Trade, Exchange) or JWT\n  bearer tokens (Prime, CDP), with WebSocket and FIX feeds available for\n  low-latency market data and order management.\napis:\n  - aid: coinbase:advanced-trade-api\n    name: Coinbase Advanced Trade API\n    tags:\n      - Automation\n      - Cryptocurrency\n      - Market Data\n      - Orders\n      - Trading\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.coinbase.com\n    humanURL: https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api\n    properties:\n      - url: https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api\n        type: Documentation\n      - url: openapi/coinbase-advanced-trade-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/coinbase-advanced-trade-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Coinbase Advanced Trade API provides programmatic\
  \ access to advanced\n      trading features on the Coinbase platform. Developers can automate market,\n      limit, and stop-limit orders, manage portfolios, retrieve real-time and\n      historical market data, and monitor fees. The REST API is available at\n      api.coinbase.com/api/v3/brokerage and supports authenticated access using\n      API keys with HMAC SHA-256 signatures.\n    x-features:\n      - Market, limit, and stop-limit order types\n      - HMAC-SHA256 API key signatures\n      - WebSocket feed for real-time order updates\n      - Portfolio and account balance management\n      - Public market data without authentication\n    x-use-cases:\n      - Build retail trading bots and automated strategies\n      - Power portfolio dashboards with live balances\n      - Run algorithmic strategies against advanced order types\n      - Sync transaction history into accounting tooling\n  - aid: coinbase:exchange-api\n    name: Coinbase Exchange API\n    tags:\n      - Cryptocurrency\n\
  \      - Exchange\n      - FIX\n      - Market Data\n      - Trading\n      - WebSocket\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.exchange.coinbase.com\n    humanURL: https://www.coinbase.com/developer-platform/products/exchange-api\n    properties:\n      - url: https://docs.cdp.coinbase.com/exchange/docs/welcome\n        type: Documentation\n      - url: openapi/coinbase-exchange-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/coinbase-exchange-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Coinbase Exchange API provides high-throughput access to real-time\n      market data and order management for institutional and professional\n      traders. It supports REST APIs, FIX protocol, and WebSocket feeds for\n      direct order placement and live market data streaming. The API enables\n      programmatic trading at scale with low-latency execution and is designed\n      for high-volume\
  \ trading operations on the Coinbase exchange.\n    x-features:\n      - REST, FIX, and WebSocket interfaces\n      - Sub-millisecond market data feeds\n      - Direct order entry for institutional flow\n      - Full order book and trade history access\n    x-use-cases:\n      - Run market-making and liquidity-providing strategies\n      - Stream consolidated market data into trading systems\n      - Connect legacy FIX trading stacks to crypto venues\n      - Operate institutional execution and risk pipelines\n  - aid: coinbase:prime-api\n    name: Coinbase Prime API\n    tags:\n      - Cryptocurrency\n      - Custody\n      - Institutional\n      - Prime Brokerage\n      - Trading\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.prime.coinbase.com\n    humanURL: https://www.coinbase.com/developer-platform/products/prime-apis\n    properties:\n      - url: https://docs.cdp.coinbase.com/prime/docs/rest-requests\n        type:\
  \ Documentation\n      - url: openapi/coinbase-prime-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Coinbase Prime API enables institutions to manage cryptocurrency\n      trading and custody on behalf of their clients. It supports programmatic\n      trading strategies, automated platform processes, portfolio management,\n      and custodial operations. The REST API provides endpoints for order\n      execution, account management, transaction history, and reporting,\n      designed for institutional-grade workflows and compliance requirements.\n    x-features:\n      - Multi-portfolio and multi-entity account model\n      - Cold and hot custody with whitelisted addresses\n      - Order execution, allocation, and TWAP support\n      - Transaction history and reporting endpoints\n      - JWT-based authentication with per-entity scoping\n    x-use-cases:\n      - Operate prime brokerage flows on behalf of clients\n      - Automate treasury and custody workflows\n   \
  \   - Allocate fills across sub-accounts and entities\n      - Stream compliance and reporting data into back-office systems\n  - aid: coinbase:onramp-api\n    name: Coinbase Onramp API\n    tags:\n      - Cryptocurrency\n      - Fiat\n      - Offramp\n      - Onramp\n      - Payments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.developer.coinbase.com\n    humanURL: https://www.coinbase.com/developer-platform/products/onramp\n    properties:\n      - url: https://docs.cdp.coinbase.com/onramp/docs/welcome\n        type: Documentation\n      - url: openapi/coinbase-onramp-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Coinbase Onramp API allows developers to integrate fiat-to-crypto\n      purchasing directly into their applications. It provides a FundCard React\n      component and REST APIs to create one-click-buy URLs that enable users to\n      purchase cryptocurrency with minimal friction. The API\
  \ supports multiple\n      fiat currencies and payment methods, making it straightforward for\n      developers to onboard users into the crypto ecosystem from any\n      application.\n    x-features:\n      - One-click-buy URL generation\n      - FundCard React component for embedded UX\n      - Multiple fiat rails and payment methods\n      - Onramp and offramp flows in a single API\n    x-use-cases:\n      - Embed fiat funding directly into a wallet or dapp\n      - Enable users to cash out from on-chain holdings\n      - Reduce KYC and PCI scope by leveraging Coinbase's stack\n  - aid: coinbase:commerce-api\n    name: Coinbase Commerce API\n    tags:\n      - Checkout\n      - Commerce\n      - Cryptocurrency\n      - Invoices\n      - Payments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.commerce.coinbase.com\n    humanURL: https://commerce.coinbase.com/docs\n    properties:\n      - url: https://commerce.coinbase.com/docs/api\n\
  \        type: Documentation\n      - url: openapi/coinbase-commerce-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/coinbase-commerce-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Coinbase Commerce API enables merchants and developers to accept\n      cryptocurrency payments globally. It supports payment links, payouts,\n      invoices, and checkout flows that can be integrated into websites and\n      applications. The API provides endpoints for creating charges, managing\n      payments, handling webhooks for payment notifications, and automating\n      financial workflows for businesses accepting crypto as a payment method.\n    x-features:\n      - Charges, checkouts, invoices, and payment links\n      - Webhook event delivery for charge state changes\n      - Hosted checkout pages and embedded SDK options\n      - Payouts in stablecoins and supported assets\n    x-use-cases:\n      - Accept crypto payments on e-commerce sites\n      - Issue\
  \ branded invoices payable in crypto\n      - Trigger fulfillment workflows from charge webhooks\n      - Pay vendors and contractors in stablecoins\n  - aid: coinbase:wallet-sdk\n    name: Coinbase Wallet SDK\n    tags:\n      - Cryptocurrency\n      - DApps\n      - SDK\n      - Wallet\n      - Web3\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.coinbase.com/developer-platform/products/wallet-sdk\n    properties:\n      - url: https://docs.cdp.coinbase.com/wallet-sdk/docs/welcome\n        type: Documentation\n    description: >-\n      The Coinbase Wallet SDK allows developers to integrate Coinbase Wallet\n      connectivity into decentralized applications. It provides a streamlined\n      interface for users to connect their wallets, sign transactions, and\n      interact with smart contracts across multiple blockchain networks. The\n      SDK supports millions of Coinbase Wallet users and enables dapp\n      developers\
  \ to offer seamless wallet-based experiences for trading assets\n      and managing NFTs.\n    x-features:\n      - EIP-1193 provider compatible with web3 libraries\n      - Mobile and desktop wallet connection flows\n      - Smart contract signing and transaction handling\n      - NFT and asset management primitives\n    x-use-cases:\n      - Add Connect Wallet flows to dapps\n      - Sign messages and transactions in mobile and web apps\n      - Bridge web3 user identity to traditional UX patterns\n  - aid: coinbase:data-api\n    name: Coinbase Data API\n    tags:\n      - Analytics\n      - Blockchain\n      - Cryptocurrency\n      - Market Data\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.coinbase.com/developer-platform/products/data-api\n    properties:\n      - url: https://www.coinbase.com/developer-platform/products/data-api\n        type: Documentation\n    description: >-\n      The Coinbase Data API provides\
  \ developers with access to cryptocurrency\n      market data, blockchain analytics, and pricing information. It delivers\n      real-time and historical data for a wide range of digital assets,\n      enabling developers to build data-driven applications, dashboards, and\n      research tools. The API supports queries for price feeds, trading\n      volumes, and on-chain metrics across supported networks.\n    x-features:\n      - Real-time and historical price feeds\n      - On-chain analytics and metrics\n      - Trading volume and liquidity insights\n    x-use-cases:\n      - Power research dashboards and reports\n      - Drive risk and pricing models with on-chain signals\n      - Display market data in consumer apps\n  - aid: coinbase:agentkit\n    name: Coinbase AgentKit\n    tags:\n      - Agents\n      - AI\n      - Blockchain\n      - SDK\n      - Wallet\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cdp.coinbase.com/agent-kit/welcome\n\
  \    properties:\n      - url: https://docs.cdp.coinbase.com/agent-kit/welcome\n        type: Documentation\n    description: >-\n      Coinbase AgentKit is a toolkit that enables AI agents to interact with\n      blockchain networks through secure wallet management and comprehensive\n      onchain capabilities. Built on the Coinbase Developer Platform SDK, it\n      is framework-agnostic and wallet-agnostic, supporting EVM and Solana\n      networks.\n    x-features:\n      - Framework-agnostic and wallet-agnostic agent toolkit\n      - EVM and Solana network support\n      - Gasless transactions via CDP Smart Wallets\n      - LangChain, MCP, and other framework integrations\n    x-use-cases:\n      - Build autonomous AI agents that transact on-chain\n      - Automate token swaps, transfers, and contract calls\n      - Connect agentic frameworks to wallet primitives\ncommon:\n  - type: Developer Portal\n    url: https://www.coinbase.com/developer-platform\n  - type: Documentation\n  \
  \  url: https://docs.cdp.coinbase.com/\n  - type: Website\n    url: https://www.coinbase.com/\n  - type: Blog\n    url: https://www.coinbase.com/blog\n  - type: GitHub\n    url: https://github.com/coinbase\n  - type: Login\n    url: https://login.coinbase.com/\n  - type: Support\n    url: https://help.coinbase.com/\n  - type: Privacy Policy\n    url: https://www.coinbase.com/legal/privacy\n  - type: Terms of Service\n    url: https://www.coinbase.com/legal/user-agreement\n  - type: JSON-LD\n    url: json-ld/coinbase-context.jsonld\n  - type: JSONSchema\n    url: json-schema/coinbase-order-schema.json\n  - type: JSONSchema\n    url: json-schema/coinbase-charge-schema.json\n  - type: JSONSchema\n    url: json-schema/coinbase-product-schema.json\n  - type: Spectral Ruleset\n    url: rules/coinbase-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/coinbase-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/apis.yml
tags:
- Blockchain
- Cryptocurrency
- Custody
- Exchange
- Onramp
- Payments
- Trading
- Wallet
- Web3
url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/apis.yml
use_cases: []
---
