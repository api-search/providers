---
api_count: 10
apis:
- description: Mapbox Tiling Service (MTS) is a tool for creating vector tilesets. With MTS, you use sets of configuration options (tileset recipes) to transform your geospatial data into vector tiles. The resulting
  name: Mapbox Tiling Service
  slug: mapbox-tiling-service
- description: The Mapbox Vector Tiles API serves vector tiles from Mapbox-hosted vector tilesets.
  name: Mapbox Vector Tiles API
  slug: vector-tiles-api
- description: The Mapbox Raster Tiles API serves raster tiles generated from satellite imagery tilesets and tilesets generated from raster data uploaded to Mapbox.com.
  name: Mapbox Raster Tiles API
  slug: mapbox-raster-tiles-api
- description: The Mapbox Static Images API serves standalone, static map images generated from Mapbox Studio styles. These images can be displayed on web and mobile devices without the aid of a mapping library or A
  name: Mapbox Static Images API
  slug: mapbox-static-images-api
- description: The Mapbox Static Tiles API serves raster tiles generated from Mapbox Studio styles. Raster tiles can be used in traditional web mapping libraries like Mapbox.js, Leaflet, OpenLayers, and others to cr
  name: Mapbox Static Tiles API
  slug: mapbox-static-tiles-api
- description: The Mapbox Styles API lets you read and change map styles, fonts, and images. This API is the basis for Mapbox Studio.
  name: Mapbox Styles API
  slug: mapbox-styles-api
- description: The Mapbox Tilequery API allows you to retrieve data about specific features from a vector tileset, based on a given latitude and longitude. The Tilequery API makes it possible to query for features w
  name: Mapbox Tilequery API
  slug: mapbox-tilequery-api
- description: The Mapbox Uploads API transforms geographic data into tilesets that can be used with maps and geographic applications. Given a wide variety of geospatial formats, it normalizes projections and genera
  name: Mapbox Uploads API
  slug: mapbox-uploads-api
- description: The Mapbox Datasets API supports reading, creating, updating, and removing features from a dataset. Datasets contain one or more collections of GeoJSON features.
  name: Mapbox Datasets API
  slug: mapbox-datasets-api
- description: 'The Mapbox Fonts API accepts fonts as raw binary data, allows those fonts to be deleted, and generates encoded letters for map renderers. Two types of fonts are supported: TrueType fonts (.ttf) and Op'
  name: Mapbox Fonts API
  slug: mapbox-fonts-api
common:
- title: ''
  type: Support
  url: https://docs.mapbox.com/help/
- title: ''
  type: SDK
  url: https://docs.mapbox.com/api/overview/#sdk-and-library-support
- title: ''
  type: Authentication
  url: https://docs.mapbox.com/api/overview/#access-tokens-and-token-scopes
- title: ''
  type: Versioning
  url: https://docs.mapbox.com/api/overview/#api-versioning
- title: ''
  type: Rate Limits
  url: https://docs.mapbox.com/api/overview/#rate-limits
- title: ''
  type: CORS
  url: https://docs.mapbox.com/api/overview/#https-and-cors
- title: ''
  type: Pagination
  url: https://docs.mapbox.com/api/overview/#pagination
- title: ''
  type: Login
  url: https://account.mapbox.com/auth/signin/
- title: ''
  type: Sign Up
  url: https://account.mapbox.com/auth/signup/
- title: ''
  type: Terms of Service
  url: https://www.mapbox.com/tos/
- title: ''
  type: Privacy
  url: https://www.mapbox.com/privacy/
- title: ''
  type: Security
  url: https://www.mapbox.com/platform/security/
- title: ''
  type: Cheatsheet
  url: https://labs.mapbox.com/developer-cheatsheet/
- title: ''
  type: Getting Started
  url: https://docs.mapbox.com/help/getting-started
- title: ''
  type: Tutorials
  url: https://docs.mapbox.com/help/tutorials
- title: ''
  type: Videos
  url: https://docs.mapbox.com/help/how-to-videos
- title: ''
  type: Troubleshooting
  url: https://docs.mapbox.com/help/troubleshooting
- title: ''
  type: Glossary
  url: https://docs.mapbox.com/help/glossary
- title: ''
  type: Website
  url: https://www.mapbox.com/
created: '2023-11-22'
description: Mapbox is a leading mapping and location data platform that provides tools and services to help developers and businesses create custom maps, visualize geospatial data, and build location-aware applications. Their platform offers a wide range of mapping technologies, from interactive maps and map design tools to geocoding and routing services.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Mapbox
skills: []
slug: mapbox
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: mapbox\nname: Mapbox\ndescription: >-\n  Mapbox is a leading mapping and location data platform that provides tools and services\n  to help developers and businesses create custom maps, visualize geospatial data,\n  and build location-aware applications. Their platform offers a wide range of mapping\n  technologies, from interactive maps and map design tools to geocoding and routing\n  services.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consuming\ntags:\n  - Mapping\n  - Maps\n  - Geospatial\n  - Location\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/mapbox/refs/heads/main/apis.yml\ncreated: '2023-11-22'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: mapbox:mapbox-tiling-service\n    name: Mapbox Tiling Service\n    description: >-\n      Mapbox Tiling Service (MTS) is a tool for creating vector tilesets. With MTS,\n      you use sets of configuration\
  \ options (tileset recipes) to transform your geospatial\n      data into vector tiles. The resulting tiles are hosted on Mapbox servers for\n      use in your applications.\n    humanURL: https://docs.mapbox.com/api/maps/mapbox-tiling-service/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Tiles\n      - Vector Tiles\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/mapbox-tiling-service/\n  - aid: mapbox:vector-tiles-api\n    name: Mapbox Vector Tiles API\n    description: >-\n      The Mapbox Vector Tiles API serves vector tiles from Mapbox-hosted vector tilesets.\n    humanURL: https://docs.mapbox.com/api/maps/vector-tiles/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Tiles\n      - Vector Tiles\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/vector-tiles/\n  - aid: mapbox:mapbox-raster-tiles-api\n    name: Mapbox Raster Tiles API\n    description:\
  \ >-\n      The Mapbox Raster Tiles API serves raster tiles generated from satellite imagery\n      tilesets and tilesets generated from raster data uploaded to Mapbox.com.\n    humanURL: https://docs.mapbox.com/api/maps/raster-tiles/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Tiles\n      - Raster Tiles\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/raster-tiles/\n  - aid: mapbox:mapbox-static-images-api\n    name: Mapbox Static Images API\n    description: >-\n      The Mapbox Static Images API serves standalone, static map images generated\n      from Mapbox Studio styles. These images can be displayed on web and mobile devices\n      without the aid of a mapping library or API.\n    humanURL: https://docs.mapbox.com/api/maps/static-images/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Static Images\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/static-images/\n\
  \  - aid: mapbox:mapbox-static-tiles-api\n    name: Mapbox Static Tiles API\n    description: >-\n      The Mapbox Static Tiles API serves raster tiles generated from Mapbox Studio\n      styles. Raster tiles can be used in traditional web mapping libraries like Mapbox.js,\n      Leaflet, OpenLayers, and others to create interactive slippy maps.\n    humanURL: https://docs.mapbox.com/api/maps/static-tiles/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Tiles\n      - Static Tiles\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/static-tiles/\n  - aid: mapbox:mapbox-styles-api\n    name: Mapbox Styles API\n    description: >-\n      The Mapbox Styles API lets you read and change map styles, fonts, and images.\n      This API is the basis for Mapbox Studio.\n    humanURL: https://docs.mapbox.com/api/maps/styles/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Styles\n    properties:\n      -\
  \ type: Documentation\n        url: https://docs.mapbox.com/api/maps/styles/\n  - aid: mapbox:mapbox-tilequery-api\n    name: Mapbox Tilequery API\n    description: >-\n      The Mapbox Tilequery API allows you to retrieve data about specific features\n      from a vector tileset, based on a given latitude and longitude. The Tilequery\n      API makes it possible to query for features within a radius, do point-in-polygon\n      queries, query for features in multiple composite layers, and augment data from\n      the Mapbox Geocoding API with custom data.\n    humanURL: https://docs.mapbox.com/api/maps/tilequery/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Tile Query\n      - Geospatial\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/tilequery/\n  - aid: mapbox:mapbox-uploads-api\n    name: Mapbox Uploads API\n    description: >-\n      The Mapbox Uploads API transforms geographic data into tilesets that can be\n\
  \      used with maps and geographic applications. Given a wide variety of geospatial\n      formats, it normalizes projections and generates tiles at multiple zoom levels\n      to make data viewable on the web.\n    humanURL: https://docs.mapbox.com/api/maps/uploads/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Uploads\n      - Geospatial\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/uploads/\n  - aid: mapbox:mapbox-datasets-api\n    name: Mapbox Datasets API\n    description: >-\n      The Mapbox Datasets API supports reading, creating, updating, and removing features\n      from a dataset. Datasets contain one or more collections of GeoJSON features.\n    humanURL: https://docs.mapbox.com/api/maps/datasets/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Datasets\n      - GeoJSON\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/datasets/\n\
  \  - aid: mapbox:mapbox-fonts-api\n    name: Mapbox Fonts API\n    description: >-\n      The Mapbox Fonts API accepts fonts as raw binary data, allows those fonts to\n      be deleted, and generates encoded letters for map renderers. Two types of fonts\n      are supported: TrueType fonts (.ttf) and OpenType fonts (.otf).\n    humanURL: https://docs.mapbox.com/api/maps/fonts/\n    baseURL: https://api.mapbox.com\n    tags:\n      - Mapping\n      - Fonts\n    properties:\n      - type: Documentation\n        url: https://docs.mapbox.com/api/maps/fonts/\ncommon:\n  - type: Support\n    url: https://docs.mapbox.com/help/\n  - type: SDK\n    url: https://docs.mapbox.com/api/overview/#sdk-and-library-support\n  - type: Authentication\n    url: https://docs.mapbox.com/api/overview/#access-tokens-and-token-scopes\n  - type: Versioning\n    url: https://docs.mapbox.com/api/overview/#api-versioning\n  - type: Rate Limits\n    url: https://docs.mapbox.com/api/overview/#rate-limits\n  - type: CORS\n\
  \    url: https://docs.mapbox.com/api/overview/#https-and-cors\n  - type: Pagination\n    url: https://docs.mapbox.com/api/overview/#pagination\n  - type: Login\n    url: https://account.mapbox.com/auth/signin/\n  - type: Sign Up\n    url: https://account.mapbox.com/auth/signup/\n  - type: Terms of Service\n    url: https://www.mapbox.com/tos/\n  - type: Privacy\n    url: https://www.mapbox.com/privacy/\n  - type: Security\n    url: https://www.mapbox.com/platform/security/\n  - type: Cheatsheet\n    url: https://labs.mapbox.com/developer-cheatsheet/\n  - type: Getting Started\n    url: https://docs.mapbox.com/help/getting-started\n  - type: Tutorials\n    url: https://docs.mapbox.com/help/tutorials\n  - type: Videos\n    url: https://docs.mapbox.com/help/how-to-videos\n  - type: Troubleshooting\n    url: https://docs.mapbox.com/help/troubleshooting\n  - type: Glossary\n    url: https://docs.mapbox.com/help/glossary\n  - type: Website\n    url: https://www.mapbox.com/\nmaintainers:\n \
  \ - FN: API Evangelist\n    url: http://apievangelist.com\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mapbox/refs/heads/main/apis.yml
tags:
- Mapping
- Maps
- Geospatial
- Location
url: https://raw.githubusercontent.com/api-evangelist/mapbox/refs/heads/main/apis.yml
use_cases: []
---
