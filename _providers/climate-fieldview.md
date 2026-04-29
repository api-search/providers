---
api_count: 1
apis:
- description: The Climate FieldView Platform API is a partner-oriented REST API for reading and writing field-level agronomic data on behalf of growers who have linked their FieldView account. Endpoints expose fiel
  name: Climate FieldView Platform API
  slug: fieldview-platform-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://climate.com/
- title: ''
  type: Portal
  url: https://dev.fieldview.com/
- title: ''
  type: Documentation
  url: https://dev.fieldview.com/technical-documentation/
- title: ''
  type: Authentication
  url: https://dev.fieldview.com/api-details/
- title: ''
  type: GettingStarted
  url: https://dev.fieldview.com/faq/
- title: ''
  type: TermsOfService
  url: https://climate.com/en-us/legal/terms-of-service.html
- title: ''
  type: PrivacyPolicy
  url: https://climate.com/legal/privacy-policy
- title: ''
  type: GitHubOrg
  url: https://github.com/TheClimateCorporation/api-example
- title: ''
  type: Partners
  url: https://climate.com/partners
- title: ''
  type: OpenAPI
  url: openapi/climate-fieldview-platform-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/climate-fieldview-field-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/climate-fieldview-context.jsonld
- title: ''
  type: Spectral
  url: rules/climate-fieldview-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/climate-fieldview-capabilities.yml
created: '2025-03-05'
description: Climate FieldView is a digital agriculture platform from Bayer (originally developed by The Climate Corporation) that gives growers, agronomists, and agribusiness partners a single view of field-level operations. The platform ingests as-planted, as-applied, and as-harvested data from field equipment, combines it with imagery, weather, and soil layers, and exposes those agronomic datasets through a REST API at api.climate.com. Authentication is via OAuth 2.0 authorization-code grant, and resources include fields, planting and harvest activities, application records, and soil samples.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Climate Fieldview Context
  property_count: 23
  slug: climate-fieldview-context
layout: provider
modified: '2026-04-26'
name: Climate FieldView
rules:
- name: Climate FieldView API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: climate-fieldview-rules
skills: []
slug: climate-fieldview
solutions: []
source_yaml: "aid: climate-fieldview\nname: Climate FieldView\nurl: https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/apis.yml\ncreated: '2025-03-05'\nmodified: '2026-04-26'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nx-type: company\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agriculture\n  - Bayer\n  - Crop Data\n  - Field Boundaries\n  - Harvest\n  - OAuth2\n  - Planting\n  - Precision Ag\ndescription: >-\n  Climate FieldView is a digital agriculture platform from Bayer (originally\n  developed by The Climate Corporation) that gives growers, agronomists, and\n  agribusiness partners a single view of field-level operations. The platform\n  ingests as-planted, as-applied, and as-harvested data from field equipment,\n  combines it with imagery, weather, and soil layers, and exposes those\n  agronomic datasets through a REST API at api.climate.com. Authentication is\n\
  \  via OAuth 2.0 authorization-code grant, and resources include fields,\n  planting and harvest activities, application records, and soil samples.\napis:\n  - aid: climate-fieldview:fieldview-platform-api\n    name: Climate FieldView Platform API\n    tags:\n      - Agriculture\n      - Bayer\n      - Crop Data\n      - Field Boundaries\n      - Harvest\n      - OAuth2\n      - Planting\n      - Precision Ag\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://dev.fieldview.com/\n    baseURL: https://api.climate.com\n    properties:\n      - url: https://dev.fieldview.com/technical-documentation/\n        type: Documentation\n      - url: https://dev.fieldview.com/api-details/\n        type: Authentication\n      - url: https://dev.fieldview.com/faq/\n        type: FAQ\n      - url: https://dev.fieldview.com/technical-documentation/next-versions/\n        type: ChangeLog\n      - url: https://github.com/TheClimateCorporation/api-example\n\
  \        type: SDKs\n      - url: openapi/climate-fieldview-platform-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Climate FieldView Platform API is a partner-oriented REST API for\n      reading and writing field-level agronomic data on behalf of growers\n      who have linked their FieldView account. Endpoints expose fields\n      (with GeoJSON boundaries), planting layers, harvest layers,\n      application activities, and soil sample results, and use OAuth 2.0\n      access tokens passed in the Authorization header. The token endpoint\n      is https://api.climate.com/api/oauth/token; data endpoints live under\n      https://api.climate.com/api/v4 and return JSON with paginated list\n      responses.\ncommon:\n  - type: Website\n    url: https://climate.com/\n  - type: Portal\n    url: https://dev.fieldview.com/\n  - type: Documentation\n    url: https://dev.fieldview.com/technical-documentation/\n  - type: Authentication\n    url: https://dev.fieldview.com/api-details/\n\
  \  - type: GettingStarted\n    url: https://dev.fieldview.com/faq/\n  - type: TermsOfService\n    url: https://climate.com/en-us/legal/terms-of-service.html\n  - type: PrivacyPolicy\n    url: https://climate.com/legal/privacy-policy\n  - type: GitHubOrg\n    url: https://github.com/TheClimateCorporation/api-example\n  - type: Partners\n    url: https://climate.com/partners\n  - type: OpenAPI\n    url: openapi/climate-fieldview-platform-openapi.yml\n  - type: JSONSchema\n    url: json-schema/climate-fieldview-field-schema.json\n  - type: JSONLDContext\n    url: json-ld/climate-fieldview-context.jsonld\n  - type: Spectral\n    url: rules/climate-fieldview-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/climate-fieldview-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/apis.yml
tags:
- Agriculture
- Bayer
- Crop Data
- Field Boundaries
- Harvest
- OAuth2
- Planting
- Precision Ag
url: https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/apis.yml
use_cases: []
---
