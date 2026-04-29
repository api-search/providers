---
api_count: 1
api_specs:
- filename: chainlens-openapi.yml
  format: yaml
  label: Chainlens Blockchain Explorer API
  slug: chainlens-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chainlens/refs/heads/main/openapi/chainlens-openapi.yml
apis:
- description: 'The Chainlens REST API exposes block explorer data for EVM chains including transactions, internal transactions, events, blocks, addresses, tokens, NFTs, and smart contract metadata. Endpoints follow '
  name: Chainlens Blockchain Explorer API
  slug: chainlens-api
common:
- title: ''
  type: Website
  url: https://www.chainlens.com/
- title: ''
  type: Documentation
  url: https://docs.chainlens.com/
- title: ''
  type: GettingStarted
  url: https://www.chainlens.com/documentation-categories/getting-started
- title: ''
  type: SignUp
  url: https://www.chainlens.com/free-sign-up
- title: ''
  type: Pricing
  url: https://www.chainlens.com/plans
- title: ''
  type: Blog
  url: https://www.chainlens.com/blog
- title: ''
  type: GitHub
  url: https://github.com/web3labs/chainlens-free
- title: ''
  type: ParentCompany
  url: https://www.web3labs.com/
- title: ''
  type: Contact
  url: https://www.chainlens.com/contact
- title: ''
  type: TermsOfService
  url: https://www.chainlens.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.chainlens.com/privacy-policy
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/web3labs/
- title: ''
  type: X
  url: https://x.com/web3labs
- title: ''
  type: Plans
  url: ''
created: '2024-11-07'
description: Chainlens, built by Web3 Labs, is a blockchain explorer and analytics platform for EVM-compatible public and private chains (Ethereum, Hyperledger Besu, Quorum, Polygon, Avalanche, BNB Chain, etc.) as well as Substrate-based chains. It combines a user-friendly block explorer with powerful REST APIs for real-time transaction monitoring, smart contract verification, token and NFT tracking (ERC-20, ERC-721, ERC-1155), and integration of on-chain data with existing analytics and reporting pipelines. The API follows the EIP-3091 block explorer route conventions and is offered both as SaaS and self-hosted.
features:
- name: Block Explorer
- name: Transaction Search
- name: Address Tracking
- name: Internal Transactions
- name: Event Logs
- name: Smart Contract Verification
- name: Token Tracking
- name: NFT Tracking
- name: ERC-20 Support
- name: ERC-721 Support
- name: ERC-1155 Support
- name: EIP-3091 Routes
- name: Real-Time Data
- name: REST API
- name: OpenAPI 3
- name: Analytics Dashboards
- name: Multi-Chain
- name: Private Chain Support
- name: Permissioned Networks
- name: White-Label
- name: Self-Hosted Option
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Ethereum
- name: Hyperledger Besu
- name: Quorum
- name: Polygon
- name: Avalanche
- name: BNB Chain
- name: Arbitrum
- name: Optimism
- name: Base
- name: Substrate
- name: Ink! Smart Contracts
- name: Web3j
- name: MetaMask
- name: Grafana
- name: Elasticsearch
- name: Kafka
layout: provider
modified: '2026-04-23'
name: Chainlens
skills: []
slug: chainlens
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: chainlens\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chainlens/refs/heads/main/apis.yml\nname: Chainlens\nx-type: company\ntags:\n  - Analytics\n  - Blockchain\n  - Block Explorer\n  - Cryptocurrencies\n  - DeFi\n  - Ethereum\n  - EVM\n  - NFTs\n  - Smart Contracts\n  - Web3\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-07'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  Chainlens, built by Web3 Labs, is a blockchain explorer and analytics\n  platform for EVM-compatible public and private chains (Ethereum,\n  Hyperledger Besu, Quorum, Polygon, Avalanche, BNB Chain, etc.) as well\n  as Substrate-based chains. It combines a user-friendly block explorer\n  with powerful REST APIs for real-time transaction monitoring, smart\n  contract verification, token and NFT tracking (ERC-20, ERC-721,\n  ERC-1155), and integration of on-chain data with existing analytics\
  \ and\n  reporting pipelines. The API follows the EIP-3091 block explorer route\n  conventions and is offered both as SaaS and self-hosted.\napis:\n  - aid: chainlens:chainlens-api\n    name: Chainlens Blockchain Explorer API\n    tags:\n      - Blockchain\n      - Block Explorer\n      - EIP-3091\n      - Events\n      - NFTs\n      - Smart Contracts\n      - Tokens\n      - Transactions\n    humanURL: https://www.chainlens.com/\n    baseURL: https://api.chainlens.com\n    properties:\n      - url: https://docs.chainlens.com/\n        type: Documentation\n      - url: https://www.chainlens.com/features/blockchain-api\n        type: Overview\n      - url: openapi/chainlens-openapi.yml\n        type: OpenAPI\n      - url: https://eips.ethereum.org/EIPS/eip-3091\n        type: Specification\n    description: >-\n      The Chainlens REST API exposes block explorer data for EVM chains\n      including transactions, internal transactions, events, blocks,\n      addresses, tokens, NFTs, and\
  \ smart contract metadata. Endpoints\n      follow OpenAPI 3 conventions and the EIP-3091 block explorer route\n      standard, supporting real-time on-chain analytics, wallet\n      inspection, contract verification look-up, and reporting pipelines.\ncommon:\n  - type: Website\n    url: https://www.chainlens.com/\n  - type: Documentation\n    url: https://docs.chainlens.com/\n  - type: GettingStarted\n    url: https://www.chainlens.com/documentation-categories/getting-started\n  - type: SignUp\n    url: https://www.chainlens.com/free-sign-up\n  - type: Pricing\n    url: https://www.chainlens.com/plans\n  - type: Blog\n    url: https://www.chainlens.com/blog\n  - type: GitHub\n    url: https://github.com/web3labs/chainlens-free\n  - type: ParentCompany\n    url: https://www.web3labs.com/\n  - type: Contact\n    url: https://www.chainlens.com/contact\n  - type: TermsOfService\n    url: https://www.chainlens.com/terms\n  - type: PrivacyPolicy\n    url: https://www.chainlens.com/privacy-policy\n\
  \  - type: LinkedIn\n    url: https://www.linkedin.com/company/web3labs/\n  - type: X\n    url: https://x.com/web3labs\n  - name: Features\n    type: Features\n    data:\n      - name: Block Explorer\n      - name: Transaction Search\n      - name: Address Tracking\n      - name: Internal Transactions\n      - name: Event Logs\n      - name: Smart Contract Verification\n      - name: Token Tracking\n      - name: NFT Tracking\n      - name: ERC-20 Support\n      - name: ERC-721 Support\n      - name: ERC-1155 Support\n      - name: EIP-3091 Routes\n      - name: Real-Time Data\n      - name: REST API\n      - name: OpenAPI 3\n      - name: Analytics Dashboards\n      - name: Multi-Chain\n      - name: Private Chain Support\n      - name: Permissioned Networks\n      - name: White-Label\n      - name: Self-Hosted Option\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Real-Time Transaction Monitoring\n      - name: Smart Contract Event Monitoring\n      - name: On-Chain\
  \ Asset Tracking\n      - name: Wallet Portfolio Analytics\n      - name: Regulatory Reporting\n      - name: Compliance Monitoring\n      - name: DeFi Analytics\n      - name: NFT Collection Analytics\n      - name: Enterprise Blockchain Visibility\n      - name: Custom Analytics Integration\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Ethereum\n      - name: Hyperledger Besu\n      - name: Quorum\n      - name: Polygon\n      - name: Avalanche\n      - name: BNB Chain\n      - name: Arbitrum\n      - name: Optimism\n      - name: Base\n      - name: Substrate\n      - name: Ink! Smart Contracts\n      - name: Web3j\n      - name: MetaMask\n      - name: Grafana\n      - name: Elasticsearch\n      - name: Kafka\n  - name: Plans\n    type: Plans\n    data:\n      - name: Free\n      - name: Developer\n      - name: Team\n      - name: Enterprise\n      - name: Self-Hosted\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion:\
  \ '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chainlens/refs/heads/main/apis.yml
tags:
- Analytics
- Blockchain
- Block Explorer
- Cryptocurrencies
- DeFi
- Ethereum
- EVM
- NFTs
- Smart Contracts
- Web3
url: https://raw.githubusercontent.com/api-evangelist/chainlens/refs/heads/main/apis.yml
use_cases:
- name: Real-Time Transaction Monitoring
- name: Smart Contract Event Monitoring
- name: On-Chain Asset Tracking
- name: Wallet Portfolio Analytics
- name: Regulatory Reporting
- name: Compliance Monitoring
- name: DeFi Analytics
- name: NFT Collection Analytics
- name: Enterprise Blockchain Visibility
- name: Custom Analytics Integration
---
