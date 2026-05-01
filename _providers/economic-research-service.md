---
api_count: 2
apis:
- description: Access ERS data products in machine-readable formats for analysis or integration into your own applications. Delivered via api.data.gov as REST endpoints. Requires an api.data.gov key.
  name: USDA ERS Data APIs
  slug: ers-data-apis
- description: Integrate ERS map layers into the GIS package of your choice, on their own or mashed up with other geospatial data.
  name: USDA ERS Geospatial APIs
  slug: ers-geospatial-apis
common:
- title: ''
  type: Website
  url: https://www.ers.usda.gov/
- title: ''
  type: Documentation
  url: https://www.ers.usda.gov/developer/
created: '2024-12-25'
description: The Economic Research Service (ERS) is a division of the United States Department of Agriculture (USDA) that conducts economic research and analysis related to agriculture, food, and rural development. ERS provides policymakers, stakeholders, and the public with valuable information and data to help inform decision-making and policy development.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Economic Research Service
skills: []
slug: economic-research-service
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: economic-research-service\nname: Economic Research Service\ndescription: >-\n  The Economic Research Service (ERS) is a division of the United States\n  Department of Agriculture (USDA) that conducts economic research and analysis\n  related to agriculture, food, and rural development. ERS provides\n  policymakers, stakeholders, and the public with valuable information and data\n  to help inform decision-making and policy development.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agriculture\n  - Economics\n  - Federal Government\n  - Research\nurl: https://www.ers.usda.gov/\ncreated: '2024-12-25'\nmodified: '2026-04-28'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: economic-research-service:ers-data-apis\n    name: USDA ERS Data APIs\n    description: >-\n      Access ERS data products in machine-readable formats for analysis or\n      integration into your own applications.\
  \ Delivered via api.data.gov as\n      REST endpoints. Requires an api.data.gov key.\n    humanURL: https://www.ers.usda.gov/developer/data-apis\n    baseURL: https://api.ers.usda.gov\n    tags:\n      - Agriculture\n      - Data\n      - Economics\n    properties:\n      - url: https://www.ers.usda.gov/developer/data-apis\n        type: Documentation\n      - url: https://api.data.gov/signup/\n        type: SignUp\n  - aid: economic-research-service:ers-geospatial-apis\n    name: USDA ERS Geospatial APIs\n    description: >-\n      Integrate ERS map layers into the GIS package of your choice, on their\n      own or mashed up with other geospatial data.\n    humanURL: https://www.ers.usda.gov/developer/geospatial-apis\n    baseURL: https://www.ers.usda.gov\n    tags:\n      - Agriculture\n      - Geospatial\n      - GIS\n    properties:\n      - url: https://www.ers.usda.gov/developer/geospatial-apis\n        type: Documentation\ncommon:\n  - type: Website\n    url: https://www.ers.usda.gov/\n\
  \  - type: Documentation\n    url: https://www.ers.usda.gov/developer/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/economic-research-service/refs/heads/main/apis.yml
tags:
- Agriculture
- Economics
- Federal Government
- Research
url: https://www.ers.usda.gov/
use_cases: []
---
