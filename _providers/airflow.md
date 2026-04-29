---
api_count: 1
apis:
- description: The Apache Airflow REST API (v2) provides stable, backward-compatible endpoints for managing workflows (DAGs), DAG runs, task instances, connections, variables, XComs, pools, and plugins. Available at
  name: Apache Airflow API
  slug: airflow
capabilities:
- description: Unified workflow capability for managing Apache Airflow pipelines — DAGs, DAG runs, task monitoring, variables, and connections. Used by data engineers and platform teams for orchestrating data pipeli
  name: Apache Airflow Workflow Orchestration
  slug: workflow-orchestration
common:
- title: ''
  type: Portal
  url: https://airflow.apache.org
- title: ''
  type: GettingStarted
  url: https://airflow.apache.org/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/airflow
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/airflow
- title: ''
  type: Blog
  url: https://airflow.apache.org/blog/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/airflow
- title: ''
  type: ChangeLog
  url: https://airflow.apache.org/docs/apache-airflow/stable/release_notes.html
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/projects/AIRFLOW
- title: Docker Image
  type: SDK
  url: https://hub.docker.com/r/apache/airflow
- title: Helm Chart
  type: SDK
  url: https://artifacthub.io/packages/helm/airflow-helm/airflow
- title: Airflow Spectral Rules
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/rules/airflow-spectral-rules.yml
- title: Workflow Orchestration
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/capabilities/workflow-orchestration.yaml
- title: Airflow Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/vocabulary/airflow-vocabulary.yaml
created: '2026-01-02'
description: Apache Airflow is an open-source platform to programmatically author, schedule, and monitor workflows. Airflow uses directed acyclic graphs (DAGs) to manage workflow orchestration. The Airflow REST API provides programmatic access to DAGs, DAG runs, tasks, connections, variables, pools, and monitoring for both Airflow OSS and cloud-managed deployments.
features:
- description: Define workflows as Python code using Directed Acyclic Graphs (DAGs).
  name: DAG Authoring
- description: Programmatically generate DAGs and tasks based on configuration or data.
  name: Dynamic DAG Generation
- description: Pre-built operators for databases, cloud services, APIs, and data tools.
  name: Rich Operator Library
- description: Stable REST API for programmatic management of DAGs, runs, tasks, and infrastructure.
  name: REST API v2
- description: Built-in web interface for monitoring, triggering, and debugging workflows.
  name: Web UI
- description: Robust scheduler with support for CRON and timed triggers.
  name: Scheduler
- description: Plugin system and provider packages for extending functionality.
  name: Extensible
- description: Provider packages for AWS, GCP, Azure, and other cloud platforms.
  name: Multi-Cloud Support
- description: Available as managed service from AWS (MWAA), GCP (Cloud Composer), and Astronomer.
  name: Managed Services
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Run Spark jobs from Airflow DAGs.
  name: Apache Spark
- description: Orchestrate dbt model runs via the dbt operator.
  name: dbt
- description: Run tasks in Kubernetes pods with the KubernetesPodOperator.
  name: Kubernetes
- description: Provider package for S3, Redshift, EMR, Lambda, and other AWS services.
  name: AWS
- description: Provider package for BigQuery, Dataflow, GCS, and other GCP services.
  name: Google Cloud
- description: Provider package for Azure Data Factory, Blob Storage, and other Azure services.
  name: Azure
- description: SnowflakeOperator for running SQL in Snowflake data warehouse.
  name: Snowflake
- description: Trigger Airbyte syncs from Airflow DAGs.
  name: Airbyte
jsonld:
- class_count: 128
  name: Airflow Context
  property_count: 304
  slug: airflow-context
layout: provider
modified: '2026-04-19'
name: Apache Airflow
rules:
- name: Apache Airflow API Rules
  rule_count: 24
  severity_counts:
    error: 8
    hint: 0
    info: 9
    warn: 7
  slug: airflow-spectral-rules
skills: []
slug: airflow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: airflow\nname: Apache Airflow\ndescription: >-\n  Apache Airflow is an open-source platform to programmatically author, schedule, and monitor workflows. Airflow uses directed acyclic graphs (DAGs) to manage workflow orchestration. The Airflow REST API\n  provides programmatic access to DAGs, DAG runs, tasks, connections, variables, pools, and monitoring for both Airflow OSS and cloud-managed deployments.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Workflow Orchestration\n- Data Pipeline\n- Open Source\n- Apache\n- DAG\n- Scheduling\n- ETL\n- Data Engineering\ncreated: '2026-01-02'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: airflow:airflow\n  name: Apache Airflow API\n  description: >-\n    The Apache Airflow REST API (v2) provides stable, backward-compatible\
  \ endpoints for managing workflows (DAGs), DAG runs, task instances, connections, variables, XComs, pools, and plugins. Available\n    at /api/v2 on any Airflow deployment.\n  humanURL: 'https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html'\n  tags:\n  - Workflow Orchestration\n  - DAG\n  - Scheduling\n  - Data Pipeline\n  - Open Source\n  properties:\n  - url: https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html\n    type: Documentation\n  - url: https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html\n    type: APIReference\n  - url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/openapi/airflow-openapi.yml\n    type: OpenAPI\n  - url: https://airflow.apache.org/docs/apache-airflow/stable/security/api.html\n    type: Authentication\n  - url: https://pypi.org/project/apache-airflow/\n    type: SDK\n    title: PyPI Package\n  - url: https://pypi.org/project/apache-airflow-client/\n    type:\
  \ SDK\n    title: Python Client SDK\n  - url: https://github.com/apache/airflow\n    type: SDK\n    title: GitHub Repository\n  baseURL: http://localhost:8080/api/v2\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- url: https://airflow.apache.org\n  type: Portal\n- url: https://airflow.apache.org/docs/\n  type: GettingStarted\n- url: https://github.com/apache/airflow\n  type: GitHubOrganization\n- url: https://github.com/apache/airflow\n  type: GitHubRepository\n- url: https://airflow.apache.org/blog/\n  type: Blog\n- url: https://stackoverflow.com/questions/tagged/airflow\n  type: StackOverflow\n- url: https://airflow.apache.org/docs/apache-airflow/stable/release_notes.html\n  type: ChangeLog\n- url: https://issues.apache.org/jira/projects/AIRFLOW\n  type: IssueTracker\n- url: https://hub.docker.com/r/apache/airflow\n  type: SDK\n  title: Docker Image\n- url: https://artifacthub.io/packages/helm/airflow-helm/airflow\n  type: SDK\n  title: Helm Chart\n- type: Features\n\
  \  data:\n  - name: DAG Authoring\n    description: Define workflows as Python code using Directed Acyclic Graphs (DAGs).\n  - name: Dynamic DAG Generation\n    description: Programmatically generate DAGs and tasks based on configuration or data.\n  - name: Rich Operator Library\n    description: Pre-built operators for databases, cloud services, APIs, and data tools.\n  - name: REST API v2\n    description: Stable REST API for programmatic management of DAGs, runs, tasks, and infrastructure.\n  - name: Web UI\n    description: Built-in web interface for monitoring, triggering, and debugging workflows.\n  - name: Scheduler\n    description: Robust scheduler with support for CRON and timed triggers.\n  - name: Extensible\n    description: Plugin system and provider packages for extending functionality.\n  - name: Multi-Cloud Support\n    description: Provider packages for AWS, GCP, Azure, and other cloud platforms.\n  - name: Managed Services\n    description: Available as managed service\
  \ from AWS (MWAA), GCP (Cloud Composer), and Astronomer.\n- type: UseCases\n  data:\n  - name: ETL Pipeline Orchestration\n    description: Schedule and monitor extract, transform, load data pipelines.\n  - name: ML Pipeline Management\n    description: Orchestrate machine learning training, evaluation, and deployment workflows.\n  - name: Data Quality Checks\n    description: Schedule data validation and quality check jobs.\n  - name: Report Generation\n    description: Automate periodic report generation and distribution.\n  - name: API Orchestration\n    description: Coordinate calls to multiple APIs in complex workflows.\n  - name: Database Operations\n    description: Schedule database maintenance, migrations, and backup jobs.\n- type: Integrations\n  data:\n  - name: Apache Spark\n    description: Run Spark jobs from Airflow DAGs.\n  - name: dbt\n    description: Orchestrate dbt model runs via the dbt operator.\n  - name: Kubernetes\n    description: Run tasks in Kubernetes pods\
  \ with the KubernetesPodOperator.\n  - name: AWS\n    description: Provider package for S3, Redshift, EMR, Lambda, and other AWS services.\n  - name: Google Cloud\n    description: Provider package for BigQuery, Dataflow, GCS, and other GCP services.\n  - name: Azure\n    description: Provider package for Azure Data Factory, Blob Storage, and other Azure services.\n  - name: Snowflake\n    description: SnowflakeOperator for running SQL in Snowflake data warehouse.\n  - name: Airbyte\n    description: Trigger Airbyte syncs from Airflow DAGs.\n- url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/rules/airflow-spectral-rules.yml\n  type: SpectralRules\n  title: Airflow Spectral Rules\n- url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/capabilities/workflow-orchestration.yaml\n  type: NaftikoCapability\n  title: Workflow Orchestration\n- url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/vocabulary/airflow-vocabulary.yaml\n\
  \  type: Vocabulary\n  title: Airflow Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/apis.yml
tags:
- Workflow Orchestration
- Data Pipeline
- Open Source
- Apache
- DAG
- Scheduling
- ETL
- Data Engineering
url: https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/apis.yml
use_cases:
- description: Schedule and monitor extract, transform, load data pipelines.
  name: ETL Pipeline Orchestration
- description: Orchestrate machine learning training, evaluation, and deployment workflows.
  name: ML Pipeline Management
- description: Schedule data validation and quality check jobs.
  name: Data Quality Checks
- description: Automate periodic report generation and distribution.
  name: Report Generation
- description: Coordinate calls to multiple APIs in complex workflows.
  name: API Orchestration
- description: Schedule database maintenance, migrations, and backup jobs.
  name: Database Operations
---
