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
