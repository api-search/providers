---
api_count: 6
apis:
- description: Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Local Bus service. Includes GTFS-Fares V2 fare data.
  name: MDOT MTA Local Bus GTFS
  slug: mta-local-bus-gtfs
- description: Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Light Rail service. Includes GTFS-Fares V2 fare data.
  name: MDOT MTA Light Rail GTFS
  slug: mta-light-rail-gtfs
- description: Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Metro Subway service. Includes GTFS-Fares V2 fare data.
  name: MDOT MTA Metro Subway GTFS
  slug: mta-metro-subway-gtfs
- description: Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA MARC commuter rail service.
  name: MDOT MTA MARC Train GTFS
  slug: mta-marc-train-gtfs
- description: Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Commuter Bus service.
  name: MDOT MTA Commuter Bus GTFS
  slug: mta-commuter-bus-gtfs
- description: System-wide GTFS-RT service alerts feed for all MDOT MTA modes.
  name: MDOT MTA Service Alerts
  slug: mta-service-alerts
common:
- title: ''
  type: Portal
  url: https://www.mta.maryland.gov/developer-resources
- title: ''
  type: Website
  url: https://www.mta.maryland.gov/
- title: ''
  type: GTFS Specification
  url: https://gtfs.org/
- title: ''
  type: Swiftly Documentation
  url: https://swiftly-inc.stoplight.io/docs/realtime-standalone/
created: '2025-05-02'
description: The Maryland Transit Administration (MDOT MTA) supports open transit data initiatives and makes resources available to developers and applications. It primarily uses the General Transit Feed Specification (GTFS) and GTFS-RT to convey schedule, geographic, fare, vehicle position, and trip update data for Local Bus, Light Rail, Metro Subway, MARC Train, and Commuter Bus services in a standardized format.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Maryland Transit Administration
skills: []
slug: maryland-transit-administration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: maryland-transit-administration\nname: Maryland Transit Administration\ndescription: >-\n  The Maryland Transit Administration (MDOT MTA) supports open transit data\n  initiatives and makes resources available to developers and applications.\n  It primarily uses the General Transit Feed Specification (GTFS) and GTFS-RT\n  to convey schedule, geographic, fare, vehicle position, and trip update\n  data for Local Bus, Light Rail, Metro Subway, MARC Train, and Commuter Bus\n  services in a standardized format.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Government\n  - GTFS\n  - GTFS-RT\n  - Public Transportation\n  - Transit\n  - Bus\n  - Rail\n  - Subway\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/maryland-transit-administration/refs/heads/main/apis.yml\ncreated: '2025-05-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: maryland-transit-administration:mta-local-bus-gtfs\n\
  \    name: MDOT MTA Local Bus GTFS\n    description: >-\n      Static GTFS feed and GTFS-RT vehicle positions and trip updates for\n      MDOT MTA Local Bus service. Includes GTFS-Fares V2 fare data.\n    humanURL: https://www.mta.maryland.gov/developer-resources\n    baseURL: https://feeds.mta.maryland.gov/gtfs/local-bus\n    tags:\n      - GTFS\n      - Bus\n      - Public Transportation\n    properties:\n      - type: Documentation\n        url: https://www.mta.maryland.gov/developer-resources\n      - type: GTFS\n        url: https://feeds.mta.maryland.gov/gtfs/local-bus\n  - aid: maryland-transit-administration:mta-light-rail-gtfs\n    name: MDOT MTA Light Rail GTFS\n    description: >-\n      Static GTFS feed and GTFS-RT vehicle positions and trip updates for\n      MDOT MTA Light Rail service. Includes GTFS-Fares V2 fare data.\n    humanURL: https://www.mta.maryland.gov/developer-resources\n    baseURL: https://feeds.mta.maryland.gov/gtfs/light-rail\n    tags:\n      - GTFS\n  \
  \    - Light Rail\n      - Public Transportation\n    properties:\n      - type: Documentation\n        url: https://www.mta.maryland.gov/developer-resources\n      - type: GTFS\n        url: https://feeds.mta.maryland.gov/gtfs/light-rail\n  - aid: maryland-transit-administration:mta-metro-subway-gtfs\n    name: MDOT MTA Metro Subway GTFS\n    description: >-\n      Static GTFS feed and GTFS-RT vehicle positions and trip updates for\n      MDOT MTA Metro Subway service. Includes GTFS-Fares V2 fare data.\n    humanURL: https://www.mta.maryland.gov/developer-resources\n    baseURL: https://feeds.mta.maryland.gov/gtfs/metro\n    tags:\n      - GTFS\n      - Subway\n      - Public Transportation\n    properties:\n      - type: Documentation\n        url: https://www.mta.maryland.gov/developer-resources\n      - type: GTFS\n        url: https://feeds.mta.maryland.gov/gtfs/metro\n  - aid: maryland-transit-administration:mta-marc-train-gtfs\n    name: MDOT MTA MARC Train GTFS\n    description:\
  \ >-\n      Static GTFS feed and GTFS-RT vehicle positions and trip updates for\n      MDOT MTA MARC commuter rail service.\n    humanURL: https://www.mta.maryland.gov/developer-resources\n    baseURL: https://feeds.mta.maryland.gov/gtfs/marc\n    tags:\n      - GTFS\n      - Rail\n      - Public Transportation\n    properties:\n      - type: Documentation\n        url: https://www.mta.maryland.gov/developer-resources\n      - type: GTFS\n        url: https://feeds.mta.maryland.gov/gtfs/marc\n      - type: GTFS-RT Trip Updates\n        url: https://mdotmta-gtfs-rt.s3.amazonaws.com/MARC+RT/marc-tu.pb\n      - type: GTFS-RT Vehicle Positions\n        url: https://mdotmta-gtfs-rt.s3.amazonaws.com/MARC+RT/marc-vp.pb\n  - aid: maryland-transit-administration:mta-commuter-bus-gtfs\n    name: MDOT MTA Commuter Bus GTFS\n    description: >-\n      Static GTFS feed and GTFS-RT vehicle positions and trip updates for\n      MDOT MTA Commuter Bus service.\n    humanURL: https://www.mta.maryland.gov/developer-resources\n\
  \    baseURL: https://feeds.mta.maryland.gov/gtfs/commuter-bus\n    tags:\n      - GTFS\n      - Bus\n      - Public Transportation\n    properties:\n      - type: Documentation\n        url: https://www.mta.maryland.gov/developer-resources\n      - type: GTFS\n        url: https://feeds.mta.maryland.gov/gtfs/commuter-bus\n  - aid: maryland-transit-administration:mta-service-alerts\n    name: MDOT MTA Service Alerts\n    description: >-\n      System-wide GTFS-RT service alerts feed for all MDOT MTA modes.\n    humanURL: https://www.mta.maryland.gov/developer-resources\n    baseURL: https://feeds.mta.maryland.gov/alerts.pb\n    tags:\n      - GTFS-RT\n      - Alerts\n      - Public Transportation\n    properties:\n      - type: Documentation\n        url: https://www.mta.maryland.gov/developer-resources\n      - type: GTFS-RT Alerts\n        url: https://feeds.mta.maryland.gov/alerts.pb\ncommon:\n  - type: Portal\n    url: https://www.mta.maryland.gov/developer-resources\n  - type: Website\n\
  \    url: https://www.mta.maryland.gov/\n  - type: GTFS Specification\n    url: https://gtfs.org/\n  - type: Swiftly Documentation\n    url: https://swiftly-inc.stoplight.io/docs/realtime-standalone/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/maryland-transit-administration/refs/heads/main/apis.yml
tags:
- Government
- GTFS
- GTFS-RT
- Public Transportation
- Transit
- Bus
- Rail
- Subway
url: https://raw.githubusercontent.com/api-evangelist/maryland-transit-administration/refs/heads/main/apis.yml
use_cases: []
---
