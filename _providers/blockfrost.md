---
api_count: 1
apis:
- description: RESTful API for interacting with the Cardano blockchain and parts of its ecosystem. Provides access to blocks, transactions, accounts, addresses, native assets, epochs, governance data, and IPFS. Requ
  name: Blockfrost API
  slug: blockfrost
capabilities:
- description: Workflow capability for Cardano blockchain exploration and dApp integration using the Blockfrost API. Enables developers, analysts, and dApp builders to query blocks, transactions, accounts, addresses
  name: Blockfrost Cardano Explorer
  slug: blockfrost-cardano-explorer
common:
- title: ''
  type: Website
  url: https://blockfrost.io/
- title: ''
  type: Documentation
  url: https://blockfrost.dev/
- title: ''
  type: GettingStarted
  url: https://blockfrost.dev/overview/getting-started
- title: ''
  type: Pricing
  url: https://blockfrost.io/#pricing
- title: ''
  type: StatusPage
  url: https://status.blockfrost.io/
- title: ''
  type: Support
  url: https://blockfrost.dev/support
- title: ''
  type: GitHubOrganization
  url: https://github.com/blockfrost
- title: ''
  type: Discord
  url: https://discord.gg/inputoutput
- title: ''
  type: TermsOfService
  url: https://blockfrost.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://blockfrost.io/privacy
- title: ''
  type: Login
  url: https://blockfrost.io/auth/signin
- title: Official SDKs
  type: SDK
  url: https://blockfrost.dev/sdks
- title: ''
  type: SpectralRules
  url: rules/blockfrost-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/blockfrost-cardano-explorer.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/blockfrost-vocabulary.yaml
created: '2024-09-27'
description: Blockfrost is a RESTful API service providing access to the Cardano blockchain and its ecosystem. It serves as an infrastructure layer for developers building dApps, wallets, NFT platforms, DeFi protocols, and analytics tools on Cardano. Blockfrost provides endpoints for querying blocks, transactions, accounts, addresses, native assets, epochs, governance data, and IPFS storage, supporting both mainnet and testnet networks.
features:
- description: Query blocks, transactions, slots, epochs, accounts, and addresses on the Cardano mainnet and testnet networks.
  name: Cardano Blockchain Access
- description: Full support for Cardano native assets including fungible tokens, NFTs, and multi-asset UTXOs with on-chain metadata (CIP-25, CIP-68).
  name: Native Asset Support
- description: Query stake pool information, delegation history, rewards, and account activity for Cardano staking workflows.
  name: Stake Pool and Delegation Data
- description: Access Cardano governance data including proposals, DRep registrations, and voting activity introduced in the Conway era.
  name: Governance Data
- description: Built-in IPFS API for storing and retrieving off-chain NFT metadata and other content via Blockfrost's IPFS gateway.
  name: IPFS Integration
- description: Single API surface covering Cardano mainnet, preview testnet, preprod testnet, and the Midnight blockchain.
  name: Multi-Network Support
- description: Submit signed transactions directly to the Cardano network via the Blockfrost API without running a local node.
  name: Transaction Submission
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: The Mesh JavaScript/TypeScript SDK integrates with Blockfrost as a provider for Cardano dApp development.
  name: Mesh SDK
- description: Lucid Evolution (TypeScript library) supports Blockfrost as a blockchain provider for transaction building and submission.
  name: Lucid Evolution
- description: PyCardano Python library uses Blockfrost as a chain context provider for Cardano smart contract development.
  name: PyCardano
- description: The Cardano Serialization Library (CSL) pairs with Blockfrost for transaction construction and UTXO management.
  name: Cardano Serialization Library
jsonld:
- class_count: 22
  name: Blockfrost Context
  property_count: 51
  slug: blockfrost-context
layout: provider
modified: '2026-04-19'
name: Blockfrost
rules:
- name: Blockfrost API Rules
  rule_count: 30
  severity_counts:
    error: 13
    hint: 0
    info: 7
    warn: 10
  slug: blockfrost-spectral-rules
skills: []
slug: blockfrost
solutions: []
source_yaml: "aid: blockfrost\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/blockfrost/refs/heads/main/apis.yml\nname: Blockfrost\ndescription: >-\n  Blockfrost is a RESTful API service providing access to the Cardano blockchain and its\n  ecosystem. It serves as an infrastructure layer for developers building dApps, wallets,\n  NFT platforms, DeFi protocols, and analytics tools on Cardano. Blockfrost provides\n  endpoints for querying blocks, transactions, accounts, addresses, native assets,\n  epochs, governance data, and IPFS storage, supporting both mainnet and testnet networks.\ntags:\n  - Blockchain\n  - Cardano\n  - Cryptocurrency\n  - DApps\n  - NFT\n  - Web3\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-09-27'\nmodified: '2026-04-19'\nposition: Consuming\nspecificationVersion: '0.19'\napis:\n  - aid: blockfrost:blockfrost\n    name: Blockfrost API\n    description: >-\n      RESTful\
  \ API for interacting with the Cardano blockchain and parts of its ecosystem.\n      Provides access to blocks, transactions, accounts, addresses, native assets, epochs,\n      governance data, and IPFS. Requires a project_id obtained from blockfrost.io for\n      authentication. Supports Cardano mainnet, preview testnet, preprod testnet,\n      and Midnight mainnet networks.\n    humanURL: https://blockfrost.io/\n    tags:\n      - Blockchain\n      - Cardano\n      - Cryptocurrency\n      - Web3\n    properties:\n      - type: Documentation\n        url: https://docs.blockfrost.io/\n      - type: OpenAPI\n        url: openapi/blockfrost-openapi.yaml\n      - type: NaftikoCapability\n        url: capabilities/blockfrost-cardano-explorer.yaml\n      - type: SpectralRules\n        url: rules/blockfrost-spectral-rules.yml\n      - type: Vocabulary\n        url: vocabulary/blockfrost-vocabulary.yaml\ncommon:\n  - type: Website\n    url: https://blockfrost.io/\n  - type: Documentation\n  \
  \  url: https://blockfrost.dev/\n  - type: GettingStarted\n    url: https://blockfrost.dev/overview/getting-started\n  - type: Pricing\n    url: https://blockfrost.io/#pricing\n  - type: StatusPage\n    url: https://status.blockfrost.io/\n  - type: Support\n    url: https://blockfrost.dev/support\n  - type: GitHubOrganization\n    url: https://github.com/blockfrost\n  - type: Discord\n    url: https://discord.gg/inputoutput\n  - type: TermsOfService\n    url: https://blockfrost.io/terms\n  - type: PrivacyPolicy\n    url: https://blockfrost.io/privacy\n  - type: Login\n    url: https://blockfrost.io/auth/signin\n  - type: SDK\n    url: https://blockfrost.dev/sdks\n    title: Official SDKs\n  - type: SpectralRules\n    url: rules/blockfrost-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/blockfrost-cardano-explorer.yaml\n  - type: Vocabulary\n    url: vocabulary/blockfrost-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Cardano Blockchain Access\n   \
  \     description: >-\n          Query blocks, transactions, slots, epochs, accounts, and addresses on the\n          Cardano mainnet and testnet networks.\n      - name: Native Asset Support\n        description: >-\n          Full support for Cardano native assets including fungible tokens, NFTs,\n          and multi-asset UTXOs with on-chain metadata (CIP-25, CIP-68).\n      - name: Stake Pool and Delegation Data\n        description: >-\n          Query stake pool information, delegation history, rewards, and account\n          activity for Cardano staking workflows.\n      - name: Governance Data\n        description: >-\n          Access Cardano governance data including proposals, DRep registrations,\n          and voting activity introduced in the Conway era.\n      - name: IPFS Integration\n        description: >-\n          Built-in IPFS API for storing and retrieving off-chain NFT metadata and\n          other content via Blockfrost's IPFS gateway.\n      - name: Multi-Network\
  \ Support\n        description: >-\n          Single API surface covering Cardano mainnet, preview testnet, preprod\n          testnet, and the Midnight blockchain.\n      - name: Transaction Submission\n        description: >-\n          Submit signed transactions directly to the Cardano network via the\n          Blockfrost API without running a local node.\n  - type: UseCases\n    data:\n      - name: dApp Development\n        description: >-\n          Developers build Cardano dApps using Blockfrost to query blockchain state,\n          submit transactions, and interact with smart contracts.\n      - name: NFT Platform Integration\n        description: >-\n          NFT marketplaces and minting platforms use Blockfrost to track asset minting,\n          transfers, and metadata across the Cardano network.\n      - name: DeFi Protocol Building\n        description: >-\n          DeFi protocols integrate Blockfrost to monitor liquidity pool states,\n          track DEX transactions, and\
  \ manage smart contract interactions.\n      - name: Wallet Development\n        description: >-\n          Cardano wallet applications use Blockfrost to fetch UTXOs, balances,\n          transaction history, and submit transactions.\n      - name: Blockchain Analytics\n        description: >-\n          Analytics platforms query Blockfrost for on-chain data including block\n          history, epoch statistics, and network activity metrics.\n  - type: Integrations\n    data:\n      - name: Mesh SDK\n        description: >-\n          The Mesh JavaScript/TypeScript SDK integrates with Blockfrost as a provider\n          for Cardano dApp development.\n      - name: Lucid Evolution\n        description: >-\n          Lucid Evolution (TypeScript library) supports Blockfrost as a blockchain\n          provider for transaction building and submission.\n      - name: PyCardano\n        description: >-\n          PyCardano Python library uses Blockfrost as a chain context provider for\n      \
  \    Cardano smart contract development.\n      - name: Cardano Serialization Library\n        description: >-\n          The Cardano Serialization Library (CSL) pairs with Blockfrost for\n          transaction construction and UTXO management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/blockfrost/refs/heads/main/apis.yml
tags:
- Blockchain
- Cardano
- Cryptocurrency
- DApps
- NFT
- Web3
url: https://raw.githubusercontent.com/api-evangelist/blockfrost/refs/heads/main/apis.yml
use_cases:
- description: Developers build Cardano dApps using Blockfrost to query blockchain state, submit transactions, and interact with smart contracts.
  name: dApp Development
- description: NFT marketplaces and minting platforms use Blockfrost to track asset minting, transfers, and metadata across the Cardano network.
  name: NFT Platform Integration
- description: DeFi protocols integrate Blockfrost to monitor liquidity pool states, track DEX transactions, and manage smart contract interactions.
  name: DeFi Protocol Building
- description: Cardano wallet applications use Blockfrost to fetch UTXOs, balances, transaction history, and submit transactions.
  name: Wallet Development
- description: Analytics platforms query Blockfrost for on-chain data including block history, epoch statistics, and network activity metrics.
  name: Blockchain Analytics
---
