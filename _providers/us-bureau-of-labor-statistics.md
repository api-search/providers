---
api_count: 1
api_specs:
- filename: bls-public-data-api-openapi.yml
  format: yaml
  label: BLS Public Data API
  slug: bls-public-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/openapi/bls-public-data-api-openapi.yml
apis:
- description: The BLS Public Data API allows developers to programmatically retrieve published historical time series data from all BLS surveys. Version 1 is open without registration; Version 2 requires a free API
  name: BLS Public Data API
  slug: bls-public-data-api
capabilities:
- description: Unified capability for accessing Bureau of Labor Statistics time series data, including employment, unemployment, inflation (CPI), wages, and occupational statistics. Designed for economic researchers
  name: BLS Labor Statistics Data Access
  slug: labor-statistics-data
common: []
created: '2025-02-09'
description: The US Bureau of Labor Statistics (BLS) is the principal federal agency responsible for measuring labor market activity, working conditions, price changes, and productivity in the US economy. BLS provides a Public Data API that enables developers to retrieve published historical time series data covering employment, unemployment, inflation, wages, productivity, and occupational statistics across all BLS programs. The API supports both unauthenticated access (v1) and registered access with higher limits (v2), returning data in JSON format for integration into applications, research tools, and economic dashboards.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Us Bureau Of Labor Statistics Context
  property_count: 30
  slug: us-bureau-of-labor-statistics-context
layout: provider
modified: '2026-05-03'
name: US Bureau of Labor Statistics
rules:
- name: US Bureau of Labor Statistics API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 3
    warn: 5
  slug: bls-public-data-api-rules
skills: []
slug: us-bureau-of-labor-statistics
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-bureau-of-labor-statistics\nname: US Bureau of Labor Statistics\ndescription: >-\n  The US Bureau of Labor Statistics (BLS) is the principal federal agency responsible\n  for measuring labor market activity, working conditions, price changes, and productivity\n  in the US economy. BLS provides a Public Data API that enables developers to retrieve\n  published historical time series data covering employment, unemployment, inflation,\n  wages, productivity, and occupational statistics across all BLS programs. The API\n  supports both unauthenticated access (v1) and registered access with higher limits (v2),\n  returning data in JSON format for integration into applications, research tools, and\n  economic dashboards.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Federal Government\n  - Labor Statistics\n  - Economic Data\n  - Open Data\ncreated: '2025-02-09'\nmodified:\
  \ '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: us-bureau-of-labor-statistics:bls-public-data-api\n    name: BLS Public Data API\n    description: >-\n      The BLS Public Data API allows developers to programmatically retrieve\n      published historical time series data from all BLS surveys. Version 1 is\n      open without registration; Version 2 requires a free API key and provides\n      higher query limits (500 daily, up to 50 series per request, 20 years of\n      data). The API covers Consumer Price Index (CPI), employment and\n      unemployment statistics, wages, productivity, industry employment, and\n      occupational statistics. Data is returned in JSON format.\n    humanURL: https://www.bls.gov/developers/home.htm\n    baseURL: https://api.bls.gov/publicAPI/v2\n    tags:\n      - Labor Statistics\n      - Employment\n      - Unemployment\n   \
  \   - Consumer Price Index\n      - Economic Data\n      - Time Series\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://www.bls.gov/developers/home.htm\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/openapi/bls-public-data-api-openapi.yml\n      - type: Registration\n        url: https://data.bls.gov/registrationEngine/\n      - type: TermsOfService\n        url: https://www.bls.gov/developers/termsOfService.htm\n      - type: DataAPI\n        url: https://api.bls.gov/publicAPI/v2/timeseries/data/\n    contact:\n      - FN: BLS Data Support\n        url: https://www.bls.gov/developers/home.htm\n        email: data_staff@bls.gov\nfeatures:\n  - name: Time Series Data Retrieval\n    description: Retrieve historical time series data for one or multiple BLS series IDs\n  - name: Multi-Series Requests\n    description: Query up to 50 series per request with\
  \ API v2 registration\n  - name: Date Range Filtering\n    description: Filter data by start and end year to retrieve specific date ranges\n  - name: Statistical Calculations\n    description: Request net changes and percent changes alongside raw values (v2)\n  - name: Series Catalog\n    description: Retrieve metadata and descriptions for series (v2)\n  - name: Annual Averages\n    description: Include annual average values in time series responses (v2)\n  - name: Survey Discovery\n    description: List all BLS surveys and their metadata\n  - name: Popular Series\n    description: Retrieve the 25 most popular BLS series IDs\nuseCases:\n  - name: Economic Research Dashboard\n    description: Build dashboards displaying unemployment rate trends, CPI inflation data, and wage growth\n  - name: Labor Market Analysis\n    description: Analyze employment patterns across industries, occupations, and demographics\n  - name: Inflation Monitoring\n    description: Track Consumer Price Index changes\
  \ for economic forecasting and policy analysis\n  - name: Occupational Wage Studies\n    description: Retrieve occupational employment and wage data for compensation benchmarking\n  - name: FOIA Data Applications\n    description: Access publicly available BLS survey data for transparency and accountability reporting\nsolutions:\n  - name: Economic Intelligence Platforms\n    description: Integrate BLS data into economic intelligence and forecasting platforms\n  - name: HR Analytics Tools\n    description: Power HR compensation analysis tools with BLS wage and employment data\n  - name: Government Data Portals\n    description: Enrich government open data portals with BLS statistical datasets\nintegrations:\n  - name: data.gov\n    description: BLS datasets are cataloged and accessible through data.gov\n    url: https://catalog.data.gov/organization/bls-gov\n  - name: api.data.gov\n    description: BLS API is accessible via the api.data.gov gateway\n    url: https://api.data.gov\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/apis.yml
tags:
- Federal Government
- Labor Statistics
- Economic Data
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/apis.yml
use_cases: []
---
