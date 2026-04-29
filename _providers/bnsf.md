---
api_count: 6
apis:
- description: The BNSF Tracing API provides real-time shipment tracking from origin to destination for automotive VINs, carload railcars, intermodal units, and trains. Supports bulk queries of up to 300 vehicles or
  name: BNSF Tracing API
  slug: bnsf-tracing-api
- description: The BNSF Hub Operations API provides access to intermodal facility data including container and trailer delivery details, storage locations, driver pickup and delivery information, dray bookings, gate
  name: BNSF Hub Operations API
  slug: bnsf-hub-operations-api
- description: The BNSF Pricing & Rates API provides access to freight shipping prices and rates for both carload and intermodal shipments, enabling customers to obtain BNSF shipping costs programmatically.
  name: BNSF Pricing & Rates API
  slug: bnsf-pricing-rates-api
- description: The BNSF Schedules API provides intermodal transit schedules enabling customers to view planned departure and arrival times to help schedule freight shipments across the BNSF rail network.
  name: BNSF Schedules API
  slug: bnsf-schedules-api
- description: The BNSF Waybill Management API enables customers to submit bills of lading with transit details and retrieve submissions for carload shipments. Supports electronic submission and retrieval of waybill
  name: BNSF Waybill Management API
  slug: bnsf-waybill-management-api
- description: The BNSF Reference Files API provides access to reference data including city names, commodity descriptions (STCC codes), station data, event codes, and hazardous materials information used in freight
  name: BNSF Reference Files API
  slug: bnsf-reference-files-api
common:
- title: ''
  type: Website
  url: https://www.bnsf.com
- title: ''
  type: Portal
  url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/
- title: ''
  type: Documentation
  url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/
- title: ''
  type: DeveloperConsole
  url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/developers-console/
- title: ''
  type: Support
  url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/support/
created: '2025-02-06'
description: BNSF Railway, a subsidiary of Berkshire Hathaway Inc., is one of the largest freight railroad networks in North America. The company operates an extensive network of over 32,000 route miles in 28 states and three Canadian provinces, serving major markets in the United States and connecting with Mexico through rail lines in Texas.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: BNSF
skills: []
slug: bnsf
solutions: []
source_yaml: "aid: bnsf\nname: BNSF\ndescription: >-\n  BNSF Railway, a subsidiary of Berkshire Hathaway Inc., is one of the largest freight\n  railroad networks in North America. The company operates an extensive network of\n  over 32,000 route miles in 28 states and three Canadian provinces, serving major\n  markets in the United States and connecting with Mexico through rail lines in Texas.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bnsf/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n  - Freight\n  - Railroad\n  - Shipping\n  - Trains\n  - Intermodal\n  - Logistics\napis:\n  - aid: bnsf:bnsf-tracing-api\n    name: BNSF Tracing API\n    description: >-\n      The BNSF Tracing API provides real-time shipment tracking from origin to destination\n      for automotive VINs, carload railcars, intermodal units, and trains. Supports\n\
  \      bulk queries of up to 300 vehicles or units per request with detailed trip plan\n      and event data.\n    humanURL: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/\n    tags:\n      - Freight\n      - Railroad\n      - Tracking\n      - Tracing\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/\n      - type: Portal\n        url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/developers-console/\n\n  - aid: bnsf:bnsf-hub-operations-api\n    name: BNSF Hub Operations API\n    description: >-\n      The BNSF Hub Operations API provides access to intermodal facility data including\n      container and trailer delivery details, storage locations, driver pickup and delivery\n      information, dray bookings, gate operations, and unit status for intermodal hubs\n      across the BNSF network.\n    humanURL: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/\n\
  \    tags:\n      - Freight\n      - Intermodal\n      - Hub\n      - Logistics\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/\n\n  - aid: bnsf:bnsf-pricing-rates-api\n    name: BNSF Pricing & Rates API\n    description: >-\n      The BNSF Pricing & Rates API provides access to freight shipping prices and rates\n      for both carload and intermodal shipments, enabling customers to obtain BNSF\n      shipping costs programmatically.\n    humanURL: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/\n    tags:\n      - Freight\n      - Pricing\n      - Rates\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/\n\n  - aid: bnsf:bnsf-schedules-api\n    name: BNSF Schedules API\n    description: >-\n      The BNSF Schedules API provides intermodal transit schedules enabling\
  \ customers\n      to view planned departure and arrival times to help schedule freight shipments\n      across the BNSF rail network.\n    humanURL: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/\n    tags:\n      - Freight\n      - Schedules\n      - Transit\n      - Intermodal\n    properties:\n      - type: Documentation\n        url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/\n\n  - aid: bnsf:bnsf-waybill-management-api\n    name: BNSF Waybill Management API\n    description: >-\n      The BNSF Waybill Management API enables customers to submit bills of lading with\n      transit details and retrieve submissions for carload shipments. Supports electronic\n      submission and retrieval of waybill documentation for freight management.\n    humanURL: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/\n    tags:\n      - Freight\n      - Waybill\n      - Documentation\n      - Carload\n    properties:\n      - type:\
  \ Documentation\n        url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/\n\n  - aid: bnsf:bnsf-reference-files-api\n    name: BNSF Reference Files API\n    description: >-\n      The BNSF Reference Files API provides access to reference data including city\n      names, commodity descriptions (STCC codes), station data, event codes, and\n      hazardous materials information used in freight operations and waybill processing.\n    humanURL: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/\n    tags:\n      - Freight\n      - Reference\n      - Data\n      - STCC\n      - Stations\n    properties:\n      - type: Documentation\n        url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/\n\ncommon:\n  - type: Website\n    url: https://www.bnsf.com\n  - type: Portal\n    url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/\n  - type: Documentation\n    url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/catalog/\n\
  \  - type: DeveloperConsole\n    url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/developers-console/\n  - type: Support\n    url: https://www.bnsf.com/ship-with-bnsf/support-services/customer-api/support/\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bnsf/refs/heads/main/apis.yml
tags:
- Freight
- Railroad
- Shipping
- Trains
- Intermodal
- Logistics
url: https://raw.githubusercontent.com/api-evangelist/bnsf/refs/heads/main/apis.yml
use_cases: []
---
