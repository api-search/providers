---
api_count: 4
api_specs:
- filename: metro-transit-nextrip-openapi.json
  format: json
  label: Metro Transit NexTrip API
  slug: nextrip-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-nextrip-openapi.json
- filename: metro-transit-alerts-openapi.json
  format: json
  label: Metro Transit Service Alerts API
  slug: alerts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-alerts-openapi.json
- filename: metro-transit-tripplanner-openapi.json
  format: json
  label: Metro Transit Trip Planner API
  slug: trip-planner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-tripplanner-openapi.json
- filename: metro-transit-schedule-openapi.json
  format: json
  label: Metro Transit Schedule API
  slug: schedule-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-schedule-openapi.json
apis:
- description: The NexTrip API provides real-time departure information for creating transit departure displays. It offers endpoints for routes, stops, and real-time departure data for the Twin Cities metro area.
  name: Metro Transit NexTrip API
  slug: nextrip-api
- description: The Service Alerts API provides current service alerts for routes and stops across the Twin Cities Metro Transit network.
  name: Metro Transit Service Alerts API
  slug: alerts-api
- description: The Trip Planner API supports building itineraries and routing trips across the Twin Cities Metro Transit system using stops, places, and schedules.
  name: Metro Transit Trip Planner API
  slug: trip-planner-api
- description: The Schedule API provides published timetable data including routes, directions, stops, and schedule details for the Twin Cities Metro Transit system.
  name: Metro Transit Schedule API
  slug: schedule-api
common:
- title: ''
  type: Portal
  url: https://www.metrotransit.org/developer-resources
- title: ''
  type: Documentation
  url: https://svc.metrotransit.org/swagger/index.html
- title: ''
  type: Website
  url: https://www.metrotransit.org/
created: '2025-05-02'
description: Metro Transit provides real-time departure information, service alerts, trip planning, and schedule data APIs for the Minneapolis-Saint Paul metropolitan transit system. The APIs support creating transit departure displays and accessing real-time bus and train arrival data for the Twin Cities.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Metro Transit
skills: []
slug: metro-transit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: metro-transit\nname: Metro Transit\ndescription: >-\n  Metro Transit provides real-time departure information, service alerts, trip\n  planning, and schedule data APIs for the Minneapolis-Saint Paul metropolitan\n  transit system. The APIs support creating transit departure displays and\n  accessing real-time bus and train arrival data for the Twin Cities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Minneapolis\n  - Minnesota\n  - Public Transportation\n  - Real-Time\n  - Transit\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/apis.yml\ncreated: '2025-05-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: metro-transit:nextrip-api\n    name: Metro Transit NexTrip API\n    description: >-\n      The NexTrip API provides real-time departure information for creating\n      transit departure displays. It offers endpoints for routes, stops, and\n\
  \      real-time departure data for the Twin Cities metro area.\n    humanURL: https://svc.metrotransit.org/swagger/index.html\n    baseURL: https://svc.metrotransit.org/nextripv2\n    tags:\n      - Departures\n      - Real-Time\n      - Transit\n    properties:\n      - type: Documentation\n        url: https://svc.metrotransit.org/swagger/index.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-nextrip-openapi.json\n  - aid: metro-transit:alerts-api\n    name: Metro Transit Service Alerts API\n    description: >-\n      The Service Alerts API provides current service alerts for routes and\n      stops across the Twin Cities Metro Transit network.\n    humanURL: https://svc.metrotransit.org/swagger/index.html\n    baseURL: https://svc.metrotransit.org/alerts\n    tags:\n      - Alerts\n      - Real-Time\n      - Transit\n    properties:\n      - type: Documentation\n        url:\
  \ https://svc.metrotransit.org/swagger/index.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-alerts-openapi.json\n  - aid: metro-transit:trip-planner-api\n    name: Metro Transit Trip Planner API\n    description: >-\n      The Trip Planner API supports building itineraries and routing trips\n      across the Twin Cities Metro Transit system using stops, places, and\n      schedules.\n    humanURL: https://svc.metrotransit.org/swagger/index.html\n    baseURL: https://svc.metrotransit.org/tripplanner\n    tags:\n      - Trip Planner\n      - Routing\n      - Transit\n    properties:\n      - type: Documentation\n        url: https://svc.metrotransit.org/swagger/index.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-tripplanner-openapi.json\n  - aid: metro-transit:schedule-api\n\
  \    name: Metro Transit Schedule API\n    description: >-\n      The Schedule API provides published timetable data including routes,\n      directions, stops, and schedule details for the Twin Cities Metro\n      Transit system.\n    humanURL: https://svc.metrotransit.org/swagger/index.html\n    baseURL: https://svc.metrotransit.org/schedule\n    tags:\n      - Schedule\n      - Timetable\n      - Transit\n    properties:\n      - type: Documentation\n        url: https://svc.metrotransit.org/swagger/index.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/openapi/metro-transit-schedule-openapi.json\ncommon:\n  - type: Portal\n    url: https://www.metrotransit.org/developer-resources\n  - type: Documentation\n    url: https://svc.metrotransit.org/swagger/index.html\n  - type: Website\n    url: https://www.metrotransit.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/apis.yml
tags:
- Minneapolis
- Minnesota
- Public Transportation
- Real-Time
- Transit
url: https://raw.githubusercontent.com/api-evangelist/metro-transit/refs/heads/main/apis.yml
use_cases: []
---
