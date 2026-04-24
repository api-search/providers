---
api_count: 23
apis:
- description: Barclays Smartpay Web Payment API enables businesses to accept payments on their website with real-time processing, secure encryption, and fraud prevention.
  name: Barclays Smartpay Web Payment API
  slug: barclaycard-smartpay-web-payment-api
- description: Verify the availability of funds in a Barclays Bank Ireland account in real-time.
  name: Barclays Bank Ireland Confirmation of Funds API
  slug: barclays-bank-ireland-confirmation-of-funds-api
- description: Access and manage account information and transaction history through UK Open Banking standards.
  name: Barclays Account and Transactions API
  slug: account-and-transactions-api
- description: Securely access and retrieve account information from Barclays Bank Ireland accounts.
  name: Barclays Bank Ireland Account Information API
  slug: barclays-bank-ireland-account-information-api
- description: Initiate payments from Barclays Bank Ireland accounts via PSD2-compliant API.
  name: Barclays Bank Ireland Payment Initiation API
  slug: barclays-bank-ireland-payment-initiation-api
- description: Verify the availability of funds in a Barclays account in real-time.
  name: Barclays Confirmation of Funds API
  slug: confirmation-of-funds-api
- description: Manage customer consent for third-party access to Barclays account data.
  name: Barclays Consent API
  slug: consent-api
- description: Programmatically register TPP client applications with Barclays for Open Banking access.
  name: Barclays Dynamic Client Registration API
  slug: dynamic-client-registration-api
- description: Receive real-time webhook notifications for account and transaction events.
  name: Barclays Event Notification API
  slug: event-notification-api
- description: Securely initiate and authorize payments from Barclays accounts via Open Banking.
  name: Barclays Payment Initiation API
  slug: payment-initiation-api
- description: Find the nearest Barclays ATMs with details on available services and operating hours.
  name: Barclays ATM Locator API
  slug: atm-locator-api
- description: Find Barclays bank branches with addresses, phone numbers, and operating hours.
  name: Barclays Branch Locator API
  slug: branch-locator-api
- description: Access Barclays FCA-mandated service performance metrics data.
  name: Barclays FCA Service Metrics API
  slug: fca-service-metrics-api
- description: Access detailed information about Barclays banking products including rates, fees, and eligibility.
  name: Barclays Product Details API
  slug: product-details-api
- description: Access and manage Barclays account information via Open Banking standards.
  name: Barclays Accounts API
  slug: accounts-api
- description: Secure OAuth2 authentication for accessing Barclays Open Banking APIs.
  name: Barclays Authentication API
  slug: authentication-api
- description: Integrate credit card application functionality with real-time status updates.
  name: Barclays Card Application API
  slug: card-application-api
- description: Secure cryptographic key exchange for encrypted API communication with Barclays.
  name: Barclays Cryptography Key Exchange API
  slug: cryptography-key-exchange-api
- description: Integrate digital wallet functionality for mobile payments and account management.
  name: Barclays Digital Wallet API
  slug: digital-wallet-api
- description: Securely make and receive payments with fraud detection and real-time tracking.
  name: Barclays Payments API
  slug: payments-api
- description: Integrate loyalty programs and sync rewards data with Barclays customer accounts.
  name: Barclays Rewards Loyalty Sync API
  slug: rewards-loyalty-sync-api
- description: Enable customers to pay with Barclays Rewards points at merchant point-of-sale.
  name: Barclays Rewards Pay with Points API
  slug: rewards-pay-with-points-api
- description: Access detailed transaction history and spending analytics for Barclays accounts.
  name: Barclays Transactions API
  slug: transactions-api
capabilities:
- description: ''
  name: Open Banking
  slug: open-banking
common:
- title: ''
  type: Portal
  url: https://developer.barclays.com/
- title: ''
  type: Documentation
  url: https://developer.barclays.com/catalogue
- title: ''
  type: Support
  url: https://developer.barclays.com/support/help-guides
- title: ''
  type: Login
  url: https://developer.barclays.com/login
- title: ''
  type: SignUp
  url: https://drm.developer.barclays.com/s/registration
- title: ''
  type: Knowledgebase
  url: https://developer.barclays.com/support/knowledge-base
- title: ''
  type: TermsOfService
  url: https://developer.barclays.com/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://developer.barclays.com/privacy-policy
- title: ''
  type: SpectralRules
  url: rules/barclays-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/barclays-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/open-banking.yaml
- title: ''
  type: JSON-LD
  url: json-ld/barclays-context.jsonld
created: '2025-02-21'
description: Barclays is a multinational financial services company providing retail and commercial banking, investment banking, wealth management, and credit cards. The Barclays API Exchange (developer.barclays.com) offers 22+ APIs covering open banking account information, payment initiation, confirmation of funds, ATM/branch location, rewards, digital wallet, and more, compliant with UK Open Banking and EU PSD2 standards.
features:
- description: PSD2 and UK Open Banking compliant account balance and transaction access.
  name: Open Banking Account Information
- description: Secure third-party payment initiation from customer accounts.
  name: Payment Initiation
- description: Real-time verification of available funds for payment authorization.
  name: Confirmation of Funds
- description: Location services for Barclays ATMs and branches worldwide.
  name: ATM and Branch Locator
- description: Real-time webhook notifications for account and transaction events.
  name: Event Notifications
- description: Automated TPP registration for Open Banking API access.
  name: Dynamic Client Registration
- description: Loyalty program integration and pay-with-points capabilities.
  name: Rewards and Loyalty
- description: Mobile payment and digital wallet integration.
  name: Digital Wallet
- description: Credit card application submission and status tracking.
  name: Card Applications
- description: Mandated service performance metrics for regulatory reporting.
  name: FCA Compliance Metrics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Barclays Context
  property_count: 17
  slug: barclays-context
layout: provider
modified: '2026-04-21'
name: Barclays
rules:
- name: Barclays API Rules
  rule_count: 7
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 1
  slug: barclays-spectral-rules
skills: []
slug: barclays
solutions: []
tags:
- Banking
- Credit Cards
- Finance
- Open Banking
- Payments
- PSD2
- UK Banking
url: https://raw.githubusercontent.com/api-evangelist/barclays/refs/heads/main/apis.yml
use_cases:
- description: Aggregate Barclays account data in budgeting and financial planning apps.
  name: Personal Finance Management
- description: Initiate payments directly from customer bank accounts via PSD2.
  name: Open Banking Payments
- description: Accept Barclays-branded payments via Smartpay Web Payment API.
  name: E-Commerce Checkout
- description: Embed ATM and branch location search in apps and websites.
  name: Branch and ATM Finder
- description: Integrate Barclays Rewards with merchant loyalty programs.
  name: Loyalty Integration
- description: Enable online credit card applications through partner platforms.
  name: Credit Card Origination
---
