---
api_count: 5
api_specs:
- filename: sage-accounting-openapi.yml
  format: yaml
  label: Sage Accounting API
  slug: accounting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/openapi/sage-accounting-openapi.yml
apis:
- description: Sage Accounting API (v3.1) is a RESTful web service that connects software to Sage's cloud accounting platform. Supports contacts, sales invoices, purchase invoices, payments, bank accounts, ledger ac
  name: Sage Accounting API
  slug: accounting
- description: Sage Intacct provides both REST and XML APIs for advanced financial management including multi-entity consolidations, project accounting, revenue recognition, and advanced reporting. The REST API uses
  name: Sage Intacct API
  slug: intacct
- description: Sage X3 provides a GraphQL API offering flexible data access for ERP operations including manufacturing, distribution, procurement, finance, and CRM. Supports SOAP API for legacy integrations. Targete
  name: Sage X3 API
  slug: sage-x3
- description: Sage 200 API provides REST access to Sage 200 Standard and Professional business management data including customers, suppliers, stock, sales orders, purchase orders, nominal ledger, bank reconciliati
  name: Sage 200 API
  slug: sage-200
- description: Sage 50 Accounts API enables desktop accounting integration for UK small businesses. Provides access to accounts, transactions, customers, suppliers, products, and financial data within Sage 50 Accoun
  name: Sage 50 Accounts API
  slug: sage-50
capabilities:
- description: Unified workflow for accounting and financial management using Sage Accounting API v3.1. Covers contacts, invoicing, payment recording, bank reconciliation, and financial reporting. Used by accountant
  name: Sage Accounting and Finance
  slug: accounting-and-finance
common:
- title: ''
  type: Portal
  url: https://developer.sage.com/
- title: ''
  type: Documentation
  url: https://developer.sage.com/
- title: ''
  type: Authentication
  url: https://developer.sage.com/accounting/guides/concepts/authentication
- title: ''
  type: Sandbox
  url: https://developer.sage.com/accounting/guides/test-drive/
- title: ''
  type: Website
  url: https://www.sage.com/
- title: ''
  type: Support
  url: https://developer.sage.com/support/
- title: ''
  type: Blog
  url: https://www.sage.com/en-us/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/Sage
- title: ''
  type: OpenAPI
  url: openapi/sage-accounting-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/sage-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/sage-contact-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sage-invoice-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sage-contact-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/sage-invoice-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/sage-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/sage-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/accounting-and-finance.yaml
created: '2025-03-01'
description: Sage provides cloud-based ERP, accounting, payroll, and HR software for businesses worldwide. The Sage Developer program provides APIs for integrating with Sage products including Sage Accounting (Business Cloud), Sage Intacct, Sage 200, Sage X3, and Sage 50. APIs support OAuth 2.0 authentication and cover contacts, invoices, payments, ledger accounts, bank accounts, products, and financial reporting. Sage Accounting API v3.1 is the current supported REST version with daily limits of 1,296,000 requests per app.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 40
  name: Sage Context
  property_count: 1
  slug: sage-context
layout: provider
modified: '2026-05-02'
name: Sage
rules:
- name: Sage API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 5
    warn: 4
  slug: sage-rules
skills: []
slug: sage
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sage\nname: Sage\ndescription: >-\n  Sage provides cloud-based ERP, accounting, payroll, and HR software for\n  businesses worldwide. The Sage Developer program provides APIs for integrating\n  with Sage products including Sage Accounting (Business Cloud), Sage Intacct,\n  Sage 200, Sage X3, and Sage 50. APIs support OAuth 2.0 authentication and\n  cover contacts, invoices, payments, ledger accounts, bank accounts, products,\n  and financial reporting. Sage Accounting API v3.1 is the current supported\n  REST version with daily limits of 1,296,000 requests per app.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accounting\n  - Business Management\n  - Cloud Software\n  - ERP\n  - Payroll\n  - HR\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ sage:accounting\n    name: Sage Accounting API\n    description: >-\n      Sage Accounting API (v3.1) is a RESTful web service that connects\n      software to Sage's cloud accounting platform. Supports contacts,\n      sales invoices, purchase invoices, payments, bank accounts, ledger\n      accounts, products/services, and financial reports. Uses OAuth 2.0\n      for authentication. Covers Sage Business Cloud Accounting and Sage\n      Business Cloud Start products.\n    humanURL: https://developer.sage.com/accounting\n    tags:\n      - Accounting\n      - ERP\n      - REST\n      - OAuth 2.0\n    properties:\n      - type: Documentation\n        url: https://developer.sage.com/accounting/reference\n      - type: GettingStarted\n        url: https://developer.sage.com/accounting/guides/concepts/overview\n      - type: OpenAPI\n        url: openapi/sage-accounting-openapi.yml\n\n  - aid: sage:intacct\n    name: Sage Intacct API\n    description: >-\n      Sage Intacct provides both\
  \ REST and XML APIs for advanced financial\n      management including multi-entity consolidations, project accounting,\n      revenue recognition, and advanced reporting. The REST API uses OAuth 2.0\n      for authorization. Targeted at mid-market and enterprise finance teams.\n    humanURL: https://developer.sage.com/intacct/\n    tags:\n      - Accounting\n      - ERP\n      - REST\n      - XML\n      - OAuth 2.0\n    properties:\n      - type: Documentation\n        url: https://developer.intacct.com/api/\n      - type: Authentication\n        url: https://developer.sage.com/intacct/docs/1/sage-intacct-rest-api/authorization-and-security/oauth2\n\n  - aid: sage:sage-x3\n    name: Sage X3 API\n    description: >-\n      Sage X3 provides a GraphQL API offering flexible data access for ERP\n      operations including manufacturing, distribution, procurement, finance,\n      and CRM. Supports SOAP API for legacy integrations. Targeted at\n      enterprise and manufacturing organizations.\n\
  \    humanURL: https://developer.sage.com/x3/\n    tags:\n      - ERP\n      - GraphQL\n      - Manufacturing\n      - Distribution\n    properties:\n      - type: Documentation\n        url: https://developer.sage.com/x3/\n\n  - aid: sage:sage-200\n    name: Sage 200 API\n    description: >-\n      Sage 200 API provides REST access to Sage 200 Standard and Professional\n      business management data including customers, suppliers, stock, sales\n      orders, purchase orders, nominal ledger, bank reconciliation, and\n      financial reporting for UK and Ireland mid-size businesses.\n    humanURL: https://developer.sage.com/sage-200/\n    tags:\n      - Accounting\n      - ERP\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sage.com/sage-200/\n\n  - aid: sage:sage-50\n    name: Sage 50 Accounts API\n    description: >-\n      Sage 50 Accounts API enables desktop accounting integration for UK small\n      businesses. Provides access to accounts,\
  \ transactions, customers,\n      suppliers, products, and financial data within Sage 50 Accounts software.\n    humanURL: https://developer.sage.com/sage-50-accounts/\n    tags:\n      - Accounting\n      - Desktop\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sage.com/sage-50-accounts/\n\ncommon:\n  - type: Portal\n    url: https://developer.sage.com/\n  - type: Documentation\n    url: https://developer.sage.com/\n  - type: Authentication\n    url: https://developer.sage.com/accounting/guides/concepts/authentication\n  - type: Sandbox\n    url: https://developer.sage.com/accounting/guides/test-drive/\n  - type: Website\n    url: https://www.sage.com/\n  - type: Support\n    url: https://developer.sage.com/support/\n  - type: Blog\n    url: https://www.sage.com/en-us/blog/\n  - type: GitHubOrganization\n    url: https://github.com/Sage\n  - type: OpenAPI\n    url: openapi/sage-accounting-openapi.yml\n  - type: SpectralRules\n    url: rules/sage-rules.yml\n\
  \  - type: JSONSchema\n    url: json-schema/sage-contact-schema.json\n  - type: JSONSchema\n    url: json-schema/sage-invoice-schema.json\n  - type: JSONStructure\n    url: json-structure/sage-contact-structure.json\n  - type: JSONStructure\n    url: json-structure/sage-invoice-structure.json\n  - type: JSONLDContext\n    url: json-ld/sage-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/sage-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/accounting-and-finance.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/apis.yml
tags:
- Accounting
- Business Management
- Cloud Software
- ERP
- Payroll
- HR
url: https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/apis.yml
use_cases: []
---
