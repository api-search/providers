---
api_count: 7
api_specs:
- filename: uber-riders-openapi.yml
  format: yaml
  label: Uber Riders API
  slug: uber-riders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-riders-openapi.yml
- filename: uber-drivers-openapi.yml
  format: yaml
  label: Uber Drivers API
  slug: uber-drivers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-drivers-openapi.yml
- filename: uber-eats-openapi.yml
  format: yaml
  label: Uber Eats API
  slug: uber-eats
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-eats-openapi.yml
- filename: uber-direct-openapi.yml
  format: yaml
  label: Uber Direct API
  slug: uber-direct
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-direct-openapi.yml
- filename: uber-vouchers-openapi.yml
  format: yaml
  label: Uber Vouchers API
  slug: uber-vouchers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-vouchers-openapi.yml
- filename: uber-businesses-openapi.yml
  format: yaml
  label: Uber for Business API
  slug: uber-businesses
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-businesses-openapi.yml
apis:
- description: The Uber Riders API enables applications to interact with the Uber platform on behalf of riders. It allows requesting rides, getting product listings, price and time estimates, viewing trip history, a
  name: Uber Riders API
  slug: uber-riders
- description: The Uber Drivers API allows partners to access driver profile information, payment history, and trip records. It provides access to driver earnings, completed trips, and partner program data via OAuth
  name: Uber Drivers API
  slug: uber-drivers
- description: The Uber Eats Marketplace API enables partners to programmatically manage stores, menus, and orders on the Uber Eats platform. It supports real-time menu synchronization, order processing, store opera
  name: Uber Eats API
  slug: uber-eats
- description: The Uber Direct API allows merchants to leverage Uber's courier network to deliver their orders. It supports on-demand delivery creation, courier tracking, refunds, and location management. Webhooks p
  name: Uber Direct API
  slug: uber-direct
- description: The Uber Guest Rides API enables businesses to allow their users to request rides from Uber without requiring an Uber account. Uses OAuth 2.0 with the guest.rides scope for authentication.
  name: Uber Guest Rides API
  slug: uber-guest-rides
- description: The Uber Vouchers API allows businesses to create and manage voucher programs and codes for rides and meals. It supports program creation, code generation, bulk distribution, guest management, and cod
  name: Uber Vouchers API
  slug: uber-vouchers
- description: The Uber for Business API enables organizations to automate workflows within their enterprise Uber accounts. Provides access to trip invoices, receipts, and business travel data for expense management
  name: Uber for Business API
  slug: uber-businesses
capabilities:
- description: 'Workflow capability combining Uber Eats (restaurant ordering and store management) and Uber Direct (on-demand courier delivery) APIs. Supports restaurant operators, e-commerce merchants, and delivery '
  name: Uber Food and Delivery
  slug: food-and-delivery
- description: Workflow capability for managing the complete Uber ride lifecycle. Combines the Riders API (ride requests, estimates, products) and Drivers API (driver profile, trips, payments) to support ride-bookin
  name: Uber Ride Management
  slug: ride-management
common: []
created: '2025-02-06'
description: Uber is a global technology platform offering transportation, food delivery, and logistics services. Its developer platform provides APIs for integrating ride requests, food ordering, on-demand delivery, voucher programs, and business travel management into third-party applications. APIs use OAuth 2.0 authentication with scope-based access controls and support both production and sandbox environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Uber Context
  property_count: 30
  slug: uber-context
layout: provider
modified: '2026-05-03'
name: Uber
rules:
- name: Uber API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 9
  slug: uber-rules
skills: []
slug: uber
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uber\nurl: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/apis.yml\napis:\n  - aid: uber:uber-riders\n    name: Uber Riders API\n    tags:\n      - Ride-Sharing\n      - Rides\n      - Products\n      - Estimates\n      - Transportation\n    humanURL: https://developer.uber.com/docs/riders/introduction\n    baseURL: https://api.uber.com/v1.2\n    properties:\n      - url: https://developer.uber.com/docs/riders/references/api\n        type: Documentation\n      - url: https://developer.uber.com/docs/riders/ride-requests/introduction\n        type: Documentation\n      - url: openapi/uber-riders-openapi.yml\n        type: OpenAPI\n      - url: examples/uber-riders-list-products-example.json\n        type: Example\n      - url: examples/uber-riders-create-ride-request-example.json\n        type: Example\n      - url: json-schema/uber-ride-request-schema.json\n        type: JSONSchema\n    description: >-\n      The Uber Riders API enables applications\
  \ to interact with the Uber platform on\n      behalf of riders. It allows requesting rides, getting product listings, price\n      and time estimates, viewing trip history, and managing saved places. Authentication\n      uses OAuth 2.0 bearer tokens.\n\n  - aid: uber:uber-drivers\n    name: Uber Drivers API\n    tags:\n      - Drivers\n      - Ride-Sharing\n      - Payments\n      - Trips\n      - Transportation\n    humanURL: https://developer.uber.com/docs/drivers/introduction\n    baseURL: https://api.uber.com/v1\n    properties:\n      - url: https://developer.uber.com/docs/drivers/references/api\n        type: Documentation\n      - url: openapi/uber-drivers-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Uber Drivers API allows partners to access driver profile information,\n      payment history, and trip records. It provides access to driver earnings,\n      completed trips, and partner program data via OAuth 2.0 bearer tokens.\n\n  - aid: uber:uber-eats\n\
  \    name: Uber Eats API\n    tags:\n      - Food Delivery\n      - Restaurants\n      - Orders\n      - Menus\n      - Delivery\n    humanURL: https://developer.uber.com/docs/eats/introduction\n    baseURL: https://api.uber.com/v1\n    properties:\n      - url: https://developer.uber.com/docs/eats/introduction\n        type: Documentation\n      - url: https://developer.uber.com/docs/eats/api-change-log\n        type: ChangeLog\n      - url: openapi/uber-eats-openapi.yml\n        type: OpenAPI\n      - url: examples/uber-eats-get-order-example.json\n        type: Example\n    description: >-\n      The Uber Eats Marketplace API enables partners to programmatically manage\n      stores, menus, and orders on the Uber Eats platform. It supports real-time\n      menu synchronization, order processing, store operations, promotional campaigns,\n      and analytics reporting. Access requires written approval from Uber.\n\n  - aid: uber:uber-direct\n    name: Uber Direct API\n    tags:\n    \
  \  - Delivery\n      - Courier\n      - Logistics\n      - Fulfillment\n    humanURL: https://developer.uber.com/docs/deliveries/overview\n    baseURL: https://api.uber.com/v1\n    properties:\n      - url: https://developer.uber.com/docs/deliveries/overview\n        type: Documentation\n      - url: openapi/uber-direct-openapi.yml\n        type: OpenAPI\n      - url: examples/uber-direct-create-delivery-example.json\n        type: Example\n      - url: json-schema/uber-delivery-schema.json\n        type: JSONSchema\n    description: >-\n      The Uber Direct API allows merchants to leverage Uber's courier network\n      to deliver their orders. It supports on-demand delivery creation, courier\n      tracking, refunds, and location management. Webhooks provide real-time\n      delivery status, courier updates, and shopping progress notifications.\n\n  - aid: uber:uber-guest-rides\n    name: Uber Guest Rides API\n    tags:\n      - Ride-Sharing\n      - Guest\n      - Trips\n      - Transportation\n\
  \    humanURL: https://developer.uber.com/docs/guest-rides/introduction\n    baseURL: https://api.uber.com/v1\n    properties:\n      - url: https://developer.uber.com/docs/guest-rides/introduction\n        type: Documentation\n      - url: https://developer.uber.com/docs/guest-rides/about/u4b-api-introduction\n        type: Documentation\n    description: >-\n      The Uber Guest Rides API enables businesses to allow their users to request\n      rides from Uber without requiring an Uber account. Uses OAuth 2.0 with the\n      guest.rides scope for authentication.\n\n  - aid: uber:uber-vouchers\n    name: Uber Vouchers API\n    tags:\n      - Vouchers\n      - Promotions\n      - Incentives\n      - Codes\n    humanURL: https://developer.uber.com/docs/vouchers/introduction\n    baseURL: https://api.uber.com/v1\n    properties:\n      - url: https://developer.uber.com/docs/vouchers/introduction\n        type: Documentation\n      - url: openapi/uber-vouchers-openapi.yml\n        type:\
  \ OpenAPI\n    description: >-\n      The Uber Vouchers API allows businesses to create and manage voucher programs\n      and codes for rides and meals. It supports program creation, code generation,\n      bulk distribution, guest management, and code redemption workflows.\n\n  - aid: uber:uber-businesses\n    name: Uber for Business API\n    tags:\n      - Business\n      - Enterprise\n      - Receipts\n      - Trips\n      - Expenses\n    humanURL: https://developer.uber.com/docs/businesses/introduction\n    baseURL: https://api.uber.com/v1.2\n    properties:\n      - url: https://developer.uber.com/docs/businesses/introduction\n        type: Documentation\n      - url: https://developer.uber.com/docs/businesses/receipts/references/api\n        type: Documentation\n      - url: openapi/uber-businesses-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Uber for Business API enables organizations to automate workflows within\n      their enterprise Uber accounts. Provides\
  \ access to trip invoices, receipts,\n      and business travel data for expense management and reporting.\n\nname: Uber\ntags:\n  - Ride-Sharing\n  - Rides\n  - Taxis\n  - Transportation\n  - Food Delivery\n  - Delivery\n  - Logistics\ntype: Index\nproperties:\n  - url: rules/uber-rules.yml\n    type: SpectralRules\n  - url: vocabulary/uber-vocabulary.yml\n    type: Vocabulary\n  - url: json-ld/uber-context.jsonld\n    type: JSONLDContext\n  - url: capabilities/ride-management.yaml\n    type: NaftikoCapabilities\n  - url: capabilities/food-and-delivery.yaml\n    type: NaftikoCapabilities\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Uber is a global technology platform offering transportation, food delivery,\n  and logistics services. Its developer platform provides APIs for integrating\n  ride requests, food ordering, on-demand delivery, voucher\
  \ programs, and business\n  travel management into third-party applications. APIs use OAuth 2.0 authentication\n  with scope-based access controls and support both production and sandbox environments.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/apis.yml
tags:
- Ride-Sharing
- Rides
- Taxis
- Transportation
- Food Delivery
- Delivery
- Logistics
url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/apis.yml
use_cases: []
---
