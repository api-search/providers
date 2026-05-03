---
api_count: 6
api_specs:
- filename: weatherbit-current-weather-openapi-original.yml
  format: yaml
  label: Weatherbit Current Weather API
  slug: weatherbit-current-weather-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/openapi/weatherbit-current-weather-openapi-original.yml
apis:
- description: Returns current weather conditions from Weatherbit's global network of sub-hourly reporting weather stations and atmospheric meso-analyses. Supports lookup by lat/lon, city name, city ID, postal code,
  name: Weatherbit Current Weather API
  slug: weatherbit-current-weather-api
- description: Returns severe weather alerts issued by local meteorological agencies. Covers the USA (NOAA), EU nations and UK (Meteoalarm), Canada (Environment Canada), and China (China Meteorological Administratio
  name: Weatherbit Severe Weather Alerts API
  slug: weatherbit-severe-weather-alerts-api
- description: Provides accurate weather forecasts using high-resolution global and regional weather models. Includes 16-day daily, 240-hour hourly, and 60-minute precipitation nowcasts.
  name: Weatherbit Weather Forecast API
  slug: weatherbit-weather-forecast-api
- description: High-resolution historical weather data backed by over 120,000 weather stations and gridded datasets. Includes daily, hourly, and sub-hourly observations, climate normals, and gap-free data.
  name: Weatherbit Historical Weather API
  slug: weatherbit-historical-weather-api
- description: Agricultural weather data using the GLDAS re-analysis with global coverage at 0.25-degree resolution. Includes evapotranspiration, soil moisture, and crop-specific weather parameters.
  name: Weatherbit Ag-Weather API
  slug: weatherbit-ag-weather-api
- description: High-quality air quality data derived from global and regional air quality models. Tracks six major pollutants (PM2.5, PM10, O3, NO2, SO2, CO) plus pollen levels and mold. Includes current and 72-hour
  name: Weatherbit Air Quality API
  slug: weatherbit-air-quality-api
capabilities:
- description: Unified weather intelligence workflow combining current conditions, forecasts, historical data, alerts, and air quality. Used by developers, businesses, and researchers to access global weather data.
  name: Weatherbit Weather Intelligence
  slug: weather-intelligence
common:
- title: ''
  type: Plans
  url: https://www.weatherbit.io/pricing
- title: ''
  type: FAQ
  url: https://help.weatherbit.io/faq/
- title: ''
  type: StatusPage
  url: https://status.weatherbit.io/
- title: ''
  type: Blog
  url: https://blog.weatherbit.io/
- title: ''
  type: KnowledgeCenter
  url: https://help.weatherbit.io/
- title: ''
  type: SignUp
  url: https://www.weatherbit.io/account/create
- title: ''
  type: Login
  url: https://www.weatherbit.io/account/login
- title: ''
  type: TermsOfService
  url: https://www.weatherbit.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.weatherbit.io/privacy
- title: ''
  type: Contact
  url: https://www.weatherbit.io/contact
- title: ''
  type: GitHubRepository
  url: https://github.com/weatherbit/weatherbit-python
- title: Python SDK
  type: SDK
  url: https://pypi.org/project/pyweatherbit/
- title: ''
  type: SpectralRules
  url: rules/weatherbit-spectral-rules.yml
- title: Weather Intelligence Capability
  type: NaftikoCapability
  url: capabilities/weather-intelligence.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/weatherbit-vocabulary.yml
created: 2023/11/20
description: Weatherbit is a leading provider of weather data and forecasting services. They specialize in delivering accurate and up-to-date weather information to businesses and individuals around the world. Services include real-time current weather, 16-day daily and 240-hour hourly forecasts, historical weather data, severe alerts, air quality monitoring, agricultural weather, energy forecasts, and climate normals. Data is available globally via lat/lon, city name, postal code, and station ID.
features:
- description: Live observations updated every 5-30 minutes from global weather station network.
  name: Current Weather
- description: High-accuracy daily forecasts for up to 16 days ahead using state-of-the-art weather models.
  name: 16-Day Daily Forecasts
- description: Detailed hourly forecasts for up to 10 days (240 hours) ahead.
  name: 240-Hour Hourly Forecasts
- description: Real-time severe weather alerts from official agencies in the US, EU, Canada, and China.
  name: Severe Weather Alerts
- description: Gap-free historical weather data going back decades using ML and statistical backfilling.
  name: Historical Weather Data
- description: Current and forecast air quality data tracking PM2.5, PM10, O3, NO2, SO2, CO, and pollen levels.
  name: Air Quality Monitoring
- description: Specialized agricultural weather data including evapotranspiration, soil moisture, and growing degree days.
  name: Agricultural Weather
- description: Energy sector weather forecasts including heating and cooling degree days.
  name: Energy Forecasts
- description: 1991-2020 climate normals at 9km resolution for historical comparison.
  name: Climate Normals
- description: Access data by lat/lon, city name, city ID, station ID, ICAO code, or postal code.
  name: Multiple Lookup Methods
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Python SDK available on PyPI (pyweatherbit)
  name: Python
- description: RESTful JSON API compatible with any programming language
  name: REST API
jsonld:
- class_count: 32
  name: Weatherbit Context
  property_count: 121
  slug: weatherbit-context
layout: provider
modified: '2026-05-03'
name: Weatherbit
rules:
- name: Weatherbit API Rules
  rule_count: 19
  severity_counts:
    error: 6
    hint: 0
    info: 4
    warn: 9
  slug: weatherbit-spectral-rules
skills: []
slug: weatherbit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: weatherbit\nurl: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/apis.yml\napis:\n  - aid: weatherbit:weatherbit-current-weather-api\n    name: Weatherbit Current Weather API\n    tags:\n      - Weather\n      - Current Conditions\n      - Observations\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io/v2.0\n    humanURL: https://www.weatherbit.io/api/weather-current\n    properties:\n      - url: https://www.weatherbit.io/api/weather-current\n        type: Documentation\n      - url: openapi/weatherbit-current-weather-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      Returns current weather conditions from Weatherbit's global network of\n      sub-hourly reporting weather stations and atmospheric meso-analyses.\n      Supports lookup by lat/lon, city name, city ID, postal code, or station ID.\n\n  - aid: weatherbit:weatherbit-severe-weather-alerts-api\n\
  \    name: Weatherbit Severe Weather Alerts API\n    tags:\n      - Weather\n      - Alerts\n      - Emergency\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io/v2.0\n    humanURL: https://www.weatherbit.io/api/alerts\n    properties:\n      - url: https://www.weatherbit.io/api/alerts\n        type: Documentation\n    description: >-\n      Returns severe weather alerts issued by local meteorological agencies.\n      Covers the USA (NOAA), EU nations and UK (Meteoalarm), Canada (Environment\n      Canada), and China (China Meteorological Administration).\n\n  - aid: weatherbit:weatherbit-weather-forecast-api\n    name: Weatherbit Weather Forecast API\n    tags:\n      - Weather\n      - Forecasting\n      - Daily\n      - Hourly\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io/v2.0\n    humanURL: https://www.weatherbit.io/api/weather-forecast-api\n\
  \    properties:\n      - url: https://www.weatherbit.io/api/weather-forecast-api\n        type: Documentation\n    description: >-\n      Provides accurate weather forecasts using high-resolution global and\n      regional weather models. Includes 16-day daily, 240-hour hourly,\n      and 60-minute precipitation nowcasts.\n\n  - aid: weatherbit:weatherbit-historical-weather-api\n    name: Weatherbit Historical Weather API\n    tags:\n      - Weather\n      - Historical\n      - Climate\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io/v2.0\n    humanURL: https://www.weatherbit.io/api/historical-weather-api\n    properties:\n      - url: https://www.weatherbit.io/api/historical-weather-api\n        type: Documentation\n    description: >-\n      High-resolution historical weather data backed by over 120,000 weather\n      stations and gridded datasets. Includes daily, hourly, and sub-hourly\n      observations,\
  \ climate normals, and gap-free data.\n\n  - aid: weatherbit:weatherbit-ag-weather-api\n    name: Weatherbit Ag-Weather API\n    tags:\n      - Weather\n      - Agriculture\n      - Evapotranspiration\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io/v2.0\n    humanURL: https://www.weatherbit.io/api/agweather-api\n    properties:\n      - url: https://www.weatherbit.io/api/agweather-api\n        type: Documentation\n    description: >-\n      Agricultural weather data using the GLDAS re-analysis with global\n      coverage at 0.25-degree resolution. Includes evapotranspiration,\n      soil moisture, and crop-specific weather parameters.\n\n  - aid: weatherbit:weatherbit-air-quality-api\n    name: Weatherbit Air Quality API\n    tags:\n      - Air Quality\n      - AQI\n      - Environment\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io/v2.0\n\
  \    humanURL: https://www.weatherbit.io/api/air-quality-api\n    properties:\n      - url: https://www.weatherbit.io/api/air-quality-api\n        type: Documentation\n    description: >-\n      High-quality air quality data derived from global and regional air\n      quality models. Tracks six major pollutants (PM2.5, PM10, O3, NO2,\n      SO2, CO) plus pollen levels and mold. Includes current and 72-hour\n      forecast data.\n\nname: Weatherbit\ntags:\n  - Weather\n  - Forecasting\n  - Historical Data\n  - Air Quality\n  - Alerts\n  - Agricultural Weather\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncommon:\n  - url: https://www.weatherbit.io/pricing\n    type: Plans\n  - url: https://www.weatherbit.io/features\n    type: Features\n  - url: https://help.weatherbit.io/faq/\n    type: FAQ\n  - url: https://status.weatherbit.io/\n    type: StatusPage\n  - url: https://blog.weatherbit.io/\n    type: Blog\n  - url: https://help.weatherbit.io/\n    type:\
  \ KnowledgeCenter\n  - url: https://www.weatherbit.io/account/create\n    type: SignUp\n  - url: https://www.weatherbit.io/account/login\n    type: Login\n  - url: https://www.weatherbit.io/terms\n    type: TermsOfService\n  - url: https://www.weatherbit.io/privacy\n    type: PrivacyPolicy\n  - url: https://www.weatherbit.io/contact\n    type: Contact\n  - url: https://github.com/weatherbit/weatherbit-python\n    type: GitHubRepository\n  - url: https://pypi.org/project/pyweatherbit/\n    type: SDK\n    title: Python SDK\n  - type: SpectralRules\n    url: rules/weatherbit-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/weather-intelligence.yaml\n    title: Weather Intelligence Capability\n  - type: Vocabulary\n    url: vocabulary/weatherbit-vocabulary.yml\n  - type: Features\n    data:\n      - name: Current Weather\n        description: >-\n          Live observations updated every 5-30 minutes from global weather\n          station network.\n      - name: 16-Day\
  \ Daily Forecasts\n        description: >-\n          High-accuracy daily forecasts for up to 16 days ahead using\n          state-of-the-art weather models.\n      - name: 240-Hour Hourly Forecasts\n        description: >-\n          Detailed hourly forecasts for up to 10 days (240 hours) ahead.\n      - name: Severe Weather Alerts\n        description: >-\n          Real-time severe weather alerts from official agencies in the US,\n          EU, Canada, and China.\n      - name: Historical Weather Data\n        description: >-\n          Gap-free historical weather data going back decades using ML and\n          statistical backfilling.\n      - name: Air Quality Monitoring\n        description: >-\n          Current and forecast air quality data tracking PM2.5, PM10, O3,\n          NO2, SO2, CO, and pollen levels.\n      - name: Agricultural Weather\n        description: >-\n          Specialized agricultural weather data including evapotranspiration,\n          soil moisture, and growing\
  \ degree days.\n      - name: Energy Forecasts\n        description: >-\n          Energy sector weather forecasts including heating and cooling\n          degree days.\n      - name: Climate Normals\n        description: >-\n          1991-2020 climate normals at 9km resolution for historical comparison.\n      - name: Multiple Lookup Methods\n        description: >-\n          Access data by lat/lon, city name, city ID, station ID, ICAO code,\n          or postal code.\n  - type: UseCases\n    data:\n      - name: Mobile Weather Apps\n        description: >-\n          Power consumer weather applications with accurate forecasts and\n          real-time conditions.\n      - name: Agricultural Planning\n        description: >-\n          Optimize crop management with specialized agricultural weather\n          forecasts and historical data.\n      - name: Energy Management\n        description: >-\n          Use degree-day forecasts for energy demand prediction and grid\n          management.\n\
  \      - name: Emergency Management\n        description: >-\n          Monitor severe weather alerts for disaster preparedness and\n          emergency response.\n      - name: Insurance and Risk\n        description: >-\n          Access historical and forecast weather data for risk assessment\n          and claims processing.\n      - name: Logistics and Transportation\n        description: >-\n          Optimize routing and operations based on weather forecasts and\n          real-time conditions.\n  - type: Integrations\n    data:\n      - name: Python\n        description: \"Official Python SDK available on PyPI (pyweatherbit)\"\n      - name: REST API\n        description: \"RESTful JSON API compatible with any programming language\"\ncreated: 2023/11/20\nmodified: '2026-05-03'\ndescription: >-\n  Weatherbit is a leading provider of weather data and forecasting services.\n  They specialize in delivering accurate and up-to-date weather information\n  to businesses and individuals\
  \ around the world. Services include real-time\n  current weather, 16-day daily and 240-hour hourly forecasts, historical\n  weather data, severe alerts, air quality monitoring, agricultural weather,\n  energy forecasts, and climate normals. Data is available globally via\n  lat/lon, city name, postal code, and station ID.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ntype: Index\nposition: Consumer\naccess: 3rd-Party\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/apis.yml
tags:
- Weather
- Forecasting
- Historical Data
- Air Quality
- Alerts
- Agricultural Weather
url: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/apis.yml
use_cases:
- description: Power consumer weather applications with accurate forecasts and real-time conditions.
  name: Mobile Weather Apps
- description: Optimize crop management with specialized agricultural weather forecasts and historical data.
  name: Agricultural Planning
- description: Use degree-day forecasts for energy demand prediction and grid management.
  name: Energy Management
- description: Monitor severe weather alerts for disaster preparedness and emergency response.
  name: Emergency Management
- description: Access historical and forecast weather data for risk assessment and claims processing.
  name: Insurance and Risk
- description: Optimize routing and operations based on weather forecasts and real-time conditions.
  name: Logistics and Transportation
---
