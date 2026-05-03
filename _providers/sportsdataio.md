---
api_count: 5
api_specs:
- filename: sportsdataio-nfl-openapi.yml
  format: yaml
  label: SportsDataIO NFL API
  slug: sportsdataio-nfl
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nfl-openapi.yml
- filename: sportsdataio-mlb-openapi.yml
  format: yaml
  label: SportsDataIO MLB API
  slug: sportsdataio-mlb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-mlb-openapi.yml
- filename: sportsdataio-nba-openapi.yml
  format: yaml
  label: SportsDataIO NBA API
  slug: sportsdataio-nba
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nba-openapi.yml
- filename: sportsdataio-nhl-openapi.yml
  format: yaml
  label: SportsDataIO NHL API
  slug: sportsdataio-nhl
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nhl-openapi.yml
- filename: sportsdataio-soccer-openapi.yml
  format: yaml
  label: SportsDataIO Soccer API
  slug: sportsdataio-soccer
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-soccer-openapi.yml
apis:
- description: Comprehensive NFL data API providing live scores, team statistics, player stats, fantasy projections, injuries, depth charts, standings, schedules, and betting odds. Covers all 32 teams and all NFL re
  name: SportsDataIO NFL API
  slug: sportsdataio-nfl
- description: Complete MLB data API with live scores, box scores, player statistics, fantasy projections, injuries, lineups, standings, schedules, and odds for all Major League Baseball games. Includes Statcast dat
  name: SportsDataIO MLB API
  slug: sportsdataio-mlb
- description: NBA data API providing live scores, play-by-play, player statistics, fantasy projections, injuries, lineups, standings, and odds. Covers all NBA regular season, playoff, and in-season tournament games
  name: SportsDataIO NBA API
  slug: sportsdataio-nba
- description: NHL data API with live scores, play-by-play, goalie stats, skater statistics, fantasy projections, injuries, line combinations, standings, and odds for all NHL regular season and playoff games.
  name: SportsDataIO NHL API
  slug: sportsdataio-nhl
- description: Soccer data API providing live scores, player statistics, team standings, match schedules, lineups, and odds for major leagues including EPL, MLS, La Liga, Bundesliga, Serie A, Champions League, and m
  name: SportsDataIO Soccer API
  slug: sportsdataio-soccer
capabilities:
- description: Unified sports data capability composing SportsDataIO APIs for multi-sport data access including live scores, statistics, fantasy projections, odds, player news, injuries, and standings across NFL, ML
  name: SportsDataIO Sports Data
  slug: sports-data
common:
- title: ''
  type: Website
  url: https://sportsdata.io/
- title: ''
  type: Portal
  url: https://sportsdata.io/developers
- title: ''
  type: Documentation
  url: https://sportsdata.io/developers
- title: ''
  type: Pricing
  url: https://sportsdata.io/pricing
- title: ''
  type: Login
  url: https://sportsdata.io/login
- title: ''
  type: SignUp
  url: https://sportsdata.io/signup
- title: ''
  type: Support
  url: https://support.sportsdata.io/
- title: ''
  type: SDKs
  url: https://sportsdata.io/developers/integration-tools
- title: ''
  type: OpenAPI
  url: https://sportsdata.io/developers/sports-data-open-api-swagger-files
created: '2025-03-01'
description: SportsDataIO is an award-winning sports data and content provider producing millions of data points across thousands of games annually. The platform offers robust REST APIs, responsive widgets, database downloads, and fantasy sports tools covering 14+ major sports including NFL, MLB, NBA, NHL, Soccer, Golf, NASCAR, MMA/UFC, Tennis, Formula 1, College Football, College Basketball, WNBA, and Olympics. Data includes live scores, statistics, odds feeds, fantasy projections, injuries, lineups, depth charts, standings, and player news.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 39
  name: Sportsdataio Context
  property_count: 4
  slug: sportsdataio-context
layout: provider
modified: '2026-05-02'
name: SportsDataIO
rules:
- name: SportsDataIO API Rules
  rule_count: 9
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 3
  slug: sportsdataio-rules
skills: []
slug: sportsdataio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sportsdataio\nname: SportsDataIO\ndescription: >-\n  SportsDataIO is an award-winning sports data and content provider producing millions\n  of data points across thousands of games annually. The platform offers robust REST APIs,\n  responsive widgets, database downloads, and fantasy sports tools covering 14+ major sports\n  including NFL, MLB, NBA, NHL, Soccer, Golf, NASCAR, MMA/UFC, Tennis, Formula 1, College\n  Football, College Basketball, WNBA, and Olympics. Data includes live scores, statistics,\n  odds feeds, fantasy projections, injuries, lineups, depth charts, standings, and player news.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Sports Data\n  - Statistics\n  - Live Scores\n  - Fantasy Sports\n  - Odds\n  - NFL\n  - NBA\n  - MLB\n  - NHL\n  - Soccer\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: sportsdataio:sportsdataio-nfl\n    name: SportsDataIO NFL API\n    description: >-\n      Comprehensive NFL data API providing live scores, team statistics, player stats,\n      fantasy projections, injuries, depth charts, standings, schedules, and betting odds.\n      Covers all 32 teams and all NFL regular season, preseason, and playoff games with\n      136 endpoints for detailed analysis.\n    humanURL: https://sportsdata.io/developers/api-documentation/nfl\n    baseURL: https://api.sportsdata.io\n    tags:\n      - NFL\n      - Football\n      - Sports Data\n      - Live Scores\n      - Statistics\n      - Fantasy Sports\n    properties:\n      - type: Documentation\n        url: https://sportsdata.io/developers/api-documentation/nfl\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nfl-openapi.yml\n  - aid: sportsdataio:sportsdataio-mlb\n\
  \    name: SportsDataIO MLB API\n    description: >-\n      Complete MLB data API with live scores, box scores, player statistics, fantasy\n      projections, injuries, lineups, standings, schedules, and odds for all Major\n      League Baseball games. Includes Statcast data, pitch-by-pitch data, and\n      real-time game events.\n    humanURL: https://sportsdata.io/developers/api-documentation/mlb\n    baseURL: https://api.sportsdata.io\n    tags:\n      - MLB\n      - Baseball\n      - Sports Data\n      - Live Scores\n      - Statistics\n      - Fantasy Sports\n    properties:\n      - type: Documentation\n        url: https://sportsdata.io/developers/api-documentation/mlb\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-mlb-openapi.yml\n  - aid: sportsdataio:sportsdataio-nba\n    name: SportsDataIO NBA API\n    description: >-\n      NBA data API providing live scores, play-by-play,\
  \ player statistics, fantasy\n      projections, injuries, lineups, standings, and odds. Covers all NBA regular\n      season, playoff, and in-season tournament games with real-time data feeds.\n    humanURL: https://sportsdata.io/developers/api-documentation/nba\n    baseURL: https://api.sportsdata.io\n    tags:\n      - NBA\n      - Basketball\n      - Sports Data\n      - Live Scores\n      - Statistics\n      - Fantasy Sports\n    properties:\n      - type: Documentation\n        url: https://sportsdata.io/developers/api-documentation/nba\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nba-openapi.yml\n  - aid: sportsdataio:sportsdataio-nhl\n    name: SportsDataIO NHL API\n    description: >-\n      NHL data API with live scores, play-by-play, goalie stats, skater statistics,\n      fantasy projections, injuries, line combinations, standings, and odds for all\n      NHL regular season\
  \ and playoff games.\n    humanURL: https://sportsdata.io/developers/api-documentation/nhl\n    baseURL: https://api.sportsdata.io\n    tags:\n      - NHL\n      - Hockey\n      - Sports Data\n      - Live Scores\n      - Statistics\n      - Fantasy Sports\n    properties:\n      - type: Documentation\n        url: https://sportsdata.io/developers/api-documentation/nhl\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nhl-openapi.yml\n  - aid: sportsdataio:sportsdataio-soccer\n    name: SportsDataIO Soccer API\n    description: >-\n      Soccer data API providing live scores, player statistics, team standings, match\n      schedules, lineups, and odds for major leagues including EPL, MLS, La Liga,\n      Bundesliga, Serie A, Champions League, and more.\n    humanURL: https://sportsdata.io/developers/api-documentation/soccer\n    baseURL: https://api.sportsdata.io\n    tags:\n      - Soccer\n\
  \      - Football\n      - EPL\n      - MLS\n      - Champions League\n      - Sports Data\n      - Live Scores\n    properties:\n      - type: Documentation\n        url: https://sportsdata.io/developers/api-documentation/soccer\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-soccer-openapi.yml\ncommon:\n  - type: Website\n    url: https://sportsdata.io/\n  - type: Portal\n    url: https://sportsdata.io/developers\n  - type: Documentation\n    url: https://sportsdata.io/developers\n  - type: Pricing\n    url: https://sportsdata.io/pricing\n  - type: Login\n    url: https://sportsdata.io/login\n  - type: SignUp\n    url: https://sportsdata.io/signup\n  - type: Support\n    url: https://support.sportsdata.io/\n  - type: SDKs\n    url: https://sportsdata.io/developers/integration-tools\n  - type: OpenAPI\n    url: https://sportsdata.io/developers/sports-data-open-api-swagger-files\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/apis.yml
tags:
- Sports Data
- Statistics
- Live Scores
- Fantasy Sports
- Odds
- NFL
- NBA
- MLB
- NHL
- Soccer
url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/apis.yml
use_cases: []
---
