---
api_count: 1
api_specs:
- filename: apache-shardingsphere-rest-api.yaml
  format: yaml
  label: Apache ShardingSphere
  slug: apache-shardingsphere
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/openapi/apache-shardingsphere-rest-api.yaml
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
source_filename: apis.yml
source_yaml: "aid: apache-shardingsphere\nname: Apache ShardingSphere\ndescription: >-\n  Apache ShardingSphere is an open-source ecosystem for distributed database systems providing data sharding, distributed transactions, and database governance. It supports MySQL, PostgreSQL, and other\n  databases with transparent sharding capabilities.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Database\n- Distributed SQL\n- Read-Write Splitting\n- Sharding\n- SQL\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-shardingsphere:apache-shardingsphere\n  name: Apache ShardingSphere\n  description: >-\n    ShardingSphere provides ShardingSphere-JDBC for Java applications, ShardingSphere-Proxy with MySQL/PostgreSQL wire protocol\
  \ compatibility, DistSQL for distributed database management, and a Governance\n    API for cluster management.\n  humanURL: https://shardingsphere.apache.org/document/current/en/overview/\n  tags:\n  - Database\n  - Distributed SQL\n  - REST\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://shardingsphere.apache.org/document/current/en/overview/\n  - type: Documentation\n    url: https://shardingsphere.apache.org/document/current/\n  - type: OpenAPI\n    url: openapi/apache-shardingsphere-rest-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/shardingsphere\n- type: Documentation\n  url: https://shardingsphere.apache.org/\n- type: SpectralRules\n  url: rules/apache-shardingsphere-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-shardingsphere-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shardingsphere-workflow.yaml\n- type:\
  \ JSON-LD\n  url: json-ld/apache-shardingsphere-context.jsonld\n- type: Features\n  data:\n  - name: Database Sharding\n    description: Horizontal database sharding with flexible sharding algorithms\n  - name: Read-Write Splitting\n    description: Transparent primary/replica read-write splitting\n  - name: Distributed Transactions\n    description: XA and BASE distributed transaction support\n  - name: Data Encryption\n    description: Transparent data encryption at the SQL layer\n  - name: Shadow Database\n    description: Shadow database for production traffic testing\n  - name: DistSQL\n    description: SQL-based distributed database management language\n  - name: Database Federation\n    description: Query across heterogeneous database instances\n- type: UseCases\n  data:\n  - name: Database Scale-Out\n    description: Horizontally scale relational databases without changing application code\n  - name: Multi-Tenant Sharding\n    description: Shard data by tenant ID for SaaS applications\n\
  \  - name: Read Scaling\n    description: Scale read traffic with primary/replica splitting\n  - name: Data Migration\n    description: Online data migration between database clusters\n- type: Integrations\n  data:\n  - name: MySQL\n    description: MySQL-compatible sharding and proxy\n  - name: PostgreSQL\n    description: PostgreSQL protocol support for sharding\n  - name: Apache ZooKeeper\n    description: Cluster coordination and configuration storage\n  - name: Spring Boot\n    description: ShardingSphere Spring Boot starter for Java applications\n  - name: Kubernetes\n    description: Kubernetes operator for cloud-native deployment\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-shardingsphere/refs/heads/main/apis.yml
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
