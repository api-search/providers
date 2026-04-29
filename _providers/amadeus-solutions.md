---
api_count: 4
api_specs:
- filename: amadeus-solutions-flight-offers-search-openapi.yaml
  format: yaml
  label: Flight Offers Search API
  slug: flight-offers-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-flight-offers-search-openapi.yaml
- filename: amadeus-solutions-flight-offers-price-openapi.yaml
  format: yaml
  label: Flight Offers Price API
  slug: flight-offers-price-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-flight-offers-price-openapi.yaml
- filename: amadeus-solutions-branded-fares-upsell-openapi.yaml
  format: yaml
  label: Branded Fares Upsell API
  slug: branded-fares-upsell-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-branded-fares-upsell-openapi.yaml
- filename: amadeus-solutions-seat-map-display-openapi.yaml
  format: yaml
  label: Seat Map Display API
  slug: seat-map-display-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/openapi/amadeus-solutions-seat-map-display-openapi.yaml
apis:
- description: 'The Amadeus Flight Offers Search API enables searching and comparing flight offers from over 400 airlines. Search one-way, round-trip, or multi-city itineraries with cabin class, baggage, and pricing '
  name: Flight Offers Search API
  slug: flight-offers-search-api
- description: The Amadeus Flight Offers Price API confirms the availability and price of a flight offer before booking. Validates current pricing, seat availability, and fare conditions for offers returned by Fligh
  name: Flight Offers Price API
  slug: flight-offers-price-api
- description: The Amadeus Branded Fares Upsell API provides upgrade options for travelers, enabling upsell from basic economy to premium economy, business, or first class branded fares. Returns available upgrade op
  name: Branded Fares Upsell API
  slug: branded-fares-upsell-api
- description: The Amadeus Seat Map Display API provides cabin layout and seat availability information for a flight. Returns detailed seat maps with seat characteristics, availability status, and pricing for seat s
  name: Seat Map Display API
  slug: seat-map-display-api
capabilities:
- description: Unified workflow capability for complete flight shopping encompassing search, pricing, upsell, and seat selection. Used by OTA developers, airline retailing platforms, and travel chatbots to build end
  name: Amadeus Flight Shopping
  slug: flight-shopping
common:
- title: ''
  type: Portal
  url: https://developers.amadeus.com/
- title: ''
  type: GettingStarted
  url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/
- title: ''
  type: Authentication
  url: https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262
- title: ''
  type: SignUp
  url: https://developers.amadeus.com/register
- title: ''
  type: Pricing
  url: https://developers.amadeus.com/pricing
- title: ''
  type: Blog
  url: https://developers.amadeus.com/blog
- title: ''
  type: FAQ
  url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/
- title: ''
  type: Support
  url: https://developers.amadeus.com/support
- title: ''
  type: TermsOfService
  url: https://developers.amadeus.com/legal/terms-and-conditions
- title: ''
  type: PrivacyPolicy
  url: https://developers.amadeus.com/legal/privacy-policy
- title: ''
  type: GitHubOrganization
  url: https://github.com/amadeus4dev
- title: Python SDK
  type: SDK
  url: https://github.com/amadeus4dev/amadeus-python
- title: Node.js SDK
  type: SDK
  url: https://github.com/amadeus4dev/amadeus-node
- title: Java SDK
  type: SDK
  url: https://github.com/amadeus4dev/amadeus-java
- title: ''
  type: StatusPage
  url: https://developers.amadeus.com/status
- title: ''
  type: SpectralRules
  url: rules/amadeus-solutions-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/flight-shopping.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amadeus-solutions-vocabulary.yaml
created: '2024-01-01'
description: Amadeus is a leading technology partner for the global travel industry, providing technology solutions for airlines, airports, hotels, travel sellers, and corporate travel. The Amadeus platform includes a global distribution system (GDS), passenger service systems, airport operations, hospitality management, and a suite of APIs enabling developers to search, price, book, and manage travel across air, hotel, and ground transportation.
features:
- description: Access flight schedules and availability from over 400 airlines through a single integration with the Amadeus GDS.
  name: Global Flight Inventory
- description: Connect to airline NDC offers alongside traditional GDS content for a comprehensive view of available fares and ancillaries.
  name: NDC Content Support
- description: Display branded fare options with included services, restrictions, and price differences to enable informed purchase decisions.
  name: Branded Fares and Fare Families
- description: Access seat selection, baggage, meals, and other ancillary services through integrated APIs alongside fare shopping.
  name: Ancillary Services
- description: Confirm current pricing and availability before booking with the Flight Offers Price API to prevent pricing discrepancies.
  name: Real-Time Pricing
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Convert searched and priced flight offers into confirmed bookings using the Flight Create Orders API.
  name: Amadeus Flight Create Orders
- description: Combine flight search with hotel search to build complete trip planning experiences for travelers.
  name: Amadeus Hotel Search
- description: Enhance destination content alongside flight search with attractions, experiences, and activities data.
  name: Amadeus Points of Interest
- description: Add ground transportation options to flight itineraries through the Transfer Search API.
  name: Amadeus Transfer Search
- description: Integrate travel payments processing through Amadeus Outpayce for airline and OTA payment acceptance.
  name: Outpayce (Payments)
jsonld:
- class_count: 22
  name: Amadeus Branded Fares Upsell Context
  property_count: 56
  slug: amadeus-branded-fares-upsell-context
- class_count: 37
  name: Amadeus Flight Offers Price Context
  property_count: 98
  slug: amadeus-flight-offers-price-context
- class_count: 32
  name: Amadeus Flight Offers Search Context
  property_count: 94
  slug: amadeus-flight-offers-search-context
- class_count: 48
  name: Amadeus Seat Map Display Context
  property_count: 136
  slug: amadeus-seat-map-display-context
layout: provider
modified: '2026-04-19'
name: Amadeus Solutions
rules:
- name: Amadeus Solutions API Rules
  rule_count: 15
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 4
  slug: amadeus-solutions-spectral-rules
skills: []
slug: amadeus-solutions
solutions:
- description: Next-generation airline retailing platform enabling offer and order management for airlines pursuing NDC-based retailing strategies.
  name: Amadeus Nevio (Airline Retailing)
- description: Core passenger service system for full-service carriers providing reservations, inventory management, and departure control.
  name: Amadeus Altéa (Passenger Service System)
- description: Distribution platform for travel agencies providing GDS access, NDC content, and LCC integrations through a unified API.
  name: Amadeus Selling Platform Connect
- description: Corporate travel and expense management platform integrated with Microsoft Teams and major enterprise collaboration tools.
  name: Amadeus Cytric (Corporate Travel)
- description: Airport operations technology including baggage, passenger experience, ground handling, and border control solutions.
  name: Amadeus Airport IT
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amadeus-solutions\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/apis.yml\nname: Amadeus Solutions\ntags:\n  - Airlines\n  - Booking\n  - Flights\n  - GDS\n  - Hotels\n  - Travel\n  - Travel Technology\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Amadeus is a leading technology partner for the global travel industry,\n  providing technology solutions for airlines, airports, hotels, travel sellers,\n  and corporate travel. The Amadeus platform includes a global distribution\n  system (GDS), passenger service systems, airport operations, hospitality\n  management, and a suite of APIs enabling developers to search, price, book,\n  and manage travel across air, hotel, and ground transportation.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amadeus-solutions:flight-offers-search-api\n    name: Flight Offers Search\
  \ API\n    description: >-\n      The Amadeus Flight Offers Search API enables searching and comparing\n      flight offers from over 400 airlines. Search one-way, round-trip, or\n      multi-city itineraries with cabin class, baggage, and pricing filters.\n      Returns comprehensive fare details including branded fares, ancillaries,\n      and pricing breakdowns.\n    humanURL: https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search\n    baseURL: https://test.api.amadeus.com/v2\n    tags:\n      - Airlines\n      - Flights\n      - Search\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search\n      - type: APIReference\n        url: https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search/api-reference\n      - type: OpenAPI\n        url: openapi/amadeus-solutions-flight-offers-search-openapi.yaml\n  - aid:\
  \ amadeus-solutions:flight-offers-price-api\n    name: Flight Offers Price API\n    description: >-\n      The Amadeus Flight Offers Price API confirms the availability and price\n      of a flight offer before booking. Validates current pricing, seat\n      availability, and fare conditions for offers returned by Flight Offers\n      Search, ensuring accurate pricing at time of reservation.\n    humanURL: https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price\n    baseURL: https://test.api.amadeus.com/v1\n    tags:\n      - Airlines\n      - Flights\n      - Pricing\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price\n      - type: OpenAPI\n        url: openapi/amadeus-solutions-flight-offers-price-openapi.yaml\n  - aid: amadeus-solutions:branded-fares-upsell-api\n    name: Branded Fares Upsell API\n    description: >-\n      The Amadeus Branded\
  \ Fares Upsell API provides upgrade options for\n      travelers, enabling upsell from basic economy to premium economy, business,\n      or first class branded fares. Returns available upgrade options with fare\n      families, services included, and price differences.\n    humanURL: https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell\n    baseURL: https://test.api.amadeus.com/v1\n    tags:\n      - Airlines\n      - Ancillaries\n      - Flights\n      - Upsell\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell\n      - type: OpenAPI\n        url: openapi/amadeus-solutions-branded-fares-upsell-openapi.yaml\n  - aid: amadeus-solutions:seat-map-display-api\n    name: Seat Map Display API\n    description: >-\n      The Amadeus Seat Map Display API provides cabin layout and seat\n      availability information for a flight. Returns detailed seat maps with\n\
  \      seat characteristics, availability status, and pricing for seat selection\n      during the booking process.\n    humanURL: https://developers.amadeus.com/self-service/category/flights/api-doc/seat-map-display\n    baseURL: https://test.api.amadeus.com/v1\n    tags:\n      - Airlines\n      - Ancillaries\n      - Flights\n      - Seats\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/flights/api-doc/seat-map-display\n      - type: OpenAPI\n        url: openapi/amadeus-solutions-seat-map-display-openapi.yaml\ncommon:\n  - type: Portal\n    url: https://developers.amadeus.com/\n  - type: GettingStarted\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/\n  - type: Authentication\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262\n  - type: SignUp\n    url: https://developers.amadeus.com/register\n  - type: Pricing\n    url: https://developers.amadeus.com/pricing\n\
  \  - type: Blog\n    url: https://developers.amadeus.com/blog\n  - type: FAQ\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/\n  - type: Support\n    url: https://developers.amadeus.com/support\n  - type: TermsOfService\n    url: https://developers.amadeus.com/legal/terms-and-conditions\n  - type: PrivacyPolicy\n    url: https://developers.amadeus.com/legal/privacy-policy\n  - type: GitHubOrganization\n    url: https://github.com/amadeus4dev\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-python\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-node\n    title: Node.js SDK\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-java\n    title: Java SDK\n  - type: StatusPage\n    url: https://developers.amadeus.com/status\n  - type: SpectralRules\n    url: rules/amadeus-solutions-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/flight-shopping.yaml\n  - type: Vocabulary\n\
  \    url: vocabulary/amadeus-solutions-vocabulary.yaml\n  - type: Solutions\n    data:\n      - name: Amadeus Nevio (Airline Retailing)\n        description: >-\n          Next-generation airline retailing platform enabling offer and order\n          management for airlines pursuing NDC-based retailing strategies.\n      - name: Amadeus Altéa (Passenger Service System)\n        description: >-\n          Core passenger service system for full-service carriers providing\n          reservations, inventory management, and departure control.\n      - name: Amadeus Selling Platform Connect\n        description: >-\n          Distribution platform for travel agencies providing GDS access,\n          NDC content, and LCC integrations through a unified API.\n      - name: Amadeus Cytric (Corporate Travel)\n        description: >-\n          Corporate travel and expense management platform integrated with\n          Microsoft Teams and major enterprise collaboration tools.\n      - name: Amadeus\
  \ Airport IT\n        description: >-\n          Airport operations technology including baggage, passenger\n          experience, ground handling, and border control solutions.\n  - type: Features\n    data:\n      - name: Global Flight Inventory\n        description: >-\n          Access flight schedules and availability from over 400 airlines\n          through a single integration with the Amadeus GDS.\n      - name: NDC Content Support\n        description: >-\n          Connect to airline NDC offers alongside traditional GDS content\n          for a comprehensive view of available fares and ancillaries.\n      - name: Branded Fares and Fare Families\n        description: >-\n          Display branded fare options with included services, restrictions,\n          and price differences to enable informed purchase decisions.\n      - name: Ancillary Services\n        description: >-\n          Access seat selection, baggage, meals, and other ancillary\n          services through integrated\
  \ APIs alongside fare shopping.\n      - name: Real-Time Pricing\n        description: >-\n          Confirm current pricing and availability before booking with the\n          Flight Offers Price API to prevent pricing discrepancies.\n  - type: UseCases\n    data:\n      - name: Flight Search and Booking Engine\n        description: >-\n          Build complete flight shopping experiences searching, pricing, and\n          booking flights across hundreds of airlines through a unified API.\n      - name: Airline Retailing Platform\n        description: >-\n          Power airline direct channels with offer creation, branded fares,\n          seat maps, and ancillary upsell capabilities.\n      - name: Corporate Travel Management\n        description: >-\n          Enable policy-compliant flight shopping for corporate travelers with\n          fare filtering, approval workflows, and reporting.\n      - name: Travel Metasearch\n        description: >-\n          Aggregate flight offers for\
  \ price comparison across airlines with\n          detailed fare family and service information.\n      - name: AI Travel Assistant\n        description: >-\n          Enable conversational travel assistants to search and compare\n          flights using natural language queries.\n  - type: Integrations\n    data:\n      - name: Amadeus Flight Create Orders\n        description: >-\n          Convert searched and priced flight offers into confirmed bookings\n          using the Flight Create Orders API.\n      - name: Amadeus Hotel Search\n        description: >-\n          Combine flight search with hotel search to build complete trip\n          planning experiences for travelers.\n      - name: Amadeus Points of Interest\n        description: >-\n          Enhance destination content alongside flight search with\n          attractions, experiences, and activities data.\n      - name: Amadeus Transfer Search\n        description: >-\n          Add ground transportation options to flight\
  \ itineraries through\n          the Transfer Search API.\n      - name: Outpayce (Payments)\n        description: >-\n          Integrate travel payments processing through Amadeus Outpayce for\n          airline and OTA payment acceptance.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/apis.yml
tags:
- Airlines
- Booking
- Flights
- GDS
- Hotels
- Travel
- Travel Technology
url: https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/apis.yml
use_cases:
- description: Build complete flight shopping experiences searching, pricing, and booking flights across hundreds of airlines through a unified API.
  name: Flight Search and Booking Engine
- description: Power airline direct channels with offer creation, branded fares, seat maps, and ancillary upsell capabilities.
  name: Airline Retailing Platform
- description: Enable policy-compliant flight shopping for corporate travelers with fare filtering, approval workflows, and reporting.
  name: Corporate Travel Management
- description: Aggregate flight offers for price comparison across airlines with detailed fare family and service information.
  name: Travel Metasearch
- description: Enable conversational travel assistants to search and compare flights using natural language queries.
  name: AI Travel Assistant
---
