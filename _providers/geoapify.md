---
api_count: 10
api_specs:
- filename: geoapify-forward-geocoding-api-openapi.yml
  format: yaml
  label: Forward Geocoding API
  slug: forward-geocoding
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/geoapify/refs/heads/main/openapi/geoapify-forward-geocoding-api-openapi.yml
apis:
- description: Retrieve map tiles for various types and styles.
  name: Map Tiles API
  slug: map-tiles
- description: Generate static map images for embedding in applications.
  name: Static Maps API
  slug: static-maps
- description: Convert addresses into geographic coordinates.
  name: Forward Geocoding API
  slug: forward-geocoding
- description: Convert geographic coordinates into addresses.
  name: Reverse Geocoding API
  slug: reverse-geocoding
- description: Address autocomplete suggestions for search fields.
  name: Address Autocomplete API
  slug: address-autocomplete
- description: Identify the location of an IP address.
  name: IP Geolocation API
  slug: ip-geolocation
- description: Provides routing directions between multiple points.
  name: Routing API
  slug: routing
- description: Discover places based on various categories and parameters.
  name: Places API
  slug: places
- description: Retrieve boundary data for administrative regions.
  name: Boundaries API
  slug: boundaries
- description: Generate isolines to represent reachable areas.
  name: Isoline API
  slug: isoline
common:
- title: ''
  type: Website
  url: https://www.geoapify.com/
- title: ''
  type: Documentation
  url: https://apidocs.geoapify.com/
- title: ''
  type: Sign Up
  url: https://myprojects.geoapify.com/register
- title: ''
  type: Terms of Service
  url: https://www.geoapify.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.geoapify.com/privacy
created: '2024-01-01'
description: Geoapify Location Platform APIs for location-based services and mapping solutions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Geoapify
skills: []
slug: geoapify
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: geoapify\nname: Geoapify\ndescription: >-\n  Geoapify Location Platform APIs for location-based services and mapping\n  solutions.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nposition: Consumer\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/geoapify/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\ntags:\n  - Geocoding\n  - Geospatial\n  - Location\n  - Maps\napis:\n  - aid: geoapify:map-tiles\n    name: Map Tiles API\n    description: Retrieve map tiles for various types and styles.\n    humanURL: https://apidocs.geoapify.com/maps/map-tiles\n    baseURL: https://maps.geoapify.com/maptiles\n    tags:\n      - Maps\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/maps/map-tiles\n  - aid: geoapify:static-maps\n    name: Static Maps API\n    description: Generate static map images for embedding in\
  \ applications.\n    humanURL: https://apidocs.geoapify.com/maps/static-maps-api\n    baseURL: https://maps.geoapify.com/staticmap\n    tags:\n      - Maps\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/maps/static-maps-api\n  - aid: geoapify:forward-geocoding\n    name: Forward Geocoding API\n    description: Convert addresses into geographic coordinates.\n    humanURL: https://apidocs.geoapify.com/addresses-location/forward-geocoding-api\n    baseURL: https://api.geoapify.com/geocode/search\n    tags:\n      - Geocoding\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/addresses-location/forward-geocoding-api\n      - type: OpenAPI\n        url: openapi/geoapify-forward-geocoding-api-openapi.yml\n  - aid: geoapify:reverse-geocoding\n    name: Reverse Geocoding API\n    description: Convert geographic coordinates into addresses.\n    humanURL: https://apidocs.geoapify.com/addresses-location/reverse-geocoding-api\n\
  \    baseURL: https://api.geoapify.com/geocode/reverse\n    tags:\n      - Geocoding\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/addresses-location/reverse-geocoding-api\n  - aid: geoapify:address-autocomplete\n    name: Address Autocomplete API\n    description: Address autocomplete suggestions for search fields.\n    humanURL: https://apidocs.geoapify.com/addresses-location/address-autocomplete\n    baseURL: https://api.geoapify.com/geocode/autocomplete\n    tags:\n      - Geocoding\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/addresses-location/address-autocomplete\n  - aid: geoapify:ip-geolocation\n    name: IP Geolocation API\n    description: Identify the location of an IP address.\n    humanURL: https://apidocs.geoapify.com/addresses-location/ip-geolocation-api\n    baseURL: https://api.geoapify.com/geocode/ip\n    tags:\n      - Geolocation\n    properties:\n      - type: Documentation\n  \
  \      url: https://apidocs.geoapify.com/addresses-location/ip-geolocation-api\n  - aid: geoapify:routing\n    name: Routing API\n    description: Provides routing directions between multiple points.\n    humanURL: https://apidocs.geoapify.com/routes-optimization/routing-api\n    baseURL: https://api.geoapify.com/routing\n    tags:\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/routes-optimization/routing-api\n  - aid: geoapify:places\n    name: Places API\n    description: Discover places based on various categories and parameters.\n    humanURL: https://apidocs.geoapify.com/places-details/places-api\n    baseURL: https://api.geoapify.com/places\n    tags:\n      - Places\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/places-details/places-api\n  - aid: geoapify:boundaries\n    name: Boundaries API\n    description: Retrieve boundary data for administrative regions.\n    humanURL: https://apidocs.geoapify.com/boundaries/about-boundaries-api\n\
  \    baseURL: https://api.geoapify.com/boundaries\n    tags:\n      - Boundaries\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/boundaries/about-boundaries-api\n  - aid: geoapify:isoline\n    name: Isoline API\n    description: Generate isolines to represent reachable areas.\n    humanURL: https://apidocs.geoapify.com/reachability/isolines\n    baseURL: https://api.geoapify.com/isolines\n    tags:\n      - Reachability\n    properties:\n      - type: Documentation\n        url: https://apidocs.geoapify.com/reachability/isolines\ncommon:\n  - type: Website\n    url: https://www.geoapify.com/\n  - type: Documentation\n    url: https://apidocs.geoapify.com/\n  - type: Sign Up\n    url: https://myprojects.geoapify.com/register\n  - type: Terms of Service\n    url: https://www.geoapify.com/terms\n  - type: Privacy Policy\n    url: https://www.geoapify.com/privacy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/geoapify/refs/heads/main/apis.yml
tags:
- Geocoding
- Geospatial
- Location
- Maps
url: https://raw.githubusercontent.com/api-evangelist/geoapify/refs/heads/main/apis.yml
use_cases: []
---
