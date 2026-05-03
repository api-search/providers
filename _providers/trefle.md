---
api_count: 1
api_specs:
- filename: trefle-openapi.yml
  format: yaml
  label: Trefle API
  slug: trefle
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trefle/refs/heads/main/openapi/trefle-openapi.yml
apis:
- description: An open, freely accessible botanical data source and REST API for plant information with taxonomy, species, distributions, and growth data.
  name: Trefle API
  slug: trefle
capabilities:
- description: Workflow capability for Trefle botanical data covering plant search, species detail retrieval, taxonomy navigation, and geographic distribution analysis. Designed for gardening applications, agricultu
  name: Trefle Botanical Data
  slug: botanical-data
common:
- title: ''
  type: Website
  url: https://trefle.io/
- title: ''
  type: Documentation
  url: https://docs.trefle.io/
- title: ''
  type: Sign Up
  url: https://trefle.io/users/sign_in
- title: ''
  type: GitHub
  url: https://github.com/treflehq
- title: ''
  type: NaftikoCapability
  url: capabilities/botanical-data.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/trefle-vocabulary.yml
created: '2025-02-24'
description: An open, freely accessible botanical data source and REST API for plant information covering over 400,000 plant species with taxonomy, morphology, growth requirements, and geographic distributions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 44
  name: Trefle Context
  property_count: 0
  slug: trefle-context
layout: provider
modified: '2026-05-03'
name: Trefle
rules:
- name: Trefle API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: trefle-rules
skills: []
slug: trefle
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trefle\nname: Trefle\ndescription: An open, freely accessible botanical data source and REST API for plant information covering over 400,000 plant species with taxonomy, morphology, growth requirements, and geographic distributions.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agriculture\n  - Botany\n  - Open Data\n  - Plants\n  - Science\ncreated: '2025-02-24'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trefle/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: trefle:trefle\n    name: Trefle API\n    description: An open, freely accessible botanical data source and REST API for plant information with taxonomy, species, distributions, and growth data.\n    humanURL: https://trefle.io/\n    baseURL: https://trefle.io/api/v1\n    tags:\n      - Botany\n      - Open Data\n      - Plants\n      - Science\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.trefle.io/\n      - type: Getting Started\n        url: https://docs.trefle.io/docs/guides/getting-started\n      - type: OpenAPI\n        url: openapi/trefle-openapi.yml\n      - type: JSONSchema\n        url: json-schema/trefle-plant-schema.json\n      - type: JSONSchema\n        url: json-schema/trefle-species-schema.json\n      - type: JSONLD\n        url: json-ld/trefle-context.jsonld\n      - type: JSONStructure\n        url: json-structure/trefle-species-structure.json\n      - type: Example\n        url: examples/trefle-search-plants-example.json\n      - type: Example\n        url: examples/trefle-get-species-example.json\n      - type: SpectralRuleset\n        url: rules/trefle-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/shared/trefle-api.yaml\ncommon:\n  - type: Website\n    url: https://trefle.io/\n  - type: Documentation\n    url: https://docs.trefle.io/\n  - type: Sign Up\n    url: https://trefle.io/users/sign_in\n\
  \  - type: GitHub\n    url: https://github.com/treflehq\n  - type: NaftikoCapability\n    url: capabilities/botanical-data.yaml\n  - type: Vocabulary\n    url: vocabulary/trefle-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trefle/refs/heads/main/apis.yml
tags:
- Agriculture
- Botany
- Open Data
- Plants
- Science
url: https://raw.githubusercontent.com/api-evangelist/trefle/refs/heads/main/apis.yml
use_cases: []
---
