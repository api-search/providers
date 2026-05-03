---
api_count: 2
api_specs:
- filename: taddy-podcast-openapi.yml
  format: yaml
  label: Taddy Podcast API
  slug: taddy-podcast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/openapi/taddy-podcast-openapi.yml
apis:
- description: GraphQL API providing access to over 4 million podcasts and 200 million episodes. Supports podcast and episode search, transcript retrieval with speaker and timecode data, top charts by country, webho
  name: Taddy Podcast API
  slug: taddy-podcast-api
- description: GraphQL API for accessing comic book series, issues, and creator data from the Taddy comic book database.
  name: Taddy Comics API
  slug: taddy-comics-api
capabilities:
- description: Workflow capability for discovering, searching, and analyzing podcast content via the Taddy API. Enables content teams, app developers, and media researchers to find podcasts, retrieve episode transcr
  name: Taddy Podcast Discovery
  slug: podcast-discovery
common:
- title: ''
  type: Portal
  url: https://taddy.org/developers
- title: ''
  type: Documentation
  url: https://taddy.org/developers/podcast-api
- title: ''
  type: Getting Started
  url: https://taddy.org/developers/intro-to-taddy-graphql-api
- title: ''
  type: Sign Up
  url: https://taddy.org/register
- title: ''
  type: Website
  url: https://taddy.org/
- title: ''
  type: Pricing
  url: https://taddy.org/developers#pricing
- title: ''
  type: GitHub Org
  url: https://github.com/taddyorg
- title: ''
  type: Example Project
  url: https://github.com/taddyorg/taddy-api-example-project
- title: ''
  type: Dataset Export
  url: https://github.com/taddyorg/podcast-dataset-export
- title: ''
  type: Webhooks
  url: https://github.com/taddyorg/webhook-example-taddy
- title: ''
  type: n8n Integration
  url: https://github.com/taddyorg/podcast-data-n8n-integration
- title: ''
  type: Zapier Integration
  url: https://github.com/taddyorg/podcast-data-zapier-integration
- title: ''
  type: JSON Schema
  url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-schema/taddy-podcast-series-schema.json
- title: ''
  type: JSON Schema
  url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-schema/taddy-podcast-episode-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/vocabulary/taddy-api-vocabulary.yml
created: '2025-05-02'
description: Taddy provides a GraphQL-based podcast API giving developers access to over 4 million podcasts and 200 million episodes with real-time search, episode transcripts, webhooks, top charts, and comic book data. Taddy simplifies building podcast applications by aggregating and standardizing RSS feed data at scale with daily updates of 1,000 new podcasts and 50,000 new episodes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Taddy Api Context
  property_count: 41
  slug: taddy-api-context
layout: provider
modified: '2026-05-03'
name: Taddy API
rules:
- name: Taddy API API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: taddy-api-rules
skills: []
slug: taddy-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: taddy-api\nname: Taddy API\ndescription: >-\n  Taddy provides a GraphQL-based podcast API giving developers access to over\n  4 million podcasts and 200 million episodes with real-time search, episode\n  transcripts, webhooks, top charts, and comic book data. Taddy simplifies\n  building podcast applications by aggregating and standardizing RSS feed data\n  at scale with daily updates of 1,000 new podcasts and 50,000 new episodes.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Audio\n  - Comics\n  - GraphQL\n  - Media\n  - Podcasts\n  - Transcripts\n  - Webhooks\ncreated: '2025-05-02'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: taddy-api:taddy-podcast-api\n    name: Taddy Podcast API\n    description: >-\n      GraphQL API providing access to over 4 million\
  \ podcasts and 200 million\n      episodes. Supports podcast and episode search, transcript retrieval with\n      speaker and timecode data, top charts by country, webhooks for real-time\n      updates and brand monitoring, and detailed metadata including genres,\n      persons, chapters, and transcription status.\n    humanURL: https://taddy.org/developers/podcast-api\n    baseURL: https://api.taddy.org\n    tags:\n      - Audio\n      - Episodes\n      - GraphQL\n      - Podcasts\n      - Search\n      - Transcripts\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://taddy.org/developers/podcast-api\n      - type: Getting Started\n        url: https://taddy.org/developers/intro-to-taddy-graphql-api\n      - type: GraphQL Schema\n        url: https://ax0.taddy.org/docs/schema.graphql\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/openapi/taddy-podcast-openapi.yml\n  - aid:\
  \ taddy-api:taddy-comics-api\n    name: Taddy Comics API\n    description: >-\n      GraphQL API for accessing comic book series, issues, and creator data\n      from the Taddy comic book database.\n    humanURL: https://taddy.org/developers/comics-api\n    baseURL: https://api.taddy.org\n    tags:\n      - Comics\n      - GraphQL\n      - Media\n    properties:\n      - type: Documentation\n        url: https://taddy.org/developers/comics-api\ncommon:\n  - type: Portal\n    url: https://taddy.org/developers\n  - type: Documentation\n    url: https://taddy.org/developers/podcast-api\n  - type: Getting Started\n    url: https://taddy.org/developers/intro-to-taddy-graphql-api\n  - type: Sign Up\n    url: https://taddy.org/register\n  - type: Website\n    url: https://taddy.org/\n  - type: Pricing\n    url: https://taddy.org/developers#pricing\n  - type: GitHub Org\n    url: https://github.com/taddyorg\n  - type: Example Project\n    url: https://github.com/taddyorg/taddy-api-example-project\n\
  \  - type: Dataset Export\n    url: https://github.com/taddyorg/podcast-dataset-export\n  - type: Webhooks\n    url: https://github.com/taddyorg/webhook-example-taddy\n  - type: n8n Integration\n    url: https://github.com/taddyorg/podcast-data-n8n-integration\n  - type: Zapier Integration\n    url: https://github.com/taddyorg/podcast-data-zapier-integration\n  - type: JSON Schema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-schema/taddy-podcast-series-schema.json\n  - type: JSON Schema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-schema/taddy-podcast-episode-schema.json\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/vocabulary/taddy-api-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/apis.yml
tags:
- Audio
- Comics
- GraphQL
- Media
- Podcasts
- Transcripts
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/apis.yml
use_cases: []
---
