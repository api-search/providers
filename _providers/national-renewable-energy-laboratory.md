---
api_count: 5
api_specs:
- filename: national-renewable-energy-laboratory-openapi.yml
  format: yaml
  label: NREL Developer Network
  slug: nrel-developer-network
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/national-renewable-energy-laboratory/refs/heads/main/openapi/national-renewable-energy-laboratory-openapi.yml
apis:
- description: The umbrella developer portal for NREL APIs spanning alternative fuel stations, solar resource and PV modeling, utility rates, building energy use, climate, electricity, transportation, wave, and wind
  name: NREL Developer Network
  slug: nrel-developer-network
- description: Locate alternative fuel stations across the United States with filters for fuel type, location, status, and access.
  name: Alternative Fuel Stations
  slug: alternative-fuel-stations
- description: Estimate the energy production and cost of grid-connected photovoltaic energy systems for any location.
  name: PVWatts
  slug: pvwatts
- description: Average commercial, industrial, and residential utility rates by US location.
  name: Utility Rates
  slug: utility-rates
- description: Average direct normal, global horizontal, and tilt at latitude irradiance for a US location.
  name: Solar Resource Data
  slug: solar-resource-data
common:
- title: ''
  type: Website
  url: https://www.nrel.gov/
- title: ''
  type: Portal
  url: https://developer.nrel.gov/
- title: ''
  type: SignUp
  url: https://developer.nrel.gov/signup/
created: '2025-05-02'
description: The National Renewable Energy Laboratory (NREL) developer network provides a catalog of public APIs that give developers access to renewable energy, alternative fuel, electricity, building, climate, solar, wind, and transportation data and analysis services produced by NREL.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: National Renewable Energy Laboratory
skills: []
slug: national-renewable-energy-laboratory
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: national-renewable-energy-laboratory\nname: National Renewable Energy Laboratory\ndescription: >-\n  The National Renewable Energy Laboratory (NREL) developer network provides a\n  catalog of public APIs that give developers access to renewable energy,\n  alternative fuel, electricity, building, climate, solar, wind, and\n  transportation data and analysis services produced by NREL.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/national-renewable-energy-laboratory/refs/heads/main/apis.yml\ncreated: '2025-05-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Energy\n  - Renewable Energy\n  - Federal Government\n  - Climate\n  - Research\napis:\n  - aid: national-renewable-energy-laboratory:nrel-developer-network\n    name: NREL Developer Network\n    description: >-\n      The umbrella developer portal for NREL\
  \ APIs spanning alternative fuel\n      stations, solar resource and PV modeling, utility rates, building energy\n      use, climate, electricity, transportation, wave, and wind data.\n    humanURL: https://developer.nrel.gov/\n    baseURL: https://developer.nrel.gov/api/\n    tags:\n      - Energy\n      - Renewable Energy\n    properties:\n      - type: Documentation\n        url: https://developer.nrel.gov/docs/\n      - type: SignUp\n        url: https://developer.nrel.gov/signup/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/national-renewable-energy-laboratory/refs/heads/main/openapi/national-renewable-energy-laboratory-openapi.yml\n  - aid: national-renewable-energy-laboratory:alternative-fuel-stations\n    name: Alternative Fuel Stations\n    description: Locate alternative fuel stations across the United States with filters for fuel type, location, status, and access.\n    humanURL: https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/\n\
  \    baseURL: https://developer.nrel.gov/api/alt-fuel-stations/v1/\n    tags:\n      - Transportation\n      - Alternative Fuel\n    properties:\n      - type: Documentation\n        url: https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/\n  - aid: national-renewable-energy-laboratory:pvwatts\n    name: PVWatts\n    description: Estimate the energy production and cost of grid-connected photovoltaic energy systems for any location.\n    humanURL: https://developer.nrel.gov/docs/solar/pvwatts/v8/\n    baseURL: https://developer.nrel.gov/api/pvwatts/v8/\n    tags:\n      - Solar\n      - Modeling\n    properties:\n      - type: Documentation\n        url: https://developer.nrel.gov/docs/solar/pvwatts/v8/\n  - aid: national-renewable-energy-laboratory:utility-rates\n    name: Utility Rates\n    description: Average commercial, industrial, and residential utility rates by US location.\n    humanURL: https://developer.nrel.gov/docs/electricity/utility-rates-v3/\n    baseURL:\
  \ https://developer.nrel.gov/api/utility_rates/v3/\n    tags:\n      - Electricity\n      - Rates\n    properties:\n      - type: Documentation\n        url: https://developer.nrel.gov/docs/electricity/utility-rates-v3/\n  - aid: national-renewable-energy-laboratory:solar-resource-data\n    name: Solar Resource Data\n    description: Average direct normal, global horizontal, and tilt at latitude irradiance for a US location.\n    humanURL: https://developer.nrel.gov/docs/solar/solar-resource-v1/\n    baseURL: https://developer.nrel.gov/api/solar/solar_resource/v1/\n    tags:\n      - Solar\n      - Climate\n    properties:\n      - type: Documentation\n        url: https://developer.nrel.gov/docs/solar/solar-resource-v1/\ncommon:\n  - type: Website\n    url: https://www.nrel.gov/\n  - type: Portal\n    url: https://developer.nrel.gov/\n  - type: SignUp\n    url: https://developer.nrel.gov/signup/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/national-renewable-energy-laboratory/refs/heads/main/apis.yml
tags:
- Energy
- Renewable Energy
- Federal Government
- Climate
- Research
url: https://raw.githubusercontent.com/api-evangelist/national-renewable-energy-laboratory/refs/heads/main/apis.yml
use_cases: []
---
