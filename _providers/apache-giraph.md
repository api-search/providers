---
api_count: 2
api_specs:
- filename: apache-giraph-job-openapi.yml
  format: yaml
  label: Apache Giraph Job Monitoring API
  slug: apache-giraph-job-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/openapi/apache-giraph-job-openapi.yml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-giraph\nname: Apache Giraph\ndescription: >-\n  Apache Giraph is an iterative graph processing system built for high scalability on Apache Hadoop. It is modeled after Google's Pregel and provides a simple yet flexible Java API for graph algorithms at massive scale using the Bulk Synchronous Parallel (BSP) model. Note - Apache Giraph has been retired as of 2024.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Big Data\n  - BSP\n  - Graph Processing\n  - Hadoop\n  - Open Source\n  - Retired\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-giraph:apache-giraph-job-api\n    name: Apache Giraph Job Monitoring API\n    description: >-\n      Monitoring API for Apache Giraph graph processing jobs via the YARN ResourceManager\
  \ REST API, providing job status, progress tracking, and cluster capacity metrics.\n    humanURL: https://giraph.apache.org/quick_start.html\n    baseURL: http://localhost:8088\n    tags:\n      - BSP\n      - Graph\n      - Hadoop\n      - Job Management\n      - YARN\n    properties:\n      - type: Documentation\n        url: https://giraph.apache.org/quick_start.html\n      - type: OpenAPI\n        url: openapi/apache-giraph-job-openapi.yml\n      - type: JSONSchema\n        url: json-schema/giraph-job-application-info-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-giraph-job-context.jsonld\n\n  - aid: apache-giraph:apache-giraph-java-api\n    name: Apache Giraph Java API\n    description: >-\n      Java API based on the Bulk Synchronous Parallel (BSP) model for implementing graph algorithms, with Vertex, Edge, and Master compute APIs for distributed graph processing on Hadoop.\n    humanURL: https://giraph.apache.org/apidocs/\n    tags:\n      - BSP\n      - Graph\n\
  \      - Java\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://giraph.apache.org/apidocs/\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.giraph/giraph-core\n        title: Java SDK (Maven Central)\n\ncommon:\n  - type: Documentation\n    url: https://giraph.apache.org/\n  - type: GettingStarted\n    url: https://giraph.apache.org/quick_start.html\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/giraph\n  - type: SpectralRules\n    url: rules/apache-giraph-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-giraph-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/giraph-graph-processing.yaml\n  - type: Features\n    data:\n      - name: Bulk Synchronous Parallel (BSP) Model\n        description: Google Pregel-inspired BSP computation model where vertices communicate through supersteps.\n      - name: Vertex-Centric\
  \ Programming\n        description: Write graph algorithms by defining per-vertex compute functions that exchange messages with neighbors.\n      - name: Master Compute API\n        description: Global coordination API for aggregating results and controlling algorithm termination across supersteps.\n      - name: Aggregators\n        description: Sharded aggregators for collecting global statistics across all vertices during computation.\n      - name: Edge-Oriented Input\n        description: Flexible input formats for loading graphs from HDFS, Hive, Gora, and Rexster sources.\n      - name: Out-of-Core Computation\n        description: Spill graph data to disk for processing graphs larger than available memory.\n      - name: Hadoop Integration\n        description: Runs as a MapReduce job on Apache Hadoop YARN for resource management and fault tolerance.\n      - name: Fault Tolerance\n        description: Checkpoint-based recovery for fault tolerance across superstep boundaries.\n\
  \  - type: UseCases\n    data:\n      - name: Social Graph Analysis\n        description: Analyze social network connections, communities, and influence at billions-of-vertices scale (as used at Facebook).\n      - name: PageRank Computation\n        description: Compute web page or entity rankings using iterative link analysis algorithms.\n      - name: Shortest Path Computation\n        description: Find shortest paths between vertices for network routing and recommendation problems.\n      - name: Connected Components\n        description: Identify clusters and connected components in large graphs for community detection.\n      - name: Graph Machine Learning Features\n        description: Generate graph-structural features for machine learning models at scale.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop\n        description: Runs on Hadoop YARN as a MapReduce application for cluster resource management.\n      - name: Apache Hive\n        description: Hive I/O module\
  \ for loading graph data from Hive tables.\n      - name: Apache Gora\n        description: Gora I/O module for loading graph data from various NoSQL data stores.\n      - name: Rexster\n        description: Rexster graph server I/O module for loading data from TinkerPop graph databases.\n      - name: Apache HBase\n        description: HBase integration for storing and loading vertex and edge data.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/apis.yml
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
