---
api_count: 9
apis:
- description: The AppDynamics Controller REST API provides programmatic access to the AppDynamics Controller for retrieving application performance data, managing configurations, and automating monitoring workflows
  name: AppDynamics Controller REST API
  slug: controller-rest-api
- description: 'The AppDynamics Metric and Snapshot API allows developers to retrieve metric data and transaction snapshots from monitored applications. It supports configurable time ranges, data aggregation through '
  name: AppDynamics Metric and Snapshot API
  slug: metric-and-snapshot-api
- description: The AppDynamics Alert and Respond API enables programmatic management of health rules, policies, and actions within the AppDynamics Controller. Developers can create, update, and delete health rules t
  name: AppDynamics Alert and Respond API
  slug: alert-and-respond-api
- description: The AppDynamics Configuration API provides endpoints for managing Controller configuration settings programmatically. It includes Configuration Import and Export capabilities that allow administrators
  name: AppDynamics Configuration API
  slug: configuration-api
- description: The AppDynamics Analytics Events API allows developers to send custom analytics events from external data sources to the AppDynamics Events Service. This API supports creating custom event schemas, pu
  name: AppDynamics Analytics Events API
  slug: analytics-events-api
- description: The AppDynamics Database Agent API provides HTTP endpoints for managing Database Monitoring database Collectors. Developers can programmatically create, retrieve, update, and delete database collector
  name: AppDynamics Database Agent API
  slug: database-agent-api
- description: The AppDynamics Machine Agent API provides HTTP endpoints available at the machine agent for uploading custom metrics to the AppDynamics Controller. Developers can use this API to report custom infras
  name: AppDynamics Machine Agent API
  slug: machine-agent-api
- description: The Cisco Cloud Observability API is the next-generation cloud-native platform for AppDynamics, available through the Cisco DevNet developer portal. It provides REST APIs for managing cloud connection
  name: Cisco Cloud Observability API
  slug: cloud-observability-api
- description: The AppDynamics OAuth Authentication API enables developers to generate short-lived access tokens using the OAuth 2.0 Client Credentials Grant flow. API clients can request access tokens to authentica
  name: AppDynamics OAuth Authentication API
  slug: authentication-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/appdynamics-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/appdynamics-application-model-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/appdynamics-health-rule-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/appdynamics-database-collector-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/appdynamics-analytics-event-schema.json
- title: ''
  type: Documentation
  url: https://docs.appdynamics.com/appd/24.x/24.3/en/extend-cisco-appdynamics/cisco-appdynamics-apis
- title: ''
  type: DeveloperPortal
  url: https://developer.cisco.com/site/appdynamics/
- title: ''
  type: GettingStarted
  url: https://developer.cisco.com/docs/appdynamics/
- title: ''
  type: GitHubOrganization
  url: https://github.com/Appdynamics
- title: ''
  type: Pricing
  url: https://www.appdynamics.com/pricing/
- title: ''
  type: Support
  url: https://www.cisco.com/c/en/us/support/index.html
- title: ''
  type: JSONStructure
  url: json-structure/appdynamics-application-model-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/appdynamics-health-rule-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/appdynamics-database-collector-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/appdynamics-analytics-event-structure.json
- title: ''
  type: Example
  url: examples/appdynamics-application-model-example.json
- title: ''
  type: Example
  url: examples/appdynamics-health-rule-example.json
- title: ''
  type: Example
  url: examples/appdynamics-database-collector-example.json
- title: ''
  type: Example
  url: examples/appdynamics-analytics-event-example.json
created: ''
description: AppDynamics, now part of Cisco, is an application performance monitoring (APM) and observability platform that provides full-stack visibility into application, business, and infrastructure performance. The platform offers REST APIs for controller management, metrics, alerts, analytics events, database monitoring, and the next-generation Cisco Cloud Observability platform.
features:
- description: Full-stack APM with code-level visibility into Java, .NET, Node.js, PHP, Python, Go, and Ruby applications.
  name: Application Performance Monitoring
- description: End-to-end transaction tracing correlating application performance with business outcomes.
  name: Business Transaction Monitoring
- description: Automatic baselining and AI-driven anomaly detection to identify performance degradation.
  name: AI-Powered Anomaly Detection
- description: Server, container, and Kubernetes infrastructure monitoring via Machine Agent.
  name: Infrastructure Monitoring
- description: Database performance monitoring for PostgreSQL, MySQL, MongoDB, Oracle, and more.
  name: Database Monitoring
- description: Custom analytics events ingestion for correlating business data with application performance.
  name: Analytics Events API
- description: Next-generation Cisco Cloud Observability platform with OpenTelemetry support and cloud provider connections.
  name: Cloud Observability
- description: Configurable health rules and automated alerting with policy-based response actions.
  name: Health Rules and Alerting
- description: Import/export configuration for backup, restore, and migration between Controller instances.
  name: Configuration Management API
- description: Short-lived OAuth 2.0 access tokens for secure API authentication via Cisco platform.
  name: OAuth 2.0 Authentication
image: ''
integrations:
- description: Integration with Cisco FSO platform and Thousand Eyes for end-to-end observability.
  name: Cisco Full-Stack Observability
- description: Support for OpenTelemetry metrics ingestion via Cisco Cloud Observability common ingestion pipeline.
  name: OpenTelemetry
- description: Integration with Splunk for log correlation and SIEM.
  name: Splunk
- description: ITSM integration for automated incident and change management.
  name: ServiceNow
- description: Alerting integration for automated on-call notification and incident management.
  name: PagerDuty
- description: Amazon Web Services cloud connection for infrastructure and application monitoring.
  name: AWS
- description: Microsoft Azure cloud connection for cloud-native observability.
  name: Azure
- description: Google Cloud Platform connection for multi-cloud observability.
  name: GCP
jsonld:
- class_count: 0
  name: Appdynamics Context
  property_count: 11
  slug: appdynamics-context
layout: provider
modified: '2026-04-19'
name: AppDynamics
skills: []
slug: appdynamics
solutions: []
tags:
- APM
- Application Performance Monitoring
- Cisco
- Cloud Observability
- DevOps
- Monitoring
- Observability
- OpenTelemetry
url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/apis.yml
use_cases:
- description: Identify and resolve performance bottlenecks at the code level before they impact end users.
  name: Application Performance Optimization
- description: Integrate performance monitoring into CI/CD pipelines using the Controller REST API.
  name: DevOps Integration
- description: Monitor application performance during and after cloud migration using Cloud Observability.
  name: Cloud Migration Monitoring
- description: Correlate application performance data with business metrics using the Analytics Events API.
  name: Business Impact Analysis
- description: Automate incident response workflows by integrating AppDynamics alerting with ticketing systems.
  name: Automated Incident Response
---
