---
api_count: 1
apis:
- description: The Atlas REST API provides endpoints for managing types, entities, lineage, discovery, and glossary resources, enabling programmatic metadata management and data governance operations. It covers enti
  name: Apache Atlas REST API
  slug: apache-atlas-rest-api
capabilities:
- description: Unified capability for Apache Atlas data governance workflows including metadata discovery, lineage tracking, entity management, and glossary management. Used by data governance teams and data enginee
  name: Apache Atlas Data Governance
  slug: atlas-data-governance
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/atlas
- title: ''
  type: Documentation
  url: https://atlas.apache.org/
- title: ''
  type: GettingStarted
  url: https://atlas.apache.org/quick_start_v2.html
- title: ''
  type: Support
  url: https://atlas.apache.org/mailing_list.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: ChangeLog
  url: https://github.com/apache/atlas/releases
- title: ''
  type: SpectralRules
  url: rules/apache-atlas-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-atlas-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/atlas-data-governance.yaml
created: '2026-03-16'
description: Apache Atlas is a scalable and extensible set of core foundational data governance services developed by the Apache Software Foundation. It enables enterprises to effectively meet their compliance requirements within Hadoop and allows integration with the whole enterprise data ecosystem. Atlas provides metadata management, data classification, lineage tracking, business glossary, and a REST API for programmatic governance operations. It supports discovery, auditing, and policy management for enterprise data assets.
features:
- description: Centrally manage metadata for enterprise data assets including Hive tables, HDFS files, Kafka topics, HBase tables, and Spark jobs.
  name: Metadata Management
- description: Apply classification tags to data assets for sensitivity classification (PII, PHI, confidential) and policy enforcement.
  name: Data Classification
- description: Automatically capture and visualize data lineage across data pipeline stages for impact analysis and compliance.
  name: Data Lineage Tracking
- description: Manage a centralized business glossary of terms and categories to standardize data definitions across the organization.
  name: Business Glossary
- description: Comprehensive REST API for programmatic metadata management, discovery, lineage retrieval, and type definition management.
  name: REST API
- description: Find data assets using basic, full-text, DSL, and attribute-based search across all registered metadata.
  name: Search and Discovery
- description: Integrate with Apache Ranger for attribute-based access control policies driven by Atlas classification tags.
  name: Policy-Based Data Access
- description: Comprehensive audit trail of all metadata changes and entity operations for compliance and governance.
  name: Auditing
- description: Hooks for Hive, HBase, Sqoop, Storm, and other Hadoop ecosystem tools for automatic metadata harvesting.
  name: Hook-Based Metadata Collection
- description: Extensible type system for defining custom entity types, classification types, and relationship types.
  name: Type System
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Hive hook for automatic metadata harvesting of Hive databases, tables, and query lineage.
  name: Apache Hive
- description: Integration with Ranger for policy-based data access control driven by Atlas classification tags.
  name: Apache Ranger
- description: Kafka hook for tracking Kafka topics and message schema metadata.
  name: Apache Kafka
- description: HBase hook for capturing table and namespace metadata.
  name: Apache HBase
- description: Spark integration for capturing dataset and job-level lineage from Spark applications.
  name: Apache Spark
- description: Sqoop hook for importing relational database metadata and lineage into Atlas.
  name: Apache Sqoop
- description: Native integration with Cloudera Data Platform (CDP) as the metadata management backbone.
  name: Cloudera Data Platform
jsonld:
- class_count: 11
  name: Apache Atlas Context
  property_count: 34
  slug: apache-atlas-context
layout: provider
modified: '2026-04-19'
name: Apache Atlas
rules:
- name: Apache Atlas API Rules
  rule_count: 12
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 5
  slug: apache-atlas-spectral-rules
skills: []
slug: apache-atlas
solutions: []
tags:
- Apache
- Big Data
- Compliance
- Data Governance
- Data Lineage
- Hadoop
- Metadata
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-atlas/refs/heads/main/apis.yml
use_cases:
- description: Track data assets, apply classifications, and enforce policies for GDPR, HIPAA, and CCPA compliance.
  name: Data Governance and Compliance
- description: Trace data from source to consumption to understand pipeline impact and debug data quality issues.
  name: Data Lineage Analysis
- description: Enable data consumers to find relevant datasets using classification-based and attribute-based search.
  name: Metadata-Driven Data Discovery
- description: Serve as the metadata backbone for enterprise data catalogs and data mesh architectures.
  name: Data Catalog Integration
- description: Classify PII and sensitive data assets and integrate with Ranger for attribute-based access control.
  name: Sensitive Data Identification
- description: Maintain standard business definitions and link them to technical metadata for consistent data interpretation.
  name: Business Glossary Management
---
