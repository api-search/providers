---
api_count: 10
apis:
- description: The MapQuest Directions API provides routing capabilities with turn-by-turn directions, alternate routes, optimized routes, and travel time estimates using real-time traffic data.
  name: MapQuest Directions API
  slug: mapquest-directions-api
- description: The MapQuest Geocoding API converts addresses into geographic coordinates and vice versa, supporting both single and batch geocoding requests.
  name: MapQuest Geocoding API
  slug: mapquest-geocoding-api
- description: The MapQuest Static Map API returns a map image based on specified parameters including center, zoom, size, and map type.
  name: MapQuest Static Map API
  slug: mapquest-static-map-api
- description: The MapQuest Traffic API returns traffic incidents for a specified bounding box in JSON or XML formats, including road construction and collisions.
  name: MapQuest Traffic API
  slug: mapquest-traffic-api
- description: The MapQuest Search API supports radius, rectangle, polygon, and corridor searches against MapQuest hosted data tables, returning matching points of interest with attributes.
  name: MapQuest Search API
  slug: mapquest-search-api
- description: The MapQuest Place Search API returns places matching a search query, with support for category, location, and bounding-box filtering.
  name: MapQuest Place Search API
  slug: mapquest-place-search-api
- description: The MapQuest Search Ahead API delivers prediction-based search suggestions as users type, supporting addresses, places, categories, and admin areas.
  name: MapQuest Search Ahead API
  slug: mapquest-search-ahead-api
- description: The MapQuest Geolocation API returns the approximate location of a device based on cell tower and Wi-Fi access point information.
  name: MapQuest Geolocation API
  slug: mapquest-geolocation-api
- description: The MapQuest Icons API serves customizable map marker icons for use with MapQuest static and interactive maps.
  name: MapQuest Icons API
  slug: mapquest-icons-api
- description: The MapQuest Data Manager API allows developers to upload, manage, and query custom hosted data tables for use with MapQuest search and mapping services.
  name: MapQuest Data Manager API
  slug: mapquest-data-manager-api
common:
- title: ''
  type: Portal
  url: https://developer.mapquest.com/
- title: ''
  type: Getting Started
  url: https://developer.mapquest.com/documentation/
- title: ''
  type: Sign Up
  url: https://developer.mapquest.com/plan_purchase/steps/business_edition/business_edition_free/register
- title: ''
  type: Login
  url: https://developer.mapquest.com/user/login
- title: ''
  type: Support
  url: https://developer.mapquest.com/support/
- title: ''
  type: Terms of Service
  url: https://hello.mapquest.com/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://hello.mapquest.com/privacy-policy
created: '2025-01-07'
description: MapQuest provides mapping, geocoding, routing, and traffic data APIs for developers to build location-aware applications. The developer portal offers free API keys and documentation for directions, static maps, geocoding, and traffic incident services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: MapQuest
skills: []
slug: mapquest
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: mapquest\nname: MapQuest\ndescription: >-\n  MapQuest provides mapping, geocoding, routing, and traffic data APIs for\n  developers to build location-aware applications. The developer portal offers\n  free API keys and documentation for directions, static maps, geocoding, and\n  traffic incident services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Geocoding\n  - Mapping\n  - Maps\n  - Navigation\n  - Routing\n  - Traffic\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/mapquest/refs/heads/main/apis.yml\ncreated: '2025-01-07'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: mapquest:mapquest-directions-api\n    name: MapQuest Directions API\n    description: >-\n      The MapQuest Directions API provides routing capabilities with turn-by-turn\n      directions, alternate routes, optimized routes, and travel time estimates\n      using real-time traffic data.\n    humanURL:\
  \ https://developer.mapquest.com/documentation/directions-api/\n    baseURL: https://www.mapquestapi.com/directions/v2\n    tags:\n      - Directions\n      - Navigation\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/directions-api/\n  - aid: mapquest:mapquest-geocoding-api\n    name: MapQuest Geocoding API\n    description: >-\n      The MapQuest Geocoding API converts addresses into geographic coordinates\n      and vice versa, supporting both single and batch geocoding requests.\n    humanURL: https://developer.mapquest.com/documentation/geocoding-api/\n    baseURL: https://www.mapquestapi.com/geocoding/v1\n    tags:\n      - Geocoding\n      - Location\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/geocoding-api/\n  - aid: mapquest:mapquest-static-map-api\n    name: MapQuest Static Map API\n    description: >-\n      The MapQuest Static Map API returns\
  \ a map image based on specified\n      parameters including center, zoom, size, and map type.\n    humanURL: https://developer.mapquest.com/documentation/static-map-api/v5/\n    baseURL: https://www.mapquestapi.com/staticmap/v5\n    tags:\n      - Maps\n      - Static Maps\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/static-map-api/v5/\n  - aid: mapquest:mapquest-traffic-api\n    name: MapQuest Traffic API\n    description: >-\n      The MapQuest Traffic API returns traffic incidents for a specified bounding\n      box in JSON or XML formats, including road construction and collisions.\n    humanURL: https://developer.mapquest.com/documentation/traffic-api/\n    baseURL: https://www.mapquestapi.com/traffic/v2\n    tags:\n      - Incidents\n      - Traffic\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/traffic-api/\n      - type: Reference\n        url: https://developer.mapquest.com/documentation/api/traffic/incidents/get.html\n\
  \  - aid: mapquest:mapquest-search-api\n    name: MapQuest Search API\n    description: >-\n      The MapQuest Search API supports radius, rectangle, polygon, and\n      corridor searches against MapQuest hosted data tables, returning\n      matching points of interest with attributes.\n    humanURL: https://developer.mapquest.com/documentation/searchapi/\n    baseURL: https://www.mapquestapi.com/search/v2\n    tags:\n      - Points of Interest\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/searchapi/\n  - aid: mapquest:mapquest-place-search-api\n    name: MapQuest Place Search API\n    description: >-\n      The MapQuest Place Search API returns places matching a search query,\n      with support for category, location, and bounding-box filtering.\n    humanURL: https://developer.mapquest.com/documentation/place-search-api/v5/\n    baseURL: https://www.mapquestapi.com/search/v5\n    tags:\n      - Place Search\n\
  \      - Points of Interest\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/place-search-api/v5/\n  - aid: mapquest:mapquest-search-ahead-api\n    name: MapQuest Search Ahead API\n    description: >-\n      The MapQuest Search Ahead API delivers prediction-based search\n      suggestions as users type, supporting addresses, places, categories,\n      and admin areas.\n    humanURL: https://developer.mapquest.com/documentation/searchahead-api/v5/\n    baseURL: https://www.mapquestapi.com/search/v5\n    tags:\n      - Autocomplete\n      - Search\n      - Search Ahead\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/searchahead-api/v5/\n  - aid: mapquest:mapquest-geolocation-api\n    name: MapQuest Geolocation API\n    description: >-\n      The MapQuest Geolocation API returns the approximate location of a\n      device based on cell tower and Wi-Fi access point\
  \ information.\n    humanURL: https://developer.mapquest.com/documentation/geolocation-api/\n    baseURL: https://www.mapquestapi.com/geolocation/v1\n    tags:\n      - Geolocation\n      - Location\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/geolocation-api/\n  - aid: mapquest:mapquest-icons-api\n    name: MapQuest Icons API\n    description: >-\n      The MapQuest Icons API serves customizable map marker icons for use\n      with MapQuest static and interactive maps.\n    humanURL: https://developer.mapquest.com/documentation/icons-api/\n    baseURL: https://www.mapquestapi.com/icons/v2\n    tags:\n      - Icons\n      - Maps\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/icons-api/\n  - aid: mapquest:mapquest-data-manager-api\n    name: MapQuest Data Manager API\n    description: >-\n      The MapQuest Data Manager API allows developers to upload, manage,\n      and\
  \ query custom hosted data tables for use with MapQuest search\n      and mapping services.\n    humanURL: https://developer.mapquest.com/documentation/data-manager-api/v2/\n    baseURL: https://www.mapquestapi.com/datamanager/v2\n    tags:\n      - Custom Data\n      - Data Management\n    properties:\n      - type: Documentation\n        url: https://developer.mapquest.com/documentation/data-manager-api/v2/\ncommon:\n  - type: Portal\n    url: https://developer.mapquest.com/\n  - type: Getting Started\n    url: https://developer.mapquest.com/documentation/\n  - type: Sign Up\n    url: https://developer.mapquest.com/plan_purchase/steps/business_edition/business_edition_free/register\n  - type: Login\n    url: https://developer.mapquest.com/user/login\n  - type: Support\n    url: https://developer.mapquest.com/support/\n  - type: Terms of Service\n    url: https://hello.mapquest.com/terms-of-use\n  - type: Privacy Policy\n    url: https://hello.mapquest.com/privacy-policy\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mapquest/refs/heads/main/apis.yml
tags:
- Geocoding
- Mapping
- Maps
- Navigation
- Routing
- Traffic
url: https://raw.githubusercontent.com/api-evangelist/mapquest/refs/heads/main/apis.yml
use_cases: []
---
