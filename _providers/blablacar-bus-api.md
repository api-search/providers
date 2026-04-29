---
api_count: 1
api_specs:
- filename: blablacar-bus-api-openapi.yaml
  format: yaml
  label: BlaBlaCar Bus API
  slug: blablacar-bus-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blablacar-bus-api/refs/heads/main/openapi/blablacar-bus-api-openapi.yaml
apis:
- description: REST API for integrating with BlaBlaCar Bus (formerly BlaBlaBus) coach booking platform. Enables partners to search routes, check seat availability, create bookings, manage tickets, and receive bookin
  name: BlaBlaCar Bus API
  slug: blablacar-bus-api
capabilities:
- description: Workflow capability for end-to-end coach booking on the BlaBlaCar Bus network. Enables OTAs, travel aggregators, and corporate travel platforms to search routes and trips, create bookings, manage tick
  name: BlaBlaCar Bus Booking
  slug: blablacar-bus-booking
common:
- title: ''
  type: Website
  url: https://www.blablacar.com/bus
- title: ''
  type: Documentation
  url: https://bus-api.blablacar.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/blablacar
- title: ''
  type: TermsOfService
  url: https://www.blablacar.com/about-us/terms-and-conditions
- title: ''
  type: PrivacyPolicy
  url: https://www.blablacar.com/about-us/privacy-policy
- title: ''
  type: SpectralRules
  url: rules/blablacar-bus-api-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/blablacar-bus-booking.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/blablacar-bus-api-vocabulary.yaml
created: '2024-11-14'
description: BlaBlaCar Bus API enables transport operators, OTAs, and travel aggregators to integrate with BlaBlaCar's coach and bus booking platform across Europe. The API provides access to route search, seat availability, booking creation, ticket management, and passenger notifications. BlaBlaCar Bus operates coach services across France, Germany, Poland, Spain, Italy, Ukraine, and other European markets under the BlaBlaBus brand.
features:
- description: Search available coach routes between origin and destination stations across European markets with departure dates and passenger counts.
  name: Route Search
- description: Check real-time seat availability and pricing for specific routes, trips, and departure times.
  name: Seat Availability
- description: Create confirmed bookings for passengers with seat selection, passenger details, and payment processing integration.
  name: Booking Creation
- description: Retrieve, modify, and cancel tickets with electronic ticket delivery and QR code generation.
  name: Ticket Management
- description: Access comprehensive station data including names, addresses, GPS coordinates, and amenities across the BlaBlaCar Bus network.
  name: Station Information
- description: Single API integration covering coach routes across France, Germany, Poland, Spain, Italy, Ukraine, and other European markets.
  name: Multi-Market Coverage
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: BlaBlaCar Bus complements the carpooling marketplace, enabling multimodal journey planning combining bus and ridesharing.
  name: BlaBlaCar Carpooling
- description: Station coordinates and route data can be overlaid on mapping platforms for journey visualization.
  name: Google Maps Platform
jsonld:
- class_count: 13
  name: Blablacar Bus Api Context
  property_count: 20
  slug: blablacar-bus-api-context
layout: provider
modified: '2026-04-19'
name: BlaBlaCar Bus API
rules:
- name: BlaBlaCar Bus API API Rules
  rule_count: 36
  severity_counts:
    error: 13
    hint: 0
    info: 5
    warn: 18
  slug: blablacar-bus-api-spectral-rules
skills: []
slug: blablacar-bus-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: blablacar-bus-api\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/blablacar-bus-api/refs/heads/main/apis.yml\nname: BlaBlaCar Bus API\ndescription: >-\n  BlaBlaCar Bus API enables transport operators, OTAs, and travel aggregators to\n  integrate with BlaBlaCar's coach and bus booking platform across Europe. The API\n  provides access to route search, seat availability, booking creation, ticket\n  management, and passenger notifications. BlaBlaCar Bus operates coach services\n  across France, Germany, Poland, Spain, Italy, Ukraine, and other European markets\n  under the BlaBlaBus brand.\ntags:\n  - Booking\n  - Buses\n  - Coach\n  - Europe\n  - Mobility\n  - Ticketing\n  - Transportation\n  - Travel\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-14'\nmodified: '2026-04-19'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  - aid: blablacar-bus-api:blablacar-bus-api\n\
  \    name: BlaBlaCar Bus API\n    description: >-\n      REST API for integrating with BlaBlaCar Bus (formerly BlaBlaBus) coach booking\n      platform. Enables partners to search routes, check seat availability, create\n      bookings, manage tickets, and receive booking confirmations. Targeted at OTAs,\n      travel aggregators, mobility platforms, and enterprise travel management companies\n      operating in European markets.\n    humanURL: https://bus-api.blablacar.com/\n    tags:\n      - Booking\n      - Buses\n      - Coach\n      - Europe\n      - Ticketing\n      - Transportation\n    properties:\n      - type: Documentation\n        url: https://bus-api.blablacar.com/\n      - type: OpenAPI\n        url: openapi/blablacar-bus-api-openapi.yaml\ncommon:\n  - type: Website\n    url: https://www.blablacar.com/bus\n  - type: Documentation\n    url: https://bus-api.blablacar.com/\n  - type: GitHubOrganization\n    url: https://github.com/blablacar\n  - type: TermsOfService\n    url:\
  \ https://www.blablacar.com/about-us/terms-and-conditions\n  - type: PrivacyPolicy\n    url: https://www.blablacar.com/about-us/privacy-policy\n  - type: SpectralRules\n    url: rules/blablacar-bus-api-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/blablacar-bus-booking.yaml\n  - type: Vocabulary\n    url: vocabulary/blablacar-bus-api-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Route Search\n        description: >-\n          Search available coach routes between origin and destination stations\n          across European markets with departure dates and passenger counts.\n      - name: Seat Availability\n        description: >-\n          Check real-time seat availability and pricing for specific routes,\n          trips, and departure times.\n      - name: Booking Creation\n        description: >-\n          Create confirmed bookings for passengers with seat selection, passenger\n          details, and payment processing integration.\n      -\
  \ name: Ticket Management\n        description: >-\n          Retrieve, modify, and cancel tickets with electronic ticket delivery\n          and QR code generation.\n      - name: Station Information\n        description: >-\n          Access comprehensive station data including names, addresses, GPS\n          coordinates, and amenities across the BlaBlaCar Bus network.\n      - name: Multi-Market Coverage\n        description: >-\n          Single API integration covering coach routes across France, Germany,\n          Poland, Spain, Italy, Ukraine, and other European markets.\n  - type: UseCases\n    data:\n      - name: OTA Integration\n        description: >-\n          Online travel agencies can search and book BlaBlaCar Bus routes alongside\n          trains, flights, and car rentals for multimodal journey planning.\n      - name: Travel Aggregator\n        description: >-\n          Price comparison and travel search engines can surface BlaBlaCar Bus\n          options in coach\
  \ and intercity bus search results.\n      - name: Corporate Travel\n        description: >-\n          Enterprise travel management companies can include BlaBlaCar Bus as\n          an affordable intercity transport option for business travelers.\n      - name: Mobility Platform\n        description: >-\n          Mobility-as-a-Service platforms can integrate BlaBlaCar Bus as a\n          long-distance transport mode in multimodal journey planning.\n      - name: Reseller Programs\n        description: >-\n          Authorized resellers can distribute BlaBlaCar Bus tickets through\n          their own branded channels and sales touchpoints.\n  - type: Integrations\n    data:\n      - name: BlaBlaCar Carpooling\n        description: >-\n          BlaBlaCar Bus complements the carpooling marketplace, enabling\n          multimodal journey planning combining bus and ridesharing.\n      - name: Google Maps Platform\n        description: >-\n          Station coordinates and route data can\
  \ be overlaid on mapping\n          platforms for journey visualization.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/blablacar-bus-api/refs/heads/main/apis.yml
tags:
- Booking
- Buses
- Coach
- Europe
- Mobility
- Ticketing
- Transportation
- Travel
url: https://raw.githubusercontent.com/api-evangelist/blablacar-bus-api/refs/heads/main/apis.yml
use_cases:
- description: Online travel agencies can search and book BlaBlaCar Bus routes alongside trains, flights, and car rentals for multimodal journey planning.
  name: OTA Integration
- description: Price comparison and travel search engines can surface BlaBlaCar Bus options in coach and intercity bus search results.
  name: Travel Aggregator
- description: Enterprise travel management companies can include BlaBlaCar Bus as an affordable intercity transport option for business travelers.
  name: Corporate Travel
- description: Mobility-as-a-Service platforms can integrate BlaBlaCar Bus as a long-distance transport mode in multimodal journey planning.
  name: Mobility Platform
- description: Authorized resellers can distribute BlaBlaCar Bus tickets through their own branded channels and sales touchpoints.
  name: Reseller Programs
---
