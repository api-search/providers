---
api_count: 2
apis:
- description: Integrate your election systems with AP Elections API. Your election results delivery application retrieves election race information from AP Elections API to power election websites, reporting system
  name: AP Elections API
  slug: ap-elections-api
- description: The AP Media API provides access to AP's digital media assets including photos, videos, and graphics from AP's global newsgathering operations. Enables integration with digital asset management system
  name: AP Media API
  slug: ap-media-api
common:
- title: Associated Press Website
  type: Portal
  url: https://www.ap.org/
- title: AP Developer Portal
  type: Portal
  url: https://developer.ap.org/
- title: Developer Documentation
  type: Documentation
  url: https://developer.ap.org/
created: '2024-04-14'
description: The Associated Press (AP) is an American not-for-profit news agency founded in 1846. The AP is the world's oldest and largest newsgathering organization, serving media companies worldwide with text, photos, video, audio, and interactive content. The AP provides developer APIs for accessing election data, news content, and media assets including the AP Elections API for real-time election results, the AP Content API for news and media asset access, and the AP Media API for digital asset management integration.
features:
- description: Real-time election results delivery for federal, state, and local elections with candidate data, race calls, and vote totals.
  name: AP Elections API
- description: Access to AP's global news content including text stories, photos, video, and graphics from AP correspondents worldwide.
  name: AP Content API
- description: Digital asset management integration for AP's extensive photo and video library with metadata, rights, and distribution capabilities.
  name: AP Media API
- description: Streaming news content delivery for applications requiring real-time news updates and content ingestion.
  name: AP DataStream
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AP content APIs integrate with major content management systems used by newspapers, broadcasters, and digital media publishers.
  name: Newsroom CMS Integrations
- description: Election technology vendors integrate AP Elections API for authoritative election result data in voting systems and election night reporting tools.
  name: Election Management Systems
layout: provider
modified: '2026-04-19'
name: Associated Press
skills: []
slug: associated-press
solutions: []
source_yaml: "aid: associated-press\nname: Associated Press\ndescription: >-\n  The Associated Press (AP) is an American not-for-profit news agency founded\n  in 1846. The AP is the world's oldest and largest newsgathering organization,\n  serving media companies worldwide with text, photos, video, audio, and\n  interactive content. The AP provides developer APIs for accessing election\n  data, news content, and media assets including the AP Elections API for\n  real-time election results, the AP Content API for news and media asset\n  access, and the AP Media API for digital asset management integration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Elections\n  - Journalism\n  - Media\n  - News\n  - Content\ncreated: '2024-04-14'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/associated-press/refs/heads/main/apis.yml\napis:\n  - aid: associated-press:ap-elections-api\n\
  \    name: AP Elections API\n    description: >-\n      Integrate your election systems with AP Elections API. Your election\n      results delivery application retrieves election race information from\n      AP Elections API to power election websites, reporting systems, and\n      news dashboards. Provides real-time election results, candidate data,\n      and race call information for federal, state, and local elections.\n    humanURL: https://developer.ap.org/ap-elections-api/\n    baseURL: https://api.ap.org\n    tags:\n      - Elections\n      - News\n      - Results\n    properties:\n      - type: Documentation\n        url: https://developer.ap.org/ap-elections-api/\n      - type: GettingStarted\n        url: https://developer.ap.org/ap-elections-api/\n  - aid: associated-press:ap-media-api\n    name: AP Media API\n    description: >-\n      The AP Media API provides access to AP's digital media assets including\n      photos, videos, and graphics from AP's global newsgathering\
  \ operations.\n      Enables integration with digital asset management systems and content\n      management platforms for news organizations.\n    humanURL: https://developer.ap.org/\n    baseURL: https://api.ap.org\n    tags:\n      - Media\n      - Photos\n      - Video\n      - Content\n    properties:\n      - type: Documentation\n        url: https://developer.ap.org/\n      - type: OpenAPI\n        url: openapi/associated-press-meda-openapi-original.yml\ncommon:\n  - type: Portal\n    url: https://www.ap.org/\n    title: Associated Press Website\n  - type: Portal\n    url: https://developer.ap.org/\n    title: AP Developer Portal\n  - type: Documentation\n    url: https://developer.ap.org/\n    title: Developer Documentation\n  - type: Features\n    data:\n      - name: AP Elections API\n        description: >-\n          Real-time election results delivery for federal, state, and local\n          elections with candidate data, race calls, and vote totals.\n      - name: AP Content\
  \ API\n        description: >-\n          Access to AP's global news content including text stories, photos,\n          video, and graphics from AP correspondents worldwide.\n      - name: AP Media API\n        description: >-\n          Digital asset management integration for AP's extensive photo and\n          video library with metadata, rights, and distribution capabilities.\n      - name: AP DataStream\n        description: >-\n          Streaming news content delivery for applications requiring real-time\n          news updates and content ingestion.\n  - type: UseCases\n    data:\n      - name: Election Coverage\n        description: >-\n          News organizations and election management companies use the AP\n          Elections API to power live election result dashboards and reporting.\n      - name: News Content Integration\n        description: >-\n          Media companies integrate AP content APIs to supplement their own\n          coverage with AP newswire stories and\
  \ multimedia content.\n      - name: Photo and Video Licensing\n        description: >-\n          Publishers and digital media companies access AP's photo and video\n          archive through the Media API for editorial and commercial use.\n  - type: Integrations\n    data:\n      - name: Newsroom CMS Integrations\n        description: >-\n          AP content APIs integrate with major content management systems\n          used by newspapers, broadcasters, and digital media publishers.\n      - name: Election Management Systems\n        description: >-\n          Election technology vendors integrate AP Elections API for\n          authoritative election result data in voting systems and election\n          night reporting tools.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/associated-press/refs/heads/main/apis.yml
tags:
- Elections
- Journalism
- Media
- News
- Content
url: https://raw.githubusercontent.com/api-evangelist/associated-press/refs/heads/main/apis.yml
use_cases:
- description: News organizations and election management companies use the AP Elections API to power live election result dashboards and reporting.
  name: Election Coverage
- description: Media companies integrate AP content APIs to supplement their own coverage with AP newswire stories and multimedia content.
  name: News Content Integration
- description: Publishers and digital media companies access AP's photo and video archive through the Media API for editorial and commercial use.
  name: Photo and Video Licensing
---
