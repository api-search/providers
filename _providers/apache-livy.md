---
api_count: 1
apis:
- description: The Livy REST API provides endpoints for creating and managing interactive Spark sessions, submitting batch Spark jobs, executing code statements (Python, Scala, R, SQL), and retrieving job results an
  name: Apache Livy REST API
  slug: rest-api
capabilities:
- description: Workflow capability for data engineers and data scientists to manage interactive Spark sessions and submit batch Spark jobs via Apache Livy REST API.
  name: Apache Livy Spark Job Management
  slug: spark-job-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/incubator-livy
- title: ''
  type: Documentation
  url: https://livy.apache.org/docs/latest/
- title: ''
  type: GettingStarted
  url: https://livy.apache.org/get-started/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://livy.apache.org/download/
- title: ''
  type: SpectralRules
  url: rules/apache-livy-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-livy-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/spark-job-management.yaml
created: '2026-03-16'
description: Apache Livy is a service that enables easy interaction with a Spark cluster over a REST interface. It allows submitting Spark jobs or snippets of Spark code, retrieving results synchronously or asynchronously, and managing Spark contexts across multiple users. Licensed under Apache 2.0.
features:
- description: Create persistent Spark contexts for interactive code execution in Python, Scala, R, and SQL.
  name: Interactive Spark Sessions
- description: Submit batch Spark jobs without creating an interactive session.
  name: Batch Job Submission
- description: Execute code in PySpark, Spark (Scala), SparkR, and SQL.
  name: Multi-Language Support
- description: Proxy user support for multi-tenant Spark cluster access.
  name: Multi-User Impersonation
- description: Submit jobs and poll for results asynchronously.
  name: Asynchronous Execution
- description: Retrieve driver and executor logs for debugging.
  name: Log Access
- description: Simple HTTP REST API for Spark cluster interaction without native clients.
  name: REST Interface
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Livy requires a Spark cluster and acts as the REST gateway to Spark.
  name: Apache Spark
- description: Zeppelin notebook backend using Livy for distributed Spark execution.
  name: Apache Zeppelin
- description: Jupyter sparkmagic extension uses Livy for remote Spark kernel access.
  name: Jupyter Notebook
- description: Airflow LivyOperator for submitting Spark batch jobs from DAGs.
  name: Apache Airflow
- description: Livy is available as an EMR application for REST-based Spark access.
  name: Amazon EMR
jsonld:
- class_count: 12
  name: Apache Livy Rest Api Context
  property_count: 31
  slug: apache-livy-rest-api-context
layout: provider
modified: '2026-04-19'
name: Apache Livy
rules:
- name: Apache Livy API Rules
  rule_count: 13
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 3
  slug: apache-livy-spectral-rules
skills: []
slug: apache-livy
solutions: []
tags:
- Big Data
- Interactive Computing
- Open Source
- REST
- Spark
url: https://raw.githubusercontent.com/api-evangelist/apache-livy/refs/heads/main/apis.yml
use_cases:
- description: Power Jupyter, Zeppelin, and other notebooks with Spark backends via Livy.
  name: Notebook Integration
- description: Submit Spark batch jobs from orchestration tools like Airflow and Oozie.
  name: Data Engineering Pipelines
- description: Execute ad-hoc Spark code for exploratory data analysis.
  name: Interactive Data Exploration
- description: Enable multiple users to share a Spark cluster with isolation via Livy sessions.
  name: Multi-Tenant Spark Access
---
