---
api_count: 6
apis:
- description: The Nest Device Access API (Google Smart Device Management API) provides programmatic control over Nest thermostats, cameras, and doorbells. Supports reading thermostat state, setting target temperatu
  name: Google Nest Device Access API
  slug: nest-device-access
- description: The Ecobee API provides access to ecobee smart thermostats for reading and writing thermostat data, managing schedules, reading sensor data, and implementing custom home automation. Supports OAuth2 au
  name: Ecobee API
  slug: ecobee
- description: The Resideo API (formerly Honeywell Home API) provides access to Honeywell and Resideo smart thermostats and home security systems. Supports reading and controlling thermostat setpoints, modes, schedu
  name: Resideo (Honeywell Home) API
  slug: resideo-honeywell
- description: The Sensibo API provides control over Sensibo Sky and Air devices that add smart functionality to existing mini-split and window AC units. Supports reading AC state, setting temperature and mode, sche
  name: Sensibo API
  slug: sensibo
- description: OpenWeatherMap provides weather data APIs used in HVAC automation to adapt cooling/heating based on outdoor conditions. Offers current weather, forecasts, historical data, and air quality data relevan
  name: OpenWeatherMap API
  slug: openweathermap
- description: 'The Home Assistant REST API provides access to all home automation entities including climate/HVAC entities. Supports reading thermostat state, setting temperature, changing HVAC mode, and triggering '
  name: Home Assistant REST API
  slug: home-assistant
common:
- title: Aircon Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/vocabulary/aircon-vocabulary.yaml
created: '2024-01-15'
description: A curated index of APIs, data sources, and developer resources related to air conditioning, HVAC (Heating, Ventilation, and Air Conditioning), and climate control systems. This topic collection covers smart thermostat APIs, building automation protocols, IoT climate APIs, and environmental data APIs used in residential, commercial, and industrial HVAC applications.
features:
- description: APIs for reading and setting thermostat temperature, mode, and schedule.
  name: Thermostat Control
- description: Switch between heating, cooling, auto, and fan-only modes programmatically.
  name: HVAC Mode Management
- description: Create and manage time-based HVAC schedules and programs.
  name: Schedule Automation
- description: Read temperature, humidity, and occupancy sensor data from smart thermostats.
  name: Sensor Data Access
- description: Track HVAC runtime, energy consumption, and efficiency metrics.
  name: Energy Monitoring
- description: Combine outdoor weather data with HVAC control for predictive conditioning.
  name: Weather Integration
- description: Integrate HVAC control with broader smart home platforms (Google Home, Apple HomeKit, SmartThings).
  name: Smart Home Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with Google Home and Google Assistant for voice control.
  name: Google Home
- description: Integration with Apple HomeKit for iOS smart home control.
  name: Apple HomeKit
- description: Voice control via Amazon Alexa smart home skills.
  name: Amazon Alexa
- description: Open-source home automation platform with broad HVAC device support.
  name: Home Assistant
- description: Automation via IFTTT applets for condition-based HVAC control.
  name: IFTTT
- description: Samsung SmartThings integration for HVAC devices.
  name: SmartThings
jsonld:
- class_count: 6
  name: Aircon Context
  property_count: 22
  slug: aircon-context
layout: provider
modified: '2026-04-19'
name: Aircon
skills: []
slug: aircon
solutions: []
source_filename: apis.yml
source_yaml: "aid: aircon\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/apis.yml\nname: Aircon\ntags:\n- Air Conditioning\n- HVAC\n- Climate Control\n- IoT\n- Smart Home\n- Thermostat\n- Building Automation\n- Energy Management\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  A curated index of APIs, data sources, and developer resources related to air conditioning, HVAC (Heating, Ventilation, and Air Conditioning), and climate control systems. This topic collection covers\n  smart thermostat APIs, building automation protocols, IoT climate APIs, and environmental data APIs used in residential, commercial, and industrial HVAC applications.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: aircon:nest-device-access\n  name: Google Nest Device Access API\n  tags:\n  - Thermostat\n  - Smart Home\n  - HVAC\n  - Google\n  - Nest\n  humanURL: https://developers.home.google.com/nest/device-access\n\
  \  baseURL: https://smartdevicemanagement.googleapis.com/v1\n  description: The Nest Device Access API (Google Smart Device Management API) provides programmatic control over Nest thermostats, cameras, and doorbells. Supports reading thermostat state, setting \n    target temperatures, switching HVAC modes, and managing heating/cooling schedules.\n  properties:\n  - url: https://developers.home.google.com/nest/device-access\n    type: Documentation\n  - url: https://developers.home.google.com/nest/device-access/api\n    type: APIReference\n  - url: https://smartdevicemanagement.googleapis.com/v1/$discovery/rest\n    type: Discovery\n- aid: aircon:ecobee\n  name: Ecobee API\n  tags:\n  - Thermostat\n  - Smart Home\n  - HVAC\n  - Energy Management\n  humanURL: https://www.ecobee.com/home/developer/api/introduction/index.shtml\n  baseURL: https://api.ecobee.com\n  description: The Ecobee API provides access to ecobee smart thermostats for reading and writing thermostat data, managing schedules,\
  \ reading sensor data, and implementing custom home automation. \n    Supports OAuth2 authentication and provides access to thermostat runtime data, alerts, and equipment status.\n  properties:\n  - url: https://www.ecobee.com/home/developer/api/introduction/index.shtml\n    type: Documentation\n  - url: https://www.ecobee.com/home/developer/api/introduction/index.shtml\n    type: APIReference\n- aid: aircon:resideo-honeywell\n  name: Resideo (Honeywell Home) API\n  tags:\n  - Thermostat\n  - Smart Home\n  - HVAC\n  - Honeywell\n  humanURL: https://developer.resideo.com\n  baseURL: https://api.honeywell.com\n  description: The Resideo API (formerly Honeywell Home API) provides access to Honeywell and Resideo smart thermostats and home security systems. Supports reading and controlling thermostat \n    setpoints, modes, schedules, and fan operation. Uses OAuth2 and API key authentication.\n  properties:\n  - url: https://developer.resideo.com\n    type: Documentation\n  - url: https://developer.resideo.com/docs\n\
  \    type: APIReference\n- aid: aircon:sensibo\n  name: Sensibo API\n  tags:\n  - Air Conditioning\n  - Smart Home\n  - IoT\n  - Energy Management\n  humanURL: https://sensibo.github.io\n  baseURL: https://home.sensibo.com/api/v2\n  description: The Sensibo API provides control over Sensibo Sky and Air devices that add smart functionality to existing mini-split and window AC units. Supports reading AC state, setting temperature\n    and mode, scheduling, and accessing historical usage data.\n  properties:\n  - url: https://sensibo.github.io\n    type: Documentation\n  - url: https://sensibo.github.io\n    type: APIReference\n- aid: aircon:openweathermap\n  name: OpenWeatherMap API\n  tags:\n  - Weather\n  - Climate\n  - Environmental Data\n  - IoT\n  humanURL: https://openweathermap.org/api\n  baseURL: https://api.openweathermap.org/data/2.5\n  description: OpenWeatherMap provides weather data APIs used in HVAC automation to adapt cooling/heating based on outdoor conditions. Offers current\
  \ weather, forecasts, historical data, and air \n    quality data relevant to climate control decisions.\n  properties:\n  - url: https://openweathermap.org/api\n    type: Documentation\n  - url: https://openweathermap.org/current\n    type: APIReference\n- aid: aircon:home-assistant\n  name: Home Assistant REST API\n  tags:\n  - Smart Home\n  - HVAC\n  - IoT\n  - Open Source\n  - Automation\n  humanURL: https://developers.home-assistant.io/docs/api/rest/\n  baseURL: http://homeassistant.local:8123/api\n  description: The Home Assistant REST API provides access to all home automation entities including climate/HVAC entities. Supports reading thermostat state, setting temperature, changing HVAC mode, \n    and triggering automations for air conditioning control.\n  properties:\n  - url: https://developers.home-assistant.io/docs/api/rest/\n    type: Documentation\n  - url: https://developers.home-assistant.io/docs/api/rest/\n    type: APIReference\nmaintainers:\n- FN: Kin Lane\n  email:\
  \ kin@apievangelist.com\ncommon:\n- type: Features\n  data:\n  - name: Thermostat Control\n    description: APIs for reading and setting thermostat temperature, mode, and schedule.\n  - name: HVAC Mode Management\n    description: Switch between heating, cooling, auto, and fan-only modes programmatically.\n  - name: Schedule Automation\n    description: Create and manage time-based HVAC schedules and programs.\n  - name: Sensor Data Access\n    description: Read temperature, humidity, and occupancy sensor data from smart thermostats.\n  - name: Energy Monitoring\n    description: Track HVAC runtime, energy consumption, and efficiency metrics.\n  - name: Weather Integration\n    description: Combine outdoor weather data with HVAC control for predictive conditioning.\n  - name: Smart Home Integration\n    description: Integrate HVAC control with broader smart home platforms (Google Home, Apple HomeKit, SmartThings).\n- type: UseCases\n  data:\n  - name: Smart Home Automation\n    description:\
  \ Automate AC/heating based on occupancy, time, and weather conditions.\n  - name: Energy Optimization\n    description: Reduce energy costs by dynamically adjusting HVAC based on occupancy and utility pricing.\n  - name: Building Management\n    description: Commercial HVAC monitoring and control across multiple zones and buildings.\n  - name: Comfort Monitoring\n    description: Track and maintain optimal temperature and humidity levels.\n  - name: Remote Control\n    description: Control air conditioning remotely via mobile apps and API integrations.\n  - name: Predictive Conditioning\n    description: Pre-cool or pre-heat based on weather forecasts and schedules.\n- type: Integrations\n  data:\n  - name: Google Home\n    description: Integration with Google Home and Google Assistant for voice control.\n  - name: Apple HomeKit\n    description: Integration with Apple HomeKit for iOS smart home control.\n  - name: Amazon Alexa\n    description: Voice control via Amazon Alexa smart home\
  \ skills.\n  - name: Home Assistant\n    description: Open-source home automation platform with broad HVAC device support.\n  - name: IFTTT\n    description: Automation via IFTTT applets for condition-based HVAC control.\n  - name: SmartThings\n    description: Samsung SmartThings integration for HVAC devices.\n- url: https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/vocabulary/aircon-vocabulary.yaml\n  type: Vocabulary\n  title: Aircon Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/apis.yml
tags:
- Air Conditioning
- HVAC
- Climate Control
- IoT
- Smart Home
- Thermostat
- Building Automation
- Energy Management
url: https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/apis.yml
use_cases:
- description: Automate AC/heating based on occupancy, time, and weather conditions.
  name: Smart Home Automation
- description: Reduce energy costs by dynamically adjusting HVAC based on occupancy and utility pricing.
  name: Energy Optimization
- description: Commercial HVAC monitoring and control across multiple zones and buildings.
  name: Building Management
- description: Track and maintain optimal temperature and humidity levels.
  name: Comfort Monitoring
- description: Control air conditioning remotely via mobile apps and API integrations.
  name: Remote Control
- description: Pre-cool or pre-heat based on weather forecasts and schedules.
  name: Predictive Conditioning
---
