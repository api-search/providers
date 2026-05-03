---
api_count: 1
api_specs:
- filename: songstats-openapi.yml
  format: yaml
  label: Songstats Enterprise API
  slug: songstats-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/openapi/songstats-openapi.yml
apis:
- description: The Songstats Enterprise API (v1) provides music data analytics for artists, tracks, labels, and collaborators. Endpoints return JSON data including current stats, historic stats, audience details, ca
  name: Songstats Enterprise API
  slug: songstats-enterprise-api
capabilities:
- description: Workflow capability for music industry analytics using the Songstats Enterprise API. Provides streaming performance monitoring, audience insights, catalog management, and playlist tracking for artists
  name: Songstats Music Analytics
  slug: music-analytics
common:
- title: ''
  type: Portal
  url: https://songstats.com/for/developers
- title: ''
  type: Documentation
  url: https://docs.songstats.com/
- title: ''
  type: Website
  url: https://songstats.com/
- title: ''
  type: GitHub
  url: https://github.com/Songstats
- title: ''
  type: Blog
  url: https://lab.songstats.com/
- title: ''
  type: SignUp
  url: https://songstats.com/for/developers
created: '2025-02-12'
description: Songstats provides music data analytics through its Enterprise API, enabling music industry professionals to access streaming statistics, audience data, chart positions, playlist placements, and catalog information for artists, tracks, record labels, and collaborators across all major streaming platforms including Spotify, Apple Music, Amazon Music, Deezer, TikTok, and more. Integrated with Radiostats for radio airplay data across 40,000+ stations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Songstats Context
  property_count: 13
  slug: songstats-context
layout: provider
modified: '2026-05-02'
name: Songstats
rules:
- name: Songstats API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 5
  slug: songstats-rules
skills: []
slug: songstats
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: songstats\nname: Songstats\ndescription: >-\n  Songstats provides music data analytics through its Enterprise API, enabling\n  music industry professionals to access streaming statistics, audience data,\n  chart positions, playlist placements, and catalog information for artists, tracks,\n  record labels, and collaborators across all major streaming platforms including\n  Spotify, Apple Music, Amazon Music, Deezer, TikTok, and more. Integrated with\n  Radiostats for radio airplay data across 40,000+ stations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Music\n  - Streaming\n  - Artists\n  - Tracks\n  - Labels\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/apis.yml\ncreated: '2025-02-12'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: songstats:songstats-enterprise-api\n    name: Songstats Enterprise\
  \ API\n    description: >-\n      The Songstats Enterprise API (v1) provides music data analytics for artists,\n      tracks, labels, and collaborators. Endpoints return JSON data including current\n      stats, historic stats, audience details, catalog information, activities, top\n      playlists, top tracks, and geographic location data across major streaming\n      platforms. Authentication uses an API key in the request header. Includes\n      Radiostats integration for radio airplay data.\n    humanURL: https://docs.songstats.com/\n    baseURL: https://api.songstats.com/enterprise/v1\n    tags:\n      - Analytics\n      - Music\n      - Streaming\n      - Artists\n      - Tracks\n      - Labels\n      - Collaborators\n    properties:\n      - type: Documentation\n        url: https://docs.songstats.com/\n      - type: Reference\n        url: https://docs.songstats.com/docs/api/e80265bb8b01b-songstats-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/openapi/songstats-openapi.yml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/json-schema/songstats-artist-schema.json\n    contact:\n      - FN: Songstats API Support\n        email: api@songstats.com\n        url: https://songstats.com/for/developers\ncommon:\n  - type: Portal\n    url: https://songstats.com/for/developers\n  - type: Documentation\n    url: https://docs.songstats.com/\n  - type: Website\n    url: https://songstats.com/\n  - type: GitHub\n    url: https://github.com/Songstats\n  - type: Blog\n    url: https://lab.songstats.com/\n  - type: SignUp\n    url: https://songstats.com/for/developers\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/apis.yml
tags:
- Analytics
- Music
- Streaming
- Artists
- Tracks
- Labels
url: https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/apis.yml
use_cases: []
---
