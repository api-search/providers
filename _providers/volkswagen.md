---
api_count: 1
api_specs:
- filename: volkswagen-okapi-openapi.yml
  format: yaml
  label: Volkswagen OKAPI - Open Konfigurator API
  slug: volkswagen-okapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volkswagen/refs/heads/main/openapi/volkswagen-okapi-openapi.yml
apis:
- description: The VW OKAPI API provides access to Volkswagen AG product data and vehicle configuration services across global markets. Catalog endpoints (GET) browse countries, brands, models, types, and options. O
  name: Volkswagen OKAPI - Open Konfigurator API
  slug: volkswagen-okapi
capabilities:
- description: Unified capability for the Volkswagen OKAPI vehicle configurator workflow. Enables browsing the VW Group product catalog across global markets, configuring vehicles with options, validating buildabili
  name: Volkswagen Vehicle Configuration
  slug: vehicle-configuration
common:
- title: ''
  type: WhatsNew
  url: https://productdata.volkswagenag.com/whats-new.html
- title: ''
  type: Guide
  url: https://productdata.volkswagenag.com/introduction.html
- title: ''
  type: Support
  url: https://productdata.volkswagenag.com/support.html
- title: ''
  type: TermsOfService
  url: https://productdata.volkswagenag.com/condition-of-use.html
- title: ''
  type: Portal
  url: https://okapi-ddp.productdata.volkswagenag.com/dev-portal/
- title: ''
  type: OpenAPI
  url: openapi/volkswagen-okapi-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/volkswagen-vehicle-config-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/volkswagen-vehicle-config-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/volkswagen-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/volkswagen-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/volkswagen-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/vehicle-configuration.yaml
created: '2025-02-25'
description: Volkswagen is a German automotive company and the parent of the VW Group, manufacturing vehicles under brands including Volkswagen, Audi, SEAT, Skoda, CUPRA, Porsche, Lamborghini, and Bentley. The OKAPI (Open Konfigurator API) provides programmatic access to VW AG product data for vehicle catalog browsing, interactive configuration, buildability validation, WLTP emissions data, configuration images, and order/pricing information across global markets.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Volkswagen Context
  property_count: 0
  slug: volkswagen-context
layout: provider
modified: '2026-05-03'
name: Volkswagen
rules:
- name: Volkswagen API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: volkswagen-rules
skills: []
slug: volkswagen
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: volkswagen\nname: Volkswagen\nurl: https://productdata.volkswagenag.com/\ndescription: >-\n  Volkswagen is a German automotive company and the parent of the VW Group,\n  manufacturing vehicles under brands including Volkswagen, Audi, SEAT, Skoda,\n  CUPRA, Porsche, Lamborghini, and Bentley. The OKAPI (Open Konfigurator API)\n  provides programmatic access to VW AG product data for vehicle catalog browsing,\n  interactive configuration, buildability validation, WLTP emissions data,\n  configuration images, and order/pricing information across global markets.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-25'\nmodified: '2026-05-03'\nposition: Consumer\ntags:\n  - Automobiles\n  - Cars\n  - Vehicles\n  - Automotive\n  - Vehicle Configuration\nspecificationVersion: '0.19'\napis:\n  - aid: volkswagen:volkswagen-okapi\n    name: Volkswagen OKAPI - Open Konfigurator API\n    description: >-\n\
  \      The VW OKAPI API provides access to Volkswagen AG product data and vehicle\n      configuration services across global markets. Catalog endpoints (GET) browse\n      countries, brands, models, types, and options. Operation endpoints (POST)\n      handle buildability checking, configuration recovery, interactive configuration,\n      resolution, WLTP emissions data, vehicle images, and order information with pricing.\n    humanURL: https://productdata.volkswagenag.com/\n    baseURL: https://productdata.volkswagenag.com/v3\n    tags:\n      - Automobiles\n      - Vehicle Configuration\n      - Konfigurator\n      - Product Data\n    properties:\n      - url: https://productdata.volkswagenag.com/swagger-doc.html\n        type: Documentation\n      - url: https://productdata.volkswagenag.com/tutorial.html\n        type: GettingStarted\n      - url: openapi/volkswagen-okapi-openapi.yml\n        type: OpenAPI\n      - url: json-schema/volkswagen-vehicle-config-schema.json\n        type:\
  \ JSONSchema\ncommon:\n  - name: Volkswagen OKAPI - Whats New\n    description: Release notes and updates for the OKAPI API.\n    url: https://productdata.volkswagenag.com/whats-new.html\n    type: WhatsNew\n  - name: Volkswagen OKAPI Guide\n    description: Tutorial and guide for using the OKAPI API.\n    url: https://productdata.volkswagenag.com/introduction.html\n    type: Guide\n  - name: Volkswagen OKAPI - Support\n    description: Support resources for OKAPI API users.\n    url: https://productdata.volkswagenag.com/support.html\n    type: Support\n  - name: Volkswagen OKAPI Terms and Condition of Use\n    description: Terms and conditions for OKAPI API access.\n    url: https://productdata.volkswagenag.com/condition-of-use.html\n    type: TermsOfService\n  - name: Volkswagen OKAPI Developer Portal\n    description: Developer registration and API key management.\n    url: https://okapi-ddp.productdata.volkswagenag.com/dev-portal/\n    type: Portal\n  - type: OpenAPI\n    url: openapi/volkswagen-okapi-openapi.yml\n\
  \  - type: JSONSchema\n    url: json-schema/volkswagen-vehicle-config-schema.json\n  - type: JSONStructure\n    url: json-structure/volkswagen-vehicle-config-structure.json\n  - type: JSON-LD\n    url: json-ld/volkswagen-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/volkswagen-vocabulary.yml\n  - type: SpectralRules\n    url: rules/volkswagen-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/vehicle-configuration.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/volkswagen/refs/heads/main/apis.yml
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Vehicle Configuration
url: https://productdata.volkswagenag.com/
use_cases: []
---
