---
api_count: 2
apis:
- description: 'AeroAPI is FlightAware''s query-based REST API for accessing aviation data on demand. It exposes 60+ endpoints across flights, airports, operators, alerts, history, and Foresight predictive analytics, '
  name: FlightAware AeroAPI
  slug: aeroapi
- description: Firehose is FlightAware's real-time streaming feed of global flight data, delivering ADS-B, radar, and ATC-derived position, status, and event messages over a persistent TLS connection for enterprise-
  name: FlightAware Firehose
  slug: firehose
common:
- title: ''
  type: Website
  url: https://www.flightaware.com/
- title: ''
  type: CommercialData
  url: https://www.flightaware.com/commercial/data/
- title: ''
  type: AeroAPIPortal
  url: https://www.flightaware.com/aeroapi/portal/
- title: ''
  type: Documentation
  url: https://www.flightaware.com/aeroapi/portal/documentation
- title: ''
  type: Pricing
  url: https://www.flightaware.com/commercial/aeroapi/
- title: ''
  type: Blog
  url: https://blog.flightaware.com/
- title: ''
  type: Support
  url: https://www.flightaware.com/about/contact/
- title: ''
  type: PrivacyPolicy
  url: https://www.flightaware.com/about/privacy
- title: ''
  type: TermsOfService
  url: https://www.flightaware.com/about/termsofuse
- title: ''
  type: GitHub
  url: https://github.com/flightaware
created: '2025-02-24'
description: FlightAware is a global flight tracking and data platform that provides real-time flight tracking, mapping, and predictive technology to both individual users and commercial aviation companies. The platform collects data from a variety of sources including air traffic control systems, radar, ADS-B, and satellite data, and exposes that data to developers and commercial customers through its AeroAPI query-based REST API and its Firehose streaming feed.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: FlightAware
skills: []
slug: flightaware
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flightaware\nname: FlightAware\ndescription: >-\n  FlightAware is a global flight tracking and data platform that provides\n  real-time flight tracking, mapping, and predictive technology to both\n  individual users and commercial aviation companies. The platform\n  collects data from a variety of sources including air traffic control\n  systems, radar, ADS-B, and satellite data, and exposes that data to\n  developers and commercial customers through its AeroAPI query-based\n  REST API and its Firehose streaming feed.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consumer\ncreated: '2025-02-24'\nmodified: '2026-04-28'\ntags:\n  - Aviation\n  - Flights\n  - Flight Tracking\n  - Mapping\n  - Radar\n  - Satellites\n  - Traffic Control\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/flightaware/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: flightaware:aeroapi\n\
  \    name: FlightAware AeroAPI\n    description: >-\n      AeroAPI is FlightAware's query-based REST API for accessing aviation\n      data on demand. It exposes 60+ endpoints across flights, airports,\n      operators, alerts, history, and Foresight predictive analytics, and\n      supports both real-time and historical flight tracking, status,\n      positions, routes, and notifications.\n    humanURL: https://www.flightaware.com/aeroapi/portal/\n    baseURL: https://aeroapi.flightaware.com/aeroapi\n    tags:\n      - Airports\n      - Alerts\n      - Aviation\n      - Flights\n      - Flight Tracking\n      - Foresight\n      - History\n      - Operators\n      - Predictive Analytics\n    properties:\n      - type: Documentation\n        url: https://www.flightaware.com/aeroapi/portal/documentation\n      - type: Portal\n        url: https://www.flightaware.com/aeroapi/portal/\n      - type: Pricing\n        url: https://www.flightaware.com/commercial/aeroapi/\n  - aid: flightaware:firehose\n\
  \    name: FlightAware Firehose\n    description: >-\n      Firehose is FlightAware's real-time streaming feed of global flight\n      data, delivering ADS-B, radar, and ATC-derived position, status,\n      and event messages over a persistent TLS connection for\n      enterprise-grade flight tracking, situational awareness, and\n      operations analytics.\n    humanURL: https://www.flightaware.com/commercial/firehose/\n    tags:\n      - ADS-B\n      - Aviation\n      - Flight Tracking\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://www.flightaware.com/commercial/firehose/documentation\n      - type: ProductPage\n        url: https://www.flightaware.com/commercial/firehose/\ncommon:\n  - type: Website\n    url: https://www.flightaware.com/\n  - type: CommercialData\n    url: https://www.flightaware.com/commercial/data/\n  - type: AeroAPIPortal\n    url: https://www.flightaware.com/aeroapi/portal/\n  - type: Documentation\n   \
  \ url: https://www.flightaware.com/aeroapi/portal/documentation\n  - type: Pricing\n    url: https://www.flightaware.com/commercial/aeroapi/\n  - type: Blog\n    url: https://blog.flightaware.com/\n  - type: Support\n    url: https://www.flightaware.com/about/contact/\n  - type: PrivacyPolicy\n    url: https://www.flightaware.com/about/privacy\n  - type: TermsOfService\n    url: https://www.flightaware.com/about/termsofuse\n  - type: GitHub\n    url: https://github.com/flightaware\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flightaware/refs/heads/main/apis.yml
tags:
- Aviation
- Flights
- Flight Tracking
- Mapping
- Radar
- Satellites
- Traffic Control
url: https://raw.githubusercontent.com/api-evangelist/flightaware/refs/heads/main/apis.yml
use_cases: []
---
