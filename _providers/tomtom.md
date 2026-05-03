---
api_count: 9
api_specs:
- filename: tomtom-maps-openapi.yml
  format: yaml
  label: TomTom Maps API
  slug: tomtom-maps-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-maps-openapi.yml
- filename: tomtom-search-openapi.yml
  format: yaml
  label: TomTom Search API
  slug: tomtom-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-search-openapi.yml
- filename: tomtom-routing-openapi.yml
  format: yaml
  label: TomTom Routing API
  slug: tomtom-routing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-routing-openapi.yml
- filename: tomtom-traffic-openapi.yml
  format: yaml
  label: TomTom Traffic API
  slug: tomtom-traffic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-traffic-openapi.yml
apis:
- description: The TomTom Maps API provides raster and vector map tiles for display in web and mobile applications. Includes copyright information endpoints and supports 19+ zoom levels. Returns PNG/JPG tiles for ra
  name: TomTom Maps API
  slug: tomtom-maps-api
- description: The TomTom Search API provides fuzzy search for addresses, points of interest, and geographic features. Returns latitude/longitude coordinates, place details, and geometry data. Includes additional da
  name: TomTom Search API
  slug: tomtom-search-api
- description: The TomTom Routing API calculates routes between origins and destinations with support for up to 150 waypoints, real-time and historical traffic, vehicle type optimization, EV consumption models, reac
  name: TomTom Routing API
  slug: tomtom-routing-api
- description: The TomTom Traffic API provides real-time traffic incidents and flow data. The Traffic Incidents service delivers accurate information about jams, accidents, and delays. The Traffic Flow service provi
  name: TomTom Traffic API
  slug: tomtom-traffic-api
- description: The TomTom Geocoding API converts structured addresses into geographic coordinates and supports reverse geocoding to translate coordinates into human-readable addresses. The Premium Geocoding API adds
  name: TomTom Geocoding API
  slug: tomtom-geocoding-api
- description: The TomTom Fuel Prices API provides current fuel price information at specific fueling stations, including price by fuel type.
  name: TomTom Fuel Prices API
  slug: tomtom-fuel-prices-api
- description: The TomTom Parking Availability API provides real-time availability status of parking sites and on-street parking, including pricing information.
  name: TomTom Parking Availability API
  slug: tomtom-parking-availability-api
- description: The TomTom Geofencing API enables creation and management of geofence boundaries, location history tracking, and notification delivery when assets enter or exit defined perimeters.
  name: TomTom Geofencing API
  slug: tomtom-geofencing-api
- description: TomTom AutoStream is a map data delivery platform optimized for on-demand and over-the-air cloud-to-device and cloud-to-cloud data streaming for automotive applications.
  name: TomTom AutoStream API
  slug: tomtom-autostream-api
capabilities:
- description: Unified location intelligence capability combining TomTom's Search, Routing, and Traffic APIs. Enables applications and AI agents to search for places, calculate optimized routes, monitor real-time tr
  name: TomTom Location Intelligence
  slug: location-intelligence
common:
- title: ''
  type: Website
  url: https://www.tomtom.com/
- title: ''
  type: Developer Portal
  url: https://developer.tomtom.com/
- title: ''
  type: Documentation
  url: https://developer.tomtom.com/
- title: ''
  type: Sign Up
  url: https://developer.tomtom.com/
- title: ''
  type: API Explorer
  url: https://developer.tomtom.com/api-explorer-index/documentation/product-information/introduction
- title: ''
  type: MCP Server
  url: https://developer.tomtom.com/tomtom-mcp-server
- title: ''
  type: Blog
  url: https://developer.tomtom.com/blog
- title: ''
  type: GitHub Organization
  url: https://github.com/tomtom-international
- title: ''
  type: Pricing
  url: https://developer.tomtom.com/pricing
- title: ''
  type: Terms of Service
  url: https://developer.tomtom.com/terms-and-conditions
created: '2025-01-07'
description: TomTom provides a comprehensive suite of location technology APIs and SDKs including maps, search, routing, traffic, navigation, and automotive data services. The TomTom developer platform is trusted by major automotive manufacturers, logistics companies, and application developers. APIs cover real-time traffic incidents and flow, route calculation, geocoding, points of interest search, geofencing, parking availability, fuel prices, and electric vehicle routing. TomTom also provides an MCP Server for AI integration with location intelligence.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Tomtom Context
  property_count: 4
  slug: tomtom-context
layout: provider
modified: '2026-05-03'
name: TomTom
rules:
- name: TomTom API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: tomtom-rules
skills: []
slug: tomtom
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tomtom\nname: TomTom\ndescription: >-\n  TomTom provides a comprehensive suite of location technology APIs and SDKs including\n  maps, search, routing, traffic, navigation, and automotive data services. The TomTom\n  developer platform is trusted by major automotive manufacturers, logistics companies,\n  and application developers. APIs cover real-time traffic incidents and flow, route\n  calculation, geocoding, points of interest search, geofencing, parking availability,\n  fuel prices, and electric vehicle routing. TomTom also provides an MCP Server for\n  AI integration with location intelligence.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Maps\n  - Traffic\n  - Transportation\n  - Navigation\n  - Location\n  - Geospatial\n  - Routing\n  - Geocoding\ncreated: '2025-01-07'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: tomtom:tomtom-maps-api\n    name: TomTom Maps API\n    description: >-\n      The TomTom Maps API provides raster and vector map tiles for display in web\n      and mobile applications. Includes copyright information endpoints and supports\n      19+ zoom levels. Returns PNG/JPG tiles for raster and Protocol Buffer format\n      for vector tiles.\n    humanURL: https://developer.tomtom.com/map-display-api/documentation/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n      - Maps\n      - Tiles\n      - Raster\n      - Vector\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/map-display-api/documentation/product-information/introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-maps-openapi.yml\n  - aid: tomtom:tomtom-search-api\n    name: TomTom Search API\n    description:\
  \ >-\n      The TomTom Search API provides fuzzy search for addresses, points of interest,\n      and geographic features. Returns latitude/longitude coordinates, place details,\n      and geometry data. Includes additional data retrieval, structured geocoding,\n      and batch search capabilities.\n    humanURL: https://developer.tomtom.com/search-api/documentation/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n      - Search\n      - Geocoding\n      - Points of Interest\n      - Location\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/search-api/documentation/product-information/introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-search-openapi.yml\n      - type: API Explorer\n        url: https://developer.tomtom.com/search-api/api-explorer\n  - aid: tomtom:tomtom-routing-api\n    name: TomTom Routing API\n  \
  \  description: >-\n      The TomTom Routing API calculates routes between origins and destinations with\n      support for up to 150 waypoints, real-time and historical traffic, vehicle type\n      optimization, EV consumption models, reachable range calculation, and batch\n      routing for multiple route requests.\n    humanURL: https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n      - Routing\n      - Navigation\n      - Transportation\n      - Electric Vehicle\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/routing-api/documentation/tomtom-maps/product-information/introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-routing-openapi.yml\n      - type: API Explorer\n        url: https://developer.tomtom.com/routing-api/api-explorer\n  - aid: tomtom:tomtom-traffic-api\n\
  \    name: TomTom Traffic API\n    description: >-\n      The TomTom Traffic API provides real-time traffic incidents and flow data.\n      The Traffic Incidents service delivers accurate information about jams, accidents,\n      and delays. The Traffic Flow service provides observed speeds and travel times\n      updated every minute for key roads. Includes raster and vector tile formats.\n    humanURL: https://developer.tomtom.com/traffic-api/documentation/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n      - Traffic\n      - Incidents\n      - Real-Time\n      - Transportation\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/traffic-api/documentation/product-information/introduction\n      - type: API Explorer\n        url: https://developer.tomtom.com/traffic-api/api-explorer\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/openapi/tomtom-traffic-openapi.yml\n\
  \      - type: NaftikoCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/capabilities/location-intelligence.yaml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/rules/tomtom-rules.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/vocabulary/tomtom-vocabulary.yml\n  - aid: tomtom:tomtom-geocoding-api\n    name: TomTom Geocoding API\n    description: >-\n      The TomTom Geocoding API converts structured addresses into geographic coordinates\n      and supports reverse geocoding to translate coordinates into human-readable addresses.\n      The Premium Geocoding API adds parking and building entrance location data.\n    humanURL: https://developer.tomtom.com/geocoding-api/documentation/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n \
  \     - Geocoding\n      - Location\n      - Address\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/geocoding-api/documentation/product-information/introduction\n      - type: API Explorer\n        url: https://developer.tomtom.com/geocoding-api/api-explorer\n  - aid: tomtom:tomtom-fuel-prices-api\n    name: TomTom Fuel Prices API\n    description: >-\n      The TomTom Fuel Prices API provides current fuel price information at specific\n      fueling stations, including price by fuel type.\n    humanURL: https://developer.tomtom.com/fuel-prices-api/documentation/tomtom-maps/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n      - Fuel\n      - Prices\n      - Automotive\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/fuel-prices-api/documentation/tomtom-maps/product-information/introduction\n  - aid: tomtom:tomtom-parking-availability-api\n    name: TomTom Parking Availability\
  \ API\n    description: >-\n      The TomTom Parking Availability API provides real-time availability status\n      of parking sites and on-street parking, including pricing information.\n    humanURL: https://developer.tomtom.com/parking-availability-api/documentation/tomtom-maps/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n      - Parking\n      - Transportation\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/parking-availability-api/documentation/tomtom-maps/product-information/introduction\n  - aid: tomtom:tomtom-geofencing-api\n    name: TomTom Geofencing API\n    description: >-\n      The TomTom Geofencing API enables creation and management of geofence boundaries,\n      location history tracking, and notification delivery when assets enter or exit\n      defined perimeters.\n    humanURL: https://developer.tomtom.com/geofencing-api/documentation/product-information/introduction\n \
  \   baseURL: https://api.tomtom.com\n    tags:\n      - Geofencing\n      - Location\n      - Tracking\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/geofencing-api/documentation/product-information/introduction\n  - aid: tomtom:tomtom-autostream-api\n    name: TomTom AutoStream API\n    description: >-\n      TomTom AutoStream is a map data delivery platform optimized for on-demand and\n      over-the-air cloud-to-device and cloud-to-cloud data streaming for automotive\n      applications.\n    humanURL: https://developer.tomtom.com/autostream-sdk/documentation/product-information/introduction\n    baseURL: https://api.tomtom.com\n    tags:\n      - Maps\n      - Streaming\n      - Automotive\n    properties:\n      - type: Documentation\n        url: https://developer.tomtom.com/autostream-sdk/documentation/product-information/introduction\nfeatures:\n  - Real-time traffic flow and incidents\n  - Route calculation with\
  \ traffic optimization\n  - Fuzzy address and POI search\n  - Raster and vector map tiles\n  - Geocoding and reverse geocoding\n  - Electric vehicle routing\n  - Geofencing and location tracking\n  - Parking availability and pricing\n  - Fuel price lookup\n  - Batch routing and search\n  - Waypoint optimization\n  - MCP Server for AI integration\nuseCases:\n  - Navigation application development\n  - Fleet management and logistics\n  - Automotive infotainment systems\n  - Delivery route optimization\n  - Location-based services\n  - Traffic monitoring dashboards\n  - EV trip planning\n  - Smart city applications\nsolutions:\n  - Automotive navigation\n  - Enterprise logistics\n  - Mobile mapping\n  - Location intelligence\nintegrations:\n  - MCP Server for AI agents\n  - Android SDK\n  - iOS SDK\n  - ADAS SDK\ncommon:\n  - type: Website\n    url: https://www.tomtom.com/\n  - type: Developer Portal\n    url: https://developer.tomtom.com/\n  - type: Documentation\n    url: https://developer.tomtom.com/\n\
  \  - type: Sign Up\n    url: https://developer.tomtom.com/\n  - type: API Explorer\n    url: https://developer.tomtom.com/api-explorer-index/documentation/product-information/introduction\n  - type: MCP Server\n    url: https://developer.tomtom.com/tomtom-mcp-server\n  - type: Blog\n    url: https://developer.tomtom.com/blog\n  - type: GitHub Organization\n    url: https://github.com/tomtom-international\n  - type: Pricing\n    url: https://developer.tomtom.com/pricing\n  - type: Terms of Service\n    url: https://developer.tomtom.com/terms-and-conditions\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/apis.yml
tags:
- Maps
- Traffic
- Transportation
- Navigation
- Location
- Geospatial
- Routing
- Geocoding
url: https://raw.githubusercontent.com/api-evangelist/tomtom/refs/heads/main/apis.yml
use_cases: []
---
