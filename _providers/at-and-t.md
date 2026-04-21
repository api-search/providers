---
api_count: 5
apis:
- description: A RESTful API enabling established businesses to broadcast SMS short code messages to AT&T subscribers in the United States. Supports sending to up to 50 recipients per call and up to 1 million messag
  name: AT&T SMS API
  slug: att-sms-api
- description: A messaging API enabling applications to send, receive, update, and delete MMS and SMS messages on behalf of users with explicit consent. Supports messages to phone numbers, short codes, and email add
  name: AT&T In-App Messaging API
  slug: att-in-app-messaging-api
- description: 'AT&T OAuth 2.0 authentication API providing access tokens for all AT&T REST APIs. Supports Authorization Code, Client Credentials, and Refresh Token grant types. Scopes include ADS, MMS, SMS, SPEECH, '
  name: AT&T OAuth 2.0 API
  slug: att-oauth-api
- description: TM Forum-aligned API suite for mobile virtual network operators (MVNOs) enabling subscriber activation, number management, porting operations, device and SIM management, subscriber profile management,
  name: AT&T MVNX API
  slug: att-mvnx-api
- description: 'Wireline business APIs enabling partners to expedite quoting, service qualification, and ordering of AT&T wireline products. Includes Quick Quote, Product Catalog, Service Qualification, Price Offer, '
  name: AT&T Alliance Wireline APIs
  slug: att-alliance-wireline-apis
capabilities:
- description: Unified messaging capability combining AT&T SMS API and In-App Messaging API for customer notifications, two-way messaging, and inbox management. Used by developers building mobile apps and enterprise
  name: AT&T Messaging
  slug: messaging
- description: Comprehensive MVNO management capability using AT&T MVNX API for subscriber lifecycle management, number portability, device inventory, and balance management. Used by MVNO operators managing AT&T-pow
  name: AT&T MVNO Operations
  slug: mvno-operations
common:
- title: ''
  type: Website
  url: https://www.att.com
- title: ''
  type: Portal
  url: https://developer.att.com/s/
- title: ''
  type: DeveloperPortal
  url: https://devex-web.att.com/
- title: ''
  type: Documentation
  url: https://developer.att.com/s/
- title: ''
  type: Authentication
  url: https://developer.att.com/oauth-2/docs
- title: ''
  type: Support
  url: https://developer.att.com/support
- title: ''
  type: FAQ
  url: https://developer.att.com/support/faqs/att-developer-program-and-api-platform-faqs
- title: ''
  type: TermsOfService
  url: https://www.att.com/gen/general?pid=11561
- title: ''
  type: PrivacyPolicy
  url: https://www.att.com/gen/privacy-policy?pid=2506
- title: ''
  type: SignUp
  url: https://developer.att.com/developer/manageMyAccount.jsp
- title: ''
  type: GitHubOrganization
  url: https://github.com/attdevsupport
- title: ''
  type: GitHubOrganization
  url: https://github.com/att
- title: ''
  type: SpectralRules
  url: rules/at-and-t-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/at-and-t-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/messaging.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/mvno-operations.yaml
created: '2026-03-21'
description: AT&T is a multinational telecommunications holding company providing wireless and wireline telecommunications services, broadband, and digital entertainment to consumers and businesses worldwide. AT&T offers a suite of developer APIs spanning messaging, speech, mobile virtual network operations, business voice, wholesale service qualification, enterprise wireline ordering, and mobility management, enabling developers and enterprise partners to integrate AT&T network capabilities into applications and systems.
features:
- description: All APIs use OAuth 2.0 with client credentials, authorization code, and refresh token flows supporting multiple API scopes.
  name: OAuth 2.0 Authentication
- description: Broadcast SMS short code messages to AT&T subscribers with delivery tracking and callback notifications.
  name: SMS Short Code Messaging
- description: Send and receive MMS and SMS messages with inbox management, delta synchronization, and cross-carrier support.
  name: MMS and In-App Messaging
- description: Full MVNO lifecycle management including subscriber activation, number portability, device management, and balance management via TM Forum APIs.
  name: MVNO Infrastructure Services
- description: Automated quoting, service eligibility validation, and ordering for AT&T wireline products including AVPN, IPBB, ATTPhone, and more.
  name: Wireline Service Qualification and Ordering
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AT&T API Platform Adapters for IBM Worklight mobile development platform.
  name: IBM Worklight
- description: AT&T Toolkit for Salesforce enabling speech and messaging API integration in Salesforce apps.
  name: Salesforce Platform
- description: MVNX APIs align with TM Forum Open API standards including TMF 622, 637, 639, 640, 654, 674, 689, 702, 716, and 761.
  name: TM Forum APIs
jsonld:
- class_count: 9
  name: At And T In App Messaging Api Context
  property_count: 28
  slug: at-and-t-in-app-messaging-api-context
- class_count: 18
  name: At And T Mvnx Api Context
  property_count: 30
  slug: at-and-t-mvnx-api-context
- class_count: 8
  name: At And T Sms Api Context
  property_count: 27
  slug: at-and-t-sms-api-context
layout: provider
modified: '2026-04-19'
name: AT&T
rules:
- name: AT&T API Rules
  rule_count: 37
  severity_counts:
    error: 16
    hint: 0
    info: 3
    warn: 18
  slug: at-and-t-spectral-rules
skills: []
slug: at-and-t
solutions: []
tags:
- Telecommunications
- Wireless
- Wireline
- Messaging
- Speech
- Mobile
- Broadband
- Enterprise
url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/apis.yml
use_cases:
- description: Send security verification codes, appointment reminders, promotional offers, and customer feedback requests via SMS short code.
  name: SMS Alerts and Notifications
- description: Embed MMS and SMS messaging directly into mobile applications with full inbox management capabilities.
  name: In-App Messaging Integration
- description: Launch and operate MVNO services using AT&T's network with automated subscriber onboarding, porting, and lifecycle management.
  name: Mobile Virtual Network Operations
- description: Automate service qualification, quoting, and order submission for enterprise connectivity services.
  name: Enterprise Wireline Ordering
---
