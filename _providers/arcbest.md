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
