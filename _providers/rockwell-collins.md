---
api_count: 2
api_specs:
- filename: flightaware-aeroapi-openapi.yml
  format: yaml
  label: FlightAware AeroAPI
  slug: flightaware-aeroapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/openapi/flightaware-aeroapi-openapi.yml
apis:
- description: FlightAware AeroAPI (formerly FlightXML) is a RESTful aviation data API acquired by Collins Aerospace in 2021. It provides access to real-time and historical flight tracking data, airport activity, fl
  name: FlightAware AeroAPI
  slug: flightaware-aeroapi
- description: The Collins Digital Exchange is a developer portal operated by Collins Aerospace providing API products for aerospace integration. The portal provides quick-start guides and authenticated access to Co
  name: Collins Digital Exchange APIs
  slug: collins-digital-exchange-apis
capabilities:
- description: Unified workflow capability for aviation flight operations using FlightAware AeroAPI. Enables airlines, ground handlers, flight departments, and technology providers to track flights in real-time, mon
  name: Collins Aerospace Flight Operations
  slug: flight-operations
common:
- title: ''
  type: Website
  url: https://www.rockwellcollins.com
- title: ''
  type: Website
  url: https://www.rtx.com/collinsaerospace/
- title: ''
  type: Portal
  url: https://developer.collins.com/api-products
- title: ''
  type: Portal
  url: https://portal.rockwellcollins.com/
- title: ''
  type: Portal
  url: https://customers.collinsaerospace.com/
- title: ''
  type: Documentation
  url: https://www.flightaware.com/commercial/aeroapi/
- title: ''
  type: Support
  url: https://www.rtx.com/collinsaerospace/what-we-do/service-and-support/support/support-lookup
- title: ''
  type: OpenAPI
  url: openapi/flightaware-aeroapi-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/rockwell-collins-flight-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/rockwell-collins-flight-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/rockwell-collins-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/rockwell-collins-vocabulary.yml
- title: ''
  type: SpectralRuleset
  url: rules/rockwell-collins-rules.yml
created: '2026-03-24'
description: Rockwell Collins was a major American company providing avionics and information technology systems and services to government agencies and aircraft manufacturers. In 2018, Rockwell Collins was acquired by United Technologies and became part of Collins Aerospace, a subsidiary of RTX Corporation (formerly Raytheon Technologies). Collins Aerospace provides flight deck systems, cabin electronics, mission systems, communications, and advanced data services including FlightAware AeroAPI for aviation data. The Collins Digital Exchange offers API products for aerospace and defense integration.
features: []
image: ''
integrations: []
jsonld:
- class_count: 3
  name: Rockwell Collins Context
  property_count: 31
  slug: rockwell-collins-context
layout: provider
modified: '2026-05-02'
name: Rockwell Collins
rules:
- name: Rockwell Collins API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 5
  slug: rockwell-collins-rules
skills: []
slug: rockwell-collins
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rockwell-collins\nname: Rockwell Collins\ndescription: >-\n  Rockwell Collins was a major American company providing avionics and information\n  technology systems and services to government agencies and aircraft manufacturers.\n  In 2018, Rockwell Collins was acquired by United Technologies and became part\n  of Collins Aerospace, a subsidiary of RTX Corporation (formerly Raytheon Technologies).\n  Collins Aerospace provides flight deck systems, cabin electronics, mission systems,\n  communications, and advanced data services including FlightAware AeroAPI for\n  aviation data. The Collins Digital Exchange offers API products for aerospace\n  and defense integration.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/apis.yml\ntags:\n  - Avionics\n  - Aerospace\n  - Defense\n  - Aviation\n  - Flight Deck\ncreated: '2026-03-24'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rockwell-collins:flightaware-aeroapi\n\
  \    name: FlightAware AeroAPI\n    description: >-\n      FlightAware AeroAPI (formerly FlightXML) is a RESTful aviation data API\n      acquired by Collins Aerospace in 2021. It provides access to real-time\n      and historical flight tracking data, airport activity, flight positions,\n      predictive ETAs powered by machine learning (FlightAware Foresight), and\n      configurable alerting on flight events. With over 60 distinct endpoints\n      organized into 7 functional families, AeroAPI supports aviation operations,\n      maintenance scheduling, flight planning, and resource management.\n    tags:\n      - Aviation\n      - Flight Tracking\n      - Aerospace\n      - REST\n      - Real-Time Data\n    humanURL: https://www.flightaware.com/commercial/aeroapi/\n    baseURL: https://aeroapi.flightaware.com/aeroapi\n    properties:\n      - url: https://www.flightaware.com/commercial/aeroapi/\n        type: Documentation\n      - url: https://www.flightaware.com/aeroapi/portal\n \
  \       type: Portal\n      - url: openapi/flightaware-aeroapi-openapi.yml\n        type: OpenAPI\n      - url: https://github.com/flightaware/aeroapps\n        type: GitHubRepository\n    solutions:\n      - Flight Planning\n      - Resource Management\n      - Maintenance Scheduling\n      - Competitive Analysis\n      - Real-Time Alerting\n    features:\n      - Real-Time Flight Tracking\n      - Historical Flight Data (from 2011)\n      - Predictive ETAs (Foresight)\n      - Flight Event Alerts\n      - Airport Activity\n      - Aircraft Position\n      - 60+ API Endpoints\n\n  - aid: rockwell-collins:collins-digital-exchange-apis\n    name: Collins Digital Exchange APIs\n    description: >-\n      The Collins Digital Exchange is a developer portal operated by Collins\n      Aerospace providing API products for aerospace integration. The portal\n      provides quick-start guides and authenticated access to Collins Aerospace\n      API products for authorized partners, customers, and\
  \ suppliers.\n    tags:\n      - Aerospace\n      - Defense\n      - Integration\n      - Partner APIs\n    humanURL: https://developer.collins.com/api-products\n    baseURL: https://developer.collins.com\n    properties:\n      - url: https://developer.collins.com/api-products\n        type: Portal\n\ncommon:\n  - url: https://www.rockwellcollins.com\n    type: Website\n  - url: https://www.rtx.com/collinsaerospace/\n    type: Website\n  - url: https://developer.collins.com/api-products\n    type: Portal\n  - url: https://portal.rockwellcollins.com/\n    type: Portal\n  - url: https://customers.collinsaerospace.com/\n    type: Portal\n  - url: https://www.flightaware.com/commercial/aeroapi/\n    type: Documentation\n  - url: https://www.rtx.com/collinsaerospace/what-we-do/service-and-support/support/support-lookup\n    type: Support\n  - url: openapi/flightaware-aeroapi-openapi.yml\n    type: OpenAPI\n  - url: json-schema/rockwell-collins-flight-schema.json\n    type: JSONSchema\n  -\
  \ url: json-structure/rockwell-collins-flight-structure.json\n    type: JSONStructure\n  - url: json-ld/rockwell-collins-context.jsonld\n    type: JSONLDContext\n  - url: vocabulary/rockwell-collins-vocabulary.yml\n    type: Vocabulary\n  - url: rules/rockwell-collins-rules.yml\n    type: SpectralRuleset\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/apis.yml
tags:
- Avionics
- Aerospace
- Defense
- Aviation
- Flight Deck
url: https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/apis.yml
use_cases: []
---
