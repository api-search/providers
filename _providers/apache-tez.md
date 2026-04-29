---
api_count: 2
apis:
- description: The Tez DAG API provides a Java programming model for defining and submitting directed-acyclic-graph (DAG) computation jobs to Apache YARN. It allows building DAGs composed of Vertex (processing units
  name: Apache Tez DAG API
  slug: apache-tez-dag-api
- description: The Tez UI and YARN Application History Server expose REST endpoints for monitoring Tez application history, DAG details, vertex and task statistics. The Tez Timeline Server integration provides histo
  name: Apache Tez UI REST API
  slug: apache-tez-ui-rest-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/tez
- title: ''
  type: Documentation
  url: https://tez.apache.org/
- title: ''
  type: Portal
  url: https://tez.apache.org/
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/tez/releases
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache Tez is an application framework that allows for complex directed-acyclic-graph (DAG) based processing of data built on Apache Hadoop YARN. It is designed as a successor to MapReduce for executing Hive and Pig queries, providing a flexible API for creating DAG execution pipelines, in-memory data passing between tasks, and session reuse for reduced startup latency. Apache Tez is an Apache Software Foundation top-level project.
features:
- description: Flexible DAG computation model replacing MapReduce for complex multi-stage pipelines.
  name: DAG-Based Execution
- description: Direct in-memory data transfer between connected vertices eliminating HDFS I/O.
  name: In-Memory Data Passing
- description: Tez sessions reuse container allocations across DAG submissions for reduced latency.
  name: Session Reuse
- description: Runtime DAG modification based on actual data statistics during execution.
  name: Dynamic Optimization
- description: Native YARN resource management with fine-grained resource requests per vertex.
  name: YARN Integration
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native YARN resource manager integration for cluster resource allocation.
  name: Apache Hadoop YARN
- description: Default execution engine for Hive queries in HDP and CDH distributions.
  name: Apache Hive
- description: Tez execution backend for Apache Pig script compilation and execution.
  name: Apache Pig
- description: Input/output storage for Tez job data via Hadoop Distributed File System.
  name: Apache HDFS
layout: provider
modified: '2026-04-19'
name: Apache Tez
skills: []
slug: apache-tez
solutions: []
source_yaml: "aid: apache-tez\nname: Apache Tez\ndescription: >-\n  Apache Tez is an application framework that allows for complex directed-acyclic-graph (DAG)\n  based processing of data built on Apache Hadoop YARN. It is designed as a successor to\n  MapReduce for executing Hive and Pig queries, providing a flexible API for creating DAG\n  execution pipelines, in-memory data passing between tasks, and session reuse for reduced\n  startup latency. Apache Tez is an Apache Software Foundation top-level project.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Big Data\n  - DAG\n  - Execution Engine\n  - Hadoop\n  - YARN\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-tez/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-tez:apache-tez-dag-api\n    name: Apache Tez DAG API\n    description:\
  \ >-\n      The Tez DAG API provides a Java programming model for defining and submitting\n      directed-acyclic-graph (DAG) computation jobs to Apache YARN. It allows building DAGs\n      composed of Vertex (processing units), Edge (data connections between vertices), and\n      Processor implementations. The API supports data source/sink definitions, vertex grouping,\n      fault tolerance configuration, and monitoring via the Tez UI and REST API.\n    humanURL: https://tez.apache.org/developer-docs.html\n    tags:\n      - Java\n      - DAG\n      - YARN\n      - Hadoop\n    properties:\n      - type: Documentation\n        url: https://tez.apache.org/developer-docs.html\n      - type: APIReference\n        url: https://tez.apache.org/javadocs/\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.tez\n        title: Maven Java SDK\n  - aid: apache-tez:apache-tez-ui-rest-api\n    name: Apache Tez UI REST API\n    description: >-\n      The Tez UI and YARN Application\
  \ History Server expose REST endpoints for monitoring\n      Tez application history, DAG details, vertex and task statistics. The Tez Timeline\n      Server integration provides historical data for DAGs, vertices, tasks, and task attempts\n      with detailed resource usage and timing information.\n    humanURL: https://tez.apache.org/tez-ui.html\n    tags:\n      - REST\n      - Monitoring\n      - YARN\n      - History\n    properties:\n      - type: Documentation\n        url: https://tez.apache.org/tez-ui.html\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/tez\n  - type: Documentation\n    url: https://tez.apache.org/\n  - type: Portal\n    url: https://tez.apache.org/\n  - type: ReleaseNotes\n    url: https://github.com/apache/tez/releases\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: DAG-Based Execution\n        description: Flexible DAG computation model replacing MapReduce for complex\
  \ multi-stage pipelines.\n      - name: In-Memory Data Passing\n        description: Direct in-memory data transfer between connected vertices eliminating HDFS I/O.\n      - name: Session Reuse\n        description: Tez sessions reuse container allocations across DAG submissions for reduced latency.\n      - name: Dynamic Optimization\n        description: Runtime DAG modification based on actual data statistics during execution.\n      - name: YARN Integration\n        description: Native YARN resource management with fine-grained resource requests per vertex.\n  - type: UseCases\n    data:\n      - name: Apache Hive Query Execution\n        description: Tez is the default execution engine for Apache Hive queries replacing MapReduce.\n      - name: Apache Pig Script Execution\n        description: Execute Apache Pig Latin scripts as optimized Tez DAGs.\n      - name: Complex ETL Pipelines\n        description: Multi-stage data transformation pipelines with in-memory data passing.\n  -\
  \ type: Integrations\n    data:\n      - name: Apache Hadoop YARN\n        description: Native YARN resource manager integration for cluster resource allocation.\n      - name: Apache Hive\n        description: Default execution engine for Hive queries in HDP and CDH distributions.\n      - name: Apache Pig\n        description: Tez execution backend for Apache Pig script compilation and execution.\n      - name: Apache HDFS\n        description: Input/output storage for Tez job data via Hadoop Distributed File System.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-tez/refs/heads/main/apis.yml
tags:
- Big Data
- DAG
- Execution Engine
- Hadoop
- YARN
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-tez/refs/heads/main/apis.yml
use_cases:
- description: Tez is the default execution engine for Apache Hive queries replacing MapReduce.
  name: Apache Hive Query Execution
- description: Execute Apache Pig Latin scripts as optimized Tez DAGs.
  name: Apache Pig Script Execution
- description: Multi-stage data transformation pipelines with in-memory data passing.
  name: Complex ETL Pipelines
---
