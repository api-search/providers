---
api_count: 1
api_specs:
- filename: hacker-news-openapi.yml
  format: yaml
  label: Hacker News API
  slug: hacker-news-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hacker-news/refs/heads/main/openapi/hacker-news-openapi.yml
apis:
- description: The Hacker News API provides access to items (stories, comments, jobs, Ask HNs, polls), users, and live data via Firebase endpoints. It is a public, read-only REST API that exposes the full dataset of
  name: Hacker News API
  slug: hacker-news-api
common:
- title: ''
  type: Website
  url: https://news.ycombinator.com/
- title: ''
  type: Documentation
  url: https://github.com/HackerNews/API
- title: ''
  type: Guidelines
  url: https://news.ycombinator.com/newsguidelines.html
- title: ''
  type: TermsOfService
  url: https://news.ycombinator.com/legal
- title: ''
  type: Security
  url: https://news.ycombinator.com/security.html
- title: ''
  type: Portal
  url: https://news.ycombinator.com/lists
- title: ''
  type: RSS
  url: https://news.ycombinator.com/rss
- title: ''
  type: Forum
  url: https://news.ycombinator.com/ask
- title: ''
  type: Showcase
  url: https://news.ycombinator.com/show
- title: ''
  type: About
  url: https://www.ycombinator.com/
created: '2026-03-24'
description: Hacker News is Y Combinator's technology news aggregation and discussion platform. It exposes a public, read-only Firebase-backed API that gives developers real-time access to stories, comments, jobs, polls, and user profiles across the full HN dataset.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Hacker News
skills: []
slug: hacker-news
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hacker-news\nname: Hacker News\ndescription: >-\n  Hacker News is Y Combinator's technology news aggregation and discussion\n  platform. It exposes a public, read-only Firebase-backed API that gives\n  developers real-time access to stories, comments, jobs, polls, and user\n  profiles across the full HN dataset.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/hacker-news/refs/heads/main/apis.yml\naccess: 3rd-Party\ntags:\n  - Developer Community\n  - Technology News\n  - Y Combinator\ncreated: '2026-03-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: hacker-news:hacker-news-api\n    name: Hacker News API\n    description: >-\n      The Hacker News API provides access to items (stories, comments, jobs,\n      Ask HNs, polls), users, and live data via Firebase endpoints. It is a\n      public, read-only REST API that exposes the full dataset of\
  \ Hacker\n      News content in near real-time. Developers can retrieve individual\n      items by ID, look up user profiles, and subscribe to live feeds of\n      new, top, best, ask, show, and job stories. The API requires no\n      authentication and returns JSON data from Firebase's real-time\n      database infrastructure.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/HackerNews/API\n    baseURL: https://hacker-news.firebaseio.com\n    tags:\n      - Comments\n      - News\n      - Stories\n    properties:\n      - type: Documentation\n        url: https://github.com/HackerNews/API\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/hacker-news/refs/heads/main/openapi/hacker-news-openapi.yml\n      - type: Rules\n        url: https://raw.githubusercontent.com/api-evangelist/hacker-news/refs/heads/main/hacker-news-rules.yml\ncommon:\n  - url: https://news.ycombinator.com/\n\
  \    name: Hacker News Website\n    type: Website\n  - url: https://github.com/HackerNews/API\n    name: API Documentation\n    type: Documentation\n  - url: https://news.ycombinator.com/newsguidelines.html\n    name: Community Guidelines\n    type: Guidelines\n  - url: https://news.ycombinator.com/legal\n    name: Legal\n    type: TermsOfService\n  - url: https://news.ycombinator.com/security.html\n    name: Security Policy\n    type: Security\n  - url: https://news.ycombinator.com/lists\n    name: Lists\n    type: Portal\n  - url: https://news.ycombinator.com/rss\n    name: RSS Feed\n    type: RSS\n  - url: https://news.ycombinator.com/ask\n    name: Ask HN\n    type: Forum\n  - url: https://news.ycombinator.com/show\n    name: Show HN\n    type: Showcase\n  - url: https://www.ycombinator.com/\n    name: Y Combinator\n    type: About\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hacker-news/refs/heads/main/apis.yml
tags:
- Developer Community
- Technology News
- Y Combinator
url: https://raw.githubusercontent.com/api-evangelist/hacker-news/refs/heads/main/apis.yml
use_cases: []
---
