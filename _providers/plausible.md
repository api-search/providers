---
api_count: 3
api_specs:
- filename: plausible-stats-openapi.yml
  format: yaml
  label: Plausible Stats API
  slug: stats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/openapi/plausible-stats-openapi.yml
- filename: plausible-events-openapi.yml
  format: yaml
  label: Plausible Events API
  slug: events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/openapi/plausible-events-openapi.yml
- filename: plausible-sites-openapi.yml
  format: yaml
  label: Plausible Sites API
  slug: sites-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/openapi/plausible-sites-openapi.yml
apis:
- description: The Plausible Stats API provides programmatic access to website analytics data including aggregate metrics, time-series data, and breakdowns by various dimensions such as pages, sources, countries, de
  name: Plausible Stats API
  slug: stats-api
- description: The Plausible Events API allows developers to send pageview and custom events to Plausible from server-side applications, mobile apps, or any environment where the standard JavaScript snippet cannot b
  name: Plausible Events API
  slug: events-api
- description: The Plausible Sites API enables developers to programmatically manage sites within their Plausible account. It supports creating new sites, deleting existing sites, retrieving site information, and ma
  name: Plausible Sites API
  slug: sites-api
common:
- title: ''
  type: Website
  url: https://plausible.io
- title: ''
  type: Documentation
  url: https://plausible.io/docs
- title: ''
  type: APIDocumentation
  url: https://plausible.io/docs/stats-api
- title: ''
  type: GettingStarted
  url: https://plausible.io/docs/add-website
- title: ''
  type: Blog
  url: https://plausible.io/blog
- title: ''
  type: Pricing
  url: https://plausible.io/pricing
- title: ''
  type: GitHub
  url: https://github.com/plausible/analytics
- title: ''
  type: Login
  url: https://plausible.io/login
- title: ''
  type: Signup
  url: https://plausible.io/register
- title: ''
  type: Support
  url: https://plausible.io/contact
- title: ''
  type: SelfHosted
  url: https://plausible.io/self-hosted-web-analytics
- title: ''
  type: Changelog
  url: https://github.com/plausible/analytics/releases
- title: ''
  type: TermsOfService
  url: https://plausible.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://plausible.io/privacy
- title: ''
  type: DataPolicy
  url: https://plausible.io/data-policy
created: '2026-03-26'
description: Plausible is an open source, privacy-friendly web analytics platform designed as a lightweight alternative to Google Analytics. It provides essential website traffic metrics without using cookies or collecting personal data, making it compliant with GDPR, CCPA, and other privacy regulations out of the box. It can be self-hosted or used as a cloud service.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Plausible
skills: []
slug: plausible
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: plausible\nname: Plausible\ndescription: >-\n  Plausible is an open source, privacy-friendly web analytics platform designed\n  as a lightweight alternative to Google Analytics. It provides essential website\n  traffic metrics without using cookies or collecting personal data, making it\n  compliant with GDPR, CCPA, and other privacy regulations out of the box. It\n  can be self-hosted or used as a cloud service.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Cookie-Free\n  - GDPR\n  - Open Source\n  - Privacy\n  - Web Analytics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: plausible:stats-api\n    name: Plausible Stats API\n    description: >-\n      The Plausible Stats API provides programmatic access to website analytics\n      data including aggregate\
  \ metrics, time-series data, and breakdowns by\n      various dimensions such as pages, sources, countries, devices, and\n      browsers. It enables developers to retrieve visitor counts, pageviews,\n      bounce rates, visit durations, and custom event data for building\n      external dashboards and integrating analytics into other applications.\n    humanURL: https://plausible.io/docs/stats-api\n    baseURL: https://plausible.io/api/v2\n    tags:\n      - Analytics\n      - Metrics\n      - Reporting\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://plausible.io/docs/stats-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/openapi/plausible-stats-openapi.yml\n  - aid: plausible:events-api\n    name: Plausible Events API\n    description: >-\n      The Plausible Events API allows developers to send pageview and custom\n      events to Plausible from server-side applications,\
  \ mobile apps, or\n      any environment where the standard JavaScript snippet cannot be used.\n      It supports recording pageviews, custom events with properties, and\n      revenue tracking data while maintaining Plausible's privacy-first\n      approach.\n    humanURL: https://plausible.io/docs/events-api\n    baseURL: https://plausible.io/api\n    tags:\n      - Analytics\n      - Events\n      - Pageviews\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://plausible.io/docs/events-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/openapi/plausible-events-openapi.yml\n  - aid: plausible:sites-api\n    name: Plausible Sites API\n    description: >-\n      The Plausible Sites API enables developers to programmatically manage\n      sites within their Plausible account. It supports creating new sites,\n      deleting existing sites, retrieving site information, and managing\n\
  \      shared links and goals. This API is useful for agencies and platforms\n      that need to automate site provisioning and configuration.\n    humanURL: https://plausible.io/docs/sites-api\n    baseURL: https://plausible.io/api/v1/sites\n    tags:\n      - Analytics\n      - Management\n      - Provisioning\n      - Sites\n    properties:\n      - type: Documentation\n        url: https://plausible.io/docs/sites-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/openapi/plausible-sites-openapi.yml\ncommon:\n  - type: Website\n    url: https://plausible.io\n  - type: Documentation\n    url: https://plausible.io/docs\n  - type: APIDocumentation\n    url: https://plausible.io/docs/stats-api\n  - type: GettingStarted\n    url: https://plausible.io/docs/add-website\n  - type: Blog\n    url: https://plausible.io/blog\n  - type: Pricing\n    url: https://plausible.io/pricing\n  - type: GitHub\n    url: https://github.com/plausible/analytics\n\
  \  - type: Login\n    url: https://plausible.io/login\n  - type: Signup\n    url: https://plausible.io/register\n  - type: Support\n    url: https://plausible.io/contact\n  - type: SelfHosted\n    url: https://plausible.io/self-hosted-web-analytics\n  - type: Changelog\n    url: https://github.com/plausible/analytics/releases\n  - type: TermsOfService\n    url: https://plausible.io/terms\n  - type: PrivacyPolicy\n    url: https://plausible.io/privacy\n  - type: DataPolicy\n    url: https://plausible.io/data-policy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/apis.yml
tags:
- Analytics
- Cookie-Free
- GDPR
- Open Source
- Privacy
- Web Analytics
url: https://raw.githubusercontent.com/api-evangelist/plausible/refs/heads/main/apis.yml
use_cases: []
---
