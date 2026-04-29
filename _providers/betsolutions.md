---
api_count: 6
api_specs:
- filename: betsolutions-wallet-api.yaml
  format: yaml
  label: BetSolutions Wallet API
  slug: wallet-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/betsolutions/refs/heads/main/openapi/betsolutions-wallet-api.yaml
apis:
- description: Two-mode wallet integration for casino operators. Transfer mode provides deposit, withdraw, and balance operations managed by BetSolutions. Seamless mode enables operator-side wallet management with b
  name: BetSolutions Wallet API
  slug: wallet-api
- description: Player information and data retrieval endpoints including player profile details, rake data by date range, and game list retrieval with product metadata.
  name: BetSolutions Player API
  slug: player-api
- description: Slot game integration and campaign management including freespin campaign creation, deactivation, configuration retrieval, and player assignment for promotional campaigns.
  name: BetSolutions Slots API
  slug: slots-api
- description: Multiplayer table game integration supporting Backgammon, Bura, Okey, Domino, and Seka. Includes tournament management with types and statuses, and achievement systems for player engagement.
  name: BetSolutions Table Games API
  slug: table-games-api
- description: Provably fair game integration for Zeppelin, High Low, Dice, Mines, and Plinko. Provides jackpot history, multiplier history, and freebet creation for provably fair game mechanics.
  name: BetSolutions Provably Fair Games API
  slug: provably-fair-api
- description: Third-party sportsbook integration starting with BCBetting, providing bet retrieval, bonus management, and player-specific bonus operations.
  name: BetSolutions Third-Party Integration API
  slug: third-party-api
capabilities:
- description: Unified casino platform workflow combining wallet management, player profile, and game catalog operations. Designed for casino operators and developers integrating BetSolutions into their gaming platf
  name: BetSolutions Casino Platform
  slug: casino-platform
common:
- title: ''
  type: Documentation
  url: https://docs.betsolutions.com/
- title: ''
  type: Authentication
  url: https://docs.betsolutions.com/
- title: ''
  type: Website
  url: https://betsolutions.com
- title: .NET SDK (NuGet)
  type: SDK
  url: https://www.nuget.org/packages/BetSolutions
- title: PHP SDK (Composer)
  type: SDK
  url: https://packagist.org/packages/betsolutions/casino-api
- title: ''
  type: SpectralRules
  url: rules/betsolutions-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/casino-platform.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/betsolutions-vocabulary.yaml
created: '2025-02-24'
description: BetSolutions provides a casino and gaming platform API offering a two-way HTTP API with JSON data format for implementing requests and responses for slots, single and multiplayer games, and other casino platform services. The platform supports transfer and seamless wallet integration modes, slot campaigns with freespins, table games, provably fair games, poker, and third-party sportsbook integrations. Authentication uses SHA-256 hash-based signing with merchant secret keys.
features:
- description: BetSolutions-managed wallet with deposit, withdraw, and balance operations for casino operators.
  name: Transfer Wallet Mode
- description: Operator-side wallet integration where BetSolutions calls the operator's server for bet, win, and balance operations.
  name: Seamless Wallet Mode
- description: Secure request signing using SHA-256 hash algorithm with merchant secret keys and pipe-separated parameter concatenation.
  name: SHA-256 Authentication
- description: Slot game integration with freespin campaign management, player assignment, and campaign configuration.
  name: Slot Games
- description: Multiplayer table games including Backgammon, Bura, Okey, Domino, and Seka with tournament support.
  name: Table Games
- description: Cryptographically verifiable games including Zeppelin, High Low, Dice, Mines, and Plinko.
  name: Provably Fair Games
- description: Poker integration with jackpot tracking and daily financial reporting.
  name: Poker
- description: Integration with BCBetting sportsbook platform for bet and bonus management.
  name: Third-Party Sportsbook
- description: Official SDK packages available for .NET (NuGet), PHP (Composer), and Java (JAR) platforms.
  name: SDK Packages
- description: API supports 11 languages for international casino operator deployments.
  name: Multi-Language Support
- description: ISO 4217 currency codes for international payment processing.
  name: Multi-Currency Support
image: ''
integrations:
- description: Third-party sportsbook integration providing sports betting functionality for casino operators.
  name: BCBetting
- description: .NET SDK available via NuGet for easy integration in .NET casino platform backends.
  name: NuGet Package Manager
- description: PHP SDK available via Composer for PHP-based casino platform implementations.
  name: Composer Package Manager
- description: Java SDK available as a JAR package for Java-based casino platform implementations.
  name: Java JAR
jsonld:
- class_count: 14
  name: Betsolutions Wallet Api Context
  property_count: 23
  slug: betsolutions-wallet-api-context
layout: provider
modified: '2026-04-19'
name: BetSolutions
rules:
- name: BetSolutions API Rules
  rule_count: 30
  severity_counts:
    error: 15
    hint: 0
    info: 2
    warn: 13
  slug: betsolutions-spectral-rules
skills: []
slug: betsolutions
solutions: []
source_filename: apis.yml
source_yaml: "aid: betsolutions\nurl: https://raw.githubusercontent.com/api-evangelist/betsolutions/refs/heads/main/apis.yml\nname: BetSolutions\ntags:\n  - Betting\n  - Casinos\n  - Gaming\n  - Gambling\n  - Slots\n  - Sports Betting\nx-type: company\ncreated: '2025-02-24'\nmodified: '2026-04-19'\ndescription: >-\n  BetSolutions provides a casino and gaming platform API offering a two-way HTTP API\n  with JSON data format for implementing requests and responses for slots, single and\n  multiplayer games, and other casino platform services. The platform supports transfer\n  and seamless wallet integration modes, slot campaigns with freespins, table games,\n  provably fair games, poker, and third-party sportsbook integrations. Authentication\n  uses SHA-256 hash-based signing with merchant secret keys.\napis:\n  - aid: betsolutions:wallet-api\n    name: BetSolutions Wallet API\n    tags:\n      - Wallet\n      - Payments\n      - Transfer\n      - Seamless\n    humanURL: https://docs.betsolutions.com/\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.betsolutions.com/\n      - type: OpenAPI\n        url: openapi/betsolutions-wallet-api.yaml\n    description: >-\n      Two-mode wallet integration for casino operators. Transfer mode provides deposit,\n      withdraw, and balance operations managed by BetSolutions. Seamless mode enables\n      operator-side wallet management with bet, win, cancel bet, change win, and balance\n      endpoints called by BetSolutions on the operator's server.\n\n  - aid: betsolutions:player-api\n    name: BetSolutions Player API\n    tags:\n      - Players\n      - Accounts\n      - Information\n    humanURL: https://docs.betsolutions.com/\n    properties:\n      - type: Documentation\n        url: https://docs.betsolutions.com/\n    description: >-\n      Player information and data retrieval endpoints including player profile details,\n      rake data by date range, and game list retrieval with product metadata.\n\n  - aid: betsolutions:slots-api\n\
  \    name: BetSolutions Slots API\n    tags:\n      - Slots\n      - Campaigns\n      - Freespins\n      - Gaming\n    humanURL: https://docs.betsolutions.com/\n    properties:\n      - type: Documentation\n        url: https://docs.betsolutions.com/\n    description: >-\n      Slot game integration and campaign management including freespin campaign creation,\n      deactivation, configuration retrieval, and player assignment for promotional\n      campaigns.\n\n  - aid: betsolutions:table-games-api\n    name: BetSolutions Table Games API\n    tags:\n      - Table Games\n      - Multiplayer\n      - Tournaments\n      - Gaming\n    humanURL: https://docs.betsolutions.com/\n    properties:\n      - type: Documentation\n        url: https://docs.betsolutions.com/\n    description: >-\n      Multiplayer table game integration supporting Backgammon, Bura, Okey, Domino,\n      and Seka. Includes tournament management with types and statuses, and achievement\n      systems for player engagement.\n\
  \n  - aid: betsolutions:provably-fair-api\n    name: BetSolutions Provably Fair Games API\n    tags:\n      - Provably Fair\n      - Zeppelin\n      - Gaming\n    humanURL: https://docs.betsolutions.com/\n    properties:\n      - type: Documentation\n        url: https://docs.betsolutions.com/\n    description: >-\n      Provably fair game integration for Zeppelin, High Low, Dice, Mines, and Plinko.\n      Provides jackpot history, multiplier history, and freebet creation for provably\n      fair game mechanics.\n\n  - aid: betsolutions:third-party-api\n    name: BetSolutions Third-Party Integration API\n    tags:\n      - Sportsbook\n      - BCBetting\n      - Integration\n    humanURL: https://docs.betsolutions.com/\n    properties:\n      - type: Documentation\n        url: https://docs.betsolutions.com/\n    description: >-\n      Third-party sportsbook integration starting with BCBetting, providing bet retrieval,\n      bonus management, and player-specific bonus operations.\n\ncommon:\n\
  \  - type: Documentation\n    url: https://docs.betsolutions.com/\n  - type: Authentication\n    url: https://docs.betsolutions.com/\n  - type: Website\n    url: https://betsolutions.com\n  - type: SDK\n    url: https://www.nuget.org/packages/BetSolutions\n    title: .NET SDK (NuGet)\n  - type: SDK\n    url: https://packagist.org/packages/betsolutions/casino-api\n    title: PHP SDK (Composer)\n  - type: Features\n    data:\n      - name: Transfer Wallet Mode\n        description: BetSolutions-managed wallet with deposit, withdraw, and balance operations for casino operators.\n      - name: Seamless Wallet Mode\n        description: Operator-side wallet integration where BetSolutions calls the operator's server for bet, win, and balance operations.\n      - name: SHA-256 Authentication\n        description: Secure request signing using SHA-256 hash algorithm with merchant secret keys and pipe-separated parameter concatenation.\n      - name: Slot Games\n        description: Slot game integration\
  \ with freespin campaign management, player assignment, and campaign configuration.\n      - name: Table Games\n        description: Multiplayer table games including Backgammon, Bura, Okey, Domino, and Seka with tournament support.\n      - name: Provably Fair Games\n        description: Cryptographically verifiable games including Zeppelin, High Low, Dice, Mines, and Plinko.\n      - name: Poker\n        description: Poker integration with jackpot tracking and daily financial reporting.\n      - name: Third-Party Sportsbook\n        description: Integration with BCBetting sportsbook platform for bet and bonus management.\n      - name: SDK Packages\n        description: Official SDK packages available for .NET (NuGet), PHP (Composer), and Java (JAR) platforms.\n      - name: Multi-Language Support\n        description: API supports 11 languages for international casino operator deployments.\n      - name: Multi-Currency Support\n        description: ISO 4217 currency codes for international\
  \ payment processing.\n  - type: UseCases\n    data:\n      - name: Casino Platform Integration\n        description: Online casino operators integrate BetSolutions APIs to offer slots, table games, and card games to players.\n      - name: Wallet Integration\n        description: Casino operators choose transfer or seamless wallet mode to manage player funds and game transactions.\n      - name: Freespin Campaigns\n        description: Marketing teams create and manage freespin slot campaigns to acquire and retain players.\n      - name: Tournament Management\n        description: Operators run tournaments for multiplayer table games with configurable types and prize structures.\n      - name: Provably Fair Gaming\n        description: Platforms offering cryptographically verifiable game results using BetSolutions' provably fair API.\n      - name: Sportsbook Integration\n        description: Operators add sports betting capabilities through the BCBetting third-party integration.\n  -\
  \ type: Integrations\n    data:\n      - name: BCBetting\n        description: Third-party sportsbook integration providing sports betting functionality for casino operators.\n      - name: NuGet Package Manager\n        description: .NET SDK available via NuGet for easy integration in .NET casino platform backends.\n      - name: Composer Package Manager\n        description: PHP SDK available via Composer for PHP-based casino platform implementations.\n      - name: Java JAR\n        description: Java SDK available as a JAR package for Java-based casino platform implementations.\n  - type: SpectralRules\n    url: rules/betsolutions-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/casino-platform.yaml\n  - type: Vocabulary\n    url: vocabulary/betsolutions-vocabulary.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/betsolutions/refs/heads/main/apis.yml
tags:
- Betting
- Casinos
- Gaming
- Gambling
- Slots
- Sports Betting
url: https://raw.githubusercontent.com/api-evangelist/betsolutions/refs/heads/main/apis.yml
use_cases:
- description: Online casino operators integrate BetSolutions APIs to offer slots, table games, and card games to players.
  name: Casino Platform Integration
- description: Casino operators choose transfer or seamless wallet mode to manage player funds and game transactions.
  name: Wallet Integration
- description: Marketing teams create and manage freespin slot campaigns to acquire and retain players.
  name: Freespin Campaigns
- description: Operators run tournaments for multiplayer table games with configurable types and prize structures.
  name: Tournament Management
- description: Platforms offering cryptographically verifiable game results using BetSolutions' provably fair API.
  name: Provably Fair Gaming
- description: Operators add sports betting capabilities through the BCBetting third-party integration.
  name: Sportsbook Integration
---
