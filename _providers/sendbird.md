---
api_count: 4
api_specs:
- filename: sendbird-platform-openapi.yml
  format: yaml
  label: Sendbird Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sendbird/refs/heads/main/openapi/sendbird-platform-openapi.yml
apis:
- description: The Sendbird Platform API provides server-side access to manage users, channels, messages, and moderation for chat applications. Supports group channels, open channels, direct messages, push notificat
  name: Sendbird Platform API
  slug: ''
- description: The Sendbird Calls API provides voice and video calling capabilities, enabling real-time one-on-one and group calls within applications.
  name: Sendbird Calls API
  slug: ''
- description: The Sendbird Business Messaging API enables omnichannel customer engagement through SMS, WhatsApp, and other messaging channels, supporting customer support and marketing use cases.
  name: Sendbird Business Messaging API
  slug: ''
- description: The Sendbird AI Chatbot API enables building and deploying AI-powered chatbots within chat applications, supporting automated customer support and conversational AI experiences.
  name: Sendbird AI Chatbot API
  slug: ''
capabilities:
- description: Workflow capability for building and managing community chat experiences with Sendbird — covering channel management, user onboarding, message delivery, and community moderation for marketplaces, comm
  name: Sendbird Community Chat
  slug: community-chat
- description: 'Workflow capability for customer support messaging using Sendbird — enabling support teams to manage customer conversations, assign agents, send messages, moderate users, and monitor channel activity '
  name: Sendbird Customer Support Messaging
  slug: customer-support-messaging
common:
- title: ''
  type: Portal
  url: https://sendbird.com/docs/
- title: ''
  type: Authentication
  url: https://sendbird.com/docs/chat/platform-api/v3/authentication
- title: ''
  type: Rate Limits
  url: https://sendbird.com/docs/chat/platform-api/v3/rate-limits
- title: ''
  type: Webhooks
  url: https://sendbird.com/docs/chat/platform-api/v3/webhooks
- title: ''
  type: Changelog
  url: https://sendbird.com/release-notes/
- title: ''
  type: Status
  url: https://status.sendbird.com/
- title: ''
  type: Support
  url: https://sendbird.com/contact-us/
- title: ''
  type: Pricing
  url: https://sendbird.com/pricing/
- title: ''
  type: Blog
  url: https://sendbird.com/blog/
- title: ''
  type: Privacy Policy
  url: https://sendbird.com/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://sendbird.com/terms-of-service/
- title: ''
  type: Website
  url: https://sendbird.com
- title: ''
  type: Dashboard
  url: https://dashboard.sendbird.com/
- title: ''
  type: SpectralRules
  url: rules/sendbird-rules.yml
- title: ''
  type: JSONLDContext
  url: json-ld/sendbird-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/sendbird-vocabulary.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/customer-support-messaging.yaml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/community-chat.yaml
created: '2025-01-14'
description: Sendbird provides APIs and SDKs for in-app chat, voice, video, AI chatbots, and omnichannel business messaging. Used by over 4,000 companies to build real-time communication experiences for customer support, communities, and marketplace platforms.
features: []
image: https://sendbird.com/favicon.ico
integrations: []
jsonld:
- class_count: 11
  name: Sendbird Context
  property_count: 11
  slug: sendbird-context
layout: provider
modified: '2026-05-02'
name: Sendbird
rules:
- name: Sendbird API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: sendbird-rules
skills: []
slug: sendbird
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Sendbird\ndescription: >-\n  Sendbird provides APIs and SDKs for in-app chat, voice, video, AI chatbots,\n  and omnichannel business messaging. Used by over 4,000 companies to build\n  real-time communication experiences for customer support, communities, and\n  marketplace platforms.\nimage: https://sendbird.com/favicon.ico\nurl: https://sendbird.com\ncreated: '2025-01-14'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\napis:\n  - name: Sendbird Platform API\n    description: >-\n      The Sendbird Platform API provides server-side access to manage users, channels,\n      messages, and moderation for chat applications. Supports group channels, open\n      channels, direct messages, push notifications, and webhooks.\n    image: https://sendbird.com/favicon.ico\n    humanURL: https://sendbird.com/docs/chat/platform-api/\n    baseURL: https://api-{application_id}.sendbird.com/v3\n    tags:\n      - Chat\n      - Messaging\n      - Real-Time Communication\n      -\
  \ Push Notifications\n    properties:\n      - type: Documentation\n        url: https://sendbird.com/docs/chat/platform-api/\n      - type: OpenAPI\n        url: openapi/sendbird-platform-openapi.yml\n      - type: Authentication\n        url: https://sendbird.com/docs/chat/platform-api/v3/authentication\n      - type: Rate Limits\n        url: https://sendbird.com/docs/chat/platform-api/v3/rate-limits\n    contact:\n      - FN: Sendbird Support\n        url: https://sendbird.com/contact-us/\n\n  - name: Sendbird Calls API\n    description: >-\n      The Sendbird Calls API provides voice and video calling capabilities,\n      enabling real-time one-on-one and group calls within applications.\n    image: https://sendbird.com/favicon.ico\n    humanURL: https://sendbird.com/docs/calls/\n    baseURL: https://api-{application_id}.sendbird.com/v3\n    tags:\n      - Voice\n      - Video\n      - Calls\n      - Real-Time Communication\n    properties:\n      - type: Documentation\n        url:\
  \ https://sendbird.com/docs/calls/\n    contact:\n      - FN: Sendbird Support\n        url: https://sendbird.com/contact-us/\n\n  - name: Sendbird Business Messaging API\n    description: >-\n      The Sendbird Business Messaging API enables omnichannel customer engagement\n      through SMS, WhatsApp, and other messaging channels, supporting customer\n      support and marketing use cases.\n    image: https://sendbird.com/favicon.ico\n    humanURL: https://sendbird.com/docs/business-messaging/\n    baseURL: https://api-{application_id}.sendbird.com/v3\n    tags:\n      - Business Messaging\n      - Omnichannel\n      - Customer Support\n      - WhatsApp\n      - SMS\n    properties:\n      - type: Documentation\n        url: https://sendbird.com/docs/business-messaging/\n\n  - name: Sendbird AI Chatbot API\n    description: >-\n      The Sendbird AI Chatbot API enables building and deploying AI-powered\n      chatbots within chat applications, supporting automated customer support\n\
  \      and conversational AI experiences.\n    image: https://sendbird.com/favicon.ico\n    humanURL: https://sendbird.com/docs/ai-chatbot/\n    baseURL: https://api-{application_id}.sendbird.com/v3\n    tags:\n      - AI\n      - Chatbot\n      - Customer Support\n      - Automation\n    properties:\n      - type: Documentation\n        url: https://sendbird.com/docs/ai-chatbot/\n\ncommon:\n  - type: Portal\n    url: https://sendbird.com/docs/\n  - type: Authentication\n    url: https://sendbird.com/docs/chat/platform-api/v3/authentication\n  - type: Rate Limits\n    url: https://sendbird.com/docs/chat/platform-api/v3/rate-limits\n  - type: Webhooks\n    url: https://sendbird.com/docs/chat/platform-api/v3/webhooks\n  - type: Changelog\n    url: https://sendbird.com/release-notes/\n  - type: Status\n    url: https://status.sendbird.com/\n  - type: Support\n    url: https://sendbird.com/contact-us/\n  - type: Pricing\n    url: https://sendbird.com/pricing/\n  - type: Blog\n    url: https://sendbird.com/blog/\n\
  \  - type: Privacy Policy\n    url: https://sendbird.com/privacy-policy/\n  - type: Terms of Service\n    url: https://sendbird.com/terms-of-service/\n  - type: Website\n    url: https://sendbird.com\n  - type: Dashboard\n    url: https://dashboard.sendbird.com/\n  - type: SpectralRules\n    url: rules/sendbird-rules.yml\n  - type: JSONLDContext\n    url: json-ld/sendbird-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/sendbird-vocabulary.yml\n  - type: NaftikoCapabilities\n    url: capabilities/customer-support-messaging.yaml\n  - type: NaftikoCapabilities\n    url: capabilities/community-chat.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sendbird/refs/heads/main/apis.yml
tags: []
url: https://sendbird.com
use_cases: []
---
