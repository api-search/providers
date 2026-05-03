---
api_count: 1
api_specs:
- filename: themeparks-wiki-openapi.yml
  format: yaml
  label: ThemeParks.wiki API
  slug: themeparks-wiki
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/themeparks-wiki/refs/heads/main/openapi/themeparks-wiki-openapi.yml
apis:
- description: An ever-growing database of real-time data for the world's best theme parks, including wait times, schedules, and park information. Provides live wait times, operational status, park schedules, and en
  name: ThemeParks.wiki API
  slug: themeparks-wiki
capabilities:
- description: Unified workflow for theme park trip planning and real-time park monitoring. Combines destination discovery, live wait time monitoring, schedule lookups, and attraction browsing for park visitors, tra
  name: ThemeParks.wiki Theme Park Planning
  slug: theme-park-planning
common:
- title: ''
  type: Website
  url: https://themeparks.wiki/
- title: ''
  type: Documentation
  url: https://api.themeparks.wiki/docs/v1/
- title: ''
  type: GitHub Organization
  url: https://github.com/ThemeParks
- title: ThemeParks.wiki Spectral Rules
  type: SpectralRules
  url: rules/themeparks-wiki-spectral-rules.yml
- title: ThemeParks.wiki Vocabulary
  type: Vocabulary
  url: vocabulary/themeparks-wiki-vocabulary.yml
- title: Theme Park Planning
  type: NaftikoCapability
  url: capabilities/theme-park-planning.yaml
- title: ''
  type: Authentication
  url: ''
created: '2025-02-24'
description: An ever-growing database of real-time data for the world's best theme parks, including wait times, schedules, and park information.
features:
- description: Live queue wait times and operational status for attractions at 75+ destinations
  name: Real-Time Wait Times
- description: Operating hours, special event schedules, and monthly calendar views for parks
  name: Park Schedules
- description: Complete listing of all supported theme park resort destinations worldwide
  name: Destination Catalog
- description: Detailed information for parks, attractions, shows, and restaurants
  name: Entity Metadata
- description: Real-time OPERATING, DOWN, CLOSED, and REFURBISHMENT status for all entities
  name: Live Operational Status
- description: Historical and future operating schedules by specific month and year
  name: Monthly Schedule Lookup
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Community integrations for theme park data displays
  name: EmulationStation/RetroPie
- description: Smart home integrations for displaying live park data on dashboards
  name: Home Assistant
- description: Media center plugin integrations for theme park information
  name: Kodi
jsonld:
- class_count: 12
  name: Themeparks Wiki Context
  property_count: 32
  slug: themeparks-wiki-context
layout: provider
modified: '2026-05-03'
name: ThemeParks.wiki
rules:
- name: ThemeParks.wiki API Rules
  rule_count: 22
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 11
  slug: themeparks-wiki-spectral-rules
skills: []
slug: themeparks-wiki
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: themeparks-wiki\nname: ThemeParks.wiki\ndescription: An ever-growing database of real-time data for the world's best theme parks, including wait times, schedules, and park information.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Entertainment\n  - Real-Time\n  - Theme Parks\n  - Wait Times\n  - Travel\ncreated: '2025-02-24'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/themeparks-wiki/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: themeparks-wiki:themeparks-wiki\n    name: ThemeParks.wiki API\n    description: >-\n      An ever-growing database of real-time data for the world's best theme\n      parks, including wait times, schedules, and park information. Provides\n      live wait times, operational status, park schedules, and entity metadata\n      for 75+ destinations worldwide including Disney, Universal,\
  \ Cedar Fair,\n      and Six Flags. No authentication required.\n    humanURL: https://themeparks.wiki/\n    baseURL: https://api.themeparks.wiki/v1\n    tags:\n      - Entertainment\n      - Real-Time\n      - Theme Parks\n      - Wait Times\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://api.themeparks.wiki/docs/v1/\n      - type: OpenAPI\n        url: openapi/themeparks-wiki-openapi.yml\n      - type: JSONSchema\n        url: json-schema/themeparks-wiki-destination-schema.json\n        title: Destination Schema\n      - type: JSONStructure\n        url: json-structure/themeparks-wiki-destination-structure.json\n        title: Destination Structure\n      - type: JSON-LD\n        url: json-ld/themeparks-wiki-context.jsonld\n        title: ThemeParks.wiki JSON-LD Context\ncommon:\n  - type: Website\n    url: https://themeparks.wiki/\n  - type: Documentation\n    url: https://api.themeparks.wiki/docs/v1/\n  - type: GitHub Organization\n    url: https://github.com/ThemeParks\n\
  \  - type: SpectralRules\n    url: rules/themeparks-wiki-spectral-rules.yml\n    title: ThemeParks.wiki Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/themeparks-wiki-vocabulary.yml\n    title: ThemeParks.wiki Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/theme-park-planning.yaml\n    title: Theme Park Planning\n  - type: Authentication\n    data:\n      - name: No Authentication Required\n        description: ThemeParks.wiki API is publicly accessible with no API key or authentication required\n  - type: Features\n    data:\n      - name: Real-Time Wait Times\n        description: Live queue wait times and operational status for attractions at 75+ destinations\n      - name: Park Schedules\n        description: Operating hours, special event schedules, and monthly calendar views for parks\n      - name: Destination Catalog\n        description: Complete listing of all supported theme park resort destinations worldwide\n      - name: Entity Metadata\n      \
  \  description: Detailed information for parks, attractions, shows, and restaurants\n      - name: Live Operational Status\n        description: Real-time OPERATING, DOWN, CLOSED, and REFURBISHMENT status for all entities\n      - name: Monthly Schedule Lookup\n        description: Historical and future operating schedules by specific month and year\n  - type: UseCases\n    data:\n      - name: Trip Planning\n        description: Research park schedules and wait time patterns before visiting\n      - name: Real-Time Monitoring\n        description: Monitor live wait times and attraction availability during a park visit\n      - name: Media Centers\n        description: Power home media center displays with live park data and wait times\n      - name: AI Park Assistant\n        description: Power AI agents that help users plan and navigate theme park visits\n  - type: Integrations\n    data:\n      - name: EmulationStation/RetroPie\n        description: Community integrations for theme\
  \ park data displays\n      - name: Home Assistant\n        description: Smart home integrations for displaying live park data on dashboards\n      - name: Kodi\n        description: Media center plugin integrations for theme park information\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/themeparks-wiki/refs/heads/main/apis.yml
tags:
- Entertainment
- Real-Time
- Theme Parks
- Wait Times
- Travel
url: https://raw.githubusercontent.com/api-evangelist/themeparks-wiki/refs/heads/main/apis.yml
use_cases:
- description: Research park schedules and wait time patterns before visiting
  name: Trip Planning
- description: Monitor live wait times and attraction availability during a park visit
  name: Real-Time Monitoring
- description: Power home media center displays with live park data and wait times
  name: Media Centers
- description: Power AI agents that help users plan and navigate theme park visits
  name: AI Park Assistant
---
