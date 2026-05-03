---
api_count: 1
api_specs:
- filename: smartcar-vehicles-openapi.yml
  format: yaml
  label: Smartcar Vehicles API
  slug: vehicles-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/openapi/smartcar-vehicles-openapi.yml
apis:
- description: The Smartcar Vehicles API lets you access standardized vehicle data and send commands to connected vehicles. Retrieve signals such as battery level, odometer, location, fuel, engine oil, and diagnosti
  name: Smartcar Vehicles API
  slug: vehicles-api
capabilities:
- description: Unified workflow capability for managing connected vehicles through Smartcar's platform. Enables fleet operators, mobility apps, and EV management solutions to read vehicle telemetry, monitor charging
  name: Smartcar Connected Vehicle Management
  slug: connected-vehicle-management
common:
- title: ''
  type: Portal
  url: https://smartcar.com/
- title: ''
  type: Documentation
  url: https://smartcar.com/docs/api/
- title: ''
  type: Website
  url: https://smartcar.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/smartcar
- title: ''
  type: Pricing
  url: https://smartcar.com/pricing/
- title: ''
  type: OpenAPI
  url: openapi/smartcar-vehicles-openapi.yml
- title: ''
  type: Spectral
  url: rules/smartcar-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/connected-vehicle-management.yaml
- title: ''
  type: JSONSchema
  url: json-schema/smartcar-vehicle-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/smartcar-battery-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/smartcar-vehicles-structure.json
- title: ''
  type: JSONLD
  url: json-ld/smartcar-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/smartcar-vocabulary.yml
created: '2026-03-16'
description: Smartcar is a connected vehicle platform that provides a standardized REST API for accessing vehicle data and sending commands to connected cars. The API enables developers to retrieve battery levels, odometer readings, location, lock/unlock doors, start/stop charging, and access vehicle attributes across multiple vehicle brands through a single integration. Smartcar supports OAuth 2.0 authorization and covers EVs and ICE vehicles from dozens of OEMs including Tesla, Ford, BMW, Honda, and more.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Smartcar Context
  property_count: 11
  slug: smartcar-context
layout: provider
modified: '2026-05-02'
name: Smartcar
rules:
- name: Smartcar API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 4
  slug: smartcar-rules
skills: []
slug: smartcar
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: smartcar\nname: Smartcar\ndescription: >-\n  Smartcar is a connected vehicle platform that provides a standardized REST\n  API for accessing vehicle data and sending commands to connected cars. The\n  API enables developers to retrieve battery levels, odometer readings,\n  location, lock/unlock doors, start/stop charging, and access vehicle\n  attributes across multiple vehicle brands through a single integration.\n  Smartcar supports OAuth 2.0 authorization and covers EVs and ICE vehicles\n  from dozens of OEMs including Tesla, Ford, BMW, Honda, and more.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Automotive\n  - Connected Vehicles\n  - IoT\n  - Mobility\n  - Fleet Management\n  - EV Management\n  - Telematics\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\napis:\n  - aid: smartcar:vehicles-api\n\
  \    name: Smartcar Vehicles API\n    description: >-\n      The Smartcar Vehicles API lets you access standardized vehicle data and\n      send commands to connected vehicles. Retrieve signals such as battery\n      level, odometer, location, fuel, engine oil, and diagnostic codes, as\n      well as issue commands like lock/unlock doors, start/stop charging,\n      set charge limit, and set navigation destinations across multiple vehicle\n      brands. Uses OAuth 2.0 bearer token authentication.\n    humanURL: https://smartcar.com/docs/api/\n    tags:\n      - Connected Cars\n      - Telematics\n      - Vehicles\n      - Fleet\n      - EV\n    properties:\n      - type: Documentation\n        url: https://smartcar.com/docs/api/\n      - type: Reference\n        url: https://smartcar.com/docs/api-reference/intro\n      - type: Authentication\n        url: https://smartcar.com/docs/api-reference/intro\n      - type: OpenAPI\n        url: openapi/smartcar-vehicles-openapi.yml\n      - type:\
  \ Postman\n        url: https://www.postman.com/smartcar/smartcar-api/documentation/fqmwehs/smartcar-api\ncommon:\n  - type: Portal\n    url: https://smartcar.com/\n  - type: Documentation\n    url: https://smartcar.com/docs/api/\n  - type: Website\n    url: https://smartcar.com/\n  - type: GitHubOrganization\n    url: https://github.com/smartcar\n  - type: Pricing\n    url: https://smartcar.com/pricing/\n  - type: OpenAPI\n    url: openapi/smartcar-vehicles-openapi.yml\n  - type: Spectral\n    url: rules/smartcar-rules.yml\n  - type: Capabilities\n    url: capabilities/connected-vehicle-management.yaml\n  - type: JSONSchema\n    url: json-schema/smartcar-vehicle-schema.json\n  - type: JSONSchema\n    url: json-schema/smartcar-battery-schema.json\n  - type: JSONStructure\n    url: json-structure/smartcar-vehicles-structure.json\n  - type: JSONLD\n    url: json-ld/smartcar-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/smartcar-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/apis.yml
tags:
- Automotive
- Connected Vehicles
- IoT
- Mobility
- Fleet Management
- EV Management
- Telematics
url: https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/apis.yml
use_cases: []
---
