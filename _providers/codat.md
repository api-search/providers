---
api_count: 8
apis:
- description: The Codat Platform API provides core functionality used across all Codat solutions, including programmatic creation and management of companies, data connections, and configuration of integrations wit
  name: Codat Platform API
  slug: platform-api
- description: The Codat Lending API enables digital lenders, neobanks, and corporate card providers to make smarter credit decisions on small businesses by aggregating and analyzing standardized financial data from
  name: Codat Lending API
  slug: lending-api
- description: The Codat Bank Feeds API enables banks, neobanks, corporate card issuers, and payment providers to set up automatic bank feeds from their applications to supported accounting software, simplifying the
  name: Codat Bank Feeds API
  slug: bank-feeds-api
- description: 'The Codat Sync for Expenses API enables corporate card and expense management platforms to provide high-quality integrations with multiple accounting platforms, synchronizing categorized expense data '
  name: Codat Sync for Expenses API
  slug: sync-for-expenses-api
- description: The Codat Bill Pay API (Sync for Payables) enables neobanks, expense management providers, and B2B payment platforms to automate customers' accounts payable workflows, providing a standardized data mo
  name: Codat Bill Pay API
  slug: sync-for-payables-api
- description: The Codat Spend Insights API enables banks and commercial card issuers to access clients' accounts payable data from their ERP or accounting software within minutes, providing insights on spend and su
  name: Codat Spend Insights API
  slug: spend-insights-api
- description: The Codat Sync for Commerce API automatically replicates and reconciles sales data from merchant point-of-sale, payments, and eCommerce systems into their accounting software, transforming raw sales a
  name: Codat Sync for Commerce API
  slug: sync-for-commerce-api
- description: The Codat Sync for Payroll API enables HR, payroll, and vertical SaaS platforms to integrate their customers' payroll data into accounting software and support its reconciliation, providing a standard
  name: Codat Sync for Payroll API
  slug: sync-for-payroll-api
common:
- title: ''
  type: Portal
  url: https://app.codat.io/
- title: ''
  type: Documentation
  url: https://docs.codat.io/
- title: ''
  type: Getting Started
  url: https://docs.codat.io/get-started/first-steps
- title: ''
  type: SDKs
  url: https://docs.codat.io/get-started/libraries
- title: ''
  type: OpenAPI Source
  url: https://github.com/codatio/oas
- title: ''
  type: GitHub Organization
  url: https://github.com/codatio
- title: ''
  type: Blog
  url: https://codat.io/blog/
- title: ''
  type: Change Log
  url: https://docs.codat.io/updates
- title: ''
  type: Status
  url: https://status.codat.io
- title: ''
  type: Sign Up
  url: https://codat.io/start-building/
- title: ''
  type: About
  url: https://codat.io/about/
- title: ''
  type: Legal
  url: https://legal.codat.io/
- title: ''
  type: TypeScript SDK
  url: https://github.com/codatio/client-sdk-typescript
- title: ''
  type: Python SDK
  url: https://github.com/codatio/client-sdk-python
- title: ''
  type: C# SDK
  url: https://github.com/codatio/client-sdk-csharp
- title: ''
  type: Go SDK
  url: https://github.com/codatio/client-sdk-go
- title: ''
  type: Java SDK
  url: https://github.com/codatio/client-sdk-java
created: '2026-03-03'
description: Codat is a unified API platform focused on SMB financial data, connecting to 30+ accounting, ERP, banking, and payment platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-01'
name: Codat
skills: []
slug: codat
solutions: []
source_yaml: "aid: codat\nname: Codat\nsegments:\n  - Unified_API\ndescription: >-\n  Codat is a unified API platform focused on SMB financial data, connecting to 30+ accounting, ERP, banking, and payment platforms.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Unified_API\ncreated: '2026-03-03'\nmodified: '2026-04-01'\nurl: https://raw.githubusercontent.com/api-evangelist/codat/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: codat:platform-api\n    name: Codat Platform API\n    description: >-\n      The Codat Platform API provides core functionality used across all Codat solutions, including programmatic creation and management of companies, data connections, and configuration of integrations with accounting, banking, and commerce platforms.\n    humanURL: https://docs.codat.io/using-the-api/overview\n    tags:\n      - Companies\n      - Connections\n      - Platform\n\
  \      - Unified_API\n    properties:\n      - type: Documentation\n        url: https://docs.codat.io/using-the-api/overview\n      - type: API Reference\n        url: https://docs.codat.io/platform-api\n      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\n      - type: OpenAPI\n        url: openapi/codat-platform-openapi.json\n  - aid: codat:lending-api\n    name: Codat Lending API\n    description: >-\n      The Codat Lending API enables digital lenders, neobanks, and corporate card providers to make smarter credit decisions on small businesses by aggregating and analyzing standardized financial data from accounting, banking, and commerce platforms to assess SMB creditworthiness.\n    humanURL: https://docs.codat.io/lending/overview\n    tags:\n      - Credit\n      - Financial Data\n      - Lending\n      - Underwriting\n      - Unified_API\n    properties:\n      - type: Documentation\n        url: https://docs.codat.io/lending/overview\n      - type: API Reference\n\
  \        url: https://docs.codat.io/lending-api\n      - type: OpenAPI\n        url: openapi/codat-lending-openapi.json\n      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\n  - aid: codat:bank-feeds-api\n    name: Codat Bank Feeds API\n    description: >-\n      The Codat Bank Feeds API enables banks, neobanks, corporate card issuers, and payment providers to set up automatic bank feeds from their applications to supported accounting software, simplifying the deployment of bank statement synchronization into SMB accounting platforms through a single standardized integration.\n    humanURL: https://docs.codat.io/bank-feeds/overview\n    tags:\n      - Accounting\n      - Bank Feeds\n      - Reconciliation\n      - Unified_API\n    properties:\n      - type: Documentation\n        url: https://docs.codat.io/bank-feeds/overview\n      - type: OpenAPI\n        url: openapi/codat-bank-feeds-openapi.json\n      - type: API Reference\n        url: https://docs.codat.io/bank-feeds-api\n\
  \      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\n  - aid: codat:sync-for-expenses-api\n    name: Codat Sync for Expenses API\n    description: >-\n      The Codat Sync for Expenses API enables corporate card and expense management platforms to provide high-quality integrations with multiple accounting platforms, synchronizing categorized expense data including receipts, general ledger mappings, and tracking categories into SMB accounting software through a standardized data model.\n    humanURL: https://docs.codat.io/expenses/overview\n    tags:\n      - Accounting Sync\n      - Corporate Cards\n      - Expenses\n      - Unified_API\n    properties:\n      - type: Documentation\n        url: https://docs.codat.io/expenses/overview\n      - type: API Reference\n        url: https://docs.codat.io/sync-for-expenses-api\n      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\n  - aid: codat:sync-for-payables-api\n    name: Codat Bill Pay API\n\
  \    description: >-\n      The Codat Bill Pay API (Sync for Payables) enables neobanks, expense management providers, and B2B payment platforms to automate customers' accounts payable workflows, providing a standardized data model to sync bills and bill payments with all major accounting software in real time.\n    humanURL: https://docs.codat.io/payables/overview\n    tags:\n      - Accounts Payable\n      - Bill Pay\n      - Payables\n      - Unified_API\n    properties:\n      - type: Documentation\n        url: https://docs.codat.io/payables/overview\n      - type: API Reference\n        url: https://docs.codat.io/sync-for-payables-v2-api\n      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\n  - aid: codat:spend-insights-api\n    name: Codat Spend Insights API\n    description: >-\n      The Codat Spend Insights API enables banks and commercial card issuers to access clients' accounts payable data from their ERP or accounting software within minutes, providing\
  \ insights on spend and supplier activity to identify suppliers eligible for virtual card programs and grow commercial card volume in B2B payments.\n    humanURL: https://docs.codat.io/spend-insights/overview\n    tags:\n      - Accounts Payable\n      - Spend Insights\n      - Unified_API\n      - Virtual Cards\n    properties:\n      - type: Documentation\n        url: https://docs.codat.io/spend-insights/overview\n      - type: API Reference\n        url: https://docs.codat.io/spend-insights-api\n      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\n  - aid: codat:sync-for-commerce-api\n    name: Codat Sync for Commerce API\n    description: >-\n      The Codat Sync for Commerce API automatically replicates and reconciles sales data from merchant point-of-sale, payments, and eCommerce systems into their accounting software, transforming raw sales and payments data into detailed sales invoices for automated accounting reconciliation.\n    humanURL: https://docs.codat.io/commerce/overview\n\
  \    tags:\n      - Commerce\n      - Point of Sale\n      - Reconciliation\n      - Unified_API\n    properties:\n      - type: Documentation\n        url: https://docs.codat.io/commerce/overview\n      - type: API Reference\n        url: https://docs.codat.io/sync-for-commerce-api\n      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\n  - aid: codat:sync-for-payroll-api\n    name: Codat Sync for Payroll API\n    description: >-\n      The Codat Sync for Payroll API enables HR, payroll, and vertical SaaS platforms to integrate their customers' payroll data into accounting software and support its reconciliation, providing a standardized data model to create and manage accounts, journal entries, and tracking categories across all supported accounting and ERP packages.\n    humanURL: https://docs.codat.io/payroll/overview\n    tags:\n      - Accounting Sync\n      - HR\n      - Payroll\n      - Unified_API\n    properties:\n      - type: Documentation\n        url:\
  \ https://docs.codat.io/payroll/overview\n      - type: API Reference\n        url: https://docs.codat.io/sync-for-payroll-api\n      - type: OpenAPI Source\n        url: https://github.com/codatio/oas\ncommon:\n  - type: Portal\n    url: https://app.codat.io/\n  - type: Documentation\n    url: https://docs.codat.io/\n  - type: Getting Started\n    url: https://docs.codat.io/get-started/first-steps\n  - type: SDKs\n    url: https://docs.codat.io/get-started/libraries\n  - type: OpenAPI Source\n    url: https://github.com/codatio/oas\n  - type: GitHub Organization\n    url: https://github.com/codatio\n  - type: Blog\n    url: https://codat.io/blog/\n  - type: Change Log\n    url: https://docs.codat.io/updates\n  - type: Status\n    url: https://status.codat.io\n  - type: Sign Up\n    url: https://codat.io/start-building/\n  - type: About\n    url: https://codat.io/about/\n  - type: Legal\n    url: https://legal.codat.io/\n  - type: TypeScript SDK\n    url: https://github.com/codatio/client-sdk-typescript\n\
  \  - type: Python SDK\n    url: https://github.com/codatio/client-sdk-python\n  - type: C# SDK\n    url: https://github.com/codatio/client-sdk-csharp\n  - type: Go SDK\n    url: https://github.com/codatio/client-sdk-go\n  - type: Java SDK\n    url: https://github.com/codatio/client-sdk-java\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/codat/refs/heads/main/apis.yml
tags:
- Unified_API
url: https://raw.githubusercontent.com/api-evangelist/codat/refs/heads/main/apis.yml
use_cases: []
---
