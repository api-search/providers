---
api_count: 1
api_specs:
- filename: wine-searcher-openapi.yml
  format: yaml
  label: Wine-Searcher API
  slug: wine-searcher-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/openapi/wine-searcher-openapi.yml
apis:
- description: The Wine-Searcher API provides wine pricing data, aggregated critic scores, grape variety, region, and merchant listings for any wine in the Wine-Searcher database. The API uses HTTP GET requests with
  name: Wine-Searcher API
  slug: wine-searcher-api
capabilities:
- description: Wine data capability for Wine-Searcher, enabling end-to-end wine price discovery, merchant comparisons, critic score lookups, and cellar valuation. Designed for wine apps, investment platforms, insura
  name: Wine-Searcher Wine Data
  slug: wine-data
common:
- title: ''
  type: Website
  url: https://www.wine-searcher.com
- title: ''
  type: Documentation
  url: https://www.wine-searcher.com/trade/ws-api
- title: ''
  type: DeveloperPortal
  url: https://www.wine-searcher.com/trade/developer
- title: ''
  type: Pricing
  url: https://www.wine-searcher.com/trade/api
- title: ''
  type: FAQ
  url: https://www.wine-searcher.com/trade/faq
- title: ''
  type: DataFeed
  url: https://www.wine-searcher.com/trade/datafeed
- title: ''
  type: Linking
  url: https://www.wine-searcher.com/trade/ws-link
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/json-ld/wine-searcher-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/vocabulary/wine-searcher-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/capabilities/wine-data.yaml
created: '2025-02-24'
description: Wine-Searcher is the world's leading wine search engine and marketplace, providing access to prices, availability, and data on over 15 million wines from retailers worldwide. The Wine-Searcher API allows developers to integrate wine pricing data, merchant listings, critic scores, vintage availability, and wine details directly into websites and applications. Typical API consumers include wine apps, websites, blogs, market research companies, wine investment platforms, and insurance services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Wine Searcher Context
  property_count: 16
  slug: wine-searcher-context
layout: provider
modified: '2026-05-03'
name: Wine-Searcher
rules:
- name: Wine-Searcher API Rules
  rule_count: 9
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 2
  slug: wine-searcher-rules
skills: []
slug: wine-searcher
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wine-searcher\nname: Wine-Searcher\ndescription: >-\n  Wine-Searcher is the world's leading wine search engine and marketplace, providing\n  access to prices, availability, and data on over 15 million wines from retailers\n  worldwide. The Wine-Searcher API allows developers to integrate wine pricing data,\n  merchant listings, critic scores, vintage availability, and wine details directly\n  into websites and applications. Typical API consumers include wine apps, websites,\n  blogs, market research companies, wine investment platforms, and insurance services.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data\n  - Marketplace\n  - Wine\n  - Prices\n  - Merchants\n  - Vintages\n  - Critics\ncreated: '2025-02-24'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ wine-searcher:wine-searcher-api\n    name: Wine-Searcher API\n    description: >-\n      The Wine-Searcher API provides wine pricing data, aggregated critic scores,\n      grape variety, region, and merchant listings for any wine in the Wine-Searcher\n      database. The API uses HTTP GET requests with query parameters. Responses are\n      available in JSON or XML format. Includes a Wine Check endpoint for aggregated\n      wine data and a Market Price endpoint for individual merchant listings.\n    humanURL: https://www.wine-searcher.com/trade/ws-api\n    baseURL: https://www.wine-searcher.com/ws_api.php\n    tags:\n      - Wine\n      - Prices\n      - Data\n      - Marketplace\n    properties:\n      - type: Documentation\n        url: https://www.wine-searcher.com/trade/ws-api\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/openapi/wine-searcher-openapi.yml\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/rules/wine-searcher-rules.yml\n\
  common:\n  - type: Website\n    url: https://www.wine-searcher.com\n  - type: Documentation\n    url: https://www.wine-searcher.com/trade/ws-api\n  - type: DeveloperPortal\n    url: https://www.wine-searcher.com/trade/developer\n  - type: Pricing\n    url: https://www.wine-searcher.com/trade/api\n  - type: FAQ\n    url: https://www.wine-searcher.com/trade/faq\n  - type: DataFeed\n    url: https://www.wine-searcher.com/trade/datafeed\n  - type: Linking\n    url: https://www.wine-searcher.com/trade/ws-link\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/json-ld/wine-searcher-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/vocabulary/wine-searcher-vocabulary.yml\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/capabilities/wine-data.yaml\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/apis.yml
tags:
- Data
- Marketplace
- Wine
- Prices
- Merchants
- Vintages
- Critics
url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/apis.yml
use_cases: []
---
