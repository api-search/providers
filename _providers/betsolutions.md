---
api_count: 6
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
