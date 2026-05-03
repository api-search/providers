---
api_count: 1
api_specs:
- filename: ssc-geneva-fund-accounting-openapi.yml
  format: yaml
  label: SS&C Geneva Fund Accounting API
  slug: ssc-geneva-fund-accounting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/openapi/ssc-geneva-fund-accounting-openapi.yml
apis:
- description: SS&C Geneva provides fund accounting and portfolio management APIs for asset managers, hedge funds, and fund administrators. APIs enable NAV calculation, trade processing, investor accounting, positio
  name: SS&C Geneva Fund Accounting API
  slug: ssc-geneva-fund-accounting
capabilities:
- description: 'Unified workflow capability for fund accounting and portfolio management operations using SS&C Geneva. Enables portfolio managers, fund accountants, and operations teams to manage portfolios, process '
  name: SS&C Geneva Fund Operations
  slug: fund-operations
common:
- title: ''
  type: Website
  url: https://www.ssctech.com/
- title: ''
  type: Portal
  url: https://www.ssctech.com/products
- title: ''
  type: Blog
  url: https://www.ssctech.com/blog
- title: ''
  type: Support
  url: https://www.ssctech.com/about/support-client-portals
- title: ''
  type: PrivacyPolicy
  url: https://www.ssctech.com/about/privacy
- title: ''
  type: Documentation
  url: https://www.ssctech.com/resources
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/openapi/ssc-geneva-fund-accounting-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-schema/ssc-geneva-portfolio-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-structure/ssc-geneva-fund-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-ld/ssc-geneva-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/rules/ssc-geneva-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/capabilities/fund-operations.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/vocabulary/ssc-geneva-vocabulary.yml
created: '2026-03-18'
description: SS&C Geneva is an enterprise-grade fund accounting and portfolio management platform for asset managers, hedge funds, and fund administrators. Geneva provides APIs for NAV calculation, trade processing, investor accounting, position management, and regulatory reporting across multi-asset portfolios including equities, fixed income, derivatives, and alternative investments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: Ssc Geneva Context
  property_count: 12
  slug: ssc-geneva-context
layout: provider
modified: '2026-05-02'
name: SS&C Geneva
rules:
- name: SS&C Geneva API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 1
    info: 0
    warn: 5
  slug: ssc-geneva-rules
skills: []
slug: ssc-geneva
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ssc-geneva\nname: SS&C Geneva\ndescription: >-\n  SS&C Geneva is an enterprise-grade fund accounting and portfolio management\n  platform for asset managers, hedge funds, and fund administrators. Geneva\n  provides APIs for NAV calculation, trade processing, investor accounting,\n  position management, and regulatory reporting across multi-asset portfolios\n  including equities, fixed income, derivatives, and alternative investments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Fund Accounting\n  - Asset Management\n  - Portfolio Management\n  - Financial Services\n  - Hedge Funds\n  - NAV Calculation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: ssc-geneva:ssc-geneva-fund-accounting\n    name: SS&C Geneva Fund Accounting API\n    description: >-\n      SS&C Geneva\
  \ provides fund accounting and portfolio management APIs for\n      asset managers, hedge funds, and fund administrators. APIs enable NAV\n      calculation, trade processing, investor accounting, position management,\n      and regulatory reporting across multi-asset portfolios. Geneva is an\n      enterprise system with REST APIs for integration with external systems\n      including OMS, custodians, and reporting platforms.\n    humanURL: https://www.ssctech.com/\n    baseURL: https://api.ssctech.example.com/geneva/v1\n    tags:\n      - Fund Accounting\n      - Portfolio Management\n      - Asset Management\n      - Financial Services\n      - NAV Calculation\n      - Trade Processing\n    properties:\n      - type: Documentation\n        url: https://www.ssctech.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/openapi/ssc-geneva-fund-accounting-openapi.yml\n      - type: JSONSchema\n        url: >-\n\
  \          https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-schema/ssc-geneva-portfolio-schema.json\n    contact:\n      - FN: SS&C Technologies Support\n        url: https://www.ssctech.com/about/support-client-portals\ncommon:\n  - type: Website\n    url: https://www.ssctech.com/\n  - type: Portal\n    url: https://www.ssctech.com/products\n  - type: Blog\n    url: https://www.ssctech.com/blog\n  - type: Support\n    url: https://www.ssctech.com/about/support-client-portals\n  - type: PrivacyPolicy\n    url: https://www.ssctech.com/about/privacy\n  - type: Documentation\n    url: https://www.ssctech.com/resources\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/openapi/ssc-geneva-fund-accounting-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-schema/ssc-geneva-portfolio-schema.json\n  - type: JSONStructure\n\
  \    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-structure/ssc-geneva-fund-structure.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/json-ld/ssc-geneva-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/rules/ssc-geneva-rules.yml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/capabilities/fund-operations.yaml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/vocabulary/ssc-geneva-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/apis.yml
tags:
- Fund Accounting
- Asset Management
- Portfolio Management
- Financial Services
- Hedge Funds
- NAV Calculation
url: https://raw.githubusercontent.com/api-evangelist/ssc-geneva/refs/heads/main/apis.yml
use_cases: []
---
