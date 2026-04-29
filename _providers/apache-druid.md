---
api_count: 1
apis:
- description: Druid exposes REST APIs for Druid SQL (POST /druid/v2/sql), native JSON queries (POST /druid/v2), batch and streaming data ingestion tasks, supervisor management for Kafka/Kinesis ingestion, data segm
  name: Apache Druid REST API
  slug: apache-druid-rest-api
common:
- title: ''
  type: Portal
  url: https://druid.apache.org/
- title: ''
  type: Documentation
  url: https://druid.apache.org/docs/latest/
- title: ''
  type: GettingStarted
  url: https://druid.apache.org/docs/latest/tutorials/
- title: ''
  type: Blog
  url: https://druid.apache.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/druid
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/druid
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/vocabulary/apache-druid-vocabulary.yaml
created: '2026-03-16'
description: Apache Druid is a high-performance, real-time analytics database governed by the Apache Software Foundation, designed for fast slice-and-dice OLAP queries on event-time data. It features a distributed, column-oriented storage engine with automatic rollup, supports both streaming (Kafka, Kinesis) and batch (S3, HDFS, local) data ingestion, and provides a SQL query interface plus a native JSON query API via REST. Druid is optimized for sub-second queries at petabyte scale with high concurrency.
features:
- description: Columnar storage with bitmap indexes, dictionary encoding, and pre-aggregation (rollup) enables sub-second queries on billions of events.
  name: Sub-Second OLAP Queries
- description: REST endpoint for submitting standard SQL queries with ANSI SQL support, time-based filtering, and streaming response options.
  name: Druid SQL API
- description: Druid-native query format (Timeseries, TopN, GroupBy, Scan, Search) for maximum control and performance.
  name: Native JSON Query API
- description: Real-time data ingestion from Apache Kafka and Amazon Kinesis with supervisor-managed offset tracking and exactly-once semantics.
  name: Streaming Ingestion
- description: Parallel batch indexing tasks from local files, S3, GCS, HDFS, and other external storage systems.
  name: Batch Ingestion
- description: Pre-aggregates metrics at ingestion time to reduce storage and query time, configurable per datasource.
  name: Automatic Rollup
- description: All data is partitioned by time interval (segments), enabling efficient time-range query pruning.
  name: Time-Based Partitioning
- description: Query isolation and resource management via query lanes, scheduler priorities, and row-level access control.
  name: Multi-Tenancy
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: KafkaSupervisor for real-time continuous ingestion from Kafka topics into Druid datasources.
  name: Apache Kafka
- description: KinesisSupervisor for real-time data ingestion from AWS Kinesis data streams.
  name: Amazon Kinesis
- description: Native Hadoop batch indexing task for bulk loading data from HDFS or MapReduce job outputs.
  name: Apache Hadoop / HDFS
- description: Batch and streaming ingestion from object storage (S3, GCS, Azure Blob) using index tasks.
  name: Amazon S3 / GCS
- description: Druid-Hive integration for querying Druid datasources from HiveQL and performing joins.
  name: Apache Hive
- description: Official Kubernetes operator for deploying and managing Druid clusters on Kubernetes.
  name: Kubernetes
- description: Imply provides a commercial managed Druid service with additional features and enterprise support.
  name: Imply (Commercial)
jsonld:
- class_count: 5
  name: Apache Druid Context
  property_count: 32
  slug: apache-druid-context
layout: provider
modified: '2026-04-19'
name: Apache Druid
skills: []
slug: apache-druid
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-druid\nname: Apache Druid\ndescription: >-\n  Apache Druid is a high-performance, real-time analytics database governed by the Apache Software Foundation, designed for fast slice-and-dice OLAP queries on event-time data. It features a distributed,\n  column-oriented storage engine with automatic rollup, supports both streaming (Kafka, Kinesis) and batch (S3, HDFS, local) data ingestion, and provides a SQL query interface plus a native JSON query API\n  via REST. Druid is optimized for sub-second queries at petabyte scale with high concurrency.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Analytics\n- Apache\n- Database\n- Kafka\n- OLAP\n- Open Source\n- Real-Time\n- SQL\n- Time Series\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n\
  - aid: apache-druid:apache-druid-rest-api\n  name: Apache Druid REST API\n  description: >-\n    Druid exposes REST APIs for Druid SQL (POST /druid/v2/sql), native JSON queries (POST /druid/v2), batch and streaming data ingestion tasks, supervisor management for Kafka/Kinesis ingestion, data segment\n    management, coordinator and overlord operations, process status, and dynamic configuration. A JDBC driver is also available for SQL access via JDBC clients.\n  humanURL: https://druid.apache.org/docs/latest/api-reference/\n  tags:\n  - Analytics\n  - Data Ingestion\n  - Datasources\n  - JSON Query\n  - Kafka\n  - OLAP\n  - REST\n  - SQL\n  - Segments\n  - Supervisors\n  properties:\n  - type: Documentation\n    url: https://druid.apache.org/docs/latest/api-reference/\n  - type: GettingStarted\n    url: https://druid.apache.org/docs/latest/tutorials/tutorial-batch-hadoop\n  - type: APIReference\n    url: https://druid.apache.org/docs/latest/api-reference/\n  - type: GitHubRepository\n \
  \   url: https://github.com/apache/druid\n  - type: Tools\n    url: https://github.com/apache/druid-operator\n    title: Kubernetes Operator\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.druid/druid-sql\n    title: JDBC Driver (Maven)\n  - type: SDK\n    url: https://pypi.org/project/pydruid/\n    title: pydruid Python Client\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-ingestion-task-schema.json\n    title: Ingestion Task\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-sql-query-request-schema.json\n    title: Sql Query Request\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-sql-query-response-schema.json\n    title: Sql Query Response\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-schema/apache-druid-supervisor-schema.json\n\
  \    title: Supervisor\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-ingestion-task-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-sql-query-request-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-sql-query-response-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-structure/apache-druid-supervisor-structure.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/json-ld/apache-druid-context.jsonld\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-ingestion-task-example.json\n\
  \  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-sql-query-request-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-sql-query-response-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/examples/apache-druid-supervisor-example.json\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: Portal\n  url: https://druid.apache.org/\n- type: Documentation\n  url: https://druid.apache.org/docs/latest/\n- type: GettingStarted\n  url: https://druid.apache.org/docs/latest/tutorials/\n- type: Blog\n  url: https://druid.apache.org/blog/\n- type: GitHubOrganization\n  url: https://github.com/apache\n- type: GitHubRepository\n  url: https://github.com/apache/druid\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/druid\n\
  - type: Features\n  data:\n  - name: Sub-Second OLAP Queries\n    description: Columnar storage with bitmap indexes, dictionary encoding, and pre-aggregation (rollup) enables sub-second queries on billions of events.\n  - name: Druid SQL API\n    description: REST endpoint for submitting standard SQL queries with ANSI SQL support, time-based filtering, and streaming response options.\n  - name: Native JSON Query API\n    description: Druid-native query format (Timeseries, TopN, GroupBy, Scan, Search) for maximum control and performance.\n  - name: Streaming Ingestion\n    description: Real-time data ingestion from Apache Kafka and Amazon Kinesis with supervisor-managed offset tracking and exactly-once semantics.\n  - name: Batch Ingestion\n    description: Parallel batch indexing tasks from local files, S3, GCS, HDFS, and other external storage systems.\n  - name: Automatic Rollup\n    description: Pre-aggregates metrics at ingestion time to reduce storage and query time, configurable\
  \ per datasource.\n  - name: Time-Based Partitioning\n    description: All data is partitioned by time interval (segments), enabling efficient time-range query pruning.\n  - name: Multi-Tenancy\n    description: Query isolation and resource management via query lanes, scheduler priorities, and row-level access control.\n- type: UseCases\n  data:\n  - name: Real-Time Event Analytics\n    description: Analyze click streams, IoT events, application logs, and user behavior data with sub-second query latency.\n  - name: Business Intelligence Dashboards\n    description: Power interactive BI dashboards with high-concurrency low-latency queries backed by Druid's columnar engine.\n  - name: Network and Security Monitoring\n    description: Ingest and analyze network flow data and security events in real time for threat detection and capacity planning.\n  - name: Ad Tech Analytics\n    description: Process advertising impression, click, and conversion events at high volume with real-time aggregation.\n\
  \  - name: Operational Analytics\n    description: Monitor application performance metrics and operational data with drilldown and filtering capabilities.\n- type: Integrations\n  data:\n  - name: Apache Kafka\n    description: KafkaSupervisor for real-time continuous ingestion from Kafka topics into Druid datasources.\n  - name: Amazon Kinesis\n    description: KinesisSupervisor for real-time data ingestion from AWS Kinesis data streams.\n  - name: Apache Hadoop / HDFS\n    description: Native Hadoop batch indexing task for bulk loading data from HDFS or MapReduce job outputs.\n  - name: Amazon S3 / GCS\n    description: Batch and streaming ingestion from object storage (S3, GCS, Azure Blob) using index tasks.\n  - name: Apache Hive\n    description: Druid-Hive integration for querying Druid datasources from HiveQL and performing joins.\n  - name: Kubernetes\n    description: Official Kubernetes operator for deploying and managing Druid clusters on Kubernetes.\n  - name: Imply (Commercial)\n\
  \    description: Imply provides a commercial managed Druid service with additional features and enterprise support.\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/vocabulary/apache-druid-vocabulary.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/apis.yml
tags:
- Analytics
- Apache
- Database
- Kafka
- OLAP
- Open Source
- Real-Time
- SQL
- Time Series
url: https://raw.githubusercontent.com/api-evangelist/apache-druid/refs/heads/main/apis.yml
use_cases:
- description: Analyze click streams, IoT events, application logs, and user behavior data with sub-second query latency.
  name: Real-Time Event Analytics
- description: Power interactive BI dashboards with high-concurrency low-latency queries backed by Druid's columnar engine.
  name: Business Intelligence Dashboards
- description: Ingest and analyze network flow data and security events in real time for threat detection and capacity planning.
  name: Network and Security Monitoring
- description: Process advertising impression, click, and conversion events at high volume with real-time aggregation.
  name: Ad Tech Analytics
- description: Monitor application performance metrics and operational data with drilldown and filtering capabilities.
  name: Operational Analytics
---
