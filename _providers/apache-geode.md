---
api_count: 2
api_specs:
- filename: apache-geode-rest-openapi.yml
  format: yaml
  label: Apache Geode REST API
  slug: apache-geode-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-geode/refs/heads/main/openapi/apache-geode-rest-openapi.yml
apis:
- description: REST API for accessing and managing data in Apache Geode in-memory data grid, including region operations, OQL queries, function execution, and cluster monitoring.
  name: Apache Geode REST API
  slug: apache-geode-rest-api
- description: Java API for cache operations, continuous queries, function execution, and data serialization in Apache Geode clusters.
  name: Apache Geode Java Client API
  slug: apache-geode-java-api
capabilities:
- description: Unified capability for managing data in Apache Geode in-memory data grid — accessing regions, executing OQL queries, and running server-side functions. Designed for application developers and platform
  name: Apache Geode Data Management
  slug: geode-data-management
common:
- title: ''
  type: Documentation
  url: https://geode.apache.org/docs/
- title: ''
  type: GettingStarted
  url: https://geode.apache.org/docs/guide/latest/getting_started/book_intro.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/geode
- title: ''
  type: Blog
  url: https://geode.apache.org/blog/
- title: ''
  type: SpectralRules
  url: rules/apache-geode-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-geode-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/geode-data-management.yaml
created: '2026-03-16'
description: Apache Geode is an in-memory data management platform that provides real-time, consistent access to data-intensive applications throughout widely distributed cloud architectures. It pools memory, CPU, network resources, and local disk storage across multiple processes, offering a REST API for data access, OQL queries, function execution, and cluster management.
features:
- description: Pool memory across distributed nodes for consistent sub-millisecond data access at scale.
  name: In-Memory Data Grid
- description: HTTP REST API for language-agnostic CRUD operations on Geode regions using JSON.
  name: REST Data API
- description: SQL-like Object Query Language for executing complex queries against in-memory data.
  name: OQL Query Language
- description: Register interest in data changes meeting OQL criteria for real-time event notification.
  name: Continuous Queries
- description: Deploy and execute Java functions on the cluster nodes to co-locate compute with data.
  name: Server-Side Functions
- description: Full ACID transaction support for consistent multi-region data operations.
  name: ACID Transactions
- description: Asynchronous and synchronous WAN gateway replication for geo-distributed data consistency.
  name: WAN Replication
- description: Configurable eviction policies (LRU, heap, disk) and TTL-based entry expiration.
  name: Eviction and Expiration
- description: Disk persistence option for data recovery after restart without network re-loading.
  name: Persistence
- description: High-performance C++ and .NET native client libraries for non-JVM applications.
  name: Native Clients
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Geode-Spark connector for using Geode regions as Spark RDD/DataFrame data sources.
  name: Apache Spark
- description: Spring Data integration for repository-based data access and caching annotations.
  name: Spring Data Geode
- description: Kubernetes operator for deploying and managing Geode clusters on Kubernetes.
  name: Kubernetes
- description: Cloud Foundry service broker for provisioning Geode instances as managed services.
  name: Pivotal Cloud Foundry
jsonld:
- class_count: 11
  name: Apache Geode Rest Context
  property_count: 11
  slug: apache-geode-rest-context
layout: provider
modified: '2026-04-19'
name: Apache Geode
rules:
- name: Apache Geode API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 4
  slug: apache-geode-spectral-rules
skills: []
slug: apache-geode
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-geode\nname: Apache Geode\ndescription: >-\n  Apache Geode is an in-memory data management platform that provides real-time, consistent access to data-intensive applications throughout widely distributed cloud architectures. It pools memory, CPU, network resources, and local disk storage across multiple processes, offering a REST API for data access, OQL queries, function execution, and cluster management.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Caching\n  - Data Grid\n  - Distributed Systems\n  - In-Memory\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-geode/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-geode:apache-geode-rest-api\n    name: Apache Geode REST API\n    description: >-\n      REST API for accessing and managing data\
  \ in Apache Geode in-memory data grid, including region operations, OQL queries, function execution, and cluster monitoring.\n    humanURL: https://geode.apache.org/docs/guide/latest/rest_apps/chapter_overview.html\n    baseURL: http://localhost:8080\n    tags:\n      - Cache\n      - Data Grid\n      - In-Memory\n      - OQL\n      - REST\n    properties:\n      - type: Documentation\n        url: https://geode.apache.org/docs/guide/latest/rest_apps/chapter_overview.html\n      - type: OpenAPI\n        url: openapi/apache-geode-rest-openapi.yml\n      - type: JSONSchema\n        url: json-schema/geode-rest-region-info-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-geode-rest-context.jsonld\n\n  - aid: apache-geode:apache-geode-java-api\n    name: Apache Geode Java Client API\n    description: >-\n      Java API for cache operations, continuous queries, function execution, and data serialization in Apache Geode clusters.\n    humanURL: https://geode.apache.org/docs/guide/latest/developing/book_intro.html\n\
  \    tags:\n      - Java\n      - SDK\n      - Cache\n      - Continuous Query\n    properties:\n      - type: Documentation\n        url: https://geode.apache.org/docs/guide/latest/developing/book_intro.html\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.geode/geode-core\n        title: Java SDK (Maven Central)\n\ncommon:\n  - type: Documentation\n    url: https://geode.apache.org/docs/\n  - type: GettingStarted\n    url: https://geode.apache.org/docs/guide/latest/getting_started/book_intro.html\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/geode\n  - type: Blog\n    url: https://geode.apache.org/blog/\n  - type: SpectralRules\n    url: rules/apache-geode-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-geode-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/geode-data-management.yaml\n  - type: Features\n    data:\n      - name: In-Memory\
  \ Data Grid\n        description: Pool memory across distributed nodes for consistent sub-millisecond data access at scale.\n      - name: REST Data API\n        description: HTTP REST API for language-agnostic CRUD operations on Geode regions using JSON.\n      - name: OQL Query Language\n        description: SQL-like Object Query Language for executing complex queries against in-memory data.\n      - name: Continuous Queries\n        description: Register interest in data changes meeting OQL criteria for real-time event notification.\n      - name: Server-Side Functions\n        description: Deploy and execute Java functions on the cluster nodes to co-locate compute with data.\n      - name: ACID Transactions\n        description: Full ACID transaction support for consistent multi-region data operations.\n      - name: WAN Replication\n        description: Asynchronous and synchronous WAN gateway replication for geo-distributed data consistency.\n      - name: Eviction and Expiration\n\
  \        description: Configurable eviction policies (LRU, heap, disk) and TTL-based entry expiration.\n      - name: Persistence\n        description: Disk persistence option for data recovery after restart without network re-loading.\n      - name: Native Clients\n        description: High-performance C++ and .NET native client libraries for non-JVM applications.\n  - type: UseCases\n    data:\n      - name: Session Caching\n        description: Replace Redis or Memcached with Geode for distributed session caching with ACID guarantees.\n      - name: Real-Time Analytics\n        description: Perform OQL queries on in-flight event data for real-time analytical processing.\n      - name: Financial Transaction Processing\n        description: Low-latency transaction processing with ACID guarantees for financial trading and payments.\n      - name: Microservices Shared State\n        description: Share state between microservices with consistent in-memory data across distributed nodes.\n\
  \      - name: IoT Data Aggregation\n        description: Aggregate and query high-velocity IoT telemetry data in memory for real-time responses.\n  - type: Integrations\n    data:\n      - name: Apache Spark\n        description: Geode-Spark connector for using Geode regions as Spark RDD/DataFrame data sources.\n      - name: Spring Data Geode\n        description: Spring Data integration for repository-based data access and caching annotations.\n      - name: Kubernetes\n        description: Kubernetes operator for deploying and managing Geode clusters on Kubernetes.\n      - name: Pivotal Cloud Foundry\n        description: Cloud Foundry service broker for provisioning Geode instances as managed services.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-geode/refs/heads/main/apis.yml
tags:
- Apache
- Caching
- Data Grid
- Distributed Systems
- In-Memory
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-geode/refs/heads/main/apis.yml
use_cases:
- description: Replace Redis or Memcached with Geode for distributed session caching with ACID guarantees.
  name: Session Caching
- description: Perform OQL queries on in-flight event data for real-time analytical processing.
  name: Real-Time Analytics
- description: Low-latency transaction processing with ACID guarantees for financial trading and payments.
  name: Financial Transaction Processing
- description: Share state between microservices with consistent in-memory data across distributed nodes.
  name: Microservices Shared State
- description: Aggregate and query high-velocity IoT telemetry data in memory for real-time responses.
  name: IoT Data Aggregation
---
