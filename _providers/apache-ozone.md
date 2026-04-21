---
api_count: 1
apis:
- description: Ozone provides an S3-compatible REST API for object storage operations, a Hadoop-compatible File System API (o3fs, ofs), a Java client API for bucket and key management, and a Recon REST API for clust
  name: Apache Ozone
  slug: apache-ozone
capabilities:
- description: Workflow capability for managing object storage using Apache Ozone's S3-compatible API.
  name: Apache Ozone Object Storage Workflow
  slug: ozone-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/ozone
- title: ''
  type: Documentation
  url: https://ozone.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-ozone-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-ozone-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ozone-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-ozone-context.jsonld
created: '2026-03-16'
description: Apache Ozone is a scalable, redundant, and distributed object store optimized for big data workloads. It provides an S3-compatible interface and a Hadoop-compatible file system interface for seamless integration with existing big data tools.
features:
- description: Fully compatible with Amazon S3 API for object storage operations
  name: S3-Compatible API
- description: Hadoop-compatible file system interface (o3fs, ofs) for existing Hadoop workloads
  name: HDFS-Compatible
- description: Volume/bucket hierarchy with multi-tenant access controls
  name: Multi-Tenant
- description: Configurable replication for data durability
  name: Replication
- description: Erasure coding support for storage efficiency
  name: Erasure Coding
- description: Scale to billions of files with petabytes of data
  name: Scalability
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native HDFS-compatible file system integration
  name: Apache Hadoop
- description: Direct Spark data source for reading and writing ORC/Parquet
  name: Apache Spark
- description: Hive metastore integration for data lake querying
  name: Apache Hive
- description: Compatible with AWS SDK for S3 operations
  name: Amazon S3 SDK
- description: Container-native deployment with CSI driver support
  name: Kubernetes
jsonld:
- class_count: 5
  name: Apache Ozone Context
  property_count: 16
  slug: apache-ozone-context
layout: provider
modified: '2026-04-19'
name: Apache Ozone
rules:
- name: Apache Ozone API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 1
  slug: apache-ozone-spectral-rules
skills: []
slug: apache-ozone
solutions: []
tags:
- Distributed Storage
- Hadoop
- Object Storage
- S3-Compatible
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-ozone/refs/heads/main/apis.yml
use_cases:
- description: Store raw data in a highly scalable and S3-compatible data lake
  name: Data Lake Storage
- description: Replace HDFS with Ozone for petabyte-scale Hadoop clusters
  name: Hadoop Migration
- description: Use S3-compatible API for application file and media storage
  name: Application Object Storage
- description: Cost-effective backup and long-term data archival
  name: Backup and Archive
---
