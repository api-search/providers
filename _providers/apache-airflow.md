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
source_yaml: "aid: apache-airflow\nname: Apache Airflow\ndescription: >-\n  Apache Airflow is an open-source platform to programmatically author, schedule, and monitor workflows, developed by the Apache Software Foundation. It allows you to define workflows as Directed Acyclic Graphs (DAGs) in Python code, making them maintainable, versionable, testable, and collaborative. Airflow provides a stable REST API for managing DAGs, DAG runs, tasks, connections, variables, pools, and users, along with a web-based UI for monitoring and managing pipeline execution.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://airflow.apache.org/images/feature-image.png\ntags:\n  - Apache\n  - DAG\n  - Data Pipeline\n  - ETL\n  - Open Source\n  - Orchestration\n  - Python\n  - Scheduling\n  - Workflow\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-airflow/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ apache-airflow:apache-airflow-rest-api\n    name: Apache Airflow REST API\n    description: >-\n      The stable public REST API for interacting with Apache Airflow programmatically, allowing management of DAGs, DAG runs, task instances, connections, variables, pools, roles, users, and monitoring resources.\n    humanURL: https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html\n    baseURL: http://localhost:8080/api/v1\n    tags:\n      - DAGs\n      - REST\n      - Tasks\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html\n      - type: OpenAPI\n        url: openapi/apache-airflow-openapi.yaml\n      - type: Authentication\n        url: https://airflow.apache.org/docs/apache-airflow/stable/security/api.html\n      - type: ChangeLog\n        url: https://airflow.apache.org/docs/apache-airflow/stable/release_notes.html\n  - aid: apache-airflow:apache-airflow-experimental-api\n\
  \    name: Apache Airflow Experimental API (Deprecated)\n    description: >-\n      The experimental API that preceded the stable REST API. This is deprecated and should not be used for new implementations.\n    humanURL: https://airflow.apache.org/docs/apache-airflow/stable/deprecated-rest-api-ref.html\n    baseURL: http://localhost:8080/api/experimental\n    tags:\n      - Deprecated\n      - Legacy\n      - REST\n    properties:\n      - type: Documentation\n        url: https://airflow.apache.org/docs/apache-airflow/stable/deprecated-rest-api-ref.html\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/airflow\n  - type: Documentation\n    url: https://airflow.apache.org/\n  - type: GettingStarted\n    url: https://airflow.apache.org/docs/apache-airflow/stable/start.html\n  - type: Tutorials\n    url: https://airflow.apache.org/docs/apache-airflow/stable/tutorial/index.html\n  - type: SDK\n    url:\
  \ https://pypi.org/project/apache-airflow/\n    title: Python Package (PyPI)\n  - type: SDK\n    url: https://hub.docker.com/r/apache/airflow\n    title: Docker Image\n  - type: Security\n    url: https://airflow.apache.org/docs/apache-airflow/stable/security/\n  - type: Blog\n    url: https://airflow.apache.org/blog/\n  - type: Support\n    url: https://airflow.apache.org/community/\n  - type: ChangeLog\n    url: https://airflow.apache.org/docs/apache-airflow/stable/release_notes.html\n  - type: SpectralRules\n    url: rules/apache-airflow-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-airflow-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/airflow-orchestration.yaml\n  - type: Features\n    data:\n      - name: DAG-as-Code\n        description: Define workflows as Python code (Directed Acyclic Graphs) for version control, testing, and collaboration.\n      - name: Stable REST API\n        description: Full-featured REST API for programmatic management\
  \ of DAGs, runs, tasks, connections, variables, pools, and users.\n      - name: Dynamic Pipeline Generation\n        description: Generate DAGs dynamically using Python, supporting complex conditional and parametric pipelines.\n      - name: Extensible Providers\n        description: Rich ecosystem of provider packages for integrating with AWS, GCP, Azure, databases, and hundreds of external services.\n      - name: Rich Web UI\n        description: Browser-based dashboard for monitoring DAG runs, task statuses, logs, and Gantt charts.\n      - name: Resource Pools\n        description: Control concurrency and resource allocation across tasks using configurable pools.\n      - name: Cross-DAG Dependencies\n        description: Define dependencies between DAGs using sensors, dataset-driven scheduling, and external task sensors.\n      - name: Pluggable Executors\n        description: Supports Sequential, Local, Celery, Kubernetes, and DASK executors for flexible deployment.\n      - name:\
  \ SLA Monitoring\n        description: Define and track Service Level Agreements on task and DAG completion times.\n      - name: Variable and Connection Management\n        description: Centrally manage environment-specific configuration via Airflow variables and connections.\n  - type: UseCases\n    data:\n      - name: ETL Pipeline Orchestration\n        description: Schedule and manage extract, transform, load pipelines with dependency management and retry logic.\n      - name: Machine Learning Workflows\n        description: Orchestrate ML training, validation, and deployment pipelines with data dependency tracking.\n      - name: Data Warehouse Loading\n        description: Coordinate data ingestion from multiple sources into data warehouses like BigQuery, Redshift, and Snowflake.\n      - name: Batch Report Generation\n        description: Schedule periodic batch reporting jobs with email notification on completion or failure.\n      - name: Multi-Cloud Data Movement\n        description:\
  \ Move data between AWS, GCP, and Azure using provider integrations with dependency control.\n      - name: CI/CD Pipeline Orchestration\n        description: Trigger and monitor software deployment pipelines with upstream/downstream task dependencies.\n  - type: Integrations\n    data:\n      - name: Apache Spark\n        description: Native Spark submit and Livy operator integration for distributed data processing.\n      - name: Google Cloud\n        description: Comprehensive GCP provider for BigQuery, Cloud Storage, Dataflow, Dataproc, and more.\n      - name: Amazon Web Services\n        description: AWS provider for S3, Redshift, EMR, Glue, Lambda, and other services.\n      - name: Microsoft Azure\n        description: Azure provider for Blob Storage, Data Factory, HDInsight, and Databricks.\n      - name: dbt\n        description: dbt operator for running dbt transformations within Airflow pipelines.\n      - name: Kubernetes\n        description: KubernetesPodOperator for running\
  \ tasks in isolated Kubernetes pods.\n      - name: Docker\n        description: DockerOperator for running tasks in Docker containers with isolated environments.\n      - name: Apache Kafka\n        description: Kafka producers and consumers as Airflow tasks via the Kafka provider.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-airflow/refs/heads/main/apis.yml
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
