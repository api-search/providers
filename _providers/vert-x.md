---
api_count: 7
apis:
- description: The core toolkit for building reactive, event-driven applications on the JVM. Provides the event loop, verticle deployment, event bus, HTTP server and client, TCP/UDP networking, and the fundamental a
  name: Vert.x Core
  slug: vert-x-core
- description: A set of building blocks for building web applications and RESTful HTTP microservices with Vert.x. Provides routing, request handling, session management, template engine support, and WebSocket handli
  name: Vert.x Web
  slug: vertx-web
- description: Vert.x OpenAPI provides OpenAPI 3.1 specification support for Vert.x, enabling contract-driven API development with automatic request/response validation, routing, and API specification serving for Ve
  name: Vert.x OpenAPI
  slug: vertx-openapi
- description: A Vert.x-native gRPC implementation providing a reactive, non-blocking gRPC client and server built on top of Vert.x HTTP/2. Supports protobuf service definitions with Vert.x Future and stream-based A
  name: Vert.x gRPC
  slug: vertx-grpc
- description: 'A high-performance reactive SQL client for Vert.x supporting PostgreSQL, MySQL, Microsoft SQL Server, IBM DB2, and Oracle databases. Provides a non-blocking, fully reactive API for executing queries, '
  name: Vert.x SQL Client
  slug: vertx-sql-client
- description: Authentication and authorization support for Vert.x applications. Provides JWT, OAuth2, JDBC, MongoDB, and WebAuthn/FIDO2 authentication providers with a unified async security API that integrates wit
  name: Vert.x Auth
  slug: vertx-auth
- description: 'A Vert.x component for implementing health check endpoints for Kubernetes liveness and readiness probes. Provides a composable health procedure mechanism that aggregates multiple health checks into a '
  name: Vert.x Health Check
  slug: vertx-health-check
common:
- title: ''
  type: Website
  url: https://vertx.io/
- title: ''
  type: Documentation
  url: https://vertx.io/docs/
- title: ''
  type: GettingStarted
  url: https://vertx.io/get-started/
- title: ''
  type: GitHubOrganization
  url: https://github.com/eclipse-vertx
- title: ''
  type: Blog
  url: https://vertx.io/blog/
- title: ''
  type: PrivacyPolicy
  url: https://www.eclipse.org/legal/privacy.php
- title: ''
  type: TermsOfService
  url: https://www.eclipse.org/legal/termsofuse.php
- title: ''
  type: License
  url: https://www.eclipse.org/legal/epl-2.0/
- title: ''
  type: Changelog
  url: https://github.com/eclipse-vertx/vert.x/blob/master/CHANGELOG.adoc
- title: ''
  type: MavenCentral
  url: https://central.sonatype.com/search?q=io.vertx
- title: ''
  type: Forums
  url: https://groups.google.com/forum/#!forum/vertx
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/vert.x
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/vocabulary/vert-x-vocabulary.yaml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/rules/vert-x-spectral-rules.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-ld/vert-x-context.jsonld
created: '2026-03-26'
description: Eclipse Vert.x is a toolkit for building reactive applications on the JVM, providing support for multiple languages including Java, JavaScript, Groovy, Ruby, and Kotlin with an event-driven, non-blocking architecture. Part of the Eclipse Foundation under the Eclipse Public License 2.0. Vert.x follows a polyglot, unopinionated model allowing developers to build microservices, web applications, IoT backends, and event-driven systems with high concurrency using a small memory footprint.
features:
- description: Non-blocking event loop model with verticles for concurrent request handling without traditional threading overhead.
  name: Event-Driven Architecture
- description: Write Vert.x applications in Java, JavaScript, Groovy, Kotlin, Scala, and Ruby on the same JVM platform.
  name: Polyglot Support
- description: Distributed message-passing backbone enabling communication between verticles across nodes in a cluster.
  name: Event Bus
- description: High-performance HTTP/1.1 and HTTP/2 server and client with WebSocket, SSE, and gRPC support.
  name: Reactive HTTP Client and Server
- description: Automatic request and response validation against OpenAPI 3.1 specifications using vertx-openapi.
  name: OpenAPI Contract Validation
- description: Non-blocking, fully reactive SQL clients for PostgreSQL, MySQL, MSSQL, DB2, and Oracle.
  name: Reactive SQL Clients
- description: Pluggable security providers for JWT, OAuth2, JDBC, MongoDB, LDAP, and WebAuthn/FIDO2.
  name: Authentication and Authorization
- description: Composable health check procedures for Kubernetes liveness and readiness probe endpoints.
  name: Health Checks
- description: Built-in cluster support via Hazelcast, Infinispan, Zookeeper, or Apache Ignite for distributed deployments.
  name: Clustering
- description: Java 21 virtual thread support enabling synchronous-style code in Vert.x worker verticles.
  name: Virtual Threads
image: https://vertx.io/images/logo-wide.png
integrations:
- description: Vert.x is the reactive engine underlying Quarkus, providing the event loop and HTTP server for Quarkus applications.
  name: Quarkus
- description: Deploy Vert.x verticles on Kubernetes with health check endpoints, clustering, and horizontal pod autoscaling.
  name: Kubernetes
- description: Vert.x Kafka Client provides reactive, non-blocking Kafka producer and consumer integration.
  name: Apache Kafka
- description: Vert.x Redis Client enables async Redis operations for caching, pub/sub, and session storage.
  name: Redis
- description: Hazelcast cluster manager for distributed Vert.x deployments with shared data and event bus clustering.
  name: Hazelcast
- description: Vert.x Micrometer Metrics provides application metrics integration with Prometheus and Grafana.
  name: Micrometer
jsonld:
- class_count: 7
  name: Vert X Context
  property_count: 44
  slug: vert-x-context
layout: provider
modified: '2026-05-03'
name: Vert.x
rules:
- name: Vert.x API Rules
  rule_count: 26
  severity_counts:
    error: 7
    hint: 4
    info: 0
    warn: 15
  slug: vert-x-spectral-rules
skills: []
slug: vert-x
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vert-x\nname: Vert.x\ndescription: >-\n  Eclipse Vert.x is a toolkit for building reactive applications on the JVM,\n  providing support for multiple languages including Java, JavaScript, Groovy,\n  Ruby, and Kotlin with an event-driven, non-blocking architecture. Part of the\n  Eclipse Foundation under the Eclipse Public License 2.0. Vert.x follows a\n  polyglot, unopinionated model allowing developers to build microservices, web\n  applications, IoT backends, and event-driven systems with high concurrency\n  using a small memory footprint.\ntype: Index\nimage: https://vertx.io/images/logo-wide.png\ntags:\n  - Event-Driven\n  - Frameworks\n  - Java\n  - JVM\n  - Microservices\n  - Polyglot\n  - Reactive\n  - Eclipse Foundation\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vert-x:vert-x-core\n    name: Vert.x Core\n\
  \    description: >-\n      The core toolkit for building reactive, event-driven applications on the\n      JVM. Provides the event loop, verticle deployment, event bus, HTTP server\n      and client, TCP/UDP networking, and the fundamental async programming model\n      used by all Vert.x components.\n    humanURL: https://vertx.io/docs/vertx-core/java/\n    tags:\n      - Event-Driven\n      - Event Loop\n      - Verticles\n      - Event Bus\n      - Reactive\n      - JVM\n    properties:\n      - type: Documentation\n        url: https://vertx.io/docs/vertx-core/java/\n      - type: GettingStarted\n        url: https://vertx.io/get-started/\n      - type: GitHubRepository\n        url: https://github.com/eclipse-vertx/vert.x\n      - type: MavenPackage\n        url: https://central.sonatype.com/artifact/io.vertx/vertx-core\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-schema/vertx-config.json\n    \
  \  - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-structure/vertx-config-structure.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-schema/vertx-deployment-descriptor.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-structure/vertx-deployment-descriptor-structure.json\n\n  - aid: vert-x:vertx-web\n    name: Vert.x Web\n    description: >-\n      A set of building blocks for building web applications and RESTful HTTP\n      microservices with Vert.x. Provides routing, request handling, session\n      management, template engine support, and WebSocket handling on top of\n      Vert.x Core HTTP server.\n    humanURL: https://vertx.io/docs/vertx-web/java/\n    tags:\n      - REST\n      - HTTP\n      - Web Framework\n      - Routing\n  \
  \    - WebSocket\n    properties:\n      - type: Documentation\n        url: https://vertx.io/docs/vertx-web/java/\n      - type: GitHubRepository\n        url: https://github.com/eclipse-vertx/vert.x\n      - type: MavenPackage\n        url: https://central.sonatype.com/artifact/io.vertx/vertx-web\n\n  - aid: vert-x:vertx-openapi\n    name: Vert.x OpenAPI\n    description: >-\n      Vert.x OpenAPI provides OpenAPI 3.1 specification support for Vert.x,\n      enabling contract-driven API development with automatic request/response\n      validation, routing, and API specification serving for Vert.x Web\n      applications.\n    humanURL: https://vertx.io/docs/vertx-openapi/java/\n    tags:\n      - OpenAPI\n      - API Specification\n      - Validation\n      - Contract-Driven\n    properties:\n      - type: Documentation\n        url: https://vertx.io/docs/vertx-openapi/java/\n      - type: GitHubRepository\n        url: https://github.com/eclipse-vertx/vertx-openapi\n      - type: MavenPackage\n\
  \        url: https://central.sonatype.com/artifact/io.vertx/vertx-openapi\n\n  - aid: vert-x:vertx-grpc\n    name: Vert.x gRPC\n    description: >-\n      A Vert.x-native gRPC implementation providing a reactive, non-blocking\n      gRPC client and server built on top of Vert.x HTTP/2. Supports protobuf\n      service definitions with Vert.x Future and stream-based APIs.\n    humanURL: https://vertx.io/docs/vertx-grpc/java/\n    tags:\n      - gRPC\n      - Protocol Buffers\n      - HTTP/2\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://vertx.io/docs/vertx-grpc/java/\n      - type: GitHubRepository\n        url: https://github.com/eclipse-vertx/vertx-grpc\n      - type: MavenPackage\n        url: https://central.sonatype.com/artifact/io.vertx/vertx-grpc\n\n  - aid: vert-x:vertx-sql-client\n    name: Vert.x SQL Client\n    description: >-\n      A high-performance reactive SQL client for Vert.x supporting PostgreSQL,\n      MySQL, Microsoft SQL Server,\
  \ IBM DB2, and Oracle databases. Provides a\n      non-blocking, fully reactive API for executing queries, transactions, and\n      batch operations.\n    humanURL: https://vertx.io/docs/vertx-pg-client/java/\n    tags:\n      - SQL\n      - Database\n      - PostgreSQL\n      - MySQL\n      - Reactive\n    properties:\n      - type: Documentation\n        url: https://vertx.io/docs/vertx-pg-client/java/\n      - type: GitHubRepository\n        url: https://github.com/eclipse-vertx/vertx-sql-client\n      - type: MavenPackage\n        url: https://central.sonatype.com/artifact/io.vertx/vertx-pg-client\n\n  - aid: vert-x:vertx-auth\n    name: Vert.x Auth\n    description: >-\n      Authentication and authorization support for Vert.x applications. Provides\n      JWT, OAuth2, JDBC, MongoDB, and WebAuthn/FIDO2 authentication providers\n      with a unified async security API that integrates with Vert.x Web routing.\n    humanURL: https://vertx.io/docs/vertx-auth-common/java/\n    tags:\n\
  \      - Authentication\n      - Authorization\n      - JWT\n      - OAuth2\n      - Security\n    properties:\n      - type: Documentation\n        url: https://vertx.io/docs/vertx-auth-common/java/\n      - type: GitHubRepository\n        url: https://github.com/eclipse-vertx/vertx-auth\n      - type: MavenPackage\n        url: https://central.sonatype.com/artifact/io.vertx/vertx-auth-common\n\n  - aid: vert-x:vertx-health-check\n    name: Vert.x Health Check\n    description: >-\n      A Vert.x component for implementing health check endpoints for Kubernetes\n      liveness and readiness probes. Provides a composable health procedure\n      mechanism that aggregates multiple health checks into a single HTTP\n      endpoint response.\n    humanURL: https://vertx.io/docs/vertx-health-check/java/\n    tags:\n      - Health Check\n      - Kubernetes\n      - Observability\n      - Liveness\n      - Readiness\n    properties:\n      - type: Documentation\n        url: https://vertx.io/docs/vertx-health-check/java/\n\
  \      - type: GitHubRepository\n        url: https://github.com/eclipse-vertx/vertx-health-check\n      - type: MavenPackage\n        url: https://central.sonatype.com/artifact/io.vertx/vertx-health-check\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-schema/vertx-health-check-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-structure/vertx-health-check-structure.json\n\ncommon:\n  - type: Website\n    url: https://vertx.io/\n  - type: Documentation\n    url: https://vertx.io/docs/\n  - type: GettingStarted\n    url: https://vertx.io/get-started/\n  - type: GitHubOrganization\n    url: https://github.com/eclipse-vertx\n  - type: Blog\n    url: https://vertx.io/blog/\n  - type: PrivacyPolicy\n    url: https://www.eclipse.org/legal/privacy.php\n  - type: TermsOfService\n    url: https://www.eclipse.org/legal/termsofuse.php\n\
  \  - type: License\n    url: https://www.eclipse.org/legal/epl-2.0/\n  - type: Changelog\n    url: https://github.com/eclipse-vertx/vert.x/blob/master/CHANGELOG.adoc\n  - type: MavenCentral\n    url: https://central.sonatype.com/search?q=io.vertx\n  - type: Forums\n    url: https://groups.google.com/forum/#!forum/vertx\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/vert.x\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/vocabulary/vert-x-vocabulary.yaml\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/rules/vert-x-spectral-rules.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-ld/vert-x-context.jsonld\n  - type: Features\n    data:\n      - name: Event-Driven Architecture\n        description: Non-blocking event loop model with verticles for concurrent\
  \ request handling without traditional threading overhead.\n      - name: Polyglot Support\n        description: Write Vert.x applications in Java, JavaScript, Groovy, Kotlin, Scala, and Ruby on the same JVM platform.\n      - name: Event Bus\n        description: Distributed message-passing backbone enabling communication between verticles across nodes in a cluster.\n      - name: Reactive HTTP Client and Server\n        description: High-performance HTTP/1.1 and HTTP/2 server and client with WebSocket, SSE, and gRPC support.\n      - name: OpenAPI Contract Validation\n        description: Automatic request and response validation against OpenAPI 3.1 specifications using vertx-openapi.\n      - name: Reactive SQL Clients\n        description: Non-blocking, fully reactive SQL clients for PostgreSQL, MySQL, MSSQL, DB2, and Oracle.\n      - name: Authentication and Authorization\n        description: Pluggable security providers for JWT, OAuth2, JDBC, MongoDB, LDAP, and WebAuthn/FIDO2.\n\
  \      - name: Health Checks\n        description: Composable health check procedures for Kubernetes liveness and readiness probe endpoints.\n      - name: Clustering\n        description: Built-in cluster support via Hazelcast, Infinispan, Zookeeper, or Apache Ignite for distributed deployments.\n      - name: Virtual Threads\n        description: Java 21 virtual thread support enabling synchronous-style code in Vert.x worker verticles.\n  - type: UseCases\n    data:\n      - name: Microservices Backend\n        description: Build lightweight, high-concurrency microservices with Vert.x Web routing, service proxy patterns, and event bus communication.\n      - name: API Gateway\n        description: Implement reactive API gateways using vertx-http-proxy with routing, authentication, and rate limiting.\n      - name: Real-Time Applications\n        description: Build WebSocket and SSE-based real-time applications for live dashboards, chat, and notification systems.\n      - name: IoT Data\
  \ Ingestion\n        description: Handle high-volume MQTT and TCP data streams from IoT devices using Vert.x non-blocking networking.\n      - name: Contract-First REST APIs\n        description: Develop OpenAPI 3.1 contract-first REST APIs with automatic validation using vertx-openapi and vertx-web.\n  - type: Integrations\n    data:\n      - name: Quarkus\n        description: Vert.x is the reactive engine underlying Quarkus, providing the event loop and HTTP server for Quarkus applications.\n      - name: Kubernetes\n        description: Deploy Vert.x verticles on Kubernetes with health check endpoints, clustering, and horizontal pod autoscaling.\n      - name: Apache Kafka\n        description: Vert.x Kafka Client provides reactive, non-blocking Kafka producer and consumer integration.\n      - name: Redis\n        description: Vert.x Redis Client enables async Redis operations for caching, pub/sub, and session storage.\n      - name: Hazelcast\n        description: Hazelcast cluster\
  \ manager for distributed Vert.x deployments with shared data and event bus clustering.\n      - name: Micrometer\n        description: Vert.x Micrometer Metrics provides application metrics integration with Prometheus and Grafana.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/apis.yml
tags:
- Event-Driven
- Frameworks
- Java
- JVM
- Microservices
- Polyglot
- Reactive
- Eclipse Foundation
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/apis.yml
use_cases:
- description: Build lightweight, high-concurrency microservices with Vert.x Web routing, service proxy patterns, and event bus communication.
  name: Microservices Backend
- description: Implement reactive API gateways using vertx-http-proxy with routing, authentication, and rate limiting.
  name: API Gateway
- description: Build WebSocket and SSE-based real-time applications for live dashboards, chat, and notification systems.
  name: Real-Time Applications
- description: Handle high-volume MQTT and TCP data streams from IoT devices using Vert.x non-blocking networking.
  name: IoT Data Ingestion
- description: Develop OpenAPI 3.1 contract-first REST APIs with automatic validation using vertx-openapi and vertx-web.
  name: Contract-First REST APIs
---
