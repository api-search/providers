---
api_count: 1
apis:
- description: REST management API for Amazon Aurora DSQL covering cluster creation, configuration, multi-region deployments, and connection endpoint management.
  name: Amazon Aurora DSQL API
  slug: amazon-aurora-dsql-api
capabilities:
- description: Workflow capability for creating and managing distributed SQL clusters with Amazon Aurora DSQL including multi-region configurations.
  name: Distributed SQL Management Workflow
  slug: distributed-sql-management
common: []
created: '2026-03-16'
description: Amazon Aurora DSQL is a distributed SQL database service optimized for transactional workloads. It provides a serverless, fully managed PostgreSQL-compatible database with built-in high availability, scalability, and global distribution capabilities.
features:
- Serverless PostgreSQL-compatible distributed SQL database
- Automatic scaling with no database instances to manage
- Multi-region active-active replication for global distribution
- Built-in high availability with automatic failover
- Pay-per-use pricing based on I/O and storage
- Standard PostgreSQL client compatibility
- Transactional consistency across distributed nodes
- Integrated with AWS IAM for authentication
- Automatic software patching and maintenance
- Point-in-time recovery with continuous backups
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- Amazon VPC
- AWS IAM
- Amazon CloudWatch
- AWS CloudTrail
- Amazon RDS
- AWS KMS
- Amazon Route 53
- AWS PrivateLink
- Amazon S3
- AWS Secrets Manager
jsonld:
- class_count: 4
  name: Amazon Aurora Dsql Context
  property_count: 0
  slug: amazon-aurora-dsql-context
layout: provider
modified: '2026-04-19'
name: Amazon Aurora DSQL
rules:
- name: Amazon Aurora DSQL API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: amazon-aurora-dsql-spectral-rules
skills: []
slug: amazon-aurora-dsql
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-aurora-dsql\nname: Amazon Aurora DSQL\ndescription: >-\n  Amazon Aurora DSQL is a distributed SQL database service optimized for transactional workloads. It provides a serverless, fully managed PostgreSQL-compatible database with built-in high availability, scalability, and global distribution capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon Aurora DSQL\n  - Distributed SQL\n  - PostgreSQL\n  - Serverless\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-aurora-dsql:amazon-aurora-dsql-api\n    name: Amazon Aurora DSQL API\n    description: >-\n      REST management API for Amazon Aurora DSQL covering cluster creation, configuration, multi-region deployments, and connection endpoint management.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://docs.aws.amazon.com/aurora-dsql/latest/userguide/getting-started.html\n    baseURL: https://dsql.us-east-1.amazonaws.com\n    tags:\n      - Amazon Aurora DSQL\n      - Distributed SQL\n      - PostgreSQL\n      - Serverless\n      - AWS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/openapi/amazon-aurora-dsql-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/rules/amazon-aurora-dsql-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/capabilities/shared/aurora-dsql-api.yaml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/capabilities/distributed-sql-management.yaml\n\
  \      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/vocabulary/amazon-aurora-dsql-vocabulary.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/json-schema/aurora-dsql-cluster-summary-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/json-schema/aurora-dsql-create-cluster-input-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/json-structure/aurora-dsql-cluster-summary-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/json-structure/aurora-dsql-get-cluster-output-structure.json\n      - type: JSONLD\n      \
  \  url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/json-ld/amazon-aurora-dsql-context.jsonld\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/examples/aurora-dsql-create-cluster-input-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/examples/aurora-dsql-get-cluster-output-example.json\ncommon:\n  - type: Features\n    data:\n      - Serverless PostgreSQL-compatible distributed SQL database\n      - Automatic scaling with no database instances to manage\n      - Multi-region active-active replication for global distribution\n      - Built-in high availability with automatic failover\n      - Pay-per-use pricing based on I/O and storage\n      - Standard PostgreSQL client compatibility\n      - Transactional consistency across distributed nodes\n     \
  \ - Integrated with AWS IAM for authentication\n      - Automatic software patching and maintenance\n      - Point-in-time recovery with continuous backups\n  - type: UseCases\n    data:\n      - Build globally distributed transactional applications\n      - Run PostgreSQL workloads without managing instances\n      - Deploy active-active multi-region database architectures\n      - Migrate PostgreSQL applications to serverless infrastructure\n      - Build applications requiring strong consistency at global scale\n      - Implement high-throughput transactional microservices\n  - type: Integrations\n    data:\n      - Amazon VPC\n      - AWS IAM\n      - Amazon CloudWatch\n      - AWS CloudTrail\n      - Amazon RDS\n      - AWS KMS\n      - Amazon Route 53\n      - AWS PrivateLink\n      - Amazon S3\n      - AWS Secrets Manager\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/apis.yml
tags:
- Amazon Aurora DSQL
- Distributed SQL
- PostgreSQL
- Serverless
- AWS
url: https://raw.githubusercontent.com/api-evangelist/amazon-aurora-dsql/refs/heads/main/apis.yml
use_cases:
- Build globally distributed transactional applications
- Run PostgreSQL workloads without managing instances
- Deploy active-active multi-region database architectures
- Migrate PostgreSQL applications to serverless infrastructure
- Build applications requiring strong consistency at global scale
- Implement high-throughput transactional microservices
---
