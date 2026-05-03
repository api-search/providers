---
api_count: 8
api_specs:
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Expense Report v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Expense Entry v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Quick Expense v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
- filename: sap-concur-expense-report-openapi.yml
  format: yaml
  label: Receipt Image v3 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/openapi/sap-concur-expense-report-openapi.yml
apis:
- description: Allows developers to read and write expense report headers, manage the expense report lifecycle including submission and approval workflows, and retrieve expense report data for integration with ERP a
  name: Expense Report v3 API
  slug: ''
- description: Manage individual expense entries within expense reports including itemizations, attendees, custom fields, and form field values. Supports creating, reading, updating, and deleting individual line ite
  name: Expense Entry v3 API
  slug: ''
- description: 'Create and manage basic expenses quickly outside of a formal expense report. Quick expenses can be added to an expense report later. Useful for capturing expenses on-the-go before being ready to file '
  name: Quick Expense v3 API
  slug: ''
- description: Upload, retrieve, and manage receipt images associated with expense entries. Supports attaching scanned receipts, e-receipts from travel providers, and credit card transaction images to expense line i
  name: Receipt Image v3 API
  slug: ''
- description: Retrieve digital tax invoice data associated with expense entries for compliance and auditing in jurisdictions that require electronic invoicing (e-invoicing). Provides access to CFDI (Mexico), NF-e (
  name: Digital Tax Invoice API
  slug: ''
- description: Retrieve expense group configurations including expense types, expense policies, payment types, and workflow settings. Used to dynamically configure expense capture UIs and enforce policy rules during
  name: Expense Group Configuration API
  slug: ''
- description: 'Manage allocation of expenses across multiple cost centers, projects, departments, or GL accounts. Supports percentage-based and amount-based allocation splits for corporate expense policy compliance '
  name: Expense Allocations API
  slug: ''
- description: Retrieve and manage payment batches for processed expense reports ready for reimbursement. Provides visibility into batch payment status, amounts, and payee information for integration with payroll an
  name: Payment Batch v1 API
  slug: ''
capabilities:
- description: Workflow capability for mobile expense capture and receipt management in SAP Concur. Enables on-the-go expense logging via quick expenses and receipt image capture before formal report submission. Des
  name: SAP Concur Expense Capture and Receipt Management
  slug: expense-capture-and-receipts
- description: 'Unified workflow capability for the full expense report lifecycle in SAP Concur: creating reports, adding expense entries, submitting for approval, tracking approval status, and monitoring reimburseme'
  name: SAP Concur Expense Reporting and Approval
  slug: expense-reporting-and-approval
common:
- title: ''
  type: Developer Portal
  url: https://developer.concur.com/
- title: ''
  type: Getting Started
  url: https://developer.concur.com/api-reference/expense/
- title: ''
  type: Authentication
  url: https://developer.concur.com/api-reference/authentication/getting-started.html
- title: ''
  type: OAuth 2.0
  url: https://developer.concur.com/api-reference/authentication/apidoc.html
- title: ''
  type: API Explorer
  url: https://developer.concur.com/api-explorer/
- title: ''
  type: Support
  url: https://developer.concur.com/support
- title: ''
  type: Terms of Service
  url: https://developer.concur.com/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: Status Page
  url: https://open.concur.com/
- title: ''
  type: Release Notes
  url: https://developer.concur.com/tools-support/release-notes/
- title: ''
  type: Community
  url: https://community.sap.com/topics/concur
- title: ''
  type: Blog
  url: https://developer.concur.com/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/concur
- title: ''
  type: Website
  url: https://www.concur.com/
- title: ''
  type: Sign Up
  url: https://www.concur.com/en-us/try-concur.html
- title: ''
  type: SDKs
  url: https://github.com/concur/concur-platform-sdk-java
- title: ''
  type: Postman Collection
  url: https://developer.concur.com/tools-support/postman.html
- title: ''
  type: OpenAPI
  url: openapi/sap-concur-expense-report-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/sap-concur-expense-report-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-concur-expense-entry-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-concur-expense-receipt-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-concur-expense-report-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-concur-expense-entry-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/sap-concur-expense-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/sap-concur-expense-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/expense-reporting-and-approval.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/expense-capture-and-receipts.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/sap-concur-expense-vocabulary.yml
created: '2025-01-01'
description: SAP Concur Expense is a cloud-based travel and expense management solution that automates and streamlines expense reporting, approval workflows, and reimbursement processes for businesses. It integrates with corporate card programs, receipt capture, and ERP systems to provide end-to-end expense lifecycle management with audit controls and policy enforcement.
features: []
image: https://www.concur.com/themes/custom/concur/logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Sap Concur Expense Context
  property_count: 34
  slug: sap-concur-expense-context
layout: provider
modified: '2026-05-02'
name: SAP Concur Expense
rules:
- name: SAP Concur Expense API Rules
  rule_count: 16
  severity_counts:
    error: 2
    hint: 5
    info: 1
    warn: 8
  slug: sap-concur-expense-rules
skills: []
slug: sap-concur-expense
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP Concur Expense\ndescription: >-\n  SAP Concur Expense is a cloud-based travel and expense management solution that\n  automates and streamlines expense reporting, approval workflows, and reimbursement\n  processes for businesses. It integrates with corporate card programs, receipt capture,\n  and ERP systems to provide end-to-end expense lifecycle management with audit controls\n  and policy enforcement.\nimage: https://www.concur.com/themes/custom/concur/logo.svg\nurl: https://developer.concur.com/\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Expense Management\n  - Financial Management\n  - Receipts\n  - Reimbursement\n  - Reporting\n  - SAP\n  - Travel\napis:\n  - name: Expense Report v3 API\n    description: >-\n      Allows developers to read and write expense report headers, manage the expense\n      report lifecycle including submission and approval workflows, and retrieve\n      expense report data for integration\
  \ with ERP and financial systems.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    humanURL: https://developer.concur.com/api-reference/expense/expense-report/v3.reports.html\n    baseURL: https://us.api.concursolutions.com/api/v3.0\n    version: '3.0'\n    tags:\n      - Approval\n      - Expenses\n      - Financial\n      - Reports\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/v3.reports.html\n      - type: Authentication\n        url: https://developer.concur.com/api-reference/authentication/getting-started.html\n      - type: OpenAPI\n        url: openapi/sap-concur-expense-report-openapi.yml\n    contact:\n      - type: Support\n        url: https://developer.concur.com/support\n  - name: Expense Entry v3 API\n    description: >-\n      Manage individual expense entries within expense reports including itemizations,\n      attendees, custom fields, and form field\
  \ values. Supports creating, reading,\n      updating, and deleting individual line items in expense reports.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    humanURL: https://developer.concur.com/api-reference/expense/expense-report/expense-entry.html\n    baseURL: https://us.api.concursolutions.com/api/v3.0\n    version: '3.0'\n    tags:\n      - Expense Entries\n      - Itemization\n      - Line Items\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/expense-entry.html\n      - type: OpenAPI\n        url: openapi/sap-concur-expense-report-openapi.yml\n    contact:\n      - type: Support\n        url: https://developer.concur.com/support\n  - name: Quick Expense v3 API\n    description: >-\n      Create and manage basic expenses quickly outside of a formal expense report.\n      Quick expenses can be added to an expense report later. Useful for capturing\n      expenses on-the-go before\
  \ being ready to file a complete report.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    humanURL: https://developer.concur.com/api-reference/expense/quick-expense/v3.quick-expense.html\n    baseURL: https://us.api.concursolutions.com/api/v3.0\n    version: '3.0'\n    tags:\n      - Expenses\n      - Mobile\n      - Quick Expense\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/quick-expense/v3.quick-expense.html\n      - type: OpenAPI\n        url: openapi/sap-concur-expense-report-openapi.yml\n    contact:\n      - type: Support\n        url: https://developer.concur.com/support\n  - name: Receipt Image v3 API\n    description: >-\n      Upload, retrieve, and manage receipt images associated with expense entries.\n      Supports attaching scanned receipts, e-receipts from travel providers, and\n      credit card transaction images to expense line items for compliance and audit.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n\
  \    humanURL: https://developer.concur.com/api-reference/image/v1.image.html\n    baseURL: https://us.api.concursolutions.com/api/v3.0\n    version: '3.0'\n    tags:\n      - Documents\n      - Images\n      - Receipts\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/image/v1.image.html\n      - type: OpenAPI\n        url: openapi/sap-concur-expense-report-openapi.yml\n    contact:\n      - type: Support\n        url: https://developer.concur.com/support\n  - name: Digital Tax Invoice API\n    description: >-\n      Retrieve digital tax invoice data associated with expense entries for compliance\n      and auditing in jurisdictions that require electronic invoicing (e-invoicing).\n      Provides access to CFDI (Mexico), NF-e (Brazil), and other country-specific\n      digital tax documents.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    humanURL: https://developer.concur.com/api-reference/expense/digital-tax-invoices/digital-tax-invoice.html\n\
  \    baseURL: https://us.api.concursolutions.com/api/v3.0\n    version: '3.0'\n    tags:\n      - Compliance\n      - Invoice\n      - Tax\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/digital-tax-invoices/digital-tax-invoice.html\n    contact:\n      - type: Support\n        url: https://developer.concur.com/support\n  - name: Expense Group Configuration API\n    description: >-\n      Retrieve expense group configurations including expense types, expense policies,\n      payment types, and workflow settings. Used to dynamically configure expense\n      capture UIs and enforce policy rules during expense report creation.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    humanURL: https://developer.concur.com/api-reference/expense/expense-report/expense-group-configurations.html\n    baseURL: https://us.api.concursolutions.com/api/v3.0\n    version: '3.0'\n    tags:\n      - Configuration\n      - Policies\n\
  \      - Settings\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/expense-group-configurations.html\n    contact:\n      - type: Support\n        url: https://developer.concur.com/support\n  - name: Expense Allocations API\n    description: >-\n      Manage allocation of expenses across multiple cost centers, projects, departments,\n      or GL accounts. Supports percentage-based and amount-based allocation splits\n      for corporate expense policy compliance and financial reporting.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    humanURL: https://developer.concur.com/api-reference/expense/expense-report/expense-allocations.html\n    baseURL: https://us.api.concursolutions.com/api/v3.0\n    version: '3.0'\n    tags:\n      - Accounting\n      - Allocations\n      - Cost Centers\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/expense-report/expense-allocations.html\n\
  \    contact:\n      - type: Support\n        url: https://developer.concur.com/support\n  - name: Payment Batch v1 API\n    description: >-\n      Retrieve and manage payment batches for processed expense reports ready for\n      reimbursement. Provides visibility into batch payment status, amounts, and\n      payee information for integration with payroll and ERP payment systems.\n    image: https://www.concur.com/themes/custom/concur/logo.svg\n    humanURL: https://developer.concur.com/api-reference/expense/payment-batch/v1.payment-batches.html\n    baseURL: https://us.api.concursolutions.com/api/v1.1\n    version: '1.1'\n    tags:\n      - Batch Processing\n      - Payments\n      - Reimbursement\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/expense/payment-batch/v1.payment-batches.html\n    contact:\n      - type: Support\n        url: https://developer.concur.com/support\ncommon:\n  - type: Developer Portal\n    url: https://developer.concur.com/\n\
  \  - type: Getting Started\n    url: https://developer.concur.com/api-reference/expense/\n  - type: Authentication\n    url: https://developer.concur.com/api-reference/authentication/getting-started.html\n  - type: OAuth 2.0\n    url: https://developer.concur.com/api-reference/authentication/apidoc.html\n  - type: API Explorer\n    url: https://developer.concur.com/api-explorer/\n  - type: Support\n    url: https://developer.concur.com/support\n  - type: Terms of Service\n    url: https://developer.concur.com/terms-of-use\n  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: Status Page\n    url: https://open.concur.com/\n  - type: Release Notes\n    url: https://developer.concur.com/tools-support/release-notes/\n  - type: Community\n    url: https://community.sap.com/topics/concur\n  - type: Blog\n    url: https://developer.concur.com/blog/\n  - type: GitHub Organization\n    url: https://github.com/concur\n  - type: Website\n    url: https://www.concur.com/\n\
  \  - type: Sign Up\n    url: https://www.concur.com/en-us/try-concur.html\n  - type: SDKs\n    url: https://github.com/concur/concur-platform-sdk-java\n  - type: Postman Collection\n    url: https://developer.concur.com/tools-support/postman.html\n  - type: OpenAPI\n    url: openapi/sap-concur-expense-report-openapi.yml\n  - type: JSONSchema\n    url: json-schema/sap-concur-expense-report-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-concur-expense-entry-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-concur-expense-receipt-schema.json\n  - type: JSONStructure\n    url: json-structure/sap-concur-expense-report-structure.json\n  - type: JSONStructure\n    url: json-structure/sap-concur-expense-entry-structure.json\n  - type: JSON-LD\n    url: json-ld/sap-concur-expense-context.jsonld\n  - type: SpectralRules\n    url: rules/sap-concur-expense-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/expense-reporting-and-approval.yaml\n  - type: NaftikoCapability\n\
  \    url: capabilities/expense-capture-and-receipts.yaml\n  - type: Vocabulary\n    url: vocabulary/sap-concur-expense-vocabulary.yml\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-concur-expense/refs/heads/main/apis.yml
tags:
- Expense Management
- Financial Management
- Receipts
- Reimbursement
- Reporting
- SAP
- Travel
url: https://developer.concur.com/
use_cases: []
---
