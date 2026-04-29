---
api_count: 3
apis:
- description: Cross-platform API providing access to the full Bloomberg data ecosystem including real-time, reference, and historical data with SDKs for Python, Java, C++, and other languages.
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: Enterprise data distribution platform for delivering Bloomberg data at scale to multiple applications and users within an institution using a managed entitlement and authorization framework.
  name: Bloomberg B-PIPE
  slug: bpipe
- description: Bloomberg's Electronic Order Management System (EMSX) enabling electronic order routing to brokers across equities, fixed income, FX, and derivatives. Provides FIX connectivity, algorithmic trading, a
  name: Bloomberg EMSX (Electronic Order Management)
  slug: emsx
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
description: Bloomberg Products and Platforms covers the breadth of Bloomberg's integrated offerings spanning the Bloomberg Terminal, Enterprise data products, API platforms, trading systems, analytics, messaging, media, and government intelligence solutions. Bloomberg serves financial professionals with an interconnected ecosystem of products and platforms for data, analytics, and communication.
features:
- description: Professional workstation integrating data, analytics, news, and messaging.
  name: Bloomberg Terminal
- description: B-PIPE for institution-wide Bloomberg data sharing.
  name: Enterprise Data Distribution
- description: EMSX for electronic order routing and execution management.
  name: Electronic Trading
- description: Cloud-native Bloomberg data and analytics via cloud connectivity.
  name: Cloud Products
- description: Bloomberg Anywhere for mobile and remote product access.
  name: Mobile Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Products and Platforms
skills: []
slug: bloomberg-products-and-platforms
solutions: []
source_yaml: "aid: bloomberg-products-and-platforms\nname: Bloomberg Products and Platforms\ndescription: Bloomberg Products and Platforms covers the breadth of Bloomberg's integrated\n  offerings spanning the Bloomberg Terminal, Enterprise data products, API platforms,\n  trading systems, analytics, messaging, media, and government intelligence solutions.\n  Bloomberg serves financial professionals with an interconnected ecosystem of products\n  and platforms for data, analytics, and communication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-products-and-platforms/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Products\n- Platforms\n- Terminal\n- Enterprise\n- Financial Data\n- Analytics\n- Bloomberg\napis:\n- aid: bloomberg-products-and-platforms:blpapi\n  name: Bloomberg Open API (BLPAPI)\n  description: Cross-platform\
  \ API providing access to the full Bloomberg data ecosystem\n    including real-time, reference, and historical data with SDKs for Python, Java,\n    C++, and other languages.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Core API\n  - Cross-Platform\n  - Market Data\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n- aid: bloomberg-products-and-platforms:bpipe\n  name: Bloomberg B-PIPE\n  description: Enterprise data distribution platform for delivering Bloomberg data\n    at scale to multiple applications and users within an institution using a managed\n    entitlement and authorization framework.\n  humanURL: https://www.bloomberg.com/professional/support/api-library/\n  baseURL: blpapi://bpipe-server:8194\n  tags:\n  - B-PIPE\n  - Enterprise\n  - Data Distribution\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\n- aid: bloomberg-products-and-platforms:emsx\n\
  \  name: Bloomberg EMSX (Electronic Order Management)\n  description: Bloomberg's Electronic Order Management System (EMSX) enabling electronic\n    order routing to brokers across equities, fixed income, FX, and derivatives.\n    Provides FIX connectivity, algorithmic trading, and TCA.\n  humanURL: https://www.bloomberg.com/professional/solution/emsx/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - EMSX\n  - Order Management\n  - FIX\n  - Electronic Trading\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/emsx/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n\
  \  data:\n  - name: Bloomberg Terminal\n    description: Professional workstation integrating data, analytics, news, and\n      messaging.\n  - name: Enterprise Data Distribution\n    description: B-PIPE for institution-wide Bloomberg data sharing.\n  - name: Electronic Trading\n    description: EMSX for electronic order routing and execution management.\n  - name: Cloud Products\n    description: Cloud-native Bloomberg data and analytics via cloud connectivity.\n  - name: Mobile Access\n    description: Bloomberg Anywhere for mobile and remote product access.\n- type: UseCases\n  data:\n  - name: Buy-Side Investment Workflows\n    description: End-to-end data, analytics, and trading workflow for asset managers.\n  - name: Sell-Side Market Making\n    description: Data and trading tools for bank trading desks and market makers.\n  - name: Financial Research\n    description: Bloomberg Intelligence and data for research teams.\n  - name: Risk Operations\n    description: Risk data and analytics\
  \ integration for risk management operations.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-products-and-platforms/refs/heads/main/apis.yml
tags:
- Products
- Platforms
- Terminal
- Enterprise
- Financial Data
- Analytics
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-products-and-platforms/refs/heads/main/apis.yml
use_cases:
- description: End-to-end data, analytics, and trading workflow for asset managers.
  name: Buy-Side Investment Workflows
- description: Data and trading tools for bank trading desks and market makers.
  name: Sell-Side Market Making
- description: Bloomberg Intelligence and data for research teams.
  name: Financial Research
- description: Risk data and analytics integration for risk management operations.
  name: Risk Operations
---
