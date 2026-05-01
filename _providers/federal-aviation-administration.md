---
api_count: 6
apis:
- description: The FAA NOTAM API provides access to Notices to Air Missions (NOTAMs), which are time-critical aeronautical information that could affect a pilot's decision to make a flight. The API allows developers
  name: FAA NOTAM
  slug: notam-api
- description: The FAA Airport Status Web Service (ASWS) provides current airport conditions, including delays and ground stops, for major United States airports. Developers can use the service to retrieve real-time
  name: FAA Airport Status
  slug: airport-status
- description: The FAA National Airspace System Resources (NASR) Subscription provides authoritative aeronautical data covering airports, navigation aids, airways, fixes, and special-use airspace on a 28-day publica
  name: FAA NASR Subscription
  slug: nasr-subscription
- description: The FAA Airmen Registry provides downloadable data on certificated pilots and other airmen in the United States, including pilot certificates, ratings, and medical certificates. The dataset supports v
  name: FAA Airmen Registry
  slug: airmen-registry
- description: The FAA Aircraft Registry provides downloadable data on civil aircraft registered in the United States, including registration, ownership, and airworthiness information. The dataset is widely used for
  name: FAA Aircraft Registry
  slug: aircraft-registry
- description: The FAA System Wide Information Management (SWIM) program is a service-oriented information sharing platform that delivers real-time National Airspace System data to authorized consumers. SWIM publish
  name: FAA System Wide Information Management
  slug: swim
common:
- title: ''
  type: Website
  url: https://www.faa.gov/
- title: ''
  type: Documentation
  url: https://www.faa.gov/data_research
created: '2024-12-03'
description: The Federal Aviation Administration (FAA) is the U.S. Department of Transportation agency responsible for the regulation and oversight of civil aviation. The FAA publishes a range of public data products and APIs covering airport status, NOTAMs, aeronautical information, airmen and aircraft registries, and System Wide Information Management (SWIM) feeds for air traffic operations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Federal Aviation Administration
skills: []
slug: federal-aviation-administration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: federal-aviation-administration\nname: Federal Aviation Administration\ndescription: >-\n  The Federal Aviation Administration (FAA) is the U.S. Department of\n  Transportation agency responsible for the regulation and oversight of civil\n  aviation. The FAA publishes a range of public data products and APIs covering\n  airport status, NOTAMs, aeronautical information, airmen and aircraft\n  registries, and System Wide Information Management (SWIM) feeds for\n  air traffic operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - Aviation\n  - Federal Government\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/federal-aviation-administration/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: federal-aviation-administration:notam-api\n    name: FAA NOTAM\n    description: >-\n      The FAA NOTAM\
  \ API provides access to Notices to Air Missions (NOTAMs),\n      which are time-critical aeronautical information that could affect a\n      pilot's decision to make a flight. The API allows developers to query\n      active NOTAMs by location, type, and effective date for use in flight\n      planning and situational awareness applications.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://api.faa.gov/notamapi/\n    baseURL: https://external-api.faa.gov/notamapi/v1\n    tags:\n      - Aeronautical Information\n      - Air Traffic\n      - NOTAM\n    properties:\n      - type: Documentation\n        url: https://api.faa.gov/notamapi/\n  - aid: federal-aviation-administration:airport-status\n    name: FAA Airport Status\n    description: >-\n      The FAA Airport Status Web Service (ASWS) provides current airport\n      conditions, including delays and ground stops, for major United States\n      airports. Developers can use the\
  \ service to retrieve real-time status\n      information for use in flight planning, traveler-facing applications,\n      and operational dashboards.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.faa.gov/data_research/aviation_data_statistics\n    baseURL: https://soa.smext.faa.gov/asws\n    tags:\n      - Airport\n      - Air Traffic\n      - Delays\n    properties:\n      - type: Documentation\n        url: https://www.faa.gov/data_research/aviation_data_statistics\n  - aid: federal-aviation-administration:nasr-subscription\n    name: FAA NASR Subscription\n    description: >-\n      The FAA National Airspace System Resources (NASR) Subscription provides\n      authoritative aeronautical data covering airports, navigation aids,\n      airways, fixes, and special-use airspace on a 28-day publication cycle.\n      The data is the source of truth used to update aeronautical charts and\n      flight planning systems.\n \
  \   image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://nfdc.faa.gov/nfdcApps/services/ajv5/airportSubscriberFile.jsp\n    tags:\n      - Aeronautical Information\n      - Airports\n      - Navigation\n    properties:\n      - type: Documentation\n        url: https://nfdc.faa.gov/nfdcApps/services/ajv5/airportSubscriberFile.jsp\n  - aid: federal-aviation-administration:airmen-registry\n    name: FAA Airmen Registry\n    description: >-\n      The FAA Airmen Registry provides downloadable data on certificated\n      pilots and other airmen in the United States, including pilot\n      certificates, ratings, and medical certificates. The dataset supports\n      verification, research, and analytics use cases.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.faa.gov/licenses_certificates/airmen_certification/releasable_airmen_download\n    tags:\n      - Airmen\n      - Certification\n\
  \      - Pilots\n    properties:\n      - type: Documentation\n        url: https://www.faa.gov/licenses_certificates/airmen_certification/releasable_airmen_download\n  - aid: federal-aviation-administration:aircraft-registry\n    name: FAA Aircraft Registry\n    description: >-\n      The FAA Aircraft Registry provides downloadable data on civil aircraft\n      registered in the United States, including registration, ownership, and\n      airworthiness information. The dataset is widely used for safety\n      analysis, fleet research, and aircraft tracking applications.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download\n    tags:\n      - Aircraft\n      - Registration\n      - Certification\n    properties:\n      - type: Documentation\n        url: https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download\n\
  \  - aid: federal-aviation-administration:swim\n    name: FAA System Wide Information Management\n    description: >-\n      The FAA System Wide Information Management (SWIM) program is a\n      service-oriented information sharing platform that delivers real-time\n      National Airspace System data to authorized consumers. SWIM publishes\n      message-oriented data streams covering flight, weather, surveillance,\n      and aeronautical information through a common infrastructure.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.faa.gov/air_traffic/technology/swim\n    tags:\n      - Air Traffic\n      - Real-Time\n      - System Wide Information Management\n    properties:\n      - type: Documentation\n        url: https://www.faa.gov/air_traffic/technology/swim\ncommon:\n  - type: Website\n    url: https://www.faa.gov/\n  - type: Documentation\n    url: https://www.faa.gov/data_research\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/federal-aviation-administration/refs/heads/main/apis.yml
tags:
- Aviation
- Federal Government
url: https://raw.githubusercontent.com/api-evangelist/federal-aviation-administration/refs/heads/main/apis.yml
use_cases: []
---
