---
api_count: 1
apis:
- description: Use the Environments API to define incident groups based on incident properties such as source, severity, or alert data.
  name: BigPanda
  slug: bigpanda
capabilities:
- description: ''
  name: Incident Management
  slug: incident-management
common:
- title: ''
  type: Portal
  url: https://docs.bigpanda.io
- title: ''
  type: GettingStarted
  url: https://docs.bigpanda.io/docs/get-started
- title: ''
  type: Documentation
  url: https://docs.bigpanda.io/reference
- title: ''
  type: ChangeLog
  url: https://docs.bigpanda.io/docs/release-notes
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/bigpandaio/bigpanda-api-staging/overview
- title: ''
  type: Status
  url: https://status.bigpanda.io/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/rules/bigpanda-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/vocabulary/bigpanda-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/capabilities/incident-management.yaml
created: '2025-01-08'
description: BigPanda is a software platform that uses artificial intelligence (AI) to help IT operations teams automate incident management by correlating alerts from various systems, identifying root causes, and streamlining the incident resolution process, essentially moving from reactive to proactive incident response by providing context and insights through intelligent data analysis.
features:
- description: ML-powered correlation of alerts from 200+ monitoring tools into actionable incidents.
  name: AI Alert Correlation
- description: Triage, acknowledge, and resolve correlated incidents with full audit trail.
  name: Incident Management
- description: Automatically identify root causes by correlating alerts with change events.
  name: Root Cause Analysis
- description: Schedule maintenance windows to suppress expected alerts during planned work.
  name: Maintenance Plans
- description: Ingest deployment and config changes to correlate with alert spikes.
  name: Change Correlation
- description: Define DSL-based environments to group incidents by source, severity, or host.
  name: Environments
- description: Enrich alerts with contextual tags from CMDB and other data sources.
  name: Enrichments
- description: Automate incident response workflows with AI-driven insights and routing.
  name: AIOps Automation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Route correlated incidents to PagerDuty for on-call alerting.
  name: PagerDuty
- description: Create and update ServiceNow incidents automatically from BigPanda.
  name: ServiceNow
- description: Ingest Datadog alerts into BigPanda for cross-tool correlation.
  name: Datadog
- description: Ingest Nagios monitoring alerts via BigPanda integration.
  name: Nagios
- description: Correlate Prometheus/Alertmanager alerts in BigPanda.
  name: Prometheus
- description: Create Jira issues from BigPanda incidents for engineering tracking.
  name: Jira
jsonld:
- class_count: 6
  name: Bigpanda Context
  property_count: 19
  slug: bigpanda-context
layout: provider
modified: '2026-04-19'
name: BigPanda
rules:
- name: BigPanda API Rules
  rule_count: 23
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 15
  slug: bigpanda-spectral-rules
skills: []
slug: bigpanda
solutions: []
tags:
- Incidents
- Monitoring
- Platform
url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/apis.yml
use_cases:
- description: Reduce alert fatigue by correlating thousands of alerts into a handful of incidents.
  name: Alert Noise Reduction
- description: Automatically link deployment changes to alert spikes for faster root cause identification.
  name: Change Impact Analysis
- description: Route correlated incidents to the right on-call team with full context.
  name: On-Call Automation
- description: Suppress alerts during planned maintenance to prevent false incident creation.
  name: Maintenance Scheduling
- description: Automatically create and update tickets in ServiceNow or Jira from correlated incidents.
  name: ITSM Integration
---
