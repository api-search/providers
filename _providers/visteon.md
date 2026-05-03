---
api_count: 2
api_specs:
- filename: visteon-phoenix-openapi.yml
  format: yaml
  label: Visteon Phoenix API
  slug: phoenix-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visteon/refs/heads/main/openapi/visteon-phoenix-openapi.yml
apis:
- description: 'The Phoenix API is an automotive-oriented JavaScript interface for building HTML5 applications on Visteon''s Phoenix infotainment platform. The API provides access to vehicle cockpit domains including '
  name: Visteon Phoenix API
  slug: phoenix-api
- description: The Phoenix Software Development Kit provides development tools for building automotive infotainment applications targeting Visteon hardware. Phoenix Studio 2.0 is a PC-based IDE that enables app deve
  name: Visteon Phoenix SDK
  slug: phoenix-sdk
capabilities:
- description: Workflow capability for automotive connected cockpit applications built on the Visteon Phoenix platform. Combines audio, phone, media, navigation, vehicle data, and screen management APIs into a unifi
  name: Visteon Connected Cockpit
  slug: connected-cockpit
common:
- title: ''
  type: Website
  url: https://www.visteon.com
- title: ''
  type: Developer Portal
  url: https://developer.visteon.com/phoenix/
- title: ''
  type: OpenAPI
  url: openapi/visteon-phoenix-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/visteon-vehicle-data-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/visteon-audio-schema.json
- title: ''
  type: JSONLD
  url: json-ld/visteon-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/visteon-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/visteon-rules.yml
created: '2026-03-24'
description: Visteon Corporation is a global automotive electronics supplier providing innovative cockpit electronics products and connected car solutions to vehicle manufacturers worldwide. The Visteon Phoenix platform offers a JavaScript API for building HTML5-based automotive infotainment applications covering audio control, phone integration, media playback, navigation, screen management, remote UI, and vehicle data access. Phoenix Studio enables third-party app development targeting Visteon's SmartCore and display audio infotainment systems.
features: []
image: https://www.visteon.com/wp-content/themes/visteon/images/visteon-logo.png
integrations: []
jsonld:
- class_count: 39
  name: Visteon Context
  property_count: 2
  slug: visteon-context
layout: provider
modified: '2026-05-03'
name: Visteon
rules:
- name: Visteon API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 2
    info: 0
    warn: 5
  slug: visteon-rules
skills: []
slug: visteon
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: visteon\nname: Visteon\ndescription: >-\n  Visteon Corporation is a global automotive electronics supplier providing innovative\n  cockpit electronics products and connected car solutions to vehicle manufacturers\n  worldwide. The Visteon Phoenix platform offers a JavaScript API for building HTML5-based\n  automotive infotainment applications covering audio control, phone integration, media\n  playback, navigation, screen management, remote UI, and vehicle data access. Phoenix\n  Studio enables third-party app development targeting Visteon's SmartCore and display\n  audio infotainment systems.\nimage: https://www.visteon.com/wp-content/themes/visteon/images/visteon-logo.png\ntype: Index\ntags:\n  - Automotive\n  - Connected Car\n  - Infotainment\n  - IoT\nurl: https://raw.githubusercontent.com/api-evangelist/visteon/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: visteon:phoenix-api\n    name: Visteon\
  \ Phoenix API\n    description: >-\n      The Phoenix API is an automotive-oriented JavaScript interface for building HTML5\n      applications on Visteon's Phoenix infotainment platform. The API provides access\n      to vehicle cockpit domains including audio playback and volume control, phone call\n      management, media library browsing, navigation routing, screen and display management,\n      remote UI rendering, and vehicle data such as speed, fuel level, and HVAC status.\n      Applications written with the Phoenix API can run across multiple Visteon infotainment\n      hardware platforms including SmartCore and display audio units.\n    humanURL: https://developer.visteon.com/phoenix/api.html\n    baseURL: https://developer.visteon.com/phoenix\n    tags:\n      - Audio\n      - Automotive\n      - Connected Car\n      - HMI\n      - HTML5\n      - Infotainment\n      - JavaScript\n      - Navigation\n      - Vehicle Data\n    properties:\n      - type: Documentation\n       \
  \ url: https://developer.visteon.com/phoenix/api.html\n      - type: SDK\n        url: https://developer.visteon.com/phoenix/sdk.html\n      - type: Developer Portal\n        url: https://developer.visteon.com/phoenix/\n      - type: OpenAPI\n        url: openapi/visteon-phoenix-openapi.yml\n    contact:\n      - FN: Visteon Developer Network\n        url: https://developer.visteon.com/phoenix/\n  - aid: visteon:phoenix-sdk\n    name: Visteon Phoenix SDK\n    description: >-\n      The Phoenix Software Development Kit provides development tools for building\n      automotive infotainment applications targeting Visteon hardware. Phoenix Studio 2.0\n      is a PC-based IDE that enables app development with hardware simulation, device\n      emulation, and the Phoenix API reference integrated into the development environment.\n      Apps can be developed once and deployed to any supported Visteon infotainment platform.\n    humanURL: https://developer.visteon.com/phoenix/sdk.html\n    baseURL:\
  \ https://developer.visteon.com/phoenix\n    tags:\n      - Automotive\n      - Development Tools\n      - HTML5\n      - Infotainment\n      - JavaScript\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://developer.visteon.com/phoenix/sdk.html\n      - type: Getting Started\n        url: https://developer.visteon.com/phoenix/\n    contact:\n      - FN: Visteon Developer Network\n        url: https://developer.visteon.com/phoenix/\ncommon:\n  - type: Website\n    url: https://www.visteon.com\n  - type: Developer Portal\n    url: https://developer.visteon.com/phoenix/\n  - type: OpenAPI\n    url: openapi/visteon-phoenix-openapi.yml\n  - type: JSONSchema\n    url: json-schema/visteon-vehicle-data-schema.json\n  - type: JSONSchema\n    url: json-schema/visteon-audio-schema.json\n  - type: JSONLD\n    url: json-ld/visteon-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/visteon-vocabulary.yml\n  - type: SpectralRules\n    url: rules/visteon-rules.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visteon/refs/heads/main/apis.yml
tags:
- Automotive
- Connected Car
- Infotainment
- IoT
url: https://raw.githubusercontent.com/api-evangelist/visteon/refs/heads/main/apis.yml
use_cases: []
---
