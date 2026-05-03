---
api_count: 8
api_specs:
- filename: virtual_service.proto
  format: yaml
  label: Istio Service Mesh API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/istio/api/master/networking/v1alpha3/virtual_service.proto
- filename: api
  format: yaml
  label: Envoy Proxy Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/api
- filename: openapi.yaml
  format: yaml
  label: Apache Kafka REST Proxy API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/confluentinc/kafka-rest/master/api/v3/openapi.yaml
- filename: index.json
  format: json
  label: RabbitMQ Management HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/rabbitmq/rabbitmq-server/main/deps/rabbitmq_management/priv/www/api/index.json
- filename: swagger.json
  format: json
  label: Kubernetes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json
- filename: swagger.json
  format: json
  label: Argo Workflows API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/argoproj/argo-workflows/main/api/openapi-spec/swagger.json
apis:
- description: Istio is the leading open-source service mesh providing traffic management, security (mTLS), and observability for microservices. The Istio API includes VirtualService, DestinationRule, Gateway, and S
  name: Istio Service Mesh API
  slug: ''
- description: Linkerd is a lightweight, security-first service mesh for Kubernetes. Built on Rust-based micro-proxy (linkerd2-proxy), Linkerd provides automatic mTLS, observability with golden metrics (success rate
  name: Linkerd API
  slug: ''
- description: Envoy is a high-performance, open-source edge and service proxy, and the underlying data plane for Istio, Linkerd, and most service meshes. The Envoy Admin API provides REST endpoints for configuratio
  name: Envoy Proxy Admin API
  slug: ''
- description: The Confluent REST Proxy provides a RESTful interface to an Apache Kafka cluster, making it easy to produce and consume messages, view the state of the cluster, and perform administrative actions with
  name: Apache Kafka REST Proxy API
  slug: ''
- description: Redis is an in-memory data structure store used as a cache, message broker, and streaming engine. Redis Stack provides REST API access via the RedisJSON and RediSearch modules. Used extensively in sca
  name: Redis REST API (Redis Stack)
  slug: ''
- description: RabbitMQ is a widely-deployed open-source message broker implementing AMQP, MQTT, STOMP, and other messaging protocols. The RabbitMQ Management HTTP API provides REST endpoints for managing exchanges,
  name: RabbitMQ Management HTTP API
  slug: ''
- description: The Kubernetes API is the foundation of the container orchestration ecosystem, providing REST endpoints for managing the full lifecycle of containerized workloads. Core to scalable architecture, Kuber
  name: Kubernetes API
  slug: ''
- description: Argo Workflows is a Kubernetes-native workflow engine for orchestrating parallel jobs. Used extensively in scalable data pipelines, CI/CD systems, and ML workflows. Provides a REST API for submitting,
  name: Argo Workflows API
  slug: ''
common:
- title: ''
  type: CNCF Landscape
  url: https://landscape.cncf.io/
- title: ''
  type: GitHub Organization
  url: https://github.com/cncf
- title: ''
  type: Blog
  url: https://www.cncf.io/blog/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-schema/scalable-architecture-microservice-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-schema/scalable-architecture-event-schema.json
- title: ''
  type: JSONLd
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-ld/scalable-architecture-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/vocabulary/scalable-architecture-vocabulary.yml
created: '2024-01-15'
description: A subject-matter collection covering APIs, patterns, tools, and frameworks for building scalable system architecture. This topic encompasses microservices design, service mesh, event-driven architecture, CQRS, saga patterns, container orchestration, caching, message queuing, and observability patterns that enable distributed systems to scale reliably.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 17
  name: Scalable Architecture Context
  property_count: 8
  slug: scalable-architecture-context
layout: provider
modified: '2026-05-02'
name: Scalable Architecture
skills: []
slug: scalable-architecture
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Scalable Architecture\ndescription: >-\n  A subject-matter collection covering APIs, patterns, tools, and frameworks for\n  building scalable system architecture. This topic encompasses microservices design,\n  service mesh, event-driven architecture, CQRS, saga patterns, container orchestration,\n  caching, message queuing, and observability patterns that enable distributed systems\n  to scale reliably.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Cloud Architecture\n  - Cloud Native\n  - Distributed Systems\n  - High Availability\n  - Infrastructure\n  - Microservices\n  - Performance\n  - Resilience\n  - Scalability\n  - Service Mesh\napis:\n\n  - name: Istio Service Mesh API\n    description: >-\n      Istio is the leading open-source service\
  \ mesh providing traffic management,\n      security (mTLS), and observability for microservices. The Istio API includes\n      VirtualService, DestinationRule, Gateway, and ServiceEntry custom resources\n      for controlling service-to-service communication in Kubernetes. Graduated\n      CNCF project.\n    image: https://istio.io/latest/img/istio-whitelogo-bluebackground-framed.svg\n    humanUrl: https://istio.io/\n    baseUrl: https://api.istio.io\n    tags:\n      - CNCF\n      - Kubernetes\n      - Microservices\n      - Observability\n      - Security\n      - Service Mesh\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://istio.io/latest/docs/\n      - type: GitHub\n        url: https://github.com/istio/istio\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/istio/api/master/networking/v1alpha3/virtual_service.proto\n      - type: Changelog\n        url: https://istio.io/latest/news/releases/\n      - type: Getting\
  \ Started\n        url: https://istio.io/latest/docs/setup/getting-started/\n    contact:\n      - type: Slack\n        url: https://slack.istio.io/\n      - type: GitHub Issues\n        url: https://github.com/istio/istio/issues\n\n  - name: Linkerd API\n    description: >-\n      Linkerd is a lightweight, security-first service mesh for Kubernetes. Built on\n      Rust-based micro-proxy (linkerd2-proxy), Linkerd provides automatic mTLS,\n      observability with golden metrics (success rate, latency, throughput), and\n      traffic management without the operational complexity of Istio. CNCF graduated project.\n    image: https://linkerd.io/images/home/logo.svg\n    humanUrl: https://linkerd.io/\n    baseUrl: https://api.linkerd.io\n    tags:\n      - CNCF\n      - Kubernetes\n      - Microservices\n      - mTLS\n      - Observability\n      - Security\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://linkerd.io/2.x/overview/\n      - type: GitHub\n\
  \        url: https://github.com/linkerd/linkerd2\n      - type: Getting Started\n        url: https://linkerd.io/2.x/getting-started/\n    contact:\n      - type: Slack\n        url: https://slack.linkerd.io/\n      - type: GitHub Issues\n        url: https://github.com/linkerd/linkerd2/issues\n\n  - name: Envoy Proxy Admin API\n    description: >-\n      Envoy is a high-performance, open-source edge and service proxy, and the\n      underlying data plane for Istio, Linkerd, and most service meshes. The Envoy\n      Admin API provides REST endpoints for configuration, statistics, health checks,\n      cluster management, and runtime modification. CNCF graduated project.\n    image: https://www.envoyproxy.io/img/envoy-logo.svg\n    humanUrl: https://www.envoyproxy.io/\n    baseUrl: https://envoy-admin.local:9901\n    tags:\n      - CNCF\n      - Load Balancing\n      - Open Source\n      - Proxy\n      - Service Mesh\n      - Traffic Management\n    properties:\n      - type: Documentation\n\
  \        url: https://www.envoyproxy.io/docs/envoy/latest/operations/admin\n      - type: GitHub\n        url: https://github.com/envoyproxy/envoy\n      - type: OpenAPI\n        url: https://www.envoyproxy.io/docs/envoy/latest/api-v3/api\n    contact:\n      - type: Slack\n        url: https://envoyproxy.slack.com/\n      - type: GitHub Issues\n        url: https://github.com/envoyproxy/envoy/issues\n\n  - name: Apache Kafka REST Proxy API\n    description: >-\n      The Confluent REST Proxy provides a RESTful interface to an Apache Kafka cluster,\n      making it easy to produce and consume messages, view the state of the cluster,\n      and perform administrative actions without using the native Kafka protocol.\n      Central to event-driven scalable architectures.\n    image: https://kafka.apache.org/images/apache-kafka.png\n    humanUrl: https://kafka.apache.org/\n    baseUrl: https://kafka-rest.example.com\n    tags:\n      - Apache Kafka\n      - Event Streaming\n      - Event-Driven\n\
  \      - Message Broker\n      - Microservices\n      - Pub-Sub\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/platform/current/kafka-rest/api.html\n      - type: GitHub\n        url: https://github.com/confluentinc/kafka-rest\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/confluentinc/kafka-rest/master/api/v3/openapi.yaml\n      - type: Getting Started\n        url: https://kafka.apache.org/quickstart\n    contact:\n      - type: Community\n        url: https://kafka.apache.org/contact\n      - type: GitHub Issues\n        url: https://github.com/apache/kafka/issues\n\n  - name: Redis REST API (Redis Stack)\n    description: >-\n      Redis is an in-memory data structure store used as a cache, message broker,\n      and streaming engine. Redis Stack provides REST API access via the RedisJSON\n      and RediSearch modules. Used extensively in scalable architectures for caching,\n      session management, real-time leaderboards,\
  \ and pub/sub messaging.\n    image: https://redis.io/images/redis-logo.svg\n    humanUrl: https://redis.io/\n    baseUrl: https://redis.example.com/redis\n    tags:\n      - Caching\n      - Data Store\n      - In-Memory\n      - Message Broker\n      - Open Source\n      - Pub-Sub\n      - Redis\n    properties:\n      - type: Documentation\n        url: https://redis.io/docs/\n      - type: GitHub\n        url: https://github.com/redis/redis\n      - type: API Reference\n        url: https://redis.io/docs/data-types/\n      - type: Pricing\n        url: https://redis.io/pricing/\n    contact:\n      - type: Community\n        url: https://redis.io/community/\n      - type: GitHub Issues\n        url: https://github.com/redis/redis/issues\n\n  - name: RabbitMQ Management HTTP API\n    description: >-\n      RabbitMQ is a widely-deployed open-source message broker implementing AMQP,\n      MQTT, STOMP, and other messaging protocols. The RabbitMQ Management HTTP API\n      provides REST\
  \ endpoints for managing exchanges, queues, bindings, users,\n      and virtual hosts—critical for scalable event-driven microservice architectures.\n    image: https://www.rabbitmq.com/img/logo-rabbitmq.svg\n    humanUrl: https://www.rabbitmq.com/\n    baseUrl: https://rabbitmq.example.com:15672/api\n    tags:\n      - AMQP\n      - Event-Driven\n      - Message Broker\n      - Microservices\n      - Open Source\n      - RabbitMQ\n    properties:\n      - type: Documentation\n        url: https://www.rabbitmq.com/management.html\n      - type: GitHub\n        url: https://github.com/rabbitmq/rabbitmq-server\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/rabbitmq/rabbitmq-server/main/deps/rabbitmq_management/priv/www/api/index.json\n      - type: Getting Started\n        url: https://www.rabbitmq.com/tutorials\n    contact:\n      - type: Community\n        url: https://groups.google.com/g/rabbitmq-users\n      - type: GitHub Issues\n        url: https://github.com/rabbitmq/rabbitmq-server/issues\n\
  \n  - name: Kubernetes API\n    description: >-\n      The Kubernetes API is the foundation of the container orchestration ecosystem,\n      providing REST endpoints for managing the full lifecycle of containerized workloads.\n      Core to scalable architecture, Kubernetes manages Deployments, Services, Ingress,\n      HPA, VPA, ConfigMaps, Secrets, and the entire cluster state. CNCF graduated project.\n    image: https://kubernetes.io/images/favicon.png\n    humanUrl: https://kubernetes.io/\n    baseUrl: https://kubernetes.default.svc\n    tags:\n      - CNCF\n      - Cloud Native\n      - Containers\n      - Kubernetes\n      - Orchestration\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/reference/\n      - type: GitHub\n        url: https://github.com/kubernetes/kubernetes\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json\n      - type: Getting\
  \ Started\n        url: https://kubernetes.io/docs/tutorials/\n      - type: Changelog\n        url: https://kubernetes.io/releases/\n    contact:\n      - type: Slack\n        url: https://slack.k8s.io/\n      - type: GitHub Issues\n        url: https://github.com/kubernetes/kubernetes/issues\n\n  - name: Argo Workflows API\n    description: >-\n      Argo Workflows is a Kubernetes-native workflow engine for orchestrating parallel\n      jobs. Used extensively in scalable data pipelines, CI/CD systems, and ML workflows.\n      Provides a REST API for submitting, monitoring, and managing workflows and\n      workflow templates. CNCF graduated project.\n    image: https://argoproj.github.io/static/4f7f63c9de5b9a7bd1f28ea8d2cb06c9/argo-horizontal-color.png\n    humanUrl: https://argoproj.github.io/argo-workflows/\n    baseUrl: https://argo-server.example.com/api/v1\n    tags:\n      - CNCF\n      - CI/CD\n      - Kubernetes\n      - Orchestration\n      - Pipelines\n      - Workflow\n  \
  \  properties:\n      - type: Documentation\n        url: https://argoproj.github.io/argo-workflows/\n      - type: GitHub\n        url: https://github.com/argoproj/argo-workflows\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/argoproj/argo-workflows/main/api/openapi-spec/swagger.json\n      - type: Getting Started\n        url: https://argoproj.github.io/argo-workflows/quick-start/\n    contact:\n      - type: Slack\n        url: https://cloud-native.slack.com/archives/C01LWLS5M2X\n      - type: GitHub Issues\n        url: https://github.com/argoproj/argo-workflows/issues\n\ncommon:\n  - type: CNCF Landscape\n    url: https://landscape.cncf.io/\n  - type: GitHub Organization\n    url: https://github.com/cncf\n  - type: Blog\n    url: https://www.cncf.io/blog/\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-schema/scalable-architecture-microservice-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-schema/scalable-architecture-event-schema.json\n\
  \  - type: JSONLd\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-ld/scalable-architecture-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/vocabulary/scalable-architecture-vocabulary.yml\n\nmaintainers:\n  - FN: API Evangelist\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n\ninclude:\n  - name: Scalability APIs\n    url: https://raw.githubusercontent.com/api-evangelist/scalability/refs/heads/main/apis.yml\n  - name: Scalable Infrastructure\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/apis.yml
tags:
- Cloud Architecture
- Cloud Native
- Distributed Systems
- High Availability
- Infrastructure
- Microservices
- Performance
- Resilience
- Scalability
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/apis.yml
use_cases: []
---
