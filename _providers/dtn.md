---
api_count: 5
api_specs:
- filename: dtn-weather-conditions-openapi.yml
  format: yaml
  label: DTN Weather Conditions API
  slug: dtn-weather-conditions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/openapi/dtn-weather-conditions-openapi.yml
apis:
- description: DTN Weather Conditions API delivers worldwide forecast, current condition, and historical weather data. The API leverages cloud technology and global forecast models to provide validated, continuously
  name: DTN Weather Conditions API
  slug: dtn-weather-conditions-api
- description: DTN Point Observation API delivers high-quality weather observation data from weather stations and locations worldwide. Supports near real-time and up to 30 years of historical weather observations. A
  name: DTN Point Observation API
  slug: dtn-point-observation-api
- description: DTN Point Forecast API delivers high-quality weather forecasts for specified locations. Provides hourly and daily forecast data for agriculture, aviation, shipping, and utilities use cases. Uses the s
  name: DTN Point Forecast API
  slug: dtn-point-forecast-api
- description: DTN Radar Precipitation Forecast API provides short-term precipitation forecasts derived from radar data. Supports agricultural, utility, and renewable energy operational planning. Uses OAuth2 authent
  name: DTN Radar Precipitation Forecast API
  slug: dtn-radar-precipitation-forecast-api
- description: DTN provides real-time and historical commodity price data, grain and livestock prices, planting condition indices, and market analysis APIs for precision agriculture and commodity trading workflows.
  name: DTN Commodity & Market Data API
  slug: dtn-commodity-data-api
common:
- title: ''
  type: Website
  url: https://www.dtn.com/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/openapi/dtn-weather-conditions-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/json-schema/dtn-weather-observation-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/json-ld/dtn-context.jsonld
- title: ''
  type: Portal
  url: https://devportal.dtn.com/
- title: ''
  type: Documentation
  url: https://www.dtn.com/resources/api-data-integrations/
- title: ''
  type: Reference
  url: https://api.weather.mg/
- title: ''
  type: TermsOfService
  url: https://www.dtn.com/subscription-agreement-standard-terms-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.dtn.com/wp-content/uploads/2020/04/DTN-External-Privacy-Statement.pdf
- title: ''
  type: GettingStarted
  url: https://www.dtn.com/weather/
created: ''
description: The operation intelligence you can rely on to make confident desicions. Empower your business with the best data resource possible.
features: []
image: ''
integrations: []
jsonld:
- class_count: 2
  name: Dtn Context
  property_count: 20
  slug: dtn-context
layout: provider
modified: '2026-04-28'
name: dtn
skills: []
slug: dtn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dtn\nurl: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/apis.yml\napis:\n  - aid: dtn:dtn-weather-conditions-api\n    name: DTN Weather Conditions API\n    tags:\n      - Agriculture\n      - Climate\n      - Forecast\n      - REST\n      - Weather\n    image: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/image.png\n    humanURL: https://devportal.dtn.com/catalog/Weather/dtn-weather-conditions-api/documentation\n    baseURL: https://weather.api.dtn.com/conditions\n    properties:\n      - url: https://devportal.dtn.com/catalog/Weather/dtn-weather-conditions-api/documentation\n        type: Documentation\n      - url: https://devportal.dtn.com/catalog/Weather/dtn-weather-conditions-api/documentation\n        type: Reference\n      - url: https://devportal.dtn.com/\n        type: Portal\n      - url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/openapi/dtn-weather-conditions-openapi.yml\n        type:\
  \ OpenAPI\n    description: >-\n      DTN Weather Conditions API delivers worldwide forecast, current condition, and\n      historical weather data. The API leverages cloud technology and global forecast\n      models to provide validated, continuously calibrated weather data. Supports\n      geospatial queries, time-based filtering, and multi-station requests across\n      over 70,000 weather stations worldwide. OpenAPI/Swagger spec, Postman collections,\n      and release notes available via the developer portal.\n  - aid: dtn:dtn-point-observation-api\n    name: DTN Point Observation API\n    tags:\n      - Agriculture\n      - Historical Data\n      - Observations\n      - Weather\n    image: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/image.png\n    humanURL: https://api.weather.mg/api-detail-pages/observation-parameter.html\n    baseURL: https://point-observation.weather.mg\n    properties:\n      - url: https://api.weather.mg/api-detail-pages/observation-parameter.html\n\
  \        type: Documentation\n      - url: https://api.weather.mg/\n        type: Portal\n    description: >-\n      DTN Point Observation API delivers high-quality weather observation data from\n      weather stations and locations worldwide. Supports near real-time and up to\n      30 years of historical weather observations. Authentication uses OAuth2 with\n      Client ID and Client Secret. Access tokens obtained via POST to auth.weather.mg/oauth/token,\n      valid for approximately 1 hour, delivered as Bearer tokens.\n  - aid: dtn:dtn-point-forecast-api\n    name: DTN Point Forecast API\n    tags:\n      - Agriculture\n      - Aviation\n      - Forecast\n      - Weather\n    image: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/image.png\n    humanURL: https://api.weather.mg/api-detail-pages/forecast-parameter.html\n    baseURL: https://point-forecast.weather.mg\n    properties:\n      - url: https://api.weather.mg/api-detail-pages/forecast-parameter.html\n\
  \        type: Documentation\n      - url: https://api.weather.mg/\n        type: Portal\n    description: >-\n      DTN Point Forecast API delivers high-quality weather forecasts for specified\n      locations. Provides hourly and daily forecast data for agriculture, aviation,\n      shipping, and utilities use cases. Uses the same OAuth2 authentication as the\n      Point Observation API.\n  - aid: dtn:dtn-radar-precipitation-forecast-api\n    name: DTN Radar Precipitation Forecast API\n    tags:\n      - Precipitation\n      - Radar\n      - Short-Term Forecast\n      - Weather\n    image: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/image.png\n    humanURL: https://api.weather.mg/\n    baseURL: https://precipitation-forecast.weather.mg\n    properties:\n      - url: https://api.weather.mg/\n        type: Documentation\n    description: >-\n      DTN Radar Precipitation Forecast API provides short-term precipitation forecasts\n      derived from radar data. Supports\
  \ agricultural, utility, and renewable energy\n      operational planning. Uses OAuth2 authentication with Client ID and Client Secret\n      credentials.\n  - aid: dtn:dtn-commodity-data-api\n    name: DTN Commodity & Market Data API\n    tags:\n      - Agriculture\n      - Commodity Prices\n      - Grain\n      - Livestock\n      - Market Data\n    image: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/image.png\n    humanURL: https://www.dtn.com/resources/api-data-integrations/\n    baseURL: https://api.dtn.com\n    properties:\n      - url: https://www.dtn.com/resources/api-data-integrations/\n        type: Documentation\n    description: >-\n      DTN provides real-time and historical commodity price data, grain and livestock\n      prices, planting condition indices, and market analysis APIs for precision agriculture\n      and commodity trading workflows.\ncommon:\n  - url: https://www.dtn.com/\n    type: Website\n  - url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/openapi/dtn-weather-conditions-openapi.yml\n\
  \    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/json-schema/dtn-weather-observation-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/json-ld/dtn-context.jsonld\n    type: JSONLDContext\n  - url: https://devportal.dtn.com/\n    type: Portal\n  - url: https://www.dtn.com/resources/api-data-integrations/\n    type: Documentation\n  - url: https://api.weather.mg/\n    type: Reference\n  - url: https://www.dtn.com/subscription-agreement-standard-terms-conditions/\n    type: TermsOfService\n  - url: https://www.dtn.com/wp-content/uploads/2020/04/DTN-External-Privacy-Statement.pdf\n    type: PrivacyPolicy\n  - url: https://www.dtn.com/weather/\n    type: GettingStarted\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\nmodified: '2026-04-28'\ndescription: >-\n  The operation intelligence you can rely on to make confident desicions. Empower\n  your business with the\
  \ best data resource possible.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/dtn/refs/heads/main/apis.yml
use_cases: []
---
