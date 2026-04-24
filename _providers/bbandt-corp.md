---
api_count: 5
apis:
- description: Provides access to personal and small business account data including account balances, account details, and account lists for authenticated customers. Supports open banking use cases for fintech appl
  name: Truist Personal and Small Business Accounts API
  slug: personal-small-business-accounts
- description: Provides access to transaction history and transaction details for personal and small business bank accounts. Enables fintech applications to retrieve customer transaction data with proper authorizati
  name: Truist Personal and Small Business Transactions API
  slug: personal-small-business-transactions
- description: Provides access to commercial banking account data including account balances, account details, and account management for business customers. Supports treasury management and commercial banking integ
  name: Truist Commercial Accounts API
  slug: commercial-accounts
- description: Provides access to transaction history and transaction details for commercial bank accounts. Supports enterprise financial applications, ERP integrations, and treasury management workflows.
  name: Truist Commercial Account Transactions API
  slug: commercial-account-transactions
- description: Provides banking and payment services APIs for associations, HOAs, and membership organizations. Supports dues collection, payment processing, and financial management for association management compa
  name: Truist Association Services API
  slug: association-services
capabilities:
- description: ''
  name: Open Banking
  slug: open-banking
common:
- title: ''
  type: Portal
  url: https://developer.truist.com/
- title: ''
  type: Website
  url: https://www.truist.com/
- title: ''
  type: Documentation
  url: https://developer.truist.com/api/view-api
- title: ''
  type: GettingStarted
  url: https://developer.truist.com/api/working-with-truist
- title: ''
  type: TermsOfService
  url: https://www.truist.com/terms-and-conditions
- title: ''
  type: PrivacyPolicy
  url: https://www.truist.com/privacy-security
- title: ''
  type: SpectralRules
  url: rules/bbandt-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bbandt-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/open-banking.yaml
- title: ''
  type: JSON-LD
  url: json-ld/bbandt-context.jsonld
created: '2026-03-23'
description: BB&T Corporation was a major financial services holding company that merged with SunTrust Banks in December 2019 to form Truist Financial Corporation. The combined entity operates as Truist Bank and maintains a developer portal at developer.truist.com offering REST APIs for account information, transaction data, and banking services for personal, small business, and commercial customers. The APIs support open banking integrations and financial technology applications.
features:
- description: REST APIs enabling fintech applications to access account and transaction data with customer consent.
  name: Open Banking APIs
- description: APIs for personal and small business banking account access including balances and transaction history.
  name: Personal Banking APIs
- description: APIs for commercial account management, treasury operations, and enterprise banking integrations.
  name: Commercial Banking APIs
- description: Specialized APIs for association management companies to handle dues, payments, and financial reporting.
  name: Association Services
- description: Secure OAuth 2.0 based authentication for customer data access with proper consent flows.
  name: OAuth 2.0 Authentication
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Third-party data aggregator providing alternative connectivity to Truist account data.
  name: Plaid
- description: Open banking platform providing access to Truist banking data via aggregation.
  name: Tink
- description: Accounting software integration for Truist commercial banking customers.
  name: QuickBooks
jsonld:
- class_count: 0
  name: Bbandt Context
  property_count: 11
  slug: bbandt-context
layout: provider
modified: '2026-04-21'
name: BB&T Corp (Truist)
rules:
- name: BB&T Corp (Truist) API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 1
  slug: bbandt-spectral-rules
skills: []
slug: bbandt-corp
solutions: []
tags:
- Banking
- Financial Services
- Open Banking
- Truist
- BB&T
url: https://raw.githubusercontent.com/api-evangelist/bbandt-corp/refs/heads/main/apis.yml
use_cases:
- description: Build personal finance management apps that aggregate account and transaction data for Truist customers.
  name: Personal Finance Apps
- description: Integrate Truist commercial accounts with accounting software like QuickBooks or Xero.
  name: Accounting Software Integration
- description: Enable enterprise treasury teams to access real-time commercial account balances and transaction data.
  name: Treasury Management
- description: Automate dues collection and financial reporting for homeowners associations and membership organizations.
  name: Association Management
---
