---
api_count: 1
api_specs:
- filename: spacex-api-openapi.yml
  format: yaml
  label: SpaceX API
  slug: spacex-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/openapi/spacex-api-openapi.yml
apis:
- description: Open-source REST API providing data on SpaceX launches, rockets, capsules, cores, crew, launchpads, landing pads, payloads, ships, and Starlink satellites. Supports query, pagination, and population o
  name: SpaceX API
  slug: spacex-api
capabilities:
- description: Workflow capability for tracking SpaceX missions end-to-end — from upcoming launches through vehicle reuse history. Combines launch data, rocket specs, crew assignments, capsule and core reuse, payloa
  name: SpaceX Mission Tracking
  slug: mission-tracking
common:
- title: ''
  type: Website
  url: https://www.spacex.com
- title: ''
  type: GitHub
  url: https://github.com/r-spacex/SpaceX-API
- title: ''
  type: Documentation
  url: https://github.com/r-spacex/SpaceX-API/blob/master/docs/v5/README.md
created: '2024-11-07'
description: The SpaceX API is an open-source REST API providing comprehensive data about SpaceX missions, rockets, capsules, cores, crew, launchpads, landing pads, payloads, and the Starlink satellite constellation. It offers endpoints for all past and upcoming launches, real-time mission data, and vehicle telemetry. No authentication is required.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 17
  name: Spacex Api Context
  property_count: 15
  slug: spacex-api-context
layout: provider
modified: '2026-05-02'
name: SpaceX API
rules:
- name: SpaceX API API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 4
  slug: spacex-api-rules
skills: []
slug: spacex-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spacex-api\nurl: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/apis.yml\nname: SpaceX API\ndescription: >-\n  The SpaceX API is an open-source REST API providing comprehensive data about SpaceX\n  missions, rockets, capsules, cores, crew, launchpads, landing pads, payloads, and the\n  Starlink satellite constellation. It offers endpoints for all past and upcoming launches,\n  real-time mission data, and vehicle telemetry. No authentication is required.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Space\n  - Aerospace\n  - Launches\n  - SpaceX\ncreated: '2024-11-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spacex-api:spacex-api\n    name: SpaceX API\n    description: >-\n      Open-source REST API providing data on SpaceX launches, rockets, capsules, cores,\n      crew, launchpads, landing pads, payloads, ships, and Starlink satellites. Supports\n  \
  \    query, pagination, and population of linked entity IDs. No authentication required.\n    humanURL: https://github.com/r-spacex/SpaceX-API\n    baseURL: https://api.spacexdata.com/v5\n    tags:\n      - Space\n      - Aerospace\n      - Launches\n      - SpaceX\n    properties:\n      - url: https://github.com/r-spacex/SpaceX-API\n        type: GitHubRepository\n      - url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/openapi/spacex-api-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/rules/spacex-api-rules.yml\n        type: SpectralRules\n      - url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/json-schema/spacex-api-launch-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/json-structure/spacex-api-launch-structure.json\n        type: JSONStructure\n      - url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/json-ld/spacex-api-context.jsonld\n\
  \        type: JSONLDContext\n      - url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/vocabulary/spacex-api-vocabulary.yml\n        type: Vocabulary\ncommon:\n  - type: Website\n    url: https://www.spacex.com\n  - type: GitHub\n    url: https://github.com/r-spacex/SpaceX-API\n  - type: Documentation\n    url: https://github.com/r-spacex/SpaceX-API/blob/master/docs/v5/README.md\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/apis.yml
tags:
- Space
- Aerospace
- Launches
- SpaceX
url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/apis.yml
use_cases: []
---
