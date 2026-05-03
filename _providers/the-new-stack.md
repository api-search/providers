---
api_count: 2
apis:
- description: RSS feed providing the latest articles and news from The New Stack covering cloud native, DevOps, AI, and open source technologies. Feed follows RSS 2.0 with Dublin Core and WordPress content extensio
  name: The New Stack RSS Feed
  slug: rss
- description: RSS feed for The New Stack podcast, featuring discussions with developers, engineers, and operations professionals building at-scale architectures. Hosted on Simplecast.
  name: The New Stack Podcast Feed
  slug: podcast-rss
common:
- title: ''
  type: Website
  url: https://thenewstack.io/
- title: ''
  type: About
  url: https://thenewstack.io/about-and-contact-info/
- title: ''
  type: RSS
  url: https://thenewstack.io/rss-feeds/
- title: ''
  type: RSS
  url: https://thenewstack.io/feed/
- title: ''
  type: Newsletter
  url: https://thenewstack.io/newsletter/
- title: ''
  type: Podcast
  url: https://thenewstack.io/podcasts/
- title: ''
  type: Podcast
  url: https://thenewstack.simplecast.com/
- title: ''
  type: Podcast
  url: https://open.spotify.com/show/2nj1mpDb9jxHxi9vjZvDdk
- title: ''
  type: Contribute
  url: https://thenewstack.io/contributions/
- title: ''
  type: Sponsorship
  url: https://thenewstack.io/sponsorship/
- title: ''
  type: Events
  url: https://thenewstack.io/events/
- title: ''
  type: Webinars
  url: https://thenewstack.io/webinars/
- title: ''
  type: PrivacyPolicy
  url: https://thenewstack.io/privacy-policy/
- title: ''
  type: X
  url: https://x.com/thenewstack
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/the-new-stack
- title: ''
  type: Facebook
  url: https://www.facebook.com/thenewstack/
- title: ''
  type: YouTube
  url: https://www.youtube.com/thenewstack
created: '2024-01-01'
description: The New Stack is a tech media platform covering cloud native, DevOps, AI, and open source technologies, providing news, analysis, podcasts, webinars, and ebooks for developers, software engineers, and operations professionals. Public data access is available via RSS feeds for articles and podcasts.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: The New Stack Context
  property_count: 17
  slug: the-new-stack-context
layout: provider
modified: '2026-05-03'
name: The New Stack
skills: []
slug: the-new-stack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-new-stack\nurl: https://raw.githubusercontent.com/api-evangelist/the-new-stack/refs/heads/main/apis.yml\napis:\n  - aid: the-new-stack:rss\n    name: The New Stack RSS Feed\n    description: RSS feed providing the latest articles and news from The New Stack covering cloud native, DevOps, AI, and open source technologies. Feed follows RSS 2.0 with Dublin Core and WordPress content extensions.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://thenewstack.io/rss-feeds/\n    baseURL: https://thenewstack.io\n    tags:\n      - Cloud Native\n      - DevOps\n      - News Feed\n      - RSS\n    properties:\n      - url: https://thenewstack.io/feed/\n        type: RSS\n      - url: https://thenewstack.io/rss-feeds/\n        type: Documentation\n    features:\n      - RSS 2.0 Feed\n      - Category Filtering\n      - Full Article Content\n      - Author Attribution\n      - Publication Timestamps\n    useCases:\n   \
  \   - News Aggregation\n      - Content Monitoring\n      - Tech News Alert Feeds\n      - Developer Tool Discovery\n  - aid: the-new-stack:podcast-rss\n    name: The New Stack Podcast Feed\n    description: RSS feed for The New Stack podcast, featuring discussions with developers, engineers, and operations professionals building at-scale architectures. Hosted on Simplecast.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://thenewstack.io/podcasts/\n    baseURL: https://thenewstack.simplecast.com\n    tags:\n      - Cloud Native\n      - DevOps\n      - Podcast\n      - RSS\n    properties:\n      - url: https://thenewstack.simplecast.com/episodes\n        type: RSS\n      - url: https://thenewstack.io/podcasts/\n        type: HumanURL\n    features:\n      - Podcast RSS Feed\n      - Episode Audio Downloads\n      - Show Notes\n      - Guest Information\n    useCases:\n      - Podcast Aggregation\n      - Developer Podcast Discovery\n\
  \      - Tech Interview Content\nname: The New Stack\ntags:\n  - Cloud Native\n  - DevOps\n  - Media\n  - Technology News\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://thenewstack.io/\n    name: The New Stack Website\n    type: Website\n  - url: https://thenewstack.io/about-and-contact-info/\n    name: About\n    type: About\n  - url: https://thenewstack.io/rss-feeds/\n    name: RSS Feeds\n    type: RSS\n  - url: https://thenewstack.io/feed/\n    name: Main RSS Feed\n    type: RSS\n  - url: https://thenewstack.io/newsletter/\n    name: Newsletter\n    type: Newsletter\n  - url: https://thenewstack.io/podcasts/\n    name: Podcasts\n    type: Podcast\n  - url: https://thenewstack.simplecast.com/\n    name: Podcast on Simplecast\n    type: Podcast\n  - url: https://open.spotify.com/show/2nj1mpDb9jxHxi9vjZvDdk\n    name: Podcast on Spotify\n    type: Podcast\n  - url: https://thenewstack.io/contributions/\n\
  \    name: Contribute\n    type: Contribute\n  - url: https://thenewstack.io/sponsorship/\n    name: Sponsorship\n    type: Sponsorship\n  - url: https://thenewstack.io/events/\n    name: Events\n    type: Events\n  - url: https://thenewstack.io/webinars/\n    name: Webinars\n    type: Webinars\n  - url: https://thenewstack.io/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://x.com/thenewstack\n    name: X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/the-new-stack\n    name: LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/thenewstack/\n    name: Facebook\n    type: Facebook\n  - url: https://www.youtube.com/thenewstack\n    name: YouTube\n    type: YouTube\ndescription: The New Stack is a tech media platform covering cloud native, DevOps, AI, and open source technologies, providing news, analysis, podcasts, webinars, and ebooks for developers, software engineers, and operations professionals. Public data access is\
  \ available via RSS feeds for articles and podcasts.\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-new-stack/refs/heads/main/apis.yml
tags:
- Cloud Native
- DevOps
- Media
- Technology News
url: https://raw.githubusercontent.com/api-evangelist/the-new-stack/refs/heads/main/apis.yml
use_cases: []
---
