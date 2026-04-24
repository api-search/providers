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
