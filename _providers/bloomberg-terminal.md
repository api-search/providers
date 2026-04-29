---
api_count: 4
apis:
- description: The Bloomberg Open API (BLPAPI) enables programmatic access to Bloomberg Terminal data from applications running on the same machine or connecting via Bloomberg's network. Provides real-time data subs
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: Extends Bloomberg Terminal functionality into Microsoft Excel with BDP, BDH, BDS, and BQL formula functions for retrieving real-time, historical, and reference data directly in spreadsheet cells.
  name: Bloomberg Excel Add-in
  slug: bloomberg-excel-addin
- description: Secure messaging platform built into the Bloomberg Terminal enabling real-time communication between financial professionals globally, with compliance archiving and monitoring capabilities.
  name: Bloomberg IB (Instant Bloomberg)
  slug: bloomberg-ib
- description: Electronic trading and order management system integrated in the Bloomberg Terminal for routing orders to brokers across equities, fixed income, FX, and derivatives with FIX connectivity and algorithm
  name: Bloomberg EMSX
  slug: bloomberg-emsx
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://developer.bloomberg.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomberg
- title: Python SDK (blpapi)
  type: SDK
  url: https://pypi.org/project/blpapi/
- title: Node.js SDK
  type: SDK
  url: https://www.npmjs.com/package/blpapi
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
created: '2024-01-01'
description: The Bloomberg Terminal (Bloomberg Professional Service) is the flagship product of Bloomberg LP, providing financial professionals with real-time market data, news, analytics, trading capabilities, and secure messaging through a unified workstation. The Terminal connects over 325,000 subscribers globally and is the standard infrastructure for financial markets professionals. Developers can access Terminal data programmatically via the Bloomberg Open API (BLPAPI).
features:
- description: Streaming real-time prices and quotes across global markets.
  name: Real-Time Market Data
- description: Security attributes, identifiers, corporate actions, and fundamentals.
  name: Reference Data
- description: End-of-day and intraday historical data for all asset classes.
  name: Historical Data
- description: Bond pricing, yield calculations, risk analytics, and scenario analysis.
  name: Fixed Income Analytics
- description: Equity valuation, relative value, and quantitative screening tools.
  name: Equity Analytics
- description: Bloomberg News, analyst research, and Bloomberg Intelligence.
  name: News and Research
- description: Compliant secure messaging for the Bloomberg professional network.
  name: IB Messaging
- description: EMSX for order routing and execution across asset classes.
  name: Electronic Trading
- description: BDP, BDH, BDS formulas for Excel integration.
  name: Bloomberg Excel Add-in
- description: Mobile and remote access to Terminal capabilities.
  name: Bloomberg Anywhere
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Terminal
skills: []
slug: bloomberg-terminal
solutions: []
source_yaml: "aid: bloomberg-terminal\nname: Bloomberg Terminal\ndescription: The Bloomberg Terminal (Bloomberg Professional Service) is the flagship\n  product of Bloomberg LP, providing financial professionals with real-time market\n  data, news, analytics, trading capabilities, and secure messaging through a unified\n  workstation. The Terminal connects over 325,000 subscribers globally and is the\n  standard infrastructure for financial markets professionals. Developers can access\n  Terminal data programmatically via the Bloomberg Open API (BLPAPI).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-terminal/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Terminal\n- Bloomberg Professional Service\n- Market Data\n- Financial Workstation\n- Trading\n- Analytics\n- Bloomberg\napis:\n- aid: bloomberg-terminal:blpapi\n\
  \  name: Bloomberg Open API (BLPAPI)\n  description: The Bloomberg Open API (BLPAPI) enables programmatic access to Bloomberg\n    Terminal data from applications running on the same machine or connecting via\n    Bloomberg's network. Provides real-time data subscriptions, reference data requests,\n    historical data, and Bloomberg analytics. SDKs for Python, Java, C++, C#, and\n    Perl.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - BLPAPI\n  - Core API\n  - Market Data\n  - Real-Time Subscriptions\n  - Reference Data\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n  - type: GettingStarted\n    url: https://data.bloomberglp.com/professional/sites/10/2017/03/BLPAPI-Core-Developer-Guide.pdf\n  - type: GitHubRepository\n    url: https://github.com/bloomberg/blpapi-node\n  - type: SDK\n    url: https://pypi.org/project/blpapi/\n    title: Python SDK\n  - type: SDK\n    url: https://www.npmjs.com/package/blpapi\n\
  \    title: Node.js SDK\n- aid: bloomberg-terminal:bloomberg-excel-addin\n  name: Bloomberg Excel Add-in\n  description: Extends Bloomberg Terminal functionality into Microsoft Excel with\n    BDP, BDH, BDS, and BQL formula functions for retrieving real-time, historical,\n    and reference data directly in spreadsheet cells.\n  humanURL: https://www.bloomberg.com/professional/solution/bloomberg-excel/\n  baseURL: https://bloomberg.com/excel\n  tags:\n  - Excel\n  - Add-in\n  - BDP\n  - BDH\n  - Formulas\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bloomberg-excel/\n- aid: bloomberg-terminal:bloomberg-ib\n  name: Bloomberg IB (Instant Bloomberg)\n  description: Secure messaging platform built into the Bloomberg Terminal enabling\n    real-time communication between financial professionals globally, with compliance\n    archiving and monitoring capabilities.\n  humanURL: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n\
  \  baseURL: blpapi://localhost:8194\n  tags:\n  - IB\n  - Messaging\n  - Compliance\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n- aid: bloomberg-terminal:bloomberg-emsx\n  name: Bloomberg EMSX\n  description: Electronic trading and order management system integrated in the Bloomberg\n    Terminal for routing orders to brokers across equities, fixed income, FX, and\n    derivatives with FIX connectivity and algorithmic trading support.\n  humanURL: https://www.bloomberg.com/professional/solution/emsx/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - EMSX\n  - Order Management\n  - Electronic Trading\n  - FIX\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/emsx/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n-\
  \ type: SDK\n  url: https://pypi.org/project/blpapi/\n  title: Python SDK (blpapi)\n- type: SDK\n  url: https://www.npmjs.com/package/blpapi\n  title: Node.js SDK\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Real-Time Market Data\n    description: Streaming real-time prices and quotes across global markets.\n  - name: Reference Data\n    description: Security attributes, identifiers, corporate actions, and fundamentals.\n  - name: Historical Data\n    description: End-of-day and intraday historical data for all asset classes.\n  - name: Fixed Income Analytics\n    description: Bond pricing, yield calculations, risk analytics, and scenario analysis.\n  - name: Equity Analytics\n    description: Equity valuation, relative value, and quantitative screening tools.\n  - name: News and Research\n\
  \    description: Bloomberg News, analyst research, and Bloomberg Intelligence.\n  - name: IB Messaging\n    description: Compliant secure messaging for the Bloomberg professional network.\n  - name: Electronic Trading\n    description: EMSX for order routing and execution across asset classes.\n  - name: Bloomberg Excel Add-in\n    description: BDP, BDH, BDS formulas for Excel integration.\n  - name: Bloomberg Anywhere\n    description: Mobile and remote access to Terminal capabilities.\n- type: UseCases\n  data:\n  - name: Market Monitoring\n    description: Track real-time price movements and market events across global\n      markets.\n  - name: Fixed Income Research\n    description: Analyze bonds using Bloomberg's fixed income analytics functions.\n  - name: Equity Research\n    description: Screen, analyze, and value equities using Terminal data and functions.\n  - name: FX Trading\n    description: Monitor FX rates and execute currency trades through EMSX.\n  - name: Portfolio\
  \ Management\n    description: Manage and analyze investment portfolios with Bloomberg data.\n  - name: Quantitative Development\n    description: Build quantitative models and strategies using BLPAPI data access.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-terminal/refs/heads/main/apis.yml
tags:
- Terminal
- Bloomberg Professional Service
- Market Data
- Financial Workstation
- Trading
- Analytics
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-terminal/refs/heads/main/apis.yml
use_cases:
- description: Track real-time price movements and market events across global markets.
  name: Market Monitoring
- description: Analyze bonds using Bloomberg's fixed income analytics functions.
  name: Fixed Income Research
- description: Screen, analyze, and value equities using Terminal data and functions.
  name: Equity Research
- description: Monitor FX rates and execute currency trades through EMSX.
  name: FX Trading
- description: Manage and analyze investment portfolios with Bloomberg data.
  name: Portfolio Management
- description: Build quantitative models and strategies using BLPAPI data access.
  name: Quantitative Development
---
