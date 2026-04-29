---
api_count: 1
api_specs:
- filename: amazon-kinesis-firehose-openapi.yml
  format: yaml
  label: Amazon Kinesis Data Firehose API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis-firehose/refs/heads/main/openapi/amazon-kinesis-firehose-openapi.yml
apis:
- description: The Amazon Kinesis Data Firehose API provides the easiest way to reliably load streaming data into data lakes, data stores, and analytics services. The API allows you to create and manage delivery str
  name: Amazon Kinesis Data Firehose API
  slug: ''
capabilities:
- description: Unified workflow capability for Amazon Kinesis Data Firehose combining resource management and operations.
  name: Amazon Kinesis Data Firehose Workflow
  slug: amazon-kinesis-firehose-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Portal
  url: https://aws.amazon.com/kinesis/data-firehose/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/firehose/
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
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/firehose/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-kinesis-firehose-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-kinesis-firehose-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-kinesis-firehose-vocabulary.yaml
created: '2024-01-15'
description: Amazon Kinesis Data Firehose is the easiest way to reliably load streaming data into data lakes, data stores, and analytics services. It can capture, transform, and deliver streaming data to Amazon S3, Amazon Redshift, Amazon OpenSearch Service, Splunk, and any custom HTTP endpoint. It is a fully managed service that automatically scales to match the throughput of your data and requires no ongoing administration.
features:
- description: Fully managed service that automatically scales to match data throughput with no ongoing administration.
  name: Zero Administration
- description: Transform streaming data using AWS Lambda before delivering to destinations.
  name: Data Transformation
- description: Deliver data to Amazon S3, Redshift, OpenSearch Service, Splunk, Datadog, and custom HTTP endpoints.
  name: Multiple Destinations
- description: Automatically convert data formats such as JSON to Apache Parquet or Apache ORC before storing in S3.
  name: Format Conversion
- description: Compress data using GZIP, ZIP, or Snappy before delivering to S3 to reduce storage costs.
  name: Data Compression
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Deliver streaming data to S3 buckets as the primary data lake destination.
  name: Amazon S3
- description: Load streaming data into Redshift data warehouse for SQL analytics.
  name: Amazon Redshift
- description: Index streaming data in OpenSearch for real-time search and visualization.
  name: Amazon OpenSearch Service
- description: Transform and enrich streaming data using Lambda functions before delivery.
  name: AWS Lambda
- description: Send streaming data to Splunk for security and operational analytics.
  name: Splunk
jsonld:
- class_count: 1
  name: Amazon Kinesis Firehose Context
  property_count: 7
  slug: amazon-kinesis-firehose-context
layout: provider
modified: '2026-04-19'
name: Amazon Kinesis Data Firehose
rules:
- name: Amazon Kinesis Data Firehose API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-kinesis-firehose-spectral-rules
skills: []
slug: amazon-kinesis-firehose
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Kinesis Data Firehose\ndescription: Amazon Kinesis Data Firehose is the easiest way to reliably load streaming data into data lakes, data stores, and analytics services. It can capture, transform, and deliver streaming data\n  to Amazon S3, Amazon Redshift, Amazon OpenSearch Service, Splunk, and any custom HTTP endpoint. It is a fully managed service that automatically scales to match the throughput of your data and \n  requires no ongoing administration.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/kinesis/data-firehose/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Kinesis Data Firehose API\n  description: >-\n    The Amazon Kinesis Data Firehose API provides the easiest way to reliably\n    load streaming data into data lakes, data stores, and analytics services. The\n    API allows you to create and manage delivery streams, configure data\n    transformations using AWS\
  \ Lambda, set up destinations such as Amazon S3,\n    Amazon Redshift, Amazon OpenSearch Service, and custom HTTP endpoints, and\n    put records into delivery streams. It automatically scales to match your data\n    throughput with no ongoing administration required.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/kinesis/data-firehose/\n  baseURL: https://firehose.amazonaws.com\n  tags:\n  - Analytics\n  - AWS\n  - Data Delivery\n  - Streaming\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/firehose/\n  - type: OpenAPI\n    url: openapi/amazon-kinesis-firehose-openapi.yml\n  - type: Pricing\n    url: https://aws.amazon.com/kinesis/data-firehose/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/kinesis/data-firehose/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/kinesis/data-firehose/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-firehose-delivery-stream-schema.json\n\
  \  - type: JSONLD\n    url: json-ld/amazon-kinesis-firehose-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Portal\n  url: https://aws.amazon.com/kinesis/data-firehose/\n- type: Documentation\n  url: https://docs.aws.amazon.com/firehose/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/firehose/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Features\n  data:\n  - name: Zero Administration\n    description: Fully managed service that automatically scales to match data throughput\
  \ with no ongoing administration.\n  - name: Data Transformation\n    description: Transform streaming data using AWS Lambda before delivering to destinations.\n  - name: Multiple Destinations\n    description: Deliver data to Amazon S3, Redshift, OpenSearch Service, Splunk, Datadog, and custom HTTP endpoints.\n  - name: Format Conversion\n    description: Automatically convert data formats such as JSON to Apache Parquet or Apache ORC before storing in S3.\n  - name: Data Compression\n    description: Compress data using GZIP, ZIP, or Snappy before delivering to S3 to reduce storage costs.\n- type: UseCases\n  data:\n  - name: Log Analytics\n    description: Stream application and infrastructure logs to Amazon OpenSearch Service for real-time analysis.\n  - name: Clickstream Analytics\n    description: Capture website clickstream data and deliver to data lakes for behavioral analysis.\n  - name: IoT Data Ingestion\n    description: Ingest IoT device telemetry into S3 or Redshift for analytics\
  \ and reporting.\n  - name: Security Analytics\n    description: Stream security events and logs to SIEM systems like Splunk for threat detection.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Deliver streaming data to S3 buckets as the primary data lake destination.\n  - name: Amazon Redshift\n    description: Load streaming data into Redshift data warehouse for SQL analytics.\n  - name: Amazon OpenSearch Service\n    description: Index streaming data in OpenSearch for real-time search and visualization.\n  - name: AWS Lambda\n    description: Transform and enrich streaming data using Lambda functions before delivery.\n  - name: Splunk\n    description: Send streaming data to Splunk for security and operational analytics.\n- type: SpectralRules\n  url: rules/amazon-kinesis-firehose-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-kinesis-firehose-workflow.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-kinesis-firehose-vocabulary.yaml\n\
  maintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- Analytics\n- AWS\n- Data Delivery\n- Streaming\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis-firehose/refs/heads/main/apis.yml
tags:
- Analytics
- AWS
- Data Delivery
- Streaming
url: https://aws.amazon.com/kinesis/data-firehose/
use_cases:
- description: Stream application and infrastructure logs to Amazon OpenSearch Service for real-time analysis.
  name: Log Analytics
- description: Capture website clickstream data and deliver to data lakes for behavioral analysis.
  name: Clickstream Analytics
- description: Ingest IoT device telemetry into S3 or Redshift for analytics and reporting.
  name: IoT Data Ingestion
- description: Stream security events and logs to SIEM systems like Splunk for threat detection.
  name: Security Analytics
---
