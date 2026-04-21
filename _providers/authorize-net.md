---
api_count: 4
apis:
- description: The Authorize.net Payment API enables merchants to process credit card, debit card, eCheck, Apple Pay, Google Pay, and PayPal transactions via a POST-based XML/JSON API with API Login ID and Transacti
  name: Authorize.net Payment API
  slug: authorize-net-payment-api
- description: The Authorize.net Automated Recurring Billing (ARB) API enables merchants to create, update, and cancel subscription-based payment schedules for recurring charges.
  name: Authorize.net Recurring Billing API
  slug: authorize-net-recurring-billing-api
- description: The Authorize.net Customer Information Manager (CIM) API enables secure storage and management of customer payment profiles including credit cards and bank accounts for reuse in future transactions.
  name: Authorize.net Customer Profiles API
  slug: authorize-net-customer-profiles-api
- description: Authorize.net Webhooks deliver real-time event notifications for transaction, subscription, and fraud management events to merchant-configured HTTP endpoints.
  name: Authorize.net Webhooks
  slug: authorize-net-webhooks
common:
- title: ''
  type: Website
  url: https://www.authorize.net/
- title: ''
  type: Documentation
  url: https://developer.authorize.net/
- title: ''
  type: Portal
  url: https://developer.authorize.net/
- title: ''
  type: Blog
  url: https://developer.authorize.net/blog/
- title: ''
  type: Sign Up
  url: https://www.authorize.net/sign-up/
- title: ''
  type: Login
  url: https://account.authorize.net/
- title: ''
  type: Pricing
  url: https://www.authorize.net/sign-up/pricing/
- title: ''
  type: Support
  url: https://support.authorize.net/
- title: ''
  type: Status
  url: https://status.authorize.net/
- title: ''
  type: Terms of Service
  url: https://www.authorize.net/company/terms/
- title: ''
  type: Privacy Policy
  url: https://www.authorize.net/company/privacy/
- title: ''
  type: GitHub Organization
  url: https://github.com/AuthorizeNet
- title: PHP SDK
  type: SDK
  url: https://github.com/AuthorizeNet/sdk-php
- title: .NET SDK
  type: SDK
  url: https://github.com/AuthorizeNet/sdk-dotnet
- title: Java SDK
  type: SDK
  url: https://github.com/AuthorizeNet/sdk-java
- title: Ruby SDK
  type: SDK
  url: https://github.com/AuthorizeNet/sdk-ruby
- title: Python SDK
  type: SDK
  url: https://github.com/AuthorizeNet/sdk-python
- title: Node.js SDK
  type: SDK
  url: https://github.com/AuthorizeNet/sdk-node
created: '2025-02-17'
description: Authorize.net is a leading payment gateway providing secure online payment processing for merchants. It offers a POST-based XML/JSON API, Accept.js hosted payment forms, the Accept Hosted solution, recurring billing (ARB), customer profile management (CIM), advanced fraud detection, and webhooks. Official SDKs are available for PHP, .NET, Java, Ruby, Python, and Node.js.
features:
- description: Accept credit cards, debit cards, eChecks, Apple Pay, Google Pay, and PayPal via a single unified API.
  name: Payment Processing
- description: Client-side JavaScript library that tokenizes payment data in the browser to keep merchant servers out of PCI scope.
  name: Accept.js
- description: Fully hosted payment form that redirects customers to Authorize.net for payment collection with iframe support.
  name: Accept Hosted
- description: Automated recurring billing for subscriptions and installment plans with flexible scheduling options.
  name: Recurring Billing (ARB)
- description: Securely vault customer payment methods for future charges without storing sensitive card data.
  name: Customer Profiles (CIM)
- description: Advanced fraud detection tools including velocity controls, IP blocking, card security code verification, and address verification.
  name: Fraud Detection Suite
- description: Real-time event notifications for transaction completions, declines, fraud holds, and subscription events.
  name: Webhooks
- description: Official Authorize.net MCP server for AI-assisted payment processing integration at github.com/AuthorizeNet/authorize-net-mcp.
  name: MCP Server
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Authorize.net WooCommerce payment plugin for WordPress-based e-commerce stores.
  name: WooCommerce
- description: Official Authorize.net Medusa payment plugin for headless commerce implementations.
  name: Medusa
- description: Direct connection to major card networks for authorization and settlement of card-based transactions.
  name: Visa and Mastercard Networks
- description: eCheck processing through the NACHA ACH network for bank-to-bank payment transfers.
  name: NACHA ACH Network
layout: provider
modified: '2026-04-19'
name: Authorize.net
skills: []
slug: authorize-net
solutions:
- description: Comprehensive payment gateway solution connecting merchants to card networks with fraud protection and reporting.
  name: Payment Gateway
- description: Reduce PCI scope using Accept.js or Accept Hosted to tokenize payment data without touching card numbers.
  name: PCI-Compliant Payments
tags:
- Accept.js
- Credit Cards
- eChecks
- Fraud Detection
- Payment Gateway
- Payments
- Recurring Billing
- Transactions
url: https://raw.githubusercontent.com/api-evangelist/authorize-net/refs/heads/main/apis.yml
use_cases:
- description: Accept payments on web storefronts using Accept.js or Accept Hosted for PCI-compliant card processing.
  name: E-Commerce Payment Processing
- description: Manage recurring charges for SaaS, membership, and subscription-based business models using ARB.
  name: Subscription Billing
- description: Accept Apple Pay and Google Pay in mobile apps using the in-person and mobile payment SDKs.
  name: Mobile Payments
- description: Integrate card-present transactions via the iOS, Android, or Windows in-person payment SDKs.
  name: Point-of-Sale Integration
- description: Process ACH/eCheck payments for B2B invoicing and recurring bank account debit scenarios.
  name: B2B and eCheck Payments
---
