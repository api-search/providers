---
api_count: 1
apis:
- description: BANCOMAT Pay is a mobile payment service enabling Italian consumers to make e-commerce purchases and P2P transfers through a smartphone app linked to their bank account by phone number and IBAN. Merch
  name: BANCOMAT Pay
  slug: bancomat-pay
capabilities:
- description: ''
  name: Bancomat Payment Capability
  slug: bancomat-payment-capability
common:
- title: ''
  type: Website
  url: https://bancomat.it/en
- title: ''
  type: Website
  url: https://bancomat.it/en/the-company
- title: ''
  type: SpectralRules
  url: rules/bancomat-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bancomat-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/bancomat-payment-capability.yaml
- title: ''
  type: JSON-LD
  url: json-ld/bancomat-context.jsonld
created: '2024-01-15'
description: BANCOMAT S.p.A. is Italy's leading payment network operator managing the PagoBancomat debit card scheme, ATM network, and BANCOMAT Pay mobile payment service. Launched in 1983 for ATM withdrawals and expanded in 1986 with PagoBancomat for PIN-based POS payments, the network underpins Italian electronic payment infrastructure. BANCOMAT Pay, introduced in 2019, enables mobile e-commerce and P2P payments linked to bank accounts via phone number and IBAN.
features:
- description: Italy's largest ATM cash withdrawal network operational since 1983.
  name: ATM Network
- description: PIN-based POS debit card payments accepted at millions of Italian merchants.
  name: PagoBancomat Debit
- description: Mobile app payment service for e-commerce and P2P transfers linked to bank accounts.
  name: BANCOMAT Pay Mobile
- description: QR code-based checkout integration for online and in-store merchants.
  name: QR Code Payments
- description: Deep integration with Italian banks enabling account-linked payment authorization.
  name: Bank Integration
- description: Person-to-person money transfers between Italian bank accounts via mobile app.
  name: P2P Transfers
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration via Nexi XPay Global payment gateway for merchant acceptance.
  name: Nexi
- description: Integration via Axerve/Fabrick for Italian e-commerce BANCOMAT Pay acceptance.
  name: Axerve (Fabrick)
- description: Integration via PPRO for international PSP access to BANCOMAT Pay.
  name: PPRO
- description: Integration via HiPay payment platform.
  name: HiPay
- description: Integration via Viva.com payment services.
  name: Viva.com
- description: Integration via PayPal Braintree payment gateway.
  name: PayPal Braintree
- description: Integration via Nuvei payment technology platform.
  name: Nuvei
jsonld:
- class_count: 0
  name: Bancomat Context
  property_count: 15
  slug: bancomat-context
layout: provider
modified: '2026-04-21'
name: Bancomat
rules:
- name: Bancomat API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: bancomat-spectral-rules
skills: []
slug: bancomat
solutions: []
tags:
- ATM
- Banking
- Financial Services
- Italy
- Mobile Payments
- Payments
- Debit Cards
url: https://raw.githubusercontent.com/api-evangelist/bancomat/refs/heads/main/apis.yml
use_cases:
- description: Debit card ATM withdrawals across Italy's national banking network.
  name: ATM Cash Withdrawals
- description: PIN-based debit card payments at retail point-of-sale terminals.
  name: POS Debit Payments
- description: Online checkout integration via BANCOMAT Pay mobile app.
  name: E-Commerce Payments
- description: Person-to-person payments between bank accounts via mobile app.
  name: P2P Money Transfer
- description: Enable BANCOMAT Pay as a local Italian payment method for online stores.
  name: Merchant Acceptance
---
