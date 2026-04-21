---
api_count: 1
apis:
- description: Lucene provides a comprehensive Java API for full-text indexing, searching, faceting, hit highlighting, spatial search, vector nearest-neighbor search, and text analysis with support for custom analyz
  name: Apache Lucene
  slug: apache-lucene
common:
- title: ''
  type: Portal
  url: https://lucene.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/lucene
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/lucenenet
- title: ''
  type: IssueTracker
  url: https://github.com/apache/lucene/issues
- title: ''
  type: Blog
  url: https://lucene.apache.org/news.html
- title: ''
  type: MailingList
  url: https://lists.apache.org/list.html?dev@lucene.apache.org
- title: ''
  type: Slack
  url: https://the-asf.slack.com/messages/CE70MDPMF
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache Lucene is a high-performance, full-featured text search engine library written entirely in Java. It provides indexing and search technology, as well as spellchecking, hit highlighting, faceting, vector similarity search, and advanced analysis and tokenization capabilities. Lucene is the foundation for many popular search applications including Apache Solr.
features:
- description: High-performance full-text indexing with over 800GB/hour throughput on modern hardware with minimal RAM requirements.
  name: Full-Text Indexing
- description: Native support for approximate and exact k-nearest-neighbor vector similarity search alongside traditional keyword search.
  name: Vector Nearest-Neighbor Search
- description: Supports phrase queries, wildcard, proximity, range, fuzzy, and fielded queries with pluggable query parsers.
  name: Advanced Query Types
- description: Built-in faceted search and result grouping capabilities for navigation and aggregation.
  name: Faceting and Grouping
- description: Highlights search keywords in result snippets using the Highlighter and UnifiedHighlighter modules.
  name: Hit Highlighting
- description: Auto-suggest and spell-checking support via the Suggest module with multiple suggester implementations.
  name: Spell Checking and Suggestions
- description: Extensive analyzer ecosystem supporting dozens of languages including ICU, Kuromoji (Japanese), Nori (Korean), OpenNLP, and more.
  name: Pluggable Analyzers
- description: Supports Vector Space Model, Okapi BM25, and custom pluggable similarity implementations.
  name: Pluggable Ranking Models
- description: Geospatial search capabilities via the Spatial and Spatial3D modules.
  name: Spatial Search
- description: Index replication support via the Replicator module for leader-follower architectures.
  name: Replication Support
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Apache Solr is built on top of Lucene and adds distributed search, REST API, and enterprise features.
  name: Apache Solr
- description: Elasticsearch and OpenSearch use Lucene as their underlying search engine.
  name: Elasticsearch/OpenSearch
- description: Lucene integrates with Hadoop for large-scale distributed indexing pipelines.
  name: Apache Hadoop
- description: Apache Tika extracts text from thousands of file formats for indexing into Lucene.
  name: Apache Tika
- description: OpenNLP provides NLP analysis capabilities integrated through Lucene analyzers.
  name: Apache OpenNLP
- description: Apache Nutch is a web crawler that stores and indexes content via Lucene.
  name: Apache Nutch
- description: Official .NET port of Apache Lucene, maintained in the apache/lucenenet repository.
  name: Lucene.NET
layout: provider
modified: '2026-04-19'
name: Apache Lucene
skills: []
slug: apache-lucene
solutions: []
tags:
- Full-Text Search
- Indexing
- Java
- Search
- Text Analysis
- Vector Search
url: https://raw.githubusercontent.com/api-evangelist/apache-lucene/refs/heads/main/apis.yml
use_cases:
- description: Power full-text search across enterprise documents, emails, databases, and file systems.
  name: Enterprise Search
- description: Implement fast, relevant product search with facets, autocomplete, and spell correction.
  name: E-Commerce Product Search
- description: Index and search structured and unstructured log data for observability and security analytics.
  name: Log and Event Search
- description: Combine keyword search with vector embeddings for hybrid semantic and lexical retrieval.
  name: Semantic Search
- description: Build searchable knowledge bases and documentation portals with rich query capabilities.
  name: Knowledge Base Search
---
