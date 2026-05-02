---
api_count: 6
api_specs:
- filename: iterable-rest-api-openapi.yml
  format: yaml
  label: Iterable REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/openapi/iterable-rest-api-openapi.yml
- filename: iterable-export-api-openapi.yml
  format: yaml
  label: Iterable Export API
  slug: export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/openapi/iterable-export-api-openapi.yml
apis:
- description: The Iterable REST API provides programmatic access to the Iterable cross-channel marketing automation platform. It exposes endpoints for managing users, campaigns, lists, events, commerce tracking, ca
  name: Iterable REST API
  slug: rest-api
- description: The Iterable Export API enables developers to extract data from Iterable projects for analytics, reporting, and data warehousing purposes. It provides asynchronous export endpoints that allow bulk ret
  name: Iterable Export API
  slug: export-api
- description: The Iterable Web SDK enables developers to integrate Iterable's marketing automation capabilities directly into JavaScript and Node.js applications. It provides functions for tracking user events, man
  name: Iterable Web SDK
  slug: web-sdk
- description: The Iterable iOS SDK allows developers to integrate Iterable's marketing automation features into native iOS applications built with Swift or Objective-C. It supports push notifications, in-app messag
  name: Iterable iOS SDK
  slug: ios-sdk
- description: The Iterable Android SDK provides native integration between Android applications and the Iterable marketing automation platform. It supports push notifications, in-app messages, deep links, and Mobil
  name: Iterable Android SDK
  slug: android-sdk
- description: The Iterable React Native SDK enables developers to integrate Iterable's marketing automation capabilities into cross-platform mobile applications built with React Native. It wraps Iterable's native i
  name: Iterable React Native SDK
  slug: react-native-sdk
asyncapis:
- description: Iterable system webhooks send real-time event data from an Iterable project to external systems via HTTP POST requests whenever specified events occur. System webhooks can be configured to fire on ema
  name: Iterable System Webhooks
  slug: iterable-system-webhooks-asyncapi
common:
- title: ''
  type: AsyncAPI
  url: asyncapi/iterable-system-webhooks-asyncapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/iterable-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/iterable-user-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/iterable-campaign-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/iterable-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/iterable-commerce-item-schema.json
- title: ''
  type: Website
  url: https://iterable.com/
- title: ''
  type: Documentation
  url: https://api.iterable.com/api/docs
- title: ''
  type: Support
  url: https://support.iterable.com/hc/en-us
- title: ''
  type: Blog
  url: https://iterable.com/blog/
- title: ''
  type: Login
  url: https://app.iterable.com/login
- title: ''
  type: PrivacyPolicy
  url: https://iterable.com/trust/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://iterable.com/trust/terms-of-service/
created: '2026-03-20'
description: Iterable is an AI customer engagement platform that powers unified cross-channel marketing experiences and empowers marketers to create, optimize, and measure relevant interactions across email, push, SMS, in-app, and web channels. Their developer platform provides REST APIs, export APIs, AsyncAPI webhooks, and native SDKs for web, iOS, Android, and React Native.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Iterable Context
  property_count: 8
  slug: iterable-context
layout: provider
modified: '2026-04-28'
name: Iterable
skills: []
slug: iterable
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: iterable\nname: Iterable\ndescription: >-\n  Iterable is an AI customer engagement platform that powers unified\n  cross-channel marketing experiences and empowers marketers to create,\n  optimize, and measure relevant interactions across email, push, SMS, in-app,\n  and web channels. Their developer platform provides REST APIs, export APIs,\n  AsyncAPI webhooks, and native SDKs for web, iOS, Android, and React Native.\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cross-Channel Messaging\n  - Customer Engagement\n  - Email\n  - Marketing Automation\n  - Push Notifications\n  - SMS\nurl: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/apis.yml\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: iterable:rest-api\n    name: Iterable REST API\n    tags:\n      - Campaigns\n      - Cross-Channel Messaging\n      - Email\n      - Marketing Automation\n\
  \      - Push Notifications\n      - SMS\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.iterable.com\n    humanURL: https://api.iterable.com/api/docs\n    properties:\n      - url: https://api.iterable.com/api/docs\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/iterable-rest-api-openapi.yml\n    description: >-\n      The Iterable REST API provides programmatic access to the Iterable cross-channel\n      marketing automation platform. It exposes endpoints for managing users, campaigns,\n      lists, events, commerce tracking, catalogs, channels, templates, experiments,\n      workflows, and message delivery across email, push, SMS, and in-app channels.\n      The API uses standard HTTP methods, JSON request and response bodies, and supports\n      authentication via API keys or JWT-enabled keys.\n  - aid: iterable:export-api\n    name: Iterable Export API\n    tags:\n      - Analytics\n\
  \      - Data Export\n      - Marketing Data\n      - Reporting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.iterable.com\n    humanURL: https://support.iterable.com/hc/en-us/articles/204780579-Iterable-API-Endpoints-and-Sample-Payloads\n    properties:\n      - url: https://support.iterable.com/hc/en-us/articles/204780579-Iterable-API-Endpoints-and-Sample-Payloads\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/iterable-export-api-openapi.yml\n    description: >-\n      The Iterable Export API enables developers to extract data from Iterable\n      projects for analytics, reporting, and data warehousing purposes. It\n      provides asynchronous export endpoints that allow bulk retrieval of user\n      data, event data, campaign metrics, and message engagement information.\n      The export endpoints support filtering by date ranges and other criteria,\n      making it possible to build custom\
  \ reporting pipelines and synchronize\n      Iterable data with external business intelligence tools.\n  - aid: iterable:web-sdk\n    name: Iterable Web SDK\n    tags:\n      - In-App Messaging\n      - JavaScript\n      - SDK\n      - User Tracking\n      - Web\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://github.com/Iterable/iterable-web-sdk\n    properties:\n      - url: https://github.com/Iterable/iterable-web-sdk\n        type: Documentation\n    description: >-\n      The Iterable Web SDK enables developers to integrate Iterable's marketing automation\n      capabilities directly into JavaScript and Node.js applications. It provides\n      functions for tracking user events, managing user profiles, displaying in-app\n      messages, and handling web push notifications.\n  - aid: iterable:ios-sdk\n    name: Iterable iOS SDK\n    tags:\n      - In-App Messaging\n      - iOS\n     \
  \ - Mobile\n      - Push Notifications\n      - SDK\n      - Swift\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://support.iterable.com/hc/en-us/articles/360035018152-Iterable-s-iOS-SDK\n    properties:\n      - url: https://support.iterable.com/hc/en-us/articles/360035018152-Iterable-s-iOS-SDK\n        type: Documentation\n    description: >-\n      The Iterable iOS SDK allows developers to integrate Iterable's marketing\n      automation features into native iOS applications built with Swift or\n      Objective-C. It supports push notifications, in-app messages, deep links,\n      and Mobile Inbox functionality. The SDK can be installed via Swift Package\n      Manager, CocoaPods, or Carthage, and supports iOS 10 and higher. It\n      enables mobile apps to track user events, display targeted in-app content,\n      and participate in Iterable's cross-channel marketing campaigns.\n  - aid:\
  \ iterable:android-sdk\n    name: Iterable Android SDK\n    tags:\n      - Android\n      - In-App Messaging\n      - Mobile\n      - Push Notifications\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://support.iterable.com/hc/en-us/articles/360028925511-Overview-of-Iterable-s-iOS-and-Android-SDKs\n    properties:\n      - url: https://support.iterable.com/hc/en-us/articles/360028925511-Overview-of-Iterable-s-iOS-and-Android-SDKs\n        type: Documentation\n    description: >-\n      The Iterable Android SDK provides native integration between Android\n      applications and the Iterable marketing automation platform. It supports\n      push notifications, in-app messages, deep links, and Mobile Inbox\n      features. The open-source SDK enables Android apps to track user events,\n      manage user profiles, render in-app content, and connect with Iterable's\n      cross-channel\
  \ campaign orchestration. Developers can use it to deliver\n      personalized marketing experiences within their Android applications.\n  - aid: iterable:react-native-sdk\n    name: Iterable React Native SDK\n    tags:\n      - Cross-Platform\n      - JavaScript\n      - Mobile\n      - React Native\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://support.iterable.com/hc/en-us/articles/360045714072-Overview-of-Iterable-s-React-Native-SDK\n    properties:\n      - url: https://support.iterable.com/hc/en-us/articles/360045714072-Overview-of-Iterable-s-React-Native-SDK\n        type: Documentation\n    description: >-\n      The Iterable React Native SDK enables developers to integrate Iterable's marketing\n      automation capabilities into cross-platform mobile applications built with React\n      Native. It wraps Iterable's native iOS and Android SDKs and supports both JavaScript\n\
  \      and TypeScript. The SDK provides access to push notifications, in-app messages,\n      Mobile Inbox, user event tracking, and deep linking.\ncommon:\n  - type: AsyncAPI\n    url: asyncapi/iterable-system-webhooks-asyncapi.yml\n  - type: JSON-LD\n    url: json-ld/iterable-context.jsonld\n  - type: JSONSchema\n    url: json-schema/iterable-user-schema.json\n  - type: JSONSchema\n    url: json-schema/iterable-campaign-schema.json\n  - type: JSONSchema\n    url: json-schema/iterable-event-schema.json\n  - type: JSONSchema\n    url: json-schema/iterable-commerce-item-schema.json\n  - name: Iterable\n    url: https://iterable.com/\n    type: Website\n  - name: Iterable Developer Documentation\n    url: https://api.iterable.com/api/docs\n    type: Documentation\n  - name: Iterable Support Center\n    url: https://support.iterable.com/hc/en-us\n    type: Support\n  - name: Iterable Blog\n    url: https://iterable.com/blog/\n    type: Blog\n  - name: Iterable Login\n    url: https://app.iterable.com/login\n\
  \    type: Login\n  - name: Iterable Privacy Policy\n    url: https://iterable.com/trust/privacy-policy/\n    type: PrivacyPolicy\n  - name: Iterable Terms of Service\n    url: https://iterable.com/trust/terms-of-service/\n    type: TermsOfService\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/apis.yml
tags:
- Cross-Channel Messaging
- Customer Engagement
- Email
- Marketing Automation
- Push Notifications
- SMS
url: https://raw.githubusercontent.com/api-evangelist/iterable/refs/heads/main/apis.yml
use_cases: []
---
