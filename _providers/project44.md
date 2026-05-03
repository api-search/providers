---
api_count: 10
api_specs:
- filename: project44-tracking-openapi.yml
  format: yaml
  label: project44 Tracking API
  slug: project44-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/openapi/project44-tracking-openapi.yml
- filename: project44-shipment-events-asyncapi.yml
  format: yaml
  label: project44 Webhooks API
  slug: project44-webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/asyncapi/project44-shipment-events-asyncapi.yml
apis:
- description: The project44 Tracking API provides real-time multimodal shipment tracking, predictive ETAs, status updates, and exception alerts across truckload, LTL, ocean, rail, air, and parcel modes. Shippers an
  name: project44 Tracking API
  slug: project44-tracking-api
- description: The project44 LTL API supports less-than-truckload workflows including rate quoting, dispatch, electronic bills of lading, image retrieval, and address book management across the LCL carrier network.
  name: project44 LTL API
  slug: project44-ltl-api
- description: The project44 Truckload (TL) API enables management of available vehicles, connected capacity, dispatch, and tracking for full truckload shipments across the carrier network.
  name: project44 Truckload API
  slug: project44-tl-api
- description: The project44 Rating API provides freight rate retrieval, quote generation, and carrier rate comparison across multiple modes to support procurement and real-time spot market pricing.
  name: project44 Rating API
  slug: project44-rating-api
- description: The project44 Booking API enables programmatic freight booking, carrier tendering, and shipment dispatch across truckload, LTL, and multimodal shipments, integrating with carrier networks and TMS plat
  name: project44 Booking API
  slug: project44-booking-api
- description: The project44 Documents API enables retrieval, upload, and management of freight documents including bills of lading, proof of delivery, and customs documentation across the shipment lifecycle.
  name: project44 Documents API
  slug: project44-documents-api
- description: The project44 Yard Management System (YMS) API manages appointments, capacity planning, milestones, reason codes, site codes, and slot scheduling for yard operations and dock management.
  name: project44 Yard Management API
  slug: project44-yard-management-api
- description: The project44 Rail API provides rail asset enrollment and tracking for intermodal and rail freight shipments, supporting visibility across rail networks.
  name: project44 Rail API
  slug: project44-rail-api
- description: The project44 Analytics API provides carrier performance metrics, port intelligence, on-time delivery analytics, lane benchmarking, and supply chain KPI data for transportation intelligence and carrie
  name: project44 Analytics API
  slug: project44-analytics-api
- description: The project44 Webhooks API delivers real-time event notifications for shipments, inventory, orders, and loads, allowing customers to subscribe to lifecycle events and react to status changes asynchron
  name: project44 Webhooks API
  slug: project44-webhooks-api
asyncapis:
- description: project44 publishes real-time freight visibility events via webhooks. Events include shipment status updates, position changes, ETA revisions, and exception alerts across TL, LTL, ocean, air, and parc
  name: project44 Shipment Events API
  slug: project44-shipment-events-asyncapi
common:
- title: ''
  type: Portal
  url: https://developers.project44.com/
- title: ''
  type: Documentation
  url: https://developers.project44.com/
- title: ''
  type: Website
  url: https://www.project44.com/
- title: ''
  type: Status
  url: https://status.project44.com/
- title: ''
  type: PrivacyPolicy
  url: https://www.project44.com/privacy/
- title: ''
  type: Terms of Service
  url: https://www.project44.com/legal/
- title: ''
  type: GitHub Organization
  url: https://github.com/project44
- title: ''
  type: JSON-LD
  url: json-ld/project44-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/project44-shipment-schema.json
created: '2025-01-01'
description: project44 is a supply chain visibility platform that provides real-time shipment tracking, predictive ETAs, freight booking, rating, document management, and analytics across truckload, LTL, ocean, rail, air, and parcel modes. The Movement platform exposes RESTful APIs and webhooks for shippers, carriers, and logistics service providers.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Project44 Context
  property_count: 28
  slug: project44-context
layout: provider
modified: '2026-04-28'
name: project44
skills: []
slug: project44
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: project44\nname: project44\ndescription: >-\n  project44 is a supply chain visibility platform that provides real-time shipment\n  tracking, predictive ETAs, freight booking, rating, document management, and\n  analytics across truckload, LTL, ocean, rail, air, and parcel modes. The Movement\n  platform exposes RESTful APIs and webhooks for shippers, carriers, and logistics\n  service providers.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/apis.yml\ntags:\n  - Logistics\n  - Freight\n  - Supply Chain\n  - Visibility\n  - Tracking\n  - Transportation\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: project44:project44-tracking-api\n    name: project44 Tracking API\n    description: >-\n      The project44 Tracking API provides real-time multimodal shipment\n      tracking, predictive ETAs, status updates, and exception alerts across\n      truckload, LTL, ocean, rail, air, and\
  \ parcel modes. Shippers and LSPs use\n      it to integrate visibility into TMS, OMS, and customer-facing systems.\n    humanURL: https://developers.project44.com/\n    tags:\n      - Tracking\n      - Visibility\n      - Shipments\n      - ETA\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n      - type: OpenAPI\n        url: openapi/project44-tracking-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/project44-shipment-events-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/project44-shipment-schema.json\n  - aid: project44:project44-ltl-api\n    name: project44 LTL API\n    description: >-\n      The project44 LTL API supports less-than-truckload workflows including\n      rate quoting, dispatch, electronic bills of lading, image retrieval, and\n      address book management across the LCL carrier network.\n    humanURL: https://developers.project44.com/\n    tags:\n      - LTL\n      - Quoting\n      - Dispatch\n\
  \      - Freight\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-tl-api\n    name: project44 Truckload API\n    description: >-\n      The project44 Truckload (TL) API enables management of available\n      vehicles, connected capacity, dispatch, and tracking for full truckload\n      shipments across the carrier network.\n    humanURL: https://developers.project44.com/\n    tags:\n      - Truckload\n      - Capacity\n      - Dispatch\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-rating-api\n    name: project44 Rating API\n    description: >-\n      The project44 Rating API provides freight rate retrieval, quote\n      generation, and carrier rate comparison across multiple modes to support\n      procurement and real-time spot market pricing.\n    humanURL: https://developers.project44.com/\n    tags:\n      - Rating\n      - Pricing\n\
  \      - Quoting\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-booking-api\n    name: project44 Booking API\n    description: >-\n      The project44 Booking API enables programmatic freight booking, carrier\n      tendering, and shipment dispatch across truckload, LTL, and multimodal\n      shipments, integrating with carrier networks and TMS platforms.\n    humanURL: https://developers.project44.com/\n    tags:\n      - Booking\n      - Tendering\n      - Dispatch\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-documents-api\n    name: project44 Documents API\n    description: >-\n      The project44 Documents API enables retrieval, upload, and management of\n      freight documents including bills of lading, proof of delivery, and\n      customs documentation across the shipment lifecycle.\n    humanURL: https://developers.project44.com/\n\
  \    tags:\n      - Documents\n      - BOL\n      - POD\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-yard-management-api\n    name: project44 Yard Management API\n    description: >-\n      The project44 Yard Management System (YMS) API manages appointments,\n      capacity planning, milestones, reason codes, site codes, and slot\n      scheduling for yard operations and dock management.\n    humanURL: https://developers.project44.com/\n    tags:\n      - Yard Management\n      - Appointments\n      - Dock Scheduling\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-rail-api\n    name: project44 Rail API\n    description: >-\n      The project44 Rail API provides rail asset enrollment and tracking for\n      intermodal and rail freight shipments, supporting visibility across rail\n      networks.\n    humanURL: https://developers.project44.com/\n\
  \    tags:\n      - Rail\n      - Intermodal\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-analytics-api\n    name: project44 Analytics API\n    description: >-\n      The project44 Analytics API provides carrier performance metrics, port\n      intelligence, on-time delivery analytics, lane benchmarking, and supply\n      chain KPI data for transportation intelligence and carrier scorecarding.\n    humanURL: https://developers.project44.com/\n    tags:\n      - Analytics\n      - Performance\n      - Port Intelligence\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n  - aid: project44:project44-webhooks-api\n    name: project44 Webhooks API\n    description: >-\n      The project44 Webhooks API delivers real-time event notifications for\n      shipments, inventory, orders, and loads, allowing customers to subscribe\n      to lifecycle events and\
  \ react to status changes asynchronously.\n    humanURL: https://developers.project44.com/\n    tags:\n      - Webhooks\n      - Events\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://developers.project44.com/\n      - type: AsyncAPI\n        url: asyncapi/project44-shipment-events-asyncapi.yml\ncommon:\n  - type: Portal\n    url: https://developers.project44.com/\n  - type: Documentation\n    url: https://developers.project44.com/\n  - type: Website\n    url: https://www.project44.com/\n  - type: Status\n    url: https://status.project44.com/\n  - type: PrivacyPolicy\n    url: https://www.project44.com/privacy/\n  - type: Terms of Service\n    url: https://www.project44.com/legal/\n  - type: GitHub Organization\n    url: https://github.com/project44\n  - type: JSON-LD\n    url: json-ld/project44-context.jsonld\n  - type: JSONSchema\n    url: json-schema/project44-shipment-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/apis.yml
tags:
- Logistics
- Freight
- Supply Chain
- Visibility
- Tracking
- Transportation
url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/apis.yml
use_cases: []
---
