---
api_count: 2
api_specs:
- filename: techcrunch-wordpress-rest-api-openapi.yml
  format: yaml
  label: TechCrunch WordPress REST API
  slug: wordpress-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/openapi/techcrunch-wordpress-rest-api-openapi.yml
apis:
- description: TechCrunch is built on WordPress and exposes the standard WordPress REST API, providing JSON endpoints for accessing posts, pages, categories, tags, authors, media, comments, and search. The API is av
  name: TechCrunch WordPress REST API
  slug: wordpress-rest-api
- description: TechCrunch provides RSS feeds covering its full range of technology news, startup coverage, and venture capital reporting. The main feed delivers all published articles, and category-specific feeds ar
  name: TechCrunch RSS Feed
  slug: rss-feed
capabilities:
- description: Unified content discovery workflow for TechCrunch. Combines article retrieval, category and tag browsing, author profiles, media access, and full-text search through the WordPress REST API. Designed f
  name: TechCrunch Content Discovery
  slug: content-discovery
common:
- title: ''
  type: Website
  url: https://techcrunch.com/
- title: ''
  type: About
  url: https://techcrunch.com/about-techcrunch/
- title: ''
  type: Newsletter
  url: https://techcrunch.com/newsletters/
- title: ''
  type: RSSFeeds
  url: https://techcrunch.com/feed/
- title: ''
  type: Advertising
  url: https://techcrunch.com/advertise/
- title: ''
  type: Contact
  url: https://techcrunch.com/contact-us/
- title: ''
  type: TermsOfService
  url: https://techcrunch.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://techcrunch.com/privacy-policy/
- title: ''
  type: X
  url: https://x.com/TechCrunch
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/techcrunch/
- title: ''
  type: Facebook
  url: https://www.facebook.com/techcrunch/
- title: ''
  type: Instagram
  url: https://www.instagram.com/techcrunch/
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/vocabulary/techcrunch-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/json-ld/techcrunch-context.jsonld
created: '2026-03-24'
description: TechCrunch (https://techcrunch.com/) is a leading technology media property dedicated to covering startups, venture capital, and innovation. Founded in 2005 and acquired by AOL in 2010 and later by Yahoo, TechCrunch delivers breaking news, in-depth analysis, and original reporting on the technology industry, emerging companies, funding rounds, and the people shaping the future of tech. The publication hosts flagship events including TechCrunch Disrupt and the Startup Battlefield competition. TechCrunch runs on WordPress and exposes the standard WordPress REST API for programmatic content access.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 57
  name: Techcrunch Context
  property_count: 0
  slug: techcrunch-context
layout: provider
modified: '2026-05-03'
name: TechCrunch
rules:
- name: TechCrunch API Rules
  rule_count: 12
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 5
  slug: techcrunch-wordpress-rules
skills: []
slug: techcrunch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: techcrunch\nname: TechCrunch\ndescription: >-\n  TechCrunch (https://techcrunch.com/) is a leading technology media property dedicated\n  to covering startups, venture capital, and innovation. Founded in 2005 and acquired\n  by AOL in 2010 and later by Yahoo, TechCrunch delivers breaking news, in-depth analysis,\n  and original reporting on the technology industry, emerging companies, funding rounds,\n  and the people shaping the future of tech. The publication hosts flagship events\n  including TechCrunch Disrupt and the Startup Battlefield competition. TechCrunch runs\n  on WordPress and exposes the standard WordPress REST API for programmatic content access.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Media\n  - News\n  - Startups\n  - Technology News\n  - Venture Capital\nurl: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\n\
  specificationVersion: '0.19'\napis:\n  - aid: techcrunch:wordpress-rest-api\n    name: TechCrunch WordPress REST API\n    description: >-\n      TechCrunch is built on WordPress and exposes the standard WordPress REST API,\n      providing JSON endpoints for accessing posts, pages, categories, tags, authors,\n      media, comments, and search. The API is available at the /wp-json/wp/v2/ base path\n      and supports filtering, pagination, searching, and sorting across all TechCrunch\n      content. TechCrunch uses a headless WordPress architecture with a React frontend,\n      making the REST API the primary data layer for content delivery. No authentication\n      is required for read operations.\n    humanURL: https://developer.wordpress.org/rest-api/\n    baseURL: https://techcrunch.com/wp-json/wp/v2\n    tags:\n      - Content\n      - JSON\n      - Media\n      - REST\n      - WordPress\n    properties:\n      - type: Documentation\n        url: https://developer.wordpress.org/rest-api/\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/openapi/techcrunch-wordpress-rest-api-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/json-schema/techcrunch-post-schema.json\n      - type: NaftikoPCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/capabilities/content-discovery.yaml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/rules/techcrunch-wordpress-rules.yml\n  - aid: techcrunch:rss-feed\n    name: TechCrunch RSS Feed\n    description: >-\n      TechCrunch provides RSS feeds covering its full range of technology news,\n      startup coverage, and venture capital reporting. The main feed delivers\n      all published articles, and category-specific feeds are available\
  \ for\n      topics including startups, venture capital, artificial intelligence,\n      security, apps, gadgets, and more. These standard RSS/Atom feeds allow\n      readers and developers to consume TechCrunch content programmatically\n      using any standard feed reader or parsing library.\n    humanURL: https://techcrunch.com/feed/\n    baseURL: https://techcrunch.com\n    tags:\n      - Feed\n      - News\n      - RSS\n      - Syndication\n    properties:\n      - type: Documentation\n        url: https://techcrunch.com/feed/\n      - type: RSSFeed\n        url: https://techcrunch.com/feed/\ncommon:\n  - url: https://techcrunch.com/\n    name: TechCrunch\n    type: Website\n  - url: https://techcrunch.com/about-techcrunch/\n    name: About TechCrunch\n    type: About\n  - url: https://techcrunch.com/newsletters/\n    name: TechCrunch Newsletters\n    type: Newsletter\n  - url: https://techcrunch.com/feed/\n    name: TechCrunch RSS Feed\n    type: RSSFeeds\n  - url: https://techcrunch.com/advertise/\n\
  \    name: Advertise with TechCrunch\n    type: Advertising\n  - url: https://techcrunch.com/contact-us/\n    name: Contact TechCrunch\n    type: Contact\n  - url: https://techcrunch.com/terms-of-service/\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://techcrunch.com/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://x.com/TechCrunch\n    name: TechCrunch on X\n    type: X\n  - url: https://www.linkedin.com/company/techcrunch/\n    name: TechCrunch on LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/techcrunch/\n    name: TechCrunch on Facebook\n    type: Facebook\n  - url: https://www.instagram.com/techcrunch/\n    name: TechCrunch on Instagram\n    type: Instagram\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/vocabulary/techcrunch-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/json-ld/techcrunch-context.jsonld\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/apis.yml
tags:
- Media
- News
- Startups
- Technology News
- Venture Capital
url: https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/apis.yml
use_cases: []
---
