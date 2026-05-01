---
api_count: 1
api_specs:
- filename: amazon-lookout-for-metrics-openapi-original.yaml
  format: yaml
  label: Amazon Lookout for Metrics API
  slug: amazon-lookout-for-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/openapi/amazon-lookout-for-metrics-openapi-original.yaml
apis:
- description: The Amazon Lookout for Metrics API provides programmatic access to create and manage anomaly detectors, anomaly groups, alerts, and datasets for automated anomaly detection in business metrics. Suppor
  name: Amazon Lookout for Metrics API
  slug: amazon-lookout-for-metrics-api
capabilities:
- description: Workflow capability for data science and operations teams to manage anomaly detectors, monitor metric anomalies, configure alerts, and provide detection feedback using Amazon Lookout for Metrics.
  name: Amazon Lookout for Metrics - Anomaly Detection Operations
  slug: anomaly-detection-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/lookout-for-metrics/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/lookoutmetrics/
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
  url: https://aws.amazon.com/blogs/machine-learning/tag/amazon-lookout-for-metrics/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/lookoutmetrics/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-lookout-for-metrics-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-lookout-for-metrics-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/anomaly-detection-operations.yaml
created: '2026-03-16'
description: Amazon Lookout for Metrics uses machine learning to automatically detect anomalies in business and operational metrics such as revenue performance, customer engagement, and user activity. It continuously monitors data from various sources including Amazon S3, CloudWatch, RDS, Redshift, Athena, and AppFlow, providing root cause analysis and alert notifications when anomalies are detected.
features:
- description: Uses ML to automatically detect anomalies in business and operational metrics without requiring ML expertise.
  name: Automated Anomaly Detection
- description: Identifies the top contributors to each anomaly to help determine root causes quickly.
  name: Root Cause Analysis
- description: Connects to Amazon S3, CloudWatch, RDS, Redshift, Athena, and AppFlow as data sources.
  name: Multi-Source Data Ingestion
- description: Continuously monitors metrics and sends real-time alerts when anomalies are detected.
  name: Continuous Monitoring
- description: Configure alerts via Amazon SNS, Lambda, or other AWS services when anomalies occur.
  name: Alert Configuration
- description: Provide feedback on detected anomalies to improve future detection accuracy.
  name: Anomaly Feedback
- description: Tag anomaly detectors and related resources for cost allocation and organization.
  name: Resource Tagging
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use S3 buckets as a data source for metric data in CSV or JSON format.
  name: Amazon S3
- description: Ingest CloudWatch metrics directly for anomaly detection.
  name: Amazon CloudWatch
- description: Connect to RDS databases to retrieve metric data for analysis.
  name: Amazon RDS
- description: Use Redshift data warehouse as a source for business metrics.
  name: Amazon Redshift
- description: Query Athena tables to feed metric data into anomaly detectors.
  name: Amazon Athena
- description: Use AppFlow connectors to ingest data from SaaS applications.
  name: AWS AppFlow
- description: Send alert notifications via SNS topics when anomalies are detected.
  name: Amazon SNS
- description: Trigger Lambda functions in response to detected anomalies for custom workflows.
  name: AWS Lambda
jsonld:
- class_count: 117
  name: Amazon Lookout For Metrics Context
  property_count: 114
  slug: amazon-lookout-for-metrics-context
layout: provider
modified: '2026-04-19'
name: Amazon Lookout for Metrics
rules:
- name: Amazon Lookout for Metrics API Rules
  rule_count: 24
  severity_counts:
    error: 8
    hint: 0
    info: 5
    warn: 11
  slug: amazon-lookout-for-metrics-spectral-rules
skills: []
slug: amazon-lookout-for-metrics
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-lookout-for-metrics\nname: Amazon Lookout for Metrics\ndescription: >-\n  Amazon Lookout for Metrics uses machine learning to automatically detect\n  anomalies in business and operational metrics such as revenue performance,\n  customer engagement, and user activity. It continuously monitors data from\n  various sources including Amazon S3, CloudWatch, RDS, Redshift, Athena, and\n  AppFlow, providing root cause analysis and alert notifications when anomalies\n  are detected.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Anomaly Detection\n  - AWS\n  - Business Intelligence\n  - Machine Learning\n  - Metrics\n  - Monitoring\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-lookout-for-metrics:amazon-lookout-for-metrics-api\n    name: Amazon Lookout\
  \ for Metrics API\n    description: >-\n      The Amazon Lookout for Metrics API provides programmatic access to\n      create and manage anomaly detectors, anomaly groups, alerts, and datasets\n      for automated anomaly detection in business metrics. Supports detector\n      lifecycle management, metric set configuration, alert creation, anomaly\n      analysis, feedback collection, and resource tagging across 30 operations.\n    humanURL: https://aws.amazon.com/lookout-for-metrics/\n    baseURL: https://lookoutmetrics.amazonaws.com\n    tags:\n      - Anomaly Detection\n      - Machine Learning\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/lookoutmetrics/latest/api/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-lookout-for-metrics-openapi-original.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/lookout-for-metrics/getting-started/\n      - type: Pricing\n       \
  \ url: https://aws.amazon.com/lookout-for-metrics/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/lookout-for-metrics/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-lookout-for-metrics-activate-anomaly-detector-response-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-lookout-for-metrics-activate-anomaly-detector-response-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-lookout-for-metrics-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/lookout-for-metrics/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/lookoutmetrics/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/machine-learning/tag/amazon-lookout-for-metrics/\n  - type: GitHubOrganization\n    url:\
  \ https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/lookoutmetrics/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-lookout-for-metrics-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-lookout-for-metrics-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/anomaly-detection-operations.yaml\n  - type: Features\n    data:\n      - name: Automated Anomaly Detection\n        description: Uses ML to automatically detect anomalies in business and operational metrics without requiring ML expertise.\n      - name: Root Cause Analysis\n        description: Identifies the top contributors to each anomaly to help determine root causes quickly.\n      - name: Multi-Source\
  \ Data Ingestion\n        description: Connects to Amazon S3, CloudWatch, RDS, Redshift, Athena, and AppFlow as data sources.\n      - name: Continuous Monitoring\n        description: Continuously monitors metrics and sends real-time alerts when anomalies are detected.\n      - name: Alert Configuration\n        description: Configure alerts via Amazon SNS, Lambda, or other AWS services when anomalies occur.\n      - name: Anomaly Feedback\n        description: Provide feedback on detected anomalies to improve future detection accuracy.\n      - name: Resource Tagging\n        description: Tag anomaly detectors and related resources for cost allocation and organization.\n  - type: UseCases\n    data:\n      - name: Revenue Anomaly Detection\n        description: Monitor revenue metrics and detect unexpected drops or spikes that could indicate fraud or system issues.\n      - name: Customer Engagement Monitoring\n        description: Track customer engagement metrics and alert teams when\
  \ patterns deviate from expected ranges.\n      - name: Operational Metrics Monitoring\n        description: Monitor operational metrics such as system performance, error rates, and throughput for anomalies.\n      - name: E-Commerce Performance\n        description: Detect anomalies in e-commerce metrics like conversion rates, cart abandonment, and sales volume.\n      - name: User Activity Analysis\n        description: Analyze user activity patterns and detect unusual behavior that may indicate security incidents.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: Use S3 buckets as a data source for metric data in CSV or JSON format.\n      - name: Amazon CloudWatch\n        description: Ingest CloudWatch metrics directly for anomaly detection.\n      - name: Amazon RDS\n        description: Connect to RDS databases to retrieve metric data for analysis.\n      - name: Amazon Redshift\n        description: Use Redshift data warehouse as a source for business\
  \ metrics.\n      - name: Amazon Athena\n        description: Query Athena tables to feed metric data into anomaly detectors.\n      - name: AWS AppFlow\n        description: Use AppFlow connectors to ingest data from SaaS applications.\n      - name: Amazon SNS\n        description: Send alert notifications via SNS topics when anomalies are detected.\n      - name: AWS Lambda\n        description: Trigger Lambda functions in response to detected anomalies for custom workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/apis.yml
tags:
- Anomaly Detection
- Business Intelligence
- Machine Learning
- Metrics
- Monitoring
url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/apis.yml
use_cases:
- description: Monitor revenue metrics and detect unexpected drops or spikes that could indicate fraud or system issues.
  name: Revenue Anomaly Detection
- description: Track customer engagement metrics and alert teams when patterns deviate from expected ranges.
  name: Customer Engagement Monitoring
- description: Monitor operational metrics such as system performance, error rates, and throughput for anomalies.
  name: Operational Metrics Monitoring
- description: Detect anomalies in e-commerce metrics like conversion rates, cart abandonment, and sales volume.
  name: E-Commerce Performance
- description: Analyze user activity patterns and detect unusual behavior that may indicate security incidents.
  name: User Activity Analysis
---
