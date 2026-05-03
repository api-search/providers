---
api_count: 1
apis:
- description: The Next Web provides an RSS 2.0 feed updated hourly with the latest technology news, analysis, and articles published on thenextweb.com. The feed covers topics including artificial intelligence, star
  name: TNW RSS Feed
  slug: the-next-web-rss-feed
common:
- title: ''
  type: Website
  url: https://thenextweb.com/
- title: ''
  type: RSS
  url: https://thenextweb.com/feed/
- title: ''
  type: News
  url: https://thenextweb.com/latest
- title: ''
  type: Newsletter
  url: https://thenextweb.com/newsletters
- title: ''
  type: Events
  url: https://thenextweb.com/events
- title: ''
  type: Events
  url: https://thenextweb.com/conference
- title: ''
  type: About
  url: https://thenextweb.com/about
- title: ''
  type: Advertising
  url: https://thenextweb.com/advertise
- title: ''
  type: Marketplace
  url: https://deals.thenextweb.com/
- title: ''
  type: PrivacyPolicy
  url: https://thenextweb.com/privacy-statement
- title: ''
  type: TermsOfService
  url: https://thenextweb.com/terms-of-service
- title: ''
  type: Contact
  url: https://thenextweb.com/contact
- title: ''
  type: X
  url: https://x.com/thenextweb
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/the-next-web
- title: ''
  type: Facebook
  url: https://www.facebook.com/thenextweb/
- title: ''
  type: GitHub
  url: https://github.com/thenextweb
- title: ''
  type: JSONSchema
  url: json-schema/the-next-web-article-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/the-next-web-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/the-next-web-vocabulary.yml
created: '2026-03-24'
description: The Next Web is a leading online media organization covering technology news, business, and culture. Founded in 2006, TNW reports on startups, innovation, artificial intelligence, digital culture, and the future of work. The primary programmatic access to TNW content is through its RSS 2.0 feed, which is updated hourly with the latest articles across all topic areas. Category-specific feeds are also available for Deep Tech, Plugged (consumer tech), and Sustainability. TNW also organizes the annual TNW Conference and operates a technology events business.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 12
  name: The Next Web Context
  property_count: 4
  slug: the-next-web-context
layout: provider
modified: '2026-05-03'
name: The Next Web
skills: []
slug: the-next-web
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-next-web\nurl: https://raw.githubusercontent.com/api-evangelist/the-next-web/refs/heads/main/apis.yml\nname: The Next Web\ndescription: >-\n  The Next Web is a leading online media organization covering technology news,\n  business, and culture. Founded in 2006, TNW reports on startups, innovation,\n  artificial intelligence, digital culture, and the future of work. The primary\n  programmatic access to TNW content is through its RSS 2.0 feed, which is updated\n  hourly with the latest articles across all topic areas. Category-specific feeds\n  are also available for Deep Tech, Plugged (consumer tech), and Sustainability.\n  TNW also organizes the annual TNW Conference and operates a technology events\n  business.\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ntags:\n  - Technology News\n  - Innovation\n  - Media\n  - Events\n  - Startups\n  - Artificial Intelligence\ncreated: '2026-03-24'\nmodified:\
  \ '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: the-next-web:the-next-web-rss-feed\n    name: TNW RSS Feed\n    description: >-\n      The Next Web provides an RSS 2.0 feed updated hourly with the latest\n      technology news, analysis, and articles published on thenextweb.com.\n      The feed covers topics including artificial intelligence, startups,\n      innovation, digital culture, and the future of work. Category-specific\n      feeds are available for Deep Tech, Plugged (consumer tech), and\n      Sustainability. Each article entry includes title, link, description,\n      publication date, author, and category tags.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://thenextweb.com\n    humanURL: https://thenextweb.com/feed/\n    tags:\n      - Articles\n      - News\n      - RSS\n      - Technology\n      - Innovation\n    properties:\n      - url: https://thenextweb.com/feed/\n        type: RSS\n      - url:\
  \ https://thenextweb.com/deep-tech/feed/\n        name: Deep Tech RSS Feed\n        type: RSS\n      - url: https://thenextweb.com/plugged/feed/\n        name: Plugged RSS Feed\n        type: RSS\n      - url: https://thenextweb.com/sustainability/feed/\n        name: Sustainability RSS Feed\n        type: RSS\n\ncommon:\n  - url: https://thenextweb.com/\n    name: TNW Website\n    type: Website\n  - url: https://thenextweb.com/feed/\n    name: RSS Feed\n    type: RSS\n  - url: https://thenextweb.com/latest\n    name: Latest News\n    type: News\n  - url: https://thenextweb.com/newsletters\n    name: TNW Newsletters\n    type: Newsletter\n  - url: https://thenextweb.com/events\n    name: TNW Events\n    type: Events\n  - url: https://thenextweb.com/conference\n    name: TNW Conference\n    type: Events\n  - url: https://thenextweb.com/about\n    name: About TNW\n    type: About\n  - url: https://thenextweb.com/advertise\n    name: Advertise with TNW\n    type: Advertising\n  - url: https://deals.thenextweb.com/\n\
  \    name: TNW Deals\n    type: Marketplace\n  - url: https://thenextweb.com/privacy-statement\n    name: Privacy Statement\n    type: PrivacyPolicy\n  - url: https://thenextweb.com/terms-of-service\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://thenextweb.com/contact\n    name: Contact TNW\n    type: Contact\n  - url: https://x.com/thenextweb\n    name: TNW on X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/the-next-web\n    name: TNW on LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/thenextweb/\n    name: TNW on Facebook\n    type: Facebook\n  - url: https://github.com/thenextweb\n    name: TNW on GitHub\n    type: GitHub\n  - url: json-schema/the-next-web-article-schema.json\n    type: JSONSchema\n  - url: json-ld/the-next-web-context.jsonld\n    type: JSONLDContext\n  - url: vocabulary/the-next-web-vocabulary.yml\n    type: Vocabulary\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-next-web/refs/heads/main/apis.yml
tags:
- Technology News
- Innovation
- Media
- Events
- Startups
- Artificial Intelligence
url: https://raw.githubusercontent.com/api-evangelist/the-next-web/refs/heads/main/apis.yml
use_cases: []
---
