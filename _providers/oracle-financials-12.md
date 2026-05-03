---
api_count: 8
api_specs:
- filename: gl-api.json
  format: json
  label: Oracle General Ledger API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/openapi/gl-api.json
- filename: ap-api.json
  format: json
  label: Oracle Accounts Payable API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/openapi/ap-api.json
- filename: ar-api.json
  format: json
  label: Oracle Accounts Receivable API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/openapi/ar-api.json
apis:
- description: API for managing general ledger operations including journals, budgets, and financial reporting.
  name: Oracle General Ledger API
  slug: ''
- description: API for managing supplier invoices, payments, and payables operations.
  name: Oracle Accounts Payable API
  slug: ''
- description: API for managing customer invoices, receipts, and receivables operations.
  name: Oracle Accounts Receivable API
  slug: ''
- description: API for managing bank accounts, cash positions, and treasury operations.
  name: Oracle Cash Management API
  slug: ''
- description: API for managing fixed assets, depreciation, and asset lifecycle.
  name: Oracle Fixed Assets API
  slug: ''
- description: API for managing purchase orders, requisitions, and procurement operations.
  name: Oracle Purchasing API
  slug: ''
- description: API for managing employee expenses, expense reports, and reimbursements.
  name: Oracle Expenses API
  slug: ''
- description: API for managing projects, project costs, and project billing.
  name: Oracle Projects API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://support.oracle.com
- title: ''
  type: Authentication
  url: https://docs.oracle.com/en/cloud/saas/financials/r13-update17d/fafrs/authentication.html
- title: ''
  type: Rate Limits
  url: https://docs.oracle.com/en/cloud/saas/financials/r13-update17d/fafrs/rate-limits.html
- title: ''
  type: Status
  url: https://status.oracle.com
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
created: '2024-01-15'
description: Collection of REST APIs for Oracle E-Business Suite Financials Release 12.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Oracle Financials 12
skills: []
slug: oracle-financials-12
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-financials-12\nname: Oracle Financials 12\ndescription: >-\n  Collection of REST APIs for Oracle E-Business Suite Financials Release 12.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-financials-12/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Oracle General Ledger API\n    description: >-\n      API for managing general ledger operations including journals, budgets, and\n      financial reporting.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13561/toc.htm\n    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Accounting\n      - Financial Reporting\n      - General Ledger\n      - Journals\n    properties:\n\
  \      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/openapi/gl-api.json\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13561/T302934T531415.htm\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/r13-update17d/fafrs/authentication.html\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle Accounts Payable API\n    description: >-\n      API for managing supplier invoices, payments, and payables operations.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13533/toc.htm\n    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Accounts Payable\n      - Invoices\n      - Payments\n      - Suppliers\n    properties:\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/openapi/ap-api.json\n\
  \      - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13533/T302934T531415.htm\n      - type: API Guide\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e20280/toc.htm\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle Accounts Receivable API\n    description: >-\n      API for managing customer invoices, receipts, and receivables operations.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13522/toc.htm\n    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Accounts Receivable\n      - Collections\n      - Customer Invoices\n      - Receipts\n    properties:\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/openapi/ar-api.json\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13522/T302934T531415.htm\n\
  \      - type: API Guide\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e20281/toc.htm\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle Cash Management API\n    description: >-\n      API for managing bank accounts, cash positions, and treasury operations.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13540/toc.htm\n    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Bank Accounts\n      - Cash Management\n      - Reconciliation\n      - Treasury\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13540/T302934T531415.htm\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/r13-update17d/fafrs/api-cash-management.html\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name:\
  \ Oracle Fixed Assets API\n    description: >-\n      API for managing fixed assets, depreciation, and asset lifecycle.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13549/toc.htm\n    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Asset Management\n      - Capital Assets\n      - Depreciation\n      - Fixed Assets\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13549/T302934T531415.htm\n      - type: API Guide\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e20282/toc.htm\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle Purchasing API\n    description: >-\n      API for managing purchase orders, requisitions, and procurement operations.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13513/toc.htm\n\
  \    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Procurement\n      - Purchase Orders\n      - Purchasing\n      - Requisitions\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13513/T302934T531415.htm\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/procurement/r13-update17d/oaprc/api-purchasing.html\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle Expenses API\n    description: >-\n      API for managing employee expenses, expense reports, and reimbursements.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13548/toc.htm\n    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Expense Reports\n      - Expenses\n      - Reimbursements\n      - Travel\n    properties:\n    \
  \  - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13548/T302934T531415.htm\n      - type: API Guide\n        url: https://docs.oracle.com/en/cloud/saas/financials/r13-update17d/fafrs/api-expenses.html\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle Projects API\n    description: >-\n      API for managing projects, project costs, and project billing.\n    image: https://www.oracle.com/a/ocom/img/oracle-financials-icon.png\n    humanUrl: https://docs.oracle.com/cd/E18727_01/doc.121/e13523/toc.htm\n    baseUrl: https://your-instance.oracle.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Contracts\n      - Project Billing\n      - Project Costing\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E18727_01/doc.121/e13523/T302934T531415.htm\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/project-management/r13-update17d/oapjm/api-projects.html\n\
  \    contact:\n      - type: Support\n        url: https://support.oracle.com\ncommon:\n  - type: Portal\n    url: https://support.oracle.com\n  - type: Authentication\n    url: https://docs.oracle.com/en/cloud/saas/financials/r13-update17d/fafrs/authentication.html\n  - type: Rate Limits\n    url: https://docs.oracle.com/en/cloud/saas/financials/r13-update17d/fafrs/rate-limits.html\n  - type: Status\n    url: https://status.oracle.com\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Accounting\n  - E-Business Suite\n  - Enterprise\n  - ERP\n  - Financial Management\n  - Oracle\n  - Release 12\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-financials-12/refs/heads/main/apis.yml
tags:
- Accounting
- E-Business Suite
- Enterprise
- ERP
- Financial Management
- Oracle
- Release 12
url: https://raw.githubusercontent.com/api-evangelist/oracle-financials-12/refs/heads/main/apis.yml
use_cases: []
---
