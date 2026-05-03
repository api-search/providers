---
api_count: 1
api_specs:
- filename: tesla-motors-owner-openapi.yml
  format: yaml
  label: Tesla Owner API
  slug: owner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/openapi/tesla-motors-owner-openapi.yml
apis:
- description: The Tesla Owner API (unofficial) provides access to Tesla vehicle telemetry, state data, and remote command capabilities for personal vehicles. Supports vehicle listing, state retrieval (charge, clima
  name: Tesla Owner API
  slug: owner-api
capabilities:
- description: Unified workflow capability for Tesla electric vehicle management and monitoring. Enables fleet operators, vehicle owners, and IoT integrations to monitor vehicle telemetry (charge, climate, location,
  name: Tesla Motors Vehicle Management
  slug: vehicle-management
common:
- title: ''
  type: Portal
  url: https://developer.tesla.com
- title: ''
  type: Documentation
  url: https://developer.tesla.com/docs/fleet-api
- title: ''
  type: Documentation
  url: https://tesla-api.timdorr.com/
- title: ''
  type: Repository
  url: https://github.com/teslamotors
- title: ''
  type: Website
  url: https://www.tesla.com
- title: ''
  type: SDK
  url: https://github.com/tdorssers/TeslaPy
- title: ''
  type: SDK
  url: https://github.com/timdorr/tesla-api
created: '2026-03-16'
description: Tesla, Inc. (formerly Tesla Motors, Inc.) is an American electric vehicle and clean energy company that designs and manufactures electric cars, battery energy storage systems, solar panels, and related products. The Tesla Owner API provides programmatic access to Tesla vehicles for monitoring state, controlling climate, locking/unlocking doors, managing charging, and executing remote commands.
features: []
image: https://www.tesla.com/favicon.ico
integrations: []
jsonld:
- class_count: 32
  name: Tesla Motors Context
  property_count: 0
  slug: tesla-motors-context
layout: provider
modified: '2026-05-03'
name: Tesla Motors
rules:
- name: Tesla Motors API Rules
  rule_count: 7
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 5
  slug: tesla-motors-rules
skills: []
slug: tesla-motors
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tesla-motors\nname: Tesla Motors\ndescription: >-\n  Tesla, Inc. (formerly Tesla Motors, Inc.) is an American electric vehicle and\n  clean energy company that designs and manufactures electric cars, battery energy\n  storage systems, solar panels, and related products. The Tesla Owner API provides\n  programmatic access to Tesla vehicles for monitoring state, controlling climate,\n  locking/unlocking doors, managing charging, and executing remote commands.\ntype: Index\nimage: https://www.tesla.com/favicon.ico\ntags:\n  - Automobiles\n  - Electric Vehicles\n  - Cars\n  - Smart Vehicles\n  - IoT\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tesla-motors:owner-api\n    name: Tesla Owner API\n    description: >-\n      The Tesla Owner API (unofficial) provides access to Tesla vehicle telemetry,\n      state data, and remote command\
  \ capabilities for personal vehicles. Supports\n      vehicle listing, state retrieval (charge, climate, drive, vehicle config),\n      and commands including wake-up, door lock/unlock, climate control, charging,\n      trunk control, and media playback.\n    humanURL: https://tesla-api.timdorr.com/\n    baseURL: https://owner-api.teslamotors.com\n    tags:\n      - Vehicles\n      - Telemetry\n      - Remote Commands\n      - Charging\n      - Climate Control\n    properties:\n      - url: https://tesla-api.timdorr.com/\n        type: Documentation\n      - url: https://github.com/timdorr/tesla-api\n        type: Repository\n      - url: https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/openapi/tesla-motors-owner-openapi.yml\n        type: OpenAPI\ncommon:\n  - name: Tesla Developer Portal\n    url: https://developer.tesla.com\n    type: Portal\n  - name: Tesla Fleet API Documentation\n    url: https://developer.tesla.com/docs/fleet-api\n    type: Documentation\n\
  \  - name: Tesla Owner API (Unofficial Documentation)\n    url: https://tesla-api.timdorr.com/\n    type: Documentation\n  - name: Tesla Motors GitHub\n    url: https://github.com/teslamotors\n    type: Repository\n  - name: Tesla Website\n    url: https://www.tesla.com\n    type: Website\n  - name: Tesla Developer SDK (Python)\n    url: https://github.com/tdorssers/TeslaPy\n    type: SDK\n  - name: Tesla API Ruby Gem\n    url: https://github.com/timdorr/tesla-api\n    type: SDK\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/apis.yml
tags:
- Automobiles
- Electric Vehicles
- Cars
- Smart Vehicles
- IoT
url: https://raw.githubusercontent.com/api-evangelist/tesla-motors/refs/heads/main/apis.yml
use_cases: []
---
