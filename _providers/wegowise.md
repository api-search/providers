---
api_count: 4
api_specs:
- filename: wegowise-openapi.yml
  format: yaml
  label: WegoWise API
  slug: wegowise
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/openapi/wegowise-openapi.yml
apis:
- description: The WegoWise REST API (now Comply API) for managing building portfolios, utility meters, and energy data. Supports buildings, apartments, commercial areas, developments, meters, and raw usage datapoin
  name: WegoWise API
  slug: wegowise
- description: The WegoPro API for multifamily and commercial property portfolios. Provides endpoints for buildings, apartments, areas, meters, raw data, and monthly normalized usage data. The primary API for proper
  name: WegoWise Pro API
  slug: wegowise-pro
- description: 'The WegoData API for data-only accounts. Enables meter management and automated utility data import without the full building structure hierarchy. Supports all utility types: Electric, Gas, Oil, Water'
  name: WegoWise Data API
  slug: wegowise-data
- description: Public endpoints accessible without authentication. Provides a list of utility companies supported for automated data import, useful for finding utility_company_id values when configuring meters.
  name: WegoWise Public API
  slug: wegowise-public
capabilities:
- description: Capability for building energy and water benchmarking using the WegoWise API. Enables property managers and energy service providers to assess portfolio performance, identify underperforming buildings
  name: WegoWise Building Energy Benchmarking
  slug: building-energy-benchmarking
common:
- title: ''
  type: Documentation
  url: https://www.wegowise.com/api
- title: ''
  type: Website
  url: https://www.wegowise.com
- title: ''
  type: Product Tour
  url: https://www.wegowise.com/tour
- title: ''
  type: Energy Service Providers
  url: https://www.wegowise.com/customer-profiles/energy-service-providers
- title: ''
  type: Compliance
  url: https://www.wegowise.com/compliance
- title: ''
  type: Blog
  url: http://blog.wegowise.com/
- title: ''
  type: SpectralRules
  url: rules/wegowise-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/wegowise-vocabulary.yml
- title: ''
  type: JSONLD
  url: json-ld/wegowise-context.jsonld
created: '2025-05-02'
description: WegoWise (now Comply by Measurabl) is a building energy and water benchmarking platform enabling property owners, managers, and energy service providers to programmatically manage building portfolios, track utility meter data, and benchmark energy and water performance. The REST API supports building management, apartment and commercial area tracking, utility meter data import, and normalized monthly usage analytics across multifamily and commercial properties.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Wegowise Context
  property_count: 24
  slug: wegowise-context
layout: provider
modified: '2026-05-03'
name: WegoWise
rules:
- name: WegoWise API Rules
  rule_count: 12
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 10
  slug: wegowise-rules
skills: []
slug: wegowise
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wegowise\nname: WegoWise\ndescription: >-\n  WegoWise (now Comply by Measurabl) is a building energy and water benchmarking\n  platform enabling property owners, managers, and energy service providers to\n  programmatically manage building portfolios, track utility meter data, and benchmark\n  energy and water performance. The REST API supports building management, apartment\n  and commercial area tracking, utility meter data import, and normalized monthly\n  usage analytics across multifamily and commercial properties.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Benchmarking\n  - Building Energy\n  - Energy Efficiency\n  - Multifamily\n  - Property Management\n  - Utility Data\ncreated: '2025-05-02'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: wegowise:wegowise\n\
  \    name: WegoWise API\n    description: >-\n      The WegoWise REST API (now Comply API) for managing building portfolios,\n      utility meters, and energy data. Supports buildings, apartments, commercial areas,\n      developments, meters, and raw usage datapoints. Authenticated via OAuth 1.0.\n    humanURL: https://www.wegowise.com/api\n    baseUrl: https://www.wegowise.com\n    tags:\n      - Apartments\n      - Benchmarking\n      - Buildings\n      - Developments\n      - Energy Data\n      - Meters\n      - REST\n      - Utility Companies\n      - Water Data\n    properties:\n      - type: Documentation\n        url: https://www.wegowise.com/api\n      - type: OpenAPI\n        url: openapi/wegowise-openapi.yml\n      - type: JSONSchema\n        url: json-schema/wegowise-building-schema.json\n      - type: JSONSchema\n        url: json-schema/wegowise-meter-schema.json\n      - type: JSONStructure\n        url: json-structure/wegowise-building-structure.json\n      - type: JSONLD\n\
  \        url: json-ld/wegowise-context.jsonld\n\n  - aid: wegowise:wegowise-pro\n    name: WegoWise Pro API\n    description: >-\n      The WegoPro API for multifamily and commercial property portfolios. Provides\n      endpoints for buildings, apartments, areas, meters, raw data, and monthly\n      normalized usage data. The primary API for property managers.\n    humanURL: https://www.wegowise.com/api/wego_pro\n    baseUrl: https://www.wegowise.com/api/v1/wego_pro\n    tags:\n      - Apartments\n      - Buildings\n      - Commercial Areas\n      - Multifamily\n      - Pro\n    properties:\n      - type: Documentation\n        url: https://www.wegowise.com/api/wego_pro\n\n  - aid: wegowise:wegowise-data\n    name: WegoWise Data API\n    description: >-\n      The WegoData API for data-only accounts. Enables meter management and automated\n      utility data import without the full building structure hierarchy. Supports\n      all utility types: Electric, Gas, Oil, Water, Steam, Propane,\
  \ Solar.\n    humanURL: https://www.wegowise.com/api/wego_data\n    baseUrl: https://www.wegowise.com/api/v1/wego_data\n    tags:\n      - Automated Import\n      - Data Only\n      - Meters\n      - Utility Data\n    properties:\n      - type: Documentation\n        url: https://www.wegowise.com/api/wego_data\n\n  - aid: wegowise:wegowise-public\n    name: WegoWise Public API\n    description: >-\n      Public endpoints accessible without authentication. Provides a list of utility\n      companies supported for automated data import, useful for finding utility_company_id\n      values when configuring meters.\n    humanURL: https://www.wegowise.com/api/public\n    baseUrl: https://www.wegowise.com/api/v1\n    tags:\n      - Public\n      - Utility Companies\n    properties:\n      - type: Documentation\n        url: https://www.wegowise.com/api/public\n\ncommon:\n  - type: Documentation\n    url: https://www.wegowise.com/api\n  - type: Website\n    url: https://www.wegowise.com\n  - type:\
  \ Product Tour\n    url: https://www.wegowise.com/tour\n  - type: Energy Service Providers\n    url: https://www.wegowise.com/customer-profiles/energy-service-providers\n  - type: Compliance\n    url: https://www.wegowise.com/compliance\n  - type: Blog\n    url: http://blog.wegowise.com/\n  - type: SpectralRules\n    url: rules/wegowise-rules.yml\n  - type: Vocabulary\n    url: vocabulary/wegowise-vocabulary.yml\n  - type: JSONLD\n    url: json-ld/wegowise-context.jsonld\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/apis.yml
tags:
- Benchmarking
- Building Energy
- Energy Efficiency
- Multifamily
- Property Management
- Utility Data
url: https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/apis.yml
use_cases: []
---
