---
api_count: 3
api_specs:
- filename: statorium-football-api-openapi.yml
  format: yaml
  label: Statorium Football API
  slug: football-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/openapi/statorium-football-api-openapi.yml
- filename: statorium-basketball-api-openapi.yml
  format: yaml
  label: Statorium Basketball API
  slug: basketball-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/openapi/statorium-basketball-api-openapi.yml
- filename: statorium-american-football-api-openapi.yml
  format: yaml
  label: Statorium American Football API
  slug: american-football-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/openapi/statorium-american-football-api-openapi.yml
apis:
- description: The Statorium Football API delivers comprehensive football/soccer data including live scores, match results, standings, fixtures, lineups, player and team statistics for over 200 football leagues worl
  name: Statorium Football API
  slug: football-api
- description: The Statorium Basketball API provides live basketball data including NBA live scores, game results, standings, player statistics, and team information delivered in JSON format. The API covers major ba
  name: Statorium Basketball API
  slug: basketball-api
- description: The Statorium American Football API provides NFL data including live game data, scores, schedules, player news, team statistics, and historical records. The API delivers unique daily news feeds linked
  name: Statorium American Football API
  slug: american-football-api
capabilities:
- description: Unified sports data capability combining Statorium's Football, Basketball, and American Football APIs into a single workflow. Enables sports platforms, fantasy sports apps, and media publishers to acc
  name: Statorium Sports Data
  slug: sports-data
common:
- title: ''
  type: Website
  url: https://statorium.com/
- title: ''
  type: Documentation
  url: https://statorium.com/stats-api-documentation
- title: ''
  type: Pricing
  url: https://statorium.com/
- title: ''
  type: JSONSchema
  url: json-schema/statorium-match-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/statorium-team-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/statorium-player-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/statorium-match-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/statorium-team-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/statorium-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/statorium-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/sports-data.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/statorium-vocabulary.yml
created: '2025-03-01'
description: Statorium is a sports data API provider delivering live scores, statistics, schedules, standings, and news across 6+ sports including Soccer, American Football, Basketball, Hockey, Volleyball, and Handball. The API provides JSON-format responses covering over 200 football leagues, NBA, NFL, and other major competitions with full coverage of live data, historical data, player stats, team stats, lineups, and predictions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 37
  name: Statorium Context
  property_count: 0
  slug: statorium-context
layout: provider
modified: '2026-05-02'
name: Statorium
rules:
- name: Statorium API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 4
  slug: statorium-rules
skills: []
slug: statorium
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: statorium\nname: Statorium\ndescription: >-\n  Statorium is a sports data API provider delivering live scores, statistics,\n  schedules, standings, and news across 6+ sports including Soccer, American\n  Football, Basketball, Hockey, Volleyball, and Handball. The API provides\n  JSON-format responses covering over 200 football leagues, NBA, NFL, and\n  other major competitions with full coverage of live data, historical data,\n  player stats, team stats, lineups, and predictions.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sports\n  - Sports Data\n  - Football\n  - Soccer\n  - Basketball\n  - American Football\n  - Live Scores\n  - Statistics\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: statorium:football-api\n    name: Statorium\
  \ Football API\n    description: >-\n      The Statorium Football API delivers comprehensive football/soccer data\n      including live scores, match results, standings, fixtures, lineups,\n      player and team statistics for over 200 football leagues worldwide\n      including the English Premier League, Champions League, World Cup, and\n      Major League Soccer. The API uses JSON format with token-based\n      authentication and supports head-to-head data, translated names, and\n      league logos.\n    humanURL: https://statorium.com/football-api\n    baseURL: https://api.statorium.com/api/v1\n    tags:\n      - Football\n      - Soccer\n      - Live Scores\n      - Sports Data\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://statorium.com/stats-api-documentation\n      - type: OpenAPI\n        url: openapi/statorium-football-api-openapi.yml\n    contact:\n      - FN: Statorium Support\n        url: https://statorium.com/\n  - aid: statorium:basketball-api\n\
  \    name: Statorium Basketball API\n    description: >-\n      The Statorium Basketball API provides live basketball data including NBA\n      live scores, game results, standings, player statistics, and team\n      information delivered in JSON format. The API covers major basketball\n      leagues and competitions with real-time updates.\n    humanURL: https://statorium.com/basketball-api\n    baseURL: https://api.statorium.com/api/v1\n    tags:\n      - Basketball\n      - NBA\n      - Live Scores\n      - Sports Data\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://statorium.com/stats-api-documentation\n      - type: OpenAPI\n        url: openapi/statorium-basketball-api-openapi.yml\n    contact:\n      - FN: Statorium Support\n        url: https://statorium.com/\n  - aid: statorium:american-football-api\n    name: Statorium American Football API\n    description: >-\n      The Statorium American Football API provides NFL data including live\n\
  \      game data, scores, schedules, player news, team statistics, and\n      historical records. The API delivers unique daily news feeds linked\n      to NFL players and teams in JSON format.\n    humanURL: https://statorium.com/american-football-nfl-api\n    baseURL: https://api.statorium.com/api/v1\n    tags:\n      - American Football\n      - NFL\n      - Live Scores\n      - Sports Data\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://statorium.com/stats-api-documentation\n      - type: OpenAPI\n        url: openapi/statorium-american-football-api-openapi.yml\n    contact:\n      - FN: Statorium Support\n        url: https://statorium.com/\ncommon:\n  - type: Website\n    url: https://statorium.com/\n  - type: Documentation\n    url: https://statorium.com/stats-api-documentation\n  - type: Pricing\n    url: https://statorium.com/\n  - type: JSONSchema\n    url: json-schema/statorium-match-schema.json\n  - type: JSONSchema\n    url: json-schema/statorium-team-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/statorium-player-schema.json\n  - type: JSONStructure\n    url: json-structure/statorium-match-structure.json\n  - type: JSONStructure\n    url: json-structure/statorium-team-structure.json\n  - type: JSON-LD\n    url: json-ld/statorium-context.jsonld\n  - type: SpectralRules\n    url: rules/statorium-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/sports-data.yaml\n  - type: Vocabulary\n    url: vocabulary/statorium-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/apis.yml
tags:
- Sports
- Sports Data
- Football
- Soccer
- Basketball
- American Football
- Live Scores
- Statistics
url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/apis.yml
use_cases: []
---
