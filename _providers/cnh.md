---
api_count: 2
api_specs:
- filename: cnh-fieldops-openapi.yml
  format: yaml
  label: CNH FieldOps API
  slug: cnh-fieldops-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/openapi/cnh-fieldops-openapi.yml
apis:
- description: The CNH FieldOps API replaces the previously available CNH Ag Data and CONNECT Machine Data APIs and provides a unified, OAuth 2.0 secured REST API for both agronomic machinery and construction equipm
  name: CNH FieldOps API
  slug: cnh-fieldops-api
- description: The CNH Developer Portal at develop.cnh.com hosts onboarding, authentication guidance, API guides, Postman collections, and curated SwaggerHub documentation for FieldOps and related CNH APIs. Develope
  name: CNH Developer Portal
  slug: cnh-developer-portal
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cnhindustrial.com/
- title: ''
  type: Portal
  url: https://develop.cnh.com/
- title: ''
  type: GettingStarted
  url: https://develop.cnh.com/get-started
- title: ''
  type: Documentation
  url: https://develop.cnh.com/api-guides
- title: ''
  type: OpenAPI
  url: openapi/cnh-fieldops-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/cnh-equipment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cnh-telemetry-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/cnh-context.jsonld
- title: ''
  type: SpectralRuleset
  url: rules/cnh-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/cnh-fieldops-capabilities.yml
- title: ''
  type: PrivacyPolicy
  url: https://www.cnhindustrial.com/en-us/privacy/pages/default.aspx
created: '2025-03-01'
description: CNH Industrial is a global leader in the manufacturing and distribution of agricultural and construction equipment, with brands including Case IH, New Holland, STEYR, Case CE, and New Holland Construction. Through develop.cnh.com CNH operates a developer portal that exposes the FieldOps API - a unified, ISO 15143-3 compliant REST API for vehicle telemetry, equipment management, farm/grower hierarchy, operations, prescription Rx delivery, and webhook subscriptions across both agronomic machinery and construction equipment.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 31
  name: Cnh Context
  property_count: 0
  slug: cnh-context
layout: provider
modified: '2026-04-23'
name: CNH
rules:
- name: CNH API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 4
  slug: cnh-rules
skills: []
slug: cnh
solutions: []
source_filename: apis.yml
source_yaml: "aid: cnh\nurl: https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/apis.yml\nname: CNH\nx-type: company\ntags:\n  - Agriculture\n  - Construction\n  - Telematics\n  - Equipment\n  - FieldOps\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ndescription: >-\n  CNH Industrial is a global leader in the manufacturing and distribution of\n  agricultural and construction equipment, with brands including Case IH, New\n  Holland, STEYR, Case CE, and New Holland Construction. Through develop.cnh.com\n  CNH operates a developer portal that exposes the FieldOps API - a unified,\n  ISO 15143-3 compliant REST API for vehicle telemetry, equipment management,\n  farm/grower hierarchy, operations, prescription Rx delivery, and webhook\n  subscriptions across both agronomic machinery and construction equipment.\napis:\n  - aid: cnh:cnh-fieldops-api\n\
  \    name: CNH FieldOps API\n    tags:\n      - Agriculture\n      - Construction\n      - ISO 15143-3\n      - OAuth2\n      - Telemetry\n      - Vehicles\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://develop.cnh.com/api-guides/fieldops-api\n    baseURL: https://api.fieldops.cnh.com\n    properties:\n      - url: https://develop.cnh.com/get-started\n        type: GettingStarted\n      - url: https://develop.cnh.com/api-guides\n        type: Documentation\n      - url: https://develop.cnh.com/api-guides/fieldops-api\n        type: Reference\n      - url: https://develop.cnh.com/api-guides/fieldops-api/vehicle-telemetry\n        type: Reference\n      - url: openapi/cnh-fieldops-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cnh-equipment-schema.json\n        type: JSONSchema\n      - url: json-schema/cnh-telemetry-schema.json\n        type: JSONSchema\n      - url: json-ld/cnh-context.jsonld\n        type: JSONLDContext\n\
  \      - url: rules/cnh-rules.yml\n        type: SpectralRuleset\n      - url: capabilities/cnh-fieldops-capabilities.yml\n        type: NaftikoCapabilities\n    description: >-\n      The CNH FieldOps API replaces the previously available CNH Ag Data and\n      CONNECT Machine Data APIs and provides a unified, OAuth 2.0 secured REST\n      API for both agronomic machinery and construction equipment connected to\n      a FieldOps account. Vehicle telemetry follows the ISO 15143-3\n      specification with two profiles - CP (CAN Parameter, default) and MH\n      (Machine Health) - and supports time-series data such as locations,\n      operating hours, idle hours, fuel and DEF remaining, peak speed, distance,\n      fault codes, and engine condition. Additional endpoint groups cover\n      Equipment, Operations By Vehicle, Prescriptions (send Rx files),\n      Farm Setup (Grower / Farm / Field / Boundary), Files, and Webhooks.\n    x-features:\n      - name: ISO 15143-3 Telemetry\n    \
  \    description: Standards-based vehicle telemetry across CNH brands and equipment classes.\n      - name: CP and MH Profiles\n        description: CAN Parameter (default) and Machine Health telemetry profiles.\n      - name: Fault Codes\n        description: Fault, caution, and engine-condition codes per vehicle.\n      - name: Aggregated Metrics\n        description: Daily metrics including operating hours, idle hours, fuel ratio, distance, and peak speed.\n      - name: Prescription Rx Delivery\n        description: Push prescription files directly to a vehicle or FieldOps field.\n      - name: Farm Hierarchy\n        description: Grower / Farm / Field / Boundary management.\n      - name: Operations by Vehicle\n        description: Recorded field operations per vehicle.\n      - name: Webhooks\n        description: Subscribe to FieldOps event notifications.\n      - name: OAuth 2.0\n        description: Refresh and access token authentication via develop.cnh.com.\n    x-useCases:\n\
  \      - name: Fleet Telematics\n        description: Power third-party fleet-management systems with CNH equipment telemetry.\n      - name: Predictive Maintenance\n        description: Use Machine Health telemetry and fault codes to anticipate maintenance.\n      - name: Precision Agriculture\n        description: Push prescription Rx files into the workflow for variable-rate application.\n      - name: Farm Management Systems\n        description: Hydrate FMS dashboards with grower / farm / field hierarchies and operations.\n      - name: Construction Equipment Tracking\n        description: Track Case CE and New Holland Construction equipment via standardized ISO telematics.\n  - aid: cnh:cnh-developer-portal\n    name: CNH Developer Portal\n    tags:\n      - Developer Portal\n      - Documentation\n      - OAuth2\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://develop.cnh.com/\n    properties:\n      - url: https://develop.cnh.com/\n\
  \        type: Portal\n      - url: https://develop.cnh.com/get-started\n        type: GettingStarted\n    description: >-\n      The CNH Developer Portal at develop.cnh.com hosts onboarding,\n      authentication guidance, API guides, Postman collections, and curated\n      SwaggerHub documentation for FieldOps and related CNH APIs. Developers\n      register for credentials, obtain refresh tokens, and progress from sandbox\n      to live data through the portal.\ncommon:\n  - url: https://www.cnhindustrial.com/\n    type: Website\n  - url: https://develop.cnh.com/\n    type: Portal\n  - url: https://develop.cnh.com/get-started\n    type: GettingStarted\n  - url: https://develop.cnh.com/api-guides\n    type: Documentation\n  - url: openapi/cnh-fieldops-openapi.yml\n    type: OpenAPI\n  - url: json-schema/cnh-equipment-schema.json\n    type: JSONSchema\n  - url: json-schema/cnh-telemetry-schema.json\n    type: JSONSchema\n  - url: json-ld/cnh-context.jsonld\n    type: JSONLDContext\n \
  \ - url: rules/cnh-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/cnh-fieldops-capabilities.yml\n    type: NaftikoCapabilities\n  - url: https://www.cnhindustrial.com/en-us/privacy/pages/default.aspx\n    type: PrivacyPolicy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/apis.yml
tags:
- Agriculture
- Construction
- Telematics
- Equipment
- FieldOps
url: https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/apis.yml
use_cases: []
---
