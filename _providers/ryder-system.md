---
api_count: 5
api_specs:
- filename: ryder-fleet-management-api-openapi.yml
  format: yaml
  label: Ryder Fleet Management API
  slug: fleet-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-fleet-management-api-openapi.yml
- filename: ryder-carrier-api-openapi.yml
  format: yaml
  label: Ryder Carrier API
  slug: carrier-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-carrier-api-openapi.yml
- filename: ryder-tm-shipment-api-openapi.yml
  format: yaml
  label: Ryder TM Shipment Management API
  slug: tm-shipment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-tm-shipment-api-openapi.yml
apis:
- description: The Ryder Fleet Management API (FMS) enables seamless integration of fleet and location data into business systems. It provides access to Ryder fleet details including vehicle information and specific
  name: Ryder Fleet Management API
  slug: fleet-management-api
- description: The Ryder Carrier API enables carriers to push updates to Ryder for managing transportation, brokerage, and tracking services. It supports resource assignment and tracking for load tenders, event upda
  name: Ryder Carrier API
  slug: carrier-api
- description: The Ryder TM Shipment Management API enables seamless integration for customers to manage shipments, loads, and tracking updates. It uses OAuth 2.0 Client Credentials flow via Okta combined with an AP
  name: Ryder TM Shipment Management API
  slug: tm-shipment-api
- description: The Ryder Last Mile API handles last-mile delivery operations, enabling integration with Ryder's last-mile delivery network for e-commerce fulfillment and parcel delivery management.
  name: Ryder Last Mile API
  slug: last-mile-api
- description: The Ryder 3PA Load Tracking API provides third-party logistics load tracking functionality, enabling visibility into load status and location throughout the shipment lifecycle.
  name: Ryder 3PA Load Tracking API
  slug: 3pa-load-tracking-api
capabilities:
- description: Unified workflow for fleet operations customers leasing and maintaining commercial vehicles with Ryder. Enables fleet managers to view vehicle specifications, track maintenance history, access service
  name: Ryder Fleet Operations
  slug: fleet-operations
- description: 'Unified workflow for supply chain visibility across Ryder''s carrier and shipment management APIs. Enables logistics managers to manage carrier load tenders, track shipment status in real-time, submit '
  name: Ryder Supply Chain Visibility
  slug: supply-chain-visibility
common:
- title: ''
  type: Website
  url: https://www.ryder.com
- title: ''
  type: DeveloperPortal
  url: https://developer.ryder.com
- title: ''
  type: Documentation
  url: https://developer.ryder.com/fms/overview
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/vocabulary/ryder-system-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-ld/ryder-system-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/rules/ryder-spectral-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/capabilities/fleet-operations.yaml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/capabilities/supply-chain-visibility.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-schema/ryder-vehicle-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-schema/ryder-shipment-schema.json
created: '2026-03-21'
description: Ryder System, Inc. is a leading provider of supply chain, dedicated transportation, and fleet management solutions. Ryder operates a developer portal offering REST APIs for fleet management and supply chain operations, enabling customers to integrate Ryder services into their business systems. The Fleet Management APIs support customers who lease, rent, and maintain vehicles, while the Supply Chain Solutions APIs support carrier management, load tracking, shipment management, and last-mile delivery operations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Ryder System Context
  property_count: 29
  slug: ryder-system-context
layout: provider
modified: '2026-05-02'
name: Ryder System
rules:
- name: Ryder System API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 3
  slug: ryder-spectral-rules
skills: []
slug: ryder-system
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ryder-system\nname: Ryder System\ndescription: >-\n  Ryder System, Inc. is a leading provider of supply chain, dedicated transportation,\n  and fleet management solutions. Ryder operates a developer portal offering REST APIs\n  for fleet management and supply chain operations, enabling customers to integrate\n  Ryder services into their business systems. The Fleet Management APIs support\n  customers who lease, rent, and maintain vehicles, while the Supply Chain Solutions\n  APIs support carrier management, load tracking, shipment management, and last-mile\n  delivery operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Fleet Management\n  - Logistics\n  - Supply Chain\n  - Transportation\n  - Trucking\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: ryder-system:fleet-management-api\n\
  \    name: Ryder Fleet Management API\n    description: >-\n      The Ryder Fleet Management API (FMS) enables seamless integration of fleet\n      and location data into business systems. It provides access to Ryder fleet\n      details including vehicle information and specifications, location data with\n      address and service hours, historical maintenance records, and invoice details\n      with line items and payment status. Requires API key authentication via the\n      Ocp-Apim-Subscription-Key header.\n    humanURL: https://developer.ryder.com/fms/overview\n    baseURL: https://developer.ryder.com/fms/apis\n    tags:\n      - Fleet Management\n      - Invoices\n      - Locations\n      - Service History\n      - Vehicles\n    properties:\n      - type: Documentation\n        url: https://developer.ryder.com/fms/docs/fms-fleet-api/overview\n      - type: GettingStarted\n        url: https://developer.ryder.com/fms/docs/fms-fleet-api/getting-started\n      - type: OpenAPI\n   \
  \     url: >-\n          https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-fleet-management-api-openapi.yml\n  - aid: ryder-system:carrier-api\n    name: Ryder Carrier API\n    description: >-\n      The Ryder Carrier API enables carriers to push updates to Ryder for managing\n      transportation, brokerage, and tracking services. It supports resource assignment\n      and tracking for load tenders, event updates for load events and milestones,\n      vehicle locations, and document uploads to the RyderShare platform.\n    humanURL: https://developer.ryder.com/scs/docs/scs-carrier/overview\n    baseURL: https://api.ryder.com/rcsc/events/v1\n    tags:\n      - Carrier Management\n      - Load Tracking\n      - Supply Chain\n      - Transportation\n    properties:\n      - type: Documentation\n        url: https://developer.ryder.com/scs/docs/scs-carrier/overview\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-carrier-api-openapi.yml\n\
  \  - aid: ryder-system:tm-shipment-api\n    name: Ryder TM Shipment Management API\n    description: >-\n      The Ryder TM Shipment Management API enables seamless integration for customers\n      to manage shipments, loads, and tracking updates. It uses OAuth 2.0 Client\n      Credentials flow via Okta combined with an API subscription key. Supports\n      Shipment, Load, Ship Confirmation, Ship Status, and Event Notifications.\n    humanURL: https://developer.ryder.com/scs/docs/tm-shipment-management/overview\n    baseURL: https://api.ryder.com/tmshipment/v1\n    tags:\n      - Shipment Management\n      - Supply Chain\n      - Transportation\n    properties:\n      - type: Documentation\n        url: https://developer.ryder.com/scs/docs/tm-shipment-management/overview\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/openapi/ryder-tm-shipment-api-openapi.yml\n  - aid: ryder-system:last-mile-api\n    name:\
  \ Ryder Last Mile API\n    description: >-\n      The Ryder Last Mile API handles last-mile delivery operations, enabling\n      integration with Ryder's last-mile delivery network for e-commerce fulfillment\n      and parcel delivery management.\n    humanURL: https://developer.ryder.com/scs/docs/ryder-last-mile/overview\n    tags:\n      - E-Commerce\n      - Last Mile Delivery\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://developer.ryder.com/scs/docs/ryder-last-mile/overview\n  - aid: ryder-system:3pa-load-tracking-api\n    name: Ryder 3PA Load Tracking API\n    description: >-\n      The Ryder 3PA Load Tracking API provides third-party logistics load tracking\n      functionality, enabling visibility into load status and location throughout\n      the shipment lifecycle.\n    humanURL: https://developer.ryder.com/scs/docs/3pa-load-tracking/overview\n    tags:\n      - Load Tracking\n      - Logistics\n      - Supply Chain\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.ryder.com/scs/docs/3pa-load-tracking/overview\ncommon:\n  - type: Website\n    url: https://www.ryder.com\n  - type: DeveloperPortal\n    url: https://developer.ryder.com\n  - type: Documentation\n    url: https://developer.ryder.com/fms/overview\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/vocabulary/ryder-system-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-ld/ryder-system-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/rules/ryder-spectral-rules.yml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/capabilities/fleet-operations.yaml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/capabilities/supply-chain-visibility.yaml\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-schema/ryder-vehicle-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/json-schema/ryder-shipment-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/apis.yml
tags:
- Fleet Management
- Logistics
- Supply Chain
- Transportation
- Trucking
url: https://raw.githubusercontent.com/api-evangelist/ryder-system/refs/heads/main/apis.yml
use_cases: []
---
