---
api_count: 3
api_specs:
- filename: apache-iceberg-rest-catalog-open-api.yaml
  format: yaml
  label: Apache Iceberg REST Catalog API
  slug: rest-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-iceberg/refs/heads/main/openapi/apache-iceberg-rest-catalog-open-api.yaml
apis:
- description: The Iceberg REST Catalog API defines the specification for catalog server implementations, enabling table discovery, creation, metadata management, namespace management, and multi-table transactions o
  name: Apache Iceberg REST Catalog API
  slug: rest-catalog-api
- description: The Iceberg Java API provides programmatic access to table operations, schema management, partition management, and catalog implementations. It is the primary library for integrating Iceberg with JVM-
  name: Apache Iceberg Java API
  slug: java-api
- description: PyIceberg is the official Python implementation of the Apache Iceberg table specification. It provides programmatic access to Iceberg table metadata and data, with integrations for PyArrow, Pandas, Du
  name: PyIceberg Python API
  slug: python-api
capabilities:
- description: Workflow capability for data engineers and lakehouse architects to manage namespaces, tables, and views in Apache Iceberg catalogs via the REST Catalog API.
  name: Apache Iceberg Catalog Management
  slug: catalog-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/iceberg
- title: ''
  type: Documentation
  url: https://iceberg.apache.org/docs/latest/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Blog
  url: https://iceberg.apache.org/blogs/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@ApacheIceberg
- title: ''
  type: Versioning
  url: https://iceberg.apache.org/releases/
- title: ''
  type: ReleaseNotes
  url: https://iceberg.apache.org/releases/
- title: ''
  type: SpectralRules
  url: rules/apache-iceberg-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-iceberg-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/catalog-management.yaml
created: '2026-03-16'
description: Apache Iceberg is an open table format for large analytic datasets that provides ACID transactions, schema evolution, hidden partitioning, and time travel. It works with Spark, Flink, Hive, Presto, Trino, DuckDB, ClickHouse, and many more compute engines. Governed by the Apache Software Foundation under the Apache 2.0 license.
features:
- description: Full ACID transaction support with serializable isolation for concurrent readers and writers.
  name: ACID Transactions
- description: Add, drop, update, or rename columns without rewriting existing data files.
  name: Schema Evolution
- description: Automatic partition management that prevents common user mistakes and silently incorrect results.
  name: Hidden Partitioning
- description: Change partition layout over time without rewriting existing data.
  name: Partition Evolution
- description: Query historical snapshots of tables and roll back to any prior version.
  name: Time Travel
- description: Supports upserts, deletes, and updates at the row level via merge-on-read and copy-on-write modes.
  name: Row-Level Updates
- description: Works with Spark, Flink, Hive, Trino, Presto, Impala, DuckDB, ClickHouse, and more.
  name: Multi-Engine Support
- description: Native support for S3, ADLS, GCS, and HDFS with no filesystem dependencies.
  name: Cloud-Native Storage
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Full read/write support for Iceberg tables in Spark batch and streaming workloads.
  name: Apache Spark
- description: Streaming and batch integration with exactly-once write support.
  name: Apache Flink
- description: Read and write Iceberg tables from Hive queries using the Iceberg Hive integration.
  name: Apache Hive
- description: Query Iceberg tables from Trino with full partition pruning and predicate pushdown.
  name: Trino
- description: Use AWS Glue as the Iceberg catalog backend with full metadata management.
  name: AWS Glue Catalog
- description: Query Iceberg tables stored in S3 using Amazon Athena.
  name: AWS Athena
- description: Git-like catalog branching and versioning via Nessie catalog integration.
  name: Project Nessie
- description: Local analytics on Iceberg tables via the DuckDB Iceberg extension.
  name: DuckDB
- description: Query Iceberg tables from ClickHouse via the ClickHouse Iceberg integration.
  name: ClickHouse
- description: Access Iceberg tables managed in Snowflake's Polaris catalog.
  name: Snowflake
- description: Use BigQuery as a compute engine over Iceberg tables with BigLake Metastore.
  name: Google BigQuery
- description: Create and query Iceberg tables on Databricks using Unity Catalog.
  name: Databricks
jsonld:
- class_count: 119
  name: Apache Iceberg Rest Catalog Open Api Context
  property_count: 190
  slug: apache-iceberg-rest-catalog-open-api-context
layout: provider
modified: '2026-04-19'
name: Apache Iceberg
rules:
- name: Apache Iceberg API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 5
    warn: 12
  slug: apache-iceberg-spectral-rules
skills: []
slug: apache-iceberg
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-iceberg\nname: Apache Iceberg\ndescription: >-\n  Apache Iceberg is an open table format for large analytic datasets that provides ACID transactions, schema evolution, hidden partitioning, and time travel. It works with Spark, Flink, Hive, Presto, Trino, DuckDB, ClickHouse, and many more compute engines. Governed by the Apache Software Foundation under the Apache 2.0 license.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ACID\n  - Analytics\n  - Apache\n  - Data Lake\n  - Lakehouse\n  - Open Source\n  - Table Format\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-iceberg/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-iceberg:rest-catalog-api\n    name: Apache Iceberg REST Catalog API\n    description: >-\n      The Iceberg REST Catalog API defines the specification\
  \ for catalog server implementations, enabling table discovery, creation, metadata management, namespace management, and multi-table transactions over HTTP. It is the standard integration point for compute engines connecting to Iceberg catalogs.\n    humanURL: https://iceberg.apache.org/rest-catalog-spec/\n    tags:\n      - Catalog\n      - Namespace\n      - REST\n      - Table Format\n    properties:\n      - type: Documentation\n        url: https://iceberg.apache.org/rest-catalog-spec/\n      - type: OpenAPI\n        url: openapi/apache-iceberg-rest-catalog-open-api.yaml\n\n  - aid: apache-iceberg:java-api\n    name: Apache Iceberg Java API\n    description: >-\n      The Iceberg Java API provides programmatic access to table operations, schema management, partition management, and catalog implementations. It is the primary library for integrating Iceberg with JVM-based compute engines including Spark, Flink, Hive, Trino, and Presto.\n    humanURL: https://iceberg.apache.org/javadoc/latest/\n\
  \    tags:\n      - Java\n      - JVM\n      - SDK\n      - Table Format\n    properties:\n      - type: Documentation\n        url: https://iceberg.apache.org/javadoc/latest/\n      - type: GettingStarted\n        url: https://iceberg.apache.org/docs/latest/java-api-quickstart/\n\n  - aid: apache-iceberg:python-api\n    name: PyIceberg Python API\n    description: >-\n      PyIceberg is the official Python implementation of the Apache Iceberg table specification. It provides programmatic access to Iceberg table metadata and data, with integrations for PyArrow, Pandas, DuckDB, Ray, Polars, and multiple catalog backends.\n    humanURL: https://py.iceberg.apache.org/\n    tags:\n      - Python\n      - SDK\n      - Table Format\n    properties:\n      - type: Documentation\n        url: https://py.iceberg.apache.org/\n      - type: SDK\n        url: https://pypi.org/project/pyiceberg/\n      - type: GitHubRepository\n        url: https://github.com/apache/iceberg-python\n\ncommon:\n  - type:\
  \ GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/iceberg\n  - type: Documentation\n    url: https://iceberg.apache.org/docs/latest/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Blog\n    url: https://iceberg.apache.org/blogs/\n  - type: YouTube\n    url: https://www.youtube.com/@ApacheIceberg\n  - type: Versioning\n    url: https://iceberg.apache.org/releases/\n  - type: ReleaseNotes\n    url: https://iceberg.apache.org/releases/\n  - type: SpectralRules\n    url: rules/apache-iceberg-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-iceberg-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/catalog-management.yaml\n  - type: Features\n    data:\n      - name: ACID Transactions\n        description: Full ACID transaction support with serializable isolation for concurrent readers and writers.\n      - name: Schema Evolution\n        description:\
  \ Add, drop, update, or rename columns without rewriting existing data files.\n      - name: Hidden Partitioning\n        description: Automatic partition management that prevents common user mistakes and silently incorrect results.\n      - name: Partition Evolution\n        description: Change partition layout over time without rewriting existing data.\n      - name: Time Travel\n        description: Query historical snapshots of tables and roll back to any prior version.\n      - name: Row-Level Updates\n        description: Supports upserts, deletes, and updates at the row level via merge-on-read and copy-on-write modes.\n      - name: Multi-Engine Support\n        description: Works with Spark, Flink, Hive, Trino, Presto, Impala, DuckDB, ClickHouse, and more.\n      - name: Cloud-Native Storage\n        description: Native support for S3, ADLS, GCS, and HDFS with no filesystem dependencies.\n  - type: UseCases\n    data:\n      - name: Lakehouse Analytics\n        description: Build\
  \ open lakehouse architectures with ACID guarantees across petabyte-scale datasets.\n      - name: Real-Time Data Pipelines\n        description: Stream data into Iceberg tables via Flink or Kafka Connect with exactly-once semantics.\n      - name: Data Versioning and Auditing\n        description: Use time travel to audit historical data states and implement regulatory compliance.\n      - name: Multi-Engine Query Federation\n        description: Query the same Iceberg tables from multiple engines (Spark, Trino, DuckDB) without data duplication.\n      - name: Cloud Data Migration\n        description: Migrate on-premises Hive workloads to cloud-native Iceberg tables with full compatibility.\n  - type: Integrations\n    data:\n      - name: Apache Spark\n        description: Full read/write support for Iceberg tables in Spark batch and streaming workloads.\n      - name: Apache Flink\n        description: Streaming and batch integration with exactly-once write support.\n      - name:\
  \ Apache Hive\n        description: Read and write Iceberg tables from Hive queries using the Iceberg Hive integration.\n      - name: Trino\n        description: Query Iceberg tables from Trino with full partition pruning and predicate pushdown.\n      - name: AWS Glue Catalog\n        description: Use AWS Glue as the Iceberg catalog backend with full metadata management.\n      - name: AWS Athena\n        description: Query Iceberg tables stored in S3 using Amazon Athena.\n      - name: Project Nessie\n        description: Git-like catalog branching and versioning via Nessie catalog integration.\n      - name: DuckDB\n        description: Local analytics on Iceberg tables via the DuckDB Iceberg extension.\n      - name: ClickHouse\n        description: Query Iceberg tables from ClickHouse via the ClickHouse Iceberg integration.\n      - name: Snowflake\n        description: Access Iceberg tables managed in Snowflake's Polaris catalog.\n      - name: Google BigQuery\n        description:\
  \ Use BigQuery as a compute engine over Iceberg tables with BigLake Metastore.\n      - name: Databricks\n        description: Create and query Iceberg tables on Databricks using Unity Catalog.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-iceberg/refs/heads/main/apis.yml
tags:
- ACID
- Analytics
- Apache
- Data Lake
- Lakehouse
- Open Source
- Table Format
url: https://raw.githubusercontent.com/api-evangelist/apache-iceberg/refs/heads/main/apis.yml
use_cases:
- description: Build open lakehouse architectures with ACID guarantees across petabyte-scale datasets.
  name: Lakehouse Analytics
- description: Stream data into Iceberg tables via Flink or Kafka Connect with exactly-once semantics.
  name: Real-Time Data Pipelines
- description: Use time travel to audit historical data states and implement regulatory compliance.
  name: Data Versioning and Auditing
- description: Query the same Iceberg tables from multiple engines (Spark, Trino, DuckDB) without data duplication.
  name: Multi-Engine Query Federation
- description: Migrate on-premises Hive workloads to cloud-native Iceberg tables with full compatibility.
  name: Cloud Data Migration
---
