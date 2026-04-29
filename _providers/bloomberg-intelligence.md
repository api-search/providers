---
api_count: 5
apis:
- description: The core Bloomberg API providing real-time market data, reference data, historical data, and intraday tick data. SDKs available for C++, Java, Python, C#/.NET, and Perl. Connects to Bloomberg Terminal
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: A powerful query language for requesting Bloomberg data with flexible filtering, aggregation, and calculation capabilities. Enables custom data requests beyond standard API fields.
  name: Bloomberg Query Language (BQL)
  slug: bql
- description: Enterprise data delivery platform providing bulk financial data via SFTP and SOAP API. Supports requesting reference data, pricing data, corporate actions, and derived data for specified securities an
  name: Bloomberg Data License API
  slug: data-license
- description: High-performance server-side API for distributing Bloomberg data within enterprise environments. Supports B-PIPE for managed data distribution with authentication, authorization, and entitlement manag
  name: Bloomberg Server API (SAPI)
  slug: server-api
- description: Access to Bloomberg Intelligence research reports, analyst insights, industry analysis, and company research across equities, credit, government, and ESG.
  name: Bloomberg Intelligence Research API
  slug: research-api
common:
- title: ''
  type: Portal
  url: https://developer.bloomberg.com/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/support/api-library/
- title: ''
  type: GettingStarted
  url: https://bloomberg.github.io/blpapi-docs/
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
description: Bloomberg Intelligence provides research, data, and analytics on companies, industries, credit, government, litigation, and ESG. The Bloomberg developer platform offers BLPAPI (Bloomberg Open API) for real-time and reference data, BQL (Bloomberg Query Language) for flexible data queries, Data License for enterprise data delivery, and Server API / B-PIPE for high-performance data distribution.
features:
- description: Streaming real-time prices, quotes, and market activity across global markets.
  name: Real-Time Market Data
- description: Static and semi-static security attributes, corporate actions, and fundamentals.
  name: Reference Data
- description: End-of-day and intraday historical pricing, volume, and analytics data.
  name: Historical Data
- description: Tick-by-tick trade and quote data for detailed market microstructure analysis.
  name: Intraday Tick Data
- description: Flexible query language for custom data requests with filtering and aggregation.
  name: Bloomberg Query Language (BQL)
- description: Bulk enterprise data delivery via SFTP and SOAP for reference data, pricing, and analytics.
  name: Data License
- description: Managed high-performance data distribution with entitlement management for enterprise.
  name: B-PIPE Data Distribution
- description: Analyst research reports, industry analysis, and ESG insights from Bloomberg Intelligence.
  name: Intelligence Research
- description: Official SDKs for Python, Java, C++, C#/.NET, Node.js, and Perl.
  name: Multi-Language SDKs
- description: Authentication, authorization, and permissioning for enterprise data distribution.
  name: Enterprise Authentication
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-17'
name: Bloomberg Intelligence
rules:
- name: Bloomberg Intelligence API Rules
  rule_count: 17
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 2
  slug: bloomberg-intelligence-spectral-rules
skills: []
slug: bloomberg-intelligence
solutions:
- description: Professional terminal with integrated BLPAPI for desktop application development.
  name: Bloomberg Terminal
- description: Server API and B-PIPE for enterprise-wide data distribution.
  name: Bloomberg Enterprise
- description: Bulk data delivery platform for enterprise data management.
  name: Bloomberg Data License
- description: Research and analysis platform with proprietary data and expert insights.
  name: Bloomberg Intelligence
source_yaml: "aid: bloomberg-intelligence\nname: Bloomberg Intelligence\ndescription: Bloomberg Intelligence provides research, data, and analytics on companies,\n  industries, credit, government, litigation, and ESG. The Bloomberg developer platform\n  offers BLPAPI (Bloomberg Open API) for real-time and reference data, BQL (Bloomberg\n  Query Language) for flexible data queries, Data License for enterprise data delivery,\n  and Server API / B-PIPE for high-performance data distribution.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-intelligence/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntags:\n- Company Analysis\n- Credit Research\n- ESG Data\n- Financial Data\n- Financial Research\n- Market Data\n- Market Intelligence\napis:\n- aid: bloomberg-intelligence:blpapi\n  name: Bloomberg Open API (BLPAPI)\n  description:\
  \ The core Bloomberg API providing real-time market data, reference data,\n    historical data, and intraday tick data. SDKs available for C++, Java, Python,\n    C#/.NET, and Perl. Connects to Bloomberg Terminal and Enterprise products.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Core API\n  - Market Data\n  - Real-Time Data\n  - Reference Data\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n  - type: GettingStarted\n    url: https://data.bloomberglp.com/professional/sites/10/2017/03/BLPAPI-Core-Developer-Guide.pdf\n  - type: GitHubRepository\n    url: https://github.com/bloomberg/blpapi-node\n  - type: SDK\n    url: https://pypi.org/project/blpapi/\n    title: Python SDK\n- aid: bloomberg-intelligence:bql\n  name: Bloomberg Query Language (BQL)\n  description: A powerful query language for requesting Bloomberg data with flexible\n    filtering, aggregation, and calculation capabilities.\
  \ Enables custom data requests\n    beyond standard API fields.\n  humanURL: https://www.bloomberg.com/professional/support/api-library/\n  baseURL: bql://bloomberg.com\n  tags:\n  - Analytics\n  - Data Query\n  - Query Language\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\n- aid: bloomberg-intelligence:data-license\n  name: Bloomberg Data License API\n  description: Enterprise data delivery platform providing bulk financial data via\n    SFTP and SOAP API. Supports requesting reference data, pricing data, corporate\n    actions, and derived data for specified securities and data fields.\n  humanURL: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n  baseURL: https://dlws.bloomberg.com\n  tags:\n  - Bulk Data\n  - Data License\n  - Enterprise\n  - SFTP\n  - SOAP\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/products/data/data-management/data-license/\n\
  - aid: bloomberg-intelligence:server-api\n  name: Bloomberg Server API (SAPI)\n  description: High-performance server-side API for distributing Bloomberg data within\n    enterprise environments. Supports B-PIPE for managed data distribution with authentication,\n    authorization, and entitlement management.\n  humanURL: https://www.bloomberg.com/professional/support/api-library/\n  baseURL: blpapi://server:8194\n  tags:\n  - B-PIPE\n  - Enterprise\n  - High Performance\n  - Server API\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\n- aid: bloomberg-intelligence:research-api\n  name: Bloomberg Intelligence Research API\n  description: Access to Bloomberg Intelligence research reports, analyst insights,\n    industry analysis, and company research across equities, credit, government, and\n    ESG.\n  humanURL: https://www.bloomberg.com/professional/solution/bloomberg-intelligence/\n  baseURL: https://api.bloomberg.com/intelligence\n\
  \  tags:\n  - Analysis\n  - ESG\n  - Industry Research\n  - Reports\n  - Research\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bloomberg-intelligence/\ncommon:\n- type: Portal\n  url: https://developer.bloomberg.com/\n- type: Documentation\n  url: https://www.bloomberg.com/professional/support/api-library/\n- type: GettingStarted\n  url: https://bloomberg.github.io/blpapi-docs/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n- type: SDK\n  url: https://pypi.org/project/blpapi/\n  title: Python SDK (blpapi)\n- type: SDK\n  url: https://www.npmjs.com/package/blpapi\n  title: Node.js SDK\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Real-Time Market Data\n    description: Streaming real-time prices, quotes, and market activity\
  \ across global\n      markets.\n  - name: Reference Data\n    description: Static and semi-static security attributes, corporate actions, and\n      fundamentals.\n  - name: Historical Data\n    description: End-of-day and intraday historical pricing, volume, and analytics\n      data.\n  - name: Intraday Tick Data\n    description: Tick-by-tick trade and quote data for detailed market microstructure\n      analysis.\n  - name: Bloomberg Query Language (BQL)\n    description: Flexible query language for custom data requests with filtering and\n      aggregation.\n  - name: Data License\n    description: Bulk enterprise data delivery via SFTP and SOAP for reference data,\n      pricing, and analytics.\n  - name: B-PIPE Data Distribution\n    description: Managed high-performance data distribution with entitlement management\n      for enterprise.\n  - name: Intelligence Research\n    description: Analyst research reports, industry analysis, and ESG insights from\n      Bloomberg Intelligence.\n\
  \  - name: Multi-Language SDKs\n    description: Official SDKs for Python, Java, C++, C#/.NET, Node.js, and Perl.\n  - name: Enterprise Authentication\n    description: Authentication, authorization, and permissioning for enterprise data\n      distribution.\n- type: UseCases\n  data:\n  - name: Trading Systems\n    description: Feed real-time market data into trading and execution management\n      systems.\n  - name: Risk Management\n    description: Source pricing and reference data for portfolio risk calculations.\n  - name: Quantitative Research\n    description: Access historical data and BQL for quantitative analysis and backtesting.\n  - name: Portfolio Analytics\n    description: Retrieve security attributes and pricing for portfolio valuation\n      and attribution.\n  - name: Compliance and Reporting\n    description: Source reference data for regulatory reporting and compliance.\n  - name: Data Warehousing\n    description: Bulk load financial data via Data License for enterprise\
  \ data warehouses.\n  - name: ESG Analysis\n    description: Access Bloomberg Intelligence ESG scores and research for sustainable\n      investing.\n  - name: Credit Research\n    description: Access credit analysis, ratings data, and fixed income research.\n- type: Solutions\n  data:\n  - name: Bloomberg Terminal\n    description: Professional terminal with integrated BLPAPI for desktop application\n      development.\n  - name: Bloomberg Enterprise\n    description: Server API and B-PIPE for enterprise-wide data distribution.\n  - name: Bloomberg Data License\n    description: Bulk data delivery platform for enterprise data management.\n  - name: Bloomberg Intelligence\n    description: Research and analysis platform with proprietary data and expert insights.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-intelligence/refs/heads/main/apis.yml
tags:
- Company Analysis
- Credit Research
- ESG Data
- Financial Data
- Financial Research
- Market Data
- Market Intelligence
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-intelligence/refs/heads/main/apis.yml
use_cases:
- description: Feed real-time market data into trading and execution management systems.
  name: Trading Systems
- description: Source pricing and reference data for portfolio risk calculations.
  name: Risk Management
- description: Access historical data and BQL for quantitative analysis and backtesting.
  name: Quantitative Research
- description: Retrieve security attributes and pricing for portfolio valuation and attribution.
  name: Portfolio Analytics
- description: Source reference data for regulatory reporting and compliance.
  name: Compliance and Reporting
- description: Bulk load financial data via Data License for enterprise data warehouses.
  name: Data Warehousing
- description: Access Bloomberg Intelligence ESG scores and research for sustainable investing.
  name: ESG Analysis
- description: Access credit analysis, ratings data, and fixed income research.
  name: Credit Research
---
