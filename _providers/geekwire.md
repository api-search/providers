---
api_count: 2
api_specs:
- filename: openapi.yaml
  format: yaml
  label: GeekWire WordPress REST API
  slug: wordpress-rest-api
  spec_type: OpenAPI
  url: https://www.geekwire.com/wp-json/
apis:
- description: GeekWire provides RSS feeds for its main news stream and individual topic categories including Microsoft, Space, Science, Real Estate, Games, Google, Mobile, GeekLife, Podcasts, and Apple. These Atom/
  name: GeekWire RSS Feed
  slug: rss-feed
- description: GeekWire is built on WordPress and exposes the standard WordPress REST API, providing JSON endpoints for accessing posts, categories, tags, authors, and other content types. The API is available at th
  name: GeekWire WordPress REST API
  slug: wordpress-rest-api
common:
- title: ''
  type: Website
  url: https://www.geekwire.com/
- title: ''
  type: About
  url: https://www.geekwire.com/about-geekwire/
- title: ''
  type: Contact
  url: https://www.geekwire.com/contact-us/
- title: ''
  type: RSSFeeds
  url: https://www.geekwire.com/rss-feeds/
- title: ''
  type: RSSFeed
  url: https://www.geekwire.com/feed/
- title: ''
  type: Newsletter
  url: https://www.geekwire.com/newsletter/
- title: ''
  type: JobBoard
  url: https://www.geekwire.com/jobs/
- title: ''
  type: Advertising
  url: https://www.geekwire.com/advertise/
- title: ''
  type: PrivacyPolicy
  url: https://www.geekwire.com/privacy/
- title: ''
  type: TermsOfService
  url: https://www.geekwire.com/termsofuse/
- title: ''
  type: Podcast
  url: https://podcasts.apple.com/us/podcast/geekwire/id427374434
- title: ''
  type: Podcast
  url: https://open.spotify.com/show/2PPEGel5l0v3XxlD8fVxAh
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/geekwire
- title: ''
  type: X
  url: https://x.com/geekwire
created: '2026-03-24'
description: GeekWire is a leading technology news site covering startups, innovation, and the Pacific Northwest tech scene. Founded in Seattle, GeekWire delivers breaking news, analysis, and commentary on technology, business, and entrepreneurship, with a particular focus on companies like Amazon, Microsoft, and the broader Seattle and Pacific Northwest startup ecosystem. GeekWire also operates GeekWork, a technology job board, and produces popular podcasts and weekly radio programming.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: GeekWire
skills: []
slug: geekwire
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: geekwire\nname: GeekWire\ndescription: >-\n  GeekWire is a leading technology news site covering startups, innovation, and\n  the Pacific Northwest tech scene. Founded in Seattle, GeekWire delivers breaking\n  news, analysis, and commentary on technology, business, and entrepreneurship,\n  with a particular focus on companies like Amazon, Microsoft, and the broader\n  Seattle and Pacific Northwest startup ecosystem. GeekWire also operates GeekWork,\n  a technology job board, and produces popular podcasts and weekly radio programming.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Media\n  - Startups\n  - Technology News\nurl: https://raw.githubusercontent.com/api-evangelist/geekwire/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: geekwire:rss-feed\n    name: GeekWire RSS Feed\n    description: >-\n      GeekWire provides RSS feeds for its main\
  \ news stream and individual topic\n      categories including Microsoft, Space, Science, Real Estate, Games, Google,\n      Mobile, GeekLife, Podcasts, and Apple. These Atom/RSS feeds allow developers\n      and readers to consume GeekWire content programmatically using standard\n      feed parsing libraries and tools.\n    humanURL: https://www.geekwire.com/rss-feeds/\n    baseURL: https://www.geekwire.com\n    tags:\n      - Feed\n      - News\n      - RSS\n      - Syndication\n    properties:\n      - type: Documentation\n        url: https://www.geekwire.com/rss-feeds/\n      - type: RSSFeed\n        url: https://www.geekwire.com/feed/\n  - aid: geekwire:wordpress-rest-api\n    name: GeekWire WordPress REST API\n    description: >-\n      GeekWire is built on WordPress and exposes the standard WordPress REST API,\n      providing JSON endpoints for accessing posts, categories, tags, authors, and\n      other content types. The API is available at the /wp-json/wp/v2/ base path\n  \
  \    and supports filtering, pagination, and searching across all GeekWire content.\n    humanURL: https://developer.wordpress.org/rest-api/\n    baseURL: https://www.geekwire.com/wp-json/wp/v2\n    tags:\n      - Content\n      - JSON\n      - REST\n      - WordPress\n    properties:\n      - type: Documentation\n        url: https://developer.wordpress.org/rest-api/\n      - type: OpenAPI\n        url: https://www.geekwire.com/wp-json/\ncommon:\n  - url: https://www.geekwire.com/\n    name: GeekWire\n    type: Website\n    description: 'null'\n  - url: https://www.geekwire.com/about-geekwire/\n    name: About GeekWire\n    type: About\n    description: 'null'\n  - url: https://www.geekwire.com/contact-us/\n    name: Contact GeekWire\n    type: Contact\n    description: 'null'\n  - url: https://www.geekwire.com/rss-feeds/\n    name: GeekWire RSS Feeds\n    type: RSSFeeds\n    description: 'null'\n  - url: https://www.geekwire.com/feed/\n    name: GeekWire Main RSS Feed\n    type: RSSFeed\n\
  \    description: 'null'\n  - url: https://www.geekwire.com/newsletter/\n    name: GeekWire Newsletter\n    type: Newsletter\n    description: 'null'\n  - url: https://www.geekwire.com/jobs/\n    name: GeekWork Job Board\n    type: JobBoard\n    description: 'null'\n  - url: https://www.geekwire.com/advertise/\n    name: Advertise on GeekWire\n    type: Advertising\n    description: 'null'\n  - url: https://www.geekwire.com/privacy/\n    name: Privacy Policy for GeekWire\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://www.geekwire.com/termsofuse/\n    name: Terms of Use for GeekWire\n    type: TermsOfService\n    description: 'null'\n  - url: https://podcasts.apple.com/us/podcast/geekwire/id427374434\n    name: GeekWire Podcast on Apple Podcasts\n    type: Podcast\n    description: 'null'\n  - url: https://open.spotify.com/show/2PPEGel5l0v3XxlD8fVxAh\n    name: GeekWire Podcast on Spotify\n    type: Podcast\n    description: 'null'\n  - url: https://www.linkedin.com/company/geekwire\n\
  \    name: GeekWire on LinkedIn\n    type: LinkedIn\n    description: 'null'\n  - url: https://x.com/geekwire\n    name: GeekWire on X\n    type: X\n    description: 'null'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/geekwire/refs/heads/main/apis.yml
tags:
- Media
- Startups
- Technology News
url: https://raw.githubusercontent.com/api-evangelist/geekwire/refs/heads/main/apis.yml
use_cases: []
---
