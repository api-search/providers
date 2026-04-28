---
api_count: 10
apis:
- description: Create and manage server-side wallets where the application controls private keys via Circle's secure key management. Supports balances, transfers, signing, and webhook notifications.
  name: Developer-Controlled Wallets
  slug: developer-controlled-wallets
- description: Create wallets that end users control via PIN, biometrics, or social recovery while Circle handles the cryptography. Used to embed non-custodial USDC wallets directly inside consumer apps.
  name: User-Controlled Wallets
  slug: user-controlled-wallets
- description: Sponsor gas fees on behalf of users or let users pay gas in USDC via Circle Paymaster, removing native-token friction from onboarding.
  name: Gas Station and Paymaster
  slug: gas-station
- description: Burn-and-mint protocol for moving native USDC between supported blockchains without wrapped assets. Provides REST endpoints for attestations and a Bridge Kit SDK for frontend integration.
  name: Cross-Chain Transfer Protocol (CCTP)
  slug: cctp
- description: Unified USDC balance across multiple EVM chains and support for nanopayments down to $0.000001 of USDC.
  name: Circle Gateway
  slug: gateway
- description: Deploy, query, and interact with smart contracts across supported blockchains, including ERC-20 and ERC-721 templates and arbitrary contract calls.
  name: Smart Contract Platform
  slug: smart-contract-platform
- description: A network for regulated financial institutions to settle cross-border payments using USDC, with originating and beneficiary financial institution (OFI/BFI) APIs.
  name: Circle Payments Network (CPN)
  slug: cpn
- description: Screen wallet addresses and transactions against sanctions lists and risk signals; configure rule sets and review queues for AML programs.
  name: Compliance Engine
  slug: compliance-engine
- description: Stablecoin foreign-exchange trading API on the Arc blockchain for converting between USDC, EURC, and other regulated stablecoins.
  name: StableFX
  slug: stablefx
- description: Issue and redeem regulated stablecoins backed by USDC reserves; manage minting, burning, and reserve attestations.
  name: xReserve
  slug: xreserve
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.circle.com/
- title: ''
  type: Portal
  url: https://developers.circle.com/
- title: ''
  type: Console
  url: https://console.circle.com/
- title: ''
  type: Authentication
  url: https://developers.circle.com/w3s/authentication
- title: ''
  type: Getting Started
  url: https://developers.circle.com/w3s/getting-started
- title: ''
  type: Status
  url: https://status.circle.com/
- title: ''
  type: Support
  url: https://support.usdc.circle.com/
- title: ''
  type: Blog
  url: https://www.circle.com/blog
- title: ''
  type: Community
  url: https://discord.com/invite/buildoncircle
- title: ''
  type: GitHub Organization
  url: https://github.com/circlefin
- title: ''
  type: Privacy Policy
  url: https://www.circle.com/legal/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.circle.com/legal/terms-of-service
- title: ''
  type: JSON-LD
  url: json-ld/circle-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/circle-wallet-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/circle-transaction-schema.json
- title: ''
  type: Spectral
  url: rules/circle-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/circle-capabilities.yml
created: '2024-11-07'
description: Circle Internet Financial is the issuer of USDC and EURC and operates a developer platform for moving regulated stablecoin money across the internet. Their APIs cover programmable wallets (developer- and user-controlled), gas sponsorship, the Cross-Chain Transfer Protocol (CCTP), Gateway unified balances, the Smart Contract Platform, the Circle Payments Network (CPN) for cross-border payments, compliance, StableFX trading on Arc, and xReserve for issuing USDC-backed stablecoins.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Circle Context
  property_count: 6
  slug: circle-context
layout: provider
modified: '2026-04-23'
name: Circle
rules:
- name: Circle API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 4
  slug: circle-rules
skills: []
slug: circle
solutions: []
tags:
- Blockchain
- Compliance
- Cross-Chain
- Currency
- Money
- Payments
- Stablecoin
- Transfers
- USDC
- Wallets
url: https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/apis.yml
use_cases: []
---
