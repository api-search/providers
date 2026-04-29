---
api_count: 4
apis:
- description: The CargoSmart Container Booking API enables programmatic submission of container booking requests across multiple ocean carriers. APIs support booking creation, amendment, cancellation, and confirmat
  name: CargoSmart Container Booking API
  slug: cargosmart-container-booking-api
- description: The CargoSmart Shipment Tracking API provides real-time container tracking and shipment visibility across ocean carriers and ports. APIs return container movement events, vessel positions, ETA predict
  name: CargoSmart Shipment Tracking API
  slug: cargosmart-shipment-tracking-api
- description: 'The CargoSmart Vessel Schedule API provides access to ocean carrier vessel schedules, port rotation data, and sailing frequency information. APIs support route planning, transit time calculation, and '
  name: CargoSmart Vessel Schedule API
  slug: cargosmart-vessel-schedule-api
- description: The CargoSmart Shipping Documentation API enables electronic exchange of shipping documents including bills of lading, cargo manifests, and customs declarations. APIs and EDI integrations support pape
  name: CargoSmart Shipping Documentation API
  slug: cargosmart-shipping-documents-api
asyncapis:
- description: 'The CargoSmart Shipment Events API delivers real-time event notifications for container movements, shipment milestones, and vessel arrivals/departures via webhooks or server-sent events. Subscribe to '
  name: CargoSmart Shipment Events API
  slug: cargosmart-events-asyncapi
common:
- title: ''
  type: Website
  url: https://www.cargosmart.com
- title: ''
  type: Portal
  url: https://www.cargosmart.com/
- title: ''
  type: Documentation
  url: https://www.cargosmart.com/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml
- title: ''
  type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/asyncapi/cargosmart-events-asyncapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-container-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-booking-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-ld/cargosmart-context.jsonld
- title: ''
  type: GSBN
  url: https://www.gsbn.trade/
- title: ''
  type: IQAX
  url: https://www.iqax.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cargosmart-limited/
created: '2025-01-15'
description: CargoSmart (now operating as IQAX) is a global shipment management software provider that gives shippers, consignees, freight forwarders, and logistics service providers ocean freight booking, container tracking, vessel scheduling, and shipping documentation tools across multiple ocean carriers. CargoSmart co-founded the Global Shipping Business Network (GSBN), a blockchain-based data exchange for carriers, terminals, banks, and customs authorities, and exposes its APIs so trading partners can embed booking, visibility, schedule, and documentation workflows directly into TMS, ERP, and supply-chain platforms.
features: []
image: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/image.png
integrations: []
jsonld:
- class_count: 0
  name: Cargosmart Context
  property_count: 6
  slug: cargosmart-context
layout: provider
modified: '2026-04-23'
name: CargoSmart
skills: []
slug: cargosmart
solutions: []
source_yaml: "aid: cargosmart\nurl: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/apis.yml\nname: CargoSmart\ndescription: >-\n  CargoSmart (now operating as IQAX) is a global shipment management\n  software provider that gives shippers, consignees, freight\n  forwarders, and logistics service providers ocean freight booking,\n  container tracking, vessel scheduling, and shipping documentation\n  tools across multiple ocean carriers. CargoSmart co-founded the\n  Global Shipping Business Network (GSBN), a blockchain-based data\n  exchange for carriers, terminals, banks, and customs authorities,\n  and exposes its APIs so trading partners can embed booking,\n  visibility, schedule, and documentation workflows directly into\n  TMS, ERP, and supply-chain platforms.\ntype: Index\nx-type: company\nposition: Consumer\naccess: 3rd-Party\nimage: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/image.png\ntags:\n  - Booking\n  - Container\n\
  \  - Documentation\n  - GSBN\n  - IQAX\n  - Logistics\n  - Maritime\n  - Ocean Freight\n  - Schedule\n  - Shipping\n  - Supply Chain\n  - Tracking\n  - Visibility\n  - Vessel\ncreated: '2025-01-15'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: cargosmart:cargosmart-container-booking-api\n    name: CargoSmart Container Booking API\n    description: >-\n      The CargoSmart Container Booking API enables programmatic\n      submission of container booking requests across multiple ocean\n      carriers. APIs support booking creation, amendment,\n      cancellation, and confirmation workflows for shippers, NVOCCs,\n      and logistics service providers.\n    humanURL: https://www.cargosmart.com/\n    baseURL: https://api.cargosmart.com\n    tags:\n      - Booking\n      - Container\n      - Logistics\n      - Maritime\n      - Ocean Freight\n      - Shipping\n    image: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/image.png\n    properties:\n\
  \      - url: https://www.cargosmart.com/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml\n        type: OpenAPI\n    x-features:\n      - Multi-carrier container booking submission\n      - Booking creation, amendment, and cancellation\n      - Acknowledgment and confirmation callbacks\n      - Shipper, NVOCC, and LSP role support\n      - Integration with carrier back-ends via CargoSmart\n    x-use-cases:\n      - Shipper TMS booking automation\n      - NVOCC consolidation booking\n      - Freight forwarder tender flow\n      - Enterprise ERP-to-carrier booking integration\n  - aid: cargosmart:cargosmart-shipment-tracking-api\n    name: CargoSmart Shipment Tracking API\n    description: >-\n      The CargoSmart Shipment Tracking API provides real-time\n      container tracking and shipment visibility across ocean carriers\n      and ports. APIs return container movement\
  \ events, vessel\n      positions, ETA predictions, and port arrival/departure data for\n      supply chain visibility platforms. An accompanying AsyncAPI\n      channel emits milestone events so subscribers can react without\n      polling.\n    humanURL: https://www.cargosmart.com/\n    baseURL: https://api.cargosmart.com\n    tags:\n      - Container\n      - Logistics\n      - Maritime\n      - Shipping\n      - Tracking\n      - Visibility\n    image: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/image.png\n    properties:\n      - url: https://www.cargosmart.com/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/asyncapi/cargosmart-events-asyncapi.yml\n        type: AsyncAPI\n    x-features:\n      - Real-time container movement\
  \ events\n      - Vessel position and ETA predictions\n      - Port arrival/departure milestones\n      - AsyncAPI event channel for push delivery\n      - Cross-carrier normalized schema\n      - Exception and delay detection\n    x-use-cases:\n      - Supply-chain visibility platforms\n      - Customer self-service tracking portals\n      - Proactive exception management and ETA-based allocation\n      - Carrier performance analytics\n  - aid: cargosmart:cargosmart-vessel-schedule-api\n    name: CargoSmart Vessel Schedule API\n    description: >-\n      The CargoSmart Vessel Schedule API provides access to ocean\n      carrier vessel schedules, port rotation data, and sailing\n      frequency information. APIs support route planning, transit\n      time calculation, and carrier selection for ocean freight\n      shippers and forwarders.\n    humanURL: https://www.cargosmart.com/\n    baseURL: https://api.cargosmart.com\n    tags:\n      - Logistics\n      - Maritime\n      - Port\n \
  \     - Schedule\n      - Shipping\n      - Vessel\n    image: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/image.png\n    properties:\n      - url: https://www.cargosmart.com/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml\n        type: OpenAPI\n    x-features:\n      - Carrier vessel schedule lookup\n      - Port rotation and sailing frequency data\n      - Transit time calculation by lane\n      - Multi-carrier normalized schema\n    x-use-cases:\n      - Route planning and carrier selection\n      - Transit time SLAs for customer quotes\n      - Sailing calendar feeds in TMS platforms\n  - aid: cargosmart:cargosmart-shipping-documents-api\n    name: CargoSmart Shipping Documentation API\n    description: >-\n      The CargoSmart Shipping Documentation API enables electronic\n      exchange of shipping documents including bills of lading,\
  \ cargo\n      manifests, and customs declarations. APIs and EDI integrations\n      support paperless documentation workflows across carriers,\n      ports, customs authorities, and logistics service providers.\n    humanURL: https://www.cargosmart.com/\n    baseURL: https://api.cargosmart.com\n    tags:\n      - Bill of Lading\n      - Container\n      - Documentation\n      - EDI\n      - Maritime\n      - Shipping\n    image: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/image.png\n    properties:\n      - url: https://www.cargosmart.com/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml\n        type: OpenAPI\n    x-features:\n      - Bill of lading and manifest exchange\n      - Customs declaration integration\n      - API plus EDI support\n      - GSBN-aligned document workflows\n    x-use-cases:\n      - Paperless carrier documentation\n\
  \      - Port and customs authority integration\n      - LSP document hub aggregation\ncommon:\n  - url: https://www.cargosmart.com\n    type: Website\n  - url: https://www.cargosmart.com/\n    type: Portal\n  - url: https://www.cargosmart.com/\n    type: Documentation\n  - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/asyncapi/cargosmart-events-asyncapi.yml\n    type: AsyncAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-container-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-schema/cargosmart-booking-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-ld/cargosmart-context.jsonld\n    type:\
  \ JSONLDContext\n  - type: GSBN\n    url: https://www.gsbn.trade/\n  - type: IQAX\n    url: https://www.iqax.com/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cargosmart-limited/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/apis.yml
tags:
- Booking
- Container
- Documentation
- GSBN
- IQAX
- Logistics
- Maritime
- Ocean Freight
- Schedule
- Shipping
- Supply Chain
- Tracking
- Visibility
- Vessel
url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/apis.yml
use_cases: []
---
