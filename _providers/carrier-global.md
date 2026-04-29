---
api_count: 5
apis:
- description: REST API surface exposing Lynx Fleet telematics and control data for diesel and electric transport refrigeration units (TRUs). Enables systems integrators to pull asset inventory, setpoints, temperatu
  name: Carrier Lynx Fleet API
  slug: lynx-fleet-api
- description: i-Vu is Carrier's web-based commercial building automation system for monitoring and controlling HVAC, lighting, and related building systems. It integrates with BACnet and other standard building pro
  name: Carrier i-Vu Building Automation
  slug: i-vu-building-automation
- description: Carrier Comfort Network (CCN) is Carrier's proprietary control and communication network for tying together chillers, air handlers, and related HVAC equipment, typically integrated into BMS/BAS deploy
  name: Carrier Comfort Network
  slug: carrier-comfort-network
- description: Abound is Carrier's cloud-based building intelligence platform that aggregates data from HVAC, IAQ sensors, and occupancy systems to provide indoor-environmental-quality analytics, energy insights, an
  name: Carrier Abound
  slug: abound-building-platform
- description: The Carrier SmartHome app lets homeowners remotely control Carrier connected smart thermostats and residential HVAC equipment. No public developer API is currently published; integration is via the co
  name: Carrier SmartHome App
  slug: carrier-smarthome
common:
- title: ''
  type: Website
  url: https://www.corporate.carrier.com
- title: ''
  type: ConsumerSite
  url: https://www.carrier.com/us/en/
- title: ''
  type: Documentation
  url: https://doc-api.fleet.lynx.carrier.io/
- title: ''
  type: Portal
  url: https://api.tta.lynxfleet.carrier.com/
- title: ''
  type: GettingStarted
  url: https://doc-api.fleet.lynx.carrier.io/api-documentation
- title: ''
  type: Abound
  url: https://www.carrier.com/commercial/en/us/software/abound/
- title: ''
  type: BuildingAutomation
  url: https://www.carrier.com/commercial/en/us/software/building-automation/i-vu-building-automation/
- title: ''
  type: SmartHome
  url: https://www.carrier.com/residential/en/us/smart-thermostats/smarthome-app/
- title: ''
  type: InvestorRelations
  url: https://ir.carrier.com
- title: ''
  type: Careers
  url: https://careers.corporate.carrier.com
- title: ''
  type: Contact
  url: https://www.corporate.carrier.com/contact-us/
created: '2026-03-21'
description: Carrier Global Corporation is a global provider of healthy, safe, sustainable, and intelligent building and cold-chain solutions, spanning HVAC, refrigeration, fire, security, and building automation technologies. Its digital ecosystem includes the Lynx Fleet telematics platform (Lynx APIs for transport refrigeration units), the Abound building management platform, i-Vu and Carrier Comfort Network for commercial building automation, and the Carrier SmartHome app for residential smart thermostats.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Carrier Global Context
  property_count: 10
  slug: carrier-global-context
layout: provider
modified: '2026-04-23'
name: Carrier Global
skills: []
slug: carrier-global
solutions: []
source_filename: apis.yml
source_yaml: "aid: carrier-global\nname: Carrier Global\ndescription: >-\n  Carrier Global Corporation is a global provider of healthy, safe, sustainable,\n  and intelligent building and cold-chain solutions, spanning HVAC, refrigeration,\n  fire, security, and building automation technologies. Its digital ecosystem\n  includes the Lynx Fleet telematics platform (Lynx APIs for transport\n  refrigeration units), the Abound building management platform, i-Vu and\n  Carrier Comfort Network for commercial building automation, and the Carrier\n  SmartHome app for residential smart thermostats.\ntype: Index\nposition: Provider\naccess: Partner\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - HVAC\n  - Cold Chain\n  - Telematics\n  - Building Automation\n  - IoT\n  - Refrigeration\n  - Fortune 500\ncreated: '2026-03-21'\nmodified: '2026-04-23'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carrier-global/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: carrier-global:lynx-fleet-api\n    name: Carrier Lynx Fleet API\n    description: >-\n      REST API surface exposing Lynx Fleet telematics and control data for\n      diesel and electric transport refrigeration units (TRUs). Enables\n      systems integrators to pull asset inventory, setpoints, temperatures,\n      alarms, and GPS location, and to issue two-way commands to connected\n      refrigeration units directly from existing transport-management systems.\n    humanURL: https://doc-api.fleet.lynx.carrier.io/\n    baseURL: https://doc-api.fleet.lynx.carrier.io/\n    tags:\n      - Cold Chain\n      - Telematics\n      - Fleet\n      - Refrigeration\n      - IoT\n    properties:\n      - type: Documentation\n        url: https://doc-api.fleet.lynx.carrier.io/api-documentation\n      - type: Portal\n        url: https://api.tta.lynxfleet.carrier.com/\n      - type: Reference\n        url: https://doc-api.fleet.lynx.carrier.io/docs/lynx-prod-api/1/routes/v1/assets/get\n\
  \      - type: Products\n        url: https://api.tta.lynxfleet.carrier.com/products\n  - aid: carrier-global:i-vu-building-automation\n    name: Carrier i-Vu Building Automation\n    description: >-\n      i-Vu is Carrier's web-based commercial building automation system for\n      monitoring and controlling HVAC, lighting, and related building systems.\n      It integrates with BACnet and other standard building protocols rather\n      than a public REST API surface.\n    humanURL: https://www.carrier.com/commercial/en/us/software/building-automation/i-vu-building-automation/\n    tags:\n      - Building Automation\n      - BACnet\n      - HVAC\n    properties:\n      - type: Documentation\n        url: https://www.carrier.com/commercial/en/us/software/building-automation/i-vu-building-automation/\n  - aid: carrier-global:carrier-comfort-network\n    name: Carrier Comfort Network\n    description: >-\n      Carrier Comfort Network (CCN) is Carrier's proprietary control and\n      communication\
  \ network for tying together chillers, air handlers, and\n      related HVAC equipment, typically integrated into BMS/BAS deployments.\n    humanURL: https://www.carrier.com/commercial/en/us/carrier-comfort-network/\n    tags:\n      - Building Automation\n      - HVAC\n      - Chillers\n    properties:\n      - type: Documentation\n        url: https://www.carrier.com/commercial/en/us/carrier-comfort-network/\n  - aid: carrier-global:abound-building-platform\n    name: Carrier Abound\n    description: >-\n      Abound is Carrier's cloud-based building intelligence platform that\n      aggregates data from HVAC, IAQ sensors, and occupancy systems to provide\n      indoor-environmental-quality analytics, energy insights, and\n      healthy-building dashboards for commercial real estate operators.\n    humanURL: https://www.carrier.com/commercial/en/us/software/abound/\n    tags:\n      - Building Intelligence\n      - IAQ\n      - Analytics\n    properties:\n      - type: Documentation\n\
  \        url: https://www.carrier.com/commercial/en/us/software/abound/\n  - aid: carrier-global:carrier-smarthome\n    name: Carrier SmartHome App\n    description: >-\n      The Carrier SmartHome app lets homeowners remotely control Carrier\n      connected smart thermostats and residential HVAC equipment. No public\n      developer API is currently published; integration is via the consumer\n      mobile app and connected thermostat web portals.\n    humanURL: https://www.carrier.com/residential/en/us/smart-thermostats/smarthome-app/\n    tags:\n      - Smart Home\n      - Thermostats\n      - Residential\n    properties:\n      - type: Documentation\n        url: https://www.carrier.com/residential/en/us/smart-thermostats/smarthome-app/\ncommon:\n  - type: Website\n    url: https://www.corporate.carrier.com\n  - type: ConsumerSite\n    url: https://www.carrier.com/us/en/\n  - type: Documentation\n    name: Lynx Fleet API Documentation\n    url: https://doc-api.fleet.lynx.carrier.io/\n\
  \  - type: Portal\n    name: Lynx Fleet Developer Portal\n    url: https://api.tta.lynxfleet.carrier.com/\n  - type: GettingStarted\n    url: https://doc-api.fleet.lynx.carrier.io/api-documentation\n  - type: Abound\n    url: https://www.carrier.com/commercial/en/us/software/abound/\n  - type: BuildingAutomation\n    url: https://www.carrier.com/commercial/en/us/software/building-automation/i-vu-building-automation/\n  - type: SmartHome\n    url: https://www.carrier.com/residential/en/us/smart-thermostats/smarthome-app/\n  - type: InvestorRelations\n    url: https://ir.carrier.com\n  - type: Careers\n    url: https://careers.corporate.carrier.com\n  - type: Contact\n    url: https://www.corporate.carrier.com/contact-us/\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carrier-global/refs/heads/main/apis.yml
tags:
- HVAC
- Cold Chain
- Telematics
- Building Automation
- IoT
- Refrigeration
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/carrier-global/refs/heads/main/apis.yml
use_cases: []
---
