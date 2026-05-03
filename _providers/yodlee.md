---
api_count: 3
api_specs:
- filename: yodlee-core-openapi.yml
  format: yaml
  label: Yodlee Core API
  slug: yodlee-core-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/openapi/yodlee-core-openapi.yml
apis:
- description: The Yodlee Core APIs v1.1 provide a flexible RESTful API for accessing personal financial data. Key capabilities include account aggregation across banks and brokerages, transaction history and enrich
  name: Yodlee Core API
  slug: yodlee-core-api
- description: The Yodlee Account Verification API enables real-time verification of bank account ownership and balance. Supports verification workflows via FastLink 4, holder profile retrieval, verified account sta
  name: Yodlee Account Verification API
  slug: yodlee-account-verification-api
- description: FastLink 4 is Yodlee's white-label account aggregation widget that enables users to securely link their financial accounts. Provides a customizable embedded UI for account login, MFA, account selectio
  name: Yodlee FastLink
  slug: yodlee-fastlink
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.yodlee.com/
- title: ''
  type: Developer Portal
  url: https://developer.yodlee.com/
- title: ''
  type: Documentation
  url: https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/openapi/yodlee-core-openapi.yml
- title: ''
  type: GitHub Organization
  url: https://github.com/yodlee
- title: ''
  type: SDK
  url: https://github.com/Yodlee/java-sdk
- title: ''
  type: Getting Started
  url: https://developer.yodlee.com/docs/getting-started
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/vocabulary/yodlee-vocabulary.yml
created: '2026-03-27'
description: Yodlee (Envestnet | Yodlee) is a financial data aggregation platform providing unified API access to bank accounts, credit card transactions, investments, loans, and insurance data across thousands of financial institutions. The Yodlee Core APIs v1.1 enable secure account aggregation, transaction enrichment, risk analytics, consent management, and account verification for fintech applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-03'
name: Yodlee
skills: []
slug: yodlee
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: yodlee\nname: Yodlee\ndescription: >-\n  Yodlee (Envestnet | Yodlee) is a financial data aggregation platform providing\n  unified API access to bank accounts, credit card transactions, investments, loans,\n  and insurance data across thousands of financial institutions. The Yodlee Core APIs\n  v1.1 enable secure account aggregation, transaction enrichment, risk analytics,\n  consent management, and account verification for fintech applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Financial Data\n  - Data Aggregation\n  - Banking\n  - Fintech\n  - Open Finance\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: yodlee:yodlee-core-api\n    name: Yodlee Core API\n    description: >-\n      The Yodlee Core APIs v1.1 provide a flexible RESTful API for accessing\n      personal\
  \ financial data. Key capabilities include account aggregation across\n      banks and brokerages, transaction history and enrichment, holdings and\n      investment data, consent and provider account management, documents, statements,\n      data extracts, risk analytics, and account verification. Supports 90% of top\n      US, UK, Australia, and India financial institutions.\n    humanURL: https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs/overview\n    baseURL: https://production.api.yodlee.com/ysl\n    tags:\n      - Financial Data\n      - Aggregation\n      - Transactions\n      - Accounts\n      - Banking\n      - Investments\n    properties:\n      - type: Documentation\n        url: https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/openapi/yodlee-core-openapi.yml\n      - type: Getting Started\n        url: https://developer.yodlee.com/docs/getting-started\n\
  \n  - aid: yodlee:yodlee-account-verification-api\n    name: Yodlee Account Verification API\n    description: >-\n      The Yodlee Account Verification API enables real-time verification of bank account\n      ownership and balance. Supports verification workflows via FastLink 4, holder profile\n      retrieval, verified account status, and account classification summaries.\n    humanURL: https://developer.yodlee.com/products/yodlee/account-aggregation/docs/api-reference\n    baseURL: https://production.api.yodlee.com/ysl\n    tags:\n      - Account Verification\n      - Banking\n      - Fintech\n      - KYC\n    properties:\n      - type: Documentation\n        url: https://developer.yodlee.com/products/yodlee/account-aggregation/docs/api-reference\n\n  - aid: yodlee:yodlee-fastlink\n    name: Yodlee FastLink\n    description: >-\n      FastLink 4 is Yodlee's white-label account aggregation widget that enables users\n      to securely link their financial accounts. Provides a customizable\
  \ embedded UI\n      for account login, MFA, account selection, verification, and consent management.\n    humanURL: https://developer.yodlee.com/\n    tags:\n      - Account Linking\n      - Widget\n      - Embedded Finance\n    properties:\n      - type: Documentation\n        url: https://developer.yodlee.com/\n\ncommon:\n  - type: Website\n    url: https://www.yodlee.com/\n  - type: Developer Portal\n    url: https://developer.yodlee.com/\n  - type: Documentation\n    url: https://developer.yodlee.com/resources/yodlee/yodlee-api-overview/docs\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/openapi/yodlee-core-openapi.yml\n  - type: GitHub Organization\n    url: https://github.com/yodlee\n  - type: SDK\n    url: https://github.com/Yodlee/java-sdk\n  - type: Getting Started\n    url: https://developer.yodlee.com/docs/getting-started\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/vocabulary/yodlee-vocabulary.yml\n\
  \nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/apis.yml
tags:
- Financial Data
- Data Aggregation
- Banking
- Fintech
- Open Finance
url: https://raw.githubusercontent.com/api-evangelist/yodlee/refs/heads/main/apis.yml
use_cases: []
---
