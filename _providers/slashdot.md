---
api_count: 1
api_specs:
- filename: slashdot-rss-openapi.yml
  format: yaml
  label: Slashdot RSS/Atom Feeds
  slug: rss-feeds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/slashdot/refs/heads/main/openapi/slashdot-rss-openapi.yml
apis:
- description: Slashdot provides RSS 1.0 and Atom 1.0 feeds for programmatic access to technology news across multiple topic sections. Feeds are rate-limited to one request per 30 minutes per feed URL. Section feeds
  name: Slashdot RSS/Atom Feeds
  slug: rss-feeds
common:
- title: ''
  type: Website
  url: https://slashdot.org/
- title: ''
  type: RSS
  url: https://rss.slashdot.org/Slashdot/slashdotMain
- title: ''
  type: RSS
  url: https://rss.slashdot.org/Slashdot/slashdotDevelopers
- title: ''
  type: RSS
  url: https://rss.slashdot.org/Slashdot/slashdotApple
- title: ''
  type: RSS
  url: https://rss.slashdot.org/Slashdot/slashdotLinux
- title: ''
  type: RSS
  url: https://rss.slashdot.org/Slashdot/slashdotGames
- title: ''
  type: RSS
  url: https://rss.slashdot.org/Slashdot/slashdotScience
- title: ''
  type: RSS
  url: https://rss.slashdot.org/Slashdot/slashdotYourRightsOnline
- title: ''
  type: About
  url: https://slashdot.org/faq/slashmeta.shtml
- title: ''
  type: FAQ
  url: https://slashdot.org/faq/index.shtml
- title: ''
  type: FAQ-Feeds
  url: https://slashdot.org/faq/feeds.shtml
- title: ''
  type: Firehose
  url: https://slashdot.org/faq/firehose.shtml
- title: ''
  type: Privacy Policy
  url: https://slashdot.org/privacy
- title: ''
  type: OpenAPI
  url: openapi/slashdot-rss-openapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/slashdot-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/slashdot-vocabulary.yml
created: '2026-03-24'
description: Slashdot is a technology news aggregation and community discussion site founded in 1997, focused on open source software, Linux, science, and technology topics. Known by its tagline "News for nerds, stuff that matters," Slashdot allows readers to submit and vote on stories, comment on articles, and follow developments across the technology landscape. The site offers RSS and Atom feeds for programmatic access to its content across multiple topic sections including developers, Linux, games, science, Apple, and more. Feed requests are rate-limited to one per 30 minutes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Slashdot Context
  property_count: 5
  slug: slashdot-context
layout: provider
modified: '2026-05-02'
name: Slashdot
rules:
- name: Slashdot API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: slashdot-rules
skills: []
slug: slashdot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: slashdot\nurl: https://raw.githubusercontent.com/api-evangelist/slashdot/refs/heads/main/apis.yml\nname: Slashdot\ntags:\n  - Media\n  - Open Source\n  - Technology News\n  - RSS\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-24'\nmodified: '2026-05-02'\nposition: Consumer\nsegments:\n  - Media\n  - Technology News\ndescription: >-\n  Slashdot is a technology news aggregation and community discussion site founded\n  in 1997, focused on open source software, Linux, science, and technology topics.\n  Known by its tagline \"News for nerds, stuff that matters,\" Slashdot allows readers\n  to submit and vote on stories, comment on articles, and follow developments across\n  the technology landscape. The site offers RSS and Atom feeds for programmatic access\n  to its content across multiple topic sections including developers, Linux, games,\n  science, Apple, and more. Feed requests are rate-limited\
  \ to one per 30 minutes.\napis:\n  - aid: slashdot:rss-feeds\n    name: Slashdot RSS/Atom Feeds\n    tags:\n      - RSS\n      - Atom\n      - News\n      - Technology News\n      - Open Source\n      - Media\n    humanURL: https://slashdot.org/faq/feeds.shtml\n    properties:\n      - url: https://rss.slashdot.org/Slashdot/slashdotMain\n        type: RSS\n      - url: https://rss.slashdot.org/Slashdot/slashdotDevelopers\n        type: RSS\n      - url: https://rss.slashdot.org/Slashdot/slashdotApple\n        type: RSS\n      - url: https://rss.slashdot.org/Slashdot/slashdotLinux\n        type: RSS\n      - url: https://rss.slashdot.org/Slashdot/slashdotGames\n        type: RSS\n      - url: https://rss.slashdot.org/Slashdot/slashdotScience\n        type: RSS\n      - url: https://rss.slashdot.org/Slashdot/slashdotYourRightsOnline\n        type: RSS\n      - url: openapi/slashdot-rss-openapi.yml\n        type: OpenAPI\n      - url: json-ld/slashdot-context.jsonld\n        type: JSON-LD\n\
  \      - url: vocabulary/slashdot-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      Slashdot provides RSS 1.0 and Atom 1.0 feeds for programmatic access to\n      technology news across multiple topic sections. Feeds are rate-limited to\n      one request per 30 minutes per feed URL. Section feeds are available by\n      substituting section names in the base RSS URL pattern. Subscriber feeds\n      support a log token parameter for personalized content.\ncommon:\n  - type: Website\n    url: https://slashdot.org/\n  - type: RSS\n    url: https://rss.slashdot.org/Slashdot/slashdotMain\n  - type: RSS\n    url: https://rss.slashdot.org/Slashdot/slashdotDevelopers\n  - type: RSS\n    url: https://rss.slashdot.org/Slashdot/slashdotApple\n  - type: RSS\n    url: https://rss.slashdot.org/Slashdot/slashdotLinux\n  - type: RSS\n    url: https://rss.slashdot.org/Slashdot/slashdotGames\n  - type: RSS\n    url: https://rss.slashdot.org/Slashdot/slashdotScience\n  - type: RSS\n \
  \   url: https://rss.slashdot.org/Slashdot/slashdotYourRightsOnline\n  - type: About\n    url: https://slashdot.org/faq/slashmeta.shtml\n  - type: FAQ\n    url: https://slashdot.org/faq/index.shtml\n  - type: FAQ-Feeds\n    url: https://slashdot.org/faq/feeds.shtml\n  - type: Firehose\n    url: https://slashdot.org/faq/firehose.shtml\n  - type: Privacy Policy\n    url: https://slashdot.org/privacy\n  - type: OpenAPI\n    url: openapi/slashdot-rss-openapi.yml\n  - type: JSON-LD\n    url: json-ld/slashdot-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/slashdot-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/slashdot/refs/heads/main/apis.yml
tags:
- Media
- Open Source
- Technology News
- RSS
url: https://raw.githubusercontent.com/api-evangelist/slashdot/refs/heads/main/apis.yml
use_cases: []
---
