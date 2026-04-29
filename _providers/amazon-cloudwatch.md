---
api_count: 1
api_specs:
- filename: amazon-cloudwatch-openapi.yml
  format: yaml
  label: Amazon CloudWatch API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/openapi/amazon-cloudwatch-openapi.yml
apis:
- description: API for publishing metrics, creating alarms, managing dashboards, querying logs, and configuring observability for AWS resources and applications.
  name: Amazon CloudWatch API
  slug: ''
capabilities:
- description: Workflow for observability and monitoring using Amazon CloudWatch for Operations Engineer personas.
  name: Amazon CloudWatch Observability and Monitoring
  slug: observability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloudwatch/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/mt/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cloudwatch/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-cloudwatch
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloudwatch-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloudwatch-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/observability.yaml
created: '2024-01-15'
description: Amazon CloudWatch is an intelligent observability platform providing complete visibility into performance, availability, and security across your entire technology stack. Monitor applications, infrastructure, and workloads with unified metrics, logs, and traces plus AI-powered insights.
features:
- description: Monitor metrics, logs, and traces in one interface for complete system visibility.
  name: Unified Observability
- description: Detect anomalies and investigate issues using AI-powered CloudWatch Investigations.
  name: AI-Powered Insights
- description: Create custom dashboards with pre-built and customizable metric visualizations.
  name: Dashboards
- description: Set threshold-based alarms on any metric to trigger automated actions.
  name: Alarms
- description: Analyze log data with SQL and natural language queries using CloudWatch Logs Insights.
  name: Log Insights
- description: Ingest OpenTelemetry data alongside native AWS metrics and traces.
  name: OpenTelemetry Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Monitor EC2 instance performance metrics including CPU, network, and disk.
  name: Amazon EC2
- description: Monitor Lambda invocations, errors, and duration metrics automatically.
  name: AWS Lambda
- description: Ingest Prometheus metrics into CloudWatch for unified monitoring.
  name: Amazon Prometheus
- description: Connect CloudWatch data sources to Grafana dashboards.
  name: Grafana
- description: Correlate traces from X-Ray with CloudWatch metrics and logs.
  name: AWS X-Ray
jsonld:
- class_count: 10
  name: Amazon Cloudwatch Context
  property_count: 32
  slug: amazon-cloudwatch-context
layout: provider
modified: '2026-04-19'
name: Amazon CloudWatch
rules:
- name: Amazon CloudWatch API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: amazon-cloudwatch-spectral-rules
skills: []
slug: amazon-cloudwatch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-cloudwatch\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/apis.yml\nname: Amazon CloudWatch\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  Amazon CloudWatch is an intelligent observability platform providing complete visibility into performance, availability, and security across your entire technology stack. Monitor applications, infrastructure,\n  and workloads with unified metrics, logs, and traces plus AI-powered insights.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon CloudWatch API\n  description: API for publishing metrics, creating alarms, managing dashboards, querying logs, and configuring observability for AWS resources and applications.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/cloudwatch/\n  baseURL: https://monitoring.us-east-1.amazonaws.com\n\
  \  tags:\n  - AWS\n  - CloudWatch\n  - Monitoring\n  - Observability\n  properties:\n  - type: OpenAPI\n    url: openapi/amazon-cloudwatch-openapi.yml\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudwatch/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudwatch/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudwatch/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudwatch/\n  - type: JSONSchema\n    url: json-schema/cloudwatch-get-metric-data-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudwatch-get-metric-statistics-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudwatch-list-metrics-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudwatch-describe-alarms-response-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/cloudwatch-put-dashboard-response-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-cloudwatch-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/cloudwatch/\n- type: Documentation\n  url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/mt/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudwatch/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n\
  \  url: https://stackoverflow.com/questions/tagged/amazon-cloudwatch\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-cloudwatch-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloudwatch-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/observability.yaml\n- type: Features\n  data:\n  - name: Unified Observability\n    description: Monitor metrics, logs, and traces in one interface for complete system visibility.\n  - name: AI-Powered Insights\n    description: Detect anomalies and investigate issues using AI-powered CloudWatch Investigations.\n  - name: Dashboards\n    description: Create custom dashboards with pre-built and customizable metric visualizations.\n  - name: Alarms\n    description: Set threshold-based alarms on any metric to trigger automated actions.\n  - name: Log Insights\n    description: Analyze log data with SQL and natural\
  \ language queries using CloudWatch Logs Insights.\n  - name: OpenTelemetry Integration\n    description: Ingest OpenTelemetry data alongside native AWS metrics and traces.\n- type: UseCases\n  data:\n  - name: Infrastructure Monitoring\n    description: Monitor EC2, RDS, Lambda, and other AWS resources with built-in metrics.\n  - name: Application Performance\n    description: Track application performance metrics and detect latency or error rate spikes.\n  - name: Log Analysis\n    description: Aggregate and query application logs for troubleshooting and analytics.\n  - name: Automated Remediation\n    description: Trigger auto-scaling, Lambda functions, or SNS alerts based on metric alarms.\n- type: Integrations\n  data:\n  - name: Amazon EC2\n    description: Monitor EC2 instance performance metrics including CPU, network, and disk.\n  - name: AWS Lambda\n    description: Monitor Lambda invocations, errors, and duration metrics automatically.\n  - name: Amazon Prometheus\n    description:\
  \ Ingest Prometheus metrics into CloudWatch for unified monitoring.\n  - name: Grafana\n    description: Connect CloudWatch data sources to Grafana dashboards.\n  - name: AWS X-Ray\n    description: Correlate traces from X-Ray with CloudWatch metrics and logs.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- CloudWatch\n- Monitoring\n- Observability\n- Metrics\n- Logs\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/apis.yml
tags:
- AWS
- CloudWatch
- Monitoring
- Observability
- Metrics
- Logs
url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/apis.yml
use_cases:
- description: Monitor EC2, RDS, Lambda, and other AWS resources with built-in metrics.
  name: Infrastructure Monitoring
- description: Track application performance metrics and detect latency or error rate spikes.
  name: Application Performance
- description: Aggregate and query application logs for troubleshooting and analytics.
  name: Log Analysis
- description: Trigger auto-scaling, Lambda functions, or SNS alerts based on metric alarms.
  name: Automated Remediation
---
