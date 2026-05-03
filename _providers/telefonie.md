---
api_count: 4
api_specs:
- filename: telefonie-voice-openapi.yml
  format: yaml
  label: Telefonie Voice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-voice-openapi.yml
- filename: telefonie-sms-openapi.yml
  format: yaml
  label: Telefonie SMS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-sms-openapi.yml
- filename: telefonie-numbers-openapi.yml
  format: yaml
  label: Telefonie Number Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-numbers-openapi.yml
- filename: telefonie-recording-openapi.yml
  format: yaml
  label: Telefonie Call Recording API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/openapi/telefonie-recording-openapi.yml
apis:
- description: Make, receive, and control phone calls programmatically. Supports outbound dialing, inbound call handling, call routing, IVR (Interactive Voice Response), call transfer, conferencing, and real-time ca
  name: Telefonie Voice API
  slug: ''
- description: Send and receive SMS and MMS messages globally. Supports one-way notifications, two-way conversations, bulk messaging, unicode (international character sets), delivery receipts, inbound message webhoo
  name: Telefonie SMS API
  slug: ''
- description: Search, purchase, configure, and manage phone numbers across multiple countries and number types (local, national, toll-free, mobile). Supports number portability (LNP), number lookup, capabilities ch
  name: Telefonie Number Management API
  slug: ''
- description: Record, store, and retrieve call recordings. Supports dual-channel recording, on-demand recording, automatic recording, transcription, storage management, compliance archiving, and secure download URL
  name: Telefonie Call Recording API
  slug: ''
capabilities:
- description: Unified capability combining Telefonie Voice and SMS APIs for comprehensive communications workflows. Enables voice calling, SMS messaging, conferencing, and call recording from a single interface. De
  name: Telefonie Communications
  slug: telephony-communications
common:
- title: ''
  type: Authentication
  url: https://developers.telefonie.com/authentication
- title: ''
  type: Getting Started
  url: https://developers.telefonie.com/getting-started
- title: ''
  type: Rate Limits
  url: https://developers.telefonie.com/rate-limits
- title: ''
  type: SDKs
  url: https://www.telefonie.com/sdks
- title: ''
  type: Status
  url: https://status.telefonie.com
- title: ''
  type: Terms of Service
  url: https://www.telefonie.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.telefonie.com/privacy
- title: ''
  type: Sign Up
  url: https://www.telefonie.com/signup
- title: ''
  type: Login
  url: https://www.telefonie.com/login
- title: ''
  type: Blog
  url: https://blog.telefonie.com
- title: ''
  type: Pricing
  url: https://www.telefonie.com/pricing
- title: ''
  type: Change Log
  url: https://developers.telefonie.com/changelog
- title: ''
  type: GitHub
  url: https://github.com/telefonie
created: '2024-01-20'
description: Telefonie is a cloud communications platform providing programmable telephony, voice, SMS, and number management APIs for developers and businesses. The platform enables developers to build voice calling, SMS messaging, number provisioning, and call recording capabilities into their applications. Telefonie supports WebRTC, SIP trunking, and REST APIs for building modern communication workflows.
features: []
image: https://www.telefonie.com/logo.png
integrations: []
jsonld:
- class_count: 5
  name: Telefonie Context
  property_count: 21
  slug: telefonie-context
layout: provider
modified: '2026-05-03'
name: Telefonie
rules:
- name: Telefonie API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 4
    warn: 4
  slug: telefonie-rules
skills: []
slug: telefonie
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Telefonie\ndescription: >-\n  Telefonie is a cloud communications platform providing programmable telephony,\n  voice, SMS, and number management APIs for developers and businesses. The platform\n  enables developers to build voice calling, SMS messaging, number provisioning,\n  and call recording capabilities into their applications. Telefonie supports\n  WebRTC, SIP trunking, and REST APIs for building modern communication workflows.\nimage: https://www.telefonie.com/logo.png\nurl: https://www.telefonie.com\ntype: Index\ntags:\n  - Call Recording\n  - CPaaS\n  - Messaging\n  - Number Provisioning\n  - SMS\n  - Telecommunications\n  - Telephony\n  - Voice\n  - VoIP\ncreated: '2024-01-20'\nmodified: '2026-05-03'\napis:\n  - name: Telefonie Voice API\n    description: >-\n      Make, receive, and control phone calls programmatically. Supports outbound\n      dialing, inbound call handling, call routing, IVR (Interactive Voice Response),\n      call transfer, conferencing,\
  \ and real-time call control via REST and WebSockets.\n    image: https://www.telefonie.com/images/voice-api.png\n    humanURL: https://developers.telefonie.com/voice\n    baseURL: https://api.telefonie.com/v1/voice\n    tags:\n      - Calls\n      - Conferencing\n      - IVR\n      - Outbound Calling\n      - Telephony\n      - Voice\n      - VoIP\n      - WebRTC\n    properties:\n      - type: Documentation\n        url: https://developers.telefonie.com/voice\n      - type: OpenAPI\n        url: openapi/telefonie-voice-openapi.yml\n      - type: Authentication\n        url: https://developers.telefonie.com/authentication\n      - type: GettingStarted\n        url: https://developers.telefonie.com/getting-started\n      - type: Pricing\n        url: https://www.telefonie.com/pricing/voice\n      - type: RateLimits\n        url: https://developers.telefonie.com/rate-limits\n    contact:\n      - type: Support\n        url: https://www.telefonie.com/support\n      - type: Email\n      \
  \  url: mailto:support@telefonie.com\n\n  - name: Telefonie SMS API\n    description: >-\n      Send and receive SMS and MMS messages globally. Supports one-way notifications,\n      two-way conversations, bulk messaging, unicode (international character sets),\n      delivery receipts, inbound message webhooks, and long message concatenation.\n    image: https://www.telefonie.com/images/sms-api.png\n    humanURL: https://developers.telefonie.com/sms\n    baseURL: https://api.telefonie.com/v1/sms\n    tags:\n      - Bulk SMS\n      - Delivery Receipts\n      - Messaging\n      - MMS\n      - SMS\n      - Text Messages\n      - Two-Way Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.telefonie.com/sms\n      - type: OpenAPI\n        url: openapi/telefonie-sms-openapi.yml\n      - type: Authentication\n        url: https://developers.telefonie.com/authentication\n      - type: Pricing\n        url: https://www.telefonie.com/pricing/sms\n      - type:\
  \ RateLimits\n        url: https://developers.telefonie.com/rate-limits\n    contact:\n      - type: Support\n        url: https://www.telefonie.com/support\n      - type: Email\n        url: mailto:support@telefonie.com\n\n  - name: Telefonie Number Management API\n    description: >-\n      Search, purchase, configure, and manage phone numbers across multiple\n      countries and number types (local, national, toll-free, mobile). Supports\n      number portability (LNP), number lookup, capabilities checking, and\n      configuring inbound call/SMS routing for numbers.\n    image: https://www.telefonie.com/images/numbers-api.png\n    humanURL: https://developers.telefonie.com/numbers\n    baseURL: https://api.telefonie.com/v1/numbers\n    tags:\n      - DID\n      - LNP\n      - Number Portability\n      - Number Provisioning\n      - Phone Numbers\n      - Toll-Free\n    properties:\n      - type: Documentation\n        url: https://developers.telefonie.com/numbers\n      - type: OpenAPI\n\
  \        url: openapi/telefonie-numbers-openapi.yml\n      - type: Authentication\n        url: https://developers.telefonie.com/authentication\n      - type: Pricing\n        url: https://www.telefonie.com/pricing/numbers\n    contact:\n      - type: Support\n        url: https://www.telefonie.com/support\n\n  - name: Telefonie Call Recording API\n    description: >-\n      Record, store, and retrieve call recordings. Supports dual-channel recording,\n      on-demand recording, automatic recording, transcription, storage management,\n      compliance archiving, and secure download URLs. Recordings are stored in\n      MP3 and WAV formats with configurable retention policies.\n    image: https://www.telefonie.com/images/recording-api.png\n    humanURL: https://developers.telefonie.com/recording\n    baseURL: https://api.telefonie.com/v1/recordings\n    tags:\n      - Archiving\n      - Compliance\n      - Dual Channel\n      - Recording\n      - Storage\n      - Transcription\n    properties:\n\
  \      - type: Documentation\n        url: https://developers.telefonie.com/recording\n      - type: OpenAPI\n        url: openapi/telefonie-recording-openapi.yml\n      - type: Authentication\n        url: https://developers.telefonie.com/authentication\n      - type: Pricing\n        url: https://www.telefonie.com/pricing/recording\n    contact:\n      - type: Support\n        url: https://www.telefonie.com/support\n\ncommon:\n  - type: Authentication\n    url: https://developers.telefonie.com/authentication\n  - type: Getting Started\n    url: https://developers.telefonie.com/getting-started\n  - type: Rate Limits\n    url: https://developers.telefonie.com/rate-limits\n  - type: SDKs\n    url: https://www.telefonie.com/sdks\n  - type: Status\n    url: https://status.telefonie.com\n  - type: Terms of Service\n    url: https://www.telefonie.com/terms\n  - type: Privacy Policy\n    url: https://www.telefonie.com/privacy\n  - type: Sign Up\n    url: https://www.telefonie.com/signup\n  -\
  \ type: Login\n    url: https://www.telefonie.com/login\n  - type: Blog\n    url: https://blog.telefonie.com\n  - type: Pricing\n    url: https://www.telefonie.com/pricing\n  - type: Change Log\n    url: https://developers.telefonie.com/changelog\n  - type: GitHub\n    url: https://github.com/telefonie\nmaintainers:\n  - name: Telefonie API Team\n    email: api@telefonie.com\n    url: https://www.telefonie.com/team\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telefonie/refs/heads/main/apis.yml
tags:
- Call Recording
- CPaaS
- Messaging
- Number Provisioning
- SMS
- Telecommunications
- Telephony
- Voice
- VoIP
url: https://www.telefonie.com
use_cases: []
---
