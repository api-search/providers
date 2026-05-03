---
api_count: 11
apis:
- description: The EcoStruxure IT Expert API provides programmatic access to data center infrastructure management data. It enables integrations to query locations, devices, alarms, sensors, and measurements from th
  name: EcoStruxure IT Expert API
  slug: ecostruxure-it-expert-api
- description: API providing time series data and alarms access for buildings and equipment monitored by EcoStruxure Facility Expert. Enables facility managers and integrators to retrieve energy measurements, equipm
  name: EcoStruxure Facility Expert Data API
  slug: ecostruxure-facility-expert-api
- description: Provides contextualized energy data from EcoStruxure Energy hubs, including consumption metrics, load profiles, and energy optimization data for buildings and industrial sites.
  name: EcoStruxure Energy Contextualized Data API
  slug: ecostruxure-energy-contextualized-data-api
- description: API providing transformer health analytics and monitoring data. Enables integration of transformer assets into enterprise applications, delivering condition monitoring, diagnostics, and predictive mai
  name: EcoStruxure Transformer Expert Data API
  slug: ecostruxure-transformer-expert-api
- description: Provides access to comprehensive technical data for Schneider Electric products from a single source, including product specifications, technical documentation, and ETIM 10.0 classification data.
  name: Partner Product Catalog API
  slug: partner-product-catalog-api
- description: Provides the date when a required quantity of a product can be delivered to a defined address. Queries Schneider Electric's supply chain for delivery lead times by product reference and delivery locat
  name: Partner Product Availability API
  slug: partner-product-availability-api
- description: Provides real-time access to both public list price and personalized net price for Schneider Electric products based on the partner account and standard commercial discounts.
  name: Partner Net Price API
  slug: partner-net-price-api
- description: Provides current order status, shipment schedule, and list of items for orders associated with a registered buying account. Enables distributors to track order fulfillment in real time.
  name: Partner Order Status API
  slug: partner-order-status-api
- description: A read-only service allowing distributors to retrieve quote-lines based on quotes associated with their accounts. Supports the conversion workflow from quote to order in the partner sales process.
  name: Partner Distributor Quote API
  slug: partner-distributor-quote-api
- description: Retrieves public information about installed product warranty start and end dates by providing a product serial number. Supports asset lifecycle management and warranty tracking for field-installed eq
  name: Partner Installed Product API
  slug: partner-installed-product-api
- description: Provides access to product-related digital assets and visualization services including 360-degree image sets and 3D models for Schneider Electric products.
  name: Partner Product Digital Asset API
  slug: partner-digital-asset-api
common:
- title: ''
  type: Portal
  url: https://devportal.exchange.se.com/
- title: ''
  type: Website
  url: https://exchange.se.com/develop
- title: ''
  type: Partner Portal
  url: https://api-explorer.se.com/en
- title: ''
  type: Community
  url: https://community.se.com/t5/EcoStruxure-IT-Expert-API/tkb-p/ecostruxure-it-expert-api
- title: ''
  type: Documentation
  url: https://exchange.se.com/develop
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/showcase/schneider-electric-exchange/
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-structure/schneider-electric-exchange-api-structure.json
- title: ''
  type: JSONLd
  url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-ld/schneider-electric-exchange-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/vocabulary/schneider-electric-exchange-vocabulary.yml
- title: ''
  type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/examples/ecostruxure-it-get-devices-example.json
created: '2026-03-16'
description: Schneider Electric Exchange is a developer platform providing APIs for EcoStruxure energy management, building automation, industrial IoT, and commerce partner integrations. The Exchange platform enables partners and developers to build integrations with Schneider Electric products and services. APIs span EcoStruxure data services (IT Expert, Facility Expert, Transformer Expert, Energy Contextualized Data) and Partner Commerce APIs for product catalog, inventory, pricing, orders, quotes, and marketplace integrations. Authentication uses OAuth 2.0 with client credentials for Partner APIs and subscription-based API keys for EcoStruxure data APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 32
  name: Schneider Electric Exchange Context
  property_count: 3
  slug: schneider-electric-exchange-context
layout: provider
modified: '2026-05-02'
name: Schneider Electric Exchange
skills: []
slug: schneider-electric-exchange
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: schneider-electric-exchange\nname: Schneider Electric Exchange\ndescription: >-\n  Schneider Electric Exchange is a developer platform providing APIs for\n  EcoStruxure energy management, building automation, industrial IoT, and\n  commerce partner integrations. The Exchange platform enables partners and\n  developers to build integrations with Schneider Electric products and services.\n  APIs span EcoStruxure data services (IT Expert, Facility Expert, Transformer\n  Expert, Energy Contextualized Data) and Partner Commerce APIs for product\n  catalog, inventory, pricing, orders, quotes, and marketplace integrations.\n  Authentication uses OAuth 2.0 with client credentials for Partner APIs and\n  subscription-based API keys for EcoStruxure data APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Building Automation\n  - Commerce APIs\n  - EcoStruxure\n  - Energy Management\n  - Industrial IoT\n  - Schneider Electric\n\
  url: >-\n  https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: schneider-electric-exchange:ecostruxure-it-expert-api\n    name: EcoStruxure IT Expert API\n    description: >-\n      The EcoStruxure IT Expert API provides programmatic access to data center\n      infrastructure management data. It enables integrations to query locations,\n      devices, alarms, sensors, and measurements from the EcoStruxure IT cloud\n      platform. Requires an active IT Expert subscription.\n    humanURL: https://community.se.com/t5/EcoStruxure-IT-Expert-API/tkb-p/ecostruxure-it-expert-api\n    tags:\n      - Data Center\n      - EcoStruxure IT\n      - Infrastructure Monitoring\n      - IoT\n    properties:\n      - type: Documentation\n        url: https://community.se.com/t5/EcoStruxure-IT-Expert-API/tkb-p/ecostruxure-it-expert-api\n      - type: API Reference\n\
  \        url: https://api.ecostruxureit.com/rest/\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-schema/ecostruxure-it-device-schema.json\n  - aid: schneider-electric-exchange:ecostruxure-facility-expert-api\n    name: EcoStruxure Facility Expert Data API\n    description: >-\n      API providing time series data and alarms access for buildings and equipment\n      monitored by EcoStruxure Facility Expert. Enables facility managers and\n      integrators to retrieve energy measurements, equipment alarms, and\n      historical sensor data.\n    humanURL: https://shop.exchange.se.com/en-US/apps/76237/ecostruxure-facility-expert-data-api\n    tags:\n      - Building Automation\n      - EcoStruxure\n      - Facility Management\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://exchange.se.com/devportal/api/ecostruxure-facility-expert-data-api\n  - aid:\
  \ schneider-electric-exchange:ecostruxure-energy-contextualized-data-api\n    name: EcoStruxure Energy Contextualized Data API\n    description: >-\n      Provides contextualized energy data from EcoStruxure Energy hubs, including\n      consumption metrics, load profiles, and energy optimization data for\n      buildings and industrial sites.\n    humanURL: https://exchange.se.com/develop/products/ecostruxure-energy-contextualized-data-api\n    tags:\n      - EcoStruxure\n      - Energy Management\n      - Energy Monitoring\n      - Sustainability\n    properties:\n      - type: Documentation\n        url: https://exchange.se.com/develop/products/ecostruxure-energy-contextualized-data-api\n  - aid: schneider-electric-exchange:ecostruxure-transformer-expert-api\n    name: EcoStruxure Transformer Expert Data API\n    description: >-\n      API providing transformer health analytics and monitoring data. Enables\n      integration of transformer assets into enterprise applications, delivering\n\
  \      condition monitoring, diagnostics, and predictive maintenance data.\n    humanURL: https://exchange.se.com/develop/products/684854/ecostruxure-transformer-expert-data-api\n    tags:\n      - Asset Management\n      - EcoStruxure\n      - Industrial IoT\n      - Predictive Maintenance\n    properties:\n      - type: Documentation\n        url: https://exchange.se.com/develop/products/684854/ecostruxure-transformer-expert-data-api\n  - aid: schneider-electric-exchange:partner-product-catalog-api\n    name: Partner Product Catalog API\n    description: >-\n      Provides access to comprehensive technical data for Schneider Electric\n      products from a single source, including product specifications, technical\n      documentation, and ETIM 10.0 classification data.\n    humanURL: https://api-explorer.se.com/en/api/product-catalog-v2\n    tags:\n      - Commerce\n      - Partner Integration\n      - Product Catalog\n    properties:\n      - type: Documentation\n        url: https://api-explorer.se.com/en/api/product-catalog-v2\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-schema/partner-product-schema.json\n  - aid: schneider-electric-exchange:partner-product-availability-api\n    name: Partner Product Availability API\n    description: >-\n      Provides the date when a required quantity of a product can be delivered\n      to a defined address. Queries Schneider Electric's supply chain for\n      delivery lead times by product reference and delivery location.\n    humanURL: https://api-explorer.se.com/en/api/product-availability-v2\n    tags:\n      - Commerce\n      - Inventory\n      - Partner Integration\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://api-explorer.se.com/en/api/product-availability-v2\n  - aid: schneider-electric-exchange:partner-net-price-api\n    name: Partner Net Price API\n    description: >-\n      Provides real-time access to both public\
  \ list price and personalized\n      net price for Schneider Electric products based on the partner account\n      and standard commercial discounts.\n    humanURL: https://api-explorer.se.com/en\n    tags:\n      - Commerce\n      - Partner Integration\n      - Pricing\n    properties:\n      - type: Documentation\n        url: https://api-explorer.se.com/en\n  - aid: schneider-electric-exchange:partner-order-status-api\n    name: Partner Order Status API\n    description: >-\n      Provides current order status, shipment schedule, and list of items\n      for orders associated with a registered buying account. Enables\n      distributors to track order fulfillment in real time.\n    humanURL: https://api-explorer.se.com/en/api/distributor-order-status-v1.0\n    tags:\n      - Commerce\n      - Order Management\n      - Partner Integration\n    properties:\n      - type: Documentation\n        url: https://api-explorer.se.com/en/api/distributor-order-status-v1.0\n  - aid: schneider-electric-exchange:partner-distributor-quote-api\n\
  \    name: Partner Distributor Quote API\n    description: >-\n      A read-only service allowing distributors to retrieve quote-lines based\n      on quotes associated with their accounts. Supports the conversion workflow\n      from quote to order in the partner sales process.\n    humanURL: https://api-explorer.se.com/en/api/distributor-quote-v1\n    tags:\n      - Commerce\n      - Partner Integration\n      - Quotes\n    properties:\n      - type: Documentation\n        url: https://api-explorer.se.com/en/api/distributor-quote-v1\n  - aid: schneider-electric-exchange:partner-installed-product-api\n    name: Partner Installed Product API\n    description: >-\n      Retrieves public information about installed product warranty start and\n      end dates by providing a product serial number. Supports asset lifecycle\n      management and warranty tracking for field-installed equipment.\n    humanURL: https://api-explorer.se.com/en/api/Partner-Installed-Product-v1.0\n    tags:\n     \
  \ - Asset Management\n      - Partner Integration\n      - Warranty\n    properties:\n      - type: Documentation\n        url: https://api-explorer.se.com/en/api/Partner-Installed-Product-v1.0\n  - aid: schneider-electric-exchange:partner-digital-asset-api\n    name: Partner Product Digital Asset API\n    description: >-\n      Provides access to product-related digital assets and visualization\n      services including 360-degree image sets and 3D models for Schneider\n      Electric products.\n    humanURL: https://api-explorer.se.com/en/api/product-digital-asset-v1\n    tags:\n      - Commerce\n      - Digital Assets\n      - Partner Integration\n    properties:\n      - type: Documentation\n        url: https://api-explorer.se.com/en/api/product-digital-asset-v1\ncommon:\n  - type: Portal\n    url: https://devportal.exchange.se.com/\n  - type: Website\n    url: https://exchange.se.com/develop\n  - type: Partner Portal\n    url: https://api-explorer.se.com/en\n  - type: Community\n\
  \    url: https://community.se.com/t5/EcoStruxure-IT-Expert-API/tkb-p/ecostruxure-it-expert-api\n  - type: Documentation\n    url: https://exchange.se.com/develop\n  - type: LinkedIn\n    url: https://www.linkedin.com/showcase/schneider-electric-exchange/\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-structure/schneider-electric-exchange-api-structure.json\n  - type: JSONLd\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/json-ld/schneider-electric-exchange-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/vocabulary/schneider-electric-exchange-vocabulary.yml\n  - type: Examples\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/examples/ecostruxure-it-get-devices-example.json\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/apis.yml
tags:
- Building Automation
- Commerce APIs
- EcoStruxure
- Energy Management
- Industrial IoT
- Schneider Electric
url: https://raw.githubusercontent.com/api-evangelist/schneider-electric-exchange/refs/heads/main/apis.yml
use_cases: []
---
