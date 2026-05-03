---
api_count: 3
api_specs:
- filename: nasdaq-data-link-timeseries-openapi.yml
  format: yaml
  label: Nasdaq Data Link REST API (Time-Series)
  slug: nasdaq-data-link-timeseries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/openapi/nasdaq-data-link-timeseries-openapi.yml
apis:
- description: Nasdaq Data Link REST API (formerly Quandl) provides access to financial and economic time-series datasets including stock prices, economic indicators, interest rates, and commodity data in JSON, XML,
  name: Nasdaq Data Link REST API (Time-Series)
  slug: nasdaq-data-link-timeseries-api
- description: Nasdaq Data Link Tables API provides access to tabular financial datasets including equity fundamentals, options data, and alternative data sets. Limited to 10,000 rows per call with pagination suppor
  name: Nasdaq Data Link Tables REST API
  slug: nasdaq-data-link-tables-api
- description: Nasdaq Cloud Data Service (NCDS) provides streaming and REST APIs for real-time and delayed market data delivery including equities, options, and fixed income from Nasdaq exchange feeds.
  name: Nasdaq Cloud Data Service (NCDS) Streaming API
  slug: nasdaq-cloud-data-service-api
common:
- title: ''
  type: Portal
  url: https://data.nasdaq.com/
- title: ''
  type: Documentation
  url: https://docs.data.nasdaq.com/
- title: ''
  type: GettingStarted
  url: https://docs.data.nasdaq.com/docs/getting-started
- title: ''
  type: RateLimits
  url: https://docs.data.nasdaq.com/docs/rate-limits
- title: ''
  type: Website
  url: https://data.nasdaq.com/
- title: ''
  type: Support
  url: https://docs.data.nasdaq.com/docs/contact-support
- title: ''
  type: GitHubOrganization
  url: https://github.com/Nasdaq
- title: ''
  type: GitHubOrganization
  url: https://github.com/quandl
- title: ''
  type: SDKs
  url: https://github.com/Nasdaq/data-link-python
- title: ''
  type: SDKs
  url: https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Python
- title: ''
  type: SDKs
  url: https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Java
- title: ''
  type: OpenAPI
  url: openapi/nasdaq-data-link-timeseries-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/nasdaq-data-link-dataset-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/nasdaq-data-link-context.jsonld
created: '2026-03-18'
description: Nasdaq Data Link (formerly Quandl) provides REST and streaming APIs for financial and economic data including time-series datasets, tabular datasets, and real-time market data feeds. Datasets cover stock prices, economic indicators, interest rates, commodities, equity fundamentals, options data, and alternative data sets.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Nasdaq Data Link Context
  property_count: 19
  slug: nasdaq-data-link-context
layout: provider
modified: '2026-04-28'
name: Quandl (Nasdaq Data Link)
skills: []
slug: quandl
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: quandl\nname: Quandl (Nasdaq Data Link)\ndescription: >-\n  Nasdaq Data Link (formerly Quandl) provides REST and streaming APIs for\n  financial and economic data including time-series datasets, tabular datasets,\n  and real-time market data feeds. Datasets cover stock prices, economic\n  indicators, interest rates, commodities, equity fundamentals, options data,\n  and alternative data sets.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/apis.yml\ntags:\n  - Finance\n  - Market Data\n  - Economic Data\n  - Time Series\n  - Streaming\ncreated: '2026-03-18'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: quandl:nasdaq-data-link-timeseries-api\n    name: Nasdaq Data Link REST API (Time-Series)\n    description: >-\n      Nasdaq Data Link REST API (formerly Quandl) provides access to financial\n      and economic time-series\
  \ datasets including stock prices, economic\n      indicators, interest rates, and commodity data in JSON, XML, and CSV\n      formats. Authenticated users receive up to 50,000 calls per day.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.data.nasdaq.com/\n    baseURL: https://data.nasdaq.com/api/v3\n    tags:\n      - Finance\n      - Economic Data\n      - Time Series\n      - Market Data\n      - REST\n    properties:\n      - url: https://docs.data.nasdaq.com/\n        type: Documentation\n      - url: https://docs.data.nasdaq.com/\n        type: Reference\n      - url: https://docs.data.nasdaq.com/docs/getting-started\n        type: GettingStarted\n      - url: https://docs.data.nasdaq.com/docs/rate-limits\n        type: RateLimits\n      - url: https://docs.data.nasdaq.com/docs/python-installation\n        type: SDKs\n      - url: openapi/nasdaq-data-link-timeseries-openapi.yml\n        type: OpenAPI\n  - aid: quandl:nasdaq-data-link-tables-api\n\
  \    name: Nasdaq Data Link Tables REST API\n    description: >-\n      Nasdaq Data Link Tables API provides access to tabular financial datasets\n      including equity fundamentals, options data, and alternative data sets.\n      Limited to 10,000 rows per call with pagination support up to 1,000,000\n      rows via the Python client.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.data.nasdaq.com/\n    baseURL: https://data.nasdaq.com/api/v3\n    tags:\n      - Finance\n      - Market Data\n      - Tables\n      - REST\n    properties:\n      - url: https://docs.data.nasdaq.com/\n        type: Documentation\n      - url: https://docs.data.nasdaq.com/docs/rate-limits-1\n        type: RateLimits\n  - aid: quandl:nasdaq-cloud-data-service-api\n    name: Nasdaq Cloud Data Service (NCDS) Streaming API\n    description: >-\n      Nasdaq Cloud Data Service (NCDS) provides streaming and REST APIs for\n      real-time and delayed\
  \ market data delivery including equities, options,\n      and fixed income from Nasdaq exchange feeds.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/Nasdaq/NasdaqCloudDataService-REST-API\n    tags:\n      - Finance\n      - Market Data\n      - Streaming\n      - Real-time\n      - REST\n    properties:\n      - url: https://github.com/Nasdaq/NasdaqCloudDataService-REST-API\n        type: Documentation\n      - url: https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Python\n        type: SDKs\n      - url: https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Java\n        type: SDKs\ncommon:\n  - url: https://data.nasdaq.com/\n    type: Portal\n  - url: https://docs.data.nasdaq.com/\n    type: Documentation\n  - url: https://docs.data.nasdaq.com/docs/getting-started\n    type: GettingStarted\n  - url: https://docs.data.nasdaq.com/docs/rate-limits\n    type: RateLimits\n  - url: https://data.nasdaq.com/\n   \
  \ type: Website\n  - url: https://docs.data.nasdaq.com/docs/contact-support\n    type: Support\n  - url: https://github.com/Nasdaq\n    type: GitHubOrganization\n  - url: https://github.com/quandl\n    type: GitHubOrganization\n  - url: https://github.com/Nasdaq/data-link-python\n    type: SDKs\n  - url: https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Python\n    type: SDKs\n  - url: https://github.com/Nasdaq/NasdaqCloudDataService-SDK-Java\n    type: SDKs\n  - url: openapi/nasdaq-data-link-timeseries-openapi.yml\n    type: OpenAPI\n  - url: json-schema/nasdaq-data-link-dataset-schema.json\n    type: JSONSchema\n  - url: json-ld/nasdaq-data-link-context.jsonld\n    type: JSONLDContext\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/apis.yml
tags:
- Finance
- Market Data
- Economic Data
- Time Series
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/apis.yml
use_cases: []
---
