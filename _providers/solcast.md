---
api_count: 1
api_specs:
- filename: solcast-openapi.yml
  format: yaml
  label: Solcast API
  slug: solcast
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/openapi/solcast-openapi.yml
apis:
- description: The Solcast API provides live, forecast, historical, and typical meteorological year (TMY) solar irradiance, PV power, and weather data derived from a global fleet of weather satellites. It supports r
  name: Solcast API
  slug: solcast
capabilities:
- description: Workflow capability for solar energy forecasting and real-time monitoring. Combines live and forecast radiation, PV power, soiling, and grid aggregation data to support energy market bidding, dispatch
  name: Solcast Solar Forecasting
  slug: solar-forecasting
- description: Workflow capability for solar resource assessment, project financing, and long-term yield analysis. Combines historical irradiance, rooftop and advanced PV power histories, TMY data, historical soilin
  name: Solcast Solar Resource Assessment
  slug: solar-resource-assessment
common:
- title: ''
  type: Portal
  url: https://solcast.com/
- title: ''
  type: Documentation
  url: https://docs.solcast.com.au/
- title: ''
  type: SDKs
  url: https://solcast.com/sdk
- title: ''
  type: Sign Up
  url: https://toolkit.solcast.com.au/register
- title: ''
  type: Pricing
  url: https://solcast.com/pricing/irradiance-weather
- title: ''
  type: Change Log
  url: https://solcast.com/changelog
- title: ''
  type: Website
  url: https://solcast.com
- title: ''
  type: GitHub
  url: https://github.com/Solcast
- title: ''
  type: API Toolkit
  url: https://toolkit.solcast.com.au/
- title: ''
  type: Terms of Service
  url: https://solcast.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://solcast.com/privacy-policy
- title: ''
  type: Contact
  url: https://solcast.com/contact
created: '2025-05-02'
description: Solcast is a solar and renewable energy data company, acquired by DNV in 2023, that provides high-resolution, satellite-derived solar irradiance, PV power, weather forecasting, and historical climate data via a developer API. Its data covers live, forecast, historical, and typical meteorological year (TMY) datasets for rooftop PV, advanced PV, grid aggregations, and soiling models globally.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Solcast Context
  property_count: 56
  slug: solcast-context
layout: provider
modified: '2026-05-02'
name: Solcast
rules:
- name: Solcast API Rules
  rule_count: 18
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 12
  slug: solcast-rules
skills: []
slug: solcast
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: solcast\nname: Solcast\ndescription: >-\n  Solcast is a solar and renewable energy data company, acquired by DNV in 2023,\n  that provides high-resolution, satellite-derived solar irradiance, PV power,\n  weather forecasting, and historical climate data via a developer API. Its data\n  covers live, forecast, historical, and typical meteorological year (TMY) datasets\n  for rooftop PV, advanced PV, grid aggregations, and soiling models globally.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Solar\n  - Energy\n  - Forecasting\n  - Irradiance\n  - Weather\n  - Renewable Energy\n  - PV Power\ncreated: '2025-05-02'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: solcast:solcast\n    name: Solcast API\n    description: >-\n      The Solcast API provides live, forecast,\
  \ historical, and typical meteorological\n      year (TMY) solar irradiance, PV power, and weather data derived from a global\n      fleet of weather satellites. It supports rooftop PV power, advanced PV power\n      (for registered sites), grid aggregation data, and soiling loss models (Kimber\n      and HSU). Authentication uses an API key. Data is available in JSON and CSV\n      formats with 5- to 60-minute granularity anywhere on the planet.\n    humanURL: https://docs.solcast.com.au/\n    baseURL: https://api.solcast.com.au\n    tags:\n      - Solar\n      - Forecasting\n      - Irradiance\n      - PV Power\n      - Weather\n      - Renewable Energy\n      - Grid Aggregation\n      - Historical Data\n      - TMY\n      - Soiling\n    properties:\n      - type: Documentation\n        url: https://docs.solcast.com.au/\n      - type: Getting Started\n        url: https://docs.solcast.com.au/docs/getting-started\n      - type: Authentication\n        url: https://docs.solcast.com.au/docs/api-authentication\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/openapi/solcast-openapi.yml\n      - type: SDKs\n        url: https://solcast.com/sdk\n      - type: PythonSDK\n        url: https://github.com/Solcast/solcast-api-python-sdk\n      - type: CSharpSDK\n        url: https://github.com/Solcast/solcast-api-csharp-sdk\n      - type: JuliaSDK\n        url: https://github.com/Solcast/Solcast.jl\n      - type: Rules\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/rules/solcast-rules.yml\n      - type: Capabilities\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/capabilities/solar-forecasting.yaml\n      - type: Capabilities\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/capabilities/solar-resource-assessment.yaml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-schema/solcast-radiation-and-weather-schema.json\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-schema/solcast-pv-power-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-schema/solcast-pv-power-site-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-structure/solcast-radiation-and-weather-structure.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-structure/solcast-pv-power-structure.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-structure/solcast-pv-power-site-structure.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/json-ld/solcast-context.jsonld\n      - type: Vocabulary\n     \
  \   url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/vocabulary/solcast-vocabulary.yml\n    contact:\n      - FN: Solcast Support\n        url: https://solcast.com/contact\n    features:\n      - name: Live Radiation and Weather Data\n        description: Real-time satellite-derived solar irradiance and weather, updated every 5 minutes, covering the last 7 days.\n      - name: Forecast Radiation and Weather\n        description: Solar irradiance and weather forecasts up to 14 days ahead with 5- to 60-minute granularity.\n      - name: Rooftop PV Power (Live, Forecast, Historic, TMY)\n        description: Estimated PV power output for rooftop solar sites by latitude/longitude without pre-registration.\n      - name: Advanced PV Power (Live, Forecast, Historic)\n        description: High-specification PV power data for registered PV power sites using Solcast's advanced PV model.\n      - name: Historical Data\n        description: Historical solar radiation and\
  \ weather data available from 2007-01-01 up to 7 days before present.\n      - name: Typical Meteorological Year (TMY)\n        description: Long-run average solar and weather profiles calculated from 2007 to 2023 data.\n      - name: Grid Aggregation (Live and Forecast)\n        description: Live and forecast aggregation data for grid collections and sub-aggregations, up to 7 days.\n      - name: Soiling Models\n        description: Hourly soiling loss estimates using the Kimber and HSU models, available for live, forecast, and historic data.\n      - name: PV Power Site Management\n        description: CRUD management of registered PV power sites for use with the advanced PV power model.\n    useCases:\n      - name: Solar Farm Performance Monitoring\n        description: Operators monitor live and forecast irradiance alongside actual PV output to detect underperformance.\n      - name: Energy Market Bidding\n        description: Traders use 14-day forecasts to place optimal bids in\
  \ electricity markets.\n      - name: Grid Management\n        description: Grid operators aggregate real-time and forecast PV generation across portfolios using the aggregation API.\n      - name: Solar Resource Assessment\n        description: Project developers use historical and TMY data for bankable resource assessment in project financing.\n      - name: Soiling Analysis\n        description: Asset managers model panel soiling losses to schedule cleaning and improve yield.\n      - name: Renewable Energy Integration\n        description: Utilities integrate solar forecasts to balance supply and demand and optimise dispatch decisions.\n    integrations:\n      - name: Python\n        url: https://github.com/Solcast/solcast-api-python-sdk\n      - name: C# / .NET\n        url: https://github.com/Solcast/solcast-api-csharp-sdk\n      - name: Julia\n        url: https://github.com/Solcast/Solcast.jl\n      - name: pvlib\n        url: https://pvlib-python.readthedocs.io/\n      - name:\
  \ Pandas\n        url: https://github.com/Solcast/howto-pandas\n      - name: GeoServer\n        url: https://github.com/Solcast/geoserver\ncommon:\n  - type: Portal\n    url: https://solcast.com/\n  - type: Documentation\n    url: https://docs.solcast.com.au/\n  - type: SDKs\n    url: https://solcast.com/sdk\n  - type: Sign Up\n    url: https://toolkit.solcast.com.au/register\n  - type: Pricing\n    url: https://solcast.com/pricing/irradiance-weather\n  - type: Change Log\n    url: https://solcast.com/changelog\n  - type: Website\n    url: https://solcast.com\n  - type: GitHub\n    url: https://github.com/Solcast\n  - type: API Toolkit\n    url: https://toolkit.solcast.com.au/\n  - type: Terms of Service\n    url: https://solcast.com/terms-of-service\n  - type: Privacy Policy\n    url: https://solcast.com/privacy-policy\n  - type: Contact\n    url: https://solcast.com/contact\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/apis.yml
tags:
- Solar
- Energy
- Forecasting
- Irradiance
- Weather
- Renewable Energy
- PV Power
url: https://raw.githubusercontent.com/api-evangelist/solcast/refs/heads/main/apis.yml
use_cases: []
---
