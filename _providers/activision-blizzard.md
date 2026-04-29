---
api_count: 1
api_specs:
- filename: activision-blizzard-battle-net.json
  format: json
  label: Battle.net API
  slug: battle-net
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/activision-blizzard/refs/heads/main/openapi/activision-blizzard-battle-net.json
apis:
- description: Game data and profile APIs for World of Warcraft, Diablo III, Hearthstone, StarCraft II, and Battle.net account information. Requires OAuth2 authentication via develop.battle.net.
  name: Battle.net API
  slug: battle-net
capabilities:
- description: Unified game data workflow for accessing World of Warcraft characters, realms, guilds, items, Hearthstone cards, Diablo III profiles, and StarCraft II ladder data. Used by game developers, community a
  name: Activision Blizzard Game Data
  slug: game-data
common:
- title: ''
  type: Website
  url: https://www.activision-blizzard.com
- title: ''
  type: Portal
  url: https://develop.battle.net/
- title: ''
  type: Documentation
  url: https://develop.battle.net/documentation
- title: ''
  type: GettingStarted
  url: https://develop.battle.net/documentation/guides/getting-started
- title: ''
  type: Authentication
  url: https://develop.battle.net/documentation/guides/using-oauth
- title: ''
  type: Pricing
  url: https://develop.battle.net/documentation/guides/getting-started
- title: ''
  type: GitHubOrganization
  url: https://github.com/Blizzard
- title: ''
  type: SpectralRules
  url: rules/activision-blizzard-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/activision-blizzard-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/game-data.yaml
- title: ''
  type: JSONLD
  url: json-ld/activision-blizzard-context.jsonld
created: ''
description: Activision Blizzard is a global video game developer and publisher producing franchises including Call of Duty, World of Warcraft, Diablo, Overwatch, and Candy Crush across console, PC, and mobile platforms.
features: []
image: /assets/icons/activision-blizzard.png
integrations: []
jsonld:
- class_count: 17
  name: Activision Blizzard Context
  property_count: 79
  slug: activision-blizzard-context
layout: provider
modified: '2026-04-19'
name: activision-blizzard
rules:
- name: activision-blizzard API Rules
  rule_count: 23
  severity_counts:
    error: 9
    hint: 0
    info: 2
    warn: 12
  slug: activision-blizzard-spectral-rules
skills: []
slug: activision-blizzard
solutions: []
source_filename: apis.yml
source_yaml: "aid: activision-blizzard\nurl: https://raw.githubusercontent.com/api-evangelist/activision-blizzard/refs/heads/main/apis.yml\nmodified: '2026-04-19'\napis:\n  - aid: activision-blizzard:battle-net\n    name: Battle.net API\n    tags:\n      - Gaming\n      - World Of Warcraft\n      - Hearthstone\n      - Diablo\n      - Starcraft\n      - Battle.net\n    properties:\n      - type: HumanURL\n        url: https://develop.battle.net/\n      - type: BaseURL\n        url: https://us.api.blizzard.com\n      - type: OpenAPI\n        url: openapi/activision-blizzard-battle-net.json\n      - type: JSONSchema\n        url: json-schema/\n      - type: JSONStructure\n        url: json-structure/\n      - type: Examples\n        url: examples/\n    description: >-\n      Game data and profile APIs for World of Warcraft, Diablo III, Hearthstone,\n      StarCraft II, and Battle.net account information. Requires OAuth2 authentication\n      via develop.battle.net.\ncommon:\n  - type: Website\n\
  \    url: https://www.activision-blizzard.com\n  - type: Portal\n    url: https://develop.battle.net/\n  - type: Documentation\n    url: https://develop.battle.net/documentation\n  - type: GettingStarted\n    url: https://develop.battle.net/documentation/guides/getting-started\n  - type: Authentication\n    url: https://develop.battle.net/documentation/guides/using-oauth\n  - type: Pricing\n    url: https://develop.battle.net/documentation/guides/getting-started\n  - type: GitHubOrganization\n    url: https://github.com/Blizzard\n  - type: SpectralRules\n    url: rules/activision-blizzard-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/activision-blizzard-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/game-data.yaml\n  - type: JSONLD\n    url: json-ld/activision-blizzard-context.jsonld\ndescription: >-\n  Activision Blizzard is a global video game developer and publisher producing franchises\n  including Call of Duty, World of Warcraft, Diablo, Overwatch,\
  \ and Candy Crush across\n  console, PC, and mobile platforms.\nfeatures:\n  - name: World Of Warcraft Game Data\n    description: Access WoW character profiles, realm listings, guild data, and item information via the Battle.net API.\n    tags:\n      - World Of Warcraft\n      - Game Data\n  - name: Diablo III Profiles\n    description: Retrieve Diablo III career profiles and hero data for Battle.net accounts.\n    tags:\n      - Diablo\n      - Game Data\n  - name: Hearthstone Cards\n    description: Search and retrieve Hearthstone collectible card data including class, set, and mana cost filters.\n    tags:\n      - Hearthstone\n      - Game Data\n  - name: StarCraft II Profiles\n    description: Access StarCraft II player profiles and ladder data.\n    tags:\n      - Starcraft\n      - Game Data\n  - name: Battle.net OAuth2\n    description: OAuth2 client credentials and authorization code flows for game data and profile access.\n    tags:\n      - Authentication\n      - OAuth2\n\
  \  - name: Regional API Endpoints\n    description: Battle.net APIs are available across US, EU, KR, TW, and CN regions.\n    tags:\n      - Regions\n      - Infrastructure\nuseCases:\n  - name: Community App Development\n    description: Build community tools, addons, leaderboards, and companion apps powered by live game data.\n    tags:\n      - Community\n      - Developer\n  - name: Game Analytics\n    description: Analyze game statistics, player performance, and progression data across Blizzard franchises.\n    tags:\n      - Analytics\n      - Gaming\n  - name: Fan Websites\n    description: Power fan websites and wikis with live character profiles, item databases, and realm status.\n    tags:\n      - Fan Sites\n      - Gaming\n  - name: Discord Bots\n    description: Build Discord bots that surface WoW character lookups, Hearthstone card searches, and Diablo profiles.\n    tags:\n      - Discord\n      - Bots\nintegrations:\n  - name: WoW Community Tools\n    description: Integrate\
  \ with World of Warcraft addon ecosystems and community platforms like Wowhead and Curseforge.\n    tags:\n      - World Of Warcraft\n      - Community\n  - name: Twitch\n    description: Surface game data in Twitch stream overlays and channel bot integrations.\n    tags:\n      - Twitch\n      - Streaming\n  - name: Discord\n    description: Enable Discord server bots to query Blizzard game data for guild and community members.\n    tags:\n      - Discord\n      - Community\nsolutions:\n  - name: Game Data API Access\n    description: Free API access via developer.battle.net for community and non-commercial game data use.\n    tags:\n      - Developer\n      - Free Tier\n  - name: OAuth2 Profile Access\n    description: Authorized user profile access using OAuth2 authorization code flow for personalized data.\n    tags:\n      - OAuth2\n      - Profile\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/activision-blizzard/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/activision-blizzard/refs/heads/main/apis.yml
use_cases: []
---
