---
api_count: 4
api_specs:
- filename: toyota-telematics-openapi.yml
  format: yaml
  label: Toyota Telematics API
  slug: toyota-telematics
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/openapi/toyota-telematics-openapi.yml
- filename: toyota-connected-services-openapi.yml
  format: yaml
  label: Toyota Connected Services API
  slug: toyota-connected-services
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/openapi/toyota-connected-services-openapi.yml
apis:
- description: Toyota Vehicle API provides lifecycle information for vehicles from initial order through retail sale. Enables dealers, fleet managers, and authorized business partners to access vehicle inventory, or
  name: Toyota Vehicle API
  slug: toyota-vehicle
- description: Toyota Telematics API provides details related to connected services, satellite radio subscriptions, and vehicle health data for enrolled vehicles based on Unit ID or VIN. Supports fleet management, r
  name: Toyota Telematics API
  slug: toyota-telematics
- description: Toyota Connected Services API enables authorized applications to access real-time vehicle status, remote control features, location data, electric vehicle charging status, climate control, and trip hi
  name: Toyota Connected Services API
  slug: toyota-connected-services
- description: Toyota Dealers API enables searching and retrieving dealer information including location, hours, services offered, and inventory. Supports dealer locator applications and service scheduling integrati
  name: Toyota Dealers API
  slug: toyota-dealers
capabilities:
- description: Workflow capability for Toyota and Lexus vehicle owners and mobility app developers using Toyota Connected Services. Provides real-time vehicle monitoring, remote control, EV charging management, clim
  name: Toyota Connected Vehicle
  slug: connected-vehicle
- description: Workflow capability for fleet managers and rental car operators combining Toyota Telematics and Connected Services APIs. Enables vehicle enrollment, health monitoring, location tracking, telemetry ana
  name: Toyota Fleet Management
  slug: fleet-management
common:
- title: ''
  type: Website
  url: https://developer.eig.toyota.com/
- title: ''
  type: Developer
  url: https://developer.eig.toyota.com/
- title: ''
  type: Documentation
  url: https://developer.eig.toyota.com/apis
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/toyota-motor-corporation
- title: ''
  type: Rules
  url: rules/toyota-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/toyota-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: json-ld/toyota-context.jsonld
created: '2025-02-25'
description: Toyota Motor Corporation is a Japanese multinational automotive manufacturer that designs, manufactures, and sells vehicles, including cars, trucks, and buses. Founded in 1937, Toyota has become one of the largest automakers in the world, known for its reliability, innovation, and commitment to sustainability. Toyota's developer platform (developer.eig.toyota.com) provides APIs for vehicle lifecycle management, telematics and connected services, dealer data, and fleet management for business partners, dealers, fleet operators, and developers building mobility applications. Toyota's product lineup includes hybrids like the Prius, trucks like the Tacoma, and EVs including the bZ4X.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 58
  name: Toyota Context
  property_count: 0
  slug: toyota-context
layout: provider
modified: '2026-05-03'
name: Toyota
rules:
- name: Toyota API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 6
  slug: toyota-spectral-rules
skills: []
slug: toyota
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: toyota\nurl: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/apis.yml\napis:\n  - aid: toyota:toyota-vehicle\n    name: Toyota Vehicle API\n    tags:\n      - Automotive\n      - Vehicles\n      - Connected Car\n      - Vehicle Lifecycle\n      - Dealer\n    humanURL: https://developer.eig.toyota.com/apis/vehicle\n    properties:\n      - url: https://developer.eig.toyota.com/apis/vehicle\n        type: Documentation\n      - url: openapi/toyota-vehicle-openapi.yml\n        type: OpenAPI\n    description: >-\n      Toyota Vehicle API provides lifecycle information for vehicles from initial\n      order through retail sale. Enables dealers, fleet managers, and authorized\n      business partners to access vehicle inventory, order status, and vehicle\n      configuration data for Toyota North America vehicles.\n  - aid: toyota:toyota-telematics\n    name: Toyota Telematics API\n    tags:\n      - Automotive\n      - Telematics\n      - Connected Car\n\
  \      - Fleet Management\n      - Vehicle Health\n    humanURL: https://developer.eig.toyota.com/apis/telematics\n    properties:\n      - url: https://developer.eig.toyota.com/apis/telematics\n        type: Documentation\n      - url: openapi/toyota-telematics-openapi.yml\n        type: OpenAPI\n    description: >-\n      Toyota Telematics API provides details related to connected services,\n      satellite radio subscriptions, and vehicle health data for enrolled\n      vehicles based on Unit ID or VIN. Supports fleet management, rental\n      car operations, and telematics insurance use cases.\n  - aid: toyota:toyota-connected-services\n    name: Toyota Connected Services API\n    tags:\n      - Automotive\n      - Connected Car\n      - Remote Control\n      - Vehicle Status\n      - EV\n    humanURL: https://developer.eig.toyota.com/\n    properties:\n      - url: https://developer.eig.toyota.com/\n        type: Documentation\n      - url: openapi/toyota-connected-services-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      Toyota Connected Services API enables authorized applications to access\n      real-time vehicle status, remote control features, location data, electric\n      vehicle charging status, climate control, and trip history for Toyota and\n      Lexus connected vehicles.\n  - aid: toyota:toyota-dealers\n    name: Toyota Dealers API\n    tags:\n      - Automotive\n      - Dealers\n      - Dealer Locator\n      - Service\n      - Inventory\n    humanURL: https://developer-sb.eig.toyota.com/apis/dealer\n    properties:\n      - url: https://developer-sb.eig.toyota.com/apis/dealer\n        type: Documentation\n    description: >-\n      Toyota Dealers API enables searching and retrieving dealer information\n      including location, hours, services offered, and inventory. Supports\n      dealer locator applications and service scheduling integrations for\n      Toyota and Lexus dealers.\ncommon:\n  - type: Website\n    url: https://developer.eig.toyota.com/\n\
  \  - type: Developer\n    url: https://developer.eig.toyota.com/\n  - type: Documentation\n    url: https://developer.eig.toyota.com/apis\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/toyota-motor-corporation\n  - type: Rules\n    url: rules/toyota-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/toyota-vocabulary.yml\n  - type: JSONLDContext\n    url: json-ld/toyota-context.jsonld\nname: Toyota\ntags:\n  - Automobiles\n  - Cars\n  - Vehicles\n  - Connected Car\n  - Telematics\n  - Fleet Management\n  - Electric Vehicles\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-25'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Toyota Motor Corporation is a Japanese multinational automotive manufacturer\n  that designs, manufactures, and sells vehicles, including cars, trucks, and buses.\n  Founded in 1937, Toyota has become one of the largest automakers in the world,\n\
  \  known for its reliability, innovation, and commitment to sustainability. Toyota's\n  developer platform (developer.eig.toyota.com) provides APIs for vehicle lifecycle\n  management, telematics and connected services, dealer data, and fleet management\n  for business partners, dealers, fleet operators, and developers building mobility\n  applications. Toyota's product lineup includes hybrids like the Prius, trucks like\n  the Tacoma, and EVs including the bZ4X.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/apis.yml
tags:
- Automobiles
- Cars
- Vehicles
- Connected Car
- Telematics
- Fleet Management
- Electric Vehicles
url: https://raw.githubusercontent.com/api-evangelist/toyota/refs/heads/main/apis.yml
use_cases: []
---
