---
api_count: 1
api_specs:
- filename: transportapi-openapi.yml
  format: yaml
  label: TransportAPI
  slug: transportapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/openapi/transportapi-openapi.yml
apis:
- description: UK public transport data API providing real-time bus and rail departures, multimodal journey planning, bus and rail performance analytics, and transport places lookup across Great Britain.
  name: TransportAPI
  slug: transportapi
capabilities:
- description: Workflow capability for UK public transport data covering real-time bus and rail departures, multimodal journey planning, and transport places lookup. Used by transit app developers, website builders,
  name: TransportAPI UK Transport Information
  slug: uk-transport-information
common:
- title: ''
  type: Website
  url: https://www.transportapi.com/
- title: ''
  type: Documentation
  url: https://developer.transportapi.com/
- title: ''
  type: Sign Up
  url: https://developer.transportapi.com/
- title: ''
  type: GitHub
  url: https://github.com/transportapi
created: '2025-05-02'
description: TransportAPI is a managed data service provider for UK public transport, offering real-time and scheduled bus, rail, and multimodal transport data via REST and WebSocket APIs to power apps, websites, analytics, and data-mining workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 29
  name: Transportapi Context
  property_count: 0
  slug: transportapi-context
layout: provider
modified: '2026-05-03'
name: TransportAPI
rules:
- name: TransportAPI API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 3
    info: 1
    warn: 4
  slug: transportapi-rules
skills: []
slug: transportapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: transportapi\nname: TransportAPI\ndescription: >-\n  TransportAPI is a managed data service provider for UK public transport,\n  offering real-time and scheduled bus, rail, and multimodal transport data\n  via REST and WebSocket APIs to power apps, websites, analytics, and\n  data-mining workflows.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Public Transit\n  - Transport\n  - UK\n  - Real-Time\n  - Journey Planning\n  - Bus\n  - Rail\ncreated: '2025-05-02'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: transportapi:transportapi\n    name: TransportAPI\n    description: >-\n      UK public transport data API providing real-time bus and rail departures,\n      multimodal journey planning, bus and rail performance analytics, and\n      transport places\
  \ lookup across Great Britain.\n    humanURL: https://developer.transportapi.com/\n    baseURL: https://transportapi.com/v3/uk\n    tags:\n      - Public Transit\n      - Transport\n      - UK\n      - Real-Time\n      - Journey Planning\n      - Bus\n      - Rail\n    properties:\n      - type: Documentation\n        url: https://developer.transportapi.com/docs/\n      - type: OpenAPI\n        url: openapi/transportapi-openapi.yml\n      - type: JSONStructure\n        url: json-structure/transportapi-departure-structure.json\n      - type: JSONLD\n        url: json-ld/transportapi-context.jsonld\n      - type: SpectralRules\n        url: rules/transportapi-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/uk-transport-information.yaml\n      - type: Vocabulary\n        url: vocabulary/transportapi-vocabulary.yml\n      - type: Sign Up\n        url: https://developer.transportapi.com/\n    x-services:\n      - TAPI Journey Planner\n      - TAPI Bus Information\n \
  \     - TAPI Bus Performance\n      - TAPI Rail Information\n      - TAPI Rail Performance\n      - TAPI Places\n    x-authentication:\n      type: API Key\n      description: app_id and app_key query parameters or X-App-Id and X-App-Key HTTP headers\n    x-pricing:\n      free: 30 hits per day forever\n      paid: Higher allowance tiers via subscription\ncommon:\n  - type: Website\n    url: https://www.transportapi.com/\n  - type: Documentation\n    url: https://developer.transportapi.com/\n  - type: Sign Up\n    url: https://developer.transportapi.com/\n  - type: GitHub\n    url: https://github.com/transportapi\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/apis.yml
tags:
- Public Transit
- Transport
- UK
- Real-Time
- Journey Planning
- Bus
- Rail
url: https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/apis.yml
use_cases: []
---
