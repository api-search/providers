---
api_count: 1
api_specs:
- filename: open-fec-openapi.yml
  format: yaml
  label: OpenFEC API
  slug: openfec-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/open-fec/refs/heads/main/openapi/open-fec-openapi.yml
apis:
- description: RESTful web service supporting full-text and field-specific searches on Federal Election Commission data including candidates, committees, and financial data.
  name: OpenFEC API
  slug: openfec-api
common:
- title: ''
  type: Website
  url: https://www.fec.gov/
- title: ''
  type: Documentation
  url: https://api.open.fec.gov/developers/
created: '2024-03-30'
description: The Federal Election Commission (FEC) API is a RESTful web service supporting full-text and field-specific searches on FEC data. Bulk downloads are available on the current site. Information is tied to the underlying forms by file ID and image ID. Data are updated nightly.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OpenFEC
skills: []
slug: open-fec
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: open-fec\nname: OpenFEC\ndescription: >-\n  The Federal Election Commission (FEC) API is a RESTful web service supporting\n  full-text and field-specific searches on FEC data. Bulk downloads are available\n  on the current site. Information is tied to the underlying forms by file ID and\n  image ID. Data are updated nightly.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Campaign Finance\n  - Elections\n  - FEC\n  - Federal\n  - Government\nurl: https://raw.githubusercontent.com/api-evangelist/open-fec/refs/heads/main/apis.yml\ncreated: '2024-03-30'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: open-fec:openfec-api\n    name: OpenFEC API\n    description: >-\n      RESTful web service supporting full-text and field-specific searches on\n      Federal Election Commission data including candidates, committees, and\n      financial data.\n    humanURL: https://api.open.fec.gov/developers/\n\
  \    baseURL: https://api.open.fec.gov/v1\n    tags:\n      - Campaign Finance\n      - Elections\n      - FEC\n    properties:\n      - type: Documentation\n        url: https://api.open.fec.gov/developers/\n      - type: OpenAPI\n        url: openapi/open-fec-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.fec.gov/\n  - type: Documentation\n    url: https://api.open.fec.gov/developers/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/open-fec/refs/heads/main/apis.yml
tags:
- Campaign Finance
- Elections
- FEC
- Federal
- Government
url: https://raw.githubusercontent.com/api-evangelist/open-fec/refs/heads/main/apis.yml
use_cases: []
---
