---
api_count: 4
api_specs:
- filename: alaska-air-flight-status-openapi.yaml
  format: yaml
  label: Alaska Airlines Flight Status API
  slug: flight-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-flight-status-openapi.yaml
- filename: alaska-air-flight-schedules-openapi.yaml
  format: yaml
  label: Alaska Airlines Flight Schedules API
  slug: flight-schedules-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-flight-schedules-openapi.yaml
- filename: alaska-air-cargo-openapi.yaml
  format: yaml
  label: Alaska Air Cargo API
  slug: cargo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-cargo-openapi.yaml
- filename: alaska-air-mileage-plan-openapi.yaml
  format: yaml
  label: Alaska Airlines Mileage Plan API
  slug: mileage-plan-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/openapi/alaska-air-mileage-plan-openapi.yaml
apis:
- description: The Alaska Airlines Flight Status API provides real-time flight status, departure and arrival information, gate assignments, and delay details for Alaska Airlines (AS) and Horizon Air (QX) flights.
  name: Alaska Airlines Flight Status API
  slug: flight-status-api
- description: The Alaska Airlines Flight Schedules API provides access to flight schedule data including route information, operating days, departure and arrival times, and equipment information across the Alaska A
  name: Alaska Airlines Flight Schedules API
  slug: flight-schedules-api
- description: Alaska Air Cargo APIs enable partners to book shipments, track cargo, get rate estimates, and access schedules across 115+ cargo destinations worldwide. Alaska Airlines operates the only U.S. passenge
  name: Alaska Air Cargo API
  slug: cargo-api
- description: The Alaska Mileage Plan partner API enables airline partners, hotel chains, car rental companies, and other loyalty partners to report and redeem miles for members. Alaska's Mileage Plan is consistent
  name: Alaska Airlines Mileage Plan API
  slug: mileage-plan-api
capabilities:
- description: 'Workflow capability combining Alaska Airlines Flight Status and Cargo APIs for travel operations management. Enables travel agents, corporate travel managers, and freight forwarders to track flights, '
  name: Alaska Airlines Travel Operations
  slug: travel-operations
common:
- title: ''
  type: Website
  url: https://www.alaskaair.com
- title: ''
  type: Portal
  url: https://developers.alaskaair.com/
- title: ''
  type: Blog
  url: https://www.alaskaair.com/content/about-us/news-and-events
- title: ''
  type: Support
  url: https://www.alaskaair.com/content/about-us/investor-relations
- title: API Support Email
  type: Support
  url: api.support@alaskaair.com
- title: Alaska Air Cargo Portal
  type: Documentation
  url: https://www.alaskacargo.com/
- title: ''
  type: SpectralRules
  url: rules/alaska-air-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/alaska-air-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/alaska-air-context.jsonld
- title: Flight Status API Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/flight-status-api.yaml
- title: Cargo API Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/cargo-api.yaml
- title: Travel Operations Workflow
  type: NaftikoCapability
  url: capabilities/travel-operations.yaml
created: '2024-01-01'
description: Alaska Air Group is the parent company of Alaska Airlines and Horizon Air, providing passenger and cargo air transportation throughout the United States, Mexico, Canada, Costa Rica, and Belize. Alaska Airlines offers a developer portal at developers.alaskaair.com for accessing flight status, schedules, and other APIs, and operates Alaska Air Cargo serving 115+ destinations worldwide with dedicated cargo aircraft.
features:
- description: Track live flight status, departure and arrival times, gate assignments, and delay information for Alaska Airlines and Horizon Air flights.
  name: Real-Time Flight Status
- description: Access flight schedule data including routes, operating days, departure/arrival times, and equipment across the Alaska network.
  name: Flight Schedules
- description: Book shipments and track cargo across 115+ destinations worldwide via Alaska Air Cargo's network, including dedicated widebody aircraft.
  name: Cargo Booking and Tracking
- description: Get real-time rate estimates for cargo shipments based on origin, destination, weight, dimensions, and special handling requirements.
  name: Cargo Rate Estimates
- description: Enable partner mile accrual and redemption for Alaska's Mileage Plan loyalty program across airline, hotel, car rental, and retail partners.
  name: Mileage Plan Partner Integration
- description: Alaska Air Cargo operates the only U.S. passenger airline with dedicated cargo aircraft (Airbus A330s and Boeing 787s) for increased capacity on key routes.
  name: Dedicated Cargo Aircraft
- description: Support for dangerous goods transport, live animal shipments via Pet Connect, and international cargo across Asia, Pacific, Canada, and Mexico.
  name: Specialized Cargo Services
- description: Developer portal powered by Microsoft Azure API Management with subscription-based key management, interactive API console, and automatic API documentation generation.
  name: API Management via Azure
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Developer portal and API gateway powered by Azure API Management with subscription key management and interactive testing console.
  name: Microsoft Azure API Management
- description: Alaska Air Cargo partnerships including connections with Hawaiian Airlines cargo network for Pacific and inter-island routes.
  name: Hawaiian Airlines
- description: Member of the oneworld airline alliance enabling Mileage Plan accrual and redemption across 13 member airlines.
  name: One World Alliance
- description: Third-party travel API provider enabling search, booking, and ticket issuance for Alaska Airlines flights.
  name: Duffel
- description: Customer service platform integration for Alaska Air Cargo live chat and support operations.
  name: Five9
jsonld:
- class_count: 22
  name: Alaska Air Context
  property_count: 84
  slug: alaska-air-context
layout: provider
modified: '2026-04-19'
name: Alaska Airlines
rules:
- name: Alaska Airlines API Rules
  rule_count: 32
  severity_counts:
    error: 16
    hint: 0
    info: 2
    warn: 14
  slug: alaska-air-spectral-rules
skills: []
slug: alaska-air
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: alaska-air\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/apis.yml\nname: Alaska Airlines\ntags:\n  - Airlines\n  - Aviation\n  - Travel\n  - Cargo\n  - Loyalty\n  - Flight Status\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Alaska Air Group is the parent company of Alaska Airlines and Horizon Air,\n  providing passenger and cargo air transportation throughout the United States,\n  Mexico, Canada, Costa Rica, and Belize. Alaska Airlines offers a developer\n  portal at developers.alaskaair.com for accessing flight status, schedules,\n  and other APIs, and operates Alaska Air Cargo serving 115+ destinations\n  worldwide with dedicated cargo aircraft.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: alaska-air:flight-status-api\n    name: Alaska Airlines Flight Status API\n    tags:\n      - Flight Status\n      - Aviation\n\
  \      - Real-Time Data\n    properties:\n      - url: https://developers.alaskaair.com/\n        type: Documentation\n      - url: https://developers.alaskaair.com/\n        type: APIReference\n      - url: openapi/alaska-air-flight-status-openapi.yaml\n        type: OpenAPI\n    humanURL: https://developers.alaskaair.com/\n    baseURL: https://api.alaskaair.com\n    description: >-\n      The Alaska Airlines Flight Status API provides real-time flight status,\n      departure and arrival information, gate assignments, and delay details\n      for Alaska Airlines (AS) and Horizon Air (QX) flights.\n  - aid: alaska-air:flight-schedules-api\n    name: Alaska Airlines Flight Schedules API\n    tags:\n      - Schedules\n      - Aviation\n      - Itinerary\n    properties:\n      - url: https://developers.alaskaair.com/\n        type: Documentation\n      - url: openapi/alaska-air-flight-schedules-openapi.yaml\n        type: OpenAPI\n    humanURL: https://developers.alaskaair.com/\n    baseURL:\
  \ https://api.alaskaair.com\n    description: >-\n      The Alaska Airlines Flight Schedules API provides access to flight\n      schedule data including route information, operating days, departure\n      and arrival times, and equipment information across the Alaska Airlines\n      and Horizon Air networks.\n  - aid: alaska-air:cargo-api\n    name: Alaska Air Cargo API\n    tags:\n      - Cargo\n      - Freight\n      - Shipping\n      - Tracking\n    properties:\n      - url: https://www.alaskacargo.com/\n        type: Documentation\n      - url: https://www.alaskacargo.com/\n        type: Portal\n      - url: openapi/alaska-air-cargo-openapi.yaml\n        type: OpenAPI\n    humanURL: https://www.alaskacargo.com/\n    baseURL: https://api.alaskacargo.com\n    description: >-\n      Alaska Air Cargo APIs enable partners to book shipments, track cargo,\n      get rate estimates, and access schedules across 115+ cargo destinations\n      worldwide. Alaska Airlines operates the only U.S.\
  \ passenger airline with\n      dedicated cargo aircraft including Airbus A330s and Boeing 787s.\n  - aid: alaska-air:mileage-plan-api\n    name: Alaska Airlines Mileage Plan API\n    tags:\n      - Loyalty\n      - Mileage Plan\n      - Rewards\n      - Partners\n    properties:\n      - url: https://www.alaskaair.com/content/mileage-plan\n        type: Documentation\n      - url: openapi/alaska-air-mileage-plan-openapi.yaml\n        type: OpenAPI\n    humanURL: https://www.alaskaair.com/content/mileage-plan\n    baseURL: https://api.alaskaair.com\n    description: >-\n      The Alaska Mileage Plan partner API enables airline partners, hotel\n      chains, car rental companies, and other loyalty partners to report and\n      redeem miles for members. Alaska's Mileage Plan is consistently rated\n      among the top frequent flyer programs.\ncommon:\n  - url: https://www.alaskaair.com\n    type: Website\n  - url: https://developers.alaskaair.com/\n    type: Portal\n  - url: https://www.alaskaair.com/content/about-us/news-and-events\n\
  \    type: Blog\n  - url: https://www.alaskaair.com/content/about-us/investor-relations\n    type: Support\n  - url: api.support@alaskaair.com\n    type: Support\n    title: API Support Email\n  - url: https://www.alaskacargo.com/\n    type: Documentation\n    title: Alaska Air Cargo Portal\n  - url: rules/alaska-air-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/alaska-air-vocabulary.yaml\n    type: Vocabulary\n  - url: json-ld/alaska-air-context.jsonld\n    type: JSONLD\n  - url: capabilities/shared/flight-status-api.yaml\n    type: NaftikoCapability\n    title: Flight Status API Shared Capability\n  - url: capabilities/shared/cargo-api.yaml\n    type: NaftikoCapability\n    title: Cargo API Shared Capability\n  - url: capabilities/travel-operations.yaml\n    type: NaftikoCapability\n    title: Travel Operations Workflow\n  - type: Features\n    data:\n      - name: Real-Time Flight Status\n        description: >-\n          Track live flight status, departure and arrival\
  \ times, gate\n          assignments, and delay information for Alaska Airlines and Horizon\n          Air flights.\n      - name: Flight Schedules\n        description: >-\n          Access flight schedule data including routes, operating days,\n          departure/arrival times, and equipment across the Alaska network.\n      - name: Cargo Booking and Tracking\n        description: >-\n          Book shipments and track cargo across 115+ destinations worldwide\n          via Alaska Air Cargo's network, including dedicated widebody aircraft.\n      - name: Cargo Rate Estimates\n        description: >-\n          Get real-time rate estimates for cargo shipments based on origin,\n          destination, weight, dimensions, and special handling requirements.\n      - name: Mileage Plan Partner Integration\n        description: >-\n          Enable partner mile accrual and redemption for Alaska's Mileage\n          Plan loyalty program across airline, hotel, car rental, and\n          retail\
  \ partners.\n      - name: Dedicated Cargo Aircraft\n        description: >-\n          Alaska Air Cargo operates the only U.S. passenger airline with\n          dedicated cargo aircraft (Airbus A330s and Boeing 787s) for\n          increased capacity on key routes.\n      - name: Specialized Cargo Services\n        description: >-\n          Support for dangerous goods transport, live animal shipments via\n          Pet Connect, and international cargo across Asia, Pacific, Canada,\n          and Mexico.\n      - name: API Management via Azure\n        description: >-\n          Developer portal powered by Microsoft Azure API Management with\n          subscription-based key management, interactive API console, and\n          automatic API documentation generation.\n  - type: UseCases\n    data:\n      - name: Travel Agent and OTA Integration\n        description: >-\n          Integrate Alaska Airlines flight schedules and status into online\n          travel agencies and booking platforms\
  \ for real-time availability\n          and status updates.\n      - name: Cargo Partner Booking\n        description: >-\n          Enable freight forwarders and cargo brokers to book shipments,\n          get rate quotes, and track Alaska Air Cargo shipments programmatically.\n      - name: Loyalty Partner Mile Reporting\n        description: >-\n          Integrate Mileage Plan mile accrual into partner platforms (hotels,\n          car rentals, credit cards) to automatically report earned miles.\n      - name: Airport Operations Display\n        description: >-\n          Power airport operations systems and display boards with real-time\n          Alaska Airlines flight status and gate assignment data.\n      - name: Corporate Travel Management\n        description: >-\n          Integrate Alaska Airlines flight data into corporate travel\n          management systems for booking, tracking, and expense reporting.\n      - name: Mobile App Integration\n        description: >-\n   \
  \       Embed Alaska Airlines flight status and schedule data into third-party\n          mobile applications for travelers.\n  - type: Integrations\n    data:\n      - name: Microsoft Azure API Management\n        description: >-\n          Developer portal and API gateway powered by Azure API Management\n          with subscription key management and interactive testing console.\n      - name: Hawaiian Airlines\n        description: >-\n          Alaska Air Cargo partnerships including connections with Hawaiian\n          Airlines cargo network for Pacific and inter-island routes.\n      - name: One World Alliance\n        description: >-\n          Member of the oneworld airline alliance enabling Mileage Plan\n          accrual and redemption across 13 member airlines.\n      - name: Duffel\n        description: >-\n          Third-party travel API provider enabling search, booking, and\n          ticket issuance for Alaska Airlines flights.\n      - name: Five9\n        description:\
  \ >-\n          Customer service platform integration for Alaska Air Cargo\n          live chat and support operations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/apis.yml
tags:
- Airlines
- Aviation
- Travel
- Cargo
- Loyalty
- Flight Status
url: https://raw.githubusercontent.com/api-evangelist/alaska-air/refs/heads/main/apis.yml
use_cases:
- description: Integrate Alaska Airlines flight schedules and status into online travel agencies and booking platforms for real-time availability and status updates.
  name: Travel Agent and OTA Integration
- description: Enable freight forwarders and cargo brokers to book shipments, get rate quotes, and track Alaska Air Cargo shipments programmatically.
  name: Cargo Partner Booking
- description: Integrate Mileage Plan mile accrual into partner platforms (hotels, car rentals, credit cards) to automatically report earned miles.
  name: Loyalty Partner Mile Reporting
- description: Power airport operations systems and display boards with real-time Alaska Airlines flight status and gate assignment data.
  name: Airport Operations Display
- description: Integrate Alaska Airlines flight data into corporate travel management systems for booking, tracking, and expense reporting.
  name: Corporate Travel Management
- description: Embed Alaska Airlines flight status and schedule data into third-party mobile applications for travelers.
  name: Mobile App Integration
---
