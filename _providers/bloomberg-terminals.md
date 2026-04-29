---
api_count: 3
apis:
- description: The Bloomberg Open API provides programmatic access to data available in the Bloomberg Terminal including real-time prices, reference data, historical data, news, and analytics. SDKs for C++, Java, Py
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: Remote access service extending Bloomberg Terminal functionality to any internet-connected device. Provides authentication and secure remote access to Terminal data, analytics, and messaging.
  name: Bloomberg Anywhere
  slug: bloomberg-anywhere-api
- description: Customizable Bloomberg Terminal display consisting of smaller panels for monitoring multiple securities, markets, and data streams simultaneously. Supports custom configurations for different workflow
  name: Bloomberg Launchpad
  slug: bloomberg-launchpad
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
description: Bloomberg Terminals (Bloomberg Professional Service) are financial software systems providing real-time financial market data, news, analytics, and trading capabilities to financial professionals worldwide. The Terminal offers access to over 35,000 different data types for financial instruments globally, integrated analytics, messaging, and the Bloomberg Open API (BLPAPI) for programmatic data access.
features:
- description: Live prices, quotes, and market data for 35,000+ data types globally.
  name: Real-Time Market Data
- description: Static and semi-static security attributes, corporate actions, and fundamentals.
  name: Reference Data
- description: Historical pricing, volume, and analytics data.
  name: Historical Data
- description: Fixed income, equity, and derivatives analytics functions.
  name: Bloomberg Analytics
- description: Secure messaging for the Bloomberg professional community.
  name: Bloomberg IB Messaging
- description: Remote and mobile access to Terminal capabilities.
  name: Bloomberg Anywhere
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Terminals
skills: []
slug: bloomberg-terminals
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-terminals\nname: Bloomberg Terminals\ndescription: Bloomberg Terminals (Bloomberg Professional Service) are financial software\n  systems providing real-time financial market data, news, analytics, and trading\n  capabilities to financial professionals worldwide. The Terminal offers access to\n  over 35,000 different data types for financial instruments globally, integrated\n  analytics, messaging, and the Bloomberg Open API (BLPAPI) for programmatic data\n  access.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-terminals/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Terminal\n- Bloomberg Professional\n- Market Data\n- Financial Data\n- Trading\n- Analytics\n- Bloomberg\napis:\n- aid: bloomberg-terminals:blpapi\n  name: Bloomberg Open API (BLPAPI)\n  description: The Bloomberg Open API\
  \ provides programmatic access to data available\n    in the Bloomberg Terminal including real-time prices, reference data, historical\n    data, news, and analytics. SDKs for C++, Java, Python, C#/.NET, and Perl.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - BLPAPI\n  - Market Data\n  - Real-Time\n  - Terminal API\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n  - type: GitHubRepository\n    url: https://github.com/bloomberg/blpapi-node\n  - type: SDK\n    url: https://pypi.org/project/blpapi/\n    title: Python SDK\n- aid: bloomberg-terminals:bloomberg-anywhere-api\n  name: Bloomberg Anywhere\n  description: Remote access service extending Bloomberg Terminal functionality to\n    any internet-connected device. Provides authentication and secure remote access\n    to Terminal data, analytics, and messaging.\n  humanURL: https://www.bloomberg.com/professional/solution/bloomberg-anywhere/\n\
  \  baseURL: https://bba.bloomberg.net\n  tags:\n  - Remote Access\n  - Mobile\n  - Anywhere\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bloomberg-anywhere/\n- aid: bloomberg-terminals:bloomberg-launchpad\n  name: Bloomberg Launchpad\n  description: Customizable Bloomberg Terminal display consisting of smaller panels\n    for monitoring multiple securities, markets, and data streams simultaneously.\n    Supports custom configurations for different workflow types.\n  humanURL: https://www.bloomberg.com/professional/solution/bloomberg-terminal/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Launchpad\n  - Terminal Dashboard\n  - Monitoring\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bloomberg-terminal/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n\
  - type: SDK\n  url: https://pypi.org/project/blpapi/\n  title: Python SDK (blpapi)\n- type: SDK\n  url: https://www.npmjs.com/package/blpapi\n  title: Node.js SDK\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Real-Time Market Data\n    description: Live prices, quotes, and market data for 35,000+ data types globally.\n  - name: Reference Data\n    description: Static and semi-static security attributes, corporate actions, and\n      fundamentals.\n  - name: Historical Data\n    description: Historical pricing, volume, and analytics data.\n  - name: Bloomberg Analytics\n    description: Fixed income, equity, and derivatives analytics functions.\n  - name: Bloomberg IB Messaging\n    description: Secure messaging for the Bloomberg professional community.\n  - name: Bloomberg Anywhere\n   \
  \ description: Remote and mobile access to Terminal capabilities.\n- type: UseCases\n  data:\n  - name: Trading\n    description: Monitor markets and execute trades using Terminal data and analytics.\n  - name: Research\n    description: Conduct fundamental and quantitative research using Bloomberg data.\n  - name: Risk Management\n    description: Monitor and manage portfolio risk using Terminal analytics.\n  - name: Fixed Income Analysis\n    description: Analyze bonds and credit using Bloomberg fixed income functions.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-terminals/refs/heads/main/apis.yml
tags:
- Terminal
- Bloomberg Professional
- Market Data
- Financial Data
- Trading
- Analytics
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-terminals/refs/heads/main/apis.yml
use_cases:
- description: Monitor markets and execute trades using Terminal data and analytics.
  name: Trading
- description: Conduct fundamental and quantitative research using Bloomberg data.
  name: Research
- description: Monitor and manage portfolio risk using Terminal analytics.
  name: Risk Management
- description: Analyze bonds and credit using Bloomberg fixed income functions.
  name: Fixed Income Analysis
---
