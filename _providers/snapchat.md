---
api_count: 6
api_specs:
- filename: snapchat-ads-api-openapi.yml
  format: yaml
  label: Snapchat Ads API
  slug: snapchat-ads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-ads-api-openapi.yml
- filename: snapchat-conversions-api-openapi.yml
  format: yaml
  label: Snapchat Conversions API
  slug: snapchat-conversions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-conversions-api-openapi.yml
- filename: snapchat-login-kit-openapi.yml
  format: yaml
  label: Snapchat Login Kit API
  slug: snapchat-login-kit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-login-kit-openapi.yml
apis:
- description: The Snapchat Ads API (Marketing API) allows developers to programmatically create, manage, and optimize advertising campaigns on the Snapchat platform. It provides endpoints for managing organizations
  name: Snapchat Ads API
  slug: snapchat-ads-api
- description: The Snapchat Conversions API (CAPI) is a structured, privacy-centric server-to-server interface allowing advertisers to pass web, app, and offline conversion events directly to Snap. It helps optimize
  name: Snapchat Conversions API
  slug: snapchat-conversions-api
- description: 'Snapchat Login Kit enables developers to let users sign up and log in to their apps using their Snapchat account credentials. Built on the OAuth 2.0 standard, it provides endpoints for authorization, '
  name: Snapchat Login Kit API
  slug: snapchat-login-kit
- description: Creative Kit allows developers to let users share content including Lenses, AR experiences, filters, GIFs, videos, links, and captions from a website or app directly to Snapchat's camera or preview sc
  name: Snapchat Creative Kit
  slug: snapchat-creative-kit
- description: Camera Kit enables developers to integrate Snap's AR camera technology directly into iOS, Android, and web applications, giving users access to Snap's lens library and AR experiences without leaving t
  name: Snapchat Camera Kit
  slug: snapchat-camera-kit
- description: Lens Studio is Snap's desktop application for building augmented reality lenses for Snapchat and Spectacles. Provides an API for scripting lens behaviors, integrating dynamic data, and publishing to t
  name: Lens Studio
  slug: snapchat-lens-studio
capabilities:
- description: 'Unified workflow capability for programmatic management of Snapchat advertising campaigns. Combines the Ads API and Conversions API to support the full ad lifecycle: creating and managing organization'
  name: Snapchat Ad Campaign Management
  slug: ad-campaign-management
- description: Workflow capability for integrating Snapchat user identity into third-party applications. Uses Login Kit OAuth 2.0 to authenticate users via their Snapchat credentials, retrieve user profile data incl
  name: Snapchat User Authentication
  slug: user-authentication
common:
- title: ''
  type: Website
  url: https://snap.com
- title: ''
  type: DeveloperPortal
  url: https://developers.snap.com
- title: ''
  type: Documentation
  url: https://developers.snap.com/api/marketing-api/Ads-API/introduction
- title: ''
  type: GitHubOrganization
  url: https://github.com/Snapchat
- title: ''
  type: TermsOfService
  url: https://snap.com/en-US/terms
- title: ''
  type: PrivacyPolicy
  url: https://snap.com/en-US/privacy/privacy-policy
- title: ''
  type: Blog
  url: https://eng.snap.com
- title: ''
  type: Support
  url: https://businesshelp.snapchat.com
- title: ''
  type: Login
  url: https://kit.snapchat.com/manage/
- title: ''
  type: Pricing
  url: https://ads.snapchat.com
- title: ''
  type: SignUp
  url: https://kit.snapchat.com/manage/
created: '2026-05-02'
description: Snap Inc. operates Snapchat, a visual messaging app and camera platform with developer tools including the Marketing API for programmatic advertising, Conversions API for server-side conversion tracking, Login Kit for OAuth-based user authentication, Creative Kit for content sharing to Snapchat, Camera Kit for embedding Snap AR technology into third-party apps, and Lens Studio for building augmented reality experiences.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Snapchat Context
  property_count: 10
  slug: snapchat-context
layout: provider
modified: '2026-05-02'
name: Snapchat
rules:
- name: Snapchat API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 4
    warn: 5
  slug: snapchat-rules
skills: []
slug: snapchat
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: snapchat\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/apis.yml\nname: Snapchat\ndescription: >-\n  Snap Inc. operates Snapchat, a visual messaging app and camera platform\n  with developer tools including the Marketing API for programmatic advertising,\n  Conversions API for server-side conversion tracking, Login Kit for OAuth-based\n  user authentication, Creative Kit for content sharing to Snapchat, Camera Kit\n  for embedding Snap AR technology into third-party apps, and Lens Studio for\n  building augmented reality experiences.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Advertising\n  - AR\n  - Augmented Reality\n  - Marketing\n  - Messaging\n  - Social Media\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: snapchat:snapchat-ads-api\n    name: Snapchat Ads API\n    description: >-\n      The Snapchat Ads API (Marketing\
  \ API) allows developers to programmatically\n      create, manage, and optimize advertising campaigns on the Snapchat platform.\n      It provides endpoints for managing organizations, ad accounts, campaigns,\n      ad squads, ads, creatives, media, funding sources, audience segments, and\n      measurement reporting. The API supports the full advertising lifecycle from\n      campaign setup through reporting and optimization.\n    humanURL: https://developers.snap.com/api/marketing-api/Ads-API/introduction\n    tags:\n      - Advertising\n      - Campaigns\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://developers.snap.com/api/marketing-api/Ads-API/introduction\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-ads-api-openapi.yml\n  - aid: snapchat:snapchat-conversions-api\n    name: Snapchat Conversions API\n    description: >-\n      The Snapchat Conversions API (CAPI)\
  \ is a structured, privacy-centric\n      server-to-server interface allowing advertisers to pass web, app, and\n      offline conversion events directly to Snap. It helps optimize ad campaigns,\n      improve targeting, and measure conversions while supporting first-party\n      custom audience population in real-time. Current version is v3.\n    humanURL: https://developers.snap.com/api/marketing-api/Conversions-API/Introduction\n    tags:\n      - Advertising\n      - Analytics\n      - Conversions\n      - Privacy\n    properties:\n      - type: Documentation\n        url: https://developers.snap.com/api/marketing-api/Conversions-API/Introduction\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-conversions-api-openapi.yml\n  - aid: snapchat:snapchat-login-kit\n    name: Snapchat Login Kit API\n    description: >-\n      Snapchat Login Kit enables developers to let users sign up and log in to\n      their\
  \ apps using their Snapchat account credentials. Built on the OAuth 2.0\n      standard, it provides endpoints for authorization, token exchange, token\n      refresh, and retrieving user profile information including display name and\n      Bitmoji avatar. Available for iOS, Android, and Web platforms.\n    humanURL: https://developers.snap.com/snap-kit/login-kit/overview\n    tags:\n      - Authentication\n      - Identity\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://developers.snap.com/snap-kit/login-kit/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-login-kit-openapi.yml\n  - aid: snapchat:snapchat-creative-kit\n    name: Snapchat Creative Kit\n    description: >-\n      Creative Kit allows developers to let users share content including\n      Lenses, AR experiences, filters, GIFs, videos, links, and captions from\n      a website or app directly to Snapchat's\
  \ camera or preview screen.\n      Supports Dynamic Lenses, Stickers, and Spotlight Posting. Available as\n      a code-only integration (SDK deprecated October 2024).\n    humanURL: https://developers.snap.com/snap-kit/creative-kit/overview\n    tags:\n      - AR\n      - Content Sharing\n      - Integration\n      - Social Media\n    properties:\n      - type: Documentation\n        url: https://developers.snap.com/snap-kit/creative-kit/overview\n      - type: GitHubRepository\n        url: https://github.com/Snapchat/creative-kit\n  - aid: snapchat:snapchat-camera-kit\n    name: Snapchat Camera Kit\n    description: >-\n      Camera Kit enables developers to integrate Snap's AR camera technology\n      directly into iOS, Android, and web applications, giving users access\n      to Snap's lens library and AR experiences without leaving the host app.\n    humanURL: https://developers.snap.com/camera-kit/home\n    tags:\n      - AR\n      - Augmented Reality\n      - Camera\n      - SDK\n\
  \    properties:\n      - type: Documentation\n        url: https://developers.snap.com/camera-kit/home\n  - aid: snapchat:snapchat-lens-studio\n    name: Lens Studio\n    description: >-\n      Lens Studio is Snap's desktop application for building augmented reality\n      lenses for Snapchat and Spectacles. Provides an API for scripting lens\n      behaviors, integrating dynamic data, and publishing to the Snap Lens Network.\n    humanURL: https://developers.snap.com/lens-studio/home\n    tags:\n      - AR\n      - Augmented Reality\n      - Creative Tools\n      - Lens\n    properties:\n      - type: Documentation\n        url: https://developers.snap.com/lens-studio/home\ncommon:\n  - type: Website\n    url: https://snap.com\n  - type: DeveloperPortal\n    url: https://developers.snap.com\n  - type: Documentation\n    url: https://developers.snap.com/api/marketing-api/Ads-API/introduction\n  - type: GitHubOrganization\n    url: https://github.com/Snapchat\n  - type: TermsOfService\n\
  \    url: https://snap.com/en-US/terms\n  - type: PrivacyPolicy\n    url: https://snap.com/en-US/privacy/privacy-policy\n  - type: Blog\n    url: https://eng.snap.com\n  - type: Support\n    url: https://businesshelp.snapchat.com\n  - type: Login\n    url: https://kit.snapchat.com/manage/\n  - type: Pricing\n    url: https://ads.snapchat.com\n  - type: SignUp\n    url: https://kit.snapchat.com/manage/\nsegments:\n  - Social Media\n  - Advertising\n  - AR/VR\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/apis.yml
tags:
- Advertising
- AR
- Augmented Reality
- Marketing
- Messaging
- Social Media
url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/apis.yml
use_cases: []
---
