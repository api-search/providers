---
api_count: 1
apis:
- description: The ArcBest API provides programmatic access to freight services including LTL rate quotes, shipment booking, tracking, BOL generation, and supply chain visibility. Access is by invitation only.
  name: ArcBest API
  slug: arcbest-api
common:
- title: ''
  type: Portal
  url: https://www.arcbest.com/
- title: ''
  type: SignUp
  url: https://www.arcbest.com/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/rules/arcbest-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/vocabulary/arcbest-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/json-ld/arcbest-api-context.jsonld
created: '2026-03-23'
description: ArcBest is a logistics company offering less-than-truckload (LTL) freight, truckload, moving, and supply chain management services. The ArcBest API platform provides integration capabilities for freight rating, booking, tracking, and supply chain visibility.
features:
- description: Real-time less-than-truckload freight rate quotes with transit time estimates.
  name: LTL Rate Quotes
- description: API-based shipment booking and scheduling for LTL and truckload freight.
  name: Shipment Booking
- description: Real-time tracking of freight shipments with status updates and delivery notifications.
  name: Shipment Tracking
- description: Electronic Bill of Lading generation and management through API integration.
  name: BOL Generation
- description: Automated pickup scheduling and confirmation for outbound freight.
  name: Pickup Scheduling
- description: End-to-end supply chain visibility across ArcBest freight and logistics services.
  name: Supply Chain Visibility
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with SAP ERP for freight cost allocation and logistics management.
  name: SAP
- description: Connect to Oracle ERP and WMS systems for automated freight operations.
  name: Oracle
- description: Integrate shipment tracking and freight data with Salesforce CRM.
  name: Salesforce
- description: Multi-carrier shipping management platform integration.
  name: ShipStation
- description: E-commerce platform integration for LTL freight rate display and booking.
  name: Shopify
jsonld:
- class_count: 12
  name: Arcbest Api Context
  property_count: 41
  slug: arcbest-api-context
layout: provider
modified: '2026-04-19'
name: ArcBest
rules:
- name: ArcBest API Rules
  rule_count: 18
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 6
  slug: arcbest-spectral-rules
skills: []
slug: arcbest
solutions: []
source_filename: apis.yml
source_yaml: "aid: arcbest\nname: ArcBest\ndescription: ArcBest is a logistics company offering less-than-truckload (LTL) freight, truckload, moving, and supply chain management services. The ArcBest API platform provides integration \n  capabilities for freight rating, booking, tracking, and supply chain visibility.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Logistics\n- Freight\n- LTL\n- Supply Chain\n- Shipping\n- Transportation\nurl: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: arcbest:arcbest-api\n  name: ArcBest API\n  description: The ArcBest API provides programmatic access to freight services including LTL rate quotes, shipment booking, tracking, BOL generation, and supply chain visibility. Access is by \n    invitation only.\n  humanURL: https://www.arcbest.com/\n  tags:\n  - LTL Freight\n\
  \  - Rate Quote\n  - Shipment Tracking\n  - BOL\n  - Supply Chain\n  properties:\n  - type: Documentation\n    url: https://www.arcbest.com/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/openapi/arcbest-api.yaml\ncommon:\n- type: Portal\n  url: https://www.arcbest.com/\n- type: SignUp\n  url: https://www.arcbest.com/\n- type: Features\n  data:\n  - name: LTL Rate Quotes\n    description: Real-time less-than-truckload freight rate quotes with transit time estimates.\n  - name: Shipment Booking\n    description: API-based shipment booking and scheduling for LTL and truckload freight.\n  - name: Shipment Tracking\n    description: Real-time tracking of freight shipments with status updates and delivery notifications.\n  - name: BOL Generation\n    description: Electronic Bill of Lading generation and management through API integration.\n  - name: Pickup Scheduling\n    description: Automated pickup scheduling and confirmation for outbound\
  \ freight.\n  - name: Supply Chain Visibility\n    description: End-to-end supply chain visibility across ArcBest freight and logistics services.\n- type: UseCases\n  data:\n  - name: E-Commerce Shipping\n    description: Integrate ArcBest freight rates and booking into e-commerce platforms for automated shipping.\n  - name: ERP Integration\n    description: Connect ArcBest freight services to ERP systems for automated freight procurement and accounting.\n  - name: TMS Integration\n    description: Integrate with Transportation Management Systems for multi-carrier freight optimization.\n  - name: Warehouse Management\n    description: Connect ArcBest pickup scheduling with warehouse management systems for outbound logistics automation.\n- type: Integrations\n  data:\n  - name: SAP\n    description: Integration with SAP ERP for freight cost allocation and logistics management.\n  - name: Oracle\n    description: Connect to Oracle ERP and WMS systems for automated freight operations.\n \
  \ - name: Salesforce\n    description: Integrate shipment tracking and freight data with Salesforce CRM.\n  - name: ShipStation\n    description: Multi-carrier shipping management platform integration.\n  - name: Shopify\n    description: E-commerce platform integration for LTL freight rate display and booking.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/rules/arcbest-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/vocabulary/arcbest-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/json-ld/arcbest-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/apis.yml
tags:
- Logistics
- Freight
- LTL
- Supply Chain
- Shipping
- Transportation
url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/apis.yml
use_cases:
- description: Integrate ArcBest freight rates and booking into e-commerce platforms for automated shipping.
  name: E-Commerce Shipping
- description: Connect ArcBest freight services to ERP systems for automated freight procurement and accounting.
  name: ERP Integration
- description: Integrate with Transportation Management Systems for multi-carrier freight optimization.
  name: TMS Integration
- description: Connect ArcBest pickup scheduling with warehouse management systems for outbound logistics automation.
  name: Warehouse Management
---
