---
api_count: 9
apis:
- description: 'Provides access to World of Warcraft game data including achievements, auction house listings, character classes, races, realms, guild data, items, spells, zones, and PvP leaderboards. Requires OAuth '
  name: World of Warcraft Game Data API
  slug: world-of-warcraft-game-data
- description: Provides access to player profile data for World of Warcraft including character summaries, equipment, achievements, collections, mythic keystone profile, and PvP profile data. Requires OAuth 2.0 auth
  name: World of Warcraft Profile API
  slug: world-of-warcraft-profile
- description: Provides game data for World of Warcraft Classic (Era and Seasonal), including classic realm lists, auction house data, character classes, races, and items specific to the classic game versions.
  name: World of Warcraft Classic Game Data API
  slug: world-of-warcraft-classic
- description: Provides access to Diablo III game data including season index and season data, era index and era leaderboards. Requires OAuth 2.0 client credentials flow.
  name: Diablo III Game Data API
  slug: diablo-3-game-data
- description: Provides access to Diablo III community data including character profiles, hero data, item data, follower data, artisan data, and act information. Requires OAuth 2.0 for profile endpoints.
  name: Diablo III Community API
  slug: diablo-3-community
- description: Provides access to Hearthstone card data including card search, card back collections, deck building, and metadata such as card sets, classes, card types, rarities, and keywords. Requires OAuth 2.0 cl
  name: Hearthstone Game Data API
  slug: hearthstone-game-data
- description: Provides access to StarCraft II game data including league data for multiple game modes. Requires OAuth 2.0 client credentials flow.
  name: StarCraft II Game Data API
  slug: starcraft-2-game-data
- description: Provides access to StarCraft II community data including player profile, ladder summaries, grandmaster leaderboards, and static game data for profile, legacy, and ladder resources.
  name: StarCraft II Community API
  slug: starcraft-2-community
- description: Provides OAuth 2.0 authorization services for Battle.net including client credentials flow for game data access and authorization code flow for player profile data. Token endpoint, authorization endpo
  name: Battle.net OAuth API
  slug: battle-net-oauth
capabilities:
- description: ''
  name: Gaming Data
  slug: gaming-data
common:
- title: ''
  type: Portal
  url: https://community.developer.battle.net/
- title: ''
  type: Documentation
  url: https://community.developer.battle.net/documentation
- title: ''
  type: GettingStarted
  url: https://community.developer.battle.net/documentation/guides/getting-started
- title: ''
  type: Authentication
  url: https://community.developer.battle.net/documentation/guides/using-oauth
- title: ''
  type: RateLimits
  url: https://us.forums.blizzard.com/en/blizzard/t/api-access-clients-rate-limits/5602
- title: ''
  type: GitHubOrganization
  url: https://github.com/Blizzard
- title: ''
  type: Support
  url: https://us.forums.blizzard.com/en/blizzard/c/api-discussion
- title: ''
  type: TermsOfService
  url: https://www.blizzard.com/en-us/legal/a2989b50-54f6-43f3-b55c-fa78e0ca3b38/blizzard-developer-api-terms-of-use
- title: Passport.js Battle.net Strategy
  type: SDK
  url: https://github.com/Blizzard/passport-bnet
- title: OmniAuth Battle.net Strategy (Ruby)
  type: SDK
  url: https://github.com/Blizzard/omniauth-bnet
- title: Java OAuth Sample
  type: CodeExamples
  url: https://github.com/Blizzard/java-signature-generator
- title: Node.js OAuth Sample
  type: CodeExamples
  url: https://github.com/Blizzard/node-signature-generator
- title: Ruby OAuth Sample
  type: CodeExamples
  url: https://github.com/Blizzard/ruby-signature-generator
- title: OAuth Client Sample
  type: CodeExamples
  url: https://github.com/Blizzard/oauth-client-sample
- title: ''
  type: SpectralRules
  url: rules/battle-net-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/battle-net-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/gaming-data.yaml
created: '2025-03-01'
description: Battle.net is Blizzard Entertainment's online gaming platform and developer API ecosystem. It provides game data and player profile APIs for World of Warcraft, Diablo III, Hearthstone, and StarCraft II via OAuth 2.0-secured REST endpoints, enabling developers to build applications that access character data, game statistics, leaderboards, card collections, and auction house data.
features:
- description: Supports both client credentials flow for game data and authorization code flow for player profile data access.
  name: OAuth 2.0 Authentication
- description: APIs are available across US, EU, and APAC regions with regional base URLs (us.api.blizzard.com, eu.api.blizzard.com).
  name: Multi-Region Support
- description: Access static and dynamic game data including items, spells, realms, seasons, leaderboards, and card metadata.
  name: Game Data APIs
- description: Access authenticated player data including character profiles, achievements, equipment, and PvP records.
  name: Player Profile APIs
- description: API responses support multiple locales per region, enabling localized game data in multiple languages.
  name: Localization Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Battle.net OAuth strategy for Node.js applications using Passport.js authentication middleware.
  name: Passport.js
- description: Battle.net authentication strategy for Ruby on Rails applications using OmniAuth.
  name: OmniAuth
- description: API mocking and testing platform for Battle.net API contract testing.
  name: Microcks
jsonld:
- class_count: 12
  name: Battle Net Hearthstone Game Data Context
  property_count: 37
  slug: battle-net-hearthstone-game-data-context
layout: provider
modified: '2026-04-21'
name: Battle.net
rules:
- name: Battle.net API Rules
  rule_count: 30
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 15
  slug: battle-net-spectral-rules
skills: []
slug: battle-net
solutions: []
tags:
- Games
- Gaming
- Blizzard
- World Of Warcraft
- Diablo
- Hearthstone
- Starcraft
url: https://raw.githubusercontent.com/api-evangelist/battle-net/refs/heads/main/apis.yml
use_cases:
- description: Build companion applications for WoW, Hearthstone, or Diablo that display character stats, gear scores, and progression.
  name: Game Companion Apps
- description: Monitor World of Warcraft auction house data to track item prices and market trends.
  name: Auction House Trackers
- description: Show StarCraft II, Diablo III season, and WoW PvP leaderboards in custom applications.
  name: Leaderboard Displays
- description: Create Hearthstone deck-building tools using the card data, metadata, and deck APIs.
  name: Deck Builders
- description: Build guild management utilities using WoW guild roster, achievements, and activity data.
  name: Guild Management Tools
---
