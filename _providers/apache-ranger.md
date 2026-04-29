---
api_count: 1
api_specs:
- filename: apache-ranger-rest-api.yaml
  format: yaml
  label: Apache Ranger REST API
  slug: apache-ranger-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/openapi/apache-ranger-rest-api.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-ranger\nname: Apache Ranger\ndescription: >-\n  Apache Ranger is a framework to enable, monitor, and manage comprehensive data security across the Hadoop platform. It provides centralized security administration for fine-grained authorization policies\n  across Hadoop ecosystem components.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Access Control\n- Authorization\n- Hadoop\n- Policy Management\n- Security\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-ranger:apache-ranger-rest-api\n  name: Apache Ranger REST API\n  description: >-\n    The Ranger REST API provides endpoints for policy management, service management, user/group management, audit log retrieval, and security zone administration,\
  \ with plugin APIs for enforcing policies\n    in HDFS, Hive, HBase, and other services.\n  humanURL: https://ranger.apache.org/apidocs/index.html\n  tags:\n  - Access Control\n  - Policy Management\n  - REST\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://ranger.apache.org/apidocs/index.html\n  - type: Documentation\n    url: https://ranger.apache.org/\n  - type: OpenAPI\n    url: openapi/apache-ranger-rest-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/ranger\n- type: Documentation\n  url: https://ranger.apache.org/\n- type: SpectralRules\n  url: rules/apache-ranger-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-ranger-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/ranger-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-ranger-context.jsonld\n- type: Features\n  data:\n  - name: Centralized Policy Management\n \
  \   description: Manage security policies for all Hadoop services from a single interface\n  - name: Fine-Grained Access Control\n    description: Column-level, row-level, and data masking policies for Hive and HBase\n  - name: Attribute-Based Access Control\n    description: Context-aware policies based on user attributes and tag classifications\n  - name: Audit Logging\n    description: Comprehensive audit trail of all resource access events\n  - name: Multi-Service Support\n    description: Supports HDFS, Hive, HBase, Kafka, Storm, Solr, Kudu, and more\n  - name: LDAP/AD Integration\n    description: Sync users and groups from Active Directory or LDAP\n  - name: Security Zones\n    description: Delegate policy administration with security zones\n- type: UseCases\n  data:\n  - name: Data Lake Security\n    description: Enforce column and row-level security on Hadoop data lake\n  - name: Regulatory Compliance\n    description: Meet GDPR, HIPAA, and SOX requirements with audit logs and\
  \ masking\n  - name: Multi-Tenant Authorization\n    description: Isolate access between teams and business units\n  - name: Kafka Topic Authorization\n    description: Control which applications can produce and consume Kafka topics\n- type: Integrations\n  data:\n  - name: Apache Hadoop\n    description: Native HDFS and YARN authorization integration\n  - name: Apache Hive\n    description: Column-level and row-level security for Hive queries\n  - name: Apache HBase\n    description: Table and column family security for HBase\n  - name: Apache Kafka\n    description: Topic-level authorization for Kafka producers and consumers\n  - name: Apache Atlas\n    description: Tag-based policies using Atlas data classifications\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-ranger/refs/heads/main/apis.yml
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
