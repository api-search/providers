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
source_yaml: "aid: blackrock\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/blackrock/refs/heads/main/apis.yml\nname: BlackRock\ndescription: >-\n  BlackRock is the world's largest asset manager with over $10 trillion in assets under\n  management. Through its Aladdin platform, BlackRock provides institutional investors,\n  wealth managers, and financial services firms with risk analytics, portfolio management,\n  and data capabilities via APIs. The Aladdin platform powers investment operations for\n  many of the world's largest pension funds, insurers, and asset managers.\ntags:\n  - Asset Management\n  - Finance\n  - FinTech\n  - Investment Management\n  - Portfolio Management\n  - Risk Analytics\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2026-03-21'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: blackrock:aladdin-api\n    name: BlackRock Aladdin API\n    description: >-\n      The Aladdin\
  \ Developer program provides APIs that enable clients to access\n      BlackRock's Aladdin platform capabilities programmatically. Aladdin APIs\n      support portfolio analytics, risk reporting, data access, order management,\n      and workflow automation for institutional asset managers, wealth managers,\n      and financial services clients.\n    humanURL: https://www.blackrock.com/aladdin/products/aladdin-developer\n    tags:\n      - Asset Management\n      - Finance\n      - Portfolio Management\n      - Risk Analytics\n    properties:\n      - type: Documentation\n        url: https://www.blackrock.com/aladdin/products/aladdin-developer\n      - type: SDK\n        url: https://github.com/blackrock/aladdinsdk\n        title: Python SDK (AladdinSDK)\n      - type: JSONSchema\n        url: json-schema/blackrock-portfolio-schema.json\n      - type: JSONSchema\n        url: json-schema/blackrock-risk-report-schema.json\n      - type: JSONStructure\n        url: json-structure/blackrock-portfolio-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/blackrock-risk-report-structure.json\n      - type: JSONLD\n        url: json-ld/blackrock-context.jsonld\n      - type: Example\n        url: examples/blackrock-portfolio-example.json\n      - type: Example\n        url: examples/blackrock-risk-report-example.json\ncommon:\n  - type: Website\n    url: https://www.blackrock.com\n  - type: Documentation\n    url: https://www.blackrock.com/aladdin/products/aladdin-developer\n  - type: GitHubOrganization\n    url: https://github.com/blackrock\n  - type: TermsOfService\n    url: https://www.blackrock.com/us/individual/regulatory/privacy-policy\n  - type: PrivacyPolicy\n    url: https://www.blackrock.com/us/individual/regulatory/privacy-policy\n  - type: Blog\n    url: https://www.blackrock.com/us/individual/insights\n  - type: SpectralRules\n    url: rules/blackrock-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/blackrock-aladdin.yaml\n  - type: Vocabulary\n\
  \    url: vocabulary/blackrock-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Aladdin Risk Analytics\n        description: >-\n          Multi-asset risk measurement and attribution capabilities accessible\n          via API, including VaR, factor exposures, stress testing, and scenario\n          analysis.\n      - name: Portfolio Management APIs\n        description: >-\n          APIs for portfolio construction, optimization, rebalancing, and\n          compliance monitoring integrated with the Aladdin operating system.\n      - name: Data Access Layer\n        description: >-\n          Structured access to market data, security reference data, and\n          portfolio data via RESTful APIs with enterprise data governance.\n      - name: Order Management System Integration\n        description: >-\n          APIs for trade order management, execution, and settlement workflows\n          integrating with OMS and EMS systems.\n      - name: AladdinSDK\n        description:\
  \ >-\n          Open-source Python SDK providing programmatic access to Aladdin APIs\n          with authentication, pagination, and data transformation utilities.\n      - name: Workflow Automation\n        description: >-\n          Event-driven workflow APIs enabling clients to automate investment\n          operations processes and integrate with third-party systems.\n  - type: UseCases\n    data:\n      - name: Institutional Risk Reporting\n        description: >-\n          Institutional investors use Aladdin APIs to generate regulatory risk\n          reports, UCITS compliance reports, and investor disclosures.\n      - name: Portfolio Analytics Integration\n        description: >-\n          Wealth managers and RIAs integrate Aladdin risk analytics into their\n          own client-facing and advisor-facing platforms.\n      - name: Fintech Data Integration\n        description: >-\n          FinTech companies access structured investment data through Aladdin\n          APIs to\
  \ power analytics, research, and advisory products.\n      - name: Automated Rebalancing\n        description: >-\n          Portfolio managers automate rebalancing workflows using Aladdin APIs\n          to trigger trades based on drift thresholds and target allocations.\n      - name: Multi-Manager Aggregation\n        description: >-\n          Family offices and fund-of-funds use Aladdin APIs to aggregate\n          portfolio data across multiple managers into a single risk view.\n  - type: Integrations\n    data:\n      - name: Charles River Development\n        description: >-\n          Aladdin integrates with Charles River IMS for order management and\n          compliance workflow automation.\n      - name: SimCorp Dimension\n        description: >-\n          Integration between Aladdin risk analytics and SimCorp's portfolio\n          management and accounting systems.\n      - name: Bloomberg\n        description: >-\n          Market data and analytics integrations with Bloomberg\
  \ Data License\n          and Bloomberg PORT for risk and performance.\n      - name: Refinitiv\n        description: >-\n          Security master data and market data integrations with Refinitiv\n          Datascope and Eikon platforms.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/blackrock/refs/heads/main/apis.yml
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
