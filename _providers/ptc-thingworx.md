---
api_count: 3
api_specs:
- filename: ptc-thingworx-rest-openapi.yml
  format: yaml
  label: PTC ThingWorx REST API
  slug: thingworx-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/openapi/ptc-thingworx-rest-openapi.yml
- filename: ptc-thingworx-websocket-asyncapi.yml
  format: yaml
  label: PTC ThingWorx WebSocket/AlwaysOn API
  slug: thingworx-websocket-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/asyncapi/ptc-thingworx-websocket-asyncapi.yml
apis:
- description: PTC ThingWorx REST API provides programmatic access to the ThingWorx IoT platform including thing management, property read/write, service execution, event subscription, and mashup data APIs using App
  name: PTC ThingWorx REST API
  slug: thingworx-rest-api
- description: PTC ThingWorx AlwaysOn WebSocket API enables persistent bidirectional connections for industrial edge devices and remote assets, supporting real-time telemetry streaming, command and control, and devi
  name: PTC ThingWorx WebSocket/AlwaysOn API
  slug: thingworx-websocket-api
- description: PTC Windchill REST API provides product lifecycle management and PDM access for CAD data management, bill of materials, change management, workflow automation, and product lifecycle workflows in manuf
  name: PTC Windchill REST API
  slug: windchill-rest-api
asyncapis:
- description: PTC ThingWorx AlwaysOn WebSocket API enables persistent bidirectional connections for industrial edge devices and remote assets. Supports real-time telemetry streaming, command and control, event noti
  name: PTC ThingWorx AlwaysOn WebSocket API
  slug: ptc-thingworx-websocket-asyncapi
common:
- title: ''
  type: Portal
  url: https://docs.ptc.com/
- title: ''
  type: Documentation
  url: https://docs.ptc.com/
- title: ''
  type: Website
  url: https://www.ptc.com/en/technologies/iiot/thingworx-platform
- title: ''
  type: PrivacyPolicy
  url: https://www.ptc.com/en/privacy-policy
- title: ''
  type: GitHubOrganization
  url: https://github.com/ptc-iot-sharing
- title: ''
  type: OpenAPI
  url: openapi/ptc-thingworx-rest-openapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/ptc-thingworx-websocket-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/ptc-thingworx-thing-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/ptc-thingworx-context.jsonld
created: ''
description: PTC ThingWorx is an industrial Internet of Things platform that enables companies to rapidly develop and deploy smart, connected solutions for industrial environments.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Ptc Thingworx Context
  property_count: 27
  slug: ptc-thingworx-context
layout: provider
modified: '2026-04-28'
name: ptc-thingworx
skills: []
slug: ptc-thingworx
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ptc-thingworx\nurl: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/apis.yml\napis:\n  - aid: ptc-thingworx:thingworx-rest-api\n    name: PTC ThingWorx REST API\n    tags:\n      - Digital Twin\n      - IoT\n      - Manufacturing\n      - REST\n    image: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/image.png\n    humanURL: https://docs.ptc.com/r/en-US/ThingWorx-Help/ThingWorx/Help/Composer/Security/ApplicationKeys/ApplicationKeys\n    baseURL: https://api.thingworx.example.com/Thingworx\n    properties:\n      - url: https://docs.ptc.com/\n        type: Documentation\n      - url: https://docs.ptc.com/\n        type: Reference\n      - url: openapi/ptc-thingworx-rest-openapi.yml\n        type: OpenAPI\n    description: >-\n      PTC ThingWorx REST API provides programmatic access to the ThingWorx IoT platform\n      including thing management, property read/write, service execution, event subscription,\n\
  \      and mashup data APIs using Application Key or OAuth authentication.\n\n  - aid: ptc-thingworx:thingworx-websocket-api\n    name: PTC ThingWorx WebSocket/AlwaysOn API\n    tags:\n      - IoT\n      - Manufacturing\n      - Real-Time\n      - WebSocket\n    image: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/image.png\n    humanURL: https://docs.ptc.com/\n    baseURL: https://api.thingworx.example.com\n    properties:\n      - url: https://docs.ptc.com/\n        type: Documentation\n      - url: asyncapi/ptc-thingworx-websocket-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      PTC ThingWorx AlwaysOn WebSocket API enables persistent bidirectional connections\n      for industrial edge devices and remote assets, supporting real-time telemetry\n      streaming, command and control, and device lifecycle management.\n\n  - aid: ptc-thingworx:windchill-rest-api\n    name: PTC Windchill REST API\n    tags:\n      - CAD\n      - Manufacturing\n\
  \      - PDM\n      - PLM\n      - REST\n    image: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/image.png\n    humanURL: https://docs.ptc.com/\n    baseURL: https://api.windchill.example.com\n    properties:\n      - url: https://docs.ptc.com/\n        type: Documentation\n    description: >-\n      PTC Windchill REST API provides product lifecycle management and PDM access\n      for CAD data management, bill of materials, change management, workflow automation,\n      and product lifecycle workflows in manufacturing environments.\n\ncommon:\n  - url: https://docs.ptc.com/\n    type: Portal\n  - url: https://docs.ptc.com/\n    type: Documentation\n  - url: https://www.ptc.com/en/technologies/iiot/thingworx-platform\n    type: Website\n  - url: https://www.ptc.com/en/privacy-policy\n    type: PrivacyPolicy\n  - url: https://github.com/ptc-iot-sharing\n    type: GitHubOrganization\n  - url: openapi/ptc-thingworx-rest-openapi.yml\n    type: OpenAPI\n  -\
  \ url: asyncapi/ptc-thingworx-websocket-asyncapi.yml\n    type: AsyncAPI\n  - url: json-schema/ptc-thingworx-thing-schema.json\n    type: JSONSchema\n  - url: json-ld/ptc-thingworx-context.jsonld\n    type: JSONLDContext\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\nmodified: '2026-04-28'\ndescription: >-\n  PTC ThingWorx is an industrial Internet of Things platform that enables companies\n  to rapidly develop and deploy smart, connected solutions for industrial environments.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/apis.yml
use_cases: []
---
