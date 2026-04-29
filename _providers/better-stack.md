---
api_count: 1
apis:
- description: The Better Stack API provides programmatic access to uptime monitoring, heartbeat monitoring, incident management, status pages, escalation policies, and team management. It follows the JSON:API speci
  name: Better Stack API
  slug: better-stack
capabilities:
- description: 'Unified incident response workflow combining Better Stack uptime monitoring, heartbeat monitoring, and incident management. Used by SRE teams and on-call engineers to detect, acknowledge, and resolve '
  name: Better Stack Incident Response
  slug: incident-response
common:
- title: ''
  type: Portal
  url: https://betterstack.com/docs/
- title: ''
  type: GettingStarted
  url: https://betterstack.com/docs/uptime/api/getting-started/
- title: ''
  type: Authentication
  url: https://betterstack.com/docs/uptime/api/getting-started/
- title: ''
  type: Pricing
  url: https://betterstack.com/pricing
- title: ''
  type: StatusPage
  url: https://status.betterstack.com/
- title: ''
  type: Blog
  url: https://betterstack.com/community/blog
- title: ''
  type: ChangeLog
  url: https://betterstack.com/tag/changelog
- title: ''
  type: GitHubOrganization
  url: https://github.com/BetterStackHQ
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/rules/better-stack-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/vocabulary/better-stack-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/capabilities/incident-response.yaml
created: '2025-01-08'
description: Better Stack is a comprehensive infrastructure monitoring and observability platform that combines uptime monitoring, log management, incident management, status pages, and AI-powered site reliability tools. It helps teams identify and resolve website and server issues quickly by providing real-time alerting, detailed diagnostics, on-call scheduling, and public/private status pages.
features:
- description: Monitor URLs, APIs, and services for availability with checks from multiple global regions every 30 seconds.
  name: Uptime Monitoring
- description: Monitor scheduled jobs, cron tasks, and background workers by pinging a unique URL on each run.
  name: Heartbeat Monitoring
- description: Automatically create and manage incidents when monitors detect downtime, with acknowledgement and resolution workflows.
  name: Incident Management
- description: Configure escalation policies with multi-step notification sequences via phone, SMS, email, and push.
  name: On-Call Scheduling
- description: Create public and private status pages with custom domains, branding, and real-time component status.
  name: Status Pages
- description: Collect, search, and visualize logs across your entire infrastructure stack.
  name: Log Management
- description: AI-powered root cause analysis that automatically investigates incidents and suggests resolutions.
  name: AI SRE
- description: OpenTelemetry-native monitoring with dashboards for metrics and infrastructure health.
  name: Infrastructure Monitoring
- description: Manage Better Stack resources as code using the official Terraform provider.
  name: Terraform Provider
- description: Model Context Protocol server for integrating Better Stack with AI tools and agents.
  name: MCP Server
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Receive incident alerts and status updates directly in Slack channels.
  name: Slack
- description: Forward incidents to PagerDuty for existing on-call workflows.
  name: PagerDuty
- description: Manage monitors, status pages, and escalation policies as infrastructure as code.
  name: Terraform
- description: Send metrics, logs, and traces using OpenTelemetry-compatible exporters.
  name: OpenTelemetry
- description: Compatible with Sentry SDK for error tracking integration.
  name: Sentry
- description: Connect Better Stack monitoring data with New Relic dashboards.
  name: New Relic
jsonld:
- class_count: 43
  name: Better Stack Context
  property_count: 48
  slug: better-stack-context
layout: provider
modified: '2026-04-19'
name: Better Stack
rules:
- name: Better Stack API Rules
  rule_count: 37
  severity_counts:
    error: 13
    hint: 0
    info: 7
    warn: 17
  slug: better-stack-spectral-rules
skills: []
slug: better-stack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: better-stack\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/apis.yml\napis:\n  - aid: better-stack:better-stack\n    name: Better Stack API\n    tags:\n      - Monitoring\n      - Incidents\n      - Uptime\n      - Heartbeats\n      - Status Pages\n    humanURL: https://betterstack.com/docs/uptime/api/getting-started/\n    baseURL: https://uptime.betterstack.com/api/v2\n    properties:\n      - url: https://betterstack.com/docs/uptime/api/getting-started/\n        type: Documentation\n      - url: https://betterstack.com/docs/uptime/api/monitors/\n        type: APIReference\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/openapi/better-stack-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Better Stack API provides programmatic access to uptime monitoring,\n      heartbeat monitoring, incident management, status pages, escalation\n      policies, and team\
  \ management. It follows the JSON:API specification and\n      uses Bearer token authentication.\nname: Better Stack\ntags:\n  - Incidents\n  - Logs\n  - Monitoring\n  - Platform\n  - Status\n  - Uptime\n  - Observability\n  - On-Call\n  - Heartbeats\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  Better Stack is a comprehensive infrastructure monitoring and observability\n  platform that combines uptime monitoring, log management, incident management,\n  status pages, and AI-powered site reliability tools. It helps teams identify\n  and resolve website and server issues quickly by providing real-time alerting,\n  detailed diagnostics, on-call scheduling, and public/private status pages.\ncommon:\n  - type: Portal\n    url: https://betterstack.com/docs/\n  - type: GettingStarted\n    url: https://betterstack.com/docs/uptime/api/getting-started/\n\
  \  - type: Authentication\n    url: https://betterstack.com/docs/uptime/api/getting-started/\n  - type: Pricing\n    url: https://betterstack.com/pricing\n  - type: StatusPage\n    url: https://status.betterstack.com/\n  - type: Blog\n    url: https://betterstack.com/community/blog\n  - type: ChangeLog\n    url: https://betterstack.com/tag/changelog\n  - type: GitHubOrganization\n    url: https://github.com/BetterStackHQ\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/rules/better-stack-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/vocabulary/better-stack-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/capabilities/incident-response.yaml\n  - type: Features\n    data:\n      - name: Uptime Monitoring\n        description: Monitor\
  \ URLs, APIs, and services for availability with checks from multiple global regions every 30 seconds.\n      - name: Heartbeat Monitoring\n        description: Monitor scheduled jobs, cron tasks, and background workers by pinging a unique URL on each run.\n      - name: Incident Management\n        description: Automatically create and manage incidents when monitors detect downtime, with acknowledgement and resolution workflows.\n      - name: On-Call Scheduling\n        description: Configure escalation policies with multi-step notification sequences via phone, SMS, email, and push.\n      - name: Status Pages\n        description: Create public and private status pages with custom domains, branding, and real-time component status.\n      - name: Log Management\n        description: Collect, search, and visualize logs across your entire infrastructure stack.\n      - name: AI SRE\n        description: AI-powered root cause analysis that automatically investigates incidents and suggests\
  \ resolutions.\n      - name: Infrastructure Monitoring\n        description: OpenTelemetry-native monitoring with dashboards for metrics and infrastructure health.\n      - name: Terraform Provider\n        description: Manage Better Stack resources as code using the official Terraform provider.\n      - name: MCP Server\n        description: Model Context Protocol server for integrating Better Stack with AI tools and agents.\n  - type: UseCases\n    data:\n      - name: Website Uptime Monitoring\n        description: Monitor public websites and APIs for availability and alert on-call engineers when they go down.\n      - name: API Health Checking\n        description: Continuously verify that REST APIs return expected status codes and response times.\n      - name: Cron Job Monitoring\n        description: Use heartbeats to ensure scheduled tasks run on time and alert when they fail to check in.\n      - name: Incident Response Automation\n        description: Automate incident creation,\
  \ on-call notifications, and resolution workflows to reduce MTTR.\n      - name: Customer-Facing Status Communication\n        description: Publish status pages that automatically reflect the real-time health of monitored services.\n      - name: Infrastructure Observability\n        description: Aggregate logs, metrics, and traces in a single platform for full-stack observability.\n  - type: Integrations\n    data:\n      - name: Slack\n        description: Receive incident alerts and status updates directly in Slack channels.\n      - name: PagerDuty\n        description: Forward incidents to PagerDuty for existing on-call workflows.\n      - name: Terraform\n        description: Manage monitors, status pages, and escalation policies as infrastructure as code.\n      - name: OpenTelemetry\n        description: Send metrics, logs, and traces using OpenTelemetry-compatible exporters.\n      - name: Sentry\n        description: Compatible with Sentry SDK for error tracking integration.\n\
  \      - name: New Relic\n        description: Connect Better Stack monitoring data with New Relic dashboards.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/apis.yml
tags:
- Incidents
- Logs
- Monitoring
- Platform
- Status
- Uptime
- Observability
- On-Call
- Heartbeats
url: https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/apis.yml
use_cases:
- description: Monitor public websites and APIs for availability and alert on-call engineers when they go down.
  name: Website Uptime Monitoring
- description: Continuously verify that REST APIs return expected status codes and response times.
  name: API Health Checking
- description: Use heartbeats to ensure scheduled tasks run on time and alert when they fail to check in.
  name: Cron Job Monitoring
- description: Automate incident creation, on-call notifications, and resolution workflows to reduce MTTR.
  name: Incident Response Automation
- description: Publish status pages that automatically reflect the real-time health of monitored services.
  name: Customer-Facing Status Communication
- description: Aggregate logs, metrics, and traces in a single platform for full-stack observability.
  name: Infrastructure Observability
---
