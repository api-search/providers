---
api_count: 3
api_specs:
- filename: dynamodb-openapi.yml
  format: yaml
  label: Amazon DynamoDB API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynamodb/refs/heads/main/openapi/dynamodb-openapi.yml
- filename: dynamodb-streams-asyncapi.yml
  format: yaml
  label: Amazon DynamoDB Streams API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynamodb/refs/heads/main/asyncapi/dynamodb-streams-asyncapi.yml
apis:
- description: RESTful API for interacting with DynamoDB tables and items.
  name: Amazon DynamoDB API
  slug: ''
- description: API for capturing and processing change data from DynamoDB tables in near real-time, providing time-ordered sequences of item-level modifications.
  name: Amazon DynamoDB Streams API
  slug: ''
- description: API for managing DynamoDB Accelerator (DAX) clusters, an in-memory caching service that delivers microsecond response times for DynamoDB read workloads.
  name: Amazon DynamoDB Accelerator (DAX) API
  slug: ''
asyncapis:
- description: Amazon DynamoDB Streams captures a time-ordered sequence of item-level modifications in any DynamoDB table and stores this information in a log for up to 24 hours. Applications can access this log and
  name: Amazon DynamoDB Streams
  slug: dynamodb-streams-asyncapi
capabilities:
- description: Unified workflow for managing DynamoDB tables, items, queries, batch operations, transactions, and backups. Used by backend developers and data engineers.
  name: Amazon DynamoDB Database Management
  slug: database-management
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/database/category/database/amazon-dynamodb/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Resources
  url: https://aws.amazon.com/dynamodb/resources/
- title: ''
  type: SpectralRules
  url: rules/dynamodb-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/dynamodb-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/database-management.yaml
created: '2024'
description: A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability.
features:
- description: Consistent low-latency reads and writes at any scale with SSD-backed storage.
  name: Single-Digit Millisecond Performance
- description: Multi-region, multi-active replication for globally distributed applications.
  name: Global Tables
- description: Automatically scale throughput capacity based on workload without capacity planning.
  name: On-Demand Capacity
- description: Capture item-level changes for real-time processing, replication, and event-driven architectures.
  name: DynamoDB Streams
- description: Continuous backups with restore to any second within the last 35 days.
  name: Point-in-Time Recovery
- description: ACID transactions across multiple items and tables for complex business logic.
  name: Transactions
- description: Execute SQL-compatible queries against DynamoDB tables using PartiQL language.
  name: PartiQL Support
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Trigger Lambda functions from DynamoDB Streams for event-driven processing.
  name: AWS Lambda
- description: Export table data to S3 or import from S3 for analytics and data migration.
  name: Amazon S3
- description: Stream DynamoDB changes to Kinesis for real-time analytics pipelines.
  name: Amazon Kinesis
- description: Provision and manage DynamoDB tables as infrastructure as code.
  name: AWS CloudFormation
- description: Monitor table metrics, set alarms, and track performance with CloudWatch integration.
  name: Amazon CloudWatch
jsonld:
- class_count: 0
  name: Dynamodb Context
  property_count: 0
  slug: dynamodb-context
layout: provider
modified: '2026-04-18'
name: Amazon DynamoDB
rules:
- name: Amazon DynamoDB API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: dynamodb-spectral-rules
skills: []
slug: dynamodb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon DynamoDB\ndescription: >-\n  A fully managed NoSQL database service that provides fast and predictable performance\n  with seamless scalability.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ntags:\n  - AWS\n  - Cloud\n  - Database\n  - Document Store\n  - Key-Value\n  - Managed Service\n  - NoSQL\n  - Serverless\ncreated: '2024'\nmodified: '2026-04-18'\nurl: https://aws.amazon.com/dynamodb/\nspecificationVersion: '0.18'\napis:\n  - name: Amazon DynamoDB API\n    description: >-\n      RESTful API for interacting with DynamoDB tables and items.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/dynamodb/\n    baseURL: https://dynamodb.{region}.amazonaws.com\n    tags:\n      - Database\n      - Items\n      - Managed Service\n      - NoSQL\n      - Queries\n      - Tables\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/dynamodb/\n\
  \      - type: OpenAPI\n        url: openapi/dynamodb-openapi.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/Welcome.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStartedDynamoDB.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n      - type: Pricing\n        url: https://aws.amazon.com/dynamodb/pricing/\n      - type: Console\n        url: https://console.aws.amazon.com/dynamodb/\n      - type: BestPractices\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/best-practices.html\n      - type: FAQ\n        url: https://aws.amazon.com/dynamodb/faqs/\n      - type: StatusPage\n        url: https://status.aws.amazon.com/\n      - type: Security\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/security.html\n      - type: Features\n        url: https://aws.amazon.com/dynamodb/features/\n\
  \      - type: JSONSchema\n        url: json-schema/dynamodb-item-schema.json\n      - type: JSONLD\n        url: json-ld/dynamodb-context.jsonld\n    contact:\n      - type: Support\n        url: https://aws.amazon.com/premiumsupport/\n  - name: Amazon DynamoDB Streams API\n    description: >-\n      API for capturing and processing change data from DynamoDB tables in near real-time,\n      providing time-ordered sequences of item-level modifications.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Streams.html\n    baseURL: https://streams.dynamodb.{region}.amazonaws.com\n    tags:\n      - Change Data Capture\n      - Event-Driven\n      - Real-Time\n      - Streams\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Streams.html\n      - type: AsyncAPI\n        url: asyncapi/dynamodb-streams-asyncapi.yml\n\
  \      - type: APIReference\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/API_Operations_Amazon_DynamoDB_Streams.html\n  - name: Amazon DynamoDB Accelerator (DAX) API\n    description: >-\n      API for managing DynamoDB Accelerator (DAX) clusters, an in-memory caching service\n      that delivers microsecond response times for DynamoDB read workloads.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/dynamodbaccelerator/\n    baseURL: https://dax.{region}.amazonaws.com\n    tags:\n      - Accelerator\n      - Caching\n      - In-Memory\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DAX.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/dax/2017-04-19/openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/API_Types_Amazon_DynamoDB_Accelerator__DAX_.html\n\
  common:\n  - type: Blog\n    url: https://aws.amazon.com/blogs/database/category/database/amazon-dynamodb/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Resources\n    url: https://aws.amazon.com/dynamodb/resources/\n  - type: SpectralRules\n    url: rules/dynamodb-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/dynamodb-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/database-management.yaml\n  - type: Features\n    data:\n      - name: Single-Digit Millisecond Performance\n        description: Consistent low-latency reads and writes at any scale with SSD-backed storage.\n      - name: Global Tables\n        description: Multi-region, multi-active replication for globally distributed applications.\n      - name: On-Demand Capacity\n        description: Automatically scale throughput\
  \ capacity based on workload without capacity planning.\n      - name: DynamoDB Streams\n        description: Capture item-level changes for real-time processing, replication, and event-driven architectures.\n      - name: Point-in-Time Recovery\n        description: Continuous backups with restore to any second within the last 35 days.\n      - name: Transactions\n        description: ACID transactions across multiple items and tables for complex business logic.\n      - name: PartiQL Support\n        description: Execute SQL-compatible queries against DynamoDB tables using PartiQL language.\n  - type: UseCases\n    data:\n      - name: Serverless Application Backend\n        description: Use as the data layer for serverless architectures with Lambda and API Gateway.\n      - name: Gaming Leaderboards\n        description: Store and query player data, session state, and leaderboards with consistent low latency.\n      - name: IoT Data Storage\n        description: Ingest and query high-volume\
  \ time-series data from IoT devices at scale.\n      - name: E-Commerce Shopping Cart\n        description: Store shopping cart and session data with high availability and automatic scaling.\n  - type: Integrations\n    data:\n      - name: AWS Lambda\n        description: Trigger Lambda functions from DynamoDB Streams for event-driven processing.\n      - name: Amazon S3\n        description: Export table data to S3 or import from S3 for analytics and data migration.\n      - name: Amazon Kinesis\n        description: Stream DynamoDB changes to Kinesis for real-time analytics pipelines.\n      - name: AWS CloudFormation\n        description: Provision and manage DynamoDB tables as infrastructure as code.\n      - name: Amazon CloudWatch\n        description: Monitor table metrics, set alarms, and track performance with CloudWatch integration.\nmaintainers:\n  - name: Amazon Web Services\n    email: aws-dynamodb@amazon.com\n    url: https://aws.amazon.com\n  - name: Kin Lane\n    email:\
  \ kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dynamodb/refs/heads/main/apis.yml
tags:
- AWS
- Cloud
- Database
- Document Store
- Key-Value
- Managed Service
- NoSQL
- Serverless
url: https://aws.amazon.com/dynamodb/
use_cases:
- description: Use as the data layer for serverless architectures with Lambda and API Gateway.
  name: Serverless Application Backend
- description: Store and query player data, session state, and leaderboards with consistent low latency.
  name: Gaming Leaderboards
- description: Ingest and query high-volume time-series data from IoT devices at scale.
  name: IoT Data Storage
- description: Store shopping cart and session data with high availability and automatic scaling.
  name: E-Commerce Shopping Cart
---
