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
source_filename: apis.yml
source_yaml: "aid: circle\nname: Circle\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/apis.yml\ntags:\n  - Blockchain\n  - Compliance\n  - Cross-Chain\n  - Currency\n  - Money\n  - Payments\n  - Stablecoin\n  - Transfers\n  - USDC\n  - Wallets\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-07'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  Circle Internet Financial is the issuer of USDC and EURC and operates a\n  developer platform for moving regulated stablecoin money across the\n  internet. Their APIs cover programmable wallets (developer- and\n  user-controlled), gas sponsorship, the Cross-Chain Transfer Protocol\n  (CCTP), Gateway unified balances, the Smart Contract Platform, the Circle\n  Payments Network (CPN) for cross-border payments, compliance, StableFX\n  trading on Arc, and xReserve for issuing USDC-backed\
  \ stablecoins.\napis:\n  - aid: circle:developer-controlled-wallets\n    name: Developer-Controlled Wallets\n    tags:\n      - Custody\n      - USDC\n      - Wallets\n    humanURL: https://developers.circle.com/w3s/programmable-wallets\n    baseURL: https://api.circle.com/v1/w3s\n    properties:\n      - url: https://developers.circle.com/w3s/programmable-wallets\n        type: Documentation\n      - url: https://developers.circle.com/openapi/developer-controlled-wallets.yaml\n        type: OpenAPI\n    description: >-\n      Create and manage server-side wallets where the application controls\n      private keys via Circle's secure key management. Supports balances,\n      transfers, signing, and webhook notifications.\n  - aid: circle:user-controlled-wallets\n    name: User-Controlled Wallets\n    tags:\n      - Custody\n      - End-User\n      - USDC\n      - Wallets\n    humanURL: https://developers.circle.com/w3s/user-controlled-wallets\n    baseURL: https://api.circle.com/v1/w3s\n\
  \    properties:\n      - url: https://developers.circle.com/w3s/user-controlled-wallets\n        type: Documentation\n      - url: https://developers.circle.com/openapi/user-controlled-wallets.yaml\n        type: OpenAPI\n    description: >-\n      Create wallets that end users control via PIN, biometrics, or social\n      recovery while Circle handles the cryptography. Used to embed\n      non-custodial USDC wallets directly inside consumer apps.\n  - aid: circle:gas-station\n    name: Gas Station and Paymaster\n    tags:\n      - Gas Sponsorship\n      - Paymaster\n      - USDC\n    humanURL: https://developers.circle.com/w3s/gas-station\n    baseURL: https://api.circle.com/v1/w3s\n    properties:\n      - url: https://developers.circle.com/w3s/gas-station\n        type: Documentation\n    description: >-\n      Sponsor gas fees on behalf of users or let users pay gas in USDC via\n      Circle Paymaster, removing native-token friction from onboarding.\n  - aid: circle:cctp\n    name:\
  \ Cross-Chain Transfer Protocol (CCTP)\n    tags:\n      - Bridging\n      - Cross-Chain\n      - USDC\n    humanURL: https://developers.circle.com/cctp\n    properties:\n      - url: https://developers.circle.com/cctp\n        type: Documentation\n      - url: https://developers.circle.com/openapi/cctp.yaml\n        type: OpenAPI\n    description: >-\n      Burn-and-mint protocol for moving native USDC between supported\n      blockchains without wrapped assets. Provides REST endpoints for\n      attestations and a Bridge Kit SDK for frontend integration.\n  - aid: circle:gateway\n    name: Circle Gateway\n    tags:\n      - Cross-Chain\n      - Liquidity\n      - USDC\n    humanURL: https://developers.circle.com/gateway\n    properties:\n      - url: https://developers.circle.com/gateway\n        type: Documentation\n      - url: https://developers.circle.com/openapi/gateway.yaml\n        type: OpenAPI\n    description: >-\n      Unified USDC balance across multiple EVM chains and support\
  \ for\n      nanopayments down to $0.000001 of USDC.\n  - aid: circle:smart-contract-platform\n    name: Smart Contract Platform\n    tags:\n      - Contracts\n      - EVM\n      - Web3\n    humanURL: https://developers.circle.com/w3s/smart-contract-platform\n    baseURL: https://api.circle.com/v1/w3s\n    properties:\n      - url: https://developers.circle.com/w3s/smart-contract-platform\n        type: Documentation\n      - url: https://developers.circle.com/openapi/smart-contract-platform.yaml\n        type: OpenAPI\n    description: >-\n      Deploy, query, and interact with smart contracts across supported\n      blockchains, including ERC-20 and ERC-721 templates and arbitrary\n      contract calls.\n  - aid: circle:cpn\n    name: Circle Payments Network (CPN)\n    tags:\n      - Cross-Border\n      - Payments\n      - Settlement\n    humanURL: https://developers.circle.com/cpn\n    properties:\n      - url: https://developers.circle.com/cpn\n        type: Documentation\n      -\
  \ url: https://developers.circle.com/openapi/cpn-ofi.yaml\n        type: OpenAPI\n    description: >-\n      A network for regulated financial institutions to settle cross-border\n      payments using USDC, with originating and beneficiary financial\n      institution (OFI/BFI) APIs.\n  - aid: circle:compliance-engine\n    name: Compliance Engine\n    tags:\n      - AML\n      - Compliance\n      - Risk\n    humanURL: https://developers.circle.com/w3s/compliance-engine\n    properties:\n      - url: https://developers.circle.com/w3s/compliance-engine\n        type: Documentation\n      - url: https://developers.circle.com/openapi/compliance.yaml\n        type: OpenAPI\n    description: >-\n      Screen wallet addresses and transactions against sanctions lists and\n      risk signals; configure rule sets and review queues for AML programs.\n  - aid: circle:stablefx\n    name: StableFX\n    tags:\n      - Arc\n      - FX\n      - Trading\n    humanURL: https://developers.circle.com/stablefx\n\
  \    properties:\n      - url: https://developers.circle.com/stablefx\n        type: Documentation\n      - url: https://developers.circle.com/openapi/stablefx.yaml\n        type: OpenAPI\n    description: >-\n      Stablecoin foreign-exchange trading API on the Arc blockchain for\n      converting between USDC, EURC, and other regulated stablecoins.\n  - aid: circle:xreserve\n    name: xReserve\n    tags:\n      - Issuance\n      - Reserves\n      - Stablecoin\n    humanURL: https://developers.circle.com/xreserve\n    properties:\n      - url: https://developers.circle.com/xreserve\n        type: Documentation\n      - url: https://developers.circle.com/openapi/xreserve.yaml\n        type: OpenAPI\n    description: >-\n      Issue and redeem regulated stablecoins backed by USDC reserves;\n      manage minting, burning, and reserve attestations.\ncommon:\n  - type: Website\n    url: https://www.circle.com/\n  - type: Portal\n    url: https://developers.circle.com/\n  - type: Console\n\
  \    url: https://console.circle.com/\n  - type: Authentication\n    url: https://developers.circle.com/w3s/authentication\n  - type: Getting Started\n    url: https://developers.circle.com/w3s/getting-started\n  - type: Status\n    url: https://status.circle.com/\n  - type: Support\n    url: https://support.usdc.circle.com/\n  - type: Blog\n    url: https://www.circle.com/blog\n  - type: Community\n    url: https://discord.com/invite/buildoncircle\n  - type: GitHub Organization\n    url: https://github.com/circlefin\n  - type: Privacy Policy\n    url: https://www.circle.com/legal/privacy-policy\n  - type: Terms of Service\n    url: https://www.circle.com/legal/terms-of-service\n  - type: JSON-LD\n    url: json-ld/circle-context.jsonld\n  - type: JSONSchema\n    url: json-schema/circle-wallet-schema.json\n  - type: JSONSchema\n    url: json-schema/circle-transaction-schema.json\n  - type: Spectral\n    url: rules/circle-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/circle-capabilities.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/apis.yml
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
