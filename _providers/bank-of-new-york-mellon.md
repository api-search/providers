---
api_count: 1
apis:
- description: The BNY Mellon Treasury Services API enables institutional clients to programmatically initiate and track payments (wire, ACH, SWIFT, CHIPS), access account balances and transaction history, and manag
  name: BNY Mellon Treasury Services API
  slug: treasury-services-api
capabilities:
- description: 'BNY Mellon treasury operations workflow for institutional clients covering account management, balance reporting, payment initiation, funds transfers, and transaction history. Integrates with TMS and '
  name: BNY Mellon Treasury Operations
  slug: treasury-operations
common:
- title: ''
  type: Website
  url: https://www.bnymellon.com/
- title: ''
  type: Documentation
  url: https://marketplace.bnymellon.com/treasury/api-central/
- title: ''
  type: Documentation
  url: https://developer.bny.com/app/
- title: ''
  type: PrivacyPolicy
  url: https://www.bnymellon.com/us/en/disclaimers/privacy-notice.html
- title: ''
  type: SpectralRules
  url: rules/bny-mellon-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bny-mellon-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/treasury-operations.yaml
- title: ''
  type: JSON-LD
  url: json-ld/bny-mellon-context.jsonld
created: '2024-01-01'
description: BNY Mellon is a global investments company providing asset servicing, asset management, wealth management, treasury services, and clearance and collateral management for institutions and individuals. The BNY Mellon Marketplace (marketplace.bnymellon.com) and developer portal (developer.bny.com) provide Treasury Services APIs for corporate clients to automate payments, account management, balance reporting, and funds transfers.
features:
- description: Access institutional account details and metadata.
  name: Account Management
- description: Real-time and intraday account balance queries.
  name: Balance Reporting
- description: Detailed transaction history with date range filtering.
  name: Transaction History
- description: Initiate wire, ACH, SWIFT, and CHIPS payments globally.
  name: Payment Initiation
- description: Internal account-to-account funds transfer management.
  name: Funds Transfers
- description: Client credentials OAuth2 flow for secure API access.
  name: OAuth2 Security
- description: UAT sandbox for developer testing and integration validation.
  name: Sandbox Environment
- description: Support for payments and balances across multiple currencies.
  name: Multi-Currency
image: ''
integrations:
- name: SAP
- name: Oracle
- name: Kyriba
- name: FIS Quantum
- name: ION Treasury
- name: Workday
- name: Reval
jsonld:
- class_count: 0
  name: Bny Mellon Context
  property_count: 54
  slug: bny-mellon-context
layout: provider
modified: '2026-04-21'
name: BNY Mellon
rules:
- name: BNY Mellon API Rules
  rule_count: 16
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 6
  slug: bny-mellon-spectral-rules
skills: []
slug: bank-of-new-york-mellon
solutions: []
tags:
- Asset Servicing
- Banking
- Institutional Banking
- Payments
- Treasury
- Wire Transfers
url: https://raw.githubusercontent.com/api-evangelist/bank-of-new-york-mellon/refs/heads/main/apis.yml
use_cases:
- description: Automate daily cash positioning, balance queries, and payment workflows.
  name: Treasury Automation
- description: Initiate global wire, ACH, and SWIFT payments programmatically.
  name: Payment Processing
- description: Real-time account balance visibility for institutional liquidity decisions.
  name: Liquidity Management
- description: Automated transaction downloads for reconciliation and reporting.
  name: Reconciliation
- description: Connect SAP, Oracle, and other ERP/TMS systems to BNY Mellon treasury APIs.
  name: ERP Integration
- description: Integrate treasury APIs into asset servicing and custody workflows.
  name: Custody Operations
---
