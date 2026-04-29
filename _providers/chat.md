---
api_count: 1
api_specs:
- filename: chat-reference-openapi.yml
  format: yaml
  label: Reference Chat API
  slug: reference-chat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/openapi/chat-reference-openapi.yml
apis:
- description: Reference REST API shape for chat platforms covering conversation lifecycle (create/list/get), message send and history, participant management, and typing indicator events. Intended as a vocabulary a
  name: Reference Chat API
  slug: reference-chat-api
common:
- title: ''
  type: Repository
  url: https://github.com/api-evangelist/chat
- title: ''
  type: Catalog
  url: https://apis.json/
- title: ''
  type: JSONLD
  url: json-ld/chat-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/chat-conversation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/chat-message-schema.json
created: '2024-01-15'
description: Topic-level profile capturing the Chat API category in the API Evangelist network. This profile defines a reference vocabulary and a generic OpenAPI shape for chat APIs that manage conversations, messages, and participants, and is used as a baseline when cataloguing chat platform APIs (such as Slack, Discord, Microsoft Teams, Twilio Conversations, and conversational AI platforms) into the broader catalogue.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Chat Context
  property_count: 3
  slug: chat-context
layout: provider
modified: '2026-04-23'
name: Chat
skills: []
slug: chat
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: chat\nname: Chat\ndescription: >-\n  Topic-level profile capturing the Chat API category in the API Evangelist\n  network. This profile defines a reference vocabulary and a generic OpenAPI\n  shape for chat APIs that manage conversations, messages, and participants,\n  and is used as a baseline when cataloguing chat platform APIs (such as\n  Slack, Discord, Microsoft Teams, Twilio Conversations, and conversational\n  AI platforms) into the broader catalogue.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/apis.yml\ntype: Topic\naccess: 3rd-Party\nposition: Reference\ntags:\n  - Chat\n  - Conversational AI\n  - Conversations\n  - Customer Support\n  - Messaging\n  - Real-time\ncreated: '2024-01-15'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: chat:reference-chat-api\n    name: Reference Chat API\n    description: >-\n      Reference\
  \ REST API shape for chat platforms covering conversation\n      lifecycle (create/list/get), message send and history, participant\n      management, and typing indicator events. Intended as a vocabulary\n      and OpenAPI baseline for cataloguing concrete chat platform APIs.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/api-evangelist/chat\n    baseURL: https://api.example.com/v1/chat\n    tags:\n      - Chat\n      - Conversations\n      - Messaging\n    properties:\n      - type: OpenAPI\n        url: openapi/chat-reference-openapi.yml\n      - type: Spectral\n        url: spectral/chat-spectral.yml\n      - type: NaftikoCapabilities\n        url: naftiko/chat-capabilities.yml\ncommon:\n  - type: Repository\n    url: https://github.com/api-evangelist/chat\n  - type: Catalog\n    url: https://apis.json/\n  - type: JSONLD\n    url: json-ld/chat-context.jsonld\n  - type: JSONSchema\n    url: json-schema/chat-conversation-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/chat-message-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/apis.yml
tags:
- Chat
- Conversational AI
- Conversations
- Customer Support
- Messaging
- Real-time
url: https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/apis.yml
use_cases: []
---
