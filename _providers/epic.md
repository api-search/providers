---
api_count: 10
apis:
- description: 'Epic Account Services (EAS) provides authentication and identity for players using Epic Games accounts. Supports OAuth 2.0 authorization code, device, and exchange code flows, account info retrieval, '
  name: Epic Account Services API
  slug: epic-account-services
- description: The EOS Achievements API enables developers to define, unlock, and query player achievements across platforms. Supports definitions, player progress, and unlocking via the EOS SDK or Web API.
  name: Epic Online Services Achievements API
  slug: eos-achievements
- description: The EOS Leaderboards API provides global and per-friend leaderboards backed by player stats. Developers configure leaderboards in the developer portal and query rankings via the EOS SDK or Web API.
  name: Epic Online Services Leaderboards API
  slug: eos-leaderboards
- description: The EOS Stats API tracks player statistics over time, providing the data source that powers leaderboards and achievements. Supports ingest, increment, and query operations on stat values.
  name: Epic Online Services Stats API
  slug: eos-stats
- description: The EOS Friends API exposes a player's Epic Games friends list, allowing games to surface social presence, invitations, and party formation across platforms.
  name: Epic Online Services Friends API
  slug: eos-friends
- description: The EOS Ecom (Ecommerce) Interface API exposes the player's Epic Games Store entitlements, ownership, catalog offers, and checkout flows. Used by titles published on the Epic Games Store to verify pur
  name: Epic Online Services Ecom API
  slug: eos-ecom
- description: The EOS Lobby and Sessions APIs provide matchmaking primitives for multiplayer games, including lobby creation, joining, attribute filtering, and dedicated session management.
  name: Epic Online Services Lobby and Sessions API
  slug: eos-lobby-sessions
- description: The EOS Player Data Storage and Title Storage APIs persist per-player save data and shared title-level configuration in the cloud, with cross-platform availability and versioning.
  name: Epic Online Services Player Data Storage API
  slug: eos-player-data-storage
- description: Easy Anti-Cheat (EAC) integrated into Epic Online Services provides kernel and user-mode anti-cheat protections, server-side validation, and reporting tooling for cross-platform multiplayer titles.
  name: Epic Online Services Anti-Cheat API
  slug: eos-anti-cheat
- description: The EOS Voice Interface delivers in-game voice chat using Vivox backend infrastructure, with positional audio, room management, and moderation controls across platforms.
  name: Epic Online Services Voice API
  slug: eos-voice
common:
- title: ''
  type: Website
  url: https://www.epicgames.com/
- title: ''
  type: Portal
  url: https://dev.epicgames.com/portal/
- title: ''
  type: Documentation
  url: https://dev.epicgames.com/docs/
- title: ''
  type: GettingStarted
  url: https://dev.epicgames.com/docs/epic-online-services/eos-get-started
- title: ''
  type: Authentication
  url: https://dev.epicgames.com/docs/epic-account-services/auth/auth-interface
- title: ''
  type: TermsOfService
  url: https://dev.epicgames.com/services-agreement
- title: ''
  type: PrivacyPolicy
  url: https://www.epicgames.com/site/en-US/privacypolicy
- title: ''
  type: Support
  url: https://dev.epicgames.com/community/
- title: ''
  type: Store
  url: https://store.epicgames.com/
created: '2024-07-02'
description: Epic Games operates the Epic Games Store digital storefront and the Epic Online Services (EOS) platform, providing developers with cross-platform game services. Epic Online Services is a free SDK based on Fortnite's backend infrastructure, supporting matchmaking, friends, leaderboards, achievements, voice chat, anti-cheat, and player data storage across Windows, macOS, PlayStation, Xbox, Nintendo Switch, iOS, and Android. The Epic Account Services and EOS Web APIs deliver authentication, account management, ecommerce, and analytics for games published on the Epic Games Store and other platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Epic Games
skills: []
slug: epic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: epic\nname: Epic Games\ndescription: >-\n  Epic Games operates the Epic Games Store digital storefront and the Epic\n  Online Services (EOS) platform, providing developers with cross-platform\n  game services. Epic Online Services is a free SDK based on Fortnite's\n  backend infrastructure, supporting matchmaking, friends, leaderboards,\n  achievements, voice chat, anti-cheat, and player data storage across\n  Windows, macOS, PlayStation, Xbox, Nintendo Switch, iOS, and Android.\n  The Epic Account Services and EOS Web APIs deliver authentication,\n  account management, ecommerce, and analytics for games published on the\n  Epic Games Store and other platforms.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Game Services\n  - Gaming\n  - Cross-Platform\n  - Achievements\n  - Leaderboards\n  - Matchmaking\n  - Anti-Cheat\n  - OAuth2\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/epic/refs/heads/main/apis.yml\n\
  created: '2024-07-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nposition: Provider\naccess: Partner\napis:\n  - aid: epic:epic-account-services\n    name: Epic Account Services API\n    description: >-\n      Epic Account Services (EAS) provides authentication and identity for\n      players using Epic Games accounts. Supports OAuth 2.0 authorization\n      code, device, and exchange code flows, account info retrieval, and\n      single sign-on across Epic Games Store and partner titles.\n    humanURL: https://dev.epicgames.com/docs/epic-account-services\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Authentication\n      - OAuth2\n      - Identity\n      - Single Sign-On\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/epic-account-services\n      - type: Authentication\n        url: https://dev.epicgames.com/docs/epic-account-services/auth/auth-interface\n      - type: GettingStarted\n        url: https://dev.epicgames.com/docs/epic-account-services/getting-started\n\
  \  - aid: epic:eos-achievements\n    name: Epic Online Services Achievements API\n    description: >-\n      The EOS Achievements API enables developers to define, unlock, and\n      query player achievements across platforms. Supports definitions,\n      player progress, and unlocking via the EOS SDK or Web API.\n    humanURL: https://dev.epicgames.com/docs/game-services/achievements\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Achievements\n      - Game Services\n      - Progression\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/game-services/achievements\n  - aid: epic:eos-leaderboards\n    name: Epic Online Services Leaderboards API\n    description: >-\n      The EOS Leaderboards API provides global and per-friend leaderboards\n      backed by player stats. Developers configure leaderboards in the\n      developer portal and query rankings via the EOS SDK or Web API.\n    humanURL: https://dev.epicgames.com/docs/game-services/leaderboards\n\
  \    baseURL: https://api.epicgames.dev\n    tags:\n      - Leaderboards\n      - Game Services\n      - Stats\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/game-services/leaderboards\n  - aid: epic:eos-stats\n    name: Epic Online Services Stats API\n    description: >-\n      The EOS Stats API tracks player statistics over time, providing the\n      data source that powers leaderboards and achievements. Supports\n      ingest, increment, and query operations on stat values.\n    humanURL: https://dev.epicgames.com/docs/game-services/eos-stats-interface\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Stats\n      - Game Services\n      - Telemetry\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/game-services/eos-stats-interface\n  - aid: epic:eos-friends\n    name: Epic Online Services Friends API\n    description: >-\n      The EOS Friends API exposes a player's Epic Games friends list,\n\
  \      allowing games to surface social presence, invitations, and party\n      formation across platforms.\n    humanURL: https://dev.epicgames.com/docs/epic-account-services/eos-friends-interface\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Friends\n      - Social\n      - Game Services\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/epic-account-services/eos-friends-interface\n  - aid: epic:eos-ecom\n    name: Epic Online Services Ecom API\n    description: >-\n      The EOS Ecom (Ecommerce) Interface API exposes the player's Epic\n      Games Store entitlements, ownership, catalog offers, and checkout\n      flows. Used by titles published on the Epic Games Store to verify\n      purchases and unlock downloadable content.\n    humanURL: https://dev.epicgames.com/docs/epic-games-store/services/ecom/ecom-overview\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Ecommerce\n      - Entitlements\n      - Catalog\n    \
  \  - Epic Games Store\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/epic-games-store/services/ecom/ecom-overview\n  - aid: epic:eos-lobby-sessions\n    name: Epic Online Services Lobby and Sessions API\n    description: >-\n      The EOS Lobby and Sessions APIs provide matchmaking primitives for\n      multiplayer games, including lobby creation, joining, attribute\n      filtering, and dedicated session management.\n    humanURL: https://dev.epicgames.com/docs/game-services/lobbies-and-sessions\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Matchmaking\n      - Lobbies\n      - Sessions\n      - Multiplayer\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/game-services/lobbies-and-sessions\n  - aid: epic:eos-player-data-storage\n    name: Epic Online Services Player Data Storage API\n    description: >-\n      The EOS Player Data Storage and Title Storage APIs persist\n      per-player\
  \ save data and shared title-level configuration in the\n      cloud, with cross-platform availability and versioning.\n    humanURL: https://dev.epicgames.com/docs/game-services/player-data-storage\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Storage\n      - Cloud Saves\n      - Game Services\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/game-services/player-data-storage\n  - aid: epic:eos-anti-cheat\n    name: Epic Online Services Anti-Cheat API\n    description: >-\n      Easy Anti-Cheat (EAC) integrated into Epic Online Services provides\n      kernel and user-mode anti-cheat protections, server-side validation,\n      and reporting tooling for cross-platform multiplayer titles.\n    humanURL: https://dev.epicgames.com/docs/game-services/anti-cheat\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Anti-Cheat\n      - Security\n      - Multiplayer\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/game-services/anti-cheat\n\
  \  - aid: epic:eos-voice\n    name: Epic Online Services Voice API\n    description: >-\n      The EOS Voice Interface delivers in-game voice chat using Vivox\n      backend infrastructure, with positional audio, room management, and\n      moderation controls across platforms.\n    humanURL: https://dev.epicgames.com/docs/game-services/eos-voice-interface\n    baseURL: https://api.epicgames.dev\n    tags:\n      - Voice\n      - Chat\n      - Communications\n      - Vivox\n    properties:\n      - type: Documentation\n        url: https://dev.epicgames.com/docs/game-services/eos-voice-interface\ncommon:\n  - type: Website\n    url: https://www.epicgames.com/\n  - type: Portal\n    url: https://dev.epicgames.com/portal/\n  - type: Documentation\n    url: https://dev.epicgames.com/docs/\n  - type: GettingStarted\n    url: https://dev.epicgames.com/docs/epic-online-services/eos-get-started\n  - type: Authentication\n    url: https://dev.epicgames.com/docs/epic-account-services/auth/auth-interface\n\
  \  - type: TermsOfService\n    url: https://dev.epicgames.com/services-agreement\n  - type: PrivacyPolicy\n    url: https://www.epicgames.com/site/en-US/privacypolicy\n  - type: Support\n    url: https://dev.epicgames.com/community/\n  - type: Store\n    url: https://store.epicgames.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/epic/refs/heads/main/apis.yml
tags:
- Game Services
- Gaming
- Cross-Platform
- Achievements
- Leaderboards
- Matchmaking
- Anti-Cheat
- OAuth2
url: https://raw.githubusercontent.com/api-evangelist/epic/refs/heads/main/apis.yml
use_cases: []
---
