---
api_count: 3
apis:
- description: The Pandora Developer API provides GraphQL-based access to Pandora's music catalog of over 30 million tracks, stations, podcasts, and playlists. It supports personalized playback, search, user feedbac
  name: Pandora Developer API
  slug: pandora-api
- description: The AdsWizz Domain API is a programmatic audio advertising platform API enabling dynamic ad insertion, campaign management, and audience targeting across streaming radio, podcasts, and digital audio c
  name: AdsWizz Domain API
  slug: adswizz-domain-api
- description: The AdsWizz SDK provides mobile and web integration for audio advertising, supporting VAST-compliant ad tech with companion banner support. Available for iOS (Swift), Android (Kotlin), and Web (JavaSc
  name: AdsWizz SDK
  slug: adswizz-sdk
common:
- title: ''
  type: Website
  url: https://www.siriusxm.com/
- title: ''
  type: Website
  url: https://www.siriusxmmedia.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.pandora.com/
- title: ''
  type: Documentation
  url: https://developer.pandora.com/docs/
- title: ''
  type: Blog
  url: https://www.siriusxm.com/blog/
- title: ''
  type: GitHubOrg
  url: https://github.com/SiriusXM
- title: ''
  type: AdvertisingPlatform
  url: https://www.siriusxmmedia.com/
- title: ''
  type: AdsWizz
  url: https://www.adswizz.com/
- title: ''
  type: AdsWizzDocs
  url: https://docs.adswizz.com/
- title: ''
  type: TermsOfService
  url: https://www.siriusxm.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.siriusxm.com/privacy
- title: ''
  type: InvestorRelations
  url: https://investor.siriusxm.com/
created: '2025-01-01'
description: Sirius XM Holdings is the leading audio entertainment company in North America, providing satellite radio, digital streaming, podcast, and advertising services through SiriusXM, Pandora, and AdsWizz brands. The Pandora Developer API enables partners to build personalized music and podcast streaming experiences using GraphQL. AdsWizz, a SiriusXM company, provides programmatic audio advertising APIs for ad insertion, targeting, and measurement across streaming and podcast platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Sirius Xm Context
  property_count: 8
  slug: sirius-xm-context
layout: provider
modified: '2026-05-02'
name: Sirius XM
skills: []
slug: sirius-xm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sirius-xm\nname: Sirius XM\ndescription: >-\n  Sirius XM Holdings is the leading audio entertainment company in North America,\n  providing satellite radio, digital streaming, podcast, and advertising services\n  through SiriusXM, Pandora, and AdsWizz brands. The Pandora Developer API enables\n  partners to build personalized music and podcast streaming experiences using\n  GraphQL. AdsWizz, a SiriusXM company, provides programmatic audio advertising APIs\n  for ad insertion, targeting, and measurement across streaming and podcast platforms.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Audio\n  - Streaming\n  - Radio\n  - Music\n  - Podcast\n  - Advertising\n  - Entertainment\nx-fortune: Fortune 500\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sirius-xm/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: sirius-xm:pandora-api\n    name: Pandora Developer API\n    description: >-\n      The Pandora Developer API provides GraphQL-based access to Pandora's music\n      catalog of over 30 million tracks, stations, podcasts, and playlists. It\n      supports personalized playback, search, user feedback (thumbs up/down),\n      collection management, and listener profile data. Authentication uses OAuth2.\n      The API is available through the Pandora Developer Center for approved\n      partner applications.\n    humanURL: https://developer.pandora.com/\n    baseURL: https://www.pandora.com/api\n    tags:\n      - Music\n      - Streaming\n      - Podcast\n      - GraphQL\n    properties:\n      - type: Documentation\n        url: https://developer.pandora.com/docs/key-concepts/apis/\n      - type: DeveloperPortal\n        url: https://developer.pandora.com/\n\n  - aid: sirius-xm:adswizz-domain-api\n    name: AdsWizz Domain API\n    description: >-\n      The AdsWizz Domain\
  \ API is a programmatic audio advertising platform API\n      enabling dynamic ad insertion, campaign management, and audience targeting\n      across streaming radio, podcasts, and digital audio content. AdsWizz is a\n      SiriusXM company powering audio advertising technology including AudioID\n      for listener identity and contextual targeting.\n    humanURL: https://docs.adswizz.com/domain-api/v8/\n    baseURL: https://api.adswizz.com\n    tags:\n      - Advertising\n      - Audio Ads\n      - Programmatic\n      - Ad Insertion\n    properties:\n      - type: Documentation\n        url: https://docs.adswizz.com/domain-api/v8/\n\n  - aid: sirius-xm:adswizz-sdk\n    name: AdsWizz SDK\n    description: >-\n      The AdsWizz SDK provides mobile and web integration for audio advertising,\n      supporting VAST-compliant ad tech with companion banner support. Available\n      for iOS (Swift), Android (Kotlin), and Web (JavaScript).\n    humanURL: https://docs.sdk.adswizz.com/\n    baseURL:\
  \ https://api.sdk.adswizz.com\n    tags:\n      - SDK\n      - Mobile\n      - Audio Ads\n      - VAST\n    properties:\n      - type: Documentation\n        url: https://docs.sdk.adswizz.com/\n\ncommon:\n  - type: Website\n    url: https://www.siriusxm.com/\n  - type: Website\n    url: https://www.siriusxmmedia.com/\n  - type: DeveloperPortal\n    url: https://developer.pandora.com/\n  - type: Documentation\n    url: https://developer.pandora.com/docs/\n  - type: Blog\n    url: https://www.siriusxm.com/blog/\n  - type: GitHubOrg\n    url: https://github.com/SiriusXM\n  - type: AdvertisingPlatform\n    url: https://www.siriusxmmedia.com/\n  - type: AdsWizz\n    url: https://www.adswizz.com/\n  - type: AdsWizzDocs\n    url: https://docs.adswizz.com/\n  - type: TermsOfService\n    url: https://www.siriusxm.com/terms\n  - type: PrivacyPolicy\n    url: https://www.siriusxm.com/privacy\n  - type: InvestorRelations\n    url: https://investor.siriusxm.com/\n\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sirius-xm/refs/heads/main/apis.yml
tags:
- Audio
- Streaming
- Radio
- Music
- Podcast
- Advertising
- Entertainment
url: https://raw.githubusercontent.com/api-evangelist/sirius-xm/refs/heads/main/apis.yml
use_cases: []
---
