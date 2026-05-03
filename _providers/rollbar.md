---
api_count: 5
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Rollbar REST API
  slug: rollbar-rest-api
  spec_type: OpenAPI
  url: https://explorer.docs.rollbar.com/
- filename: rollbar-deployment-api-openapi.yml
  format: yaml
  label: Rollbar Deployment API
  slug: rollbar-deployment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/openapi/rollbar-deployment-api-openapi.yml
- filename: rollbar-metrics-api-openapi.yml
  format: yaml
  label: Rollbar Metrics API
  slug: rollbar-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/openapi/rollbar-metrics-api-openapi.yml
- filename: rollbar-rql-api-openapi.yml
  format: yaml
  label: Rollbar RQL API
  slug: rollbar-rql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/openapi/rollbar-rql-api-openapi.yml
- filename: rollbar-webhooks-asyncapi.yml
  format: yaml
  label: Rollbar Webhooks
  slug: rollbar-webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/asyncapi/rollbar-webhooks-asyncapi.yml
apis:
- description: 'The Rollbar REST API provides programmatic access to the Rollbar error tracking and monitoring platform. Manage projects, items, occurrences, deploys, teams, users, invites, notifications, and source '
  name: Rollbar REST API
  slug: rollbar-rest-api
- description: 'The Rollbar Deployment API allows developers to notify Rollbar of application deployments and releases. By reporting deploys, teams can correlate error spikes with specific releases, track deployment '
  name: Rollbar Deployment API
  slug: rollbar-deployment-api
- description: The Rollbar Metrics API is part of Rollbar Analyze and provides programmatic access to metrics data for error tracking analysis and discovery. Enables developers to query resolution time metrics, occu
  name: Rollbar Metrics API
  slug: rollbar-metrics-api
- description: The Rollbar RQL (Rollbar Query Language) API provides a SQL-like interface for querying error and deployment data stored in Rollbar. Supports SELECT queries against item_occurrence and deploy tables f
  name: Rollbar RQL API
  slug: rollbar-rql-api
- description: Rollbar supports outbound webhook notifications for real-time event-driven integrations. Webhooks deliver payload data when errors occur, items are resolved, or deployment events happen, enabling inte
  name: Rollbar Webhooks
  slug: rollbar-webhooks
asyncapis:
- description: Rollbar's webhook notification system delivers real-time event notifications to configured endpoints when errors, deployments, and other significant events occur. Webhooks are triggered based on confi
  name: Rollbar Webhook Events
  slug: rollbar-webhooks-asyncapi
capabilities:
- description: Unified workflow capability for error monitoring, incident triage, and deployment correlation using Rollbar REST and RQL APIs. Enables engineering teams and on-call engineers to investigate errors, qu
  name: Rollbar Error Monitoring
  slug: error-monitoring
common:
- title: ''
  type: Website
  url: https://rollbar.com/
- title: ''
  type: Documentation
  url: https://docs.rollbar.com/
- title: ''
  type: Documentation
  url: https://docs.rollbar.com/reference/getting-started-1
- title: ''
  type: Portal
  url: https://explorer.docs.rollbar.com/
- title: ''
  type: Pricing
  url: https://rollbar.com/pricing/
- title: ''
  type: GitHubOrganization
  url: https://github.com/rollbar
- title: ''
  type: TermsOfService
  url: https://rollbar.com/terms/
- title: ''
  type: PrivacyPolicy
  url: https://rollbar.com/privacy/
- title: ''
  type: Support
  url: https://rollbar.com/support/
- title: ''
  type: OpenAPI
  url: openapi/rollbar-rest-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/rollbar-deployment-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/rollbar-metrics-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/rollbar-rql-api-openapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/rollbar-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/rollbar-item-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rollbar-occurrence-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rollbar-deploy-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rollbar-webhook-payload-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/rollbar-context.jsonld
created: '2026-05-02'
description: Rollbar is a real-time error tracking and monitoring platform for software teams. It automatically captures exceptions and errors from web, mobile, and server-side applications, groups them by root cause, and provides actionable alerts to speed up debugging. Rollbar provides SDKs for over a dozen platforms including JavaScript, Python, PHP, Ruby, Go, Swift, .NET, and Java. The REST API enables programmatic management of projects, items, occurrences, deployments, teams, notifications, and source maps. The RQL (Rollbar Query Language) provides SQL-like queries for error analysis.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Rollbar Context
  property_count: 8
  slug: rollbar-context
layout: provider
modified: '2026-05-02'
name: Rollbar
rules:
- name: Rollbar API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 6
  slug: rollbar-rules
skills: []
slug: rollbar
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rollbar\nname: Rollbar\ndescription: >-\n  Rollbar is a real-time error tracking and monitoring platform for software\n  teams. It automatically captures exceptions and errors from web, mobile, and\n  server-side applications, groups them by root cause, and provides actionable\n  alerts to speed up debugging. Rollbar provides SDKs for over a dozen platforms\n  including JavaScript, Python, PHP, Ruby, Go, Swift, .NET, and Java. The REST\n  API enables programmatic management of projects, items, occurrences, deployments,\n  teams, notifications, and source maps. The RQL (Rollbar Query Language) provides\n  SQL-like queries for error analysis.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/apis.yml\ntags:\n  - Error Tracking\n  - Monitoring\n  - Debugging\n  - DevOps\n  - Application Performance\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rollbar:rollbar-rest-api\n    name: Rollbar\
  \ REST API\n    description: >-\n      The Rollbar REST API provides programmatic access to the Rollbar error\n      tracking and monitoring platform. Manage projects, items, occurrences,\n      deploys, teams, users, invites, notifications, and source maps through\n      a RESTful JSON interface. Authentication is via project access tokens\n      in the X-Rollbar-Access-Token header.\n    tags:\n      - Error Tracking\n      - Monitoring\n      - REST\n      - Projects\n      - Teams\n    humanURL: https://docs.rollbar.com/reference/getting-started-1\n    baseURL: https://api.rollbar.com/api/1\n    properties:\n      - url: https://docs.rollbar.com/reference/getting-started-1\n        type: Documentation\n      - url: https://explorer.docs.rollbar.com/\n        type: OpenAPI\n      - url: openapi/rollbar-rest-api-openapi.yml\n        type: OpenAPI\n    solutions:\n      - Error Management\n      - Project Administration\n      - Team Management\n      - Source Map Debugging\n    features:\n\
  \      - Item Management\n      - Occurrence Retrieval\n      - Project Management\n      - Access Token Management\n      - Team and User Management\n      - Source Map Upload\n      - Webhook Notifications\n\n  - aid: rollbar:rollbar-deployment-api\n    name: Rollbar Deployment API\n    description: >-\n      The Rollbar Deployment API allows developers to notify Rollbar of application\n      deployments and releases. By reporting deploys, teams can correlate error\n      spikes with specific releases, track deployment history, and manage rollbacks\n      with full visibility into which code version is running in production.\n    tags:\n      - Deployment\n      - Release Management\n      - Error Tracking\n      - REST\n      - DevOps\n    humanURL: https://docs.rollbar.com/reference/post_deploy\n    baseURL: https://api.rollbar.com/api/1\n    properties:\n      - url: https://docs.rollbar.com/reference/post_deploy\n        type: Documentation\n      - url: openapi/rollbar-deployment-api-openapi.yml\n\
  \        type: OpenAPI\n\n  - aid: rollbar:rollbar-metrics-api\n    name: Rollbar Metrics API\n    description: >-\n      The Rollbar Metrics API is part of Rollbar Analyze and provides\n      programmatic access to metrics data for error tracking analysis and\n      discovery. Enables developers to query resolution time metrics, occurrence\n      counts, and item activation metrics across projects.\n    tags:\n      - Metrics\n      - Analytics\n      - Error Tracking\n      - REST\n      - Monitoring\n    humanURL: https://docs.rollbar.com/reference/metrics\n    baseURL: https://api.rollbar.com/api/1\n    properties:\n      - url: https://docs.rollbar.com/reference/metrics\n        type: Documentation\n      - url: openapi/rollbar-metrics-api-openapi.yml\n        type: OpenAPI\n\n  - aid: rollbar:rollbar-rql-api\n    name: Rollbar RQL API\n    description: >-\n      The Rollbar RQL (Rollbar Query Language) API provides a SQL-like interface\n      for querying error and deployment data\
  \ stored in Rollbar. Supports SELECT\n      queries against item_occurrence and deploy tables for advanced error\n      analysis, reporting, and custom integrations.\n    tags:\n      - Query Language\n      - Analytics\n      - Error Tracking\n      - REST\n      - SQL\n    humanURL: https://docs.rollbar.com/reference/rql\n    baseURL: https://api.rollbar.com/api/1\n    properties:\n      - url: https://docs.rollbar.com/reference/rql\n        type: Documentation\n      - url: openapi/rollbar-rql-api-openapi.yml\n        type: OpenAPI\n\n  - aid: rollbar:rollbar-webhooks\n    name: Rollbar Webhooks\n    description: >-\n      Rollbar supports outbound webhook notifications for real-time event-driven\n      integrations. Webhooks deliver payload data when errors occur, items are\n      resolved, or deployment events happen, enabling integration with Slack,\n      PagerDuty, email, and custom HTTP endpoints.\n    tags:\n      - Webhooks\n      - Event-Driven\n      - Notifications\n    \
  \  - AsyncAPI\n      - Monitoring\n    humanURL: https://docs.rollbar.com/docs/webhooks\n    baseURL: https://api.rollbar.com\n    properties:\n      - url: https://docs.rollbar.com/docs/webhooks\n        type: Documentation\n      - url: asyncapi/rollbar-webhooks-asyncapi.yml\n        type: AsyncAPI\n\ncommon:\n  - url: https://rollbar.com/\n    type: Website\n  - url: https://docs.rollbar.com/\n    type: Documentation\n  - url: https://docs.rollbar.com/reference/getting-started-1\n    type: Documentation\n  - url: https://explorer.docs.rollbar.com/\n    type: Portal\n  - url: https://rollbar.com/pricing/\n    type: Pricing\n  - url: https://github.com/rollbar\n    type: GitHubOrganization\n  - url: https://rollbar.com/terms/\n    type: TermsOfService\n  - url: https://rollbar.com/privacy/\n    type: PrivacyPolicy\n  - url: https://rollbar.com/support/\n    type: Support\n  - url: openapi/rollbar-rest-api-openapi.yml\n    type: OpenAPI\n  - url: openapi/rollbar-deployment-api-openapi.yml\n\
  \    type: OpenAPI\n  - url: openapi/rollbar-metrics-api-openapi.yml\n    type: OpenAPI\n  - url: openapi/rollbar-rql-api-openapi.yml\n    type: OpenAPI\n  - url: asyncapi/rollbar-webhooks-asyncapi.yml\n    type: AsyncAPI\n  - url: json-schema/rollbar-item-schema.json\n    type: JSONSchema\n  - url: json-schema/rollbar-occurrence-schema.json\n    type: JSONSchema\n  - url: json-schema/rollbar-deploy-schema.json\n    type: JSONSchema\n  - url: json-schema/rollbar-webhook-payload-schema.json\n    type: JSONSchema\n  - url: json-ld/rollbar-context.jsonld\n    type: JSONLDContext\nintegrations:\n  - Slack\n  - PagerDuty\n  - Jira\n  - GitHub\n  - Bitbucket\n  - Heroku\nsolutions:\n  - Error Tracking\n  - Application Monitoring\n  - Release Management\n  - On-call Alerting\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/apis.yml
tags:
- Error Tracking
- Monitoring
- Debugging
- DevOps
- Application Performance
url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/apis.yml
use_cases: []
---
