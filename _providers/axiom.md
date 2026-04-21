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
