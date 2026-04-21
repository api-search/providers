---
api_count: 2
apis:
- description: The Apache BookKeeper HTTP Admin API provides REST endpoints for managing and monitoring BookKeeper clusters, bookies, ledgers, and auto-recovery operations. It enables programmatic cluster administra
  name: Apache BookKeeper Admin API
  slug: apache-bookkeeper-admin-api
- description: The BookKeeper Java client API provides programmatic access for creating, writing, reading, and managing ledgers. It supports both the legacy LedgerHandle API and the newer Ledger API with explicit du
  name: Apache BookKeeper Java Client API
  slug: apache-bookkeeper-java-client
capabilities:
- description: Workflow capability for managing and monitoring Apache BookKeeper clusters, including bookie health checks, ledger inspection, and auto-recovery operations.
  name: Bookkeeper Cluster Management
  slug: bookkeeper-cluster-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/bookkeeper
- title: ''
  type: Documentation
  url: https://bookkeeper.apache.org/
- title: ''
  type: GettingStarted
  url: https://bookkeeper.apache.org/docs/getting-started/installation
- title: ''
  type: Support
  url: https://bookkeeper.apache.org/community/mailing-lists
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: ChangeLog
  url: https://github.com/apache/bookkeeper/releases
- title: ''
  type: SpectralRules
  url: rules/apache-bookkeeper-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-bookkeeper-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/bookkeeper-cluster-management.yaml
created: '2026-03-16'
description: Apache BookKeeper is a scalable, fault-tolerant, and low-latency storage service optimized for real-time workloads developed by the Apache Software Foundation. It provides a simple log-oriented storage abstraction called ledgers for reliable, replicated storage of sequential data. BookKeeper is used as the durable log storage layer in Apache Pulsar and other distributed messaging and stream processing systems. It provides a Java client API and an HTTP Admin REST API for cluster management, bookie monitoring, and auto-recovery operations.
features:
- description: Append-only log segments called ledgers provide the foundational storage primitive for reliable sequential data storage.
  name: Ledger Storage
- description: Data is written to a configurable ensemble of bookies with write quorum and ack quorum parameters for fault tolerance.
  name: Ensemble Replication
- description: Built-in under-replication detection and automatic ledger re-replication when bookie nodes fail.
  name: Auto-Recovery
- description: RESTful HTTP Admin API for managing ledgers, bookies, cluster configuration, and triggering recovery operations.
  name: HTTP Admin API
- description: Prometheus-format metrics endpoint for monitoring bookie performance and storage utilization.
  name: Metrics Export
- description: ZooKeeper-based leader election for the auditor role responsible for detecting under-replicated ledgers.
  name: Auditor Election
- description: Configurable garbage collection for reclaiming storage from deleted or expired ledger data.
  name: Garbage Collection
- description: Separate journal and ledger storage paths optimized for sequential write throughput and random read performance.
  name: Journal and Ledger Storage
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: BookKeeper serves as the durable log storage layer for Apache Pulsar messaging topics.
  name: Apache Pulsar
- description: ZooKeeper is used for bookie coordination, auditor election, and cluster metadata management.
  name: Apache ZooKeeper
- description: BookKeeper can be used with Hadoop ecosystem tools for reliable log storage alongside HDFS.
  name: Apache Hadoop
- description: BookKeeper exports Prometheus-format metrics for cluster monitoring and alerting.
  name: Prometheus
- description: Grafana dashboards consume BookKeeper Prometheus metrics for operational visibility.
  name: Grafana
jsonld:
- class_count: 9
  name: Apache Bookkeeper Context
  property_count: 23
  slug: apache-bookkeeper-context
layout: provider
modified: '2026-04-19'
name: Apache BookKeeper
rules:
- name: Apache BookKeeper API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 8
  slug: apache-bookkeeper-spectral-rules
skills: []
slug: apache-bookkeeper
solutions: []
tags:
- Apache
- Distributed Systems
- Log Storage
- Open Source
- Storage
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/apache-bookkeeper/refs/heads/main/apis.yml
use_cases:
- description: Serve as the replicated, durable write-ahead log for Apache Pulsar topics and distributed streaming systems.
  name: Durable Log Storage
- description: Store distributed transaction log segments for systems requiring exactly-once semantics and durable commit records.
  name: Distributed Transaction Logs
- description: Persist metadata and configuration data for distributed systems requiring consistent, replicated storage.
  name: Metadata Store
- description: Provide low-latency, high-throughput sequential storage for real-time stream processing pipelines.
  name: Stream Processing Storage
- description: Monitor and manage BookKeeper clusters using the HTTP Admin API for operational visibility and recovery.
  name: Cluster Administration
---
