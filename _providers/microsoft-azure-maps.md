---
api_count: 10
apis:
- description: Provides geocoding, reverse geocoding, address parsing, point of interest search, and structured search. Returns candidate matches ranked by relevance for free-form, structured, and POI queries with w
  name: Azure Maps Search API
  slug: ''
- description: Calculates routes between origin and destination, provides turn-by-turn directions, supports multiple travel modes, traffic-aware routing, route matrices, and route range (isochrone) calculations.
  name: Azure Maps Route API
  slug: ''
- description: Returns map tiles, static images, and vector tiles in multiple styles including satellite, road, and hybrid. Supports raster and vector tile formats, custom imagery, and traffic overlays for embedding
  name: Azure Maps Render API
  slug: ''
- description: Provides real-time and historical traffic data including traffic flow, incident reports, and traffic tile imagery. Useful for routing, fleet management, and applications requiring up-to-date road cond
  name: Azure Maps Traffic API
  slug: ''
- description: Provides current weather conditions, hourly and daily forecasts, severe weather alerts, weather along a route, and historical weather. Powered by AccuWeather data and global coverage.
  name: Azure Maps Weather API
  slug: ''
- description: Returns time zone information for a given coordinate, IANA time zone ID, or Windows time zone ID. Includes current time, daylight saving offsets, and time zone metadata.
  name: Azure Maps Timezone API
  slug: ''
- description: Returns the ISO country code for a supplied IP address, useful for content localization, regulatory compliance, and access control based on user geographic location.
  name: Azure Maps Geolocation API
  slug: ''
- description: Performs spatial computations such as distance, closest point, point in polygon, geofence evaluation, and great circle distance. Enables location analytics and spatial reasoning workloads.
  name: Azure Maps Spatial API
  slug: ''
- description: Returns elevation data in meters above sea level for points, polylines, and bounding boxes. Useful for terrain analysis, topographic visualization, and elevation profile calculations along a route.
  name: Azure Maps Elevation API
  slug: ''
- description: Indoor maps service for creating, managing, and rendering custom indoor maps. Supports drawing package conversion, dataset and tileset management, feature state, and wayfinding for indoor environments
  name: Azure Maps Creator API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/azure-maps/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/azure-maps/quick-demo-map-app
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/azure-maps/azure-maps-authentication
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/azure-maps/about-azure-maps
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/azure-maps/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/tag/azure-maps/
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/azure/azure-maps/release-notes-map-control
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/azure-maps
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free
created: '2026-03-13'
description: Azure Maps provides geospatial APIs for maps, routing, geocoding, traffic, weather, and spatial analysis. The service offers a comprehensive suite of REST APIs to embed location intelligence into applications spanning mobile, web, and IoT scenarios across multiple transport modes.
features: []
image: https://azure.microsoft.com/svghandler/azure-maps/
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Maps
skills: []
slug: microsoft-azure-maps
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Maps\ndescription: >-\n  Azure Maps provides geospatial APIs for maps, routing, geocoding, traffic,\n  weather, and spatial analysis. The service offers a comprehensive suite of\n  REST APIs to embed location intelligence into applications spanning mobile,\n  web, and IoT scenarios across multiple transport modes.\nimage: https://azure.microsoft.com/svghandler/azure-maps/\ntags:\n  - Geocoding\n  - Geospatial\n  - Location\n  - Maps\n  - Mobility\n  - Routing\n  - Traffic\n  - Weather\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/azure-maps/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Maps Search API\n    description: >-\n      Provides geocoding, reverse geocoding, address parsing, point of interest\n      search, and structured search. Returns candidate matches ranked by\n      relevance for free-form, structured, and POI queries with worldwide\n      coverage.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n\
  \    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/search\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - Address\n      - Geocoding\n      - POI\n      - Reverse Geocoding\n      - Search\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/search\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/azure-maps-authentication\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/how-to-use-search-service\n  - name: Azure Maps Route API\n    description: >-\n      Calculates routes between origin and destination, provides turn-by-turn\n      directions, supports multiple travel modes, traffic-aware routing, route\n      matrices, and route range (isochrone) calculations.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/route\n    baseURL: https://atlas.microsoft.com\n\
  \    tags:\n      - Directions\n      - Isochrone\n      - Routing\n      - Traffic-Aware\n      - Travel Modes\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/route\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/how-to-use-best-practices-for-routing\n  - name: Azure Maps Render API\n    description: >-\n      Returns map tiles, static images, and vector tiles in multiple styles\n      including satellite, road, and hybrid. Supports raster and vector tile\n      formats, custom imagery, and traffic overlays for embedding maps into\n      applications.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/render\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - Map Tiles\n      - Raster\n      - Render\n      - Static Images\n      - Vector Tiles\n    properties:\n      - type: Documentation\n   \
  \     url: https://learn.microsoft.com/en-us/rest/api/maps/render\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/zoom-levels-and-tile-grid\n  - name: Azure Maps Traffic API\n    description: >-\n      Provides real-time and historical traffic data including traffic flow,\n      incident reports, and traffic tile imagery. Useful for routing, fleet\n      management, and applications requiring up-to-date road conditions.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/traffic\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - Flow\n      - Incidents\n      - Real-Time\n      - Traffic\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/traffic\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/traffic-coverage\n  - name: Azure Maps Weather API\n    description: >-\n\
  \      Provides current weather conditions, hourly and daily forecasts, severe\n      weather alerts, weather along a route, and historical weather. Powered by\n      AccuWeather data and global coverage.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/weather\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - Alerts\n      - Forecast\n      - Historical\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/weather\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/weather-coverage\n  - name: Azure Maps Timezone API\n    description: >-\n      Returns time zone information for a given coordinate, IANA time zone ID,\n      or Windows time zone ID. Includes current time, daylight saving offsets,\n      and time zone metadata.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n  \
  \  humanURL: https://learn.microsoft.com/en-us/rest/api/maps/timezone\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - DST\n      - IANA\n      - Time Zone\n      - UTC Offset\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/timezone\n  - name: Azure Maps Geolocation API\n    description: >-\n      Returns the ISO country code for a supplied IP address, useful for\n      content localization, regulatory compliance, and access control based on\n      user geographic location.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/geolocation\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - Country Code\n      - Geolocation\n      - IP Address\n      - Localization\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/geolocation\n  - name: Azure Maps Spatial API\n    description:\
  \ >-\n      Performs spatial computations such as distance, closest point, point in\n      polygon, geofence evaluation, and great circle distance. Enables location\n      analytics and spatial reasoning workloads.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/spatial\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - Geofencing\n      - Point in Polygon\n      - Spatial Analysis\n      - Spatial Operations\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/spatial\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/geofence-geojson\n  - name: Azure Maps Elevation API\n    description: >-\n      Returns elevation data in meters above sea level for points, polylines,\n      and bounding boxes. Useful for terrain analysis, topographic\n      visualization, and elevation profile calculations along a route.\n\
  \    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/elevation\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - DEM\n      - Elevation\n      - Terrain\n      - Topography\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/elevation\n  - name: Azure Maps Creator API\n    description: >-\n      Indoor maps service for creating, managing, and rendering custom indoor\n      maps. Supports drawing package conversion, dataset and tileset\n      management, feature state, and wayfinding for indoor environments.\n    image: https://azure.microsoft.com/svghandler/azure-maps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/maps/creator\n    baseURL: https://atlas.microsoft.com\n    tags:\n      - Creator\n      - Indoor Maps\n      - Tileset\n      - Wayfinding\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/maps/creator\n\
  \      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-maps/creator-indoor-maps\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/azure-maps/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/azure-maps/quick-demo-map-app\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/azure-maps/azure-maps-authentication\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/azure-maps/about-azure-maps\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/azure-maps/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/tag/azure-maps/\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/azure/azure-maps/release-notes-map-control\n  - type:\
  \ Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/azure-maps\n  - type: Login\n    url: https://portal.azure.com\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-maps/refs/heads/main/apis.yml
tags:
- Geocoding
- Geospatial
- Location
- Maps
- Mobility
- Routing
- Traffic
- Weather
url: https://azure.microsoft.com/en-us/services/azure-maps/
use_cases: []
---
