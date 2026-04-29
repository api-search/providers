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
source_yaml: "aid: apache-solr\nname: Apache Solr\ndescription: >-\n  Apache Solr is an open-source enterprise search platform built on Apache Lucene. It provides\n  distributed indexing, replication, load-balanced querying, automated failover and recovery,\n  and centralized configuration through SolrCloud. Solr exposes comprehensive REST/HTTP APIs\n  for document indexing, full-text search with faceting and highlighting, schema management,\n  collections management, and cluster operations. It is an Apache Software Foundation project\n  used by major organizations for enterprise-scale search solutions.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Enterprise Search\n  - Full-Text Search\n  - Lucene\n  - Search\n  - SolrCloud\n  - Open Source\n  - Java\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-solr/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-solr:apache-solr-search-api\n    name: Apache Solr Search API\n    description: >-\n      The Solr Search API provides HTTP endpoints for full-text document search, including\n      query parsers (Standard, DisMax, Extended DisMax), JSON Query DSL, faceting and JSON\n      Facet API, spell checking, suggestions, MoreLikeThis, spatial search, dense vector\n      search, result grouping, highlighting, and result clustering. Queries are submitted to\n      the /select handler and support complex relevancy scoring with Learning to Rank.\n    humanURL: https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html\n    tags:\n      - Search\n      - Faceting\n      - Full-Text Search\n      - REST\n      - Indexing\n    properties:\n      - type: Documentation\n        url: https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html\n      - type: Documentation\n        url: https://solr.apache.org/guide/solr/latest/query-guide/json-request-api.html\n\
  \n  - aid: apache-solr:apache-solr-indexing-api\n    name: Apache Solr Indexing API\n    description: >-\n      The Solr Indexing API provides HTTP endpoints for adding, updating, and deleting documents\n      from the search index. It supports JSON, XML, CSV, and binary Solr formats via the /update\n      handler, atomic updates, optimistic concurrency, document routing in SolrCloud, and the\n      DataImportHandler for bulk loading from databases and file systems.\n    humanURL: https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html\n    tags:\n      - Indexing\n      - Documents\n      - REST\n      - Updates\n    properties:\n      - type: Documentation\n        url: https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html\n\n  - aid: apache-solr:apache-solr-schema-api\n    name: Apache Solr Schema API\n    description: >-\n      The Solr Schema API provides REST endpoints for managing the schema of a Solr collection,\n\
  \      including field types, fields, dynamic fields, and copy fields. The Managed Schema approach\n      allows runtime schema modifications without server restart via the /schema endpoint.\n    humanURL: https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html\n    tags:\n      - Schema\n      - REST\n      - Management\n    properties:\n      - type: Documentation\n        url: https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html\n\n  - aid: apache-solr:apache-solr-collections-api\n    name: Apache Solr Collections API\n    description: >-\n      The Solr Collections API provides REST endpoints for managing SolrCloud collections,\n      shards, replicas, and aliases. It supports collection creation, deletion, modification,\n      shard splitting, replica management, collection backup/restore, alias management, and\n      cross-datacenter replication (CDCR) configuration.\n    humanURL: https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html\n\
  \    tags:\n      - Collections\n      - SolrCloud\n      - Cluster\n      - Management\n    properties:\n      - type: Documentation\n        url: https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html\n\n  - aid: apache-solr:apache-solr-config-api\n    name: Apache Solr Config API\n    description: >-\n      The Solr Config API and Request Parameters API provide REST endpoints for managing\n      Solr's solrconfig.xml settings at runtime without server restart, including request\n      handler configuration, search component configuration, query settings, and configset\n      management. The v2 API provides a modern JSON-based interface for all configuration operations.\n    humanURL: https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html\n    tags:\n      - Configuration\n      - REST\n      - Management\n    properties:\n      - type: Documentation\n        url: https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html\n\
  \ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/solr\n  - type: Documentation\n    url: https://solr.apache.org/guide/solr/latest/\n  - type: Portal\n    url: https://solr.apache.org/\n  - type: GettingStarted\n    url: https://solr.apache.org/guide/solr/latest/getting-started/introduction.html\n  - type: ReleaseNotes\n    url: https://github.com/apache/solr/releases\n  - type: Support\n    url: https://solr.apache.org/community.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: SDK\n    url: https://solr.apache.org/guide/solr/latest/deployment-guide/solrj.html\n    title: SolrJ Java Client\n  - type: SDK\n    url: https://github.com/apache/solr-operator\n    title: Solr Kubernetes Operator\n  - type: Features\n    data:\n      - name: Full-Text Search\n        description: Comprehensive full-text search with tokenization, stemming, synonyms, and relevance scoring.\n      - name: SolrCloud\n        description: Distributed search\
  \ and indexing with automatic sharding, replication, and ZooKeeper coordination.\n      - name: Faceted Search\n        description: Dynamic faceting including field facets, range facets, pivot facets, and JSON Facet API.\n      - name: Streaming Expressions\n        description: SQL-like streaming expressions for distributed corpus analytics and aggregations.\n      - name: Dense Vector Search\n        description: Approximate nearest neighbor (ANN) search for AI/ML vector embeddings using HNSW algorithm.\n      - name: Learning to Rank\n        description: Machine learning-based relevancy tuning with custom feature extraction and model training.\n      - name: Real-Time Get\n        description: Near-real-time document retrieval before documents are committed to the index.\n      - name: Spatial Search\n        description: Geographic and spatial search with distance filtering and bounding box queries.\n      - name: SQL Interface\n        description: SQL query language with JDBC support\
  \ for analytics tools like Zeppelin and R.\n  - type: UseCases\n    data:\n      - name: Enterprise Search\n        description: Unified enterprise search across documents, databases, web content, and file systems.\n      - name: E-Commerce Product Search\n        description: Product catalog search with faceting, filtering, and recommendation engines.\n      - name: Log Analytics\n        description: Log ingestion and search for operational intelligence and security analysis.\n      - name: AI/ML Vector Search\n        description: Semantic and similarity search using dense vector embeddings from AI models.\n      - name: Content Management Search\n        description: Full-text search backend for CMS platforms and digital asset management systems.\n  - type: Integrations\n    data:\n      - name: Apache ZooKeeper\n        description: Distributed coordination service for SolrCloud cluster management and configuration.\n      - name: Apache Kafka\n        description: Stream ingestion\
  \ via Kafka connector for real-time document indexing.\n      - name: Kubernetes\n        description: Solr Kubernetes Operator for cloud-native deployment and management.\n      - name: Grafana\n        description: Metrics integration via Prometheus exporter for Solr cluster monitoring.\n      - name: Apache Tika\n        description: Document parsing for indexing rich content like PDFs, Word documents, and HTML.\n      - name: Apache NiFi\n        description: Data flow integration for automated document ingestion pipelines.\n      - name: OpenNLP\n        description: Natural language processing integration for text analysis and named entity recognition.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-solr/refs/heads/main/apis.yml
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
