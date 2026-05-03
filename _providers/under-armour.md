---
api_count: 1
api_specs:
- filename: mapmyfitness-openapi.yml
  format: yaml
  label: MapMyFitness API
  slug: mapmyfitness-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/under-armour/refs/heads/main/openapi/mapmyfitness-openapi.yml
apis:
- description: The MapMyFitness API (Under Armour Connected Fitness API) provides RESTful access to fitness data including workouts, routes, user profiles, heart rate zones, fitness devices, and webhooks. The platfo
  name: MapMyFitness API
  slug: mapmyfitness-api
capabilities:
- description: Unified capability for Under Armour's Connected Fitness platform. Combines workout tracking, route management, user profiles, and heart rate zones into a single workflow surface for fitness app develo
  name: Under Armour Connected Fitness
  slug: connected-fitness
common:
- title: ''
  type: Website
  url: https://www.under-armour.com
- title: ''
  type: Developer Portal
  url: https://developer.mapmyfitness.com/
- title: ''
  type: Documentation
  url: https://developer.mapmyfitness.com/docs/
- title: ''
  type: Authentication
  url: https://developer.mapmyfitness.com/docs/v71_OAuth_2_Intro/
- title: ''
  type: Terms of Service
  url: https://developer.mapmyfitness.com/Terms_Of_Service/
- title: ''
  type: GitHub Org
  url: https://github.com/underarmour
- title: ''
  type: OpenAPI
  url: openapi/mapmyfitness-openapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/under-armour-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/under-armour-vocabulary.yml
- title: ''
  type: Spectral Rules
  url: rules/under-armour-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/under-armour-workout-schema.json
- title: ''
  type: Capabilities
  url: capabilities/connected-fitness.yaml
created: '2026-03-24'
description: Under Armour is an American company that manufactures footwear, sports, and casual apparel known for its performance products designed for athletes. Under Armour operates a Connected Fitness platform — powered by MapMyFitness — that provides developer APIs for integrating workout tracking, route data, user profiles, heart rate zones, and fitness devices into third-party applications.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Under Armour Context
  property_count: 18
  slug: under-armour-context
layout: provider
modified: '2026-05-03'
name: Under Armour
rules:
- name: Under Armour API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 6
  slug: under-armour-rules
skills: []
slug: under-armour
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: under-armour\nname: Under Armour\ndescription: >-\n  Under Armour is an American company that manufactures footwear, sports, and\n  casual apparel known for its performance products designed for athletes. Under\n  Armour operates a Connected Fitness platform — powered by MapMyFitness — that\n  provides developer APIs for integrating workout tracking, route data, user\n  profiles, heart rate zones, and fitness devices into third-party applications.\nurl: https://raw.githubusercontent.com/api-evangelist/under-armour/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Fitness\n  - Health\n  - Wearables\n  - Connected Fitness\n  - Sports\n  - Fortune 1000\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: under-armour:mapmyfitness-api\n    name: MapMyFitness API\n    tags:\n      - Fitness\n      - Workouts\n      - Routes\n      - Health\n      - Connected\
  \ Fitness\n      - OAuth2\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.ua.com\n    humanURL: https://developer.mapmyfitness.com/\n    properties:\n      - url: https://developer.mapmyfitness.com/docs/\n        type: Documentation\n      - url: https://developer.mapmyfitness.com/docs/v71_OAuth_2_Intro/\n        type: Authentication\n      - url: openapi/mapmyfitness-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MapMyFitness API (Under Armour Connected Fitness API) provides\n      RESTful access to fitness data including workouts, routes, user profiles,\n      heart rate zones, fitness devices, and webhooks. The platform powers\n      MapMyFitness, MapMyRun, MapMyRide, and MapMyWalk and supports over 400\n      partner apps and devices. Authentication uses OAuth 2.0.\ncommon:\n  - type: Website\n    url: https://www.under-armour.com\n  - type: Developer Portal\n    url: https://developer.mapmyfitness.com/\n\
  \  - type: Documentation\n    url: https://developer.mapmyfitness.com/docs/\n  - type: Authentication\n    url: https://developer.mapmyfitness.com/docs/v71_OAuth_2_Intro/\n  - type: Terms of Service\n    url: https://developer.mapmyfitness.com/Terms_Of_Service/\n  - type: GitHub Org\n    url: https://github.com/underarmour\n  - type: OpenAPI\n    url: openapi/mapmyfitness-openapi.yml\n  - type: JSON-LD\n    url: json-ld/under-armour-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/under-armour-vocabulary.yml\n  - type: Spectral Rules\n    url: rules/under-armour-rules.yml\n  - type: JSONSchema\n    url: json-schema/under-armour-workout-schema.json\n  - type: Capabilities\n    url: capabilities/connected-fitness.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/under-armour/refs/heads/main/apis.yml
tags:
- Fitness
- Health
- Wearables
- Connected Fitness
- Sports
- Fortune 1000
url: https://raw.githubusercontent.com/api-evangelist/under-armour/refs/heads/main/apis.yml
use_cases: []
---
