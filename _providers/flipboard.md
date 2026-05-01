---
api_count: 2
apis:
- description: Flipboard supports RSS feeds as the primary integration mechanism for publishers and content creators. Publishers can submit RSS feeds to be featured as Flipboard Magazines, enabling content distribut
  name: Flipboard RSS Feeds
  slug: rss-feeds
- description: Flipboard has implemented the ActivityPub protocol, making its content available to the broader Fediverse. Starting in 2023, Flipboard began federating its magazines and curators via ActivityPub, allo
  name: Flipboard ActivityPub
  slug: activitypub
common:
- title: ''
  type: Website
  url: https://flipboard.com/
- title: ''
  type: About
  url: https://about.flipboard.com/
- title: ''
  type: Portal
  url: https://about.flipboard.com/forpublishers/
- title: ''
  type: Documentation
  url: https://about.flipboard.com/rss-guidelines/
- title: ''
  type: Validator
  url: https://feedvalidator.flipboard.com/
- title: ''
  type: Blog
  url: https://engineering.flipboard.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/Flipboard
- title: ''
  type: GitHubRepository
  url: https://github.com/Flipboard/activitypub
- title: ''
  type: Support
  url: https://flipboard.helpshift.com/hc/en/
- title: ''
  type: Contact
  url: https://flipboard.helpshift.com/hc/en/1-flipboard/contact-us/
- title: ''
  type: TermsOfService
  url: https://about.flipboard.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://about.flipboard.com/privacy-policy/
- title: ''
  type: CookiePolicy
  url: https://about.flipboard.com/cookie-policy/
- title: ''
  type: CommunityGuidelines
  url: https://about.flipboard.com/community-guidelines/
- title: ''
  type: X
  url: https://x.com/flipboard
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/flipboard
- title: ''
  type: Facebook
  url: https://www.facebook.com/flipboard
created: '2024-01-01'
description: Flipboard is a content curation and social magazine platform that aggregates articles, videos, and social media posts into personalized, magazine-style feeds. Founded in 2010, Flipboard allows users to curate content into magazines around topics of interest and follow curators and publishers. Flipboard has embraced open web standards, implementing ActivityPub to federate with the Fediverse and supporting RSS for publisher content distribution.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Flipboard
skills: []
slug: flipboard
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flipboard\nurl: https://raw.githubusercontent.com/api-evangelist/flipboard/refs/heads/main/apis.yml\napis:\n  - aid: flipboard:rss-feeds\n    name: Flipboard RSS Feeds\n    description: Flipboard supports RSS feeds as the primary integration mechanism for publishers and content creators. Publishers can submit RSS feeds to be featured as Flipboard Magazines, enabling content distribution to Flipboard's audience. Feeds must meet Flipboard's RSS guidelines, including full article body content, images of at least 400px wide, at least 30 items, and updates pushed via PubSubHubbub.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://about.flipboard.com/rss-guidelines/\n    baseURL: https://flipboard.com\n    tags:\n      - Content Syndication\n      - News\n      - Publishers\n      - RSS\n    properties:\n      - url: https://about.flipboard.com/rss-guidelines/\n        type: Documentation\n      - url: https://about.flipboard.com/forpublishers/\n\
  \        type: GettingStarted\n      - url: https://feedvalidator.flipboard.com/\n        type: Validator\n      - url: https://flipboard.helpshift.com/hc/en/1-flipboard/faq/1024-submit-a-publisher-application/\n        type: GettingStarted\n  - aid: flipboard:activitypub\n    name: Flipboard ActivityPub\n    description: Flipboard has implemented the ActivityPub protocol, making its content available to the broader Fediverse. Starting in 2023, Flipboard began federating its magazines and curators via ActivityPub, allowing users on Mastodon, Threads, Pixelfed, and other ActivityPub-compatible platforms to follow and interact with Flipboard content. Flipboard's full architecture is built around ActivityPub.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://about.flipboard.com/inside-flipboard/flipboard-begins-to-federate/\n    baseURL: https://flipboard.com\n    tags:\n      - ActivityPub\n      - Decentralized\n      - Fediverse\n\
  \      - Mastodon\n      - Open Social Web\n    properties:\n      - url: https://github.com/Flipboard/activitypub\n        type: GitHubRepository\n      - url: https://about.flipboard.com/inside-flipboard/flipboard-begins-to-federate/\n        type: Announcement\n      - url: https://about.flipboard.com/business/publisher-federation-flipboard/\n        type: Guide\nname: Flipboard\ntags:\n  - ActivityPub\n  - Content Curation\n  - Digital Publishing\n  - Fediverse\n  - News\n  - RSS\n  - Social Media\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://flipboard.com/\n    name: Flipboard Website\n    type: Website\n  - url: https://about.flipboard.com/\n    name: About Flipboard\n    type: About\n  - url: https://about.flipboard.com/forpublishers/\n    name: For Publishers\n    type: Portal\n  - url: https://about.flipboard.com/rss-guidelines/\n    name: RSS Guidelines\n    type: Documentation\n  -\
  \ url: https://feedvalidator.flipboard.com/\n    name: Feed Validator\n    type: Validator\n  - url: https://engineering.flipboard.com/\n    name: Flipboard Engineering Blog\n    type: Blog\n  - url: https://github.com/Flipboard\n    name: Flipboard on GitHub\n    type: GitHubOrganization\n  - url: https://github.com/Flipboard/activitypub\n    name: ActivityPub Implementation\n    type: GitHubRepository\n  - url: https://flipboard.helpshift.com/hc/en/\n    name: Help Center\n    type: Support\n  - url: https://flipboard.helpshift.com/hc/en/1-flipboard/contact-us/\n    name: Contact Us\n    type: Contact\n  - url: https://about.flipboard.com/terms-of-service/\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://about.flipboard.com/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://about.flipboard.com/cookie-policy/\n    name: Cookie Policy\n    type: CookiePolicy\n  - url: https://about.flipboard.com/community-guidelines/\n    name: Community\
  \ Guidelines\n    type: CommunityGuidelines\n  - url: https://x.com/flipboard\n    name: X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/flipboard\n    name: LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/flipboard\n    name: Facebook\n    type: Facebook\ndescription: >-\n  Flipboard is a content curation and social magazine platform that aggregates articles,\n  videos, and social media posts into personalized, magazine-style feeds. Founded\n  in 2010, Flipboard allows users to curate content into magazines around topics of\n  interest and follow curators and publishers. Flipboard has embraced open web standards,\n  implementing ActivityPub to federate with the Fediverse and supporting RSS for publisher\n  content distribution.\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flipboard/refs/heads/main/apis.yml
tags:
- ActivityPub
- Content Curation
- Digital Publishing
- Fediverse
- News
- RSS
- Social Media
url: https://raw.githubusercontent.com/api-evangelist/flipboard/refs/heads/main/apis.yml
use_cases: []
---
