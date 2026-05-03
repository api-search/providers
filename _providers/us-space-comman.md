---
api_count: 1
api_specs:
- filename: us-space-command-space-track-openapi.yml
  format: yaml
  label: Space-Track.org REST API
  slug: space-track-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/openapi/us-space-command-space-track-openapi.yml
apis:
- description: Space-Track.org is the official public source for US Space Command's satellite catalog and space situational awareness data, maintained by the 18th Space Defense Squadron. The REST API provides access
  name: Space-Track.org REST API
  slug: space-track-api
capabilities:
- description: Unified capability for space situational awareness (SSA) operations, combining orbital element tracking, satellite catalog queries, conjunction monitoring, and reentry prediction. Supports satellite o
  name: US Space Command Space Situational Awareness
  slug: space-situational-awareness
common: []
created: '2024-12-03'
description: US Space Command (USSPACECOM) is a unified combatant command in the United States Department of Defense responsible for conducting operations in, from, and through space to deter conflict and, if necessary, defeat aggressors. The command provides space situational awareness (SSA) data through Space-Track.org, including the official satellite catalog with orbital element sets, conjunction warnings, and reentry predictions for all tracked objects.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Us Space Comman Context
  property_count: 20
  slug: us-space-comman-context
layout: provider
modified: '2026-05-03'
name: US Space Command
rules:
- name: US Space Command API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 2
  slug: us-space-comman-rules
skills: []
slug: us-space-comman
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-space-comman\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/apis.yml\napis:\n  - aid: us-space-comman:space-track-api\n    name: Space-Track.org REST API\n    tags:\n      - Space Situational Awareness\n      - Orbital Data\n      - Satellite Tracking\n      - Federal Government\n      - Open Data\n    humanURL: https://www.space-track.org/documentation\n    properties:\n      - url: https://www.space-track.org/documentation\n        type: Documentation\n      - url: https://www.space-track.org\n        type: Portal\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/openapi/us-space-command-space-track-openapi.yml\n        type: OpenAPI\n    description: >-\n      Space-Track.org is the official public source for US Space Command's\n      satellite catalog and space situational awareness data, maintained by the\n      18th Space Defense Squadron. The REST API provides\
  \ access to orbital element\n      sets (GP/TLEs), the satellite catalog (SATCAT), conjunction data messages\n      (CDMs), decay predictions (TIP), and space object history. Requires a free\n      Space-Track.org account for authentication.\nname: US Space Command\ntags:\n  - Federal Government\n  - Space\n  - Space Situational Awareness\n  - Satellite Tracking\n  - Open Data\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  US Space Command (USSPACECOM) is a unified combatant command in the United States\n  Department of Defense responsible for conducting operations in, from, and through\n  space to deter conflict and, if necessary, defeat aggressors. The command provides\n  space situational awareness (SSA) data through Space-Track.org, including the\n  official satellite catalog with orbital element sets, conjunction warnings, and\n\
  \  reentry predictions for all tracked objects.\nfeatures:\n  - Orbital Element Sets (GP / TLE)\n  - Satellite Catalog (SATCAT)\n  - Conjunction Data Messages (CDM)\n  - Tracking and Impact Prediction (TIP)\n  - Historical Orbital Ephemerides\n  - Space Object Decay Data\nuseCases:\n  - Satellite operations and collision avoidance\n  - Space debris monitoring\n  - Orbital mechanics research\n  - Satellite tracking and identification\n  - Space traffic management\n  - Launch planning and collision risk assessment\nintegrations:\n  - TraCSS (Traffic Coordination System for Space)\nsolutions:\n  - Space Situational Awareness\n  - Space Traffic Management\n  - Orbital Debris Research\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/apis.yml
tags:
- Federal Government
- Space
- Space Situational Awareness
- Satellite Tracking
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/us-space-comman/refs/heads/main/apis.yml
use_cases: []
---
