---
api_count: 5
api_specs:
- filename: sightline-api.yml
  format: yaml
  label: Goodyear SightLine API
  slug: sightline-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/goodyear-tire-and-rubber/refs/heads/main/openapi/sightline-api.yml
- filename: gaas-portal.yml
  format: yaml
  label: Goodyear API Management Portal
  slug: gaas-portal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/goodyear-tire-and-rubber/refs/heads/main/openapi/gaas-portal.yml
apis:
- description: Goodyear SightLine API provides developer-friendly access to intelligent tire data including tire type, tread depth, tire pressure, load, wear state, and temperature. The API uses REST architecture wi
  name: Goodyear SightLine API
  slug: sightline-api
- description: The Goodyear API Management Portal (GaaS) provides access to Goodyear's suite of APIs for tire and fleet management services.
  name: Goodyear API Management Portal
  slug: gaas-portal
- description: The Goodyear Truck Tire Catalog API provides access to Goodyear's commercial truck tire catalog data.
  name: Goodyear Truck Tire Catalog API
  slug: catalog-api
- description: The Goodyear Work Order API enables management of service work orders for commercial truck tire services.
  name: Goodyear Work Order API
  slug: work-order-api
- description: The Goodyear Service Ticket API provides management of service tickets for commercial truck tire services.
  name: Goodyear Service Ticket API
  slug: service-ticket-api
common:
- title: ''
  type: Website
  url: https://www.goodyear.com
- title: ''
  type: Portal
  url: https://developer.goodyearsightline.com/
- title: ''
  type: Portal
  url: https://gaas-portal.goodyear.com/
created: '2026-03-21'
description: The Goodyear Tire & Rubber Company is a global tire manufacturer that provides developer APIs for intelligent tire data, fleet management, and commercial truck tire services. Goodyear's SightLine technology and GaaS API platform enable programmatic access to tire telematics, catalogs, work orders, and service tickets.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Goodyear Tire & Rubber
skills: []
slug: goodyear-tire-and-rubber
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: goodyear-tire-and-rubber\nurl: https://raw.githubusercontent.com/api-evangelist/goodyear-tire-and-rubber/refs/heads/main/apis.yml\napis:\n  - aid: goodyear-tire-and-rubber:sightline-api\n    name: Goodyear SightLine API\n    tags:\n      - Connected Vehicles\n      - IoT\n      - Telematics\n      - Tire Data\n      - Tires\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://developer.goodyearsightline.com\n    humanURL: https://developer.goodyearsightline.com/\n    properties:\n      - type: Portal\n        url: https://developer.goodyearsightline.com/\n      - type: OpenAPI\n        url: openapi/sightline-api.yml\n    description: >-\n      Goodyear SightLine API provides developer-friendly access to intelligent\n      tire data including tire type, tread depth, tire pressure, load, wear\n      state, and temperature. The API uses REST architecture with robust\n      security protocols for efficient and secure\
  \ data sharing.\n  - aid: goodyear-tire-and-rubber:gaas-portal\n    name: Goodyear API Management Portal\n    tags:\n      - API Management\n      - Fleet Management\n      - Tires\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://gaas-portal.goodyear.com\n    humanURL: https://gaas-portal.goodyear.com/\n    properties:\n      - type: Portal\n        url: https://gaas-portal.goodyear.com/\n      - type: SignUp\n        url: https://gaas-portal.goodyear.com/signup\n      - type: OpenAPI\n        url: openapi/gaas-portal.yml\n    description: >-\n      The Goodyear API Management Portal (GaaS) provides access to Goodyear's\n      suite of APIs for tire and fleet management services.\n  - aid: goodyear-tire-and-rubber:catalog-api\n    name: Goodyear Truck Tire Catalog API\n    tags:\n      - Catalog\n      - Tires\n      - Truck Tires\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://api.catalog.goodyeartrucktires.com\n    humanURL: https://api.catalog.goodyeartrucktires.com/\n    properties:\n      - type: Portal\n        url: https://api.catalog.goodyeartrucktires.com/\n    description: >-\n      The Goodyear Truck Tire Catalog API provides access to Goodyear's\n      commercial truck tire catalog data.\n  - aid: goodyear-tire-and-rubber:work-order-api\n    name: Goodyear Work Order API\n    tags:\n      - Fleet Management\n      - Tires\n      - Work Orders\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.workorder.goodyeartrucktires.com\n    humanURL: https://api.workorder.goodyeartrucktires.com/\n    properties:\n      - type: Portal\n        url: https://api.workorder.goodyeartrucktires.com/\n    description: >-\n      The Goodyear Work Order API enables management of service work orders\n      for commercial truck tire services.\n  - aid: goodyear-tire-and-rubber:service-ticket-api\n \
  \   name: Goodyear Service Ticket API\n    tags:\n      - Fleet Management\n      - Service Tickets\n      - Tires\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.serviceticket.goodyeartrucktires.com\n    humanURL: https://api.serviceticket.goodyeartrucktires.com/\n    properties:\n      - type: Portal\n        url: https://api.serviceticket.goodyeartrucktires.com/\n    description: >-\n      The Goodyear Service Ticket API provides management of service tickets\n      for commercial truck tire services.\nname: Goodyear Tire & Rubber\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Connected Vehicles\n  - Fleet Management\n  - IoT\n  - Telematics\n  - Tires\ncommon:\n  - url: https://www.goodyear.com\n    name: Goodyear Website\n    type: Website\n  - url: https://developer.goodyearsightline.com/\n\
  \    name: SightLine Developer Portal\n    type: Portal\n  - url: https://gaas-portal.goodyear.com/\n    name: Goodyear API Management Portal\n    type: Portal\ndescription: >-\n  The Goodyear Tire & Rubber Company is a global tire manufacturer that\n  provides developer APIs for intelligent tire data, fleet management, and\n  commercial truck tire services. Goodyear's SightLine technology and GaaS\n  API platform enable programmatic access to tire telematics, catalogs,\n  work orders, and service tickets.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/goodyear-tire-and-rubber/refs/heads/main/apis.yml
tags:
- Connected Vehicles
- Fleet Management
- IoT
- Telematics
- Tires
url: https://raw.githubusercontent.com/api-evangelist/goodyear-tire-and-rubber/refs/heads/main/apis.yml
use_cases: []
---
