---
api_count: 1
apis:
- description: REST management API for Amazon Athena covering query executions, named queries, work groups, data catalogs, databases, table metadata, and prepared statements.
  name: Amazon Athena API
  slug: amazon-athena-api
capabilities:
- description: Workflow capability for running and managing SQL analytics queries with Amazon Athena including query execution, named queries, work groups, and data catalog management.
  name: SQL Analytics Workflow
  slug: sql-analytics
common: []
created: '2024-01-15'
description: Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.
features:
- Serverless SQL query execution against Amazon S3 data
- Pay-per-query pricing with no infrastructure management
- Support for standard ANSI SQL with complex joins and window functions
- Integration with AWS Glue Data Catalog for schema management
- Named queries for saving and reusing SQL statements
- Work groups for query isolation and cost management
- Prepared statements for parameterized query execution
- Multiple data format support including Parquet, ORC, JSON, CSV
- Query result caching for improved performance and cost reduction
- Fine-grained access control with IAM and Lake Formation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- Amazon S3
- AWS Glue
- Amazon QuickSight
- AWS Lake Formation
- Amazon CloudWatch
- AWS IAM
- Amazon DynamoDB
- AWS Step Functions
- Amazon SageMaker
- Apache Spark
jsonld:
- class_count: 11
  name: Amazon Athena Context
  property_count: 0
  slug: amazon-athena-context
layout: provider
modified: '2026-04-19'
name: Amazon Athena
rules:
- name: Amazon Athena API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 0
    warn: 7
  slug: amazon-athena-spectral-rules
skills: []
slug: amazon-athena
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-athena\nname: Amazon Athena\ndescription: >-\n  Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon Athena\n  - SQL\n  - Analytics\n  - Serverless\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-athena:amazon-athena-api\n    name: Amazon Athena API\n    description: >-\n      REST management API for Amazon Athena covering query executions, named queries, work groups, data catalogs, databases, table metadata, and prepared statements.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n   \
  \ humanURL: https://docs.aws.amazon.com/athena/latest/APIReference/Welcome.html\n    baseURL: https://athena.us-east-1.amazonaws.com\n    tags:\n      - Amazon Athena\n      - SQL\n      - Analytics\n      - Serverless\n      - AWS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/openapi/amazon-athena-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/rules/amazon-athena-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/capabilities/shared/athena-api.yaml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/capabilities/sql-analytics.yaml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/vocabulary/amazon-athena-vocabulary.yaml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/json-schema/athena-query-execution-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/json-schema/athena-named-query-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/json-schema/athena-work-group-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/json-structure/athena-query-execution-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/json-structure/athena-work-group-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/json-ld/amazon-athena-context.jsonld\n\
  \      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/examples/athena-query-execution-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/examples/athena-named-query-example.json\ncommon:\n  - type: Features\n    data:\n      - Serverless SQL query execution against Amazon S3 data\n      - Pay-per-query pricing with no infrastructure management\n      - Support for standard ANSI SQL with complex joins and window functions\n      - Integration with AWS Glue Data Catalog for schema management\n      - Named queries for saving and reusing SQL statements\n      - Work groups for query isolation and cost management\n      - Prepared statements for parameterized query execution\n      - Multiple data format support including Parquet, ORC, JSON, CSV\n      - Query result caching for improved performance and cost reduction\n    \
  \  - Fine-grained access control with IAM and Lake Formation\n  - type: UseCases\n    data:\n      - Analyze log files and clickstream data stored in S3\n      - Run ad-hoc SQL queries on data lake without ETL\n      - Build serverless data pipelines and reporting solutions\n      - Query AWS service logs including CloudTrail, ELB, and VPC Flow Logs\n      - Perform cost analysis on AWS Cost and Usage Reports\n      - Enable self-service analytics for business intelligence teams\n  - type: Integrations\n    data:\n      - Amazon S3\n      - AWS Glue\n      - Amazon QuickSight\n      - AWS Lake Formation\n      - Amazon CloudWatch\n      - AWS IAM\n      - Amazon DynamoDB\n      - AWS Step Functions\n      - Amazon SageMaker\n      - Apache Spark\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/apis.yml
tags:
- Amazon Athena
- SQL
- Analytics
- Serverless
- AWS
url: https://raw.githubusercontent.com/api-evangelist/amazon-athena/refs/heads/main/apis.yml
use_cases:
- Analyze log files and clickstream data stored in S3
- Run ad-hoc SQL queries on data lake without ETL
- Build serverless data pipelines and reporting solutions
- Query AWS service logs including CloudTrail, ELB, and VPC Flow Logs
- Perform cost analysis on AWS Cost and Usage Reports
- Enable self-service analytics for business intelligence teams
---
