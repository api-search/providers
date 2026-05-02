---
api_count: 6
api_specs:
- filename: grubhub-menu-openapi.yml
  format: yaml
  label: Grubhub Menu API
  slug: menu-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-menu-openapi.yml
- filename: grubhub-orders-openapi.yml
  format: yaml
  label: Grubhub Orders API
  slug: orders-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-orders-openapi.yml
- filename: grubhub-merchant-data-openapi.yml
  format: yaml
  label: Grubhub Merchant Data API
  slug: merchant-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-merchant-data-openapi.yml
- filename: grubhub-merchant-schedules-openapi.yml
  format: yaml
  label: Grubhub Merchant Schedules API
  slug: merchant-schedules-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-merchant-schedules-openapi.yml
- filename: grubhub-deliveries-openapi.yml
  format: yaml
  label: Grubhub Deliveries API
  slug: deliveries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-deliveries-openapi.yml
- filename: grubhub-onboarding-openapi.yml
  format: yaml
  label: Grubhub Onboarding API
  slug: onboarding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/openapi/grubhub-onboarding-openapi.yml
apis:
- description: The Grubhub Menu API enables partners and merchants to create, update, and manage restaurant menus within the Grubhub Marketplace. It supports building normalized menu structures including categories,
  name: Grubhub Menu API
  slug: menu-api
- description: 'The Grubhub Orders API allows partners to receive, manage, and update order statuses for restaurant orders placed through the Grubhub Marketplace. When a customer places an order, Grubhub sends it to '
  name: Grubhub Orders API
  slug: orders-api
- description: The Grubhub Merchant Data API provides endpoints for managing merchant information, including store details, tax rates, fulfillment settings, and configuration groups. Partners can retrieve all Grubhu
  name: Grubhub Merchant Data API
  slug: merchant-data-api
- description: The Grubhub Merchant Schedules API allows partners to manage restaurant operating hours and availability on the Grubhub Marketplace. It supports setting regular business hours, temporary closures, and
  name: Grubhub Merchant Schedules API
  slug: merchant-schedules-api
- description: The Grubhub Deliveries API enables partners to manage delivery logistics and interact with Grubhub's nationwide courier network. It provides delivery status tracking through key states including drive
  name: Grubhub Deliveries API
  slug: deliveries-api
- description: The Grubhub Onboarding API enables partners to offer self-service integration onboarding directly to their merchants using OAuth-based authentication. It provides endpoints for new merchant referrals,
  name: Grubhub Onboarding API
  slug: onboarding-api
asyncapis:
- description: 'Event-driven interface for receiving real-time delivery status updates from Grubhub. Partners can subscribe to webhook notifications for delivery updates including driver assignment, courier location '
  name: Grubhub Delivery Events
  slug: grubhub-delivery-events-asyncapi
- description: Event-driven interface for receiving real-time order notifications from Grubhub. When a diner places an order, Grubhub monitors that order and sends notifications based on the current status. The webh
  name: Grubhub Order Events
  slug: grubhub-order-events-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/grubhub-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/grubhub-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/grubhub-menu-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/grubhub-merchant-schema.json
created: ''
description: Grubhub works with brands, point of sale companies, and online ordering providers to power an ordering experience in Grubhub Marketplace and within restaurant-branded web experiences. This documentation describes the normalized endpoints required for ingesting menu content and facilitating order transmission.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Grubhub Context
  property_count: 7
  slug: grubhub-context
layout: provider
modified: '2026-04-28'
name: grubhub
skills: []
slug: grubhub
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: grubhub\nurl: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: grubhub:menu-api\n    name: Grubhub Menu API\n    tags:\n      - Food Delivery\n      - Menus\n      - Online Ordering\n      - Restaurants\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.grubhub.com\n    humanURL: https://developer.grubhub.com/api/menu\n    properties:\n      - url: https://developer.grubhub.com/api/menu\n        type: Documentation\n      - url: openapi/grubhub-menu-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Grubhub Menu API enables partners and merchants to create, update,\n      and manage restaurant menus within the Grubhub Marketplace. It supports\n      building normalized menu structures including categories, items, modifiers,\n      and pricing. POS integrations are required to sync menus through this API,\n      ensuring\
  \ that restaurant offerings on Grubhub stay current with their\n      local menu changes.\n  - aid: grubhub:orders-api\n    name: Grubhub Orders API\n    tags:\n      - Food Delivery\n      - Online Ordering\n      - Orders\n      - Restaurants\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.grubhub.com\n    humanURL: https://developer.grubhub.com/api/orders\n    properties:\n      - url: https://developer.grubhub.com/api/orders\n        type: Documentation\n      - url: openapi/grubhub-orders-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/grubhub-order-events-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Grubhub Orders API allows partners to receive, manage, and update\n      order statuses for restaurant orders placed through the Grubhub\n      Marketplace. When a customer places an order, Grubhub sends it to the\n      partner's endpoint via webhook subscription. Partners\
  \ can confirm orders,\n      update preparation status, mark orders as ready for pickup, and track\n      delivery progress through defined order lifecycle states.\n  - aid: grubhub:merchant-data-api\n    name: Grubhub Merchant Data API\n    tags:\n      - Data Management\n      - Food Delivery\n      - Merchants\n      - Restaurants\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.grubhub.com\n    humanURL: https://developer.grubhub.com/api/merchant-data\n    properties:\n      - url: https://developer.grubhub.com/api/merchant-data\n        type: Documentation\n      - url: openapi/grubhub-merchant-data-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Grubhub Merchant Data API provides endpoints for managing merchant\n      information, including store details, tax rates, fulfillment settings,\n      and configuration groups. Partners can retrieve all Grubhub locations\n      associated with a merchant's\
  \ account, update merchant profiles, and\n      manage operational settings. This API is essential for maintaining\n      accurate restaurant data across the Grubhub platform.\n  - aid: grubhub:merchant-schedules-api\n    name: Grubhub Merchant Schedules API\n    tags:\n      - Availability\n      - Food Delivery\n      - Restaurants\n      - Scheduling\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.grubhub.com\n    humanURL: https://developer.grubhub.com/docs/6uXmPesMoYmoV6jZx6lVfa/checking-merchant-availability\n    properties:\n      - url: https://developer.grubhub.com/docs/6uXmPesMoYmoV6jZx6lVfa/checking-merchant-availability\n        type: Documentation\n      - url: openapi/grubhub-merchant-schedules-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Grubhub Merchant Schedules API allows partners to manage restaurant\n      operating hours and availability on the Grubhub Marketplace. It supports\n\
  \      setting regular business hours, temporary closures, and special holiday\n      schedules. Partners can check merchant availability status and update\n      schedules to ensure customers see accurate ordering windows for each\n      restaurant location.\n  - aid: grubhub:deliveries-api\n    name: Grubhub Deliveries API\n    tags:\n      - Delivery Tracking\n      - Drivers\n      - Food Delivery\n      - Logistics\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.grubhub.com\n    humanURL: https://developer.grubhub.com/docs/2xRv0wZtNljuMTpizzNqD2/interacting-with-drivers\n    properties:\n      - url: https://developer.grubhub.com/docs/2xRv0wZtNljuMTpizzNqD2/interacting-with-drivers\n        type: Documentation\n      - url: openapi/grubhub-deliveries-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/grubhub-delivery-events-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Grubhub Deliveries\
  \ API enables partners to manage delivery logistics\n      and interact with Grubhub's nationwide courier network. It provides\n      delivery status tracking through key states including driver assignment,\n      pickup ready, and out for delivery. Partners can leverage Grubhub Connect,\n      a full-service delivery solution for delivery aggregators, marketplaces,\n      and enterprise merchants to fulfill orders using Grubhub drivers.\n  - aid: grubhub:onboarding-api\n    name: Grubhub Onboarding API\n    tags:\n      - Food Delivery\n      - Integration\n      - Merchants\n      - Onboarding\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.grubhub.com\n    humanURL: https://developer.grubhub.com/api/onboarding\n    properties:\n      - url: https://developer.grubhub.com/api/onboarding\n        type: Documentation\n      - url: openapi/grubhub-onboarding-openapi.yml\n        type: OpenAPI\n    description: >-\n      The\
  \ Grubhub Onboarding API enables partners to offer self-service\n      integration onboarding directly to their merchants using OAuth-based\n      authentication. It provides endpoints for new merchant referrals,\n      merchant activation and deactivation, merchant association, and reporting\n      onboarding issues. The API can reduce merchant onboarding time from 7-10\n      days down to as little as 5-10 minutes, significantly decreasing\n      integration downtime.\ncommon:\n  - type: JSON-LD\n    url: json-ld/grubhub-context.jsonld\n  - type: JSONSchema\n    url: json-schema/grubhub-order-schema.json\n  - type: JSONSchema\n    url: json-schema/grubhub-menu-schema.json\n  - type: JSONSchema\n    url: json-schema/grubhub-merchant-schema.json\ndescription: >-\n  Grubhub works with brands, point of sale companies, and online ordering providers\n  to power an ordering experience in Grubhub Marketplace and within restaurant-branded\n  web experiences. This documentation describes the normalized\
  \ endpoints required\n  for ingesting menu content and facilitating order transmission.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/grubhub/refs/heads/main/apis.yml
use_cases: []
---
