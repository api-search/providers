---
api_count: 5
apis:
- description: REST API for monitoring Spark applications, accessing cluster information, and managing Spark jobs through the Spark UI backend. Exposes endpoints for applications, jobs, stages, tasks, storage, envir
  name: Apache Spark REST API
  slug: apache-spark-rest-api
- description: Spark module for structured data processing with DataFrame and Dataset APIs. Provides a SQL interface and supports various data sources including Parquet, ORC, JSON, CSV, JDBC, Hive, and Delta Lake. T
  name: Apache Spark SQL API
  slug: apache-spark-sql-api
- description: Scalable, high-throughput, fault-tolerant stream processing of live data streams. Supports Structured Streaming (the newer DStream-based API) with exactly-once semantics, continuous processing mode, a
  name: Apache Spark Streaming API
  slug: apache-spark-streaming-api
- description: Spark's scalable machine learning library consisting of common learning algorithms and utilities, including classification, regression, clustering, collaborative filtering, dimensionality reduction, a
  name: Apache Spark MLlib API
  slug: apache-spark-mllib-api
- description: Spark API for graphs and graph-parallel computation with a collection of graph algorithms and builders, including PageRank, Connected Components, Triangle Counting, and shortest paths.
  name: Apache Spark GraphX API
  slug: apache-spark-graphx-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/spark
- title: ''
  type: Portal
  url: https://spark.apache.org/
- title: ''
  type: Documentation
  url: https://spark.apache.org/docs/latest/
- title: ''
  type: GettingStarted
  url: https://spark.apache.org/docs/latest/quick-start.html
- title: ''
  type: Blog
  url: https://spark.apache.org/news/
- title: ''
  type: Support
  url: https://spark.apache.org/community.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/apache-spark
- title: PySpark (Python)
  type: SDK
  url: https://pypi.org/project/pyspark/
- title: Maven (Scala/Java)
  type: SDK
  url: https://search.maven.org/search?q=g:org.apache.spark
created: '2024-01-01'
description: Apache Spark is a unified analytics engine for large-scale data processing. It provides high-level APIs in Java, Scala, Python, and R, and an optimized engine that supports general execution graphs. Spark offers a comprehensive suite of APIs for batch processing, SQL queries, streaming analytics, machine learning, and graph computation, governed by the Apache Software Foundation.
features:
- description: Single engine for batch, streaming, SQL, ML, and graph processing workloads.
  name: Unified Analytics Engine
- description: Optimized execution plans with Catalyst optimizer and DAG scheduling.
  name: Lazy Evaluation and DAG Execution
- description: Up to 100x faster than Hadoop MapReduce for iterative algorithms via in-memory caching.
  name: In-Memory Processing
- description: Unified streaming and batch processing with exactly-once semantics and Kafka integration.
  name: Structured Streaming
- description: High-level APIs in Scala, Java, Python (PySpark), and R (SparkR).
  name: Multi-Language Support
- description: ACID transactions, schema evolution, and time travel for data lakes.
  name: Delta Lake Integration
- description: Native Kubernetes scheduling for cloud-native deployment of Spark workloads.
  name: Kubernetes Native
image: https://spark.apache.org/images/spark-logo-trademark.png
integrations:
- description: HDFS storage, YARN cluster manager, and Hadoop ecosystem integration.
  name: Apache Hadoop
- description: Structured Streaming source and sink for real-time event processing.
  name: Apache Kafka
- description: Open-source storage layer with ACID transactions for data lakes.
  name: Delta Lake
- description: Open table format for huge analytic datasets on cloud storage.
  name: Apache Iceberg
- description: Hive metastore integration for table catalog and metadata management.
  name: Apache Hive
- description: Native Kubernetes scheduling for cloud-native Spark deployments.
  name: Kubernetes
- description: Workflow orchestration for scheduling and managing Spark jobs.
  name: Apache Airflow
layout: provider
modified: '2026-04-19'
name: Apache Spark
skills: []
slug: apache-spark
solutions: []
tags:
- Analytics
- Big Data
- Distributed Computing
- Machine Learning
- Open Source
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/apache-spark/refs/heads/main/apis.yml
use_cases:
- description: Extract, transform, and load petabytes of data across distributed clusters.
  name: Large-Scale ETL
- description: Streaming analytics on live event data with sub-second latency.
  name: Real-Time Analytics
- description: Distributed ML training and feature engineering at scale with MLlib.
  name: Machine Learning Pipelines
- description: Query and transform data stored in cloud object stores and HDFS.
  name: Data Lake Processing
- description: Interactive SQL queries on structured and semi-structured data at scale.
  name: Interactive SQL Analytics
---
