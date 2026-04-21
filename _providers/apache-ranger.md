---
api_count: 1
apis:
- description: 'The Ranger REST API provides endpoints for policy management, service management, user/group management, audit log retrieval, and security zone administration, with plugin APIs for enforcing policies '
  name: Apache Ranger REST API
  slug: apache-ranger-rest-api
capabilities:
- description: ''
  name: Ranger Workflow
  slug: ranger-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/ranger
- title: ''
  type: Documentation
  url: https://ranger.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-ranger-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-ranger-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ranger-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-ranger-context.jsonld
created: '2026-03-16'
description: Apache Ranger is a framework to enable, monitor, and manage comprehensive data security across the Hadoop platform. It provides centralized security administration for fine-grained authorization policies across Hadoop ecosystem components.
features:
- description: Manage security policies for all Hadoop services from a single interface
  name: Centralized Policy Management
- description: Column-level, row-level, and data masking policies for Hive and HBase
  name: Fine-Grained Access Control
- description: Context-aware policies based on user attributes and tag classifications
  name: Attribute-Based Access Control
- description: Comprehensive audit trail of all resource access events
  name: Audit Logging
- description: Supports HDFS, Hive, HBase, Kafka, Storm, Solr, Kudu, and more
  name: Multi-Service Support
- description: Sync users and groups from Active Directory or LDAP
  name: LDAP/AD Integration
- description: Delegate policy administration with security zones
  name: Security Zones
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native HDFS and YARN authorization integration
  name: Apache Hadoop
- description: Column-level and row-level security for Hive queries
  name: Apache Hive
- description: Table and column family security for HBase
  name: Apache HBase
- description: Topic-level authorization for Kafka producers and consumers
  name: Apache Kafka
- description: Tag-based policies using Atlas data classifications
  name: Apache Atlas
jsonld:
- class_count: 13
  name: Apache Ranger Context
  property_count: 42
  slug: apache-ranger-context
layout: provider
modified: '2026-04-19'
name: Apache Ranger
rules:
- name: Apache Ranger API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-ranger-spectral-rules
skills: []
slug: apache-ranger
solutions: []
tags:
- Access Control
- Authorization
- Hadoop
- Policy Management
- Security
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/apis.yml
use_cases:
- description: Enforce column and row-level security on Hadoop data lake
  name: Data Lake Security
- description: Meet GDPR, HIPAA, and SOX requirements with audit logs and masking
  name: Regulatory Compliance
- description: Isolate access between teams and business units
  name: Multi-Tenant Authorization
- description: Control which applications can produce and consume Kafka topics
  name: Kafka Topic Authorization
---
