---
api_count: 2
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Feedough WordPress REST API
  slug: wordpress-rest-api
  spec_type: OpenAPI
  url: https://www.feedough.com/wp-json/
apis:
- description: Feedough provides an RSS feed for its main content stream, allowing developers and readers to consume articles on startup ideas, business models, and entrepreneurship programmatically using standard f
  name: Feedough RSS Feed
  slug: rss-feed
- description: Feedough is built on WordPress and exposes the standard WordPress REST API, providing JSON endpoints for accessing posts, categories, tags, authors, and other content types. The API is available at th
  name: Feedough WordPress REST API
  slug: wordpress-rest-api
common:
- title: ''
  type: Website
  url: https://www.feedough.com/
- title: ''
  type: About
  url: https://www.feedough.com/about-us/
- title: ''
  type: Newsletter
  url: https://www.feedough.com/subscribe/
- title: ''
  type: Advertising
  url: https://www.feedough.com/partner-with-feedough/
- title: ''
  type: RSSFeed
  url: https://www.feedough.com/feed/
- title: ''
  type: Portal
  url: https://www.feedough.com/startup-resources/
- title: ''
  type: Blog
  url: https://www.feedough.com/daily/
- title: ''
  type: PrivacyPolicy
  url: https://www.feedough.com/legal/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.feedough.com/legal/terms/
- title: ''
  type: CookiePolicy
  url: https://www.feedough.com/legal/cookie-policy/
- title: ''
  type: Disclaimer
  url: https://www.feedough.com/disclaimer/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/feedough
- title: ''
  type: X
  url: https://x.com/FeedoughCom
created: '2026-03-24'
description: Feedough is a media platform and entrepreneurship resource covering startup ideas, business models, and entrepreneurship. Founded in December 2013 by Aashish Pahwa to bridge the information gap in the startup industry, Feedough explains startup concepts in plain language without the fluff. The platform is ranked among the top twenty startup websites globally and is cited as a resource by institutions including Harvard Business School and the University of Washington.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Feedough
skills: []
slug: feedough
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: feedough\nname: Feedough\ndescription: >-\n  Feedough is a media platform and entrepreneurship resource covering startup ideas,\n  business models, and entrepreneurship. Founded in December 2013 by Aashish Pahwa\n  to bridge the information gap in the startup industry, Feedough explains startup\n  concepts in plain language without the fluff. The platform is ranked among the top\n  twenty startup websites globally and is cited as a resource by institutions including\n  Harvard Business School and the University of Washington.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Business Models\n  - Entrepreneurship\n  - Media\n  - Startups\nurl: https://raw.githubusercontent.com/api-evangelist/feedough/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: feedough:rss-feed\n    name: Feedough RSS Feed\n    description: >-\n      Feedough provides an RSS\
  \ feed for its main content stream, allowing\n      developers and readers to consume articles on startup ideas, business\n      models, and entrepreneurship programmatically using standard feed parsing\n      libraries and tools.\n    humanURL: https://www.feedough.com/feed/\n    baseURL: https://www.feedough.com\n    tags:\n      - Feed\n      - News\n      - RSS\n      - Syndication\n    properties:\n      - type: RSSFeed\n        url: https://www.feedough.com/feed/\n  - aid: feedough:wordpress-rest-api\n    name: Feedough WordPress REST API\n    description: >-\n      Feedough is built on WordPress and exposes the standard WordPress REST\n      API, providing JSON endpoints for accessing posts, categories, tags,\n      authors, and other content types. The API is available at the\n      /wp-json/wp/v2/ base path and supports filtering, pagination, and\n      searching across all Feedough content.\n    humanURL: https://developer.wordpress.org/rest-api/\n    baseURL: https://www.feedough.com/wp-json/wp/v2\n\
  \    tags:\n      - Content\n      - JSON\n      - REST\n      - WordPress\n    properties:\n      - type: Documentation\n        url: https://developer.wordpress.org/rest-api/\n      - type: OpenAPI\n        url: https://www.feedough.com/wp-json/\ncommon:\n  - url: https://www.feedough.com/\n    name: Feedough\n    type: Website\n    description: 'null'\n  - url: https://www.feedough.com/about-us/\n    name: About Feedough\n    type: About\n    description: 'null'\n  - url: https://www.feedough.com/subscribe/\n    name: Subscribe to Feedough\n    type: Newsletter\n    description: 'null'\n  - url: https://www.feedough.com/partner-with-feedough/\n    name: Partner with Feedough\n    type: Advertising\n    description: 'null'\n  - url: https://www.feedough.com/feed/\n    name: Feedough RSS Feed\n    type: RSSFeed\n    description: 'null'\n  - url: https://www.feedough.com/startup-resources/\n    name: Feedough Startup Resources\n    type: Portal\n    description: 'null'\n  - url: https://www.feedough.com/daily/\n\
  \    name: Feedough Startup Daily\n    type: Blog\n    description: 'null'\n  - url: https://www.feedough.com/legal/privacy-policy/\n    name: Privacy Policy for Feedough\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://www.feedough.com/legal/terms/\n    name: Terms of Service for Feedough\n    type: TermsOfService\n    description: 'null'\n  - url: https://www.feedough.com/legal/cookie-policy/\n    name: Cookie Policy for Feedough\n    type: CookiePolicy\n    description: 'null'\n  - url: https://www.feedough.com/disclaimer/\n    name: Disclaimer for Feedough\n    type: Disclaimer\n    description: 'null'\n  - url: https://www.linkedin.com/company/feedough\n    name: Feedough on LinkedIn\n    type: LinkedIn\n    description: 'null'\n  - url: https://x.com/FeedoughCom\n    name: Feedough on X\n    type: X\n    description: 'null'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/feedough/refs/heads/main/apis.yml
tags:
- Business Models
- Entrepreneurship
- Media
- Startups
url: https://raw.githubusercontent.com/api-evangelist/feedough/refs/heads/main/apis.yml
use_cases: []
---
