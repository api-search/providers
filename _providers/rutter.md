---
api_count: 4
api_specs:
- filename: rutter-unified-api-openapi.yml
  format: yaml
  label: Rutter Unified API
  slug: unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/openapi/rutter-unified-api-openapi.yml
apis:
- description: The Rutter Unified API provides a single RESTful interface to over 60 commerce, payments, and accounting platforms. It supports connection management, accounting data (accounts, transactions, invoices
  name: Rutter Unified API
  slug: unified-api
- description: The Rutter Commerce API enables reading and writing data to all major commerce platforms through a unified API, supporting platforms like Shopify, WooCommerce, Amazon, and more.
  name: Rutter Commerce API
  slug: commerce-api
- description: The Rutter Accounting API provides a unified interface to read and write data to all major accounting platforms including QuickBooks, Xero, Freshbooks, and Zoho Books.
  name: Rutter Accounting API
  slug: accounting-api
- description: The Rutter Payments API provides a unified interface to read and write data to all major payment platforms through a single REST API.
  name: Rutter Payments API
  slug: payments-api
capabilities:
- description: Unified workflow for managing commerce operations across platforms like Shopify, WooCommerce, Amazon, BigCommerce, and Magento. Enables operations teams to read and manage orders, products, customers,
  name: Rutter Commerce Operations
  slug: commerce-operations
- description: Unified workflow for syncing financial data across accounting platforms including QuickBooks, Xero, NetSuite, and Freshbooks. Enables finance teams to read and reconcile accounts, transactions, invoic
  name: Rutter Financial Data Sync
  slug: financial-data-sync
common:
- title: ''
  type: Website
  url: https://www.rutter.com/
- title: ''
  type: Documentation
  url: https://docs.rutter.com/
- title: ''
  type: Pricing
  url: https://www.rutter.com/pricing
- title: ''
  type: Blog
  url: https://www.rutter.com/blog
- title: ''
  type: APIs
  url: https://www.rutter.com/our-features/apis
- title: ''
  type: SignUp
  url: https://dashboard.rutterapi.com/sign-up
- title: ''
  type: GitHub
  url: https://github.com/rutter
- title: ''
  type: SDK
  url: https://github.com/rutter/react-rutter-link
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/vocabulary/rutter-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-ld/rutter-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/rules/rutter-spectral-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/capabilities/financial-data-sync.yaml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/capabilities/commerce-operations.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-connection-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-invoice-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-order-schema.json
created: '2026-03-16'
description: Rutter is the leading unified RESTful API for B2B financial products that connects to over 60 commerce, payments, accounting, and ads platforms through a single API. Trusted by companies like Airwallex, Mercury, and Ramp, Rutter enables developers to read, update, write, and remove data across major business platforms with a unified data model and idempotency guarantees for financial data. The API supports OAuth2 and Basic authentication, versioning via the X-Rutter-Version header, cursor-based pagination, and asynchronous request processing.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Rutter Context
  property_count: 24
  slug: rutter-context
layout: provider
modified: '2026-05-02'
name: Rutter
rules:
- name: Rutter API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: rutter-spectral-rules
skills: []
slug: rutter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rutter\nname: Rutter\ndescription: >-\n  Rutter is the leading unified RESTful API for B2B financial products that\n  connects to over 60 commerce, payments, accounting, and ads platforms through\n  a single API. Trusted by companies like Airwallex, Mercury, and Ramp, Rutter\n  enables developers to read, update, write, and remove data across major business\n  platforms with a unified data model and idempotency guarantees for financial data.\n  The API supports OAuth2 and Basic authentication, versioning via the X-Rutter-Version\n  header, cursor-based pagination, and asynchronous request processing.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accounting\n  - B2B\n  - Commerce\n  - Financial Data\n  - Payments\n  - Unified API\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ rutter:unified-api\n    name: Rutter Unified API\n    description: >-\n      The Rutter Unified API provides a single RESTful interface to over 60\n      commerce, payments, and accounting platforms. It supports connection management,\n      accounting data (accounts, transactions, invoices, bills, expenses), commerce\n      data (orders, products, customers), payments data, ads data, and banking data\n      through a versioned API with cursor pagination and idempotent writes.\n    humanURL: https://docs.rutter.com/\n    baseURL: https://production.rutterapi.com/versioned\n    tags:\n      - Accounting\n      - B2B\n      - Commerce\n      - Financial Data\n      - Payments\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://docs.rutter.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/openapi/rutter-unified-api-openapi.yml\n  - aid: rutter:commerce-api\n    name: Rutter\
  \ Commerce API\n    description: >-\n      The Rutter Commerce API enables reading and writing data to all major\n      commerce platforms through a unified API, supporting platforms like\n      Shopify, WooCommerce, Amazon, and more.\n    humanURL: https://www.rutter.com/product/commerce-api\n    tags:\n      - Commerce\n      - E-Commerce\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://docs.rutter.com/\n      - type: ProductPage\n        url: https://www.rutter.com/product/commerce-api\n  - aid: rutter:accounting-api\n    name: Rutter Accounting API\n    description: >-\n      The Rutter Accounting API provides a unified interface to read and write\n      data to all major accounting platforms including QuickBooks, Xero,\n      Freshbooks, and Zoho Books.\n    humanURL: https://www.rutter.com/product/accounting-api\n    tags:\n      - Accounting\n      - Financial Data\n      - Unified API\n    properties:\n      - type: Documentation\n      \
  \  url: https://docs.rutter.com/\n      - type: ProductPage\n        url: https://www.rutter.com/product/accounting-api\n  - aid: rutter:payments-api\n    name: Rutter Payments API\n    description: >-\n      The Rutter Payments API provides a unified interface to read and write\n      data to all major payment platforms through a single REST API.\n    humanURL: https://www.rutter.com/product/payments-api\n    tags:\n      - Financial Data\n      - Payments\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://docs.rutter.com/\n      - type: ProductPage\n        url: https://www.rutter.com/product/payments-api\ncommon:\n  - type: Website\n    url: https://www.rutter.com/\n  - type: Documentation\n    url: https://docs.rutter.com/\n  - type: Pricing\n    url: https://www.rutter.com/pricing\n  - type: Blog\n    url: https://www.rutter.com/blog\n  - type: Integrations\n    url: https://www.rutter.com/integrations\n  - type: APIs\n    url: https://www.rutter.com/our-features/apis\n\
  \  - type: SignUp\n    url: https://dashboard.rutterapi.com/sign-up\n  - type: GitHub\n    url: https://github.com/rutter\n  - type: SDK\n    url: https://github.com/rutter/react-rutter-link\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/vocabulary/rutter-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-ld/rutter-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/rules/rutter-spectral-rules.yml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/capabilities/financial-data-sync.yaml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/capabilities/commerce-operations.yaml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-connection-schema.json\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-invoice-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-order-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/apis.yml
tags:
- Accounting
- B2B
- Commerce
- Financial Data
- Payments
- Unified API
url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/apis.yml
use_cases: []
---
