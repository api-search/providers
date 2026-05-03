---
api_count: 4
api_specs:
- filename: thesports-football-openapi.yml
  format: yaml
  label: TheSports Football API
  slug: football-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thesports/refs/heads/main/openapi/thesports-football-openapi.yml
apis:
- description: Real-time football data feeds covering competitions, teams, players, matches, live scores, lineups, statistics, standings, and match analysis worldwide including major leagues and international tourna
  name: TheSports Football API
  slug: football-api
- description: Real-time basketball data feeds including NBA, EuroLeague, and other major leagues. Covers teams, players, matches, live scores, box scores, and season statistics.
  name: TheSports Basketball API
  slug: basketball-api
- description: Tennis data feeds covering ATP, WTA, and Grand Slam tournaments. Includes player profiles, match results, live scores, rankings, and tournament brackets.
  name: TheSports Tennis API
  slug: tennis-api
- description: Esports data feeds for CS:GO, League of Legends, and other major titles. Covers teams, players, tournaments, matches, live scores, and statistics.
  name: TheSports Esports API
  slug: esports-api
capabilities:
- description: Unified sports data capability for accessing real-time football data including live match tracking, standings, team and player analytics. Used by media platforms, OTT services, and sports analytics ap
  name: TheSports Sports Data
  slug: sports-data
common:
- title: ''
  type: Website
  url: https://www.thesports.com/
- title: ''
  type: Documentation
  url: https://www.thesports.com/docs
- title: ''
  type: SignUp
  url: https://www.thesports.com/register
- title: ''
  type: Pricing
  url: https://www.thesports.com/api
- title: ''
  type: FreeTrial
  url: https://www.thesports.com/api
- title: ''
  type: Support
  url: https://www.thesports.com/
created: '2025-03-01'
description: TheSports provides real-time sports data feeds, live trackers, and widgets covering football, basketball, tennis, esports, and other major sports worldwide. Their API delivers live scores, match statistics, player data, standings, and comprehensive sports analytics for media, broadcasters, OTT platforms, and developers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 27
  name: Thesports Context
  property_count: 0
  slug: thesports-context
layout: provider
modified: '2026-05-03'
name: TheSports
rules:
- name: TheSports API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: thesports-rules
skills: []
slug: thesports
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thesports\nname: TheSports\ndescription: >-\n  TheSports provides real-time sports data feeds, live trackers, and widgets\n  covering football, basketball, tennis, esports, and other major sports\n  worldwide. Their API delivers live scores, match statistics, player data,\n  standings, and comprehensive sports analytics for media, broadcasters, OTT\n  platforms, and developers.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sports\n  - Football\n  - Basketball\n  - Tennis\n  - Esports\n  - Data\n  - Real-Time\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thesports/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: thesports:football-api\n    name: TheSports Football API\n    description: >-\n      Real-time football data feeds covering competitions, teams, players,\n      matches, live scores,\
  \ lineups, statistics, standings, and match analysis\n      worldwide including major leagues and international tournaments.\n    humanURL: https://www.thesports.com/\n    baseURL: https://api.thesports.com/v1\n    tags:\n      - Football\n      - Soccer\n      - Sports\n      - Real-Time\n      - Data\n    properties:\n      - type: Documentation\n        url: https://www.thesports.com/docs\n      - type: Website\n        url: https://www.thesports.com/\n      - type: Pricing\n        url: https://www.thesports.com/api\n      - type: FreeTrial\n        url: https://www.thesports.com/api\n      - type: OpenAPI\n        url: openapi/thesports-football-openapi.yml\n      - type: JSONSchema\n        url: json-schema/thesports-match-schema.json\n      - type: JSONSchema\n        url: json-schema/thesports-team-schema.json\n    contact:\n      - FN: TheSports API Support\n        url: https://www.thesports.com/\n  - aid: thesports:basketball-api\n    name: TheSports Basketball API\n    description:\
  \ >-\n      Real-time basketball data feeds including NBA, EuroLeague, and other\n      major leagues. Covers teams, players, matches, live scores, box scores,\n      and season statistics.\n    humanURL: https://www.thesports.com/\n    baseURL: https://api.thesports.com/v1\n    tags:\n      - Basketball\n      - NBA\n      - Sports\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://www.thesports.com/docs\n  - aid: thesports:tennis-api\n    name: TheSports Tennis API\n    description: >-\n      Tennis data feeds covering ATP, WTA, and Grand Slam tournaments.\n      Includes player profiles, match results, live scores, rankings, and\n      tournament brackets.\n    humanURL: https://www.thesports.com/\n    baseURL: https://api.thesports.com/v1\n    tags:\n      - Tennis\n      - ATP\n      - WTA\n      - Sports\n    properties:\n      - type: Documentation\n        url: https://www.thesports.com/docs\n  - aid: thesports:esports-api\n    name: TheSports\
  \ Esports API\n    description: >-\n      Esports data feeds for CS:GO, League of Legends, and other major titles.\n      Covers teams, players, tournaments, matches, live scores, and statistics.\n    humanURL: https://www.thesports.com/\n    baseURL: https://api.thesports.com/v1\n    tags:\n      - Esports\n      - CS:GO\n      - League of Legends\n      - Gaming\n    properties:\n      - type: Documentation\n        url: https://www.thesports.com/docs\ncommon:\n  - type: Website\n    url: https://www.thesports.com/\n  - type: Documentation\n    url: https://www.thesports.com/docs\n  - type: SignUp\n    url: https://www.thesports.com/register\n  - type: Pricing\n    url: https://www.thesports.com/api\n  - type: FreeTrial\n    url: https://www.thesports.com/api\n  - type: Support\n    url: https://www.thesports.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thesports/refs/heads/main/apis.yml
tags:
- Sports
- Football
- Basketball
- Tennis
- Esports
- Data
- Real-Time
url: https://raw.githubusercontent.com/api-evangelist/thesports/refs/heads/main/apis.yml
use_cases: []
---
