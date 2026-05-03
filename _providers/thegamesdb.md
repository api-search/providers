---
api_count: 1
api_specs:
- filename: thegamesdb-openapi.yml
  format: yaml
  label: TheGamesDB API
  slug: thegamesdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/openapi/thegamesdb-openapi.yml
apis:
- description: An open, online database for video game fans providing game information, artwork, and metadata via API. Search and retrieve game details, platform information, game artwork (boxart, screenshots, fanar
  name: TheGamesDB API
  slug: thegamesdb
capabilities:
- description: Unified workflow for video game discovery, metadata lookup, and platform research. Combines game search, platform browsing, artwork retrieval, and reference data (genres, developers, publishers) for g
  name: TheGamesDB Video Game Discovery
  slug: video-game-discovery
common:
- title: ''
  type: Website
  url: https://thegamesdb.net/
- title: ''
  type: Documentation
  url: https://api.thegamesdb.net/
- title: ''
  type: Sign Up
  url: https://api.thegamesdb.net/key.php
- title: ''
  type: GitHub Organization
  url: https://github.com/TheGamesDB
- title: TheGamesDB Spectral Rules
  type: SpectralRules
  url: rules/thegamesdb-spectral-rules.yml
- title: TheGamesDB Vocabulary
  type: Vocabulary
  url: vocabulary/thegamesdb-vocabulary.yml
- title: Video Game Discovery
  type: NaftikoCapability
  url: capabilities/video-game-discovery.yaml
- title: ''
  type: RateLimits
  url: https://api.thegamesdb.net/key.php
- title: ''
  type: Authentication
  url: https://api.thegamesdb.net/key.php
created: '2025-02-08'
description: An open, online database for video game fans providing game information, artwork, and metadata via API.
features:
- description: Search games by name with optional platform filtering
  name: Game Search
- description: Retrieve complete game metadata by ID including overview, ratings, and system requirements
  name: Game Details
- description: Full catalog of all gaming platforms with hardware specifications and images
  name: Platform Catalog
- description: Boxart, screenshots, fanart, banners, and clearlogos for games and platforms
  name: Game Artwork
- description: Retrieve games updated since a given timestamp for database synchronization
  name: Game Updates
- description: Complete lists of genres, developers, and publishers
  name: Reference Data
- description: Request multiple game or platform IDs in a single API call
  name: Batch Requests
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Popular retro gaming frontend using TheGamesDB for scraping
  name: EmulationStation
- description: Game scraper tools using the API for artwork and metadata
  name: Skraper
jsonld:
- class_count: 9
  name: Thegamesdb Context
  property_count: 35
  slug: thegamesdb-context
layout: provider
modified: '2026-05-03'
name: TheGamesDB
rules:
- name: TheGamesDB API Rules
  rule_count: 22
  severity_counts:
    error: 8
    hint: 0
    info: 4
    warn: 10
  slug: thegamesdb-spectral-rules
skills: []
slug: thegamesdb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thegamesdb\nname: TheGamesDB\ndescription: An open, online database for video game fans providing game information, artwork, and metadata via API.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Database\n  - Gaming\n  - Video Games\n  - Metadata\n  - Artwork\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: thegamesdb:thegamesdb\n    name: TheGamesDB API\n    description: >-\n      An open, online database for video game fans providing game information,\n      artwork, and metadata via API. Search and retrieve game details, platform\n      information, game artwork (boxart, screenshots, fanart), genres,\n      developers, and publishers. Requires an API key.\n    humanURL: https://api.thegamesdb.net/\n    baseURL: https://api.thegamesdb.net\n\
  \    tags:\n      - Database\n      - Gaming\n      - Video Games\n      - Metadata\n      - Artwork\n    properties:\n      - type: Documentation\n        url: https://api.thegamesdb.net/\n      - type: OpenAPI\n        url: openapi/thegamesdb-openapi.yml\n      - type: Sign Up\n        url: https://api.thegamesdb.net/key.php\n      - type: JSONSchema\n        url: json-schema/thegamesdb-game-schema.json\n        title: Game Schema\n      - type: JSONStructure\n        url: json-structure/thegamesdb-game-structure.json\n        title: Game Structure\n      - type: JSON-LD\n        url: json-ld/thegamesdb-context.jsonld\n        title: TheGamesDB JSON-LD Context\ncommon:\n  - type: Website\n    url: https://thegamesdb.net/\n  - type: Documentation\n    url: https://api.thegamesdb.net/\n  - type: Sign Up\n    url: https://api.thegamesdb.net/key.php\n  - type: GitHub Organization\n    url: https://github.com/TheGamesDB\n  - type: SpectralRules\n    url: rules/thegamesdb-spectral-rules.yml\n\
  \    title: TheGamesDB Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/thegamesdb-vocabulary.yml\n    title: TheGamesDB Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/video-game-discovery.yaml\n    title: Video Game Discovery\n  - type: RateLimits\n    url: https://api.thegamesdb.net/key.php\n    data:\n      - name: Monthly Allowance\n        description: 1000 queries per month (20 calls per query = 20,000 total calls)\n  - type: Authentication\n    url: https://api.thegamesdb.net/key.php\n    data:\n      - name: API Key Query Parameter\n        description: API key passed as 'apikey' query parameter on all requests\n  - type: Features\n    data:\n      - name: Game Search\n        description: Search games by name with optional platform filtering\n      - name: Game Details\n        description: Retrieve complete game metadata by ID including overview, ratings, and system requirements\n      - name: Platform Catalog\n        description: Full catalog of all\
  \ gaming platforms with hardware specifications and images\n      - name: Game Artwork\n        description: Boxart, screenshots, fanart, banners, and clearlogos for games and platforms\n      - name: Game Updates\n        description: Retrieve games updated since a given timestamp for database synchronization\n      - name: Reference Data\n        description: Complete lists of genres, developers, and publishers\n      - name: Batch Requests\n        description: Request multiple game or platform IDs in a single API call\n  - type: UseCases\n    data:\n      - name: Gaming Applications\n        description: Build game databases, libraries, and collection managers\n      - name: Media Centers\n        description: Power game scrapers for Emulation Station, Kodi, and similar media centers\n      - name: Game Collections\n        description: Manage personal or commercial video game collection databases\n      - name: AI Game Assistant\n        description: Power AI agents that answer questions\
  \ about video games\n  - type: Integrations\n    data:\n      - name: EmulationStation\n        description: Popular retro gaming frontend using TheGamesDB for scraping\n      - name: Skraper\n        description: Game scraper tools using the API for artwork and metadata\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/apis.yml
tags:
- Database
- Gaming
- Video Games
- Metadata
- Artwork
url: https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/apis.yml
use_cases:
- description: Build game databases, libraries, and collection managers
  name: Gaming Applications
- description: Power game scrapers for Emulation Station, Kodi, and similar media centers
  name: Media Centers
- description: Manage personal or commercial video game collection databases
  name: Game Collections
- description: Power AI agents that answer questions about video games
  name: AI Game Assistant
---
