---
api_count: 8
api_specs:
- filename: veryfi-ocr-openapi.yml
  format: yaml
  label: Veryfi OCR API
  slug: ocr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/openapi/veryfi-ocr-openapi.yml
apis:
- description: The Veryfi OCR API (v8) provides AI-powered document data extraction across multiple document types. The base URL is https://api.veryfi.com/api/v8. Authentication uses CLIENT-ID header and AUTHORIZATI
  name: Veryfi OCR API
  slug: ocr-api
- description: The Veryfi Receipts & Invoices API uses AI-powered OCR to extract structured JSON data from receipts, invoices, bills, and other financial documents. It supports documents in PDF and image formats and
  name: Veryfi Receipts & Invoices API
  slug: receipts-invoices-api
- description: The Veryfi Bank Statements API extracts structured data from bank statements using AI-powered OCR, enabling automated reconciliation, fraud detection, and financial data capture workflows.
  name: Veryfi Bank Statements API
  slug: bank-statements-api
- description: The Veryfi W-2 API extracts structured data from W-2 wage and tax statements using AI-powered OCR, enabling automated processing of employee wage and tax documents for tax preparation and loan approva
  name: Veryfi W-2 API
  slug: w2-api
- description: The Veryfi W-9 API extracts structured data from W-9 Request for Taxpayer Identification forms including TIN, entity type, and address information for HR and vendor management workflows.
  name: Veryfi W-9 API
  slug: w9-api
- description: The Veryfi Checks API extracts bank routing numbers, account numbers, check numbers, payee names, amounts, and dates from check images using AI-powered OCR.
  name: Veryfi Checks API
  slug: checks-api
- description: The Veryfi ∀Docs (Any Documents) API extracts data from any custom document type using named blueprints. Supports contracts, custom forms, and any unstructured document where standard OCR APIs don't a
  name: Veryfi Any Documents API
  slug: any-docs-api
- description: The Veryfi Classification API determines the document type before processing, enabling intelligent routing to the appropriate extraction endpoint.
  name: Veryfi Classification API
  slug: classification-api
capabilities:
- description: Unified financial document processing capability using the Veryfi OCR API. Enables accounts payable teams, tax professionals, lenders, and finance teams to extract structured data from receipts, invoi
  name: Veryfi Financial Document Processing
  slug: financial-document-processing
common:
- title: ''
  type: Website
  url: https://www.veryfi.com/
- title: ''
  type: Documentation
  url: https://docs.veryfi.com/
- title: ''
  type: Console
  url: https://hub.veryfi.com/
- title: ''
  type: SignUp
  url: https://app.veryfi.com/signup/api/
- title: ''
  type: Support
  url: https://faq.veryfi.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/veryfi
- title: ''
  type: PrivacyPolicy
  url: https://www.veryfi.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.veryfi.com/terms-of-service/
- title: ''
  type: SDK
  url: https://pypi.org/project/veryfi/
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/veryfi
created: '2026-05-03'
description: Veryfi provides AI-powered OCR APIs for extracting structured data from financial documents including receipts, invoices, bank statements, checks, W-2s, W-8s, W-9s, business cards, contracts, and custom documents. The platform captures line items, taxes, totals, barcodes, vendor details, and more across 91 currencies and 38 languages with enterprise-grade accuracy. Veryfi offers SDKs in Python, Node.js, Go, Java, Swift, C#, Ruby, PHP, Rust, Kotlin, and Dart, plus mobile SDKs (Veryfi Lens) for iOS, Android, React Native, Ionic, Xamarin, and Cordova.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Veryfi Context
  property_count: 28
  slug: veryfi-context
layout: provider
modified: '2026-05-03'
name: Veryfi
rules:
- name: Veryfi API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 7
  slug: veryfi-ocr-rules
skills: []
slug: veryfi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: veryfi\nname: Veryfi\ndescription: >-\n  Veryfi provides AI-powered OCR APIs for extracting structured data from\n  financial documents including receipts, invoices, bank statements, checks,\n  W-2s, W-8s, W-9s, business cards, contracts, and custom documents. The\n  platform captures line items, taxes, totals, barcodes, vendor details, and\n  more across 91 currencies and 38 languages with enterprise-grade accuracy.\n  Veryfi offers SDKs in Python, Node.js, Go, Java, Swift, C#, Ruby, PHP,\n  Rust, Kotlin, and Dart, plus mobile SDKs (Veryfi Lens) for iOS, Android,\n  React Native, Ionic, Xamarin, and Cordova.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Document Processing\n  - Finance\n  - Invoices\n  - OCR\n  - Receipts\n  - Tax Forms\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: veryfi:ocr-api\n    name: Veryfi OCR API\n    description: >-\n      The Veryfi OCR API (v8) provides AI-powered document data extraction\n      across multiple document types. The base URL is https://api.veryfi.com/api/v8.\n      Authentication uses CLIENT-ID header and AUTHORIZATION header with\n      apikey USERNAME:API_KEY format, plus optional HMAC-SHA256 request\n      signatures (X-Veryfi-Request-Signature and X-Veryfi-Request-Timestamp).\n    humanURL: https://docs.veryfi.com/\n    tags:\n      - AI\n      - Document Processing\n      - OCR\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/\n      - type: Reference\n        url: https://docs.veryfi.com/api/\n      - type: Authentication\n        url: https://docs.veryfi.com/api/getting-started/authentication/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/openapi/veryfi-ocr-openapi.yml\n      - type: Console\n       \
  \ url: https://hub.veryfi.com/\n  - aid: veryfi:receipts-invoices-api\n    name: Veryfi Receipts & Invoices API\n    description: >-\n      The Veryfi Receipts & Invoices API uses AI-powered OCR to extract\n      structured JSON data from receipts, invoices, bills, and other financial\n      documents. It supports documents in PDF and image formats and returns\n      line-item level data including taxes, totals, vendor details, and barcodes.\n    humanURL: https://docs.veryfi.com/\n    tags:\n      - Document Processing\n      - Invoices\n      - OCR\n      - Receipts\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/\n      - type: Reference\n        url: https://docs.veryfi.com/api/receipts-invoices/process-a-document/\n  - aid: veryfi:bank-statements-api\n    name: Veryfi Bank Statements API\n    description: >-\n      The Veryfi Bank Statements API extracts structured data from bank\n      statements using AI-powered OCR, enabling automated reconciliation,\n\
  \      fraud detection, and financial data capture workflows.\n    humanURL: https://docs.veryfi.com/api/bank-statements/\n    tags:\n      - Bank Statements\n      - Finance\n      - OCR\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/api/bank-statements/\n      - type: Reference\n        url: https://docs.veryfi.com/api/bank-statements/get-a-bank-statement/\n  - aid: veryfi:w2-api\n    name: Veryfi W-2 API\n    description: >-\n      The Veryfi W-2 API extracts structured data from W-2 wage and tax\n      statements using AI-powered OCR, enabling automated processing of\n      employee wage and tax documents for tax preparation and loan approvals.\n    humanURL: https://docs.veryfi.com/api/w2s/\n    tags:\n      - OCR\n      - Tax Forms\n      - W-2\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/api/w2s/\n  - aid: veryfi:w9-api\n    name: Veryfi W-9 API\n    description: >-\n      The Veryfi W-9 API extracts structured\
  \ data from W-9 Request for\n      Taxpayer Identification forms including TIN, entity type, and address\n      information for HR and vendor management workflows.\n    humanURL: https://docs.veryfi.com/api/w9s/\n    tags:\n      - HR\n      - OCR\n      - Tax Forms\n      - W-9\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/api/w9s/\n  - aid: veryfi:checks-api\n    name: Veryfi Checks API\n    description: >-\n      The Veryfi Checks API extracts bank routing numbers, account numbers,\n      check numbers, payee names, amounts, and dates from check images using\n      AI-powered OCR.\n    humanURL: https://docs.veryfi.com/api/checks/\n    tags:\n      - Banking\n      - Checks\n      - OCR\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/api/checks/\n  - aid: veryfi:any-docs-api\n    name: Veryfi Any Documents API\n    description: >-\n      The Veryfi ∀Docs (Any Documents) API extracts data from any custom\n    \
  \  document type using named blueprints. Supports contracts, custom forms,\n      and any unstructured document where standard OCR APIs don't apply.\n    humanURL: https://docs.veryfi.com/\n    tags:\n      - Contracts\n      - Custom Documents\n      - Document Processing\n      - OCR\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/\n  - aid: veryfi:classification-api\n    name: Veryfi Classification API\n    description: >-\n      The Veryfi Classification API determines the document type before\n      processing, enabling intelligent routing to the appropriate extraction\n      endpoint.\n    humanURL: https://docs.veryfi.com/\n    tags:\n      - Classification\n      - Document Processing\n      - OCR\n    properties:\n      - type: Documentation\n        url: https://docs.veryfi.com/\ncommon:\n  - url: https://www.veryfi.com/\n    name: Veryfi - OCR APIs for Invoices, Receipts, Checks\n    type: Website\n    description: Veryfi's main website for\
  \ AI-powered OCR document extraction APIs.\n  - url: https://docs.veryfi.com/\n    name: Veryfi API Documentation\n    type: Documentation\n    description: Comprehensive API reference, tutorials, and integration guides.\n  - url: https://hub.veryfi.com/\n    name: Veryfi Interactive API Docs\n    type: Console\n    description: Interactive API explorer for testing Veryfi OCR endpoints.\n  - url: https://app.veryfi.com/signup/api/\n    name: Veryfi API Sign Up\n    type: SignUp\n    description: Register for a Veryfi API account.\n  - url: https://faq.veryfi.com/\n    name: Veryfi Help Center\n    type: Support\n    description: FAQs, guides, and support for Veryfi APIs.\n  - url: https://github.com/veryfi\n    name: Veryfi GitHub Organization\n    type: GitHubOrganization\n    description: >-\n      Veryfi's GitHub organization hosting SDKs for Python, Node.js, Go,\n      Java, Swift, C#, Ruby, PHP, Rust, Kotlin, Dart, and mobile SDKs\n      (Veryfi Lens) for iOS, Android, React Native,\
  \ Ionic, and Xamarin.\n  - url: https://www.veryfi.com/privacy-policy/\n    name: Veryfi Privacy Policy\n    type: PrivacyPolicy\n    description: Veryfi privacy policy for API data handling.\n  - url: https://www.veryfi.com/terms-of-service/\n    name: Veryfi Terms of Service\n    type: TermsOfService\n    description: Veryfi terms of service for API usage.\n  - url: https://pypi.org/project/veryfi/\n    name: Veryfi Python SDK (PyPI)\n    type: SDK\n    description: Official Veryfi Python SDK available on PyPI.\n  - url: https://www.npmjs.com/package/veryfi\n    name: Veryfi Node.js SDK (npm)\n    type: SDK\n    description: Official Veryfi Node.js SDK available on npm.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/apis.yml
tags:
- AI
- Document Processing
- Finance
- Invoices
- OCR
- Receipts
- Tax Forms
url: https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/apis.yml
use_cases: []
---
