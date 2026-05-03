---
api_count: 1
api_specs:
- filename: rentcast-openapi.json
  format: json
  label: RentCast API
  slug: rentcast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rentcast/refs/heads/main/openapi/rentcast-openapi.json
apis:
- description: 'The RentCast API provides programmatic access to US real estate data including 140+ million property records with ownership details, automated valuation model (AVM) rent and home value estimates with '
  name: RentCast API
  slug: rentcast-api
capabilities:
- description: 'Unified workflow for real estate property research, market analysis, and investment evaluation using the RentCast API. Combines property record lookup, rent and home value estimation, listing search, '
  name: RentCast Property Research
  slug: property-research
common:
- title: ''
  type: Website
  url: https://www.rentcast.io
- title: ''
  type: Portal
  url: https://developers.rentcast.io
- title: ''
  type: Portal
  url: https://app.rentcast.io/app/api
- title: ''
  type: Documentation
  url: https://www.rentcast.io/api
- title: ''
  type: Support
  url: https://help.rentcast.io
- title: ''
  type: Blog
  url: https://www.rentcast.io/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/RentCast
created: '2025-03-01'
description: RentCast provides a real estate data API with instant access to over 140 million property records, automated valuation models (AVM) for home value and rent estimates, active and historical sale and rental listings, and aggregate real estate market statistics for US zip codes. The API enables real estate investors, property managers, landlords, and proptech applications to programmatically access comprehensive residential and commercial property data across all 50 US states.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Rentcast Context
  property_count: 9
  slug: rentcast-context
layout: provider
modified: '2026-05-02'
name: RentCast
rules:
- name: RentCast API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 3
  slug: rentcast-rules
skills: []
slug: rentcast
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rentcast\nname: RentCast\ndescription: >-\n  RentCast provides a real estate data API with instant access to over 140\n  million property records, automated valuation models (AVM) for home value\n  and rent estimates, active and historical sale and rental listings, and\n  aggregate real estate market statistics for US zip codes. The API enables\n  real estate investors, property managers, landlords, and proptech applications\n  to programmatically access comprehensive residential and commercial property\n  data across all 50 US states.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Real Estate\n  - Property Data\n  - Valuation\n  - Rental Market\n  - AVM\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rentcast/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rentcast:rentcast-api\n    name: RentCast API\n    description: >-\n  \
  \    The RentCast API provides programmatic access to US real estate data\n      including 140+ million property records with ownership details, automated\n      valuation model (AVM) rent and home value estimates with comparable\n      properties, active and inactive sale and rental listings across all 50\n      states, and aggregate market statistics for zip codes. Authentication\n      uses an X-Api-Key header. All endpoints are read-only GET requests.\n    humanURL: https://www.rentcast.io/api\n    baseURL: https://api.rentcast.io/v1\n    tags:\n      - Real Estate\n      - Property Data\n      - Valuation\n      - Rental Market\n    properties:\n      - type: Documentation\n        url: https://developers.rentcast.io/reference/introduction\n      - type: OpenAPI\n        url: openapi/rentcast-openapi.json\n      - type: PostmanCollection\n        url: https://www.postman.com/rentcast/rentcast-api/documentation/ca4yudw/rentcast-api-endpoints\n      - type: GitHubOrganization\n    \
  \    url: https://github.com/RentCast\n      - type: Rules\n        url: rules/rentcast-rules.yml\n      - type: Capabilities\n        url: capabilities/property-research.yaml\n      - type: JSONSchema\n        url: json-schema/rentcast-property-schema.json\n      - type: JSONStructure\n        url: json-structure/rentcast-property-structure.json\n      - type: JSONLD\n        url: json-ld/rentcast-context.jsonld\n      - type: Vocabulary\n        url: vocabulary/rentcast-vocabulary.yml\ncommon:\n  - url: https://www.rentcast.io\n    name: RentCast\n    type: Website\n    description: RentCast real estate data platform homepage\n  - url: https://developers.rentcast.io\n    name: RentCast Developer Portal\n    type: Portal\n    description: API documentation and developer resources\n  - url: https://app.rentcast.io/app/api\n    name: RentCast API Dashboard\n    type: Portal\n    description: API key management and usage dashboard\n  - url: https://www.rentcast.io/api\n    name: RentCast\
  \ API\n    type: Documentation\n    description: Overview of RentCast API features and pricing\n  - url: https://help.rentcast.io\n    name: RentCast Help Center\n    type: Support\n    description: Help articles and support documentation\n  - url: https://www.rentcast.io/blog\n    name: RentCast Blog\n    type: Blog\n    description: Product updates and real estate data insights\n  - url: https://github.com/RentCast\n    name: RentCast GitHub\n    type: GitHubOrganization\n    description: OpenAPI specs, Postman collections, and developer resources\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rentcast/refs/heads/main/apis.yml
tags:
- Real Estate
- Property Data
- Valuation
- Rental Market
- AVM
url: https://raw.githubusercontent.com/api-evangelist/rentcast/refs/heads/main/apis.yml
use_cases: []
---
