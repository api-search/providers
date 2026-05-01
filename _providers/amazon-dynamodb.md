---
api_count: 1
api_specs:
- filename: amazon-dynamodb-openapi.yml
  format: yaml
  label: Amazon DynamoDB API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-dynamodb/refs/heads/main/openapi/amazon-dynamodb-openapi.yml
apis:
- description: Core API for managing Amazon DynamoDB tables, items, indexes, and performing data plane operations including single-item actions, queries, scans, batch operations, and transactions.
  name: Amazon DynamoDB API
  slug: ''
capabilities:
- description: Unified capability for managing DynamoDB tables, items, queries, and transactions for application developers and data engineers.
  name: Amazon DynamoDB NoSQL Database Operations
  slug: dynamodb-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/dynamodb/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/dynamodb/
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
  url: https://aws.amazon.com/blogs/database/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/dynamodbv2/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-dynamodb
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/security.html
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-dynamodb-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-dynamodb-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/dynamodb-management.yaml
created: '2024-01-15'
description: Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability, allowing you to store and retrieve any amount of data and serve any level of request traffic using key-value and document data models.
features:
- description: Fully managed, no server provisioning, patching, or capacity management required.
  name: Serverless Architecture
- description: Consistent performance at any scale with single-digit millisecond response times.
  name: Single-Digit Millisecond Performance
- description: Multi-Region, active-active replication with up to 99.999% availability and zero RPO.
  name: Global Tables
- description: On-demand mode automatically adapts to application throughput without capacity planning.
  name: Automatic Scaling
- description: ACID transactions across multiple items and tables with conditional operations.
  name: Transactions
- description: DynamoDB Streams captures a time-ordered sequence of changes to items for event-driven architectures.
  name: Streams
- description: Enables continuous backups with point-in-time recovery to any second over the last 35 days.
  name: Point-in-Time Recovery
- description: Time to Live automatically deletes expired items to reduce storage costs.
  name: TTL
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Event-driven processing of DynamoDB Streams with Lambda functions for real-time workflows.
  name: AWS Lambda
- description: Monitor DynamoDB table metrics, set alarms, and view consumption and performance data.
  name: Amazon CloudWatch
- description: Fine-grained access control for tables, items, and attributes using IAM policies.
  name: AWS IAM
- description: Export DynamoDB changes to Kinesis for real-time analytics and archiving.
  name: Amazon Kinesis Data Streams
- description: Export DynamoDB data to S3 for analysis with Athena, Redshift Spectrum, or SageMaker.
  name: AWS Glue
jsonld:
- class_count: 32
  name: Amazon Dynamodb Context
  property_count: 92
  slug: amazon-dynamodb-context
layout: provider
modified: '2026-04-19'
name: Amazon DynamoDB
rules:
- name: Amazon DynamoDB API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 13
  slug: amazon-dynamodb-spectral-rules
skills: []
slug: amazon-dynamodb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon DynamoDB\ndescription: Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability, allowing you to store and retrieve any amount of data \n  and serve any level of request traffic using key-value and document data models.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/dynamodb/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon DynamoDB API\n  description: >-\n    Core API for managing Amazon DynamoDB tables, items, indexes, and\n    performing data plane operations including single-item actions,\n    queries, scans, batch operations, and transactions.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/dynamodb/\n  baseURL: https://dynamodb.amazonaws.com\n  tags:\n  - AWS\n  - Database\n  - Document Store\n  - Key-Value\n  - NoSQL\n  properties:\n\
  \  - type: Documentation\n    url: https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/\n  - type: OpenAPI\n    url: openapi/amazon-dynamodb-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/dynamodb/2012-08-10/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-dynamodb-table-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-dynamodb-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/dynamodb/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/dynamodb/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/dynamodb/faqs/\n  - type: TermsOfService\n    url: https://aws.amazon.com/dynamodb/sla/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cli/latest/reference/dynamodb/\n\
  \  - type: Security\n    url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/security.html\n  - type: JSONStructure\n    url: json-structure/amazon-dynamodb-table-structure.json\n  - type: Example\n    url: examples/amazon-dynamodb-table-example.json\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/dynamodb/\n- type: Documentation\n  url: https://docs.aws.amazon.com/dynamodb/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/database/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/dynamodbv2/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n\
  \  url: https://health.aws.amazon.com/health/status\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-dynamodb\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Security\n  url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/security.html\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Features\n  data:\n  - name: Serverless Architecture\n    description: Fully managed, no server provisioning, patching, or capacity management required.\n  - name: Single-Digit Millisecond Performance\n    description: Consistent performance at any scale with single-digit millisecond response times.\n  - name: Global Tables\n    description: Multi-Region, active-active replication with up to 99.999% availability and zero RPO.\n  - name: Automatic Scaling\n    description: On-demand\
  \ mode automatically adapts to application throughput without capacity planning.\n  - name: Transactions\n    description: ACID transactions across multiple items and tables with conditional operations.\n  - name: Streams\n    description: DynamoDB Streams captures a time-ordered sequence of changes to items for event-driven architectures.\n  - name: Point-in-Time Recovery\n    description: Enables continuous backups with point-in-time recovery to any second over the last 35 days.\n  - name: TTL\n    description: Time to Live automatically deletes expired items to reduce storage costs.\n- type: UseCases\n  data:\n  - name: Financial Services\n    description: Fraud detection, digital onboarding, and regulatory compliance workloads requiring consistent low latency.\n  - name: Gaming Applications\n    description: Player profiles, leaderboards, session state, and game data with high-throughput requirements.\n  - name: E-Commerce\n    description: Shopping carts, inventory tracking, order\
  \ management, and customer data platforms.\n  - name: IoT Data Storage\n    description: High-volume telemetry data ingestion and time-series storage from IoT devices.\n  - name: Content Management\n    description: Metadata storage and content indexing for media streaming and publishing platforms.\n- type: Integrations\n  data:\n  - name: AWS Lambda\n    description: Event-driven processing of DynamoDB Streams with Lambda functions for real-time workflows.\n  - name: Amazon CloudWatch\n    description: Monitor DynamoDB table metrics, set alarms, and view consumption and performance data.\n  - name: AWS IAM\n    description: Fine-grained access control for tables, items, and attributes using IAM policies.\n  - name: Amazon Kinesis Data Streams\n    description: Export DynamoDB changes to Kinesis for real-time analytics and archiving.\n  - name: AWS Glue\n    description: Export DynamoDB data to S3 for analysis with Athena, Redshift Spectrum, or SageMaker.\n- type: SpectralRules\n  url:\
  \ rules/amazon-dynamodb-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-dynamodb-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/dynamodb-management.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Database\n- Document Store\n- Key-Value\n- NoSQL\n- Serverless\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-dynamodb/refs/heads/main/apis.yml
tags:
- Database
- Document Store
- Key-Value
- NoSQL
- Serverless
url: https://aws.amazon.com/dynamodb/
use_cases:
- description: Fraud detection, digital onboarding, and regulatory compliance workloads requiring consistent low latency.
  name: Financial Services
- description: Player profiles, leaderboards, session state, and game data with high-throughput requirements.
  name: Gaming Applications
- description: Shopping carts, inventory tracking, order management, and customer data platforms.
  name: E-Commerce
- description: High-volume telemetry data ingestion and time-series storage from IoT devices.
  name: IoT Data Storage
- description: Metadata storage and content indexing for media streaming and publishing platforms.
  name: Content Management
---
