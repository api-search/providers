---
api_count: 1
api_specs:
- filename: rawg-openapi.yml
  format: yaml
  label: RAWG Video Games Database API
  slug: rawg
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/openapi/rawg-openapi.yml
apis:
- description: The RAWG Video Games Database API provides programmatic access to a catalog of more than 350,000 games across 50+ platforms, including creator roles, individual creators, game developers, game publish
  name: RAWG Video Games Database API
  slug: rawg
capabilities:
- description: Unified game discovery and research capability powered by the RAWG Video Games Database. Enables developers, content creators, and gaming applications to search, filter, and retrieve comprehensive gam
  name: RAWG Game Discovery
  slug: game-discovery
common:
- title: ''
  type: Website
  url: https://rawg.io
- title: ''
  type: Documentation
  url: https://rawg.io/apidocs
- title: ''
  type: SignUp
  url: https://rawg.io/login?forward=developer
- title: ''
  type: TermsOfService
  url: https://rawg.io/terms
- title: ''
  type: Blog
  url: https://rawg.io/blog
created: '2025-02-08'
description: RAWG is the largest video game database and game discovery service, providing access to more than 350,000 games across 50+ platforms with rich metadata including tags, genres, developers, publishers, creators, release dates, Metacritic ratings, store links, ESRB ratings, average playtime, achievements, screenshots, trailers, and social media data. RAWG offers a free REST API for personal and small commercial use with API key authentication, enabling developers to search and filter games by platform, genre, developer, publisher, tag, release date, and rating. The API also provides endpoints for exploring game series, DLCs, development team members, and visually similar games (enterprise tier). RAWG is used by developers building game discovery apps, recommendation engines, gaming dashboards, and data warehouses.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 39
  name: Rawg Context
  property_count: 12
  slug: rawg-context
layout: provider
modified: '2026-05-02'
name: RAWG
rules:
- name: RAWG API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: rawg-rules
skills: []
slug: rawg
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rawg\nname: RAWG\ndescription: >-\n  RAWG is the largest video game database and game discovery service,\n  providing access to more than 350,000 games across 50+ platforms with rich\n  metadata including tags, genres, developers, publishers, creators, release\n  dates, Metacritic ratings, store links, ESRB ratings, average playtime,\n  achievements, screenshots, trailers, and social media data. RAWG offers a\n  free REST API for personal and small commercial use with API key\n  authentication, enabling developers to search and filter games by platform,\n  genre, developer, publisher, tag, release date, and rating. The API also\n  provides endpoints for exploring game series, DLCs, development team\n  members, and visually similar games (enterprise tier). RAWG is used by\n  developers building game discovery apps, recommendation engines, gaming\n  dashboards, and data warehouses.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/apis.yml\ntags:\n  - Database\n  - Entertainment\n  - Game Discovery\n  - Games\n  - Gaming\n  - Metadata\n  - Video Games\ncreated: '2025-02-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rawg:rawg\n    name: RAWG Video Games Database API\n    description: >-\n      The RAWG Video Games Database API provides programmatic access to a\n      catalog of more than 350,000 games across 50+ platforms, including\n      creator roles, individual creators, game developers, game publishers,\n      genres, tags, storefronts, platforms, and detailed game metadata. The\n      API supports pagination, search, and multi-dimensional filtering across\n      dates, platforms, genres, tags, Metacritic scores, and more. All\n      requests require an API key passed as a query parameter.\n    humanURL: https://rawg.io/apidocs\n    baseURL: https://api.rawg.io/api\n    tags:\n      - Database\n      - Entertainment\n\
  \      - Game Discovery\n      - Games\n      - Gaming\n      - Metadata\n      - Video Games\n    properties:\n      - type: Documentation\n        url: https://rawg.io/apidocs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/openapi/rawg-openapi.yml\n      - type: Rules\n        url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/rules/rawg-rules.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-schema/rawg-game-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-structure/rawg-game-structure.json\n      - type: JSONLd\n        url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-ld/rawg-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/vocabulary/rawg-vocabulary.yml\n\
  common:\n  - type: Website\n    url: https://rawg.io\n  - type: Documentation\n    url: https://rawg.io/apidocs\n  - type: SignUp\n    url: https://rawg.io/login?forward=developer\n  - type: TermsOfService\n    url: https://rawg.io/terms\n  - type: Blog\n    url: https://rawg.io/blog\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/apis.yml
tags:
- Database
- Entertainment
- Game Discovery
- Games
- Gaming
- Metadata
- Video Games
url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/apis.yml
use_cases: []
---
