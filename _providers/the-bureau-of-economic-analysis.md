---
api_count: 1
api_specs:
- filename: index.htm
  format: yaml
  label: The Bureau of Economic Analysis API
  slug: the-bureau-of-economic-analysis
  spec_type: OpenAPI
  url: https://apps.bea.gov/API/docs/index.htm
apis:
- description: The Bureau of Economic Analysis (BEA) Data API provides programmatic access to BEA published economic statistics. Methods include retrieving statistical data and metadata from datasets covering Nation
  name: The Bureau of Economic Analysis API
  slug: the-bureau-of-economic-analysis
common:
- title: ''
  type: Website
  url: https://www.bea.gov/
- title: ''
  type: Documentation
  url: https://www.bea.gov/resources/for-developers
- title: ''
  type: Sign Up
  url: https://apps.bea.gov/api/signup/
- title: ''
  type: GettingStarted
  url: https://apps.bea.gov/api/_pdf/bea_web_service_api_user_guide.pdf
- title: ''
  type: GitHub Organization
  url: https://github.com/us-bea
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/openapi/the-bureau-of-economic-analysis-openapi.yml
- title: ''
  type: InteractiveData
  url: https://apps.bea.gov/itable
- title: ''
  type: RSS
  url: https://apps.bea.gov/rss/rss.xml
created: '2024-11-14'
description: The Bureau of Economic Analysis (BEA) is an agency within the U.S. Department of Commerce that provides economic data to policymakers, businesses, and the general public. The BEA collects and analyzes a wide range of economic indicators, including gross domestic product (GDP), personal income, and trade data. Through its reports and analysis, the BEA helps inform decision-making at all levels of government and helps businesses and individuals understand the state of the economy. The BEA Data API provides programmatic access to all published economic statistics including NIPA, regional data, international accounts, and industry-level data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: The Bureau Of Economic Analysis Context
  property_count: 20
  slug: the-bureau-of-economic-analysis-context
layout: provider
modified: '2026-05-03'
name: The Bureau of Economic Analysis
rules:
- name: The Bureau of Economic Analysis API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: the-bureau-of-economic-analysis-rules
skills: []
slug: the-bureau-of-economic-analysis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-bureau-of-economic-analysis\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/apis.yml\napis:\n  - aid: the-bureau-of-economic-analysis:the-bureau-of-economic-analysis\n    name: The Bureau of Economic Analysis API\n    tags:\n      - Economics\n      - Federal Government\n      - GDP\n      - National Accounts\n      - Statistics\n    humanURL: https://www.bea.gov/resources/for-developers\n    baseURL: https://apps.bea.gov/api/data\n    properties:\n      - url: https://www.bea.gov/resources/for-developers\n        type: Documentation\n      - url: https://apps.bea.gov/api/signup/\n        type: Sign Up\n      - url: https://apps.bea.gov/api/_pdf/bea_web_service_api_user_guide.pdf\n        type: GettingStarted\n      - url: https://apps.bea.gov/API/docs/index.htm\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/openapi/the-bureau-of-economic-analysis-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Bureau of Economic Analysis (BEA) Data API provides programmatic\n      access to BEA published economic statistics. Methods include retrieving\n      statistical data and metadata from datasets covering National Income and\n      Product Accounts (NIPA), GDP by Industry, Regional economic data by state\n      and metro area, International Transactions Accounts (ITA), International\n      Investment Position (IIP), Fixed Assets, Input-Output tables, Multinational\n      Enterprises (MNE), and International Services Trade. Data is available in\n      JSON or XML formats and requires a free API key.\n    contact:\n      - FN: BEA Developer Support\n        url: https://www.bea.gov/resources/for-developers\n        email: BEA.Data.API@bea.gov\n    features:\n      - Dataset Discovery\n      - Parameter Discovery\n      - NIPA Tables\n      - GDP Data\n      - Regional Economic Data\n      - International Transactions\n      - Fixed Assets\n\
  \      - Input-Output Tables\n      - Multinational Enterprise Data\n      - JSON and XML Response Formats\n    useCases:\n      - Economic Research and Analysis\n      - GDP Monitoring and Reporting\n      - Regional Economic Development Planning\n      - Trade Balance Analysis\n      - Business Intelligence and Forecasting\n      - Academic Research\n      - Government Policy Analysis\n    integrations:\n      - url: https://github.com/us-bea/beaapi\n        name: BEA Python Library\n        type: SDK\n      - url: https://github.com/us-bea/bea.R\n        name: BEA R Library\n        type: SDK\nname: The Bureau of Economic Analysis\ntags:\n  - Economics\n  - Federal Government\n  - GDP\n  - National Accounts\n  - Open Data\n  - Statistics\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-14'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The Bureau of Economic Analysis (BEA) is an\
  \ agency within the U.S. Department\n  of Commerce that provides economic data to policymakers, businesses, and the\n  general public. The BEA collects and analyzes a wide range of economic\n  indicators, including gross domestic product (GDP), personal income, and trade\n  data. Through its reports and analysis, the BEA helps inform decision-making at\n  all levels of government and helps businesses and individuals understand the\n  state of the economy. The BEA Data API provides programmatic access to all\n  published economic statistics including NIPA, regional data, international\n  accounts, and industry-level data.\ncommon:\n  - type: Website\n    url: https://www.bea.gov/\n  - type: Documentation\n    url: https://www.bea.gov/resources/for-developers\n  - type: Sign Up\n    url: https://apps.bea.gov/api/signup/\n  - type: GettingStarted\n    url: https://apps.bea.gov/api/_pdf/bea_web_service_api_user_guide.pdf\n  - type: GitHub Organization\n    url: https://github.com/us-bea\n\
  \  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/openapi/the-bureau-of-economic-analysis-openapi.yml\n  - type: InteractiveData\n    url: https://apps.bea.gov/itable\n  - type: RSS\n    url: https://apps.bea.gov/rss/rss.xml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/apis.yml
tags:
- Economics
- Federal Government
- GDP
- National Accounts
- Open Data
- Statistics
url: https://raw.githubusercontent.com/api-evangelist/the-bureau-of-economic-analysis/refs/heads/main/apis.yml
use_cases: []
---
