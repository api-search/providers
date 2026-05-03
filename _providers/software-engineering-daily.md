---
api_count: 2
apis:
- description: Software Engineering Daily provides RSS podcast feeds for its main episode stream as well as topic-specific feeds. These standard podcast RSS feeds are compatible with all major podcast clients includ
  name: Software Engineering Daily Podcast RSS Feed
  slug: podcast-rss-feed
- description: The Software Engineering Daily Backend API is an open-source REST API that powers the platform's web, iOS, and Android front ends. Built with Node.js, MongoDB, and Redis, it provides endpoints for acc
  name: Software Engineering Daily Backend API
  slug: backend-api
common:
- title: ''
  type: Website
  url: https://softwareengineeringdaily.com/
- title: ''
  type: About
  url: https://softwareengineeringdaily.com/about/
- title: ''
  type: Pricing
  url: https://softwareengineeringdaily.com/premium/
- title: ''
  type: RSSFeed
  url: https://softwareengineeringdaily.com/feed/podcast/
- title: ''
  type: RSSFeeds
  url: https://softwareengineeringdaily.com/2017/07/05/new-topic-feeds/
- title: ''
  type: GitHubRepository
  url: https://github.com/SoftwareEngineeringDaily/software-engineering-daily-api
- title: ''
  type: Documentation
  url: https://softwareengineeringdaily.github.io/Backend/gettingstarted/
- title: ''
  type: Podcast
  url: https://podcasts.apple.com/podcast/software-engineering-daily/id1019576853
- title: ''
  type: Podcast
  url: https://open.spotify.com/show/6UCtBYL29hwhw4YbTdX83N
- title: ''
  type: X
  url: https://twitter.com/software_daily
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/software-engineering-daily
- title: ''
  type: GitHubOrganization
  url: https://github.com/softwareengineeringdaily
created: '2026-03-24'
description: Software Engineering Daily is a podcast and media platform dedicated to covering software engineering topics through daily technical interviews and discussions. Founded by Jeff Meyerson in 2015, the platform publishes episodes five days a week featuring conversations with software engineers, startup founders, and technology leaders on topics ranging from distributed systems, cloud computing, databases, and programming languages to AI, machine learning, and the business of software.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-24'
name: Software Engineering Daily
skills: []
slug: software-engineering-daily
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: software-engineering-daily\nname: Software Engineering Daily\ndescription: >-\n  Software Engineering Daily is a podcast and media platform dedicated to covering\n  software engineering topics through daily technical interviews and discussions.\n  Founded by Jeff Meyerson in 2015, the platform publishes episodes five days a week\n  featuring conversations with software engineers, startup founders, and technology\n  leaders on topics ranging from distributed systems, cloud computing, databases,\n  and programming languages to AI, machine learning, and the business of software.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Media\n  - Podcasts\n  - Software Engineering\nurl: https://raw.githubusercontent.com/api-evangelist/software-engineering-daily/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-03-24'\nspecificationVersion: '0.19'\napis:\n  - aid: software-engineering-daily:podcast-rss-feed\n\
  \    name: Software Engineering Daily Podcast RSS Feed\n    description: >-\n      Software Engineering Daily provides RSS podcast feeds for its main episode\n      stream as well as topic-specific feeds. These standard podcast RSS feeds\n      are compatible with all major podcast clients including Apple Podcasts,\n      Spotify, Overcast, and Podcast Addict, and can be consumed programmatically\n      using any feed parsing library to access episode metadata, audio file URLs,\n      descriptions, and publication dates.\n    humanURL: https://softwareengineeringdaily.com/\n    baseURL: https://softwareengineeringdaily.com\n    tags:\n      - Feed\n      - Podcasts\n      - RSS\n      - Syndication\n    properties:\n      - type: Documentation\n        url: https://softwareengineeringdaily.com/2017/07/05/new-topic-feeds/\n      - type: RSSFeed\n        url: https://softwareengineeringdaily.com/feed/podcast/\n  - aid: software-engineering-daily:backend-api\n    name: Software Engineering\
  \ Daily Backend API\n    description: >-\n      The Software Engineering Daily Backend API is an open-source REST API that\n      powers the platform's web, iOS, and Android front ends. Built with Node.js,\n      MongoDB, and Redis, it provides endpoints for accessing podcast episodes,\n      user accounts, bookmarks, playback tracking, upvotes, comments, and search.\n      API documentation is available in Swagger format at the /api/docs path.\n      The codebase is MIT-licensed and available on GitHub.\n    humanURL: https://github.com/SoftwareEngineeringDaily/software-engineering-daily-api\n    baseURL: https://softwareengineeringdaily.com\n    tags:\n      - Episodes\n      - Open Source\n      - Podcasts\n      - REST\n    properties:\n      - type: Documentation\n        url: https://softwareengineeringdaily.github.io/Backend/gettingstarted/\n      - type: GitHubRepository\n        url: https://github.com/SoftwareEngineeringDaily/software-engineering-daily-api\ncommon:\n  - url:\
  \ https://softwareengineeringdaily.com/\n    name: Software Engineering Daily Website\n    type: Website\n  - url: https://softwareengineeringdaily.com/about/\n    name: About Software Engineering Daily\n    type: About\n  - url: https://softwareengineeringdaily.com/premium/\n    name: Premium Membership\n    type: Pricing\n  - url: https://softwareengineeringdaily.com/feed/podcast/\n    name: Main Podcast RSS Feed\n    type: RSSFeed\n  - url: https://softwareengineeringdaily.com/2017/07/05/new-topic-feeds/\n    name: Topic RSS Feeds\n    type: RSSFeeds\n  - url: https://github.com/SoftwareEngineeringDaily/software-engineering-daily-api\n    name: Backend API Repository\n    type: GitHubRepository\n  - url: https://softwareengineeringdaily.github.io/Backend/gettingstarted/\n    name: API Getting Started Guide\n    type: Documentation\n  - url: https://podcasts.apple.com/podcast/software-engineering-daily/id1019576853\n    name: Software Engineering Daily on Apple Podcasts\n    type: Podcast\n\
  \  - url: https://open.spotify.com/show/6UCtBYL29hwhw4YbTdX83N\n    name: Software Engineering Daily on Spotify\n    type: Podcast\n  - url: https://twitter.com/software_daily\n    name: Software Engineering Daily on X\n    type: X\n  - url: https://www.linkedin.com/company/software-engineering-daily\n    name: Software Engineering Daily on LinkedIn\n    type: LinkedIn\n  - url: https://github.com/softwareengineeringdaily\n    name: Software Engineering Daily on GitHub\n    type: GitHubOrganization\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/software-engineering-daily/refs/heads/main/apis.yml
tags:
- Media
- Podcasts
- Software Engineering
url: https://raw.githubusercontent.com/api-evangelist/software-engineering-daily/refs/heads/main/apis.yml
use_cases: []
---
