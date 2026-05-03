---
api_count: 8
apis:
- description: REST API for managing general ledger operations including journals, chartfields, budgets, and financial reporting.
  name: PeopleSoft General Ledger API
  slug: general-ledger
- description: REST API for vendor management, invoice processing, payments, and AP reporting.
  name: PeopleSoft Accounts Payable API
  slug: accounts-payable
- description: REST API for customer management, billing, receipts, and AR reporting.
  name: PeopleSoft Accounts Receivable API
  slug: accounts-receivable
- description: REST API for fixed asset tracking, depreciation, transfers, and asset reporting.
  name: PeopleSoft Asset Management API
  slug: asset-management
- description: REST API for purchase requisitions, purchase orders, receiving, and procurement reporting.
  name: PeopleSoft Purchasing API
  slug: purchasing
- description: REST API for expense reporting, reimbursements, and travel management.
  name: PeopleSoft Expenses API
  slug: expenses
- description: REST API for project costing, billing, resource management, and project reporting.
  name: PeopleSoft Projects API
  slug: projects
- description: REST API for executing PeopleSoft queries and retrieving data from various financial modules.
  name: PeopleSoft Query API
  slug: query
common:
- title: ''
  type: Authentication
  url: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tprs/index.html
- title: ''
  type: Portal
  url: https://www.oracle.com/applications/peoplesoft/
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
created: '2024-01-01'
description: API collection for Oracle PeopleSoft Financials suite covering General Ledger, Accounts Payable, Accounts Receivable, Asset Management, and other financial modules.
features: []
image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: PeopleSoft Financials
skills: []
slug: peoplesoft-financials
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: peoplesoft-financials\nname: PeopleSoft Financials\ndescription: >-\n  API collection for Oracle PeopleSoft Financials suite covering General Ledger,\n  Accounts Payable, Accounts Receivable, Asset Management, and other financial\n  modules.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/peoplesoft-financials/refs/heads/main/apis.yml\ntags:\n  - Enterprise\n  - ERP\n  - Financials\n  - Oracle\n  - PeopleSoft\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: peoplesoft-financials:general-ledger\n    name: PeopleSoft General Ledger API\n    description: >-\n      REST API for managing general ledger operations including journals,\n      chartfields, budgets, and financial reporting.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n\
  \    baseURL: https://{hostname}:{port}/psrestservice/financials/gl/\n    tags:\n      - ChartFields\n      - Financial Reporting\n      - General Ledger\n      - Journals\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - aid: peoplesoft-financials:accounts-payable\n    name: PeopleSoft Accounts Payable API\n    description: >-\n      REST API for vendor management, invoice processing, payments, and AP\n      reporting.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n    baseURL: https://{hostname}:{port}/psrestservice/financials/ap/\n    tags:\n      - Accounts Payable\n      - Invoices\n      - Payments\n      - Vendors\n    properties:\n      - type: Documentation\n       \
  \ url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - aid: peoplesoft-financials:accounts-receivable\n    name: PeopleSoft Accounts Receivable API\n    description: >-\n      REST API for customer management, billing, receipts, and AR reporting.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n    baseURL: https://{hostname}:{port}/psrestservice/financials/ar/\n    tags:\n      - Accounts Receivable\n      - Billing\n      - Customers\n      - Receipts\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - aid: peoplesoft-financials:asset-management\n\
  \    name: PeopleSoft Asset Management API\n    description: >-\n      REST API for fixed asset tracking, depreciation, transfers, and asset\n      reporting.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n    baseURL: https://{hostname}:{port}/psrestservice/financials/am/\n    tags:\n      - Asset Management\n      - Asset Tracking\n      - Depreciation\n      - Fixed Assets\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - aid: peoplesoft-financials:purchasing\n    name: PeopleSoft Purchasing API\n    description: >-\n      REST API for purchase requisitions, purchase orders, receiving, and\n      procurement reporting.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n\
  \    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n    baseURL: https://{hostname}:{port}/psrestservice/financials/po/\n    tags:\n      - Procurement\n      - Purchase Orders\n      - Purchasing\n      - Requisitions\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - aid: peoplesoft-financials:expenses\n    name: PeopleSoft Expenses API\n    description: >-\n      REST API for expense reporting, reimbursements, and travel management.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n    baseURL: https://{hostname}:{port}/psrestservice/financials/exp/\n    tags:\n      - Expense Reports\n      - Expenses\n      - Reimbursements\n      - Travel\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - aid: peoplesoft-financials:projects\n    name: PeopleSoft Projects API\n    description: >-\n      REST API for project costing, billing, resource management, and project\n      reporting.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n    baseURL: https://{hostname}:{port}/psrestservice/financials/proj/\n    tags:\n      - Billing\n      - Project Costing\n      - Projects\n      - Resources\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n\
  \  - aid: peoplesoft-financials:query\n    name: PeopleSoft Query API\n    description: >-\n      REST API for executing PeopleSoft queries and retrieving data from\n      various financial modules.\n    image: https://www.oracle.com/a/ocom/img/logo-peoplesoft.svg\n    humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/index.html\n    baseURL: https://{hostname}:{port}/psrestservice/query/\n    tags:\n      - Data Retrieval\n      - Query\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E92519_02/fscm92pbr30/eng/fscm/rest_services/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\ncommon:\n  - type: Authentication\n    url: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tprs/index.html\n  - type: Portal\n    url: https://www.oracle.com/applications/peoplesoft/\n  - type: Support\n    url: https://support.oracle.com\n  - type: Terms\
  \ of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\nmaintainers:\n  - FN: Oracle Corporation\n    email: peoplesoft-info@oracle.com\n    url: https://www.oracle.com/applications/peoplesoft/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/peoplesoft-financials/refs/heads/main/apis.yml
tags:
- Enterprise
- ERP
- Financials
- Oracle
- PeopleSoft
url: https://raw.githubusercontent.com/api-evangelist/peoplesoft-financials/refs/heads/main/apis.yml
use_cases: []
---
