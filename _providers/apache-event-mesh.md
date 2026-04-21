---
api_count: 2
apis:
- description: HTTP endpoints for managing the EventMesh runtime including topic management, subscription management, event publishing via HTTP, client monitoring, and runtime metrics.
  name: Apache EventMesh Admin API
  slug: eventmesh-admin-api
- description: Event-driven messaging via TCP, HTTP, and gRPC protocols. Events follow the CloudEvents specification. Supports pub-sub, request-reply, and broadcast messaging patterns.
  name: Apache EventMesh Messaging API
  slug: eventmesh-messaging-api
asyncapis:
- description: Apache EventMesh provides event-driven messaging via multiple protocols including TCP, HTTP, and gRPC. Events follow the CloudEvents specification. EventMesh decouples event producers and consumers, s
  name: Apache EventMesh Messaging API
  slug: eventmesh-messaging
capabilities:
- description: Unified capability for event-driven architectures using Apache EventMesh — managing topics, subscriptions, and publishing CloudEvents. Designed for platform engineers and developers building distribut
  name: Apache EventMesh Event Streaming
  slug: eventmesh-event-streaming
common:
- title: ''
  type: Documentation
  url: https://eventmesh.apache.org/docs/introduction
- title: ''
  type: GettingStarted
  url: https://eventmesh.apache.org/docs/instruction/quickstart
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/eventmesh
- title: ''
  type: Blog
  url: https://eventmesh.apache.org/blog
- title: ''
  type: Support
  url: https://eventmesh.apache.org/community
- title: ''
  type: SpectralRules
  url: rules/apache-event-mesh-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-event-mesh-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/eventmesh-event-streaming.yaml
created: '2026-03-26'
description: Apache EventMesh is a dynamic event-driven application runtime used to decouple the application and backend middleware layer, providing a serverless platform for building distributed event-driven architectures with support for CloudEvents and multiple messaging protocols including HTTP, TCP, and gRPC.
features:
- description: Native CloudEvents specification support for standardized event envelopes across all messaging protocols.
  name: CloudEvents Support
- description: Support for HTTP, TCP, and gRPC messaging protocols enabling flexible client connectivity.
  name: Multi-Protocol Messaging
- description: Publish-subscribe messaging pattern with topic-based routing for event-driven architectures.
  name: Pub-Sub Messaging
- description: Synchronous request-reply messaging over asynchronous infrastructure for RPC-style interactions.
  name: Request-Reply Pattern
- description: Durable event storage with replay capability for reliable event delivery and audit trails.
  name: Event Store
- description: Event-driven workflow engine for coordinating distributed business processes and sagas.
  name: Workflow Orchestration
- description: Pluggable connector model supporting Kafka, RocketMQ, Pulsar, and other messaging backends.
  name: Multi-Runtime Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Kafka connector for event streaming with durable storage and consumer groups.
  name: Apache Kafka
- description: RocketMQ connector for high-throughput message queueing and topic management.
  name: Apache RocketMQ
- description: Pulsar connector for multi-tenant event streaming with geo-replication.
  name: Apache Pulsar
- description: Cloud-native deployment on Kubernetes with operator support for cluster management.
  name: Kubernetes
jsonld:
- class_count: 5
  name: Apache Event Mesh Admin Context
  property_count: 21
  slug: apache-event-mesh-admin-context
layout: provider
modified: '2026-04-19'
name: Apache EventMesh
rules:
- name: Apache EventMesh API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: apache-event-mesh-spectral-rules
skills: []
slug: apache-event-mesh
solutions: []
tags:
- Apache
- CloudEvents
- Event-Driven
- Messaging
- Open Source
- Pub-Sub
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/apis.yml
use_cases:
- description: Decouple microservices through asynchronous event-driven communication reducing direct service dependencies.
  name: Microservices Decoupling
- description: Build scalable event streaming pipelines with durable delivery and replay capabilities.
  name: Event Streaming Pipelines
- description: Orchestrate distributed business processes using event-driven saga and choreography patterns.
  name: Distributed Workflows
- description: Ingest and process high-volume IoT device events through standardized CloudEvents format.
  name: IoT Event Ingestion
---
