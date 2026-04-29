---
api_count: 2
api_specs:
- filename: apache-hive-webhcat-openapi.yml
  format: yaml
  label: Apache Hive WebHCat REST API
  slug: apache-hive-webhcat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/openapi/apache-hive-webhcat-openapi.yml
apis:
- description: WebHCat (Templeton) REST API for Apache Hive providing DDL operations, HiveQL job submission, and Hive Metastore metadata access over HTTP.
  name: Apache Hive WebHCat REST API
  slug: apache-hive-webhcat-api
- description: JDBC interface to HiveServer2 for standard SQL client connectivity, supporting parameterized queries, result sets, and connection pooling from Java and ODBC-bridge applications.
  name: Apache Hive JDBC API
  slug: apache-hive-jdbc
capabilities:
- description: ''
  name: Hive Data Querying
  slug: hive-data-querying
common:
- title: ''
  type: Documentation
  url: https://cwiki.apache.org/confluence/display/Hive/Home
- title: ''
  type: GettingStarted
  url: https://cwiki.apache.org/confluence/display/Hive/GettingStarted
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/hive
- title: ''
  type: SpectralRules
  url: rules/apache-hive-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-hive-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/hive-data-querying.yaml
created: '2026-03-16'
description: Apache Hive is a data warehouse software that facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. It provides a SQL-like interface called HiveQL for querying data stored in Hadoop, along with a WebHCat REST API for job submission and metastore access.
features:
- description: SQL-like query language for reading, writing, and aggregating data stored in distributed storage.
  name: HiveQL SQL Interface
- description: HTTP REST API (Templeton) for DDL operations, job submission, and metastore metadata access.
  name: WebHCat REST API
- description: Thrift-based server with JDBC and ODBC drivers for standard SQL client connectivity.
  name: HiveServer2 JDBC/ODBC
- description: Central repository for table schema, partition metadata, and storage location information.
  name: Hive Metastore
- description: Partition tables by column values for efficient query pruning and data organization.
  name: Partitioning
- description: Optimized columnar storage formats with predicate pushdown and compression support.
  name: ORC and Parquet Storage
- description: Full ACID transaction support for inserts, updates, and deletes on managed ORC tables.
  name: ACID Transactions
- description: Batch processing of rows in CPU register-width vectors for improved query throughput.
  name: Vectorized Query Execution
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Hive reads and writes data stored in HDFS as the primary storage layer.
  name: Apache Hadoop HDFS
- description: Spark uses the Hive Metastore for table discovery and supports Hive UDFs.
  name: Apache Spark
- description: Hive HBase storage handler enables HiveQL queries against HBase tables.
  name: Apache HBase
- description: Apache Tez DAG execution engine replaces MapReduce for faster Hive query processing.
  name: Apache Tez
- description: Presto and Trino use the Hive Metastore for table metadata in federated SQL queries.
  name: Presto / Trino
jsonld:
- class_count: 21
  name: Apache Hive Webhcat Context
  property_count: 0
  slug: apache-hive-webhcat-context
layout: provider
modified: '2026-04-19'
name: Apache Hive
rules:
- name: Apache Hive API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: apache-hive-spectral-rules
skills: []
slug: apache-hive
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-hive\nname: Apache Hive\ndescription: >-\n  Apache Hive is a data warehouse software that facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. It provides a SQL-like interface called HiveQL for querying data stored in Hadoop, along with a WebHCat REST API for job submission and metastore access.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Big Data\n  - Data Warehouse\n  - ETL\n  - Hadoop\n  - Open Source\n  - SQL\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-hive:apache-hive-webhcat-api\n    name: Apache Hive WebHCat REST API\n    description: >-\n      WebHCat (Templeton) REST API for Apache Hive providing DDL operations, HiveQL job submission, and Hive\
  \ Metastore metadata access over HTTP.\n    humanURL: https://cwiki.apache.org/confluence/display/Hive/WebHCat\n    baseURL: http://localhost:50111/templeton/v1\n    tags:\n      - Databases\n      - Jobs\n      - Metastore\n      - REST\n      - Tables\n    properties:\n      - type: Documentation\n        url: https://cwiki.apache.org/confluence/display/Hive/WebHCat\n      - type: OpenAPI\n        url: openapi/apache-hive-webhcat-openapi.yml\n      - type: JSONSchema\n        url: json-schema/hive-webhcat-table-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-hive-webhcat-context.jsonld\n\n  - aid: apache-hive:apache-hive-jdbc\n    name: Apache Hive JDBC API\n    description: >-\n      JDBC interface to HiveServer2 for standard SQL client connectivity, supporting parameterized queries, result sets, and connection pooling from Java and ODBC-bridge applications.\n    humanURL: https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC\n\
  \    tags:\n      - JDBC\n      - SQL\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Clients#HiveServer2Clients-JDBC\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.hive/hive-jdbc\n        title: Java JDBC Driver (Maven Central)\n\ncommon:\n  - type: Documentation\n    url: https://cwiki.apache.org/confluence/display/Hive/Home\n  - type: GettingStarted\n    url: https://cwiki.apache.org/confluence/display/Hive/GettingStarted\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/hive\n  - type: SpectralRules\n    url: rules/apache-hive-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-hive-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/hive-data-querying.yaml\n  - type: Features\n    data:\n      - name: HiveQL SQL Interface\n        description: SQL-like query\
  \ language for reading, writing, and aggregating data stored in distributed storage.\n      - name: WebHCat REST API\n        description: HTTP REST API (Templeton) for DDL operations, job submission, and metastore metadata access.\n      - name: HiveServer2 JDBC/ODBC\n        description: Thrift-based server with JDBC and ODBC drivers for standard SQL client connectivity.\n      - name: Hive Metastore\n        description: Central repository for table schema, partition metadata, and storage location information.\n      - name: Partitioning\n        description: Partition tables by column values for efficient query pruning and data organization.\n      - name: ORC and Parquet Storage\n        description: Optimized columnar storage formats with predicate pushdown and compression support.\n      - name: ACID Transactions\n        description: Full ACID transaction support for inserts, updates, and deletes on managed ORC tables.\n      - name: Vectorized Query Execution\n        description:\
  \ Batch processing of rows in CPU register-width vectors for improved query throughput.\n  - type: UseCases\n    data:\n      - name: Data Warehouse Analytics\n        description: Run SQL analytics on petabyte-scale datasets stored in HDFS or object storage.\n      - name: ETL Pipeline Orchestration\n        description: Use HiveQL scripts to transform and load data between raw and curated data lake zones.\n      - name: Ad-Hoc Data Exploration\n        description: Query structured data interactively using Beeline or JDBC-connected BI tools.\n      - name: Log Analysis\n        description: Parse and aggregate application logs stored as text or JSON in HDFS using Hive SerDes.\n      - name: Data Catalog Integration\n        description: Use the Hive Metastore as a shared schema registry for Spark, Flink, and Presto.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop HDFS\n        description: Hive reads and writes data stored in HDFS as the primary storage layer.\n     \
  \ - name: Apache Spark\n        description: Spark uses the Hive Metastore for table discovery and supports Hive UDFs.\n      - name: Apache HBase\n        description: Hive HBase storage handler enables HiveQL queries against HBase tables.\n      - name: Apache Tez\n        description: Apache Tez DAG execution engine replaces MapReduce for faster Hive query processing.\n      - name: Presto / Trino\n        description: Presto and Trino use the Hive Metastore for table metadata in federated SQL queries.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/apis.yml
tags:
- Apache
- Big Data
- Data Warehouse
- ETL
- Hadoop
- Open Source
- SQL
url: https://raw.githubusercontent.com/api-evangelist/apache-hive/refs/heads/main/apis.yml
use_cases:
- description: Run SQL analytics on petabyte-scale datasets stored in HDFS or object storage.
  name: Data Warehouse Analytics
- description: Use HiveQL scripts to transform and load data between raw and curated data lake zones.
  name: ETL Pipeline Orchestration
- description: Query structured data interactively using Beeline or JDBC-connected BI tools.
  name: Ad-Hoc Data Exploration
- description: Parse and aggregate application logs stored as text or JSON in HDFS using Hive SerDes.
  name: Log Analysis
- description: Use the Hive Metastore as a shared schema registry for Spark, Flink, and Presto.
  name: Data Catalog Integration
---
