---
api_count: 2
apis:
- description: The Mesos Operator HTTP API provides a POST-based API at /api/v1 on both master and agent nodes for cluster administration including health checks, state queries, resource reservation, maintenance sch
  name: Apache Mesos Operator HTTP API
  slug: mesos-operator-http-api
- description: The Mesos Scheduler HTTP API at /api/v1/scheduler enables framework schedulers to subscribe to resource offers, launch tasks, kill tasks, reconcile status, and manage framework lifecycle over a persis
  name: Apache Mesos Scheduler HTTP API
  slug: mesos-scheduler-http-api
common:
- title: ''
  type: Portal
  url: https://mesos.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/mesos
- title: ''
  type: Documentation
  url: https://mesos.apache.org/documentation/latest/
- title: ''
  type: Blog
  url: https://mesos.apache.org/blog/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache Mesos is a retired cluster manager (now in the Apache Attic) that provided efficient resource isolation and sharing across distributed applications or frameworks. It abstracted CPU, memory, storage, and other compute resources from machines, enabling fault-tolerant and elastic distributed systems. Mesos exposed comprehensive HTTP APIs for schedulers, operators, executors, and agents.
features:
- description: Abstracts CPU, memory, storage, and other compute resources from physical machines across the entire cluster.
  name: Resource Abstraction
- description: Framework schedulers receive resource offers from Mesos and decide how to use them, enabling coexistence of diverse workloads.
  name: Two-Level Scheduling
- description: Proven to scale to tens of thousands of nodes with fault-tolerant replicated master using ZooKeeper.
  name: Linear Scalability
- description: Native Docker and AppC container image support for running containerized workloads.
  name: Container Support
- description: Comprehensive HTTP API supporting JSON and Protobuf encoding for schedulers, operators, executors, and agents.
  name: HTTP API
- description: Fault-tolerant master failover via ZooKeeper with automatic leader election and state recovery.
  name: High Availability
- description: Static and dynamic resource reservations for frameworks and roles with quota management.
  name: Resource Reservations
- description: Built-in maintenance window scheduling for graceful draining and reactivation of agent nodes.
  name: Maintenance Scheduling
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Run Hadoop MapReduce jobs on Mesos-managed cluster resources.
  name: Apache Hadoop
- description: Apache Spark supports Mesos as a cluster manager for distributed job execution.
  name: Apache Spark
- description: Kafka brokers can be scheduled and managed on Mesos clusters.
  name: Apache Kafka
- description: ZooKeeper provides leader election and state storage for Mesos master high availability.
  name: Apache ZooKeeper
- description: Native Docker container image and runtime support for containerized workload execution.
  name: Docker
- description: Elasticsearch can be deployed and managed as a framework on Mesos clusters.
  name: Elasticsearch
layout: provider
modified: '2026-04-19'
name: Apache Mesos
skills: []
slug: apache-mesos
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-mesos\nname: Apache Mesos\ndescription: >-\n  Apache Mesos is a retired cluster manager (now in the Apache Attic) that provided efficient resource isolation and sharing across distributed applications or frameworks. It abstracted CPU, memory, storage, and other compute resources from machines, enabling fault-tolerant and elastic distributed systems. Mesos exposed comprehensive HTTP APIs for schedulers, operators, executors, and agents.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cluster Management\n  - Distributed Systems\n  - Resource Management\n  - Scheduling\n  - Retired\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-mesos/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-mesos:mesos-operator-http-api\n    name: Apache Mesos Operator HTTP API\n    description: >-\n\
  \      The Mesos Operator HTTP API provides a POST-based API at /api/v1 on both master and agent nodes for cluster administration including health checks, state queries, resource reservation, maintenance scheduling, quota management, and agent lifecycle management. Supports JSON and Protobuf encoding.\n    humanURL: https://mesos.apache.org/documentation/latest/operator-http-api/\n    tags:\n      - Cluster Management\n      - HTTP API\n      - Operations\n      - Resource Management\n    properties:\n      - type: Documentation\n        url: https://mesos.apache.org/documentation/latest/operator-http-api/\n      - type: GitHubRepository\n        url: https://github.com/apache/mesos\n  - aid: apache-mesos:mesos-scheduler-http-api\n    name: Apache Mesos Scheduler HTTP API\n    description: >-\n      The Mesos Scheduler HTTP API at /api/v1/scheduler enables framework schedulers to subscribe to resource offers, launch tasks, kill tasks, reconcile status, and manage framework lifecycle over\
  \ a persistent HTTP connection with RecordIO-encoded streaming responses.\n    humanURL: https://mesos.apache.org/documentation/latest/scheduler-http-api/\n    tags:\n      - Framework\n      - HTTP API\n      - Scheduling\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://mesos.apache.org/documentation/latest/scheduler-http-api/\n      - type: GitHubRepository\n        url: https://github.com/apache/mesos\ncommon:\n  - type: Portal\n    url: https://mesos.apache.org/\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/mesos\n  - type: Documentation\n    url: https://mesos.apache.org/documentation/latest/\n  - type: Blog\n    url: https://mesos.apache.org/blog/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Features\n    data:\n      - name: Resource Abstraction\n        description: Abstracts CPU, memory, storage, and other compute resources\
  \ from physical machines across the entire cluster.\n      - name: Two-Level Scheduling\n        description: Framework schedulers receive resource offers from Mesos and decide how to use them, enabling coexistence of diverse workloads.\n      - name: Linear Scalability\n        description: Proven to scale to tens of thousands of nodes with fault-tolerant replicated master using ZooKeeper.\n      - name: Container Support\n        description: Native Docker and AppC container image support for running containerized workloads.\n      - name: HTTP API\n        description: Comprehensive HTTP API supporting JSON and Protobuf encoding for schedulers, operators, executors, and agents.\n      - name: High Availability\n        description: Fault-tolerant master failover via ZooKeeper with automatic leader election and state recovery.\n      - name: Resource Reservations\n        description: Static and dynamic resource reservations for frameworks and roles with quota management.\n      - name:\
  \ Maintenance Scheduling\n        description: Built-in maintenance window scheduling for graceful draining and reactivation of agent nodes.\n  - type: UseCases\n    data:\n      - name: Distributed Systems Orchestration\n        description: Run multiple distributed frameworks including Hadoop, Spark, and Kafka on shared cluster resources.\n      - name: Container Orchestration\n        description: Schedule and manage containerized workloads across a datacenter with resource isolation.\n      - name: Big Data Processing\n        description: Run Apache Spark, Hadoop MapReduce, and other big data frameworks on Mesos-managed resources.\n      - name: Microservices Platform\n        description: Host microservices workloads with Marathon framework providing long-running service scheduling on Mesos.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop\n        description: Run Hadoop MapReduce jobs on Mesos-managed cluster resources.\n      - name: Apache Spark\n        description:\
  \ Apache Spark supports Mesos as a cluster manager for distributed job execution.\n      - name: Apache Kafka\n        description: Kafka brokers can be scheduled and managed on Mesos clusters.\n      - name: Apache ZooKeeper\n        description: ZooKeeper provides leader election and state storage for Mesos master high availability.\n      - name: Docker\n        description: Native Docker container image and runtime support for containerized workload execution.\n      - name: Elasticsearch\n        description: Elasticsearch can be deployed and managed as a framework on Mesos clusters.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-mesos/refs/heads/main/apis.yml
tags:
- Cluster Management
- Distributed Systems
- Resource Management
- Scheduling
- Retired
url: https://raw.githubusercontent.com/api-evangelist/apache-mesos/refs/heads/main/apis.yml
use_cases:
- description: Run multiple distributed frameworks including Hadoop, Spark, and Kafka on shared cluster resources.
  name: Distributed Systems Orchestration
- description: Schedule and manage containerized workloads across a datacenter with resource isolation.
  name: Container Orchestration
- description: Run Apache Spark, Hadoop MapReduce, and other big data frameworks on Mesos-managed resources.
  name: Big Data Processing
- description: Host microservices workloads with Marathon framework providing long-running service scheduling on Mesos.
  name: Microservices Platform
---
