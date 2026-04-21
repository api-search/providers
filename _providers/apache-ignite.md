---
api_count: 3
apis:
- description: The Ignite 3 REST API provides HTTP endpoints for cluster initialization, cluster management, node management, SQL query execution, configuration management, and deployment unit management.
  name: Apache Ignite REST API
  slug: rest-api
- description: The Ignite Java client API provides native Java access to Ignite clusters for table operations, SQL queries, transactions, and compute task execution.
  name: Apache Ignite Java Client API
  slug: java-api
- description: The Ignite .NET client API provides native C# and .NET access to Ignite clusters for table operations, SQL queries, and distributed computing.
  name: Apache Ignite .NET Client API
  slug: dotnet-api
capabilities:
- description: Workflow capability for database administrators and platform engineers to manage Apache Ignite clusters, execute SQL queries, and configure distributed nodes.
  name: Apache Ignite Cluster Management
  slug: cluster-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/ignite-3
- title: ''
  type: Documentation
  url: https://ignite.apache.org/docs/ignite3/3.1.0/
- title: ''
  type: GettingStarted
  url: https://ignite.apache.org/docs/ignite3/3.1.0/getting-started/quick-start
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://ignite.apache.org/releases/
- title: ''
  type: SpectralRules
  url: rules/apache-ignite-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-ignite-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/cluster-management.yaml
created: '2026-03-16'
description: Apache Ignite is a distributed database for mission-critical high-velocity applications requiring in-memory performance. It provides ACID transactions, SQL queries, key-value storage, compute grid, and backpressured streaming across distributed clusters. Governed by the Apache Software Foundation under the Apache 2.0 license.
features:
- description: Memory-first storage with MVCC for consistent high-velocity performance.
  name: In-Memory Speed
- description: Full ACID transactions across distributed cluster nodes.
  name: ACID Transactions
- description: ANSI SQL-compliant queries across distributed tables with JDBC/ODBC drivers.
  name: SQL Support
- description: Native key-value API for direct cache access without SQL overhead.
  name: Key-Value Storage
- description: Distributed compute tasks co-located with data for low-latency processing.
  name: Compute Grid
- description: Native clients for Java, .NET, C++, and Python.
  name: Multi-Language Clients
- description: Online schema changes without cluster downtime.
  name: Schema Evolution
- description: Event stream ingestion and enrichment with flow control.
  name: Backpressured Streaming
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Spring Boot integration for Ignite cluster connectivity.
  name: Spring Boot
- description: Stream data from Kafka topics into Ignite tables for real-time processing.
  name: Apache Kafka
- description: Standard JDBC driver for connecting SQL tools to Ignite clusters.
  name: JDBC
- description: ODBC driver for BI tool integration with Ignite SQL engine.
  name: ODBC
jsonld:
- class_count: 37
  name: Apache Ignite Rest Api Context
  property_count: 53
  slug: apache-ignite-rest-api-context
layout: provider
modified: '2026-04-19'
name: Apache Ignite
rules:
- name: Apache Ignite API Rules
  rule_count: 23
  severity_counts:
    error: 10
    hint: 0
    info: 4
    warn: 9
  slug: apache-ignite-spectral-rules
skills: []
slug: apache-ignite
solutions: []
tags:
- Caching
- Compute Grid
- Distributed Database
- In-Memory
- Open Source
- SQL
url: https://raw.githubusercontent.com/api-evangelist/apache-ignite/refs/heads/main/apis.yml
use_cases:
- description: Ingest, enrich, and process high-velocity event streams with in-memory speed.
  name: Event Stream Processing
- description: Distributed state store for microservices with ACID guarantees.
  name: Microservices State Management
- description: High-speed session caching for web applications.
  name: Session Management
- description: Low-latency feature serving for machine learning model inference.
  name: AI/ML Feature Store
- description: SQL analytics over continuously updated distributed datasets.
  name: Real-Time Analytics
---
