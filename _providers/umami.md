---
api_count: 1
api_specs:
- filename: umami-openapi.yml
  format: yaml
  label: Umami API
  slug: umami-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/umami/refs/heads/main/openapi/umami-openapi.yml
apis:
- description: The Umami API provides programmatic access to website analytics data including pageviews, sessions, events, and metrics, allowing developers to collect tracking data and retrieve analytics reports. Se
  name: Umami API
  slug: umami-api
capabilities:
- description: Web analytics workflow for tracking website performance, visitor behavior, and real-time data using Umami's privacy-first analytics platform.
  name: Umami Web Analytics
  slug: web-analytics
common:
- title: ''
  type: Website
  url: https://umami.is
- title: ''
  type: Documentation
  url: https://umami.is/docs
- title: ''
  type: Blog
  url: https://umami.is/blog
- title: ''
  type: Pricing
  url: https://umami.is/pricing
- title: ''
  type: GitHub
  url: https://github.com/umami-software/umami
- title: ''
  type: Login
  url: https://cloud.umami.is
- title: ''
  type: Signup
  url: https://cloud.umami.is
- title: ''
  type: SelfHosting
  url: https://umami.is/docs/install
- title: ''
  type: Support
  url: https://umami.is/docs/support
- title: ''
  type: SpectralRules
  url: rules/umami-spectral-rules.yml
- title: Web Analytics
  type: NaftikoCapability
  url: capabilities/web-analytics.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/umami-vocabulary.yaml
created: '2026-03-26'
description: Umami is an open source, privacy-first web analytics platform that provides website traffic insights without cookies or personal data collection, serving as a simple and fast alternative to Google Analytics. The Umami API provides full programmatic access to analytics data, website management, session tracking, event data, and team collaboration features for both self-hosted and cloud instances.
features:
- description: Tracks website traffic without cookies or personal data, fully GDPR compliant without consent banners.
  name: Privacy-First Analytics
- description: Live visitor counts and real-time pageview tracking for immediate traffic insights.
  name: Real-Time Data
- description: Track custom user interactions and conversions with a simple JavaScript API.
  name: Custom Events
- description: Share analytics access across teams with role-based access control.
  name: Team Collaboration
- description: Deploy on your own infrastructure for complete data ownership and control.
  name: Self-Hosting Support
- description: MIT-licensed open source software with active community development and full transparency.
  name: Open Source
- description: Manage and analyze multiple websites from a single Umami instance.
  name: Multi-Site Support
- description: Full REST API for programmatic access to all analytics data and management functions.
  name: API Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: First-class integration with Next.js via the @umami/nextjs package for page view tracking.
  name: Next.js
- description: Track WordPress sites by adding the Umami tracking script via plugin or manual installation.
  name: WordPress
- description: Deploy Umami on Vercel with a one-click deployment for managed self-hosting.
  name: Vercel
- description: Run Umami in any environment using the official Docker container image.
  name: Docker
- description: Deploy tracking scripts behind Cloudflare for performance and abuse prevention.
  name: Cloudflare
jsonld:
- class_count: 0
  name: Umami Context
  property_count: 0
  slug: umami-context
layout: provider
modified: '2026-05-03'
name: Umami
rules:
- name: Umami API Rules
  rule_count: 31
  severity_counts:
    error: 13
    hint: 0
    info: 7
    warn: 11
  slug: umami-spectral-rules
skills: []
slug: umami
solutions:
- description: Hosted Umami instance at cloud.umami.is with managed infrastructure and API key authentication.
  name: Umami Cloud
- description: Run your own Umami instance on any infrastructure with full data ownership and JWT authentication.
  name: Umami Self-Hosted
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: umami\nname: Umami\ndescription: >-\n  Umami is an open source, privacy-first web analytics platform that provides\n  website traffic insights without cookies or personal data collection, serving\n  as a simple and fast alternative to Google Analytics. The Umami API provides\n  full programmatic access to analytics data, website management, session tracking,\n  event data, and team collaboration features for both self-hosted and cloud instances.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cookieless Tracking\n  - Open Source\n  - Privacy\n  - Web Analytics\n  - Website Analytics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/umami/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: umami:umami-api\n    name: Umami API\n    description: >-\n      The Umami API provides programmatic access to website analytics data\n      including\
  \ pageviews, sessions, events, and metrics, allowing developers\n      to collect tracking data and retrieve analytics reports. Self-hosted\n      instances use JWT bearer tokens; Umami Cloud uses API key authentication.\n    humanURL: https://umami.is\n    baseURL: https://api.umami.is\n    tags:\n      - Open Source\n      - Privacy\n      - Tracking API\n      - Web Analytics\n    properties:\n      - type: Documentation\n        url: https://umami.is/docs\n      - type: GettingStarted\n        url: https://umami.is/docs/getting-started\n      - type: APIDocumentation\n        url: https://umami.is/docs/api\n      - type: GitHubOrg\n        url: https://github.com/umami-software/umami\n      - type: OpenAPI\n        url: openapi/umami-openapi.yml\n      - type: JSONSchema\n        url: json-schema/umami-website-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-website-list-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-website-request-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/umami-website-stats-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-pageview-data-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-metric-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-active-visitors-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-session-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-session-list-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-session-stats-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-user-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-user-request-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-team-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-team-list-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-team-member-schema.json\n      - type: JSONSchema\n \
  \       url: json-schema/umami-team-request-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-login-request-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-login-response-schema.json\n      - type: JSONSchema\n        url: json-schema/umami-ok-response-schema.json\n      - type: JSONStructure\n        url: json-structure/umami-website-structure.json\n      - type: JSONStructure\n        url: json-structure/umami-website-list-structure.json\n      - type: JSONStructure\n        url: json-structure/umami-website-stats-structure.json\n      - type: JSONStructure\n        url: json-structure/umami-session-structure.json\n      - type: JSONStructure\n        url: json-structure/umami-session-list-structure.json\n      - type: JSONStructure\n        url: json-structure/umami-metric-structure.json\n      - type: JSONStructure\n        url: json-structure/umami-user-structure.json\n      - type: JSONStructure\n        url: json-structure/umami-team-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/umami-team-member-structure.json\n      - type: JSONLDContext\n        url: json-ld/umami-context.jsonld\n      - type: Example\n        url: examples/umami-website-example.json\n      - type: Example\n        url: examples/umami-website-stats-example.json\n      - type: Example\n        url: examples/umami-pageview-data-example.json\n      - type: Example\n        url: examples/umami-metric-example.json\n      - type: Example\n        url: examples/umami-session-example.json\n      - type: Example\n        url: examples/umami-session-stats-example.json\n      - type: Example\n        url: examples/umami-user-example.json\n      - type: Example\n        url: examples/umami-team-example.json\n      - type: Example\n        url: examples/umami-active-visitors-example.json\ncommon:\n  - type: Website\n    url: https://umami.is\n  - type: Documentation\n    url: https://umami.is/docs\n  - type: Blog\n    url: https://umami.is/blog\n\
  \  - type: Pricing\n    url: https://umami.is/pricing\n  - type: GitHub\n    url: https://github.com/umami-software/umami\n  - type: Login\n    url: https://cloud.umami.is\n  - type: Signup\n    url: https://cloud.umami.is\n  - type: SelfHosting\n    url: https://umami.is/docs/install\n  - type: Support\n    url: https://umami.is/docs/support\n  - type: SpectralRules\n    url: rules/umami-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/web-analytics.yaml\n    title: Web Analytics\n  - type: Vocabulary\n    url: vocabulary/umami-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Privacy-First Analytics\n        description: Tracks website traffic without cookies or personal data, fully GDPR compliant without consent banners.\n      - name: Real-Time Data\n        description: Live visitor counts and real-time pageview tracking for immediate traffic insights.\n      - name: Custom Events\n        description: Track custom user interactions and conversions\
  \ with a simple JavaScript API.\n      - name: Team Collaboration\n        description: Share analytics access across teams with role-based access control.\n      - name: Self-Hosting Support\n        description: Deploy on your own infrastructure for complete data ownership and control.\n      - name: Open Source\n        description: MIT-licensed open source software with active community development and full transparency.\n      - name: Multi-Site Support\n        description: Manage and analyze multiple websites from a single Umami instance.\n      - name: API Access\n        description: Full REST API for programmatic access to all analytics data and management functions.\n  - type: UseCases\n    data:\n      - name: Website Performance Monitoring\n        description: Track pageviews, unique visitors, bounce rates, and session duration for website optimization.\n      - name: Privacy-Compliant Analytics\n        description: Replace Google Analytics with a cookieless solution that\
  \ requires no consent banners under GDPR.\n      - name: Marketing Analytics\n        description: Analyze traffic sources, referrers, and UTM campaign data to measure marketing effectiveness.\n      - name: Custom Event Tracking\n        description: Track button clicks, form submissions, and custom conversions using the Umami event API.\n      - name: Developer Dashboards\n        description: Build custom analytics dashboards using the REST API to display site metrics in your own apps.\n      - name: Multi-Tenant Analytics\n        description: Provide analytics access to multiple clients or teams with shared infrastructure and access controls.\n  - type: Integrations\n    data:\n      - name: Next.js\n        description: First-class integration with Next.js via the @umami/nextjs package for page view tracking.\n      - name: WordPress\n        description: Track WordPress sites by adding the Umami tracking script via plugin or manual installation.\n      - name: Vercel\n        description:\
  \ Deploy Umami on Vercel with a one-click deployment for managed self-hosting.\n      - name: Docker\n        description: Run Umami in any environment using the official Docker container image.\n      - name: Cloudflare\n        description: Deploy tracking scripts behind Cloudflare for performance and abuse prevention.\n  - type: Solutions\n    data:\n      - name: Umami Cloud\n        description: Hosted Umami instance at cloud.umami.is with managed infrastructure and API key authentication.\n      - name: Umami Self-Hosted\n        description: Run your own Umami instance on any infrastructure with full data ownership and JWT authentication.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/umami/refs/heads/main/apis.yml
tags:
- Cookieless Tracking
- Open Source
- Privacy
- Web Analytics
- Website Analytics
url: https://raw.githubusercontent.com/api-evangelist/umami/refs/heads/main/apis.yml
use_cases:
- description: Track pageviews, unique visitors, bounce rates, and session duration for website optimization.
  name: Website Performance Monitoring
- description: Replace Google Analytics with a cookieless solution that requires no consent banners under GDPR.
  name: Privacy-Compliant Analytics
- description: Analyze traffic sources, referrers, and UTM campaign data to measure marketing effectiveness.
  name: Marketing Analytics
- description: Track button clicks, form submissions, and custom conversions using the Umami event API.
  name: Custom Event Tracking
- description: Build custom analytics dashboards using the REST API to display site metrics in your own apps.
  name: Developer Dashboards
- description: Provide analytics access to multiple clients or teams with shared infrastructure and access controls.
  name: Multi-Tenant Analytics
---
