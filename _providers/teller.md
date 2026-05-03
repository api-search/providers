---
api_count: 1
api_specs:
- filename: teller-openapi.yml
  format: yaml
  label: Teller API
  slug: teller-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teller/refs/heads/main/openapi/teller-openapi.yml
apis:
- description: Unified banking API for real-time access to accounts, transactions, balances, and identity data across US financial institutions. Supports account management, transaction history, balance retrieval, a
  name: Teller API
  slug: teller-api
capabilities:
- description: Unified open banking workflow combining account management, transaction history, balance monitoring, and identity verification through the Teller API. Enables fintech applications, personal finance to
  name: Teller Open Banking
  slug: open-banking
common:
- title: ''
  type: Website
  url: https://teller.io/
- title: ''
  type: Documentation
  url: https://teller.io/docs
- title: ''
  type: Developer Portal
  url: https://teller.io/docs/api
- title: ''
  type: GitHub Organization
  url: https://github.com/tellerhq
- title: ''
  type: SDK
  url: https://github.com/tellerhq/teller-ruby
- title: ''
  type: SDK
  url: https://github.com/tellerhq/teller-connect-react
- title: ''
  type: SDK
  url: https://github.com/tellerhq/iOS-SDK
- title: ''
  type: SDK
  url: https://github.com/tellerhq/teller-connect-android
created: ''
description: Teller is a unified banking API providing real-time access to bank accounts, transactions, balances, identity data, and payment initiation across US financial institutions. Connect to thousands of banks and credit unions through a single integration. Teller uses mutual TLS (mTLS) for application authentication and access tokens obtained via Teller Connect for per-account authorization.
features: []
image: ''
integrations: []
jsonld:
- class_count: 2
  name: Teller Context
  property_count: 7
  slug: teller-context
layout: provider
modified: '2026-05-03'
name: Teller
rules:
- name: Teller API Rules
  rule_count: 12
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 5
  slug: teller-rules
skills: []
slug: teller
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: teller\nname: Teller\ndescription: >-\n  Teller is a unified banking API providing real-time access to bank accounts,\n  transactions, balances, identity data, and payment initiation across US financial\n  institutions. Connect to thousands of banks and credit unions through a single\n  integration. Teller uses mutual TLS (mTLS) for application authentication and\n  access tokens obtained via Teller Connect for per-account authorization.\nurl: https://raw.githubusercontent.com/api-evangelist/teller/refs/heads/main/apis.yml\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Banking\n  - Financial Data\n  - FinTech\n  - Open Banking\n  - Transactions\n  - Unified API\napis:\n  - aid: teller:teller-api\n    name: Teller API\n    description: >-\n      Unified banking API for real-time access to accounts, transactions, balances,\n      and identity data across US financial institutions. Supports account management,\n      transaction history, balance retrieval,\
  \ and account holder identity verification\n      via a single REST API secured with mTLS and per-user access tokens.\n    humanURL: https://teller.io/docs/api\n    baseURL: https://api.teller.io\n    tags:\n      - Accounts\n      - Balance\n      - Banking\n      - Financial Data\n      - Identity\n      - Open Banking\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://teller.io/docs/api\n      - type: OpenAPI\n        url: openapi/teller-openapi.yml\n      - type: Getting Started\n        url: https://teller.io/docs/guides/quickstart\n      - type: Authentication\n        url: https://teller.io/docs/api/authentication\n      - type: SDK\n        url: https://teller.io/docs/guides/sdks\ncommon:\n  - type: Website\n    url: https://teller.io/\n  - type: Documentation\n    url: https://teller.io/docs\n  - type: Developer Portal\n    url: https://teller.io/docs/api\n  - type: GitHub Organization\n    url: https://github.com/tellerhq\n  - type: SDK\n\
  \    url: https://github.com/tellerhq/teller-ruby\n  - type: SDK\n    url: https://github.com/tellerhq/teller-connect-react\n  - type: SDK\n    url: https://github.com/tellerhq/iOS-SDK\n  - type: SDK\n    url: https://github.com/tellerhq/teller-connect-android\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/teller/refs/heads/main/apis.yml
tags:
- Banking
- Financial Data
- FinTech
- Open Banking
- Transactions
- Unified API
url: https://raw.githubusercontent.com/api-evangelist/teller/refs/heads/main/apis.yml
use_cases: []
---
