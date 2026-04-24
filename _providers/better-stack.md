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
