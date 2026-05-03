---
api_count: 6
api_specs:
- filename: riot-games-league-of-legends-openapi.yml
  format: yaml
  label: League of Legends API
  slug: league-of-legends-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/openapi/riot-games-league-of-legends-openapi.yml
apis:
- description: 'API for accessing League of Legends game data including champion mastery, clash tournaments, ranked league standings, match history, live spectator data, summoner profiles, and tournament management. '
  name: League of Legends API
  slug: league-of-legends-api
- description: API for accessing VALORANT game data including match history, ranked standings, content catalog, and status information. Covers both PC and console platforms.
  name: VALORANT API
  slug: valorant-api
- description: API for accessing Teamfight Tactics game data including match history, ranked standings, summoner profiles, and live spectator data for the auto battler game mode.
  name: Teamfight Tactics API
  slug: teamfight-tactics-api
- description: API for accessing Legends of Runeterra game data including player decks, inventory, match history, and ranked standings. Requires Riot Sign-On (RSO) authentication for player-specific data.
  name: Legends of Runeterra API
  slug: legends-of-runeterra-api
- description: Cross-game account API for resolving Riot IDs (gameName + tagLine) to PUUIDs used across all Riot Games APIs. Supports account linking through Riot Sign-On (RSO) OAuth 2.0 authentication.
  name: Riot Account API
  slug: account-api
- description: Static data and asset delivery service for Riot Games. Provides localized game data for champions, items, summoner spells, runes, profile icons, and maps in JSON format. Available in 28+ languages. Up
  name: Riot Data Dragon
  slug: data-dragon
capabilities:
- description: Unified capability for Riot Games game data analytics across League of Legends. Enables player profile lookup, match history analysis, ranked standing tracking, champion mastery insights, and live gam
  name: Riot Games Game Data Analytics
  slug: game-data-analytics
common:
- title: ''
  type: Developer
  url: https://developer.riotgames.com/
- title: ''
  type: Documentation
  url: https://developer.riotgames.com/apis
- title: ''
  type: Authentication
  url: https://developer.riotgames.com/docs/portal
- title: ''
  type: RateLimiting
  url: https://developer.riotgames.com/docs/portal
- title: ''
  type: GithubOrg
  url: https://github.com/RiotGames
- title: ''
  type: SignUp
  url: https://developer.riotgames.com/
- title: ''
  type: TermsOfService
  url: https://developer.riotgames.com/policies/general
- title: ''
  type: PrivacyPolicy
  url: https://www.riotgames.com/en/privacy-notice
- title: ''
  type: Website
  url: https://www.riotgames.com
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/rules/riot-games-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/capabilities/game-data-analytics.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-schema/riot-games-summoner-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-schema/riot-games-match-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-ld/riot-games-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/vocabulary/riot-games-vocabulary.yml
created: '2025-02-08'
description: Riot Games provides a comprehensive developer platform for accessing game data across League of Legends, VALORANT, Teamfight Tactics, Legends of Runeterra, and other titles. The Riot Developer Portal offers REST APIs for match history, ranked standings, champion mastery, live spectator data, tournament management, and player account data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 48
  name: Riot Games Context
  property_count: 0
  slug: riot-games-context
layout: provider
modified: '2026-05-02'
name: Riot Games
rules:
- name: Riot Games API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: riot-games-rules
skills: []
slug: riot-games
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: riot-games\nname: Riot Games\ndescription: >-\n  Riot Games provides a comprehensive developer platform for accessing game\n  data across League of Legends, VALORANT, Teamfight Tactics, Legends of\n  Runeterra, and other titles. The Riot Developer Portal offers REST APIs for\n  match history, ranked standings, champion mastery, live spectator data,\n  tournament management, and player account data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Esports\n  - Gaming\n  - League of Legends\n  - Legends of Runeterra\n  - Teamfight Tactics\n  - VALORANT\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/apis.yml\ncreated: '2025-02-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: riot-games:league-of-legends-api\n    name: League of Legends API\n    description: >-\n      API for accessing League of Legends game data including champion mastery,\n      clash\
  \ tournaments, ranked league standings, match history, live spectator\n      data, summoner profiles, and tournament management. All APIs are\n      currently version 4 or 5.\n    humanURL: https://developer.riotgames.com/apis\n    baseURL: https://na1.api.riotgames.com\n    tags:\n      - Champion Mastery\n      - Clash\n      - League of Legends\n      - Match History\n      - Ranked\n      - Summoner\n      - Tournaments\n    properties:\n      - type: Documentation\n        url: https://developer.riotgames.com/apis\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/openapi/riot-games-league-of-legends-openapi.yml\n  - aid: riot-games:valorant-api\n    name: VALORANT API\n    description: >-\n      API for accessing VALORANT game data including match history, ranked\n      standings, content catalog, and status information. Covers both PC\n      and console platforms.\n    humanURL: https://developer.riotgames.com/apis\n\
  \    baseURL: https://na.api.riotgames.com\n    tags:\n      - Console\n      - Match History\n      - Ranked\n      - VALORANT\n    properties:\n      - type: Documentation\n        url: https://developer.riotgames.com/docs/valorant\n  - aid: riot-games:teamfight-tactics-api\n    name: Teamfight Tactics API\n    description: >-\n      API for accessing Teamfight Tactics game data including match history,\n      ranked standings, summoner profiles, and live spectator data for the\n      auto battler game mode.\n    humanURL: https://developer.riotgames.com/apis\n    baseURL: https://na1.api.riotgames.com\n    tags:\n      - Match History\n      - Ranked\n      - Summoner\n      - Teamfight Tactics\n    properties:\n      - type: Documentation\n        url: https://developer.riotgames.com/apis\n  - aid: riot-games:legends-of-runeterra-api\n    name: Legends of Runeterra API\n    description: >-\n      API for accessing Legends of Runeterra game data including player decks,\n      inventory,\
  \ match history, and ranked standings. Requires Riot Sign-On\n      (RSO) authentication for player-specific data.\n    humanURL: https://developer.riotgames.com/apis\n    baseURL: https://americas.api.riotgames.com\n    tags:\n      - Decks\n      - Legends of Runeterra\n      - Match History\n      - Ranked\n    properties:\n      - type: Documentation\n        url: https://developer.riotgames.com/docs/lor\n  - aid: riot-games:account-api\n    name: Riot Account API\n    description: >-\n      Cross-game account API for resolving Riot IDs (gameName + tagLine) to\n      PUUIDs used across all Riot Games APIs. Supports account linking through\n      Riot Sign-On (RSO) OAuth 2.0 authentication.\n    humanURL: https://developer.riotgames.com/apis\n    baseURL: https://americas.api.riotgames.com\n    tags:\n      - Account\n      - Authentication\n      - Identity\n      - PUUID\n    properties:\n      - type: Documentation\n        url: https://developer.riotgames.com/apis\n  - aid: riot-games:data-dragon\n\
  \    name: Riot Data Dragon\n    description: >-\n      Static data and asset delivery service for Riot Games. Provides\n      localized game data for champions, items, summoner spells, runes,\n      profile icons, and maps in JSON format. Available in 28+ languages.\n      Updated with each game patch.\n    humanURL: https://developer.riotgames.com/docs/lol\n    baseURL: https://ddragon.leagueoflegends.com/cdn\n    tags:\n      - Champions\n      - Data Dragon\n      - Items\n      - Static Data\n    properties:\n      - type: Documentation\n        url: https://developer.riotgames.com/docs/lol\ncommon:\n  - type: Developer\n    url: https://developer.riotgames.com/\n  - type: Documentation\n    url: https://developer.riotgames.com/apis\n  - type: Authentication\n    url: https://developer.riotgames.com/docs/portal\n  - type: RateLimiting\n    url: https://developer.riotgames.com/docs/portal\n  - type: GithubOrg\n    url: https://github.com/RiotGames\n  - type: SignUp\n    url: https://developer.riotgames.com/\n\
  \  - type: TermsOfService\n    url: https://developer.riotgames.com/policies/general\n  - type: PrivacyPolicy\n    url: https://www.riotgames.com/en/privacy-notice\n  - type: Website\n    url: https://www.riotgames.com\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/rules/riot-games-rules.yml\n  - type: NaftikoCapabilities\n    url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/capabilities/game-data-analytics.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-schema/riot-games-summoner-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-schema/riot-games-match-schema.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-ld/riot-games-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/vocabulary/riot-games-vocabulary.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/apis.yml
tags:
- Esports
- Gaming
- League of Legends
- Legends of Runeterra
- Teamfight Tactics
- VALORANT
url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/apis.yml
use_cases: []
---
