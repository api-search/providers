---
api_count: 4
api_specs:
- filename: telefon-voice-openapi.yml
  format: yaml
  label: Telefon Voice API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-voice-openapi.yml
- filename: telefon-sms-openapi.yml
  format: yaml
  label: Telefon SMS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-sms-openapi.yml
- filename: telefon-numbers-openapi.yml
  format: yaml
  label: Telefon Number Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-numbers-openapi.yml
- filename: telefon-recording-openapi.yml
  format: yaml
  label: Telefon Call Recording API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/openapi/telefon-recording-openapi.yml
apis:
- description: Programmable voice API for building call-based applications. Make outbound calls, handle inbound calls with webhooks, build IVR menus, perform call transfer and conferencing, and control calls in real
  name: Telefon Voice API
  slug: ''
- description: Send and receive SMS and MMS messages globally. Supports A2P (Application-to-Person) messaging, two-way conversational SMS, delivery receipts, inbound webhooks, message queuing for high throughput, an
  name: Telefon SMS API
  slug: ''
- description: Search, provision, configure, and manage phone numbers worldwide. Supports local, national, mobile, toll-free, and short code numbers across 70+ countries. Configure voice and SMS routing, manage numb
  name: Telefon Number Management API
  slug: ''
- description: Record, store, transcribe, and retrieve call recordings. Supports on-demand and automatic recording, dual-channel recording for separate caller/callee audio, AI-powered transcription in 30+ languages,
  name: Telefon Call Recording API
  slug: ''
capabilities:
- description: 'Unified capability combining Telefon Voice and SMS APIs for comprehensive programmable communications. Supports voice calls, conferencing, SMS messaging, and recording across 180+ countries. Designed '
  name: Telefon Communications Platform
  slug: telephony-platform
common:
- title: ''
  type: Getting Started
  url: https://developers.telefon.com/getting-started
- title: ''
  type: Authentication
  url: https://developers.telefon.com/authentication
- title: ''
  type: SDKs
  url: https://www.telefon.com/sdks
- title: ''
  type: Status Page
  url: https://status.telefon.com
- title: ''
  type: Terms of Service
  url: https://www.telefon.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.telefon.com/privacy
- title: ''
  type: Support
  url: https://www.telefon.com/support
- title: ''
  type: Blog
  url: https://blog.telefon.com
- title: ''
  type: Change Log
  url: https://developers.telefon.com/changelog
- title: ''
  type: Pricing
  url: https://www.telefon.com/pricing
- title: ''
  type: GitHub
  url: https://github.com/telefon-api
created: '2024-01-15'
description: Telefon is a cloud-based programmable communications platform providing voice calling, SMS messaging, number management, and call recording APIs for developers and enterprises. The platform enables applications to make and receive phone calls, send SMS and MMS messages, manage phone number inventories, and record calls for compliance and quality assurance purposes. Telefon supports global coverage across 180+ countries with competitive per-minute and per-message pricing.
features: []
image: https://www.telefon.com/logo.png
integrations: []
jsonld:
- class_count: 6
  name: Telefon Context
  property_count: 20
  slug: telefon-context
layout: provider
modified: '2026-05-03'
name: Telefon
rules:
- name: Telefon API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 4
  slug: telefon-rules
skills: []
slug: telefon
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Telefon\ndescription: >-\n  Telefon is a cloud-based programmable communications platform providing voice\n  calling, SMS messaging, number management, and call recording APIs for developers\n  and enterprises. The platform enables applications to make and receive phone calls,\n  send SMS and MMS messages, manage phone number inventories, and record calls for\n  compliance and quality assurance purposes. Telefon supports global coverage across\n  180+ countries with competitive per-minute and per-message pricing.\nimage: https://www.telefon.com/logo.png\nurl: https://www.telefon.com\ntype: Index\ntags:\n  - Call Recording\n  - Communications\n  - CPaaS\n  - Global Coverage\n  - Messaging\n  - Number Provisioning\n  - SMS\n  - Telephony\n  - Voice\n  - VoIP\ncreated: '2024-01-15'\nmodified: '2026-05-03'\nspecificationVersion: '0.16'\napis:\n  - name: Telefon Voice API\n    description: >-\n      Programmable voice API for building call-based applications. Make outbound\n\
  \      calls, handle inbound calls with webhooks, build IVR menus, perform call\n      transfer and conferencing, and control calls in real-time. Supports SIP\n      trunking, WebRTC, text-to-speech, speech recognition, and call recording.\n    image: https://www.telefon.com/voice-icon.png\n    humanURL: https://developers.telefon.com/voice\n    baseURL: https://api.telefon.com/v1/voice\n    version: v1\n    tags:\n      - Calls\n      - Communications\n      - IVR\n      - SIP Trunking\n      - Telephony\n      - TTS\n      - Voice\n      - WebRTC\n    properties:\n      - type: Documentation\n        url: https://developers.telefon.com/voice\n      - type: OpenAPI\n        url: openapi/telefon-voice-openapi.yml\n      - type: Authentication\n        url: https://developers.telefon.com/authentication\n      - type: GettingStarted\n        url: https://developers.telefon.com/getting-started\n      - type: Pricing\n        url: https://www.telefon.com/pricing/voice\n      - type: RateLimits\n\
  \        url: https://developers.telefon.com/rate-limits\n    contact:\n      - type: Email\n        url: mailto:api@telefon.com\n      - type: Support\n        url: https://www.telefon.com/support\n\n  - name: Telefon SMS API\n    description: >-\n      Send and receive SMS and MMS messages globally. Supports A2P (Application-to-Person)\n      messaging, two-way conversational SMS, delivery receipts, inbound webhooks,\n      message queuing for high throughput, and unicode character sets for international\n      languages. Compliant with TCPA (US), GDPR (EU), and other regional regulations.\n    image: https://www.telefon.com/sms-icon.png\n    humanURL: https://developers.telefon.com/sms\n    baseURL: https://api.telefon.com/v1/sms\n    version: v1\n    tags:\n      - A2P Messaging\n      - Communications\n      - Messaging\n      - MMS\n      - SMS\n      - Two-Way SMS\n      - Unicode\n    properties:\n      - type: Documentation\n        url: https://developers.telefon.com/sms\n  \
  \    - type: OpenAPI\n        url: openapi/telefon-sms-openapi.yml\n      - type: Authentication\n        url: https://developers.telefon.com/authentication\n      - type: Pricing\n        url: https://www.telefon.com/pricing/sms\n      - type: Rate Limits\n        url: https://developers.telefon.com/rate-limits\n    contact:\n      - type: Email\n        url: mailto:api@telefon.com\n\n  - name: Telefon Number Management API\n    description: >-\n      Search, provision, configure, and manage phone numbers worldwide. Supports\n      local, national, mobile, toll-free, and short code numbers across 70+ countries.\n      Configure voice and SMS routing, manage number pools, and handle number\n      portability requests. Supports regulatory compliance requirements including\n      address verification for regulated number types.\n    image: https://www.telefon.com/numbers-icon.png\n    humanURL: https://developers.telefon.com/numbers\n    baseURL: https://api.telefon.com/v1/numbers\n    version:\
  \ v1\n    tags:\n      - DID\n      - Number Management\n      - Number Portability\n      - Number Provisioning\n      - Phone Numbers\n      - Short Codes\n      - Toll-Free\n    properties:\n      - type: Documentation\n        url: https://developers.telefon.com/numbers\n      - type: OpenAPI\n        url: openapi/telefon-numbers-openapi.yml\n      - type: Authentication\n        url: https://developers.telefon.com/authentication\n      - type: Pricing\n        url: https://www.telefon.com/pricing/numbers\n    contact:\n      - type: Email\n        url: mailto:api@telefon.com\n\n  - name: Telefon Call Recording API\n    description: >-\n      Record, store, transcribe, and retrieve call recordings. Supports on-demand and\n      automatic recording, dual-channel recording for separate caller/callee audio,\n      AI-powered transcription in 30+ languages, PII redaction, storage management,\n      and compliance archiving with configurable retention policies.\n    image: https://www.telefon.com/recording-icon.png\n\
  \    humanURL: https://developers.telefon.com/recording\n    baseURL: https://api.telefon.com/v1/recording\n    version: v1\n    tags:\n      - AI Transcription\n      - Audio\n      - Call Recording\n      - Compliance\n      - Dual Channel\n      - PII Redaction\n      - Storage\n      - Transcription\n    properties:\n      - type: Documentation\n        url: https://developers.telefon.com/recording\n      - type: OpenAPI\n        url: openapi/telefon-recording-openapi.yml\n      - type: Authentication\n        url: https://developers.telefon.com/authentication\n      - type: Privacy Policy\n        url: https://www.telefon.com/privacy\n      - type: Compliance\n        url: https://www.telefon.com/compliance\n    contact:\n      - type: Email\n        url: mailto:api@telefon.com\n\ncommon:\n  - type: Getting Started\n    url: https://developers.telefon.com/getting-started\n  - type: Authentication\n    url: https://developers.telefon.com/authentication\n  - type: SDKs\n    url: https://www.telefon.com/sdks\n\
  \  - type: Status Page\n    url: https://status.telefon.com\n  - type: Terms of Service\n    url: https://www.telefon.com/terms\n  - type: Privacy Policy\n    url: https://www.telefon.com/privacy\n  - type: Support\n    url: https://www.telefon.com/support\n  - type: Blog\n    url: https://blog.telefon.com\n  - type: Change Log\n    url: https://developers.telefon.com/changelog\n  - type: Pricing\n    url: https://www.telefon.com/pricing\n  - type: GitHub\n    url: https://github.com/telefon-api\nmaintainers:\n  - name: Telefon API Team\n    email: api@telefon.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telefon/refs/heads/main/apis.yml
tags:
- Call Recording
- Communications
- CPaaS
- Global Coverage
- Messaging
- Number Provisioning
- SMS
- Telephony
- Voice
- VoIP
url: https://www.telefon.com
use_cases: []
---
