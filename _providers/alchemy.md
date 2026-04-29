---
api_count: 4
apis:
- description: The Alchemy Gas Manager API enables developers to sponsor gas fees for end users via the ERC-4337 Account Abstraction standard. Manage sponsorship policies with per-user spend limits, total caps, allo
  name: Alchemy Gas Manager API
  slug: alchemy-gas-manager-api
- description: The Alchemy Token API provides comprehensive access to ERC-20 token data across EVM-compatible networks. Retrieve token balances by wallet address, token metadata (name, symbol, decimals, logo), and r
  name: Alchemy Token API
  slug: alchemy-token-api
- description: The Alchemy Transfers API provides access to historical on-chain transfer data across EVM-compatible networks. Query asset transfers by address, block range, and transfer category (ETH, ERC-20, ERC-72
  name: Alchemy Transfers API
  slug: alchemy-transfers-api
- description: The Alchemy Bundler API implements the ERC-4337 Account Abstraction bundler standard, allowing UserOperations to be submitted to the blockchain. Developers can send, estimate, and track UserOperations
  name: Alchemy Bundler API
  slug: alchemy-bundler-api
capabilities:
- description: Capability for managing gasless transaction sponsorship using ERC-4337 Account Abstraction. Combines the Gas Manager API for policy creation and management with paymaster sponsorship. Designed for dAp
  name: Alchemy Gasless Transaction Management
  slug: gasless-transaction-management
- description: Unified capability for building Web3 wallet and portfolio applications. Combines the Token API for balance and metadata queries with the Transfers API for transaction history. Designed for wallet deve
  name: Alchemy Web3 Wallet Portfolio
  slug: web3-wallet-portfolio
common:
- title: ''
  type: Pricing
  url: https://www.alchemy.com/pricing
- title: ''
  type: Sandbox
  url: https://www.alchemy.com/sandbox
- title: ''
  type: Webhooks
  url: https://www.alchemy.com/webhooks
- title: ''
  type: SDKs
  url: https://www.alchemy.com/sdk
- title: ''
  type: Blog
  url: https://www.alchemy.com/blog
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/alchemyapi/alchemy-platforms/overview
- title: ''
  type: Documentation
  url: https://docs.alchemy.com
- title: ''
  type: Support
  url: https://www.alchemy.com/support
- title: ''
  type: SignUp
  url: https://dashboard.alchemy.com/signup
- title: ''
  type: StatusPage
  url: https://status.alchemy.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/alchemyplatform
- title: ''
  type: SpectralRules
  url: rules/alchemy-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/alchemy-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/web3-wallet-portfolio.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/gasless-transaction-management.yaml
created: '2024-11-07T00:00:00.000Z'
description: Alchemy is a Web3 developer platform providing powerful APIs, SDKs, and infrastructure tools to build and scale blockchain applications. Supporting Ethereum, Polygon, and other EVM-compatible networks, Alchemy powers production dApps with reliable node infrastructure, enhanced APIs for token data, asset transfers, NFTs, and ERC-4337 Account Abstraction tools including gas sponsorship (Gas Manager) and smart account bundling.
features:
- description: Query token data and transfers across Ethereum, Polygon, and other EVM-compatible networks.
  name: Multi-Chain Support
- description: Full support for ERC-4337 with bundler, paymaster (Gas Manager), and smart account APIs.
  name: ERC-4337 Account Abstraction
- description: Sponsor gas fees for end users via Gas Manager policies with spend limits and network rules.
  name: Gasless Transactions
- description: Real-time ERC-20 token balances and metadata including name, symbol, decimals, and logo.
  name: Token Data
- description: Historical on-chain transfer data for ETH, ERC-20, ERC-721, and ERC-1155 assets.
  name: Transfer History
- description: Standard Ethereum JSON-RPC interface with Alchemy-enhanced methods for additional data.
  name: JSON-RPC Compatibility
- description: Real-time blockchain event notifications via webhooks for address activity and mined transactions.
  name: Webhook Notifications
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native support for Ethereum mainnet and testnets.
  name: Ethereum
- description: Full API support for Polygon (MATIC) mainnet and Mumbai testnet.
  name: Polygon
- description: Works with any ERC-4337 compatible bundler for UserOperation submission.
  name: ERC-4337 Bundlers
- description: Integration with MetaMask wallet for Web3 connection management.
  name: MetaMask
- description: Developer toolchain integration for local testing and deployment.
  name: Hardhat and Foundry
jsonld:
- class_count: 7
  name: Alchemy Gas Manager Api Context
  property_count: 15
  slug: alchemy-gas-manager-api-context
- class_count: 6
  name: Alchemy Token Api Context
  property_count: 12
  slug: alchemy-token-api-context
- class_count: 4
  name: Alchemy Transfers Api Context
  property_count: 14
  slug: alchemy-transfers-api-context
layout: provider
modified: '2026-04-19'
name: Alchemy
rules:
- name: Alchemy API Rules
  rule_count: 32
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 15
  slug: alchemy-spectral-rules
skills: []
slug: alchemy
solutions: []
source_yaml: "aid: alchemy\nurl: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml\nname: Alchemy\ntags:\n  - Blockchain\n  - Cryptocurrency\n  - Web3\n  - Account Abstraction\n  - Ethereum\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-07T00:00:00.000Z'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  Alchemy is a Web3 developer platform providing powerful APIs, SDKs, and\n  infrastructure tools to build and scale blockchain applications. Supporting\n  Ethereum, Polygon, and other EVM-compatible networks, Alchemy powers\n  production dApps with reliable node infrastructure, enhanced APIs for token\n  data, asset transfers, NFTs, and ERC-4337 Account Abstraction tools including\n  gas sponsorship (Gas Manager) and smart account bundling.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\napis:\n  - aid: alchemy:alchemy-gas-manager-api\n\
  \    name: Alchemy Gas Manager API\n    tags:\n      - Gas Manager\n      - Account Abstraction\n      - ERC-4337\n    humanURL: https://www.alchemy.com/gas-manager\n    description: >-\n      The Alchemy Gas Manager API enables developers to sponsor gas fees for\n      end users via the ERC-4337 Account Abstraction standard. Manage\n      sponsorship policies with per-user spend limits, total caps, allowlisted\n      contracts, and time-based expiry, enabling gasless transactions for dApp\n      users.\n    properties:\n      - type: OpenAPI\n        url: openapi/alchemy-gas-manager-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/alchemy-gas-manager-api-policy-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-gas-manager-api-policy-list-response-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-gas-manager-api-create-policy-request-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-gas-manager-api-sponsor-user-operation-request-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/alchemy-gas-manager-api-sponsor-user-operation-result-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-gas-manager-api-sponsor-user-operation-response-schema.json\n      - type: JSONStructure\n        url: json-structure/alchemy-gas-manager-api-policy-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-gas-manager-api-policy-list-response-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-gas-manager-api-create-policy-request-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-gas-manager-api-sponsor-user-operation-request-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-gas-manager-api-sponsor-user-operation-result-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-gas-manager-api-sponsor-user-operation-response-structure.json\n      - type: JSON-LD\n        url:\
  \ json-ld/alchemy-gas-manager-api-context.jsonld\n      - type: Example\n        url: examples/alchemy-gas-manager-api-policy-example.json\n      - type: Example\n        url: examples/alchemy-gas-manager-api-policy-list-response-example.json\n      - type: Example\n        url: examples/alchemy-gas-manager-api-create-policy-request-example.json\n      - type: Example\n        url: examples/alchemy-gas-manager-api-sponsor-user-operation-request-example.json\n      - type: Example\n        url: examples/alchemy-gas-manager-api-sponsor-user-operation-result-example.json\n      - type: Example\n        url: examples/alchemy-gas-manager-api-sponsor-user-operation-response-example.json\n\n  - aid: alchemy:alchemy-token-api\n    name: Alchemy Token API\n    tags:\n      - Tokens\n      - ERC-20\n      - DeFi\n    humanURL: https://www.alchemy.com/token-api\n    description: >-\n      The Alchemy Token API provides comprehensive access to ERC-20 token data\n      across EVM-compatible networks.\
  \ Retrieve token balances by wallet address,\n      token metadata (name, symbol, decimals, logo), and real-time pricing\n      data. Supports multi-chain queries for wallets, portfolio trackers, and\n      DeFi applications.\n    properties:\n      - type: OpenAPI\n        url: openapi/alchemy-token-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/alchemy-token-api-token-balance-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-token-api-token-balances-result-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-token-api-token-balances-response-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-token-api-token-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-token-api-token-metadata-response-schema.json\n      - type: JSONStructure\n        url: json-structure/alchemy-token-api-token-balance-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-token-api-token-balances-result-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/alchemy-token-api-token-balances-response-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-token-api-token-metadata-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-token-api-token-metadata-response-structure.json\n      - type: JSON-LD\n        url: json-ld/alchemy-token-api-context.jsonld\n      - type: Example\n        url: examples/alchemy-token-api-token-balance-example.json\n      - type: Example\n        url: examples/alchemy-token-api-token-balances-result-example.json\n      - type: Example\n        url: examples/alchemy-token-api-token-balances-response-example.json\n      - type: Example\n        url: examples/alchemy-token-api-token-metadata-example.json\n      - type: Example\n        url: examples/alchemy-token-api-token-metadata-response-example.json\n\n  - aid: alchemy:alchemy-transfers-api\n    name: Alchemy Transfers API\n    tags:\n      - Transfers\n\
  \      - NFTs\n      - Transaction History\n    humanURL: https://www.alchemy.com/transfers-api\n    description: >-\n      The Alchemy Transfers API provides access to historical on-chain transfer\n      data across EVM-compatible networks. Query asset transfers by address,\n      block range, and transfer category (ETH, ERC-20, ERC-721, ERC-1155, and\n      internal transfers), enabling wallet activity tracking, portfolio history,\n      and transaction auditing.\n    properties:\n      - type: OpenAPI\n        url: openapi/alchemy-transfers-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/alchemy-transfers-api-asset-transfer-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-transfers-api-transfer-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-transfers-api-asset-transfers-result-schema.json\n      - type: JSONSchema\n        url: json-schema/alchemy-transfers-api-asset-transfers-response-schema.json\n      -\
  \ type: JSONStructure\n        url: json-structure/alchemy-transfers-api-asset-transfer-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-transfers-api-transfer-metadata-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-transfers-api-asset-transfers-result-structure.json\n      - type: JSONStructure\n        url: json-structure/alchemy-transfers-api-asset-transfers-response-structure.json\n      - type: JSON-LD\n        url: json-ld/alchemy-transfers-api-context.jsonld\n      - type: Example\n        url: examples/alchemy-transfers-api-asset-transfer-example.json\n      - type: Example\n        url: examples/alchemy-transfers-api-transfer-metadata-example.json\n      - type: Example\n        url: examples/alchemy-transfers-api-asset-transfers-result-example.json\n      - type: Example\n        url: examples/alchemy-transfers-api-asset-transfers-response-example.json\n\n  - aid: alchemy:alchemy-bundler-api\n    name: Alchemy\
  \ Bundler API\n    tags:\n      - Bundler\n      - Account Abstraction\n      - ERC-4337\n    humanURL: https://www.alchemy.com/bundler\n    description: >-\n      The Alchemy Bundler API implements the ERC-4337 Account Abstraction\n      bundler standard, allowing UserOperations to be submitted to the\n      blockchain. Developers can send, estimate, and track UserOperations\n      using standard eth_sendUserOperation and related methods.\n    properties: []\n\ncommon:\n  - url: https://www.alchemy.com/pricing\n    name: Pricing\n    type: Pricing\n  - url: https://www.alchemy.com/sandbox\n    name: Sandbox\n    type: Sandbox\n  - url: https://www.alchemy.com/webhooks\n    name: Webhooks\n    type: Webhooks\n  - url: https://www.alchemy.com/sdk\n    name: Alchemy SDK\n    type: SDKs\n  - url: https://www.alchemy.com/blog\n    name: Blog\n    type: Blog\n  - url: https://www.postman.com/alchemyapi/alchemy-platforms/overview\n    name: Postman Workspace\n    type: PostmanWorkspace\n  -\
  \ url: https://docs.alchemy.com\n    name: Documentation\n    type: Documentation\n  - url: https://www.alchemy.com/support\n    name: Support\n    type: Support\n  - url: https://dashboard.alchemy.com/signup\n    name: Sign Up\n    type: SignUp\n  - url: https://status.alchemy.com\n    name: Status Page\n    type: StatusPage\n  - url: https://github.com/alchemyplatform\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: rules/alchemy-spectral-rules.yml\n    name: Alchemy Spectral Rules\n    type: SpectralRules\n  - url: vocabulary/alchemy-vocabulary.yaml\n    name: Alchemy Vocabulary\n    type: Vocabulary\n  - url: capabilities/web3-wallet-portfolio.yaml\n    name: Web3 Wallet Portfolio\n    type: NaftikoCapability\n  - url: capabilities/gasless-transaction-management.yaml\n    name: Gasless Transaction Management\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Multi-Chain Support\n        description: Query token data and transfers across\
  \ Ethereum, Polygon, and other EVM-compatible networks.\n      - name: ERC-4337 Account Abstraction\n        description: Full support for ERC-4337 with bundler, paymaster (Gas Manager), and smart account APIs.\n      - name: Gasless Transactions\n        description: Sponsor gas fees for end users via Gas Manager policies with spend limits and network rules.\n      - name: Token Data\n        description: Real-time ERC-20 token balances and metadata including name, symbol, decimals, and logo.\n      - name: Transfer History\n        description: Historical on-chain transfer data for ETH, ERC-20, ERC-721, and ERC-1155 assets.\n      - name: JSON-RPC Compatibility\n        description: Standard Ethereum JSON-RPC interface with Alchemy-enhanced methods for additional data.\n      - name: Webhook Notifications\n        description: Real-time blockchain event notifications via webhooks for address activity and mined transactions.\n  - type: UseCases\n    data:\n      - name: Wallet Application\
  \ Development\n        description: Build EVM wallets with real-time token balances, transaction history, and NFT support.\n      - name: DeFi Portfolio Tracking\n        description: Track multi-asset portfolios across EVM networks with accurate token pricing and balances.\n      - name: Gasless dApp UX\n        description: Abstract gas fees from end users so they can interact with dApps without holding ETH.\n      - name: NFT Marketplace Integration\n        description: Query ERC-721 and ERC-1155 transfer history for NFT ownership tracking and provenance.\n      - name: Blockchain Analytics\n        description: Analyze on-chain transfer patterns, wallet activity, and token flow across EVM networks.\n  - type: Integrations\n    data:\n      - name: Ethereum\n        description: Native support for Ethereum mainnet and testnets.\n      - name: Polygon\n        description: Full API support for Polygon (MATIC) mainnet and Mumbai testnet.\n      - name: ERC-4337 Bundlers\n        description:\
  \ Works with any ERC-4337 compatible bundler for UserOperation submission.\n      - name: MetaMask\n        description: Integration with MetaMask wallet for Web3 connection management.\n      - name: Hardhat and Foundry\n        description: Developer toolchain integration for local testing and deployment.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml
tags:
- Blockchain
- Cryptocurrency
- Web3
- Account Abstraction
- Ethereum
url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/apis.yml
use_cases:
- description: Build EVM wallets with real-time token balances, transaction history, and NFT support.
  name: Wallet Application Development
- description: Track multi-asset portfolios across EVM networks with accurate token pricing and balances.
  name: DeFi Portfolio Tracking
- description: Abstract gas fees from end users so they can interact with dApps without holding ETH.
  name: Gasless dApp UX
- description: Query ERC-721 and ERC-1155 transfer history for NFT ownership tracking and provenance.
  name: NFT Marketplace Integration
- description: Analyze on-chain transfer patterns, wallet activity, and token flow across EVM networks.
  name: Blockchain Analytics
---
