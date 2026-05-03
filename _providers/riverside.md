---
api_count: 1
api_specs:
- filename: riverside-business-openapi.yml
  format: yaml
  label: Riverside Business API
  slug: riverside-business-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/openapi/riverside-business-openapi.yml
apis:
- description: The Riverside Business API provides access to recording management, production workflows, studio and project organization, file downloads, transcription retrieval, export management, and webinar regis
  name: Riverside Business API
  slug: riverside-business-api
capabilities:
- description: Unified workflow capability for enterprise podcast and video production using the Riverside Business API. Combines recording management, transcription retrieval, export handling, and webinar registrat
  name: Riverside Podcast Production
  slug: podcast-production
common:
- title: ''
  type: Website
  url: https://riverside.fm
- title: ''
  type: Documentation
  url: https://docs.riverside.fm/
- title: ''
  type: Support
  url: https://support.riverside.fm
- title: ''
  type: Pricing
  url: https://riverside.fm/pricing
- title: ''
  type: Blog
  url: https://riverside.fm/blog
- title: ''
  type: PrivacyPolicy
  url: https://riverside.fm/privacy-policy
- title: ''
  type: TermsOfService
  url: https://riverside.fm/terms-of-service
- title: ''
  type: SignUp
  url: https://riverside.fm/signup
- title: ''
  type: Login
  url: https://riverside.fm/login
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/json-ld/riverside-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/vocabulary/riverside-vocabulary.yml
created: '2026-03-16'
description: Riverside is a professional podcast and video recording platform that enables remote studio-quality recording, AI-powered editing, and publishing. The Riverside Business API provides programmatic access to recordings, productions, studios, projects, exports, transcriptions, and webinar management for enterprise podcast production workflows. API access is available on Business plan only.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Riverside Context
  property_count: 0
  slug: riverside-context
layout: provider
modified: '2026-05-02'
name: Riverside
rules:
- name: Riverside API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 4
    warn: 4
  slug: riverside-business-rules
skills: []
slug: riverside
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: riverside\nname: Riverside\ndescription: >-\n  Riverside is a professional podcast and video recording platform that\n  enables remote studio-quality recording, AI-powered editing, and publishing.\n  The Riverside Business API provides programmatic access to recordings,\n  productions, studios, projects, exports, transcriptions, and webinar\n  management for enterprise podcast production workflows. API access is\n  available on Business plan only.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Podcast\n  - Video Recording\n  - Media\n  - Content Creation\n  - Audio\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: riverside:riverside-business-api\n    name: Riverside Business API\n    description: >-\n      The Riverside Business API provides access to recording management,\n\
  \      production workflows, studio and project organization, file downloads,\n      transcription retrieval, export management, and webinar registration.\n      Authentication uses API key bearer tokens available on Business plan.\n      Base URL is https://platform.riverside.fm with v2 and v3 versioned paths.\n    humanURL: https://docs.riverside.fm/\n    baseURL: https://platform.riverside.fm\n    tags:\n      - Podcast\n      - Recording\n      - Media\n      - Video\n      - Audio\n      - Transcription\n    properties:\n      - url: https://docs.riverside.fm/endpoints-reference/v3/\n        type: Documentation\n      - url: https://support.riverside.fm/hc/en-us/articles/9068592900381-Riverside-Business-API\n        type: GettingStarted\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/openapi/riverside-business-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/rules/riverside-business-rules.yml\n\
  \        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/capabilities/podcast-production.yaml\n        type: NaftikoCapabilities\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/json-schema/riverside-recording-schema.json\n        type: JSONSchema\n    contact:\n      - FN: Riverside Support\n        url: https://support.riverside.fm\n    features:\n      - Recording Management\n      - Production Organization\n      - Studio and Project Hierarchy\n      - File Downloads\n      - Transcription Access\n      - Export Management\n      - Webinar Registration\n      - AI Editing Tools\n    useCases:\n      - Enterprise podcast production\n      - Remote video recording management\n      - Automated transcription retrieval\n      - Webinar content archiving\n      - Media asset management\n    solutions:\n      - Podcast Production\n      - Video Recording\n    \
  \  - Content Creation Platform\n\ncommon:\n  - type: Website\n    url: https://riverside.fm\n  - type: Documentation\n    url: https://docs.riverside.fm/\n  - type: Support\n    url: https://support.riverside.fm\n  - type: Pricing\n    url: https://riverside.fm/pricing\n  - type: Blog\n    url: https://riverside.fm/blog\n  - type: PrivacyPolicy\n    url: https://riverside.fm/privacy-policy\n  - type: TermsOfService\n    url: https://riverside.fm/terms-of-service\n  - type: SignUp\n    url: https://riverside.fm/signup\n  - type: Login\n    url: https://riverside.fm/login\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/json-ld/riverside-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/vocabulary/riverside-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/apis.yml
tags:
- Podcast
- Video Recording
- Media
- Content Creation
- Audio
url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/apis.yml
use_cases: []
---
