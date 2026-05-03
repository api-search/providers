---
api_count: 1
api_specs:
- filename: the-news-api-openapi.yml
  format: yaml
  label: The News API
  slug: the-news-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-news-api/refs/heads/main/openapi/the-news-api-openapi.yml
apis:
- description: Get free access to search worldwide news and top stories from over 40,000 sources in 50 countries. Access live and historical articles with filters for keyword, category, language, locale, domain, and
  name: The News API
  slug: the-news-api
capabilities:
- description: 'Comprehensive workflow for monitoring worldwide news, discovering trending stories, and researching topics. Combines headline aggregation, top story search, full archive access, and source discovery. '
  name: News Monitoring and Discovery
  slug: news-monitoring
common:
- title: ''
  type: Website
  url: https://www.thenewsapi.com/
- title: ''
  type: Documentation
  url: https://www.thenewsapi.com/documentation
- title: ''
  type: Sign Up
  url: https://www.thenewsapi.com/register
- title: ''
  type: Pricing
  url: https://www.thenewsapi.com/pricing
- title: ''
  type: SpectralRuleset
  url: rules/the-news-api-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/news-monitoring.yaml
- title: ''
  type: JSONSchema
  url: json-schema/the-news-api-article-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/the-news-api-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/the-news-api-vocabulary.yml
created: '2025-02-09'
description: The News API provides free access to search worldwide news and top stories from over 40,000 sources in 50 countries. Access live and historical news articles with advanced filtering by keyword, category, language, country, domain, and date. The API supports boolean search operators, pagination, and returns structured article data including headlines, descriptions, images, and category classifications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: The News Api Context
  property_count: 3
  slug: the-news-api-context
layout: provider
modified: '2026-05-03'
name: The News API
rules:
- name: The News API API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 2
    info: 0
    warn: 4
  slug: the-news-api-rules
skills: []
slug: the-news-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-news-api\nname: The News API\ndescription: >-\n  The News API provides free access to search worldwide news and top stories\n  from over 40,000 sources in 50 countries. Access live and historical news\n  articles with advanced filtering by keyword, category, language, country,\n  domain, and date. The API supports boolean search operators, pagination, and\n  returns structured article data including headlines, descriptions, images,\n  and category classifications.\ntype: Contract\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Articles\n  - Headlines\n  - News\n  - Media\n  - Search\n  - International\ncreated: '2025-02-09'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-news-api/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: the-news-api:the-news-api\n    name: The News API\n    description: >-\n      Get free access\
  \ to search worldwide news and top stories from over 40,000\n      sources in 50 countries. Access live and historical articles with filters\n      for keyword, category, language, locale, domain, and publication date.\n    humanURL: https://www.thenewsapi.com/\n    baseURL: https://api.thenewsapi.com/v1\n    tags:\n      - Articles\n      - Headlines\n      - News\n      - Search\n      - International\n    properties:\n      - type: Documentation\n        url: https://www.thenewsapi.com/documentation\n      - type: Sign Up\n        url: https://www.thenewsapi.com/register\n      - type: Authentication\n        url: https://www.thenewsapi.com/documentation#auth\n      - type: OpenAPI\n        url: openapi/the-news-api-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.thenewsapi.com/\n  - type: Documentation\n    url: https://www.thenewsapi.com/documentation\n  - type: Sign Up\n    url: https://www.thenewsapi.com/register\n  - type: Pricing\n    url: https://www.thenewsapi.com/pricing\n\
  \  - type: SpectralRuleset\n    url: rules/the-news-api-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/news-monitoring.yaml\n  - type: JSONSchema\n    url: json-schema/the-news-api-article-schema.json\n  - type: JSONLDContext\n    url: json-ld/the-news-api-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/the-news-api-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-news-api/refs/heads/main/apis.yml
tags:
- Articles
- Headlines
- News
- Media
- Search
- International
url: https://raw.githubusercontent.com/api-evangelist/the-news-api/refs/heads/main/apis.yml
use_cases: []
---
