---
api_count: 1
api_specs:
- filename: waste-management-customer-api-openapi.yml
  format: yaml
  label: Waste Management Customer API
  slug: waste-management-customer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/waste-management/refs/heads/main/openapi/waste-management-customer-api-openapi.yml
apis:
- description: The Waste Management Customer API provides RESTful access to customer account data including balance, contract details, invoice history, service details, pickup schedules, and ETA information. Uses JW
  name: Waste Management Customer API
  slug: waste-management-customer-api
capabilities:
- description: 'Unified customer service capability for Waste Management accounts. Combines account management, service scheduling, ETA tracking, and billing operations to support residential and commercial customer '
  name: Waste Management Customer Service
  slug: customer-service
common:
- title: ''
  type: Website
  url: https://www.wm.com
- title: ''
  type: Portal
  url: https://api.wm.com/
- title: ''
  type: OpenAPI
  url: openapi/waste-management-customer-api-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/waste-management-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/waste-management-service-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/waste-management-invoice-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/waste-management-service-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/waste-management-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/waste-management-vocabulary.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/customer-service.yaml
created: '2026-05-03'
description: Waste Management (WM) is the largest environmental services company in North America, providing waste collection, transfer, disposal, and recycling services to over 20 million residential, commercial, industrial, and municipal customers across the United States. WM provides RESTful APIs for customers and third-party integrators to access account data including balance, services, invoices, pickup schedules, and ETAs via JWT authentication.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Waste Management Context
  property_count: 21
  slug: waste-management-context
layout: provider
modified: '2026-05-03'
name: Waste Management
rules:
- name: Waste Management API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 0
    warning: 3
  slug: waste-management-rules
skills: []
slug: waste-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: waste-management\nname: Waste Management\ndescription: >-\n  Waste Management (WM) is the largest environmental services company in North\n  America, providing waste collection, transfer, disposal, and recycling services\n  to over 20 million residential, commercial, industrial, and municipal customers\n  across the United States. WM provides RESTful APIs for customers and third-party\n  integrators to access account data including balance, services, invoices, pickup\n  schedules, and ETAs via JWT authentication.\nurl: https://www.wm.com\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Environmental Services\n  - Fortune 500\n  - Recycling\n  - Solid Waste\n  - Sustainability\n  - Waste Management\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: waste-management:waste-management-customer-api\n    name: Waste Management Customer API\n    description: >-\n      The Waste\
  \ Management Customer API provides RESTful access to customer\n      account data including balance, contract details, invoice history,\n      service details, pickup schedules, and ETA information. Uses JWT bearer\n      token authentication with ClientId and Request-Tracking-Id headers.\n    humanURL: https://api.wm.com/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://api.wm.com/\n      - type: OpenAPI\n        url: openapi/waste-management-customer-api-openapi.yml\n      - type: SpectralRules\n        url: rules/waste-management-rules.yml\n    tags:\n      - Customer API\n      - Billing\n      - Services\n      - Pickup Scheduling\n      - REST\ncommon:\n  - type: Website\n    url: https://www.wm.com\n  - type: Portal\n    url: https://api.wm.com/\n  - type: OpenAPI\n    url: openapi/waste-management-customer-api-openapi.yml\n  - type: SpectralRules\n    url: rules/waste-management-rules.yml\n\
  \  - type: JSONSchema\n    url: json-schema/waste-management-service-schema.json\n  - type: JSONSchema\n    url: json-schema/waste-management-invoice-schema.json\n  - type: JSONStructure\n    url: json-structure/waste-management-service-structure.json\n  - type: JSON-LD\n    url: json-ld/waste-management-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/waste-management-vocabulary.yml\n  - type: NaftikoCapabilities\n    url: capabilities/customer-service.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/waste-management/refs/heads/main/apis.yml
tags:
- Environmental Services
- Fortune 500
- Recycling
- Solid Waste
- Sustainability
- Waste Management
url: https://www.wm.com
use_cases: []
---
