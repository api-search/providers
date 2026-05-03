---
api_count: 1
api_specs:
- filename: union-pacific-api.yaml
  format: yaml
  label: Union Pacific API
  slug: union-pacific
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/openapi/union-pacific-api.yaml
apis:
- description: 'The Union Pacific API provides programmatic access to real-time railroad supply chain data and operational actions. The API enables shipment tracking, equipment management, order placement, exception '
  name: Union Pacific API
  slug: union-pacific
capabilities:
- description: Unified rail freight operations workflow for shipment visibility, supply chain exception management, intermodal planning, and equipment management. Used by logistics managers, supply chain analysts, a
  name: Union Pacific Rail Freight Operations
  slug: rail-freight-operations
common: []
created: '2025-02-06'
description: Union Pacific is one of the largest freight railroad networks in the United States, operating across 23 states in the western two-thirds of the country. The company transports a diverse range of commodities including agricultural products, automotive goods, chemicals, energy resources, and industrial materials. Union Pacific's API platform gives businesses programmatic access to real-time shipment tracking, equipment management, intermodal planning, and supply chain exception handling, enabling seamless integration with logistics and supply chain management systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Union Pacific Context
  property_count: 18
  slug: union-pacific-context
layout: provider
modified: '2026-05-03'
name: Union Pacific
rules:
- name: Union Pacific API Rules
  rule_count: 31
  severity_counts:
    error: 13
    hint: 0
    info: 3
    warn: 15
  slug: union-pacific-spectral-rules
skills: []
slug: union-pacific
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: union-pacific\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/apis.yml\napis:\n  - aid: union-pacific:union-pacific\n    name: Union Pacific API\n    tags:\n      - Freight\n      - Railroads\n      - Shipping\n      - Trains\n      - Supply Chain\n      - Logistics\n    humanURL: https://www.up.com/customers/all/api-developer/index.htm\n    baseURL: https://api.up.com\n    properties:\n      - url: https://www.up.com/customers/all/api-developer/index.htm\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/openapi/union-pacific-api.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/rules/union-pacific-spectral-rules.yml\n        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/capabilities/shared/union-pacific-api.yaml\n\
  \        type: NaftikoCapability\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/capabilities/rail-freight-operations.yaml\n        type: NaftikoCapability\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/vocabulary/union-pacific-vocabulary.yaml\n        type: Vocabulary\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-ld/union-pacific-context.jsonld\n        type: JSONLDContext\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-shipment-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-case-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-equipment-schema.json\n\
  \        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-location-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-waybill-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-intermodal-reservation-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-intermodal-lane-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-intermodal-departure-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-account-schema.json\n\
  \        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-action-response-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-order-equipment-request-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-release-shipment-request-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-cancel-request-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-structure/union-pacific-shipment-structure.json\n        type: JSONStructure\n      - url: >-\n  \
  \        https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-structure/union-pacific-case-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-structure/union-pacific-equipment-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-structure/union-pacific-location-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-structure/union-pacific-intermodal-reservation-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-structure/union-pacific-waybill-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/examples/union-pacific-list-shipments-example.json\n\
  \        type: Example\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/examples/union-pacific-create-intermodal-reservation-example.json\n        type: Example\n    description: >-\n      The Union Pacific API provides programmatic access to real-time railroad supply\n      chain data and operational actions. The API enables shipment tracking, equipment\n      management, order placement, exception case management, and intermodal planning.\n      APIs are structured as data objects that can be used standalone or combined to\n      create robust supply chain workflows. Authentication uses OAuth 2.0 Client\n      Credentials flow.\n    data:\n      - name: Features\n        data:\n          - name: Real-Time Shipment Tracking\n            description: Track active rail shipments with current location and estimated arrival times\n          - name: Exception Case Management\n            description: Monitor and resolve supply chain\
  \ exceptions for off-course or delayed shipments\n          - name: Equipment Management\n            description: Search, order, and release rail car equipment including intermodal containers\n          - name: Intermodal Planning\n            description: Create reservations, find service lanes, and view departure schedules for intermodal transport\n          - name: Network Locations\n            description: Access Union Pacific facility, yard, and terminal location data across the network\n          - name: Waybill Lookup\n            description: Retrieve waybill documents with shipment routing and billing information\n          - name: OAuth 2.0 Security\n            description: Secure API access using OAuth 2.0 Client Credentials flow\n      - name: UseCases\n        data:\n          - name: Supply Chain Visibility\n            description: Logistics managers monitor active shipments across the UP network in real time\n          - name: Exception Resolution\n            description:\
  \ Operations teams identify and resolve shipment exceptions to minimize delays\n          - name: Intermodal Logistics\n            description: Shippers book intermodal container space between UP terminals for coast-to-coast transport\n          - name: Equipment Procurement\n            description: Businesses order rail car equipment for upcoming shipping needs\n          - name: Supply Chain Integration\n            description: ERP and TMS platforms integrate UP freight data via API for automated logistics workflows\n      - name: Integrations\n        data:\n          - name: ERP Systems\n            description: Integrate with SAP, Oracle, and other ERP platforms for automated freight management\n          - name: TMS Platforms\n            description: Connect transportation management systems to UP rail data for multimodal planning\n          - name: Supply Chain Platforms\n            description: Embed UP tracking and exception data in supply chain visibility platforms\n   \
  \       - name: Warehouse Management\n            description: Synchronize inbound rail shipment ETAs with warehouse receiving operations\n\nname: Union Pacific\ntags:\n  - Freight\n  - Railroads\n  - Shipping\n  - Trains\n  - Supply Chain\n  - Logistics\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Union Pacific is one of the largest freight railroad networks in the United States,\n  operating across 23 states in the western two-thirds of the country. The company\n  transports a diverse range of commodities including agricultural products, automotive\n  goods, chemicals, energy resources, and industrial materials. Union Pacific's API\n  platform gives businesses programmatic access to real-time shipment tracking,\n  equipment management, intermodal planning, and supply chain exception handling,\n  enabling seamless integration with\
  \ logistics and supply chain management systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/apis.yml
tags:
- Freight
- Railroads
- Shipping
- Trains
- Supply Chain
- Logistics
url: https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/apis.yml
use_cases: []
---
