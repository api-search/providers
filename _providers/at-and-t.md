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
source_yaml: "aid: at-and-t\nname: AT&T\ndescription: >-\n  AT&T is a multinational telecommunications holding company providing wireless\n  and wireline telecommunications services, broadband, and digital entertainment\n  to consumers and businesses worldwide. AT&T offers a suite of developer APIs\n  spanning messaging, speech, mobile virtual network operations, business voice,\n  wholesale service qualification, enterprise wireline ordering, and mobility\n  management, enabling developers and enterprise partners to integrate AT&T\n  network capabilities into applications and systems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Telecommunications\n  - Wireless\n  - Wireline\n  - Messaging\n  - Speech\n  - Mobile\n  - Broadband\n  - Enterprise\nurl: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: at-and-t:att-sms-api\n\
  \    name: AT&T SMS API\n    description: >-\n      A RESTful API enabling established businesses to broadcast SMS short code\n      messages to AT&T subscribers in the United States. Supports sending to up\n      to 50 recipients per call and up to 1 million messaging API calls monthly.\n      Includes delivery status callbacks and GSMA OneAPI-compatible endpoints.\n    humanURL: https://developer.att.com/sms\n    baseURL: https://api.att.com\n    tags:\n      - SMS\n      - Messaging\n      - Short Code\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://developer.att.com/sms/docs\n      - type: APIReference\n        url: https://developer.att.com/sms/docs/v2\n      - type: Authentication\n        url: https://developer.att.com/oauth-2/docs\n      - type: GettingStarted\n        url: https://developer.att.com/sms\n      - type: OpenAPI\n        url: openapi/at-and-t-sms-api.yaml\n  - aid: at-and-t:att-in-app-messaging-api\n    name: AT&T In-App\
  \ Messaging API\n    description: >-\n      A messaging API enabling applications to send, receive, update, and delete\n      MMS and SMS messages on behalf of users with explicit consent. Supports\n      messages to phone numbers, short codes, and email addresses across AT&T\n      and other carriers, with inbox management and delta synchronization.\n    humanURL: https://developer.att.com/in-app-messaging\n    baseURL: https://api.att.com\n    tags:\n      - MMS\n      - SMS\n      - Messaging\n      - In-App\n      - Inbox\n    properties:\n      - type: Documentation\n        url: https://developer.att.com/in-app-messaging/docs\n      - type: Authentication\n        url: https://developer.att.com/oauth-2/docs\n      - type: OpenAPI\n        url: openapi/at-and-t-in-app-messaging-api.yaml\n  - aid: at-and-t:att-oauth-api\n    name: AT&T OAuth 2.0 API\n    description: >-\n      AT&T OAuth 2.0 authentication API providing access tokens for all AT&T\n      REST APIs. Supports Authorization\
  \ Code, Client Credentials, and Refresh\n      Token grant types. Scopes include ADS, MMS, SMS, SPEECH, STTC, and TTS.\n    humanURL: https://developer.att.com/oauth-2\n    baseURL: https://api.att.com\n    tags:\n      - OAuth\n      - Authentication\n      - Authorization\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.att.com/oauth-2/docs\n      - type: Authentication\n        url: https://developer.att.com/oauth-2/docs\n  - aid: at-and-t:att-mvnx-api\n    name: AT&T MVNX API\n    description: >-\n      TM Forum-aligned API suite for mobile virtual network operators (MVNOs)\n      enabling subscriber activation, number management, porting operations,\n      device and SIM management, subscriber profile management, service\n      management, and policy and balance management. Follows TMF standards\n      (622, 637, 639, 640, 654, 674, 689, 702, 716, 761).\n    humanURL: https://devex-web.att.com/mvnx\n    baseURL: https://devex-web.att.com\n\
  \    tags:\n      - MVNO\n      - Mobile\n      - Subscriber\n      - TM Forum\n      - Porting\n      - SIM\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/mvnx/docs/mvnx-quickstart\n      - type: GettingStarted\n        url: https://devex-web.att.com/mvnx/docs/mvnx-quickstart\n      - type: OpenAPI\n        url: openapi/at-and-t-mvnx-api.yaml\n  - aid: at-and-t:att-alliance-wireline-apis\n    name: AT&T Alliance Wireline APIs\n    description: >-\n      Wireline business APIs enabling partners to expedite quoting, service\n      qualification, and ordering of AT&T wireline products. Includes Quick\n      Quote, Product Catalog, Service Qualification, Price Offer, Wireline\n      Ordering, Order Status, AIAB (AT&T Internet Air for Business) Ordering,\n      and Address Search APIs.\n    humanURL: https://devex-web.att.com/alliance\n    baseURL: https://devex-web.att.com\n    tags:\n      - Wireline\n      - Enterprise\n      - Ordering\n      - Service\
  \ Qualification\n      - Quoting\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/alliance\n      - type: GettingStarted\n        url: https://devex-web.att.com/order/docs/get-started-with-ordering-api\ncommon:\n  - type: Website\n    url: https://www.att.com\n  - type: Portal\n    url: https://developer.att.com/s/\n  - type: DeveloperPortal\n    url: https://devex-web.att.com/\n  - type: Documentation\n    url: https://developer.att.com/s/\n  - type: Authentication\n    url: https://developer.att.com/oauth-2/docs\n  - type: Support\n    url: https://developer.att.com/support\n  - type: FAQ\n    url: https://developer.att.com/support/faqs/att-developer-program-and-api-platform-faqs\n  - type: TermsOfService\n    url: https://www.att.com/gen/general?pid=11561\n  - type: PrivacyPolicy\n    url: https://www.att.com/gen/privacy-policy?pid=2506\n  - type: SignUp\n    url: https://developer.att.com/developer/manageMyAccount.jsp\n  - type: GitHubOrganization\n\
  \    url: https://github.com/attdevsupport\n  - type: GitHubOrganization\n    url: https://github.com/att\n  - type: SpectralRules\n    url: rules/at-and-t-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/at-and-t-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/messaging.yaml\n  - type: NaftikoCapability\n    url: capabilities/mvno-operations.yaml\n  - type: Features\n    data:\n      - name: OAuth 2.0 Authentication\n        description: >-\n          All APIs use OAuth 2.0 with client credentials, authorization code,\n          and refresh token flows supporting multiple API scopes.\n      - name: SMS Short Code Messaging\n        description: >-\n          Broadcast SMS short code messages to AT&T subscribers with delivery\n          tracking and callback notifications.\n      - name: MMS and In-App Messaging\n        description: >-\n          Send and receive MMS and SMS messages with inbox management,\n          delta synchronization, and cross-carrier\
  \ support.\n      - name: MVNO Infrastructure Services\n        description: >-\n          Full MVNO lifecycle management including subscriber activation,\n          number portability, device management, and balance management via TM Forum APIs.\n      - name: Wireline Service Qualification and Ordering\n        description: >-\n          Automated quoting, service eligibility validation, and ordering\n          for AT&T wireline products including AVPN, IPBB, ATTPhone, and more.\n  - type: UseCases\n    data:\n      - name: SMS Alerts and Notifications\n        description: >-\n          Send security verification codes, appointment reminders, promotional\n          offers, and customer feedback requests via SMS short code.\n      - name: In-App Messaging Integration\n        description: >-\n          Embed MMS and SMS messaging directly into mobile applications\n          with full inbox management capabilities.\n      - name: Mobile Virtual Network Operations\n        description:\
  \ >-\n          Launch and operate MVNO services using AT&T's network with automated\n          subscriber onboarding, porting, and lifecycle management.\n      - name: Enterprise Wireline Ordering\n        description: >-\n          Automate service qualification, quoting, and order submission\n          for enterprise connectivity services.\n  - type: Integrations\n    data:\n      - name: IBM Worklight\n        description: >-\n          AT&T API Platform Adapters for IBM Worklight mobile development platform.\n      - name: Salesforce Platform\n        description: >-\n          AT&T Toolkit for Salesforce enabling speech and messaging API integration in Salesforce apps.\n      - name: TM Forum APIs\n        description: >-\n          MVNX APIs align with TM Forum Open API standards including TMF 622, 637, 639, 640, 654, 674, 689, 702, 716, and 761.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/at-and-t/refs/heads/main/apis.yml
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
