---
api_count: 1
api_specs:
- filename: energy-information-administration-open-data-api-openapi.yml
  format: yaml
  label: EIA Open Data API
  slug: open-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/energy-information-administration/refs/heads/main/openapi/energy-information-administration-open-data-api-openapi.yml
apis:
- description: The EIA Open Data API v2 provides programmatic access to free U.S. energy time-series data through a hierarchical route structure organized by energy category. An API key is required (free registratio
  name: EIA Open Data API
  slug: open-data-api
common:
- title: ''
  type: Website
  url: https://www.eia.gov
- title: ''
  type: Documentation
  url: https://www.eia.gov/opendata/
- title: ''
  type: API Browser
  url: https://www.eia.gov/opendata/browser/
- title: ''
  type: Signup
  url: https://www.eia.gov/opendata/register.php
- title: ''
  type: Bulk Downloads
  url: https://www.eia.gov/opendata/bulkfiles.php
- title: ''
  type: Excel Add-in
  url: https://www.eia.gov/opendata/excel/
created: '2024-12-03'
description: The U.S. Energy Information Administration (EIA) is committed to its free and open data by making it available through an Application Programming Interface (API) and its open data tools. The EIA Open Data API v2 is multi-faceted and contains time-series datasets organized by the main energy categories, including electricity, natural gas, petroleum, coal, nuclear, renewables, total energy, international energy statistics, the State Energy Data System (SEDS), and CO2 emissions aggregates.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Energy Information Administration
skills: []
slug: energy-information-administration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: energy-information-administration\nname: Energy Information Administration\nurl:\n  https://raw.githubusercontent.com/api-evangelist/energy-information-administration/refs/heads/main/apis.yml\ntags:\n  - Energy\n  - Federal Government\n  - Open Data\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  The U.S. Energy Information Administration (EIA) is committed to its free and\n  open data by making it available through an Application Programming Interface\n  (API) and its open data tools. The EIA Open Data API v2 is multi-faceted and\n  contains time-series datasets organized by the main energy categories,\n  including electricity, natural gas, petroleum, coal, nuclear, renewables,\n  total energy, international energy statistics, the State Energy Data System\n  (SEDS), and CO2 emissions aggregates.\napis:\n  - aid: energy-information-administration:open-data-api\n\
  \    name: EIA Open Data API\n    tags:\n      - Energy\n      - Federal Government\n      - Open Data\n      - Time Series\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.eia.gov/v2\n    humanURL: https://www.eia.gov/opendata/\n    properties:\n      - url: https://www.eia.gov/opendata/\n        type: Documentation\n      - url: https://www.eia.gov/opendata/browser/\n        type: API Browser\n      - url: https://www.eia.gov/opendata/register.php\n        type: Signup\n      - url: openapi/energy-information-administration-open-data-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The EIA Open Data API v2 provides programmatic access to free U.S. energy\n      time-series data through a hierarchical route structure organized by\n      energy category. An API key is required (free registration) and is passed\n      as a URL query parameter on every request. Responses include rich\n      metadata for navigating\
  \ child routes, facets, frequencies, and available\n      data columns. The API supports JSON (default) and XML output, with up to\n      5,000 rows per request for JSON and 300 rows for XML.\ncommon:\n  - type: Website\n    url: https://www.eia.gov\n  - type: Documentation\n    url: https://www.eia.gov/opendata/\n  - type: API Browser\n    url: https://www.eia.gov/opendata/browser/\n  - type: Signup\n    url: https://www.eia.gov/opendata/register.php\n  - type: Bulk Downloads\n    url: https://www.eia.gov/opendata/bulkfiles.php\n  - type: Excel Add-in\n    url: https://www.eia.gov/opendata/excel/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.20'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/energy-information-administration/refs/heads/main/apis.yml
tags:
- Energy
- Federal Government
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/energy-information-administration/refs/heads/main/apis.yml
use_cases: []
---
