---
api_count: 1
apis:
- description: The Abacus API provides programmatic access to expense management functionality, including inviting and suspending members, listing and retrieving expense reports, and integrating with third-party pla
  name: Abacus API
  slug: abacus-api
capabilities:
- description: 'Unified workflow for managing employee expenses, reimbursements, and member provisioning. Enables finance teams and administrators to automate expense reporting, track spending by member or category, '
  name: Abacus Expense Management
  slug: expense-management
common:
- title: ''
  type: Website
  url: https://www.abacus.com/
- title: ''
  type: Documentation
  url: https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API
- title: ''
  type: Support
  url: https://support.abacus.com/
- title: ''
  type: PrivacyPolicy
  url: https://legal.emburse.com/
- title: ''
  type: TrustCenter
  url: https://trust.emburse.com/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/rules/abacus-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/vocabulary/abacus-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/capabilities/expense-management.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-ld/abacus-api-context.jsonld
created: '2024-01-15'
description: Abacus (now part of Emburse Spend) is an expense management platform that allows businesses to streamline expense reporting, receipts, and reimbursements. The Abacus API is available to partners and enterprise customers, providing programmatic access to member management and expense operations using OAuth 2.0 authentication.
features:
- description: Invite, update, and suspend organization members programmatically
  name: Member Management
- description: Retrieve and filter expense reports by status, member, and date range
  name: Expense Tracking
- description: Secure API access using client credentials grant flow
  name: OAuth 2.0 Authentication
- description: Link receipts to expense reports via URL references
  name: Receipt Management
- description: Categorize expenses across meals, travel, lodging, office supplies, and software
  name: Multi-category Expenses
- description: Paginated API responses with configurable page sizes
  name: Paginated Results
image: /assets/icons/abacus.png
integrations:
- description: Sync expense data with QuickBooks for accounting reconciliation
  name: QuickBooks
- description: Integrate with Xero for automated expense accounting
  name: Xero
- description: Connect expense reports with NetSuite ERP
  name: NetSuite
- description: Sync expenses with Sage Intacct for financial management
  name: Sage Intacct
jsonld:
- class_count: 8
  name: Abacus Api Context
  property_count: 27
  slug: abacus-api-context
layout: provider
modified: '2026-04-19'
name: Abacus
rules:
- name: Abacus API Rules
  rule_count: 39
  severity_counts:
    error: 13
    hint: 0
    info: 7
    warn: 19
  slug: abacus-spectral-rules
skills: []
slug: abacus
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: abacus\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/apis.yml\nname: Abacus\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accounting\n  - Expense Management\n  - Finance\n  - Reimbursement\ndescription: >-\n  Abacus (now part of Emburse Spend) is an expense management platform that allows businesses to streamline\n  expense reporting, receipts, and reimbursements. The Abacus API is available\n  to partners and enterprise customers, providing programmatic access to member\n  management and expense operations using OAuth 2.0 authentication.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: abacus:abacus-api\n    name: Abacus API\n    tags:\n      - Expenses\n      - Finance\n      - Members\n      - Reimbursement\n    humanURL: https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API\n    baseURL: https://api.abacus.com\n\
  \    properties:\n      - url: https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/openapi/abacus-api-openapi.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-member-schema.json\n        type: JSONSchema\n        title: Member\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-expense-schema.json\n        type: JSONSchema\n        title: Expense\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-invite-member-request-schema.json\n        type: JSONSchema\n        title: Invite Member Request\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-update-member-request-schema.json\n\
  \        type: JSONSchema\n        title: Update Member Request\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-member-list-response-schema.json\n        type: JSONSchema\n        title: Member List Response\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-expense-list-response-schema.json\n        type: JSONSchema\n        title: Expense List Response\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-oauth-token-request-schema.json\n        type: JSONSchema\n        title: OAuth Token Request\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-schema/abacus-oauth-token-response-schema.json\n        type: JSONSchema\n        title: OAuth Token Response\n    description: >-\n      The Abacus API provides programmatic access to expense\
  \ management\n      functionality, including inviting and suspending members, listing and retrieving\n      expense reports, and integrating with third-party platforms. Available to\n      partners and enterprise customers using OAuth 2.0 client credentials.\ncommon:\n  - type: Website\n    url: https://www.abacus.com/\n  - type: Documentation\n    url: https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API\n  - type: Support\n    url: https://support.abacus.com/\n  - type: PrivacyPolicy\n    url: https://legal.emburse.com/\n  - type: TrustCenter\n    url: https://trust.emburse.com/\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/rules/abacus-spectral-rules.yml\n    name: Abacus Spectral Rules\n    type: SpectralRules\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/vocabulary/abacus-vocabulary.yaml\n    name: Abacus Vocabulary\n    type: Vocabulary\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/capabilities/expense-management.yaml\n\
  \    name: Expense Management Capability\n    type: NaftikoCapability\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/json-ld/abacus-api-context.jsonld\n    name: Abacus API JSON-LD Context\n    type: JSONLD\n  - type: Features\n    data:\n      - name: Member Management\n        description: Invite, update, and suspend organization members programmatically\n      - name: Expense Tracking\n        description: Retrieve and filter expense reports by status, member, and date range\n      - name: OAuth 2.0 Authentication\n        description: Secure API access using client credentials grant flow\n      - name: Receipt Management\n        description: Link receipts to expense reports via URL references\n      - name: Multi-category Expenses\n        description: Categorize expenses across meals, travel, lodging, office supplies, and software\n      - name: Paginated Results\n        description: Paginated API responses with configurable page sizes\n\
  \  - type: UseCases\n    data:\n      - name: Employee Onboarding\n        description: Automatically invite new employees to the expense platform via API\n      - name: Employee Offboarding\n        description: Programmatically suspend departed employees from expense access\n      - name: Expense Reconciliation\n        description: Retrieve and reconcile expense reports for accounting integration\n      - name: Spend Analytics\n        description: Pull expense data by category, member, or date range for reporting\n      - name: Third-party Integration\n        description: Connect Abacus expense data with ERP and accounting systems\n  - type: Integrations\n    data:\n      - name: QuickBooks\n        description: Sync expense data with QuickBooks for accounting reconciliation\n      - name: Xero\n        description: Integrate with Xero for automated expense accounting\n      - name: NetSuite\n        description: Connect expense reports with NetSuite ERP\n      - name: Sage Intacct\n\
  \        description: Sync expenses with Sage Intacct for financial management\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/apis.yml
tags:
- Accounting
- Expense Management
- Finance
- Reimbursement
url: https://raw.githubusercontent.com/api-evangelist/abacus/refs/heads/main/apis.yml
use_cases:
- description: Automatically invite new employees to the expense platform via API
  name: Employee Onboarding
- description: Programmatically suspend departed employees from expense access
  name: Employee Offboarding
- description: Retrieve and reconcile expense reports for accounting integration
  name: Expense Reconciliation
- description: Pull expense data by category, member, or date range for reporting
  name: Spend Analytics
- description: Connect Abacus expense data with ERP and accounting systems
  name: Third-party Integration
---
