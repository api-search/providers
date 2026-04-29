---
api_count: 2
apis:
- description: Real-time and forecast air quality data from 11,000+ monitoring stations globally. Returns AQI measurements for PM2.5, PM10, NO2, CO, SO2, and ozone pollutants by city, station, geographic coordinates
  name: AQICN Real-Time Air Quality API
  slug: air-quality-programmatic-apis
- description: JSON API returning real-time AQI station data by city name, station name, geographic coordinates, or IP geolocation. Includes pollutant breakdowns (PM2.5, PM10, NO2, CO, SO2, O3), weather data, and mu
  name: AQICN JSON Air Quality API
  slug: aqicn-json-api
capabilities:
- description: Unified workflow for querying real-time air quality data, monitoring station health, and spatial air quality analysis. Used by environmental monitoring applications and public health systems.
  name: Air Quality Monitoring Workflow
  slug: air-quality-monitoring
common:
- title: ''
  type: FAQ
  url: https://aqicn.org/faq/
- title: ''
  type: Authentication
  url: https://aqicn.org/data-platform/token/
- title: ''
  type: Portal
  url: https://aqicn.org/map/
- title: ''
  type: Portal
  url: https://aqicn.org/data-platform/
- title: ''
  type: TermsOfService
  url: https://aqicn.org/api/tos/
- title: ''
  type: SpectralRules
  url: rules/aqicn-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/air-quality-monitoring.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/aqicn-vocabulary.yaml
created: '2024-11-07'
description: Air Quality Programmatic APIs provide real-time and forecast air quality data from 11,000+ monitoring stations in 1,000+ cities worldwide. APIs deliver Air Quality Index (AQI) measurements for PM2.5, PM10, NO2, CO, SO2, and ozone pollutants. Provided by AQICN (World Air Quality Index project) in partnership with the US EPA and global environmental agencies. Data is available via JSON API and map tile API for visualization.
features:
- description: Live air quality index readings from 11,000+ monitoring stations updated continuously.
  name: Real-Time AQI Data
- description: Data from 1,000+ cities worldwide including US EPA, China MEP, Europe EEA, and other monitoring networks.
  name: Global Coverage
- description: Pollutant-specific AQI for PM2.5, PM10, nitrogen dioxide, carbon monoxide, sulfur dioxide, and ozone.
  name: Multi-Pollutant Data
- description: 3-8 day air quality forecasts for major monitoring stations.
  name: Air Quality Forecasts
- description: Find nearest stations by latitude/longitude, city name, or IP-based geolocation.
  name: Geolocation Queries
- description: Raster map tiles for overlaying real-time AQI data on web maps (Leaflet, Google Maps, etc.).
  name: Map Tile API
- description: Search and discover monitoring stations by name or location within a geographic boundary.
  name: Station Search
- description: Current weather conditions co-located with air quality measurements.
  name: Weather Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate AQI map tiles with Leaflet.js for interactive air quality maps.
  name: Leaflet Maps
- description: Overlay AQI data on Google Maps using the tile API.
  name: Google Maps
- description: Data aggregated from US EPA AirNow monitoring network.
  name: US EPA AirNow
- description: Complementary open air quality data platform with API access.
  name: OpenAQ
jsonld:
- class_count: 11
  name: Aqicn Context
  property_count: 24
  slug: aqicn-context
layout: provider
modified: '2026-04-19'
name: Air Quality Programmatic APIs
rules:
- name: Air Quality Programmatic APIs API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: aqicn-spectral-rules
skills: []
slug: air-quality-programmatic-apis
solutions: []
source_yaml: "aid: air-quality-programmatic-apis\nurl: >-\n  https://raw.githubusercontent.com/api-search/air-quality-programmatic-apis/refs/heads/main/apis.yml\napis:\n- aid: air-quality-programmatic-apis:air-quality-programmatic-apis\n  name: AQICN Real-Time Air Quality API\n  tags:\n  - Air Quality\n  - AQI\n  - PM2.5\n  - EPA\n  - Environment\n  - Public Health\n  - Real-Time\n  - Open Data\n  humanURL: https://aqicn.org/api/\n  properties:\n  - url: https://aqicn.org/api/\n    type: Documentation\n  - url: https://aqicn.org/json-api/doc/\n    type: APIReference\n    title: JSON API Reference\n  - url: openapi/air-quality-programmatic-apis-openapi.yml\n    type: OpenAPI\n    title: Map Tile API\n  - url: https://aqicn.org/data-platform/token/\n    type: Authentication\n    title: API Token Request\n  description: >-\n    Real-time and forecast air quality data from 11,000+ monitoring stations globally. Returns AQI measurements for PM2.5, PM10, NO2, CO, SO2, and ozone pollutants by city,\
  \ station, geographic coordinates,\n    or IP geolocation. Includes weather data and 3-8 day air quality forecasts.\n- aid: air-quality-programmatic-apis:aqicn-json-api\n  name: AQICN JSON Air Quality API\n  tags:\n  - Air Quality\n  - AQI\n  - PM2.5\n  - JSON\n  - Real-Time\n  - Forecast\n  humanURL: https://aqicn.org/json-api/doc/\n  description: JSON API returning real-time AQI station data by city name, station name, geographic coordinates, or IP geolocation. Includes pollutant breakdowns (PM2.5, PM10, NO2, CO, SO2, O3), \n    weather data, and multi-day forecasts.\n  properties:\n  - url: https://aqicn.org/json-api/doc/\n    type: Documentation\n  - url: https://aqicn.org/json-api/doc/\n    type: APIReference\n  - url: openapi/aqicn-json-api-openapi.yaml\n    type: OpenAPI\nname: Air Quality Programmatic APIs\ntags:\n- Air Quality\n- Environment\n- EPA\n- Open Data\n- Public Health\n- IoT\n- Government Data\n- Real-Time Data\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncommon:\n- name: AQICN FAQ\n  url: https://aqicn.org/faq/\n  type: FAQ\n  description: Frequently asked questions about AQICN air quality data and APIs.\n- name: AQICN API Token\n  url: https://aqicn.org/data-platform/token/\n  type: Authentication\n  description: Request an API access token for AQICN programmatic APIs.\n- name: AQICN Map\n  url: https://aqicn.org/map/\n  type: Portal\n  description: World air quality index map powered by the AQICN API.\n- name: AQICN Data Platform\n  url: https://aqicn.org/data-platform/\n  type: Portal\n  description: AQICN data platform for historical downloads and enterprise access.\n- name: AQICN Terms of Use\n  url: https://aqicn.org/api/tos/\n  type: TermsOfService\n  description: Terms of service for AQICN API usage (non-commercial free use).\n- type: Features\n  data:\n  - name: Real-Time AQI Data\n    description: Live air quality index readings from 11,000+ monitoring stations updated continuously.\n  - name: Global Coverage\n\
  \    description: Data from 1,000+ cities worldwide including US EPA, China MEP, Europe EEA, and other monitoring networks.\n  - name: Multi-Pollutant Data\n    description: Pollutant-specific AQI for PM2.5, PM10, nitrogen dioxide, carbon monoxide, sulfur dioxide, and ozone.\n  - name: Air Quality Forecasts\n    description: 3-8 day air quality forecasts for major monitoring stations.\n  - name: Geolocation Queries\n    description: Find nearest stations by latitude/longitude, city name, or IP-based geolocation.\n  - name: Map Tile API\n    description: Raster map tiles for overlaying real-time AQI data on web maps (Leaflet, Google Maps, etc.).\n  - name: Station Search\n    description: Search and discover monitoring stations by name or location within a geographic boundary.\n  - name: Weather Data\n    description: Current weather conditions co-located with air quality measurements.\n- type: UseCases\n  data:\n  - name: Air Quality Mobile Apps\n    description: Build apps that show users\
  \ real-time air quality for their location with health recommendations.\n  - name: Environmental Monitoring Dashboards\n    description: Create web dashboards visualizing air quality trends across cities and regions.\n  - name: Public Health Research\n    description: Access historical and real-time air quality data for epidemiological and public health research.\n  - name: Smart City Integration\n    description: Integrate air quality data into smart city platforms and IoT systems for environmental management.\n  - name: Outdoor Activity Planning\n    description: Provide air quality-based recommendations for outdoor activities in fitness and weather apps.\n- type: Integrations\n  data:\n  - name: Leaflet Maps\n    description: Integrate AQI map tiles with Leaflet.js for interactive air quality maps.\n  - name: Google Maps\n    description: Overlay AQI data on Google Maps using the tile API.\n  - name: US EPA AirNow\n    description: Data aggregated from US EPA AirNow monitoring network.\n\
  \  - name: OpenAQ\n    description: Complementary open air quality data platform with API access.\n- name: AQICN Spectral Rules\n  url: rules/aqicn-spectral-rules.yml\n  type: SpectralRules\n  description: Spectral rules for AQICN API conventions.\n- name: Air Quality Monitoring Capability\n  url: capabilities/air-quality-monitoring.yaml\n  type: NaftikoCapability\n  description: Naftiko workflow for air quality monitoring.\n- name: AQICN Vocabulary\n  url: vocabulary/aqicn-vocabulary.yaml\n  type: Vocabulary\n  description: Taxonomy for AQICN air quality APIs.\ncreated: '2024-11-07'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  Air Quality Programmatic APIs provide real-time and forecast air quality data from 11,000+ monitoring stations in 1,000+ cities worldwide. APIs deliver Air Quality Index (AQI) measurements for PM2.5,\n  PM10, NO2, CO, SO2, and ozone pollutants. Provided by AQICN (World Air Quality Index project) in partnership with the US EPA and global environmental\
  \ agencies. Data is available via JSON API and map tile\n  API for visualization.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/air-quality-programmatic-apis/refs/heads/main/apis.yml
tags:
- Air Quality
- Environment
- EPA
- Open Data
- Public Health
- IoT
- Government Data
- Real-Time Data
url: https://raw.githubusercontent.com/api-search/air-quality-programmatic-apis/refs/heads/main/apis.yml
use_cases:
- description: Build apps that show users real-time air quality for their location with health recommendations.
  name: Air Quality Mobile Apps
- description: Create web dashboards visualizing air quality trends across cities and regions.
  name: Environmental Monitoring Dashboards
- description: Access historical and real-time air quality data for epidemiological and public health research.
  name: Public Health Research
- description: Integrate air quality data into smart city platforms and IoT systems for environmental management.
  name: Smart City Integration
- description: Provide air quality-based recommendations for outdoor activities in fitness and weather apps.
  name: Outdoor Activity Planning
---
