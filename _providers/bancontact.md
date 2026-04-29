---
api_count: 1
apis:
- description: REST API for accepting Bancontact payments online and via QR code. Enables merchants to create payment transactions, generate QR codes, handle callbacks, and process refunds. The API is organized arou
  name: Bancontact Payconiq Acceptance API
  slug: payconiq-acceptance-api
capabilities:
- description: ''
  name: Bancontact Payment Capability
  slug: bancontact-payment-capability
common:
- title: ''
  type: Website
  url: https://www.bancontact.com/
- title: ''
  type: Documentation
  url: https://docs.bancontactpro.com/
- title: ''
  type: SpectralRules
  url: rules/bancontact-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bancontact-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/bancontact-payment-capability.yaml
- title: ''
  type: JSON-LD
  url: json-ld/bancontact-context.jsonld
created: '2025-01-01'
description: Bancontact is Belgium's most popular electronic payment system, operating through the Bancontact Payconiq Company (now transitioning to Bancontact Pro brand). The platform provides debit card payments, QR code payments, and mobile payments via the Payconiq by Bancontact app. The REST API enables merchants to accept payments online, in-app, and via QR codes with settlement in Belgian bank accounts.
features:
- description: Accept Bancontact debit card payments in e-commerce checkouts.
  name: Online Payments
- description: Generate QR codes for in-store and contactless payment acceptance.
  name: QR Code Payments
- description: Payconiq by Bancontact app integration for mobile checkout.
  name: Mobile App Payments
- description: Real-time payment status notifications via webhook callbacks.
  name: Webhooks
- description: Programmatic refund processing for completed transactions.
  name: Refunds
- description: EUR-denominated payments with Belgian bank account settlement.
  name: Multi-currency
- description: Mobile deep links to open the Payconiq app directly from merchant checkout.
  name: Deep Links
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Accept Bancontact via Adyen payment gateway.
  name: Adyen
- description: Accept Bancontact via Computop payment platform.
  name: Computop
- description: Access Bancontact via PPRO's local payment method network.
  name: PPRO
- description: Accept Bancontact via Stripe payment infrastructure.
  name: Stripe
- description: Accept Bancontact via Mollie payment service.
  name: Mollie
- description: Accept Bancontact via MultiSafepay payment gateway.
  name: MultiSafepay
jsonld:
- class_count: 0
  name: Bancontact Context
  property_count: 18
  slug: bancontact-context
layout: provider
modified: '2026-04-21'
name: Bancontact
rules:
- name: Bancontact API Rules
  rule_count: 12
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 6
  slug: bancontact-spectral-rules
skills: []
slug: bancontact
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bancontact\nname: Bancontact\ndescription: >-\n  Bancontact is Belgium's most popular electronic payment system, operating through the\n  Bancontact Payconiq Company (now transitioning to Bancontact Pro brand). The platform\n  provides debit card payments, QR code payments, and mobile payments via the Payconiq\n  by Bancontact app. The REST API enables merchants to accept payments online, in-app,\n  and via QR codes with settlement in Belgian bank accounts.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Belgium\n  - Debit Cards\n  - E-Commerce\n  - Fintech\n  - Payments\nurl: https://raw.githubusercontent.com/api-evangelist/bancontact/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: bancontact:payconiq-acceptance-api\n    name: Bancontact Payconiq Acceptance API\n    description: >-\n      REST API for accepting Bancontact payments\
  \ online and via QR code. Enables merchants\n      to create payment transactions, generate QR codes, handle callbacks, and process\n      refunds. The API is organized around REST with HTTP response codes, header authentication,\n      and standard HTTP verbs. Transitioning to Bancontact Pro branding in 2026.\n    humanURL: https://docs.bancontactpro.com/\n    tags:\n      - Checkout\n      - Payments\n      - QR Code\n      - Transactions\n      - Refunds\n    properties:\n      - type: Documentation\n        url: https://docs.bancontactpro.com/\n      - type: Documentation\n        url: https://docs.payconiq.be/\n        name: Legacy Payconiq Documentation\ncommon:\n  - type: Website\n    url: https://www.bancontact.com/\n    name: Bancontact\n  - type: Documentation\n    url: https://docs.bancontactpro.com/\n    name: Bancontact Pro Developer Portal\n  - type: SpectralRules\n    url: rules/bancontact-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/bancontact-vocabulary.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/bancontact-payment-capability.yaml\n  - type: JSON-LD\n    url: json-ld/bancontact-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Online Payments\n        description: Accept Bancontact debit card payments in e-commerce checkouts.\n      - name: QR Code Payments\n        description: Generate QR codes for in-store and contactless payment acceptance.\n      - name: Mobile App Payments\n        description: Payconiq by Bancontact app integration for mobile checkout.\n      - name: Webhooks\n        description: Real-time payment status notifications via webhook callbacks.\n      - name: Refunds\n        description: Programmatic refund processing for completed transactions.\n      - name: Multi-currency\n        description: EUR-denominated payments with Belgian bank account settlement.\n      - name: Deep Links\n        description: Mobile deep links to open the Payconiq app directly from merchant checkout.\n\
  \  - name: UseCases\n    type: UseCases\n    data:\n      - name: E-Commerce Checkout\n        description: Accept Bancontact as a local Belgian payment method at checkout.\n      - name: QR Code POS\n        description: In-store and restaurant QR code payment acceptance.\n      - name: Mobile In-App Payments\n        description: Integrate Bancontact into iOS and Android apps.\n      - name: Invoice Payments\n        description: Payment links and QR codes for invoicing and B2C collections.\n      - name: Subscription Billing\n        description: Recurring payment collection from Belgian consumers.\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Adyen\n        description: Accept Bancontact via Adyen payment gateway.\n      - name: Computop\n        description: Accept Bancontact via Computop payment platform.\n      - name: PPRO\n        description: Access Bancontact via PPRO's local payment method network.\n      - name: Stripe\n        description: Accept\
  \ Bancontact via Stripe payment infrastructure.\n      - name: Mollie\n        description: Accept Bancontact via Mollie payment service.\n      - name: MultiSafepay\n        description: Accept Bancontact via MultiSafepay payment gateway.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bancontact/refs/heads/main/apis.yml
tags:
- Banking
- Belgium
- Debit Cards
- E-Commerce
- Fintech
- Payments
url: https://raw.githubusercontent.com/api-evangelist/bancontact/refs/heads/main/apis.yml
use_cases:
- description: Accept Bancontact as a local Belgian payment method at checkout.
  name: E-Commerce Checkout
- description: In-store and restaurant QR code payment acceptance.
  name: QR Code POS
- description: Integrate Bancontact into iOS and Android apps.
  name: Mobile In-App Payments
- description: Payment links and QR codes for invoicing and B2C collections.
  name: Invoice Payments
- description: Recurring payment collection from Belgian consumers.
  name: Subscription Billing
---
