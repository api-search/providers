---
api_count: 1
api_specs:
- filename: sound-transit-onebusaway-openapi.yml
  format: yaml
  label: Sound Transit OneBusAway API
  slug: sound-transit-onebusaway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/openapi/sound-transit-onebusaway-openapi.yml
apis:
- description: The Sound Transit OneBusAway API provides access to real-time and scheduled transit data for the Puget Sound region. Supports route information, stop locations, real-time arrivals and departures, vehi
  name: Sound Transit OneBusAway API
  slug: sound-transit-onebusaway-api
capabilities:
- description: Unified capability for accessing Sound Transit real-time and scheduled transit data for the Puget Sound region. Enables transit app developers, trip planners, and data analysts to query routes, stops,
  name: Sound Transit Transit Data
  slug: transit-data
common:
- title: ''
  type: Portal
  url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd
- title: ''
  type: Website
  url: https://www.soundtransit.org/
- title: ''
  type: GTFS Static Feeds
  url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/otd-downloads
- title: ''
  type: GTFS-RT Service Alerts (Protocol Buffers)
  url: https://s3.amazonaws.com/st-service-alerts-prod/alerts.pb
- title: ''
  type: GTFS-RT Service Alerts (JSON)
  url: https://s3.amazonaws.com/st-service-alerts-prod/alerts_pb.json
- title: ''
  type: Transitland Feed
  url: https://www.transit.land/feeds/f-c23-soundtransit
- title: ''
  type: OneBusAway
  url: https://onebusaway.org/
- title: ''
  type: Terms of Use
  url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/transit-data-terms-use
- title: ''
  type: API Key Request
  url: mailto:oba_api_key@soundtransit.org
- title: ''
  type: Support
  url: mailto:open_transit_data@soundtransit.org
- title: ''
  type: Trip Planner
  url: https://tripplanner.kingcounty.gov/
- title: ''
  type: Real-Time Coverage
  url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd
created: '2026-03-16'
description: Sound Transit is a regional transit authority serving the Seattle-Puget Sound area of Washington State, operating light rail, commuter rail, and express bus services. The Sound Transit Open Transit Data (OTD) program provides GTFS static and real-time data feeds, OneBusAway API access, and GTFS-RT service alerts for transit application developers and researchers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Sound Transit Context
  property_count: 15
  slug: sound-transit-context
layout: provider
modified: '2026-05-02'
name: Sound Transit
rules:
- name: Sound Transit API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 7
  slug: sound-transit-rules
skills: []
slug: sound-transit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sound-transit\nname: Sound Transit\ndescription: >-\n  Sound Transit is a regional transit authority serving the Seattle-Puget Sound area\n  of Washington State, operating light rail, commuter rail, and express bus services.\n  The Sound Transit Open Transit Data (OTD) program provides GTFS static and real-time\n  data feeds, OneBusAway API access, and GTFS-RT service alerts for transit application\n  developers and researchers.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Transit\n  - Transportation\n  - GTFS\n  - Real-Time\n  - Public Transit\n  - Government\n  - Seattle\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: sound-transit:sound-transit-onebusaway-api\n    name: Sound Transit OneBusAway API\n    description: >-\n  \
  \    The Sound Transit OneBusAway API provides access to real-time and scheduled\n      transit data for the Puget Sound region. Supports route information, stop\n      locations, real-time arrivals and departures, vehicle positions, and trip\n      details for 1 Line, 2 Line, T Line, and ST Express routes.\n    humanURL: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd\n    baseURL: https://api.pugetsound.onebusaway.org/api/where\n    tags:\n      - Transit\n      - GTFS\n      - Real-Time\n      - Routes\n      - Stops\n      - Vehicles\n    properties:\n      - type: Documentation\n        url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd\n      - type: Reference\n        url: http://developer.onebusaway.org/\n      - type: GTFS Downloads\n        url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/otd-downloads\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/openapi/sound-transit-onebusaway-openapi.yml\n\
  \    contact:\n      - FN: Sound Transit Open Transit Data\n        url: https://www.soundtransit.org/\n        email: open_transit_data@soundtransit.org\ncommon:\n  - type: Portal\n    url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd\n  - type: Website\n    url: https://www.soundtransit.org/\n  - type: GTFS Static Feeds\n    url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/otd-downloads\n  - type: GTFS-RT Service Alerts (Protocol Buffers)\n    url: https://s3.amazonaws.com/st-service-alerts-prod/alerts.pb\n  - type: GTFS-RT Service Alerts (JSON)\n    url: https://s3.amazonaws.com/st-service-alerts-prod/alerts_pb.json\n  - type: Transitland Feed\n    url: https://www.transit.land/feeds/f-c23-soundtransit\n  - type: OneBusAway\n    url: https://onebusaway.org/\n  - type: Terms of Use\n    url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/transit-data-terms-use\n \
  \ - type: API Key Request\n    url: mailto:oba_api_key@soundtransit.org\n  - type: Support\n    url: mailto:open_transit_data@soundtransit.org\n  - type: Trip Planner\n    url: https://tripplanner.kingcounty.gov/\n  - type: Real-Time Coverage\n    url: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/apis.yml
tags:
- Transit
- Transportation
- GTFS
- Real-Time
- Public Transit
- Government
- Seattle
url: https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/apis.yml
use_cases: []
---
