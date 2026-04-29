---
api_count: 1
apis:
- description: The Better Stack API provides programmatic access to uptime monitoring, heartbeat monitoring, incident management, status pages, escalation policies, and team management. It follows the JSON:API speci
  name: Better Stack API
  slug: betterstack-api
common:
- title: ''
  type: Portal
  url: https://betterstack.com/docs/
- title: ''
  type: GettingStarted
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
created: '2026-03-25'
description: Better Stack is a comprehensive infrastructure monitoring and observability platform combining uptime monitoring, log management, incident management, status pages, and AI-powered site reliability tools. This is an alias entry for the better-stack repository. See https://github.com/api-evangelist/better-stack for the full API profile with OpenAPI specs, capabilities, and vocabulary.
features:
- description: Monitor URLs, APIs, and services for availability with global region checks.
  name: Uptime Monitoring
- description: Monitor scheduled jobs and cron tasks with heartbeat pings.
  name: Heartbeat Monitoring
- description: On-call alerting with escalation policies, acknowledgement, and resolution workflows.
  name: Incident Management
- description: Public and private status pages with custom domains and real-time component status.
  name: Status Pages
- description: Collect, search, and visualize logs across your infrastructure stack.
  name: Log Management
- description: AI-powered root cause analysis for automated incident investigation.
  name: AI SRE
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Receive incident alerts in Slack channels.
  name: Slack
- description: Forward incidents to PagerDuty.
  name: PagerDuty
- description: Manage Better Stack resources as infrastructure as code.
  name: Terraform
- description: Send metrics, logs, and traces using OpenTelemetry exporters.
  name: OpenTelemetry
layout: provider
modified: '2026-04-19'
name: Better Stack
skills: []
slug: betterstack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: betterstack\nname: Better Stack\ndescription: >-\n  Better Stack is a comprehensive infrastructure monitoring and observability\n  platform combining uptime monitoring, log management, incident management,\n  status pages, and AI-powered site reliability tools. This is an alias entry\n  for the better-stack repository. See https://github.com/api-evangelist/better-stack\n  for the full API profile with OpenAPI specs, capabilities, and vocabulary.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Observability\n  - Uptime Monitoring\n  - Incidents\n  - Logs\n  - Monitoring\n  - Status Pages\n  - On-Call\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/betterstack/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: betterstack:betterstack-api\n    name: Better Stack API\n    description: >-\n      The Better Stack API provides programmatic\
  \ access to uptime monitoring,\n      heartbeat monitoring, incident management, status pages, escalation\n      policies, and team management. It follows the JSON:API specification\n      and uses Bearer token authentication.\n    humanURL: https://betterstack.com/docs/uptime/api/getting-started/\n    baseURL: https://uptime.betterstack.com/api/v2\n    tags:\n      - Monitoring\n      - Incidents\n      - Uptime\n      - Heartbeats\n      - Status Pages\n    properties:\n      - type: Documentation\n        url: https://betterstack.com/docs/uptime/api/getting-started/\n      - type: APIReference\n        url: https://betterstack.com/docs/uptime/api/monitors/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/better-stack/refs/heads/main/openapi/better-stack-openapi.yml\ncommon:\n  - type: Portal\n    url: https://betterstack.com/docs/\n  - type: GettingStarted\n    url: https://betterstack.com/docs/uptime/api/getting-started/\n  - type:\
  \ Pricing\n    url: https://betterstack.com/pricing\n  - type: StatusPage\n    url: https://status.betterstack.com/\n  - type: Blog\n    url: https://betterstack.com/community/blog\n  - type: ChangeLog\n    url: https://betterstack.com/tag/changelog\n  - type: GitHubOrganization\n    url: https://github.com/BetterStackHQ\n  - type: Features\n    data:\n      - name: Uptime Monitoring\n        description: Monitor URLs, APIs, and services for availability with global region checks.\n      - name: Heartbeat Monitoring\n        description: Monitor scheduled jobs and cron tasks with heartbeat pings.\n      - name: Incident Management\n        description: On-call alerting with escalation policies, acknowledgement, and resolution workflows.\n      - name: Status Pages\n        description: Public and private status pages with custom domains and real-time component status.\n      - name: Log Management\n        description: Collect, search, and visualize logs across your infrastructure stack.\n\
  \      - name: AI SRE\n        description: AI-powered root cause analysis for automated incident investigation.\n  - type: Integrations\n    data:\n      - name: Slack\n        description: Receive incident alerts in Slack channels.\n      - name: PagerDuty\n        description: Forward incidents to PagerDuty.\n      - name: Terraform\n        description: Manage Better Stack resources as infrastructure as code.\n      - name: OpenTelemetry\n        description: Send metrics, logs, and traces using OpenTelemetry exporters.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/betterstack/refs/heads/main/apis.yml
tags:
- Observability
- Uptime Monitoring
- Incidents
- Logs
- Monitoring
- Status Pages
- On-Call
url: https://raw.githubusercontent.com/api-evangelist/betterstack/refs/heads/main/apis.yml
use_cases: []
---
