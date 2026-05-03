---
api_count: 1
api_specs:
- filename: bls-public-data-api-openapi.yaml
  format: yaml
  label: BLS Public Data API
  slug: bls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/openapi/bls-public-data-api-openapi.yaml
apis:
- description: The BLS Public Data API provides programmatic access to published historical time series data covering employment, unemployment, consumer prices, wages, productivity, and other labor market indicators
  name: BLS Public Data API
  slug: bls-api
capabilities:
- description: Workflow capability for economists, researchers, policy analysts, and data engineers to access U.S. Bureau of Labor Statistics time series data covering employment, unemployment, inflation, wages, and
  name: BLS Labor Market Intelligence
  slug: labor-market-intelligence
common:
- title: ''
  type: Website
  url: https://www.bls.gov/
- title: ''
  type: Documentation
  url: https://www.bls.gov/developers/
- title: ''
  type: GettingStarted
  url: https://www.bls.gov/developers/home.htm
- title: ''
  type: PrivacyPolicy
  url: https://www.bls.gov/bls/bls-privacy.htm
- title: ''
  type: FAQ
  url: https://www.bls.gov/developers/api_faqs.htm
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/rules/bls-public-data-api-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/vocabulary/u-s-bureau-of-labor-statistics-vocabulary.yaml
- title: Labor Market Intelligence
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/capabilities/labor-market-intelligence.yaml
created: '2024-12-25'
description: The U.S. Bureau of Labor Statistics (BLS) is the principal federal statistical agency responsible for measuring labor market activity, working conditions, and price changes in the U.S. economy. BLS collects, processes, analyzes, and disseminates statistical data on employment, unemployment, inflation, wages, productivity, and occupational safety through a public API that provides programmatic access to published historical time series data.
features:
- description: Retrieve historical labor statistics data using BLS series IDs covering employment, unemployment, CPI, wages, and productivity.
  name: Time Series Data Access
- description: Version 2 API allows requesting up to 50 series in a single POST request, returning 20 years of data per series.
  name: Multiple Series in One Request
- description: Optional calculations including net change and percent change from prior periods are available in Version 2 responses.
  name: Net and Percent Change Calculations
- description: Retrieve metadata for all available BLS surveys and discover popular series IDs through the catalog endpoint.
  name: Survey Catalog Discovery
- description: Request annual average values (M13 period) alongside monthly data for trend analysis.
  name: Annual Averages
- description: The BLS API is free to use. Version 1 requires no registration; Version 2 requires a free API key for higher query limits.
  name: Public API with Free Registration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Open-source Python package for querying the BLS API with support for v1 and v2 endpoints.
  name: Python blsapi
- description: CRAN R package providing a simple interface to the BLS Public Data API for statistical computing.
  name: R blsAPI
- description: BLS connector available in Power Automate, Power Apps, and Copilot Studio for low-code BLS data access.
  name: Microsoft Power Platform
- description: BLS datasets are cataloged on data.gov as part of the federal open data initiative.
  name: data.gov
jsonld:
- class_count: 13
  name: Bls Public Data Api Context
  property_count: 36
  slug: bls-public-data-api-context
layout: provider
modified: '2026-05-03'
name: U.S. Bureau of Labor Statistics
rules:
- name: U.S. Bureau of Labor Statistics API Rules
  rule_count: 33
  severity_counts:
    error: 9
    hint: 0
    info: 7
    warn: 17
  slug: bls-public-data-api-rules
skills: []
slug: u-s-bureau-of-labor-statistics
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: u-s-bureau-of-labor-statistics\nname: U.S. Bureau of Labor Statistics\ndescription: >-\n  The U.S. Bureau of Labor Statistics (BLS) is the principal federal statistical\n  agency responsible for measuring labor market activity, working conditions, and\n  price changes in the U.S. economy. BLS collects, processes, analyzes, and\n  disseminates statistical data on employment, unemployment, inflation, wages,\n  productivity, and occupational safety through a public API that provides\n  programmatic access to published historical time series data.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/apis.yml\ntype: Index\ncreated: '2024-12-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Federal Government\n  - Labor\n  - Statistics\n  - Employment\n  - Economic Data\napis:\n  - aid: u-s-bureau-of-labor-statistics:bls-api\n\
  \    name: BLS Public Data API\n    description: >-\n      The BLS Public Data API provides programmatic access to published\n      historical time series data covering employment, unemployment, consumer\n      prices, wages, productivity, and other labor market indicators. Version 2\n      (registration required) supports up to 50 series per request, 20 years\n      of data, and optional calculations including net and percent changes.\n    humanURL: https://www.bls.gov/developers/\n    baseURL: https://api.bls.gov/publicAPI/v2\n    tags:\n      - Labor Statistics\n      - Employment\n      - Unemployment\n      - Consumer Prices\n      - Wages\n    properties:\n      - type: Documentation\n        url: https://www.bls.gov/developers/api_signature_v2.htm\n      - type: GettingStarted\n        url: https://www.bls.gov/developers/\n      - type: Authentication\n        url: https://data.bls.gov/registrationEngine/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/openapi/bls-public-data-api-openapi.yaml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/json-schema/bls-series-data-schema.json\n        title: Series Data Schema\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/json-schema/bls-data-point-schema.json\n        title: Data Point Schema\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/json-schema/bls-survey-schema.json\n        title: Survey Schema\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/json-structure/bls-series-data-structure.json\n        title: Series Data Structure\n      - type: JSON-LD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/json-ld/bls-public-data-api-context.jsonld\n\
  \      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/examples/bls-series-data-example.json\n        title: Series Data Example\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/examples/bls-data-point-example.json\n        title: Data Point Example\ncommon:\n  - type: Website\n    url: https://www.bls.gov/\n  - type: Documentation\n    url: https://www.bls.gov/developers/\n  - type: GettingStarted\n    url: https://www.bls.gov/developers/home.htm\n  - type: PrivacyPolicy\n    url: https://www.bls.gov/bls/bls-privacy.htm\n  - type: FAQ\n    url: https://www.bls.gov/developers/api_faqs.htm\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/rules/bls-public-data-api-rules.yml\n  - type: Vocabulary\n    url: >-\n\
  \      https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/vocabulary/u-s-bureau-of-labor-statistics-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/capabilities/labor-market-intelligence.yaml\n    title: Labor Market Intelligence\n  - type: Features\n    data:\n      - name: Time Series Data Access\n        description: >-\n          Retrieve historical labor statistics data using BLS series IDs\n          covering employment, unemployment, CPI, wages, and productivity.\n      - name: Multiple Series in One Request\n        description: >-\n          Version 2 API allows requesting up to 50 series in a single POST\n          request, returning 20 years of data per series.\n      - name: Net and Percent Change Calculations\n        description: >-\n          Optional calculations including net change and percent change from\n     \
  \     prior periods are available in Version 2 responses.\n      - name: Survey Catalog Discovery\n        description: >-\n          Retrieve metadata for all available BLS surveys and discover popular\n          series IDs through the catalog endpoint.\n      - name: Annual Averages\n        description: >-\n          Request annual average values (M13 period) alongside monthly data\n          for trend analysis.\n      - name: Public API with Free Registration\n        description: >-\n          The BLS API is free to use. Version 1 requires no registration;\n          Version 2 requires a free API key for higher query limits.\n  - type: UseCases\n    data:\n      - name: Economic Research\n        description: >-\n          Economists and researchers use BLS time series data to analyze\n          labor market trends, wage growth, and employment cycles.\n      - name: Inflation Monitoring\n        description: >-\n          Track CPI and PPI data for measuring inflation trends across\n\
  \          consumer goods, food, energy, and other categories.\n      - name: Employment Policy Analysis\n        description: >-\n          Policy analysts use unemployment and employment statistics to\n          evaluate labor market conditions and inform policy decisions.\n      - name: Dashboard and Application Development\n        description: >-\n          Developers integrate BLS data into economic dashboards,\n          journalism applications, and data visualization tools.\n      - name: Academic Research\n        description: >-\n          Universities and think tanks use BLS historical data for\n          econometric modeling, academic papers, and policy reports.\n  - type: Integrations\n    data:\n      - name: Python blsapi\n        description: >-\n          Open-source Python package for querying the BLS API with\n          support for v1 and v2 endpoints.\n      - name: R blsAPI\n        description: >-\n          CRAN R package providing a simple interface to the BLS Public\n\
  \          Data API for statistical computing.\n      - name: Microsoft Power Platform\n        description: >-\n          BLS connector available in Power Automate, Power Apps, and\n          Copilot Studio for low-code BLS data access.\n      - name: data.gov\n        description: >-\n          BLS datasets are cataloged on data.gov as part of the federal\n          open data initiative.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/apis.yml
tags:
- Federal Government
- Labor
- Statistics
- Employment
- Economic Data
url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/apis.yml
use_cases:
- description: Economists and researchers use BLS time series data to analyze labor market trends, wage growth, and employment cycles.
  name: Economic Research
- description: Track CPI and PPI data for measuring inflation trends across consumer goods, food, energy, and other categories.
  name: Inflation Monitoring
- description: Policy analysts use unemployment and employment statistics to evaluate labor market conditions and inform policy decisions.
  name: Employment Policy Analysis
- description: Developers integrate BLS data into economic dashboards, journalism applications, and data visualization tools.
  name: Dashboard and Application Development
- description: Universities and think tanks use BLS historical data for econometric modeling, academic papers, and policy reports.
  name: Academic Research
---
