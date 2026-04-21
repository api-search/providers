---
api_count: 2
apis:
- description: The Tez DAG API provides a Java programming model for defining and submitting directed-acyclic-graph (DAG) computation jobs to Apache YARN. It allows building DAGs composed of Vertex (processing units
  name: Apache Tez DAG API
  slug: apache-tez-dag-api
- description: The Tez UI and YARN Application History Server expose REST endpoints for monitoring Tez application history, DAG details, vertex and task statistics. The Tez Timeline Server integration provides histo
  name: Apache Tez UI REST API
  slug: apache-tez-ui-rest-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/tez
- title: ''
  type: Documentation
  url: https://tez.apache.org/
- title: ''
  type: Portal
  url: https://tez.apache.org/
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/tez/releases
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache Tez is an application framework that allows for complex directed-acyclic-graph (DAG) based processing of data built on Apache Hadoop YARN. It is designed as a successor to MapReduce for executing Hive and Pig queries, providing a flexible API for creating DAG execution pipelines, in-memory data passing between tasks, and session reuse for reduced startup latency. Apache Tez is an Apache Software Foundation top-level project.
features:
- description: Flexible DAG computation model replacing MapReduce for complex multi-stage pipelines.
  name: DAG-Based Execution
- description: Direct in-memory data transfer between connected vertices eliminating HDFS I/O.
  name: In-Memory Data Passing
- description: Tez sessions reuse container allocations across DAG submissions for reduced latency.
  name: Session Reuse
- description: Runtime DAG modification based on actual data statistics during execution.
  name: Dynamic Optimization
- description: Native YARN resource management with fine-grained resource requests per vertex.
  name: YARN Integration
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native YARN resource manager integration for cluster resource allocation.
  name: Apache Hadoop YARN
- description: Default execution engine for Hive queries in HDP and CDH distributions.
  name: Apache Hive
- description: Tez execution backend for Apache Pig script compilation and execution.
  name: Apache Pig
- description: Input/output storage for Tez job data via Hadoop Distributed File System.
  name: Apache HDFS
layout: provider
modified: '2026-04-19'
name: Apache Tez
skills: []
slug: apache-tez
solutions: []
tags:
- Big Data
- DAG
- Execution Engine
- Hadoop
- YARN
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-tez/refs/heads/main/apis.yml
use_cases:
- description: Tez is the default execution engine for Apache Hive queries replacing MapReduce.
  name: Apache Hive Query Execution
- description: Execute Apache Pig Latin scripts as optimized Tez DAGs.
  name: Apache Pig Script Execution
- description: Multi-stage data transformation pipelines with in-memory data passing.
  name: Complex ETL Pipelines
---
