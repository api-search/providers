---
api_count: 5
api_specs:
- filename: sportradar-sports-data-openapi.yml
  format: yaml
  label: Sportradar Sports Data API
  slug: sports-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportradar/refs/heads/main/openapi/sportradar-sports-data-openapi.yml
apis:
- description: Comprehensive sports data API providing real-time scores, statistics, odds, and content covering 80+ sports, 500+ leagues, and 750,000+ annual events in JSON and XML formats. Supports live score feeds
  name: Sportradar Sports Data API
  slug: sports-data-api
- description: Provides comprehensive NBA data including real-time play-by-play, box scores, standings, team and player statistics, schedules, and injury reports. Covers both regular season and playoffs with live ga
  name: Sportradar NBA API
  slug: nba-api
- description: Delivers detailed NFL data including game summaries, play-by-play, drive charts, team and player statistics, schedules, standings, and depth charts. Supports live feeds and historical season data.
  name: Sportradar NFL API
  slug: nfl-api
- description: Covers 500+ soccer competitions globally, providing live match data, match timelines, team and player statistics, standings, tournament coverage, and detailed competition data for leagues like Premier
  name: Sportradar Soccer API
  slug: soccer-api
- description: Provides pre-match and live odds comparison data from major sportsbooks worldwide, including opening lines, closing lines, and line movement history for sports betting applications and analytics platf
  name: Sportradar Odds API
  slug: odds-api
capabilities:
- description: Unified capability for accessing Sportradar's comprehensive sports data across major leagues and sports. Combines NBA, NFL, and soccer data feeds into a single workflow for sports media platforms, fan
  name: Sportradar Sports Data Intelligence
  slug: sports-data-intelligence
common:
- title: ''
  type: Portal
  url: https://developer.sportradar.com/
- title: ''
  type: Documentation
  url: https://developer.sportradar.com/docs/read/Home
- title: ''
  type: Getting Started
  url: https://developer.sportradar.com/getting-started/docs/get-started
- title: ''
  type: Website
  url: https://sportradar.com/
- title: ''
  type: Blog
  url: https://sportradar.com/blog/
- title: ''
  type: Pricing
  url: https://developer.sportradar.com/getting-started/docs/pricing
- title: ''
  type: Status
  url: https://status.sportradar.com/
- title: ''
  type: Support
  url: https://developer.sportradar.com/docs/read/Home#support
- title: ''
  type: JSONSchema
  url: json-schema/sportradar-sport-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sportradar-competitor-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sportradar-sport-event-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/sportradar-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/sportradar-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/sportradar-vocabulary.yml
created: '2024-12-25'
description: Sportradar is the world's leading sports technology company, providing comprehensive sports data APIs delivering real-time scores, statistics, odds, and content for over 80 sports and 500 leagues worldwide. Their APIs serve media companies, sportsbooks, fantasy sports platforms, and sports technology companies with structured data covering NBA, NFL, MLB, NHL, soccer, tennis, golf, esports, and hundreds of other sports. Sportradar APIs use REST with API key authentication and deliver JSON and XML responses.
features: []
image: ''
integrations: []
jsonld:
- class_count: 42
  name: Sportradar Context
  property_count: 3
  slug: sportradar-context
layout: provider
modified: '2026-05-02'
name: Sportradar
rules:
- name: Sportradar API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 3
    warn: 5
  slug: sportradar-rules
skills: []
slug: sportradar
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sportradar\nname: Sportradar\ndescription: >-\n  Sportradar is the world's leading sports technology company, providing\n  comprehensive sports data APIs delivering real-time scores, statistics, odds,\n  and content for over 80 sports and 500 leagues worldwide. Their APIs serve\n  media companies, sportsbooks, fantasy sports platforms, and sports technology\n  companies with structured data covering NBA, NFL, MLB, NHL, soccer, tennis,\n  golf, esports, and hundreds of other sports. Sportradar APIs use REST with\n  API key authentication and deliver JSON and XML responses.\nurl: https://raw.githubusercontent.com/api-evangelist/sportradar/refs/heads/main/apis.yml\ncreated: '2024-12-25'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Data\n  - Esports\n  - Fantasy Sports\n  - Media\n  - Real-Time\n  - Sports\n  - Sports Data\n  - Statistics\napis:\n  - aid: sportradar:sports-data-api\n    name: Sportradar Sports Data API\n    description: >-\n\
  \      Comprehensive sports data API providing real-time scores, statistics, odds,\n      and content covering 80+ sports, 500+ leagues, and 750,000+ annual events\n      in JSON and XML formats. Supports live score feeds, historical statistics,\n      player and team profiles, schedules, standings, and odds comparison across\n      markets.\n    humanURL: https://developer.sportradar.com/\n    tags:\n      - Data\n      - Real-Time\n      - Sports\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://developer.sportradar.com/docs/read/Home\n      - type: Getting Started\n        url: https://developer.sportradar.com/getting-started/docs/get-started\n      - type: OpenAPI\n        url: openapi/sportradar-sports-data-openapi.yml\n\n  - aid: sportradar:nba-api\n    name: Sportradar NBA API\n    description: >-\n      Provides comprehensive NBA data including real-time play-by-play, box scores,\n      standings, team and player statistics, schedules, and\
  \ injury reports. Covers\n      both regular season and playoffs with live game feeds and historical data.\n    humanURL: https://developer.sportradar.com/docs/read/basketball/NBA_v8\n    tags:\n      - Basketball\n      - NBA\n      - Real-Time\n      - Sports\n    properties:\n      - type: Documentation\n        url: https://developer.sportradar.com/docs/read/basketball/NBA_v8\n\n  - aid: sportradar:nfl-api\n    name: Sportradar NFL API\n    description: >-\n      Delivers detailed NFL data including game summaries, play-by-play, drive\n      charts, team and player statistics, schedules, standings, and depth charts.\n      Supports live feeds and historical season data.\n    humanURL: https://developer.sportradar.com/docs/read/american_football/NFL_v7\n    tags:\n      - American Football\n      - NFL\n      - Real-Time\n      - Sports\n    properties:\n      - type: Documentation\n        url: https://developer.sportradar.com/docs/read/american_football/NFL_v7\n\n  - aid: sportradar:soccer-api\n\
  \    name: Sportradar Soccer API\n    description: >-\n      Covers 500+ soccer competitions globally, providing live match data, match\n      timelines, team and player statistics, standings, tournament coverage,\n      and detailed competition data for leagues like Premier League, La Liga,\n      Bundesliga, Champions League, and more.\n    humanURL: https://developer.sportradar.com/docs/read/soccer/Soccer_v4\n    tags:\n      - Real-Time\n      - Soccer\n      - Sports\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://developer.sportradar.com/docs/read/soccer/Soccer_v4\n\n  - aid: sportradar:odds-api\n    name: Sportradar Odds API\n    description: >-\n      Provides pre-match and live odds comparison data from major sportsbooks\n      worldwide, including opening lines, closing lines, and line movement history\n      for sports betting applications and analytics platforms.\n    humanURL: https://developer.sportradar.com/docs/read/odds_comparison/Odds_Comparison_v2\n\
  \    tags:\n      - Betting\n      - Odds\n      - Sports\n      - Sportsbook\n    properties:\n      - type: Documentation\n        url: https://developer.sportradar.com/docs/read/odds_comparison/Odds_Comparison_v2\n\ncommon:\n  - type: Portal\n    url: https://developer.sportradar.com/\n  - type: Documentation\n    url: https://developer.sportradar.com/docs/read/Home\n  - type: Getting Started\n    url: https://developer.sportradar.com/getting-started/docs/get-started\n  - type: Website\n    url: https://sportradar.com/\n  - type: Blog\n    url: https://sportradar.com/blog/\n  - type: Pricing\n    url: https://developer.sportradar.com/getting-started/docs/pricing\n  - type: Status\n    url: https://status.sportradar.com/\n  - type: Support\n    url: https://developer.sportradar.com/docs/read/Home#support\n  - type: JSONSchema\n    url: json-schema/sportradar-sport-event-schema.json\n  - type: JSONSchema\n    url: json-schema/sportradar-competitor-schema.json\n  - type: JSONStructure\n\
  \    url: json-structure/sportradar-sport-event-structure.json\n  - type: JSON-LD\n    url: json-ld/sportradar-context.jsonld\n  - type: SpectralRules\n    url: rules/sportradar-rules.yml\n  - type: Vocabulary\n    url: vocabulary/sportradar-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sportradar/refs/heads/main/apis.yml
tags:
- Data
- Esports
- Fantasy Sports
- Media
- Real-Time
- Sports
- Sports Data
- Statistics
url: https://raw.githubusercontent.com/api-evangelist/sportradar/refs/heads/main/apis.yml
use_cases: []
---
