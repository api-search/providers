---
api_count: 1
apis:
- description: REST API for managing Apache Nutch crawl jobs, configurations, seed URL lists, database queries (CrawlDB and FetchDB), and data readers. Supports full crawl lifecycle management including inject, gene
  name: Apache Nutch REST API
  slug: apache-nutch-rest-api
capabilities:
- description: Workflow capability for managing end-to-end web crawl pipelines with Apache Nutch. Covers job lifecycle management, configuration control, seed list management, and CrawlDB querying for web crawl engi
  name: Apache Nutch Crawl Management
  slug: apache-nutch-crawl-management
common:
- title: Apache Nutch GitHub Repository
  type: GitHubRepository
  url: https://github.com/apache/nutch
- title: Apache Software Foundation GitHub
  type: GitHubOrganization
  url: https://github.com/apache
- title: Apache Nutch Documentation
  type: Documentation
  url: https://nutch.apache.org/documentation/
- title: Nutch Tutorial
  type: GettingStarted
  url: https://cwiki.apache.org/confluence/display/NUTCH/NutchTutorial
- title: Apache Nutch Tutorials
  type: Tutorials
  url: https://nutch.apache.org/documentation/tutorials/
- title: Apache Nutch FAQs
  type: FAQ
  url: https://nutch.apache.org/documentation/faqs/
- title: Nutch Release Notes
  type: ReleaseNotes
  url: https://github.com/apache/nutch/blob/master/CHANGES.md
- title: Apache License 2.0
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: Mailing Lists
  type: Support
  url: https://nutch.apache.org/community/mailing-lists/
- title: Nutch on Stack Overflow
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/nutch
- title: Apache Nutch Spectral Rules
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/rules/apache-nutch-spectral-rules.yml
- title: Apache Nutch Crawl Management
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/capabilities/apache-nutch-crawl-management.yaml
- title: Apache Nutch Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/vocabulary/apache-nutch-vocabulary.yaml
- title: Apache Nutch JSON-LD Context
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-ld/apache-nutch-context.jsonld
created: '2026-03-16'
description: Apache Nutch is a highly extensible and scalable open-source web crawler software project built on Apache Hadoop data structures for batch processing. It provides a pluggable architecture supporting custom parse filters, scoring filters, index writers, and protocol implementations. Nutch integrates with Apache Solr and Elasticsearch for full-text search and exposes a REST API for managing crawl jobs, configurations, seed lists, and database queries. Governed by the Apache Software Foundation under the Apache License 2.0.
features:
- description: Leverages Apache Hadoop data structures for distributed, large-scale web crawling batch processing.
  name: Scalable Batch Crawling
- description: Extensible plugin system supporting custom parse filters, scoring filters, index writers, protocol plugins, and URL filters.
  name: Pluggable Architecture
- description: Full REST API for managing crawl jobs, configurations, seed lists, CrawlDB/FetchDB queries, and sequence file readers.
  name: REST API for Crawl Management
- description: Built-in index writers for Apache Solr and Elasticsearch to enable full-text search over crawled content.
  name: Full-Text Search Integration
- description: Uses Apache Tika for parsing a wide variety of document formats during the crawl pipeline.
  name: Apache Tika Parsing
- description: Built-in deduplication support to identify and remove duplicate content from the crawl database and search index.
  name: Duplicate Detection
- description: Regex-based and custom URL filter plugins to control crawl scope and exclusions.
  name: Configurable URL Filtering
- description: Supports multi-round incremental crawling workflows to keep the crawl database fresh.
  name: Incremental Crawling
- description: Service operations for exporting crawl data in CommonCrawl-compatible formats.
  name: CommonCrawl Export
- description: Configurable HTTP authentication schemes for crawling password-protected sites.
  name: HTTP Authentication Support
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native index writer plugin for indexing crawled content into Apache Solr for full-text search.
  name: Apache Solr
- description: Index writer plugin for sending crawled content to Elasticsearch clusters.
  name: Elasticsearch
- description: Core dependency providing distributed storage and processing via HDFS and MapReduce.
  name: Apache Hadoop
- description: Used for content detection and extraction from a wide range of document formats during parsing.
  name: Apache Tika
- description: Support for SolrCloud distributed search clusters for scalable indexing.
  name: SolrCloud
jsonld:
- class_count: 16
  name: Apache Nutch Context
  property_count: 35
  slug: apache-nutch-context
layout: provider
modified: '2026-04-19'
name: Apache Nutch
rules:
- name: Apache Nutch API Rules
  rule_count: 33
  severity_counts:
    error: 12
    hint: 0
    info: 2
    warn: 19
  slug: apache-nutch-spectral-rules
skills: []
slug: apache-nutch
solutions: []
tags:
- Web Crawler
- Indexing
- Search
- Apache
- Java
- Hadoop
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/apis.yml
use_cases:
- description: Build enterprise search engines over internal or external web content using Nutch as the crawler and Solr/Elasticsearch as the search backend.
  name: Enterprise Search
- description: Academic and research teams use Nutch for large-scale systematic web data collection and indexing.
  name: Research Data Collection
- description: Crawl and index intranet sites, wikis, and document repositories for internal enterprise search.
  name: Intranet Document Search
- description: Create structured web archives compatible with CommonCrawl format for long-term data preservation.
  name: Web Archive Creation
- description: Monitor web content changes, track competitor sites, and analyze web structure at scale.
  name: SEO and Content Monitoring
- description: Build custom extraction pipelines using Nutch plugin architecture for targeted data acquisition tasks.
  name: Custom Data Extraction Pipelines
---
