---
api_count: 2
apis:
- description: Monitoring API for Apache Giraph graph processing jobs via the YARN ResourceManager REST API, providing job status, progress tracking, and cluster capacity metrics.
  name: Apache Giraph Job Monitoring API
  slug: apache-giraph-job-api
- description: Java API based on the Bulk Synchronous Parallel (BSP) model for implementing graph algorithms, with Vertex, Edge, and Master compute APIs for distributed graph processing on Hadoop.
  name: Apache Giraph Java API
  slug: apache-giraph-java-api
capabilities:
- description: Capability for monitoring Apache Giraph graph processing jobs on Hadoop YARN — tracking job status, completion progress, and cluster capacity. Designed for data engineers running large-scale graph alg
  name: Apache Giraph Graph Processing
  slug: giraph-graph-processing
common:
- title: ''
  type: Documentation
  url: https://giraph.apache.org/
- title: ''
  type: GettingStarted
  url: https://giraph.apache.org/quick_start.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/giraph
- title: ''
  type: SpectralRules
  url: rules/apache-giraph-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-giraph-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/giraph-graph-processing.yaml
created: '2026-03-16'
description: Apache Giraph is an iterative graph processing system built for high scalability on Apache Hadoop. It is modeled after Google's Pregel and provides a simple yet flexible Java API for graph algorithms at massive scale using the Bulk Synchronous Parallel (BSP) model. Note - Apache Giraph has been retired as of 2024.
features:
- description: Google Pregel-inspired BSP computation model where vertices communicate through supersteps.
  name: Bulk Synchronous Parallel (BSP) Model
- description: Write graph algorithms by defining per-vertex compute functions that exchange messages with neighbors.
  name: Vertex-Centric Programming
- description: Global coordination API for aggregating results and controlling algorithm termination across supersteps.
  name: Master Compute API
- description: Sharded aggregators for collecting global statistics across all vertices during computation.
  name: Aggregators
- description: Flexible input formats for loading graphs from HDFS, Hive, Gora, and Rexster sources.
  name: Edge-Oriented Input
- description: Spill graph data to disk for processing graphs larger than available memory.
  name: Out-of-Core Computation
- description: Runs as a MapReduce job on Apache Hadoop YARN for resource management and fault tolerance.
  name: Hadoop Integration
- description: Checkpoint-based recovery for fault tolerance across superstep boundaries.
  name: Fault Tolerance
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Runs on Hadoop YARN as a MapReduce application for cluster resource management.
  name: Apache Hadoop
- description: Hive I/O module for loading graph data from Hive tables.
  name: Apache Hive
- description: Gora I/O module for loading graph data from various NoSQL data stores.
  name: Apache Gora
- description: Rexster graph server I/O module for loading data from TinkerPop graph databases.
  name: Rexster
- description: HBase integration for storing and loading vertex and edge data.
  name: Apache HBase
jsonld:
- class_count: 5
  name: Apache Giraph Job Context
  property_count: 14
  slug: apache-giraph-job-context
layout: provider
modified: '2026-04-19'
name: Apache Giraph
rules:
- name: Apache Giraph API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 3
  slug: apache-giraph-spectral-rules
skills: []
slug: apache-giraph
solutions: []
tags:
- Apache
- Big Data
- BSP
- Graph Processing
- Hadoop
- Open Source
- Retired
url: https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/apis.yml
use_cases:
- description: Analyze social network connections, communities, and influence at billions-of-vertices scale (as used at Facebook).
  name: Social Graph Analysis
- description: Compute web page or entity rankings using iterative link analysis algorithms.
  name: PageRank Computation
- description: Find shortest paths between vertices for network routing and recommendation problems.
  name: Shortest Path Computation
- description: Identify clusters and connected components in large graphs for community detection.
  name: Connected Components
- description: Generate graph-structural features for machine learning models at scale.
  name: Graph Machine Learning Features
---
