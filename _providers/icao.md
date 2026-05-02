---
api_count: 7
apis:
- description: The ICAO API Data Service provides programmatic access to authoritative civil aviation data published by ICAO, with continuously updated endpoints across six data areas. An API key is required and res
  name: ICAO API Data Service
  slug: icao-api-data-service
- description: Endpoints providing reference and statistical data on ICAO Member States, including state-level aviation activity, agreements, and contracting state metadata.
  name: ICAO States API
  slug: icao-states-api
- description: Endpoints exposing ICAO airport reference data including DOC7910 location indicators, airport metadata, and related aerodrome information.
  name: ICAO Airports API
  slug: icao-airports-api
- description: Endpoints providing operator reference data including DOC8585 three-letter operator designators, telephony, and operator details for airlines and aircraft operators.
  name: ICAO Operators API
  slug: icao-operators-api
- description: Endpoints providing airspace, navigation, and route data including flight information regions and airspace structures relevant to international air navigation.
  name: ICAO Airspace API
  slug: icao-airspace-api
- description: Endpoints providing access to aviation safety occurrence data, including accident and incident records reported through ICAO's safety information systems.
  name: ICAO Occurrences API
  slug: icao-occurrences-api
- description: Endpoints providing aircraft reference data including DOC8643 aircraft type designators, manufacturer information, and aircraft performance categories.
  name: ICAO Aircraft API
  slug: icao-aircraft-api
common:
- title: ''
  type: Website
  url: https://www.icao.int/
- title: ''
  type: Portal
  url: https://applications.icao.int/dataservices/default.aspx
- title: ''
  type: Documentation
  url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx
- title: ''
  type: Samples
  url: https://applications.icao.int/dataservices/api-data-samples
- title: ''
  type: Pricing
  url: https://store.icao.int/en/aviation-api-data-service
- title: ''
  type: Terms of Service
  url: https://www.icao.int/sites/default/files/Aviation-API-Data-Service/Documents/User-Terms-and-Condtions-for-ICAO-API-Data-Service-APIs-LEB_FINAL_13.04.21.pdf
- title: ''
  type: Support
  url: https://www.icao.int/contact/
created: '2026-03-16'
description: The International Civil Aviation Organization (ICAO) is a specialized agency of the United Nations that codifies the principles and techniques of international air navigation and fosters the planning and development of international air transport. ICAO's API Data Service provides 50+ continuously updated APIs covering states, airports, operators, airspace, occurrences, and aircraft, including official reference datasets such as DOC7910 location indicators, DOC8585 operator three-letter codes, and DOC8643 aircraft type designators.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: ICAO
skills: []
slug: icao
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: icao\nname: ICAO\ndescription: >-\n  The International Civil Aviation Organization (ICAO) is a specialized agency\n  of the United Nations that codifies the principles and techniques of\n  international air navigation and fosters the planning and development of\n  international air transport. ICAO's API Data Service provides 50+\n  continuously updated APIs covering states, airports, operators, airspace,\n  occurrences, and aircraft, including official reference datasets such as\n  DOC7910 location indicators, DOC8585 operator three-letter codes, and\n  DOC8643 aircraft type designators.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Airlines\n  - Airports\n  - Airspace\n  - Aviation\n  - Reference Data\n  - Standards\n  - United Nations\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/icao/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: icao:icao-api-data-service\n    name: ICAO API Data Service\n    description: >-\n      The ICAO API Data Service provides programmatic access to authoritative\n      civil aviation data published by ICAO, with continuously updated\n      endpoints across six data areas. An API key is required and responses\n      are available in CSV and JSON formats; pricing tiers include booster\n      packs, full data-set packages, and unlimited-call subscriptions.\n    humanURL: https://applications.icao.int/dataservices/default.aspx\n    tags:\n      - Aviation Data\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n      - type: Portal\n        url: https://applications.icao.int/dataservices/default.aspx\n      - type: Samples\n        url: https://applications.icao.int/dataservices/api-data-samples\n      - type: Terms of Service\n        url: https://www.icao.int/sites/default/files/Aviation-API-Data-Service/Documents/User-Terms-and-Condtions-for-ICAO-API-Data-Service-APIs-LEB_FINAL_13.04.21.pdf\n\
  \  - aid: icao:icao-states-api\n    name: ICAO States API\n    description: >-\n      Endpoints providing reference and statistical data on ICAO Member\n      States, including state-level aviation activity, agreements, and\n      contracting state metadata.\n    humanURL: https://applications.icao.int/dataservices/default.aspx\n    tags:\n      - States\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n  - aid: icao:icao-airports-api\n    name: ICAO Airports API\n    description: >-\n      Endpoints exposing ICAO airport reference data including DOC7910\n      location indicators, airport metadata, and related aerodrome\n      information.\n    humanURL: https://applications.icao.int/dataservices/default.aspx\n    tags:\n      - Airports\n      - DOC7910\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n\
  \  - aid: icao:icao-operators-api\n    name: ICAO Operators API\n    description: >-\n      Endpoints providing operator reference data including DOC8585\n      three-letter operator designators, telephony, and operator details\n      for airlines and aircraft operators.\n    humanURL: https://applications.icao.int/dataservices/default.aspx\n    tags:\n      - DOC8585\n      - Operators\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n  - aid: icao:icao-airspace-api\n    name: ICAO Airspace API\n    description: >-\n      Endpoints providing airspace, navigation, and route data including\n      flight information regions and airspace structures relevant to\n      international air navigation.\n    humanURL: https://applications.icao.int/dataservices/default.aspx\n    tags:\n      - Airspace\n      - Navigation\n    properties:\n      - type: Documentation\n        url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n\
  \  - aid: icao:icao-occurrences-api\n    name: ICAO Occurrences API\n    description: >-\n      Endpoints providing access to aviation safety occurrence data,\n      including accident and incident records reported through ICAO's\n      safety information systems.\n    humanURL: https://applications.icao.int/dataservices/default.aspx\n    tags:\n      - Accidents\n      - Incidents\n      - Safety\n    properties:\n      - type: Documentation\n        url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n  - aid: icao:icao-aircraft-api\n    name: ICAO Aircraft API\n    description: >-\n      Endpoints providing aircraft reference data including DOC8643\n      aircraft type designators, manufacturer information, and aircraft\n      performance categories.\n    humanURL: https://applications.icao.int/dataservices/default.aspx\n    tags:\n      - Aircraft\n      - DOC8643\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n\
  common:\n  - type: Website\n    url: https://www.icao.int/\n  - type: Portal\n    url: https://applications.icao.int/dataservices/default.aspx\n  - type: Documentation\n    url: https://www.icao.int/safety/iStars/Pages/API-Data-Service.aspx\n  - type: Samples\n    url: https://applications.icao.int/dataservices/api-data-samples\n  - type: Pricing\n    url: https://store.icao.int/en/aviation-api-data-service\n  - type: Terms of Service\n    url: https://www.icao.int/sites/default/files/Aviation-API-Data-Service/Documents/User-Terms-and-Condtions-for-ICAO-API-Data-Service-APIs-LEB_FINAL_13.04.21.pdf\n  - type: Support\n    url: https://www.icao.int/contact/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/icao/refs/heads/main/apis.yml
tags:
- Airlines
- Airports
- Airspace
- Aviation
- Reference Data
- Standards
- United Nations
url: https://raw.githubusercontent.com/api-evangelist/icao/refs/heads/main/apis.yml
use_cases: []
---
