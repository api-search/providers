---
api_count: 10
api_specs:
- filename: sinch-sms-openapi.yml
  format: yaml
  label: Sinch SMS API
  slug: sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-sms-openapi.yml
- filename: sinch-conversation-openapi.yml
  format: yaml
  label: Sinch Conversation API
  slug: conversation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-conversation-openapi.yml
- filename: sinch-voice-openapi.yml
  format: yaml
  label: Sinch Voice API
  slug: voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-voice-openapi.yml
- filename: sinch-verification-openapi.yml
  format: yaml
  label: Sinch Verification API
  slug: verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-verification-openapi.yml
- filename: sinch-numbers-openapi.yml
  format: yaml
  label: Sinch Numbers API
  slug: numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-numbers-openapi.yml
- filename: sinch-fax-openapi.yml
  format: yaml
  label: Sinch Fax API
  slug: fax-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-fax-openapi.yml
- filename: sinch-elastic-sip-trunking-openapi.yml
  format: yaml
  label: Sinch Elastic SIP Trunking API
  slug: elastic-sip-trunking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-elastic-sip-trunking-openapi.yml
- filename: sinch-brands-openapi.yml
  format: yaml
  label: Sinch Brands API
  slug: brands-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-brands-openapi.yml
- filename: sinch-provisioning-openapi.yml
  format: yaml
  label: Sinch Provisioning API
  slug: provisioning-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-provisioning-openapi.yml
- filename: sinch-registration-openapi.yml
  format: yaml
  label: Sinch Registration API
  slug: registration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-registration-openapi.yml
apis:
- description: The Sinch SMS API enables developers to send and receive SMS messages globally at scale. It supports batch messaging with scheduled delivery, message templates, delivery reports, and inbound message h
  name: Sinch SMS API
  slug: sms-api
- description: The Sinch Conversation API is an omnichannel messaging platform that enables developers to send and receive messages across multiple channels including SMS, RCS, WhatsApp, Facebook Messenger, Instagra
  name: Sinch Conversation API
  slug: conversation-api
- description: The Sinch Voice API is a programmable voice platform that allows developers to make, receive, and manage voice calls over PSTN, SIP, and in-app channels. It supports text-to-speech in over 115 languag
  name: Sinch Voice API
  slug: voice-api
- description: The Sinch Verification API provides phone number verification through multiple methods including SMS, flashcalls, phone calls, and data verification. It enables developers to verify user identity by s
  name: Sinch Verification API
  slug: verification-api
- description: The Sinch Numbers API enables developers to programmatically search for, purchase, configure, and manage phone numbers across multiple countries. It supports local, national, mobile, and toll-free num
  name: Sinch Numbers API
  slug: numbers-api
- description: The Sinch Fax API allows developers to send and receive faxes programmatically at scale. It supports sending faxes to single or multiple recipients, downloading received faxes, and managing fax number
  name: Sinch Fax API
  slug: fax-api
- description: The Sinch Elastic SIP Trunking API enables developers to programmatically create and manage SIP trunks for connecting existing telephony infrastructure to the Sinch network. Supports elastic scaling o
  name: Sinch Elastic SIP Trunking API
  slug: elastic-sip-trunking-api
- description: The Sinch Brands API allows developers to create, update, and manage customer brand profiles used across Sinch messaging products. Brands represent the business identity associated with messaging camp
  name: Sinch Brands API
  slug: brands-api
- description: The Sinch Provisioning API allows developers to programmatically set up and configure Sinch services and resources including service plans, credentials, and integrations.
  name: Sinch Provisioning API
  slug: provisioning-api
- description: The Sinch Registration API provides endpoints for managing sender ID registrations and campaign registrations required for compliant business messaging in regulated markets.
  name: Sinch Registration API
  slug: registration-api
asyncapis:
- description: 'Event-driven webhooks for the Sinch Conversation API. The Conversation API delivers contact messages, delivery receipts, and various notifications through HTTP POST callbacks. Up to 5 webhooks can be '
  name: Sinch Conversation API Webhooks
  slug: sinch-conversation-webhooks-asyncapi
- description: Event-driven webhooks for the Sinch SMS API. The SMS API delivers delivery reports and inbound messages via HTTP POST callbacks to your configured webhook URL. Delivery reports notify you of the deliv
  name: Sinch SMS Webhooks
  slug: sinch-sms-webhooks-asyncapi
- description: Event-driven callbacks for the Sinch Verification API. The Verification API sends HTTP POST callbacks to your application during the verification lifecycle. These include verification request events w
  name: Sinch Verification Callbacks
  slug: sinch-verification-callbacks-asyncapi
- description: Event-driven callbacks for the Sinch Voice API. The Voice API sends HTTP POST callbacks to your application during the lifecycle of a voice call. Your application responds with SVAML (Sinch Voice Appl
  name: Sinch Voice Callbacks
  slug: sinch-voice-callbacks-asyncapi
capabilities:
- description: Unified number management workflow combining the Sinch Numbers API with brand and registration management for compliant business messaging. Used by operations teams and developers provisioning phone n
  name: Sinch Number Management
  slug: number-management
- description: Unified omnichannel messaging workflow combining SMS batch messaging and Conversation API for multi-channel delivery across SMS, WhatsApp, RCS, Facebook Messenger, Viber, Telegram, and more. Used by m
  name: Sinch Omnichannel Messaging
  slug: omnichannel-messaging
- description: Unified voice and identity verification workflow combining the Sinch Voice API and Verification API. Used by identity platforms, financial services, healthcare applications, and any business needing t
  name: Sinch Voice and Verification
  slug: voice-and-verification
common:
- title: ''
  type: Website
  url: https://www.sinch.com/
- title: ''
  type: DeveloperPortal
  url: https://developers.sinch.com/
- title: ''
  type: Documentation
  url: https://developers.sinch.com/docs/
- title: ''
  type: Pricing
  url: https://www.sinch.com/pricing/
- title: ''
  type: Blog
  url: https://www.sinch.com/blog/
- title: ''
  type: GitHubOrg
  url: https://github.com/sinch
- title: ''
  type: TermsOfService
  url: https://www.sinch.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.sinch.com/privacy-policy/
- title: ''
  type: Support
  url: https://www.sinch.com/contact-us/
- title: ''
  type: StatusPage
  url: https://status.sinch.com/
- title: ''
  type: SignUp
  url: https://dashboard.sinch.com/signup
created: '2025-01-01'
description: Sinch is a cloud communications platform providing APIs for SMS, voice, video, fax, verification, and omnichannel messaging. It enables businesses to integrate global communication capabilities into their applications through programmable APIs for sending messages, making calls, verifying phone numbers, and managing sender identities across carrier networks worldwide.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sinch Context
  property_count: 12
  slug: sinch-context
layout: provider
modified: '2026-05-02'
name: Sinch
rules:
- name: Sinch API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: sinch-rules
skills: []
slug: sinch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sinch\nname: Sinch\ndescription: >-\n  Sinch is a cloud communications platform providing APIs for SMS, voice, video,\n  fax, verification, and omnichannel messaging. It enables businesses to integrate\n  global communication capabilities into their applications through programmable\n  APIs for sending messages, making calls, verifying phone numbers, and managing\n  sender identities across carrier networks worldwide.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Communications\n  - Messaging\n  - SMS\n  - Voice\n  - Verification\n  - CPaaS\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: sinch:sms-api\n    name: Sinch SMS API\n    description: >-\n      The Sinch SMS API enables developers to send and receive SMS messages\n      globally\
  \ at scale. It supports batch messaging with scheduled delivery,\n      message templates, delivery reports, and inbound message handling via\n      webhooks. The API provides group management for organizing recipients,\n      automatic message encoding optimization, and supports both transactional\n      and marketing use cases across carriers worldwide.\n    humanURL: https://developers.sinch.com/docs/sms\n    baseURL: https://us.sms.api.sinch.com\n    tags:\n      - SMS\n      - Messaging\n      - Batch Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/sms\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-sms-openapi.yml\n      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/asyncapi/sinch-sms-webhooks-asyncapi.yml\n\n  - aid: sinch:conversation-api\n    name: Sinch Conversation\
  \ API\n    description: >-\n      The Sinch Conversation API is an omnichannel messaging platform that\n      enables developers to send and receive messages across multiple channels\n      including SMS, RCS, WhatsApp, Facebook Messenger, Instagram, Viber,\n      Telegram, KakaoTalk, and LINE through a single unified API. It provides\n      contact management, conversation tracking, message templating, and webhook\n      callbacks for real-time event handling.\n    humanURL: https://developers.sinch.com/docs/conversation\n    baseURL: https://us.conversation.api.sinch.com\n    tags:\n      - Conversation\n      - Omnichannel\n      - WhatsApp\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/conversation\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-conversation-openapi.yml\n      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/asyncapi/sinch-conversation-webhooks-asyncapi.yml\n\
  \n  - aid: sinch:voice-api\n    name: Sinch Voice API\n    description: >-\n      The Sinch Voice API is a programmable voice platform that allows developers\n      to make, receive, and manage voice calls over PSTN, SIP, and in-app channels.\n      It supports text-to-speech in over 115 languages, interactive voice response\n      (IVR) menus, call recording, transcription, number masking, and conferencing.\n    humanURL: https://developers.sinch.com/docs/voice\n    baseURL: https://calling.api.sinch.com\n    tags:\n      - Voice\n      - Calling\n      - IVR\n      - Telephony\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/voice\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-voice-openapi.yml\n      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/asyncapi/sinch-voice-callbacks-asyncapi.yml\n\
  \n  - aid: sinch:verification-api\n    name: Sinch Verification API\n    description: >-\n      The Sinch Verification API provides phone number verification through\n      multiple methods including SMS, flashcalls, phone calls, and data\n      verification. It enables developers to verify user identity by sending\n      one-time codes or initiating automated verification flows.\n    humanURL: https://developers.sinch.com/docs/verification\n    baseURL: https://verification.api.sinch.com\n    tags:\n      - Verification\n      - Identity\n      - OTP\n      - Authentication\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/verification\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-verification-openapi.yml\n      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/asyncapi/sinch-verification-callbacks-asyncapi.yml\n\
  \n  - aid: sinch:numbers-api\n    name: Sinch Numbers API\n    description: >-\n      The Sinch Numbers API enables developers to programmatically search for,\n      purchase, configure, and manage phone numbers across multiple countries.\n      It supports local, national, mobile, and toll-free number types that can\n      be used with Sinch SMS, Voice, and Conversation APIs.\n    humanURL: https://developers.sinch.com/docs/numbers\n    baseURL: https://numbers.api.sinch.com\n    tags:\n      - Numbers\n      - Phone Numbers\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/numbers\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-numbers-openapi.yml\n\n  - aid: sinch:fax-api\n    name: Sinch Fax API\n    description: >-\n      The Sinch Fax API allows developers to send and receive faxes\n      programmatically at scale. It supports sending\
  \ faxes to single or multiple\n      recipients, downloading received faxes, and managing fax numbers. HIPAA,\n      SOC 2 Type 1, and GDPR compliant.\n    humanURL: https://developers.sinch.com/docs/fax\n    baseURL: https://fax.api.sinch.com\n    tags:\n      - Fax\n      - Document\n      - HIPAA\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/fax\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-fax-openapi.yml\n\n  - aid: sinch:elastic-sip-trunking-api\n    name: Sinch Elastic SIP Trunking API\n    description: >-\n      The Sinch Elastic SIP Trunking API enables developers to programmatically\n      create and manage SIP trunks for connecting existing telephony infrastructure\n      to the Sinch network. Supports elastic scaling of voice capacity without\n      fixed-capacity commitments.\n    humanURL: https://developers.sinch.com/docs/sip-trunking\n\
  \    baseURL: https://sip.api.sinch.com\n    tags:\n      - SIP\n      - Voice\n      - Trunking\n      - Telephony\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/sip-trunking\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-elastic-sip-trunking-openapi.yml\n\n  - aid: sinch:brands-api\n    name: Sinch Brands API\n    description: >-\n      The Sinch Brands API allows developers to create, update, and manage\n      customer brand profiles used across Sinch messaging products. Brands\n      represent the business identity associated with messaging campaigns and\n      sender registrations.\n    humanURL: https://developers.sinch.com/docs/brands\n    baseURL: https://brands.api.sinch.com\n    tags:\n      - Brands\n      - Messaging\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/brands\n  \
  \    - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-brands-openapi.yml\n\n  - aid: sinch:provisioning-api\n    name: Sinch Provisioning API\n    description: >-\n      The Sinch Provisioning API allows developers to programmatically set up\n      and configure Sinch services and resources including service plans,\n      credentials, and integrations.\n    humanURL: https://developers.sinch.com/docs/provisioning\n    baseURL: https://provisioning.api.sinch.com\n    tags:\n      - Provisioning\n      - Configuration\n      - Management\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/provisioning\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-provisioning-openapi.yml\n\n  - aid: sinch:registration-api\n    name: Sinch Registration API\n    description: >-\n      The Sinch Registration\
  \ API provides endpoints for managing sender ID\n      registrations and campaign registrations required for compliant business\n      messaging in regulated markets.\n    humanURL: https://developers.sinch.com/docs/registration\n    baseURL: https://registration.api.sinch.com\n    tags:\n      - Registration\n      - Sender ID\n      - Compliance\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.sinch.com/docs/registration\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/openapi/sinch-registration-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.sinch.com/\n  - type: DeveloperPortal\n    url: https://developers.sinch.com/\n  - type: Documentation\n    url: https://developers.sinch.com/docs/\n  - type: Pricing\n    url: https://www.sinch.com/pricing/\n  - type: Blog\n    url: https://www.sinch.com/blog/\n  - type: GitHubOrg\n    url: https://github.com/sinch\n\
  \  - type: TermsOfService\n    url: https://www.sinch.com/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://www.sinch.com/privacy-policy/\n  - type: Support\n    url: https://www.sinch.com/contact-us/\n  - type: StatusPage\n    url: https://status.sinch.com/\n  - type: SignUp\n    url: https://dashboard.sinch.com/signup\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/apis.yml
tags:
- Communications
- Messaging
- SMS
- Voice
- Verification
- CPaaS
url: https://raw.githubusercontent.com/api-evangelist/sinch/refs/heads/main/apis.yml
use_cases: []
---
