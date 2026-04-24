---
api_count: 1
apis:
- description: The Aladdin Developer program provides APIs that enable clients to access BlackRock's Aladdin platform capabilities programmatically. Aladdin APIs support portfolio analytics, risk reporting, data acc
  name: BlackRock Aladdin API
  slug: aladdin-api
capabilities:
- description: ''
  name: Blackrock Aladdin
  slug: blackrock-aladdin
common:
- title: ''
  type: Website
  url: https://www.blackrock.com
- title: ''
  type: Documentation
  url: https://www.blackrock.com/aladdin/products/aladdin-developer
- title: ''
  type: GitHubOrganization
  url: https://github.com/blackrock
- title: ''
  type: TermsOfService
  url: https://www.blackrock.com/us/individual/regulatory/privacy-policy
- title: ''
  type: PrivacyPolicy
  url: https://www.blackrock.com/us/individual/regulatory/privacy-policy
- title: ''
  type: Blog
  url: https://www.blackrock.com/us/individual/insights
- title: ''
  type: SpectralRules
  url: rules/blackrock-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/blackrock-aladdin.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/blackrock-vocabulary.yaml
created: '2026-03-21'
description: BlackRock is the world's largest asset manager with over $10 trillion in assets under management. Through its Aladdin platform, BlackRock provides institutional investors, wealth managers, and financial services firms with risk analytics, portfolio management, and data capabilities via APIs. The Aladdin platform powers investment operations for many of the world's largest pension funds, insurers, and asset managers.
features:
- description: Multi-asset risk measurement and attribution capabilities accessible via API, including VaR, factor exposures, stress testing, and scenario analysis.
  name: Aladdin Risk Analytics
- description: APIs for portfolio construction, optimization, rebalancing, and compliance monitoring integrated with the Aladdin operating system.
  name: Portfolio Management APIs
- description: Structured access to market data, security reference data, and portfolio data via RESTful APIs with enterprise data governance.
  name: Data Access Layer
- description: APIs for trade order management, execution, and settlement workflows integrating with OMS and EMS systems.
  name: Order Management System Integration
- description: Open-source Python SDK providing programmatic access to Aladdin APIs with authentication, pagination, and data transformation utilities.
  name: AladdinSDK
- description: Event-driven workflow APIs enabling clients to automate investment operations processes and integrate with third-party systems.
  name: Workflow Automation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Aladdin integrates with Charles River IMS for order management and compliance workflow automation.
  name: Charles River Development
- description: Integration between Aladdin risk analytics and SimCorp's portfolio management and accounting systems.
  name: SimCorp Dimension
- description: Market data and analytics integrations with Bloomberg Data License and Bloomberg PORT for risk and performance.
  name: Bloomberg
- description: Security master data and market data integrations with Refinitiv Datascope and Eikon platforms.
  name: Refinitiv
jsonld:
- class_count: 13
  name: Blackrock Context
  property_count: 0
  slug: blackrock-context
layout: provider
modified: '2026-04-21'
name: BlackRock
rules:
- name: BlackRock API Rules
  rule_count: 5
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 5
  slug: blackrock-spectral-rules
skills: []
slug: blackrock
solutions: []
tags:
- Asset Management
- Finance
- FinTech
- Investment Management
- Portfolio Management
- Risk Analytics
url: https://raw.githubusercontent.com/api-evangelist/blackrock/refs/heads/main/apis.yml
use_cases:
- description: Institutional investors use Aladdin APIs to generate regulatory risk reports, UCITS compliance reports, and investor disclosures.
  name: Institutional Risk Reporting
- description: Wealth managers and RIAs integrate Aladdin risk analytics into their own client-facing and advisor-facing platforms.
  name: Portfolio Analytics Integration
- description: FinTech companies access structured investment data through Aladdin APIs to power analytics, research, and advisory products.
  name: Fintech Data Integration
- description: Portfolio managers automate rebalancing workflows using Aladdin APIs to trigger trades based on drift thresholds and target allocations.
  name: Automated Rebalancing
- description: Family offices and fund-of-funds use Aladdin APIs to aggregate portfolio data across multiple managers into a single risk view.
  name: Multi-Manager Aggregation
---
