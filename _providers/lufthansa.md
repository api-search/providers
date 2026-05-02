---
api_count: 5
api_specs:
- filename: lufthansa-openapi.yml
  format: yaml
  label: Lufthansa Public API
  slug: public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lufthansa/refs/heads/main/openapi/lufthansa-openapi.yml
apis:
- description: The Lufthansa Public API provides reference data for countries, cities, airports, airlines, and aircraft, plus flight schedules and real-time flight status by route, arrival airport, or departure airp
  name: Lufthansa Public API
  slug: public-api
- description: 'The Lufthansa Partner API exposes deeplinks, fares, pricing offers, and seat details for integration partners. NDC capabilities including Smart Offer, NDC Bonus, Servicing, and Technology are part of '
  name: Lufthansa Partner API
  slug: partner-api
- description: The FlightOps and Crew API provides crew-specific services including check-in times, duty events, and weather information for operational use cases.
  name: Lufthansa FlightOps and Crew API
  slug: flightops-crew
- description: The Lufthansa Cargo API provides shipment tracking and LH CARGO flight routings.
  name: Lufthansa Cargo API
  slug: cargo
- description: The Notifications API delivers FlightUpdate notifications and JWT-based authentication tokens for streaming flight events.
  name: Lufthansa Notifications API
  slug: notifications
common:
- title: ''
  type: Website
  url: https://www.lufthansagroup.com
- title: ''
  type: Portal
  url: https://developer.lufthansa.com
- title: ''
  type: Documentation
  url: https://developer.lufthansa.com/docs/read/api_details
- title: ''
  type: Authentication
  url: https://developer.lufthansa.com/docs/read/Authentication
- title: ''
  type: SignUp
  url: https://developer.lufthansa.com/user/register
- title: ''
  type: TermsOfService
  url: https://developer.lufthansa.com/docs/read/General_Terms_and_Conditions
created: '2024-07-02'
description: The Lufthansa Group is a global aviation group that plays a leading role in its European home market. The Lufthansa Open API developer portal exposes reference data, flight operations, offers, notifications, and cargo APIs secured with OAuth2 for partner and public consumers.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Lufthansa
skills: []
slug: lufthansa
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: lufthansa\nname: Lufthansa\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/lufthansa/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\ntags:\n  - Airlines\n  - Travel\n  - Aviation\n  - Flights\ncreated: '2024-07-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ndescription: >-\n  The Lufthansa Group is a global aviation group that plays a leading role in\n  its European home market. The Lufthansa Open API developer portal exposes\n  reference data, flight operations, offers, notifications, and cargo APIs\n  secured with OAuth2 for partner and public consumers.\napis:\n  - aid: lufthansa:public-api\n    name: Lufthansa Public API\n    description: >-\n      The Lufthansa Public API provides reference data for countries, cities,\n      airports, airlines, and aircraft, plus flight schedules and real-time\n      flight status by route,\
  \ arrival airport, or departure airport, customer\n      flight information, seat maps, and lounge data.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.lufthansa.com\n    baseURL: https://api.lufthansa.com/v1\n    tags:\n      - Airlines\n      - Flights\n      - Reference Data\n      - Flight Status\n      - Seat Maps\n      - Lounges\n    properties:\n      - type: Documentation\n        url: https://developer.lufthansa.com/docs/read/api_details\n      - type: Portal\n        url: https://developer.lufthansa.com\n      - type: Authentication\n        url: https://developer.lufthansa.com/docs/read/Authentication\n      - type: OpenAPI\n        url: openapi/lufthansa-openapi.yml\n  - aid: lufthansa:partner-api\n    name: Lufthansa Partner API\n    description: >-\n      The Lufthansa Partner API exposes deeplinks, fares, pricing offers, and\n      seat details for integration partners. NDC capabilities including Smart\n\
  \      Offer, NDC Bonus, Servicing, and Technology are part of the partner\n      program.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.lufthansa.com\n    baseURL: https://api.lufthansa.com/v1\n    tags:\n      - Partner\n      - NDC\n      - Fares\n      - Pricing\n      - Offers\n    properties:\n      - type: Documentation\n        url: https://developer.lufthansa.com/docs/read/api_details\n      - type: Portal\n        url: https://developer.lufthansa.com\n  - aid: lufthansa:flightops-crew\n    name: Lufthansa FlightOps and Crew API\n    description: >-\n      The FlightOps and Crew API provides crew-specific services including\n      check-in times, duty events, and weather information for operational\n      use cases.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.lufthansa.com\n    baseURL: https://api.lufthansa.com/v1\n    tags:\n \
  \     - Crew\n      - Flight Operations\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://developer.lufthansa.com/docs/read/api_details\n      - type: Portal\n        url: https://developer.lufthansa.com\n  - aid: lufthansa:cargo\n    name: Lufthansa Cargo API\n    description: >-\n      The Lufthansa Cargo API provides shipment tracking and LH CARGO flight\n      routings.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.lufthansa.com\n    baseURL: https://api.lufthansa.com/v1\n    tags:\n      - Cargo\n      - Shipment Tracking\n      - Logistics\n    properties:\n      - type: Documentation\n        url: https://developer.lufthansa.com/docs/read/api_details\n      - type: Portal\n        url: https://developer.lufthansa.com\n  - aid: lufthansa:notifications\n    name: Lufthansa Notifications API\n    description: >-\n      The Notifications API delivers FlightUpdate notifications\
  \ and JWT-based\n      authentication tokens for streaming flight events.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.lufthansa.com\n    baseURL: https://api.lufthansa.com/v1\n    tags:\n      - Notifications\n      - JWT\n      - Webhooks\n      - Flight Updates\n    properties:\n      - type: Documentation\n        url: https://developer.lufthansa.com/docs/read/api_details\n      - type: Portal\n        url: https://developer.lufthansa.com\ncommon:\n  - type: Website\n    url: https://www.lufthansagroup.com\n  - type: Portal\n    url: https://developer.lufthansa.com\n  - type: Documentation\n    url: https://developer.lufthansa.com/docs/read/api_details\n  - type: Authentication\n    url: https://developer.lufthansa.com/docs/read/Authentication\n  - type: SignUp\n    url: https://developer.lufthansa.com/user/register\n  - type: TermsOfService\n    url: https://developer.lufthansa.com/docs/read/General_Terms_and_Conditions\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lufthansa/refs/heads/main/apis.yml
tags:
- Airlines
- Travel
- Aviation
- Flights
url: https://raw.githubusercontent.com/api-evangelist/lufthansa/refs/heads/main/apis.yml
use_cases: []
---
