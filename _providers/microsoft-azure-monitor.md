---
api_count: 15
api_specs:
- filename: metrics_API.json
  format: json
  label: Azure Monitor Metrics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metrics_API.json
- filename: metricDefinitions_API.json
  format: json
  label: Azure Monitor Metric Definitions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metricDefinitions_API.json
- filename: azure-monitor-metrics-batch-openapi.yml
  format: yaml
  label: Azure Monitor Metrics Batch API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/openapi/azure-monitor-metrics-batch-openapi.yml
- filename: OperationalInsights.json
  format: json
  label: Azure Monitor Logs API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/operationalinsights/data-plane/Microsoft.OperationalInsights/stable/2022-10-27/OperationalInsights.json
- filename: azure-monitor-logs-ingestion-openapi.yml
  format: yaml
  label: Azure Monitor Logs Ingestion API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/openapi/azure-monitor-logs-ingestion-openapi.yml
- filename: alertRules_API.json
  format: json
  label: Azure Monitor Alerts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2016-03-01/alertRules_API.json
- filename: scheduledQueryRule_API.json
  format: json
  label: Azure Monitor Scheduled Query Rules API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-08-01/scheduledQueryRule_API.json
- filename: actionGroups_API.json
  format: json
  label: Azure Monitor Action Groups API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-06-01/actionGroups_API.json
- filename: autoscale_API.json
  format: json
  label: Azure Monitor Autoscale API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-10-01/autoscale_API.json
- filename: AppInsights.json
  format: json
  label: Azure Application Insights API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/applicationinsights/data-plane/Microsoft.Insights/stable/v1/AppInsights.json
- filename: diagnosticsSettings_API.json
  format: json
  label: Azure Monitor Diagnostic Settings API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-05-01-preview/diagnosticsSettings_API.json
- filename: activityLogs_API.json
  format: json
  label: Azure Monitor Activity Log API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2015-04-01/activityLogs_API.json
- filename: dataCollectionRules_API.json
  format: json
  label: Azure Monitor Data Collection Rules API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionRules_API.json
- filename: dataCollectionEndpoints_API.json
  format: json
  label: Azure Monitor Data Collection Endpoints API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionEndpoints_API.json
- filename: azure-monitor-private-link-scopes-openapi.yml
  format: yaml
  label: Azure Monitor Private Link Scopes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/openapi/azure-monitor-private-link-scopes-openapi.yml
apis:
- description: Provides access to Azure Monitor platform metric definitions and values for Azure resources, including performance counters, custom metrics, and time-series data.
  name: Azure Monitor Metrics API
  slug: ''
- description: Retrieves the list of available metric definitions for a given Azure resource, including metric names, units, aggregation types, and dimensions.
  name: Azure Monitor Metric Definitions API
  slug: ''
- description: A high-volume API designed for retrieving metric values across multiple Azure resources in a single request. All resources in a batch must be in the same subscription and region.
  name: Azure Monitor Metrics Batch API
  slug: ''
- description: Query and retrieve log data from Azure Monitor Logs and Application Insights using the Kusto Query Language (KQL).
  name: Azure Monitor Logs API
  slug: ''
- description: Sends custom log data to a Log Analytics workspace using a REST API call or client libraries. Supports sending data to both supported Azure tables and custom tables via data collection rules and endpo
  name: Azure Monitor Logs Ingestion API
  slug: ''
- description: Create, update, and manage alert rules and action groups for monitoring Azure resources. Supports metric alerts, log search alerts, and activity log alerts.
  name: Azure Monitor Alerts API
  slug: ''
- description: Create and manage log search alert rules that automatically evaluate log queries at regular intervals and fire alerts when conditions are met.
  name: Azure Monitor Scheduled Query Rules API
  slug: ''
- description: Create and manage action groups that define notification and automation actions triggered by Azure Monitor alerts, including email, SMS, webhooks, and Azure Functions.
  name: Azure Monitor Action Groups API
  slug: ''
- description: Configure autoscale settings for Azure resources based on metric thresholds, schedules, or predictive rules to automatically adjust resource capacity.
  name: Azure Monitor Autoscale API
  slug: ''
- description: Access Application Insights telemetry data including requests, dependencies, exceptions, traces, and custom events for application performance monitoring.
  name: Azure Application Insights API
  slug: ''
- description: Configure diagnostic settings to route platform logs and metrics from Azure resources to destinations such as Log Analytics workspaces, Storage Accounts, and Event Hubs.
  name: Azure Monitor Diagnostic Settings API
  slug: ''
- description: Access Azure Activity Log events for subscription-level operations including resource creation, updates, deletions, and administrative actions.
  name: Azure Monitor Activity Log API
  slug: ''
- description: Create and manage data collection rules that define how data is collected, transformed, and routed to destinations within Azure Monitor.
  name: Azure Monitor Data Collection Rules API
  slug: ''
- description: Create and manage data collection endpoints that provide unique ingestion and configuration endpoints for data collection in Azure Monitor.
  name: Azure Monitor Data Collection Endpoints API
  slug: ''
- description: Create and manage Azure Monitor Private Link Scopes to connect Azure Monitor resources to private endpoints, enabling secure network access to monitoring data.
  name: Azure Monitor Private Link Scopes API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/azure-monitor/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/azure-monitor/overview
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/access-api
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/topics/monitor/
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/whats-new
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/azure-monitor/app/platforms
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/monitor/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://azure.microsoft.com/en-us/explore/trusted-cloud/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Community
  url: https://techcommunity.microsoft.com/t5/azure-monitor/bd-p/AzureMonitor
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/monitor
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free
- title: ''
  type: JSON-LD
  url: json-ld/azure-monitor-context.jsonld
created: '2024'
description: Azure Monitor helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.
features: []
image: https://azure.microsoft.com/svghandler/monitor/
integrations: []
jsonld:
- class_count: 0
  name: Azure Monitor Context
  property_count: 13
  slug: azure-monitor-context
layout: provider
modified: '2026-04-28'
name: Azure Monitor
skills: []
slug: microsoft-azure-monitor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Monitor\ndescription: >-\n  Azure Monitor helps you maximize the availability and performance of your\n  applications and services. It delivers a comprehensive solution for collecting,\n  analyzing, and acting on telemetry from your cloud and on-premises\n  environments.\nimage: https://azure.microsoft.com/svghandler/monitor/\ntags:\n  - Application Insights\n  - Cloud\n  - Logs\n  - Metrics\n  - Monitoring\n  - Observability\ncreated: '2024'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/monitor/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Monitor Metrics API\n    description: >-\n      Provides access to Azure Monitor platform metric definitions and values for\n      Azure resources, including performance counters, custom metrics, and\n      time-series data.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported\n    baseURL:\
  \ https://management.azure.com\n    tags:\n      - Metrics\n      - Performance\n      - Resource Monitoring\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/metrics\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metrics_API.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-metrics-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-metric-schema.json\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/rest-api-walkthrough\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/rest-api-walkthrough\n  - name: Azure Monitor Metric Definitions API\n    description: >-\n      Retrieves the list of available metric definitions for\
  \ a given Azure\n      resource, including metric names, units, aggregation types, and dimensions.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions\n    baseURL: https://management.azure.com\n    tags:\n      - Definitions\n      - Metadata\n      - Metrics\n      - Resource Monitoring\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/metric-definitions\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-10-01/metricDefinitions_API.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-metric-definitions-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-metric-definition-schema.json\n  - name: Azure Monitor Metrics Batch API\n    description: >-\n      A high-volume API designed\
  \ for retrieving metric values across multiple Azure\n      resources in a single request. All resources in a batch must be in the same\n      subscription and region.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch\n    baseURL: https://management.azure.com\n    tags:\n      - Batch\n      - High Volume\n      - Metrics\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/metrics-batch\n      - type: OpenAPI\n        url: openapi/azure-monitor-metrics-batch-openapi.yml\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/migrate-to-batch-api\n  - name: Azure Monitor Logs API\n    description: >-\n      Query and retrieve log data from Azure Monitor Logs and Application Insights\n      using the Kusto Query Language (KQL).\n    image: https://azure.microsoft.com/svghandler/monitor/\n\
  \    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview\n    baseURL: https://api.loganalytics.io\n    tags:\n      - Analytics\n      - KQL\n      - Logs\n      - Query\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/loganalytics/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/operationalinsights/data-plane/Microsoft.OperationalInsights/stable/2022-10-27/OperationalInsights.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-logs-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-log-query-schema.json\n      - type: Query Language\n        url: https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/overview\n  - name: Azure Monitor Logs Ingestion API\n    description: >-\n  \
  \    Sends custom log data to a Log Analytics workspace using a REST API call or\n      client libraries. Supports sending data to both supported Azure tables and\n      custom tables via data collection rules and endpoints.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Custom Logs\n      - Data Collection\n      - Ingestion\n      - Logs\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-ingestion-api-overview\n      - type: OpenAPI\n        url: openapi/azure-monitor-logs-ingestion-openapi.yml\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-api\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-code\n\
  \  - name: Azure Monitor Alerts API\n    description: >-\n      Create, update, and manage alert rules and action groups for monitoring Azure\n      resources. Supports metric alerts, log search alerts, and activity log\n      alerts.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Action Groups\n      - Alerts\n      - Monitoring\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/alertrules\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2016-03-01/alertRules_API.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-alerts-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-alert-rule-schema.json\n\
  \      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview\n  - name: Azure Monitor Scheduled Query Rules API\n    description: >-\n      Create and manage log search alert rules that automatically evaluate log\n      queries at regular intervals and fire alerts when conditions are met.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules\n    baseURL: https://management.azure.com\n    tags:\n      - Alerts\n      - Automation\n      - Log Search\n      - Scheduled Query\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/scheduledqueryrule-2021-08-01/scheduled-query-rules\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-08-01/scheduledQueryRule_API.json\n\
  \      - type: OpenAPI\n        url: openapi/azure-monitor-scheduled-query-rules-openapi.yml\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-log-api-switch\n  - name: Azure Monitor Action Groups API\n    description: >-\n      Create and manage action groups that define notification and automation\n      actions triggered by Azure Monitor alerts, including email, SMS, webhooks,\n      and Azure Functions.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups\n    baseURL: https://management.azure.com\n    tags:\n      - Action Groups\n      - Automation\n      - Notifications\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/action-groups\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-06-01/actionGroups_API.json\n\
  \      - type: OpenAPI\n        url: openapi/azure-monitor-action-groups-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-action-group-schema.json\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/action-groups\n  - name: Azure Monitor Autoscale API\n    description: >-\n      Configure autoscale settings for Azure resources based on metric thresholds,\n      schedules, or predictive rules to automatically adjust resource capacity.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Autoscale\n      - Capacity Management\n      - Performance\n      - Scaling\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/autoscale-settings\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-10-01/autoscale_API.json\n\
  \      - type: OpenAPI\n        url: openapi/azure-monitor-autoscale-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-autoscale-setting-schema.json\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-best-practices\n  - name: Azure Application Insights API\n    description: >-\n      Access Application Insights telemetry data including requests, dependencies,\n      exceptions, traces, and custom events for application performance\n      monitoring.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview\n    baseURL: https://api.applicationinsights.io\n    tags:\n      - APM\n      - Application Performance\n      - Telemetry\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/application-insights/\n      - type: OpenAPI\n   \
  \     url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/applicationinsights/data-plane/Microsoft.Insights/stable/v1/AppInsights.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-application-insights-openapi.yml\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/app/api-custom-events-metrics\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-enable\n  - name: Azure Monitor Diagnostic Settings API\n    description: >-\n      Configure diagnostic settings to route platform logs and metrics from Azure\n      resources to destinations such as Log Analytics workspaces, Storage\n      Accounts, and Event Hubs.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings\n    baseURL: https://management.azure.com\n    tags:\n      - Configuration\n\
  \      - Diagnostics\n      - Logs\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/diagnostic-settings\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2021-05-01-preview/diagnosticsSettings_API.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-diagnostic-settings-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-diagnostic-setting-schema.json\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings\n  - name: Azure Monitor Activity Log API\n    description: >-\n      Access Azure Activity Log events for subscription-level operations including\n      resource creation, updates, deletions, and administrative actions.\n    image: https://azure.microsoft.com/svghandler/monitor/\n\
  \    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log\n    baseURL: https://management.azure.com\n    tags:\n      - Activity Log\n      - Audit\n      - Compliance\n      - Events\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/activity-logs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2015-04-01/activityLogs_API.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-activity-log-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-activity-log-event-schema.json\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log-schema\n  - name: Azure Monitor Data Collection Rules API\n    description: >-\n      Create and manage data collection rules that define how data is collected,\n\
  \      transformed, and routed to destinations within Azure Monitor.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Configuration\n      - Data Collection\n      - Ingestion\n      - Rules\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/data-collection-rules\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionRules_API.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-data-collection-rules-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-monitor-data-collection-rule-schema.json\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-create-edit\n\
  \  - name: Azure Monitor Data Collection Endpoints API\n    description: >-\n      Create and manage data collection endpoints that provide unique ingestion\n      and configuration endpoints for data collection in Azure Monitor.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Configuration\n      - Data Collection\n      - Endpoints\n      - Ingestion\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/data-collection-endpoints\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2023-03-11/dataCollectionEndpoints_API.json\n      - type: OpenAPI\n        url: openapi/azure-monitor-data-collection-endpoints-openapi.yml\n   \
  \   - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview\n  - name: Azure Monitor Private Link Scopes API\n    description: >-\n      Create and manage Azure Monitor Private Link Scopes to connect Azure Monitor\n      resources to private endpoints, enabling secure network access to monitoring\n      data.\n    image: https://azure.microsoft.com/svghandler/monitor/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-security\n    baseURL: https://management.azure.com\n    tags:\n      - Configuration\n      - Networking\n      - Private Link\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/monitor/private-link-scopes\n      - type: OpenAPI\n        url: openapi/azure-monitor-private-link-scopes-openapi.yml\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-configure\n\
  \      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-design\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/azure-monitor/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/azure-monitor/overview\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/access-api\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/topics/monitor/\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/whats-new\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/azure-monitor/app/platforms\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/monitor/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Terms\
  \ of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://azure.microsoft.com/en-us/explore/trusted-cloud/privacy\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: Community\n    url: https://techcommunity.microsoft.com/t5/azure-monitor/bd-p/AzureMonitor\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/monitor\n  - type: Login\n    url: https://portal.azure.com\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free\n  - type: JSON-LD\n    url: json-ld/azure-monitor-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-monitor/refs/heads/main/apis.yml
tags:
- Application Insights
- Cloud
- Logs
- Metrics
- Monitoring
- Observability
url: https://azure.microsoft.com/en-us/services/monitor/
use_cases: []
---
