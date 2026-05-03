---
api_count: 1
api_specs:
- filename: samsara-openapi.yml
  format: yaml
  label: Samsara API
  slug: samsara
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/samsara/refs/heads/main/openapi/samsara-openapi.yml
apis:
- description: The Samsara REST API provides comprehensive access to fleet and industrial IoT data including vehicles, drivers, assets, routes, compliance (ELD/HOS), safety events, sensor readings, DVIR inspections,
  name: Samsara API
  slug: samsara
capabilities:
- description: Unified fleet operations capability composing Samsara vehicle, driver, route, address, tag, and asset management APIs into a single workflow surface for fleet managers and dispatchers. Supports full f
  name: Samsara Fleet Operations
  slug: fleet-operations
- description: Safety and compliance workflow combining Samsara safety events, driver coaching, Hours of Service (HOS/ELD) compliance logs, DVIR inspections, and maintenance tracking. Designed for safety managers an
  name: Samsara Safety and Compliance
  slug: safety-compliance
common:
- title: Samsara Developer Portal
  type: Documentation
  url: https://developers.samsara.com/
- title: Getting Started Guide
  type: Documentation
  url: https://developers.samsara.com/docs/getting-started
- title: Samsara GitHub Organization
  type: GitHubOrganization
  url: https://github.com/samsarahq
- title: API Authentication
  type: Authentication
  url: https://developers.samsara.com/docs/authentication
- title: Samsara API Spectral Rules
  type: SpectralRules
  url: rules/samsara-rules.yml
- title: Samsara Fleet Operations Capability
  type: NaftikoCapability
  url: capabilities/fleet-operations.yaml
- title: Samsara Safety and Compliance Capability
  type: NaftikoCapability
  url: capabilities/safety-compliance.yaml
- title: Samsara Vehicle Schema
  type: JSONSchema
  url: json-schema/samsara-vehicle-schema.json
- title: Samsara Driver Schema
  type: JSONSchema
  url: json-schema/samsara-driver-schema.json
- title: Samsara Safety Event Schema
  type: JSONSchema
  url: json-schema/samsara-safety-event-schema.json
- title: Samsara Vehicle Structure
  type: JSONStructure
  url: json-structure/samsara-vehicle-structure.json
- title: Samsara Driver Structure
  type: JSONStructure
  url: json-structure/samsara-driver-structure.json
- title: Samsara JSON-LD Context
  type: JSONLDContext
  url: json-ld/samsara-context.jsonld
- title: Samsara List Vehicles Example
  type: Example
  url: examples/samsara-list-vehicles-example.json
- title: Samsara List Safety Events Example
  type: Example
  url: examples/samsara-list-safety-events-example.json
- title: Samsara Vocabulary
  type: Vocabulary
  url: vocabulary/samsara-vocabulary.yml
created: '2024-11-07'
description: 'Samsara is a leading connected operations platform for physical operations industries including transportation, logistics, construction, field services, and energy. The Samsara REST API provides programmatic access to fleet telematics, driver safety, compliance (ELD/HOS), vehicle diagnostics, route management, industrial IoT sensors, and workforce management. With over two million connected devices, the platform offers real-time GPS tracking, AI-powered safety cameras, digital inspection forms (DVIRs), IFTA reporting, and data streaming via webhooks and Kafka. Base URL: https://api.samsara.com. Authentication uses Bearer tokens with OAuth 2.0 support.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 44
  name: Samsara Context
  property_count: 4
  slug: samsara-context
layout: provider
modified: '2026-05-02'
name: Samsara
rules:
- name: Samsara API Rules
  rule_count: 9
  severity_counts:
    error: 1
    hint: 0
    info: 4
    warn: 4
  slug: samsara-rules
skills: []
slug: samsara
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: samsara\nname: Samsara\ndescription: >-\n  Samsara is a leading connected operations platform for physical operations industries\n  including transportation, logistics, construction, field services, and energy.\n  The Samsara REST API provides programmatic access to fleet telematics, driver safety,\n  compliance (ELD/HOS), vehicle diagnostics, route management, industrial IoT sensors,\n  and workforce management. With over two million connected devices, the platform\n  offers real-time GPS tracking, AI-powered safety cameras, digital inspection forms\n  (DVIRs), IFTA reporting, and data streaming via webhooks and Kafka. Base URL:\n  https://api.samsara.com. Authentication uses Bearer tokens with OAuth 2.0 support.\nurl: https://www.samsara.com/\ntags:\n  - Asset Tracking\n  - Connected Operations\n  - ELD\n  - Fleet Management\n  - GPS Tracking\n  - IoT\n  - Logistics\n  - Safety\n  - Telematics\n  - Transportation\ntype: Index\nposition: Consuming\naccess: 3rd-Party\n\
  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2024-11-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: samsara:samsara\n    name: Samsara API\n    description: >-\n      The Samsara REST API provides comprehensive access to fleet and industrial\n      IoT data including vehicles, drivers, assets, routes, compliance (ELD/HOS),\n      safety events, sensor readings, DVIR inspections, documents, forms,\n      addresses, tags, users, and messaging. Supports real-time data, historical\n      queries, webhooks, and Kafka data streaming.\n    humanURL: https://developers.samsara.com/\n    baseURL: https://api.samsara.com\n    tags:\n      - Addresses\n      - Assets\n      - Compliance\n      - Documents\n      - Drivers\n      - DVIR\n      - ELD\n      - Fleet\n      - Forms\n      - Hours Of Service\n      - IoT\n      - Routes\n      - Safety\n      - Sensors\n      - Tags\n      - Telematics\n      - Users\n      - Vehicles\n\
  \      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.samsara.com/docs/rest-api-overview\n      - type: OpenAPI\n        url: openapi/samsara-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/samsarahq/api-docs\n      - type: PythonSDK\n        url: https://github.com/samsarahq/samsara-python\n      - type: JavaScriptSDK\n        url: https://github.com/samsarahq/samsara-js\n      - type: SDKDocumentation\n        url: https://developers.samsara.com/docs/sdks\ncommon:\n  - type: Documentation\n    url: https://developers.samsara.com/\n    title: Samsara Developer Portal\n  - type: Documentation\n    url: https://developers.samsara.com/docs/getting-started\n    title: Getting Started Guide\n  - type: GitHubOrganization\n    url: https://github.com/samsarahq\n    title: Samsara GitHub Organization\n  - type: Authentication\n    url: https://developers.samsara.com/docs/authentication\n    title: API Authentication\n  -\
  \ type: SpectralRules\n    url: rules/samsara-rules.yml\n    title: Samsara API Spectral Rules\n  - type: NaftikoCapability\n    url: capabilities/fleet-operations.yaml\n    title: Samsara Fleet Operations Capability\n  - type: NaftikoCapability\n    url: capabilities/safety-compliance.yaml\n    title: Samsara Safety and Compliance Capability\n  - type: JSONSchema\n    url: json-schema/samsara-vehicle-schema.json\n    title: Samsara Vehicle Schema\n  - type: JSONSchema\n    url: json-schema/samsara-driver-schema.json\n    title: Samsara Driver Schema\n  - type: JSONSchema\n    url: json-schema/samsara-safety-event-schema.json\n    title: Samsara Safety Event Schema\n  - type: JSONStructure\n    url: json-structure/samsara-vehicle-structure.json\n    title: Samsara Vehicle Structure\n  - type: JSONStructure\n    url: json-structure/samsara-driver-structure.json\n    title: Samsara Driver Structure\n  - type: JSONLDContext\n    url: json-ld/samsara-context.jsonld\n    title: Samsara JSON-LD\
  \ Context\n  - type: Example\n    url: examples/samsara-list-vehicles-example.json\n    title: Samsara List Vehicles Example\n  - type: Example\n    url: examples/samsara-list-safety-events-example.json\n    title: Samsara List Safety Events Example\n  - type: Vocabulary\n    url: vocabulary/samsara-vocabulary.yml\n    title: Samsara Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/samsara/refs/heads/main/apis.yml
tags:
- Asset Tracking
- Connected Operations
- ELD
- Fleet Management
- GPS Tracking
- IoT
- Logistics
- Safety
- Telematics
- Transportation
url: https://www.samsara.com/
use_cases: []
---
