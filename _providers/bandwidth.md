---
api_count: 6
api_specs:
- filename: bandwidth-voice-api-openapi.yml
  format: yaml
  label: Bandwidth Voice API
  slug: voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-voice-api-openapi.yml
- filename: bandwidth-messaging-api-openapi.yml
  format: yaml
  label: Bandwidth Messaging API
  slug: messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-messaging-api-openapi.yml
- filename: bandwidth-phone-numbers-api-openapi.yml
  format: yaml
  label: Bandwidth Phone Numbers API
  slug: phone-numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-phone-numbers-api-openapi.yml
- filename: bandwidth-mfa-api-openapi.yml
  format: yaml
  label: Bandwidth Multi-Factor Authentication API
  slug: multi-factor-authentication-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-mfa-api-openapi.yml
- filename: bandwidth-emergency-calling-api-openapi.yml
  format: yaml
  label: Bandwidth Emergency Calling API
  slug: emergency-calling-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-emergency-calling-api-openapi.yml
- filename: bandwidth-toll-free-verification-api-openapi.yml
  format: yaml
  label: Bandwidth Toll-Free Verification API
  slug: toll-free-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/openapi/bandwidth-toll-free-verification-api-openapi.yml
apis:
- description: The Bandwidth Voice API enables developers to programmatically make and receive phone calls, manage call recordings, and create multi-party conferences. It supports advanced call control features incl
  name: Bandwidth Voice API
  slug: voice-api
- description: The Bandwidth Messaging API allows developers to send and receive SMS and MMS messages programmatically. It supports both toll-free and local number messaging, group messaging, and application-to-pers
  name: Bandwidth Messaging API
  slug: messaging-api
- description: The Bandwidth Phone Numbers API provides programmatic access to search, order, and manage phone numbers across the United States and Canada. Developers can search for available local, toll-free, and s
  name: Bandwidth Phone Numbers API
  slug: phone-numbers-api
- description: The Bandwidth Multi-Factor Authentication API allows developers to generate and verify secure MFA codes delivered via voice calls or SMS messages. It leverages Bandwidth's Voice and Messaging APIs und
  name: Bandwidth Multi-Factor Authentication API
  slug: multi-factor-authentication-api
- description: The Bandwidth Emergency Calling API provides programmatic access to provision and manage 911 endpoints and locations for emergency services routing. It supports Dynamic Location Routing (DLR) for real
  name: Bandwidth Emergency Calling API
  slug: emergency-calling-api
- description: The Bandwidth Toll-Free Verification API enables developers to programmatically submit and manage toll-free number verification requests for A2P messaging compliance. It automates the verification sub
  name: Bandwidth Toll-Free Verification API
  slug: toll-free-verification-api
asyncapis:
- description: Bandwidth Messaging API sends webhooks to your application for real-time message delivery notifications and inbound message alerts. Callbacks are sent via HTTP POST to the callback URL configured on t
  name: Bandwidth Messaging Events
  slug: bandwidth-messaging-events-asyncapi
- description: Bandwidth Voice API sends webhooks (BXML callbacks) to your application for real-time call event notifications. These webhooks inform your application of call state changes and request BXML instructio
  name: Bandwidth Voice Events
  slug: bandwidth-voice-events-asyncapi
capabilities:
- description: Unified communications platform workflow covering voice calls, messaging (SMS/MMS), multi-factor authentication, phone number management, emergency calling (E911), and toll-free verification. Serves d
  name: Bandwidth Communications Platform
  slug: communications-platform
common:
- title: ''
  type: Website
  url: https://www.bandwidth.com/
- title: ''
  type: Documentation
  url: https://dev.bandwidth.com/
- title: ''
  type: SignUp
  url: https://app.bandwidth.com/signup
- title: ''
  type: Blog
  url: https://www.bandwidth.com/blog/
- title: ''
  type: TermsOfService
  url: https://www.bandwidth.com/legal/
- title: ''
  type: PrivacyPolicy
  url: https://www.bandwidth.com/legal/privacy-policy/
- title: ''
  type: Status
  url: https://status.bandwidth.com/
- title: ''
  type: Support
  url: https://support.bandwidth.com/
- title: ''
  type: SDK
  url: https://dev.bandwidth.com/sdks/
- title: ''
  type: SpectralRules
  url: rules/bandwidth-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bandwidth-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/communications-platform.yaml
- title: ''
  type: JSONSchema
  url: json-schema/bandwidth-call-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/bandwidth-message-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/bandwidth-phone-number-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/bandwidth-context.jsonld
created: '2024-01-01'
description: Bandwidth is a leading cloud-based communications platform providing voice, messaging, emergency calling, phone number management, multi-factor authentication, and toll-free verification APIs. Built on Bandwidth's own Tier 1 network, the platform delivers enterprise-grade reliability for CPaaS applications.
features:
- description: Programmable outbound and inbound voice call management with BXML call control.
  name: Voice Calls
- description: Send and receive SMS messages on local and toll-free numbers.
  name: SMS Messaging
- description: Send and receive multimedia messages with images, video, and audio.
  name: MMS Messaging
- description: OTP code delivery and verification via voice or SMS.
  name: Multi-Factor Authentication
- description: Search, order, port, and configure US and Canadian phone numbers.
  name: Phone Number Management
- description: Dynamic location routing for compliant emergency call handling.
  name: Emergency Calling (E911)
- description: Submit and track A2P toll-free number verification requests.
  name: Toll-Free Verification
- description: Record and retrieve voice call audio for compliance and analytics.
  name: Call Recording
- description: Create multi-party voice conferences with participant management.
  name: Conferences
- description: Real-time event notifications for call state changes and message delivery.
  name: Webhooks
- description: Direct carrier connectivity on Bandwidth's own nationwide network.
  name: Tier 1 Network
image: ''
integrations:
- name: Cisco Webex
- name: Microsoft Teams
- name: Zoom Phone
- name: Twilio
- name: Salesforce
- name: Amazon Connect
- name: Genesys Cloud
jsonld:
- class_count: 51
  name: Bandwidth Context
  property_count: 137
  slug: bandwidth-context
layout: provider
modified: '2026-04-19'
name: Bandwidth
rules:
- name: Bandwidth API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 6
  slug: bandwidth-spectral-rules
skills: []
slug: bandwidth
solutions: []
source_filename: apis.yml
source_yaml: "aid: bandwidth\nurl: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/apis.yml\nname: Bandwidth\ntags:\n  - Communications\n  - CPaaS\n  - Voice\n  - Messaging\n  - Telephony\n  - SMS\n  - MFA\nmodified: '2026-04-19'\ndescription: >-\n  Bandwidth is a leading cloud-based communications platform providing voice, messaging, emergency\n  calling, phone number management, multi-factor authentication, and toll-free verification APIs.\n  Built on Bandwidth's own Tier 1 network, the platform delivers enterprise-grade reliability\n  for CPaaS applications.\napis:\n  - aid: bandwidth:voice-api\n    name: Bandwidth Voice API\n    tags:\n      - Calls\n      - Conferences\n      - CPaaS\n      - Recordings\n      - Telephony\n      - Voice\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://voice.bandwidth.com/api/v2\n    humanURL: https://dev.bandwidth.com/docs/voice/\n    properties:\n      - url: https://dev.bandwidth.com/docs/voice/\n\
  \        type: Documentation\n      - url: openapi/bandwidth-voice-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/bandwidth-voice-events-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Bandwidth Voice API enables developers to programmatically make and\n      receive phone calls, manage call recordings, and create multi-party\n      conferences. It supports advanced call control features including call\n      transfers, bridging, DTMF detection, and text-to-speech. The API uses\n      BXML (Bandwidth XML) verbs for call flow control and provides webhooks\n      for real-time event notifications on call state changes.\n  - aid: bandwidth:messaging-api\n    name: Bandwidth Messaging API\n    tags:\n      - CPaaS\n      - Messaging\n      - MMS\n      - SMS\n      - Text Messaging\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://messaging.bandwidth.com/api/v2\n    humanURL: https://dev.bandwidth.com/docs/messaging/\n\
  \    properties:\n      - url: https://dev.bandwidth.com/docs/messaging/\n        type: Documentation\n      - url: openapi/bandwidth-messaging-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/bandwidth-messaging-events-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Bandwidth Messaging API allows developers to send and receive SMS\n      and MMS messages programmatically. It supports both toll-free and\n      local number messaging, group messaging, and application-to-person\n      (A2P) messaging workflows. The API provides delivery receipts via\n      webhooks, message status tracking, and media management for MMS\n      attachments. Bandwidth operates its own tier-1 network, providing\n      direct carrier connectivity for reliable message delivery.\n  - aid: bandwidth:phone-numbers-api\n    name: Bandwidth Phone Numbers API\n    tags:\n      - Number Management\n      - Phone Numbers\n      - Porting\n      - Telecom\n      - Telephone Numbers\n \
  \   image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://dashboard.bandwidth.com/api\n    humanURL: https://dev.bandwidth.com/docs/numbers/\n    properties:\n      - url: https://dev.bandwidth.com/docs/numbers/\n        type: Documentation\n      - url: openapi/bandwidth-phone-numbers-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bandwidth Phone Numbers API provides programmatic access to search,\n      order, and manage phone numbers across the United States and Canada.\n      Developers can search for available local, toll-free, and short code\n      numbers, initiate number porting requests, and configure number features\n      such as CNAM, directory listings, and line features. The API also\n      supports managing sites, SIP peers, and number assignments for\n      organizing telephony resources within an account.\n  - aid: bandwidth:multi-factor-authentication-api\n    name: Bandwidth Multi-Factor Authentication\
  \ API\n    tags:\n      - Authentication\n      - MFA\n      - Security\n      - Two-Factor Authentication\n      - Verification\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://mfa.bandwidth.com/api/v1\n    humanURL: https://dev.bandwidth.com/docs/mfa/\n    properties:\n      - url: https://dev.bandwidth.com/docs/mfa/\n        type: Documentation\n      - url: openapi/bandwidth-mfa-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bandwidth Multi-Factor Authentication API allows developers to\n      generate and verify secure MFA codes delivered via voice calls or SMS\n      messages. It leverages Bandwidth's Voice and Messaging APIs under the\n      hood, handling token generation and management automatically. Developers\n      can customize the code length, expiration time, and delivery message\n      template. The API supports both one-time passcode delivery and\n      verification in a simple two-step\
  \ workflow.\n  - aid: bandwidth:emergency-calling-api\n    name: Bandwidth Emergency Calling API\n    tags:\n      - Compliance\n      - E911\n      - Emergency Services\n      - Public Safety\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://dashboard.bandwidth.com/api\n    humanURL: https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/\n    properties:\n      - url: https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/\n        type: Documentation\n      - url: openapi/bandwidth-emergency-calling-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bandwidth Emergency Calling API provides programmatic access to provision\n      and manage 911 endpoints and locations for emergency services routing. It supports\n      Dynamic Location Routing (DLR) for real-time address validation and location\n      updates, ensuring compliance with Kari's Law and RAY BAUM's Act requirements.\n  - aid: bandwidth:toll-free-verification-api\n\
  \    name: Bandwidth Toll-Free Verification API\n    tags:\n      - A2P\n      - Messaging Compliance\n      - Toll-Free\n      - Verification\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://dashboard.bandwidth.com/api\n    humanURL: https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/\n    properties:\n      - url: https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/\n        type: Documentation\n      - url: openapi/bandwidth-toll-free-verification-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bandwidth Toll-Free Verification API enables developers to\n      programmatically submit and manage toll-free number verification\n      requests for A2P messaging compliance. It automates the verification\n      submission process, allowing developers to view and update the\n      verification status of their toll-free numbers.\ncommon:\n  - type: Website\n    url: https://www.bandwidth.com/\n\
  \    name: Bandwidth\n  - type: Documentation\n    url: https://dev.bandwidth.com/\n    name: Bandwidth Developer Portal\n  - type: SignUp\n    url: https://app.bandwidth.com/signup\n    name: Sign Up for Bandwidth\n  - type: Blog\n    url: https://www.bandwidth.com/blog/\n    name: Bandwidth Blog\n  - type: TermsOfService\n    url: https://www.bandwidth.com/legal/\n    name: Terms of Service\n  - type: PrivacyPolicy\n    url: https://www.bandwidth.com/legal/privacy-policy/\n    name: Privacy Policy\n  - type: Status\n    url: https://status.bandwidth.com/\n    name: Bandwidth System Status\n  - type: Support\n    url: https://support.bandwidth.com/\n    name: Bandwidth Support\n  - type: SDK\n    url: https://dev.bandwidth.com/sdks/\n    name: Bandwidth SDKs\n  - type: SpectralRules\n    url: rules/bandwidth-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/bandwidth-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/communications-platform.yaml\n  - type:\
  \ JSONSchema\n    url: json-schema/bandwidth-call-schema.json\n  - type: JSONSchema\n    url: json-schema/bandwidth-message-schema.json\n  - type: JSONSchema\n    url: json-schema/bandwidth-phone-number-schema.json\n  - type: JSON-LD\n    url: json-ld/bandwidth-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Voice Calls\n        description: Programmable outbound and inbound voice call management with BXML call control.\n      - name: SMS Messaging\n        description: Send and receive SMS messages on local and toll-free numbers.\n      - name: MMS Messaging\n        description: Send and receive multimedia messages with images, video, and audio.\n      - name: Multi-Factor Authentication\n        description: OTP code delivery and verification via voice or SMS.\n      - name: Phone Number Management\n        description: Search, order, port, and configure US and Canadian phone numbers.\n      - name: Emergency Calling (E911)\n        description: Dynamic\
  \ location routing for compliant emergency call handling.\n      - name: Toll-Free Verification\n        description: Submit and track A2P toll-free number verification requests.\n      - name: Call Recording\n        description: Record and retrieve voice call audio for compliance and analytics.\n      - name: Conferences\n        description: Create multi-party voice conferences with participant management.\n      - name: Webhooks\n        description: Real-time event notifications for call state changes and message delivery.\n      - name: Tier 1 Network\n        description: Direct carrier connectivity on Bandwidth's own nationwide network.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Click-to-Call\n        description: Embed outbound calling in web and mobile applications.\n      - name: IVR Systems\n        description: Build interactive voice response menus with DTMF input and TTS.\n      - name: A2P Messaging\n        description: Send application-to-person\
  \ SMS campaigns at scale.\n      - name: 2FA / OTP\n        description: Add SMS or voice-based multi-factor authentication to applications.\n      - name: Number Provisioning\n        description: Automate phone number procurement and assignment for customers.\n      - name: E911 Compliance\n        description: Meet Kari's Law and RAY BAUM's Act requirements for enterprise voice.\n      - name: Call Center\n        description: Build inbound/outbound contact center applications with recording.\n      - name: Number Porting\n        description: Migrate existing phone numbers to Bandwidth programmatically.\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Cisco Webex\n      - name: Microsoft Teams\n      - name: Zoom Phone\n      - name: Twilio\n      - name: Salesforce\n      - name: Amazon Connect\n      - name: Genesys Cloud\ncreated: '2024-01-01'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/apis.yml
tags:
- Communications
- CPaaS
- Voice
- Messaging
- Telephony
- SMS
- MFA
url: https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/apis.yml
use_cases:
- description: Embed outbound calling in web and mobile applications.
  name: Click-to-Call
- description: Build interactive voice response menus with DTMF input and TTS.
  name: IVR Systems
- description: Send application-to-person SMS campaigns at scale.
  name: A2P Messaging
- description: Add SMS or voice-based multi-factor authentication to applications.
  name: 2FA / OTP
- description: Automate phone number procurement and assignment for customers.
  name: Number Provisioning
- description: Meet Kari's Law and RAY BAUM's Act requirements for enterprise voice.
  name: E911 Compliance
- description: Build inbound/outbound contact center applications with recording.
  name: Call Center
- description: Migrate existing phone numbers to Bandwidth programmatically.
  name: Number Porting
---
