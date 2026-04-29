---
api_count: 6
apis:
- description: Citizens Open Banking API is the FDX-aligned API surface launched in Q1 2025 that gives business, commercial, wealth, and private- banking customers a single endpoint to share account balances, transa
  name: Citizens Open Banking API
  slug: citizens-open-banking-api
- description: The Citizens Accounts API enables authorized retrieval of Citizens Bank customer account and transaction information for use in third-party financial applications and aggregation platforms.
  name: Citizens Accounts API
  slug: citizens-accounts-api
- description: The Citizens Statements API enables authorized retrieval of Citizens Bank customer monthly statements for personal financial management and document workflows.
  name: Citizens Statements API
  slug: citizens-statements-api
- description: The Citizens ATM Locator API enables searching for Citizens Bank ATMs throughout the USA using zip code, street address, or geographical coordinates.
  name: Citizens ATM Locator API
  slug: citizens-atm-locator-api
- description: The Citizens Branch Locator API enables searching for Citizens Bank branches throughout the USA using zip code, street address, or geographical coordinates.
  name: Citizens Branch Locator API
  slug: citizens-branch-locator-api
- description: 'Citizens Pay is the buy-now-pay-later embedded financing platform offered by Citizens Bank. The Citizens Pay developer portal exposes APIs for merchant integration, underwriting, and installment-loan '
  name: Citizens Pay API
  slug: citizens-pay-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.citizensbank.com
- title: ''
  type: Portal
  url: https://developer.citizensbank.com/
- title: ''
  type: Sandbox
  url: https://sandboxdeveloper.citizensbank.com/
- title: ''
  type: Open Bank Project Sandbox
  url: https://citizensbank.openbankproject.com/
- title: ''
  type: Citizens Pay Portal
  url: https://developer-citizenspay.citizensbank.com/
- title: ''
  type: Investor Relations
  url: https://investor.citizensbank.com/
- title: ''
  type: Open Banking Announcement
  url: https://investor.citizensbank.com/about-us/newsroom/latest-news/2025/2025-03-27.aspx
- title: ''
  type: Privacy Policy
  url: https://www.citizensbank.com/account-safeguards/privacy.aspx
- title: ''
  type: Terms of Service
  url: https://www.citizensbank.com/customer-service/online-banking-service-agreement.aspx
- title: ''
  type: Support
  url: https://www.citizensbank.com/customer-service/overview.aspx
- title: ''
  type: JSON-LD
  url: json-ld/citizens-financial-group-context.jsonld
- title: ''
  type: Spectral
  url: rules/citizens-financial-group-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/citizens-financial-group-capabilities.yml
created: '2026-03-23'
description: Citizens Financial Group is one of the oldest and largest financial institutions in the United States, providing retail and commercial banking products and services to individuals, small businesses, middle-market companies, and large corporations through Citizens Bank and its subsidiaries. Citizens exposes a public developer portal at developer.citizensbank.com with REST APIs for accounts, statements, branch and ATM lookup, and a sandbox powered by the Open Bank Project. In 2025 Citizens launched a new FDX-aligned Open Banking API providing business, commercial, wealth, and private-banking customers with a single endpoint for sharing account, balance, and transaction data with authorized third parties. A separate Citizens Pay developer portal exposes Buy-Now-Pay-Later integration APIs.
features: []
image: ''
integrations: []
jsonld:
- class_count: 18
  name: Citizens Financial Group Context
  property_count: 0
  slug: citizens-financial-group-context
layout: provider
modified: '2026-04-23'
name: Citizens Financial Group
rules:
- name: Citizens Financial Group API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: citizens-financial-group-rules
skills: []
slug: citizens-financial-group
solutions: []
source_yaml: "aid: citizens-financial-group\nname: Citizens Financial Group\nurl: https://raw.githubusercontent.com/api-evangelist/citizens-financial-group/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Banking\n  - Buy Now Pay Later\n  - Financial Services\n  - FDX\n  - Locator\n  - Open Banking\n  - Payments\ndescription: >-\n  Citizens Financial Group is one of the oldest and largest financial\n  institutions in the United States, providing retail and commercial\n  banking products and services to individuals, small businesses,\n  middle-market companies, and large corporations through Citizens Bank\n  and its subsidiaries. Citizens exposes a public developer portal at\n  developer.citizensbank.com with REST APIs for accounts, statements,\n  branch and ATM lookup, and a sandbox powered by the Open Bank Project.\n  In 2025 Citizens launched a new FDX-aligned Open Banking\
  \ API providing\n  business, commercial, wealth, and private-banking customers with a\n  single endpoint for sharing account, balance, and transaction data\n  with authorized third parties. A separate Citizens Pay developer\n  portal exposes Buy-Now-Pay-Later integration APIs.\napis:\n  - aid: citizens-financial-group:citizens-open-banking-api\n    name: Citizens Open Banking API\n    tags:\n      - Accounts\n      - Balances\n      - FDX\n      - Open Banking\n      - Transactions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citizensbank.com/\n    properties:\n      - url: https://developer.citizensbank.com/\n        type: Documentation\n      - url: https://investor.citizensbank.com/about-us/newsroom/latest-news/2025/2025-03-27.aspx\n        type: Announcement\n    description: >-\n      Citizens Open Banking API is the FDX-aligned API surface launched\n      in Q1 2025 that gives business, commercial, wealth,\
  \ and private-\n      banking customers a single endpoint to share account balances,\n      transactions, and other financial data with authorized\n      third-party platforms.\n  - aid: citizens-financial-group:citizens-accounts-api\n    name: Citizens Accounts API\n    tags:\n      - Accounts\n      - Balances\n      - Banking\n      - Transactions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citizensbank.com/api\n    properties:\n      - url: https://developer.citizensbank.com/api\n        type: Documentation\n    description: >-\n      The Citizens Accounts API enables authorized retrieval of\n      Citizens Bank customer account and transaction information for\n      use in third-party financial applications and aggregation\n      platforms.\n  - aid: citizens-financial-group:citizens-statements-api\n    name: Citizens Statements API\n    tags:\n      - Banking\n      - Documents\n      - Statements\n    image:\
  \ https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citizensbank.com/api\n    properties:\n      - url: https://developer.citizensbank.com/api\n        type: Documentation\n    description: >-\n      The Citizens Statements API enables authorized retrieval of\n      Citizens Bank customer monthly statements for personal financial\n      management and document workflows.\n  - aid: citizens-financial-group:citizens-atm-locator-api\n    name: Citizens ATM Locator API\n    tags:\n      - ATM\n      - Geo Search\n      - Locator\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citizensbank.com/\n    properties:\n      - url: https://developer.citizensbank.com/\n        type: Documentation\n    description: >-\n      The Citizens ATM Locator API enables searching for Citizens Bank\n      ATMs throughout the USA using zip code, street address, or\n      geographical\
  \ coordinates.\n  - aid: citizens-financial-group:citizens-branch-locator-api\n    name: Citizens Branch Locator API\n    tags:\n      - Branch\n      - Geo Search\n      - Locator\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citizensbank.com/\n    properties:\n      - url: https://developer.citizensbank.com/\n        type: Documentation\n    description: >-\n      The Citizens Branch Locator API enables searching for Citizens\n      Bank branches throughout the USA using zip code, street address,\n      or geographical coordinates.\n  - aid: citizens-financial-group:citizens-pay-api\n    name: Citizens Pay API\n    tags:\n      - BNPL\n      - Buy Now Pay Later\n      - Citizens Pay\n      - Embedded Finance\n      - Lending\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer-citizenspay.citizensbank.com/\n    properties:\n      - url: https://developer-citizenspay.citizensbank.com/\n\
  \        type: Documentation\n    description: >-\n      Citizens Pay is the buy-now-pay-later embedded financing platform\n      offered by Citizens Bank. The Citizens Pay developer portal\n      exposes APIs for merchant integration, underwriting, and\n      installment-loan lifecycle management.\ncommon:\n  - type: Website\n    url: https://www.citizensbank.com\n  - type: Portal\n    url: https://developer.citizensbank.com/\n  - type: Sandbox\n    url: https://sandboxdeveloper.citizensbank.com/\n  - type: Open Bank Project Sandbox\n    url: https://citizensbank.openbankproject.com/\n  - type: Citizens Pay Portal\n    url: https://developer-citizenspay.citizensbank.com/\n  - type: Investor Relations\n    url: https://investor.citizensbank.com/\n  - type: Open Banking Announcement\n    url: https://investor.citizensbank.com/about-us/newsroom/latest-news/2025/2025-03-27.aspx\n  - type: Privacy Policy\n    url: https://www.citizensbank.com/account-safeguards/privacy.aspx\n  - type: Terms\
  \ of Service\n    url: https://www.citizensbank.com/customer-service/online-banking-service-agreement.aspx\n  - type: Support\n    url: https://www.citizensbank.com/customer-service/overview.aspx\n  - type: JSON-LD\n    url: json-ld/citizens-financial-group-context.jsonld\n  - type: Spectral\n    url: rules/citizens-financial-group-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/citizens-financial-group-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/citizens-financial-group/refs/heads/main/apis.yml
tags:
- Banking
- Buy Now Pay Later
- Financial Services
- FDX
- Locator
- Open Banking
- Payments
url: https://raw.githubusercontent.com/api-evangelist/citizens-financial-group/refs/heads/main/apis.yml
use_cases: []
---
