---
api_count: 3
api_specs:
- filename: whatfix-openapi.yml
  format: yaml
  label: Whatfix API
  slug: whatfix-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/openapi/whatfix-openapi.yml
apis:
- description: The Whatfix REST API enables programmatic access to end-user management, content management, flow analytics, segmentation, and report downloads. The API is stateless, uses JSON output, and authenticat
  name: Whatfix API
  slug: whatfix-api
- description: The Whatfix Android SDK provides DAP (Digital Adoption Platform) capabilities for Android mobile applications, enabling in-app guidance, onboarding flows, and user engagement analytics on native Andro
  name: Whatfix Android SDK
  slug: whatfix-android-sdk
- description: The Whatfix iOS SDK provides DAP capabilities for native iOS applications, enabling in-app guidance, walkthroughs, and analytics on iPhone and iPad apps.
  name: Whatfix iOS SDK
  slug: whatfix-ios-sdk
capabilities:
- description: Unified digital adoption platform capability composing Whatfix's end-user management, content management, analytics, and segmentation APIs into customer-facing workflows for adoption monitoring, onboa
  name: Whatfix Digital Adoption
  slug: digital-adoption
common:
- title: ''
  type: Website
  url: https://whatfix.com
- title: ''
  type: Developer Portal
  url: https://developer.whatfix.com
- title: ''
  type: Documentation
  url: https://support.whatfix.com
- title: ''
  type: GitHub Organization
  url: https://github.com/whatfix
- title: ''
  type: Blog
  url: https://whatfix.com/blog/
- title: ''
  type: Pricing
  url: https://whatfix.com/pricing/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/openapi/whatfix-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/vocabulary/whatfix-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/json-ld/whatfix-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/rules/whatfix-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/capabilities/digital-adoption.yaml
created: '2026-03-27'
description: Whatfix is a digital adoption platform providing in-app contextual guidance, SaaS management, workflow automation, and product analytics to help organizations accelerate software adoption, improve employee onboarding, and optimize digital transformation. Its platform combines guided walkthroughs, self-help content, AI-powered authoring agents, task lists, surveys, and usage analytics for web, desktop, mobile, and VDI environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 38
  name: Whatfix Context
  property_count: 0
  slug: whatfix-context
layout: provider
modified: '2026-05-03'
name: Whatfix
rules:
- name: Whatfix API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: whatfix-rules
skills: []
slug: whatfix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: whatfix\nname: Whatfix\ndescription: >-\n  Whatfix is a digital adoption platform providing in-app contextual guidance,\n  SaaS management, workflow automation, and product analytics to help organizations\n  accelerate software adoption, improve employee onboarding, and optimize digital\n  transformation. Its platform combines guided walkthroughs, self-help content,\n  AI-powered authoring agents, task lists, surveys, and usage analytics for web,\n  desktop, mobile, and VDI environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Digital Adoption\n  - SaaS Management\n  - User Onboarding\n  - In-App Guidance\n  - Analytics\n  - Change Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: whatfix:whatfix-api\n    name: Whatfix API\n    description: >-\n      The Whatfix\
  \ REST API enables programmatic access to end-user management,\n      content management, flow analytics, segmentation, and report downloads.\n      The API is stateless, uses JSON output, and authenticates via the\n      x-whatfix-integration-key header with your account API token.\n    humanURL: https://developer.whatfix.com\n    baseURL: https://whatfix.com/api/v1\n    tags:\n      - Digital Adoption\n      - Analytics\n      - Content Management\n      - User Segmentation\n    properties:\n      - type: Documentation\n        url: https://developer.whatfix.com\n      - type: Developer Guide\n        url: https://support.whatfix.com/docs/developer-guide\n      - type: Authentication\n        url: https://support.whatfix.com/docs/generatingtheapitoken\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/openapi/whatfix-openapi.yml\n      - type: Analytics API\n        url: https://support.whatfix.com/docs/downloading-report-analytics-data-using-api\n\
  \n  - aid: whatfix:whatfix-android-sdk\n    name: Whatfix Android SDK\n    description: >-\n      The Whatfix Android SDK provides DAP (Digital Adoption Platform) capabilities\n      for Android mobile applications, enabling in-app guidance, onboarding flows,\n      and user engagement analytics on native Android apps.\n    humanURL: https://github.com/whatfix/whatfix-android\n    tags:\n      - Android\n      - Mobile SDK\n      - DAP\n    properties:\n      - type: Source Code\n        url: https://github.com/whatfix/whatfix-android\n      - type: SDK\n        url: https://github.com/whatfix/whatfix-android\n\n  - aid: whatfix:whatfix-ios-sdk\n    name: Whatfix iOS SDK\n    description: >-\n      The Whatfix iOS SDK provides DAP capabilities for native iOS applications,\n      enabling in-app guidance, walkthroughs, and analytics on iPhone and iPad apps.\n    humanURL: https://github.com/whatfix/Whatfix-iOS\n    tags:\n      - iOS\n      - Mobile SDK\n      - DAP\n    properties:\n \
  \     - type: Source Code\n        url: https://github.com/whatfix/Whatfix-iOS\n      - type: SDK\n        url: https://github.com/whatfix/Whatfix-iOS\n\ncommon:\n  - type: Website\n    url: https://whatfix.com\n  - type: Developer Portal\n    url: https://developer.whatfix.com\n  - type: Documentation\n    url: https://support.whatfix.com\n  - type: GitHub Organization\n    url: https://github.com/whatfix\n  - type: Blog\n    url: https://whatfix.com/blog/\n  - type: Pricing\n    url: https://whatfix.com/pricing/\n  - type: Integrations\n    url: https://whatfix.com/integrations/\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/openapi/whatfix-openapi.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/vocabulary/whatfix-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/json-ld/whatfix-context.jsonld\n\
  \  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/rules/whatfix-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/capabilities/digital-adoption.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/apis.yml
tags:
- Digital Adoption
- SaaS Management
- User Onboarding
- In-App Guidance
- Analytics
- Change Management
url: https://raw.githubusercontent.com/api-evangelist/whatfix/refs/heads/main/apis.yml
use_cases: []
---
