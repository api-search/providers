---
api_count: 1
apis:
- description: ShardingSphere provides ShardingSphere-JDBC for Java applications, ShardingSphere-Proxy with MySQL/PostgreSQL wire protocol compatibility, DistSQL for distributed database management, and a Governance
  name: Apache ShardingSphere
  slug: apache-shardingsphere
capabilities:
- description: ''
  name: Shardingsphere Workflow
  slug: shardingsphere-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/shardingsphere
- title: ''
  type: Documentation
  url: https://shardingsphere.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-shardingsphere-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-shardingsphere-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shardingsphere-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-shardingsphere-context.jsonld
created: '2026-03-16'
description: Apache ShardingSphere is an open-source ecosystem for distributed database systems providing data sharding, distributed transactions, and database governance. It supports MySQL, PostgreSQL, and other databases with transparent sharding capabilities.
features:
- description: Horizontal database sharding with flexible sharding algorithms
  name: Database Sharding
- description: Transparent primary/replica read-write splitting
  name: Read-Write Splitting
- description: XA and BASE distributed transaction support
  name: Distributed Transactions
- description: Transparent data encryption at the SQL layer
  name: Data Encryption
- description: Shadow database for production traffic testing
  name: Shadow Database
- description: SQL-based distributed database management language
  name: DistSQL
- description: Query across heterogeneous database instances
  name: Database Federation
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: MySQL-compatible sharding and proxy
  name: MySQL
- description: PostgreSQL protocol support for sharding
  name: PostgreSQL
- description: Cluster coordination and configuration storage
  name: Apache ZooKeeper
- description: ShardingSphere Spring Boot starter for Java applications
  name: Spring Boot
- description: Kubernetes operator for cloud-native deployment
  name: Kubernetes
jsonld:
- class_count: 14
  name: Apache Shardingsphere Context
  property_count: 27
  slug: apache-shardingsphere-context
layout: provider
modified: '2026-04-19'
name: Apache ShardingSphere
rules:
- name: Apache ShardingSphere API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-shardingsphere-spectral-rules
skills: []
slug: apache-shardingsphere
solutions: []
tags:
- Database
- Distributed SQL
- Read-Write Splitting
- Sharding
- SQL
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/apis.yml
use_cases:
- description: Horizontally scale relational databases without changing application code
  name: Database Scale-Out
- description: Shard data by tenant ID for SaaS applications
  name: Multi-Tenant Sharding
- description: Scale read traffic with primary/replica splitting
  name: Read Scaling
- description: Online data migration between database clusters
  name: Data Migration
---
