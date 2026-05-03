---
api_count: 9
api_specs:
- filename: posthog-openapi.yml
  format: yaml
  label: PostHog API
  slug: posthog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/posthog/refs/heads/main/openapi/posthog-openapi.yml
apis:
- description: The PostHog API is a single consolidated REST interface that exposes every PostHog capability available in the UI, including event capture, person and group profiles, cohorts, feature flags, experimen
  name: PostHog API
  slug: posthog
- description: The PostHog Capture API allows developers to send events, identify users, and set user or group properties from any server or client. It is the primary ingestion endpoint for sending analytics data to
  name: PostHog Capture API
  slug: capture-api
- description: The PostHog Query API provides programmatic access to run HogQL queries against your PostHog data. HogQL is PostHog's SQL-like query language that enables custom analytics queries, funnel analysis, re
  name: PostHog Query API
  slug: query-api
- description: The PostHog Persons API allows developers to retrieve, search, and manage person profiles in PostHog. It supports listing persons with filters, retrieving individual person details, viewing associated
  name: PostHog Persons API
  slug: persons-api
- description: The PostHog Feature Flags API enables developers to create, manage, and evaluate feature flags programmatically. It supports boolean and multivariate flags, percentage-based rollouts, user targeting w
  name: PostHog Feature Flags API
  slug: feature-flags-api
- description: The PostHog Experiments API provides programmatic management of A/B tests and experiments. It supports creating experiments with control and test variants, defining goal metrics, launching and stoppin
  name: PostHog Experiments API
  slug: experiments-api
- description: The PostHog Insights API allows developers to create, retrieve, and manage saved insights such as trends, funnels, retention charts, paths, and lifecycle analyses. It provides programmatic access to t
  name: PostHog Insights API
  slug: insights-api
- description: The PostHog Cohorts API enables developers to create and manage cohorts, which are groups of users defined by shared properties or behavioral patterns. Cohorts can be used for targeting feature flags,
  name: PostHog Cohorts API
  slug: cohorts-api
- description: 'The PostHog Annotations API allows developers to create and manage annotations that mark significant events on PostHog charts and dashboards. Annotations provide context for data changes by recording '
  name: PostHog Annotations API
  slug: annotations-api
common:
- title: ''
  type: Website
  url: https://posthog.com
- title: ''
  type: Documentation
  url: https://posthog.com/docs
- title: ''
  type: APIDocumentation
  url: https://posthog.com/docs/api
- title: ''
  type: GettingStarted
  url: https://posthog.com/docs/getting-started/install
- title: ''
  type: Blog
  url: https://posthog.com/blog
- title: ''
  type: Pricing
  url: https://posthog.com/pricing
- title: ''
  type: GitHub
  url: https://github.com/PostHog/posthog
- title: ''
  type: Login
  url: https://app.posthog.com/login
- title: ''
  type: Signup
  url: https://app.posthog.com/signup
- title: ''
  type: Support
  url: https://posthog.com/questions
- title: ''
  type: Changelog
  url: https://posthog.com/changelog
- title: ''
  type: SDKs
  url: https://posthog.com/docs/libraries
- title: ''
  type: SelfHosted
  url: https://posthog.com/docs/self-host
- title: ''
  type: StatusPage
  url: https://status.posthog.com
- title: ''
  type: Slack
  url: https://posthog.com/slack
- title: ''
  type: TermsOfService
  url: https://posthog.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://posthog.com/privacy
created: '2026-03-26'
description: PostHog is an open source product analytics platform that provides event tracking, session recording, feature flags, A/B testing, and user surveys in a single platform. It can be self-hosted or used as a cloud service, giving teams full control over their product data while providing comprehensive tools for understanding and improving user experiences.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: PostHog
skills: []
slug: posthog
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: posthog\nname: PostHog\ndescription: >-\n  PostHog is an open source product analytics platform that provides event\n  tracking, session recording, feature flags, A/B testing, and user surveys\n  in a single platform. It can be self-hosted or used as a cloud service,\n  giving teams full control over their product data while providing\n  comprehensive tools for understanding and improving user experiences.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - A/B Testing\n  - Analytics\n  - Feature Flags\n  - Open Source\n  - Product Analytics\n  - Session Recording\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/posthog/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: posthog:posthog\n    name: PostHog API\n    description: >-\n      The PostHog API is a single consolidated REST interface that exposes\n      every PostHog capability available\
  \ in the UI, including event capture,\n      person and group profiles, cohorts, feature flags, experiments, insights,\n      dashboards, annotations, sessions, surveys, web analytics, and HogQL\n      queries. It supports project-scoped and personal API key authentication\n      for both PostHog Cloud and self-hosted deployments.\n    humanURL: https://posthog.com/docs/api\n    baseURL: https://app.posthog.com/api\n    tags:\n      - Analytics\n      - Annotations\n      - Cohorts\n      - Dashboards\n      - Events\n      - Experimentation\n      - Feature Flags\n      - HogQL\n      - Insights\n      - Persons\n      - Product Analytics\n      - Surveys\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api\n      - type: GettingStarted\n        url: https://posthog.com/docs/api\n      - type: Authentication\n        url: https://posthog.com/docs/api#authentication\n      - type: OpenAPI\n        url: openapi/posthog-openapi.yml\n  - aid: posthog:capture-api\n\
  \    name: PostHog Capture API\n    description: >-\n      The PostHog Capture API allows developers to send events, identify users,\n      and set user or group properties from any server or client. It is the\n      primary ingestion endpoint for sending analytics data to PostHog and\n      supports batch event submission, feature flag evaluation, and alias\n      operations for identity resolution.\n    humanURL: https://posthog.com/docs/api/capture\n    tags:\n      - Analytics\n      - Events\n      - Ingestion\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/capture\n  - aid: posthog:query-api\n    name: PostHog Query API\n    description: >-\n      The PostHog Query API provides programmatic access to run HogQL queries\n      against your PostHog data. HogQL is PostHog's SQL-like query language\n      that enables custom analytics queries, funnel analysis, retention\n      analysis, and trend calculations. This API allows\
  \ developers to build\n      custom dashboards and reporting tools powered by PostHog data.\n    humanURL: https://posthog.com/docs/api/query\n    tags:\n      - Analytics\n      - HogQL\n      - Queries\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/query\n  - aid: posthog:persons-api\n    name: PostHog Persons API\n    description: >-\n      The PostHog Persons API allows developers to retrieve, search, and manage\n      person profiles in PostHog. It supports listing persons with filters,\n      retrieving individual person details, viewing associated events and\n      properties, and managing person data including deletions for privacy\n      compliance.\n    humanURL: https://posthog.com/docs/api/persons\n    tags:\n      - Analytics\n      - Identity\n      - Profiles\n      - Users\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/persons\n  - aid: posthog:feature-flags-api\n    name:\
  \ PostHog Feature Flags API\n    description: >-\n      The PostHog Feature Flags API enables developers to create, manage, and\n      evaluate feature flags programmatically. It supports boolean and multivariate\n      flags, percentage-based rollouts, user targeting with property filters,\n      and integration with PostHog's experimentation framework for A/B testing.\n    humanURL: https://posthog.com/docs/api/feature-flags\n    tags:\n      - A/B Testing\n      - Experimentation\n      - Feature Flags\n      - Rollouts\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/feature-flags\n  - aid: posthog:experiments-api\n    name: PostHog Experiments API\n    description: >-\n      The PostHog Experiments API provides programmatic management of A/B tests\n      and experiments. It supports creating experiments with control and test\n      variants, defining goal metrics, launching and stopping experiments, and\n      retrieving experiment results with\
  \ statistical significance calculations.\n    humanURL: https://posthog.com/docs/api/experiments\n    tags:\n      - A/B Testing\n      - Experimentation\n      - Metrics\n      - Variants\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/experiments\n  - aid: posthog:insights-api\n    name: PostHog Insights API\n    description: >-\n      The PostHog Insights API allows developers to create, retrieve, and manage\n      saved insights such as trends, funnels, retention charts, paths, and\n      lifecycle analyses. It provides programmatic access to the same analytics\n      visualizations available in the PostHog UI, enabling integration with\n      external dashboards and automated reporting workflows.\n    humanURL: https://posthog.com/docs/api/insights\n    tags:\n      - Analytics\n      - Dashboards\n      - Insights\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/insights\n  - aid:\
  \ posthog:cohorts-api\n    name: PostHog Cohorts API\n    description: >-\n      The PostHog Cohorts API enables developers to create and manage cohorts,\n      which are groups of users defined by shared properties or behavioral\n      patterns. Cohorts can be used for targeting feature flags, filtering\n      analytics queries, and segmenting experiment populations.\n    humanURL: https://posthog.com/docs/api/cohorts\n    tags:\n      - Analytics\n      - Cohorts\n      - Segmentation\n      - Users\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/cohorts\n  - aid: posthog:annotations-api\n    name: PostHog Annotations API\n    description: >-\n      The PostHog Annotations API allows developers to create and manage\n      annotations that mark significant events on PostHog charts and dashboards.\n      Annotations provide context for data changes by recording deployments,\n      marketing campaigns, incidents, and other events that may affect\
  \ metrics.\n    humanURL: https://posthog.com/docs/api/annotations\n    tags:\n      - Analytics\n      - Annotations\n      - Charts\n    properties:\n      - type: Documentation\n        url: https://posthog.com/docs/api/annotations\ncommon:\n  - type: Website\n    url: https://posthog.com\n  - type: Documentation\n    url: https://posthog.com/docs\n  - type: APIDocumentation\n    url: https://posthog.com/docs/api\n  - type: GettingStarted\n    url: https://posthog.com/docs/getting-started/install\n  - type: Blog\n    url: https://posthog.com/blog\n  - type: Pricing\n    url: https://posthog.com/pricing\n  - type: GitHub\n    url: https://github.com/PostHog/posthog\n  - type: Login\n    url: https://app.posthog.com/login\n  - type: Signup\n    url: https://app.posthog.com/signup\n  - type: Support\n    url: https://posthog.com/questions\n  - type: Changelog\n    url: https://posthog.com/changelog\n  - type: SDKs\n    url: https://posthog.com/docs/libraries\n  - type: SelfHosted\n   \
  \ url: https://posthog.com/docs/self-host\n  - type: StatusPage\n    url: https://status.posthog.com\n  - type: Slack\n    url: https://posthog.com/slack\n  - type: TermsOfService\n    url: https://posthog.com/terms\n  - type: PrivacyPolicy\n    url: https://posthog.com/privacy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/posthog/refs/heads/main/apis.yml
tags:
- A/B Testing
- Analytics
- Feature Flags
- Open Source
- Product Analytics
- Session Recording
url: https://raw.githubusercontent.com/api-evangelist/posthog/refs/heads/main/apis.yml
use_cases: []
---
