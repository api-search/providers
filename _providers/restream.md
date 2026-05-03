---
api_count: 3
api_specs:
- filename: restream-openapi.yml
  format: yaml
  label: Restream API
  slug: restream-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/openapi/restream-openapi.yml
apis:
- description: REST API for managing Restream channels, stream keys, events, and user profiles. Uses OAuth2 authorization code flow for authentication with scopes for profile, channels, streams, events, and chat. Ba
  name: Restream API
  slug: restream-api
- description: 'WebSocket API for real-time streaming status updates. Connect to wss://streaming.api.restream.io/ws with an OAuth access token to receive incoming and outgoing stream events, platform status updates, '
  name: Restream Streaming Updates API
  slug: restream-streaming-updates-api
- description: 'WebSocket API for accessing and managing Restream Chat. Receive real-time chat messages from all connected streaming platforms (Twitch, YouTube, Facebook, Discord, LinkedIn, DLive) in a unified event '
  name: Restream Chat API
  slug: restream-chat-api
capabilities:
- description: Unified workflow capability for managing live multistreaming operations. Combines Restream REST API capabilities for channel configuration, event lifecycle management, stream key retrieval, and platfo
  name: Restream Multistream Management
  slug: multistream-management
common:
- title: ''
  type: TermsOfService
  url: https://restream.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://restream.io/privacy
- title: ''
  type: SignUp
  url: https://app.restream.io/sign-up
- title: ''
  type: Login
  url: https://app.restream.io/login
- title: ''
  type: Blog
  url: https://restream.io/blog
- title: ''
  type: Pricing
  url: https://restream.io/pricing
- title: ''
  type: Website
  url: https://restream.io
- title: ''
  type: Developer Portal
  url: https://developers.restream.io
- title: ''
  type: Authentication
  url: https://developers.restream.io/guide/getting-started
- title: ''
  type: GitHub Organization
  url: https://github.com/restreamio
created: '2025-03-15'
description: Restream is a multistreaming platform that enables content creators and businesses to simultaneously broadcast live video to 30+ platforms including YouTube, Twitch, Facebook, LinkedIn, and more. The platform offers REST APIs and WebSocket connections for managing streams, channels, events, and chat.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Restream Context
  property_count: 6
  slug: restream-context
layout: provider
modified: '2026-05-02'
name: Restream
rules:
- name: Restream API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: restream-rules
skills: []
slug: restream
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: restream\nname: Restream\ndescription: >-\n  Restream is a multistreaming platform that enables content creators and\n  businesses to simultaneously broadcast live video to 30+ platforms including\n  YouTube, Twitch, Facebook, LinkedIn, and more. The platform offers REST APIs\n  and WebSocket connections for managing streams, channels, events, and chat.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Broadcast\n  - Chat\n  - Content Delivery\n  - Live Streaming\n  - Multistreaming\n  - Video Streaming\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/apis.yml\ncreated: '2025-03-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: restream:restream-api\n    name: Restream API\n    description: >-\n      REST API for managing Restream channels, stream keys, events, and user\n      profiles. Uses OAuth2 authorization code flow for authentication with\n    \
  \  scopes for profile, channels, streams, events, and chat. Base URL is\n      https://api.restream.io/v2.\n    humanURL: https://developers.restream.io\n    baseURL: https://api.restream.io/v2\n    tags:\n      - Channels\n      - Events\n      - Live Video\n      - OAuth2\n      - Streaming\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developers.restream.io/docs\n      - type: Authentication\n        url: https://developers.restream.io/guide/getting-started\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/openapi/restream-openapi.yml\n  - aid: restream:restream-streaming-updates-api\n    name: Restream Streaming Updates API\n    description: >-\n      WebSocket API for real-time streaming status updates. Connect to\n      wss://streaming.api.restream.io/ws with an OAuth access token to receive\n      incoming and outgoing stream events, platform status updates, and viewer\n\
  \      counts in real time.\n    humanURL: https://developers.restream.io/private-api/streaming-updates\n    baseURL: wss://streaming.api.restream.io\n    tags:\n      - Real-Time\n      - Streaming\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://developers.restream.io/private-api/streaming-updates\n  - aid: restream:restream-chat-api\n    name: Restream Chat API\n    description: >-\n      WebSocket API for accessing and managing Restream Chat. Receive real-time\n      chat messages from all connected streaming platforms (Twitch, YouTube,\n      Facebook, Discord, LinkedIn, DLive) in a unified event stream. Supports\n      reply and relay actions.\n    humanURL: https://developers.restream.io/chat/getting-started\n    baseURL: wss://chat.api.restream.io\n    tags:\n      - Chat\n      - Real-Time\n      - Streaming\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://developers.restream.io/chat/getting-started\n\
  common:\n  - type: TermsOfService\n    url: https://restream.io/terms\n  - type: PrivacyPolicy\n    url: https://restream.io/privacy\n  - type: SignUp\n    url: https://app.restream.io/sign-up\n  - type: Login\n    url: https://app.restream.io/login\n  - type: Blog\n    url: https://restream.io/blog\n  - type: Pricing\n    url: https://restream.io/pricing\n  - type: Website\n    url: https://restream.io\n  - type: Developer Portal\n    url: https://developers.restream.io\n  - type: Authentication\n    url: https://developers.restream.io/guide/getting-started\n  - type: GitHub Organization\n    url: https://github.com/restreamio\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/apis.yml
tags:
- Broadcast
- Chat
- Content Delivery
- Live Streaming
- Multistreaming
- Video Streaming
url: https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/apis.yml
use_cases: []
---
