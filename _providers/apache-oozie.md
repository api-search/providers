---
api_count: 1
api_specs:
- filename: apache-oozie-openapi.yaml
  format: yaml
  label: Apache Oozie REST API
  slug: apache-oozie-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/openapi/apache-oozie-openapi.yaml
apis:
- description: The Oozie Web Services API provides REST endpoints for submitting, managing, and monitoring workflow, coordinator, and bundle jobs on Apache Hadoop. Supports full job lifecycle management (submit, sta
  name: Apache Oozie REST API
  slug: apache-oozie-rest-api
capabilities:
- description: Workflow capability for orchestrating Hadoop data processing pipelines using Apache Oozie. Covers workflow, coordinator, and bundle job lifecycle management for data engineers and Hadoop pipeline oper
  name: Apache Oozie Workflow Orchestration
  slug: apache-oozie-workflow-orchestration
common:
- title: Apache Oozie GitHub Repository
  type: GitHubRepository
  url: https://github.com/apache/oozie
- title: Apache Software Foundation GitHub
  type: GitHubOrganization
  url: https://github.com/apache
- title: Apache Oozie Documentation
  type: Documentation
  url: https://oozie.apache.org/docs/5.2.1/
- title: Oozie Quick Start Guide
  type: GettingStarted
  url: https://oozie.apache.org/docs/5.2.1/DG_QuickStart.html
- title: Oozie Examples
  type: Tutorials
  url: https://oozie.apache.org/docs/5.2.1/DG_Examples.html
- title: Oozie Release Log
  type: ReleaseNotes
  url: https://github.com/apache/oozie/blob/master/release-log.txt
- title: Apache License 2.0
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: Mailing Lists
  type: Support
  url: https://oozie.apache.org/mailing-lists.html
- title: Oozie on Stack Overflow
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/oozie
- title: Apache Oozie Spectral Rules
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/rules/apache-oozie-spectral-rules.yml
- title: Apache Oozie Workflow Orchestration
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/capabilities/apache-oozie-workflow-orchestration.yaml
- title: Apache Oozie Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/vocabulary/apache-oozie-vocabulary.yaml
- title: Apache Oozie JSON-LD Context
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-ld/apache-oozie-context.jsonld
created: '2026-03-16'
description: Apache Oozie is a workflow scheduler system for managing Apache Hadoop jobs. It enables users to define workflows as directed acyclic graphs (DAGs) of actions including MapReduce, Pig, Hive, Sqoop, and custom Java/shell steps. Coordinator jobs trigger workflows based on time schedules or data availability, while bundle jobs group multiple coordinators. Oozie provides a REST API for job submission, lifecycle management, monitoring, and system administration. Governed by the Apache Software Foundation under the Apache License 2.0, written in Java.
features:
- description: Define complex data processing pipelines as DAGs of actions executed on Apache Hadoop.
  name: Directed Acyclic Graph Workflows
- description: Schedule recurring workflows triggered by time intervals or data availability conditions in HDFS.
  name: Coordinator Jobs
- description: Group multiple coordinator jobs into a single bundle for coordinated lifecycle management.
  name: Bundle Jobs
- description: Full REST API for job submission, lifecycle control, monitoring, and system administration.
  name: REST API Management
- description: Built-in support for MapReduce, Pig, Hive, Sqoop, Distcp, and custom Java/shell actions.
  name: Native Hadoop Action Types
- description: Define and monitor service level agreements on workflow and coordinator actions with alert capabilities.
  name: SLA Management
- description: Generate PNG, SVG, or DOT graph visualizations of workflow DAGs for debugging and documentation.
  name: DAG Visualization
- description: Retrieve execution logs, error logs, and audit trails for jobs via REST API with filtering support.
  name: Log Retrieval
- description: Built-in HA support with multiple Oozie server instances and distributed state management.
  name: High Availability
- description: Manage shared Hadoop libraries across workflows for consistent classpath management.
  name: Shared Library Support
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Core integration with HDFS for data storage and YARN for resource management.
  name: Apache Hadoop
- description: Native Hive action type for executing HiveQL queries as workflow steps.
  name: Apache Hive
- description: Native Pig action type for data transformation scripts in workflow pipelines.
  name: Apache Pig
- description: Native Sqoop action type for importing and exporting data between Hadoop and RDBMS.
  name: Apache Sqoop
- description: Spark action type for running Spark jobs within Oozie workflows.
  name: Apache Spark
- description: Native MapReduce action type as the foundational Hadoop computation framework.
  name: Apache MapReduce
jsonld:
- class_count: 9
  name: Apache Oozie Context
  property_count: 27
  slug: apache-oozie-context
layout: provider
modified: '2026-04-19'
name: Apache Oozie
rules:
- name: Apache Oozie API Rules
  rule_count: 27
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 13
  slug: apache-oozie-spectral-rules
skills: []
slug: apache-oozie
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-oozie\nname: Apache Oozie\ndescription: >-\n  Apache Oozie is a workflow scheduler system for managing Apache Hadoop jobs. It enables\n  users to define workflows as directed acyclic graphs (DAGs) of actions including\n  MapReduce, Pig, Hive, Sqoop, and custom Java/shell steps. Coordinator jobs trigger\n  workflows based on time schedules or data availability, while bundle jobs group\n  multiple coordinators. Oozie provides a REST API for job submission, lifecycle\n  management, monitoring, and system administration. Governed by the Apache Software\n  Foundation under the Apache License 2.0, written in Java.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Workflow\n  - Hadoop\n  - Orchestration\n  - Scheduling\n  - Big Data\n  - Apache\n  - Java\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-oozie:apache-oozie-rest-api\n    name: Apache Oozie REST API\n    description: >-\n      The Oozie Web Services API provides REST endpoints for submitting, managing, and\n      monitoring workflow, coordinator, and bundle jobs on Apache Hadoop. Supports full\n      job lifecycle management (submit, start, suspend, resume, kill, rerun), log and\n      status retrieval, DAG visualization, SLA management, and system administration.\n      Available at /oozie/v1 and /oozie/v2 with JSON responses.\n    humanURL: https://oozie.apache.org/docs/5.2.1/WebServicesAPI.html\n    baseURL: http://localhost:11000/oozie\n    tags:\n      - REST\n      - Hadoop\n      - Workflow Management\n      - Job Scheduling\n    properties:\n      - type: Documentation\n        url: https://oozie.apache.org/docs/5.2.1/WebServicesAPI.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/openapi/apache-oozie-openapi.yaml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-schema/apache-oozie-job-info-schema.json\n        title: Job Info Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-schema/apache-oozie-job-list-schema.json\n        title: Job List Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-schema/apache-oozie-job-id-schema.json\n        title: Job ID Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-schema/apache-oozie-system-status-schema.json\n        title: System Status Schema\n\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/oozie\n    title: Apache Oozie GitHub Repository\n  - type: GitHubOrganization\n    url: https://github.com/apache\n    title: Apache Software\
  \ Foundation GitHub\n  - type: Documentation\n    url: https://oozie.apache.org/docs/5.2.1/\n    title: Apache Oozie Documentation\n  - type: GettingStarted\n    url: https://oozie.apache.org/docs/5.2.1/DG_QuickStart.html\n    title: Oozie Quick Start Guide\n  - type: Tutorials\n    url: https://oozie.apache.org/docs/5.2.1/DG_Examples.html\n    title: Oozie Examples\n  - type: ReleaseNotes\n    url: https://github.com/apache/oozie/blob/master/release-log.txt\n    title: Oozie Release Log\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n    title: Apache License 2.0\n  - type: Support\n    url: https://oozie.apache.org/mailing-lists.html\n    title: Mailing Lists\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/oozie\n    title: Oozie on Stack Overflow\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/rules/apache-oozie-spectral-rules.yml\n    title: Apache Oozie Spectral\
  \ Rules\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/capabilities/apache-oozie-workflow-orchestration.yaml\n    title: Apache Oozie Workflow Orchestration\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/vocabulary/apache-oozie-vocabulary.yaml\n    title: Apache Oozie Vocabulary\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/json-ld/apache-oozie-context.jsonld\n    title: Apache Oozie JSON-LD Context\n  - type: Features\n    data:\n      - name: Directed Acyclic Graph Workflows\n        description: Define complex data processing pipelines as DAGs of actions executed on Apache Hadoop.\n      - name: Coordinator Jobs\n        description: Schedule recurring workflows triggered by time intervals or data availability conditions in HDFS.\n      - name: Bundle Jobs\n        description: Group multiple\
  \ coordinator jobs into a single bundle for coordinated lifecycle management.\n      - name: REST API Management\n        description: Full REST API for job submission, lifecycle control, monitoring, and system administration.\n      - name: Native Hadoop Action Types\n        description: Built-in support for MapReduce, Pig, Hive, Sqoop, Distcp, and custom Java/shell actions.\n      - name: SLA Management\n        description: Define and monitor service level agreements on workflow and coordinator actions with alert capabilities.\n      - name: DAG Visualization\n        description: Generate PNG, SVG, or DOT graph visualizations of workflow DAGs for debugging and documentation.\n      - name: Log Retrieval\n        description: Retrieve execution logs, error logs, and audit trails for jobs via REST API with filtering support.\n      - name: High Availability\n        description: Built-in HA support with multiple Oozie server instances and distributed state management.\n      - name:\
  \ Shared Library Support\n        description: Manage shared Hadoop libraries across workflows for consistent classpath management.\n  - type: UseCases\n    data:\n      - name: ETL Pipeline Orchestration\n        description: Orchestrate multi-step ETL pipelines combining Hive queries, MapReduce jobs, and data transfers on Hadoop.\n      - name: Scheduled Data Processing\n        description: Run recurring Hadoop batch jobs on time-based schedules using coordinator jobs.\n      - name: Data-Triggered Workflows\n        description: Trigger workflows automatically when new data arrives in HDFS using coordinator data-in conditions.\n      - name: Machine Learning Pipeline Automation\n        description: Automate ML model training and evaluation pipelines on Hadoop with dependency chaining.\n      - name: Data Migration and Archival\n        description: Orchestrate large-scale data migration, compaction, and archival workflows across Hadoop clusters.\n      - name: Multi-Cluster Coordination\n\
  \        description: Coordinate workflows that span multiple Hadoop clusters using Distcp and remote actions.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop\n        description: Core integration with HDFS for data storage and YARN for resource management.\n      - name: Apache Hive\n        description: Native Hive action type for executing HiveQL queries as workflow steps.\n      - name: Apache Pig\n        description: Native Pig action type for data transformation scripts in workflow pipelines.\n      - name: Apache Sqoop\n        description: Native Sqoop action type for importing and exporting data between Hadoop and RDBMS.\n      - name: Apache Spark\n        description: Spark action type for running Spark jobs within Oozie workflows.\n      - name: Apache MapReduce\n        description: Native MapReduce action type as the foundational Hadoop computation framework.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/apis.yml
tags:
- Workflow
- Hadoop
- Orchestration
- Scheduling
- Big Data
- Apache
- Java
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/apis.yml
use_cases:
- description: Orchestrate multi-step ETL pipelines combining Hive queries, MapReduce jobs, and data transfers on Hadoop.
  name: ETL Pipeline Orchestration
- description: Run recurring Hadoop batch jobs on time-based schedules using coordinator jobs.
  name: Scheduled Data Processing
- description: Trigger workflows automatically when new data arrives in HDFS using coordinator data-in conditions.
  name: Data-Triggered Workflows
- description: Automate ML model training and evaluation pipelines on Hadoop with dependency chaining.
  name: Machine Learning Pipeline Automation
- description: Orchestrate large-scale data migration, compaction, and archival workflows across Hadoop clusters.
  name: Data Migration and Archival
- description: Coordinate workflows that span multiple Hadoop clusters using Distcp and remote actions.
  name: Multi-Cluster Coordination
---
