---
api_count: 2
apis:
- description: REST API for managing Apache Helix clusters, instances, resources, and partition state assignments, including ideal state queries and external view inspection.
  name: Apache Helix REST API
  slug: apache-helix-rest-api
- description: Java API for implementing Helix participant, spectator, and controller roles, with APIs for resource management, task execution, and state machine definitions.
  name: Apache Helix Java API
  slug: apache-helix-java-api
capabilities:
- description: ''
  name: Helix Cluster Management
  slug: helix-cluster-management
common:
- title: ''
  type: Documentation
  url: https://helix.apache.org/
- title: ''
  type: GettingStarted
  url: https://helix.apache.org/0.9.9-docs/Quickstart.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/helix
- title: ''
  type: SpectralRules
  url: rules/apache-helix-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-helix-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/helix-cluster-management.yaml
created: '2026-03-16'
description: Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST API for cluster administration and a Java API for participant, spectator, and controller roles.
features:
- description: Automatically assign and balance partitions across cluster nodes using pluggable rebalancer algorithms.
  name: Automatic Partition Management
- description: Define custom resource state machines (e.g., Master-Slave, Leader-Standby) for any distributed service.
  name: State Machine Framework
- description: Detect node failures and automatically reassign partitions to maintain replication targets.
  name: Fault Tolerance
- description: HTTP REST API for cluster administration, resource management, and state inspection.
  name: REST API
- description: Distributed task scheduling framework for batch jobs and recurring workflows with failure handling.
  name: Task Framework
- description: Uses Apache ZooKeeper as the distributed coordination backend for cluster state storage.
  name: ZooKeeper Integration
- description: Read-only API for external services to observe resource state and routing decisions.
  name: Spectator API
- description: Rack and zone-aware partition placement for fault-domain isolation in cloud environments.
  name: Cloud-Aware Rebalancing
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: ZooKeeper is the required coordination backend for Helix cluster state management.
  name: Apache ZooKeeper
- description: Helix is used internally by some Kafka ecosystem projects for partition management.
  name: Apache Kafka
- description: Apache Pinot uses Helix for real-time OLAP cluster partition and segment management.
  name: LinkedIn Pinot
- description: Venice feature store uses Helix for managing data store partition assignments.
  name: LinkedIn Venice
jsonld:
- class_count: 16
  name: Apache Helix Rest Context
  property_count: 0
  slug: apache-helix-rest-context
layout: provider
modified: '2026-04-19'
name: Apache Helix
rules:
- name: Apache Helix API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: apache-helix-spectral-rules
skills: []
slug: apache-helix
solutions: []
tags:
- Apache
- Cluster Management
- Distributed Systems
- Open Source
- Partitioning
- Replication
url: https://raw.githubusercontent.com/api-evangelist/apache-helix/refs/heads/main/apis.yml
use_cases:
- description: Manage shard assignment and replication for distributed databases like DistributedLog or Espresso.
  name: Distributed Database Cluster Management
- description: Automatically balance and assign search index shards across a cluster of query servers.
  name: Search Index Partition Management
- description: Schedule and execute distributed batch tasks with automatic retry and failure recovery.
  name: Distributed Task Scheduling
- description: Use Helix spectator API to implement client-side load balancing based on partition state.
  name: Microservices Load Balancing
- description: Perform rolling upgrades and partition migrations without service downtime.
  name: Stateful Service Migration
---
