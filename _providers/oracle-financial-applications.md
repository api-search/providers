---
api_count: 11
api_specs:
- filename: op-version-latest-get.html
  format: yaml
  label: Oracle ERP Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/op-version-latest-get.html
apis:
- description: REST APIs for Oracle ERP Cloud covering modules like General Ledger, Accounts Payable, Accounts Receivable, Cash Management, and Fixed Assets.
  name: Oracle ERP Cloud REST API
  slug: ''
- description: APIs for managing chart of accounts, journal entries, budgets, allocations, and financial reporting in Oracle ERP Cloud.
  name: Oracle General Ledger REST API
  slug: ''
- description: APIs for managing supplier invoices, payments, expense reports, and procurement transactions.
  name: Oracle Accounts Payable REST API
  slug: ''
- description: APIs for managing customer invoices, receipts, credit memos, and revenue recognition.
  name: Oracle Accounts Receivable REST API
  slug: ''
- description: APIs for bank account management, cash positioning, forecasting, and reconciliation.
  name: Oracle Cash Management REST API
  slug: ''
- description: APIs for managing asset lifecycle, depreciation, mass additions, and asset tracking.
  name: Oracle Fixed Assets REST API
  slug: ''
- description: REST APIs for Oracle Enterprise Performance Management Cloud including Planning, Financial Consolidation and Close, Tax Reporting, and Account Reconciliation.
  name: Oracle EPM Cloud REST API
  slug: ''
- description: APIs for creating, managing, and executing financial reports, including Smart View integration.
  name: Oracle Financial Reporting REST API
  slug: ''
- description: APIs for Financial Consolidation and Close Cloud Service for consolidations, eliminations, currency translation, and intercompany management.
  name: Oracle FCCS REST API
  slug: ''
- description: APIs for Account Reconciliation Cloud Service for managing reconciliations, certifications, and compliance workflows.
  name: Oracle ARCS REST API
  slug: ''
- description: APIs for Planning and Budgeting Cloud Service including data management, business rules, and planning operations.
  name: Oracle Planning REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://cloud.oracle.com/
- title: ''
  type: Getting Started
  url: https://docs.oracle.com/en/cloud/saas/financials/get-started.html
- title: ''
  type: Support
  url: https://support.oracle.com/
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Pricing
  url: https://www.oracle.com/cloud/price-list.html
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: Training
  url: https://education.oracle.com/
created: '2024-01-15'
description: Collection of APIs for Oracle's suite of financial management applications including ERP Cloud, EPM Cloud, and related financial services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Oracle Financial Applications
skills: []
slug: oracle-financial-applications
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-financial-applications\nname: Oracle Financial Applications\ndescription: >-\n  Collection of APIs for Oracle's suite of financial management applications\n  including ERP Cloud, EPM Cloud, and related financial services.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-financial-applications/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Accounting\n  - Cloud Applications\n  - Enterprise Performance Management\n  - Enterprise Resource Planning\n  - EPM\n  - ERP\n  - Financial Management\n  - Financial Reporting\napis:\n  - name: Oracle ERP Cloud REST API\n    description: >-\n      REST APIs for Oracle ERP Cloud covering modules like General Ledger, Accounts\n      Payable, Accounts Receivable, Cash Management, and Fixed Assets.\n    image: https://www.oracle.com/a/ocom/img/oracle-cloud.svg\n\
  \    humanUrl: https://docs.oracle.com/en/cloud/saas/financials/\n    baseUrl: https://{instance}.oraclecloud.com/fscmRestApi/resources/\n    tags:\n      - Accounts Payable\n      - Accounts Receivable\n      - ERP\n      - General Ledger\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/op-version-latest-get.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/Authentication.html\n      - type: SDKs\n        url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/sdks.htm\n  - name: Oracle General Ledger REST API\n    description: >-\n      APIs for managing chart of accounts, journal entries, budgets, allocations,\n      and financial reporting in Oracle ERP Cloud.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/financials/\n    baseUrl: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05/\n\
  \    tags:\n      - Budgets\n      - Chart of Accounts\n      - General Ledger\n      - Journals\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/api-general-ledger.html\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/endpoints-general-ledger.html\n  - name: Oracle Accounts Payable REST API\n    description: >-\n      APIs for managing supplier invoices, payments, expense reports, and procurement\n      transactions.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/financials/\n    baseUrl: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05/\n    tags:\n      - Accounts Payable\n      - Invoices\n      - Payments\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/api-payables.html\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/endpoints-payables.html\n\
  \  - name: Oracle Accounts Receivable REST API\n    description: >-\n      APIs for managing customer invoices, receipts, credit memos, and revenue recognition.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/financials/\n    baseUrl: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05/\n    tags:\n      - Accounts Receivable\n      - Customers\n      - Invoices\n      - Receipts\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/api-receivables.html\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/endpoints-receivables.html\n  - name: Oracle Cash Management REST API\n    description: >-\n      APIs for bank account management, cash positioning, forecasting, and reconciliation.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/financials/\n    baseUrl: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05/\n    tags:\n      - Bank\
  \ Accounts\n      - Cash Management\n      - Reconciliation\n      - Treasury\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/api-cash-management.html\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/endpoints-cash-management.html\n  - name: Oracle Fixed Assets REST API\n    description: >-\n      APIs for managing asset lifecycle, depreciation, mass additions, and asset tracking.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/financials/\n    baseUrl: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05/\n    tags:\n      - Asset Management\n      - Depreciation\n      - Fixed Assets\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/api-assets.html\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/24d/farfa/endpoints-assets.html\n \
  \ - name: Oracle EPM Cloud REST API\n    description: >-\n      REST APIs for Oracle Enterprise Performance Management Cloud including Planning,\n      Financial Consolidation and Close, Tax Reporting, and Account Reconciliation.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/\n    baseUrl: https://{instance}.oraclecloud.com/epm/rest/\n    tags:\n      - Account Reconciliation\n      - Budgeting\n      - EPM\n      - Financial Consolidation\n      - Planning\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/prest/\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/prest/rest_endpoints.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/prest/api_authentication.html\n  - name: Oracle Financial Reporting REST\
  \ API\n    description: >-\n      APIs for creating, managing, and executing financial reports, including Smart\n      View integration.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/\n    baseUrl: https://{instance}.oraclecloud.com/epm/rest/\n    tags:\n      - Analytics\n      - Financial Reporting\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/prest/rep_rest_api_intro.html\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/prest/rest_api_financial_reporting_overview.html\n  - name: Oracle FCCS REST API\n    description: >-\n      APIs for Financial Consolidation and Close Cloud Service for consolidations,\n      eliminations, currency translation, and intercompany management.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/financial-consolidation-cloud/\n\
  \    baseUrl: https://{instance}.oraclecloud.com/epm/rest/\n    tags:\n      - Close Management\n      - Consolidation\n      - Currency Translation\n      - Eliminations\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financial-consolidation-cloud/fcgrs/\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/financial-consolidation-cloud/fcgrs/rest_endpoints.html\n  - name: Oracle ARCS REST API\n    description: >-\n      APIs for Account Reconciliation Cloud Service for managing reconciliations,\n      certifications, and compliance workflows.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/account-reconcile-cloud/\n    baseUrl: https://{instance}.oraclecloud.com/epm/rest/\n    tags:\n      - Account Reconciliation\n      - Certifications\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/account-reconcile-cloud/suarc/\n      - type: API\
  \ Reference\n        url: https://docs.oracle.com/en/cloud/saas/account-reconcile-cloud/suarc/rest_endpoints.html\n  - name: Oracle Planning REST API\n    description: >-\n      APIs for Planning and Budgeting Cloud Service including data management, business\n      rules, and planning operations.\n    humanUrl: https://docs.oracle.com/en/cloud/saas/planning-budgeting-cloud/\n    baseUrl: https://{instance}.oraclecloud.com/epm/rest/\n    tags:\n      - Budgeting\n      - Forecasting\n      - Planning\n      - Workforce Planning\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/planning-budgeting-cloud/pfusr/\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/saas/planning-budgeting-cloud/pfusr/rest_endpoints.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude:\n  - name: Oracle Cloud Infrastructure APIs\n    url: https://docs.oracle.com/en-us/iaas/api/\n  - name: Oracle Integration Cloud\
  \ APIs\n    url: https://docs.oracle.com/en/cloud/paas/integration-cloud/\ncommon:\n  - type: Portal\n    url: https://cloud.oracle.com/\n  - type: Getting Started\n    url: https://docs.oracle.com/en/cloud/saas/financials/get-started.html\n  - type: Support\n    url: https://support.oracle.com/\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n  - type: Pricing\n    url: https://www.oracle.com/cloud/price-list.html\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n  - type: Training\n    url: https://education.oracle.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-financial-applications/refs/heads/main/apis.yml
tags:
- Accounting
- Cloud Applications
- Enterprise Performance Management
- Enterprise Resource Planning
- EPM
- ERP
- Financial Management
- Financial Reporting
url: https://raw.githubusercontent.com/api-evangelist/oracle-financial-applications/refs/heads/main/apis.yml
use_cases: []
---
