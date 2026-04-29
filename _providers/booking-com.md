---
api_count: 6
apis:
- description: The Booking.com Demand API is a RESTful API that enables Affiliate Partners to access Booking.com's extensive travel inventory. It provides endpoints for searching accommodations such as hotels and ap
  name: Booking.com Demand API
  slug: demand-api
- description: 'The Booking.com Car Rentals API is part of the Demand API and provides endpoints specific to the car rental segment of the connected trip experience. Developers can use it to search for available car '
  name: Booking.com Car Rentals API
  slug: car-rentals-api
- description: 'The Booking.com Connectivity Content API enables Connectivity Partners to register properties and modify their content directly without using the Booking.com extranet. Partners can manage facilities, '
  name: Booking.com Connectivity Content API
  slug: connectivity-content-api
- description: 'The Booking.com Connectivity Reservations API allows Connectivity Partners to retrieve and update reservation information for properties listed on Booking.com. It operates over a PCI-compliant secure '
  name: Booking.com Connectivity Reservations API
  slug: connectivity-reservations-api
- description: The Booking.com Connectivity Rates and Availability API allows Connectivity Partners to set room availability, pricing, and restrictions for properties on Booking.com. Partners can manage advance book
  name: Booking.com Connectivity Rates and Availability API
  slug: connectivity-rates-availability-api
- description: The Booking.com Connectivity Promotions API enables Connectivity Partners to create and manage promotional offers for properties listed on Booking.com. Partners can programmatically set up deals, disc
  name: Booking.com Connectivity Promotions API
  slug: connectivity-promotions-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/booking-com-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/booking-com-accommodation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/booking-com-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/booking-com-promotion-schema.json
created: ''
description: Seamlessly incorporate Booking.com inventory into your travel application.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Booking Com Context
  property_count: 10
  slug: booking-com-context
layout: provider
modified: '2026-04-19'
name: booking-com
skills: []
slug: booking-com
solutions: []
source_yaml: "aid: booking-com\nurl: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/apis.yml\nmodified: '2026-04-19'\napis:\n  - aid: booking-com:demand-api\n    name: Booking.com Demand API\n    tags:\n      - Accommodations\n      - Affiliates\n      - Booking\n      - Hotels\n      - Search\n      - Travel\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://demandapi.booking.com\n    humanURL: https://developers.booking.com/demand/docs/getting-started/overview\n    properties:\n      - url: https://developers.booking.com/demand/docs/getting-started/overview\n        type: Documentation\n      - url: openapi/booking-com-demand-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Booking.com Demand API is a RESTful API that enables Affiliate Partners\n      to access Booking.com's extensive travel inventory. It provides endpoints for\n      searching accommodations such as hotels and\
  \ apartments, checking availability,\n      retrieving reviews, and getting detailed property information. The API uses\n      JSON responses and requires HTTPS POST requests with Affiliate ID and token\n      authentication.\n  - aid: booking-com:car-rentals-api\n    name: Booking.com Car Rentals API\n    tags:\n      - Car Rentals\n      - Transportation\n      - Travel\n      - Vehicles\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://demandapi.booking.com\n    humanURL: https://developers.booking.com/demand/docs/open-api/demand-api/cars\n    properties:\n      - url: https://developers.booking.com/demand/docs/open-api/demand-api/cars\n        type: Documentation\n      - url: openapi/booking-com-car-rentals-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Booking.com Car Rentals API is part of the Demand API and provides\n      endpoints specific to the car rental segment of the connected trip\n     \
  \ experience. Developers can use it to search for available car rentals,\n      retrieve car details, and look up depots and suppliers. The API enables\n      affiliate partners to integrate Booking.com's car rental inventory into\n      their own platforms, offering users the ability to find and book vehicles\n      as part of their travel planning workflow.\n  - aid: booking-com:connectivity-content-api\n    name: Booking.com Connectivity Content API\n    tags:\n      - Connectivity\n      - Content Management\n      - Hotels\n      - Properties\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://supply-xml.booking.com\n    humanURL: https://developers.booking.com/connectivity/docs/content\n    properties:\n      - url: https://developers.booking.com/connectivity/docs/content\n        type: Documentation\n      - url: openapi/booking-com-connectivity-content-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The\
  \ Booking.com Connectivity Content API enables Connectivity Partners to\n      register properties and modify their content directly without using the\n      Booking.com extranet. Partners can manage facilities, rates, rooms, photos,\n      and other property details programmatically. This API is designed for\n      property management systems, channel managers, and other connectivity\n      solutions that need to create and maintain property listings on Booking.com\n      at scale.\n  - aid: booking-com:connectivity-reservations-api\n    name: Booking.com Connectivity Reservations API\n    tags:\n      - Booking\n      - Connectivity\n      - Hotels\n      - Reservations\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://secure-supply-xml.booking.com\n    humanURL: https://developers.booking.com/connectivity/docs\n    properties:\n      - url: https://connect.booking.com/user_guide/site/en-US/res/\n        type: Documentation\n\
  \      - url: openapi/booking-com-connectivity-reservations-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Booking.com Connectivity Reservations API allows Connectivity Partners\n      to retrieve and update reservation information for properties listed on\n      Booking.com. It operates over a PCI-compliant secure endpoint and supports\n      reservation retrieval, confirmation, and modification. This API is\n      essential for property management systems and channel managers that need\n      to synchronize booking data between Booking.com and their own systems\n      in real time.\n  - aid: booking-com:connectivity-rates-availability-api\n    name: Booking.com Connectivity Rates and Availability API\n    tags:\n      - Availability\n      - Connectivity\n      - Inventory\n      - Pricing\n      - Rates\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://supply-xml.booking.com\n    humanURL: https://developers.booking.com/connectivity/docs/ari\n\
  \    properties:\n      - url: https://developers.booking.com/connectivity/docs/ari\n        type: Documentation\n      - url: openapi/booking-com-connectivity-rates-availability-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Booking.com Connectivity Rates and Availability API allows Connectivity\n      Partners to set room availability, pricing, and restrictions for properties\n      on Booking.com. Partners can manage advance booking windows, length of stay\n      requirements, and rate plans programmatically.\n  - aid: booking-com:connectivity-promotions-api\n    name: Booking.com Connectivity Promotions API\n    tags:\n      - Connectivity\n      - Deals\n      - Discounts\n      - Marketing\n      - Promotions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://supply-xml.booking.com\n    humanURL: https://developers.booking.com/connectivity/docs\n    properties:\n      - url: https://developers.booking.com/connectivity/docs\n\
  \        type: Documentation\n      - url: openapi/booking-com-connectivity-promotions-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Booking.com Connectivity Promotions API enables Connectivity Partners to\n      create and manage promotional offers for properties listed on Booking.com. Partners\n      can programmatically set up deals, discounts, and special rates to attract travelers\n      and increase bookings.\ncommon:\n  - type: JSON-LD\n    url: json-ld/booking-com-context.jsonld\n  - type: JSONSchema\n    url: json-schema/booking-com-accommodation-schema.json\n  - type: JSONSchema\n    url: json-schema/booking-com-order-schema.json\n  - type: JSONSchema\n    url: json-schema/booking-com-promotion-schema.json\ndescription: >-\n  Seamlessly incorporate Booking.com inventory into your travel application.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/booking-com/refs/heads/main/apis.yml
use_cases: []
---
