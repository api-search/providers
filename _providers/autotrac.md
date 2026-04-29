---
api_count: 3
apis:
- description: 'The AutoTrac Supervisor Web platform provides fleet management capabilities for monitoring vehicle locations, managing fleet operations, generating reports, and coordinating driver assignments across '
  name: AutoTrac Supervisor Web API
  slug: supervisor-web-api
- description: The AutoTrac Telemetria platform provides real-time vehicle telemetry data including speed, fuel consumption, engine diagnostics, tire pressure, temperature sensors (for refrigerated cargo), and drive
  name: AutoTrac Telemetria API
  slug: telemetria-api
- description: The AutoTrac Jornada platform manages driver journey logs and compliance with Brazilian driving hour regulations, tracking driving time, rest periods, and journey records for long-distance transport c
  name: AutoTrac Jornada Driver Journey API
  slug: jornada-api
common:
- title: ''
  type: Website
  url: https://www.autotrac.com.br
created: '2024-01-01'
description: AutoTrac is a Brazilian fleet management and vehicle tracking technology company with over 30 years of experience. As the national market leader, AutoTrac provides satellite and cellular fleet tracking solutions, real-time telemetry, driver journey management, and management intelligence platforms for logistics, agriculture, maritime, and insurance sectors. The company operates its own terrestrial satellite communication station and data center for nationwide coverage.
features:
- description: AutoTrac operates its own terrestrial satellite communication station and integrated data center, providing coverage in areas with limited cellular connectivity across Brazil.
  name: Proprietary Satellite Communication
- description: Real-time monitoring of vehicle parameters including location, speed, fuel consumption, engine diagnostics, and cargo temperature for refrigerated transport.
  name: Real-Time Vehicle Telemetry
- description: Jornada platform for tracking driver hours, rest periods, and journey compliance with Brazilian transportation regulations.
  name: Driver Journey Management
- description: Informacoes Gerenciais business intelligence dashboards for fleet performance analytics, cost analysis, and operational reporting.
  name: Fleet Intelligence Reporting
- description: Specialized tracking solutions for agricultural machinery including harvesters, tractors, and implements with field operation monitoring.
  name: Agricultural Equipment Tracking
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with transportation management systems for freight dispatch, route optimization, and delivery confirmation workflows.
  name: TMS Systems
- description: Connect AutoTrac fleet data with ERP systems (SAP, TOTVS) for fleet cost accounting, maintenance scheduling, and asset management.
  name: ERP Systems
- description: API integration with insurance carriers for vehicle recovery, claims verification, and telematics-based premium calculation.
  name: Insurance Platforms
layout: provider
modified: '2026-04-19'
name: AutoTrac
skills: []
slug: autotrac
solutions: []
source_filename: apis.yml
source_yaml: "aid: autotrac\nname: AutoTrac\ndescription: >-\n  AutoTrac is a Brazilian fleet management and vehicle tracking technology company\n  with over 30 years of experience. As the national market leader, AutoTrac provides\n  satellite and cellular fleet tracking solutions, real-time telemetry, driver journey\n  management, and management intelligence platforms for logistics, agriculture, maritime,\n  and insurance sectors. The company operates its own terrestrial satellite communication\n  station and data center for nationwide coverage.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Fleet Management\n  - GPS Tracking\n  - Telematics\n  - Vehicle Tracking\n  - Logistics\n  - Brazil\n  - Satellite Communication\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/autotrac/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: autotrac:supervisor-web-api\n\
  \    name: AutoTrac Supervisor Web API\n    description: >-\n      The AutoTrac Supervisor Web platform provides fleet management capabilities\n      for monitoring vehicle locations, managing fleet operations, generating\n      reports, and coordinating driver assignments across Brazil. API access\n      enables third-party system integration with Supervisor Web data.\n    humanURL: https://www.autotrac.com.br\n    tags:\n      - Fleet Management\n      - GPS Tracking\n      - Vehicle Monitoring\n      - Fleet Operations\n    properties:\n      - type: Website\n        url: https://www.autotrac.com.br\n      - type: Documentation\n        url: https://www.autotrac.com.br\n\n  - aid: autotrac:telemetria-api\n    name: AutoTrac Telemetria API\n    description: >-\n      The AutoTrac Telemetria platform provides real-time vehicle telemetry\n      data including speed, fuel consumption, engine diagnostics, tire pressure,\n      temperature sensors (for refrigerated cargo), and driver behavior\
  \ metrics.\n      Used for preventive maintenance and operational efficiency.\n    humanURL: https://www.autotrac.com.br\n    tags:\n      - Telemetry\n      - Vehicle Diagnostics\n      - Fuel Management\n      - Driver Behavior\n    properties:\n      - type: Website\n        url: https://www.autotrac.com.br\n\n  - aid: autotrac:jornada-api\n    name: AutoTrac Jornada Driver Journey API\n    description: >-\n      The AutoTrac Jornada platform manages driver journey logs and compliance\n      with Brazilian driving hour regulations, tracking driving time, rest periods,\n      and journey records for long-distance transport compliance (Lei do Caminhoneiro).\n    humanURL: https://www.autotrac.com.br\n    tags:\n      - Driver Management\n      - Journey Logs\n      - Compliance\n      - Transportation Regulations\n    properties:\n      - type: Website\n        url: https://www.autotrac.com.br\n\ncommon:\n  - type: Website\n    url: https://www.autotrac.com.br\n  - type: Features\n  \
  \  data:\n      - name: Proprietary Satellite Communication\n        description: >-\n          AutoTrac operates its own terrestrial satellite communication station\n          and integrated data center, providing coverage in areas with limited\n          cellular connectivity across Brazil.\n      - name: Real-Time Vehicle Telemetry\n        description: >-\n          Real-time monitoring of vehicle parameters including location, speed,\n          fuel consumption, engine diagnostics, and cargo temperature for\n          refrigerated transport.\n      - name: Driver Journey Management\n        description: >-\n          Jornada platform for tracking driver hours, rest periods, and journey\n          compliance with Brazilian transportation regulations.\n      - name: Fleet Intelligence Reporting\n        description: >-\n          Informacoes Gerenciais business intelligence dashboards for fleet\n          performance analytics, cost analysis, and operational reporting.\n      - name:\
  \ Agricultural Equipment Tracking\n        description: >-\n          Specialized tracking solutions for agricultural machinery including\n          harvesters, tractors, and implements with field operation monitoring.\n  - type: UseCases\n    data:\n      - name: Long-Distance Logistics Tracking\n        description: >-\n          Track trucks and cargo across Brazil using satellite and cellular\n          communication for nationwide visibility of logistics operations.\n      - name: Refrigerated Cargo Monitoring\n        description: >-\n          Monitor temperature-controlled cargo transport with real-time\n          telemetry alerts for temperature deviations in refrigerated vehicles.\n      - name: Driver Compliance Management\n        description: >-\n          Ensure compliance with Brazilian driver hour regulations by tracking\n          journey logs and rest periods automatically via Jornada.\n      - name: Agricultural Fleet Management\n        description: >-\n          Track\
  \ agricultural equipment, monitor field operations, and manage\n          harvest logistics for agribusiness operations.\n      - name: Insurance Telematics\n        description: >-\n          Provide vehicle behavior and location data to insurance companies\n          for usage-based insurance and stolen vehicle recovery programs.\n  - type: Integrations\n    data:\n      - name: TMS Systems\n        description: >-\n          Integration with transportation management systems for freight\n          dispatch, route optimization, and delivery confirmation workflows.\n      - name: ERP Systems\n        description: >-\n          Connect AutoTrac fleet data with ERP systems (SAP, TOTVS) for\n          fleet cost accounting, maintenance scheduling, and asset management.\n      - name: Insurance Platforms\n        description: >-\n          API integration with insurance carriers for vehicle recovery,\n          claims verification, and telematics-based premium calculation.\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/autotrac/refs/heads/main/apis.yml
tags:
- Fleet Management
- GPS Tracking
- Telematics
- Vehicle Tracking
- Logistics
- Brazil
- Satellite Communication
url: https://raw.githubusercontent.com/api-evangelist/autotrac/refs/heads/main/apis.yml
use_cases:
- description: Track trucks and cargo across Brazil using satellite and cellular communication for nationwide visibility of logistics operations.
  name: Long-Distance Logistics Tracking
- description: Monitor temperature-controlled cargo transport with real-time telemetry alerts for temperature deviations in refrigerated vehicles.
  name: Refrigerated Cargo Monitoring
- description: Ensure compliance with Brazilian driver hour regulations by tracking journey logs and rest periods automatically via Jornada.
  name: Driver Compliance Management
- description: Track agricultural equipment, monitor field operations, and manage harvest logistics for agribusiness operations.
  name: Agricultural Fleet Management
- description: Provide vehicle behavior and location data to insurance companies for usage-based insurance and stolen vehicle recovery programs.
  name: Insurance Telematics
---
