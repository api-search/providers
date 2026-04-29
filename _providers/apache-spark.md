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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-spark\nname: Apache Spark\ndescription: >-\n  Apache Spark is a unified analytics engine for large-scale data processing. It provides\n  high-level APIs in Java, Scala, Python, and R, and an optimized engine that supports\n  general execution graphs. Spark offers a comprehensive suite of APIs for batch processing,\n  SQL queries, streaming analytics, machine learning, and graph computation, governed by the\n  Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://spark.apache.org/images/spark-logo-trademark.png\ntags:\n  - Analytics\n  - Big Data\n  - Distributed Computing\n  - Machine Learning\n  - Open Source\n  - Streaming\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-spark/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-spark:apache-spark-rest-api\n    name: Apache Spark REST API\n    description: >-\n      REST API for\
  \ monitoring Spark applications, accessing cluster information, and managing\n      Spark jobs through the Spark UI backend. Exposes endpoints for applications, jobs, stages,\n      tasks, storage, environment, executors, and streaming statistics on port 4040 (or 18080\n      for Spark History Server).\n    humanURL: https://spark.apache.org/docs/latest/monitoring.html#rest-api\n    tags:\n      - Jobs\n      - Metrics\n      - Monitoring\n      - Stages\n    properties:\n      - type: Documentation\n        url: https://spark.apache.org/docs/latest/monitoring.html#rest-api\n\n  - aid: apache-spark:apache-spark-sql-api\n    name: Apache Spark SQL API\n    description: >-\n      Spark module for structured data processing with DataFrame and Dataset APIs. Provides a\n      SQL interface and supports various data sources including Parquet, ORC, JSON, CSV, JDBC,\n      Hive, and Delta Lake. The Spark SQL API supports Scala, Python, Java, and R bindings.\n    humanURL: https://spark.apache.org/docs/latest/sql-programming-guide.html\n\
  \    tags:\n      - DataFrames\n      - SQL\n      - Structured Data\n    properties:\n      - type: Documentation\n        url: https://spark.apache.org/docs/latest/sql-programming-guide.html\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/scala/org/apache/spark/sql/index.html\n        title: Scala API Reference\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/index.html\n        title: Python API Reference\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/java/index.html?org/apache/spark/sql/package-summary.html\n        title: Java API Reference\n\n  - aid: apache-spark:apache-spark-streaming-api\n    name: Apache Spark Streaming API\n    description: >-\n      Scalable, high-throughput, fault-tolerant stream processing of live data streams. Supports\n      Structured Streaming (the newer DStream-based API) with exactly-once semantics, continuous\n      processing mode, and integration\
  \ with Kafka, Kinesis, HDFS, and other sources.\n    humanURL: https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html\n    tags:\n      - Data Processing\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/scala/org/apache/spark/streaming/index.html\n        title: Scala Streaming API\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/python/reference/pyspark.streaming/index.html\n        title: Python Streaming API\n\n  - aid: apache-spark:apache-spark-mllib-api\n    name: Apache Spark MLlib API\n    description: >-\n      Spark's scalable machine learning library consisting of common learning algorithms and\n      utilities, including classification, regression, clustering, collaborative filtering,\n      dimensionality reduction, and feature\
  \ engineering. Supports pipeline-based ML workflows\n      through the spark.ml package.\n    humanURL: https://spark.apache.org/docs/latest/ml-guide.html\n    tags:\n      - Algorithms\n      - Data Science\n      - Machine Learning\n      - ML\n    properties:\n      - type: Documentation\n        url: https://spark.apache.org/docs/latest/ml-guide.html\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/scala/org/apache/spark/ml/index.html\n        title: Scala MLlib API\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/python/reference/pyspark.ml.html\n        title: Python MLlib API\n\n  - aid: apache-spark:apache-spark-graphx-api\n    name: Apache Spark GraphX API\n    description: >-\n      Spark API for graphs and graph-parallel computation with a collection of graph algorithms\n      and builders, including PageRank, Connected Components, Triangle Counting, and shortest paths.\n    humanURL: https://spark.apache.org/docs/latest/graphx-programming-guide.html\n\
  \    tags:\n      - Analytics\n      - Graph Processing\n      - Graphs\n    properties:\n      - type: Documentation\n        url: https://spark.apache.org/docs/latest/graphx-programming-guide.html\n      - type: SDK\n        url: https://spark.apache.org/docs/latest/api/scala/org/apache/spark/graphx/index.html\n        title: Scala GraphX API\n\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/spark\n  - type: Portal\n    url: https://spark.apache.org/\n  - type: Documentation\n    url: https://spark.apache.org/docs/latest/\n  - type: GettingStarted\n    url: https://spark.apache.org/docs/latest/quick-start.html\n  - type: Blog\n    url: https://spark.apache.org/news/\n  - type: Support\n    url: https://spark.apache.org/community.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/apache-spark\n  - type: SDK\n    url: https://pypi.org/project/pyspark/\n\
  \    title: PySpark (Python)\n  - type: SDK\n    url: https://search.maven.org/search?q=g:org.apache.spark\n    title: Maven (Scala/Java)\n  - type: Features\n    data:\n      - name: Unified Analytics Engine\n        description: Single engine for batch, streaming, SQL, ML, and graph processing workloads.\n      - name: Lazy Evaluation and DAG Execution\n        description: Optimized execution plans with Catalyst optimizer and DAG scheduling.\n      - name: In-Memory Processing\n        description: Up to 100x faster than Hadoop MapReduce for iterative algorithms via in-memory caching.\n      - name: Structured Streaming\n        description: Unified streaming and batch processing with exactly-once semantics and Kafka integration.\n      - name: Multi-Language Support\n        description: High-level APIs in Scala, Java, Python (PySpark), and R (SparkR).\n      - name: Delta Lake Integration\n        description: ACID transactions, schema evolution, and time travel for data lakes.\n\
  \      - name: Kubernetes Native\n        description: Native Kubernetes scheduling for cloud-native deployment of Spark workloads.\n  - type: UseCases\n    data:\n      - name: Large-Scale ETL\n        description: Extract, transform, and load petabytes of data across distributed clusters.\n      - name: Real-Time Analytics\n        description: Streaming analytics on live event data with sub-second latency.\n      - name: Machine Learning Pipelines\n        description: Distributed ML training and feature engineering at scale with MLlib.\n      - name: Data Lake Processing\n        description: Query and transform data stored in cloud object stores and HDFS.\n      - name: Interactive SQL Analytics\n        description: Interactive SQL queries on structured and semi-structured data at scale.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop\n        description: HDFS storage, YARN cluster manager, and Hadoop ecosystem integration.\n      - name: Apache Kafka\n        description:\
  \ Structured Streaming source and sink for real-time event processing.\n      - name: Delta Lake\n        description: Open-source storage layer with ACID transactions for data lakes.\n      - name: Apache Iceberg\n        description: Open table format for huge analytic datasets on cloud storage.\n      - name: Apache Hive\n        description: Hive metastore integration for table catalog and metadata management.\n      - name: Kubernetes\n        description: Native Kubernetes scheduling for cloud-native Spark deployments.\n      - name: Apache Airflow\n        description: Workflow orchestration for scheduling and managing Spark jobs.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-spark/refs/heads/main/apis.yml
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
