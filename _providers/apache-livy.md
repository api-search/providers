---
api_count: 1
api_specs:
- filename: apache-livy-rest-api.yaml
  format: yaml
  label: Apache Livy REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-livy/refs/heads/main/openapi/apache-livy-rest-api.yaml
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
source_filename: apis.yml
source_yaml: "aid: apache-livy\nname: Apache Livy\ndescription: >-\n  Apache Livy is a service that enables easy interaction with a Spark cluster over a REST interface. It allows submitting Spark jobs or snippets of Spark code, retrieving results synchronously or asynchronously, and managing Spark contexts across multiple users. Licensed under Apache 2.0.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Big Data\n  - Interactive Computing\n  - Open Source\n  - REST\n  - Spark\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-livy/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-livy:rest-api\n    name: Apache Livy REST API\n    description: >-\n      The Livy REST API provides endpoints for creating and managing interactive Spark sessions, submitting batch Spark jobs, executing code statements (Python,\
  \ Scala, R, SQL), and retrieving job results and logs.\n    humanURL: https://livy.apache.org/docs/latest/rest-api.html\n    tags:\n      - Batch Jobs\n      - REST\n      - Sessions\n      - Spark\n    properties:\n      - type: Documentation\n        url: https://livy.apache.org/docs/latest/rest-api.html\n      - type: OpenAPI\n        url: openapi/apache-livy-rest-api.yaml\n\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/incubator-livy\n  - type: Documentation\n    url: https://livy.apache.org/docs/latest/\n  - type: GettingStarted\n    url: https://livy.apache.org/get-started/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Versioning\n    url: https://livy.apache.org/download/\n  - type: SpectralRules\n    url: rules/apache-livy-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-livy-vocabulary.yaml\n  - type: NaftikoCapability\n\
  \    url: capabilities/spark-job-management.yaml\n  - type: Features\n    data:\n      - name: Interactive Spark Sessions\n        description: Create persistent Spark contexts for interactive code execution in Python, Scala, R, and SQL.\n      - name: Batch Job Submission\n        description: Submit batch Spark jobs without creating an interactive session.\n      - name: Multi-Language Support\n        description: Execute code in PySpark, Spark (Scala), SparkR, and SQL.\n      - name: Multi-User Impersonation\n        description: Proxy user support for multi-tenant Spark cluster access.\n      - name: Asynchronous Execution\n        description: Submit jobs and poll for results asynchronously.\n      - name: Log Access\n        description: Retrieve driver and executor logs for debugging.\n      - name: REST Interface\n        description: Simple HTTP REST API for Spark cluster interaction without native clients.\n  - type: UseCases\n    data:\n      - name: Notebook Integration\n\
  \        description: Power Jupyter, Zeppelin, and other notebooks with Spark backends via Livy.\n      - name: Data Engineering Pipelines\n        description: Submit Spark batch jobs from orchestration tools like Airflow and Oozie.\n      - name: Interactive Data Exploration\n        description: Execute ad-hoc Spark code for exploratory data analysis.\n      - name: Multi-Tenant Spark Access\n        description: Enable multiple users to share a Spark cluster with isolation via Livy sessions.\n  - type: Integrations\n    data:\n      - name: Apache Spark\n        description: Livy requires a Spark cluster and acts as the REST gateway to Spark.\n      - name: Apache Zeppelin\n        description: Zeppelin notebook backend using Livy for distributed Spark execution.\n      - name: Jupyter Notebook\n        description: Jupyter sparkmagic extension uses Livy for remote Spark kernel access.\n      - name: Apache Airflow\n        description: Airflow LivyOperator for submitting Spark batch\
  \ jobs from DAGs.\n      - name: Amazon EMR\n        description: Livy is available as an EMR application for REST-based Spark access.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-livy/refs/heads/main/apis.yml
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
