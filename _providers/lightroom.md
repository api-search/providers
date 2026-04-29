---
api_count: 2
api_specs:
- filename: lightroom-services-openapi.yml
  format: yaml
  label: Lightroom Services API
  slug: lightroom-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/openapi/lightroom-services-openapi.yml
- filename: lightroom-firefly-services-openapi.yml
  format: yaml
  label: Adobe Lightroom API (Firefly Services)
  slug: lightroom-firefly-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/openapi/lightroom-firefly-services-openapi.yml
apis:
- description: Core partner API for accessing Lightroom cloud catalog data, albums, and assets. Partner applications authenticate Lightroom customers through Adobe Identity Management System using a standard OAuth 2
  name: Lightroom Services API
  slug: lightroom-services-api
- description: AI-powered image editing API available through Adobe Firefly Services. Provides auto tone, auto straighten, preset application, and programmatic editing capabilities using REST endpoints.
  name: Adobe Lightroom API (Firefly Services)
  slug: lightroom-firefly-services-api
capabilities:
- description: Unified workflow combining Lightroom cloud services for catalog, asset, and album management with Firefly Services AI-powered editing. Used by photographers and creative developers to manage and enhan
  name: Adobe Lightroom Photo Management
  slug: photo-management
common:
- title: ''
  type: Documentation
  url: https://developer.adobe.com/lightroom/lightroom-api-docs/
- title: ''
  type: Authentication
  url: https://developer.adobe.com/developer-console/docs/guides/authentication/
- title: ''
  type: Console
  url: https://developer.adobe.com/console
- title: ''
  type: SignUp
  url: https://developer.adobe.com/console
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: ChangeLog
  url: https://developer.adobe.com/lightroom/lightroom-api-docs/release-notes/
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy/policy.html
- title: ''
  type: GitHubRepository
  url: https://github.com/AdobeDocs/lightroom-public-apis
- title: ''
  type: GitHubOrganization
  url: https://github.com/AdobeDocs
- title: ''
  type: SDK
  url: https://developer.adobe.com/firefly-services/docs/lightroom/
created: '2024-01-01'
description: APIs for Adobe Lightroom cloud services, enabling developers to access and manipulate photos, albums, and metadata programmatically. The Lightroom APIs are also available as part of Adobe Firefly Services for AI-powered image editing operations such as auto tone, auto straighten, and preset application.
features: []
image: /assets/icons/lightroom.png
integrations: []
jsonld:
- class_count: 0
  name: Lightroom Albums Context
  property_count: 0
  slug: lightroom-albums-context
- class_count: 0
  name: Lightroom Assets Context
  property_count: 0
  slug: lightroom-assets-context
- class_count: 0
  name: Lightroom Catalog Context
  property_count: 0
  slug: lightroom-catalog-context
- class_count: 0
  name: Lightroom Context
  property_count: 5
  slug: lightroom-context
- class_count: 0
  name: Lightroom Firefly Services Context
  property_count: 0
  slug: lightroom-firefly-services-context
- class_count: 0
  name: Lightroom Services Context
  property_count: 0
  slug: lightroom-services-context
layout: provider
modified: '2026-04-18'
name: Adobe Lightroom
rules:
- name: Adobe Lightroom API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: lightroom-spectral-rules
skills: []
slug: lightroom
solutions: []
source_filename: apis.yml
source_yaml: "aid: lightroom\nname: Adobe Lightroom\ndescription: >-\n  APIs for Adobe Lightroom cloud services, enabling developers to access and\n  manipulate photos, albums, and metadata programmatically. The Lightroom APIs\n  are also available as part of Adobe Firefly Services for AI-powered image\n  editing operations such as auto tone, auto straighten, and preset application.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Storage\n  - Image Editing\n  - Metadata\n  - Photo Management\n  - Photography\nurl: https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: lightroom:lightroom-services-api\n    name: Lightroom Services API\n    description: >-\n      Core partner API for accessing Lightroom cloud catalog data, albums, and\n      assets. Partner applications authenticate Lightroom customers\
  \ through Adobe\n      Identity Management System using a standard OAuth 2.0 workflow.\n    humanURL: https://developer.adobe.com/lightroom/lightroom-api-docs/\n    tags:\n      - Albums\n      - Assets\n      - Catalogs\n      - Photos\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/lightroom/lightroom-api-docs/api/\n      - type: Authentication\n        url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n      - type: GettingStarted\n        url: https://developer.adobe.com/lightroom/lightroom-api-docs/getting-started/\n      - type: ChangeLog\n        url: https://developer.adobe.com/lightroom/lightroom-api-docs/release-notes/\n      - type: OpenAPI\n        url: openapi/lightroom-services-openapi.yml\n  - aid: lightroom:lightroom-firefly-services-api\n    name: Adobe Lightroom API (Firefly Services)\n    description: >-\n      AI-powered image editing API available through Adobe Firefly Services.\n      Provides auto\
  \ tone, auto straighten, preset application, and\n      programmatic editing capabilities using REST endpoints.\n    humanURL: https://developer.adobe.com/firefly-services/docs/lightroom/\n    tags:\n      - AI\n      - Auto Tone\n      - Image Editing\n      - Presets\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/firefly-services/docs/lightroom/\n      - type: GettingStarted\n        url: https://developer.adobe.com/firefly-services/docs/lightroom/getting_started/\n      - type: OpenAPI\n        url: openapi/lightroom-firefly-services-openapi.yml\ncommon:\n  - url: https://developer.adobe.com/firefly-services/docs/lightroom/\n    type: Features\n  - url: https://developer.adobe.com/lightroom/lightroom-api-docs/\n    type: UseCases\n  - url: https://developer.adobe.com/firefly-services/docs/lightroom/\n    type: Integrations\n  - url: https://developer.adobe.com/lightroom/lightroom-api-docs/\n    type: Documentation\n  - url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n\
  \    type: Authentication\n  - url: https://developer.adobe.com/console\n    type: Console\n  - url: https://developer.adobe.com/console\n    type: SignUp\n  - url: https://status.adobe.com/\n    type: StatusPage\n  - url: https://blog.developer.adobe.com/\n    type: Blog\n  - url: https://developer.adobe.com/lightroom/lightroom-api-docs/release-notes/\n    type: ChangeLog\n  - url: https://www.adobe.com/legal/terms.html\n    type: TermsOfService\n  - url: https://www.adobe.com/privacy/policy.html\n    type: PrivacyPolicy\n  - url: https://github.com/AdobeDocs/lightroom-public-apis\n    type: GitHubRepository\n  - url: https://github.com/AdobeDocs\n    type: GitHubOrganization\n  - url: https://developer.adobe.com/firefly-services/docs/lightroom/\n    type: SDK\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/apis.yml
tags:
- Cloud Storage
- Image Editing
- Metadata
- Photo Management
- Photography
url: https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/apis.yml
use_cases: []
---
