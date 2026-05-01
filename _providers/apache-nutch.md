---
api_count: 1
api_specs:
- filename: apache-nutch-openapi.yaml
  format: yaml
  label: Apache Nutch REST API
  slug: apache-nutch-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/openapi/apache-nutch-openapi.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-nutch\nname: Apache Nutch\ndescription: >-\n  Apache Nutch is a highly extensible and scalable open-source web crawler software project\n  built on Apache Hadoop data structures for batch processing. It provides a pluggable\n  architecture supporting custom parse filters, scoring filters, index writers, and protocol\n  implementations. Nutch integrates with Apache Solr and Elasticsearch for full-text search\n  and exposes a REST API for managing crawl jobs, configurations, seed lists, and database\n  queries. Governed by the Apache Software Foundation under the Apache License 2.0.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Web Crawler\n  - Indexing\n  - Search\n  - Apache\n  - Java\n  - Hadoop\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: apache-nutch:apache-nutch-rest-api\n    name: Apache Nutch REST API\n    description: >-\n      REST API for managing Apache Nutch crawl jobs, configurations, seed URL lists,\n      database queries (CrawlDB and FetchDB), and data readers. Supports full crawl\n      lifecycle management including inject, generate, fetch, parse, updatedb, and index\n      operations. Secured via HTTP Basic Authentication.\n    humanURL: https://cwiki.apache.org/confluence/display/NUTCH/Nutch+1.X+REST+API\n    baseURL: http://localhost:8081\n    tags:\n      - REST\n      - Crawl Management\n      - Job Management\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://cwiki.apache.org/confluence/display/NUTCH/Nutch+1.X+REST+API\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/openapi/apache-nutch-openapi.yaml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-schema/apache-nutch-nutch-config-schema.json\n\
  \        title: Nutch Config Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-schema/apache-nutch-job-config-schema.json\n        title: Job Config Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-schema/apache-nutch-job-info-schema.json\n        title: Job Info Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-schema/apache-nutch-nutch-server-info-schema.json\n        title: Server Info Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-schema/apache-nutch-seed-list-schema.json\n        title: Seed List Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-schema/apache-nutch-db-query-schema.json\n\
  \        title: DB Query Schema\n\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/nutch\n    title: Apache Nutch GitHub Repository\n  - type: GitHubOrganization\n    url: https://github.com/apache\n    title: Apache Software Foundation GitHub\n  - type: Documentation\n    url: https://nutch.apache.org/documentation/\n    title: Apache Nutch Documentation\n  - type: GettingStarted\n    url: https://cwiki.apache.org/confluence/display/NUTCH/NutchTutorial\n    title: Nutch Tutorial\n  - type: Tutorials\n    url: https://nutch.apache.org/documentation/tutorials/\n    title: Apache Nutch Tutorials\n  - type: FAQ\n    url: https://nutch.apache.org/documentation/faqs/\n    title: Apache Nutch FAQs\n  - type: ReleaseNotes\n    url: https://github.com/apache/nutch/blob/master/CHANGES.md\n    title: Nutch Release Notes\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n    title: Apache License 2.0\n  - type: Support\n    url: https://nutch.apache.org/community/mailing-lists/\n\
  \    title: Mailing Lists\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/nutch\n    title: Nutch on Stack Overflow\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/rules/apache-nutch-spectral-rules.yml\n    title: Apache Nutch Spectral Rules\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/capabilities/apache-nutch-crawl-management.yaml\n    title: Apache Nutch Crawl Management\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/vocabulary/apache-nutch-vocabulary.yaml\n    title: Apache Nutch Vocabulary\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/json-ld/apache-nutch-context.jsonld\n    title: Apache Nutch JSON-LD Context\n  - type: Features\n    data:\n      - name: Scalable Batch Crawling\n        description:\
  \ Leverages Apache Hadoop data structures for distributed, large-scale web crawling batch processing.\n      - name: Pluggable Architecture\n        description: Extensible plugin system supporting custom parse filters, scoring filters, index writers, protocol plugins, and URL filters.\n      - name: REST API for Crawl Management\n        description: Full REST API for managing crawl jobs, configurations, seed lists, CrawlDB/FetchDB queries, and sequence file readers.\n      - name: Full-Text Search Integration\n        description: Built-in index writers for Apache Solr and Elasticsearch to enable full-text search over crawled content.\n      - name: Apache Tika Parsing\n        description: Uses Apache Tika for parsing a wide variety of document formats during the crawl pipeline.\n      - name: Duplicate Detection\n        description: Built-in deduplication support to identify and remove duplicate content from the crawl database and search index.\n      - name: Configurable URL Filtering\n\
  \        description: Regex-based and custom URL filter plugins to control crawl scope and exclusions.\n      - name: Incremental Crawling\n        description: Supports multi-round incremental crawling workflows to keep the crawl database fresh.\n      - name: CommonCrawl Export\n        description: Service operations for exporting crawl data in CommonCrawl-compatible formats.\n      - name: HTTP Authentication Support\n        description: Configurable HTTP authentication schemes for crawling password-protected sites.\n  - type: UseCases\n    data:\n      - name: Enterprise Search\n        description: Build enterprise search engines over internal or external web content using Nutch as the crawler and Solr/Elasticsearch as the search backend.\n      - name: Research Data Collection\n        description: Academic and research teams use Nutch for large-scale systematic web data collection and indexing.\n      - name: Intranet Document Search\n        description: Crawl and index intranet\
  \ sites, wikis, and document repositories for internal enterprise search.\n      - name: Web Archive Creation\n        description: Create structured web archives compatible with CommonCrawl format for long-term data preservation.\n      - name: SEO and Content Monitoring\n        description: Monitor web content changes, track competitor sites, and analyze web structure at scale.\n      - name: Custom Data Extraction Pipelines\n        description: Build custom extraction pipelines using Nutch plugin architecture for targeted data acquisition tasks.\n  - type: Integrations\n    data:\n      - name: Apache Solr\n        description: Native index writer plugin for indexing crawled content into Apache Solr for full-text search.\n      - name: Elasticsearch\n        description: Index writer plugin for sending crawled content to Elasticsearch clusters.\n      - name: Apache Hadoop\n        description: Core dependency providing distributed storage and processing via HDFS and MapReduce.\n\
  \      - name: Apache Tika\n        description: Used for content detection and extraction from a wide range of document formats during parsing.\n      - name: SolrCloud\n        description: Support for SolrCloud distributed search clusters for scalable indexing.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/apis.yml
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
