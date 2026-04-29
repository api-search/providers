---
api_count: 9
api_specs:
- filename: appdynamics-controller-rest-api-openapi.yml
  format: yaml
  label: AppDynamics Controller REST API
  slug: controller-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-controller-rest-api-openapi.yml
- filename: appdynamics-metric-and-snapshot-api-openapi.yml
  format: yaml
  label: AppDynamics Metric and Snapshot API
  slug: metric-and-snapshot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-metric-and-snapshot-api-openapi.yml
- filename: appdynamics-alert-and-respond-api-openapi.yml
  format: yaml
  label: AppDynamics Alert and Respond API
  slug: alert-and-respond-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-alert-and-respond-api-openapi.yml
- filename: appdynamics-configuration-api-openapi.yml
  format: yaml
  label: AppDynamics Configuration API
  slug: configuration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-configuration-api-openapi.yml
- filename: appdynamics-analytics-events-api-openapi.yml
  format: yaml
  label: AppDynamics Analytics Events API
  slug: analytics-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-analytics-events-api-openapi.yml
- filename: appdynamics-database-agent-api-openapi.yml
  format: yaml
  label: AppDynamics Database Agent API
  slug: database-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-database-agent-api-openapi.yml
- filename: appdynamics-machine-agent-api-openapi.yml
  format: yaml
  label: AppDynamics Machine Agent API
  slug: machine-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-machine-agent-api-openapi.yml
- filename: appdynamics-cloud-observability-api-openapi.yml
  format: yaml
  label: Cisco Cloud Observability API
  slug: cloud-observability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-cloud-observability-api-openapi.yml
- filename: appdynamics-authentication-api-openapi.yml
  format: yaml
  label: AppDynamics OAuth Authentication API
  slug: authentication-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/openapi/appdynamics-authentication-api-openapi.yml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: appdynamics\nurl: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/apis.yml\nmodified: '2026-04-19'\napis:\n- aid: appdynamics:controller-rest-api\n  name: AppDynamics Controller REST API\n  tags:\n  - Application Performance Monitoring\n  - Metrics\n  - Monitoring\n  - Observability\n  - Snapshots\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis\n  properties:\n  - url: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/using-the-controller-apis\n    type: Documentation\n  - url: openapi/appdynamics-controller-rest-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AppDynamics Controller REST API provides programmatic access to the\n    AppDynamics Controller for retrieving application performance data,\n\
  \    managing configurations, and automating monitoring workflows. The API\n    uses standard HTTP methods and returns data in XML or JSON format, with\n    the base URI pattern of /controller/rest/. Developers can use it to\n    query application metrics, retrieve transaction snapshots, manage\n    business transactions, and access topology information for monitored\n    applications.\n- aid: appdynamics:metric-and-snapshot-api\n  name: AppDynamics Metric and Snapshot API\n  tags:\n  - Metrics\n  - Monitoring\n  - Performance Data\n  - Snapshots\n  - Time Series\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api\n  properties:\n  - url: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis/metric-and-snapshot-api\n    type: Documentation\n  - url: openapi/appdynamics-metric-and-snapshot-api-openapi.yml\n\
  \    type: OpenAPI\n  description: >-\n    The AppDynamics Metric and Snapshot API allows developers to retrieve\n    metric data and transaction snapshots from monitored applications. It\n    supports configurable time ranges, data aggregation through rollup\n    parameters, and access to various metric types including response times,\n    error rates, and call volumes. Developers can retrieve request snapshots\n    for detailed transaction analysis and configure metric retention periods\n    to control how long performance data is stored.\n- aid: appdynamics:alert-and-respond-api\n  name: AppDynamics Alert and Respond API\n  tags:\n  - Alerts\n  - Health Rules\n  - Incident Response\n  - Monitoring\n  - Notifications\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n  properties:\n  - url: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n\
  \    type: Documentation\n  - url: openapi/appdynamics-alert-and-respond-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AppDynamics Alert and Respond API enables programmatic management\n    of health rules, policies, and actions within the AppDynamics Controller.\n    Developers can create, update, and delete health rules that define\n    performance thresholds, configure alerting policies that determine how\n    violations are handled, and set up automated response actions. This API\n    is essential for automating incident response workflows and integrating\n    AppDynamics alerting with external notification and ticketing systems.\n- aid: appdynamics:configuration-api\n  name: AppDynamics Configuration API\n  tags:\n  - Administration\n  - Configuration\n  - Export\n  - Import\n  - Management\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n\
  \  properties:\n  - url: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n    type: Documentation\n  - url: openapi/appdynamics-configuration-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AppDynamics Configuration API provides endpoints for managing\n    Controller configuration settings programmatically. It includes\n    Configuration Import and Export capabilities that allow administrators\n    to back up, restore, and migrate application configurations between\n    Controller instances. Developers can automate the provisioning and\n    management of application monitoring configurations, business\n    transaction detection rules, and other Controller settings through\n    this API.\n- aid: appdynamics:analytics-events-api\n  name: AppDynamics Analytics Events API\n  tags:\n  - Analytics\n  - Business Intelligence\n  - Custom Data\n  - Events\n  - Observability\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \  baseURL: https://api.example.com\n  humanURL: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n  properties:\n  - url: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n    type: Documentation\n  - url: openapi/appdynamics-analytics-events-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AppDynamics Analytics Events API allows developers to send custom\n    analytics events from external data sources to the AppDynamics Events\n    Service. This API supports creating custom event schemas, publishing\n    event data, and querying stored events using the AppDynamics Analytics\n    Query Language (ADQL). It enables organizations to correlate application\n    performance data with custom business metrics and external data sources\n    for deeper operational and business intelligence insights.\n- aid: appdynamics:database-agent-api\n  name: AppDynamics Database Agent API\n  tags:\n  - Collectors\n  - Database\n\
  \  - Database Performance\n  - Monitoring\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n  properties:\n  - url: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n    type: Documentation\n  - url: openapi/appdynamics-database-agent-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AppDynamics Database Agent API provides HTTP endpoints for managing\n    Database Monitoring database Collectors. Developers can programmatically\n    create, retrieve, update, and delete database collectors that monitor\n    the performance and availability of database instances. This API enables\n    automation of database monitoring setup and management, making it\n    possible to scale database visibility across large environments without\n    manual configuration through the Controller\
  \ UI.\n- aid: appdynamics:machine-agent-api\n  name: AppDynamics Machine Agent API\n  tags:\n  - Custom Metrics\n  - Infrastructure\n  - Metrics\n  - Server Monitoring\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n  properties:\n  - url: https://docs.appdynamics.com/appd/23.x/latest/en/extend-appdynamics/appdynamics-apis\n    type: Documentation\n  - url: openapi/appdynamics-machine-agent-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AppDynamics Machine Agent API provides HTTP endpoints available at\n    the machine agent for uploading custom metrics to the AppDynamics\n    Controller. Developers can use this API to report custom infrastructure\n    metrics, hardware metrics, and other machine-level data points that are\n    not captured by the default agent instrumentation. This enables\n    organizations\
  \ to extend their monitoring coverage to include custom\n    system-level metrics and integrate data from third-party monitoring\n    tools.\n- aid: appdynamics:cloud-observability-api\n  name: Cisco Cloud Observability API\n  tags:\n  - AWS\n  - Azure\n  - Cloud\n  - Connections\n  - GCP\n  - Observability\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.cisco.com/docs/appdynamics/\n  properties:\n  - url: https://developer.cisco.com/docs/appdynamics/\n    type: Documentation\n  - url: openapi/appdynamics-cloud-observability-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Cisco Cloud Observability API is the next-generation cloud-native\n    platform for AppDynamics, available through the Cisco DevNet developer\n    portal. It provides REST APIs for managing cloud connections, configuring\n    health rules, running analytics queries, and managing application\n    principals.\
  \ The API supports connections to Amazon Web Services, Microsoft\n    Azure, and Google Cloud Platform, enabling automated cloud monitoring\n    setup and management at scale through OpenAPI-documented endpoints.\n- aid: appdynamics:authentication-api\n  name: AppDynamics OAuth Authentication API\n  tags:\n  - Access Tokens\n  - Authentication\n  - OAuth\n  - Security\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.cisco.com/docs/appdynamics/authentication/\n  properties:\n  - url: https://developer.cisco.com/docs/appdynamics/authentication/\n    type: Documentation\n  - url: openapi/appdynamics-authentication-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AppDynamics OAuth Authentication API enables developers to generate\n    short-lived access tokens using the OAuth 2.0 Client Credentials Grant\n    flow. API clients can request access tokens to authenticate against\n\
  \    AppDynamics APIs securely without using long-lived credentials. This API\n    is used in conjunction with the Cisco Observability Platform to manage\n    API client credentials and control access to the various AppDynamics\n    platform services and endpoints.\ncommon:\n- type: JSON-LD\n  url: json-ld/appdynamics-context.jsonld\n- type: JSONSchema\n  url: json-schema/appdynamics-application-model-schema.json\n- type: JSONSchema\n  url: json-schema/appdynamics-health-rule-schema.json\n- type: JSONSchema\n  url: json-schema/appdynamics-database-collector-schema.json\n- type: JSONSchema\n  url: json-schema/appdynamics-analytics-event-schema.json\n- type: Documentation\n  url: https://docs.appdynamics.com/appd/24.x/24.3/en/extend-cisco-appdynamics/cisco-appdynamics-apis\n- type: DeveloperPortal\n  url: https://developer.cisco.com/site/appdynamics/\n- type: GettingStarted\n  url: https://developer.cisco.com/docs/appdynamics/\n- type: GitHubOrganization\n  url: https://github.com/Appdynamics\n\
  - type: Pricing\n  url: https://www.appdynamics.com/pricing/\n- type: Support\n  url: https://www.cisco.com/c/en/us/support/index.html\n- type: JSONStructure\n  url: json-structure/appdynamics-application-model-structure.json\n- type: JSONStructure\n  url: json-structure/appdynamics-health-rule-structure.json\n- type: JSONStructure\n  url: json-structure/appdynamics-database-collector-structure.json\n- type: JSONStructure\n  url: json-structure/appdynamics-analytics-event-structure.json\n- type: Example\n  url: examples/appdynamics-application-model-example.json\n- type: Example\n  url: examples/appdynamics-health-rule-example.json\n- type: Example\n  url: examples/appdynamics-database-collector-example.json\n- type: Example\n  url: examples/appdynamics-analytics-event-example.json\n- type: Features\n  data:\n  - name: Application Performance Monitoring\n    description: Full-stack APM with code-level visibility into Java, .NET, Node.js, PHP, Python, Go, and Ruby applications.\n  - name:\
  \ Business Transaction Monitoring\n    description: End-to-end transaction tracing correlating application performance with business outcomes.\n  - name: AI-Powered Anomaly Detection\n    description: Automatic baselining and AI-driven anomaly detection to identify performance degradation.\n  - name: Infrastructure Monitoring\n    description: Server, container, and Kubernetes infrastructure monitoring via Machine Agent.\n  - name: Database Monitoring\n    description: Database performance monitoring for PostgreSQL, MySQL, MongoDB, Oracle, and more.\n  - name: Analytics Events API\n    description: Custom analytics events ingestion for correlating business data with application performance.\n  - name: Cloud Observability\n    description: Next-generation Cisco Cloud Observability platform with OpenTelemetry support and cloud provider connections.\n  - name: Health Rules and Alerting\n    description: Configurable health rules and automated alerting with policy-based response actions.\n\
  \  - name: Configuration Management API\n    description: Import/export configuration for backup, restore, and migration between Controller instances.\n  - name: OAuth 2.0 Authentication\n    description: Short-lived OAuth 2.0 access tokens for secure API authentication via Cisco platform.\n- type: UseCases\n  data:\n  - name: Application Performance Optimization\n    description: Identify and resolve performance bottlenecks at the code level before they impact end users.\n  - name: DevOps Integration\n    description: Integrate performance monitoring into CI/CD pipelines using the Controller REST API.\n  - name: Cloud Migration Monitoring\n    description: Monitor application performance during and after cloud migration using Cloud Observability.\n  - name: Business Impact Analysis\n    description: Correlate application performance data with business metrics using the Analytics Events API.\n  - name: Automated Incident Response\n    description: Automate incident response workflows by\
  \ integrating AppDynamics alerting with ticketing systems.\n- type: Integrations\n  data:\n  - name: Cisco Full-Stack Observability\n    description: Integration with Cisco FSO platform and Thousand Eyes for end-to-end observability.\n  - name: OpenTelemetry\n    description: Support for OpenTelemetry metrics ingestion via Cisco Cloud Observability common ingestion pipeline.\n  - name: Splunk\n    description: Integration with Splunk for log correlation and SIEM.\n  - name: ServiceNow\n    description: ITSM integration for automated incident and change management.\n  - name: PagerDuty\n    description: Alerting integration for automated on-call notification and incident management.\n  - name: AWS\n    description: Amazon Web Services cloud connection for infrastructure and application monitoring.\n  - name: Azure\n    description: Microsoft Azure cloud connection for cloud-native observability.\n  - name: GCP\n    description: Google Cloud Platform connection for multi-cloud observability.\n\
  description: >-\n  AppDynamics, now part of Cisco, is an application performance monitoring (APM) and observability platform that provides full-stack visibility into application, business, and infrastructure performance.\n  The platform offers REST APIs for controller management, metrics, alerts, analytics events, database monitoring, and the next-generation Cisco Cloud Observability platform.\nname: AppDynamics\ntags:\n- APM\n- Application Performance Monitoring\n- Cisco\n- Cloud Observability\n- DevOps\n- Monitoring\n- Observability\n- OpenTelemetry\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/appdynamics/refs/heads/main/apis.yml
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
