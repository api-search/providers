---
api_count: 1
api_specs:
- filename: basiq-api-openapi.yml
  format: yaml
  label: Basiq API
  slug: basiq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/openapi/basiq-api-openapi.yml
apis:
- description: The Basiq API provides open banking access to Australian and New Zealand bank data. Manage users, bank connections, accounts, transactions, and affordability data (income verification, expense categor
  name: Basiq API
  slug: basiq-api
capabilities:
- description: ''
  name: Open Banking
  slug: open-banking
common:
- title: ''
  type: Website
  url: https://basiq.io/
- title: ''
  type: Documentation
  url: https://api.basiq.io/reference
- title: ''
  type: Website
  url: https://dashboard.basiq.io/
- title: ''
  type: Website
  url: https://basiq.io/pricing/
- title: ''
  type: Blog
  url: https://basiq.io/blog/
- title: ''
  type: Website
  url: https://github.com/basiqio
- title: ''
  type: TermsOfService
  url: https://basiq.io/legal/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://basiq.io/legal/privacy-policy/
- title: ''
  type: SpectralRules
  url: rules/basiq-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/basiq-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/open-banking.yaml
- title: ''
  type: JSON-LD
  url: json-ld/basiq-context.jsonld
created: '2026-03-27'
description: Basiq is an Australian open banking and financial data API platform providing unified access to bank account data and enrichment services. It enables fintechs, lenders, and financial service providers to connect to 180+ Australian and New Zealand banks via CDR (Consumer Data Right) and third-party connectors. The Basiq API provides user management, bank connections, account balances, transaction history, income verification, and expense categorization. Uses JWT Bearer token authentication.
features:
- description: Connect to 180+ Australian and New Zealand banks via CDR and third-party connectors.
  name: Bank Connections
- description: Retrieve real-time account balances, available funds, and account metadata.
  name: Account Data
- description: Access enriched transaction history with categorization and merchant data.
  name: Transaction History
- description: Automated income stream identification and regular/irregular income calculation.
  name: Income Verification
- description: Transaction-based expense categorization for affordability and budgeting analysis.
  name: Expense Categorization
- description: Consumer Data Right (CDR) compliant data access for Australian open banking.
  name: CDR Compliance
- description: Transaction enrichment with merchant names, categories, and subcategories.
  name: Data Enrichment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Xero
- name: MYOB
- name: Salesforce
- name: Zapier
- name: Commonwealth Bank
- name: ANZ
- name: Westpac
- name: NAB
jsonld:
- class_count: 8
  name: Basiq Context
  property_count: 32
  slug: basiq-context
layout: provider
modified: '2026-04-21'
name: Basiq
rules:
- name: Basiq API Rules
  rule_count: 15
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 9
  slug: basiq-spectral-rules
skills: []
slug: basiq
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: basiq\nname: Basiq\ndescription: >-\n  Basiq is an Australian open banking and financial data API platform providing\n  unified access to bank account data and enrichment services. It enables fintechs,\n  lenders, and financial service providers to connect to 180+ Australian and New Zealand\n  banks via CDR (Consumer Data Right) and third-party connectors. The Basiq API provides\n  user management, bank connections, account balances, transaction history, income\n  verification, and expense categorization. Uses JWT Bearer token authentication.\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Australia\n  - Banking\n  - CDR\n  - Financial Data\n  - Fintech\n  - Open Banking\n  - Transactions\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: basiq:basiq-api\n    name:\
  \ Basiq API\n    description: >-\n      The Basiq API provides open banking access to Australian and New Zealand bank\n      data. Manage users, bank connections, accounts, transactions, and affordability\n      data (income verification, expense categorization) via JWT Bearer token authentication.\n    humanURL: https://api.basiq.io/reference\n    tags:\n      - Accounts\n      - Australia\n      - CDR\n      - Financial Data\n      - Open Banking\n      - Transactions\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://au-api.basiq.io\n    properties:\n      - type: Documentation\n        url: https://api.basiq.io/reference\n      - type: Documentation\n        url: https://api.basiq.io/reference/getting-started\n        name: Getting Started\n      - type: OpenAPI\n        url: openapi/basiq-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://basiq.io/\n    name: Basiq\n  - type: Documentation\n    url: https://api.basiq.io/reference\n\
  \    name: API Reference\n  - type: Website\n    url: https://dashboard.basiq.io/\n    name: Developer Dashboard\n  - type: Website\n    url: https://basiq.io/pricing/\n    name: Pricing\n  - type: Blog\n    url: https://basiq.io/blog/\n    name: Blog\n  - type: Website\n    url: https://github.com/basiqio\n    name: GitHub Organization\n  - type: TermsOfService\n    url: https://basiq.io/legal/terms-of-use/\n    name: Terms of Use\n  - type: PrivacyPolicy\n    url: https://basiq.io/legal/privacy-policy/\n    name: Privacy Policy\n  - type: SpectralRules\n    url: rules/basiq-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/basiq-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/open-banking.yaml\n  - type: JSON-LD\n    url: json-ld/basiq-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Bank Connections\n        description: Connect to 180+ Australian and New Zealand banks via CDR and third-party connectors.\n      - name:\
  \ Account Data\n        description: Retrieve real-time account balances, available funds, and account metadata.\n      - name: Transaction History\n        description: Access enriched transaction history with categorization and merchant data.\n      - name: Income Verification\n        description: Automated income stream identification and regular/irregular income calculation.\n      - name: Expense Categorization\n        description: Transaction-based expense categorization for affordability and budgeting analysis.\n      - name: CDR Compliance\n        description: Consumer Data Right (CDR) compliant data access for Australian open banking.\n      - name: Data Enrichment\n        description: Transaction enrichment with merchant names, categories, and subcategories.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Lending and Credit Assessment\n        description: Use income verification and expense data to assess creditworthiness and affordability.\n      - name:\
  \ Personal Finance Apps\n        description: Aggregate bank accounts and transactions for budgeting and financial planning tools.\n      - name: Mortgage Applications\n        description: Automate bank statement verification and income confirmation for home loan applications.\n      - name: BNPL Affordability\n        description: Assess buy-now-pay-later affordability using real-time transaction and income data.\n      - name: Financial Advisory\n        description: Provide financial planners with complete client financial pictures across institutions.\n      - name: Account Verification\n        description: Verify bank account ownership for payment and identity verification workflows.\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Xero\n      - name: MYOB\n      - name: Salesforce\n      - name: Zapier\n      - name: Commonwealth Bank\n      - name: ANZ\n      - name: Westpac\n      - name: NAB\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/apis.yml
tags:
- Australia
- Banking
- CDR
- Financial Data
- Fintech
- Open Banking
- Transactions
url: https://raw.githubusercontent.com/api-evangelist/basiq/refs/heads/main/apis.yml
use_cases:
- description: Use income verification and expense data to assess creditworthiness and affordability.
  name: Lending and Credit Assessment
- description: Aggregate bank accounts and transactions for budgeting and financial planning tools.
  name: Personal Finance Apps
- description: Automate bank statement verification and income confirmation for home loan applications.
  name: Mortgage Applications
- description: Assess buy-now-pay-later affordability using real-time transaction and income data.
  name: BNPL Affordability
- description: Provide financial planners with complete client financial pictures across institutions.
  name: Financial Advisory
- description: Verify bank account ownership for payment and identity verification workflows.
  name: Account Verification
---
