---
api_count: 1
apis:
- description: RESTful API for ingesting, querying, and managing logs and events in Axiom.
  name: Axiom API
  slug: axiom-api
common:
- title: ''
  type: Portal
  url: https://axiom.co/
- title: ''
  type: StatusPage
  url: https://status.axiom.co
- title: ''
  type: Blog
  url: https://axiom.co/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/axiomhq
- title: ''
  type: TermsOfService
  url: https://axiom.co/terms
- title: ''
  type: PrivacyPolicy
  url: https://axiom.co/privacy
- title: ''
  type: SignUp
  url: https://app.axiom.co/register
- title: ''
  type: Pricing
  url: https://axiom.co/pricing
- title: ''
  type: Documentation
  url: https://axiom.co/docs
- title: ''
  type: GettingStarted
  url: https://axiom.co/docs/get-started
created: '2024-01-15'
description: Axiom is a serverless log management and analytics platform that provides real-time insights into structured and unstructured data with fast querying capabilities for logs, events, and telemetry data.
features:
- description: Manage logs without managing servers or storage infrastructure.
  name: Serverless Log Management
- description: Query billions of events in seconds with APL (Axiom Processing Language).
  name: Real-Time Querying
- description: Organize data into datasets with role-based access control.
  name: Dataset Organization
- description: Create monitors with alert notifications to Slack, PagerDuty, and email.
  name: Monitors and Alerts
- description: Native OTLP ingestion for logs, metrics, and traces.
  name: OpenTelemetry Native
- description: Store data indefinitely with query-optimized cold storage.
  name: Endless Retention
- description: Build and share monitoring dashboards with rich visualization options.
  name: Dashboards
- description: Mark events like deployments on dashboards for correlation analysis.
  name: Annotations
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Vercel integration for log drains and deployment tracking.
  name: Vercel
- description: Ingest OTLP telemetry from any OTel-compatible source.
  name: OpenTelemetry
- description: Forward Lambda logs to Axiom via log subscriptions.
  name: AWS Lambda
- description: Collect pod and node logs using the Axiom DaemonSet or Helm chart.
  name: Kubernetes
- description: Send CI/CD logs from GitHub Actions to Axiom for analysis.
  name: GitHub Actions
layout: provider
modified: '2026-04-19'
name: Axiom
skills: []
slug: axiom
solutions: []
source_yaml: "aid: axiom\nname: Axiom\ndescription: >-\n  Axiom is a serverless log management and analytics platform that provides\n  real-time insights into structured and unstructured data with fast querying\n  capabilities for logs, events, and telemetry data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Analytics\n- Log Management\n- Logging\n- Observability\n- Real-Time\n- Serverless\nurl: \n  https://raw.githubusercontent.com/api-evangelist/axiom/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: axiom:axiom-api\n  name: Axiom API\n  description: RESTful API for ingesting, querying, and managing logs and events\n    in Axiom.\n  humanURL: https://axiom.co/docs/restapi/introduction\n  baseURL: https://api.axiom.co\n  tags:\n  - Analytics\n  - Logging\n  - Observability\n  properties:\n  - type: Documentation\n    url: https://axiom.co/docs/restapi/introduction\n\
  \  - type: Authentication\n    url: https://axiom.co/docs/restapi/token\ncommon:\n- type: Portal\n  url: https://axiom.co/\n- type: StatusPage\n  url: https://status.axiom.co\n- type: Blog\n  url: https://axiom.co/blog\n- type: GitHubOrganization\n  url: https://github.com/axiomhq\n- type: TermsOfService\n  url: https://axiom.co/terms\n- type: PrivacyPolicy\n  url: https://axiom.co/privacy\n- type: SignUp\n  url: https://app.axiom.co/register\n- type: Pricing\n  url: https://axiom.co/pricing\n- type: Documentation\n  url: https://axiom.co/docs\n- type: GettingStarted\n  url: https://axiom.co/docs/get-started\n- type: Features\n  data:\n  - name: Serverless Log Management\n    description: Manage logs without managing servers or storage infrastructure.\n  - name: Real-Time Querying\n    description: Query billions of events in seconds with APL (Axiom Processing \n      Language).\n  - name: Dataset Organization\n    description: Organize data into datasets with role-based access control.\n\
  \  - name: Monitors and Alerts\n    description: Create monitors with alert notifications to Slack, PagerDuty, \n      and email.\n  - name: OpenTelemetry Native\n    description: Native OTLP ingestion for logs, metrics, and traces.\n  - name: Endless Retention\n    description: Store data indefinitely with query-optimized cold storage.\n  - name: Dashboards\n    description: Build and share monitoring dashboards with rich visualization \n      options.\n  - name: Annotations\n    description: Mark events like deployments on dashboards for correlation \n      analysis.\n- type: UseCases\n  data:\n  - name: Application Logging\n    description: Centralize application logs for debugging and error analysis.\n  - name: DevOps Observability\n    description: Monitor CI/CD pipelines, deployments, and infrastructure \n      health.\n  - name: Security Analytics\n    description: Analyze audit logs and detect security anomalies.\n  - name: Edge Function Monitoring\n    description: Monitor Vercel,\
  \ Cloudflare, and other edge function execution.\n  - name: Distributed Tracing\n    description: Trace requests across services using OpenTelemetry OTLP.\n- type: Integrations\n  data:\n  - name: Vercel\n    description: Official Vercel integration for log drains and deployment \n      tracking.\n  - name: OpenTelemetry\n    description: Ingest OTLP telemetry from any OTel-compatible source.\n  - name: AWS Lambda\n    description: Forward Lambda logs to Axiom via log subscriptions.\n  - name: Kubernetes\n    description: Collect pod and node logs using the Axiom DaemonSet or Helm \n      chart.\n  - name: GitHub Actions\n    description: Send CI/CD logs from GitHub Actions to Axiom for analysis.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/axiom/refs/heads/main/apis.yml
tags:
- Analytics
- Log Management
- Logging
- Observability
- Real-Time
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/axiom/refs/heads/main/apis.yml
use_cases:
- description: Centralize application logs for debugging and error analysis.
  name: Application Logging
- description: Monitor CI/CD pipelines, deployments, and infrastructure health.
  name: DevOps Observability
- description: Analyze audit logs and detect security anomalies.
  name: Security Analytics
- description: Monitor Vercel, Cloudflare, and other edge function execution.
  name: Edge Function Monitoring
- description: Trace requests across services using OpenTelemetry OTLP.
  name: Distributed Tracing
---
