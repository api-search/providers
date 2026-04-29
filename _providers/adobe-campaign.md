---
api_count: 5
api_specs:
- filename: adobe-campaign-standard-openapi-original.yml
  format: yaml
  label: Adobe Campaign Standard API
  slug: standard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-campaign/refs/heads/main/openapi/adobe-campaign-standard-openapi-original.yml
- filename: adobe-campaign-classic-openapi-original.yml
  format: yaml
  label: Adobe Campaign Classic API
  slug: classic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-campaign/refs/heads/main/openapi/adobe-campaign-classic-openapi-original.yml
apis:
- description: REST API for Adobe Campaign Standard enabling integration with marketing campaigns, profiles, workflows, and messaging services.
  name: Adobe Campaign Standard API
  slug: standard-api
- description: SOAP and JavaScript APIs for Adobe Campaign Classic v7 and v8, providing programmatic access to campaign management, delivery, and data operations.
  name: Adobe Campaign Classic API
  slug: classic-api
- description: 'An open-source JavaScript SDK that wraps Adobe Campaign Classic SOAP APIs in a simple, expressive, JavaScript-idiomatic interface. The SDK supports asynchronous promise-based operations for querying, '
  name: Adobe Campaign Classic JavaScript SDK
  slug: classic-javascript-sdk
- description: 'A Node.js JavaScript SDK wrapping Adobe Campaign Standard REST APIs for use in Adobe I/O Runtime and App Builder applications. Provides convenience methods for profile management, service operations, '
  name: Adobe I/O Campaign Standard SDK
  slug: io-campaign-standard-sdk
- description: Native mobile SDK extensions for iOS and Android that integrate Adobe Campaign push notifications, in-app messaging, and local notifications into mobile applications. Includes the Campaign Classic ext
  name: Adobe Experience Platform Mobile SDK - Campaign Extensions
  slug: experience-platform-mobile-sdk---campaign-extensions
asyncapis:
- description: Event-driven transactional messaging system for Adobe Campaign. Supports triggering personalized messages across email, SMS, and push notification channels in response to real-time customer events. Ev
  name: Adobe Campaign Transactional Messaging Events
  slug: adobe-campaign-transactional-messaging-asyncapi-original
common:
- title: ''
  type: Portal
  url: https://developer.adobe.com/
- title: ''
  type: Authentication
  url: https://developer.adobe.com/developer-console/docs/guides/authentication/
- title: ''
  type: GettingStarted
  url: https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html
- title: ''
  type: Support
  url: https://experienceleague.adobe.com/docs/customer-one/using/home.html
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy.html
- title: ''
  type: Blog
  url: https://business.adobe.com/blog/
created: '2024-01-01'
description: Adobe Campaign is a comprehensive marketing automation platform that enables businesses to orchestrate personalized customer experiences across multiple channels including email, mobile, social, and web.
features:
- description: Design and execute campaigns across email, SMS, push, direct mail, and web channels.
  name: Cross-Channel Campaign Orchestration
- description: Manage customer profiles, segments, and audiences for targeted messaging.
  name: Profile and Audience Management
- description: Send transactional and marketing emails with personalization and A/B testing.
  name: Email Delivery
- description: Build and execute automated marketing workflows with visual workflow designer.
  name: Workflow Automation
- description: Trigger personalized messages in real time based on customer events and behaviors.
  name: Real-Time Messaging
- description: Access campaign performance metrics, delivery statistics, and audience insights.
  name: Reporting and Analytics
- description: Dynamic content blocks and personalization fields for tailored messaging.
  name: Content Personalization
- description: Send mobile push notifications to iOS and Android devices.
  name: Push Notifications
- description: Send SMS campaigns and transactional messages to mobile subscribers.
  name: SMS Messaging
- description: Create and manage landing pages for campaign responses and lead capture.
  name: Landing Pages
image: /assets/icons/adobe-campaign.png
integrations:
- description: Native integration with AEM, Analytics, and Target for unified marketing.
  name: Adobe Experience Cloud
- description: Real-time customer profile and audience sharing with AEP.
  name: Adobe Experience Platform
- description: CRM integration for syncing contacts, leads, and campaign data.
  name: Salesforce
- description: CRM integration for contact synchronization and campaign tracking.
  name: Microsoft Dynamics
jsonld:
- class_count: 29
  name: Adobe Campaign Context
  property_count: 57
  slug: adobe-campaign-context
layout: provider
modified: '2026-04-17'
name: Adobe Campaign
rules:
- name: Adobe Campaign API Rules
  rule_count: 17
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 2
  slug: adobe-campaign-spectral-rules
skills: []
slug: adobe-campaign
solutions:
- description: Cloud-native marketing automation with modern REST APIs and visual workflow designer.
  name: Adobe Campaign Standard
- description: On-premises/hybrid marketing automation with SOAP and JavaScript APIs.
  name: Adobe Campaign Classic
- description: Latest generation combining Campaign Classic power with cloud scalability.
  name: Adobe Campaign v8
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: adobe-campaign\nurl: https://raw.githubusercontent.com/api-evangelist/adobe-campaign/refs/heads/main/apis.yml\nname: Adobe Campaign\ndescription: Adobe Campaign is a comprehensive marketing automation platform that\n  enables businesses to orchestrate personalized customer experiences across multiple\n  channels including email, mobile, social, and web.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ntags:\n- Campaign Management\n- Customer Experience\n- Email Marketing\n- Marketing Automation\n- Multi-Channel Marketing\ncreated: '2024-01-01'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\napis:\n- name: Adobe Campaign Standard API\n  description: REST API for Adobe Campaign Standard enabling integration with marketing\n    campaigns, profiles, workflows, and messaging services.\n  image: https://www.adobe.com/content/dam/cc/icons/adobe-campaign.svg\n  humanURL: https://experienceleague.adobe.com/docs/campaign-standard/using/working-with-apis/about-campaign-standard-apis.html\n\
  \  baseURL: https://mc.adobe.io/{ORGANIZATION}/campaign\n  tags:\n  - Email\n  - Marketing\n  - Profiles\n  - REST API\n  - Workflows\n  properties:\n  - type: Documentation\n    url: https://experienceleague.adobe.com/docs/campaign-standard/using/working-with-apis/get-started-apis.html\n  - type: OpenAPI\n    url: openapi/adobe-campaign-standard-openapi-original.yml\n  - type: APIReference\n    url: https://developer.adobe.com/campaign/api/\n  - type: Authentication\n    url: https://experienceleague.adobe.com/docs/campaign-standard/using/working-with-apis/authentication.html\n  - type: AsyncAPI\n    url: asyncapi/adobe-campaign-transactional-messaging-asyncapi-original.yml\n  aid: adobe-campaign:standard-api\n- name: Adobe Campaign Classic API\n  description: SOAP and JavaScript APIs for Adobe Campaign Classic v7 and v8, providing\n    programmatic access to campaign management, delivery, and data operations.\n  image: https://www.adobe.com/content/dam/cc/icons/adobe-campaign.svg\n \
  \ humanURL: https://experienceleague.adobe.com/docs/campaign-classic/using/configuring-campaign-classic/api/about-web-services.html\n  baseURL: https://{instance}.campaign.adobe.com\n  tags:\n  - Campaign Classic\n  - Delivery\n  - JavaScript\n  - SOAP API\n  properties:\n  - type: Documentation\n    url: https://experienceleague.adobe.com/docs/campaign-classic/using/configuring-campaign-classic/api/web-service-calls.html\n  - type: OpenAPI\n    url: openapi/adobe-campaign-classic-openapi-original.yml\n  - type: JSAPI Reference\n    url: https://experienceleague.adobe.com/developer/campaign-api/api/index.html\n  - type: SOAP Methods\n    url: https://experienceleague.adobe.com/docs/campaign-classic/using/configuring-campaign-classic/api/soap-methods.html\n  - type: AsyncAPI\n    url: asyncapi/adobe-campaign-transactional-messaging-asyncapi-original.yml\n  aid: adobe-campaign:classic-api\n- name: Adobe Campaign Classic JavaScript SDK\n  description: An open-source JavaScript SDK that wraps\
  \ Adobe Campaign Classic SOAP\n    APIs in a simple, expressive, JavaScript-idiomatic interface. The SDK supports\n    asynchronous promise-based operations for querying, data management, workflow\n    control, and session management. It works server-side with Node.js and client-side\n    in the browser, abstracting away SOAP calls, XML-to-JSON conversion, and type\n    formatting. Compatible with Campaign Classic v7 and v8.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://opensource.adobe.com/acc-js-sdk/\n  baseURL: https://{instance}.campaign.adobe.com\n  tags:\n  - Campaign Classic\n  - JavaScript SDK\n  - Node.js\n  - Open Source\n  - SOAP Wrapper\n  properties:\n  - type: Documentation\n    url: https://opensource.adobe.com/acc-js-sdk/\n  - type: GitHubRepository\n    url: https://github.com/adobe/acc-js-sdk\n  - type: NPMPackage\n    url: https://www.npmjs.com/package/@adobe/acc-js-sdk\n  aid: adobe-campaign:classic-javascript-sdk\n\
  - name: Adobe I/O Campaign Standard SDK\n  description: A Node.js JavaScript SDK wrapping Adobe Campaign Standard REST APIs\n    for use in Adobe I/O Runtime and App Builder applications. Provides convenience\n    methods for profile management, service operations, workflow control, transactional\n    messaging, GDPR compliance requests, and custom resource management. Handles authentication\n    and API communication for building serverless integrations with Campaign Standard.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://github.com/adobe/aio-lib-campaign-standard\n  baseURL: https://mc.adobe.io/{ORGANIZATION}/campaign\n  tags:\n  - Adobe I/O\n  - App Builder\n  - Campaign Standard\n  - JavaScript SDK\n  - Node.js\n  properties:\n  - type: Documentation\n    url: https://github.com/adobe/aio-lib-campaign-standard/blob/master/README.md\n  - type: GitHubRepository\n    url: https://github.com/adobe/aio-lib-campaign-standard\n \
  \ - type: NPMPackage\n    url: https://www.npmjs.com/package/@adobe/aio-lib-campaign-standard\n  aid: adobe-campaign:io-campaign-standard-sdk\n- name: Adobe Experience Platform Mobile SDK - Campaign Extensions\n  description: Native mobile SDK extensions for iOS and Android that integrate Adobe\n    Campaign push notifications, in-app messaging, and local notifications into mobile\n    applications. Includes the Campaign Classic extension for v7 and v8 providing\n    device registration and notification click tracking, and the Campaign Standard\n    extension providing push identifier management and message interaction tracking.\n    Part of the Adobe Experience Platform Mobile SDK framework.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://developer.adobe.com/client-sdks/solution/adobe-campaign-classic/\n  baseURL: https://api.example.com\n  tags:\n  - Android\n  - In-App Messaging\n  - iOS\n  - Mobile SDK\n  - Push Notifications\n\
  \  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/client-sdks/solution/adobe-campaign-classic/\n  - type: Documentation\n    url: https://developer.adobe.com/client-sdks/solution/adobe-campaign-standard/\n  - type: APIReference\n    url: https://developer.adobe.com/client-sdks/solution/adobe-campaign-classic/api-reference/\n  aid: adobe-campaign:experience-platform-mobile-sdk---campaign-extensions\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Portal\n  url: https://developer.adobe.com/\n- type: Authentication\n  url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n- type: GettingStarted\n  url: https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html\n- type: Support\n  url: https://experienceleague.adobe.com/docs/customer-one/using/home.html\n- type: StatusPage\n  url: https://status.adobe.com/\n- type: TermsOfService\n  url: https://www.adobe.com/legal/terms.html\n- type: PrivacyPolicy\n\
  \  url: https://www.adobe.com/privacy.html\n- type: Blog\n  url: https://business.adobe.com/blog/\n- type: Features\n  data:\n  - name: Cross-Channel Campaign Orchestration\n    description: Design and execute campaigns across email, SMS, push, direct mail,\n      and web channels.\n  - name: Profile and Audience Management\n    description: Manage customer profiles, segments, and audiences for targeted messaging.\n  - name: Email Delivery\n    description: Send transactional and marketing emails with personalization and\n      A/B testing.\n  - name: Workflow Automation\n    description: Build and execute automated marketing workflows with visual workflow\n      designer.\n  - name: Real-Time Messaging\n    description: Trigger personalized messages in real time based on customer events\n      and behaviors.\n  - name: Reporting and Analytics\n    description: Access campaign performance metrics, delivery statistics, and audience\n      insights.\n  - name: Content Personalization\n \
  \   description: Dynamic content blocks and personalization fields for tailored messaging.\n  - name: Push Notifications\n    description: Send mobile push notifications to iOS and Android devices.\n  - name: SMS Messaging\n    description: Send SMS campaigns and transactional messages to mobile subscribers.\n  - name: Landing Pages\n    description: Create and manage landing pages for campaign responses and lead capture.\n- type: UseCases\n  data:\n  - name: Email Marketing Campaigns\n    description: Design, personalize, and send email campaigns with tracking and analytics.\n  - name: Customer Journey Orchestration\n    description: Build multi-step customer journeys with triggers, conditions, and\n      automated actions.\n  - name: Transactional Messaging\n    description: Send real-time transactional emails and SMS for order confirmations\n      and alerts.\n  - name: Lead Nurturing\n    description: Automate lead scoring and nurture sequences based on engagement data.\n  - name:\
  \ Audience Segmentation\n    description: Build dynamic audience segments for targeted campaign delivery.\n  - name: Cross-Channel Coordination\n    description: Coordinate messaging across email, SMS, push, and direct mail channels.\n- type: Integrations\n  data:\n  - name: Adobe Experience Cloud\n    description: Native integration with AEM, Analytics, and Target for unified marketing.\n  - name: Adobe Experience Platform\n    description: Real-time customer profile and audience sharing with AEP.\n  - name: Salesforce\n    description: CRM integration for syncing contacts, leads, and campaign data.\n  - name: Microsoft Dynamics\n    description: CRM integration for contact synchronization and campaign tracking.\n- type: Solutions\n  data:\n  - name: Adobe Campaign Standard\n    description: Cloud-native marketing automation with modern REST APIs and visual\n      workflow designer.\n  - name: Adobe Campaign Classic\n    description: On-premises/hybrid marketing automation with SOAP and\
  \ JavaScript\n      APIs.\n  - name: Adobe Campaign v8\n    description: Latest generation combining Campaign Classic power with cloud scalability.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-campaign/refs/heads/main/apis.yml
tags:
- Campaign Management
- Customer Experience
- Email Marketing
- Marketing Automation
- Multi-Channel Marketing
url: https://raw.githubusercontent.com/api-evangelist/adobe-campaign/refs/heads/main/apis.yml
use_cases:
- description: Design, personalize, and send email campaigns with tracking and analytics.
  name: Email Marketing Campaigns
- description: Build multi-step customer journeys with triggers, conditions, and automated actions.
  name: Customer Journey Orchestration
- description: Send real-time transactional emails and SMS for order confirmations and alerts.
  name: Transactional Messaging
- description: Automate lead scoring and nurture sequences based on engagement data.
  name: Lead Nurturing
- description: Build dynamic audience segments for targeted campaign delivery.
  name: Audience Segmentation
- description: Coordinate messaging across email, SMS, push, and direct mail channels.
  name: Cross-Channel Coordination
---
