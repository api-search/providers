---
api_count: 7
api_specs:
- filename: sabre-bargain-finder-max-openapi.yml
  format: yaml
  label: Sabre Bargain Finder Max API
  slug: bargain-finder-max
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/openapi/sabre-bargain-finder-max-openapi.yml
- filename: sabre-hotels-openapi.yml
  format: yaml
  label: Sabre Hotels API
  slug: hotels
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/openapi/sabre-hotels-openapi.yml
apis:
- description: Sabre Bargain Finder Max (BFM) API provides low-fare search capabilities for air shopping, returning optimal flight itineraries with pricing across Sabre's global airline content inventory including A
  name: Sabre Bargain Finder Max API
  slug: bargain-finder-max
- description: Sabre Air Booking API enables flight booking, passenger name record (PNR) creation and management, seat selection, ticketing, and booking modification for travel agencies and online travel application
  name: Sabre Air Booking API
  slug: air-booking
- description: 'Sabre Hotels API provides hotel search, availability, rate shopping, content retrieval, and booking APIs for travel agencies and OTAs, accessing Sabre''s global lodging content covering over 2 million '
  name: Sabre Hotels API
  slug: hotels
- description: Sabre Cars API provides car rental search, availability, rate shopping, reservation, and management APIs for travel agencies and OTAs, connecting to over 40 global car rental brands across 40,000 loca
  name: Sabre Cars API
  slug: cars
- description: Sabre Destination Content API provides destination guides, points of interest, geo data, and travel inspiration content for travel applications and itinerary planning tools.
  name: Sabre Destination Content API
  slug: destination-content
- description: Sabre Booking Management API provides unified management of multi-segment travel reservations including flights, hotels, and car rentals within a single booking record. Supports booking creation, retr
  name: Sabre Booking Management API
  slug: booking-management
- description: Sabre Rail API provides rail ticket search, booking, and management capabilities connecting to over 30 rail operators worldwide for travel agencies and multi-modal booking platforms.
  name: Sabre Rail API
  slug: rail
capabilities:
- description: Unified workflow for end-to-end travel booking combining air fare search, hotel availability, and reservation management. Used by travel agencies and OTAs to search and book multi-segment travel itine
  name: Sabre Travel Booking
  slug: travel-booking
common:
- title: ''
  type: Portal
  url: https://developer.sabre.com/
- title: ''
  type: Documentation
  url: https://developer.sabre.com/
- title: ''
  type: GettingStarted
  url: https://developer.sabre.com/guides/travel-agency/api-self-service-guide
- title: ''
  type: Authentication
  url: https://developer.sabre.com/guides/travel-agency/developer-guides/rest-apis-token-credentials
- title: ''
  type: Website
  url: https://www.sabre.com/
- title: ''
  type: Support
  url: https://developer.sabre.com/support
- title: ''
  type: Blog
  url: https://developer.sabre.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/SabreDevStudio
- title: ''
  type: SDKs
  url: https://github.com/SabreDevStudio
- title: ''
  type: SpectralRules
  url: rules/sabre-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/sabre-itinerary-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sabre-hotel-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sabre-air-itinerary-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/sabre-hotel-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/sabre-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/sabre-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/travel-booking.yaml
created: '2026-03-18'
description: Sabre Corporation is a leading technology provider for the global travel industry, operating one of the world's largest travel marketplaces through its Global Distribution System (GDS). Sabre provides APIs for air shopping, booking, hotel reservations, car rentals, rail ticketing, and travel agency workflow automation to airlines, hotels, travel agencies, and online travel agencies (OTAs).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 37
  name: Sabre Context
  property_count: 10
  slug: sabre-context
layout: provider
modified: '2026-05-02'
name: Sabre
rules:
- name: Sabre API Rules
  rule_count: 9
  severity_counts:
    error: 1
    hint: 0
    info: 4
    warn: 4
  slug: sabre-rules
skills: []
slug: sabre
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sabre\nname: Sabre\ndescription: >-\n  Sabre Corporation is a leading technology provider for the global travel\n  industry, operating one of the world's largest travel marketplaces through\n  its Global Distribution System (GDS). Sabre provides APIs for air shopping,\n  booking, hotel reservations, car rentals, rail ticketing, and travel agency\n  workflow automation to airlines, hotels, travel agencies, and online travel\n  agencies (OTAs).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Travel\n  - GDS\n  - Airlines\n  - Hotels\n  - Car Rental\n  - Booking\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sabre:bargain-finder-max\n    name: Sabre Bargain Finder Max API\n    description: >-\n      Sabre Bargain Finder Max (BFM) API provides low-fare search capabilities\n    \
  \  for air shopping, returning optimal flight itineraries with pricing across\n      Sabre's global airline content inventory including ATPCO, LCC, and NDC\n      content. Supports one-way, round-trip, open-jaw, and multi-city searches\n      with flexible date ranges and cabin preferences.\n    humanURL: https://developer.sabre.com/\n    tags:\n      - Travel\n      - Airlines\n      - GDS\n      - Air Shopping\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sabre.com/\n      - type: OpenAPI\n        url: openapi/sabre-bargain-finder-max-openapi.yml\n\n  - aid: sabre:air-booking\n    name: Sabre Air Booking API\n    description: >-\n      Sabre Air Booking API enables flight booking, passenger name record (PNR)\n      creation and management, seat selection, ticketing, and booking\n      modification for travel agencies and online travel applications. Supports\n      NDC offer booking, ancillary services, and PNR queue management.\n    humanURL:\
  \ https://developer.sabre.com/\n    tags:\n      - Travel\n      - Airlines\n      - GDS\n      - Booking\n      - PNR\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sabre.com/\n      - type: SDKs\n        url: https://github.com/SabreDevStudio/postman-collections\n\n  - aid: sabre:hotels\n    name: Sabre Hotels API\n    description: >-\n      Sabre Hotels API provides hotel search, availability, rate shopping,\n      content retrieval, and booking APIs for travel agencies and OTAs,\n      accessing Sabre's global lodging content covering over 2 million\n      properties and SynXis hotel distribution network. Supports radius search,\n      amenity filters, chain preferences, and cancellation management.\n    humanURL: https://developer.sabre.com/\n    tags:\n      - Travel\n      - Hotels\n      - GDS\n      - Booking\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sabre.com/\n      - type: SDKs\n\
  \        url: https://github.com/SabreDevStudio/get-hotel-avail-v2-sample-nodejs\n      - type: OpenAPI\n        url: openapi/sabre-hotels-openapi.yml\n\n  - aid: sabre:cars\n    name: Sabre Cars API\n    description: >-\n      Sabre Cars API provides car rental search, availability, rate shopping,\n      reservation, and management APIs for travel agencies and OTAs, connecting\n      to over 40 global car rental brands across 40,000 locations through\n      Sabre's GDS distribution.\n    humanURL: https://developer.sabre.com/\n    tags:\n      - Travel\n      - Car Rental\n      - GDS\n      - Booking\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sabre.com/\n\n  - aid: sabre:destination-content\n    name: Sabre Destination Content API\n    description: >-\n      Sabre Destination Content API provides destination guides, points of\n      interest, geo data, and travel inspiration content for travel applications\n      and itinerary planning\
  \ tools.\n    humanURL: https://developer.sabre.com/\n    tags:\n      - Travel\n      - Destination\n      - Content\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sabre.com/\n\n  - aid: sabre:booking-management\n    name: Sabre Booking Management API\n    description: >-\n      Sabre Booking Management API provides unified management of multi-segment\n      travel reservations including flights, hotels, and car rentals within a\n      single booking record. Supports booking creation, retrieval, modification,\n      and cancellation.\n    humanURL: https://developer.sabre.com/docs/rest_apis/trip/orders/booking_management\n    tags:\n      - Travel\n      - Booking\n      - GDS\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.sabre.com/docs/rest_apis/trip/orders/booking_management\n\n  - aid: sabre:rail\n    name: Sabre Rail API\n    description: >-\n      Sabre Rail API provides rail ticket search,\
  \ booking, and management\n      capabilities connecting to over 30 rail operators worldwide for travel\n      agencies and multi-modal booking platforms.\n    humanURL: https://developer.sabre.com/\n    tags:\n      - Travel\n      - Rail\n      - GDS\n      - Booking\n    properties:\n      - type: Documentation\n        url: https://developer.sabre.com/\n\ncommon:\n  - type: Portal\n    url: https://developer.sabre.com/\n  - type: Documentation\n    url: https://developer.sabre.com/\n  - type: GettingStarted\n    url: https://developer.sabre.com/guides/travel-agency/api-self-service-guide\n  - type: Authentication\n    url: https://developer.sabre.com/guides/travel-agency/developer-guides/rest-apis-token-credentials\n  - type: Website\n    url: https://www.sabre.com/\n  - type: Support\n    url: https://developer.sabre.com/support\n  - type: Blog\n    url: https://developer.sabre.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/SabreDevStudio\n  - type: SDKs\n   \
  \ url: https://github.com/SabreDevStudio\n  - type: SpectralRules\n    url: rules/sabre-rules.yml\n  - type: JSONSchema\n    url: json-schema/sabre-itinerary-schema.json\n  - type: JSONSchema\n    url: json-schema/sabre-hotel-schema.json\n  - type: JSONStructure\n    url: json-structure/sabre-air-itinerary-structure.json\n  - type: JSONStructure\n    url: json-structure/sabre-hotel-structure.json\n  - type: JSONLDContext\n    url: json-ld/sabre-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/sabre-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/travel-booking.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/apis.yml
tags:
- Travel
- GDS
- Airlines
- Hotels
- Car Rental
- Booking
url: https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/apis.yml
use_cases: []
---
