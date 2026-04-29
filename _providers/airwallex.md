---
api_count: 6
apis:
- description: The Airwallex Payment Acceptance API enables businesses to accept online payments globally. Supports credit and debit cards, local payment methods, and 3D Secure. Available as hosted checkout or embed
  name: Airwallex Payment Acceptance API
  slug: payment-acceptance
- description: The Airwallex Global Accounts API enables businesses to create and manage multi-currency accounts. Supports account creation, balance management, account statements, and receiving funds in multiple cu
  name: Airwallex Global Accounts API
  slug: global-accounts
- description: The Airwallex Payouts API enables businesses to send cross-border payments to suppliers, contractors, and employees globally. Supports bank transfers to 150+ countries, bulk payouts, and beneficiary m
  name: Airwallex Payouts API
  slug: payouts
- description: The Airwallex FX API provides access to real-time foreign exchange rates and currency conversion. Supports spot conversions, rate quotes, and conversion history for 60+ currencies.
  name: Airwallex FX API
  slug: fx
- description: The Airwallex Issuing API enables businesses to create and manage virtual and physical corporate cards for employee spending. Supports card issuance, spend controls, transaction management, and expens
  name: Airwallex Issuing API
  slug: issuing
- description: The Airwallex Platform API enables businesses to embed financial services into their products. Supports merchant onboarding, sub-account management, platform payments, and split payouts for marketplac
  name: Airwallex Platform API
  slug: platform
capabilities:
- description: ''
  name: Payments Management
  slug: payments-management
common:
- title: ''
  type: Portal
  url: https://www.airwallex.com
- title: ''
  type: GettingStarted
  url: https://www.airwallex.com/docs/api
- title: ''
  type: Documentation
  url: https://www.airwallex.com/docs/api#/Introduction
- title: ''
  type: Authentication
  url: https://www.airwallex.com/docs/api#/Payment_Acceptance/Authentication
- title: ''
  type: Pricing
  url: https://www.airwallex.com/pricing
- title: ''
  type: TermsOfService
  url: https://www.airwallex.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.airwallex.com/privacy
- title: ''
  type: Blog
  url: https://www.airwallex.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/airwallex
- title: Airwallex CLI
  type: CLI
  url: https://github.com/airwallex/airwallex-cli
- title: Magento Plugin
  type: SDK
  url: https://github.com/airwallex/paymentacceptance-plugin-magento
- title: Salesforce Commerce Cloud
  type: SDK
  url: https://github.com/airwallex/airwallex-salesforce-commerce-cloud-cartridge
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/rules/airwallex-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/capabilities/payments-management.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/vocabulary/airwallex-vocabulary.yaml
created: '2025-02-17'
description: Airwallex is a financial technology company that specializes in providing global payment solutions for businesses. Their platform enables companies to accept payments, manage multi-currency accounts, convert currencies at competitive rates, send cross-border payments, issue corporate cards, and embed financial services into their own products. Airwallex serves businesses in over 150 countries with APIs for payment acceptance, FX, accounts, transfers, and embedded finance.
features:
- description: Accept payments in 180+ currencies via cards and local payment methods.
  name: Global Payment Acceptance
- description: Hold, manage, and convert funds in 60+ currencies.
  name: Multi-Currency Accounts
- description: Send payments to 150+ countries with competitive FX rates.
  name: Cross-Border Payouts
- description: Real-time currency conversion at competitive exchange rates.
  name: FX Conversion
- description: Issue virtual and physical Visa cards for employee spending.
  name: Corporate Card Issuing
- description: Embed Airwallex financial services into your own platform.
  name: Embedded Finance
- description: iOS, Android, React Native, and Flutter SDKs for in-app payments.
  name: Mobile SDKs
- description: Real-time event notifications for payment status changes.
  name: Webhooks
- description: Built-in fraud detection and risk scoring via the Airwallex Risk SDK.
  name: Risk Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Airwallex payment plugin for Magento/Adobe Commerce stores.
  name: Magento
- description: Airwallex payment cartridge for Salesforce Commerce Cloud.
  name: Salesforce Commerce Cloud
- description: Payment gateway plugin for WooCommerce stores.
  name: WooCommerce
- description: Sync Airwallex transactions with Xero accounting software.
  name: Xero
- description: Accounting integration for Airwallex transactions.
  name: QuickBooks
- description: ERP integration for Airwallex payment data.
  name: NetSuite
jsonld:
- class_count: 6
  name: Airwallex Context
  property_count: 19
  slug: airwallex-context
layout: provider
modified: '2026-04-19'
name: Airwallex
rules:
- name: Airwallex API Rules
  rule_count: 29
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 14
  slug: airwallex-spectral-rules
skills: []
slug: airwallex
solutions: []
source_yaml: "aid: airwallex\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/apis.yml\napis:\n- aid: airwallex:payment-acceptance\n  name: Airwallex Payment Acceptance API\n  tags:\n  - Payments\n  - Checkout\n  - Cards\n  - Online Payments\n  humanURL: https://www.airwallex.com/docs/api#/Introduction\n  baseURL: https://api.airwallex.com/api/v1\n  description: The Airwallex Payment Acceptance API enables businesses to accept online payments globally. Supports credit and debit cards, local payment methods, and 3D Secure. Available as hosted \n    checkout or embedded via Drop-in UI, Payment Elements, and mobile SDKs for iOS, Android, React Native, and Flutter.\n  properties:\n  - url: https://www.airwallex.com/docs/api#/Introduction\n    type: Documentation\n  - url: https://www.airwallex.com/docs/api#/Payment_Acceptance\n    type: APIReference\n  - url: https://www.airwallex.com/docs/api#/Payment_Acceptance/Authentication\n    type: Authentication\n\
  \  - url: https://github.com/airwallex/airwallex-payment-android\n    type: SDK\n    title: Android SDK\n  - url: https://github.com/airwallex/airwallex-payment-ios\n    type: SDK\n    title: iOS SDK\n  - url: https://github.com/airwallex/airwallex-payment-react-native\n    type: SDK\n    title: React Native SDK\n  - url: https://github.com/airwallex/airwallex-payment-flutter\n    type: SDK\n    title: Flutter SDK\n- aid: airwallex:global-accounts\n  name: Airwallex Global Accounts API\n  tags:\n  - Accounts\n  - Multi-Currency\n  - Banking\n  - FX\n  humanURL: https://www.airwallex.com/docs/api#/Accounts\n  baseURL: https://api.airwallex.com/api/v1\n  description: The Airwallex Global Accounts API enables businesses to create and manage multi-currency accounts. Supports account creation, balance management, account statements, and receiving funds\n    in multiple currencies with local bank details.\n  properties:\n  - url: https://www.airwallex.com/docs/api#/Accounts\n    type: Documentation\n\
  \  - url: https://www.airwallex.com/docs/api#/Accounts\n    type: APIReference\n- aid: airwallex:payouts\n  name: Airwallex Payouts API\n  tags:\n  - Payouts\n  - Cross-Border Payments\n  - Transfers\n  - International\n  humanURL: https://www.airwallex.com/docs/api#/Payouts\n  baseURL: https://api.airwallex.com/api/v1\n  description: The Airwallex Payouts API enables businesses to send cross-border payments to suppliers, contractors, and employees globally. Supports bank transfers to 150+ countries, bulk payouts, \n    and beneficiary management.\n  properties:\n  - url: https://www.airwallex.com/docs/api#/Payouts\n    type: Documentation\n  - url: https://www.airwallex.com/docs/api#/Payouts\n    type: APIReference\n  - url: https://github.com/airwallex/payouts-web-sdk\n    type: SDK\n    title: Payouts Web SDK\n- aid: airwallex:fx\n  name: Airwallex FX API\n  tags:\n  - Foreign Exchange\n  - Currency Conversion\n  - FX\n  humanURL: https://www.airwallex.com/docs/api#/FX\n  baseURL: https://api.airwallex.com/api/v1\n\
  \  description: The Airwallex FX API provides access to real-time foreign exchange rates and currency conversion. Supports spot conversions, rate quotes, and conversion history for 60+ currencies.\n  properties:\n  - url: https://www.airwallex.com/docs/api#/FX\n    type: Documentation\n  - url: https://www.airwallex.com/docs/api#/FX\n    type: APIReference\n- aid: airwallex:issuing\n  name: Airwallex Issuing API\n  tags:\n  - Cards\n  - Corporate Cards\n  - Issuing\n  - Expense Management\n  humanURL: https://www.airwallex.com/docs/api#/Issuing\n  baseURL: https://api.airwallex.com/api/v1\n  description: The Airwallex Issuing API enables businesses to create and manage virtual and physical corporate cards for employee spending. Supports card issuance, spend controls, transaction \n    management, and expense reporting.\n  properties:\n  - url: https://www.airwallex.com/docs/api#/Issuing\n    type: Documentation\n  - url: https://www.airwallex.com/docs/api#/Issuing\n    type: APIReference\n\
  - aid: airwallex:platform\n  name: Airwallex Platform API\n  tags:\n  - Embedded Finance\n  - Platform\n  - Marketplace\n  - Split Payments\n  humanURL: https://www.airwallex.com/docs/api#/Platform\n  baseURL: https://api.airwallex.com/api/v1\n  description: The Airwallex Platform API enables businesses to embed financial services into their products. Supports merchant onboarding, sub-account management, platform payments, and split payouts\n    for marketplace and SaaS platforms.\n  properties:\n  - url: https://www.airwallex.com/docs/api#/Platform\n    type: Documentation\n  - url: https://www.airwallex.com/docs/api#/Platform\n    type: APIReference\n  - url: https://github.com/airwallex/platform-onboarding-sdk\n    type: SDK\n    title: Platform Onboarding SDK\nname: Airwallex\ntags:\n- Cross-Border Payments\n- FinTech\n- Foreign Exchange\n- Payments\n- Global\n- Embedded Finance\n- Multi-Currency\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  Airwallex is a financial technology company that specializes in providing global payment solutions for businesses. Their platform enables companies to accept payments, manage multi-currency accounts,\n  convert currencies at competitive rates, send cross-border payments, issue corporate cards, and embed financial services into their own products. Airwallex serves businesses in over 150 countries with\n  APIs for payment acceptance, FX, accounts, transfers, and embedded finance.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n- url: https://www.airwallex.com\n  type: Portal\n- url: https://www.airwallex.com/docs/api\n  type: GettingStarted\n- url: https://www.airwallex.com/docs/api#/Introduction\n  type: Documentation\n- url: https://www.airwallex.com/docs/api#/Payment_Acceptance/Authentication\n  type: Authentication\n- url: https://www.airwallex.com/pricing\n\
  \  type: Pricing\n- url: https://www.airwallex.com/terms\n  type: TermsOfService\n- url: https://www.airwallex.com/privacy\n  type: PrivacyPolicy\n- url: https://www.airwallex.com/blog\n  type: Blog\n- url: https://github.com/airwallex\n  type: GitHubOrganization\n- url: https://github.com/airwallex/airwallex-cli\n  type: CLI\n  title: Airwallex CLI\n- url: https://github.com/airwallex/paymentacceptance-plugin-magento\n  type: SDK\n  title: Magento Plugin\n- url: https://github.com/airwallex/airwallex-salesforce-commerce-cloud-cartridge\n  type: SDK\n  title: Salesforce Commerce Cloud\n- type: Features\n  data:\n  - name: Global Payment Acceptance\n    description: Accept payments in 180+ currencies via cards and local payment methods.\n  - name: Multi-Currency Accounts\n    description: Hold, manage, and convert funds in 60+ currencies.\n  - name: Cross-Border Payouts\n    description: Send payments to 150+ countries with competitive FX rates.\n  - name: FX Conversion\n    description:\
  \ Real-time currency conversion at competitive exchange rates.\n  - name: Corporate Card Issuing\n    description: Issue virtual and physical Visa cards for employee spending.\n  - name: Embedded Finance\n    description: Embed Airwallex financial services into your own platform.\n  - name: Mobile SDKs\n    description: iOS, Android, React Native, and Flutter SDKs for in-app payments.\n  - name: Webhooks\n    description: Real-time event notifications for payment status changes.\n  - name: Risk Management\n    description: Built-in fraud detection and risk scoring via the Airwallex Risk SDK.\n- type: UseCases\n  data:\n  - name: E-Commerce Checkout\n    description: Accept global payments on e-commerce stores and marketplaces.\n  - name: Cross-Border B2B Payments\n    description: Pay international suppliers and contractors efficiently.\n  - name: Employee Expense Management\n    description: Issue cards and track employee spending globally.\n  - name: Multi-Currency Treasury\n    description:\
  \ Manage treasury operations across multiple currencies.\n  - name: Marketplace Split Payments\n    description: Collect and distribute payments to marketplace sellers.\n  - name: SaaS Platform Monetization\n    description: Embed payment processing into SaaS platforms.\n  - name: Freelancer Payouts\n    description: Pay remote workers and freelancers in their local currencies.\n- type: Integrations\n  data:\n  - name: Magento\n    description: Airwallex payment plugin for Magento/Adobe Commerce stores.\n  - name: Salesforce Commerce Cloud\n    description: Airwallex payment cartridge for Salesforce Commerce Cloud.\n  - name: WooCommerce\n    description: Payment gateway plugin for WooCommerce stores.\n  - name: Xero\n    description: Sync Airwallex transactions with Xero accounting software.\n  - name: QuickBooks\n    description: Accounting integration for Airwallex transactions.\n  - name: NetSuite\n    description: ERP integration for Airwallex payment data.\n- url: >-\n    https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/rules/airwallex-spectral-rules.yml\n\
  \  type: SpectralRules\n- url: >-\n    https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/capabilities/payments-management.yaml\n  type: NaftikoCapability\n- url: >-\n    https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/vocabulary/airwallex-vocabulary.yaml\n  type: Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/apis.yml
tags:
- Cross-Border Payments
- FinTech
- Foreign Exchange
- Payments
- Global
- Embedded Finance
- Multi-Currency
url: https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/apis.yml
use_cases:
- description: Accept global payments on e-commerce stores and marketplaces.
  name: E-Commerce Checkout
- description: Pay international suppliers and contractors efficiently.
  name: Cross-Border B2B Payments
- description: Issue cards and track employee spending globally.
  name: Employee Expense Management
- description: Manage treasury operations across multiple currencies.
  name: Multi-Currency Treasury
- description: Collect and distribute payments to marketplace sellers.
  name: Marketplace Split Payments
- description: Embed payment processing into SaaS platforms.
  name: SaaS Platform Monetization
- description: Pay remote workers and freelancers in their local currencies.
  name: Freelancer Payouts
---
