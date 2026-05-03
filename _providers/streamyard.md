---
api_count: 1
api_specs:
- filename: streamyard-openapi.yml
  format: yaml
  label: StreamYard API
  slug: streamyard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/openapi/streamyard-openapi.yml
apis:
- description: The StreamYard API provides programmatic access to manage live broadcasts and recordings. Create and manage broadcasts, add streaming destinations (YouTube, Facebook, LinkedIn, Twitch, Twitter/X, cust
  name: StreamYard API
  slug: streamyard-api
capabilities:
- description: 'Unified capability for managing StreamYard live streaming and recording operations. Designed for content creators, media teams, and broadcast automation platforms. Covers the full broadcast lifecycle '
  name: StreamYard Live Streaming
  slug: live-streaming
common:
- title: ''
  type: Website
  url: https://streamyard.com
- title: ''
  type: Developer Portal
  url: https://developers.streamyard.com
- title: ''
  type: Documentation
  url: https://developers.streamyard.com/docs
- title: ''
  type: Dashboard
  url: https://streamyard.com/dashboard
- title: ''
  type: Sign Up
  url: https://streamyard.com/signup
- title: ''
  type: Login
  url: https://streamyard.com/login
- title: ''
  type: Pricing
  url: https://streamyard.com/pricing
- title: ''
  type: Blog
  url: https://streamyard.com/blog
- title: ''
  type: Terms of Service
  url: https://streamyard.com/resources/terms
- title: ''
  type: Privacy Policy
  url: https://streamyard.com/resources/privacy
- title: ''
  type: Status
  url: https://status.streamyard.com
- title: ''
  type: Support
  url: https://streamyard.com/resources/support
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/openapi/streamyard-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/json-schema/streamyard-broadcast-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/json-ld/streamyard-context.jsonld
created: '2024-01-01'
description: StreamYard is a professional live streaming and recording studio in the browser. Stream directly to multiple platforms simultaneously including YouTube, Facebook, LinkedIn, Twitch, and Twitter/X. Interview remote guests, share screens, display overlays, and manage brand assets. The StreamYard API enables programmatic management of broadcasts, destinations, and recordings.
features: []
image: https://streamyard.com/assets/images/logo.png
integrations: []
jsonld:
- class_count: 0
  name: Streamyard Context
  property_count: 3
  slug: streamyard-context
layout: provider
modified: '2026-05-02'
name: StreamYard
rules:
- name: StreamYard API Rules
  rule_count: 9
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 6
  slug: streamyard-rules
skills: []
slug: streamyard
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: streamyard\nname: StreamYard\ndescription: >-\n  StreamYard is a professional live streaming and recording studio in the\n  browser. Stream directly to multiple platforms simultaneously including\n  YouTube, Facebook, LinkedIn, Twitch, and Twitter/X. Interview remote guests,\n  share screens, display overlays, and manage brand assets. The StreamYard API\n  enables programmatic management of broadcasts, destinations, and recordings.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/apis.yml\nimage: https://streamyard.com/assets/images/logo.png\ntags:\n  - Broadcasting\n  - Live Streaming\n  - Multi-Streaming\n  - Recordings\n  - Video\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: streamyard:streamyard-api\n    name: StreamYard API\n    description: >-\n      The StreamYard API provides programmatic access to manage live broadcasts\n \
  \     and recordings. Create and manage broadcasts, add streaming destinations\n      (YouTube, Facebook, LinkedIn, Twitch, Twitter/X, custom RTMP), access\n      recordings, and manage connected destination accounts. Authentication\n      uses OAuth 2.0 with scope-based access control.\n    humanURL: https://developers.streamyard.com/docs\n    baseURL: https://api.streamyard.com\n    tags:\n      - Broadcasting\n      - Live Streaming\n      - Multi-Streaming\n      - Recordings\n      - Video\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/openapi/streamyard-openapi.yml\n      - type: Documentation\n        url: https://developers.streamyard.com/docs\n      - type: Authentication\n        url: https://developers.streamyard.com/docs/authentication\n      - type: OpenAPI\n        url: https://api.streamyard.com/openapi.json\ncommon:\n  - type: Website\n    url: https://streamyard.com\n  - type:\
  \ Developer Portal\n    url: https://developers.streamyard.com\n  - type: Documentation\n    url: https://developers.streamyard.com/docs\n  - type: Dashboard\n    url: https://streamyard.com/dashboard\n  - type: Sign Up\n    url: https://streamyard.com/signup\n  - type: Login\n    url: https://streamyard.com/login\n  - type: Pricing\n    url: https://streamyard.com/pricing\n  - type: Blog\n    url: https://streamyard.com/blog\n  - type: Terms of Service\n    url: https://streamyard.com/resources/terms\n  - type: Privacy Policy\n    url: https://streamyard.com/resources/privacy\n  - type: Status\n    url: https://status.streamyard.com\n  - type: Support\n    url: https://streamyard.com/resources/support\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/openapi/streamyard-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/json-schema/streamyard-broadcast-schema.json\n\
  \  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/json-ld/streamyard-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/apis.yml
tags:
- Broadcasting
- Live Streaming
- Multi-Streaming
- Recordings
- Video
url: https://raw.githubusercontent.com/api-evangelist/streamyard/refs/heads/main/apis.yml
use_cases: []
---
