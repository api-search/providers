---
api_count: 3
api_specs:
- filename: rest
  format: yaml
  label: Google Analytics Data API
  slug: google-analytics-data-api
  spec_type: OpenAPI
  url: https://analyticsdata.googleapis.com/$discovery/rest?version=v1beta
- filename: rest
  format: yaml
  label: Google Analytics Admin API
  slug: google-analytics-admin-api
  spec_type: OpenAPI
  url: https://analyticsadmin.googleapis.com/$discovery/rest?version=v1beta
apis:
- description: The Google Analytics Data API v1 provides programmatic methods to access report data in Google Analytics 4 (GA4) properties.
  name: Google Analytics Data API
  slug: google-analytics-data-api
- description: The Google Analytics Admin API allows programmatic configuration of Google Analytics 4 properties and data streams.
  name: Google Analytics Admin API
  slug: google-analytics-admin-api
- description: The Measurement Protocol for Google Analytics 4 allows developers to send events directly to Google Analytics servers for web and app streams.
  name: Google Analytics Measurement Protocol
  slug: google-analytics-measurement-protocol
common:
- title: ''
  type: Portal
  url: https://developers.google.com/analytics
- title: ''
  type: Console
  url: https://analytics.google.com/
- title: ''
  type: Authentication
  url: https://developers.google.com/analytics/devguides/reporting/data/v1/basics#authentication
- title: ''
  type: Terms of Service
  url: https://developers.google.com/analytics/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Support
  url: https://support.google.com/analytics
- title: ''
  type: SDKs
  url: https://developers.google.com/analytics/devguides/reporting/data/v1/client-libraries
- title: ''
  type: Status
  url: https://status.cloud.google.com/
- title: ''
  type: Pricing
  url: https://marketingplatform.google.com/about/analytics/compare/
created: '2024-01-01'
description: Google Analytics 4 (GA4) is the latest generation of Analytics that collects event-based data from websites and apps. It provides intelligent insights and predictive analytics powered by machine learning.
features: []
image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_analytics.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Analytics 4
skills: []
slug: google-analytics-4
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-analytics-4\nname: Google Analytics 4\ndescription: Google Analytics 4 (GA4) is the latest generation of Analytics that collects event-based data from websites and apps. It provides intelligent insights and predictive analytics powered by machine learning.\ntype: Index\nimage: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_analytics.svg\nurl: https://raw.githubusercontent.com/api-evangelist/google-analytics-4/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Data Collection\n  - Marketing\n  - Measurement\n  - Mobile Analytics\n  - Reporting\n  - Web Analytics\napis:\n  - aid: google-analytics-4:google-analytics-data-api\n    name: Google Analytics Data API\n    description: The Google Analytics Data API v1 provides programmatic methods to access report data in Google Analytics 4 (GA4) properties.\n    image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_analytics.svg\n\
  \    humanURL: https://developers.google.com/analytics/devguides/reporting/data/v1\n    baseURL: https://analyticsdata.googleapis.com\n    tags:\n      - Data\n      - Dimensions\n      - Metrics\n      - Reports\n    properties:\n      - type: OpenAPI\n        url: https://analyticsdata.googleapis.com/$discovery/rest?version=v1beta\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1\n      - type: Authentication\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1/basics#authentication\n      - type: Quickstart\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries\n      - type: Rate Limits\n        url: https://developers.google.com/analytics/devguides/reporting/data/v1/quotas\n  - aid: google-analytics-4:google-analytics-admin-api\n    name: Google Analytics Admin API\n    description: The Google Analytics Admin API allows programmatic configuration\
  \ of Google Analytics 4 properties and data streams.\n    image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_analytics.svg\n    humanURL: https://developers.google.com/analytics/devguides/config/admin/v1\n    baseURL: https://analyticsadmin.googleapis.com\n    tags:\n      - Administration\n      - Configuration\n      - Data Streams\n      - Properties\n    properties:\n      - type: OpenAPI\n        url: https://analyticsadmin.googleapis.com/$discovery/rest?version=v1beta\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/config/admin/v1\n      - type: Authentication\n        url: https://developers.google.com/analytics/devguides/config/admin/v1/rest\n      - type: Quickstart\n        url: https://developers.google.com/analytics/devguides/config/admin/v1/quickstart-client-libraries\n  - aid: google-analytics-4:google-analytics-measurement-protocol\n    name: Google Analytics Measurement Protocol\n    description: The Measurement\
  \ Protocol for Google Analytics 4 allows developers to send events directly to Google Analytics servers for web and app streams.\n    image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_analytics.svg\n    humanURL: https://developers.google.com/analytics/devguides/collection/protocol/ga4\n    baseURL: https://www.google-analytics.com/mp/collect\n    tags:\n      - Data Collection\n      - Events\n      - Server-Side\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4\n      - type: Reference\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/reference\n      - type: Validation\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/validating-events\n      - type: Events\n        url: https://developers.google.com/analytics/devguides/collection/protocol/ga4/sending-events\ncommon:\n  - type: Portal\n    url:\
  \ https://developers.google.com/analytics\n  - type: Console\n    url: https://analytics.google.com/\n  - type: Authentication\n    url: https://developers.google.com/analytics/devguides/reporting/data/v1/basics#authentication\n  - type: Terms of Service\n    url: https://developers.google.com/analytics/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Support\n    url: https://support.google.com/analytics\n  - type: SDKs\n    url: https://developers.google.com/analytics/devguides/reporting/data/v1/client-libraries\n  - type: Status\n    url: https://status.cloud.google.com/\n  - type: Pricing\n    url: https://marketingplatform.google.com/about/analytics/compare/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-analytics-4/refs/heads/main/apis.yml
tags:
- Analytics
- Data Collection
- Marketing
- Measurement
- Mobile Analytics
- Reporting
- Web Analytics
url: https://raw.githubusercontent.com/api-evangelist/google-analytics-4/refs/heads/main/apis.yml
use_cases: []
---
