---
api_count: 2
api_specs:
- filename: tesla-openapi-original.yml
  format: yaml
  label: Tesla Fleet API
  slug: fleet-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/openapi/tesla-openapi-original.yml
- filename: tesla-openapi-original.yml
  format: yaml
  label: Tesla Owner API
  slug: owner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/openapi/tesla-openapi-original.yml
apis:
- description: The Tesla Fleet API is the official partner API providing access to Tesla vehicles and energy devices with owner-granted OAuth permissions. Supports vehicle telemetry, remote vehicle commands, chargin
  name: Tesla Fleet API
  slug: fleet-api
- description: The Tesla Owner API (community-documented) provides access to Tesla vehicles via the owner-api.teslamotors.com endpoint. Supports vehicle state retrieval, remote commands, and vehicle management for p
  name: Tesla Owner API
  slug: owner-api
capabilities:
- description: Workflow capability for Tesla vehicle monitoring and remote control via the Tesla Owner API. Enables fleet managers, IoT integrations, and personal vehicle owners to monitor battery, climate, location
  name: Tesla Vehicle Monitoring and Control
  slug: vehicle-monitoring
common:
- title: ''
  type: Portal
  url: https://developer.tesla.com/
- title: ''
  type: Announcements
  url: https://developer.tesla.com/docs/fleet-api/announcements
- title: ''
  type: FAQ
  url: https://developer.tesla.com/docs/fleet-api/support/faq
- title: ''
  type: Contact
  url: https://developer.tesla.com/docs/fleet-api/support/contact
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
- title: ''
  type: Postman
  url: https://documenter.getpostman.com/view/781424/2s9YRCWB4f
created: '2025-02-25'
description: Tesla, Inc. is an American electric vehicle and clean energy company founded in 2003. Tesla offers the Fleet API for partners to access Tesla vehicles and energy devices with owner-granted permissions, covering vehicle telemetry, remote commands, charging management, energy site management, and fleet management capabilities.
features: []
image: https://www.tesla.com/favicon.ico
integrations: []
jsonld:
- class_count: 30
  name: Tesla Context
  property_count: 0
  slug: tesla-context
layout: provider
modified: '2026-05-03'
name: Tesla
rules:
- name: Tesla API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 5
  slug: tesla-rules
skills: []
slug: tesla
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tesla\nname: Tesla\ndescription: >-\n  Tesla, Inc. is an American electric vehicle and clean energy company founded in 2003.\n  Tesla offers the Fleet API for partners to access Tesla vehicles and energy devices\n  with owner-granted permissions, covering vehicle telemetry, remote commands, charging\n  management, energy site management, and fleet management capabilities.\ntype: Index\nimage: https://www.tesla.com/favicon.ico\ntags:\n  - Automobiles\n  - Cars\n  - Vehicles\n  - Electric Vehicles\n  - Energy\n  - Clean Energy\n  - IoT\nurl: https://developer.tesla.com/\ncreated: '2025-02-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tesla:fleet-api\n    name: Tesla Fleet API\n    description: >-\n      The Tesla Fleet API is the official partner API providing access to Tesla\n      vehicles and energy devices with owner-granted OAuth permissions. Supports\n      vehicle telemetry, remote vehicle commands, charging management, energy site\n \
  \     control, and fleet management for third-party applications.\n    humanURL: https://developer.tesla.com/docs/fleet-api\n    baseURL: https://fleet-api.prd.na.vn.cloud.tesla.com/api/1\n    tags:\n      - Vehicles\n      - Telemetry\n      - Remote Commands\n      - Charging\n      - Energy\n      - Fleet Management\n    properties:\n      - url: https://developer.tesla.com/docs/fleet-api\n        type: Documentation\n      - url: https://developer.tesla.com/docs/fleet-api/endpoints/vehicle-endpoints\n        type: Documentation\n      - url: https://developer.tesla.com/docs/fleet-api/endpoints/vehicle-commands\n        type: Documentation\n      - url: https://developer.tesla.com/docs/fleet-api/endpoints/charging-endpoints\n        type: Documentation\n      - url: https://developer.tesla.com/docs/fleet-api/endpoints/energy\n        type: Documentation\n      - url: https://developer.tesla.com/docs/fleet-api/authentication/overview\n        type: Authentication\n      - url: https://developer.tesla.com/docs/fleet-api/billing-and-limits\n\
  \        type: Billing\n      - url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/openapi/tesla-openapi-original.yml\n        type: OpenAPI\n  - aid: tesla:owner-api\n    name: Tesla Owner API\n    description: >-\n      The Tesla Owner API (community-documented) provides access to Tesla vehicles\n      via the owner-api.teslamotors.com endpoint. Supports vehicle state retrieval,\n      remote commands, and vehicle management for personal vehicle owners.\n    humanURL: https://tesla-api.timdorr.com/\n    baseURL: https://owner-api.teslamotors.com/api/1\n    tags:\n      - Vehicles\n      - Owner API\n      - Remote Commands\n      - Telemetry\n    properties:\n      - url: https://tesla-api.timdorr.com/\n        type: Documentation\n      - url: https://github.com/timdorr/tesla-api\n        type: Repository\n      - url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/openapi/tesla-openapi-original.yml\n        type: OpenAPI\ncommon:\n \
  \ - name: Tesla Developer Portal\n    url: https://developer.tesla.com/\n    type: Portal\n  - name: Tesla Fleet API Announcements\n    url: https://developer.tesla.com/docs/fleet-api/announcements\n    type: Announcements\n  - name: Tesla Fleet API FAQ\n    url: https://developer.tesla.com/docs/fleet-api/support/faq\n    type: FAQ\n  - name: Tesla Developer Support\n    url: https://developer.tesla.com/docs/fleet-api/support/contact\n    type: Contact\n  - name: Tesla GitHub Organization\n    url: https://github.com/teslamotors\n    type: Repository\n  - name: Tesla Website\n    url: https://www.tesla.com\n    type: Website\n  - name: TeslaPy SDK\n    url: https://github.com/tdorssers/TeslaPy\n    type: SDK\n  - name: Tesla API Ruby Gem\n    url: https://github.com/timdorr/tesla-api\n    type: SDK\n  - name: Tesla Postman Collection\n    url: https://documenter.getpostman.com/view/781424/2s9YRCWB4f\n    type: Postman\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tesla/refs/heads/main/apis.yml
tags:
- Automobiles
- Cars
- Vehicles
- Electric Vehicles
- Energy
- Clean Energy
- IoT
url: https://developer.tesla.com/
use_cases: []
---
