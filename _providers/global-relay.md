---
api_count: 4
api_specs:
- filename: global-relay-conversation-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Conversation Archiving API
  slug: conversation-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-conversation-archiving-api-openapi.yml
- filename: global-relay-email-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Email Archiving API
  slug: email-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-email-archiving-api-openapi.yml
- filename: global-relay-voice-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Voice Archiving API
  slug: voice-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-voice-archiving-api-openapi.yml
- filename: global-relay-event-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Event Archiving API
  slug: event-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-event-archiving-api-openapi.yml
apis:
- description: The Global Relay Conversation Archiving API provides a RESTful interface to seamlessly integrate messaging platforms with the Global Relay Archive. It enables secure capture and preservation of one-to
  name: Global Relay Conversation Archiving API
  slug: conversation-archiving-api
- description: The Global Relay Email Archiving API provides a RESTful interface to capture and archive email content and metadata into the Global Relay Archive. It supports archiving emails with attachments, header
  name: Global Relay Email Archiving API
  slug: email-archiving-api
- description: The Global Relay Voice Archiving API provides a RESTful interface to capture and archive audio and video recordings, including call recordings and meeting recordings, into the Global Relay Archive. Th
  name: Global Relay Voice Archiving API
  slug: voice-archiving-api
- description: 'The Global Relay Event Archiving API (EventFeed) provides a RESTful interface to integrate collaboration platforms, customer experience tools, and social media sites with the Global Relay Archive. It '
  name: Global Relay Event Archiving API
  slug: event-archiving-api
common:
- title: ''
  type: Portal
  url: https://developers.globalrelay.com/
- title: ''
  type: Documentation
  url: https://www.globalrelay.com/connector/conversation-archiving-api/
- title: ''
  type: Documentation
  url: https://www.globalrelay.com/connector/eventfeed-archiving-api/
- title: ''
  type: Documentation
  url: https://www.globalrelay.com/connector/voice-archiving-api/
created: '2025-01-01'
description: Global Relay is an enterprise-grade archiving and compliance platform for electronic communications including email, instant messaging, voice, video, and collaboration tools across regulated industries. It provides APIs for archiving conversations, emails, voice recordings, and event feeds from social media and collaboration platforms, ensuring organizations meet their compliance and regulatory requirements through secure, tamper-proof archiving with OAuth 2.0 authenticated REST APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 31
  name: Global Relay Context
  property_count: 15
  slug: global-relay-context
layout: provider
modified: '2026-04-28'
name: Global Relay
skills: []
slug: global-relay
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: global-relay\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/apis.yml\napis:\n  - aid: global-relay:conversation-archiving-api\n    name: Global Relay Conversation Archiving API\n    tags:\n      - Archiving\n      - Compliance\n      - Messaging\n    humanURL: https://developers.globalrelay.com/api/conversation-archiving-api/\n    properties:\n      - url: https://developers.globalrelay.com/api/conversation-archiving-api/\n        type: Documentation\n      - url: openapi/global-relay-conversation-archiving-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Global Relay Conversation Archiving API provides a RESTful interface\n      to seamlessly integrate messaging platforms with the Global Relay Archive.\n      It enables secure capture and preservation of one-to-one or multi-party\n      conversations, including text messages, file attachments, reactions, edits,\n      and deletions. The API uses OAuth 2.0\
  \ Client Credentials authentication\n      and is rate limited to 1000 requests per minute for conversations and 100\n      per minute for files.\n  - aid: global-relay:email-archiving-api\n    name: Global Relay Email Archiving API\n    tags:\n      - Archiving\n      - Compliance\n      - Email\n    humanURL: https://developers.globalrelay.com/api/email-archiving-api/\n    properties:\n      - url: https://developers.globalrelay.com/api/email-archiving-api/\n        type: Documentation\n      - url: openapi/global-relay-email-archiving-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Global Relay Email Archiving API provides a RESTful interface to\n      capture and archive email content and metadata into the Global Relay\n      Archive. It supports archiving emails with attachments, headers, and full\n      message structure for compliance and regulatory requirements. Rate limited\n      to 1000 requests per minute for emails and 100 per minute for files.\n  -\
  \ aid: global-relay:voice-archiving-api\n    name: Global Relay Voice Archiving API\n    tags:\n      - Archiving\n      - Compliance\n      - Voice\n    humanURL: https://developers.globalrelay.com/api/voice-archiving-api/\n    properties:\n      - url: https://developers.globalrelay.com/api/voice-archiving-api/\n        type: Documentation\n      - url: openapi/global-relay-voice-archiving-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Global Relay Voice Archiving API provides a RESTful interface to\n      capture and archive audio and video recordings, including call recordings\n      and meeting recordings, into the Global Relay Archive. The API ensures all\n      voice and video communications are securely preserved for compliance. The\n      maximum data payload per request is 3.5MB excluding file attachments.\n  - aid: global-relay:event-archiving-api\n    name: Global Relay Event Archiving API\n    tags:\n      - Archiving\n      - Collaboration\n      -\
  \ Compliance\n      - Social Media\n    humanURL: https://developers.globalrelay.com/api/event-archiving-api/\n    properties:\n      - url: https://developers.globalrelay.com/api/event-archiving-api/\n        type: Documentation\n      - url: openapi/global-relay-event-archiving-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Global Relay Event Archiving API (EventFeed) provides a RESTful\n      interface to integrate collaboration platforms, customer experience tools,\n      and social media sites with the Global Relay Archive. It enables secure\n      capture of event-based data including posts, comments, reactions, and\n      activity feeds from various digital channels for compliance archiving.\nname: Global Relay\ntags:\n  - Archiving\n  - Compliance\n  - Data Retention\n  - Email Security\n  - Regulatory Compliance\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://developers.globalrelay.com/\n\
  \    name: Global Relay Developers\n    type: Portal\n    description: 'null'\n  - url: https://www.globalrelay.com/connector/conversation-archiving-api/\n    name: Conversation Archiving\n    type: Documentation\n    description: 'null'\n  - url: https://www.globalrelay.com/connector/eventfeed-archiving-api/\n    name: Event Feed Archiving\n    type: Documentation\n    description: 'null'\n  - url: https://www.globalrelay.com/connector/voice-archiving-api/\n    name: Voice Archiving\n    type: Documentation\n    description: 'null'\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Global Relay is an enterprise-grade archiving and compliance platform for\n  electronic communications including email, instant messaging, voice, video,\n  and collaboration tools across regulated industries. It provides APIs for\n  archiving conversations, emails, voice recordings, and event feeds from\n  social media and collaboration platforms, ensuring organizations meet\
  \ their\n  compliance and regulatory requirements through secure, tamper-proof archiving\n  with OAuth 2.0 authenticated REST APIs.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/apis.yml
tags:
- Archiving
- Compliance
- Data Retention
- Email Security
- Regulatory Compliance
url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/apis.yml
use_cases: []
---
