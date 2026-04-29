---
api_count: 2
api_specs:
- filename: eventmesh-admin.yml
  format: yaml
  label: Apache EventMesh Admin API
  slug: eventmesh-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/openapi/eventmesh-admin.yml
- filename: eventmesh-messaging.yml
  format: yaml
  label: Apache EventMesh Messaging API
  slug: eventmesh-messaging-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/asyncapi/eventmesh-messaging.yml
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
source_filename: apis.yml
source_yaml: "aid: apache-event-mesh\nname: Apache EventMesh\ndescription: >-\n  Apache EventMesh is a dynamic event-driven application runtime used to decouple the application and backend middleware layer, providing a serverless platform for building distributed event-driven architectures with support for CloudEvents and multiple messaging protocols including HTTP, TCP, and gRPC.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - CloudEvents\n  - Event-Driven\n  - Messaging\n  - Open Source\n  - Pub-Sub\n  - Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apache-event-mesh:eventmesh-admin-api\n    name: Apache EventMesh Admin API\n    description: >-\n      HTTP endpoints for managing the EventMesh runtime including topic management, subscription management, event\
  \ publishing via HTTP, client monitoring, and runtime metrics.\n    humanURL: https://eventmesh.apache.org/docs/instruction/quickstart\n    baseURL: http://localhost:10106\n    tags:\n      - Admin\n      - CloudEvents\n      - REST API\n      - Topics\n    properties:\n      - type: Documentation\n        url: https://eventmesh.apache.org/docs/introduction\n      - type: OpenAPI\n        url: openapi/eventmesh-admin.yml\n      - type: JSONSchema\n        url: json-schema/eventmesh-admin-cloud-event-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-event-mesh-admin-context.jsonld\n  - aid: apache-event-mesh:eventmesh-messaging-api\n    name: Apache EventMesh Messaging API\n    description: >-\n      Event-driven messaging via TCP, HTTP, and gRPC protocols. Events follow the CloudEvents specification. Supports pub-sub, request-reply, and broadcast messaging patterns.\n    humanURL: https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage\n    tags:\n      - CloudEvents\n \
  \     - Event-Driven\n      - Messaging\n      - Pub-Sub\n    properties:\n      - type: Documentation\n        url: https://eventmesh.apache.org/docs/sdk-java/tcp-sdk-usage\n      - type: AsyncAPI\n        url: asyncapi/eventmesh-messaging.yml\ncommon:\n  - type: Documentation\n    url: https://eventmesh.apache.org/docs/introduction\n  - type: GettingStarted\n    url: https://eventmesh.apache.org/docs/instruction/quickstart\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/eventmesh\n  - type: Blog\n    url: https://eventmesh.apache.org/blog\n  - type: Support\n    url: https://eventmesh.apache.org/community\n  - type: SpectralRules\n    url: rules/apache-event-mesh-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-event-mesh-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/eventmesh-event-streaming.yaml\n  - type: Features\n    data:\n      - name: CloudEvents Support\n\
  \        description: Native CloudEvents specification support for standardized event envelopes across all messaging protocols.\n      - name: Multi-Protocol Messaging\n        description: Support for HTTP, TCP, and gRPC messaging protocols enabling flexible client connectivity.\n      - name: Pub-Sub Messaging\n        description: Publish-subscribe messaging pattern with topic-based routing for event-driven architectures.\n      - name: Request-Reply Pattern\n        description: Synchronous request-reply messaging over asynchronous infrastructure for RPC-style interactions.\n      - name: Event Store\n        description: Durable event storage with replay capability for reliable event delivery and audit trails.\n      - name: Workflow Orchestration\n        description: Event-driven workflow engine for coordinating distributed business processes and sagas.\n      - name: Multi-Runtime Support\n        description: Pluggable connector model supporting Kafka, RocketMQ, Pulsar, and other\
  \ messaging backends.\n  - type: UseCases\n    data:\n      - name: Microservices Decoupling\n        description: Decouple microservices through asynchronous event-driven communication reducing direct service dependencies.\n      - name: Event Streaming Pipelines\n        description: Build scalable event streaming pipelines with durable delivery and replay capabilities.\n      - name: Distributed Workflows\n        description: Orchestrate distributed business processes using event-driven saga and choreography patterns.\n      - name: IoT Event Ingestion\n        description: Ingest and process high-volume IoT device events through standardized CloudEvents format.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: Kafka connector for event streaming with durable storage and consumer groups.\n      - name: Apache RocketMQ\n        description: RocketMQ connector for high-throughput message queueing and topic management.\n      - name: Apache Pulsar\n\
  \        description: Pulsar connector for multi-tenant event streaming with geo-replication.\n      - name: Kubernetes\n        description: Cloud-native deployment on Kubernetes with operator support for cluster management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/apis.yml
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
