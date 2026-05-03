---
api_count: 8
api_specs:
- filename: openapi.yml
  format: yaml
  label: Temporal API
  slug: temporal
  spec_type: OpenAPI
  url: https://github.com/temporalio/api/blob/master/openapi/openapi.yml
apis:
- description: Backstage by Spotify provides a software catalog API and developer portal platform for managing all software components, services, websites, and infrastructure at scale. Its catalog API enables regist
  name: Backstage Software Catalog API
  slug: backstage
- description: CloudEvents is a CNCF specification for describing event data in a common way. It defines a core data model and HTTP, AMQP, MQTT, and Kafka bindings enabling interoperable event-driven system design a
  name: CloudEvents API
  slug: cloudevents
- description: Apache Kafka's Admin REST API enables creating and managing topics, partitions, consumer groups, and cluster configurations for high-throughput event streaming pipelines used in scalable, event-driven
  name: Apache Kafka Admin API
  slug: kafka-admin
- description: NATS is a lightweight, high-performance messaging system for distributed applications. Its management API provides monitoring, subject inspection, and JetStream (persistent streams) management for bui
  name: NATS Management API
  slug: nats
- description: 'Temporal is a durable execution platform that provides an API for defining and running long-running, fault-tolerant workflows. Implements the saga pattern with full activity retry semantics, enabling '
  name: Temporal API
  slug: temporal
- description: Dapr (Distributed Application Runtime) provides building block APIs for service invocation, pub/sub messaging, state management, bindings, actors, and distributed tracing. Abstracts away infrastructur
  name: Dapr API
  slug: dapr
- description: OpenTelemetry provides vendor-neutral APIs, SDKs, and instrumentation for generating traces, metrics, and logs. Essential for observability in scalable distributed software systems, enabling performan
  name: OpenTelemetry API
  slug: opentelemetry
- description: Argo CD provides a declarative GitOps continuous delivery API for Kubernetes applications. Enables teams to manage application deployments at scale using Git as the source of truth for system state.
  name: Argo CD API
  slug: argocd
common:
- title: ''
  type: Guide
  url: https://microservices.io/patterns/data/cqrs.html
- title: ''
  type: Guide
  url: https://microservices.io/patterns/data/event-sourcing.html
- title: ''
  type: Guide
  url: https://microservices.io/patterns/data/saga.html
- title: ''
  type: Guide
  url: https://www.cncf.io/projects/
- title: ''
  type: Guide
  url: https://12factor.net/
- title: ''
  type: JSONSchema
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-schema/scalable-software-and-systems-event-schema.json
- title: ''
  type: JSONStructure
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-structure/scalable-software-and-systems-event-structure.json
- title: ''
  type: JSONLDContext
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-ld/scalable-software-and-systems-context.jsonld
- title: ''
  type: Vocabulary
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/vocabulary/scalable-software-and-systems-vocabulary.yml
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-order-placed-event-example.json
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-temporal-workflow-example.json
created: '2025-01-20'
description: A topic collection exploring the APIs, design patterns, frameworks, and platforms that enable scalable software and systems engineering. Covers architectural patterns such as CQRS, event sourcing, saga, MACH architecture, API-first design, and modular monoliths, as well as the tooling ecosystems that support building maintainable, high-scale software. Relevant to software architects, platform teams, and senior engineers building enterprise-grade distributed systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Scalable Software And Systems Context
  property_count: 0
  slug: scalable-software-and-systems-context
layout: provider
modified: '2026-05-02'
name: Scalable Software and Systems
skills: []
slug: scalable-software-and-systems
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scalable-software-and-systems\nname: Scalable Software and Systems\ndescription: >-\n  A topic collection exploring the APIs, design patterns, frameworks, and\n  platforms that enable scalable software and systems engineering. Covers\n  architectural patterns such as CQRS, event sourcing, saga, MACH architecture,\n  API-first design, and modular monoliths, as well as the tooling ecosystems\n  that support building maintainable, high-scale software. Relevant to software\n  architects, platform teams, and senior engineers building enterprise-grade\n  distributed systems.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API First\n  - Architecture Patterns\n  - CQRS\n  - Distributed Systems\n  - Enterprise\n  - Event Driven\n  - Microservices\n  - Scalable Architecture\n  - Software Engineering\n  - Systems Design\ntype: Index\ncreated: '2025-01-20'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scalable-software-and-systems:backstage\n\
  \    name: Backstage Software Catalog API\n    description: >-\n      Backstage by Spotify provides a software catalog API and developer portal\n      platform for managing all software components, services, websites, and\n      infrastructure at scale. Its catalog API enables registering, tracking,\n      and discovering software components across an organization.\n    tags:\n      - Developer Portal\n      - Internal Developer Platform\n      - Software Catalog\n      - Systems Design\n    humanURL: https://backstage.io/docs/features/software-catalog/software-catalog-api\n    properties:\n      - type: Documentation\n        url: https://backstage.io/docs/features/software-catalog/software-catalog-api\n      - type: GitHub\n        url: https://github.com/backstage/backstage\n  - aid: scalable-software-and-systems:cloudevents\n    name: CloudEvents API\n    description: >-\n      CloudEvents is a CNCF specification for describing event data in a common\n      way. It defines a core data\
  \ model and HTTP, AMQP, MQTT, and Kafka bindings\n      enabling interoperable event-driven system design across cloud providers\n      and middleware.\n    tags:\n      - CNCF\n      - Event Driven\n      - Events\n      - Integration\n      - Standards\n    humanURL: https://cloudevents.io/\n    properties:\n      - type: Documentation\n        url: https://cloudevents.io/\n      - type: GitHub\n        url: https://github.com/cloudevents/spec\n      - type: Specification\n        url: https://github.com/cloudevents/spec/blob/main/cloudevents/spec.md\n  - aid: scalable-software-and-systems:kafka-admin\n    name: Apache Kafka Admin API\n    description: >-\n      Apache Kafka's Admin REST API enables creating and managing topics,\n      partitions, consumer groups, and cluster configurations for high-throughput\n      event streaming pipelines used in scalable, event-driven architectures.\n    tags:\n      - Event Driven\n      - Event Streaming\n      - High Throughput\n      - Messaging\n\
  \    humanURL: https://kafka.apache.org/documentation/\n    properties:\n      - type: Documentation\n        url: https://kafka.apache.org/documentation/\n      - type: GitHub\n        url: https://github.com/apache/kafka\n  - aid: scalable-software-and-systems:nats\n    name: NATS Management API\n    description: >-\n      NATS is a lightweight, high-performance messaging system for distributed\n      applications. Its management API provides monitoring, subject inspection,\n      and JetStream (persistent streams) management for building scalable\n      event-driven systems.\n    tags:\n      - Cloud Native\n      - Event Driven\n      - High Performance\n      - Messaging\n      - Microservices\n    humanURL: https://docs.nats.io/\n    properties:\n      - type: Documentation\n        url: https://docs.nats.io/\n      - type: GitHub\n        url: https://github.com/nats-io/nats-server\n  - aid: scalable-software-and-systems:temporal\n    name: Temporal API\n    description: >-\n  \
  \    Temporal is a durable execution platform that provides an API for\n      defining and running long-running, fault-tolerant workflows. Implements\n      the saga pattern with full activity retry semantics, enabling reliable\n      orchestration in distributed systems.\n    tags:\n      - Distributed Systems\n      - Durable Execution\n      - Saga Pattern\n      - Workflow Orchestration\n    humanURL: https://docs.temporal.io/\n    properties:\n      - type: Documentation\n        url: https://docs.temporal.io/\n      - type: GitHub\n        url: https://github.com/temporalio/temporal\n      - type: OpenAPI\n        url: https://github.com/temporalio/api/blob/master/openapi/openapi.yml\n  - aid: scalable-software-and-systems:dapr\n    name: Dapr API\n    description: >-\n      Dapr (Distributed Application Runtime) provides building block APIs\n      for service invocation, pub/sub messaging, state management, bindings,\n      actors, and distributed tracing. Abstracts away infrastructure\
  \ complexity\n      for portable, scalable software.\n    tags:\n      - Distributed Systems\n      - Event Driven\n      - Microservices\n      - Scalable Architecture\n    humanURL: https://docs.dapr.io/reference/api/\n    properties:\n      - type: Documentation\n        url: https://docs.dapr.io/reference/api/\n      - type: GitHub\n        url: https://github.com/dapr/dapr\n  - aid: scalable-software-and-systems:opentelemetry\n    name: OpenTelemetry API\n    description: >-\n      OpenTelemetry provides vendor-neutral APIs, SDKs, and instrumentation\n      for generating traces, metrics, and logs. Essential for observability in\n      scalable distributed software systems, enabling performance analysis and\n      root cause diagnosis.\n    tags:\n      - Distributed Tracing\n      - Logs\n      - Metrics\n      - Observability\n      - Telemetry\n    humanURL: https://opentelemetry.io/docs/\n    properties:\n      - type: Documentation\n        url: https://opentelemetry.io/docs/\n\
  \      - type: GitHub\n        url: https://github.com/open-telemetry/opentelemetry-specification\n  - aid: scalable-software-and-systems:argocd\n    name: Argo CD API\n    description: >-\n      Argo CD provides a declarative GitOps continuous delivery API for\n      Kubernetes applications. Enables teams to manage application deployments\n      at scale using Git as the source of truth for system state.\n    tags:\n      - CD\n      - GitOps\n      - Kubernetes\n      - Platform Engineering\n    humanURL: https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/\n    properties:\n      - type: Documentation\n        url: https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/\n      - type: GitHub\n        url: https://github.com/argoproj/argo-cd\ncommon:\n  - type: Guide\n    url: https://microservices.io/patterns/data/cqrs.html\n    name: CQRS Pattern\n  - type: Guide\n    url: https://microservices.io/patterns/data/event-sourcing.html\n    name: Event Sourcing\
  \ Pattern\n  - type: Guide\n    url: https://microservices.io/patterns/data/saga.html\n    name: Saga Pattern\n  - type: Guide\n    url: https://www.cncf.io/projects/\n    name: CNCF Projects Landscape\n  - type: Guide\n    url: https://12factor.net/\n    name: The Twelve-Factor App\n  - type: JSONSchema\n    url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-schema/scalable-software-and-systems-event-schema.json\n    name: Domain Event JSON Schema\n  - type: JSONStructure\n    url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-structure/scalable-software-and-systems-event-structure.json\n    name: Domain Event JSON Structure\n  - type: JSONLDContext\n    url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-ld/scalable-software-and-systems-context.jsonld\n    name: Scalable Software and Systems JSON-LD Context\n  - type: Vocabulary\n    url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/vocabulary/scalable-software-and-systems-vocabulary.yml\n\
  \    name: Scalable Software and Systems Vocabulary\n  - type: Examples\n    url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-order-placed-event-example.json\n    name: Order Placed Event Example\n  - type: Examples\n    url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-temporal-workflow-example.json\n    name: Temporal Order Saga Workflow Example\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalable-software-and-systems/refs/heads/main/apis.yml
tags:
- API First
- Architecture Patterns
- CQRS
- Distributed Systems
- Enterprise
- Event Driven
- Microservices
- Scalable Architecture
- Software Engineering
- Systems Design
url: ''
use_cases: []
---
