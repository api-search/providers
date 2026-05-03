---
api_count: 4
api_specs:
- filename: tiktok-display-openapi.yml
  format: yaml
  label: TikTok Display API
  slug: tiktok-display-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-display-openapi.yml
- filename: tiktok-content-posting-openapi.yml
  format: yaml
  label: TikTok Content Posting API
  slug: tiktok-content-posting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-content-posting-openapi.yml
- filename: tiktok-research-openapi.yml
  format: yaml
  label: TikTok Research API
  slug: tiktok-research-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-research-openapi.yml
- filename: tiktok-login-kit-openapi.yml
  format: yaml
  label: TikTok Login Kit
  slug: tiktok-login-kit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-login-kit-openapi.yml
apis:
- description: Enables developers to access TikTok user profile information and video metadata. Supports retrieving user info, listing recent videos, and querying videos by ID.
  name: TikTok Display API
  slug: tiktok-display-api
- description: Allows third-party platforms to publish videos directly to a user's TikTok account. Supports direct post and upload-then-publish flows including initiating uploads, uploading video chunks, and checkin
  name: TikTok Content Posting API
  slug: tiktok-content-posting-api
- description: Provides academic and institutional researchers with access to TikTok public data including video queries, user information, comments, followers, and liked videos.
  name: TikTok Research API
  slug: tiktok-research-api
- description: Allows users to securely log in to third-party apps and websites using their TikTok credentials via OAuth 2.0. Supports authorization code flow and token management.
  name: TikTok Login Kit
  slug: tiktok-login-kit
capabilities:
- description: 'Unified workflow capability for creating and publishing content on TikTok. Combines the Display API and Content Posting API to support the full content lifecycle: discovering user profile settings, in'
  name: TikTok Content Creation
  slug: content-creation
- description: Workflow capability for academic and institutional research on TikTok public data. Uses the Research API to query videos, analyze user profiles, examine comment threads, and map social networks. Desig
  name: TikTok Social Research
  slug: social-research
common:
- title: ''
  type: Website
  url: https://www.tiktok.com/
- title: ''
  type: Portal
  url: https://developers.tiktok.com/
- title: ''
  type: Documentation
  url: https://developers.tiktok.com/doc/overview
- title: ''
  type: Getting Started
  url: https://developers.tiktok.com/doc/overview
- title: ''
  type: Authentication
  url: https://developers.tiktok.com/doc/login-kit-manage-user-access-tokens
- title: ''
  type: GitHub Organization
  url: https://github.com/tiktok
- title: ''
  type: SDK
  url: https://github.com/tiktok/tiktok-opensdk-ios
- title: ''
  type: SDK
  url: https://github.com/tiktok/tiktok-opensdk-android
- title: ''
  type: SDK
  url: https://github.com/tiktok/tiktok-business-api-sdk
- title: ''
  type: Change Log
  url: https://developers.tiktok.com/doc/changelog
- title: ''
  type: Blog
  url: https://developers.tiktok.com/blog
- title: ''
  type: Forum
  url: https://developers.tiktok.com/community
- title: ''
  type: Status
  url: https://status.tiktok.com/
- title: ''
  type: Terms of Service
  url: https://developers.tiktok.com/doc/tiktok-api-terms-of-service
- title: ''
  type: Privacy Policy
  url: https://developers.tiktok.com/doc/tiktok-api-data-privacy
- title: ''
  type: Use Cases
  url: https://developers.tiktok.com/
- title: ''
  type: Sign Up
  url: https://developers.tiktok.com/
- title: ''
  type: Login
  url: https://developers.tiktok.com/login
created: '2025-07-29'
description: TikTok for Developers provides a suite of REST APIs enabling third-party platforms to integrate with TikTok's social video ecosystem. Products include Login Kit, Display API, Content Posting API, Research API, and the TikTok API for Business, supporting use cases from user authentication and video publishing to advertising campaign management and academic research.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 27
  name: Tiktok For Developers Context
  property_count: 0
  slug: tiktok-for-developers-context
layout: provider
modified: '2026-05-03'
name: TikTok for Developers
rules:
- name: TikTok for Developers API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: tiktok-for-developers-rules
skills: []
slug: tiktok-for-developers
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tiktok-for-developers\nname: TikTok for Developers\ndescription: >-\n  TikTok for Developers provides a suite of REST APIs enabling third-party\n  platforms to integrate with TikTok's social video ecosystem. Products include\n  Login Kit, Display API, Content Posting API, Research API, and the TikTok API\n  for Business, supporting use cases from user authentication and video\n  publishing to advertising campaign management and academic research.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Advertising\n  - Analytics\n  - Authentication\n  - Content\n  - Social Media\n  - Video\ncreated: '2025-07-29'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tiktok-for-developers:tiktok-display-api\n    name: TikTok Display API\n    description: >-\n \
  \     Enables developers to access TikTok user profile information and video\n      metadata. Supports retrieving user info, listing recent videos, and\n      querying videos by ID.\n    humanURL: https://developers.tiktok.com/doc/display-api-overview\n    baseURL: https://open.tiktokapis.com\n    tags:\n      - Content\n      - Social Media\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developers.tiktok.com/doc/display-api-overview\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-display-openapi.yml\n  - aid: tiktok-for-developers:tiktok-content-posting-api\n    name: TikTok Content Posting API\n    description: >-\n      Allows third-party platforms to publish videos directly to a user's TikTok\n      account. Supports direct post and upload-then-publish flows including\n      initiating uploads, uploading video chunks, and checking publish status.\n\
  \    humanURL: https://developers.tiktok.com/doc/content-posting-api-reference-direct-post\n    baseURL: https://open.tiktokapis.com\n    tags:\n      - Content\n      - Publishing\n      - Social Media\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developers.tiktok.com/doc/content-posting-api-get-started\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-content-posting-openapi.yml\n  - aid: tiktok-for-developers:tiktok-research-api\n    name: TikTok Research API\n    description: >-\n      Provides academic and institutional researchers with access to TikTok\n      public data including video queries, user information, comments,\n      followers, and liked videos.\n    humanURL: https://developers.tiktok.com/doc/research-api-get-started\n    baseURL: https://open.tiktokapis.com\n    tags:\n      - Analytics\n      - Research\n      - Social Media\n\
  \      - Video\n    properties:\n      - type: Documentation\n        url: https://developers.tiktok.com/doc/research-api-get-started\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-research-openapi.yml\n  - aid: tiktok-for-developers:tiktok-login-kit\n    name: TikTok Login Kit\n    description: >-\n      Allows users to securely log in to third-party apps and websites using\n      their TikTok credentials via OAuth 2.0. Supports authorization code flow\n      and token management.\n    humanURL: https://developers.tiktok.com/doc/login-kit-web\n    baseURL: https://open.tiktokapis.com\n    tags:\n      - Authentication\n      - OAuth\n      - Social Login\n    properties:\n      - type: Documentation\n        url: https://developers.tiktok.com/doc/login-kit-web\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-login-kit-openapi.yml\n\
  common:\n  - type: Website\n    url: https://www.tiktok.com/\n  - type: Portal\n    url: https://developers.tiktok.com/\n  - type: Documentation\n    url: https://developers.tiktok.com/doc/overview\n  - type: Getting Started\n    url: https://developers.tiktok.com/doc/overview\n  - type: Authentication\n    url: https://developers.tiktok.com/doc/login-kit-manage-user-access-tokens\n  - type: GitHub Organization\n    url: https://github.com/tiktok\n  - type: SDK\n    url: https://github.com/tiktok/tiktok-opensdk-ios\n  - type: SDK\n    url: https://github.com/tiktok/tiktok-opensdk-android\n  - type: SDK\n    url: https://github.com/tiktok/tiktok-business-api-sdk\n  - type: Change Log\n    url: https://developers.tiktok.com/doc/changelog\n  - type: Blog\n    url: https://developers.tiktok.com/blog\n  - type: Forum\n    url: https://developers.tiktok.com/community\n  - type: Status\n    url: https://status.tiktok.com/\n  - type: Terms of Service\n    url: https://developers.tiktok.com/doc/tiktok-api-terms-of-service\n\
  \  - type: Privacy Policy\n    url: https://developers.tiktok.com/doc/tiktok-api-data-privacy\n  - type: Use Cases\n    url: https://developers.tiktok.com/\n  - type: Sign Up\n    url: https://developers.tiktok.com/\n  - type: Login\n    url: https://developers.tiktok.com/login\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/apis.yml
tags:
- Advertising
- Analytics
- Authentication
- Content
- Social Media
- Video
url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/apis.yml
use_cases: []
---
