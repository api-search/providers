---
api_count: 1
api_specs:
- filename: arch-coal-investor-relations-api.yaml
  format: yaml
  label: Arch Coal Investor Relations
  slug: arch-coal-investor-relations
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/openapi/arch-coal-investor-relations-api.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: arch-coal\nname: Arch Coal\ndescription: Arch Coal (now Arch Resources) is a Fortune 500 producer and marketer of metallurgical and thermal coal from mines in the United States, supplying steel manufacturers, electric utilities,\n  and industrial customers worldwide.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Mining\n- Coal\n- Metallurgical Coal\n- Thermal Coal\n- Energy\n- Fortune 500\nurl: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: arch-coal:arch-coal-investor-relations\n  name: Arch Coal Investor Relations\n  description: Arch Coal provides investor relations data including SEC filings, financial reports, coal production data, and market information for shareholders and analysts.\n  humanURL: https://archresources.com/investor-relations/\n  tags:\n  - Investor Relations\n \
  \ - SEC Filings\n  - Financial Data\n  - Coal Production\n  properties:\n  - type: Documentation\n    url: https://archresources.com/investor-relations/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/openapi/arch-coal-investor-relations-api.yaml\ncommon:\n- type: Portal\n  url: https://www.arch-coal.com/\n- type: Features\n  data:\n  - name: Metallurgical Coal\n    description: High-quality metallurgical coal for steelmaking from mines in West Virginia and Virginia.\n  - name: Thermal Coal\n    description: Thermal coal for electricity generation from mines in Wyoming's Powder River Basin.\n  - name: Safety Performance Data\n    description: Publicly reported mine safety and environmental performance metrics.\n  - name: Production Reporting\n    description: Quarterly coal production and sales volume reporting for investors and analysts.\n  - name: SEC Filings\n    description: Annual reports, 10-K, 10-Q, and 8-K filings available\
  \ through SEC EDGAR.\n- type: UseCases\n  data:\n  - name: Investment Research\n    description: Analyze Arch Coal financial performance, production data, and market position for investment decisions.\n  - name: ESG Reporting\n    description: Access environmental, safety, and governance data for ESG analysis and reporting.\n  - name: Supply Chain Planning\n    description: Steel manufacturers and utilities use production data for supply chain planning and procurement.\n  - name: Commodity Market Analysis\n    description: Track coal pricing, production volumes, and export data for commodity market research.\n- type: Integrations\n  data:\n  - name: SEC EDGAR\n    description: All SEC filings available through the EDGAR electronic filing system at sec.gov.\n  - name: Bloomberg\n    description: Financial data integrated with Bloomberg terminal for market analysis.\n  - name: Refinitiv\n    description: Production and financial data available through Refinitiv (formerly Thomson Reuters)\
  \ data services.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/rules/arch-coal-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/vocabulary/arch-coal-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/json-ld/arch-coal-investor-relations-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/arch-coal/refs/heads/main/apis.yml
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
