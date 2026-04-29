---
api_count: 9
apis:
- description: The Autopay Accounting API provides Autopay invoicing data to external accounting and ERP systems, enabling automated reconciliation of parking revenue and invoice export.
  name: Autopay Accounting API
  slug: accounting-api
- description: The Autopay Booking API enables assignment of anonymous parking permits to vehicles, supporting short-term and pre-booked parking allocations in managed parking facilities.
  name: Autopay Booking API
  slug: booking-api
- description: The Autopay Parking API handles zone entry notifications and parking session modifications, enabling integration with parking gate systems, sensors, and barrier control equipment to track vehicle arri
  name: Autopay Parking API
  slug: parking-api
- description: The Autopay Payment API enables third-party systems to take payment responsibility for parking sessions, supporting employer-paid parking, fleet-billed parking, and visitor parking validation workflow
  name: Autopay Payment API
  slug: payment-api
- description: The Autopay Permit Tenant API enables tenants in managed properties to manage their parking permits, including adding vehicles, modifying permit allocations, and tracking permit usage within their ass
  name: Autopay Permit Tenant API
  slug: permit-tenant-api
- description: The Autopay Fleet API provides fleet information for company vehicle fleets, enabling fleet managers to track vehicle parking activity, costs, and permit usage across all fleet vehicles.
  name: Autopay Fleet API
  slug: fleet-api
- description: The Autopay Statistics API exports parking statistics for operators and landlords, providing data on occupancy rates, revenue, session volumes, and permit utilization for parking facility management a
  name: Autopay Statistics API
  slug: statistics-api
- description: The Autopay Vehicle API fetches data about a vehicle in a specific parking zone, providing real-time information on vehicle presence, active session status, and permit validity for enforcement and acc
  name: Autopay Vehicle API
  slug: vehicle-api
- description: The Autopay Tap and Park API enables third-party applications to validate parking sessions in Autopay-managed zones, supporting contactless parking validation via NFC, mobile apps, or access control s
  name: Autopay Tap and Park API
  slug: tap-park-api
common:
- title: ''
  type: Portal
  url: https://developer.autopay.io
- title: ''
  type: Website
  url: https://autopay.no
- title: ''
  type: Documentation
  url: https://developer.autopay.io
- title: ''
  type: Authentication
  url: https://developer.autopay.io
- title: ''
  type: TermsOfService
  url: https://developer.autopay.io
created: '2025-02-08'
description: Autopay is a Norwegian parking payment and management platform that provides APIs for parking operators, landlords, fleet managers, and third-party integrators. The platform enables automated parking permit management, payment processing, fleet tracking, and parking statistics with 13+ distinct API endpoints. All integrators must accept the Autopay API Usage Agreement before accessing the APIs.
features:
- description: All Autopay APIs use OAuth for secure authentication and authorization. Integrators must obtain API credentials and accept the Usage Agreement before accessing production endpoints.
  name: OAuth Authentication
- description: Comprehensive parking permit lifecycle management for landlords, operators, and tenants including allocation, assignment, modification, and expiration.
  name: Permit Management
- description: Real-time counts of active parking sessions in parking zones via the Status API, enabling dynamic pricing and occupancy monitoring.
  name: Real-Time Zone Status
- description: Corporate fleet parking management with automatic billing to fleet accounts and vehicle-level tracking across parking facilities.
  name: Fleet Parking Integration
- description: Tap and Park API for third-party validation of parking sessions in Autopay zones, supporting retail validation, employer programs, and visitor parking workflows.
  name: Parking Validation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Export Autopay invoicing data to external ERP and accounting systems via the Accounting API for automated reconciliation.
  name: Accounting Systems
- description: Integration with building access control and gate systems via the Parking API for automated entry/exit tracking.
  name: Building Access Control
- description: Connect corporate fleet management software with Autopay for parking cost tracking and vehicle permit assignment.
  name: Fleet Management Platforms
layout: provider
modified: '2026-04-19'
name: Autopay
skills: []
slug: autopay
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: autopay\nname: Autopay\ndescription: >-\n  Autopay is a Norwegian parking payment and management platform that provides\n  APIs for parking operators, landlords, fleet managers, and third-party integrators.\n  The platform enables automated parking permit management, payment processing,\n  fleet tracking, and parking statistics with 13+ distinct API endpoints. All\n  integrators must accept the Autopay API Usage Agreement before accessing the APIs.\ntags:\n  - Parking\n  - Parking Payments\n  - Fleet Management\n  - Permits\n  - Parking Operators\n  - Norway\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-08'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/autopay/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: autopay:accounting-api\n    name: Autopay Accounting API\n    description: >-\n      The Autopay Accounting API provides\
  \ Autopay invoicing data to external\n      accounting and ERP systems, enabling automated reconciliation of parking\n      revenue and invoice export.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Accounting\n      - Invoicing\n      - Finance\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n      - type: Authentication\n        url: https://developer.autopay.io\n\n  - aid: autopay:booking-api\n    name: Autopay Booking API\n    description: >-\n      The Autopay Booking API enables assignment of anonymous parking permits\n      to vehicles, supporting short-term and pre-booked parking allocations\n      in managed parking facilities.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Booking\n      - Parking Permits\n      - Reservations\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n\n  - aid: autopay:parking-api\n    name: Autopay Parking API\n    description: >-\n   \
  \   The Autopay Parking API handles zone entry notifications and parking\n      session modifications, enabling integration with parking gate systems,\n      sensors, and barrier control equipment to track vehicle arrivals and\n      departures in parking zones.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Parking Sessions\n      - Zone Entry\n      - Gate Control\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n\n  - aid: autopay:payment-api\n    name: Autopay Payment API\n    description: >-\n      The Autopay Payment API enables third-party systems to take payment\n      responsibility for parking sessions, supporting employer-paid parking,\n      fleet-billed parking, and visitor parking validation workflows.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Payments\n      - Parking Payment\n      - Third-Party Billing\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n\
  \n  - aid: autopay:permit-tenant-api\n    name: Autopay Permit Tenant API\n    description: >-\n      The Autopay Permit Tenant API enables tenants in managed properties to\n      manage their parking permits, including adding vehicles, modifying permit\n      allocations, and tracking permit usage within their assigned quota.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Permits\n      - Tenant Management\n      - Vehicle Permits\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n\n  - aid: autopay:fleet-api\n    name: Autopay Fleet API\n    description: >-\n      The Autopay Fleet API provides fleet information for company vehicle\n      fleets, enabling fleet managers to track vehicle parking activity, costs,\n      and permit usage across all fleet vehicles.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Fleet Management\n      - Vehicle Tracking\n      - Corporate Parking\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.autopay.io\n\n  - aid: autopay:statistics-api\n    name: Autopay Statistics API\n    description: >-\n      The Autopay Statistics API exports parking statistics for operators and\n      landlords, providing data on occupancy rates, revenue, session volumes,\n      and permit utilization for parking facility management and reporting.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Analytics\n      - Statistics\n      - Reporting\n      - Occupancy\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n\n  - aid: autopay:vehicle-api\n    name: Autopay Vehicle API\n    description: >-\n      The Autopay Vehicle API fetches data about a vehicle in a specific\n      parking zone, providing real-time information on vehicle presence,\n      active session status, and permit validity for enforcement and\n      access control purposes.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Vehicle Data\n\
  \      - Zone Status\n      - Enforcement\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n\n  - aid: autopay:tap-park-api\n    name: Autopay Tap and Park API\n    description: >-\n      The Autopay Tap and Park API enables third-party applications to validate\n      parking sessions in Autopay-managed zones, supporting contactless parking\n      validation via NFC, mobile apps, or access control systems.\n    humanURL: https://developer.autopay.io\n    tags:\n      - Parking Validation\n      - NFC\n      - Mobile Payments\n      - Contactless\n    properties:\n      - type: Documentation\n        url: https://developer.autopay.io\n\ncommon:\n  - type: Portal\n    url: https://developer.autopay.io\n  - type: Website\n    url: https://autopay.no\n  - type: Documentation\n    url: https://developer.autopay.io\n  - type: Authentication\n    url: https://developer.autopay.io\n  - type: TermsOfService\n    url: https://developer.autopay.io\n  - type:\
  \ Features\n    data:\n      - name: OAuth Authentication\n        description: >-\n          All Autopay APIs use OAuth for secure authentication and authorization.\n          Integrators must obtain API credentials and accept the Usage Agreement\n          before accessing production endpoints.\n      - name: Permit Management\n        description: >-\n          Comprehensive parking permit lifecycle management for landlords, operators,\n          and tenants including allocation, assignment, modification, and expiration.\n      - name: Real-Time Zone Status\n        description: >-\n          Real-time counts of active parking sessions in parking zones via the\n          Status API, enabling dynamic pricing and occupancy monitoring.\n      - name: Fleet Parking Integration\n        description: >-\n          Corporate fleet parking management with automatic billing to fleet\n          accounts and vehicle-level tracking across parking facilities.\n      - name: Parking Validation\n\
  \        description: >-\n          Tap and Park API for third-party validation of parking sessions in\n          Autopay zones, supporting retail validation, employer programs, and\n          visitor parking workflows.\n  - type: UseCases\n    data:\n      - name: Property Parking Management\n        description: >-\n          Landlords manage tenant parking permits and allocations through the\n          Permit Landlord and Tenant APIs for residential and commercial properties.\n      - name: Corporate Fleet Parking\n        description: >-\n          Companies manage fleet vehicle parking costs and permits using the\n          Fleet API with automatic billing to corporate accounts.\n      - name: Parking Revenue Reporting\n        description: >-\n          Parking operators export revenue and occupancy statistics from the\n          Statistics API into accounting and BI systems for reporting.\n      - name: Visitor Parking Validation\n        description: >-\n          Retail, hospitality,\
  \ and office tenants validate visitor parking\n          through the Tap and Park API integrated with access control or POS systems.\n  - type: Integrations\n    data:\n      - name: Accounting Systems\n        description: >-\n          Export Autopay invoicing data to external ERP and accounting systems\n          via the Accounting API for automated reconciliation.\n      - name: Building Access Control\n        description: >-\n          Integration with building access control and gate systems via the\n          Parking API for automated entry/exit tracking.\n      - name: Fleet Management Platforms\n        description: >-\n          Connect corporate fleet management software with Autopay for\n          parking cost tracking and vehicle permit assignment.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/autopay/refs/heads/main/apis.yml
tags:
- Parking
- Parking Payments
- Fleet Management
- Permits
- Parking Operators
- Norway
url: https://raw.githubusercontent.com/api-evangelist/autopay/refs/heads/main/apis.yml
use_cases:
- description: Landlords manage tenant parking permits and allocations through the Permit Landlord and Tenant APIs for residential and commercial properties.
  name: Property Parking Management
- description: Companies manage fleet vehicle parking costs and permits using the Fleet API with automatic billing to corporate accounts.
  name: Corporate Fleet Parking
- description: Parking operators export revenue and occupancy statistics from the Statistics API into accounting and BI systems for reporting.
  name: Parking Revenue Reporting
- description: Retail, hospitality, and office tenants validate visitor parking through the Tap and Park API integrated with access control or POS systems.
  name: Visitor Parking Validation
---
