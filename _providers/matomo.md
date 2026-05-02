---
api_count: 5
apis:
- description: The Matomo Reporting API provides programmatic access to all analytics reports available in the Matomo interface. It exposes over 200 API methods organized into modules such as VisitsSummary, Actions,
  name: Matomo Reporting API
  slug: reporting-api
- description: The Matomo Tracking API allows developers to send tracking data to Matomo from any server-side application, mobile app, or IoT device via HTTP requests. It supports recording pageviews, custom events,
  name: Matomo Tracking API
  slug: tracking-api
- description: The Matomo Live API provides real-time access to visitor data including the most recent visits, visitor profiles, and live counters showing current visitors on the site. It enables developers to build
  name: Matomo Live API
  slug: live-api
- description: The Matomo Goals API allows developers to manage and retrieve data about conversion goals. It supports creating, updating, and deleting goals, as well as retrieving goal conversion metrics, revenue da
  name: Matomo Goals API
  slug: goals-api
- description: The Matomo Segments API enables developers to create and manage saved segments for filtering analytics data. Segments allow filtering visits and actions by any combination of visitor properties, behav
  name: Matomo Segments API
  slug: segments-api
common:
- title: ''
  type: Website
  url: https://matomo.org
- title: ''
  type: Documentation
  url: https://developer.matomo.org
- title: ''
  type: APIDocumentation
  url: https://developer.matomo.org/api-reference/reporting-api
- title: ''
  type: GettingStarted
  url: https://developer.matomo.org/guides/getting-started-part-1
- title: ''
  type: Blog
  url: https://matomo.org/blog
- title: ''
  type: Pricing
  url: https://matomo.org/pricing
- title: ''
  type: GitHub
  url: https://github.com/matomo-org/matomo
- title: ''
  type: Login
  url: https://matomo.org/login
- title: ''
  type: Signup
  url: https://matomo.org/start-free-analytics-trial
- title: ''
  type: Support
  url: https://matomo.org/support
- title: ''
  type: Forum
  url: https://forum.matomo.org
- title: ''
  type: Marketplace
  url: https://plugins.matomo.org
- title: ''
  type: SelfHosted
  url: https://matomo.org/matomo-on-premise
- title: ''
  type: Changelog
  url: https://matomo.org/changelog
- title: ''
  type: SDKs
  url: https://developer.matomo.org/api-reference/tracking-api-clients
- title: ''
  type: TermsOfService
  url: https://matomo.org/terms
- title: ''
  type: PrivacyPolicy
  url: https://matomo.org/privacy-policy
created: '2026-03-26'
description: Matomo is an open source web analytics platform that provides comprehensive website and application usage analytics with full data ownership. Formerly known as Piwik, it offers an alternative to Google Analytics with on-premise or cloud hosting options, ensuring complete control over analytics data and compliance with privacy regulations including GDPR.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Matomo
skills: []
slug: matomo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: matomo\nname: Matomo\ndescription: >-\n  Matomo is an open source web analytics platform that provides comprehensive\n  website and application usage analytics with full data ownership. Formerly\n  known as Piwik, it offers an alternative to Google Analytics with on-premise\n  or cloud hosting options, ensuring complete control over analytics data and\n  compliance with privacy regulations including GDPR.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Data Ownership\n  - Open Source\n  - Privacy\n  - Self-Hosted\n  - Web Analytics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/matomo/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: matomo:reporting-api\n    name: Matomo Reporting API\n    description: >-\n      The Matomo Reporting API provides programmatic access to all analytics\n      reports available in the\
  \ Matomo interface. It exposes over 200 API\n      methods organized into modules such as VisitsSummary, Actions,\n      Referrers, UserCountry, DevicesDetection, Goals, and more. Each\n      module provides methods to retrieve metrics, dimensions, and\n      segmented data for building custom dashboards and reporting tools.\n    humanURL: https://developer.matomo.org/api-reference/reporting-api\n    tags:\n      - Analytics\n      - Dashboards\n      - Metrics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developer.matomo.org/api-reference/reporting-api\n      - type: GettingStarted\n        url: https://developer.matomo.org/api-reference/reporting-api-introduction\n  - aid: matomo:tracking-api\n    name: Matomo Tracking API\n    description: >-\n      The Matomo Tracking API allows developers to send tracking data to Matomo\n      from any server-side application, mobile app, or IoT device via HTTP\n      requests. It supports recording pageviews,\
  \ custom events, e-commerce\n      transactions, content interactions, site search queries, and custom\n      dimensions. The API also supports bulk tracking for sending multiple\n      events in a single request.\n    humanURL: https://developer.matomo.org/api-reference/tracking-api\n    tags:\n      - Analytics\n      - Events\n      - Server-Side\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://developer.matomo.org/api-reference/tracking-api\n  - aid: matomo:live-api\n    name: Matomo Live API\n    description: >-\n      The Matomo Live API provides real-time access to visitor data including\n      the most recent visits, visitor profiles, and live counters showing\n      current visitors on the site. It enables developers to build real-time\n      dashboards, visitor activity feeds, and monitoring tools that display\n      up-to-the-minute analytics data.\n    humanURL: https://developer.matomo.org/api-reference/reporting-api#Live\n    tags:\n \
  \     - Analytics\n      - Live Data\n      - Real-Time\n      - Visitors\n    properties:\n      - type: Documentation\n        url: https://developer.matomo.org/api-reference/reporting-api#Live\n  - aid: matomo:goals-api\n    name: Matomo Goals API\n    description: >-\n      The Matomo Goals API allows developers to manage and retrieve data about\n      conversion goals. It supports creating, updating, and deleting goals,\n      as well as retrieving goal conversion metrics, revenue data, and\n      conversion rates segmented by various dimensions such as referrer,\n      country, and device type.\n    humanURL: https://developer.matomo.org/api-reference/reporting-api#Goals\n    tags:\n      - Analytics\n      - Conversions\n      - Goals\n      - Revenue\n    properties:\n      - type: Documentation\n        url: https://developer.matomo.org/api-reference/reporting-api#Goals\n  - aid: matomo:segments-api\n    name: Matomo Segments API\n    description: >-\n      The Matomo Segments\
  \ API enables developers to create and manage saved\n      segments for filtering analytics data. Segments allow filtering visits\n      and actions by any combination of visitor properties, behavior patterns,\n      and custom dimensions. Any Reporting API method can accept a segment\n      parameter to return data for a specific subset of visitors.\n    humanURL: https://developer.matomo.org/api-reference/reporting-api-segmentation\n    tags:\n      - Analytics\n      - Filters\n      - Segmentation\n      - Visitors\n    properties:\n      - type: Documentation\n        url: https://developer.matomo.org/api-reference/reporting-api-segmentation\ncommon:\n  - type: Website\n    url: https://matomo.org\n  - type: Documentation\n    url: https://developer.matomo.org\n  - type: APIDocumentation\n    url: https://developer.matomo.org/api-reference/reporting-api\n  - type: GettingStarted\n    url: https://developer.matomo.org/guides/getting-started-part-1\n  - type: Blog\n    url: https://matomo.org/blog\n\
  \  - type: Pricing\n    url: https://matomo.org/pricing\n  - type: GitHub\n    url: https://github.com/matomo-org/matomo\n  - type: Login\n    url: https://matomo.org/login\n  - type: Signup\n    url: https://matomo.org/start-free-analytics-trial\n  - type: Support\n    url: https://matomo.org/support\n  - type: Forum\n    url: https://forum.matomo.org\n  - type: Marketplace\n    url: https://plugins.matomo.org\n  - type: SelfHosted\n    url: https://matomo.org/matomo-on-premise\n  - type: Changelog\n    url: https://matomo.org/changelog\n  - type: SDKs\n    url: https://developer.matomo.org/api-reference/tracking-api-clients\n  - type: TermsOfService\n    url: https://matomo.org/terms\n  - type: PrivacyPolicy\n    url: https://matomo.org/privacy-policy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/matomo/refs/heads/main/apis.yml
tags:
- Analytics
- Data Ownership
- Open Source
- Privacy
- Self-Hosted
- Web Analytics
url: https://raw.githubusercontent.com/api-evangelist/matomo/refs/heads/main/apis.yml
use_cases: []
---
