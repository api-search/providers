---
api_count: 7
api_specs:
- filename: Financial_Management.json
  format: json
  label: Workday Financial Management API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json
- filename: Revenue_Management.json
  format: json
  label: Workday Revenue Management API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Revenue_Management/v38.2/Revenue_Management.json
- filename: Expenses.json
  format: json
  label: Workday Expenses API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Expenses/v38.2/Expenses.json
- filename: Resource_Management.json
  format: json
  label: Workday Procurement API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Resource_Management/v38.2/Resource_Management.json
- filename: Cash_Management.json
  format: json
  label: Workday Cash Management API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Cash_Management/v38.2/Cash_Management.json
- filename: Financial_Management.json
  format: json
  label: Workday Financial Accounting API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json
- filename: Report_as_a_Service.json
  format: json
  label: Workday Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v38.2/Report_as_a_Service.json
apis:
- description: Core API for managing financial transactions, general ledger, accounts payable, accounts receivable, and financial reporting.
  name: Workday Financial Management API
  slug: ''
- description: API for managing revenue recognition, contracts, billing, and revenue accounting in compliance with ASC 606 and IFRS 15.
  name: Workday Revenue Management API
  slug: ''
- description: API for expense report submission, approval workflows, receipt management, and expense policy enforcement.
  name: Workday Expenses API
  slug: ''
- description: API for purchase requisitions, purchase orders, supplier management, and procurement processes.
  name: Workday Procurement API
  slug: ''
- description: API for managing cash positions, bank accounts, transactions, and cash forecasting.
  name: Workday Cash Management API
  slug: ''
- description: API for journal entries, account reconciliation, period close activities, and audit trails.
  name: Workday Financial Accounting API
  slug: ''
- description: API for accessing financial reports, custom report execution, and analytics data extraction.
  name: Workday Reporting API
  slug: ''
common:
- title: ''
  type: Developer Portal
  url: https://community.workday.com/developer
- title: ''
  type: Authentication
  url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/authentication-and-authorization.html
- title: ''
  type: Rate Limits
  url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/rate-limiting.html
- title: ''
  type: Status Page
  url: https://status.workday.com/
- title: ''
  type: Support
  url: https://www.workday.com/en-us/company/latest/support.html
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Contact
  url: https://www.workday.com/en-us/company/latest/contact-us.html
- title: ''
  type: JSON-LD
  url: json-ld/workday-financials-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/workday-financials-journal-entry-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/workday-financials-supplier-invoice-schema.json
created: '2024-01-01'
description: Workday Financials is a cloud-based financial management system that provides comprehensive solutions for accounting, procurement, expenses, and financial reporting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Workday Financials Context
  property_count: 13
  slug: workday-financials-context
layout: provider
modified: '2026-03-16'
name: Workday Financials
skills: []
slug: workday-financials
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-financials\nname: Workday Financials\ndescription: Workday Financials is a cloud-based financial management system that provides comprehensive solutions for accounting, procurement, expenses, and financial reporting.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accounting\n  - Cloud ERP\n  - Financial Management\n  - Procurement\ncreated: '2024-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-financials/refs/heads/main/apis.yml\napis:\n  - name: Workday Financial Management API\n    description: Core API for managing financial transactions, general ledger, accounts payable, accounts receivable, and financial reporting.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/overview.html\n    baseURL: https://api.workday.com/financialManagement\n\
  \    tags:\n      - Accounts Payable\n      - Accounts Receivable\n      - Financial Reporting\n      - General Ledger\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/authentication-and-authorization.html\n      - type: OpenAPI\n        url: openapi/workday-financials-financial-management-openapi.yml\n  - name: Workday Revenue Management API\n    description: API for managing revenue recognition, contracts, billing, and revenue accounting in compliance with ASC 606 and IFRS 15.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/revenue-management.html\n\
  \    baseURL: https://api.workday.com/revenueManagement\n    tags:\n      - Billing\n      - Contracts\n      - Revenue Recognition\n      - Subscription Management\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Revenue_Management/v38.2/Revenue_Management.json\n      - type: OpenAPI\n        url: openapi/workday-financials-revenue-management-openapi.yml\n  - name: Workday Expenses API\n    description: API for expense report submission, approval workflows, receipt management, and expense policy enforcement.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/expense-management.html\n    baseURL: https://api.workday.com/expenses\n    tags:\n      - Approvals\n      - Expense\
  \ Reports\n      - Receipt Management\n      - Travel Expenses\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Expenses/v38.2/Expenses.json\n      - type: OpenAPI\n        url: openapi/workday-financials-expenses-openapi.yml\n  - name: Workday Procurement API\n    description: API for purchase requisitions, purchase orders, supplier management, and procurement processes.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/procurement.html\n    baseURL: https://api.workday.com/procurement\n    tags:\n      - Procurement\n      - Purchase Orders\n      - Requisitions\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n\
  \      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Resource_Management/v38.2/Resource_Management.json\n      - type: OpenAPI\n        url: openapi/workday-financials-procurement-openapi.yml\n  - name: Workday Cash Management API\n    description: API for managing cash positions, bank accounts, transactions, and cash forecasting.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/cash-management.html\n    baseURL: https://api.workday.com/cashManagement\n    tags:\n      - Bank Accounts\n      - Cash Management\n      - Forecasting\n      - Treasury\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Cash_Management/v38.2/Cash_Management.json\n\
  \      - type: OpenAPI\n        url: openapi/workday-financials-cash-management-openapi.yml\n  - name: Workday Financial Accounting API\n    description: API for journal entries, account reconciliation, period close activities, and audit trails.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/financial-accounting.html\n    baseURL: https://api.workday.com/financialAccounting\n    tags:\n      - Account Reconciliation\n      - Audit\n      - Journal Entries\n      - Period Close\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Financial_Management/v38.2/Financial_Management.json\n      - type: OpenAPI\n        url: openapi/workday-financials-financial-accounting-openapi.yml\n\
  \  - name: Workday Reporting API\n    description: API for accessing financial reports, custom report execution, and analytics data extraction.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/financial-management/financial-reporting.html\n    baseURL: https://api.workday.com/reporting\n    tags:\n      - Analytics\n      - Custom Reports\n      - Financial Reports\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/v38.2/Report_as_a_Service.json\n      - type: OpenAPI\n        url: openapi/workday-financials-reporting-openapi.yml\ncommon:\n  - type: Developer Portal\n    url: https://community.workday.com/developer\n  - type: Authentication\n    url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/authentication-and-authorization.html\n\
  \  - type: Rate Limits\n    url: https://doc.workday.com/admin-guide/en-us/workday-web-services/wwsaas/rate-limiting.html\n  - type: Status Page\n    url: https://status.workday.com/\n  - type: Support\n    url: https://www.workday.com/en-us/company/latest/support.html\n  - type: Terms of Service\n    url: https://www.workday.com/en-us/legal.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: Contact\n    url: https://www.workday.com/en-us/company/latest/contact-us.html\n  - type: JSON-LD\n    url: json-ld/workday-financials-context.jsonld\n  - type: JSONSchema\n    url: json-schema/workday-financials-journal-entry-schema.json\n  - type: JSONSchema\n    url: json-schema/workday-financials-supplier-invoice-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-financials/refs/heads/main/apis.yml
tags:
- Accounting
- Cloud ERP
- Financial Management
- Procurement
url: https://raw.githubusercontent.com/api-evangelist/workday-financials/refs/heads/main/apis.yml
use_cases: []
---
