---
api_count: 1
api_specs:
- filename: steelcase-roomwizard-api-openapi.yml
  format: yaml
  label: Steelcase RoomWizard API
  slug: roomwizard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/openapi/steelcase-roomwizard-api-openapi.yml
apis:
- description: The Steelcase RoomWizard API provides programmatic access to conference room scheduling and reservation management. Using HTTP GET and POST requests, developers can retrieve room bookings, create rese
  name: Steelcase RoomWizard API
  slug: roomwizard-api
capabilities:
- description: Room scheduling workflow capability using the Steelcase RoomWizard API to manage conference room reservations, check availability, and synchronize bookings with enterprise calendaring systems. Enables
  name: Steelcase Room Scheduling
  slug: room-scheduling
common:
- title: ''
  type: Website
  url: https://www.steelcase.com
- title: ''
  type: TechSupport
  url: https://www.steelcase.com/techsupport/
- title: ''
  type: Downloads
  url: https://www.steelcase.com/techsupport/downloads/
- title: ''
  type: JSONSchema
  url: json-schema/steelcase-booking-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/steelcase-room-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/steelcase-booking-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/steelcase-room-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/steelcase-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/steelcase-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/room-scheduling.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/steelcase-vocabulary.yml
created: '2025-03-01'
description: Steelcase is a global leader in the office furniture and workplace design industry, providing furniture, technology, and research-based insights to help organizations create effective work environments. Steelcase offers the RoomWizard API for integrating room scheduling and conference room reservation systems with enterprise calendaring platforms. The API enables developers to manage room bookings, retrieve availability, and synchronize reservations with Microsoft Exchange, Office 365, and Google Calendar.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 28
  name: Steelcase Context
  property_count: 0
  slug: steelcase-context
layout: provider
modified: '2026-05-02'
name: Steelcase
rules:
- name: Steelcase API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: steelcase-rules
skills: []
slug: steelcase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: steelcase\nname: Steelcase\ndescription: >-\n  Steelcase is a global leader in the office furniture and workplace design\n  industry, providing furniture, technology, and research-based insights to\n  help organizations create effective work environments. Steelcase offers the\n  RoomWizard API for integrating room scheduling and conference room\n  reservation systems with enterprise calendaring platforms. The API enables\n  developers to manage room bookings, retrieve availability, and synchronize\n  reservations with Microsoft Exchange, Office 365, and Google Calendar.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Office Furniture\n  - Workplace\n  - Room Scheduling\n  - Facilities Management\n  - IoT\n  - Smart Office\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: steelcase:roomwizard-api\n    name: Steelcase RoomWizard API\n    description: >-\n      The Steelcase RoomWizard API provides programmatic access to conference\n      room scheduling and reservation management. Using HTTP GET and POST\n      requests, developers can retrieve room bookings, create reservations,\n      check room availability, and synchronize with enterprise calendaring\n      systems including Microsoft Exchange, Office 365, and Google Calendar.\n      The API returns XML-structured responses and supports webhook-style\n      synchronization for keeping room status current.\n    humanURL: https://www.steelcase.com/products/scheduling-systems/roomwizard/\n    baseURL: https://roomwizard.local/api\n    tags:\n      - Room Scheduling\n      - Conference Rooms\n      - Calendaring\n      - Facilities Management\n      - Workplace\n    properties:\n      - type: Documentation\n        url: https://www.steelcase.com/techsupport/types/spec-guide/\n \
  \     - type: OpenAPI\n        url: openapi/steelcase-roomwizard-api-openapi.yml\n    contact:\n      - FN: Steelcase Tech Support\n        url: https://www.steelcase.com/techsupport/\ncommon:\n  - type: Website\n    url: https://www.steelcase.com\n  - type: TechSupport\n    url: https://www.steelcase.com/techsupport/\n  - type: Downloads\n    url: https://www.steelcase.com/techsupport/downloads/\n  - type: JSONSchema\n    url: json-schema/steelcase-booking-schema.json\n  - type: JSONSchema\n    url: json-schema/steelcase-room-schema.json\n  - type: JSONStructure\n    url: json-structure/steelcase-booking-structure.json\n  - type: JSONStructure\n    url: json-structure/steelcase-room-structure.json\n  - type: JSON-LD\n    url: json-ld/steelcase-context.jsonld\n  - type: SpectralRules\n    url: rules/steelcase-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/room-scheduling.yaml\n  - type: Vocabulary\n    url: vocabulary/steelcase-vocabulary.yml\nmaintainers:\n  - FN: Kin\
  \ Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/apis.yml
tags:
- Office Furniture
- Workplace
- Room Scheduling
- Facilities Management
- IoT
- Smart Office
url: https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/apis.yml
use_cases: []
---
