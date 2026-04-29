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
source_filename: apis.yml
source_yaml: "aid: authorize-net\nname: Authorize.net\ndescription: |\n  Authorize.net is a leading payment gateway providing secure online payment processing for merchants. It offers a POST-based XML/JSON API, Accept.js hosted payment forms, the Accept Hosted solution, recurring billing (ARB), customer profile management (CIM), advanced fraud detection, and webhooks. Official SDKs are available for PHP, .NET, Java, Ruby, Python, and Node.js.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Accept.js\n- Credit Cards\n- eChecks\n- Fraud Detection\n- Payment Gateway\n- Payments\n- Recurring Billing\n- Transactions\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/authorize-net/refs/heads/main/apis.yml\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: authorize-net:authorize-net-payment-api\n  name: Authorize.net Payment API\n  description: |\n    The Authorize.net Payment API enables\
  \ merchants to process credit card, debit card, eCheck, Apple Pay, Google Pay, and PayPal transactions via a POST-based XML/JSON API with API Login ID and Transaction Key authentication.\n  humanURL: https://developer.authorize.net/api/reference/\n  baseURL: https://api.authorize.net/xml/v1/request.api\n  tags:\n  - Credit Cards\n  - eChecks\n  - Payment Gateway\n  - Transactions\n  properties:\n  - type: Documentation\n    url: https://developer.authorize.net/api/reference/\n  - type: GettingStarted\n    url: https://developer.authorize.net/hello_world/\n  - type: Authentication\n    url: https://developer.authorize.net/api/reference/features/authentication.html\n  - type: APIReference\n    url: https://developer.authorize.net/api/reference/\n  - type: Sandbox\n    url: https://sandbox.authorize.net/\n- aid: authorize-net:authorize-net-recurring-billing-api\n  name: Authorize.net Recurring Billing API\n  description: |\n    The Authorize.net Automated Recurring Billing (ARB) API enables\
  \ merchants to create, update, and cancel subscription-based payment schedules for recurring charges.\n  humanURL: https://developer.authorize.net/api/reference/features/recurring_billing.html\n  baseURL: https://api.authorize.net/xml/v1/request.api\n  tags:\n  - Payment Gateway\n  - Recurring Billing\n  - Subscriptions\n  properties:\n  - type: Documentation\n    url: https://developer.authorize.net/api/reference/features/recurring_billing.html\n- aid: authorize-net:authorize-net-customer-profiles-api\n  name: Authorize.net Customer Profiles API\n  description: |\n    The Authorize.net Customer Information Manager (CIM) API enables secure storage and management of customer payment profiles including credit cards and bank accounts for reuse in future transactions.\n  humanURL: https://developer.authorize.net/api/reference/features/customer_profiles.html\n  baseURL: https://api.authorize.net/xml/v1/request.api\n  tags:\n  - Customer Profiles\n  - Payment Gateway\n  - Tokenization\n  properties:\n\
  \  - type: Documentation\n    url: https://developer.authorize.net/api/reference/features/customer_profiles.html\n- aid: authorize-net:authorize-net-webhooks\n  name: Authorize.net Webhooks\n  description: |\n    Authorize.net Webhooks deliver real-time event notifications for transaction, subscription, and fraud management events to merchant-configured HTTP endpoints.\n  humanURL: https://developer.authorize.net/api/reference/features/webhooks.html\n  baseURL: https://api.authorize.net/rest/v1\n  tags:\n  - Events\n  - Payment Gateway\n  - Webhooks\n  properties:\n  - type: Documentation\n    url: https://developer.authorize.net/api/reference/features/webhooks.html\ncommon:\n- type: Website\n  url: https://www.authorize.net/\n- type: Documentation\n  url: https://developer.authorize.net/\n- type: Portal\n  url: https://developer.authorize.net/\n- type: Blog\n  url: https://developer.authorize.net/blog/\n- type: Sign Up\n  url: https://www.authorize.net/sign-up/\n- type: Login\n  url:\
  \ https://account.authorize.net/\n- type: Pricing\n  url: https://www.authorize.net/sign-up/pricing/\n- type: Support\n  url: https://support.authorize.net/\n- type: Status\n  url: https://status.authorize.net/\n- type: Terms of Service\n  url: https://www.authorize.net/company/terms/\n- type: Privacy Policy\n  url: https://www.authorize.net/company/privacy/\n- type: GitHub Organization\n  url: https://github.com/AuthorizeNet\n- type: SDK\n  title: PHP SDK\n  url: https://github.com/AuthorizeNet/sdk-php\n- type: SDK\n  title: .NET SDK\n  url: https://github.com/AuthorizeNet/sdk-dotnet\n- type: SDK\n  title: Java SDK\n  url: https://github.com/AuthorizeNet/sdk-java\n- type: SDK\n  title: Ruby SDK\n  url: https://github.com/AuthorizeNet/sdk-ruby\n- type: SDK\n  title: Python SDK\n  url: https://github.com/AuthorizeNet/sdk-python\n- type: SDK\n  title: Node.js SDK\n  url: https://github.com/AuthorizeNet/sdk-node\n- type: Features\n  data:\n  - name: Payment Processing\n    description: Accept\
  \ credit cards, debit cards, eChecks, Apple Pay, Google Pay, and PayPal via a single unified API.\n  - name: Accept.js\n    description: Client-side JavaScript library that tokenizes payment data in the browser to keep merchant servers out of PCI scope.\n  - name: Accept Hosted\n    description: Fully hosted payment form that redirects customers to Authorize.net for payment collection with iframe support.\n  - name: Recurring Billing (ARB)\n    description: Automated recurring billing for subscriptions and installment plans with flexible scheduling options.\n  - name: Customer Profiles (CIM)\n    description: Securely vault customer payment methods for future charges without storing sensitive card data.\n  - name: Fraud Detection Suite\n    description: Advanced fraud detection tools including velocity controls, IP blocking, card security code verification, and address verification.\n  - name: Webhooks\n    description: Real-time event notifications for transaction completions, declines,\
  \ fraud holds, and subscription events.\n  - name: MCP Server\n    description: Official Authorize.net MCP server for AI-assisted payment processing integration at github.com/AuthorizeNet/authorize-net-mcp.\n- type: UseCases\n  data:\n  - name: E-Commerce Payment Processing\n    description: Accept payments on web storefronts using Accept.js or Accept Hosted for PCI-compliant card processing.\n  - name: Subscription Billing\n    description: Manage recurring charges for SaaS, membership, and subscription-based business models using ARB.\n  - name: Mobile Payments\n    description: Accept Apple Pay and Google Pay in mobile apps using the in-person and mobile payment SDKs.\n  - name: Point-of-Sale Integration\n    description: Integrate card-present transactions via the iOS, Android, or Windows in-person payment SDKs.\n  - name: B2B and eCheck Payments\n    description: Process ACH/eCheck payments for B2B invoicing and recurring bank account debit scenarios.\n- type: Integrations\n  data:\n\
  \  - name: WooCommerce\n    description: Official Authorize.net WooCommerce payment plugin for WordPress-based e-commerce stores.\n  - name: Medusa\n    description: Official Authorize.net Medusa payment plugin for headless commerce implementations.\n  - name: Visa and Mastercard Networks\n    description: Direct connection to major card networks for authorization and settlement of card-based transactions.\n  - name: NACHA ACH Network\n    description: eCheck processing through the NACHA ACH network for bank-to-bank payment transfers.\n- type: Solutions\n  data:\n  - name: Payment Gateway\n    description: Comprehensive payment gateway solution connecting merchants to card networks with fraud protection and reporting.\n  - name: PCI-Compliant Payments\n    description: Reduce PCI scope using Accept.js or Accept Hosted to tokenize payment data without touching card numbers.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/authorize-net/refs/heads/main/apis.yml
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
