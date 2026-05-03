---
api_count: 1
api_specs:
- filename: thermal-power-openapi.yml
  format: yaml
  label: Thermal Power API
  slug: thermal-power
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/openapi/thermal-power-openapi.yml
apis:
- description: The Thermal Power API provides access to thermal power generation data including plant-level operational metrics, fuel consumption, heat rate performance, and capacity utilization for coal, natural ga
  name: Thermal Power API
  slug: thermal-power
capabilities:
- description: Workflow capability for monitoring thermal power generation assets including coal, natural gas, petroleum, and nuclear plants. Covers operational data, plant-level fuel metrics, generator capacity, an
  name: Thermal Power Monitoring
  slug: thermal-power-monitoring
common:
- title: ''
  type: Website
  url: https://www.eia.gov/opendata/
- title: ''
  type: Documentation
  url: https://www.eia.gov/opendata/documentation.php
- title: ''
  type: SignUp
  url: https://www.eia.gov/opendata/register.php
- title: ''
  type: Explorer
  url: https://www.eia.gov/opendata/browser/
- title: ''
  type: Documentation
  url: https://www.eia.gov/developer/
created: '2026-03-16'
description: Thermal power generation data APIs providing access to plant-level operational metrics, fuel consumption, heat rates, and generating capacity for coal, natural gas, petroleum, and nuclear power plants in the United States. Primary data source is the U.S. Energy Information Administration (EIA) Open Data API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Thermal Power Context
  property_count: 3
  slug: thermal-power-context
layout: provider
modified: '2026-05-03'
name: Thermal Power
rules:
- name: Thermal Power API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: thermal-power-rules
skills: []
slug: thermal-power
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thermal-power\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/apis.yml\napis:\n  - aid: thermal-power:thermal-power\n    name: Thermal Power API\n    tags:\n      - Energy\n      - Thermal Power\n      - Power Generation\n      - Electricity\n      - Fossil Fuels\n      - Nuclear\n    humanURL: https://www.eia.gov/opendata/\n    baseURL: https://api.eia.gov/v2\n    properties:\n      - url: https://www.eia.gov/opendata/documentation.php\n        type: Documentation\n      - url: openapi/thermal-power-openapi.yml\n        type: OpenAPI\n      - url: json-schema/thermal-power-plant-schema.json\n        type: JSONSchema\n      - url: json-ld/thermal-power-context.jsonld\n        type: JSONLD\n      - url: json-structure/thermal-power-structure.json\n        type: JSONStructure\n      - url: rules/thermal-power-rules.yml\n        type: SpectralRules\n      - url: capabilities/thermal-power-monitoring.yaml\n        type: NaftikoCapabilities\n\
  \      - url: vocabulary/thermal-power-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      The Thermal Power API provides access to thermal power generation data\n      including plant-level operational metrics, fuel consumption, heat rate\n      performance, and capacity utilization for coal, natural gas, petroleum,\n      and nuclear generation assets. Data sourced from the U.S. Energy\n      Information Administration (EIA) Open Data API.\nname: Thermal Power\ntags:\n  - Energy\n  - Thermal Power\n  - Power Generation\n  - Electricity\n  - Coal\n  - Natural Gas\n  - Nuclear\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  Thermal power generation data APIs providing access to plant-level operational\n  metrics, fuel consumption, heat rates, and generating capacity for coal,\n  natural gas, petroleum, and nuclear\
  \ power plants in the United States. Primary\n  data source is the U.S. Energy Information Administration (EIA) Open Data API.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: EIA Open Data API\n    url: https://www.eia.gov/opendata/\n    type: Website\n  - name: EIA API Documentation\n    url: https://www.eia.gov/opendata/documentation.php\n    type: Documentation\n  - name: EIA API Registration\n    url: https://www.eia.gov/opendata/register.php\n    type: SignUp\n  - name: EIA API Browser\n    url: https://www.eia.gov/opendata/browser/\n    type: Explorer\n  - name: EIA Developer Resources\n    url: https://www.eia.gov/developer/\n    type: Documentation\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/apis.yml
tags:
- Energy
- Thermal Power
- Power Generation
- Electricity
- Coal
- Natural Gas
- Nuclear
url: https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/apis.yml
use_cases: []
---
