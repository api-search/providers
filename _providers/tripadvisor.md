---
api_count: 3
api_specs:
- filename: tripadvisor-content-api-openapi.yml
  format: yaml
  label: Tripadvisor Content API
  slug: content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/openapi/tripadvisor-content-api-openapi.yml
- filename: tripadvisor-hotel-availability-check-api-openapi.yml
  format: yaml
  label: Tripadvisor Hotel Availability Check API
  slug: hotel-availability-check-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/openapi/tripadvisor-hotel-availability-check-api-openapi.yml
- filename: tripadvisor-hotel-availability-check-api-openapi.yml
  format: yaml
  label: Tripadvisor Hotel Inventory API
  slug: hotel-inventory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/openapi/tripadvisor-hotel-availability-check-api-openapi.yml
apis:
- description: 'The Tripadvisor Content API provides developers with access to Tripadvisor''s extensive dataset of more than 7.5 million locations, 1 billion reviews and opinions, and content in 29 languages. The API '
  name: Tripadvisor Content API
  slug: content-api
- description: The Tripadvisor Hotel Availability Check (HAC) API allows hotel booking partners to display their availability and pricing on Tripadvisor. When a user views a hotel page, Tripadvisor sends HTTP POST r
  name: Tripadvisor Hotel Availability Check API
  slug: hotel-availability-check-api
- description: The Tripadvisor Hotel Inventory API enables connectivity partners to manage their hotel inventory listings on the Tripadvisor platform. Partners use this API to register and update the hotels they can
  name: Tripadvisor Hotel Inventory API
  slug: hotel-inventory-api
capabilities:
- description: Workflow capability for hotel connectivity partners integrating with Tripadvisor's availability and inventory systems. Combines the Hotel Availability Check API and Hotel Inventory API to enable real-
  name: Tripadvisor Hotel Connectivity
  slug: hotel-connectivity
- description: Workflow capability for integrating Tripadvisor's travel content into applications. Combines location search, detail retrieval, photos, and reviews into a unified travel discovery and content enrichme
  name: Tripadvisor Travel Content
  slug: travel-content
common:
- title: ''
  type: Website
  url: https://www.tripadvisor.com
- title: ''
  type: DeveloperPortal
  url: https://developer-tripadvisor.com
- title: ''
  type: Documentation
  url: https://tripadvisor-content-api.readme.io/reference/overview
- title: ''
  type: SignUp
  url: https://developer-tripadvisor.com/content-api/
- title: ''
  type: TermsOfService
  url: https://developer-tripadvisor.com/content-api/terms-of-use/
- title: ''
  type: GitHubOrganization
  url: https://github.com/tripadvisor
- title: ''
  type: GitHubOrganization
  url: https://github.com/tripadvisor-dev
- title: ''
  type: JSON-LD
  url: json-ld/tripadvisor-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tripadvisor-location-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tripadvisor-review-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tripadvisor-hotel-availability-schema.json
- title: ''
  type: SpectralRules
  url: rules/tripadvisor-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/tripadvisor-vocabulary.yml
created: '2026-05-03'
description: Tripadvisor is the world's largest travel guidance platform, helping hundreds of millions of travelers each month find places to stay, things to do, and restaurants through reviews, photos, and tools. The platform maintains over 7.5 million locations and 1 billion reviews across 43 markets and 29 languages. Tripadvisor provides APIs for content integration, hotel connectivity, and restaurant reservations.
features:
- name: Location Search
- name: Nearby Search
- name: Location Details
- name: Location Photos
- name: Location Reviews
- name: Hotel Availability Check
- name: Hotel Inventory Management
- name: 7.5 Million Locations
- name: 1 Billion Reviews
- name: 29 Languages
- name: 43 Markets
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Booking.com
- name: Expedia
- name: Hotels.com
- name: Viator
- name: TheFork
jsonld:
- class_count: 0
  name: Tripadvisor Context
  property_count: 7
  slug: tripadvisor-context
layout: provider
modified: '2026-05-03'
name: Tripadvisor
rules:
- name: Tripadvisor API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 7
  slug: tripadvisor-rules
skills: []
slug: tripadvisor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tripadvisor\nurl: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml\nname: Tripadvisor\ndescription: >-\n  Tripadvisor is the world's largest travel guidance platform, helping hundreds of\n  millions of travelers each month find places to stay, things to do, and restaurants\n  through reviews, photos, and tools. The platform maintains over 7.5 million locations\n  and 1 billion reviews across 43 markets and 29 languages. Tripadvisor provides APIs\n  for content integration, hotel connectivity, and restaurant reservations.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Attractions\n  - Hotels\n  - Hospitality\n  - Restaurants\n  - Reviews\n  - Travel\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tripadvisor:content-api\n    name: Tripadvisor Content API\n    tags:\n      - Attractions\n      - Hotels\n      - Locations\n      - Restaurants\n\
  \      - Reviews\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.content.tripadvisor.com/api/v1\n    humanURL: https://developer-tripadvisor.com/content-api/\n    properties:\n      - url: https://developer-tripadvisor.com/content-api/\n        type: Documentation\n      - url: openapi/tripadvisor-content-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Tripadvisor Content API provides developers with access to Tripadvisor's\n      extensive dataset of more than 7.5 million locations, 1 billion reviews and\n      opinions, and content in 29 languages. The API includes endpoints for location\n      search, nearby search, location details, location photos, and location reviews,\n      enabling developers to integrate rich travel content into their websites and\n      applications. The first 5,000 API calls per month are free, making it\n      accessible for initial development and testing.\n\
  \n  - aid: tripadvisor:hotel-availability-check-api\n    name: Tripadvisor Hotel Availability Check API\n    tags:\n      - Availability\n      - Booking\n      - Connectivity\n      - Hospitality\n      - Hotels\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://partner-endpoint.example.com\n    humanURL: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/\n    properties:\n      - url: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/\n        type: Documentation\n      - url: openapi/tripadvisor-hotel-availability-check-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Tripadvisor Hotel Availability Check (HAC) API allows hotel booking\n      partners to display their availability and pricing on Tripadvisor. When a\n      user views a hotel page, Tripadvisor sends HTTP POST requests to the\n      partner's API to retrieve\
  \ real-time price and availability data. The API\n      supports batch requests for multiple hotels and requires responses within\n      5 seconds on average. The current version (v8) provides richer availability\n      data to help partners increase conversions.\n\n  - aid: tripadvisor:hotel-inventory-api\n    name: Tripadvisor Hotel Inventory API\n    tags:\n      - Connectivity\n      - Hospitality\n      - Hotels\n      - Inventory\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://partner-endpoint.example.com\n    humanURL: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/documentation/hotel_inventory/\n    properties:\n      - url: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/documentation/hotel_inventory/\n        type: Documentation\n      - url: openapi/tripadvisor-hotel-availability-check-api-openapi.yml\n        type: OpenAPI\n\
  \    description: >-\n      The Tripadvisor Hotel Inventory API enables connectivity partners to manage\n      their hotel inventory listings on the Tripadvisor platform. Partners use\n      this API to register and update the hotels they can provide availability\n      and pricing data for, ensuring that their connected properties are accurately\n      represented. This API works in conjunction with the Hotel Availability Check\n      API as part of Tripadvisor's connectivity solutions for the hospitality industry.\n\ncommon:\n  - type: Website\n    url: https://www.tripadvisor.com\n    name: Tripadvisor\n  - type: DeveloperPortal\n    url: https://developer-tripadvisor.com\n    name: Tripadvisor Developer Portal\n  - type: Documentation\n    url: https://tripadvisor-content-api.readme.io/reference/overview\n    name: Content API Reference\n  - type: SignUp\n    url: https://developer-tripadvisor.com/content-api/\n    name: Register for Content API\n  - type: TermsOfService\n    url:\
  \ https://developer-tripadvisor.com/content-api/terms-of-use/\n    name: Content API Terms of Use\n  - type: GitHubOrganization\n    url: https://github.com/tripadvisor\n    name: Tripadvisor GitHub Organization\n  - type: GitHubOrganization\n    url: https://github.com/tripadvisor-dev\n    name: Tripadvisor Developers GitHub\n  - type: JSON-LD\n    url: json-ld/tripadvisor-context.jsonld\n    name: Tripadvisor JSON-LD Context\n  - type: JSONSchema\n    url: json-schema/tripadvisor-location-schema.json\n    name: Location JSON Schema\n  - type: JSONSchema\n    url: json-schema/tripadvisor-review-schema.json\n    name: Review JSON Schema\n  - type: JSONSchema\n    url: json-schema/tripadvisor-hotel-availability-schema.json\n    name: Hotel Availability JSON Schema\n  - url: rules/tripadvisor-rules.yml\n    name: Tripadvisor Spectral Rules\n    type: SpectralRules\n  - url: vocabulary/tripadvisor-vocabulary.yml\n    name: Tripadvisor Vocabulary\n    type: Vocabulary\n  - name: Features\n\
  \    type: Features\n    data:\n      - name: Location Search\n      - name: Nearby Search\n      - name: Location Details\n      - name: Location Photos\n      - name: Location Reviews\n      - name: Hotel Availability Check\n      - name: Hotel Inventory Management\n      - name: 7.5 Million Locations\n      - name: 1 Billion Reviews\n      - name: 29 Languages\n      - name: 43 Markets\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Travel Content Integration\n      - name: Hotel Booking Widget\n      - name: Restaurant Discovery\n      - name: Attraction Finder\n      - name: Hotel Connectivity Partner\n      - name: Travel App Development\n      - name: Review Aggregation\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Booking.com\n      - name: Expedia\n      - name: Hotels.com\n      - name: Viator\n      - name: TheFork\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml
tags:
- Attractions
- Hotels
- Hospitality
- Restaurants
- Reviews
- Travel
url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml
use_cases:
- name: Travel Content Integration
- name: Hotel Booking Widget
- name: Restaurant Discovery
- name: Attraction Finder
- name: Hotel Connectivity Partner
- name: Travel App Development
- name: Review Aggregation
---
