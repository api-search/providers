---
api_count: 1
apis:
- description: REST management API for Amazon Aurora covering DB clusters, DB instances, cluster snapshots, parameter groups, custom endpoints, and global database management.
  name: Amazon Aurora API
  slug: amazon-aurora-api
capabilities:
- description: Workflow capability for managing Amazon Aurora relational database clusters including creation, scaling, snapshots, and global database configurations.
  name: Relational Database Management Workflow
  slug: relational-database-management
common: []
created: '2024-01-15'
description: Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.
features:
- MySQL and PostgreSQL compatible relational database engine
- Up to 5x throughput of standard MySQL and 3x of standard PostgreSQL
- Auto-scaling storage from 10GB to 128TB
- Up to 15 low-latency read replicas
- Aurora Serverless for intermittent and unpredictable workloads
- Aurora Global Database for multi-region deployments
- Continuous backup to Amazon S3 with point-in-time recovery
- Fast database cloning for testing and development
- Parallel query for faster analytical queries
- Machine learning integration through Aurora ML
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- Amazon RDS
- Amazon S3
- AWS Lambda
- Amazon CloudWatch
- AWS IAM
- Amazon VPC
- AWS KMS
- AWS Secrets Manager
- Amazon SageMaker
- AWS DMS
jsonld:
- class_count: 0
  name: Amazon Aurora Context
  property_count: 4
  slug: amazon-aurora-context
layout: provider
modified: '2026-04-19'
name: Amazon Aurora
rules:
- name: Amazon Aurora API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 6
  slug: amazon-aurora-spectral-rules
skills: []
slug: amazon-aurora
solutions: []
source_yaml: "aid: amazon-aurora\nname: Amazon Aurora\ndescription: >-\n  Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon Aurora\n  - MySQL\n  - PostgreSQL\n  - Relational Database\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-aurora:amazon-aurora-api\n    name: Amazon Aurora API\n    description: >-\n      REST management API for Amazon Aurora covering DB clusters, DB instances, cluster snapshots, parameter groups, custom endpoints, and global database management.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html\n    baseURL: https://rds.us-east-1.amazonaws.com\n    tags:\n      - Amazon Aurora\n      - MySQL\n      - PostgreSQL\n      - Relational Database\n      - AWS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/openapi/amazon-aurora-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/rules/amazon-aurora-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/capabilities/shared/aurora-api.yaml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/capabilities/relational-database-management.yaml\n      - type: Vocabulary\n\
  \        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/vocabulary/amazon-aurora-vocabulary.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/json-schema/aurora-db-cluster-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/json-schema/aurora-create-db-cluster-input-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/json-structure/aurora-db-cluster-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/json-structure/aurora-db-instance-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/json-ld/amazon-aurora-context.jsonld\n\
  \      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/examples/aurora-db-cluster-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/examples/aurora-create-db-cluster-input-example.json\ncommon:\n  - type: Features\n    data:\n      - MySQL and PostgreSQL compatible relational database engine\n      - Up to 5x throughput of standard MySQL and 3x of standard PostgreSQL\n      - Auto-scaling storage from 10GB to 128TB\n      - Up to 15 low-latency read replicas\n      - Aurora Serverless for intermittent and unpredictable workloads\n      - Aurora Global Database for multi-region deployments\n      - Continuous backup to Amazon S3 with point-in-time recovery\n      - Fast database cloning for testing and development\n      - Parallel query for faster analytical queries\n      - Machine learning integration through Aurora ML\n\
  \  - type: UseCases\n    data:\n      - Enterprise applications requiring high availability and durability\n      - SaaS applications needing scalable multi-tenant databases\n      - E-commerce platforms with variable traffic patterns\n      - Financial applications requiring ACID compliance\n      - Global applications needing low-latency multi-region access\n      - Development and testing with fast database cloning\n  - type: Integrations\n    data:\n      - Amazon RDS\n      - Amazon S3\n      - AWS Lambda\n      - Amazon CloudWatch\n      - AWS IAM\n      - Amazon VPC\n      - AWS KMS\n      - AWS Secrets Manager\n      - Amazon SageMaker\n      - AWS DMS\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/apis.yml
tags:
- Amazon Aurora
- MySQL
- PostgreSQL
- Relational Database
- AWS
url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora/refs/heads/main/apis.yml
use_cases:
- Enterprise applications requiring high availability and durability
- SaaS applications needing scalable multi-tenant databases
- E-commerce platforms with variable traffic patterns
- Financial applications requiring ACID compliance
- Global applications needing low-latency multi-region access
- Development and testing with fast database cloning
---
