---
api_count: 2
apis:
- description: The ZooKeeper Admin Server provides HTTP endpoints on port 8080 that expose the four-letter-word equivalent commands as REST endpoints for cluster monitoring, configuration, and diagnostics. Endpoints
  name: Apache ZooKeeper Admin Server API
  slug: apache-zookeeper-admin-api
- description: The ZooKeeper client API provides Java and C language bindings for distributed coordination operations. Operations include create (create znodes), delete, exists (check existence), getData, setData, g
  name: Apache ZooKeeper Client API
  slug: apache-zookeeper-client-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/zookeeper
- title: ''
  type: Documentation
  url: https://zookeeper.apache.org/doc/current/
- title: ''
  type: Portal
  url: https://zookeeper.apache.org/
- title: ''
  type: GettingStarted
  url: https://zookeeper.apache.org/doc/current/zookeeperStarted.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/zookeeper/releases
- title: ''
  type: Support
  url: https://zookeeper.apache.org/lists.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: SpectralRules
  url: rules/apache-zookeeper-spectral-rules.yml
- title: Python Kazoo Client
  type: SDK
  url: https://pypi.org/project/kazoo/
- title: Node.js Client
  type: SDK
  url: https://www.npmjs.com/package/node-zookeeper-client
created: '2026-03-16'
description: Apache ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services for distributed systems. It provides a hierarchical key-value store (znodes), watches for change notifications, ephemeral nodes for presence detection, and sequential nodes for leader election and distributed locking. ZooKeeper exposes a Java/C client API and an HTTP Admin Server API for monitoring and management. It is widely used by Kafka, Hadoop, HBase, Storm, and other distributed systems.
features:
- description: Tree-structured znode namespace similar to a filesystem for organized configuration storage.
  name: Hierarchical Namespace
- description: Client watches on znodes trigger one-time callbacks on change events for reactive patterns.
  name: Watch Notifications
- description: Nodes that disappear when the creating client session expires for presence detection.
  name: Ephemeral Nodes
- description: Auto-incrementing sequential znodes for implementing distributed queues and leader election.
  name: Sequential Nodes
- description: Compare-and-set and multi-operation batches for consistent distributed state updates.
  name: Atomic Operations
- description: Per-znode access control lists for authentication and authorization of znode operations.
  name: ACL Security
- description: Read-only observer servers for scaling read throughput without affecting write quorum.
  name: Observer Mode
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: ZooKeeper (legacy) for Kafka broker metadata and controller election (replaced by KRaft).
  name: Apache Kafka
- description: ZooKeeper for HBase region server coordination and master election.
  name: Apache HBase
- description: ZooKeeper for HDFS NameNode HA fencing and YARN ResourceManager HA.
  name: Apache Hadoop
- description: ZooKeeper for Storm Nimbus coordination and worker heartbeat tracking.
  name: Apache Storm
- description: ZooKeeper for SolrCloud cluster coordination, configuration, and leader election.
  name: Apache Solr
- description: High-level ZooKeeper client with recipes for common distributed patterns.
  name: Apache Curator
layout: provider
modified: '2026-04-19'
name: Apache ZooKeeper
rules:
- name: Apache ZooKeeper API Rules
  rule_count: 10
  severity_counts:
    error: 7
    hint: 0
    info: 2
    warn: 1
  slug: apache-zookeeper-spectral-rules
skills: []
slug: apache-zookeeper
solutions: []
tags:
- Configuration Management
- Distributed Coordination
- Leader Election
- Service Discovery
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-zookeeper/refs/heads/main/apis.yml
use_cases:
- description: Distributed leader election using ephemeral sequential znodes for coordination.
  name: Leader Election
- description: Centralized configuration storage with watch-based change notification to services.
  name: Distributed Configuration Management
- description: Service registration and lookup using ephemeral znodes as presence indicators.
  name: Service Registry and Discovery
- description: Distributed mutex and read/write locks using ephemeral sequential znode recipes.
  name: Distributed Locking
- description: Kafka broker coordination, HBase region server management, and Hadoop NameNode fencing.
  name: Cluster Coordination
---
