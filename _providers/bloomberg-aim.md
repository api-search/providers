---
api_count: 4
api_specs:
- filename: bloomberg-data-license-api.yml
  format: yaml
  label: Bloomberg Data License API
  slug: bloomberg-data-license-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/openapi/bloomberg-data-license-api.yml
- filename: bloomberg-emsx-api.yml
  format: yaml
  label: Bloomberg EMSX API
  slug: bloomberg-emsx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/openapi/bloomberg-emsx-api.yml
- filename: bloomberg-http-api.yml
  format: yaml
  label: Bloomberg HTTP API
  slug: bloomberg-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/openapi/bloomberg-http-api.yml
apis:
- description: Provides programmatic access to Bloomberg's comprehensive financial, pricing, reference, regulatory, and alternative data covering over 50 million securities and 56,000 fields via the Hypermedia API (
  name: Bloomberg Data License API
  slug: bloomberg-data-license-api
- description: Server API delivers real-time market data, historical data, premium reference data, and calculation tools from the Bloomberg Terminal into front-office applications.
  name: Bloomberg Server API (SAPI)
  slug: bloomberg-server-api
- description: The Execution Management System API allows developers to manage and automate trading for equities, futures, and options.
  name: Bloomberg EMSX API
  slug: bloomberg-emsx-api
- description: Makes the Bloomberg Open API available via HTTP and WebSockets, allowing clients to access reference and historical request-response data as well as subscribe to live streaming market data.
  name: Bloomberg HTTP API
  slug: bloomberg-http-api
capabilities:
- description: Workflow for accessing Bloomberg market data combining the Data License HAPI for bulk data with the HTTP API for real-time reference and historical data, used by quantitative analysts and portfolio ma
  name: Bloomberg Market Data and Analytics
  slug: market-data-and-analytics
- description: Workflow for automated trading combining EMSX order/route management with HTTP API market data for traders and algorithmic trading teams.
  name: Bloomberg Trading and Execution
  slug: trading-and-execution
common:
- title: ''
  type: Portal
  url: https://developer.bloomberg.com/
- title: ''
  type: Documentation
  url: https://bloomberg.github.io/blpapi-docs/
- title: ''
  type: GettingStarted
  url: https://data.bloomberglp.com/professional/sites/10/2017/03/BLPAPI-Core-Developer-Guide.pdf
- title: ''
  type: Console
  url: https://console.bloomberg.com/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/notices/
- title: ''
  type: Blog
  url: https://www.bloomberg.com/company/stories/category/tech-at-bloomberg/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomberg
- title: ''
  type: SDK
  url: https://github.com/bloomberg/blpapi-node
- title: ''
  type: SDK
  url: https://github.com/bloomberg/blpapi-python
- title: ''
  type: SDK
  url: https://github.com/bloomberg/blpapi-java
created: '2024-01-15'
description: Bloomberg's Asset and Investment Manager (AIM) is a comprehensive buy-side solution offering global, multi-asset capabilities for portfolio management, trading, compliance, and operations. Bloomberg provides a suite of developer APIs including BLPAPI, Server API, and the Hypermedia API for programmatic access to market data, analytics, and enterprise services.
features:
- Access to 50M+ Securities and 56K+ Data Fields
- Real-Time and Historical Market Data
- Hypermedia-Driven REST API (HAPI)
- Execution Management for Equities, Futures, and Options
- WebSocket Streaming for Live Market Data
- Instrument and Field Search
- Scheduled Data Delivery via Triggers
image: /assets/icons/bloomberg-aim.png
integrations:
- Bloomberg Terminal
- Excel via Bloomberg Add-In
- Python (blpapi-python)
- Java (blpapi-java)
- Node.js (blpapi-node)
- .NET (blpapi-dotnet)
- Order Management Systems
jsonld:
- class_count: 0
  name: Bloomberg Data License Context
  property_count: 0
  slug: bloomberg-data-license-context
- class_count: 0
  name: Bloomberg Emsx Context
  property_count: 0
  slug: bloomberg-emsx-context
- class_count: 0
  name: Bloomberg Http Context
  property_count: 0
  slug: bloomberg-http-context
- class_count: 0
  name: context Context
  property_count: 6
  slug: context
layout: provider
modified: '2026-04-18'
name: Bloomberg AIM
rules:
- name: Bloomberg AIM API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: bloomberg-aim-spectral-rules
skills: []
slug: bloomberg-aim
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-aim\nname: Bloomberg AIM\ndescription: >-\n  Bloomberg's Asset and Investment Manager (AIM) is a comprehensive buy-side\n  solution offering global, multi-asset capabilities for portfolio management,\n  trading, compliance, and operations. Bloomberg provides a suite of developer\n  APIs including BLPAPI, Server API, and the Hypermedia API for programmatic\n  access to market data, analytics, and enterprise services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Financial Data\n  - Market Data\n  - Order Management\n  - Portfolio Management\n  - Trading\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: bloomberg-aim:bloomberg-data-license-api\n    name: Bloomberg Data License API\n    description: >-\n      Provides programmatic access to Bloomberg's comprehensive\
  \ financial,\n      pricing, reference, regulatory, and alternative data covering over 50\n      million securities and 56,000 fields via the Hypermedia API (HAPI).\n    humanURL: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    baseURL: https://api.bloomberg.com/eap\n    tags:\n      - Financial Data\n      - Market Data\n      - Pricing Data\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: Authentication\n        url: https://console.bloomberg.com/about/82\n      - type: OpenAPI\n        url: openapi/bloomberg-data-license-api.yml\n  - aid: bloomberg-aim:bloomberg-server-api\n    name: Bloomberg Server API (SAPI)\n    description: >-\n      Server API delivers real-time market data, historical data, premium\n      reference data, and calculation tools from the Bloomberg Terminal into\n      front-office applications.\n    humanURL: https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/\n\
  \    tags:\n      - Financial Analytics\n      - Market Data\n      - Real-Time Data\n      - Server API\n    properties:\n      - type: Documentation\n        url: https://bloomberg.github.io/blpapi-docs/\n  - aid: bloomberg-aim:bloomberg-emsx-api\n    name: Bloomberg EMSX API\n    description: >-\n      The Execution Management System API allows developers to manage and\n      automate trading for equities, futures, and options.\n    humanURL: https://www.bloomberg.com/professional/products/trading/execution-management-system/\n    baseURL: https://localhost:3000\n    tags:\n      - Equities\n      - Execution Management\n      - Order Management\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://emsx-api-doc.readthedocs.io/\n      - type: OpenAPI\n        url: openapi/bloomberg-emsx-api.yml\n  - aid: bloomberg-aim:bloomberg-http-api\n    name: Bloomberg HTTP API\n    description: >-\n      Makes the Bloomberg Open API available via HTTP and WebSockets,\
  \ allowing\n      clients to access reference and historical request-response data as well\n      as subscribe to live streaming market data.\n    humanURL: https://github.com/bloomberg/blpapi-http\n    baseURL: https://localhost:3000\n    tags:\n      - Historical Data\n      - HTTP API\n      - Market Data\n      - Reference Data\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://github.com/bloomberg/blpapi-http\n      - type: OpenAPI\n        url: openapi/bloomberg-http-api.yml\n      - type: GitHubRepository\n        url: https://github.com/bloomberg/blpapi-http\ncommon:\n  - type: Portal\n    url: https://developer.bloomberg.com/\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n  - type: GettingStarted\n    url: https://data.bloomberglp.com/professional/sites/10/2017/03/BLPAPI-Core-Developer-Guide.pdf\n  - type: Console\n    url: https://console.bloomberg.com/\n  - type: TermsOfService\n    url: https://www.bloomberg.com/notices/tos/\n\
  \  - type: PrivacyPolicy\n    url: https://www.bloomberg.com/notices/\n  - type: Blog\n    url: https://www.bloomberg.com/company/stories/category/tech-at-bloomberg/\n  - type: GitHubOrganization\n    url: https://github.com/bloomberg\n  - type: SDK\n    url: https://github.com/bloomberg/blpapi-node\n  - type: SDK\n    url: https://github.com/bloomberg/blpapi-python\n  - type: SDK\n    url: https://github.com/bloomberg/blpapi-java\n  - type: Features\n    url: https://www.bloomberg.com/professional/products/data/\n    data:\n      - Access to 50M+ Securities and 56K+ Data Fields\n      - Real-Time and Historical Market Data\n      - Hypermedia-Driven REST API (HAPI)\n      - Execution Management for Equities, Futures, and Options\n      - WebSocket Streaming for Live Market Data\n      - Instrument and Field Search\n      - Scheduled Data Delivery via Triggers\n  - type: UseCases\n    url: https://www.bloomberg.com/professional/\n    data:\n      - Automated Portfolio Data Retrieval\n\
  \      - Algorithmic Trading Order Management\n      - Regulatory Compliance Data Extraction\n      - Real-Time Market Data Integration\n      - Historical Data Analysis and Backtesting\n      - Multi-Asset Trade Execution Automation\n  - type: Integrations\n    url: https://www.bloomberg.com/professional/\n    data:\n      - Bloomberg Terminal\n      - Excel via Bloomberg Add-In\n      - Python (blpapi-python)\n      - Java (blpapi-java)\n      - Node.js (blpapi-node)\n      - .NET (blpapi-dotnet)\n      - Order Management Systems\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/apis.yml
tags:
- Financial Data
- Market Data
- Order Management
- Portfolio Management
- Trading
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/apis.yml
use_cases:
- Automated Portfolio Data Retrieval
- Algorithmic Trading Order Management
- Regulatory Compliance Data Extraction
- Real-Time Market Data Integration
- Historical Data Analysis and Backtesting
- Multi-Asset Trade Execution Automation
---
