---
api_count: 5
apis:
- description: Provides access to real-time and historical market data including stocks, bonds, commodities, and currencies through the Bloomberg Terminal and enterprise data feeds.
  name: Bloomberg Market Data API
  slug: market-data-api
- description: Access to Bloomberg's breaking news, articles, and multimedia content covering global markets and business through the Bloomberg Professional platform.
  name: Bloomberg News API
  slug: news-api
- description: 'Lightweight server-side API that delivers real-time market, historical, and key reference data as well as calculation engine capabilities for proprietary and third-party applications. Available in C, '
  name: Bloomberg Server API (SAPI)
  slug: server-api
- description: Provides programmatic access to Data License content via REST API, SFTP, or cloud providers, with available content including reference, pricing, regulatory, and alternative data for over 50 million s
  name: Bloomberg Data License API
  slug: data-license-api
- description: Core Bloomberg API providing a unified programming interface for Desktop API, Server API, B-PIPE, and Platform products. Available as SDKs for C++, C# (.NET), Java, and Python.
  name: Bloomberg BLPAPI
  slug: blpapi
common:
- title: ''
  type: Portal
  url: https://developer.bloomberg.com/
- title: ''
  type: Documentation
  url: https://bloomberg.github.io/blpapi-docs/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
- title: ''
  type: Blog
  url: https://www.bloomberg.com/company/stories/category/tech-at-bloomberg/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomberg
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/notices/
- title: ''
  type: Contact
  url: https://www.bloomberg.com/professional/contact-menu/
- title: ''
  type: Login
  url: https://bba.bloomberg.net/
created: '2024-01-01'
description: Bloomberg News is a leading global provider of financial news, data, and analysis, delivering breaking news and insights on markets, economics, politics, and business. Bloomberg provides APIs through the Bloomberg Professional Services platform including BLPAPI, Server API, Data License, and market data services.
features:
- description: Access streaming real-time market data for equities, fixed income, commodities, and currencies.
  name: Real-Time Market Data
- description: Query historical pricing, volume, and fundamental data for backtesting and analysis.
  name: Historical Data Services
- description: Access comprehensive reference data for securities identification, corporate actions, and classifications.
  name: Reference Data
- description: Programmatic access to Bloomberg breaking news, articles, and research content.
  name: News and Research
- description: Server-side APIs for distributing Bloomberg data to internal applications and trading systems.
  name: Enterprise Data Distribution
- description: SDKs available in Python, Java, C++, C#, and C for cross-platform integration.
  name: Multi-Language SDK Support
image: /assets/icons/bloomberg-news.png
integrations:
- description: Bloomberg Excel Add-In for spreadsheet-based data analysis and modeling.
  name: Excel
- description: Python SDK (blpapi) for data science and quantitative finance applications.
  name: Python
- description: Bloomberg Datafeed Toolbox for MATLAB for financial modeling and analysis.
  name: MATLAB
- description: Rblpapi package for accessing Bloomberg data in R statistical computing.
  name: R
- description: Integration with order management and execution management systems.
  name: Trading Platforms
jsonld:
- class_count: 0
  name: Bloomberg News Context
  property_count: 10
  slug: bloomberg-news-context
layout: provider
modified: '2026-04-18'
name: Bloomberg News
skills: []
slug: bloomberg-news
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-news\nname: Bloomberg News\ndescription: >-\n  Bloomberg News is a leading global provider of financial news, data, and analysis,\n  delivering breaking news and insights on markets, economics, politics, and business.\n  Bloomberg provides APIs through the Bloomberg Professional Services platform\n  including BLPAPI, Server API, Data License, and market data services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bloomberg-news/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Business Intelligence\n  - Financial Services\n  - Market Data\n  - News\napis:\n  - aid: bloomberg-news:market-data-api\n    name: Bloomberg Market Data API\n    description: >-\n      Provides access to real-time and historical market data including stocks,\n      bonds, commodities, and currencies\
  \ through the Bloomberg Terminal and\n      enterprise data feeds.\n    humanURL: https://www.bloomberg.com/professional/support/api-library/\n    baseURL: https://api.bloomberg.com/v1\n    tags:\n      - Financial Data\n      - Historical Data\n      - Market Data\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/api-library/\n      - type: Authentication\n        url: https://www.bloomberg.com/professional/support/api-library/#authentication\n      - type: GettingStarted\n        url: https://bloomberg.github.io/blpapi-docs/\n  - aid: bloomberg-news:news-api\n    name: Bloomberg News API\n    description: >-\n      Access to Bloomberg's breaking news, articles, and multimedia content\n      covering global markets and business through the Bloomberg Professional\n      platform.\n    humanURL: https://www.bloomberg.com/professional/support/news-api/\n    baseURL: https://api.bloomberg.com/news/v1\n    tags:\n\
  \      - Articles\n      - Business News\n      - Financial News\n      - News\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/support/news-api/\n      - type: Pricing\n        url: https://www.bloomberg.com/professional/pricing/\n      - type: GettingStarted\n        url: https://developer.bloomberg.com/\n  - aid: bloomberg-news:server-api\n    name: Bloomberg Server API (SAPI)\n    description: >-\n      Lightweight server-side API that delivers real-time market, historical,\n      and key reference data as well as calculation engine capabilities for\n      proprietary and third-party applications. Available in C, C++, .NET,\n      Python, and Java.\n    humanURL: https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/\n    tags:\n      - Enterprise\n      - Real-Time Data\n      - Reference Data\n      - Server API\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/\n\
  \      - type: APIReference\n        url: https://bloomberg.github.io/blpapi-docs/\n      - type: GettingStarted\n        url: https://bloomberg.github.io/blpapi-docs/\n  - aid: bloomberg-news:data-license-api\n    name: Bloomberg Data License API\n    description: >-\n      Provides programmatic access to Data License content via REST API, SFTP,\n      or cloud providers, with available content including reference, pricing,\n      regulatory, and alternative data for over 50 million securities and 30\n      thousand fields.\n    humanURL: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n    tags:\n      - Alternative Data\n      - Data License\n      - Enterprise Data\n      - Pricing Data\n      - Reference Data\n      - Regulatory Data\n    properties:\n      - type: Documentation\n        url: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n      - type: APIReference\n        url: https://developer.bloomberg.com/\n\
  \      - type: GettingStarted\n        url: https://developer.bloomberg.com/\n  - aid: bloomberg-news:blpapi\n    name: Bloomberg BLPAPI\n    description: >-\n      Core Bloomberg API providing a unified programming interface for Desktop\n      API, Server API, B-PIPE, and Platform products. Available as SDKs for\n      C++, C# (.NET), Java, and Python.\n    humanURL: https://bloomberg.github.io/blpapi-docs/\n    tags:\n      - Core API\n      - Desktop API\n      - Integration\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://bloomberg.github.io/blpapi-docs/\n      - type: APIReference\n        url: https://bloomberg.github.io/blpapi-docs/\n      - type: GettingStarted\n        url: https://data.bloomberglp.com/professional/sites/10/2017/03/BLPAPI-Core-Developer-Guide.pdf\n      - type: GitHubOrganization\n        url: https://github.com/bloomberg\ncommon:\n  - type: Portal\n    url: https://developer.bloomberg.com/\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n\
  \  - type: Support\n    url: https://www.bloomberg.com/professional/support/\n  - type: Blog\n    url: https://www.bloomberg.com/company/stories/category/tech-at-bloomberg/\n  - type: GitHubOrganization\n    url: https://github.com/bloomberg\n  - type: TermsOfService\n    url: https://www.bloomberg.com/notices/tos/\n  - type: PrivacyPolicy\n    url: https://www.bloomberg.com/notices/\n  - type: Contact\n    url: https://www.bloomberg.com/professional/contact-menu/\n  - type: Login\n    url: https://bba.bloomberg.net/\n  - type: Features\n    data:\n      - name: Real-Time Market Data\n        description: Access streaming real-time market data for equities, fixed income, commodities, and currencies.\n      - name: Historical Data Services\n        description: Query historical pricing, volume, and fundamental data for backtesting and analysis.\n      - name: Reference Data\n        description: Access comprehensive reference data for securities identification, corporate actions, and classifications.\n\
  \      - name: News and Research\n        description: Programmatic access to Bloomberg breaking news, articles, and research content.\n      - name: Enterprise Data Distribution\n        description: Server-side APIs for distributing Bloomberg data to internal applications and trading systems.\n      - name: Multi-Language SDK Support\n        description: SDKs available in Python, Java, C++, C#, and C for cross-platform integration.\n  - type: UseCases\n    data:\n      - name: Quantitative Trading\n        description: Build algorithmic trading strategies using real-time and historical market data feeds.\n      - name: Risk Management\n        description: Calculate portfolio risk metrics using Bloomberg's pricing and analytics data.\n      - name: Financial Research\n        description: Automate financial research workflows with news, fundamental data, and analytics.\n      - name: Regulatory Reporting\n        description: Generate regulatory compliance reports using reference data\
  \ and pricing services.\n      - name: Portfolio Management\n        description: Integrate Bloomberg data into portfolio management systems for real-time monitoring.\n  - type: Integrations\n    data:\n      - name: Excel\n        description: Bloomberg Excel Add-In for spreadsheet-based data analysis and modeling.\n      - name: Python\n        description: Python SDK (blpapi) for data science and quantitative finance applications.\n      - name: MATLAB\n        description: Bloomberg Datafeed Toolbox for MATLAB for financial modeling and analysis.\n      - name: R\n        description: Rblpapi package for accessing Bloomberg data in R statistical computing.\n      - name: Trading Platforms\n        description: Integration with order management and execution management systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-news/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Financial Services
- Market Data
- News
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-news/refs/heads/main/apis.yml
use_cases:
- description: Build algorithmic trading strategies using real-time and historical market data feeds.
  name: Quantitative Trading
- description: Calculate portfolio risk metrics using Bloomberg's pricing and analytics data.
  name: Risk Management
- description: Automate financial research workflows with news, fundamental data, and analytics.
  name: Financial Research
- description: Generate regulatory compliance reports using reference data and pricing services.
  name: Regulatory Reporting
- description: Integrate Bloomberg data into portfolio management systems for real-time monitoring.
  name: Portfolio Management
---
