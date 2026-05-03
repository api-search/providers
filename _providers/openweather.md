---
api_count: 2
api_specs:
- filename: openweather-openapi.yml
  format: yaml
  label: OpenWeather One Call API
  slug: openweather-one-call-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openweather/refs/heads/main/openapi/openweather-openapi.yml
apis:
- description: The One Call API provides current weather, minute-by-minute forecast for one hour, hourly forecast for 48 hours, daily forecast for 8 days, and government weather alerts for any geographic coordinates
  name: OpenWeather One Call API
  slug: openweather-one-call-api
- description: The Air Pollution API provides current, forecast, and historical air pollution data for any coordinates on the globe. It returns the basic Air Quality Index along with concentrations of CO, NO, NO2, O
  name: OpenWeather Air Pollution API
  slug: openweather-air-pollution-api
common:
- title: ''
  type: Website
  url: https://openweathermap.org/
- title: ''
  type: API Portal
  url: https://openweathermap.org/api
- title: ''
  type: Documentation
  url: https://openweathermap.org/technology
- title: ''
  type: Pricing
  url: https://openweathermap.org/price
- title: ''
  type: SignUp
  url: https://home.openweathermap.org/users/sign_up
- title: ''
  type: Blog
  url: https://openweather.co.uk/blog
- title: ''
  type: FAQ
  url: https://openweathermap.org/faq
- title: ''
  type: Support
  url: https://openweathermap.org/contact-us
- title: ''
  type: Privacy
  url: https://openweather.co.uk/privacy-policy
- title: ''
  type: Terms of Service
  url: https://openweather.co.uk/terms
created: '2024-11-07'
description: OpenWeather is a data platform that provides accurate and reliable weather information to individuals, businesses, and organizations around the world. They gather real-time data from a network of sensors, satellites, and weather stations to deliver comprehensive weather forecasts, historical weather data, and climate information.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OpenWeather
skills: []
slug: openweather
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openweather\nname: OpenWeather\ndescription: >-\n  OpenWeather is a data platform that provides accurate and reliable weather\n  information to individuals, businesses, and organizations around the world.\n  They gather real-time data from a network of sensors, satellites, and weather\n  stations to deliver comprehensive weather forecasts, historical weather data,\n  and climate information.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Air Pollution\n  - Air Quality\n  - Climate\n  - Forecasting\n  - Weather\ncreated: '2024-11-07'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openweather/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: openweather:openweather-one-call-api\n    name: OpenWeather One Call API\n    description: >-\n      The One Call API provides current weather, minute-by-minute forecast for\n\
  \      one hour, hourly forecast for 48 hours, daily forecast for 8 days, and\n      government weather alerts for any geographic coordinates.\n    humanURL: https://openweathermap.org/api/one-call-3\n    tags:\n      - Climate\n      - Forecasting\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://openweathermap.org/api/one-call-3\n      - type: OpenAPI\n        url: openapi/openweather-openapi.yml\n      - type: Pricing\n        url: https://openweathermap.org/price\n      - type: SignUp\n        url: https://home.openweathermap.org/users/sign_up\n  - aid: openweather:openweather-air-pollution-api\n    name: OpenWeather Air Pollution API\n    description: >-\n      The Air Pollution API provides current, forecast, and historical air\n      pollution data for any coordinates on the globe. It returns the basic Air\n      Quality Index along with concentrations of CO, NO, NO2, O3, SO2, NH3,\n      PM2.5, and PM10 pollutants.\n    humanURL: https://openweathermap.org/api/air-pollution\n\
  \    tags:\n      - Air Pollution\n      - Air Quality\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://openweathermap.org/api/air-pollution\n      - type: Pricing\n        url: https://openweathermap.org/price\n      - type: SignUp\n        url: https://home.openweathermap.org/users/sign_up\ncommon:\n  - url: https://openweathermap.org/\n    name: OpenWeather\n    type: Website\n    description: Official OpenWeather website.\n  - url: https://openweathermap.org/api\n    name: API Catalog\n    type: API Portal\n    description: Catalog of all OpenWeather APIs and data products.\n  - url: https://openweathermap.org/technology\n    name: Technology\n    type: Documentation\n    description: Overview of OpenWeather data sources and processing technology.\n  - url: https://openweathermap.org/price\n    name: Pricing\n    type: Pricing\n    description: OpenWeather subscription tiers and pricing.\n  - url: https://home.openweathermap.org/users/sign_up\n \
  \   name: Sign Up\n    type: SignUp\n    description: Create an OpenWeather account and obtain an API key.\n  - url: https://openweather.co.uk/blog\n    name: Blog\n    type: Blog\n    description: OpenWeather blog with product news and weather data insights.\n  - url: https://openweathermap.org/faq\n    name: FAQ\n    type: FAQ\n    description: Frequently asked questions about OpenWeather APIs and data.\n  - url: https://openweathermap.org/contact-us\n    name: Support\n    type: Support\n    description: Contact and support resources for OpenWeather customers.\n  - url: https://openweather.co.uk/privacy-policy\n    name: Privacy\n    type: Privacy\n    description: OpenWeather privacy policy.\n  - url: https://openweather.co.uk/terms\n    name: Terms of Service\n    type: Terms of Service\n    description: OpenWeather terms of service.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openweather/refs/heads/main/apis.yml
tags:
- Air Pollution
- Air Quality
- Climate
- Forecasting
- Weather
url: https://raw.githubusercontent.com/api-evangelist/openweather/refs/heads/main/apis.yml
use_cases: []
---
