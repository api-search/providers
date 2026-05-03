---
api_count: 1
api_specs:
- filename: the-odds-api-openapi.yml
  format: yaml
  label: The Odds API
  slug: the-odds-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-odds-api/refs/heads/main/openapi/the-odds-api-openapi.yml
apis:
- description: 'Sports betting API providing current and historical odds from major bookmakers for 100+ sports. Access head-to-head, spreads, totals, and outrights markets. Also provides live scores, event listings, '
  name: The Odds API
  slug: the-odds-api
capabilities:
- description: Comprehensive workflow for sports betting research, odds comparison, and line movement analysis. Combines live odds from multiple bookmakers, real-time scores, event discovery, and historical odds dat
  name: Sports Betting Intelligence
  slug: sports-betting-intelligence
common:
- title: ''
  type: Website
  url: https://the-odds-api.com/
- title: ''
  type: Documentation
  url: https://the-odds-api.com/liveapi/guides/v4/
- title: ''
  type: Sign Up
  url: https://the-odds-api.com/#get-access
- title: ''
  type: GitHub Organization
  url: https://github.com/the-odds-api
- title: ''
  type: SpectralRuleset
  url: rules/the-odds-api-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/sports-betting-intelligence.yaml
- title: ''
  type: JSONSchema
  url: json-schema/the-odds-api-event-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/the-odds-api-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/the-odds-api-vocabulary.yml
created: '2025-02-08'
description: The Odds API provides sports betting odds from over 40 major bookmakers worldwide. Access current and historical odds for head-to-head, spreads, totals, and outrights markets across 100+ sports. Endpoints cover live scores, event listings, participants, and historical odds snapshots dating back to June 2020. Quota is consumed per request based on the number of regions and markets requested. All requests require an API key.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 24
  name: The Odds Api Context
  property_count: 5
  slug: the-odds-api-context
layout: provider
modified: '2026-05-03'
name: The Odds API
rules:
- name: The Odds API API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 6
  slug: the-odds-api-rules
skills: []
slug: the-odds-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-odds-api\nname: The Odds API\ndescription: >-\n  The Odds API provides sports betting odds from over 40 major bookmakers worldwide.\n  Access current and historical odds for head-to-head, spreads, totals, and outrights\n  markets across 100+ sports. Endpoints cover live scores, event listings, participants,\n  and historical odds snapshots dating back to June 2020. Quota is consumed per request\n  based on the number of regions and markets requested. All requests require an API key.\ntype: Contract\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Betting\n  - Odds\n  - Sports\n  - Scores\n  - Historical Data\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-odds-api/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: the-odds-api:the-odds-api\n    name: The Odds API\n    description: >-\n      Sports betting\
  \ API providing current and historical odds from major\n      bookmakers for 100+ sports. Access head-to-head, spreads, totals, and\n      outrights markets. Also provides live scores, event listings, and\n      participant data. Quota: 1 credit per region per market for current odds,\n      10 credits for historical odds.\n    humanURL: https://the-odds-api.com/\n    baseURL: https://api.the-odds-api.com/v4\n    tags:\n      - Betting\n      - Odds\n      - Sports\n      - Scores\n      - Bookmakers\n    properties:\n      - type: Documentation\n        url: https://the-odds-api.com/liveapi/guides/v4/\n      - type: Getting Started\n        url: https://the-odds-api.com/liveapi/guides/v4/\n      - type: Sign Up\n        url: https://the-odds-api.com/#get-access\n      - type: OpenAPI\n        url: openapi/the-odds-api-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://the-odds-api.com/\n  - type: Documentation\n    url: https://the-odds-api.com/liveapi/guides/v4/\n  - type: Sign\
  \ Up\n    url: https://the-odds-api.com/#get-access\n  - type: GitHub Organization\n    url: https://github.com/the-odds-api\n  - type: SpectralRuleset\n    url: rules/the-odds-api-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/sports-betting-intelligence.yaml\n  - type: JSONSchema\n    url: json-schema/the-odds-api-event-schema.json\n  - type: JSONLDContext\n    url: json-ld/the-odds-api-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/the-odds-api-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-odds-api/refs/heads/main/apis.yml
tags:
- Betting
- Odds
- Sports
- Scores
- Historical Data
url: https://raw.githubusercontent.com/api-evangelist/the-odds-api/refs/heads/main/apis.yml
use_cases: []
---
