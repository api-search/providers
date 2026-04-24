---
api_count: 1
apis:
- description: 'The Bank of America CashPro API enables corporate treasury clients to programmatically access banking services including payments, account information, balance reporting, and transaction history. The '
  name: Bank of America CashPro API
  slug: cashpro-api
capabilities:
- description: 'Bank of America CashPro treasury banking workflow for corporate clients covering account management, balance reporting, payment initiation, and statement access. Integrates with TMS and ERP platforms '
  name: Bank of America CashPro Treasury Banking
  slug: treasury-banking
common:
- title: ''
  type: Website
  url: https://www.bankofamerica.com/
- title: ''
  type: Documentation
  url: https://developer.bankofamerica.com/
- title: ''
  type: SignUp
  url: https://developer.bankofamerica.com/
- title: ''
  type: Blog
  url: https://newsroom.bankofamerica.com/
- title: ''
  type: TermsOfService
  url: https://www.bankofamerica.com/online-banking/digital-banking-agreement.go
- title: ''
  type: PrivacyPolicy
  url: https://www.bankofamerica.com/security-center/overview.go
- title: ''
  type: SpectralRules
  url: rules/bank-of-america-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bank-of-america-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/treasury-banking.yaml
- title: ''
  type: JSON-LD
  url: json-ld/bank-of-america-context.jsonld
created: '2024-01-01'
description: Bank of America is a multinational investment bank and financial services holding company providing consumer banking, wealth management, corporate banking, and investment banking services worldwide. The CashPro Developer Studio provides REST APIs for corporate treasury clients to automate account management, payments, balance reporting, and statement access, supporting over 350 payment types and integration with TMS and ERP platforms.
features:
- description: Programmatic access to CashPro account details and metadata.
  name: Account Management
- description: Real-time ledger, available, and collected balance queries.
  name: Balance Reporting
- description: Paginated transaction history with date range filtering.
  name: Transaction History
- description: Initiate payments across 350+ payment types including ACH, wire, SWIFT, and RTP.
  name: Payment Initiation
- description: Real-time payment status monitoring and cancellation support.
  name: Payment Status Tracking
- description: Programmatic retrieval of monthly account statements.
  name: Statement Access
- description: Client credentials OAuth2 flow for secure API access.
  name: OAuth2 Security
- description: Pre-built connectors for 28+ Treasury Management and ERP platforms.
  name: TMS/ERP Integration
- description: Developer sandbox for testing and accelerated onboarding.
  name: Sandbox Environment
image: ''
integrations:
- name: SAP
- name: Oracle
- name: Kyriba
- name: Sage Intacct
- name: Microsoft Dynamics
- name: Coupa
- name: Workday
jsonld:
- class_count: 0
  name: Bank Of America Context
  property_count: 65
  slug: bank-of-america-context
layout: provider
modified: '2026-04-21'
name: Bank of America
rules:
- name: Bank of America API Rules
  rule_count: 16
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 6
  slug: bank-of-america-spectral-rules
skills: []
slug: bank-of-america
solutions: []
tags:
- Banking
- Corporate Banking
- Finance
- Payments
- Treasury
- CashPro
url: https://raw.githubusercontent.com/api-evangelist/bank-of-america/refs/heads/main/apis.yml
use_cases:
- description: Automate daily cash positioning, balance reporting, and payment workflows.
  name: Treasury Automation
- description: Connect SAP, Oracle, or other ERP systems to Bank of America CashPro.
  name: ERP Integration
- description: Centralize payment initiation across ACH, wire, SWIFT, and real-time payment rails.
  name: Payments Hub
- description: Real-time visibility into global account balances for liquidity decisions.
  name: Liquidity Management
- description: Automated transaction download for account reconciliation workflows.
  name: Reconciliation
- description: Sweep and concentration account management via API.
  name: Cash Concentration
---
