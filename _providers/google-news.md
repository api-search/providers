---
api_count: 1
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google News RSS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/openapi/openapi.yml
apis:
- description: RSS feed endpoints for retrieving Google News headlines by topic, location, and search query across multiple languages and regions.
  name: Google News RSS API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://news.google.com
- title: ''
  type: Getting Started
  url: https://news.google.com
- title: ''
  type: Terms of Service
  url: https://policies.google.com/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Support
  url: https://support.google.com/news
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/json-ld/google-news.jsonld
created: '2026-03-13'
description: Google News provides RSS feeds that deliver news headlines organized by topic, location, and search query. The feeds expose structured XML data that can be consumed programmatically to retrieve top stories, topic-based headlines (World, Business, Technology, Sports, etc.), location-specific news, and keyword search results across multiple languages and regions.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google News Context
  property_count: 8
  slug: google-news
layout: provider
modified: '2026-04-28'
name: Google News RSS
rules:
- name: Google News RSS API Rules
  rule_count: 13
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 1
  slug: google-news-spectral-rules
skills: []
slug: google-news
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-news\nname: Google News RSS\ndescription: >-\n  Google News provides RSS feeds that deliver news headlines organized by topic,\n  location, and search query. The feeds expose structured XML data that can be\n  consumed programmatically to retrieve top stories, topic-based headlines\n  (World, Business, Technology, Sports, etc.), location-specific news, and\n  keyword search results across multiple languages and regions.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Aggregation\n  - Google News\n  - Headlines\n  - Media\n  - News\n  - RSS\napis:\n  - name: Google News RSS API\n    description: >-\n      RSS feed endpoints for retrieving Google News headlines by topic, location,\n      and search query across multiple languages and regions.\n\
  \    humanURL: https://news.google.com\n    baseURL: https://news.google.com/rss\n    properties:\n      - type: Documentation\n        url: https://news.google.com/rss/help\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/openapi/openapi.yml\n      - type: Getting Started\n        url: https://news.google.com\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/json-schema/google-news.json\n      - type: JSONLD\n        url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/json-ld/google-news.jsonld\ncommon:\n  - type: Portal\n    url: https://news.google.com\n  - type: Getting Started\n    url: https://news.google.com\n  - type: Terms of Service\n    url: https://policies.google.com/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Support\n    url: https://support.google.com/news\n  - type:\
  \ JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/json-ld/google-news.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/apis.yml
tags:
- Aggregation
- Google News
- Headlines
- Media
- News
- RSS
url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/apis.yml
use_cases: []
---
