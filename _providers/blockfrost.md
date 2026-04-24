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
