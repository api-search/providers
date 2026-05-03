---
api_count: 1
api_specs:
- filename: reuters-connect-api-openapi.yml
  format: yaml
  label: Reuters Connect API
  slug: reuters-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/openapi/reuters-connect-api-openapi.yml
apis:
- description: Professional content delivery platform providing access to news, images, video, and data from Reuters and partner content sources via REST API, powering over 100 customer applications and internal sys
  name: Reuters Connect API
  slug: reuters-connect-api
capabilities:
- description: Unified workflow capability for accessing and searching Reuters editorial content through the Reuters Connect API. Enables media publishers, news aggregators, and content platforms to discover channel
  name: Reuters Content Delivery
  slug: content-delivery
common:
- title: ''
  type: Documentation
  url: https://developers.reutersconnect.com/docs
- title: ''
  type: Authentication
  url: https://developers.reutersconnect.com/authentication
- title: ''
  type: Blog
  url: https://medium.com/tr-labs-ml-engineering-blog
- title: ''
  type: Support
  url: https://www.reuters.com/info-pages/contact-us/
- title: ''
  type: TermsOfService
  url: https://www.reuters.com/info-pages/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.thomsonreuters.com/en/privacy-statement.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/ReutersMedia
- title: ''
  type: Website
  url: https://www.reuters.com
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/openapi/reuters-connect-api-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/vocabulary/reuters-vocabulary.yml
created: '2024-01-01'
description: Global news organization providing breaking news, business, financial, and multimedia content through wire services, digital platforms, and content APIs serving media organizations worldwide. Reuters Connect Web Services provides a professional REST API for searching and retrieving editorial content including text, images, video, and graphics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 28
  name: Reuters Context
  property_count: 20
  slug: reuters-context
layout: provider
modified: '2026-05-02'
name: Reuters
rules:
- name: Reuters API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: reuters-connect-api-rules
skills: []
slug: reuters
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: reuters\nname: Reuters\ndescription: >-\n  Global news organization providing breaking news, business, financial, and\n  multimedia content through wire services, digital platforms, and content APIs\n  serving media organizations worldwide. Reuters Connect Web Services provides\n  a professional REST API for searching and retrieving editorial content including\n  text, images, video, and graphics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Business\n  - Finance\n  - Journalism\n  - Media\n  - News\n  - Wire Service\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: reuters:reuters-connect-api\n    name: Reuters Connect API\n    description: >-\n      Professional content delivery platform providing access to news, images,\n      video, and data from Reuters and partner content\
  \ sources via REST API,\n      powering over 100 customer applications and internal systems. Content\n      is organized into channels by category (TXT, PIX, VID, GFX) and items\n      can be retrieved individually or searched by keyword.\n    humanURL: https://www.reutersconnect.com\n    tags:\n      - Content Delivery\n      - Images\n      - Media\n      - News\n      - Search\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developers.reutersconnect.com/docs\n      - type: Authentication\n        url: https://developers.reutersconnect.com/authentication\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/openapi/reuters-connect-api-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/json-schema/reuters-channel-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/json-schema/reuters-item-schema.json\n\
  \      - type: JSONLD\n        url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/json-ld/reuters-context.jsonld\ncommon:\n  - type: Documentation\n    url: https://developers.reutersconnect.com/docs\n  - type: Authentication\n    url: https://developers.reutersconnect.com/authentication\n  - type: Blog\n    url: https://medium.com/tr-labs-ml-engineering-blog\n  - type: Support\n    url: https://www.reuters.com/info-pages/contact-us/\n  - type: TermsOfService\n    url: https://www.reuters.com/info-pages/terms-of-use/\n  - type: PrivacyPolicy\n    url: https://www.thomsonreuters.com/en/privacy-statement.html\n  - type: GitHubOrganization\n    url: https://github.com/ReutersMedia\n  - type: Website\n    url: https://www.reuters.com\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/openapi/reuters-connect-api-openapi.yml\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/vocabulary/reuters-vocabulary.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/apis.yml
tags:
- Business
- Finance
- Journalism
- Media
- News
- Wire Service
url: https://raw.githubusercontent.com/api-evangelist/reuters/refs/heads/main/apis.yml
use_cases: []
---
