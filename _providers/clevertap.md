---
api_count: 8
apis:
- description: Upload, retrieve, update, and delete user profiles in CleverTap with identity, demographic, and custom property data.
  name: CleverTap Profile API
  slug: profile-api
- description: Record user events with arbitrary properties for behavioral segmentation, funnels, and triggered messaging.
  name: CleverTap Event API
  slug: event-api
- description: Programmatically create and manage push, email, SMS, web, and in-app campaigns and retrieve message status reports.
  name: CleverTap Campaign API
  slug: campaign-api
- description: Raise a Bulletin in CleverTap when a business event is triggered, used to drive real-time campaign delivery from external systems.
  name: CleverTap Bulletins API
  slug: bulletins-api
- description: Manage product catalog data feeding personalization, recommendations, and product-aware messaging.
  name: CleverTap Catalog API
  slug: catalog-api
- description: Create and update custom lists used as audience segments in campaigns and journeys.
  name: CleverTap Custom List API
  slug: custom-list-api
- description: Manage feature flags and remote configuration variables delivered to mobile apps and websites.
  name: CleverTap Remote Config API
  slug: remote-config-api
- description: Query real-time counts and trends of events, profiles, and segments.
  name: CleverTap Real-Time Counts API
  slug: counts-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://clevertap.com/
- title: ''
  type: Developer Portal
  url: https://developer.clevertap.com/
- title: ''
  type: Documentation
  url: https://developer.clevertap.com/docs
- title: ''
  type: Authentication
  url: https://developer.clevertap.com/docs/api-authentication
- title: ''
  type: Status
  url: https://status.clevertap.com/
- title: ''
  type: Pricing
  url: https://clevertap.com/pricing/
- title: ''
  type: Privacy Policy
  url: https://clevertap.com/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://clevertap.com/terms-of-service/
- title: ''
  type: JSON-LD
  url: json-ld/clevertap-context.jsonld
- title: ''
  type: Spectral
  url: rules/clevertap-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clevertap-capabilities.yml
created: '2024-11-14'
description: CleverTap is a customer engagement and retention platform that helps businesses understand user behavior, segment audiences, and deliver personalized experiences across mobile push, email, SMS, in-app, web push, and WhatsApp channels. CleverTap exposes a comprehensive REST API surface covering profiles, events, campaigns, real-time analytics, catalogs, feature flags, and more, authenticated via account ID and passcode headers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Clevertap Context
  property_count: 6
  slug: clevertap-context
layout: provider
modified: '2026-04-26'
name: CleverTap
rules:
- name: CleverTap API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: clevertap-rules
skills: []
slug: clevertap
solutions: []
source_filename: apis.yml
source_yaml: "aid: clevertap\nname: CleverTap\nurl: https://raw.githubusercontent.com/api-evangelist/clevertap/refs/heads/main/apis.yml\ncreated: '2024-11-14'\nmodified: '2026-04-26'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: company\ntags:\n  - Audiences\n  - Customer Engagement\n  - Customer Retention\n  - Marketing Automation\n  - Mobile Engagement\n  - Push Notifications\n  - User Behavior\ndescription: >-\n  CleverTap is a customer engagement and retention platform that helps\n  businesses understand user behavior, segment audiences, and deliver\n  personalized experiences across mobile push, email, SMS, in-app, web push,\n  and WhatsApp channels. CleverTap exposes a comprehensive REST API surface\n  covering profiles, events, campaigns, real-time analytics, catalogs,\n  feature flags, and more, authenticated via account ID and passcode\n  headers.\napis:\n\
  \  - aid: clevertap:profile-api\n    name: CleverTap Profile API\n    tags:\n      - Profiles\n      - User Data\n    humanURL: https://developer.clevertap.com/docs/profile-api\n    properties:\n      - url: https://developer.clevertap.com/docs/profile-api\n        type: Documentation\n    description: >-\n      Upload, retrieve, update, and delete user profiles in CleverTap with\n      identity, demographic, and custom property data.\n  - aid: clevertap:event-api\n    name: CleverTap Event API\n    tags:\n      - Events\n      - Tracking\n    humanURL: https://developer.clevertap.com/docs/event-api\n    properties:\n      - url: https://developer.clevertap.com/docs/event-api\n        type: Documentation\n    description: >-\n      Record user events with arbitrary properties for behavioral\n      segmentation, funnels, and triggered messaging.\n  - aid: clevertap:campaign-api\n    name: CleverTap Campaign API\n    tags:\n      - Campaigns\n      - Messaging\n    humanURL: https://developer.clevertap.com/docs/create-a-campaign-api\n\
  \    properties:\n      - url: https://developer.clevertap.com/docs/create-a-campaign-api\n        type: Documentation\n    description: >-\n      Programmatically create and manage push, email, SMS, web, and in-app\n      campaigns and retrieve message status reports.\n  - aid: clevertap:bulletins-api\n    name: CleverTap Bulletins API\n    tags:\n      - Bulletins\n      - Triggers\n    humanURL: https://developer.clevertap.com/docs/bulletins-api\n    properties:\n      - url: https://developer.clevertap.com/docs/bulletins-api\n        type: Documentation\n    description: >-\n      Raise a Bulletin in CleverTap when a business event is triggered, used\n      to drive real-time campaign delivery from external systems.\n  - aid: clevertap:catalog-api\n    name: CleverTap Catalog API\n    tags:\n      - Catalog\n      - Product Data\n    humanURL: https://developer.clevertap.com/docs/catalog-api\n    properties:\n      - url: https://developer.clevertap.com/docs/catalog-api\n        type:\
  \ Documentation\n    description: >-\n      Manage product catalog data feeding personalization, recommendations,\n      and product-aware messaging.\n  - aid: clevertap:custom-list-api\n    name: CleverTap Custom List API\n    tags:\n      - Audiences\n      - Lists\n    humanURL: https://developer.clevertap.com/docs/custom-list-api\n    properties:\n      - url: https://developer.clevertap.com/docs/custom-list-api\n        type: Documentation\n    description: >-\n      Create and update custom lists used as audience segments in\n      campaigns and journeys.\n  - aid: clevertap:remote-config-api\n    name: CleverTap Remote Config API\n    tags:\n      - Feature Flags\n      - Remote Config\n    humanURL: https://developer.clevertap.com/docs/remote-config-api\n    properties:\n      - url: https://developer.clevertap.com/docs/remote-config-api\n        type: Documentation\n    description: >-\n      Manage feature flags and remote configuration variables delivered\n      to mobile apps\
  \ and websites.\n  - aid: clevertap:counts-api\n    name: CleverTap Real-Time Counts API\n    tags:\n      - Analytics\n      - Counts\n    humanURL: https://developer.clevertap.com/docs/real-time-counts-api\n    properties:\n      - url: https://developer.clevertap.com/docs/real-time-counts-api\n        type: Documentation\n    description: >-\n      Query real-time counts and trends of events, profiles, and segments.\ncommon:\n  - type: Website\n    url: https://clevertap.com/\n  - type: Developer Portal\n    url: https://developer.clevertap.com/\n  - type: Documentation\n    url: https://developer.clevertap.com/docs\n  - type: Authentication\n    url: https://developer.clevertap.com/docs/api-authentication\n  - type: Status\n    url: https://status.clevertap.com/\n  - type: Pricing\n    url: https://clevertap.com/pricing/\n  - type: Privacy Policy\n    url: https://clevertap.com/privacy-policy/\n  - type: Terms of Service\n    url: https://clevertap.com/terms-of-service/\n  - type:\
  \ JSON-LD\n    url: json-ld/clevertap-context.jsonld\n  - type: Spectral\n    url: rules/clevertap-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clevertap-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clevertap/refs/heads/main/apis.yml
tags:
- Audiences
- Customer Engagement
- Customer Retention
- Marketing Automation
- Mobile Engagement
- Push Notifications
- User Behavior
url: https://raw.githubusercontent.com/api-evangelist/clevertap/refs/heads/main/apis.yml
use_cases: []
---
