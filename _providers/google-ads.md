---
api_count: 2
api_specs:
- filename: google-ads-api-openapi.yml
  format: yaml
  label: Google Ads API
  slug: google-ads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-ads/refs/heads/main/openapi/google-ads-api-openapi.yml
apis:
- description: RESTful API for managing Google Ads campaigns, ad groups, ads, keywords, and more.
  name: Google Ads API
  slug: google-ads-api
- description: JavaScript-based scripting interface for programmatically managing and querying Google Ads data directly in a browser-based IDE. Scripts enable automated changes to campaigns, ad groups, and reporting
  name: Google Ads Scripts
  slug: google-ads-scripts
common:
- title: ''
  type: Portal
  url: https://developers.google.com/google-ads/api
- title: ''
  type: Getting Started
  url: https://developers.google.com/google-ads/api/docs/first-call/overview
- title: ''
  type: Authentication
  url: https://developers.google.com/google-ads/api/docs/oauth/overview
- title: ''
  type: Terms of Service
  url: https://developers.google.com/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Status Page
  url: https://status.cloud.google.com/
- title: ''
  type: Blog
  url: https://ads-developers.googleblog.com/
- title: ''
  type: Support
  url: https://developers.google.com/google-ads/api/support
- title: ''
  type: SDKs
  url: https://developers.google.com/google-ads/api/docs/client-libs
- title: ''
  type: GitHub Organization
  url: https://github.com/googleads
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/google-ads-api
- title: ''
  type: Community
  url: https://groups.google.com/g/adwords-api
- title: ''
  type: Console
  url: https://ads.google.com/
- title: ''
  type: Sign Up
  url: https://ads.google.com/signup
- title: ''
  type: Developer Tools
  url: https://developers.google.com/google-ads/api/docs/developer-toolkit/ai-assistant
- title: ''
  type: JSONSchema
  url: json-schema/google-ads-campaign-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/google-ads-context.jsonld
created: '2024-01-01'
description: The Google Ads API is the modern programmatic interface to Google Ads and the next generation of the AdWords API. It enables developers to interact directly with the Google Ads platform, vastly increasing the efficiency of managing large or complex Google Ads accounts and campaigns.
features: []
image: https://www.gstatic.com/images/branding/product/1x/google_ads_64dp.png
integrations: []
jsonld:
- class_count: 70
  name: Google Ads Context
  property_count: 36
  slug: google-ads-context
layout: provider
modified: '2026-04-28'
name: Google Ads
skills: []
slug: google-ads
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-ads\nname: Google Ads\ndescription: >-\n  The Google Ads API is the modern programmatic interface to Google Ads and the\n  next generation of the AdWords API. It enables developers to interact directly\n  with the Google Ads platform, vastly increasing the efficiency of managing\n  large or complex Google Ads accounts and campaigns.\ntype: Index\nimage: https://www.gstatic.com/images/branding/product/1x/google_ads_64dp.png\nurl: https://raw.githubusercontent.com/api-evangelist/google-ads/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Advertising\n  - Campaign Management\n  - Digital Advertising\n  - Google\n  - Marketing\n  - PPC\napis:\n  - aid: google-ads:google-ads-api\n    name: Google Ads API\n    description: >-\n      RESTful API for managing Google Ads campaigns, ad groups, ads, keywords,\n      and more.\n    image: https://www.gstatic.com/images/branding/product/1x/google_ads_64dp.png\n\
  \    humanURL: https://developers.google.com/google-ads/api\n    baseURL: https://googleads.googleapis.com\n    tags:\n      - Advertising\n      - Analytics\n      - Campaigns\n      - Marketing\n      - PPC\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/google-ads/api/docs/start\n      - type: OpenAPI\n        url: openapi/google-ads-api-openapi.yml\n      - type: Authentication\n        url: https://developers.google.com/google-ads/api/docs/oauth/overview\n      - type: SDKs\n        url: https://developers.google.com/google-ads/api/docs/client-libs\n      - type: Migration Guide\n        url: https://developers.google.com/google-ads/api/docs/migration\n      - type: Best Practices\n        url: https://developers.google.com/google-ads/api/docs/best-practices\n      - type: Rate Limits\n        url: https://developers.google.com/google-ads/api/docs/rate-limits\n      - type: Release Notes\n        url: https://developers.google.com/google-ads/api/docs/release-notes\n\
  \      - type: Support\n        url: https://developers.google.com/google-ads/api/support\n      - type: Forum\n        url: https://groups.google.com/g/adwords-api\n      - type: Client Libraries\n        url: https://developers.google.com/google-ads/api/docs/client-libs\n      - type: Change Log\n        url: https://developers.google.com/google-ads/api/docs/release-notes\n      - type: Getting Started\n        url: https://developers.google.com/google-ads/api/docs/first-call/overview\n  - aid: google-ads:google-ads-scripts\n    name: Google Ads Scripts\n    description: >-\n      JavaScript-based scripting interface for programmatically managing and\n      querying Google Ads data directly in a browser-based IDE. Scripts enable\n      automated changes to campaigns, ad groups, and reporting without requiring\n      a full API integration.\n    image: https://www.gstatic.com/images/branding/product/1x/google_ads_64dp.png\n    humanURL: https://developers.google.com/google-ads/scripts/docs/start\n\
  \    baseURL: https://googleads.googleapis.com\n    tags:\n      - Automation\n      - Campaign Management\n      - JavaScript\n      - Scripts\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/google-ads/scripts/docs/start\n      - type: Getting Started\n        url: https://developers.google.com/google-ads/scripts/docs/getting-started\n      - type: Reference\n        url: https://developers.google.com/google-ads/scripts/docs/examples\ncommon:\n  - type: Portal\n    url: https://developers.google.com/google-ads/api\n  - type: Getting Started\n    url: https://developers.google.com/google-ads/api/docs/first-call/overview\n  - type: Authentication\n    url: https://developers.google.com/google-ads/api/docs/oauth/overview\n  - type: Terms of Service\n    url: https://developers.google.com/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Status Page\n    url: https://status.cloud.google.com/\n  - type: Blog\n\
  \    url: https://ads-developers.googleblog.com/\n  - type: Support\n    url: https://developers.google.com/google-ads/api/support\n  - type: SDKs\n    url: https://developers.google.com/google-ads/api/docs/client-libs\n  - type: GitHub Organization\n    url: https://github.com/googleads\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/google-ads-api\n  - type: Community\n    url: https://groups.google.com/g/adwords-api\n  - type: Console\n    url: https://ads.google.com/\n  - type: Sign Up\n    url: https://ads.google.com/signup\n  - type: Developer Tools\n    url: https://developers.google.com/google-ads/api/docs/developer-toolkit/ai-assistant\n  - type: JSONSchema\n    url: json-schema/google-ads-campaign-schema.json\n  - type: JSON-LD\n    url: json-ld/google-ads-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-ads/refs/heads/main/apis.yml
tags:
- Advertising
- Campaign Management
- Digital Advertising
- Google
- Marketing
- PPC
url: https://raw.githubusercontent.com/api-evangelist/google-ads/refs/heads/main/apis.yml
use_cases: []
---
