---
api_count: 1
api_specs:
- filename: stormglass-openapi.yml
  format: yaml
  label: Stormglass API
  slug: stormglass-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/openapi/stormglass-openapi.yml
apis:
- description: The Stormglass API provides global weather, marine, tidal, astronomical, solar, biological, and elevation data for any coordinate on Earth. It aggregates data from multiple meteorological and oceanogr
  name: Stormglass API
  slug: stormglass-api
capabilities:
- description: Unified capability for accessing global marine and weather data from Stormglass. Combines weather forecasts, marine conditions, tidal data, astronomical events, solar radiation, biological oceanograph
  name: Stormglass Marine and Weather Intelligence
  slug: marine-weather
common:
- title: ''
  type: Portal
  url: https://stormglass.io/
- title: ''
  type: Documentation
  url: https://docs.stormglass.io/
- title: ''
  type: Sign Up
  url: https://stormglass.io/register
- title: ''
  type: Pricing
  url: https://stormglass.io/pricing
- title: ''
  type: Website
  url: https://stormglass.io/
- title: ''
  type: Blog
  url: https://stormglass.io/blog
- title: ''
  type: TermsOfService
  url: https://stormglass.io/terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://stormglass.io/privacy-policy/
- title: ''
  type: GitHubOrg
  url: https://github.com/stormglass
created: '2025-05-02'
description: Stormglass provides a global marine and weather API delivering high-resolution forecasts, historical data, and environmental measurements for any coordinate on Earth. The platform aggregates data from multiple authoritative sources including NOAA, ECMWF, DWD, and others to provide weather point forecasts, marine data, tidal information, solar and astronomical data, biological oceanographic data, and elevation/bathymetry data. Used widely for maritime navigation, renewable energy forecasting, outdoor activity planning, and environmental monitoring applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 16
  name: Stormglass Context
  property_count: 19
  slug: stormglass-context
layout: provider
modified: '2026-05-02'
name: Stormglass
rules:
- name: Stormglass API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: stormglass-rules
skills: []
slug: stormglass
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stormglass\nname: Stormglass\ndescription: >-\n  Stormglass provides a global marine and weather API delivering high-resolution\n  forecasts, historical data, and environmental measurements for any coordinate\n  on Earth. The platform aggregates data from multiple authoritative sources\n  including NOAA, ECMWF, DWD, and others to provide weather point forecasts,\n  marine data, tidal information, solar and astronomical data, biological\n  oceanographic data, and elevation/bathymetry data. Used widely for maritime\n  navigation, renewable energy forecasting, outdoor activity planning, and\n  environmental monitoring applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Astronomy\n  - Bio\n  - Climate\n  - Elevation\n  - Forecasting\n  - Marine\n  - Ocean\n  - Solar\n  - Tides\n  - Weather\n  - Wind\ncreated: '2025-05-02'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: stormglass:stormglass-api\n    name: Stormglass API\n    description: >-\n      The Stormglass API provides global weather, marine, tidal, astronomical,\n      solar, biological, and elevation data for any coordinate on Earth. It\n      aggregates data from multiple meteorological and oceanographic sources\n      into a single REST API. All endpoints return JSON and use API key\n      authentication via the Authorization header.\n    humanURL: https://stormglass.io/\n    baseURL: https://api.stormglass.io/v2\n    tags:\n      - Astronomy\n      - Bio\n      - Elevation\n      - Forecasting\n      - Marine\n      - Solar\n      - Tides\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://docs.stormglass.io/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/openapi/stormglass-openapi.yml\n      - type: Pricing\n        url: https://stormglass.io/pricing\n\
  \      - type: Sign Up\n        url: https://stormglass.io/register\n      - type: Website\n        url: https://stormglass.io/\n      - type: Blog\n        url: https://stormglass.io/blog\n      - type: TermsOfService\n        url: https://stormglass.io/terms-and-conditions/\n      - type: PrivacyPolicy\n        url: https://stormglass.io/privacy-policy/\ncommon:\n  - type: Portal\n    url: https://stormglass.io/\n  - type: Documentation\n    url: https://docs.stormglass.io/\n  - type: Sign Up\n    url: https://stormglass.io/register\n  - type: Pricing\n    url: https://stormglass.io/pricing\n  - type: Website\n    url: https://stormglass.io/\n  - type: Blog\n    url: https://stormglass.io/blog\n  - type: TermsOfService\n    url: https://stormglass.io/terms-and-conditions/\n  - type: PrivacyPolicy\n    url: https://stormglass.io/privacy-policy/\n  - type: GitHubOrg\n    url: https://github.com/stormglass\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/apis.yml
tags:
- Astronomy
- Bio
- Climate
- Elevation
- Forecasting
- Marine
- Ocean
- Solar
- Tides
- Weather
- Wind
url: https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/apis.yml
use_cases: []
---
