---
api_count: 6
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
