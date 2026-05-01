---
api_count: 1
api_specs:
- filename: amazon-documentdb-openapi.yml
  format: yaml
  label: Amazon DocumentDB API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-documentdb/refs/heads/main/openapi/amazon-documentdb-openapi.yml
apis:
- description: API for managing Amazon DocumentDB clusters, instances, parameter groups, subnet groups, snapshots, and related resources.
  name: Amazon DocumentDB API
  slug: ''
capabilities:
- description: Unified capability for managing DocumentDB clusters, instances, and snapshots for DevOps and database administrators.
  name: Amazon DocumentDB Document Database Management
  slug: documentdb-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/developer/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/documentdb/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/database/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/docdb/
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
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-documentdb
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-documentdb-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-documentdb-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/documentdb-management.yaml
created: '2024-01-15'
description: Amazon DocumentDB is a fully managed, MongoDB-compatible document database service that makes it easy to set up, operate, and scale MongoDB-compatible databases in the cloud. DocumentDB is designed from the ground up to give you the performance, scalability, and availability you need when operating mission-critical MongoDB workloads at scale.
features:
- description: Automatically scales capacity up or down in fine-grained increments based on application demand, with up to 90% cost savings versus peak provisioning.
  name: Serverless Architecture
- description: Migrate applications typically without code changes or downtime using existing MongoDB drivers and tools.
  name: MongoDB Compatibility
- description: Automatically replicates data across up to 10 AWS Regions for low-latency reads and disaster recovery.
  name: Global Clusters
- description: Eliminates database patching, backups, and monitoring overhead so you can focus on application development.
  name: Fully Managed
- description: Provides up to 40% cost savings for I/O-intensive workloads with predictable pricing.
  name: I/O-Optimized Storage
- description: Offers memory-optimized instance types with up to 43% cost savings for large workloads.
  name: Memory-Optimized Instances
- description: Continuous backups to Amazon S3 and point-in-time recovery within the backup retention window.
  name: Automated Backups
- description: Data is encrypted using AES-256, with support for AWS KMS customer-managed keys.
  name: Encryption at Rest and in Transit
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Monitor DocumentDB cluster metrics, set alarms, and view performance data through CloudWatch dashboards.
  name: Amazon CloudWatch
- description: Control access to DocumentDB resources and operations using IAM policies and roles.
  name: AWS IAM
- description: Centrally manage and automate backups of DocumentDB clusters using AWS Backup policies.
  name: AWS Backup
- description: Zero-ETL integration to replicate DocumentDB data to OpenSearch for full-text search and analytics.
  name: Amazon OpenSearch Service
- description: Log all DocumentDB API calls for auditing, compliance, and security analysis.
  name: AWS CloudTrail
- description: Manage encryption keys for DocumentDB clusters using KMS customer-managed keys.
  name: AWS Key Management Service
jsonld:
- class_count: 3
  name: Amazon Documentdb Context
  property_count: 28
  slug: amazon-documentdb-context
layout: provider
modified: '2026-04-19'
name: Amazon DocumentDB
rules:
- name: Amazon DocumentDB API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 13
  slug: amazon-documentdb-spectral-rules
skills: []
slug: amazon-documentdb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon DocumentDB\ndescription: Amazon DocumentDB is a fully managed, MongoDB-compatible document database service that makes it easy to set up, operate, and scale MongoDB-compatible databases in the cloud. DocumentDB \n  is designed from the ground up to give you the performance, scalability, and availability you need when operating mission-critical MongoDB workloads at scale.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/documentdb/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n- Amazon Web Services\n- AWS\n- Database\n- Document Database\n- DocumentDB\n- Managed Database\n- MongoDB\n- NoSQL\napis:\n- name: Amazon DocumentDB API\n  description: API for managing Amazon DocumentDB clusters, instances, parameter groups, subnet groups, snapshots, and related resources.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/documentdb/\n\
  \  baseURL: https://rds.amazonaws.com\n  tags:\n  - AWS\n  - Database\n  - Document Database\n  - MongoDB\n  - NoSQL\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/documentdb/latest/developerguide/\n  - type: OpenAPI\n    url: openapi/amazon-documentdb-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/docdb/2014-10-31/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-documentdb-dbcluster-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-documentdb-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/documentdb/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/documentdb/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/documentdb/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/documentdb/latest/developerguide/API_Reference.html\n  - type: Authentication\n    url: https://docs.aws.amazon.com/documentdb/latest/developerguide/security.html\n\
  \  - type: RateLimits\n    url: https://docs.aws.amazon.com/documentdb/latest/developerguide/limits.html\n  - type: JSONStructure\n    url: json-structure/amazon-documentdb-dbcluster-structure.json\n  - type: Example\n    url: examples/amazon-documentdb-dbcluster-example.json\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/developer/\n- type: Documentation\n  url: https://docs.aws.amazon.com/documentdb/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: Blog\n  url: https://aws.amazon.com/blogs/database/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/docdb/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n\
  - type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-documentdb\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Features\n  data:\n  - name: Serverless Architecture\n    description: Automatically scales capacity up or down in fine-grained increments based on application demand, with up to 90% cost savings versus peak provisioning.\n  - name: MongoDB Compatibility\n    description: Migrate applications typically without code changes or downtime using existing MongoDB drivers and tools.\n  - name: Global Clusters\n    description: Automatically replicates data across up to 10 AWS Regions for low-latency reads and disaster recovery.\n  - name: Fully Managed\n    description: Eliminates\
  \ database patching, backups, and monitoring overhead so you can focus on application development.\n  - name: I/O-Optimized Storage\n    description: Provides up to 40% cost savings for I/O-intensive workloads with predictable pricing.\n  - name: Memory-Optimized Instances\n    description: Offers memory-optimized instance types with up to 43% cost savings for large workloads.\n  - name: Automated Backups\n    description: Continuous backups to Amazon S3 and point-in-time recovery within the backup retention window.\n  - name: Encryption at Rest and in Transit\n    description: Data is encrypted using AES-256, with support for AWS KMS customer-managed keys.\n- type: UseCases\n  data:\n  - name: Content Management Systems\n    description: Store and retrieve flexible JSON-structured content with rich query capabilities for CMS platforms.\n  - name: E-Commerce Platforms\n    description: Manage product catalogs, user profiles, and order data with scalable document storage.\n  - name: Mobile\
  \ and Web Applications\n    description: Power real-time application backends with low-latency, scalable document storage.\n  - name: Generative AI Applications\n    description: Store and retrieve context, embeddings, and conversational history for AI-powered agentic applications.\n  - name: Gaming Applications\n    description: Handle player profiles, leaderboards, and game state with flexible schema and high throughput.\n- type: Integrations\n  data:\n  - name: Amazon CloudWatch\n    description: Monitor DocumentDB cluster metrics, set alarms, and view performance data through CloudWatch dashboards.\n  - name: AWS IAM\n    description: Control access to DocumentDB resources and operations using IAM policies and roles.\n  - name: AWS Backup\n    description: Centrally manage and automate backups of DocumentDB clusters using AWS Backup policies.\n  - name: Amazon OpenSearch Service\n    description: Zero-ETL integration to replicate DocumentDB data to OpenSearch for full-text search and\
  \ analytics.\n  - name: AWS CloudTrail\n    description: Log all DocumentDB API calls for auditing, compliance, and security analysis.\n  - name: AWS Key Management Service\n    description: Manage encryption keys for DocumentDB clusters using KMS customer-managed keys.\n- type: SpectralRules\n  url: rules/amazon-documentdb-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-documentdb-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/documentdb-management.yaml\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-documentdb/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- Database
- Document Database
- DocumentDB
- Managed Database
- MongoDB
- NoSQL
url: https://aws.amazon.com/documentdb/
use_cases:
- description: Store and retrieve flexible JSON-structured content with rich query capabilities for CMS platforms.
  name: Content Management Systems
- description: Manage product catalogs, user profiles, and order data with scalable document storage.
  name: E-Commerce Platforms
- description: Power real-time application backends with low-latency, scalable document storage.
  name: Mobile and Web Applications
- description: Store and retrieve context, embeddings, and conversational history for AI-powered agentic applications.
  name: Generative AI Applications
- description: Handle player profiles, leaderboards, and game state with flexible schema and high throughput.
  name: Gaming Applications
---
