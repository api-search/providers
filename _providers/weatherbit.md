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
- description: 'This API returns current conditions from our network of sub-hourly reporting weather stations, as well as relevant atmospheric meso-analyses (For example, the RTMA). Every API request will return the '
  name: Weatherbit Current Weather API
  slug: weatherbit-current-weather-api
- description: 'This API returns severe weather alerts issued by local meteorological agencies. Current supported countries include: The USA via NOAA. European Union member nations, the United Kingdom, and Israel via'
  name: Weatherbit Severe Weather Alerts API
  slug: weatherbit-severe-weather-alerts-api
- description: Improve your business applications with accurate forecasts derived from the world's best high resolution global, and regional weather models. These forecasts incorporate corrections for model biases u
  name: Weatherbit Weather Forecast API
  slug: weatherbit-weather-forecast-api
- description: The Historical Weather API allows you to quickly retrieve accurate, high resolution historical weather data for any location in the world. Our curated weather data is backed by over 120,000 weather st
  name: Weatherbit Historical Weather API
  slug: weatherbit-historical-weather-api
- description: Use our service to retrieve derived data specific to the agriculture industry. This API utilizes the state of the art GLDAS re-analysis to provide global coverage at a spatial resolution of 0.25 degre
  name: Weatherbit Ag-Weather API
  slug: weatherbit-ag-weather-api
- description: Enrich your business applications with high quality air quality data derived from the world's most advanced global, and regional air quality models. As well as thousands of air quality monitoring stat
  name: Weatherbit Air Quality API
  slug: weatherbit-air-quality-api
common:
- title: ''
  type: Plans
  url: https://www.weatherbit.io/pricing
- title: ''
  type: FAQs
  url: https://help.weatherbit.io/faq/
- title: ''
  type: Status
  url: https://status.weatherbit.io/
- title: ''
  type: Blog
  url: https://blog.weatherbit.io/
- title: ''
  type: Knowledge
  url: https://help.weatherbit.io/
- title: ''
  type: Sign Up
  url: https://www.weatherbit.io/account/create
- title: ''
  type: Login
  url: https://www.weatherbit.io/account/login
- title: ''
  type: Terms of Service
  url: https://www.weatherbit.io/terms
- title: ''
  type: Privacy Policy
  url: https://www.weatherbit.io/privacy
- title: ''
  type: Contact
  url: https://www.weatherbit.io/contact
created: 2023/11/20
description: Weatherbit is a leading provider of weather data and forecasting services. They specialize in delivering accurate and up-to-date weather information to businesses and individuals around the world. Their services include real-time weather data, historical weather patterns, and advanced forecasting models to help clients make informed decisions based on weather conditions.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2025-01-04'
name: Weatherbit
skills: []
slug: weatherbit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: weatherbit\nurl: >-\n  https://raw.githubusercontent.com/api-search/weather/main/_apis/weatherbit/apis.md\napis:\n  - aid: weatherbit:weatherbit-current-weather-api\n    name: Weatherbit Current Weather API\n    tags: []\n    image: \n      https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: http://api.weatherbit.io\n    humanURL: https://www.weatherbit.io/api/weather-current\n    properties:\n      - url: https://www.weatherbit.io/api/weather-current\n        type: Documentation\n      - url: openapi/weatherbit-current-weather-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      This API returns current conditions from our network of sub-hourly\n      reporting weather stations, as well as relevant atmospheric meso-analyses\n      (For example, the RTMA). Every API request will return the nearest, and\n      most recent observation.\n  - aid: weatherbit:weatherbit-severe-weather-alerts-api\n    name: Weatherbit Severe\
  \ Weather Alerts API\n    tags: []\n    image: \n      https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io\n    humanURL: https://www.weatherbit.io/api/alerts\n    properties:\n      - url: https://www.weatherbit.io/api/alerts\n        type: Documentation\n    description: >-\n      This API returns severe weather alerts issued by local meteorological agencies.\n      Current supported countries include: The USA via NOAA. European Union member\n      nations, the United Kingdom, and Israel via Meteoalarm. As well as weather alerts\n      for Canada via Environment Canada, and China via the China Meteorological Administration.\n  - aid: weatherbit:weatherbit-weather-forecast-api\n    name: Weatherbit Weather Forecast API\n    tags: []\n    image: \n      https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://www.weatherbit.io/api/weather-forecast-api\n\
  \    properties:\n      - url: https://www.weatherbit.io/api/weather-forecast-api\n        type: Documentation\n    description: >-\n      Improve your business applications with accurate forecasts derived from\n      the world's best high resolution global, and regional weather models.\n      These forecasts incorporate corrections for model biases using state of\n      the art machine learning methods. Our temperature forecasts consistently\n      outperform those of all competitors, including the US National Weather\n      Service! View our live forecast verification page to see how our API has\n      performed against the competition over the past 30 days.\n  - aid: weatherbit:weatherbit-historical-weather-api\n    name: Weatherbit Historical Weather API\n    tags: []\n    image: \n      https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.weatherbit.io\n    humanURL: https://www.weatherbit.io/api/historical-weather-api\n    properties:\n\
  \      - url: https://www.weatherbit.io/api/historical-weather-api\n        type: Documentation\n    description: >-\n      The Historical Weather API allows you to quickly retrieve accurate, high\n      resolution historical weather data for any location in the world. Our\n      curated weather data is backed by over 120,000 weather stations as well as\n      high resolution gridded weather datasets such as the ERA-5 re-analysis,\n      and global satellite / doppler radar. Data retrieved from our API is\n      gap-free (minimal missing data) due to its application of advanced machine\n      learning, and statistical backfilling techniques.\n  - aid: weatherbit:weatherbit-ag-weather-api\n    name: Weatherbit Ag-Weather API\n    tags: []\n    image: \n      https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://www.weatherbit.io/api/agweather-api\n    properties:\n      - url: https://www.weatherbit.io/api/agweather-api\n\
  \        type: Documentation\n    description: >-\n      Use our service to retrieve derived data specific to the agriculture\n      industry. This API utilizes the state of the art GLDAS re-analysis to\n      provide global coverage at a spatial resolution of 0.25 degrees.\n  - aid: weatherbit:weatherbit-air-quality-api\n    name: Weatherbit Air Quality API\n    tags: []\n    image: \n      https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://www.weatherbit.io/api/air-quality-api\n    properties:\n      - url: https://www.weatherbit.io/api/air-quality-api\n        type: Documentation\n    description: >-\n      Enrich your business applications with high quality air quality data derived\n      from the world's most advanced global, and regional air quality models. As well\n      as thousands of air quality monitoring stations around the world.\nname: Weatherbit\ntags:\n  - Weather\nimage: \n  https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  common:\n  - url: https://www.weatherbit.io/pricing\n    type: Plans\n  - url: https://www.weatherbit.io/features\n    type: Features\n  - url: https://help.weatherbit.io/faq/\n    type: FAQs\n  - url: https://status.weatherbit.io/\n    type: Status\n  - url: https://blog.weatherbit.io/\n    type: Blog\n  - url: https://help.weatherbit.io/\n    type: Knowledge\n  - url: https://www.weatherbit.io/account/create\n    type: Sign Up\n  - url: https://www.weatherbit.io/account/login\n    type: Login\n  - url: https://www.weatherbit.io/terms\n    type: Terms of Service\n  - url: https://www.weatherbit.io/privacy\n    type: Privacy Policy\n  - url: https://www.weatherbit.io/contact\n    type: Contact\ncreated: 2023/11/20\nmodified: '2025-01-04'\ndescription: >-\n  Weatherbit is a leading provider of weather data and forecasting services. They\n  specialize in delivering accurate and up-to-date weather information to businesses\n  and individuals around the world. Their services include real-time\
  \ weather data,\n  historical weather patterns, and advanced forecasting models to help clients make\n  informed decisions based on weather conditions.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.18'\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/weatherbit/refs/heads/main/apis.yml
tags:
- Weather
url: https://raw.githubusercontent.com/api-search/weather/main/_apis/weatherbit/apis.md
use_cases: []
---
