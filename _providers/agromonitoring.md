---
api_count: 1
api_specs:
- filename: agromonitoring-openapi.yml
  format: yaml
  label: Agromonitoring
  slug: agromonitoring
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/openapi/agromonitoring-openapi.yml
apis:
- description: The Agromonitoring Agro API provides satellite imagery, vegetation index time series (NDVI, EVI, DSWI, LSWI), weather data, soil conditions, and UV index for registered agricultural field polygons. En
  name: Agromonitoring
  slug: agromonitoring
capabilities:
- description: ''
  name: Crop Monitoring
  slug: crop-monitoring
common:
- title: ''
  type: Portal
  url: https://agromonitoring.com/
- title: ''
  type: Documentation
  url: https://agromonitoring.com/api/
- title: ''
  type: GettingStarted
  url: https://agromonitoring.com/api/agro/#auth
- title: ''
  type: Pricing
  url: https://agromonitoring.com/subscriptions
- title: ''
  type: FAQ
  url: https://agromonitoring.com/faq/
- title: ''
  type: TermsOfService
  url: https://agromonitoring.com/terms/
- title: ''
  type: PrivacyPolicy
  url: https://agromonitoring.com/privacy/
- title: ''
  type: JSON-LD
  url: json-ld/agromonitoring-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/agromonitoring-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/agromonitoring-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/agromonitoring-api.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/crop-monitoring.yaml
created: '2025-02-06'
description: Agromonitoring is a technology company specializing in satellite-based agricultural monitoring. Using Sentinel-2 and Landsat imagery combined with weather and soil data, Agromonitoring provides vegetation index time series (NDVI, EVI, DSWI, LSWI), current weather, multi-day forecasts, and soil conditions for registered field polygons. The platform enables precision agriculture workflows including crop health assessment, irrigation optimization, yield prediction, and climate risk monitoring.
features:
- description: Register, retrieve, and delete georeferenced agricultural field polygons using GeoJSON geometry
  name: Field Polygon Management
- description: Search Sentinel-2 and Landsat satellite archives for cloud-free imagery over registered fields
  name: Satellite Imagery Search
- description: Access NDVI, EVI, EVI2, NRI, DSWI, and LSWI historical time series to track crop health and stress
  name: Vegetation Index Time Series
- description: Real-time weather conditions including temperature, humidity, wind speed, pressure, and cloud cover
  name: Current Weather Data
- description: Multi-day weather forecasts to support irrigation scheduling and field operation planning
  name: Weather Forecasting
- description: Soil temperature at surface and 10cm depth plus volumetric soil moisture content
  name: Soil Monitoring
- description: Solar UV radiation index to assess sun exposure and radiation stress on crops
  name: UV Index Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Agromonitoring uses OpenWeatherMap weather infrastructure for current and forecast data
  name: OpenWeatherMap
- description: European Space Agency Sentinel-2 satellite data is a primary imagery source
  name: Sentinel-2
- description: NASA/USGS Landsat imagery is available as an additional satellite data source
  name: Landsat
jsonld:
- class_count: 33
  name: Agromonitoring Context
  property_count: 6
  slug: agromonitoring-context
layout: provider
modified: '2026-04-19'
name: Agromonitoring
rules:
- name: Agromonitoring API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 10
  slug: agromonitoring-spectral-rules
skills: []
slug: agromonitoring
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: agromonitoring\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/apis.yml\napis:\n  - aid: agromonitoring:agromonitoring\n    name: Agromonitoring\n    tags:\n      - Agriculture\n      - Satellite Imagery\n      - Vegetation Indices\n      - Weather\n      - Precision Agriculture\n    humanURL: https://agromonitoring.com/\n    properties:\n      - url: https://agromonitoring.com/\n        type: Documentation\n      - url: https://agromonitoring.com/api/\n        type: APIReference\n      - url: https://agromonitoring.com/api/agro/#auth\n        type: Authentication\n      - url: https://agromonitoring.com/subscriptions\n        type: Pricing\n      - url: openapi/agromonitoring-openapi.yml\n        type: OpenAPI\n      - url: json-schema/agromonitoring-polygon-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-geojson-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-satelliteimage-schema.json\n\
  \        type: JSONSchema\n      - url: json-schema/agromonitoring-ndvirecord-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-vegetationstats-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-weatherdata-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-temperaturerange-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-soildata-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-uvindexdata-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-polygoncreaterequest-schema.json\n        type: JSONSchema\n      - url: json-schema/agromonitoring-errorresponse-schema.json\n        type: JSONSchema\n      - url: json-structure/agromonitoring-polygon-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-geojson-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-satelliteimage-structure.json\n\
  \        type: JSONStructure\n      - url: json-structure/agromonitoring-ndvirecord-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-vegetationstats-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-weatherdata-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-temperaturerange-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-soildata-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-uvindexdata-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-polygoncreaterequest-structure.json\n        type: JSONStructure\n      - url: json-structure/agromonitoring-errorresponse-structure.json\n        type: JSONStructure\n      - url: examples/agromonitoring-polygon-example.json\n        type: Example\n      - url: examples/agromonitoring-geojson-example.json\n        type:\
  \ Example\n      - url: examples/agromonitoring-satelliteimage-example.json\n        type: Example\n      - url: examples/agromonitoring-ndvirecord-example.json\n        type: Example\n      - url: examples/agromonitoring-vegetationstats-example.json\n        type: Example\n      - url: examples/agromonitoring-weatherdata-example.json\n        type: Example\n      - url: examples/agromonitoring-temperaturerange-example.json\n        type: Example\n      - url: examples/agromonitoring-soildata-example.json\n        type: Example\n      - url: examples/agromonitoring-uvindexdata-example.json\n        type: Example\n      - url: examples/agromonitoring-polygoncreaterequest-example.json\n        type: Example\n      - url: examples/agromonitoring-errorresponse-example.json\n        type: Example\n    description: >-\n      The Agromonitoring Agro API provides satellite imagery, vegetation index\n      time series (NDVI, EVI, DSWI, LSWI), weather data, soil conditions, and\n      UV index for\
  \ registered agricultural field polygons. Enables precision\n      agriculture workflows including crop health monitoring, irrigation\n      decision support, and yield optimization.\n\ncommon:\n  - url: https://agromonitoring.com/\n    type: Portal\n  - url: https://agromonitoring.com/api/\n    type: Documentation\n  - url: https://agromonitoring.com/api/agro/#auth\n    type: GettingStarted\n  - url: https://agromonitoring.com/subscriptions\n    type: Pricing\n  - url: https://agromonitoring.com/faq/\n    type: FAQ\n  - url: https://agromonitoring.com/terms/\n    type: TermsOfService\n  - url: https://agromonitoring.com/privacy/\n    type: PrivacyPolicy\n  - url: json-ld/agromonitoring-context.jsonld\n    type: JSON-LD\n  - url: rules/agromonitoring-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/agromonitoring-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/shared/agromonitoring-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/crop-monitoring.yaml\n\
  \    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Field Polygon Management\n        description: Register, retrieve, and delete georeferenced agricultural field polygons using GeoJSON geometry\n      - name: Satellite Imagery Search\n        description: Search Sentinel-2 and Landsat satellite archives for cloud-free imagery over registered fields\n      - name: Vegetation Index Time Series\n        description: Access NDVI, EVI, EVI2, NRI, DSWI, and LSWI historical time series to track crop health and stress\n      - name: Current Weather Data\n        description: Real-time weather conditions including temperature, humidity, wind speed, pressure, and cloud cover\n      - name: Weather Forecasting\n        description: Multi-day weather forecasts to support irrigation scheduling and field operation planning\n      - name: Soil Monitoring\n        description: Soil temperature at surface and 10cm depth plus volumetric soil moisture content\n      - name: UV Index\
  \ Data\n        description: Solar UV radiation index to assess sun exposure and radiation stress on crops\n  - type: UseCases\n    data:\n      - name: Crop Health Monitoring\n        description: Track vegetation index trends over the growing season to identify stress, disease, or nutrient deficiencies early\n      - name: Irrigation Management\n        description: Combine soil moisture, weather forecast, and NDVI data to optimize irrigation scheduling and reduce water usage\n      - name: Yield Prediction\n        description: Use satellite-derived vegetation indices across the growing season to build yield prediction models\n      - name: Field Boundary Mapping\n        description: Register precise field polygon boundaries for targeted data retrieval and zonal analysis\n      - name: Precision Agriculture\n        description: Apply variable-rate inputs using spatial variability data from satellite imagery and vegetation indices\n      - name: Climate Risk Assessment\n        description:\
  \ Monitor weather extremes, drought, and soil conditions to assess climate-related agricultural risks\n  - type: Integrations\n    data:\n      - name: OpenWeatherMap\n        description: Agromonitoring uses OpenWeatherMap weather infrastructure for current and forecast data\n      - name: Sentinel-2\n        description: European Space Agency Sentinel-2 satellite data is a primary imagery source\n      - name: Landsat\n        description: NASA/USGS Landsat imagery is available as an additional satellite data source\n\nname: Agromonitoring\ntags:\n  - Agriculture\n  - Satellite Imagery\n  - Vegetation Indices\n  - Weather\n  - Precision Agriculture\n  - Remote Sensing\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-06'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  Agromonitoring is a technology company specializing in satellite-based\n  agricultural monitoring. Using Sentinel-2 and\
  \ Landsat imagery combined with\n  weather and soil data, Agromonitoring provides vegetation index time series\n  (NDVI, EVI, DSWI, LSWI), current weather, multi-day forecasts, and soil\n  conditions for registered field polygons. The platform enables precision\n  agriculture workflows including crop health assessment, irrigation\n  optimization, yield prediction, and climate risk monitoring.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/apis.yml
tags:
- Agriculture
- Satellite Imagery
- Vegetation Indices
- Weather
- Precision Agriculture
- Remote Sensing
url: https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/apis.yml
use_cases:
- description: Track vegetation index trends over the growing season to identify stress, disease, or nutrient deficiencies early
  name: Crop Health Monitoring
- description: Combine soil moisture, weather forecast, and NDVI data to optimize irrigation scheduling and reduce water usage
  name: Irrigation Management
- description: Use satellite-derived vegetation indices across the growing season to build yield prediction models
  name: Yield Prediction
- description: Register precise field polygon boundaries for targeted data retrieval and zonal analysis
  name: Field Boundary Mapping
- description: Apply variable-rate inputs using spatial variability data from satellite imagery and vegetation indices
  name: Precision Agriculture
- description: Monitor weather extremes, drought, and soil conditions to assess climate-related agricultural risks
  name: Climate Risk Assessment
---
