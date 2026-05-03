---
api_count: 2
api_specs:
- filename: fred-openapi.yml
  format: yaml
  label: FRED API - Reserve Data
  slug: fred-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/openapi/fred-openapi.yml
apis:
- description: The Federal Reserve Economic Data (FRED) API provided by the Federal Reserve Bank of St. Louis offers programmatic access to reserve requirement data, monetary base data, and historical H.3 and H.6 st
  name: FRED API - Reserve Data
  slug: fred-api
- description: The Federal Reserve Board's Data Download Program provides structured access to Federal Reserve statistical releases including Regulation D reserve requirement data, H.6 Money Stock Measures, and hist
  name: Federal Reserve Data Download Program
  slug: fed-data-download
common:
- title: ''
  type: Website
  url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm
- title: ''
  type: Documentation
  url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm
- title: ''
  type: Policy
  url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm
- title: ''
  type: Regulation
  url: https://www.ecfr.gov/current/title-12/chapter-II/subchapter-A/part-204
- title: ''
  type: DataDownload
  url: https://www.federalreserve.gov/datadownload/
- title: ''
  type: FRED
  url: https://fred.stlouisfed.org/categories/32217
- title: ''
  type: H6Release
  url: https://www.federalreserve.gov/releases/h6/
- title: ''
  type: GitHubOrganization
  url: https://github.com/federalreserve
created: '2025-01-01'
description: Reserve Requirements refers to the Federal Reserve's Regulation D framework governing reserve requirement ratios for depository institutions. As of March 26, 2020, the Federal Reserve reduced all reserve requirement ratios to zero percent, eliminating reserve requirements for all depository institutions. The Federal Reserve provides data access through FRED (Federal Reserve Economic Data), the H.6 Money Stock Measures release, and the federalreserve.gov data download program for historical reserve and monetary base data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Reserve Requirements Context
  property_count: 0
  slug: reserve-requirements-context
layout: provider
modified: '2026-05-02'
name: Reserve Requirements
rules:
- name: Reserve Requirements API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 4
  slug: reserve-requirements-rules
skills: []
slug: reserve-requirements
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: reserve-requirements\nname: Reserve Requirements\ndescription: >-\n  Reserve Requirements refers to the Federal Reserve's Regulation D framework\n  governing reserve requirement ratios for depository institutions. As of\n  March 26, 2020, the Federal Reserve reduced all reserve requirement ratios to\n  zero percent, eliminating reserve requirements for all depository institutions.\n  The Federal Reserve provides data access through FRED (Federal Reserve Economic\n  Data), the H.6 Money Stock Measures release, and the federalreserve.gov\n  data download program for historical reserve and monetary base data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Reserve Requirements\n  - Federal Reserve\n  - Banking Regulation\n  - Monetary Policy\n  - Regulation D\n  - Finance\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\n\
  specificationVersion: '0.19'\napis:\n  - aid: reserve-requirements:fred-api\n    name: FRED API - Reserve Data\n    description: >-\n      The Federal Reserve Economic Data (FRED) API provided by the Federal\n      Reserve Bank of St. Louis offers programmatic access to reserve requirement\n      data, monetary base data, and historical H.3 and H.6 statistical release\n      data. FRED provides a comprehensive REST API with API key authentication\n      for accessing economic time series data.\n    humanURL: https://fred.stlouisfed.org/\n    baseURL: https://api.stlouisfed.org/fred\n    tags:\n      - Federal Reserve\n      - Economic Data\n      - Reserve Requirements\n      - Monetary Base\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://fred.stlouisfed.org/docs/api/fred/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/openapi/fred-openapi.yml\n      - type:\
  \ JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-schema/fred-series-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-schema/fred-observation-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-structure/fred-series-structure.json\n      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/json-ld/reserve-requirements-context.jsonld\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/rules/reserve-requirements-rules.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/vocabulary/reserve-requirements-vocabulary.yml\n\
  \    contact:\n      - FN: Federal Reserve Bank of St. Louis\n        url: https://fred.stlouisfed.org/\n  - aid: reserve-requirements:fed-data-download\n    name: Federal Reserve Data Download Program\n    description: >-\n      The Federal Reserve Board's Data Download Program provides structured\n      access to Federal Reserve statistical releases including Regulation D\n      reserve requirement data, H.6 Money Stock Measures, and historical\n      reserve data through a web-based data download interface.\n    humanURL: https://www.federalreserve.gov/datadownload/\n    tags:\n      - Federal Reserve\n      - Statistical Releases\n      - Regulation D\n      - Reserve Requirements\n      - Data Download\n    properties:\n      - type: Documentation\n        url: https://www.federalreserve.gov/datadownload/\n      - type: About\n        url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm\ncommon:\n  - type: Website\n    url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm\n\
  \  - type: Documentation\n    url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm\n  - type: Policy\n    url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm\n  - type: Regulation\n    url: https://www.ecfr.gov/current/title-12/chapter-II/subchapter-A/part-204\n  - type: DataDownload\n    url: https://www.federalreserve.gov/datadownload/\n  - type: FRED\n    url: https://fred.stlouisfed.org/categories/32217\n  - type: H6Release\n    url: https://www.federalreserve.gov/releases/h6/\n  - type: GitHubOrganization\n    url: https://github.com/federalreserve\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/apis.yml
tags:
- Reserve Requirements
- Federal Reserve
- Banking Regulation
- Monetary Policy
- Regulation D
- Finance
url: https://raw.githubusercontent.com/api-evangelist/reserve-requirements/refs/heads/main/apis.yml
use_cases: []
---
