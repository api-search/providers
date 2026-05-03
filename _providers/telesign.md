---
api_count: 5
api_specs:
- filename: telesign-sms-openapi.yml
  format: yaml
  label: Telesign SMS API
  slug: sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-sms-openapi.yml
- filename: telesign-phoneid-openapi.yml
  format: yaml
  label: Telesign PhoneID API
  slug: phoneid-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-phoneid-openapi.yml
- filename: telesign-verify-openapi.yml
  format: yaml
  label: Telesign Verify API
  slug: verify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-verify-openapi.yml
- filename: telesign-score-openapi.yml
  format: yaml
  label: Telesign Score API
  slug: score-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/openapi/telesign-score-openapi.yml
apis:
- description: Send SMS messages including alerts, notifications, reminders, marketing messages, and one-time passwords to phone numbers worldwide. Messages are classified by type (OTP, ARN, MKT) and provide deliver
  name: Telesign SMS API
  slug: sms-api
- description: Retrieve global phone number intelligence including carrier information, geographic location, phone type (mobile, landline, VoIP), and subscriber data. Used for fraud prevention, identity verification
  name: Telesign PhoneID API
  slug: phoneid-api
- description: Multi-channel phone-based verification and MFA. Send one-time passcodes via SMS, voice, WhatsApp, Viber, RCS, or email, and verify codes submitted by end users. Supports password reset, account creati
  name: Telesign Verify API
  slug: verify-api
- description: Assess fraud risk for phone numbers using reputation scoring based on intelligence, traffic patterns, machine learning, and a global data consortium. Returns a risk level and numeric score with a reco
  name: Telesign Score API
  slug: score-api
- description: Send voice messages including OTPs, alerts, and notifications to phone numbers worldwide. Supports text-to-speech message delivery and call status tracking.
  name: Telesign Voice API
  slug: voice-api
capabilities:
- description: Unified workflow for phone-based identity verification and fraud prevention. Combines PhoneID intelligence, fraud risk scoring, and multi-channel OTP verification to enable secure account creation, lo
  name: Telesign Identity Verification
  slug: identity-verification
common:
- title: ''
  type: Website
  url: https://www.telesign.com/
- title: ''
  type: Developer Portal
  url: https://developer.telesign.com/enterprise
- title: ''
  type: Authentication
  url: https://developer.telesign.com/enterprise/docs/authentication
- title: ''
  type: Status Page
  url: https://status.telesign.com/
- title: ''
  type: Pricing
  url: https://www.telesign.com/pricing/
- title: ''
  type: Terms of Service
  url: https://www.telesign.com/terms-conditions/
- title: ''
  type: GitHub Organization
  url: https://github.com/TeleSign
created: ''
description: Telesign provides a comprehensive suite of communications and security APIs enabling businesses to verify phone numbers, send SMS and voice messages, and assess fraud risk. Core offerings include SMS messaging, voice calls, multi-channel verification (OTP/MFA), phone number intelligence (PhoneID), reputation scoring, and silent verification. Telesign serves thousands of enterprises globally for account security, fraud prevention, and customer communications.
features: []
image: ''
integrations: []
jsonld:
- class_count: 3
  name: Telesign Context
  property_count: 5
  slug: telesign-context
layout: provider
modified: '2026-05-03'
name: Telesign
rules:
- name: Telesign API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 1
    info: 0
    warn: 7
  slug: telesign-rules
skills: []
slug: telesign
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: telesign\nname: Telesign\ndescription: >-\n  Telesign provides a comprehensive suite of communications and security APIs enabling\n  businesses to verify phone numbers, send SMS and voice messages, and assess fraud risk.\n  Core offerings include SMS messaging, voice calls, multi-channel verification (OTP/MFA),\n  phone number intelligence (PhoneID), reputation scoring, and silent verification. Telesign\n  serves thousands of enterprises globally for account security, fraud prevention, and\n  customer communications.\nurl: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/apis.yml\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Authentication\n  - Communications\n  - Fraud Prevention\n  - Phone Intelligence\n  - SMS\n  - Verification\napis:\n  - aid: telesign:sms-api\n    name: Telesign SMS API\n    description: >-\n      Send SMS messages including alerts, notifications, reminders, marketing messages,\n      and one-time passwords\
  \ to phone numbers worldwide. Messages are classified by type\n      (OTP, ARN, MKT) and provide delivery status tracking via reference IDs.\n    humanURL: https://developer.telesign.com/enterprise/docs/sms-get-started\n    baseURL: https://rest-ww.telesign.com/v1\n    tags:\n      - Alerts\n      - Messaging\n      - Notifications\n      - OTP\n      - SMS\n    properties:\n      - type: Documentation\n        url: https://developer.telesign.com/enterprise/docs/sms-get-started\n      - type: OpenAPI\n        url: openapi/telesign-sms-openapi.yml\n  - aid: telesign:phoneid-api\n    name: Telesign PhoneID API\n    description: >-\n      Retrieve global phone number intelligence including carrier information, geographic\n      location, phone type (mobile, landline, VoIP), and subscriber data. Used for fraud\n      prevention, identity verification, and risk assessment during account creation and\n      transactions.\n    humanURL: https://developer.telesign.com/enterprise/docs/phoneid-api-overview\n\
  \    baseURL: https://rest-ww.telesign.com/v1\n    tags:\n      - Carrier Data\n      - Fraud Prevention\n      - Identity Verification\n      - Phone Intelligence\n      - Risk Assessment\n    properties:\n      - type: Documentation\n        url: https://developer.telesign.com/enterprise/docs/phoneid-api-overview\n      - type: OpenAPI\n        url: openapi/telesign-phoneid-openapi.yml\n  - aid: telesign:verify-api\n    name: Telesign Verify API\n    description: >-\n      Multi-channel phone-based verification and MFA. Send one-time passcodes via SMS,\n      voice, WhatsApp, Viber, RCS, or email, and verify codes submitted by end users.\n      Supports password reset, account creation verification, and login MFA flows.\n    humanURL: https://developer.telesign.com/enterprise/docs/verify-api-overview\n    baseURL: https://rest-ww.telesign.com/v1\n    tags:\n      - Authentication\n      - MFA\n      - OTP\n      - Two-Factor Authentication\n      - Verification\n    properties:\n   \
  \   - type: Documentation\n        url: https://developer.telesign.com/enterprise/docs/verify-api-overview\n      - type: OpenAPI\n        url: openapi/telesign-verify-openapi.yml\n  - aid: telesign:score-api\n    name: Telesign Score API\n    description: >-\n      Assess fraud risk for phone numbers using reputation scoring based on intelligence,\n      traffic patterns, machine learning, and a global data consortium. Returns a risk\n      level and numeric score with a recommended action (allow, flag, block).\n    humanURL: https://developer.telesign.com/enterprise/docs/score-api-overview\n    baseURL: https://rest-ww.telesign.com/v1\n    tags:\n      - Fraud Detection\n      - Phone Intelligence\n      - Risk Scoring\n    properties:\n      - type: Documentation\n        url: https://developer.telesign.com/enterprise/docs/score-api-overview\n      - type: OpenAPI\n        url: openapi/telesign-score-openapi.yml\n  - aid: telesign:voice-api\n    name: Telesign Voice API\n    description:\
  \ >-\n      Send voice messages including OTPs, alerts, and notifications to phone numbers\n      worldwide. Supports text-to-speech message delivery and call status tracking.\n    humanURL: https://developer.telesign.com/enterprise/docs/voice-get-started\n    baseURL: https://rest-ww.telesign.com/v1\n    tags:\n      - OTP\n      - Telecommunications\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://developer.telesign.com/enterprise/docs/voice-get-started\ncommon:\n  - type: Website\n    url: https://www.telesign.com/\n  - type: Developer Portal\n    url: https://developer.telesign.com/enterprise\n  - type: Authentication\n    url: https://developer.telesign.com/enterprise/docs/authentication\n  - type: Status Page\n    url: https://status.telesign.com/\n  - type: Pricing\n    url: https://www.telesign.com/pricing/\n  - type: Terms of Service\n    url: https://www.telesign.com/terms-conditions/\n  - type: GitHub Organization\n    url: https://github.com/TeleSign\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/apis.yml
tags:
- Authentication
- Communications
- Fraud Prevention
- Phone Intelligence
- SMS
- Verification
url: https://raw.githubusercontent.com/api-evangelist/telesign/refs/heads/main/apis.yml
use_cases: []
---
