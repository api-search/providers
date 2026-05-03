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
common:
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
created: ''
description: Tripadvisor is the world's largest travel guidance platform, helping hundreds of millions of travelers each month find places to stay, things to do, and restaurants through reviews, photos, and tools.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Tripadvisor Context
  property_count: 7
  slug: tripadvisor-context
layout: provider
modified: '2026-03-20'
name: tripadvisor
skills: []
slug: tripadvisor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tripadvisor\nurl: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml\nmodified: '2026-03-20'\napis:\n  - aid: tripadvisor:content-api\n    name: Tripadvisor Content API\n    tags:\n      - Attractions\n      - Hotels\n      - Locations\n      - Restaurants\n      - Reviews\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.content.tripadvisor.com\n    humanURL: https://developer-tripadvisor.com/content-api/\n    properties:\n      - url: https://developer-tripadvisor.com/content-api/\n        type: Documentation\n      - url: openapi/tripadvisor-content-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Tripadvisor Content API provides developers with access to Tripadvisor's\n      extensive dataset of more than 7.5 million locations, 1 billion reviews and\n      opinions, and content in 29 languages. The API includes endpoints for location\n\
  \      search, location details, location photos, and location reviews, enabling\n      developers to integrate rich travel content into their websites and\n      applications. The first 5,000 API calls per month are free, making it\n      accessible for initial development and testing.\n  - aid: tripadvisor:hotel-availability-check-api\n    name: Tripadvisor Hotel Availability Check API\n    tags:\n      - Availability\n      - Booking\n      - Hospitality\n      - Hotels\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/\n    properties:\n      - url: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/\n        type: Documentation\n      - url: openapi/tripadvisor-hotel-availability-check-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Tripadvisor\
  \ Hotel Availability Check (HAC) API allows hotel booking\n      partners to display their availability and pricing on Tripadvisor. When a\n      user views a hotel page, Tripadvisor sends HTTP POST requests to the\n      partner's API to retrieve real-time price and availability data. The API\n      supports batch requests for multiple hotels and requires responses within\n      5 seconds on average. The current version (v8) provides richer availability\n      data to help partners increase conversions.\n  - aid: tripadvisor:hotel-inventory-api\n    name: Tripadvisor Hotel Inventory API\n    tags:\n      - Connectivity\n      - Hospitality\n      - Hotels\n      - Inventory\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/documentation/hotel_inventory/\n    properties:\n      - url: https://developer-tripadvisor.com/connectivity-solutions/hotel-availability-check-api/documentation/hotel_inventory/\n\
  \        type: Documentation\n      - url: openapi/tripadvisor-hotel-availability-check-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Tripadvisor Hotel Inventory API enables connectivity partners to manage\n      their hotel inventory listings on the Tripadvisor platform. Partners use\n      this API to register and update the hotels they can provide availability\n      and pricing data for, ensuring that their connected properties are accurately\n      represented. This API works in conjunction with the Hotel Availability Check\n      API as part of Tripadvisor's connectivity solutions for the hospitality\n      industry.\ncommon:\n  - type: JSON-LD\n    url: json-ld/tripadvisor-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tripadvisor-location-schema.json\n  - type: JSONSchema\n    url: json-schema/tripadvisor-review-schema.json\n  - type: JSONSchema\n    url: json-schema/tripadvisor-hotel-availability-schema.json\ndescription: >-\n  Tripadvisor\
  \ is the world's largest travel guidance platform, helping hundreds of\n  millions of travelers each month find places to stay, things to do, and restaurants\n  through reviews, photos, and tools.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/tripadvisor/refs/heads/main/apis.yml
use_cases: []
---
