---
api_count: 5
apis:
- description: The Solr Search API provides HTTP endpoints for full-text document search, including query parsers (Standard, DisMax, Extended DisMax), JSON Query DSL, faceting and JSON Facet API, spell checking, sug
  name: Apache Solr Search API
  slug: apache-solr-search-api
- description: The Solr Indexing API provides HTTP endpoints for adding, updating, and deleting documents from the search index. It supports JSON, XML, CSV, and binary Solr formats via the /update handler, atomic up
  name: Apache Solr Indexing API
  slug: apache-solr-indexing-api
- description: The Solr Schema API provides REST endpoints for managing the schema of a Solr collection, including field types, fields, dynamic fields, and copy fields. The Managed Schema approach allows runtime sch
  name: Apache Solr Schema API
  slug: apache-solr-schema-api
- description: The Solr Collections API provides REST endpoints for managing SolrCloud collections, shards, replicas, and aliases. It supports collection creation, deletion, modification, shard splitting, replica ma
  name: Apache Solr Collections API
  slug: apache-solr-collections-api
- description: The Solr Config API and Request Parameters API provide REST endpoints for managing Solr's solrconfig.xml settings at runtime without server restart, including request handler configuration, search com
  name: Apache Solr Config API
  slug: apache-solr-config-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/solr
- title: ''
  type: Documentation
  url: https://solr.apache.org/guide/solr/latest/
- title: ''
  type: Portal
  url: https://solr.apache.org/
- title: ''
  type: GettingStarted
  url: https://solr.apache.org/guide/solr/latest/getting-started/introduction.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/solr/releases
- title: ''
  type: Support
  url: https://solr.apache.org/community.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: SolrJ Java Client
  type: SDK
  url: https://solr.apache.org/guide/solr/latest/deployment-guide/solrj.html
- title: Solr Kubernetes Operator
  type: SDK
  url: https://github.com/apache/solr-operator
created: '2026-03-16'
description: Apache Solr is an open-source enterprise search platform built on Apache Lucene. It provides distributed indexing, replication, load-balanced querying, automated failover and recovery, and centralized configuration through SolrCloud. Solr exposes comprehensive REST/HTTP APIs for document indexing, full-text search with faceting and highlighting, schema management, collections management, and cluster operations. It is an Apache Software Foundation project used by major organizations for enterprise-scale search solutions.
features:
- description: Comprehensive full-text search with tokenization, stemming, synonyms, and relevance scoring.
  name: Full-Text Search
- description: Distributed search and indexing with automatic sharding, replication, and ZooKeeper coordination.
  name: SolrCloud
- description: Dynamic faceting including field facets, range facets, pivot facets, and JSON Facet API.
  name: Faceted Search
- description: SQL-like streaming expressions for distributed corpus analytics and aggregations.
  name: Streaming Expressions
- description: Approximate nearest neighbor (ANN) search for AI/ML vector embeddings using HNSW algorithm.
  name: Dense Vector Search
- description: Machine learning-based relevancy tuning with custom feature extraction and model training.
  name: Learning to Rank
- description: Near-real-time document retrieval before documents are committed to the index.
  name: Real-Time Get
- description: Geographic and spatial search with distance filtering and bounding box queries.
  name: Spatial Search
- description: SQL query language with JDBC support for analytics tools like Zeppelin and R.
  name: SQL Interface
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Distributed coordination service for SolrCloud cluster management and configuration.
  name: Apache ZooKeeper
- description: Stream ingestion via Kafka connector for real-time document indexing.
  name: Apache Kafka
- description: Solr Kubernetes Operator for cloud-native deployment and management.
  name: Kubernetes
- description: Metrics integration via Prometheus exporter for Solr cluster monitoring.
  name: Grafana
- description: Document parsing for indexing rich content like PDFs, Word documents, and HTML.
  name: Apache Tika
- description: Data flow integration for automated document ingestion pipelines.
  name: Apache NiFi
- description: Natural language processing integration for text analysis and named entity recognition.
  name: OpenNLP
layout: provider
modified: '2026-04-19'
name: Apache Solr
skills: []
slug: apache-solr
solutions: []
tags:
- Enterprise Search
- Full-Text Search
- Lucene
- Search
- SolrCloud
- Open Source
- Java
url: https://raw.githubusercontent.com/api-evangelist/apache-solr/refs/heads/main/apis.yml
use_cases:
- description: Unified enterprise search across documents, databases, web content, and file systems.
  name: Enterprise Search
- description: Product catalog search with faceting, filtering, and recommendation engines.
  name: E-Commerce Product Search
- description: Log ingestion and search for operational intelligence and security analysis.
  name: Log Analytics
- description: Semantic and similarity search using dense vector embeddings from AI models.
  name: AI/ML Vector Search
- description: Full-text search backend for CMS platforms and digital asset management systems.
  name: Content Management Search
---
