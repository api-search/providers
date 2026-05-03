---
api_count: 1
api_specs:
- filename: stats-perform-stats-api-openapi.yml
  format: yaml
  label: STATS API
  slug: stats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stats-perform/refs/heads/main/openapi/stats-perform-stats-api-openapi.yml
apis:
- description: The STATS API from Stats Perform provides a comprehensive REST interface for accessing sports data including live scores, box scores, standings, schedules, player and team statistics, play-by-play dat
  name: STATS API
  slug: stats-api
capabilities:
- description: 'Unified sports analytics capability using the Stats Perform STATS API for accessing live and historical sports data across all major American sports leagues. Enables sports analysts, media platforms, '
  name: Stats Perform Sports Analytics
  slug: sports-analytics
common:
- title: ''
  type: Website
  url: https://developer.stats.com/
- title: ''
  type: Documentation
  url: https://developer.stats.com/docs/get_started
- title: ''
  type: GettingStarted
  url: https://developer.stats.com/docs/get_started
- title: ''
  type: Glossary
  url: https://developer.stats.com/docs/Glossary
- title: ''
  type: InteractiveDocs
  url: https://developer.stats.com/io-docs
- title: ''
  type: JSONSchema
  url: json-schema/stats-perform-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/stats-perform-team-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/stats-perform-event-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/stats-perform-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/stats-perform-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/sports-analytics.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/stats-perform-vocabulary.yml
created: '2025-03-01'
description: Stats Perform is the world's leading sports data and AI-powered sports intelligence company. The STATS API provides access to a vast collection of sports data through a unified REST API, including live sports data, cumulative season data, and historical data for leagues from around the world. Data covers American Football, Baseball, Basketball, Hockey, Soccer, Golf, Tennis, and more with in-depth player and team statistics, editorial coverage, live scores, standings, schedules, and play-by-play data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 42
  name: Stats Perform Context
  property_count: 0
  slug: stats-perform-context
layout: provider
modified: '2026-05-02'
name: Stats Perform
rules:
- name: Stats Perform API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 2
    info: 0
    warn: 3
  slug: stats-perform-rules
skills: []
slug: stats-perform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stats-perform\nname: Stats Perform\ndescription: >-\n  Stats Perform is the world's leading sports data and AI-powered sports\n  intelligence company. The STATS API provides access to a vast collection\n  of sports data through a unified REST API, including live sports data,\n  cumulative season data, and historical data for leagues from around the\n  world. Data covers American Football, Baseball, Basketball, Hockey, Soccer,\n  Golf, Tennis, and more with in-depth player and team statistics, editorial\n  coverage, live scores, standings, schedules, and play-by-play data.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sports\n  - Sports Data\n  - Football\n  - Baseball\n  - Basketball\n  - Hockey\n  - Soccer\n  - Golf\n  - Tennis\n  - Live Scores\n  - Statistics\n  - Sports Analytics\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stats-perform/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: stats-perform:stats-api\n    name: STATS API\n    description: >-\n      The STATS API from Stats Perform provides a comprehensive REST interface\n      for accessing sports data including live scores, box scores, standings,\n      schedules, player and team statistics, play-by-play data, editorial\n      content, and historical records. The API supports sports including\n      American Football (NFL, NCAAF), Baseball (MLB, MiLB), Basketball (NBA,\n      NCAAB), Hockey (NHL), Soccer (MLS, EPL, Champions League), Golf (PGA),\n      and Tennis (ATP, WTA). Authentication requires an API key and secret.\n    humanURL: https://developer.stats.com/\n    baseURL: https://api.stats.com/v1\n    tags:\n      - Sports Data\n      - Live Scores\n      - Statistics\n      - Football\n      - Baseball\n      - Basketball\n      - Hockey\n      - Soccer\n    properties:\n      - type: Documentation\n        url: https://developer.stats.com/docs/get_started\n\
  \      - type: OpenAPI\n        url: openapi/stats-perform-stats-api-openapi.yml\n    contact:\n      - FN: Stats Perform Support\n        email: help@support.statsperform.com\n        url: https://developer.stats.com/\ncommon:\n  - type: Website\n    url: https://developer.stats.com/\n  - type: Documentation\n    url: https://developer.stats.com/docs/get_started\n  - type: GettingStarted\n    url: https://developer.stats.com/docs/get_started\n  - type: Glossary\n    url: https://developer.stats.com/docs/Glossary\n  - type: InteractiveDocs\n    url: https://developer.stats.com/io-docs\n  - type: JSONSchema\n    url: json-schema/stats-perform-event-schema.json\n  - type: JSONSchema\n    url: json-schema/stats-perform-team-schema.json\n  - type: JSONStructure\n    url: json-structure/stats-perform-event-structure.json\n  - type: JSON-LD\n    url: json-ld/stats-perform-context.jsonld\n  - type: SpectralRules\n    url: rules/stats-perform-rules.yml\n  - type: NaftikoCapabilities\n    url:\
  \ capabilities/sports-analytics.yaml\n  - type: Vocabulary\n    url: vocabulary/stats-perform-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stats-perform/refs/heads/main/apis.yml
tags:
- Sports
- Sports Data
- Football
- Baseball
- Basketball
- Hockey
- Soccer
- Golf
- Tennis
- Live Scores
- Statistics
- Sports Analytics
url: https://raw.githubusercontent.com/api-evangelist/stats-perform/refs/heads/main/apis.yml
use_cases: []
---
