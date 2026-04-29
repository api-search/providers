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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bigpanda\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/apis.yml\napis:\n- aid: bigpanda:bigpanda\n  name: BigPanda\n  tags:\n  - Alerts\n  - Audit\n  - Changes\n  - Correlation\n  - Correlation Patterns\n  - Enrichments\n  - Environments\n  - Incident Tags\n  - Incidents\n  - Logs\n  - Maintenance\n  - Maintenance Plans\n  - Name\n  - Patterns\n  - Plans\n  - Schedules\n  - Topologies\n  - Troubleshooting\n  - Users\n  humanURL: https://docs.bigpanda.io/reference/environments-api\n  properties:\n  - url: https://docs.bigpanda.io/reference/environments-api\n    type: Documentation\n  - url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/openapi/bigpanda-openapi.yml\n    type: OpenAPI\n  description: >-\n    Use the Environments API to define incident groups based on incident\n    properties such as source, severity, or alert data.\nname: BigPanda\ntags:\n- Incidents\n- Monitoring\n- Platform\ntype: Contract\n\
  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n- type: Portal\n  url: https://docs.bigpanda.io\n- type: GettingStarted\n  url: https://docs.bigpanda.io/docs/get-started\n- type: Documentation\n  url: https://docs.bigpanda.io/reference\n- type: ChangeLog\n  url: https://docs.bigpanda.io/docs/release-notes\n- type: PostmanWorkspace\n  url: https://www.postman.com/bigpandaio/bigpanda-api-staging/overview\n- type: Status\n  url: https://status.bigpanda.io/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/rules/bigpanda-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/vocabulary/bigpanda-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/capabilities/incident-management.yaml\n- type: Features\n  data:\n  - name: AI Alert Correlation\n\
  \    description: ML-powered correlation of alerts from 200+ monitoring tools into actionable incidents.\n  - name: Incident Management\n    description: Triage, acknowledge, and resolve correlated incidents with full audit trail.\n  - name: Root Cause Analysis\n    description: Automatically identify root causes by correlating alerts with change events.\n  - name: Maintenance Plans\n    description: Schedule maintenance windows to suppress expected alerts during planned work.\n  - name: Change Correlation\n    description: Ingest deployment and config changes to correlate with alert spikes.\n  - name: Environments\n    description: Define DSL-based environments to group incidents by source, severity, or host.\n  - name: Enrichments\n    description: Enrich alerts with contextual tags from CMDB and other data sources.\n  - name: AIOps Automation\n    description: Automate incident response workflows with AI-driven insights and routing.\n- type: UseCases\n  data:\n  - name: Alert Noise\
  \ Reduction\n    description: Reduce alert fatigue by correlating thousands of alerts into a handful of incidents.\n  - name: Change Impact Analysis\n    description: Automatically link deployment changes to alert spikes for faster root cause identification.\n  - name: On-Call Automation\n    description: Route correlated incidents to the right on-call team with full context.\n  - name: Maintenance Scheduling\n    description: Suppress alerts during planned maintenance to prevent false incident creation.\n  - name: ITSM Integration\n    description: Automatically create and update tickets in ServiceNow or Jira from correlated incidents.\n- type: Integrations\n  data:\n  - name: PagerDuty\n    description: Route correlated incidents to PagerDuty for on-call alerting.\n  - name: ServiceNow\n    description: Create and update ServiceNow incidents automatically from BigPanda.\n  - name: Datadog\n    description: Ingest Datadog alerts into BigPanda for cross-tool correlation.\n  - name: Nagios\n\
  \    description: Ingest Nagios monitoring alerts via BigPanda integration.\n  - name: Prometheus\n    description: Correlate Prometheus/Alertmanager alerts in BigPanda.\n  - name: Jira\n    description: Create Jira issues from BigPanda incidents for engineering tracking.\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  BigPanda is a software platform that uses artificial intelligence (AI) to help\n  IT operations teams automate incident management by correlating alerts from\n  various systems, identifying root causes, and streamlining the incident\n  resolution process, essentially moving from reactive to proactive incident\n  response by providing context and insights through intelligent data analysis.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/apis.yml
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
