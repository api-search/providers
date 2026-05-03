---
api_count: 2
api_specs:
- filename: public-apis-openapi.yml
  format: yaml
  label: Public APIs API
  slug: public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/public-apis/refs/heads/main/openapi/public-apis-openapi.yml
apis:
- description: A collective list of free APIs organized by category including Animals, Finance, Weather, Geocoding, Government, Health, Machine Learning, Sports, and 40+ more categories for developers to discover an
  name: Public APIs Directory
  slug: public-apis-directory
- description: A RESTful API for programmatically accessing the public-apis directory data. Supports CORS and requires no authentication, with all responses served over HTTPS. Endpoints include /entries, /random, /c
  name: Public APIs API
  slug: public-api
common:
- title: ''
  type: Website
  url: https://github.com/public-apis/public-apis
- title: ''
  type: GitHub Organization
  url: https://github.com/public-apis
- title: ''
  type: Contributing Guide
  url: https://github.com/public-apis/public-apis/blob/master/CONTRIBUTING.md
- title: ''
  type: License
  url: https://github.com/public-apis/public-apis/blob/master/LICENSE
created: '2026-03-26'
description: Public APIs is a community-curated collective list of over 1,400 free APIs organized across 50+ categories, maintained by contributors and the team at APILayer. It is one of the most popular open-source projects on GitHub with over 400k stars. A companion REST API (davemachado/public-api) exposes the directory data programmatically over HTTPS with no authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Public APIs
skills: []
slug: public-apis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: public-apis\nname: Public APIs\ndescription: >-\n  Public APIs is a community-curated collective list of over 1,400 free APIs\n  organized across 50+ categories, maintained by contributors and the team at\n  APILayer. It is one of the most popular open-source projects on GitHub with\n  over 400k stars. A companion REST API (davemachado/public-api) exposes the\n  directory data programmatically over HTTPS with no authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Aggregation\n  - API Directory\n  - API Discovery\n  - Free APIs\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/public-apis/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: public-apis:public-apis-directory\n    name: Public APIs Directory\n    description: >-\n      A collective list of free APIs organized by category including Animals,\n\
  \      Finance, Weather, Geocoding, Government, Health, Machine Learning, Sports,\n      and 40+ more categories for developers to discover and integrate into\n      their projects.\n    humanURL: https://github.com/public-apis/public-apis\n    tags:\n      - API Directory\n      - Free APIs\n      - Open Source\n      - REST APIs\n    properties:\n      - type: Documentation\n        url: https://github.com/public-apis/public-apis#index\n      - type: GitHubRepository\n        url: https://github.com/public-apis/public-apis\n  - aid: public-apis:public-api\n    name: Public APIs API\n    description: >-\n      A RESTful API for programmatically accessing the public-apis directory\n      data. Supports CORS and requires no authentication, with all responses\n      served over HTTPS. Endpoints include /entries, /random, /categories, and\n      /health.\n    humanURL: https://github.com/davemachado/public-api\n    baseURL: https://api.publicapis.org\n    tags:\n      - API Directory\n  \
  \    - Free APIs\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://github.com/davemachado/public-api\n      - type: GitHubRepository\n        url: https://github.com/davemachado/public-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/public-apis/refs/heads/main/openapi/public-apis-openapi.yml\ncommon:\n  - type: Website\n    url: https://github.com/public-apis/public-apis\n  - type: GitHub Organization\n    url: https://github.com/public-apis\n  - type: Contributing Guide\n    url: https://github.com/public-apis/public-apis/blob/master/CONTRIBUTING.md\n  - type: License\n    url: https://github.com/public-apis/public-apis/blob/master/LICENSE\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/public-apis/refs/heads/main/apis.yml
tags:
- API Aggregation
- API Directory
- API Discovery
- Free APIs
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/public-apis/refs/heads/main/apis.yml
use_cases: []
---
