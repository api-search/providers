---
api_count: 4
apis:
- description: 'Akka Management provides a suite of utilities for operating Akka-based distributed systems, including an HTTP management API for cluster management, health checks, and cluster bootstrap. The HTTP API '
  name: Akka Management
  slug: akka-management
- description: Akka HTTP is a full HTTP stack (client and server-side) built on Akka actors and streams. It provides a routing DSL for building REST and WebSocket services, with built-in JSON marshalling, TLS suppor
  name: Akka HTTP
  slug: akka-http
- description: Akka Streams is a library to process and transfer a sequence of elements using bounded buffer space, implementing the Reactive Streams specification for asynchronous stream processing with non-blockin
  name: Akka Streams
  slug: akka-streams
- description: Akka gRPC provides support for building streaming gRPC servers and clients on top of Akka Streams, with code generation from protobuf definitions for both Java and Scala.
  name: Akka gRPC
  slug: akka-grpc
capabilities:
- description: Workflow for monitoring and managing Akka cluster operations including health checks, member management, and cluster bootstrap. For platform engineers and SREs operating distributed Akka systems.
  name: Akka Cluster Operations
  slug: cluster-operations
common:
- title: ''
  type: Website
  url: https://akka.io/
- title: ''
  type: Documentation
  url: https://doc.akka.io/
- title: ''
  type: GettingStarted
  url: https://doc.akka.io/libraries/akka/current/typed/guide/introduction.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/akka
- title: ''
  type: Blog
  url: https://akka.io/blog/
- title: ''
  type: Pricing
  url: https://akka.io/pricing/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/json-schema/akka-config.json
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/rules/akka-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/vocabulary/akka-vocabulary.yaml
created: '2026-03-26'
description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of libraries including actors, HTTP, streams, cluster, persistence, and gRPC for building reactive, microservice-based architectures.
features:
- description: Lightweight concurrent entities (actors) that communicate via asynchronous message passing, enabling high-throughput distributed computation.
  name: Actor Model
- description: Distributes actors across a cluster and automatically rebalances them when nodes join or leave the cluster.
  name: Cluster Sharding
- description: Durable actor state through event sourcing with pluggable journal backends (Cassandra, PostgreSQL, DynamoDB, etc.).
  name: Persistence and Event Sourcing
- description: Conflict-free replicated data types (CRDTs) for sharing data across cluster nodes without coordination overhead.
  name: Distributed Data
- description: Full HTTP/1.1 and HTTP/2 server and client stack with routing DSL, JSON support, and WebSocket upgrades.
  name: HTTP and WebSocket
- description: Backpressure-aware stream processing compliant with the Reactive Streams specification, integrating with RxJava, Project Reactor, and others.
  name: Reactive Streams
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Alpakka Kafka connector for consuming and producing Kafka messages
  name: Apache Kafka
- description: Alpakka Cassandra connector and Akka Persistence journal
  name: Cassandra
- description: Alpakka connectors for S3, SQS, SNS, DynamoDB, and other AWS services
  name: AWS
- description: Akka gRPC for code generation from protobuf and streaming gRPC services
  name: gRPC
- description: Integration with Spring Boot for mixed Akka and Spring applications
  name: Spring Boot
jsonld:
- class_count: 2
  name: Akka Context
  property_count: 7
  slug: akka-context
layout: provider
modified: '2026-04-19'
name: Akka
rules:
- name: Akka API Rules
  rule_count: 12
  severity_counts:
    error: 7
    hint: 0
    info: 1
    warn: 4
  slug: akka-spectral-rules
skills: []
slug: akka
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: akka\nname: Akka\ndescription: >-\n  Akka is a toolkit and runtime for building highly concurrent, distributed,\n  and resilient message-driven applications on the JVM using the actor model\n  for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive\n  set of libraries including actors, HTTP, streams, cluster, persistence, and\n  gRPC for building reactive, microservice-based architectures.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Actor Model\n  - Distributed Systems\n  - Frameworks\n  - Java\n  - Microservices\n  - Reactive\n  - Scala\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: akka:akka-management\n    name: Akka Management\n    description: >-\n      Akka Management provides a suite of utilities for operating Akka-based\n      distributed systems,\
  \ including an HTTP management API for cluster\n      management, health checks, and cluster bootstrap. The HTTP API exposes\n      endpoints for liveness probes, readiness probes, cluster member\n      management, and seed node discovery.\n    humanURL: https://doc.akka.io/libraries/akka-management/current/\n    tags:\n      - Actor Model\n      - Cluster Management\n      - Distributed Systems\n      - Health Checks\n    properties:\n      - type: Documentation\n        url: https://doc.akka.io/libraries/akka-management/current/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/openapi/akka-management.json\n  - aid: akka:akka-http\n    name: Akka HTTP\n    description: >-\n      Akka HTTP is a full HTTP stack (client and server-side) built on Akka\n      actors and streams. It provides a routing DSL for building REST and\n      WebSocket services, with built-in JSON marshalling, TLS support, and\n      HTTP/2 capabilities.\n\
  \    humanURL: https://doc.akka.io/libraries/akka-http/current/\n    tags:\n      - HTTP\n      - REST API\n      - Reactive\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://doc.akka.io/libraries/akka-http/current/\n      - type: GettingStarted\n        url: https://doc.akka.io/libraries/akka-http/current/introduction.html\n  - aid: akka:akka-streams\n    name: Akka Streams\n    description: >-\n      Akka Streams is a library to process and transfer a sequence of elements\n      using bounded buffer space, implementing the Reactive Streams specification\n      for asynchronous stream processing with non-blocking backpressure.\n    humanURL: https://doc.akka.io/libraries/akka/current/stream/index.html\n    tags:\n      - Backpressure\n      - Data Streaming\n      - Reactive\n      - Reactive Streams\n    properties:\n      - type: Documentation\n        url: https://doc.akka.io/libraries/akka/current/stream/index.html\n  - aid: akka:akka-grpc\n  \
  \  name: Akka gRPC\n    description: >-\n      Akka gRPC provides support for building streaming gRPC servers and clients\n      on top of Akka Streams, with code generation from protobuf definitions\n      for both Java and Scala.\n    humanURL: https://doc.akka.io/libraries/akka-grpc/current/\n    tags:\n      - gRPC\n      - Protobuf\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://doc.akka.io/libraries/akka-grpc/current/\ncommon:\n  - type: Website\n    url: https://akka.io/\n  - type: Documentation\n    url: https://doc.akka.io/\n  - type: GettingStarted\n    url: https://doc.akka.io/libraries/akka/current/typed/guide/introduction.html\n  - type: GitHubOrganization\n    url: https://github.com/akka\n  - type: Blog\n    url: https://akka.io/blog/\n  - type: Pricing\n    url: https://akka.io/pricing/\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/json-schema/akka-config.json\n  - type:\
  \ SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/rules/akka-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/vocabulary/akka-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Actor Model\n        description: >-\n          Lightweight concurrent entities (actors) that communicate via\n          asynchronous message passing, enabling high-throughput distributed\n          computation.\n      - name: Cluster Sharding\n        description: >-\n          Distributes actors across a cluster and automatically rebalances them\n          when nodes join or leave the cluster.\n      - name: Persistence and Event Sourcing\n        description: >-\n          Durable actor state through event sourcing with pluggable journal\n          backends (Cassandra, PostgreSQL, DynamoDB, etc.).\n      - name: Distributed Data\n        description: >-\n       \
  \   Conflict-free replicated data types (CRDTs) for sharing data across\n          cluster nodes without coordination overhead.\n      - name: HTTP and WebSocket\n        description: >-\n          Full HTTP/1.1 and HTTP/2 server and client stack with routing DSL,\n          JSON support, and WebSocket upgrades.\n      - name: Reactive Streams\n        description: >-\n          Backpressure-aware stream processing compliant with the Reactive\n          Streams specification, integrating with RxJava, Project Reactor, and\n          others.\n  - type: UseCases\n    data:\n      - name: Microservices\n        description: >-\n          Teams build resilient, location-transparent microservices using Akka\n          actors and HTTP with built-in backpressure and supervision.\n      - name: Real-Time Data Processing\n        description: >-\n          Organizations process high-throughput event streams using Akka Streams\n          with exactly-once processing guarantees.\n      - name: Distributed\
  \ State Management\n        description: >-\n          Applications maintain distributed mutable state using cluster sharding\n          and distributed data without external coordination systems.\n      - name: Event Sourcing\n        description: >-\n          Systems implement event sourcing and CQRS patterns using Akka\n          Persistence with pluggable journal backends.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: Alpakka Kafka connector for consuming and producing Kafka messages\n      - name: Cassandra\n        description: Alpakka Cassandra connector and Akka Persistence journal\n      - name: AWS\n        description: Alpakka connectors for S3, SQS, SNS, DynamoDB, and other AWS services\n      - name: gRPC\n        description: Akka gRPC for code generation from protobuf and streaming gRPC services\n      - name: Spring Boot\n        description: Integration with Spring Boot for mixed Akka and Spring applications\nmaintainers:\n  - FN:\
  \ Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/apis.yml
tags:
- Actor Model
- Distributed Systems
- Frameworks
- Java
- Microservices
- Reactive
- Scala
url: https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/apis.yml
use_cases:
- description: Teams build resilient, location-transparent microservices using Akka actors and HTTP with built-in backpressure and supervision.
  name: Microservices
- description: Organizations process high-throughput event streams using Akka Streams with exactly-once processing guarantees.
  name: Real-Time Data Processing
- description: Applications maintain distributed mutable state using cluster sharding and distributed data without external coordination systems.
  name: Distributed State Management
- description: Systems implement event sourcing and CQRS patterns using Akka Persistence with pluggable journal backends.
  name: Event Sourcing
---
