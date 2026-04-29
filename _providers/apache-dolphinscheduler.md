---
api_count: 1
apis:
- description: 'The DolphinScheduler REST API enables programmatic management of projects, workflow definitions (DAGs), workflow instances, task types, schedules, resources, data sources, alerts, tenants, and users. '
  name: Apache DolphinScheduler REST API
  slug: apache-dolphinscheduler-rest-api
common:
- title: ''
  type: Portal
  url: https://dolphinscheduler.apache.org/
- title: ''
  type: Documentation
  url: https://dolphinscheduler.apache.org/en-us/docs/latest/
- title: ''
  type: GettingStarted
  url: https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/start/quick-start.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/dolphinscheduler
- title: PyDolphinScheduler Python SDK
  type: SDK
  url: https://github.com/apache/dolphinscheduler-sdk-python
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/vocabulary/apache-dolphinscheduler-vocabulary.yaml
created: '2026-03-16'
description: Apache DolphinScheduler is a modern distributed and extensible data orchestration platform governed by the Apache Software Foundation. It provides a DAG-based visual workflow designer, multi-master/multi-worker architecture for horizontal scaling, and a comprehensive REST API for programmatic control. It supports dozens of task types (Shell, Spark, Flink, SQL, Python, HTTP, etc.), multi-cloud deployments, multi-tenancy, backfill, and a Python SDK (PyDolphinScheduler).
features:
- description: Web-based drag-and-drop interface for building directed acyclic graph (DAG) workflows with real-time execution visualization.
  name: DAG Visual Workflow Designer
- description: Comprehensive REST API for all platform operations including workflow management, scheduling, resource management, and administration.
  name: REST Open API
- description: Decentralized architecture with horizontal scaling support, capable of processing tens of millions of tasks per day.
  name: Multi-Master/Worker Architecture
- description: Built-in task types including Shell, Spark, Flink, SQL, Python, HTTP, DataX, Seatunnel, Jupyter, and custom task plugins.
  name: Rich Task Types
- description: Supports multiple tenants with isolated resource quotas, permissions, and workflow namespaces.
  name: Multi-Tenancy
- description: Version control for workflow definitions and instances, enabling rollback and auditing of workflow changes.
  name: Workflow Versioning
- description: Unified data source management supporting MySQL, PostgreSQL, Hive, Trino, Spark, ClickHouse, and many other databases.
  name: Data Source Management
- description: PyDolphinScheduler allows defining and managing workflows programmatically in Python with code-first workflow authoring.
  name: Python SDK
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Spark task type for submitting Spark batch and streaming jobs from DolphinScheduler workflows.
  name: Apache Spark
- description: Native Flink task type for submitting Flink stream processing jobs.
  name: Apache Flink
- description: Hive data source and task type for SQL-on-Hadoop workloads.
  name: Apache Hive
- description: Kubernetes deployment mode and K8s task type for container-native workflow execution.
  name: Kubernetes
- description: Official Docker images and Docker Compose configuration for rapid deployment.
  name: Docker
- description: Native task types for DataX and SeaTunnel data integration frameworks.
  name: DataX / SeaTunnel
- description: An Airflow provider package allows triggering DolphinScheduler workflows from Airflow DAGs.
  name: Apache Airflow
jsonld:
- class_count: 6
  name: Apache Dolphinscheduler Context
  property_count: 29
  slug: apache-dolphinscheduler-context
layout: provider
modified: '2026-04-19'
name: Apache DolphinScheduler
skills: []
slug: apache-dolphinscheduler
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-dolphinscheduler\nname: Apache DolphinScheduler\ndescription: >-\n  Apache DolphinScheduler is a modern distributed and extensible data orchestration platform governed by the Apache Software Foundation. It provides a DAG-based visual workflow designer, multi-master/multi-worker\n  architecture for horizontal scaling, and a comprehensive REST API for programmatic control. It supports dozens of task types (Shell, Spark, Flink, SQL, Python, HTTP, etc.), multi-cloud deployments, multi-tenancy,\n  backfill, and a Python SDK (PyDolphinScheduler).\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Apache\n- DAG\n- Data Pipeline\n- Open Source\n- Orchestration\n- Python\n- Scheduling\n- Workflow\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\n\
  apis:\n- aid: apache-dolphinscheduler:apache-dolphinscheduler-rest-api\n  name: Apache DolphinScheduler REST API\n  description: >-\n    The DolphinScheduler REST API enables programmatic management of projects, workflow definitions (DAGs), workflow instances, task types, schedules, resources, data sources, alerts, tenants, and users.\n    Authentication is via API token. A Swagger UI is available at /dolphinscheduler/swagger-ui/index.html.\n  humanURL: https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/guide/open-api.html\n  tags:\n  - Alerts\n  - DAG\n  - Data Sources\n  - Projects\n  - REST\n  - Resources\n  - Scheduling\n  - Tasks\n  - Tenants\n  - Workflow\n  properties:\n  - type: Documentation\n    url: https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/guide/open-api.html\n  - type: GettingStarted\n    url: https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/start/quick-start.html\n  - type: GitHubRepository\n    url: https://github.com/apache/dolphinscheduler\n\
  \  - type: SDK\n    url: https://pypi.org/project/apache-airflow-providers-apache-dolphinscheduler/\n    title: Python SDK (PyDolphinScheduler)\n  - type: Tools\n    url: https://hub.docker.com/r/apache/dolphinscheduler-standalone-server\n    title: Docker Image\n  - type: Tools\n    url: https://github.com/apache/dolphinscheduler-operator\n    title: Kubernetes Operator\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-schedule-schema.json\n    title: Schedule\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-task-definition-schema.json\n    title: Task Definition\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-workflow-definition-schema.json\n    title: Workflow Definition\n\
  \  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-schema/apache-dolphinscheduler-workflow-instance-schema.json\n    title: Workflow Instance\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-schedule-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-task-definition-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-workflow-definition-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-structure/apache-dolphinscheduler-workflow-instance-structure.json\n  - type:\
  \ JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/json-ld/apache-dolphinscheduler-context.jsonld\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-schedule-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-task-definition-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-workflow-definition-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/examples/apache-dolphinscheduler-workflow-instance-example.json\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: Portal\n  url: https://dolphinscheduler.apache.org/\n\
  - type: Documentation\n  url: https://dolphinscheduler.apache.org/en-us/docs/latest/\n- type: GettingStarted\n  url: https://dolphinscheduler.apache.org/en-us/docs/latest/user_doc/start/quick-start.html\n- type: GitHubOrganization\n  url: https://github.com/apache\n- type: GitHubRepository\n  url: https://github.com/apache/dolphinscheduler\n- type: SDK\n  url: https://github.com/apache/dolphinscheduler-sdk-python\n  title: PyDolphinScheduler Python SDK\n- type: Features\n  data:\n  - name: DAG Visual Workflow Designer\n    description: Web-based drag-and-drop interface for building directed acyclic graph (DAG) workflows with real-time execution visualization.\n  - name: REST Open API\n    description: Comprehensive REST API for all platform operations including workflow management, scheduling, resource management, and administration.\n  - name: Multi-Master/Worker Architecture\n    description: Decentralized architecture with horizontal scaling support, capable of processing tens of millions\
  \ of tasks per day.\n  - name: Rich Task Types\n    description: Built-in task types including Shell, Spark, Flink, SQL, Python, HTTP, DataX, Seatunnel, Jupyter, and custom task plugins.\n  - name: Multi-Tenancy\n    description: Supports multiple tenants with isolated resource quotas, permissions, and workflow namespaces.\n  - name: Workflow Versioning\n    description: Version control for workflow definitions and instances, enabling rollback and auditing of workflow changes.\n  - name: Data Source Management\n    description: Unified data source management supporting MySQL, PostgreSQL, Hive, Trino, Spark, ClickHouse, and many other databases.\n  - name: Python SDK\n    description: PyDolphinScheduler allows defining and managing workflows programmatically in Python with code-first workflow authoring.\n- type: UseCases\n  data:\n  - name: Data Pipeline Orchestration\n    description: Orchestrate complex ETL/ELT data pipelines with dependencies, retries, and monitoring across distributed\
  \ systems.\n  - name: Machine Learning Workflows\n    description: Schedule and manage ML model training, evaluation, and deployment pipelines with task dependencies.\n  - name: Multi-Cloud Data Workflows\n    description: Orchestrate workflows spanning multiple cloud providers and data centers with unified scheduling.\n  - name: SQL and Analytics Scheduling\n    description: Schedule recurring SQL queries, reports, and analytics jobs against multiple data sources.\n  - name: DevOps and CI/CD Pipelines\n    description: Automate deployment workflows, data quality checks, and operational tasks with DolphinScheduler DAGs.\n- type: Integrations\n  data:\n  - name: Apache Spark\n    description: Native Spark task type for submitting Spark batch and streaming jobs from DolphinScheduler workflows.\n  - name: Apache Flink\n    description: Native Flink task type for submitting Flink stream processing jobs.\n  - name: Apache Hive\n    description: Hive data source and task type for SQL-on-Hadoop\
  \ workloads.\n  - name: Kubernetes\n    description: Kubernetes deployment mode and K8s task type for container-native workflow execution.\n  - name: Docker\n    description: Official Docker images and Docker Compose configuration for rapid deployment.\n  - name: DataX / SeaTunnel\n    description: Native task types for DataX and SeaTunnel data integration frameworks.\n  - name: Apache Airflow\n    description: An Airflow provider package allows triggering DolphinScheduler workflows from Airflow DAGs.\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/vocabulary/apache-dolphinscheduler-vocabulary.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/apis.yml
tags:
- Apache
- DAG
- Data Pipeline
- Open Source
- Orchestration
- Python
- Scheduling
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/apache-dolphinscheduler/refs/heads/main/apis.yml
use_cases:
- description: Orchestrate complex ETL/ELT data pipelines with dependencies, retries, and monitoring across distributed systems.
  name: Data Pipeline Orchestration
- description: Schedule and manage ML model training, evaluation, and deployment pipelines with task dependencies.
  name: Machine Learning Workflows
- description: Orchestrate workflows spanning multiple cloud providers and data centers with unified scheduling.
  name: Multi-Cloud Data Workflows
- description: Schedule recurring SQL queries, reports, and analytics jobs against multiple data sources.
  name: SQL and Analytics Scheduling
- description: Automate deployment workflows, data quality checks, and operational tasks with DolphinScheduler DAGs.
  name: DevOps and CI/CD Pipelines
---
