---
api_count: 9
api_specs:
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage SMS API
  slug: vonage-sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Voice API
  slug: vonage-voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Messages API
  slug: vonage-messages-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Verify API
  slug: vonage-verify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Numbers API
  slug: vonage-numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
- filename: vonage-openapi.yml
  format: yaml
  label: Vonage Application API
  slug: vonage-application-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml
apis:
- description: Send and receive SMS messages globally using Vonage's SMS API. Supports text, binary, and unicode message types with delivery receipts and inbound message webhooks.
  name: Vonage SMS API
  slug: vonage-sms-api
- description: Create and control outbound and inbound voice calls using Vonage's Voice API. Supports PSTN, SIP, WebSocket, and VBC endpoints with NCCO (Vonage Call Control Object) for call flow management.
  name: Vonage Voice API
  slug: vonage-voice-api
- description: Multi-channel messaging API supporting SMS, WhatsApp, Facebook Messenger, Viber, MMS, and RCS. Send and receive messages across multiple channels with a unified API interface.
  name: Vonage Messages API
  slug: vonage-messages-api
- description: Two-factor authentication and phone verification API. Confirm user phone numbers via SMS, TTS, or WhatsApp verification codes to prevent fraud and authenticate users.
  name: Vonage Verify API
  slug: vonage-verify-api
- description: Provision and manage virtual phone numbers globally. Search available numbers, purchase numbers for your account, and configure number behavior including inbound SMS and voice call routing.
  name: Vonage Numbers API
  slug: vonage-numbers-api
- description: Configure Vonage application settings, webhook URLs, and authentication keys. Create and manage applications that group Vonage API capabilities including voice, messages, RTC, meetings, and video feat
  name: Vonage Application API
  slug: vonage-application-api
- description: Build multi-channel conversation experiences with threading across SMS, voice, and messaging channels. Manage members, events, and legs within conversation contexts.
  name: Vonage Conversations API
  slug: vonage-conversations-api
- description: Generate historical reports and lookup messages sent through your Vonage account. Access delivery receipts, call records, and usage data.
  name: Vonage Reports API
  slug: vonage-reports-api
- description: Embed live, interactive video into web, mobile, and desktop applications using WebRTC. Supports sessions, tokens, broadcasting, recording, and SIP interconnect.
  name: Vonage Video API
  slug: vonage-video-api
capabilities:
- description: Unified messaging workflow combining Vonage SMS API and Messages API for sending notifications, alerts, and multi-channel communications to customers. Used by developers building notification systems,
  name: Vonage Messaging and Notifications
  slug: messaging-and-notifications
- description: Phone-based authentication workflow combining Vonage Verify API and Numbers API. Enables two-factor authentication, user onboarding verification, and phone number provisioning. Used by identity teams,
  name: Vonage User Authentication
  slug: user-authentication
- description: Voice call workflow for Vonage Voice API. Enables programmatic creation, monitoring, and control of outbound and inbound voice calls. Used by developers building IVR systems, call center solutions, vo
  name: Vonage Voice Communications
  slug: voice-communications
common:
- title: ''
  type: Portal
  url: https://developer.vonage.com/
- title: ''
  type: Documentation
  url: https://developer.vonage.com/en/documentation
- title: ''
  type: Support
  url: https://api.support.vonage.com/hc/en-us
- title: ''
  type: GitHubOrganization
  url: https://github.com/Vonage
- title: ''
  type: Portal
  url: https://www.vonage.com/developer-center/
- title: ''
  type: Blog
  url: https://developer.vonage.com/en/blog
- title: ''
  type: Community
  url: https://vonage-community.slack.com/
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-node-sdk
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-python-sdk
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-java-sdk
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-php-sdk-core
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-ruby-sdk
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-dotnet-sdk
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-go-sdk
- title: ''
  type: SDK
  url: https://github.com/Vonage/vonage-kotlin-sdk
- title: ''
  type: CLI
  url: https://github.com/Vonage/vonage-cli
- title: ''
  type: TermsOfService
  url: https://www.vonage.com/legal/
- title: ''
  type: PrivacyPolicy
  url: https://www.vonage.com/legal/unified-communications/privacy-policy/
- title: ''
  type: Pricing
  url: https://www.vonage.com/communications-apis/#pricing
created: '2025-02-08'
description: Vonage (part of Ericsson) provides cloud communications APIs for voice, SMS, messaging, video, and verification. The Vonage API platform enables businesses to embed communication capabilities into applications including voice calls, SMS, multi-channel messaging (WhatsApp, Messenger, Viber, RCS), video conferencing, and two-factor authentication. SDKs are available for Node.js, Python, Java, PHP, Ruby, .NET, Go, and Kotlin.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Vonage Context
  property_count: 19
  slug: vonage-context
layout: provider
modified: '2026-05-03'
name: Vonage
rules:
- name: Vonage API Rules
  rule_count: 11
  severity_counts:
    error: 1
    hint: 0
    info: 6
    warn: 4
  slug: vonage-rules
skills: []
slug: vonage
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vonage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/apis.yml\napis:\n  - aid: vonage:vonage-sms-api\n    name: Vonage SMS API\n    tags:\n      - Communication\n      - Messaging\n      - SMS\n      - Telecommunications\n    humanURL: https://developer.vonage.com/en/api/sms\n    baseURL: https://rest.nexmo.com\n    description: >-\n      Send and receive SMS messages globally using Vonage's SMS API.\n      Supports text, binary, and unicode message types with delivery receipts\n      and inbound message webhooks.\n    properties:\n      - url: https://developer.vonage.com/en/api/sms\n        type: Documentation\n      - url: https://rest.nexmo.com\n        type: BaseURL\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml\n        type: OpenAPI\n\n  - aid: vonage:vonage-voice-api\n    name: Vonage Voice API\n    tags:\n      - Communication\n      - Telecommunications\n\
  \      - Voice\n      - VoIP\n    humanURL: https://developer.vonage.com/en/api/voice\n    baseURL: https://api.nexmo.com/v1\n    description: >-\n      Create and control outbound and inbound voice calls using Vonage's Voice API.\n      Supports PSTN, SIP, WebSocket, and VBC endpoints with NCCO (Vonage Call\n      Control Object) for call flow management.\n    properties:\n      - url: https://developer.vonage.com/en/api/voice\n        type: Documentation\n      - url: https://api.nexmo.com/v1\n        type: BaseURL\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml\n        type: OpenAPI\n\n  - aid: vonage:vonage-messages-api\n    name: Vonage Messages API\n    tags:\n      - Communication\n      - Messaging\n      - Omnichannel\n      - WhatsApp\n      - RCS\n    humanURL: https://developer.vonage.com/en/api/messages-olympus\n    baseURL: https://api.nexmo.com/v1/messages\n    description: >-\n      Multi-channel\
  \ messaging API supporting SMS, WhatsApp, Facebook Messenger,\n      Viber, MMS, and RCS. Send and receive messages across multiple channels\n      with a unified API interface.\n    properties:\n      - url: https://developer.vonage.com/en/api/messages-olympus\n        type: Documentation\n      - url: https://api.nexmo.com/v1/messages\n        type: BaseURL\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml\n        type: OpenAPI\n\n  - aid: vonage:vonage-verify-api\n    name: Vonage Verify API\n    tags:\n      - Authentication\n      - Communication\n      - Security\n      - Two-Factor Authentication\n      - Verification\n    humanURL: https://developer.vonage.com/en/api/verify\n    baseURL: https://api.nexmo.com\n    description: >-\n      Two-factor authentication and phone verification API. Confirm user phone\n      numbers via SMS, TTS, or WhatsApp verification codes to prevent fraud and\n      authenticate\
  \ users.\n    properties:\n      - url: https://developer.vonage.com/en/api/verify\n        type: Documentation\n      - url: https://api.nexmo.com\n        type: BaseURL\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml\n        type: OpenAPI\n\n  - aid: vonage:vonage-numbers-api\n    name: Vonage Numbers API\n    tags:\n      - Communication\n      - Number Management\n      - Telecommunications\n      - Virtual Numbers\n    humanURL: https://developer.vonage.com/en/api/numbers\n    baseURL: https://rest.nexmo.com\n    description: >-\n      Provision and manage virtual phone numbers globally. Search available numbers,\n      purchase numbers for your account, and configure number behavior including\n      inbound SMS and voice call routing.\n    properties:\n      - url: https://developer.vonage.com/en/api/numbers\n        type: Documentation\n      - url: https://rest.nexmo.com\n        type: BaseURL\n   \
  \   - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml\n        type: OpenAPI\n\n  - aid: vonage:vonage-application-api\n    name: Vonage Application API\n    tags:\n      - API Management\n      - Communication\n      - Configuration\n      - Developer Tools\n    humanURL: https://developer.vonage.com/en/api/application.v2\n    baseURL: https://api.nexmo.com/v2/applications\n    description: >-\n      Configure Vonage application settings, webhook URLs, and authentication keys.\n      Create and manage applications that group Vonage API capabilities including\n      voice, messages, RTC, meetings, and video features.\n    properties:\n      - url: https://developer.vonage.com/en/api/application.v2\n        type: Documentation\n      - url: https://api.nexmo.com/v2/applications\n        type: BaseURL\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/openapi/vonage-openapi.yml\n\
  \        type: OpenAPI\n\n  - aid: vonage:vonage-conversations-api\n    name: Vonage Conversations API\n    tags:\n      - Communication\n      - Conversations\n      - Messaging\n      - Real-Time\n    humanURL: https://developer.vonage.com/en/api/conversation\n    baseURL: https://api.nexmo.com/v1\n    description: >-\n      Build multi-channel conversation experiences with threading across SMS,\n      voice, and messaging channels. Manage members, events, and legs within\n      conversation contexts.\n    properties:\n      - url: https://developer.vonage.com/en/api/conversation\n        type: Documentation\n      - url: https://api.nexmo.com/v1\n        type: BaseURL\n\n  - aid: vonage:vonage-reports-api\n    name: Vonage Reports API\n    tags:\n      - Analytics\n      - Communication\n      - Reporting\n    humanURL: https://developer.vonage.com/en/reports/overview\n    baseURL: https://api.nexmo.com/v2/reports\n    description: >-\n      Generate historical reports and lookup messages\
  \ sent through your Vonage\n      account. Access delivery receipts, call records, and usage data.\n    properties:\n      - url: https://developer.vonage.com/en/reports/overview\n        type: Documentation\n      - url: https://api.nexmo.com/v2/reports\n        type: BaseURL\n\n  - aid: vonage:vonage-video-api\n    name: Vonage Video API\n    tags:\n      - Communication\n      - Telecommunications\n      - Video\n      - WebRTC\n    humanURL: https://developer.vonage.com/en/video/overview\n    baseURL: https://api.opentok.com\n    description: >-\n      Embed live, interactive video into web, mobile, and desktop applications\n      using WebRTC. Supports sessions, tokens, broadcasting, recording, and\n      SIP interconnect.\n    properties:\n      - url: https://developer.vonage.com/en/video/overview\n        type: Documentation\n      - url: https://tokbox.com/developer/\n        type: Portal\n      - url: https://api.opentok.com\n        type: BaseURL\n\nname: Vonage\ntags:\n  -\
  \ Communication\n  - Messaging\n  - Telecommunications\n  - Video Conferencing\n  - Voice\n  - SMS\n  - Verification\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Vonage (part of Ericsson) provides cloud communications APIs for voice, SMS,\n  messaging, video, and verification. The Vonage API platform enables businesses\n  to embed communication capabilities into applications including voice calls,\n  SMS, multi-channel messaging (WhatsApp, Messenger, Viber, RCS), video\n  conferencing, and two-factor authentication. SDKs are available for Node.js,\n  Python, Java, PHP, Ruby, .NET, Go, and Kotlin.\ncommon:\n  - url: https://developer.vonage.com/\n    name: Vonage API Developer Portal\n    type: Portal\n    description: Official developer portal for Vonage APIs.\n  - url: https://developer.vonage.com/en/documentation\n    name: Vonage\
  \ API Documentation\n    type: Documentation\n    description: Complete API documentation for all Vonage APIs.\n  - url: https://api.support.vonage.com/hc/en-us\n    name: Vonage API Support\n    type: Support\n    description: Vonage developer support center.\n  - url: https://github.com/Vonage\n    name: Vonage GitHub Organization\n    type: GitHubOrganization\n    description: Vonage SDKs, code samples, and tools on GitHub.\n  - url: https://www.vonage.com/developer-center/\n    name: Developer Center\n    type: Portal\n    description: Vonage developer resources and tools.\n  - url: https://developer.vonage.com/en/blog\n    name: Vonage Developer Blog\n    type: Blog\n    description: Developer tutorials and updates.\n  - url: https://vonage-community.slack.com/\n    name: Vonage Community Slack\n    type: Community\n    description: Community Slack workspace for Vonage developers.\n  - url: https://github.com/Vonage/vonage-node-sdk\n    name: Vonage Node.js SDK\n    type: SDK\n  \
  \  description: Official Vonage SDK for Node.js.\n  - url: https://github.com/Vonage/vonage-python-sdk\n    name: Vonage Python SDK\n    type: SDK\n    description: Official Vonage SDK for Python.\n  - url: https://github.com/Vonage/vonage-java-sdk\n    name: Vonage Java SDK\n    type: SDK\n    description: Official Vonage SDK for Java.\n  - url: https://github.com/Vonage/vonage-php-sdk-core\n    name: Vonage PHP SDK\n    type: SDK\n    description: Official Vonage SDK for PHP.\n  - url: https://github.com/Vonage/vonage-ruby-sdk\n    name: Vonage Ruby SDK\n    type: SDK\n    description: Official Vonage SDK for Ruby.\n  - url: https://github.com/Vonage/vonage-dotnet-sdk\n    name: Vonage .NET SDK\n    type: SDK\n    description: Official Vonage SDK for .NET/C#.\n  - url: https://github.com/Vonage/vonage-go-sdk\n    name: Vonage Go SDK\n    type: SDK\n    description: Official Vonage SDK for Go.\n  - url: https://github.com/Vonage/vonage-kotlin-sdk\n    name: Vonage Kotlin SDK\n    type:\
  \ SDK\n    description: Official Vonage SDK for Kotlin.\n  - url: https://github.com/Vonage/vonage-cli\n    name: Vonage CLI\n    type: CLI\n    description: Command-line interface for managing Vonage resources.\n  - url: https://www.vonage.com/legal/\n    name: Terms of Service\n    type: TermsOfService\n    description: Vonage terms of service.\n  - url: https://www.vonage.com/legal/unified-communications/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n    description: Vonage privacy policy.\n  - url: https://www.vonage.com/communications-apis/#pricing\n    name: Pricing\n    type: Pricing\n    description: Vonage API pricing.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/apis.yml
tags:
- Communication
- Messaging
- Telecommunications
- Video Conferencing
- Voice
- SMS
- Verification
url: https://raw.githubusercontent.com/api-evangelist/vonage/refs/heads/main/apis.yml
use_cases: []
---
