---
api_count: 2
api_specs:
- filename: tivo-video-metadata-openapi.yml
  format: yaml
  label: TiVo Video Metadata API
  slug: tivo-video-metadata
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/openapi/tivo-video-metadata-openapi.yml
apis:
- description: The TiVo Video Metadata API v3 provides access to high-quality entertainment imagery and information for TV shows, movies, and episodes. Supports content search by metadata fields and precise ID-based
  name: TiVo Video Metadata API
  slug: tivo-video-metadata
- description: The TiVo Music Metadata API provides access to high-quality music information including artist details, album data, track information, and music imagery. Uses the same HTTP-based query structure and J
  name: TiVo Music Metadata API
  slug: tivo-music-metadata
capabilities:
- description: Workflow capability for entertainment content discovery and metadata enrichment using TiVo's Video Metadata API. Combines content search, ID-based lookup, imagery retrieval, and episode data for strea
  name: TiVo Entertainment Metadata
  slug: entertainment-metadata
common:
- title: ''
  type: Website
  url: https://business.tivo.com/
- title: ''
  type: Documentation
  url: https://business.tivo.com/products-solutions/metadata/tv-movie-metadata-api
- title: ''
  type: Developer Portal
  url: https://developers.tivo.com/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/openapi/tivo-video-metadata-openapi.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/json-ld/tivo-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/vocabulary/tivo-vocabulary.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/rules/tivo-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/capabilities/entertainment-metadata.yaml
- title: ''
  type: GitHub Organization
  url: https://github.com/tivo
created: '2025-03-01'
description: TiVo provides a universe of high-quality entertainment imagery and information through its metadata APIs. The company offers Video Metadata API and Music Metadata API delivering TV, movie, and music content data for streaming platforms, smart TVs, IPTV systems, and entertainment applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 37
  name: Tivo Context
  property_count: 4
  slug: tivo-context
layout: provider
modified: '2026-05-03'
name: Tivo
rules:
- name: Tivo API Rules
  rule_count: 13
  severity_counts:
    error: 6
    hint: 2
    info: 0
    warn: 5
  slug: tivo-rules
skills: []
slug: tivo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tivo\nname: Tivo\ndescription: >-\n  TiVo provides a universe of high-quality entertainment imagery and information\n  through its metadata APIs. The company offers Video Metadata API and Music Metadata\n  API delivering TV, movie, and music content data for streaming platforms, smart TVs,\n  IPTV systems, and entertainment applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Entertainment\n  - Metadata\n  - Television\n  - Movies\n  - Music\n  - Streaming\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tivo:tivo-video-metadata\n    name: TiVo Video Metadata API\n    description: >-\n      The TiVo Video Metadata API v3 provides access to high-quality entertainment\n      imagery and information for TV shows, movies, and episodes. Supports\
  \ content\n      search by metadata fields and precise ID-based lookup using Rovi 1.1, Rovi 2.0,\n      TMDB, and EIDR identifiers. Returns JSON responses for reliable, scalable\n      entertainment experiences.\n    humanURL: https://business.tivo.com/products-solutions/metadata/tv-movie-metadata-api\n    baseURL: https://data.tivo.com\n    tags:\n      - Entertainment\n      - Metadata\n      - Television\n      - Movies\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://tivo.stoplight.io/docs/video-metadata-api-v3/ZG9jOjQ3NjAxNTk-introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/openapi/tivo-video-metadata-openapi.yml\n      - type: Developer Portal\n        url: https://developers.tivo.com/\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/json-schema/tivo-content-schema.json\n      - type:\
  \ JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/json-structure/tivo-content-structure.json\n      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/json-ld/tivo-context.jsonld\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/rules/tivo-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/capabilities/entertainment-metadata.yaml\n  - aid: tivo:tivo-music-metadata\n    name: TiVo Music Metadata API\n    description: >-\n      The TiVo Music Metadata API provides access to high-quality music information\n      including artist details, album data, track information, and music imagery.\n      Uses the same HTTP-based query structure and JSON response format as the\n      Video Metadata API v3.\n\
  \    humanURL: https://tivo.stoplight.io/docs/music-metadata-api/ZG9jOjQ3NjAxNTk-introduction\n    tags:\n      - Music\n      - Metadata\n      - Entertainment\n    properties:\n      - type: Documentation\n        url: https://tivo.stoplight.io/docs/music-metadata-api/ZG9jOjQ3NjAxNTk-introduction\n      - type: Developer Portal\n        url: https://developers.tivo.com/metadata/\nfeatures:\n  - Content search by multiple metadata fields\n  - ID-based lookup for precise content retrieval\n  - Support for Rovi 1.1, Rovi 2.0, TMDB, and EIDR identifiers\n  - High-quality entertainment imagery\n  - TV series season and episode data\n  - Cast and crew information\n  - Movie and TV show metadata\n  - Music artist, album, and track data\n  - Multi-language metadata support\n  - FTP delivery option for bulk data\nuseCases:\n  - Smart TV content discovery\n  - Streaming platform content enrichment\n  - IPTV guide data\n  - Entertainment recommendation engines\n  - Content catalog management\n\
  \  - EPG (Electronic Program Guide) population\n  - Music service metadata enrichment\nintegrations:\n  - Smart TV platforms\n  - DTS AutoStage automotive platform\n  - IPTV platforms\n  - Streaming services\nsolutions:\n  - Entertainment metadata platform\n  - Content experience enrichment\n  - Smart TV application development\n  - Automotive in-car entertainment\ncommon:\n  - type: Website\n    url: https://business.tivo.com/\n  - type: Documentation\n    url: https://business.tivo.com/products-solutions/metadata/tv-movie-metadata-api\n  - type: Developer Portal\n    url: https://developers.tivo.com/\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/openapi/tivo-video-metadata-openapi.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/json-ld/tivo-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/vocabulary/tivo-vocabulary.yml\n\
  \  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/rules/tivo-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/capabilities/entertainment-metadata.yaml\n  - type: GitHub Organization\n    url: https://github.com/tivo\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/apis.yml
tags:
- Entertainment
- Metadata
- Television
- Movies
- Music
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/apis.yml
use_cases: []
---
