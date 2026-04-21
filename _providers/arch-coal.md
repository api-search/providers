---
api_count: 1
apis:
- description: Arch Coal provides investor relations data including SEC filings, financial reports, coal production data, and market information for shareholders and analysts.
  name: Arch Coal Investor Relations
  slug: arch-coal-investor-relations
common:
- title: ''
  type: Portal
  url: https://www.arch-coal.com/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/rules/arch-coal-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/vocabulary/arch-coal-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/json-ld/arch-coal-investor-relations-api-context.jsonld
created: '2026-03-23'
description: Arch Coal (now Arch Resources) is a Fortune 500 producer and marketer of metallurgical and thermal coal from mines in the United States, supplying steel manufacturers, electric utilities, and industrial customers worldwide.
features:
- description: High-quality metallurgical coal for steelmaking from mines in West Virginia and Virginia.
  name: Metallurgical Coal
- description: Thermal coal for electricity generation from mines in Wyoming's Powder River Basin.
  name: Thermal Coal
- description: Publicly reported mine safety and environmental performance metrics.
  name: Safety Performance Data
- description: Quarterly coal production and sales volume reporting for investors and analysts.
  name: Production Reporting
- description: Annual reports, 10-K, 10-Q, and 8-K filings available through SEC EDGAR.
  name: SEC Filings
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: All SEC filings available through the EDGAR electronic filing system at sec.gov.
  name: SEC EDGAR
- description: Financial data integrated with Bloomberg terminal for market analysis.
  name: Bloomberg
- description: Production and financial data available through Refinitiv (formerly Thomson Reuters) data services.
  name: Refinitiv
jsonld:
- class_count: 5
  name: Arch Coal Investor Relations Api Context
  property_count: 18
  slug: arch-coal-investor-relations-api-context
layout: provider
modified: '2026-04-19'
name: Arch Coal
rules:
- name: Arch Coal API Rules
  rule_count: 13
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 3
  slug: arch-coal-spectral-rules
skills: []
slug: arch-coal
solutions: []
tags:
- Mining
- Coal
- Metallurgical Coal
- Thermal Coal
- Energy
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/apis.yml
use_cases:
- description: Analyze Arch Coal financial performance, production data, and market position for investment decisions.
  name: Investment Research
- description: Access environmental, safety, and governance data for ESG analysis and reporting.
  name: ESG Reporting
- description: Steel manufacturers and utilities use production data for supply chain planning and procurement.
  name: Supply Chain Planning
- description: Track coal pricing, production volumes, and export data for commodity market research.
  name: Commodity Market Analysis
---
