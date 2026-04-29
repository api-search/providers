---
api_count: 17
api_specs:
- filename: new-relic-openapi.yml
  format: yaml
  label: New Relic REST API v2
  slug: new-relic-rest-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-openapi.yml
- filename: new-relic-metric-api-openapi.yml
  format: yaml
  label: New Relic Metric API
  slug: new-relic-metric-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-metric-api-openapi.yml
- filename: new-relic-event-api-openapi.yml
  format: yaml
  label: New Relic Event API
  slug: new-relic-event-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-event-api-openapi.yml
- filename: new-relic-log-api-openapi.yml
  format: yaml
  label: New Relic Log API
  slug: new-relic-log-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-log-api-openapi.yml
- filename: new-relic-trace-api-openapi.yml
  format: yaml
  label: New Relic Trace API
  slug: new-relic-trace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-trace-api-openapi.yml
apis:
- description: The New Relic REST API v2 is the original HTTP REST interface for querying application performance data, configuring alerts, and managing account settings. New Relic recommends NerdGraph (GraphQL) for
  name: New Relic REST API v2
  slug: new-relic-rest-api-v2
- description: NerdGraph is New Relic's primary GraphQL API for querying observability data, managing account configuration, and accessing the full breadth of New Relic platform capabilities. It is the recommended A
  name: New Relic NerdGraph API
  slug: new-relic-nerdgraph-api
- description: The New Relic Metric API is an HTTP endpoint for ingesting dimensional metric data directly into the New Relic platform. It accepts JSON payloads via POST requests and is the underlying API used by Te
  name: New Relic Metric API
  slug: new-relic-metric-api
- description: The New Relic Event API allows you to send custom event data to the New Relic platform via HTTP POST. Custom events submitted through this API can be queried and visualized using NRQL, making it suita
  name: New Relic Event API
  slug: new-relic-event-api
- description: The New Relic Log API enables log data to be sent directly to the New Relic platform via HTTP POST requests. It accepts compressed JSON payloads and provides an alternative to log forwarding agents wh
  name: New Relic Log API
  slug: new-relic-log-api
- description: The New Relic Trace API allows distributed tracing data to be sent directly to New Relic in either New Relic format or Zipkin JSON v2 format. It is used by Telemetry SDKs, open source integrations, an
  name: New Relic Trace API
  slug: new-relic-trace-api
- description: The New Relic Alerts REST API provides endpoints for programmatically managing alert policies, conditions, notification channels, and muting rules. New Relic recommends using NerdGraph for new alert m
  name: New Relic Alerts API
  slug: new-relic-alerts-api
- description: The New Relic Synthetics API, available through NerdGraph, allows you to programmatically create, update, delete, and query synthetic monitors including ping monitors, scripted API monitors, browser m
  name: New Relic Synthetics API
  slug: new-relic-synthetics-api
- description: 'The New Relic Infrastructure Alerts REST API provides endpoints for creating and managing infrastructure-specific alert conditions such as host, process, and integration alert conditions. It uses the '
  name: New Relic Infrastructure Alerts API
  slug: new-relic-infrastructure-alerts-api
- description: The New Relic Browser API provides JavaScript methods for extending and customizing browser monitoring data collection within the New Relic browser agent. Developers can use it to add custom attribute
  name: New Relic Browser API
  slug: new-relic-browser-api
- description: The New Relic Partnership API is a web service API for New Relic partners that enables them to create, edit, upgrade, downgrade, and cancel New Relic accounts on behalf of their customers. It is avail
  name: New Relic Partnership API
  slug: new-relic-partnership-api
- description: The New Relic Telemetry SDKs are open source client libraries for sending metrics, events, logs, and traces (MELT) to New Relic using the ingest APIs. SDKs are available for Java, Python, Node.js, Go,
  name: New Relic Telemetry SDKs
  slug: new-relic-telemetry-sdk
- description: New Relic provides a native OTLP (OpenTelemetry Protocol) endpoint that accepts metrics, traces, and logs from any OpenTelemetry-instrumented application or OTLP exporter. It supports both gRPC and HT
  name: New Relic OpenTelemetry OTLP Endpoint
  slug: new-relic-opentelemetry-otlp
- description: New Relic Control is an observability control plane that unifies Fleet Control, Agent Control, and Pipeline Control into a single management layer. It enables DevOps and platform teams to remotely dep
  name: New Relic Control
  slug: new-relic-control
- description: 'The New Relic NRQL Lookups API is a REST API for managing lookup tables that can be used to enrich NRQL query results. It supports creating, updating, downloading, listing, and deleting lookup tables '
  name: New Relic NRQL Lookups API
  slug: new-relic-nrql-lookups-api
- description: 'The New Relic Security Data API allows vulnerability and security finding data to be sent directly to New Relic via HTTP POST. It accepts JSON payloads describing detected vulnerabilities or security '
  name: New Relic Security Data API
  slug: new-relic-security-data-api
- description: The New Relic Mobile SDK provides iOS and Android APIs for extending mobile monitoring data collection beyond what the agent captures automatically. Developers can add custom attributes, record custom
  name: New Relic Mobile SDK
  slug: new-relic-mobile-sdk
capabilities:
- description: Application performance monitoring workflow combining application metrics, deployments, hosts, and custom events for developers tracking application health and release impact.
  name: New Relic Application Monitoring
  slug: application-monitoring
- description: Alert policy and condition management workflow for platform admins configuring and maintaining New Relic alerting rules, notification channels, and policy structures.
  name: New Relic Alerting Configuration
  slug: full-stack-observability
- description: Incident response workflow combining alerts, incidents, violations, and events for SREs investigating and resolving production issues detected by New Relic.
  name: New Relic Incident Response
  slug: incident-response
- description: Telemetry data ingestion workflow combining event, log, metric, and trace APIs for ops engineers sending observability data to New Relic from external sources.
  name: New Relic Telemetry Ingestion
  slug: telemetry-ingestion
common:
- title: ''
  type: Portal
  url: https://newrelic.com/
- title: ''
  type: Pricing
  url: https://newrelic.com/pricing
- title: ''
  type: Documentation
  url: https://docs.newrelic.com/
- title: ''
  type: TermsOfService
  url: https://newrelic.com/termsandconditions/terms
- title: ''
  type: PrivacyPolicy
  url: https://newrelic.com/termsandconditions/privacy
- title: ''
  type: Blog
  url: https://newrelic.com/blog
- title: ''
  type: Partners
  url: https://newrelic.com/solutions/partners
- title: ''
  type: TrustCenter
  url: https://trust.newrelic.com/
- title: ''
  type: Login
  url: https://login.newrelic.com/login
- title: ''
  type: SignUp
  url: https://newrelic.com/signup
- title: ''
  type: Console
  url: https://one.newrelic.com/
- title: ''
  type: Portal
  url: https://developer.newrelic.com/
- title: ''
  type: Authentication
  url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/
- title: ''
  type: Support
  url: https://support.newrelic.com/
- title: ''
  type: StatusPage
  url: https://status.newrelic.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/newrelic
- title: ''
  type: Support
  url: https://discuss.newrelic.com/
- title: ''
  type: GettingStarted
  url: https://docs.newrelic.com/docs/new-relic-solutions/get-started/intro-new-relic/
- title: ''
  type: ChangeLog
  url: https://docs.newrelic.com/whats-new/
- title: ''
  type: ChangeLog
  url: https://docs.newrelic.com/docs/release-notes/
- title: ''
  type: RateLimits
  url: https://docs.newrelic.com/docs/data-apis/manage-data/view-system-limits/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/new-relic
- title: ''
  type: GitHubOrganization
  url: https://opensource.newrelic.com/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@NewRelicInc
- title: ''
  type: JSON-LD
  url: json-ld/new-relic-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/new-relic-metric-payload-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/new-relic-event-payload-schema.json
- title: ''
  type: X
  url: https://twitter.com/newrelic
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/new-relic-inc-
- title: ''
  type: Security
  url: https://newrelic.com/security
- title: ''
  type: Security
  url: https://newrelic.com/security/compliance-certifications
- title: ''
  type: CLI
  url: https://github.com/newrelic/newrelic-cli
- title: ''
  type: CLI
  url: https://docs.newrelic.com/docs/new-relic-solutions/build-nr-ui/newrelic-cli/
- title: ''
  type: GitHubRepository
  url: https://registry.terraform.io/providers/newrelic/newrelic/latest/docs
- title: ''
  type: GitHubRepository
  url: https://github.com/newrelic/terraform-provider-newrelic
- title: ''
  type: Resources
  url: https://www.postman.com/new-relic/
- title: ''
  type: Documentation
  url: https://docs.newrelic.com/docs/apis/intro-apis/introduction-new-relic-apis/
- title: ''
  type: Documentation
  url: https://docs.newrelic.com/docs/nrql/get-started/introduction-nrql-new-relics-query-language/
- title: Java Agent
  type: SDK
  url: https://github.com/newrelic/newrelic-java-agent
- title: Python Agent
  type: SDK
  url: https://github.com/newrelic/newrelic-python-agent
- title: Node.js Agent
  type: SDK
  url: https://github.com/newrelic/node-newrelic
- title: Go Agent
  type: SDK
  url: https://github.com/newrelic/go-agent
- title: .NET Agent
  type: SDK
  url: https://github.com/newrelic/newrelic-dotnet-agent
- title: Ruby Agent
  type: SDK
  url: https://github.com/newrelic/newrelic-ruby-agent
- title: PHP Agent
  type: SDK
  url: https://github.com/newrelic/newrelic-php-agent
- title: ''
  type: SDK
  url: https://github.com/newrelic/infrastructure-agent
- title: ''
  type: GitHubRepository
  url: https://github.com/newrelic/helm-charts
- title: ''
  type: CodeExamples
  url: https://github.com/newrelic/newrelic-opentelemetry-examples
- title: ''
  type: SpectralRules
  url: rules/new-relic-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/new-relic-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/application-monitoring.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/full-stack-observability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/telemetry-ingestion.yaml
created: '2025-01-13'
description: New Relic provides observability platform APIs for monitoring, analyzing, and optimizing your entire software stack with real-time insights into applications, infrastructure, and customer experience.
features:
- description: Monitor application performance with real-time metrics, error tracking, and transaction tracing across distributed systems.
  name: Application Performance Monitoring
- description: Monitor hosts, containers, cloud services, and on-premise infrastructure with automatic discovery and configuration.
  name: Infrastructure Monitoring
- description: Collect, search, and analyze log data at scale with structured logging, pattern detection, and correlation to traces and metrics.
  name: Log Management
- description: Trace requests across microservices and distributed systems to identify bottlenecks and optimize performance.
  name: Distributed Tracing
- description: Proactively monitor application availability and performance with scripted browser tests, API checks, and ping monitors.
  name: Synthetic Monitoring
- description: Capture real user experience data including page load times, JavaScript errors, and AJAX performance for web applications.
  name: Browser Monitoring
- description: Monitor mobile application performance, crashes, HTTP requests, and user interactions for iOS and Android apps.
  name: Mobile Monitoring
- description: Monitor network performance with flow data analysis, SNMP polling, and cloud network telemetry.
  name: Network Monitoring
- description: Monitor Kubernetes clusters, pods, containers, and workloads with automatic instrumentation and Pixie integration.
  name: Kubernetes Monitoring
- description: Monitor AWS Lambda, Azure Functions, and other serverless compute with invocation tracking and cold start analysis.
  name: Serverless Monitoring
- description: Use machine learning to detect anomalies, correlate incidents, and reduce alert noise with intelligent alerting.
  name: AIOps and Applied Intelligence
- description: Build custom dashboards with NRQL-powered charts, widgets, and real-time data visualization.
  name: Dashboards and Visualization
- description: Query all telemetry data with NRQL, a SQL-like query language for metrics, events, logs, and traces.
  name: NRQL Query Language
- description: Track, triage, and resolve application errors across the full stack with error grouping and assignment workflows.
  name: Errors Inbox
- description: Identify and prioritize security vulnerabilities in application dependencies and runtime environments.
  name: Vulnerability Management
- description: Define, track, and report on service level objectives and indicators to measure reliability.
  name: Service Level Management
- description: Track deployments and configuration changes to correlate performance shifts with code and infrastructure changes.
  name: Change Tracking
image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png
integrations:
- description: Monitor AWS services including EC2, Lambda, RDS, S3, ECS, EKS, and CloudWatch with native integration.
  name: Amazon Web Services
- description: Monitor Azure services including VMs, App Service, Functions, AKS, and Azure Monitor with native integration.
  name: Microsoft Azure
- description: Monitor GCP services including Compute Engine, Cloud Functions, GKE, BigQuery, and Cloud Monitoring.
  name: Google Cloud Platform
- description: Monitor Kubernetes clusters with automatic discovery, Pixie integration, and OpenTelemetry support.
  name: Kubernetes
- description: Ingest Prometheus metrics using remote write or the Prometheus OpenMetrics integration.
  name: Prometheus
- description: Native OTLP endpoint support for ingesting metrics, traces, and logs from OpenTelemetry-instrumented applications.
  name: OpenTelemetry
- description: Provision and manage New Relic resources as code using the official Terraform provider.
  name: Terraform
- description: Query New Relic data from Grafana dashboards using the Grafana data source plugin.
  name: Grafana
- description: Send alert notifications to PagerDuty for incident management and on-call escalation.
  name: PagerDuty
- description: Receive alert notifications and share observability insights directly in Slack channels.
  name: Slack
- description: Create Jira issues from New Relic errors and alerts for issue tracking and resolution workflows.
  name: Jira
- description: Integrate with ServiceNow for ITSM workflows, incident creation, and change management.
  name: ServiceNow
- description: Connect repositories for code-level visibility, error linking, and deployment tracking via CodeStream.
  name: GitHub
- description: Monitor Docker containers with automatic instrumentation and container-level metrics.
  name: Docker
- description: Monitor Kafka clusters, topics, consumer groups, and message throughput.
  name: Apache Kafka
- description: Monitor MySQL database performance with query analysis, connection tracking, and replication metrics.
  name: MySQL
- description: Monitor PostgreSQL database performance with query analysis, index usage, and connection metrics.
  name: PostgreSQL
- description: Monitor MongoDB instances with query performance, replication status, and cluster metrics.
  name: MongoDB
- description: Monitor Redis instances with memory usage, command statistics, and key metrics.
  name: Redis
- description: Monitor Nginx web server performance with request rates, error rates, and upstream metrics.
  name: Nginx
jsonld:
- class_count: 0
  name: New Relic Context
  property_count: 88
  slug: new-relic-context
- class_count: 2
  name: New Relic Event Api Context
  property_count: 4
  slug: new-relic-event-api-context
- class_count: 0
  name: New Relic Event Context
  property_count: 3
  slug: new-relic-event-context
- class_count: 4
  name: New Relic Log Api Context
  property_count: 8
  slug: new-relic-log-api-context
- class_count: 0
  name: New Relic Log Context
  property_count: 5
  slug: new-relic-log-context
- class_count: 6
  name: New Relic Metric Api Context
  property_count: 12
  slug: new-relic-metric-api-context
- class_count: 0
  name: New Relic Metric Context
  property_count: 6
  slug: new-relic-metric-context
- class_count: 90
  name: New Relic Openapi Context
  property_count: 122
  slug: new-relic-openapi-context
- class_count: 6
  name: New Relic Trace Api Context
  property_count: 15
  slug: new-relic-trace-api-context
- class_count: 0
  name: New Relic Trace Context
  property_count: 6
  slug: new-relic-trace-context
layout: provider
modified: '2026-04-18'
name: New Relic
rules:
- name: New Relic API Rules
  rule_count: 21
  severity_counts:
    error: 19
    hint: 0
    info: 1
    warn: 1
  slug: new-relic-spectral-rules
skills: []
slug: new-relic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: new-relic\nurl: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/apis.yml\napis:\n- aid: new-relic:new-relic-rest-api-v2\n  name: New Relic REST API v2\n  description: >-\n    The New Relic REST API v2 is the original HTTP REST interface for querying\n    application performance data, configuring alerts, and managing account\n    settings. New Relic recommends NerdGraph (GraphQL) for new integrations,\n    as the REST API v2 is in maintenance mode with minimal ongoing development.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/apis/rest-api-v2/get-started/introduction-new-relic-rest-api-v2/\n  baseURL: https://api.newrelic.com/v2/\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/apis/rest-api-v2/get-started/introduction-new-relic-rest-api-v2/\n  - type: OpenAPI\n    url: openapi/new-relic-openapi.yml\n  - type: Authentication\n\
  \    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/apis/rest-api-v2/api-explorer-v2/introduction-new-relics-rest-api-explorer/\n  - type: JSONSchema\n    url: json-schema/openapi-mobile-application-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-synthetics-condition-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-metric-parser-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-external-service-condition-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-label-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-label-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-external-service-condition-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-metric-data-response-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/openapi-policy-channels-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-deployment-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-instance-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-app-summary-data-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-deployment-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-browser-application-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-app-summary-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-policy-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-instance-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-policy-channels-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-incident-response-type-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/openapi-channel-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-channel-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-label-origins-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-violation-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-app-settings-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-condition-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-deployment-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-incident-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-metric-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-metric-data-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-key-transaction-response-schema.json\n  - type: JSONSchema\n\
  \    url: json-schema/openapi-mobile-application-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-condition-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-label-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-policy-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-instance-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-ijkterms-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-violation-entity-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-recent-event-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-external-service-condition-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-label-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-deployment-response-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/openapi-nrql-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-browser-application-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-browser-application-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-channel-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-incident-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-condition-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-timeslice-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-violation-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-end-user-summary-data-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-condition-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-metric-list-response-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/openapi-application-host-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-channel-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-external-service-condition-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-channel-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-nrql-condition-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-synthetics-condition-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-policy-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-end-user-summary-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-synthetics-condition-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-host-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-browser-application-response-schema.json\n  - type: JSONSchema\n\
  \    url: json-schema/openapi-nrql-condition-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-key-transaction-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-metric-parser-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-nrql-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-host-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-app-settings-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-nrql-condition-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-violation-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-key-transaction-links-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-recent-event-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-synthetics-condition-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-user-defined-condition-body-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/openapi-user-defined-condition-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-deployment-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-nrql-condition-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-crash-summary-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-policy-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-label-response-type-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-application-response-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-label-links-body-schema.json\n  - type: JSONSchema\n    url: json-schema/openapi-mobile-summary-data-response-schema.json\n  - type: JSONLD\n    url: json-ld/new-relic-openapi-context.jsonld\n  tags:\n  - APM\n  - Applications\n  - Monitoring\n  - REST\n- aid: new-relic:new-relic-nerdgraph-api\n  name: New Relic NerdGraph API\n  description: >-\n    NerdGraph\
  \ is New Relic's primary GraphQL API for querying observability data,\n    managing account configuration, and accessing the full breadth of New Relic\n    platform capabilities. It is the recommended API for new integrations, replacing\n    the older REST API v2 for most use cases.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/\n  baseURL: https://api.newrelic.com/graphql\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/apis/nerdgraph/get-started/nerdgraph-explorer/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  - type: RateLimits\n    url: https://docs.newrelic.com/docs/apis/nerdgraph/nerdgraph-usage-limits/\n  - type:\
  \ GettingStarted\n    url: https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/\n  - type: Console\n    url: https://api.newrelic.com/graphiql\n  - type: Resources\n    url: https://www.postman.com/new-relic/new-relic-graphql-api-collection/documentation/btuxnnc/new-relic-nerdgraph-graphql-api-collection\n  tags:\n  - GraphQL\n  - Monitoring\n  - Observability\n  - Platform\n- aid: new-relic:new-relic-metric-api\n  name: New Relic Metric API\n  description: >-\n    The New Relic Metric API is an HTTP endpoint for ingesting dimensional metric\n    data directly into the New Relic platform. It accepts JSON payloads via POST\n    requests and is the underlying API used by Telemetry SDKs and open source\n    exporters such as Prometheus and DropWizard.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/introduction-metric-api/\n  baseURL:\
  \ https://metric-api.newrelic.com/metric/v1\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/introduction-metric-api/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/report-metrics-metric-api/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  - type: RateLimits\n    url: https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/metric-api-limits-restricted-attributes/\n  - type: OpenAPI\n    url: openapi/new-relic-metric-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/new-relic-metric-payload-schema.json\n  - type: JSONSchema\n    url: json-schema/metric-api-common-block-schema.json\n  - type: JSONSchema\n    url: json-schema/metric-api-summary-value-schema.json\n  - type: JSONSchema\n    url: json-schema/metric-api-metric-data-object-schema.json\n  - type: JSONSchema\n    url: json-schema/metric-api-metric-data-point-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/metric-api-metric-payload-schema.json\n  - type: JSONSchema\n    url: json-schema/metric-api-accepted-response-schema.json\n  - type: JSONLD\n    url: json-ld/new-relic-metric-api-context.jsonld\n  tags:\n  - Ingest\n  - Metrics\n  - Monitoring\n  - Telemetry\n- aid: new-relic:new-relic-event-api\n  name: New Relic Event API\n  description: >-\n    The New Relic Event API allows you to send custom event data to the New Relic\n    platform via HTTP POST. Custom events submitted through this API can be queried\n    and visualized using NRQL, making it suitable for tracking arbitrary business\n    or application events.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/data-apis/ingest-apis/event-api/introduction-event-api/\n  baseURL: https://insights-collector.newrelic.com/v1/accounts\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/data-apis/ingest-apis/event-api/introduction-event-api/\n\
  \  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  - type: OpenAPI\n    url: openapi/new-relic-event-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/new-relic-event-payload-schema.json\n  - type: RateLimits\n    url: https://docs.newrelic.com/docs/data-apis/custom-data/custom-events/data-requirements-limits-custom-event-data/\n  - type: JSONSchema\n    url: json-schema/event-api-success-response-schema.json\n  - type: JSONSchema\n    url: json-schema/event-api-custom-event-schema.json\n  - type: JSONSchema\n    url: json-schema/event-api-event-payload-schema.json\n  - type: JSONLD\n    url: json-ld/new-relic-event-api-context.jsonld\n  tags:\n  - Custom Data\n  - Events\n  - Ingest\n  - Telemetry\n- aid: new-relic:new-relic-log-api\n  name: New Relic Log API\n  description: >-\n    The New Relic Log API enables log data to be sent directly to the New Relic\n    platform via HTTP POST requests. It accepts compressed JSON\
  \ payloads and provides\n    an alternative to log forwarding agents when direct integration is preferred.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/logs/log-api/introduction-log-api/\n  baseURL: https://log-api.newrelic.com/log/v1\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/logs/log-api/introduction-log-api/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/logs/forward-logs/enable-log-management-new-relic/\n  - type: OpenAPI\n    url: openapi/new-relic-log-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/log-api-log-data-object-schema.json\n  - type: JSONSchema\n    url: json-schema/log-api-accepted-response-schema.json\n  - type: JSONSchema\n    url: json-schema/log-api-log-record-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/log-api-common-block-schema.json\n  - type: JSONSchema\n    url: json-schema/log-api-log-payload-schema.json\n  - type: JSONLD\n    url: json-ld/new-relic-log-api-context.jsonld\n  tags:\n  - Ingest\n  - Log Management\n  - Logs\n  - Telemetry\n- aid: new-relic:new-relic-trace-api\n  name: New Relic Trace API\n  description: >-\n    The New Relic Trace API allows distributed tracing data to be sent directly\n    to New Relic in either New Relic format or Zipkin JSON v2 format. It is used\n    by Telemetry SDKs, open source integrations, and custom tracing implementations\n    that need to report span data without a full APM agent.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/distributed-tracing/trace-api/introduction-trace-api/\n  baseURL: https://trace-api.newrelic.com/trace/v1\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/distributed-tracing/trace-api/introduction-trace-api/\n\
  \  - type: APIReference\n    url: https://docs.newrelic.com/docs/distributed-tracing/trace-api/trace-api-general-requirements-limits/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  - type: OpenAPI\n    url: openapi/new-relic-trace-api-openapi.yml\n  - type: RateLimits\n    url: https://docs.newrelic.com/docs/distributed-tracing/trace-api/trace-api-general-requirements-limits/\n  - type: JSONSchema\n    url: json-schema/trace-api-new-relic-trace-payload-schema.json\n  - type: JSONSchema\n    url: json-schema/trace-api-accepted-response-schema.json\n  - type: JSONSchema\n    url: json-schema/trace-api-common-block-schema.json\n  - type: JSONSchema\n    url: json-schema/trace-api-zipkin-span-schema.json\n  - type: JSONSchema\n    url: json-schema/trace-api-span-schema.json\n  - type: JSONSchema\n    url: json-schema/trace-api-zipkin-trace-payload-schema.json\n  - type: JSONSchema\n    url: json-schema/trace-api-span-batch-schema.json\n\
  \  - type: JSONLD\n    url: json-ld/new-relic-trace-api-context.jsonld\n  tags:\n  - Distributed Tracing\n  - Ingest\n  - Telemetry\n  - Traces\n- aid: new-relic:new-relic-alerts-api\n  name: New Relic Alerts API\n  description: >-\n    The New Relic Alerts REST API provides endpoints for programmatically managing\n    alert policies, conditions, notification channels, and muting rules. New Relic\n    recommends using NerdGraph for new alert management integrations, as the REST\n    Alerts API is in maintenance mode.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/alerts/scale-automate/rest-api/rest-api-calls-alerts/\n  baseURL: https://api.newrelic.com/v2/\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/alerts/scale-automate/rest-api/rest-api-calls-alerts/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  tags:\n\
  \  - Alerts\n  - Monitoring\n  - Notifications\n  - REST\n- aid: new-relic:new-relic-synthetics-api\n  name: New Relic Synthetics API\n  description: >-\n    The New Relic Synthetics API, available through NerdGraph, allows you to\n    programmatically create, update, delete, and query synthetic monitors including\n    ping monitors, scripted API monitors, browser monitors, and broken links monitors.\n    A legacy REST-based Synthetics API is also available but NerdGraph is the recommended approach.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/synthetics/synthetic-monitoring/administration/synthetics-api/\n  baseURL: https://api.newrelic.com/graphql\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/synthetics/synthetic-monitoring/administration/synthetics-api/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/apis/nerdgraph/examples/synthetics-api/overview/\n\
  \  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  tags:\n  - Monitoring\n  - Synthetics\n  - Testing\n  - Uptime Monitoring\n- aid: new-relic:new-relic-infrastructure-alerts-api\n  name: New Relic Infrastructure Alerts API\n  description: >-\n    The New Relic Infrastructure Alerts REST API provides endpoints for creating\n    and managing infrastructure-specific alert conditions such as host, process,\n    and integration alert conditions. It uses the infra-api.newrelic.com endpoint\n    and is separate from the general Alerts REST API.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/infrastructure/infrastructure-alerts/rest-api-calls-new-relic-infrastructure-alerts/\n  baseURL: https://infra-api.newrelic.com/v2/\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/infrastructure/infrastructure-alerts/rest-api-calls-new-relic-infrastructure-alerts/\n\
  \  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  tags:\n  - Alerts\n  - Infrastructure\n  - Monitoring\n  - REST\n- aid: new-relic:new-relic-browser-api\n  name: New Relic Browser API\n  description: >-\n    The New Relic Browser API provides JavaScript methods for extending and\n    customizing browser monitoring data collection within the New Relic browser\n    agent. Developers can use it to add custom attributes, record custom events,\n    track page actions, and control agent behavior programmatically.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/browser/new-relic-browser/browser-apis/using-browser-apis/\n  baseURL: https://bam.nr-data.net\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/browser/new-relic-browser/browser-apis/using-browser-apis/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n\
  \  - type: SDK\n    url: https://github.com/newrelic/newrelic-browser-agent\n    title: Browser Agent SDK\n  tags:\n  - Browser\n  - JavaScript\n  - Monitoring\n  - Real User Monitoring\n- aid: new-relic:new-relic-partnership-api\n  name: New Relic Partnership API\n  description: >-\n    The New Relic Partnership API is a web service API for New Relic partners that\n    enables them to create, edit, upgrade, downgrade, and cancel New Relic accounts\n    on behalf of their customers. It is available only to New Relic partner accounts\n    with partnership-level access.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/new-relic-partnerships/partner-integration-guide/partner-account-maintenance/partner-api/\n  baseURL: https://rpm.newrelic.com/api/v2/partners/\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/new-relic-partnerships/partner-integration-guide/partner-account-maintenance/partner-api/\n\
  \  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  tags:\n  - Account Management\n  - Partners\n  - Platform\n- aid: new-relic:new-relic-telemetry-sdk\n  name: New Relic Telemetry SDKs\n  description: >-\n    The New Relic Telemetry SDKs are open source client libraries for sending\n    metrics, events, logs, and traces (MELT) to New Relic using the ingest APIs.\n    SDKs are available for Java, Python, Node.js, Go, .NET, and C, and are\n    released under the Apache 2.0 license on GitHub.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/data-apis/ingest-apis/telemetry-sdks-report-custom-telemetry-data/\n  baseURL: https://metric-api.newrelic.com\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/data-apis/ingest-apis/telemetry-sdks-report-custom-telemetry-data/\n  - type: SDK\n    url: https://docs.newrelic.com/docs/data-apis/ingest-apis/telemetry-sdks-report-custom-telemetry-data/\n\
  \  - type: GitHubRepository\n    url: https://github.com/newrelic/newrelic-telemetry-sdk-java\n  - type: SDK\n    url: https://github.com/newrelic/newrelic-telemetry-sdk-python\n    title: Python Telemetry SDK\n  - type: SDK\n    url: https://github.com/newrelic/newrelic-telemetry-sdk-go\n    title: Go Telemetry SDK\n  - type: SDK\n    url: https://github.com/newrelic/newrelic-telemetry-sdk-dotnet\n    title: .NET Telemetry SDK\n  tags:\n  - Client Libraries\n  - Open Source\n  - SDKs\n  - Telemetry\n- aid: new-relic:new-relic-opentelemetry-otlp\n  name: New Relic OpenTelemetry OTLP Endpoint\n  description: >-\n    New Relic provides a native OTLP (OpenTelemetry Protocol) endpoint that accepts\n    metrics, traces, and logs from any OpenTelemetry-instrumented application or\n    OTLP exporter. It supports both gRPC and HTTP/protobuf transport and is the\n    recommended integration path for OpenTelemetry users.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n\
  \  humanURL: https://docs.newrelic.com/docs/opentelemetry/best-practices/opentelemetry-otlp/\n  baseURL: https://otlp.nr-data.net\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/opentelemetry/best-practices/opentelemetry-otlp/\n  - type: GettingStarted\n    url: https://docs.newrelic.com/docs/opentelemetry/opentelemetry-introduction/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/opentelemetry/best-practices/opentelemetry-data-overview/\n  tags:\n  - Ingest\n  - OpenTelemetry\n  - OTLP\n  - Telemetry\n- aid: new-relic:new-relic-control\n  name: New Relic Control\n  description: >-\n    New Relic Control is an observability control plane that unifies Fleet Control,\n    Agent Control, and Pipeline Control into a single management layer. It enables\n    DevOps and platform teams to remotely deploy, configure, update, and monitor\n    New Relic agents and OpenTelemetry collectors across Kubernetes clusters and\n    hosts without manual per-host\
  \ intervention. Fleet Control manages agent lifecycles\n    at scale via a remote configuration API.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/new-relic-control/getting-started/\n  baseURL: https://api.newrelic.com\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/new-relic-control/getting-started/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/new-relic-control/fleet-control/overview/\n  - type: GettingStarted\n    url: https://docs.newrelic.com/docs/new-relic-control/getting-started/\n  tags:\n  - Agent Management\n  - Automation\n  - Fleet Control\n  - Observability\n  - Platform\n- aid: new-relic:new-relic-nrql-lookups-api\n  name: New Relic NRQL Lookups API\n  description: >-\n    The New Relic NRQL Lookups API is a REST API for managing lookup tables that\n    can be used to enrich NRQL query results. It supports creating, updating,\n\
  \    downloading, listing, and deleting lookup tables in both CSV and JSON formats,\n    enabling automated lookup table maintenance for data enrichment workflows.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/apis/lookups-service-api/lookups-service-api/\n  baseURL: https://nrql-lookup.service.newrelic.com\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/apis/lookups-service-api/lookups-service-api/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  tags:\n  - Data Enrichment\n  - Lookups\n  - NRQL\n  - REST\n- aid: new-relic:new-relic-security-data-api\n  name: New Relic Security Data API\n  description: >-\n    The New Relic Security Data API allows vulnerability and security finding data\n    to be sent directly to New Relic via HTTP POST. It accepts JSON payloads\n    describing detected vulnerabilities\
  \ or security events, enabling integration\n    with third-party vulnerability assessment tools and custom security scanning\n    solutions for use with New Relic Security RX.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/data-apis/ingest-apis/security-data-api/\n  baseURL: https://security-api.newrelic.com/security/v1\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/data-apis/ingest-apis/security-data-api/\n  - type: Authentication\n    url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  tags:\n  - Compliance\n  - Ingest\n  - Security\n  - Vulnerabilities\n- aid: new-relic:new-relic-mobile-sdk\n  name: New Relic Mobile SDK\n  description: >-\n    The New Relic Mobile SDK provides iOS and Android APIs for extending mobile\n    monitoring data collection beyond what the agent captures automatically. Developers\n    can add custom attributes,\
  \ record custom events, track user interactions, report\n    handled exceptions, set custom user IDs, and control agent behavior within\n    iOS (Swift/Objective-C) and Android (Java/Kotlin) applications.\n  image: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\n  humanURL: https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile/mobile-sdk/mobile-sdk-api-guide/\n  baseURL: https://mobile-collector.newrelic.com\n  properties:\n  - type: Documentation\n    url: https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile/mobile-sdk/mobile-sdk-api-guide/\n  - type: APIReference\n    url: https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile-ios/get-started/introduction-new-relic-mobile-ios/\n  - type: GitHubRepository\n    url: https://github.com/newrelic/newrelic-ios-agent\n  - type: SDK\n    url: https://github.com/newrelic/newrelic-android-agent\n    title: Android Agent SDK\n  - type: SDK\n    url: https://github.com/newrelic/newrelic-unity-agent\n\
  \    title: Unity Agent SDK\n  tags:\n  - Android\n  - iOS\n  - Mobile\n  - Monitoring\n  - SDK\nname: New Relic\ntags:\n- Analysis\n- Analytics\n- APM\n- DevOps\n- Infrastructure\n- Monitoring\n- Observability\n- Performance\n- Platform\ntype: Index\nimage: https://newrelic.com/themes/custom/erno/assets/mediakit/new_relic_logo_horizontal.png\naccess: 3rd-Party\ncreated: '2025-01-13'\nmodified: '2026-04-18'\nposition: Consumer\ndescription: New Relic provides observability platform APIs for monitoring, analyzing, and optimizing your entire software stack with real-time insights into applications, infrastructure, and customer\n  experience.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n- name: New Relic | Monitor, Debug and Improve Your Entire Stack\n  description: 'null'\n  url: https://newrelic.com/\n  type: Portal\n- name: Transparent Pricing - Start for Free | New Relic\n  description: 'null'\n  url: https://newrelic.com/pricing\n\
  \  type: Pricing\n- name: New Relic Documentation\n  description: 'null'\n  url: https://docs.newrelic.com/\n  type: Documentation\n- name: Terms of Service Agreement | New Relic\n  description: 'null'\n  url: https://newrelic.com/termsandconditions/terms\n  type: TermsOfService\n- name: General Data Privacy Notice\n  description: 'null'\n  url: https://newrelic.com/termsandconditions/privacy\n  type: PrivacyPolicy\n- name: The New Relic Blog | New Relic\n  description: 'null'\n  url: https://newrelic.com/blog\n  type: Blog\n- name: New Relic Partner Program | New Relic\n  description: 'null'\n  url: https://newrelic.com/solutions/partners\n  type: Partners\n- name: New Relic Trust Center\n  description: 'null'\n  url: https://trust.newrelic.com/\n  type: TrustCenter\n- name: Log in to New Relic\n  description: 'null'\n  url: https://login.newrelic.com/login\n  type: Login\n- name: Sign Up\n  description: 'null'\n  url: https://newrelic.com/signup\n  type: SignUp\n- url: https://one.newrelic.com/\n\
  \  name: New Relic Platform Console\n  type: Console\n- url: https://developer.newrelic.com/\n  name: New Relic Developer Portal\n  type: Portal\n- url: https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/\n  name: New Relic API Keys\n  type: Authentication\n- url: https://support.newrelic.com/\n  name: New Relic Support\n  type: Support\n- url: https://status.newrelic.com/\n  name: New Relic Status\n  type: StatusPage\n- url: https://github.com/newrelic\n  name: New Relic GitHub Organization\n  type: GitHubOrganization\n- url: https://discuss.newrelic.com/\n  name: New Relic Explorers Hub Community Forum\n  type: Support\n- url: https://docs.newrelic.com/docs/new-relic-solutions/get-started/intro-new-relic/\n  name: Get Started with New Relic\n  type: GettingStarted\n- url: https://docs.newrelic.com/whats-new/\n  name: What's New in New Relic\n  type: ChangeLog\n- url: https://docs.newrelic.com/docs/release-notes/\n  name: New Relic Release Notes\n  type: ChangeLog\n- url:\
  \ https://docs.newrelic.com/docs/data-apis/manage-data/view-system-limits/\n  name: New Relic Data Limits\n  type: RateLimits\n- url: https://stackoverflow.com/questions/tagged/new-relic\n  name: New Relic on Stack Overflow\n  type: StackOverflow\n- url: https://opensource.newrelic.com/\n  name: New Relic Open Source\n  type: GitHubOrganization\n- url: https://www.youtube.com/@NewRelicInc\n  name: New Relic YouTube Channel\n  type: YouTube\n- url: json-ld/new-relic-context.jsonld\n  name: New Relic JSON-LD Context\n  type: JSON-LD\n- url: json-schema/new-relic-metric-payload-schema.json\n  name: New Relic Metric Payload Schema\n  type: JSONSchema\n- url: json-schema/new-relic-event-payload-schema.json\n  name: New Relic Event Payload Schema\n  type: JSONSchema\n- url: https://twitter.com/newrelic\n  name: New Relic on X (Twitter)\n  type: X\n- url: https://www.linkedin.com/company/new-relic-inc-\n  name: New Relic on LinkedIn\n  type: LinkedIn\n- url: https://newrelic.com/security\n  name:\
  \ New Relic Security Overv\n\n# --- truncated at 32 KB (41 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/apis.yml
tags:
- Analysis
- Analytics
- APM
- DevOps
- Infrastructure
- Monitoring
- Observability
- Performance
- Platform
url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/apis.yml
use_cases:
- description: Gain unified visibility across applications, infrastructure, and digital experiences to quickly identify and resolve issues.
  name: Full-Stack Observability
- description: Monitor and validate cloud migration progress with baseline comparisons and performance tracking across hybrid environments.
  name: Cloud Migration Monitoring
- description: Integrate observability into development workflows with deployment markers, error tracking, and automated testing.
  name: DevOps and CI/CD Integration
- description: Define and track SLOs, manage error budgets, and implement reliability practices with data-driven insights.
  name: Site Reliability Engineering
- description: Detect, diagnose, and resolve incidents faster with correlated telemetry, anomaly detection, and automated workflows.
  name: Incident Response and Management
- description: Measure and optimize end-user experience across web, mobile, and synthetic channels.
  name: Digital Experience Monitoring
- description: Analyze resource utilization trends and forecast capacity needs to optimize infrastructure spending.
  name: Capacity Planning
- description: Maintain audit trails, security compliance, and data governance across observability data.
  name: Compliance and Audit
---
