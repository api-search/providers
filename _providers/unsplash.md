---
api_count: 1
api_specs:
- filename: unsplash-openapi.yml
  format: yaml
  label: Unsplash API
  slug: unsplash
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/openapi/unsplash-openapi.yml
apis:
- description: 'REST API providing access to Unsplash''s full photo library with endpoints for photo search, random photos, editorial feed browsing, photo detail and statistics, collection management, topic browsing, '
  name: Unsplash API
  slug: unsplash
capabilities:
- description: Workflow capability for discovering and browsing high-quality photos using the Unsplash API. Enables developers, designers, and content creators to search for photos by keyword, browse editorial feeds
  name: Unsplash Photo Discovery
  slug: photo-discovery
common:
- title: ''
  type: Website
  url: https://unsplash.com
- title: ''
  type: Documentation
  url: https://unsplash.com/documentation
- title: ''
  type: Developers
  url: https://unsplash.com/developers
- title: ''
  type: Guidelines
  url: https://help.unsplash.com/en/articles/2511245-unsplash-api-guidelines
- title: ''
  type: GitHub
  url: https://github.com/unsplash
- title: ''
  type: Changelog
  url: https://unsplash.com/documentation/changelog
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/vocabulary/unsplash-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/json-ld/unsplash-context.jsonld
created: '2024-11-13'
description: Unsplash is a platform providing the world's largest collection of high-quality, freely usable photographs. The Unsplash API gives developers programmatic access to search, browse, and retrieve photos, collections, topics, and user profiles. Photos are provided under the Unsplash License. Authentication uses Client-ID for public access or OAuth 2.0 for user-delegated operations.
features: []
image: ''
integrations: []
jsonld:
- class_count: 11
  name: Unsplash Context
  property_count: 42
  slug: unsplash-context
layout: provider
modified: '2026-05-03'
name: Unsplash
rules:
- name: Unsplash API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: unsplash-rules
skills: []
slug: unsplash
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unsplash\nname: Unsplash\ndescription: >-\n  Unsplash is a platform providing the world's largest collection of high-quality,\n  freely usable photographs. The Unsplash API gives developers programmatic access to\n  search, browse, and retrieve photos, collections, topics, and user profiles.\n  Photos are provided under the Unsplash License. Authentication uses Client-ID for\n  public access or OAuth 2.0 for user-delegated operations.\nurl: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/apis.yml\ncreated: '2024-11-13'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Photos\n  - Images\n  - Photography\n  - Stock Photos\n  - Creative\n  - Open Source\n  - Media\napis:\n  - aid: unsplash:unsplash\n    name: Unsplash API\n    description: >-\n      REST API providing access to Unsplash's full photo library with endpoints for\n      photo search, random photos, editorial feed browsing, photo detail and statistics,\n\
  \      collection management, topic browsing, and user profiles. Returns JSON responses\n      with multiple photo size URLs (raw, full, regular, small, thumb) via imgix CDN.\n      Rate limit: 50 req/hr (demo), 1000 req/hr (production). Download tracking via\n      /photos/{id}/download is required per Unsplash API guidelines.\n    humanURL: https://unsplash.com/developers\n    baseURL: https://api.unsplash.com\n    tags:\n      - Photos\n      - Search\n      - Collections\n      - Topics\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://unsplash.com/documentation\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/openapi/unsplash-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/rules/unsplash-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/capabilities/photo-discovery.yaml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/json-schema/unsplash-photo-schema.json\n\ncommon:\n  - type: Website\n    url: https://unsplash.com\n  - type: Documentation\n    url: https://unsplash.com/documentation\n  - type: Developers\n    url: https://unsplash.com/developers\n  - type: Guidelines\n    url: https://help.unsplash.com/en/articles/2511245-unsplash-api-guidelines\n  - type: GitHub\n    url: https://github.com/unsplash\n  - type: Changelog\n    url: https://unsplash.com/documentation/changelog\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/vocabulary/unsplash-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/json-ld/unsplash-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/apis.yml
tags:
- Photos
- Images
- Photography
- Stock Photos
- Creative
- Open Source
- Media
url: https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/apis.yml
use_cases: []
---
