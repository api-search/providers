---
api_count: 1
apis:
- description: Amazon MemoryDB for Redis is a durable, in-memory database service that delivers ultra-fast performance. It is Redis-compatible and provides microsecond reads, low single-digit millisecond writes, and
  name: Amazon MemoryDB API
  slug: memorydb-api
capabilities:
- description: Workflow capability for Amazon MemoryDB media processing operations for broadcast engineers and media developers.
  name: Amazon MemoryDB Workflow
  slug: amazon-memorydb-media-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/memorydb/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/memorydb/
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
  url: https://aws.amazon.com/blogs/media/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/memorydb/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-memorydb-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-memorydb-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-memorydb-media-workflow.yaml
created: '2026-03-16'
description: Amazon MemoryDB for Redis is a durable, in-memory database service that delivers ultra-fast performance. It is Redis-compatible and provides microsecond reads, low single-digit millisecond writes, and enterprise-grade security.
features:
- description: Fully compatible with Redis and Memcached data structures, APIs, and commands.
  name: Redis Compatibility
- description: Multi-AZ transactional log ensures data durability without sacrificing performance.
  name: Durable In-Memory Storage
- description: Microsecond read and low single-digit millisecond write latency at scale.
  name: Ultra-Fast Performance
- description: Create and manage MemoryDB clusters, shards, and replicas with ease.
  name: Cluster Management
- description: Create point-in-time snapshots for backup and restore operations.
  name: Snapshot and Restore
- description: Fine-grained access control with user-based ACLs for security.
  name: Access Control Lists
- description: Deploy clusters across multiple AWS regions for global low-latency access.
  name: Multi-Region Clusters
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy MemoryDB clusters within a VPC for network isolation.
  name: Amazon VPC
- description: Encrypt data at rest using AWS Key Management Service keys.
  name: AWS KMS
- description: Monitor cluster metrics including cache hits, memory usage, and connections.
  name: Amazon CloudWatch
- description: Control access using IAM policies and roles.
  name: AWS IAM
- description: Migrate from ElastiCache Redis to MemoryDB for durable storage.
  name: Amazon ElastiCache
jsonld:
- class_count: 11
  name: Amazon Memorydb Memorydb Api Context
  property_count: 21
  slug: amazon-memorydb-memorydb-api-context
layout: provider
modified: '2026-04-19'
name: Amazon MemoryDB
rules:
- name: Amazon MemoryDB API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: amazon-memorydb-spectral-rules
skills: []
slug: amazon-memorydb
solutions: []
source_yaml: "aid: amazon-memorydb\nname: Amazon MemoryDB\ndescription: Amazon MemoryDB for Redis is a durable, in-memory database service that delivers ultra-fast performance. It is Redis-compatible and provides microsecond reads, low single-digit \n  millisecond writes, and enterprise-grade security.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Broadcasting\n- Media Processing\n- Media\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-memorydb/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-memorydb:memorydb-api\n  name: Amazon MemoryDB API\n  description: Amazon MemoryDB for Redis is a durable, in-memory database service that delivers ultra-fast performance. It is Redis-compatible and provides microsecond reads, low single-digit \n    millisecond writes, and enterprise-grade security.\n  humanURL: https://aws.amazon.com/memorydb/\n\
  \  baseURL: https://memory-db.us-east-1.amazonaws.com\n  tags:\n  - Broadcasting\n  - Media Processing\n  - Media\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/memorydb/\n  - type: OpenAPI\n    url: openapi/amazon-memorydb-openapi-original.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/memorydb/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/memorydb/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/memorydb/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/memorydb/\n- type: Documentation\n  url: https://docs.aws.amazon.com/memorydb/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/media/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/memorydb/\n\
  - type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-memorydb-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-memorydb-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-memorydb-media-workflow.yaml\n- type: Features\n  data:\n  - name: Redis Compatibility\n    description: Fully compatible with Redis and Memcached data structures, APIs, and commands.\n  - name: Durable In-Memory Storage\n    description: Multi-AZ transactional log ensures data durability without sacrificing performance.\n  - name: Ultra-Fast Performance\n    description: Microsecond read and low single-digit millisecond write latency at scale.\n  - name: Cluster Management\n    description: Create and manage MemoryDB clusters, shards, and replicas with ease.\n  - name: Snapshot and Restore\n  \
  \  description: Create point-in-time snapshots for backup and restore operations.\n  - name: Access Control Lists\n    description: Fine-grained access control with user-based ACLs for security.\n  - name: Multi-Region Clusters\n    description: Deploy clusters across multiple AWS regions for global low-latency access.\n- type: UseCases\n  data:\n  - name: Microservices Session Management\n    description: Store session data with ultra-low latency for modern microservices applications.\n  - name: Real-Time Leaderboards\n    description: Maintain sorted sets for gaming leaderboards and ranking systems.\n  - name: Caching Layer\n    description: Use as a durable caching layer to reduce database load and improve response times.\n  - name: Pub/Sub Messaging\n    description: Build real-time messaging and event streaming with Redis pub/sub patterns.\n- type: Integrations\n  data:\n  - name: Amazon VPC\n    description: Deploy MemoryDB clusters within a VPC for network isolation.\n  - name:\
  \ AWS KMS\n    description: Encrypt data at rest using AWS Key Management Service keys.\n  - name: Amazon CloudWatch\n    description: Monitor cluster metrics including cache hits, memory usage, and connections.\n  - name: AWS IAM\n    description: Control access using IAM policies and roles.\n  - name: Amazon ElastiCache\n    description: Migrate from ElastiCache Redis to MemoryDB for durable storage.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-memorydb/refs/heads/main/apis.yml
tags:
- AWS
- Broadcasting
- Media Processing
- Media
url: https://raw.githubusercontent.com/api-evangelist/amazon-memorydb/refs/heads/main/apis.yml
use_cases:
- description: Store session data with ultra-low latency for modern microservices applications.
  name: Microservices Session Management
- description: Maintain sorted sets for gaming leaderboards and ranking systems.
  name: Real-Time Leaderboards
- description: Use as a durable caching layer to reduce database load and improve response times.
  name: Caching Layer
- description: Build real-time messaging and event streaming with Redis pub/sub patterns.
  name: Pub/Sub Messaging
---
