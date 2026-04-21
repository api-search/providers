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
