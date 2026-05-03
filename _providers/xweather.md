---
api_count: 1
api_specs:
- filename: xweather-weather-api-openapi.yml
  format: yaml
  label: Xweather Weather API
  slug: xweather
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/openapi/xweather-weather-api-openapi.yml
apis:
- description: The Xweather Weather API provides real-time and historical weather data including current conditions, forecasts, severe weather alerts, lightning data, air quality, maritime weather, wildfire data, an
  name: Xweather Weather API
  slug: xweather
capabilities:
- description: Drive automated stop-work and all-clear decisions for outdoor operations using Xweather lightning strike events and lightning threat nowcasts. Designed for a Safety Officer responsible for outdoor wor
  name: Lightning Safety Automation
  slug: lightning-safety
- description: Continuously monitor a portfolio of operational sites for weather risk by combining Xweather conditions, forecasts, and severe-weather alerts. Designed for an Operations Manager who needs to make go/n
  name: Operational Weather Monitoring
  slug: operational-weather-monitoring
common:
- title: ''
  type: Website
  url: https://xweather.com
- title: ''
  type: Documentation
  url: https://www.xweather.com/docs/weather-api
- title: ''
  type: APIReference
  url: https://www.xweather.com/docs/weather-api/endpoints
- title: ''
  type: Authentication
  url: https://www.xweather.com/docs/weather-api/getting-started/authentication
- title: ''
  type: SignUp
  url: https://www.xweather.com/
- title: ''
  type: Pricing
  url: https://www.xweather.com/weather-api
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/openapi/xweather-weather-api-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-location-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-conditions-observation-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-forecast-period-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-alert-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-lightning-strike-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-air-quality-observation-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-structure/xweather-weather-api-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-ld/xweather-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/vocabulary/xweather-vocabulary.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/rules/xweather-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/capabilities/operational-weather-monitoring.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/capabilities/lightning-safety.yaml
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-conditions-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-forecasts-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-alerts-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-lightning-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-air-quality-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-list-tropical-cyclones-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-maritime-example.json
created: '2024-11-08'
description: Xweather, a Vaisala company, provides weather data APIs delivering science-backed, hyper-local weather intelligence for operational applications. The Xweather Weather API exposes current conditions, forecasts, severe weather alerts, lightning data, air quality, observations, wildfire information, tropical cyclone tracks, and maritime weather through a single REST API. Authentication uses a client_id and client_secret passed as query parameters or HTTP headers.
features:
- description: Current surface weather observations for any location worldwide.
  name: Real-Time Conditions
- description: Forecast records out to 15 days with hourly and daily granularity.
  name: Hourly and Daily Forecasts
- description: Government-issued alerts, watches, and warnings with severity, urgency, and certainty.
  name: Severe Weather Alerts
- description: Cloud-to-ground and in-cloud lightning strike data from Vaisala's global detection network.
  name: Global Lightning Network
- description: Probabilistic short-term lightning threat used to drive stop-work and all-clear automation.
  name: Lightning Threat Nowcast
- description: AQI values, primary pollutant, and detailed pollutant breakdowns for monitoring and reporting.
  name: Air Quality
- description: Marine weather including waves, swell, sea-surface temperature, and sea state.
  name: Maritime Weather
- description: Active wildfire incident records and perimeters for situational awareness.
  name: Wildfire Data
- description: Active tropical cyclone tracks, intensity, and forecast cones.
  name: Tropical Cyclones
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Tile and overlay services for visualizing Xweather data on web and mobile maps.
  name: AerisWeather Mapping
- description: Underlying global lightning detection infrastructure feeding the Xweather lightning APIs.
  name: Vaisala Lightning Network
- description: Severe-weather alert payloads align with CAP severity, urgency, and certainty fields.
  name: Common Alerting Protocol
- description: Surface observations are derived from the international METAR observation standard.
  name: METAR
jsonld:
- class_count: 0
  name: Xweather Context
  property_count: 66
  slug: xweather-context
layout: provider
modified: '2026-05-03'
name: Xweather
rules:
- name: Xweather API Rules
  rule_count: 11
  severity_counts:
    error: 4
    hint: 1
    info: 0
    warn: 6
  slug: xweather-rules
skills: []
slug: xweather
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: xweather\nname: Xweather\ndescription: >-\n  Xweather, a Vaisala company, provides weather data APIs delivering science-backed,\n  hyper-local weather intelligence for operational applications. The Xweather Weather API\n  exposes current conditions, forecasts, severe weather alerts, lightning data, air quality,\n  observations, wildfire information, tropical cyclone tracks, and maritime weather through\n  a single REST API. Authentication uses a client_id and client_secret passed as query\n  parameters or HTTP headers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consumer\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/apis.yml\ntags:\n  - Air Quality\n  - Company\n  - Data\n  - Forecasts\n  - Lightning\n  - Maritime\n  - Observations\n  - Severe Weather\n  - Weather\ncreated: '2024-11-08'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n \
  \ - aid: xweather:xweather\n    name: Xweather Weather API\n    description: >-\n      The Xweather Weather API provides real-time and historical weather data including\n      current conditions, forecasts, severe weather alerts, lightning data, air quality,\n      maritime weather, wildfire data, and tropical cyclone information. Backed by Vaisala,\n      Xweather delivers science-backed hyper-local weather intelligence through a RESTful\n      interface authenticated with client ID and client secret.\n    humanURL: https://www.xweather.com/docs/weather-api\n    baseURL: https://data.api.xweather.com\n    tags:\n      - Air Quality\n      - Alerts\n      - Data\n      - Forecasts\n      - Lightning\n      - Maritime\n      - Observations\n      - Severe Weather\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://www.xweather.com/docs/weather-api\n      - type: GettingStarted\n        url: https://www.xweather.com/docs/weather-api/getting-started/authentication\n\
  \      - type: APIReference\n        url: https://www.xweather.com/docs/weather-api/endpoints\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/openapi/xweather-weather-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://xweather.com\n  - type: Documentation\n    url: https://www.xweather.com/docs/weather-api\n  - type: APIReference\n    url: https://www.xweather.com/docs/weather-api/endpoints\n  - type: Authentication\n    url: https://www.xweather.com/docs/weather-api/getting-started/authentication\n  - type: SignUp\n    url: https://www.xweather.com/\n  - type: Pricing\n    url: https://www.xweather.com/weather-api\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/openapi/xweather-weather-api-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-location-schema.json\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-conditions-observation-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-forecast-period-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-alert-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-lightning-strike-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-schema/xweather-air-quality-observation-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-structure/xweather-weather-api-structure.json\n\
  \  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/json-ld/xweather-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/vocabulary/xweather-vocabulary.yml\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/rules/xweather-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/capabilities/operational-weather-monitoring.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/capabilities/lightning-safety.yaml\n  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-conditions-example.json\n  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-forecasts-example.json\n\
  \  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-alerts-example.json\n  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-lightning-example.json\n  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-air-quality-example.json\n  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-list-tropical-cyclones-example.json\n  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/examples/xweather-get-maritime-example.json\n  - type: Features\n    data:\n      - name: Real-Time Conditions\n        description: Current surface weather observations for any location worldwide.\n      - name: Hourly and Daily Forecasts\n     \
  \   description: Forecast records out to 15 days with hourly and daily granularity.\n      - name: Severe Weather Alerts\n        description: Government-issued alerts, watches, and warnings with severity, urgency, and certainty.\n      - name: Global Lightning Network\n        description: Cloud-to-ground and in-cloud lightning strike data from Vaisala's global detection network.\n      - name: Lightning Threat Nowcast\n        description: Probabilistic short-term lightning threat used to drive stop-work and all-clear automation.\n      - name: Air Quality\n        description: AQI values, primary pollutant, and detailed pollutant breakdowns for monitoring and reporting.\n      - name: Maritime Weather\n        description: Marine weather including waves, swell, sea-surface temperature, and sea state.\n      - name: Wildfire Data\n        description: Active wildfire incident records and perimeters for situational awareness.\n      - name: Tropical Cyclones\n        description: Active\
  \ tropical cyclone tracks, intensity, and forecast cones.\n  - type: UseCases\n    data:\n      - name: Construction Lightning Safety\n        description: Automatically pause and resume outdoor construction work using lightning threat nowcasts.\n      - name: Aviation Ground Operations\n        description: Drive ramp closures and re-openings around lightning, severe weather, and visibility thresholds.\n      - name: Outdoor Sports and Events\n        description: Manage stadium and event evacuations and re-entries based on lightning and severe weather.\n      - name: Energy and Utilities\n        description: Plan grid operations, crew dispatch, and storm restoration around forecasts and alerts.\n      - name: Logistics and Routing\n        description: Optimize routing and dispatch decisions using maritime, road weather, and severe weather feeds.\n      - name: Insurance and Risk\n        description: Use historical and real-time storm and lightning data for claims and underwriting.\n\
  \      - name: Environmental Reporting\n        description: Aggregate AQI and pollutant feeds for ESG and regulatory reporting.\n  - type: Integrations\n    data:\n      - name: AerisWeather Mapping\n        description: Tile and overlay services for visualizing Xweather data on web and mobile maps.\n      - name: Vaisala Lightning Network\n        description: Underlying global lightning detection infrastructure feeding the Xweather lightning APIs.\n      - name: Common Alerting Protocol\n        description: Severe-weather alert payloads align with CAP severity, urgency, and certainty fields.\n      - name: METAR\n        description: Surface observations are derived from the international METAR observation standard.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/apis.yml
tags:
- Air Quality
- Company
- Data
- Forecasts
- Lightning
- Maritime
- Observations
- Severe Weather
- Weather
url: https://raw.githubusercontent.com/api-evangelist/xweather/refs/heads/main/apis.yml
use_cases:
- description: Automatically pause and resume outdoor construction work using lightning threat nowcasts.
  name: Construction Lightning Safety
- description: Drive ramp closures and re-openings around lightning, severe weather, and visibility thresholds.
  name: Aviation Ground Operations
- description: Manage stadium and event evacuations and re-entries based on lightning and severe weather.
  name: Outdoor Sports and Events
- description: Plan grid operations, crew dispatch, and storm restoration around forecasts and alerts.
  name: Energy and Utilities
- description: Optimize routing and dispatch decisions using maritime, road weather, and severe weather feeds.
  name: Logistics and Routing
- description: Use historical and real-time storm and lightning data for claims and underwriting.
  name: Insurance and Risk
- description: Aggregate AQI and pollutant feeds for ESG and regulatory reporting.
  name: Environmental Reporting
---
