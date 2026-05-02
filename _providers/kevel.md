---
api_count: 4
apis:
- description: The Decision API enables ad requests without using ad code. By posting to a RESTful endpoint, Kevel's ad engine returns decision data and creative contents for serving ads in your application across w
  name: Kevel Decision API
  slug: decision-api
- description: 'The Management API provides programmatic access to manage advertisers, campaigns, flights, ads, creatives, channels, sites, zones, and other platform resources. It is the system-of-record API used to '
  name: Kevel Management API
  slug: management-api
- description: The Reporting API exposes ad serving performance data, allowing customers to pull impressions, clicks, conversions, revenue, and other metrics by advertiser, campaign, flight, ad, creative, site, zone
  name: Kevel Reporting API
  slug: reporting-api
- description: The UserDB API provides first-party audience and user data management, enabling customers to read and write user keys, custom properties, interests, and audience segment membership for targeting in th
  name: Kevel UserDB API
  slug: userdb-api
common:
- title: ''
  type: Website
  url: https://www.kevel.com
- title: ''
  type: Portal
  url: https://dev.kevel.com/
- title: ''
  type: Documentation
  url: https://dev.kevel.com/docs/understanding-kevel
- title: ''
  type: GettingStarted
  url: https://dev.kevel.com/reference/getting-started-with-kevel
- title: ''
  type: Reference
  url: https://dev.kevel.com/reference
- title: ''
  type: SDKs
  url: https://dev.kevel.com/docs/sdks
- title: ''
  type: Blog
  url: https://www.kevel.com/blog
- title: ''
  type: Pricing
  url: https://www.kevel.com/pricing
created: '2026-03-16'
description: Kevel is an API-first ad serving platform that lets brands and publishers build unified, fully customized ad systems supporting any ad format, any creative, and multiple demand sources. Kevel exposes a Decision API for ad requests, a Management API for campaign and creative operations, a Reporting API for performance analytics, and a UserDB API for first-party audience and user data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Kevel
skills: []
slug: kevel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kevel\nname: Kevel\ndescription: >-\n  Kevel is an API-first ad serving platform that lets brands and publishers build\n  unified, fully customized ad systems supporting any ad format, any creative, and\n  multiple demand sources. Kevel exposes a Decision API for ad requests, a Management\n  API for campaign and creative operations, a Reporting API for performance analytics,\n  and a UserDB API for first-party audience and user data.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Ad Serving\n  - Advertising\n  - API-First\n  - Audience\n  - Monetization\n  - Reporting\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kevel/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kevel:decision-api\n    name: Kevel Decision API\n    description: >-\n      The Decision API enables ad requests without using\
  \ ad code. By posting to a\n      RESTful endpoint, Kevel's ad engine returns decision data and creative contents\n      for serving ads in your application across web, mobile, native, audio, video,\n      and CTV surfaces.\n    humanURL: https://dev.kevel.com/reference/request\n    tags:\n      - Ad Serving\n      - Decision\n      - Native Ads\n    properties:\n      - type: Documentation\n        url: https://dev.kevel.com/docs/native-ads-api-quickstart\n      - type: Reference\n        url: https://dev.kevel.com/reference/request\n  - aid: kevel:management-api\n    name: Kevel Management API\n    description: >-\n      The Management API provides programmatic access to manage advertisers, campaigns,\n      flights, ads, creatives, channels, sites, zones, and other platform resources.\n      It is the system-of-record API used to provision and operate the Kevel ad server.\n    humanURL: https://dev.kevel.com/docs/management-api-tutorial\n    tags:\n      - Campaigns\n      - Creatives\n\
  \      - Management\n    properties:\n      - type: Documentation\n        url: https://dev.kevel.com/docs/management-api-tutorial\n      - type: Reference\n        url: https://dev.kevel.com/reference/getting-started-with-the-management-api\n  - aid: kevel:reporting-api\n    name: Kevel Reporting API\n    description: >-\n      The Reporting API exposes ad serving performance data, allowing customers to\n      pull impressions, clicks, conversions, revenue, and other metrics by advertiser,\n      campaign, flight, ad, creative, site, zone, and date range for analytics and\n      finance workflows.\n    humanURL: https://dev.kevel.com/reference/reporting-overview\n    tags:\n      - Analytics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://dev.kevel.com/reference/reporting-overview\n  - aid: kevel:userdb-api\n    name: Kevel UserDB API\n    description: >-\n      The UserDB API provides first-party audience and user data management, enabling\n   \
  \   customers to read and write user keys, custom properties, interests, and audience\n      segment membership for targeting in the Decision API.\n    humanURL: https://dev.kevel.com/reference/userdb-overview\n    tags:\n      - Audience\n      - Targeting\n      - UserDB\n    properties:\n      - type: Documentation\n        url: https://dev.kevel.com/reference/userdb-overview\ncommon:\n  - type: Website\n    url: https://www.kevel.com\n    name: Kevel Website\n  - type: Portal\n    url: https://dev.kevel.com/\n    name: Kevel Developer Portal\n  - type: Documentation\n    url: https://dev.kevel.com/docs/understanding-kevel\n    name: Kevel Documentation\n  - type: GettingStarted\n    url: https://dev.kevel.com/reference/getting-started-with-kevel\n    name: Getting Started with Kevel\n  - type: Reference\n    url: https://dev.kevel.com/reference\n    name: Kevel API Reference\n  - type: SDKs\n    url: https://dev.kevel.com/docs/sdks\n    name: Kevel SDKs\n  - type: Blog\n    url: https://www.kevel.com/blog\n\
  \    name: Kevel Blog\n  - type: Pricing\n    url: https://www.kevel.com/pricing\n    name: Kevel Pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kevel/refs/heads/main/apis.yml
tags:
- Ad Serving
- Advertising
- API-First
- Audience
- Monetization
- Reporting
url: https://raw.githubusercontent.com/api-evangelist/kevel/refs/heads/main/apis.yml
use_cases: []
---
