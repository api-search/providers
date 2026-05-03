---
api_count: 1
api_specs:
- filename: zestful-openapi.yml
  format: yaml
  label: Zestful Ingredient Parser API
  slug: zestful
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/openapi/zestful-openapi.yml
apis:
- description: The Zestful Ingredient Parser API uses machine learning to convert plain recipe ingredient strings into structured JSON data. It parses ingredient names, quantities, units, preparation notes, and matc
  name: Zestful Ingredient Parser API
  slug: zestful
capabilities:
- description: Workflow capability for enriching recipe data by parsing raw ingredient strings into structured, USDA-matched nutritional data. Used by recipe app developers to build searchable recipes, generate shop
  name: Zestful Recipe Data Enrichment
  slug: recipe-data-enrichment
common:
- title: ''
  type: Website
  url: https://zestfuldata.com/
- title: ''
  type: Documentation
  url: https://zestfuldata.com/docs/
- title: ''
  type: Pricing
  url: https://zestfuldata.com/pricing/
- title: ''
  type: SDKs
  url: https://github.com/mtlynch/zestful-client
- title: ''
  type: Vocabulary
  url: vocabulary/zestful-vocabulary.yml
created: '2024-11-14'
description: Zestful provides a machine-learning-powered ingredient parser API that turns plain recipe ingredient strings into structured JSON data. The API extracts quantity, unit, product name, preparation notes, and USDA FoodData Central database matches from free-form recipe text. Designed for recipe app developers building searchable recipes, shopping lists, and ingredient databases.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Zestful Context
  property_count: 15
  slug: zestful-context
layout: provider
modified: '2026-05-03'
name: Zestful
rules:
- name: Zestful API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 5
  slug: zestful-rules
skills: []
slug: zestful
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zestful\nname: Zestful\ndescription: >-\n  Zestful provides a machine-learning-powered ingredient parser API that turns\n  plain recipe ingredient strings into structured JSON data. The API extracts\n  quantity, unit, product name, preparation notes, and USDA FoodData Central\n  database matches from free-form recipe text. Designed for recipe app\n  developers building searchable recipes, shopping lists, and ingredient\n  databases.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Food\n  - Ingredients\n  - Parsers\n  - Recipes\n  - USDA\ncreated: '2024-11-14'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: zestful:zestful\n    name: Zestful Ingredient Parser API\n    tags:\n      - Food\n      - Ingredients\n      - Parsers\n      - Recipes\n      - USDA\n \
  \   baseURL: https://zestfuldata.com\n    humanURL: https://zestfuldata.com/docs/\n    properties:\n      - url: https://zestfuldata.com/docs/\n        type: Documentation\n      - url: https://zestfuldata.com/pricing/\n        type: Pricing\n      - url: openapi/zestful-openapi.yml\n        type: OpenAPI\n      - url: json-schema/zestful-ingredient-schema.json\n        type: JSONSchema\n      - url: json-schema/zestful-parse-response-schema.json\n        type: JSONSchema\n      - url: json-ld/zestful-context.jsonld\n        type: JSONLD\n      - url: rules/zestful-rules.yml\n        type: SpectralRules\n      - url: capabilities/recipe-data-enrichment.yaml\n        type: NaftikoCapabilities\n    description: >-\n      The Zestful Ingredient Parser API uses machine learning to convert plain\n      recipe ingredient strings into structured JSON data. It parses ingredient\n      names, quantities, units, preparation notes, and matches each ingredient\n      against the USDA FoodData Central\
  \ database. Accepts up to 100 ingredients\n      per request. Pricing: free tier (30 parses/day), professional ($0.02 per\n      parse), and enterprise (flat fee, private server).\ncommon:\n  - url: https://zestfuldata.com/\n    name: Zestful Website\n    type: Website\n    description: Main Zestful website with API overview.\n  - url: https://zestfuldata.com/docs/\n    name: API Reference\n    type: Documentation\n    description: Full API documentation and reference.\n  - url: https://zestfuldata.com/pricing/\n    name: Pricing\n    type: Pricing\n    description: Pricing plans for the Zestful API.\n  - url: https://rapidapi.com/zestfuldata/api/recipe-and-ingredient-analysis\n    name: Zestful on RapidAPI\n    type: Integrations\n    description: Zestful API available on the RapidAPI marketplace.\n  - url: https://github.com/mtlynch/zestful-client\n    name: Zestful Client\n    type: SDKs\n    description: Official Zestful API client library on GitHub.\n  - url: vocabulary/zestful-vocabulary.yml\n\
  \    name: Vocabulary\n    type: Vocabulary\n    description: Domain vocabulary for Zestful ingredient parsing concepts.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/apis.yml
tags:
- Food
- Ingredients
- Parsers
- Recipes
- USDA
url: https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/apis.yml
use_cases: []
---
