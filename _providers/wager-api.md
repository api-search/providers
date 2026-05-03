---
api_count: 2
api_specs:
- filename: wager-api-openapi.yml
  format: yaml
  label: Wager API - Sports Odds
  slug: wager-api-odds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/openapi/wager-api-openapi.yml
- filename: wager-api-openapi.yml
  format: yaml
  label: Wager API - Fantasy Sports Data
  slug: wager-api-fantasy
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/openapi/wager-api-openapi.yml
apis:
- description: Real-time sports odds for game spreads, moneylines, totals, alternate spreads, alternate totals, half-time odds, winning margins, and player props across major sports including NFL, NCAA, NBA, MLB, NH
  name: Wager API - Sports Odds
  slug: wager-api-odds
- description: Fantasy sports data feed providing player statistics, projections, historical records, injury reports, lineup updates, game results and schedules, and depth charts. Used by fantasy sports applications
  name: Wager API - Fantasy Sports Data
  slug: wager-api-fantasy
capabilities:
- description: Workflow capability for sports betting applications using the Wager API. Combines real-time game odds, player props, futures markets, injury reports, and game schedules in a unified workflow. Designed
  name: Wager API Sports Betting
  slug: sports-betting
common:
- title: ''
  type: Website
  url: https://wagerapi.com/
- title: ''
  type: Contact
  url: https://wagerapi.com/#contact
created: '2025-02-08'
description: Wager API is a modern sports betting data platform that enables developers to build sports betting applications, bots, and predictive models with a single API. The platform provides real-time sports odds including spreads, moneylines, totals, player props, and futures markets across NFL, NCAA, NBA, MLB, NHL, soccer, tennis, and golf. Wager API also delivers player statistics, projections, fantasy data, injury reports, lineup updates, game schedules, and depth charts, making it a comprehensive data source for sports betting and fantasy sports applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 34
  name: Wager Api Context
  property_count: 4
  slug: wager-api-context
layout: provider
modified: '2026-05-03'
name: Wager API
rules:
- name: Wager API API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: wager-api-rules
skills: []
slug: wager-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wager-api\nname: Wager API\ndescription: >-\n  Wager API is a modern sports betting data platform that enables developers to build\n  sports betting applications, bots, and predictive models with a single API. The\n  platform provides real-time sports odds including spreads, moneylines, totals, player\n  props, and futures markets across NFL, NCAA, NBA, MLB, NHL, soccer, tennis, and golf.\n  Wager API also delivers player statistics, projections, fantasy data, injury reports,\n  lineup updates, game schedules, and depth charts, making it a comprehensive data\n  source for sports betting and fantasy sports applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sports Betting\n  - Sports Odds\n  - Fantasy Sports\n  - Sports Data\n  - NFL\n  - NBA\n  - MLB\n  - NHL\n  - NCAA\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: wager-api:wager-api-odds\n    name: Wager API - Sports Odds\n    description: >-\n      Real-time sports odds for game spreads, moneylines, totals, alternate spreads,\n      alternate totals, half-time odds, winning margins, and player props across\n      major sports including NFL, NCAA, NBA, MLB, NHL, soccer, tennis, and golf.\n      Supports thousands of futures markets including Super Bowl, NCAA Playoffs,\n      NBA Finals, Stanley Cup, Premier League, and major tennis tournaments.\n    humanURL: https://wagerapi.com/\n    baseURL: https://api.wagerapi.com\n    tags:\n      - Sports Odds\n      - Sports Betting\n      - NFL\n      - NBA\n      - MLB\n      - NHL\n      - Soccer\n      - Tennis\n      - Golf\n    properties:\n      - type: Documentation\n        url: https://wagerapi.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/openapi/wager-api-openapi.yml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/json-schema/wager-api-game-odds-schema.json\n  - aid: wager-api:wager-api-fantasy\n    name: Wager API - Fantasy Sports Data\n    description: >-\n      Fantasy sports data feed providing player statistics, projections, historical\n      records, injury reports, lineup updates, game results and schedules, and depth\n      charts. Used by fantasy sports applications, daily fantasy platforms, and\n      sports analytics models to access comprehensive player and team data.\n    humanURL: https://wagerapi.com/\n    baseURL: https://api.wagerapi.com\n    tags:\n      - Fantasy Sports\n      - Sports Data\n      - Player Statistics\n      - Injury Reports\n    properties:\n      - type: Documentation\n        url: https://wagerapi.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/openapi/wager-api-openapi.yml\n\
  common:\n  - type: Website\n    url: https://wagerapi.com/\n  - type: Contact\n    url: https://wagerapi.com/#contact\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/apis.yml
tags:
- Sports Betting
- Sports Odds
- Fantasy Sports
- Sports Data
- NFL
- NBA
- MLB
- NHL
- NCAA
url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/apis.yml
use_cases: []
---
