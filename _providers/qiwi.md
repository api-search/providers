---
api_count: 10
apis:
- description: Protocol for accepting Qiwi payments from wallet, card, and account sources, including payment confirmation, status checks, and reconciliation.
  name: Qiwi Payment Protocol
  slug: qiwi-payment-protocol
- description: API for legal entities to issue payouts to wallets, cards, and bank accounts with batch and individual transfer support.
  name: Qiwi Legal Entity Payouts
  slug: qiwi-legal-entity-payouts
- description: API for sending payouts directly to Qiwi wallets.
  name: Qiwi Wallet Payouts
  slug: qiwi-wallet-payouts
- description: API for issuing payouts to bank cards, wallets, and SBP (Faster Payments System) recipients.
  name: Qiwi Card Wallet SBP Payouts
  slug: qiwi-card-wallet-sbp-payouts
- description: API for topping up mobile phone balances across telecom operators.
  name: Qiwi Mobile Topups
  slug: qiwi-mobile-topups
- description: Banking-as-a-Service platform for issuing accounts, cards, and banking operations on top of Qiwi infrastructure.
  name: Qiwi Banking Platform
  slug: qiwi-baas
- description: API for client identification and KYC verification workflows.
  name: Qiwi Client Identification Service
  slug: qiwi-identification-service
- description: API to retrieve Qiwi terminal locations and their service capabilities.
  name: Qiwi Terminal Map
  slug: qiwi-terminal-map
- description: Personal Qiwi Wallet API for managing balance, transfers, payments, and transaction history for end users.
  name: Qiwi Wallet Personal
  slug: qiwi-wallet-personal
- description: Peer-to-peer payment API for accepting payments from individuals via payment forms and invoices.
  name: Qiwi P2P Payments
  slug: qiwi-p2p-payments
common:
- title: ''
  type: Portal
  url: https://developer.qiwi.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/QIWI-API
- title: ''
  type: Website
  url: https://qiwi.com
- title: ''
  type: Support
  url: https://qiwi.com/support
- title: ''
  type: TermsOfService
  url: https://qiwi.com/legal
created: '2026-03-16'
description: Qiwi provides payment reception, payouts, and banking platform APIs for processing wallet, card, mobile, and SBP transactions across Russia and CIS markets.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Qiwi
skills: []
slug: qiwi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: qiwi\nname: Qiwi\ndescription: >-\n  Qiwi provides payment reception, payouts, and banking platform APIs for\n  processing wallet, card, mobile, and SBP transactions across Russia and CIS\n  markets.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Payments\n  - Wallet\n  - Payouts\n  - Fintech\n  - Banking\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/qiwi/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: qiwi:qiwi-payment-protocol\n    name: Qiwi Payment Protocol\n    description: >-\n      Protocol for accepting Qiwi payments from wallet, card, and account\n      sources, including payment confirmation, status checks, and reconciliation.\n    humanURL: https://developer.qiwi.com/ru/payments/\n    tags:\n      - Payments\n      - Acceptance\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/payments/\n\
  \  - aid: qiwi:qiwi-legal-entity-payouts\n    name: Qiwi Legal Entity Payouts\n    description: >-\n      API for legal entities to issue payouts to wallets, cards, and bank\n      accounts with batch and individual transfer support.\n    humanURL: https://developer.qiwi.com/ru/payout/v2/\n    tags:\n      - Payouts\n      - B2B\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/payout/v2/\n  - aid: qiwi:qiwi-wallet-payouts\n    name: Qiwi Wallet Payouts\n    description: API for sending payouts directly to Qiwi wallets.\n    humanURL: https://developer.qiwi.com/ru/topup-wallet/\n    tags:\n      - Payouts\n      - Wallet\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/topup-wallet/\n  - aid: qiwi:qiwi-card-wallet-sbp-payouts\n    name: Qiwi Card Wallet SBP Payouts\n    description: >-\n      API for issuing payouts to bank cards, wallets, and SBP (Faster Payments\n      System) recipients.\n    humanURL:\
  \ https://developer.qiwi.com/ru/topup-card/\n    tags:\n      - Payouts\n      - Cards\n      - SBP\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/topup-card/\n  - aid: qiwi:qiwi-mobile-topups\n    name: Qiwi Mobile Topups\n    description: API for topping up mobile phone balances across telecom operators.\n    humanURL: https://developer.qiwi.com/ru/topup-mobile/\n    tags:\n      - Payouts\n      - Mobile\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/topup-mobile/\n  - aid: qiwi:qiwi-baas\n    name: Qiwi Banking Platform\n    description: >-\n      Banking-as-a-Service platform for issuing accounts, cards, and banking\n      operations on top of Qiwi infrastructure.\n    humanURL: https://developer.qiwi.com/baas/\n    tags:\n      - Banking\n      - BaaS\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/baas/\n  - aid: qiwi:qiwi-identification-service\n    name:\
  \ Qiwi Client Identification Service\n    description: API for client identification and KYC verification workflows.\n    humanURL: https://developer.qiwi.com/ru/identification-service/\n    tags:\n      - KYC\n      - Identification\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/identification-service/\n  - aid: qiwi:qiwi-terminal-map\n    name: Qiwi Terminal Map\n    description: API to retrieve Qiwi terminal locations and their service capabilities.\n    humanURL: https://developer.qiwi.com/ru/qiwi-map/\n    tags:\n      - Terminals\n      - Locations\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/qiwi-map/\n  - aid: qiwi:qiwi-wallet-personal\n    name: Qiwi Wallet Personal\n    description: >-\n      Personal Qiwi Wallet API for managing balance, transfers, payments, and\n      transaction history for end users.\n    humanURL: https://developer.qiwi.com/ru/qiwi-wallet-personal/\n    tags:\n      -\
  \ Wallet\n      - Personal\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/qiwi-wallet-personal/\n  - aid: qiwi:qiwi-p2p-payments\n    name: Qiwi P2P Payments\n    description: >-\n      Peer-to-peer payment API for accepting payments from individuals via\n      payment forms and invoices.\n    humanURL: https://developer.qiwi.com/ru/p2p-payments/\n    tags:\n      - Payments\n      - P2P\n    properties:\n      - type: Documentation\n        url: https://developer.qiwi.com/ru/p2p-payments/\ncommon:\n  - type: Portal\n    url: https://developer.qiwi.com\n  - type: GitHubOrganization\n    url: https://github.com/QIWI-API\n  - type: Website\n    url: https://qiwi.com\n  - type: Support\n    url: https://qiwi.com/support\n  - type: TermsOfService\n    url: https://qiwi.com/legal\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qiwi/refs/heads/main/apis.yml
tags:
- Payments
- Wallet
- Payouts
- Fintech
- Banking
url: https://raw.githubusercontent.com/api-evangelist/qiwi/refs/heads/main/apis.yml
use_cases: []
---
