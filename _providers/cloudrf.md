---
api_count: 1
api_specs:
- filename: cloudrf-openapi.yml
  format: yaml
  label: CloudRF API
  slug: cloudrf-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/openapi/cloudrf-openapi.yml
apis:
- description: Public REST API for RF propagation, coverage modeling, mesh and multisite analysis, HF analysis, 3D and satellite modeling, interference detection, signal geo-location, archive/export, clutter and noi
  name: CloudRF API
  slug: cloudrf-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://cloudrf.com/
- title: ''
  type: Documentation
  url: https://cloudrf.com/documentation/
- title: ''
  type: Developer Documentation
  url: https://cloudrf.com/documentation/developer/
- title: ''
  type: API Reference
  url: https://cloudrf.com/documentation/developer/swagger-ui/
- title: ''
  type: Code Samples
  url: https://github.com/Cloud-RF/CloudRF-API-clients
- title: ''
  type: Privacy Policy
  url: https://cloudrf.com/privacy
- title: ''
  type: OpenAPI
  url: openapi/cloudrf-openapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/cloudrf-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudrf-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloudrf-capabilities.yml
created: '2024-07-02'
description: CloudRF is a radio frequency (RF) propagation, coverage modeling, and wireless network planning service. The HTTPS REST API at api.cloudrf.com offers point-to-multipoint coverage heatmaps, point-to-point path analysis, mesh networks, multisite, HF point-to-multipoint and point-to-point analysis, 3D coverage, satellite modeling, interference detection, geo-location of signals, archive and export of calculations, clutter and noise data management, account metrics, and reusable templates. Authentication is by API key passed as the `key` HTTP header.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudrf Context
  property_count: 6
  slug: cloudrf-context
layout: provider
modified: '2026-04-26'
name: CloudRF
rules:
- name: CloudRF API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: cloudrf-rules
skills: []
slug: cloudrf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudrf\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/apis.yml\nname: CloudRF\ntags:\n  - Coverage Modeling\n  - HF Propagation\n  - Mesh Network\n  - Radio Frequency\n  - RF\n  - Satellite\n  - Signal Analysis\n  - Telecommunications\n  - Wireless Planning\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-07-02'\nmodified: '2026-04-26'\nposition: Consumer\nx-type: company\nx-company: CloudRF (Farrant Consulting Ltd.)\ndescription: >-\n  CloudRF is a radio frequency (RF) propagation, coverage modeling, and\n  wireless network planning service. The HTTPS REST API at\n  api.cloudrf.com offers point-to-multipoint coverage heatmaps,\n  point-to-point path analysis, mesh networks, multisite, HF\n  point-to-multipoint and point-to-point analysis, 3D coverage,\n  satellite modeling, interference detection, geo-location of signals,\n  archive and export of calculations,\
  \ clutter and noise data\n  management, account metrics, and reusable templates. Authentication is\n  by API key passed as the `key` HTTP header.\napis:\n  - aid: cloudrf:cloudrf-api\n    name: CloudRF API\n    tags:\n      - Coverage Modeling\n      - RF\n      - Signal Analysis\n    humanURL: https://cloudrf.com/documentation/developer/\n    properties:\n      - url: https://cloudrf.com/documentation/developer/\n        type: Documentation\n      - url: https://cloudrf.com/documentation/developer/swagger-ui/\n        type: Reference\n      - url: openapi/cloudrf-openapi.yml\n        type: OpenAPI\n      - url: https://github.com/Cloud-RF/CloudRF-API-clients\n        type: Code Samples\n    description: >-\n      Public REST API for RF propagation, coverage modeling, mesh and\n      multisite analysis, HF analysis, 3D and satellite modeling,\n      interference detection, signal geo-location, archive/export,\n      clutter and noise data, and reusable templates. Authentication is\n  \
  \    via the `key` HTTP header.\ncommon:\n  - type: Website\n    url: https://cloudrf.com/\n  - type: Documentation\n    url: https://cloudrf.com/documentation/\n  - type: Developer Documentation\n    url: https://cloudrf.com/documentation/developer/\n  - type: API Reference\n    url: https://cloudrf.com/documentation/developer/swagger-ui/\n  - type: Code Samples\n    url: https://github.com/Cloud-RF/CloudRF-API-clients\n  - type: Privacy Policy\n    url: https://cloudrf.com/privacy\n  - type: OpenAPI\n    url: openapi/cloudrf-openapi.yml\n  - type: JSON-LD\n    url: json-ld/cloudrf-context.jsonld\n  - type: Spectral\n    url: rules/cloudrf-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloudrf-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/apis.yml
tags:
- Coverage Modeling
- HF Propagation
- Mesh Network
- Radio Frequency
- RF
- Satellite
- Signal Analysis
- Telecommunications
- Wireless Planning
url: https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/apis.yml
use_cases: []
---
