---
api_count: 1
api_specs:
- filename: bank-of-america-cashpro-api-openapi.yml
  format: yaml
  label: Bank of America CashPro API
  slug: cashpro-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bank-of-america/refs/heads/main/openapi/bank-of-america-cashpro-api-openapi.yml
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
source_filename: apis.yml
source_yaml: "aid: bank-of-america\nurl: https://raw.githubusercontent.com/api-evangelist/bank-of-america/refs/heads/main/apis.yml\nname: Bank of America\ntags:\n  - Banking\n  - Corporate Banking\n  - Finance\n  - Payments\n  - Treasury\n  - CashPro\nmodified: '2026-04-21'\ndescription: >-\n  Bank of America is a multinational investment bank and financial services holding company\n  providing consumer banking, wealth management, corporate banking, and investment banking\n  services worldwide. The CashPro Developer Studio provides REST APIs for corporate treasury\n  clients to automate account management, payments, balance reporting, and statement access,\n  supporting over 350 payment types and integration with TMS and ERP platforms.\napis:\n  - aid: bank-of-america:cashpro-api\n    name: Bank of America CashPro API\n    tags:\n      - Accounts\n      - Balances\n      - Banking\n      - Corporate Banking\n      - Payments\n      - Statements\n      - Treasury\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.bankofamerica.com/cashpro/v1\n    humanURL: https://developer.bankofamerica.com/\n    properties:\n      - url: https://developer.bankofamerica.com/\n        type: Documentation\n      - url: openapi/bank-of-america-cashpro-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bank of America CashPro API enables corporate treasury clients to programmatically\n      access banking services including payments, account information, balance reporting,\n      and transaction history. The API supports over 350 payment types and integrates with\n      Treasury Management Systems (TMS) and ERP platforms.\ncommon:\n  - type: Website\n    url: https://www.bankofamerica.com/\n    name: Bank of America\n  - type: Documentation\n    url: https://developer.bankofamerica.com/\n    name: CashPro Developer Studio\n  - type: SignUp\n    url: https://developer.bankofamerica.com/\n    name: Developer Portal\n  - type: Blog\n    url: https://newsroom.bankofamerica.com/\n\
  \    name: Newsroom\n  - type: TermsOfService\n    url: https://www.bankofamerica.com/online-banking/digital-banking-agreement.go\n    name: Digital Banking Agreement\n  - type: PrivacyPolicy\n    url: https://www.bankofamerica.com/security-center/overview.go\n    name: Privacy Policy\n  - type: SpectralRules\n    url: rules/bank-of-america-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/bank-of-america-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/treasury-banking.yaml\n  - type: JSON-LD\n    url: json-ld/bank-of-america-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Account Management\n        description: Programmatic access to CashPro account details and metadata.\n      - name: Balance Reporting\n        description: Real-time ledger, available, and collected balance queries.\n      - name: Transaction History\n        description: Paginated transaction history with date range filtering.\n      - name: Payment Initiation\n\
  \        description: Initiate payments across 350+ payment types including ACH, wire, SWIFT, and RTP.\n      - name: Payment Status Tracking\n        description: Real-time payment status monitoring and cancellation support.\n      - name: Statement Access\n        description: Programmatic retrieval of monthly account statements.\n      - name: OAuth2 Security\n        description: Client credentials OAuth2 flow for secure API access.\n      - name: TMS/ERP Integration\n        description: Pre-built connectors for 28+ Treasury Management and ERP platforms.\n      - name: Sandbox Environment\n        description: Developer sandbox for testing and accelerated onboarding.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Treasury Automation\n        description: Automate daily cash positioning, balance reporting, and payment workflows.\n      - name: ERP Integration\n        description: Connect SAP, Oracle, or other ERP systems to Bank of America CashPro.\n      - name:\
  \ Payments Hub\n        description: Centralize payment initiation across ACH, wire, SWIFT, and real-time payment rails.\n      - name: Liquidity Management\n        description: Real-time visibility into global account balances for liquidity decisions.\n      - name: Reconciliation\n        description: Automated transaction download for account reconciliation workflows.\n      - name: Cash Concentration\n        description: Sweep and concentration account management via API.\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: SAP\n      - name: Oracle\n      - name: Kyriba\n      - name: Sage Intacct\n      - name: Microsoft Dynamics\n      - name: Coupa\n      - name: Workday\ncreated: '2024-01-01'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bank-of-america/refs/heads/main/apis.yml
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
