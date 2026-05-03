---
api_count: 1
api_specs:
- filename: openapi.yml
  format: yaml
  label: Weather.gov API Web Service
  slug: weather-gov-api-web-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weather-gov/refs/heads/main/openapi/openapi.yml
apis:
- description: The National Weather Service API provides access to real-time weather data including forecasts, alerts, observations, radar, aviation weather, and zone information for the United States. The API is fr
  name: Weather.gov API Web Service
  slug: weather-gov-api-web-service
capabilities:
- description: Unified weather monitoring workflow combining alerts, forecasts, observations, radar, and aviation weather. Used by emergency managers, developers, and weather enthusiasts to access NWS open data.
  name: Weather.gov Weather Monitoring
  slug: weather-monitoring
common:
- title: ''
  type: Documentation
  url: https://www.weather.gov/documentation/services-web-api
- title: ''
  type: GitHubRepository
  url: https://github.com/weather-gov/api
- title: ''
  type: APIReference
  url: https://api.weather.gov/openapi.json
- title: ''
  type: Portal
  url: https://www.weather.gov
- title: ''
  type: Contact
  url: https://www.weather.gov/contact
- title: ''
  type: Glossary
  url: https://api.weather.gov/glossary
- title: ''
  type: SpectralRules
  url: rules/weather-gov-spectral-rules.yml
- title: Weather Monitoring Capability
  type: NaftikoCapability
  url: capabilities/weather-monitoring.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/weather-gov-vocabulary.yml
created: '2024-07-02T00:00:00.000Z'
description: Weather.gov is the official website of the National Weather Service (NWS), operated by NOAA within the US Department of Commerce. The NWS provides weather, hydrologic, and climate forecasts and warnings for the United States, its territories, adjacent waters, and ocean areas. The Weather.gov API provides free, open access to forecasts, alerts, observations, radar data, aviation weather, and geographic zone information across all 50 states and territories.
features:
- description: No API key required (only a User-Agent header); completely free for any use.
  name: Free and Open
- description: 12-hour and hourly forecasts for 2.5km grid cells across the US.
  name: Forecast Gridpoints
- description: Live weather alerts and warnings including active counts by area, zone, and region.
  name: Real-Time Alerts
- description: Latest and historical observations from thousands of weather stations across the US.
  name: Observation Data
- description: Radar station metadata, alarms, queues, and wind profiler data.
  name: Radar Data
- description: SIGMETs, AIRMETs, Center Weather Advisories, and Terminal Aerodrome Forecasts for pilots.
  name: Aviation Weather
- description: All responses return GeoJSON or JSON-LD by default, suitable for mapping and linked data.
  name: GeoJSON Responses
- description: Supports GeoJSON, JSON-LD, DWML, OXML, CAP, and ATOM formats.
  name: Multiple Output Formats
image: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/api-web-service.png
integrations: []
jsonld:
- class_count: 42
  name: Weather Gov Context
  property_count: 181
  slug: weather-gov-context
layout: provider
modified: '2026-05-03'
name: Weather.gov
rules:
- name: Weather.gov API Rules
  rule_count: 24
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 13
  slug: weather-gov-spectral-rules
skills: []
slug: weather-gov
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: weather-gov\nurl: https://raw.githubusercontent.com/api-evangelist/weather-gov/refs/heads/main/apis.yml\napis:\n  - name: Weather.gov API Web Service\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.weather.gov/documentation/services-web-api\n    baseURL: https://api.weather.gov\n    properties:\n      - url: openapi/openapi.yml\n        name: Weather.gov OpenAPI\n        type: OpenAPI\n      - url: https://www.weather.gov/documentation/services-web-api\n        type: Documentation\n      - url: https://api.weather.gov/openapi.json\n        type: APIReference\n    description: >-\n      The National Weather Service API provides access to real-time weather\n      data including forecasts, alerts, observations, radar, aviation weather,\n      and zone information for the United States. The API is free, open, and\n      requires only a User-Agent header for identification.\n    aid: weather-gov:weather-gov-api-web-service\n\
  \    tags:\n      - Weather\n      - Forecasting\n      - Alerts\n      - Observations\n      - Radar\n      - United States\n      - Government\nname: Weather.gov\ntags:\n  - Weather\n  - Government\n  - United States\n  - Forecasting\n  - Alerts\n  - Open Data\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/api-web-service.png\ncommon:\n  - url: https://www.weather.gov/documentation/services-web-api\n    type: Documentation\n  - url: https://github.com/weather-gov/api\n    type: GitHubRepository\n  - url: https://api.weather.gov/openapi.json\n    type: APIReference\n  - url: https://www.weather.gov\n    type: Portal\n  - url: https://www.weather.gov/contact\n    type: Contact\n  - url: https://api.weather.gov/glossary\n    type: Glossary\n  - type: Features\n    data:\n      - name: Free and Open\n        description: >-\n          No API key required (only a User-Agent header); completely free for\n          any use.\n      - name: Forecast Gridpoints\n       \
  \ description: >-\n          12-hour and hourly forecasts for 2.5km grid cells across the US.\n      - name: Real-Time Alerts\n        description: >-\n          Live weather alerts and warnings including active counts by area,\n          zone, and region.\n      - name: Observation Data\n        description: >-\n          Latest and historical observations from thousands of weather stations\n          across the US.\n      - name: Radar Data\n        description: >-\n          Radar station metadata, alarms, queues, and wind profiler data.\n      - name: Aviation Weather\n        description: >-\n          SIGMETs, AIRMETs, Center Weather Advisories, and Terminal Aerodrome\n          Forecasts for pilots.\n      - name: GeoJSON Responses\n        description: >-\n          All responses return GeoJSON or JSON-LD by default, suitable for\n          mapping and linked data.\n      - name: Multiple Output Formats\n        description: >-\n          Supports GeoJSON, JSON-LD, DWML, OXML,\
  \ CAP, and ATOM formats.\n  - type: UseCases\n    data:\n      - name: Emergency Management\n        description: >-\n          Monitor active weather alerts and warnings for emergency response and\n          public safety decisions.\n      - name: Application Development\n        description: >-\n          Integrate NWS weather data into mobile apps, websites, and IoT\n          devices.\n      - name: Aviation Planning\n        description: >-\n          Access SIGMETs, AIRMETs, and TAFs for flight planning and aviation\n          safety.\n      - name: Agricultural Monitoring\n        description: >-\n          Use zone forecasts and observation data for crop management and\n          agricultural planning.\n      - name: Research and Education\n        description: >-\n          Access historical observation data and forecast products for climate\n          research and educational purposes.\n  - type: SpectralRules\n    url: rules/weather-gov-spectral-rules.yml\n  - type: NaftikoCapability\n\
  \    url: capabilities/weather-monitoring.yaml\n    title: Weather Monitoring Capability\n  - type: Vocabulary\n    url: vocabulary/weather-gov-vocabulary.yml\ncreated: '2024-07-02T00:00:00.000Z'\nmodified: '2026-05-03'\ndescription: >-\n  Weather.gov is the official website of the National Weather Service (NWS),\n  operated by NOAA within the US Department of Commerce. The NWS provides\n  weather, hydrologic, and climate forecasts and warnings for the United States,\n  its territories, adjacent waters, and ocean areas. The Weather.gov API\n  provides free, open access to forecasts, alerts, observations, radar data,\n  aviation weather, and geographic zone information across all 50 states and\n  territories.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ntype: Index\nposition: Consumer\naccess: 3rd-Party\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/weather-gov/refs/heads/main/apis.yml
tags:
- Weather
- Government
- United States
- Forecasting
- Alerts
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/weather-gov/refs/heads/main/apis.yml
use_cases:
- description: Monitor active weather alerts and warnings for emergency response and public safety decisions.
  name: Emergency Management
- description: Integrate NWS weather data into mobile apps, websites, and IoT devices.
  name: Application Development
- description: Access SIGMETs, AIRMETs, and TAFs for flight planning and aviation safety.
  name: Aviation Planning
- description: Use zone forecasts and observation data for crop management and agricultural planning.
  name: Agricultural Monitoring
- description: Access historical observation data and forecast products for climate research and educational purposes.
  name: Research and Education
---
