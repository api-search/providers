---
api_count: 1
api_specs:
- filename: amazon-elasticache-openapi.yml
  format: yaml
  label: Amazon ElastiCache API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-elasticache/refs/heads/main/openapi/amazon-elasticache-openapi.yml
apis:
- description: API for managing Amazon ElastiCache clusters, replication groups, parameter groups, and related caching infrastructure resources.
  name: Amazon ElastiCache API
  slug: ''
capabilities:
- description: Unified capability for managing Amazon ElastiCache resources. Combines Amazon ElastiCache APIs for Backend Developer workflows in Data Caching.
  name: Amazon ElastiCache Management
  slug: amazon-elasticache-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/elasticache/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/elasticache/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/elasticache/
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
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/elasticache/faqs/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/elasticache
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-elasticache-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-elasticache-capability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-elasticache-vocabulary.yaml
created: '2024-01-15'
description: Amazon ElastiCache is a fully managed in-memory caching service supporting Redis and Memcached. ElastiCache makes it easy to deploy, operate, and scale popular open-source compatible in-memory data stores, improving the performance of web applications.
features:
- description: Fully managed Redis with replication, clustering, and persistence
  name: Redis Support
- description: Fully managed Memcached for simple distributed caching
  name: Memcached Support
- description: Automatic failover with Multi-AZ replication groups
  name: Multi-AZ Replication
- description: Encryption at-rest and in-transit for compliance requirements
  name: Encryption
- description: Scheduled automatic backups with point-in-time recovery
  name: Automatic Backups
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Connect ElastiCache clusters to EC2-hosted applications
  name: Amazon EC2
- description: Cache RDS query results to reduce database load
  name: Amazon RDS
- description: Access ElastiCache from serverless Lambda functions
  name: Amazon Lambda
- description: Use ElastiCache as shared cache for Kubernetes workloads
  name: Amazon EKS
jsonld:
- class_count: 0
  name: Amazon Elasticache Context
  property_count: 3
  slug: amazon-elasticache-context
layout: provider
modified: '2026-04-19'
name: Amazon ElastiCache
rules:
- name: Amazon ElastiCache API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-elasticache-spectral-rules
skills: []
slug: amazon-elasticache
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon ElastiCache\ndescription: Amazon ElastiCache is a fully managed in-memory caching service supporting Redis and Memcached. ElastiCache makes it easy to deploy, operate, and scale popular open-source compatible \n  in-memory data stores, improving the performance of web applications.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/elasticache/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Amazon Web Services\n- AWS\n- Caching\n- Database\n- ElastiCache\n- In-Memory\n- Memcached\n- Redis\napis:\n- name: Amazon ElastiCache API\n  description: API for managing Amazon ElastiCache clusters, replication groups, parameter groups, and related caching infrastructure resources.\n  humanURL: https://aws.amazon.com/elasticache/\n  baseURL: https://elasticache.amazonaws.com\n  tags:\n  - Caching\n  - Database\n  - In-Memory\n  - Redis\n  properties:\n  - type: Documentation\n\
  \    url: https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/\n  - type: OpenAPI\n    url: openapi/amazon-elasticache-openapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/elasticache/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/elasticache/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/elasticache/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-elasticache-cache-cluster-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-elasticache-cachecluster-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-elasticache-create-cache-cluster-result-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-elasticache-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/elasticache/\n- type: Documentation\n  url: https://docs.aws.amazon.com/elasticache/\n\
  - type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/elasticache/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: FAQ\n  url: https://aws.amazon.com/elasticache/faqs/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/elasticache\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: Contact\n  url:\
  \ https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-elasticache-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-elasticache-capability.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/api.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-elasticache-vocabulary.yaml\n- type: Features\n  data:\n  - name: Redis Support\n    description: Fully managed Redis with replication, clustering, and persistence\n  - name: Memcached Support\n    description: Fully managed Memcached for simple distributed caching\n  - name: Multi-AZ Replication\n    description: Automatic failover with Multi-AZ replication groups\n  - name: Encryption\n    description: Encryption at-rest and in-transit for compliance requirements\n  - name: Automatic Backups\n    description: Scheduled automatic backups with point-in-time recovery\n- type: UseCases\n  data:\n  - name: Session Management\n    description: Store and manage user session data for web applications\n\
  \  - name: Database Query Caching\n    description: Cache expensive database queries to reduce latency\n  - name: Real-Time Analytics\n    description: Process and cache real-time data streams for analytics dashboards\n  - name: Leaderboards and Gaming\n    description: Build real-time leaderboards and gaming backends with Redis sorted sets\n- type: Integrations\n  data:\n  - name: Amazon EC2\n    description: Connect ElastiCache clusters to EC2-hosted applications\n  - name: Amazon RDS\n    description: Cache RDS query results to reduce database load\n  - name: Amazon Lambda\n    description: Access ElastiCache from serverless Lambda functions\n  - name: Amazon EKS\n    description: Use ElastiCache as shared cache for Kubernetes workloads\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-elasticache/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- Caching
- Database
- ElastiCache
- In-Memory
- Memcached
- Redis
url: https://aws.amazon.com/elasticache/
use_cases:
- description: Store and manage user session data for web applications
  name: Session Management
- description: Cache expensive database queries to reduce latency
  name: Database Query Caching
- description: Process and cache real-time data streams for analytics dashboards
  name: Real-Time Analytics
- description: Build real-time leaderboards and gaming backends with Redis sorted sets
  name: Leaderboards and Gaming
---
