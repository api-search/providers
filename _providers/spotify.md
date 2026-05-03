---
api_count: 1
api_specs:
- filename: spotify-openapi-original.yml
  format: yaml
  label: Spotify Web API
  slug: spotify-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spotify/refs/heads/main/openapi/spotify-openapi-original.yml
apis:
- description: The Spotify Web API provides RESTful access to Spotify's music and podcast catalog, user library management, playback control, and personalization features. Developers can retrieve metadata for albums
  name: Spotify Web API
  slug: spotify-web-api
capabilities:
- description: Workflow capability for Spotify music discovery, playlist building, and personalization. Enables AI assistants and applications to search the catalog, get recommendations, manage playlists, control pl
  name: Spotify Music Discovery
  slug: music-discovery
common:
- title: ''
  type: Developer
  url: https://developer.spotify.com/
- title: ''
  type: Getting Started
  url: https://developer.spotify.com/documentation/web-api/tutorials/getting-started
- title: ''
  type: Authorization
  url: https://developer.spotify.com/documentation/web-api/concepts/authorization
- title: ''
  type: Rate Limits
  url: https://developer.spotify.com/documentation/web-api/concepts/rate-limits
- title: ''
  type: Scopes
  url: https://developer.spotify.com/documentation/web-api/concepts/scopes
- title: ''
  type: Community
  url: https://developer.spotify.com/community
- title: ''
  type: Embeds
  url: https://developer.spotify.com/documentation/embeds
- title: ''
  type: Terms of Service
  url: https://developer.spotify.com/terms
- title: ''
  type: Login
  url: https://accounts.spotify.com/en/login
- title: ''
  type: Forum
  url: https://community.spotify.com/t5/Spotify-for-Developers/bd-p/Spotify_Developer
- title: ''
  type: Changelog
  url: https://developer.spotify.com/documentation/web-api/references/changes/february-2026
created: '2023-11-15'
description: Spotify is the world's leading music streaming platform with 600M+ users and 100M+ tracks. The Spotify Web API enables developers to discover music and podcasts, manage Spotify libraries, control audio playback, access audio analysis, and build personalized music experiences. Authentication uses OAuth 2.0 with scopes for user-authorized access. The API underwent significant changes in February 2026 with new generic library endpoints and streamlined playlist management.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 54
  name: Spotify Context
  property_count: 1
  slug: spotify-context
layout: provider
modified: '2026-05-02'
name: Spotify
rules:
- name: Spotify API Rules
  rule_count: 14
  severity_counts:
    error: 7
    hint: 0
    info: 3
    warn: 4
  slug: spotify-rules
skills: []
slug: spotify
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spotify\nname: Spotify\ndescription: >-\n  Spotify is the world's leading music streaming platform with 600M+ users and 100M+ tracks.\n  The Spotify Web API enables developers to discover music and podcasts, manage Spotify libraries,\n  control audio playback, access audio analysis, and build personalized music experiences.\n  Authentication uses OAuth 2.0 with scopes for user-authorized access. The API underwent\n  significant changes in February 2026 with new generic library endpoints and streamlined\n  playlist management.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Music\n  - Audio\n  - Streaming\n  - Podcasts\n  - Playlists\ncreated: '2023-11-15'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/spotify/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: spotify:spotify-web-api\n    name: Spotify Web API\n    description:\
  \ >-\n      The Spotify Web API provides RESTful access to Spotify's music and podcast catalog,\n      user library management, playback control, and personalization features. Developers\n      can retrieve metadata for albums, artists, tracks, shows, and episodes; manage user\n      playlists and saved libraries; control playback on connected devices; and access\n      audio analysis and recommendations. OAuth 2.0 authentication supports Authorization\n      Code Flow, PKCE, and Client Credentials flows.\n    humanURL: https://developer.spotify.com/documentation/web-api\n    baseURL: https://api.spotify.com/v1\n    tags:\n      - Albums\n      - Artists\n      - Tracks\n      - Playlists\n      - Player\n      - Search\n      - Podcasts\n      - Library\n      - Recommendations\n      - Audio Analysis\n    properties:\n      - type: Documentation\n        url: https://developer.spotify.com/documentation/web-api\n      - type: OpenAPI\n        url: openapi/spotify-openapi-original.yml\n\
  \      - type: Getting Started\n        url: https://developer.spotify.com/documentation/web-api/tutorials/getting-started\n      - type: Authorization\n        url: https://developer.spotify.com/documentation/web-api/concepts/authorization\n      - type: Rate Limits\n        url: https://developer.spotify.com/documentation/web-api/concepts/rate-limits\n      - type: Scopes\n        url: https://developer.spotify.com/documentation/web-api/concepts/scopes\n      - type: JSONSchema\n        url: json-schema/spotify-track-schema.json\n      - type: JSONSchema\n        url: json-schema/spotify-playlist-schema.json\n      - type: JSONStructure\n        url: json-structure/spotify-track-structure.json\n      - type: JSONLD\n        url: json-ld/spotify-context.jsonld\n      - type: SpectralRules\n        url: rules/spotify-rules.yml\n      - type: Capabilities\n        url: capabilities/music-discovery.yaml\n      - type: Vocabulary\n        url: vocabulary/spotify-vocabulary.yml\n    features:\n\
  \      - type: MusicCatalog\n        description: Search and retrieve metadata for 100M+ tracks, albums, and artists\n      - type: PlaybackControl\n        description: Control Spotify playback on any connected device via API\n      - type: LibraryManagement\n        description: Save, remove, and manage user's music library with generic URI-based endpoints\n      - type: PlaylistManagement\n        description: Create, update, and manage playlists; add, reorder, and remove items\n      - type: AudioAnalysis\n        description: Access beat-by-beat audio analysis including tempo, key, and energy\n      - type: Recommendations\n        description: Generate personalized track recommendations based on seeds and audio features\n      - type: Personalization\n        description: Access user's top artists and tracks over multiple time ranges\n      - type: PodcastsAudiobooks\n        description: Stream and manage shows, episodes, and audiobooks\n    useCases:\n      - type: MusicDiscovery\n\
  \        description: Build recommendation engines and music discovery experiences\n      - type: PlaylistBuilding\n        description: Create collaborative or AI-generated playlists\n      - type: PartyMode\n        description: Control music playback at events, restaurants, or shared spaces\n      - type: MusicAnalytics\n        description: Analyze listening patterns and audio characteristics\n      - type: DeviceControl\n        description: Remote control Spotify playback from companion apps\ncommon:\n  - url: https://developer.spotify.com/\n    type: Developer\n  - url: https://developer.spotify.com/documentation/web-api/tutorials/getting-started\n    type: Getting Started\n  - url: https://developer.spotify.com/documentation/web-api/concepts/authorization\n    type: Authorization\n  - url: https://developer.spotify.com/documentation/web-api/concepts/rate-limits\n    type: Rate Limits\n  - url: https://developer.spotify.com/documentation/web-api/concepts/scopes\n    type: Scopes\n\
  \  - url: https://developer.spotify.com/community\n    type: Community\n  - url: https://developer.spotify.com/documentation/embeds\n    type: Embeds\n  - url: https://developer.spotify.com/terms\n    type: Terms of Service\n  - url: https://accounts.spotify.com/en/login\n    type: Login\n  - url: https://community.spotify.com/t5/Spotify-for-Developers/bd-p/Spotify_Developer\n    type: Forum\n  - url: https://developer.spotify.com/documentation/web-api/references/changes/february-2026\n    type: Changelog\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spotify/refs/heads/main/apis.yml
tags:
- Music
- Audio
- Streaming
- Podcasts
- Playlists
url: https://raw.githubusercontent.com/api-evangelist/spotify/refs/heads/main/apis.yml
use_cases: []
---
