---
api_count: 1
api_specs:
- filename: fvapgov-xml-api-openapi.yml
  format: yaml
  label: FVAP.gov XML API
  slug: fvapgov-xml-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fvapgov/refs/heads/main/openapi/fvapgov-xml-api-openapi.yml
apis:
- description: 'Published XML feeds providing voter information by U.S. state and territory: important info, deadline dates, ballot rules, election offices, and a combined eVAG document.'
  name: FVAP.gov XML API
  slug: fvapgov-xml-api
common:
- title: ''
  type: Website
  url: https://www.fvap.gov/
- title: ''
  type: Documentation
  url: https://www.fvap.gov/xml-api
- title: ''
  type: JSONSchema
  url: json-schema/fvapgov-evag-schema.json
created: '2024-03-30'
description: Federal Voting Assistance Program (FVAP) publishes XML feeds of voter information by U.S. state and territory, including important info, deadline dates, ballot rules, and election offices, plus a combined electronic Voting Assistance Guide (eVAG).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: FVAP.gov
skills: []
slug: fvapgov
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fvapgov\nname: FVAP.gov\ndescription: >-\n  Federal Voting Assistance Program (FVAP) publishes XML feeds of voter\n  information by U.S. state and territory, including important info, deadline\n  dates, ballot rules, and election offices, plus a combined electronic Voting\n  Assistance Guide (eVAG).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-03-30'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - Government\n  - Voting\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fvapgov/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: fvapgov:fvapgov-xml-api\n    name: FVAP.gov XML API\n    description: >-\n      Published XML feeds providing voter information by U.S. state and\n      territory: important info, deadline dates, ballot rules, election\n      offices, and a combined eVAG document.\n    humanURL: https://www.fvap.gov/xml-api\n    baseURL: https://www.fvap.gov\n\
  \    tags:\n      - Elections\n      - Government\n      - Voting\n    properties:\n      - type: Documentation\n        url: https://www.fvap.gov/xml-api\n      - type: XSD\n        url: https://www.fvap.gov/xml-api/api-schema.xsd\n      - type: OpenAPI\n        url: openapi/fvapgov-xml-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.fvap.gov/\n  - type: Documentation\n    url: https://www.fvap.gov/xml-api\n  - type: JSONSchema\n    url: json-schema/fvapgov-evag-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fvapgov/refs/heads/main/apis.yml
tags:
- Government
- Voting
url: https://raw.githubusercontent.com/api-evangelist/fvapgov/refs/heads/main/apis.yml
use_cases: []
---
