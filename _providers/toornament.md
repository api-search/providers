---
api_count: 2
api_specs:
- filename: toornament-openapi.yml
  format: yaml
  label: Toornament Organizer API
  slug: organizer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/openapi/toornament-openapi.yml
apis:
- description: Full-featured tournament management API for tournament organizers. Provides complete CRUD operations for tournaments, participant management, stage and bracket configuration, match reporting, registra
  name: Toornament Organizer API
  slug: organizer-api
- description: Read-only public API for accessing tournament information without full organizer authentication. Ideal for embedding tournament brackets, leaderboards, and match schedules in applications, streaming o
  name: Toornament Viewer API
  slug: viewer-api
capabilities:
- description: Workflow capability for full esports tournament lifecycle management using the Toornament Organizer API — covering tournament creation, participant management, bracket progression, match reporting, an
  name: Toornament Tournament Management
  slug: tournament-management
common:
- title: ''
  type: Website
  url: https://www.toornament.com/
- title: ''
  type: Documentation
  url: https://developer.toornament.com/
- title: ''
  type: Getting Started
  url: https://developer.toornament.com/v2/overview/get-started
- title: ''
  type: Sign Up
  url: https://www.toornament.com/signup/
- title: ''
  type: Login
  url: https://app.toornament.com/
- title: ''
  type: Pricing
  url: https://www.toornament.com/en_US/p/tournament-api
- title: ''
  type: JSON-LD
  url: json-ld/toornament-context.jsonld
- title: ''
  type: JSON-Schema
  url: json-schema/toornament-tournament-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/toornament-tournament-structure.json
- title: ''
  type: SpectralRules
  url: rules/toornament-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/tournament-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/toornament-vocabulary.yml
created: '2025-02-06'
description: Toornament is an esports tournament management platform providing a comprehensive API for creating, managing, and viewing tournaments across 100+ esports disciplines. The API supports full tournament lifecycle management including participant registration, bracket generation, match reporting, and real-time standings. Used by game publishers, esports organizers, broadcasters, and gaming communities worldwide.
features:
- name: Tournament Creation and Management
- name: Participant Registration
- name: Bracket Generation (Single/Double Elimination)
- name: Group Stage Management
- name: Match Reporting
- name: Live Rankings and Standings
- name: Custom Registration Fields
- name: Check-in Management
- name: Webhook Event Notifications
- name: Multi-discipline Support (100+ games)
- name: Team and Player Support
- name: Public Tournament Viewer API
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Postman
- name: Insomnia
- name: OAuth2 Identity Providers
jsonld:
- class_count: 0
  name: Toornament Context
  property_count: 7
  slug: toornament-context
layout: provider
modified: '2026-05-03'
name: Toornament
rules:
- name: Toornament API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 5
  slug: toornament-rules
skills: []
slug: toornament
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: toornament\nname: Toornament\ndescription: >-\n  Toornament is an esports tournament management platform providing a\n  comprehensive API for creating, managing, and viewing tournaments across\n  100+ esports disciplines. The API supports full tournament lifecycle\n  management including participant registration, bracket generation, match\n  reporting, and real-time standings. Used by game publishers, esports\n  organizers, broadcasters, and gaming communities worldwide.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Esports\n  - Gaming\n  - Tournaments\n  - Brackets\n  - Competition\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: toornament:organizer-api\n    name: Toornament Organizer API\n    description: >-\n      Full-featured\
  \ tournament management API for tournament organizers.\n      Provides complete CRUD operations for tournaments, participant management,\n      stage and bracket configuration, match reporting, registration management,\n      and webhook subscriptions. Requires API key authentication plus OAuth2\n      access tokens with organizer:view or organizer:admin scopes.\n    humanURL: https://developer.toornament.com/v2/overview/get-started\n    baseURL: https://api.toornament.com/organizer/v2\n    tags:\n      - Brackets\n      - Esports\n      - Gaming\n      - Matches\n      - Organizer\n      - Participants\n      - Tournaments\n    properties:\n      - type: Documentation\n        url: https://developer.toornament.com/v2/overview/get-started\n      - type: OpenAPI\n        url: openapi/toornament-openapi.yml\n      - type: SpectralRules\n        url: rules/toornament-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/shared/toornament-organizer.yaml\n  - aid: toornament:viewer-api\n\
  \    name: Toornament Viewer API\n    description: >-\n      Read-only public API for accessing tournament information without\n      full organizer authentication. Ideal for embedding tournament brackets,\n      leaderboards, and match schedules in applications, streaming overlays,\n      and fan sites. Supports disciplines, tournaments, participants, stages,\n      matches, and rankings.\n    humanURL: https://developer.toornament.com/v2/doc/viewer_overview\n    baseURL: https://api.toornament.com/viewer/v2\n    tags:\n      - Brackets\n      - Esports\n      - Gaming\n      - Read-Only\n      - Tournaments\n      - Viewer\n    properties:\n      - type: Documentation\n        url: https://developer.toornament.com/v2/doc/viewer_overview\ncommon:\n  - type: Website\n    url: https://www.toornament.com/\n    name: Toornament Website\n    description: 'null'\n  - type: Documentation\n    url: https://developer.toornament.com/\n    name: Toornament Developer Documentation\n    description:\
  \ 'null'\n  - type: Getting Started\n    url: https://developer.toornament.com/v2/overview/get-started\n    name: Getting Started Guide\n    description: 'null'\n  - type: Sign Up\n    url: https://www.toornament.com/signup/\n    name: Toornament Sign Up\n    description: 'null'\n  - type: Login\n    url: https://app.toornament.com/\n    name: Toornament Login\n    description: 'null'\n  - type: Pricing\n    url: https://www.toornament.com/en_US/p/tournament-api\n    name: API Pricing\n    description: 'null'\n  - type: JSON-LD\n    url: json-ld/toornament-context.jsonld\n    name: Toornament JSON-LD Context\n    description: 'JSON-LD context defining Toornament tournament domain vocabulary.'\n  - type: JSON-Schema\n    url: json-schema/toornament-tournament-schema.json\n    name: Toornament Tournament Schema\n    description: 'JSON Schema for the Toornament Tournament entity.'\n  - type: JSONStructure\n    url: json-structure/toornament-tournament-structure.json\n    name: Toornament\
  \ Tournament Structure\n    description: 'Structured documentation of the Toornament Tournament object model.'\n  - type: SpectralRules\n    url: rules/toornament-rules.yml\n    name: Toornament Spectral Rules\n    description: 'Spectral ruleset for Toornament API conventions.'\n  - type: NaftikoCapability\n    url: capabilities/tournament-management.yaml\n    name: Toornament Tournament Management Capability\n    description: 'Naftiko workflow capability for esports tournament management.'\n  - type: Vocabulary\n    url: vocabulary/toornament-vocabulary.yml\n    name: Toornament Vocabulary\n    description: 'Domain vocabulary for the Toornament esports platform.'\n  - name: Features\n    type: Features\n    data:\n      - name: Tournament Creation and Management\n      - name: Participant Registration\n      - name: Bracket Generation (Single/Double Elimination)\n      - name: Group Stage Management\n      - name: Match Reporting\n      - name: Live Rankings and Standings\n      - name:\
  \ Custom Registration Fields\n      - name: Check-in Management\n      - name: Webhook Event Notifications\n      - name: Multi-discipline Support (100+ games)\n      - name: Team and Player Support\n      - name: Public Tournament Viewer API\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Esports Tournament Platform\n      - name: Game Publisher Tournament Integration\n      - name: Streaming Overlay Bracket Display\n      - name: Community Tournament Management\n      - name: Fan Site Tournament Viewer\n      - name: Circuit and League Management\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Postman\n      - name: Insomnia\n      - name: OAuth2 Identity Providers\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/apis.yml
tags:
- Esports
- Gaming
- Tournaments
- Brackets
- Competition
url: https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/apis.yml
use_cases:
- name: Esports Tournament Platform
- name: Game Publisher Tournament Integration
- name: Streaming Overlay Bracket Display
- name: Community Tournament Management
- name: Fan Site Tournament Viewer
- name: Circuit and League Management
---
