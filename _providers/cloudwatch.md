---
api_count: 10
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/monitoring/2010-08-01/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch Logs API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/logs/2014-03-28/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch Events API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/events/2015-10-07/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch Application Insights API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/application-insights/2018-11-25/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch Synthetics API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/synthetics/2017-10-11/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch Internet Monitor API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/internetmonitor/2021-06-03/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch RUM API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/rum/2018-05-10/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon CloudWatch Observability Access Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/oam/2022-06-10/openapi.yaml
apis:
- description: Core CloudWatch API for metrics, alarms, and dashboards.
  name: Amazon CloudWatch API
  slug: ''
- description: API for ingesting, storing, and analyzing log data.
  name: Amazon CloudWatch Logs API
  slug: ''
- description: Event-driven architecture for responding to state changes in AWS resources.
  name: Amazon CloudWatch Events API
  slug: ''
- description: Automated monitoring for applications with anomaly detection.
  name: Amazon CloudWatch Application Insights API
  slug: ''
- description: API for creating and managing canaries that continuously monitor endpoints and APIs using synthetic traffic.
  name: Amazon CloudWatch Synthetics API
  slug: ''
- description: API for monitoring internet performance and availability between applications hosted on AWS and end users.
  name: Amazon CloudWatch Internet Monitor API
  slug: ''
- description: API for real user monitoring to collect client-side data about web and mobile application performance from actual user sessions.
  name: Amazon CloudWatch RUM API
  slug: ''
- description: API for creating and managing cross-account observability links between source accounts and monitoring accounts.
  name: Amazon CloudWatch Observability Access Manager API
  slug: ''
- description: API for automatic instrumentation and monitoring of application services with service level objectives.
  name: Amazon CloudWatch Application Signals API
  slug: ''
- description: API for active network monitoring to identify network issues within AWS or company networks using synthetic probes.
  name: Amazon CloudWatch Network Monitor API
  slug: ''
capabilities:
- description: Monitor AWS resources with metrics, alarms, dashboards, anomaly detection, and metric streams. Used by DevOps engineers and SRE teams.
  name: AWS CloudWatch Monitoring and Observability
  slug: monitoring-and-observability
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/aws/category/management-tools/amazon-cloudwatch/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/cloudwatch/faqs/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: ChangeLog
  url: https://aws.amazon.com/releasenotes/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/cloudwatch/pricing/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cloudwatch/
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cloudwatch/
- title: ''
  type: OpenAPI
  url: openapi/cloudwatch-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/cloudwatch-alarm-schema.json
- title: ''
  type: JSONLD
  url: json-ld/cloudwatch-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/cloudwatch-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/cloudwatch-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/monitoring-and-observability.yaml
created: '2024-01-15'
description: Amazon CloudWatch is a monitoring and observability service that provides data and actionable insights for AWS, hybrid, and on-premises applications and infrastructure resources.
features:
- Unified monitoring across AWS resources with automatic dashboards
- Metric collection and custom metrics publishing
- CloudWatch Alarms with composite alarm support and anomaly detection
- CloudWatch Logs Insights for interactive log analytics
- Synthetics canaries for endpoint and API monitoring
- Real User Monitoring (RUM) for client-side performance
- Internet Monitor for availability and latency tracking
- Application Signals for automatic service instrumentation and SLOs
- Cross-account observability with Observability Access Manager
- Network Monitor for hybrid connectivity health
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- Amazon SNS for alarm notifications
- AWS Lambda for automated remediation
- Amazon EventBridge for event-driven architectures
- AWS X-Ray for distributed tracing
- Amazon Managed Grafana for visualization
- AWS Systems Manager for operational automation
- PagerDuty and Slack via SNS topic subscriptions
- Terraform and CloudFormation for infrastructure as code
jsonld:
- class_count: 0
  name: Cloudwatch Context
  property_count: 0
  slug: cloudwatch-context
layout: provider
modified: '2026-04-18'
name: AWS CloudWatch
rules:
- name: AWS CloudWatch API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: cloudwatch-spectral-rules
skills: []
slug: cloudwatch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: AWS CloudWatch\ndescription: >-\n  Amazon CloudWatch is a monitoring and observability service that provides data\n  and actionable insights for AWS, hybrid, and on-premises applications and\n  infrastructure resources.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\nurl: https://raw.githubusercontent.com/api-evangelist/cloudwatch/refs/heads/main/apis.yml\ntags:\n  - Alarms\n  - Aws\n  - Dashboards\n  - Logs\n  - Metrics\n  - Monitoring\n  - Observability\napis:\n  - name: Amazon CloudWatch API\n    description: >-\n      Core CloudWatch API for metrics, alarms, and dashboards.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/cloudwatch/\n    baseURL: https://monitoring.amazonaws.com\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cloudwatch/\n\
  \      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/monitoring/2010-08-01/openapi.yaml\n      - type: OpenAPI\n        url: openapi/cloudwatch-openapi.yml\n      - type: JSONSchema\n        url: json-schema/cloudwatch-alarm-schema.json\n      - type: JSONSchema\n        url: json-schema/cloudwatch-metric-schema.json\n      - type: JSONLD\n        url: json-ld/cloudwatch-context.jsonld\n      - type: Pricing\n        url: https://aws.amazon.com/cloudwatch/pricing/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/GettingStarted.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/\n      - type: Console\n        url: https://console.aws.amazon.com/cloudwatch/\n      - type: Features\n        url: https://aws.amazon.com/cloudwatch/features/\n    tags:\n      - Alarms\n      - Dashboards\n\
  \      - Metric-Streams\n      - Metrics\n      - Statistics\n  - name: Amazon CloudWatch Logs API\n    description: >-\n      API for ingesting, storing, and analyzing log data.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/cloudwatch/features/\n    baseURL: https://logs.amazonaws.com\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/logs/2014-03-28/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AmazonCloudWatchLogs/latest/APIReference/\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Insights\n      - Log-Analytics\n      - Log-Groups\n      - Log-Streams\n      - Logs\n  - name: Amazon CloudWatch Events API\n    description: >-\n      Event-driven architecture for responding to state changes\
  \ in AWS resources.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/eventbridge/\n    baseURL: https://events.amazonaws.com\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/eventbridge/\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/events/2015-10-07/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/eventbridge/latest/APIReference/\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Event-Bus\n      - Eventbridge\n      - Events\n      - Rules\n      - Targets\n  - name: Amazon CloudWatch Application Insights API\n    description: >-\n      Automated monitoring for applications with anomaly detection.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/cloudwatch/features/\n    baseURL: https://applicationinsights.amazonaws.com\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/cloudwatch-application-insights.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/application-insights/2018-11-25/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cloudwatch/latest/APIReference/\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Anomaly-Detection\n      - Application-Insights\n      - Observability\n  - name: Amazon CloudWatch Synthetics API\n    description: >-\n      API for creating and managing canaries that continuously monitor endpoints and\n      APIs using synthetic traffic.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Synthetics_Canaries.html\n    baseURL: https://synthetics.amazonaws.com\n    properties:\n \
  \     - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Synthetics_Canaries.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/synthetics/2017-10-11/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AmazonSynthetics/latest/APIReference/\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Canaries\n      - Endpoint-Monitoring\n      - Monitoring\n      - Synthetics\n  - name: Amazon CloudWatch Internet Monitor API\n    description: >-\n      API for monitoring internet performance and availability between applications\n      hosted on AWS and end users.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-InternetMonitor.html\n    baseURL: https://internetmonitor.amazonaws.com\n    properties:\n      - type:\
  \ Documentation\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-InternetMonitor.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/internetmonitor/2021-06-03/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/internet-monitor/latest/api/Welcome.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Availability\n      - Internet-Monitor\n      - Latency\n      - Network-Performance\n  - name: Amazon CloudWatch RUM API\n    description: >-\n      API for real user monitoring to collect client-side data about web and mobile\n      application performance from actual user sessions.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-RUM.html\n    baseURL: https://rum.amazonaws.com\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-RUM.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/rum/2018-05-10/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cloudwatchrum/latest/APIReference/Welcome.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Client-Side\n      - Real-User-Monitoring\n      - Rum\n      - Web-Performance\n  - name: Amazon CloudWatch Observability Access Manager API\n    description: >-\n      API for creating and managing cross-account observability links between source\n      accounts and monitoring accounts.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Unified-Cross-Account.html\n    baseURL: https://oam.amazonaws.com\n    properties:\n      - type: Documentation\n        url:\
  \ https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Unified-Cross-Account.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/oam/2022-06-10/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/OAM/latest/APIReference/Welcome.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Cross-Account\n      - Monitoring-Account\n      - Oam\n      - Observability\n  - name: Amazon CloudWatch Application Signals API\n    description: >-\n      API for automatic instrumentation and monitoring of application services with\n      service level objectives.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/cloudwatch/features/application-observability-apm/\n    baseURL: https://application-signals.amazonaws.com\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Application-Monitoring-Sections.html\n\
  \      - type: APIReference\n        url: https://docs.aws.amazon.com/applicationsignals/latest/APIReference/Welcome.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Apm\n      - Application-Signals\n      - Service-Level-Objectives\n      - Slo\n  - name: Amazon CloudWatch Network Monitor API\n    description: >-\n      API for active network monitoring to identify network issues within AWS or company\n      networks using synthetic probes.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/cloudwatch/features/network-monitoring/\n    baseURL: https://networkmonitor.amazonaws.com\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/what-is-network-monitor.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/networkmonitor/latest/APIReference/Welcome.html\n      - type: SDK\n       \
  \ url: https://aws.amazon.com/tools/\n    tags:\n      - Direct-Connect\n      - Hybrid-Connectivity\n      - Network-Monitor\n      - Network-Performance\ncommon:\n  - type: Blog\n    url: https://aws.amazon.com/blogs/aws/category/management-tools/amazon-cloudwatch/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudwatch/faqs/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: ChangeLog\n    url: https://aws.amazon.com/releasenotes/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudwatch/pricing/\n  - type: Features\n    url: https://aws.amazon.com/cloudwatch/features/\n  - type: Console\n    url: https://console.aws.amazon.com/cloudwatch/\n  - type: SDK\n    url: https://aws.amazon.com/tools/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cloudwatch/\n  - type: OpenAPI\n    url: openapi/cloudwatch-openapi.yml\n\
  \  - type: JSONSchema\n    url: json-schema/cloudwatch-alarm-schema.json\n  - type: JSONLD\n    url: json-ld/cloudwatch-context.jsonld\n  - type: SpectralRules\n    url: rules/cloudwatch-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/cloudwatch-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/monitoring-and-observability.yaml\n  - type: Features\n    data:\n      - Unified monitoring across AWS resources with automatic dashboards\n      - Metric collection and custom metrics publishing\n      - CloudWatch Alarms with composite alarm support and anomaly detection\n      - CloudWatch Logs Insights for interactive log analytics\n      - Synthetics canaries for endpoint and API monitoring\n      - Real User Monitoring (RUM) for client-side performance\n      - Internet Monitor for availability and latency tracking\n      - Application Signals for automatic service instrumentation and SLOs\n      - Cross-account observability with Observability Access Manager\n\
  \      - Network Monitor for hybrid connectivity health\n  - type: UseCases\n    data:\n      - Monitoring application health and setting automated alarms\n      - Centralized log aggregation and analysis across AWS services\n      - Tracking end-user experience with real user monitoring\n      - Proactively detecting API and endpoint issues with synthetic monitoring\n      - Managing SLOs across microservices architectures\n      - Monitoring network performance for Direct Connect and VPN\n      - Cross-account observability for multi-account AWS organizations\n      - Anomaly detection on metrics to identify unexpected behavior\n  - type: Integrations\n    data:\n      - Amazon SNS for alarm notifications\n      - AWS Lambda for automated remediation\n      - Amazon EventBridge for event-driven architectures\n      - AWS X-Ray for distributed tracing\n      - Amazon Managed Grafana for visualization\n      - AWS Systems Manager for operational automation\n      - PagerDuty and Slack\
  \ via SNS topic subscriptions\n      - Terraform and CloudFormation for infrastructure as code\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudwatch/refs/heads/main/apis.yml
tags:
- Alarms
- Aws
- Dashboards
- Logs
- Metrics
- Monitoring
- Observability
url: https://raw.githubusercontent.com/api-evangelist/cloudwatch/refs/heads/main/apis.yml
use_cases:
- Monitoring application health and setting automated alarms
- Centralized log aggregation and analysis across AWS services
- Tracking end-user experience with real user monitoring
- Proactively detecting API and endpoint issues with synthetic monitoring
- Managing SLOs across microservices architectures
- Monitoring network performance for Direct Connect and VPN
- Cross-account observability for multi-account AWS organizations
- Anomaly detection on metrics to identify unexpected behavior
---
