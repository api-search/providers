---
api_count: 2
apis:
- description: The stable public REST API for interacting with Apache Airflow programmatically, allowing management of DAGs, DAG runs, task instances, connections, variables, pools, roles, users, and monitoring reso
  name: Apache Airflow REST API
  slug: apache-airflow-rest-api
- description: The experimental API that preceded the stable REST API. This is deprecated and should not be used for new implementations.
  name: Apache Airflow Experimental API (Deprecated)
  slug: apache-airflow-experimental-api
capabilities:
- description: Unified capability for managing and monitoring Apache Airflow DAGs, runs, tasks, connections, and variables. Used by data engineers and platform operators to orchestrate data pipelines.
  name: Apache Airflow Workflow Orchestration
  slug: airflow-orchestration
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/airflow
- title: ''
  type: Documentation
  url: https://airflow.apache.org/
- title: ''
  type: GettingStarted
  url: https://airflow.apache.org/docs/apache-airflow/stable/start.html
- title: ''
  type: Tutorials
  url: https://airflow.apache.org/docs/apache-airflow/stable/tutorial/index.html
- title: Python Package (PyPI)
  type: SDK
  url: https://pypi.org/project/apache-airflow/
- title: Docker Image
  type: SDK
  url: https://hub.docker.com/r/apache/airflow
- title: ''
  type: Security
  url: https://airflow.apache.org/docs/apache-airflow/stable/security/
- title: ''
  type: Blog
  url: https://airflow.apache.org/blog/
- title: ''
  type: Support
  url: https://airflow.apache.org/community/
- title: ''
  type: ChangeLog
  url: https://airflow.apache.org/docs/apache-airflow/stable/release_notes.html
- title: ''
  type: SpectralRules
  url: rules/apache-airflow-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-airflow-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/airflow-orchestration.yaml
created: '2024-01-15'
description: Apache Airflow is an open-source platform to programmatically author, schedule, and monitor workflows, developed by the Apache Software Foundation. It allows you to define workflows as Directed Acyclic Graphs (DAGs) in Python code, making them maintainable, versionable, testable, and collaborative. Airflow provides a stable REST API for managing DAGs, DAG runs, tasks, connections, variables, pools, and users, along with a web-based UI for monitoring and managing pipeline execution.
features:
- description: Define workflows as Python code (Directed Acyclic Graphs) for version control, testing, and collaboration.
  name: DAG-as-Code
- description: Full-featured REST API for programmatic management of DAGs, runs, tasks, connections, variables, pools, and users.
  name: Stable REST API
- description: Generate DAGs dynamically using Python, supporting complex conditional and parametric pipelines.
  name: Dynamic Pipeline Generation
- description: Rich ecosystem of provider packages for integrating with AWS, GCP, Azure, databases, and hundreds of external services.
  name: Extensible Providers
- description: Browser-based dashboard for monitoring DAG runs, task statuses, logs, and Gantt charts.
  name: Rich Web UI
- description: Control concurrency and resource allocation across tasks using configurable pools.
  name: Resource Pools
- description: Define dependencies between DAGs using sensors, dataset-driven scheduling, and external task sensors.
  name: Cross-DAG Dependencies
- description: Supports Sequential, Local, Celery, Kubernetes, and DASK executors for flexible deployment.
  name: Pluggable Executors
- description: Define and track Service Level Agreements on task and DAG completion times.
  name: SLA Monitoring
- description: Centrally manage environment-specific configuration via Airflow variables and connections.
  name: Variable and Connection Management
image: https://airflow.apache.org/images/feature-image.png
integrations:
- description: Native Spark submit and Livy operator integration for distributed data processing.
  name: Apache Spark
- description: Comprehensive GCP provider for BigQuery, Cloud Storage, Dataflow, Dataproc, and more.
  name: Google Cloud
- description: AWS provider for S3, Redshift, EMR, Glue, Lambda, and other services.
  name: Amazon Web Services
- description: Azure provider for Blob Storage, Data Factory, HDInsight, and Databricks.
  name: Microsoft Azure
- description: dbt operator for running dbt transformations within Airflow pipelines.
  name: dbt
- description: KubernetesPodOperator for running tasks in isolated Kubernetes pods.
  name: Kubernetes
- description: DockerOperator for running tasks in Docker containers with isolated environments.
  name: Docker
- description: Kafka producers and consumers as Airflow tasks via the Kafka provider.
  name: Apache Kafka
jsonld:
- class_count: 88
  name: Apache Airflow Context
  property_count: 197
  slug: apache-airflow-context
layout: provider
modified: '2026-04-19'
name: Apache Airflow
rules:
- name: Apache Airflow API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 2
    warn: 9
  slug: apache-airflow-spectral-rules
skills: []
slug: apache-airflow
solutions: []
tags:
- Apache
- DAG
- Data Pipeline
- ETL
- Open Source
- Orchestration
- Python
- Scheduling
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/apache-airflow/refs/heads/main/apis.yml
use_cases:
- description: Schedule and manage extract, transform, load pipelines with dependency management and retry logic.
  name: ETL Pipeline Orchestration
- description: Orchestrate ML training, validation, and deployment pipelines with data dependency tracking.
  name: Machine Learning Workflows
- description: Coordinate data ingestion from multiple sources into data warehouses like BigQuery, Redshift, and Snowflake.
  name: Data Warehouse Loading
- description: Schedule periodic batch reporting jobs with email notification on completion or failure.
  name: Batch Report Generation
- description: Move data between AWS, GCP, and Azure using provider integrations with dependency control.
  name: Multi-Cloud Data Movement
- description: Trigger and monitor software deployment pipelines with upstream/downstream task dependencies.
  name: CI/CD Pipeline Orchestration
---
