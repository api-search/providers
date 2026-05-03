---
api_count: 3
api_specs:
- filename: swetrix-events-api-openapi.yml
  format: yaml
  label: Swetrix Events API
  slug: swetrix-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-events-api-openapi.yml
- filename: swetrix-statistics-api-openapi.yml
  format: yaml
  label: Swetrix Statistics API
  slug: swetrix-statistics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-statistics-api-openapi.yml
- filename: swetrix-admin-api-openapi.yml
  format: yaml
  label: Swetrix Admin API
  slug: swetrix-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-admin-api-openapi.yml
apis:
- description: The Swetrix Events API provides endpoints for recording pageview events, custom events, heartbeat events, error events, and revenue transactions. Used for sending analytics data from client or server-
  name: Swetrix Events API
  slug: swetrix-events-api
- description: The Swetrix Statistics API enables querying aggregated analytics data including traffic logs, performance metrics, session details, funnel analysis, user flows, error overviews, and feature flag stati
  name: Swetrix Statistics API
  slug: swetrix-statistics-api
- description: The Swetrix Admin API manages projects, funnels, annotations, project views (segments), and organisations. Supports full CRUD operations for analytics project management. Authenticated with an X-Api-K
  name: Swetrix Admin API
  slug: swetrix-admin-api
capabilities:
- description: Unified web analytics capability combining Swetrix Events, Statistics, and Admin APIs. Enables product teams and developers to track user behavior, analyze traffic patterns, manage analytics projects,
  name: Swetrix Web Analytics
  slug: web-analytics
common:
- title: ''
  type: Website
  url: https://swetrix.com
- title: ''
  type: Documentation
  url: https://docs.swetrix.com
- title: ''
  type: Blog
  url: https://swetrix.com/blog
- title: ''
  type: Pricing
  url: https://swetrix.com/pricing
- title: ''
  type: GitHub
  url: https://github.com/Swetrix/swetrix
- title: ''
  type: GitHubOrganization
  url: https://github.com/Swetrix
- title: ''
  type: Login
  url: https://swetrix.com/login
- title: ''
  type: Signup
  url: https://swetrix.com/signup
- title: ''
  type: Support
  url: https://swetrix.com/contact
- title: ''
  type: OpenSource
  url: https://github.com/Swetrix/swetrix-api
- title: ''
  type: SDK
  url: https://github.com/Swetrix/swetrix-js
- title: ''
  type: SDK
  url: https://github.com/Swetrix/swetrix-nextjs
- title: ''
  type: SDK
  url: https://github.com/Swetrix/swetrix-browser
- title: ''
  type: SDK
  url: https://github.com/Swetrix/django-plugin
- title: ''
  type: Status
  url: https://swetrix.com/status
- title: ''
  type: TermsOfService
  url: https://swetrix.com/privacy
- title: ''
  type: PrivacyPolicy
  url: https://swetrix.com/privacy
created: '2026-03-26'
description: Swetrix is an open source, privacy-focused web analytics platform that provides cookieless tracking, real-time dashboards, and GDPR-compliant analytics without collecting personal data. It offers a fully-featured REST API for tracking events, querying statistics, managing projects, and integrating analytics into custom applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Swetrix Context
  property_count: 6
  slug: swetrix-context
layout: provider
modified: '2026-05-03'
name: Swetrix
rules:
- name: Swetrix API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 1
    info: 0
    warn: 6
  slug: swetrix-rules
skills: []
slug: swetrix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: swetrix\nname: Swetrix\ndescription: >-\n  Swetrix is an open source, privacy-focused web analytics platform that\n  provides cookieless tracking, real-time dashboards, and GDPR-compliant\n  analytics without collecting personal data. It offers a fully-featured\n  REST API for tracking events, querying statistics, managing projects, and\n  integrating analytics into custom applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Cookieless Tracking\n  - GDPR Compliant\n  - Open Source\n  - Privacy\n  - Real-Time Analytics\n  - Web Analytics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: swetrix:swetrix-events-api\n    name: Swetrix Events API\n    description: >-\n      The Swetrix Events API provides endpoints for recording pageview events,\n      custom\
  \ events, heartbeat events, error events, and revenue transactions.\n      Used for sending analytics data from client or server-side applications\n      to Swetrix analytics projects.\n    humanURL: https://swetrix.com/docs/events-api\n    baseURL: https://api.swetrix.com\n    properties:\n      - type: Documentation\n        url: https://swetrix.com/docs/events-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-events-api-openapi.yml\n    tags:\n      - Analytics\n      - Cookieless Tracking\n      - Custom Events\n      - Error Tracking\n      - Events\n      - Pageviews\n      - Revenue Tracking\n\n  - aid: swetrix:swetrix-statistics-api\n    name: Swetrix Statistics API\n    description: >-\n      The Swetrix Statistics API enables querying aggregated analytics data\n      including traffic logs, performance metrics, session details, funnel\n      analysis, user flows, error overviews, and\
  \ feature flag statistics.\n      Authenticated with an X-Api-Key header.\n    humanURL: https://swetrix.com/docs/statistics-api\n    baseURL: https://api.swetrix.com\n    properties:\n      - type: Documentation\n        url: https://swetrix.com/docs/statistics-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-statistics-api-openapi.yml\n    tags:\n      - Analytics\n      - Funnels\n      - Performance\n      - Statistics\n      - Traffic\n\n  - aid: swetrix:swetrix-admin-api\n    name: Swetrix Admin API\n    description: >-\n      The Swetrix Admin API manages projects, funnels, annotations, project\n      views (segments), and organisations. Supports full CRUD operations for\n      analytics project management. Authenticated with an X-Api-Key header.\n    humanURL: https://swetrix.com/docs/admin-api\n    baseURL: https://api.swetrix.com\n    properties:\n      - type: Documentation\n     \
  \   url: https://swetrix.com/docs/admin-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/openapi/swetrix-admin-api-openapi.yml\n    tags:\n      - Administration\n      - Analytics\n      - Organisations\n      - Project Management\n      - Projects\n\ncommon:\n  - type: Website\n    url: https://swetrix.com\n  - type: Documentation\n    url: https://docs.swetrix.com\n  - type: Blog\n    url: https://swetrix.com/blog\n  - type: Pricing\n    url: https://swetrix.com/pricing\n  - type: GitHub\n    url: https://github.com/Swetrix/swetrix\n  - type: GitHubOrganization\n    url: https://github.com/Swetrix\n  - type: Login\n    url: https://swetrix.com/login\n  - type: Signup\n    url: https://swetrix.com/signup\n  - type: Support\n    url: https://swetrix.com/contact\n  - type: OpenSource\n    url: https://github.com/Swetrix/swetrix-api\n  - type: SDK\n    url: https://github.com/Swetrix/swetrix-js\n  - type: SDK\n\
  \    url: https://github.com/Swetrix/swetrix-nextjs\n  - type: SDK\n    url: https://github.com/Swetrix/swetrix-browser\n  - type: SDK\n    url: https://github.com/Swetrix/django-plugin\n  - type: Status\n    url: https://swetrix.com/status\n  - type: TermsOfService\n    url: https://swetrix.com/privacy\n  - type: PrivacyPolicy\n    url: https://swetrix.com/privacy\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/apis.yml
tags:
- Analytics
- Cookieless Tracking
- GDPR Compliant
- Open Source
- Privacy
- Real-Time Analytics
- Web Analytics
url: https://raw.githubusercontent.com/api-evangelist/swetrix/refs/heads/main/apis.yml
use_cases: []
---
