---
api_count: 8
apis:
- description: Track API allows customers and partners to retrieve up-to-the-minute package and shipment status, scan events, delivery details, and proof of delivery using tracking numbers, reference numbers, or TCN
  name: FedEx Track API
  slug: track
- description: Ship API lets developers create domestic and international shipments, generate shipping labels, validate addresses, schedule pickups, and manage end-to-end shipment workflows programmatically.
  name: FedEx Ship API
  slug: ship
- description: Rate API returns rate quotes and transit times for FedEx Express, Ground, Freight, and SmartPost services so applications can present pricing and delivery options at checkout or during fulfillment.
  name: FedEx Rate API
  slug: rate
- description: Address Validation API verifies postal addresses for deliverability, classifies them as residential or commercial, and corrects common formatting and spelling issues prior to shipment creation.
  name: FedEx Address Validation API
  slug: address-validation
- description: Pickup API provides programmatic access to schedule, modify, and cancel package pickups, and to determine pickup availability for a given origin and service combination.
  name: FedEx Pickup API
  slug: pickup
- description: Locations API helps applications find FedEx Office, FedEx Ship Center, drop boxes, and authorized ship centers near a given address or coordinate, including hours of operation and supported services.
  name: FedEx Locations API
  slug: locations
- description: Authorization API issues OAuth 2.0 access tokens used to authenticate all other FedEx API calls. Tokens are obtained via client credentials generated from a FedEx Developer Portal project.
  name: FedEx Authorization API
  slug: authorization
- description: Shipment Visibility Webhook pushes near real-time tracking events to a registered HTTPS endpoint, eliminating the need to repeatedly poll the Track API for shipment status changes.
  name: FedEx Shipment Visibility Webhook
  slug: shipment-visibility-webhook
common:
- title: ''
  type: Website
  url: https://www.fedex.com/
- title: ''
  type: Documentation
  url: https://developer.fedex.com/api/en-us/home.html
- title: ''
  type: Getting Started
  url: https://developer.fedex.com/api/en-us/get-started.html
- title: ''
  type: Catalog
  url: https://developer.fedex.com/api/en-us/catalog.html
- title: ''
  type: Sign Up
  url: https://developer.fedex.com/api/en-us/home.html
created: '2025-03-01'
description: FedEx is a logistics company that provides shipping and delivery services worldwide. They offer a range of solutions for individuals and businesses, including express shipping, freight services, and e-commerce fulfillment. FedEx publishes a suite of REST APIs covering tracking, shipping, rating, address validation, pickup, locator, trade documents, and post-shipment visibility through their developer portal.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: FedEx
skills: []
slug: fedex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fedex\nname: FedEx\ndescription: >-\n  FedEx is a logistics company that provides shipping and delivery services\n  worldwide. They offer a range of solutions for individuals and businesses,\n  including express shipping, freight services, and e-commerce fulfillment.\n  FedEx publishes a suite of REST APIs covering tracking, shipping, rating,\n  address validation, pickup, locator, trade documents, and post-shipment\n  visibility through their developer portal.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - Address Validation\n  - Freight\n  - Logistics\n  - Pickup\n  - Rating\n  - Shipping\n  - Tracking\n  - Webhooks\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fedex/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: fedex:track\n    name: FedEx Track API\n    description: >-\n      Track\
  \ API allows customers and partners to retrieve up-to-the-minute\n      package and shipment status, scan events, delivery details, and proof\n      of delivery using tracking numbers, reference numbers, or TCN.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/track/v1/docs.html\n    baseURL: https://apis.fedex.com\n    tags:\n      - Tracking\n      - Shipping\n      - Logistics\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/track/v1/docs.html\n      - type: Getting Started\n        url: https://developer.fedex.com/api/en-us/get-started.html\n  - aid: fedex:ship\n    name: FedEx Ship API\n    description: >-\n      Ship API lets developers create domestic and international shipments,\n      generate shipping labels, validate addresses, schedule pickups, and\n      manage end-to-end shipment workflows programmatically.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/ship/v1/docs.html\n    baseURL: https://apis.fedex.com\n\
  \    tags:\n      - Shipping\n      - Labels\n      - Logistics\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/ship/v1/docs.html\n  - aid: fedex:rate\n    name: FedEx Rate API\n    description: >-\n      Rate API returns rate quotes and transit times for FedEx Express,\n      Ground, Freight, and SmartPost services so applications can present\n      pricing and delivery options at checkout or during fulfillment.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/rate/v1/docs.html\n    baseURL: https://apis.fedex.com\n    tags:\n      - Rating\n      - Shipping\n      - Pricing\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/rate/v1/docs.html\n  - aid: fedex:address-validation\n    name: FedEx Address Validation API\n    description: >-\n      Address Validation API verifies postal addresses for deliverability,\n      classifies them as residential or commercial,\
  \ and corrects common\n      formatting and spelling issues prior to shipment creation.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/address-validation/v1/docs.html\n    baseURL: https://apis.fedex.com\n    tags:\n      - Address Validation\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/address-validation/v1/docs.html\n  - aid: fedex:pickup\n    name: FedEx Pickup API\n    description: >-\n      Pickup API provides programmatic access to schedule, modify, and cancel\n      package pickups, and to determine pickup availability for a given\n      origin and service combination.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/pickup/v1/docs.html\n    baseURL: https://apis.fedex.com\n    tags:\n      - Pickup\n      - Shipping\n      - Logistics\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/pickup/v1/docs.html\n  - aid: fedex:locations\n\
  \    name: FedEx Locations API\n    description: >-\n      Locations API helps applications find FedEx Office, FedEx Ship Center,\n      drop boxes, and authorized ship centers near a given address or\n      coordinate, including hours of operation and supported services.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/locations/v1/docs.html\n    baseURL: https://apis.fedex.com\n    tags:\n      - Locations\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/locations/v1/docs.html\n  - aid: fedex:authorization\n    name: FedEx Authorization API\n    description: >-\n      Authorization API issues OAuth 2.0 access tokens used to authenticate\n      all other FedEx API calls. Tokens are obtained via client credentials\n      generated from a FedEx Developer Portal project.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/authorization/v1/docs.html\n    baseURL: https://apis.fedex.com\n    tags:\n\
  \      - Authentication\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/authorization/v1/docs.html\n  - aid: fedex:shipment-visibility-webhook\n    name: FedEx Shipment Visibility Webhook\n    description: >-\n      Shipment Visibility Webhook pushes near real-time tracking events to a\n      registered HTTPS endpoint, eliminating the need to repeatedly poll the\n      Track API for shipment status changes.\n    humanURL: https://developer.fedex.com/api/en-us/catalog/svm/v1/docs.html\n    baseURL: https://apis.fedex.com\n    tags:\n      - Webhooks\n      - Tracking\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://developer.fedex.com/api/en-us/catalog/svm/v1/docs.html\ncommon:\n  - type: Website\n    url: https://www.fedex.com/\n  - type: Documentation\n    url: https://developer.fedex.com/api/en-us/home.html\n  - type: Getting Started\n    url: https://developer.fedex.com/api/en-us/get-started.html\n\
  \  - type: Catalog\n    url: https://developer.fedex.com/api/en-us/catalog.html\n  - type: Sign Up\n    url: https://developer.fedex.com/api/en-us/home.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fedex/refs/heads/main/apis.yml
tags:
- Address Validation
- Freight
- Logistics
- Pickup
- Rating
- Shipping
- Tracking
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/fedex/refs/heads/main/apis.yml
use_cases: []
---
