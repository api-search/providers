---
api_count: 5
apis:
- description: Provides real-time and historical market data, including stock prices, indices, commodities, and currencies.
  name: Bloomberg Market Data API
  slug: bloomberg-market-data-api
- description: Delivers real-time market data, historical data, reference data, and calculation engine capabilities from the Bloomberg Terminal for server applications.
  name: Bloomberg Server API (SAPI)
  slug: bloomberg-server-api
- description: Provides programmatic access to Bloomberg Data License content including reference, pricing, regulatory, ESG, corporate actions, fundamentals, and alternative data.
  name: Bloomberg Data License API
  slug: bloomberg-data-license-api
- description: Enables programmatic management and automation of equities, futures, and options trading through the Bloomberg Execution Management System.
  name: Bloomberg EMSX API
  slug: bloomberg-emsx-api
- description: The Bloomberg Open API (BLPAPI) Core — the foundational service-oriented, socket-based API used by the Desktop API, Server API (SAPI), B-PIPE, and Bloomberg Platform products. Provides Request/Respons
  name: Bloomberg BLPAPI Core
  slug: bloomberg-blpapi-core
capabilities:
- description: Unified workflow for accessing Bloomberg reference data, historical data, intraday analytics, and field discovery. Used by quantitative analysts and portfolio managers.
  name: Bloomberg Market Data
  slug: market-data
common:
- title: ''
  type: Portal
  url: https://developer.bloomberg.com/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/support/api-library/
- title: ''
  type: SDK
  url: https://bloomberg.github.io/blpapi-docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomberg
- title: ''
  type: GettingStarted
  url: https://www.bloomberg.com/professional/solutions/asset-management/developer/
- title: ''
  type: Login
  url: https://console.bloomberg.com/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
- title: ''
  type: SpectralRules
  url: rules/bloomberg-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bloomberg-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/market-data.yaml
created: '2024-01-20'
description: Bloomberg delivers business and markets news, data, analysis, and video to the world, featuring stories from Businessweek and Bloomberg News. Bloomberg provides a suite of developer APIs including BLPAPI, Server API, and the Hypermedia API for programmatic access to market data, analytics, and enterprise services.
features:
- description: Stream live market data for equities, fixed income, commodities, and currencies via subscription.
  name: Real-Time Market Data
- description: Access end-of-day historical time series with periodicity, currency, and corporate-action adjustments.
  name: Historical Data
- description: Retrieve raw tick-by-tick trade and quote data for granular intraday analysis.
  name: Intraday Tick Data
- description: Query current reference, descriptive, fundamental, and pricing field values for securities.
  name: Reference Data
- description: Search and discover Bloomberg field mnemonics and metadata via the API Data Dictionary.
  name: Field Discovery
- description: Access BLPAPI through C, C++, Java, .NET, Python, Perl, and COM Excel SDKs.
  name: Multi-Language SDK
image: /assets/icons/bloomberg.png
integrations:
- description: Extend Bloomberg Terminal capabilities through the Desktop API integration.
  name: Bloomberg Terminal
- description: Access BLPAPI data directly from Excel spreadsheets using the COM Excel SDK.
  name: Excel
- description: Build data analytics and machine learning pipelines with the Python BLPAPI SDK.
  name: Python
- description: Distribute Bloomberg data across enterprise infrastructure using the B-PIPE product.
  name: B-PIPE
jsonld:
- class_count: 0
  name: Bloomberg Context
  property_count: 17
  slug: bloomberg-context
- class_count: 0
  name: Blpapi Core Context
  property_count: 0
  slug: blpapi-core-context
layout: provider
modified: '2026-04-18'
name: Bloomberg
rules:
- name: Bloomberg API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: bloomberg-spectral-rules
skills: []
slug: bloomberg
solutions: []
source_yaml: "aid: bloomberg\nname: Bloomberg\ndescription: >-\n  Bloomberg delivers business and markets news, data, analysis, and video to\n  the world, featuring stories from Businessweek and Bloomberg News. Bloomberg\n  provides a suite of developer APIs including BLPAPI, Server API, and the\n  Hypermedia API for programmatic access to market data, analytics, and\n  enterprise services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Business Intelligence\n  - Data License\n  - Enterprise\n  - Execution Management\n  - Financial Services\n  - Market Data\n  - News\n  - Quantitative Analysis\n  - Trading\n  - Transaction Cost Analysis\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bloomberg/refs/heads/main/apis.yml\ncreated: '2024-01-20'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: bloomberg:bloomberg-market-data-api\n    name: Bloomberg Market Data API\n    description: >-\n\
  \      Provides real-time and historical market data, including stock prices,\n      indices, commodities, and currencies.\n    humanURL: https://www.bloomberg.com/professional/support/api-library/\n    tags:\n      - Financial Data\n      - Indices\n      - Market Data\n      - Real-Time\n      - Stocks\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: SDK\n        url: https://bloomberg.github.io/blpapi-docs/\n  - aid: bloomberg:bloomberg-server-api\n    name: Bloomberg Server API (SAPI)\n    description: >-\n      Delivers real-time market data, historical data, reference data, and\n      calculation engine capabilities from the Bloomberg Terminal for server\n      applications.\n    humanURL: https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/\n    tags:\n      - Enterprise\n      - Historical Data\n      - Market Data\n      - Real-Time\n      - Reference Data\n    \
  \  - Server API\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: SDK\n        url: https://bloomberg.github.io/blpapi-docs/\n  - aid: bloomberg:bloomberg-data-license-api\n    name: Bloomberg Data License API\n    description: >-\n      Provides programmatic access to Bloomberg Data License content including\n      reference, pricing, regulatory, ESG, corporate actions, fundamentals, and\n      alternative data.\n    humanURL: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    tags:\n      - Data License\n      - Enterprise\n      - ESG\n      - Pricing Data\n      - Reference Data\n      - Regulatory Data\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n  - aid: bloomberg:bloomberg-emsx-api\n    name: Bloomberg EMSX API\n    description: >-\n      Enables programmatic management\
  \ and automation of equities, futures, and\n      options trading through the Bloomberg Execution Management System.\n    humanURL: https://www.bloomberg.com/professional/products/trading/execution-management-system/\n    tags:\n      - Equities\n      - Execution Management\n      - Futures\n      - Options\n      - Orders\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://emsx-api-doc.readthedocs.io/\n  - aid: bloomberg:bloomberg-blpapi-core\n    name: Bloomberg BLPAPI Core\n    description: >-\n      The Bloomberg Open API (BLPAPI) Core — the foundational service-oriented,\n      socket-based API used by the Desktop API, Server API (SAPI), B-PIPE, and\n      Bloomberg Platform products. Provides Request/Response, Subscription, and\n      Publishing paradigms across services including //blp/refdata,\n      //blp/mktdata, //blp/mktbar, //blp/mktvwap, //blp/mktdepthdata,\n      //blp/apiflds, //blp/instruments, //blp/pagedata, and //blp/tasvc.\n    humanURL:\
  \ https://www.bloomberg.com/professional/support/api-library/\n    tags:\n      - B-PIPE\n      - BLPAPI\n      - Desktop API\n      - Historical Data\n      - Intraday Bars\n      - Intraday Ticks\n      - Market Data\n      - Open API\n      - Reference Data\n      - Request Response\n      - Server API\n      - Subscription\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: SDK\n        url: https://bloomberg.github.io/blpapi-docs/\n      - type: OpenAPI\n        url: openapi/blpapi-core.yml\n      - type: JSONSchema\n        url: json-schema/blpapi-core-messages-schema.json\n      - type: JSONSchema\n        url: json-schema/blpapi-core-error-message-schema.json\n      - type: JSONSchema\n        url: json-schema/blpapi-core-market-data-event-schema.json\n      - type: JSONSchema\n        url: json-schema/blpapi-core-subscription-schema.json\n      - type: JSONSchema\n        url: json-schema/blpapi-core-subscription-list-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/bloomberg-market-data-schema.json\n      - type: JSONSchema\n        url: json-schema/bloomberg-security-schema.json\n      - type: JSONLD\n        url: json-ld/bloomberg-context.jsonld\n      - type: JSONLD\n        url: json-ld/blpapi-core-context.jsonld\ncommon:\n  - type: Portal\n    url: https://developer.bloomberg.com/\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\n  - type: SDK\n    url: https://bloomberg.github.io/blpapi-docs/\n  - type: GitHubOrganization\n    url: https://github.com/bloomberg\n  - type: GettingStarted\n    url: https://www.bloomberg.com/professional/solutions/asset-management/developer/\n  - type: Login\n    url: https://console.bloomberg.com/\n  - type: TermsOfService\n    url: https://www.bloomberg.com/notices/tos/\n  - type: PrivacyPolicy\n    url: https://www.bloomberg.com/privacy\n  - type: Support\n    url: https://www.bloomberg.com/professional/support/\n\
  \  - type: SpectralRules\n    url: rules/bloomberg-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/bloomberg-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/market-data.yaml\n  - type: Features\n    data:\n      - name: Real-Time Market Data\n        description: Stream live market data for equities, fixed income, commodities, and currencies via subscription.\n      - name: Historical Data\n        description: Access end-of-day historical time series with periodicity, currency, and corporate-action adjustments.\n      - name: Intraday Tick Data\n        description: Retrieve raw tick-by-tick trade and quote data for granular intraday analysis.\n      - name: Reference Data\n        description: Query current reference, descriptive, fundamental, and pricing field values for securities.\n      - name: Field Discovery\n        description: Search and discover Bloomberg field mnemonics and metadata via the API Data Dictionary.\n      - name: Multi-Language\
  \ SDK\n        description: Access BLPAPI through C, C++, Java, .NET, Python, Perl, and COM Excel SDKs.\n  - type: UseCases\n    data:\n      - name: Quantitative Research\n        description: Build quantitative models using historical and real-time market data for alpha generation.\n      - name: Risk Management\n        description: Monitor portfolio risk exposure using real-time pricing and reference data feeds.\n      - name: Algorithmic Trading\n        description: Feed market data into trading algorithms via EMSX for automated order execution.\n      - name: Regulatory Reporting\n        description: Access regulatory and compliance data through Data License for reporting requirements.\n  - type: Integrations\n    data:\n      - name: Bloomberg Terminal\n        description: Extend Bloomberg Terminal capabilities through the Desktop API integration.\n      - name: Excel\n        description: Access BLPAPI data directly from Excel spreadsheets using the COM Excel SDK.\n      - name:\
  \ Python\n        description: Build data analytics and machine learning pipelines with the Python BLPAPI SDK.\n      - name: B-PIPE\n        description: Distribute Bloomberg data across enterprise infrastructure using the B-PIPE product.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Data License
- Enterprise
- Execution Management
- Financial Services
- Market Data
- News
- Quantitative Analysis
- Trading
- Transaction Cost Analysis
url: https://raw.githubusercontent.com/api-evangelist/bloomberg/refs/heads/main/apis.yml
use_cases:
- description: Build quantitative models using historical and real-time market data for alpha generation.
  name: Quantitative Research
- description: Monitor portfolio risk exposure using real-time pricing and reference data feeds.
  name: Risk Management
- description: Feed market data into trading algorithms via EMSX for automated order execution.
  name: Algorithmic Trading
- description: Access regulatory and compliance data through Data License for reporting requirements.
  name: Regulatory Reporting
---
