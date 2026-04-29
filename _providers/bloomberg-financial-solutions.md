---
api_count: 3
apis:
- description: Core Bloomberg API providing real-time and reference data access for financial applications across trading, risk, analytics, and compliance workflows.
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: Bloomberg's portfolio risk and analytics solution providing attribution, risk factor analysis, stress testing, and regulatory reporting for asset managers and institutional investors.
  name: Bloomberg PORT (Portfolio Risk and Analytics)
  slug: port-api
- description: Bloomberg's order and portfolio management system for asset managers supporting the full investment lifecycle from order creation through compliance and settlement.
  name: Bloomberg AIM (Asset and Investment Manager)
  slug: aim-api
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
description: Bloomberg Financial Solutions encompasses the full suite of Bloomberg financial data, analytics, and technology products designed to support front, middle, and back office workflows across asset management, banking, insurance, and corporate treasury. Solutions include market data, risk analytics, portfolio management, trading, compliance, and regulatory reporting capabilities.
features:
- description: Real-time and historical market data across equities, fixed income, FX, and commodities.
  name: Market Data
- description: Portfolio risk, attribution, and performance analytics.
  name: Portfolio Analytics
- description: End-to-end order management and execution workflow.
  name: Order Management
- description: Pre- and post-trade compliance monitoring and reporting.
  name: Compliance
- description: Regulatory data and reporting for MiFID II, EMIR, and other frameworks.
  name: Regulatory Reporting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Financial Solutions
skills: []
slug: bloomberg-financial-solutions
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-financial-solutions\nname: Bloomberg Financial Solutions\ndescription: Bloomberg Financial Solutions encompasses the full suite of Bloomberg\n  financial data, analytics, and technology products designed to support front, middle,\n  and back office workflows across asset management, banking, insurance, and corporate\n  treasury. Solutions include market data, risk analytics, portfolio management, trading,\n  compliance, and regulatory reporting capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-financial-solutions/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Financial Solutions\n- Market Data\n- Analytics\n- Trading\n- Risk Management\n- Bloomberg\napis:\n- aid: bloomberg-financial-solutions:blpapi\n  name: Bloomberg Open API (BLPAPI)\n  description: Core Bloomberg API providing\
  \ real-time and reference data access for\n    financial applications across trading, risk, analytics, and compliance workflows.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Core API\n  - Market Data\n  - Financial Data\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n- aid: bloomberg-financial-solutions:port-api\n  name: Bloomberg PORT (Portfolio Risk and Analytics)\n  description: Bloomberg's portfolio risk and analytics solution providing attribution,\n    risk factor analysis, stress testing, and regulatory reporting for asset managers\n    and institutional investors.\n  humanURL: https://www.bloomberg.com/professional/solution/portfolio-risk-analytics/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Portfolio Analytics\n  - Risk\n  - Attribution\n  - Regulatory\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/portfolio-risk-analytics/\n\
  - aid: bloomberg-financial-solutions:aim-api\n  name: Bloomberg AIM (Asset and Investment Manager)\n  description: Bloomberg's order and portfolio management system for asset managers\n    supporting the full investment lifecycle from order creation through compliance\n    and settlement.\n  humanURL: https://www.bloomberg.com/professional/solution/aim/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Order Management\n  - Portfolio Management\n  - Compliance\n  - OMS\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/aim/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n\
  \  data:\n  - name: Market Data\n    description: Real-time and historical market data across equities, fixed income,\n      FX, and commodities.\n  - name: Portfolio Analytics\n    description: Portfolio risk, attribution, and performance analytics.\n  - name: Order Management\n    description: End-to-end order management and execution workflow.\n  - name: Compliance\n    description: Pre- and post-trade compliance monitoring and reporting.\n  - name: Regulatory Reporting\n    description: Regulatory data and reporting for MiFID II, EMIR, and other frameworks.\n- type: UseCases\n  data:\n  - name: Asset Management\n    description: Full-service data and analytics for portfolio management and investment\n      operations.\n  - name: Investment Banking\n    description: Market data and analytics for capital markets, M&A, and advisory.\n  - name: Risk Management\n    description: Cross-asset risk analytics for trading and investment portfolios.\n  - name: Corporate Treasury\n    description:\
  \ FX, fixed income, and liquidity management solutions for corporates.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-financial-solutions/refs/heads/main/apis.yml
tags:
- Financial Solutions
- Market Data
- Analytics
- Trading
- Risk Management
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-financial-solutions/refs/heads/main/apis.yml
use_cases:
- description: Full-service data and analytics for portfolio management and investment operations.
  name: Asset Management
- description: Market data and analytics for capital markets, M&A, and advisory.
  name: Investment Banking
- description: Cross-asset risk analytics for trading and investment portfolios.
  name: Risk Management
- description: FX, fixed income, and liquidity management solutions for corporates.
  name: Corporate Treasury
---
