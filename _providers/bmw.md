---
api_count: 6
apis:
- description: The BMW Vehicle Identification API allows users to access detailed information about BMW vehicles by inputting their unique vehicle identification number (VIN). Provides essential data about a vehicle
  name: BMW Vehicle Identification API
  slug: vehicle-identification-api
- description: The BMW Repair and Maintenance API provides access to maintenance schedules, diagnostic information, and technical specifications for BMW vehicles. Enables automotive technicians and repair shops to a
  name: BMW Repair and Maintenance API
  slug: repair-and-maintenance-api
- description: The BMW Technical Campaign and Map Status API provides real-time data on the status of technical campaigns and software map updates related to BMW vehicles, including campaign progress, completion tim
  name: BMW Technical Campaign and Map Status API
  slug: technical-campaign-and-map-status-api
- description: The BMW Flat Rates API provides access to a database of fixed prices for specific services and repairs on BMW vehicles, enabling transparent and standardized pricing for vehicle maintenance and repair
  name: BMW Flat Rates API
  slug: flat-rates-api
- description: The BMW Smart Maintenance API provides real-time vehicle health and maintenance need information by connecting to the vehicle's onboard diagnostic system, monitoring engine performance, tire pressure,
  name: BMW Smart Maintenance API
  slug: smart-maintenance-api
- description: The BMW Open Data Platform provides developers, researchers, and innovators with access to vehicle data including performance metrics, sensor data, and diagnostic information. The platform supports de
  name: BMW Open Data Platform
  slug: bmw-open-data-platform
common:
- title: ''
  type: Website
  url: https://www.bmw.com
- title: ''
  type: Portal
  url: https://aos.bmwgroup.com/bmw-api
- title: ''
  type: GettingStarted
  url: https://aos.bmwgroup.com/getting-started
- title: ''
  type: Support
  url: https://aos.bmwgroup.com/help/overview
- title: ''
  type: Pricing
  url: https://aos.bmwgroup.com/price-list
- title: ''
  type: TermsOfService
  url: https://aos.bmwgroup.com/conditions-of-use
created: '2025-02-08'
description: BMW is a German multinational company specializing in manufacturing luxury vehicles and motorcycles. BMW provides automotive data APIs through the Aftersales Online System (AOS) portal and the BMW Open Data Platform, enabling dealers, repair shops, and developers to access vehicle identification, maintenance, technical campaign, pricing, and diagnostic data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: BMW
skills: []
slug: bmw
solutions: []
source_filename: apis.yml
source_yaml: "aid: bmw\nname: BMW\ndescription: >-\n  BMW is a German multinational company specializing in manufacturing luxury vehicles\n  and motorcycles. BMW provides automotive data APIs through the Aftersales Online\n  System (AOS) portal and the BMW Open Data Platform, enabling dealers, repair shops,\n  and developers to access vehicle identification, maintenance, technical campaign,\n  pricing, and diagnostic data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bmw/refs/heads/main/apis.yml\ncreated: '2025-02-08'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n  - Automobiles\n  - Cars\n  - Vehicles\n  - Automotive\n  - Connected Car\napis:\n  - aid: bmw:vehicle-identification-api\n    name: BMW Vehicle Identification API\n    description: >-\n      The BMW Vehicle Identification API allows users to access detailed information\n      about BMW vehicles by inputting\
  \ their unique vehicle identification number (VIN).\n      Provides essential data about a vehicle's make, model, year, trim level, engine\n      size, transmission type, and technical configuration.\n    humanURL: https://aos-portal.bmwgroup.com/basic/ui/#/detail/vehicle-identification\n    tags:\n      - Automobiles\n      - VIN\n      - Vehicle Identification\n      - Aftersales\n    properties:\n      - type: Documentation\n        url: https://aos-portal.bmwgroup.com/basic/ui/#/detail/vehicle-identification\n\n  - aid: bmw:repair-and-maintenance-api\n    name: BMW Repair and Maintenance API\n    description: >-\n      The BMW Repair and Maintenance API provides access to maintenance schedules,\n      diagnostic information, and technical specifications for BMW vehicles. Enables\n      automotive technicians and repair shops to access repair procedures and service\n      requirements programmatically.\n    humanURL: https://aos-portal.bmwgroup.com/basic/ui/#/detail/repair-maintenance\n\
  \    tags:\n      - Automobiles\n      - Repair\n      - Maintenance\n      - Diagnostics\n      - Aftersales\n    properties:\n      - type: Documentation\n        url: https://aos-portal.bmwgroup.com/basic/ui/#/detail/repair-maintenance\n\n  - aid: bmw:technical-campaign-and-map-status-api\n    name: BMW Technical Campaign and Map Status API\n    description: >-\n      The BMW Technical Campaign and Map Status API provides real-time data on the\n      status of technical campaigns and software map updates related to BMW vehicles,\n      including campaign progress, completion timelines, and related announcements.\n    humanURL: https://aos-portal.bmwgroup.com/basic/ui/#/detail/technical-campaign-map-status\n    tags:\n      - Automobiles\n      - Technical Campaign\n      - Recall\n      - Software Update\n      - Aftersales\n    properties:\n      - type: Documentation\n        url: https://aos-portal.bmwgroup.com/basic/ui/#/detail/technical-campaign-map-status\n\n  - aid: bmw:flat-rates-api\n\
  \    name: BMW Flat Rates API\n    description: >-\n      The BMW Flat Rates API provides access to a database of fixed prices for specific\n      services and repairs on BMW vehicles, enabling transparent and standardized pricing\n      for vehicle maintenance and repair operations.\n    humanURL: https://aos-portal.bmwgroup.com/basic/ui/#/detail/flatrate\n    tags:\n      - Automobiles\n      - Pricing\n      - Flat Rates\n      - Repair\n      - Aftersales\n    properties:\n      - type: Documentation\n        url: https://aos-portal.bmwgroup.com/basic/ui/#/detail/flatrate\n\n  - aid: bmw:smart-maintenance-api\n    name: BMW Smart Maintenance API\n    description: >-\n      The BMW Smart Maintenance API provides real-time vehicle health and maintenance\n      need information by connecting to the vehicle's onboard diagnostic system, monitoring\n      engine performance, tire pressure, and overall vehicle condition.\n    humanURL: https://aos-portal.bmwgroup.com/basic/ui/#/detail/smart-Maintenance\n\
  \    tags:\n      - Automobiles\n      - Smart Maintenance\n      - Diagnostics\n      - Connected Car\n      - Telematics\n    properties:\n      - type: Documentation\n        url: https://aos-portal.bmwgroup.com/basic/ui/#/detail/smart-Maintenance\n\n  - aid: bmw:bmw-open-data-platform\n    name: BMW Open Data Platform\n    description: >-\n      The BMW Open Data Platform provides developers, researchers, and innovators with\n      access to vehicle data including performance metrics, sensor data, and diagnostic\n      information. The platform supports development of applications enhancing the\n      driving experience and vehicle performance optimization.\n    humanURL: https://bmw-cardata.bmwgroup.com/thirdparty/public/repair-and-maintenance/technical-configuration/api-documentation\n    tags:\n      - Automobiles\n      - Open Data\n      - Connected Car\n      - Telematics\n      - Vehicle Data\n    properties:\n      - type: Documentation\n        url: https://bmw-cardata.bmwgroup.com/thirdparty/public/repair-and-maintenance/technical-configuration/api-documentation\n\
  \ncommon:\n  - url: https://www.bmw.com\n    type: Website\n  - url: https://aos.bmwgroup.com/bmw-api\n    type: Portal\n  - url: https://aos.bmwgroup.com/getting-started\n    type: GettingStarted\n  - url: https://aos.bmwgroup.com/help/overview\n    type: Support\n  - url: https://aos.bmwgroup.com/price-list\n    type: Pricing\n  - url: https://aos.bmwgroup.com/conditions-of-use\n    type: TermsOfService\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bmw/refs/heads/main/apis.yml
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Connected Car
url: https://raw.githubusercontent.com/api-evangelist/bmw/refs/heads/main/apis.yml
use_cases: []
---
