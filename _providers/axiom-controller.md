---
api_count: 2
apis:
- description: API for ingesting logs, events, and telemetry data into Axiom datasets.
  name: Axiom Ingest API
  slug: axiom-ingest-api
- description: API for querying and analyzing data stored in Axiom datasets using APL (Axiom Processing Language).
  name: Axiom Query API
  slug: axiom-query-api
common:
- title: ''
  type: Portal
  url: https://axiom.co/
- title: ''
  type: Authentication
  url: https://axiom.co/docs/restapi/token
- title: ''
  type: StatusPage
  url: https://status.axiom.co
- title: ''
  type: Blog
  url: https://axiom.co/blog
- title: ''
  type: TermsOfService
  url: https://axiom.co/terms
- title: ''
  type: PrivacyPolicy
  url: https://axiom.co/privacy
- title: ''
  type: GitHubOrganization
  url: https://github.com/axiomhq
- title: ''
  type: Pricing
  url: https://axiom.co/pricing
- title: ''
  type: Documentation
  url: https://axiom.co/docs
- title: ''
  type: GettingStarted
  url: https://axiom.co/docs/get-started
created: '2024-01-01'
description: Axiom is a cloud-native observability platform providing APIs for ingesting, querying, and managing telemetry data including logs, traces, and metrics with support for datasets, monitors, and organization management.
features:
- description: Ingest logs from any source at massive scale with compression.
  name: Log Ingestion
- description: Query telemetry data using Axiom Processing Language (APL), inspired by KQL.
  name: APL Query Language
- description: Organize telemetry data in datasets for granular access control and retention.
  name: Dataset Management
- description: Set up threshold-based and anomaly-detection monitors with PagerDuty/Slack integrations.
  name: Monitors and Alerts
- description: Native support for OpenTelemetry traces, metrics, and logs via OTLP.
  name: OpenTelemetry Support
- description: Store telemetry data for extended periods at low cost with queryable archives.
  name: Long-Term Retention
- description: Build custom dashboards with rich visualization for monitoring application health.
  name: Dashboards
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Ingest OTLP data from any OpenTelemetry-compatible source.
  name: OpenTelemetry
- description: Built-in Vercel log drain integration for edge function and deployment logs.
  name: Vercel
- description: Forward CloudWatch logs to Axiom via Lambda log forwarder.
  name: AWS CloudWatch
- description: Deploy Axiom Helm charts to collect Kubernetes logs and metrics.
  name: Kubernetes
- description: Send CI/CD pipeline logs to Axiom from GitHub Actions workflows.
  name: GitHub Actions
layout: provider
modified: '2026-04-19'
name: Axiom Controller
skills: []
slug: axiom-controller
solutions: []
tags:
- Analytics
- Cloud Native
- Logging
- Monitoring
- Observability
- Telemetry
url: https://raw.githubusercontent.com/api-evangelist/axiom-controller/refs/heads/main/apis.yml
use_cases:
- description: Centralize application logs for debugging and troubleshooting.
  name: Application Logging
- description: Monitor infrastructure metrics and detect anomalies.
  name: Infrastructure Monitoring
- description: Analyze security logs and audit trails for threat detection.
  name: Security Analytics
- description: Trace requests across microservices with OpenTelemetry.
  name: Distributed Tracing
- description: Analyze user behavior and business events stored as structured logs.
  name: Business Analytics
---
