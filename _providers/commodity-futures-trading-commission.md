---
api_count: 3
api_specs:
- filename: cftc-cot-openapi.yml
  format: yaml
  label: CFTC Commitments of Traders SODA API
  slug: cftc-cot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/openapi/cftc-cot-openapi.yml
apis:
- description: Programmatic access to the CFTC Commitments of Traders weekly reports via the Socrata Open Data API hosted at publicreporting.cftc.gov. Datasets cover Legacy, Disaggregated, Traders in Financial Futur
  name: CFTC Commitments of Traders SODA API
  slug: cftc-cot-api
- description: 'The CFTC oversees Swap Data Repositories (SDRs) that collect and maintain swap transaction records as required by the Dodd-Frank Act. SDRs publish certain real-time public data and the CFTC publishes '
  name: CFTC Swap Data Repositories
  slug: cftc-swap-data-repositories
- description: The CFTC publishes monthly Bank Participation reports and other aggregate large trader reports that complement the weekly COT data. These reports are released as PDFs and HTML tables on cftc.gov.
  name: CFTC Bank Participation and Large Trader Reports
  slug: cftc-large-trader-reporting
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cftc.gov/
- title: ''
  type: JSON-LD
  url: json-ld/cftc-cot-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cftc-cot-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/cftc-cot-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/cftc-cot-rules.yml
- title: ''
  type: Capability
  url: capabilities/query-commitments-of-traders.yml
- title: ''
  type: Documentation
  url: https://publicreporting.cftc.gov/
- title: ''
  type: Reference
  url: https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm
- title: ''
  type: Privacy Policy
  url: https://www.cftc.gov/About/AbouttheCFTC/Privacy.html
created: '2024-12-03'
description: The Commodity Futures Trading Commission (CFTC) is the U.S. federal regulator for commodity futures and options markets. The CFTC publishes the weekly Commitments of Traders (COT) report and other public data through a Socrata Open Data API at publicreporting.cftc.gov, providing programmatic access to Legacy, Disaggregated, Traders in Financial Futures, and Supplemental Commodity Index Trader datasets, as well as swap data and large trader reports.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cftc Cot Context
  property_count: 5
  slug: cftc-cot-context
layout: provider
modified: '2026-04-28'
name: Commodity Futures Trading Commission
rules:
- name: Commodity Futures Trading Commission API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: cftc-cot-rules
skills: []
slug: commodity-futures-trading-commission
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: commodity-futures-trading-commission\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/apis.yml\nname: Commodity Futures Trading Commission\nx-type: government\ndescription: >-\n  The Commodity Futures Trading Commission (CFTC) is the U.S. federal regulator\n  for commodity futures and options markets. The CFTC publishes the weekly\n  Commitments of Traders (COT) report and other public data through a Socrata\n  Open Data API at publicreporting.cftc.gov, providing programmatic access to\n  Legacy, Disaggregated, Traders in Financial Futures, and Supplemental\n  Commodity Index Trader datasets, as well as swap data and large trader\n  reports.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CFTC\n  - Commitments of Traders\n  - Federal Government\n  - Financial\n  - Futures\n  - Open Data\n  - SODA\n  - Trading\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: commodity-futures-trading-commission:cftc-cot-api\n    name: CFTC Commitments of Traders SODA API\n    description: >-\n      Programmatic access to the CFTC Commitments of Traders weekly reports\n      via the Socrata Open Data API hosted at publicreporting.cftc.gov.\n      Datasets cover Legacy, Disaggregated, Traders in Financial Futures, and\n      Supplemental Commodity Index Trader formats for both futures-only and\n      combined futures-and-options positions.\n    humanURL: https://publicreporting.cftc.gov/\n    baseURL: https://publicreporting.cftc.gov/resource\n    tags:\n      - COT\n      - Open Data\n      - SODA\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://publicreporting.cftc.gov/\n      - type: Reference\n        url: https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm\n      - type: Reference\n        url: https://dev.socrata.com/foundry/publicreporting.cftc.gov\n      - type: OpenAPI\n   \
  \     url: openapi/cftc-cot-openapi.yml\n      - type: JSONSchema\n        url: json-schema/cftc-cot-schema.json\n    x-features:\n      - SoQL query language for filtering ($where, $select, $order)\n      - Page through up to 50,000 rows per request\n      - JSON, CSV, XML, RDF, RSS output formats\n      - No authentication token required for typical use\n      - Weekly Tuesday data updates\n    x-useCases:\n      - Build positioning dashboards for futures markets\n      - Compute net commercial vs non-commercial open interest\n      - Track managed money positioning in Disaggregated reports\n      - Integrate COT data into quantitative trading models\n  - aid: commodity-futures-trading-commission:cftc-swap-data-repositories\n    name: CFTC Swap Data Repositories\n    description: >-\n      The CFTC oversees Swap Data Repositories (SDRs) that collect and\n      maintain swap transaction records as required by the Dodd-Frank Act.\n      SDRs publish certain real-time public data and the\
  \ CFTC publishes\n      aggregate weekly swap reports.\n    humanURL: https://www.cftc.gov/MarketReports/SwapsReports/index.htm\n    baseURL: https://www.cftc.gov\n    tags:\n      - Dodd-Frank\n      - Swaps\n      - SDR\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://www.cftc.gov/MarketReports/SwapsReports/index.htm\n      - type: Reference\n        url: https://www.cftc.gov/IndustryOversight/DataRepositories/index.htm\n    x-features:\n      - Weekly Swaps Report aggregates dealer activity\n      - Real-time public dissemination of swap transactions via SDRs\n      - Coverage of credit, interest rate, FX, and commodity asset classes\n    x-useCases:\n      - Monitor weekly swap dealer activity\n      - Research aggregate gross notional outstanding by asset class\n      - Track post-Dodd-Frank market structure changes\n  - aid: commodity-futures-trading-commission:cftc-large-trader-reporting\n    name: CFTC Bank Participation and Large Trader Reports\n\
  \    description: >-\n      The CFTC publishes monthly Bank Participation reports and other\n      aggregate large trader reports that complement the weekly COT data.\n      These reports are released as PDFs and HTML tables on cftc.gov.\n    humanURL: https://www.cftc.gov/MarketReports/BankParticipationReports/index.htm\n    baseURL: https://www.cftc.gov\n    tags:\n      - Bank Participation\n      - Large Trader\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://www.cftc.gov/MarketReports/BankParticipationReports/index.htm\n      - type: Reference\n        url: https://www.cftc.gov/MarketReports/index.htm\n    x-features:\n      - Monthly bank participation in futures markets\n      - Industry-level breakdowns of large trader positions\n      - Released as HTML and PDF; not currently exposed via SODA\n    x-useCases:\n      - Track bank participation in major futures markets\n      - Research banks' net exposure across commodity sectors\ncommon:\n\
  \  - type: Website\n    url: https://www.cftc.gov/\n  - type: JSON-LD\n    url: json-ld/cftc-cot-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cftc-cot-schema.json\n  - type: Vocabulary\n    url: vocabulary/cftc-cot-vocabulary.yml\n  - type: SpectralRules\n    url: rules/cftc-cot-rules.yml\n  - type: Capability\n    url: capabilities/query-commitments-of-traders.yml\n  - type: Documentation\n    url: https://publicreporting.cftc.gov/\n  - type: Reference\n    url: https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm\n  - type: Privacy Policy\n    url: https://www.cftc.gov/About/AbouttheCFTC/Privacy.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/apis.yml
tags:
- CFTC
- Commitments of Traders
- Federal Government
- Financial
- Futures
- Open Data
- SODA
- Trading
url: https://raw.githubusercontent.com/api-evangelist/commodity-futures-trading-commission/refs/heads/main/apis.yml
use_cases: []
---
