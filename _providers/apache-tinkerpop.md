---
api_count: 2
apis:
- description: 'The Gremlin Server provides WebSocket and HTTP endpoints for submitting Gremlin traversals to a remote graph database. The HTTP API accepts POST requests with Gremlin traversal strings or bytecode at '
  name: Apache TinkerPop Gremlin Server API
  slug: apache-tinkerpop-gremlin-server-api
- description: The Gremlin graph traversal language and API provide a functional, data-flow-based language for expressing complex graph queries and mutations. Gremlin steps include vertex/edge traversals (V, E, out,
  name: Apache TinkerPop Gremlin Traversal API
  slug: apache-tinkerpop-gremlin-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/tinkerpop
- title: ''
  type: Documentation
  url: https://tinkerpop.apache.org/docs/current/reference/
- title: ''
  type: Portal
  url: https://tinkerpop.apache.org/
- title: ''
  type: GettingStarted
  url: https://tinkerpop.apache.org/docs/current/tutorials/getting-started/
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/tinkerpop/releases
- title: ''
  type: Support
  url: https://groups.google.com/g/gremlin-users
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache TinkerPop is a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP). It provides the Gremlin graph traversal language which works with any TinkerPop-enabled graph system. TinkerPop abstracts the underlying graph database, allowing applications to work with Neo4j, Amazon Neptune, Azure Cosmos DB, JanusGraph, Amazon DynamoDB, and other graph databases using a single consistent API. It is maintained by the Apache Software Foundation.
features:
- description: Single API working across Neo4j, JanusGraph, Amazon Neptune, Azure Cosmos DB, and 20+ graph systems.
  name: Graph Database Abstraction
- description: Expressive functional graph traversal language for both queries and mutations.
  name: Gremlin Language
- description: Bulk/analytical graph processing via SparkGraphComputer for large-scale graph algorithms.
  name: OLAP Graph Processing
- description: Compact binary serialization format for efficient Gremlin traversal encoding.
  name: GraphBinary Serialization
- description: JSON-based graph serialization format for human-readable graph data exchange.
  name: GraphSON Format
- description: Standalone server hosting Gremlin traversal execution over WebSocket or HTTP.
  name: Gremlin Server
- description: Official Gremlin SDKs for Java, Python, JavaScript, Go, and .NET.
  name: Multi-Language SDKs
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AWS managed graph database with full TinkerPop and Gremlin compatibility.
  name: Amazon Neptune
- description: Azure Cosmos DB Gremlin API for TinkerPop-compatible graph storage.
  name: Azure Cosmos DB
- description: Distributed graph database with TinkerPop/Gremlin interface and Cassandra/HBase backend.
  name: JanusGraph
- description: Neo4j TinkerPop plugin for Gremlin traversal on Neo4j graph data.
  name: Neo4j
- description: SparkGraphComputer for OLAP graph analytics on Spark clusters.
  name: Apache Spark
layout: provider
modified: '2026-04-19'
name: Apache TinkerPop
skills: []
slug: apache-tinkerpop
solutions: []
tags:
- Graph Computing
- Graph Database
- Gremlin
- OLAP
- OLTP
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-tinkerpop/refs/heads/main/apis.yml
use_cases:
- description: Build and query knowledge graphs for entity relationship modeling.
  name: Knowledge Graphs
- description: Traverse and analyze social graph relationships and influence patterns.
  name: Social Network Analysis
- description: Detect fraud rings and suspicious patterns via graph relationship traversal.
  name: Fraud Detection
- description: Graph-based collaborative filtering and content recommendation.
  name: Recommendation Engines
- description: Model and query complex permission hierarchies and role relationships.
  name: Identity and Access Management
---
