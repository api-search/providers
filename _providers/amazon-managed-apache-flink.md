---
api_count: 1
api_specs:
- filename: amazon-managed-apache-flink-openapi-original.yaml
  format: yaml
  label: Amazon Managed Service for Apache Flink API
  slug: aws-managed-flink-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-apache-flink/refs/heads/main/openapi/amazon-managed-apache-flink-openapi-original.yaml
apis:
- description: The Amazon Managed Service for Apache Flink API provides programmatic access to create and manage streaming applications, application versions, snapshots, and VPC configurations for Apache Flink workl
  name: Amazon Managed Service for Apache Flink API
  slug: aws-managed-flink-api
capabilities:
- description: Workflow capability for data engineers and analysts to build, manage, and monitor Apache Flink streaming analytics applications on AWS.
  name: Amazon Managed Service for Apache Flink - Streaming Analytics Workflow
  slug: streaming-analytics-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/managed-service-apache-flink/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/managed-flink/
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
  url: https://aws.amazon.com/blogs/big-data/tag/amazon-managed-service-for-apache-flink/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/flink/
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
  url: rules/amazon-managed-apache-flink-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-managed-apache-flink-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/streaming-analytics-workflow.yaml
created: '2026-03-16'
description: Amazon Managed Service for Apache Flink is the easiest way to transform and analyze streaming data in real time with Apache Flink. It enables you to build sophisticated streaming analytics applications using Apache Flink with fully managed infrastructure and pay-as-you-go pricing.
features:
- description: Run Apache Flink applications without managing infrastructure, patching, or capacity planning.
  name: Fully Managed Apache Flink
- description: Automatically scales application parallelism based on streaming data volume.
  name: Auto Scaling
- description: Create point-in-time snapshots of application state for fault tolerance and version management.
  name: Application Snapshots
- description: Deploy Flink applications within a VPC for secure access to private data sources.
  name: VPC Integration
- description: Connect to Kinesis Data Streams, Kinesis Data Firehose, MSK, and S3 as data sources.
  name: Multiple Input Sources
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use Kinesis streams as input sources for Flink applications.
  name: Amazon Kinesis Data Streams
- description: Connect to managed Kafka clusters as input sources.
  name: Amazon MSK
- description: Read reference data from S3 and write output to S3 buckets.
  name: Amazon S3
- description: Monitor application metrics and logs in CloudWatch.
  name: Amazon CloudWatch
jsonld:
- class_count: 182
  name: Amazon Managed Apache Flink Context
  property_count: 153
  slug: amazon-managed-apache-flink-context
layout: provider
modified: '2026-04-19'
name: Amazon Managed Service for Apache Flink
rules:
- name: Amazon Managed Service for Apache Flink API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 4
    warn: 7
  slug: amazon-managed-apache-flink-spectral-rules
skills: []
slug: amazon-managed-apache-flink
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-managed-apache-flink\nname: Amazon Managed Service for Apache Flink\ndescription: >-\n  Amazon Managed Service for Apache Flink is the easiest way to transform and\n  analyze streaming data in real time with Apache Flink. It enables you to\n  build sophisticated streaming analytics applications using Apache Flink with\n  fully managed infrastructure and pay-as-you-go pricing.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache Flink\n  - AWS\n  - Big Data\n  - Real-Time Processing\n  - Streaming Analytics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-managed-apache-flink/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-managed-apache-flink:aws-managed-flink-api\n    name: Amazon Managed Service for Apache Flink API\n    description: >-\n      The Amazon Managed Service for Apache Flink API provides programmatic\n\
  \      access to create and manage streaming applications, application versions,\n      snapshots, and VPC configurations for Apache Flink workloads. Covers\n      31 paths and 31 operations.\n    humanURL: https://aws.amazon.com/managed-service-apache-flink/\n    baseURL: https://kinesisanalytics.amazonaws.com\n    tags:\n      - Apache Flink\n      - Real-Time Processing\n      - Streaming Analytics\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/managed-flink/latest/apiv2/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-managed-apache-flink-openapi-original.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/managed-service-apache-flink/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/managed-service-apache-flink/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/managed-service-apache-flink/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-managed-apache-flink-application-detail-schema.json\n\
  \      - type: JSON-LD\n        url: json-ld/amazon-managed-apache-flink-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/managed-service-apache-flink/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/managed-flink/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/big-data/tag/amazon-managed-service-for-apache-flink/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/flink/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n\
  \    url: rules/amazon-managed-apache-flink-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-managed-apache-flink-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/streaming-analytics-workflow.yaml\n  - type: Features\n    data:\n      - name: Fully Managed Apache Flink\n        description: Run Apache Flink applications without managing infrastructure, patching, or capacity planning.\n      - name: Auto Scaling\n        description: Automatically scales application parallelism based on streaming data volume.\n      - name: Application Snapshots\n        description: Create point-in-time snapshots of application state for fault tolerance and version management.\n      - name: VPC Integration\n        description: Deploy Flink applications within a VPC for secure access to private data sources.\n      - name: Multiple Input Sources\n        description: Connect to Kinesis Data Streams, Kinesis Data Firehose, MSK, and S3 as data sources.\n  - type: UseCases\n\
  \    data:\n      - name: Real-Time Analytics\n        description: Build streaming analytics pipelines to analyze data as it arrives from IoT devices, logs, or transactions.\n      - name: Event-Driven Processing\n        description: Process and transform event streams for real-time dashboards and operational monitoring.\n      - name: Anomaly Detection\n        description: Detect anomalies in streaming data for fraud detection and security monitoring.\n      - name: ETL Pipelines\n        description: Build real-time ETL pipelines to transform and enrich streaming data before loading to destinations.\n  - type: Integrations\n    data:\n      - name: Amazon Kinesis Data Streams\n        description: Use Kinesis streams as input sources for Flink applications.\n      - name: Amazon MSK\n        description: Connect to managed Kafka clusters as input sources.\n      - name: Amazon S3\n        description: Read reference data from S3 and write output to S3 buckets.\n      - name: Amazon\
  \ CloudWatch\n        description: Monitor application metrics and logs in CloudWatch.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-apache-flink/refs/heads/main/apis.yml
tags:
- Apache Flink
- AWS
- Big Data
- Real-Time Processing
- Streaming Analytics
url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-apache-flink/refs/heads/main/apis.yml
use_cases:
- description: Build streaming analytics pipelines to analyze data as it arrives from IoT devices, logs, or transactions.
  name: Real-Time Analytics
- description: Process and transform event streams for real-time dashboards and operational monitoring.
  name: Event-Driven Processing
- description: Detect anomalies in streaming data for fraud detection and security monitoring.
  name: Anomaly Detection
- description: Build real-time ETL pipelines to transform and enrich streaming data before loading to destinations.
  name: ETL Pipelines
---
