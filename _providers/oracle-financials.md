---
api_count: 7
api_specs:
- filename: openapi-general-ledger.yaml
  format: yaml
  label: Oracle Financials General Ledger API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-general-ledger.yaml
- filename: openapi-payables.yaml
  format: yaml
  label: Oracle Financials Accounts Payable API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-payables.yaml
- filename: openapi-receivables.yaml
  format: yaml
  label: Oracle Financials Accounts Receivable API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-receivables.yaml
- filename: openapi-cash-management.yaml
  format: yaml
  label: Oracle Financials Cash Management API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-cash-management.yaml
- filename: openapi-expenses.yaml
  format: yaml
  label: Oracle Financials Expense Management API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-expenses.yaml
- filename: openapi-fixed-assets.yaml
  format: yaml
  label: Oracle Financials Fixed Assets API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-fixed-assets.yaml
- filename: openapi-reporting.yaml
  format: yaml
  label: Oracle Financial Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-reporting.yaml
apis:
- description: Manage general ledger operations including journals, account balances, and period closings.
  name: Oracle Financials General Ledger API
  slug: ''
- description: Manage supplier invoices, payments, and expense reports.
  name: Oracle Financials Accounts Payable API
  slug: ''
- description: Manage customer invoices, receipts, and credit management.
  name: Oracle Financials Accounts Receivable API
  slug: ''
- description: Manage cash positioning, bank statements, and reconciliation.
  name: Oracle Financials Cash Management API
  slug: ''
- description: Manage employee expenses, reimbursements, and expense reports.
  name: Oracle Financials Expense Management API
  slug: ''
- description: Manage asset lifecycle, depreciation, and asset transfers.
  name: Oracle Financials Fixed Assets API
  slug: ''
- description: Access financial reports, analytics, and business intelligence data.
  name: Oracle Financial Reporting API
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/getting-started.html
- title: ''
  type: Authentication Guide
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html
- title: ''
  type: Rate Limits
  url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/rate-limits.html
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: Status Page
  url: https://ocistatus.oraclecloud.com
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/corporate/contracts/cloud-services/
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
created: '2024-01-15'
description: Collection of Oracle Financials Cloud APIs for financial management, accounting, and reporting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Oracle Financials
skills: []
slug: oracle-financials
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-financials\nname: Oracle Financials\ndescription: >-\n  Collection of Oracle Financials Cloud APIs for financial management, accounting,\n  and reporting.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-financials/refs/heads/main/apis.yml\ntags:\n  - Accounting\n  - Accounts Payable\n  - Accounts Receivable\n  - Cash Management\n  - ERP\n  - Expense Management\n  - Financial Management\n  - General Ledger\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Oracle Financials General Ledger API\n    description: >-\n      Manage general ledger operations including journals, account balances, and period\n      closings.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://your-instance.fa.us2.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n\
  \    tags:\n      - Account Balances\n      - Chart of Accounts\n      - General Ledger\n      - Journals\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/api-general-ledger.html\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-general-ledger.yaml\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Financials Accounts Payable API\n    description: >-\n      Manage supplier invoices, payments, and expense reports.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://your-instance.fa.us2.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Accounts\
  \ Payable\n      - Invoices\n      - Payments\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/api-payables.html\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-payables.yaml\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Financials Accounts Receivable API\n    description: >-\n      Manage customer invoices, receipts, and credit management.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://your-instance.fa.us2.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Accounts Receivable\n      - Credit Management\n      -\
  \ Customer Invoices\n      - Receipts\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/api-receivables.html\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-receivables.yaml\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Financials Cash Management API\n    description: >-\n      Manage cash positioning, bank statements, and reconciliation.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://your-instance.fa.us2.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Bank Accounts\n      - Cash Forecasting\n      - Cash Management\n      - Reconciliation\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/api-cash-management.html\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-cash-management.yaml\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Financials Expense Management API\n    description: >-\n      Manage employee expenses, reimbursements, and expense reports.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://your-instance.fa.us2.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Corporate Cards\n      - Expense Management\n      - Expense Reports\n      - Reimbursements\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/api-expenses.html\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-expenses.yaml\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Financials Fixed Assets API\n    description: >-\n      Manage asset lifecycle, depreciation, and asset transfers.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://your-instance.fa.us2.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Asset Management\n      - Asset Tracking\n      - Depreciation\n      - Fixed Assets\n    properties:\n      - type: Documentation\n        url:\
  \ https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/api-fixed-assets.html\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-fixed-assets.yaml\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Financial Reporting API\n    description: >-\n      Access financial reports, analytics, and business intelligence data.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://your-instance.fa.us2.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Financial Reports\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/api-financial-reporting.html\n\
  \      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/openapi-reporting.yaml\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\ncommon:\n  - type: Getting Started\n    url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/getting-started.html\n  - type: Authentication Guide\n    url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/Authentication.html\n  - type: Rate Limits\n    url: https://docs.oracle.com/en/cloud/saas/financials/23r3/farfa/rate-limits.html\n  - type: Support\n    url: https://support.oracle.com\n  - type: Status Page\n    url: https://ocistatus.oraclecloud.com\n  - type: Terms of Service\n    url: https://www.oracle.com/corporate/contracts/cloud-services/\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-financials/refs/heads/main/apis.yml
tags:
- Accounting
- Accounts Payable
- Accounts Receivable
- Cash Management
- ERP
- Expense Management
- Financial Management
- General Ledger
url: https://raw.githubusercontent.com/api-evangelist/oracle-financials/refs/heads/main/apis.yml
use_cases: []
---
