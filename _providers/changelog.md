---
api_count: 4
apis:
- description: The Changelog podcast RSS feed provides access to all episodes of The Changelog, a weekly podcast covering software development, open source, and the people and projects behind the code. The feed retu
  name: The Changelog Podcast RSS Feed
  slug: podcast-rss
- description: The Changelog Master Feed aggregates all Changelog podcast shows into a single RSS feed. This is the one-stop subscription for all developer-focused audio content produced by Changelog Media, includin
  name: Changelog Master Feed RSS
  slug: master-feed-rss
- description: The Changelog News RSS feed surfaces the latest developer news curated by the Changelog team. Changelog News is a weekly newsletter and short podcast covering what is happening in software development
  name: Changelog News RSS Feed
  slug: news-rss
- description: The Changelog platform is an open source Elixir and Phoenix application that powers changelog.com. The source code is publicly available on GitHub and includes the full CMS, podcast management, episod
  name: Changelog Open Source Platform (GitHub)
  slug: github-platform
common:
- title: ''
  type: Website
  url: https://changelog.com/
- title: ''
  type: Podcast
  url: https://changelog.com/podcast
- title: ''
  type: Podcast
  url: https://changelog.com/master
- title: ''
  type: Newsletter
  url: https://changelog.com/news
- title: ''
  type: RSSFeed
  url: https://changelog.com/podcast/feed
- title: ''
  type: RSSFeed
  url: https://changelog.com/master/feed
- title: ''
  type: RSSFeed
  url: https://changelog.com/news/feed
- title: ''
  type: Sponsorship
  url: https://changelog.com/sponsor
- title: ''
  type: PrivacyPolicy
  url: https://changelog.com/privacy
- title: ''
  type: GitHub
  url: https://github.com/thechangelog
- title: ''
  type: Repository
  url: https://github.com/thechangelog/changelog.com
- title: ''
  type: Podcast
  url: https://podcasts.apple.com/us/podcast/the-changelog-software-development-open-source/id341623264
- title: ''
  type: Podcast
  url: https://open.spotify.com/show/5bBki72YeKSLUqyD94qsuJ
- title: ''
  type: X
  url: https://x.com/changelog
- title: ''
  type: Shows
  url: ''
created: '2026-03-24'
description: Changelog is a media company and podcast network for developers covering open source and software development. Founded by Adam Stacoviak and Jerod Santo, Changelog produces world-class developer podcasts including The Changelog, which features deep technical interviews and conversations with the people and teams driving open source software forward. Changelog also publishes a weekly developer news newsletter and operates an open source platform (changelog.com) built with Elixir and Phoenix.
features:
- name: Developer Podcasts
- name: Open Source Focus
- name: Weekly Newsletter
- name: Podcast Network
- name: RSS Feeds
- name: Master Feed
- name: Developer Community
- name: Episode Notes
- name: Guest Interviews
- name: Live Events
- name: Open Source Platform
- name: Elixir and Phoenix
- name: Sponsorships
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Apple Podcasts
- name: Spotify
- name: Overcast
- name: Pocket Casts
- name: RSS
- name: GitHub
- name: YouTube
- name: Fireside
layout: provider
modified: '2026-04-23'
name: Changelog
skills: []
slug: changelog
solutions: []
source_yaml: "aid: changelog\nurl: https://raw.githubusercontent.com/api-evangelist/changelog/refs/heads/main/apis.yml\nname: Changelog\nx-type: company\ndescription: >-\n  Changelog is a media company and podcast network for developers covering open source\n  and software development. Founded by Adam Stacoviak and Jerod Santo, Changelog produces\n  world-class developer podcasts including The Changelog, which features deep technical\n  interviews and conversations with the people and teams driving open source software\n  forward. Changelog also publishes a weekly developer news newsletter and operates\n  an open source platform (changelog.com) built with Elixir and Phoenix.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer Community\n  - Media\n  - Open Source\n  - Podcasts\naccess: 3rd-Party\napis:\n  - aid: changelog:podcast-rss\n    name: The Changelog Podcast RSS Feed\n    description: >-\n      The Changelog podcast\
  \ RSS feed provides access to all episodes of The Changelog,\n      a weekly podcast covering software development, open source, and the people\n      and\n      projects behind the code. The feed returns standard podcast RSS/Atom XML with\n      episode metadata including titles, descriptions, audio URLs, and publish dates.\n    humanURL: https://changelog.com/podcast\n    baseURL: https://changelog.com\n    tags:\n      - Open Source\n      - Podcast\n      - RSS\n      - Software Development\n    properties:\n      - type: RSSFeed\n        url: https://changelog.com/podcast/feed\n      - type: Documentation\n        url: https://changelog.com/podcast\n  - aid: changelog:master-feed-rss\n    name: Changelog Master Feed RSS\n    description: >-\n      The Changelog Master Feed aggregates all Changelog podcast shows into a single\n      RSS feed. This is the one-stop subscription for all developer-focused audio\n      content produced by Changelog Media, including The Changelog podcast\
  \ and any\n      other active shows in the network.\n    humanURL: https://changelog.com/master\n    baseURL: https://changelog.com\n    tags:\n      - Aggregated\n      - Master Feed\n      - Podcast\n      - RSS\n    properties:\n      - type: RSSFeed\n        url: https://changelog.com/master/feed\n      - type: Documentation\n        url: https://changelog.com/master\n  - aid: changelog:news-rss\n    name: Changelog News RSS Feed\n    description: >-\n      The Changelog News RSS feed surfaces the latest developer news curated by\n      the Changelog team. Changelog News is a weekly newsletter and short podcast\n      covering what is happening in software development, open source, and the\n      broader developer ecosystem.\n    humanURL: https://changelog.com/news\n    baseURL: https://changelog.com\n    tags:\n      - Developer News\n      - News\n      - Newsletter\n      - RSS\n    properties:\n      - type: RSSFeed\n        url: https://changelog.com/news/feed\n      - type:\
  \ Documentation\n        url: https://changelog.com/news\n  - aid: changelog:github-platform\n    name: Changelog Open Source Platform (GitHub)\n    description: >-\n      The Changelog platform is an open source Elixir and Phoenix application that\n      powers changelog.com. The source code is publicly available on GitHub and includes\n      the full CMS, podcast management, episode metadata, and content delivery\n      infrastructure. Developers can explore the codebase to understand how the platform\n      works and contribute to the project.\n    humanURL: https://github.com/thechangelog/changelog.com\n    baseURL: https://github.com/thechangelog\n    tags:\n      - CMS\n      - Elixir\n      - Open Source\n      - Phoenix\n    properties:\n      - type: Documentation\n        url: https://github.com/thechangelog/changelog.com\n      - type: Repository\n        url: https://github.com/thechangelog/changelog.com\ncommon:\n  - url: https://changelog.com/\n    name: Changelog Website\n\
  \    type: Website\n  - url: https://changelog.com/podcast\n    name: The Changelog Podcast\n    type: Podcast\n  - url: https://changelog.com/master\n    name: Changelog Master Feed\n    type: Podcast\n  - url: https://changelog.com/news\n    name: Changelog News\n    type: Newsletter\n  - url: https://changelog.com/podcast/feed\n    name: The Changelog RSS Feed\n    type: RSSFeed\n  - url: https://changelog.com/master/feed\n    name: Changelog Master RSS Feed\n    type: RSSFeed\n  - url: https://changelog.com/news/feed\n    name: Changelog News RSS Feed\n    type: RSSFeed\n  - url: https://changelog.com/sponsor\n    name: Sponsor Changelog\n    type: Sponsorship\n  - url: https://changelog.com/privacy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://github.com/thechangelog\n    name: Changelog on GitHub\n    type: GitHub\n  - url: https://github.com/thechangelog/changelog.com\n    name: Changelog Open Source Platform\n    type: Repository\n  - url: https://podcasts.apple.com/us/podcast/the-changelog-software-development-open-source/id341623264\n\
  \    name: The Changelog on Apple Podcasts\n    type: Podcast\n  - url: https://open.spotify.com/show/5bBki72YeKSLUqyD94qsuJ\n    name: The Changelog on Spotify\n    type: Podcast\n  - url: https://x.com/changelog\n    name: Changelog on X\n    type: X\n  - name: Features\n    type: Features\n    data:\n      - name: Developer Podcasts\n      - name: Open Source Focus\n      - name: Weekly Newsletter\n      - name: Podcast Network\n      - name: RSS Feeds\n      - name: Master Feed\n      - name: Developer Community\n      - name: Episode Notes\n      - name: Guest Interviews\n      - name: Live Events\n      - name: Open Source Platform\n      - name: Elixir and Phoenix\n      - name: Sponsorships\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Developer Education\n      - name: Open Source Promotion\n      - name: Podcast Distribution\n      - name: Newsletter Aggregation\n      - name: Developer News Consumption\n      - name: Conference and Event Coverage\n      -\
  \ name: Sponsor Content Distribution\n  - name: Shows\n    type: Shows\n    data:\n      - name: The Changelog\n      - name: Changelog News\n      - name: Go Time\n      - name: JS Party\n      - name: Practical AI\n      - name: Ship It!\n      - name: Brain Science\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Apple Podcasts\n      - name: Spotify\n      - name: Overcast\n      - name: Pocket Casts\n      - name: RSS\n      - name: GitHub\n      - name: YouTube\n      - name: Fireside\ncreated: '2026-03-24'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/changelog/refs/heads/main/apis.yml
tags:
- Developer Community
- Media
- Open Source
- Podcasts
url: https://raw.githubusercontent.com/api-evangelist/changelog/refs/heads/main/apis.yml
use_cases:
- name: Developer Education
- name: Open Source Promotion
- name: Podcast Distribution
- name: Newsletter Aggregation
- name: Developer News Consumption
- name: Conference and Event Coverage
- name: Sponsor Content Distribution
---
