---
api_count: 1
apis:
- description: Pig provides the Pig Latin scripting language for data analysis, an embedded Pig API for programmatic execution from Java, and a UDF (User Defined Function) API for custom data transformation function
  name: Apache Pig
  slug: apache-pig
capabilities:
- description: Workflow for submitting, monitoring, and managing Pig Latin data analysis jobs on Hadoop clusters.
  name: Apache Pig Data Processing Workflow
  slug: pig-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/pig
- title: ''
  type: Documentation
  url: https://pig.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-pig-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-pig-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/pig-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-pig-context.jsonld
created: '2026-03-16'
description: Apache Pig is a platform for analyzing large data sets that provides a high-level language (Pig Latin) for expressing data analysis programs. It compiles Pig Latin programs into MapReduce/Tez jobs and runs them on Hadoop clusters.
features:
- description: High-level dataflow language for expressing data transformations
  name: Pig Latin Language
- description: Compiles Pig Latin to MapReduce or Apache Tez execution plans
  name: MapReduce/Tez Backend
- description: User-defined functions in Java, Python, JavaScript, and Ruby
  name: UDF Support
- description: Process data through external programs using STREAM operator
  name: Streaming
- description: Flexible schema handling for semi-structured data
  name: Schema Evolution
- description: Automatic logical and physical plan optimization
  name: Optimization
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native MapReduce execution on YARN/HDFS
  name: Apache Hadoop
- description: High-performance Tez execution engine support
  name: Apache Tez
- description: HBase storage handler for reading/writing HBase tables
  name: Apache HBase
- description: HCatalog integration for Hive metastore access
  name: Apache Hive
- description: S3 input/output for cloud-based data processing
  name: Amazon S3
jsonld:
- class_count: 7
  name: Apache Pig Context
  property_count: 19
  slug: apache-pig-context
layout: provider
modified: '2026-04-19'
name: Apache Pig
rules:
- name: Apache Pig API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 0
  slug: apache-pig-spectral-rules
skills: []
slug: apache-pig
solutions: []
tags:
- Big Data
- Data Analysis
- ETL
- Hadoop
- Scripting
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/apis.yml
use_cases:
- description: Build data transformation pipelines from raw logs to structured data
  name: ETL Pipelines
- description: Analyze large datasets with ad-hoc Pig Latin queries
  name: Ad-hoc Data Analysis
- description: Clean and prepare data for machine learning workflows
  name: Data Preparation
- description: Process and aggregate web server and application logs
  name: Log Processing
---
