---
api_count: 2
api_specs:
- filename: us-army-public-openapi.yml
  format: yaml
  label: US Army Public API
  slug: us-army-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/openapi/us-army-public-openapi.yml
apis:
- description: The US Army Public API provides public access to Army news articles, events, and official announcements. Documented with OpenAPI 3 (OAS3) and a Swagger UI interface at api.army.mil. The API enables ac
  name: US Army Public API
  slug: us-army-public-api
- description: The US Army provides open data resources through data.gov and maintains open source projects through the US Army Research Laboratory GitHub organization. Army data includes geospatial datasets, resear
  name: US Army Open Data
  slug: us-army-open-data
capabilities:
- description: Unified public information capability for the US Army, providing access to Army news articles, press releases, and public events. Used by journalists, researchers, and public information officers to a
  name: US Army Public Information
  slug: army-public-information
common: []
created: '2024-11-21'
description: The US Army is the largest branch of the United States military and is responsible for conducting ground combat operations. Its mission is to defend the nation and support humanitarian, peacekeeping, and training missions worldwide. The Army maintains a public API at api.army.mil providing access to news articles, events, and official content using OpenAPI 3 specification.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Us Army Context
  property_count: 7
  slug: us-army-context
layout: provider
modified: '2026-05-03'
name: US Army
rules:
- name: US Army API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 4
  slug: us-army-public-rules
skills: []
slug: us-army
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-army\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/apis.yml\napis:\n  - aid: us-army:us-army-public-api\n    name: US Army Public API\n    tags:\n      - Army\n      - Federal Government\n      - Military\n      - News\n      - Articles\n      - Public Information\n    humanURL: https://api.army.mil/\n    baseURL: https://api.army.mil/api/v1\n    properties:\n      - url: https://api.army.mil/\n        type: Documentation\n      - url: https://api.army.mil/\n        type: SwaggerUI\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/openapi/us-army-public-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/rules/us-army-public-rules.yml\n        type: SpectralRuleset\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/capabilities/army-public-information.yaml\n        type: NaftikoCapability\n\
  \      - url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/json-schema/us-army-article-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/json-ld/us-army-context.jsonld\n        type: JSONLDContext\n    description: >-\n      The US Army Public API provides public access to Army news articles, events, and official\n      announcements. Documented with OpenAPI 3 (OAS3) and a Swagger UI interface at api.army.mil.\n      The API enables access to Army content including articles, news items, and public events.\n  - aid: us-army:us-army-open-data\n    name: US Army Open Data\n    tags:\n      - Army\n      - Federal Government\n      - Open Data\n      - Military\n    humanURL: https://www.army.mil/\n    properties:\n      - url: https://www.army.mil/\n        type: Documentation\n      - url: https://catalog.data.gov/dataset?publisher=US+Army\n        type: DataGov\n      - url: https://github.com/USArmyResearchLab\n\
  \        type: GitHubOrg\n    description: >-\n      The US Army provides open data resources through data.gov and maintains open source projects\n      through the US Army Research Laboratory GitHub organization. Army data includes geospatial\n      datasets, research publications, and public information resources.\nname: US Army\ntags:\n  - Army\n  - Federal Government\n  - Military\n  - Defense\n  - Open Data\n  - News\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-21'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The US Army is the largest branch of the United States military and is responsible for\n  conducting ground combat operations. Its mission is to defend the nation and support\n  humanitarian, peacekeeping, and training missions worldwide. The Army maintains a public\n  API at api.army.mil providing access to news articles, events, and official content using\n  OpenAPI\
  \ 3 specification.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/apis.yml
tags:
- Army
- Federal Government
- Military
- Defense
- Open Data
- News
url: https://raw.githubusercontent.com/api-evangelist/us-army/refs/heads/main/apis.yml
use_cases: []
---
