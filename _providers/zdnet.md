---
api_count: 1
api_specs:
- filename: zdnet-rss.yml
  format: yaml
  label: ZDNet RSS Feed
  slug: rss
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/openapi/zdnet-rss.yml
apis:
- description: RSS feeds providing the latest news, analysis, and reviews from ZDNet covering enterprise IT, security, cloud, hardware, software, artificial intelligence, and business technology for IT professionals
  name: ZDNet RSS Feed
  slug: rss
capabilities:
- description: Unified workflow capability composing ZDNet APIs.
  name: ZDNet Workflow
  slug: zdnet-workflow
common:
- title: ''
  type: Website
  url: https://www.zdnet.com/
- title: ''
  type: About
  url: https://www.zdnet.com/about-zdnet/
- title: ''
  type: RSS
  url: https://www.zdnet.com/news/rss.xml
- title: ''
  type: RSS
  url: https://www.zdnet.com/topic/security/rss.xml
- title: ''
  type: RSS
  url: https://www.zdnet.com/topic/cloud/rss.xml
- title: ''
  type: RSS
  url: https://www.zdnet.com/topic/artificial-intelligence/rss.xml
- title: ''
  type: RSS
  url: https://www.zdnet.com/topic/developer/rss.xml
- title: ''
  type: Newsletter
  url: https://www.zdnet.com/newsletters/
- title: ''
  type: Team
  url: https://www.zdnet.com/meet-the-team/
- title: ''
  type: Advertising
  url: https://www.zdnet.com/advertise/
- title: ''
  type: EditorialGuidelines
  url: https://www.zdnet.com/article/zdnet-editorial-guidelines/
- title: ''
  type: PrivacyPolicy
  url: https://www.zdnet.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.zdnet.com/terms-of-use/
- title: ''
  type: X
  url: https://x.com/ZDNet
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/zdnet-com
- title: ''
  type: Facebook
  url: https://www.facebook.com/ZDNet
- title: ''
  type: Podcast
  url: https://podcasts.apple.com/us/podcast/zdnet-video/id271364310
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/rules/zdnet-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/vocabulary/zdnet-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/capabilities/zdnet-workflow.yaml
created: '2024-01-01'
description: ZDNet is a business technology news website owned by Ziff Davis, covering enterprise IT, cybersecurity, cloud computing, hardware, software, and innovation for IT professionals and tech-savvy business leaders. ZDNet provides news, analysis, product reviews, and how-to guides. No public developer API is available; content is accessible via RSS feeds.
features:
- description: Latest enterprise IT news from ZDNet.
  name: RSS News Feed
- description: Filtered RSS feeds for security, cloud, AI, developer, and innovation topics.
  name: Topic-Specific Feeds
- description: Standard XML RSS 2.0 format for syndication.
  name: RSS 2.0 Format
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Zdnet Rss Context
  property_count: 8
  slug: zdnet-rss-context
layout: provider
modified: '2026-05-03'
name: ZDNet
rules:
- name: ZDNet API Rules
  rule_count: 18
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 13
  slug: zdnet-rules
skills: []
slug: zdnet
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zdnet\nurl: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/apis.yml\napis:\n  - aid: zdnet:rss\n    name: ZDNet RSS Feed\n    description: RSS feeds providing the latest news, analysis, and reviews from ZDNet covering enterprise IT, security, cloud, hardware, software, artificial intelligence, and business technology for IT professionals.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.zdnet.com/news/rss.xml\n    baseURL: https://www.zdnet.com\n    tags:\n      - Artificial Intelligence\n      - Cloud\n      - Enterprise IT\n      - News Feed\n      - RSS\n      - Security\n      - Technology News\n    properties:\n      - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/openapi/zdnet-rss.yml\n        type: OpenAPI\n      - url: https://www.zdnet.com/news/rss.xml\n        type: RSS\n        name: ZDNet News RSS Feed\n      - url: https://www.zdnet.com/topic/security/rss.xml\n\
  \        type: RSS\n        name: ZDNet Security RSS Feed\n      - url: https://www.zdnet.com/topic/cloud/rss.xml\n        type: RSS\n        name: ZDNet Cloud RSS Feed\n      - url: https://www.zdnet.com/topic/artificial-intelligence/rss.xml\n        type: RSS\n        name: ZDNet AI RSS Feed\n      - url: https://www.zdnet.com/topic/developer/rss.xml\n        type: RSS\n        name: ZDNet Developer RSS Feed\n      - url: https://www.zdnet.com/topic/innovation/rss.xml\n        type: RSS\n        name: ZDNet Innovation RSS Feed\n      - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-schema/\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-structure/\n        type: JSONStructure\n      - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-ld/zdnet-rss-context.jsonld\n        type: JSON-LD\n      - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/examples/\n\
  \        type: Example\nname: ZDNet\ndescription: ZDNet is a business technology news website owned by Ziff Davis, covering enterprise IT, cybersecurity, cloud computing, hardware, software, and innovation for IT professionals and tech-savvy business leaders. ZDNet provides news, analysis, product reviews, and how-to guides. No public developer API is available; content is accessible via RSS feeds.\ntags:\n  - Enterprise IT\n  - Media\n  - Technology News\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.zdnet.com/\n    name: ZDNet Website\n    type: Website\n  - url: https://www.zdnet.com/about-zdnet/\n    name: About ZDNet\n    type: About\n  - url: https://www.zdnet.com/news/rss.xml\n    name: News RSS Feed\n    type: RSS\n  - url: https://www.zdnet.com/topic/security/rss.xml\n    name: Security RSS Feed\n    type: RSS\n  - url: https://www.zdnet.com/topic/cloud/rss.xml\n    name: Cloud RSS\
  \ Feed\n    type: RSS\n  - url: https://www.zdnet.com/topic/artificial-intelligence/rss.xml\n    name: AI RSS Feed\n    type: RSS\n  - url: https://www.zdnet.com/topic/developer/rss.xml\n    name: Developer RSS Feed\n    type: RSS\n  - url: https://www.zdnet.com/newsletters/\n    name: Newsletters\n    type: Newsletter\n  - url: https://www.zdnet.com/meet-the-team/\n    name: Editorial Team\n    type: Team\n  - url: https://www.zdnet.com/advertise/\n    name: Advertise\n    type: Advertising\n  - url: https://www.zdnet.com/article/zdnet-editorial-guidelines/\n    name: Editorial Guidelines\n    type: EditorialGuidelines\n  - url: https://www.zdnet.com/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.zdnet.com/terms-of-use/\n    name: Terms of Use\n    type: TermsOfService\n  - url: https://x.com/ZDNet\n    name: X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/zdnet-com\n    name: LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/ZDNet\n\
  \    name: Facebook\n    type: Facebook\n  - url: https://podcasts.apple.com/us/podcast/zdnet-video/id271364310\n    name: ZDNet Video Podcast on Apple Podcasts\n    type: Podcast\n  - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/rules/zdnet-rules.yml\n    name: ZDNet Spectral Ruleset\n    type: SpectralRules\n  - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/vocabulary/zdnet-vocabulary.yml\n    name: ZDNet Vocabulary\n    type: Vocabulary\n  - url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/capabilities/zdnet-workflow.yaml\n    name: ZDNet Workflow Capability\n    type: NaftikoCapability\n  - data:\n      - name: RSS News Feed\n        description: Latest enterprise IT news from ZDNet.\n      - name: Topic-Specific Feeds\n        description: Filtered RSS feeds for security, cloud, AI, developer, and innovation topics.\n      - name: RSS 2.0 Format\n        description: Standard XML RSS 2.0 format\
  \ for syndication.\n    name: Features\n    type: Features\n  - data:\n      - name: News Aggregation\n        description: Aggregate ZDNet articles into a news app or dashboard.\n      - name: Topic Monitoring\n        description: Monitor specific topic feeds (security, cloud, AI) for industry tracking.\n    name: UseCases\n    type: UseCases\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/apis.yml
tags:
- Enterprise IT
- Media
- Technology News
url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/apis.yml
use_cases:
- description: Aggregate ZDNet articles into a news app or dashboard.
  name: News Aggregation
- description: Monitor specific topic feeds (security, cloud, AI) for industry tracking.
  name: Topic Monitoring
---
