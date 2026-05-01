---
api_count: 1
api_specs:
- filename: archrock-investor-relations-api.yaml
  format: yaml
  label: Archrock Investor Relations API
  slug: archrock-investor-relations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/openapi/archrock-investor-relations-api.yaml
apis:
- description: Archrock provides investor relations data including SEC filings, financial reports, compression fleet statistics, and operational performance metrics for shareholders and analysts.
  name: Archrock Investor Relations API
  slug: archrock-investor-relations-api
common:
- title: ''
  type: Portal
  url: https://www.archrock.com/
- title: ''
  type: Documentation
  url: https://www.archrock.com/investor-relations
- title: ''
  type: Blog
  url: https://www.archrock.com/news
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/rules/archrock-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/vocabulary/archrock-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/json-ld/archrock-investor-relations-api-context.jsonld
created: '2026-03-23'
description: 'Archrock (NYSE: AROC) is the premier provider of natural gas compression services and equipment to customers in the oil and natural gas industry throughout the United States. The company operates a large fleet of compression equipment and provides contract operations and aftermarket services.'
features:
- description: Contract operations and maintenance of natural gas compression equipment across the US.
  name: Natural Gas Compression
- description: Management of one of the largest compression fleets in North America with diverse horsepower ratings.
  name: Fleet Management
- description: Parts, service, and maintenance for third-party compression equipment.
  name: Aftermarket Services
- description: Financial performance, fleet statistics, and operational metrics for investors and analysts.
  name: Investor Relations Data
- description: Annual reports, 10-K, 10-Q, and 8-K filings available through SEC EDGAR.
  name: SEC Filings
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: All SEC filings available through the EDGAR electronic filing system.
  name: SEC EDGAR
- description: Financial and operational data integrated with Bloomberg terminal.
  name: Bloomberg
- description: Production and financial data available through Refinitiv data services.
  name: Refinitiv
jsonld:
- class_count: 7
  name: Archrock Investor Relations Api Context
  property_count: 0
  slug: archrock-investor-relations-api-context
layout: provider
modified: '2026-04-19'
name: Archrock
rules:
- name: Archrock API Rules
  rule_count: 12
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 5
  slug: archrock-spectral-rules
skills: []
slug: archrock
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: archrock\nname: Archrock\ndescription: 'Archrock (NYSE: AROC) is the premier provider of natural gas compression services and equipment to customers in the oil and natural gas industry throughout the United States. The company operates a large fleet of compression equipment and provides contract operations and aftermarket services.'\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Natural Gas\n- Compression Services\n- Oil And Gas\n- Energy\n- Industrial\n- 'NYSE: AROC'\nurl: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: archrock:archrock-investor-relations-api\n  name: Archrock Investor Relations API\n  description: Archrock provides investor relations data including SEC filings, financial reports, compression fleet statistics, and operational performance metrics for shareholders and analysts.\n\
  \  humanURL: https://www.archrock.com/investor-relations\n  tags:\n  - Investor Relations\n  - SEC Filings\n  - Financial Data\n  - Compression Services\n  - Natural Gas\n  properties:\n  - type: Documentation\n    url: https://www.archrock.com/investor-relations\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/openapi/archrock-investor-relations-api.yaml\ncommon:\n- type: Portal\n  url: https://www.archrock.com/\n- type: Documentation\n  url: https://www.archrock.com/investor-relations\n- type: Blog\n  url: https://www.archrock.com/news\n- type: Features\n  data:\n  - name: Natural Gas Compression\n    description: Contract operations and maintenance of natural gas compression equipment across the US.\n  - name: Fleet Management\n    description: Management of one of the largest compression fleets in North America with diverse horsepower ratings.\n  - name: Aftermarket Services\n    description: Parts, service, and maintenance for\
  \ third-party compression equipment.\n  - name: Investor Relations Data\n    description: Financial performance, fleet statistics, and operational metrics for investors and analysts.\n  - name: SEC Filings\n    description: Annual reports, 10-K, 10-Q, and 8-K filings available through SEC EDGAR.\n- type: UseCases\n  data:\n  - name: Investment Research\n    description: Analyze Archrock financial performance and fleet utilization for investment decisions.\n  - name: Energy Sector Analysis\n    description: Track natural gas compression services market trends and operational data.\n  - name: ESG Reporting\n    description: Access environmental and safety performance data for ESG analysis.\n  - name: Supply Chain Planning\n    description: Operators use Archrock fleet data for compression capacity planning.\n- type: Integrations\n  data:\n  - name: SEC EDGAR\n    description: All SEC filings available through the EDGAR electronic filing system.\n  - name: Bloomberg\n    description: Financial\
  \ and operational data integrated with Bloomberg terminal.\n  - name: Refinitiv\n    description: Production and financial data available through Refinitiv data services.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/rules/archrock-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/vocabulary/archrock-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/json-ld/archrock-investor-relations-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/apis.yml
tags:
- Natural Gas
- Compression Services
- Oil And Gas
- Energy
- Industrial
- 'NYSE: AROC'
url: https://raw.githubusercontent.com/api-evangelist/archrock/refs/heads/main/apis.yml
use_cases:
- description: Analyze Archrock financial performance and fleet utilization for investment decisions.
  name: Investment Research
- description: Track natural gas compression services market trends and operational data.
  name: Energy Sector Analysis
- description: Access environmental and safety performance data for ESG analysis.
  name: ESG Reporting
- description: Operators use Archrock fleet data for compression capacity planning.
  name: Supply Chain Planning
---
