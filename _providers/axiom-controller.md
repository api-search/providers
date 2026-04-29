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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: axiom-controller\nname: Axiom Controller\ndescription: >-\n  Axiom is a cloud-native observability platform providing APIs for ingesting,\n  querying, and managing telemetry data including logs, traces, and metrics\n  with support for datasets, monitors, and organization management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Analytics\n- Cloud Native\n- Logging\n- Monitoring\n- Observability\n- Telemetry\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/axiom-controller/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: axiom-controller:axiom-ingest-api\n  name: Axiom Ingest API\n  description: API for ingesting logs, events, and telemetry data into Axiom \n    datasets.\n  humanURL: https://axiom.co/docs/restapi/ingest\n  baseURL: https://api.axiom.co/v1\n  tags:\n  - Events\n  - Ingest\n  - Logs\n  - Telemetry\n  properties:\n  -\
  \ type: Documentation\n    url: https://axiom.co/docs/restapi/ingest\n- aid: axiom-controller:axiom-query-api\n  name: Axiom Query API\n  description: >-\n    API for querying and analyzing data stored in Axiom datasets using APL\n    (Axiom Processing Language).\n  humanURL: https://axiom.co/docs/restapi/query\n  baseURL: https://api.axiom.co/v1\n  tags:\n  - Analytics\n  - APL\n  - Query\n  properties:\n  - type: Documentation\n    url: https://axiom.co/docs/restapi/query\ncommon:\n- type: Portal\n  url: https://axiom.co/\n- type: Authentication\n  url: https://axiom.co/docs/restapi/token\n- type: StatusPage\n  url: https://status.axiom.co\n- type: Blog\n  url: https://axiom.co/blog\n- type: TermsOfService\n  url: https://axiom.co/terms\n- type: PrivacyPolicy\n  url: https://axiom.co/privacy\n- type: GitHubOrganization\n  url: https://github.com/axiomhq\n- type: Pricing\n  url: https://axiom.co/pricing\n- type: Documentation\n  url: https://axiom.co/docs\n- type: GettingStarted\n  url:\
  \ https://axiom.co/docs/get-started\n- type: Features\n  data:\n  - name: Log Ingestion\n    description: Ingest logs from any source at massive scale with compression.\n  - name: APL Query Language\n    description: Query telemetry data using Axiom Processing Language (APL), \n      inspired by KQL.\n  - name: Dataset Management\n    description: Organize telemetry data in datasets for granular access control\n      and retention.\n  - name: Monitors and Alerts\n    description: Set up threshold-based and anomaly-detection monitors with \n      PagerDuty/Slack integrations.\n  - name: OpenTelemetry Support\n    description: Native support for OpenTelemetry traces, metrics, and logs via \n      OTLP.\n  - name: Long-Term Retention\n    description: Store telemetry data for extended periods at low cost with \n      queryable archives.\n  - name: Dashboards\n    description: Build custom dashboards with rich visualization for monitoring \n      application health.\n- type: UseCases\n  data:\n\
  \  - name: Application Logging\n    description: Centralize application logs for debugging and troubleshooting.\n  - name: Infrastructure Monitoring\n    description: Monitor infrastructure metrics and detect anomalies.\n  - name: Security Analytics\n    description: Analyze security logs and audit trails for threat detection.\n  - name: Distributed Tracing\n    description: Trace requests across microservices with OpenTelemetry.\n  - name: Business Analytics\n    description: Analyze user behavior and business events stored as structured \n      logs.\n- type: Integrations\n  data:\n  - name: OpenTelemetry\n    description: Ingest OTLP data from any OpenTelemetry-compatible source.\n  - name: Vercel\n    description: Built-in Vercel log drain integration for edge function and \n      deployment logs.\n  - name: AWS CloudWatch\n    description: Forward CloudWatch logs to Axiom via Lambda log forwarder.\n  - name: Kubernetes\n    description: Deploy Axiom Helm charts to collect Kubernetes\
  \ logs and \n      metrics.\n  - name: GitHub Actions\n    description: Send CI/CD pipeline logs to Axiom from GitHub Actions \n      workflows.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/axiom-controller/refs/heads/main/apis.yml
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
