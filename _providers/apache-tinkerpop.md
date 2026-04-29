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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-tinkerpop\nname: Apache TinkerPop\ndescription: >-\n  Apache TinkerPop is a graph computing framework for both graph databases (OLTP) and graph\n  analytic systems (OLAP). It provides the Gremlin graph traversal language which works with\n  any TinkerPop-enabled graph system. TinkerPop abstracts the underlying graph database,\n  allowing applications to work with Neo4j, Amazon Neptune, Azure Cosmos DB, JanusGraph,\n  Amazon DynamoDB, and other graph databases using a single consistent API. It is maintained\n  by the Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Graph Computing\n  - Graph Database\n  - Gremlin\n  - OLAP\n  - OLTP\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-tinkerpop/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ apache-tinkerpop:apache-tinkerpop-gremlin-server-api\n    name: Apache TinkerPop Gremlin Server API\n    description: >-\n      The Gremlin Server provides WebSocket and HTTP endpoints for submitting Gremlin traversals\n      to a remote graph database. The HTTP API accepts POST requests with Gremlin traversal\n      strings or bytecode at /gremlin endpoint. The WebSocket API supports binary (GraphBinary)\n      and text (GraphSON) serialization formats. Gremlin Server also exposes REST-like endpoints\n      for graph management operations.\n    humanURL: https://tinkerpop.apache.org/docs/current/reference/#gremlin-server\n    tags:\n      - WebSocket\n      - HTTP\n      - Gremlin\n      - Graph Database\n    properties:\n      - type: Documentation\n        url: https://tinkerpop.apache.org/docs/current/reference/#gremlin-server\n  - aid: apache-tinkerpop:apache-tinkerpop-gremlin-api\n    name: Apache TinkerPop Gremlin Traversal API\n    description: >-\n      The Gremlin graph traversal\
  \ language and API provide a functional, data-flow-based language\n      for expressing complex graph queries and mutations. Gremlin steps include vertex/edge traversals\n      (V, E, out, in, both, outE, inE), filtering (has, where, filter), transformation (map, flatMap,\n      select, project), aggregation (groupCount, group, count, sum), and mutation steps (addV, addE,\n      property, drop). Available as Java, Python, JavaScript, Go, .NET, and other language SDKs.\n    humanURL: https://tinkerpop.apache.org/docs/current/reference/\n    tags:\n      - Gremlin\n      - Graph Traversal\n      - Graph Database\n      - Java\n      - Python\n    properties:\n      - type: Documentation\n        url: https://tinkerpop.apache.org/docs/current/reference/\n      - type: SDK\n        url: https://pypi.org/project/gremlinpython/\n        title: Python Gremlin SDK\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.tinkerpop\n        title: Java Maven SDK\n      - type:\
  \ SDK\n        url: https://www.npmjs.com/package/gremlin\n        title: JavaScript/Node.js SDK\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/tinkerpop\n  - type: Documentation\n    url: https://tinkerpop.apache.org/docs/current/reference/\n  - type: Portal\n    url: https://tinkerpop.apache.org/\n  - type: GettingStarted\n    url: https://tinkerpop.apache.org/docs/current/tutorials/getting-started/\n  - type: ReleaseNotes\n    url: https://github.com/apache/tinkerpop/releases\n  - type: Support\n    url: https://groups.google.com/g/gremlin-users\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Graph Database Abstraction\n        description: Single API working across Neo4j, JanusGraph, Amazon Neptune, Azure Cosmos DB, and 20+ graph systems.\n      - name: Gremlin Language\n        description: Expressive functional graph traversal language for both queries and mutations.\n      - name: OLAP Graph\
  \ Processing\n        description: Bulk/analytical graph processing via SparkGraphComputer for large-scale graph algorithms.\n      - name: GraphBinary Serialization\n        description: Compact binary serialization format for efficient Gremlin traversal encoding.\n      - name: GraphSON Format\n        description: JSON-based graph serialization format for human-readable graph data exchange.\n      - name: Gremlin Server\n        description: Standalone server hosting Gremlin traversal execution over WebSocket or HTTP.\n      - name: Multi-Language SDKs\n        description: Official Gremlin SDKs for Java, Python, JavaScript, Go, and .NET.\n  - type: UseCases\n    data:\n      - name: Knowledge Graphs\n        description: Build and query knowledge graphs for entity relationship modeling.\n      - name: Social Network Analysis\n        description: Traverse and analyze social graph relationships and influence patterns.\n      - name: Fraud Detection\n        description: Detect fraud\
  \ rings and suspicious patterns via graph relationship traversal.\n      - name: Recommendation Engines\n        description: Graph-based collaborative filtering and content recommendation.\n      - name: Identity and Access Management\n        description: Model and query complex permission hierarchies and role relationships.\n  - type: Integrations\n    data:\n      - name: Amazon Neptune\n        description: AWS managed graph database with full TinkerPop and Gremlin compatibility.\n      - name: Azure Cosmos DB\n        description: Azure Cosmos DB Gremlin API for TinkerPop-compatible graph storage.\n      - name: JanusGraph\n        description: Distributed graph database with TinkerPop/Gremlin interface and Cassandra/HBase backend.\n      - name: Neo4j\n        description: Neo4j TinkerPop plugin for Gremlin traversal on Neo4j graph data.\n      - name: Apache Spark\n        description: SparkGraphComputer for OLAP graph analytics on Spark clusters.\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-tinkerpop/refs/heads/main/apis.yml
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
