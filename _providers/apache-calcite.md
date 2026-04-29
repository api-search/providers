---
api_count: 3
apis:
- description: The Apache Calcite Java API provides SQL parsing, validation, query planning, and optimization capabilities for embedding in JVM applications. It exposes a relational algebra framework and pluggable o
  name: Apache Calcite Java API
  slug: apache-calcite-java-api
- description: 'The Apache Calcite JDBC adapter provides a standard JDBC interface over heterogeneous data sources. Applications use it to issue SQL queries across multiple data formats and storage systems through a '
  name: Apache Calcite JDBC API
  slug: apache-calcite-jdbc-api
- description: Apache Avatica is a framework for building database drivers derived from Apache Calcite. It provides a JSON/Protobuf-over-HTTP remote protocol for JDBC clients to connect to Calcite-based query engine
  name: Apache Calcite Avatica API
  slug: apache-calcite-avatica-api
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/calcite
- title: ''
  type: Documentation
  url: https://calcite.apache.org/
- title: ''
  type: GettingStarted
  url: https://calcite.apache.org/docs/tutorial.html
- title: ''
  type: Support
  url: https://calcite.apache.org/community/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: ChangeLog
  url: https://github.com/apache/calcite/releases
- title: Java SDK (Maven)
  type: SDK
  url: https://search.maven.org/artifact/org.apache.calcite/calcite-core
- title: ''
  type: Vocabulary
  url: vocabulary/apache-calcite-vocabulary.yaml
created: '2026-03-16'
description: Apache Calcite is a dynamic data management framework developed by the Apache Software Foundation that provides SQL parsing, query planning and optimization, and data federation capabilities. It serves as the SQL engine and query optimizer for many big data systems including Apache Hive, Druid, Flink, Kafka Streams, and others. Calcite provides a Java API for embedding SQL capabilities into applications, a JDBC adapter for connecting heterogeneous data sources, and an extensible relational algebra framework for building custom query optimizers.
features:
- description: Parse and validate SQL queries using an extensible SQL grammar with support for SQL:2003 and beyond.
  name: SQL Parsing and Validation
- description: Cost-based and rule-based query optimization using a volcano-style optimizer with pluggable optimization rules.
  name: Query Optimization
- description: Extensible relational algebra framework for representing and transforming query plans as expression trees.
  name: Relational Algebra
- description: Federate queries across heterogeneous data sources including CSV, JSON, JDBC databases, and Elasticsearch.
  name: Data Federation
- description: Pluggable adapter API for connecting new data sources to the Calcite SQL engine.
  name: Adapter Framework
- description: Automatic materialized view recognition and query rewriting for query acceleration.
  name: Materialized Views
- description: SQL extensions for querying streaming data sources with window functions and temporal predicates.
  name: Streaming SQL
- description: Summary table recommendation and query rewriting using lattice structures for OLAP workloads.
  name: Lattices and Tiles
- description: Standard JDBC driver for issuing SQL queries against Calcite-connected data sources.
  name: JDBC Driver
- description: JSON/Protobuf-over-HTTP remote JDBC protocol for connecting clients to Calcite-based query servers.
  name: Avatica Remote Protocol
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Flink uses Calcite for SQL parsing and query optimization in Flink SQL and Table API.
  name: Apache Flink
- description: Hive uses Calcite for cost-based query optimization in HiveQL query planning.
  name: Apache Hive
- description: Druid uses Calcite for SQL query parsing and planning against its time-series data store.
  name: Apache Druid
- description: ksqlDB and Kafka Streams use Calcite for SQL stream processing query planning.
  name: Apache Kafka
- description: Beam SQL uses Calcite for query planning on PCollection-based streaming and batch pipelines.
  name: Apache Beam
- description: Calcite provides a SQL adapter for querying Elasticsearch indices using standard SQL.
  name: Elasticsearch
- description: Kylin uses Calcite as its SQL engine for OLAP cube query planning and execution.
  name: Apache Kylin
layout: provider
modified: '2026-04-19'
name: Apache Calcite
skills: []
slug: apache-calcite
solutions: []
source_yaml: "aid: apache-calcite\nname: Apache Calcite\ndescription: >-\n  Apache Calcite is a dynamic data management framework developed by the Apache Software Foundation that provides SQL parsing, query planning and optimization, and data federation capabilities. It serves as the SQL engine and query optimizer for many big data systems including Apache Hive, Druid, Flink, Kafka Streams, and others. Calcite provides a Java API for embedding SQL capabilities into applications, a JDBC adapter for connecting heterogeneous data sources, and an extensible relational algebra framework for building custom query optimizers.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Data Federation\n  - Framework\n  - Open Source\n  - Query Optimization\n  - SQL\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-calcite/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-calcite:apache-calcite-java-api\n    name: Apache Calcite Java API\n    description: >-\n      The Apache Calcite Java API provides SQL parsing, validation, query planning, and optimization capabilities for embedding in JVM applications. It exposes a relational algebra framework and pluggable optimizer rules for building custom query engines.\n    humanURL: https://calcite.apache.org/docs/\n    tags:\n      - Java\n      - Query Engine\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://calcite.apache.org/docs/\n      - type: APIReference\n        url: https://calcite.apache.org/javadocAggregate/\n      - type: GettingStarted\n        url: https://calcite.apache.org/docs/tutorial.html\n  - aid: apache-calcite:apache-calcite-jdbc-api\n    name: Apache Calcite JDBC API\n    description: >-\n      The Apache Calcite JDBC adapter provides a standard JDBC interface over heterogeneous data sources. Applications\
  \ use it to issue SQL queries across multiple data formats and storage systems through a unified SQL interface.\n    humanURL: https://calcite.apache.org/docs/adapter.html\n    tags:\n      - JDBC\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://calcite.apache.org/docs/adapter.html\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.calcite/calcite-core\n  - aid: apache-calcite:apache-calcite-avatica-api\n    name: Apache Calcite Avatica API\n    description: >-\n      Apache Avatica is a framework for building database drivers derived from Apache Calcite. It provides a JSON/Protobuf-over-HTTP remote protocol for JDBC clients to connect to Calcite-based query engines.\n    humanURL: https://calcite.apache.org/avatica/docs/\n    tags:\n      - Avatica\n      - HTTP\n      - JDBC\n    properties:\n      - type: Documentation\n        url: https://calcite.apache.org/avatica/docs/\n      - type: APIReference\n        url: https://calcite.apache.org/avatica/javadocAggregate/\n\
  common:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/calcite\n  - type: Documentation\n    url: https://calcite.apache.org/\n  - type: GettingStarted\n    url: https://calcite.apache.org/docs/tutorial.html\n  - type: Support\n    url: https://calcite.apache.org/community/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: ChangeLog\n    url: https://github.com/apache/calcite/releases\n  - type: SDK\n    url: https://search.maven.org/artifact/org.apache.calcite/calcite-core\n    title: Java SDK (Maven)\n  - type: Vocabulary\n    url: vocabulary/apache-calcite-vocabulary.yaml\n  - type: Features\n    data:\n      - name: SQL Parsing and Validation\n        description: Parse and validate SQL queries using an extensible SQL grammar with support for SQL:2003 and beyond.\n      - name: Query Optimization\n        description: Cost-based and rule-based query optimization using a\
  \ volcano-style optimizer with pluggable optimization rules.\n      - name: Relational Algebra\n        description: Extensible relational algebra framework for representing and transforming query plans as expression trees.\n      - name: Data Federation\n        description: Federate queries across heterogeneous data sources including CSV, JSON, JDBC databases, and Elasticsearch.\n      - name: Adapter Framework\n        description: Pluggable adapter API for connecting new data sources to the Calcite SQL engine.\n      - name: Materialized Views\n        description: Automatic materialized view recognition and query rewriting for query acceleration.\n      - name: Streaming SQL\n        description: SQL extensions for querying streaming data sources with window functions and temporal predicates.\n      - name: Lattices and Tiles\n        description: Summary table recommendation and query rewriting using lattice structures for OLAP workloads.\n      - name: JDBC Driver\n        description:\
  \ Standard JDBC driver for issuing SQL queries against Calcite-connected data sources.\n      - name: Avatica Remote Protocol\n        description: JSON/Protobuf-over-HTTP remote JDBC protocol for connecting clients to Calcite-based query servers.\n  - type: UseCases\n    data:\n      - name: Embedding SQL in Applications\n        description: Add SQL querying capability to Java applications using the Calcite Java API without a full database.\n      - name: Building Query Engines\n        description: Use Calcite as the SQL parsing and optimization layer in custom query engine implementations.\n      - name: Data Virtualization\n        description: Federate queries across multiple heterogeneous data sources using Calcite adapters.\n      - name: OLAP Query Optimization\n        description: Accelerate analytical queries using materialized view rewriting and lattice-based summary tables.\n      - name: SQL Dialect Translation\n        description: Parse SQL in one dialect and transpile\
  \ it to another using Calcite's SQL generation framework.\n  - type: Integrations\n    data:\n      - name: Apache Flink\n        description: Flink uses Calcite for SQL parsing and query optimization in Flink SQL and Table API.\n      - name: Apache Hive\n        description: Hive uses Calcite for cost-based query optimization in HiveQL query planning.\n      - name: Apache Druid\n        description: Druid uses Calcite for SQL query parsing and planning against its time-series data store.\n      - name: Apache Kafka\n        description: ksqlDB and Kafka Streams use Calcite for SQL stream processing query planning.\n      - name: Apache Beam\n        description: Beam SQL uses Calcite for query planning on PCollection-based streaming and batch pipelines.\n      - name: Elasticsearch\n        description: Calcite provides a SQL adapter for querying Elasticsearch indices using standard SQL.\n      - name: Apache Kylin\n        description: Kylin uses Calcite as its SQL engine for OLAP\
  \ cube query planning and execution.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-calcite/refs/heads/main/apis.yml
tags:
- Apache
- Data Federation
- Framework
- Open Source
- Query Optimization
- SQL
url: https://raw.githubusercontent.com/api-evangelist/apache-calcite/refs/heads/main/apis.yml
use_cases:
- description: Add SQL querying capability to Java applications using the Calcite Java API without a full database.
  name: Embedding SQL in Applications
- description: Use Calcite as the SQL parsing and optimization layer in custom query engine implementations.
  name: Building Query Engines
- description: Federate queries across multiple heterogeneous data sources using Calcite adapters.
  name: Data Virtualization
- description: Accelerate analytical queries using materialized view rewriting and lattice-based summary tables.
  name: OLAP Query Optimization
- description: Parse SQL in one dialect and transpile it to another using Calcite's SQL generation framework.
  name: SQL Dialect Translation
---
