---
api_count: 3
apis:
- description: 'Zilla is a stateless, cloud-native multi-protocol edge and service proxy that enables seamless access to Apache Kafka through HTTP REST, gRPC, SSE, MQTT, and WebSocket protocols. Zilla eliminates the '
  name: Zilla Gateway
  slug: zilla-gateway
- description: 'The Zilla Platform adds an enterprise management layer on top of Zilla Gateway, providing API data products with versioning and rate limits, Kafka governance policies, a self-service developer portal '
  name: Zilla Platform
  slug: zilla-platform
- description: ZillaBase is an event-driven backend framework for the next generation of web, mobile, and AI applications, built on top of Apache Kafka and Zilla to enable real-time, event-sourced application develo
  name: ZillaBase
  slug: zillabase
capabilities:
- description: Workflow for exposing Apache Kafka topics as REST APIs and managing event-driven integrations via Zilla. Enables HTTP, MQTT, and gRPC clients to produce and consume Kafka events without Kafka client l
  name: Aklivity Kafka API Gateway
  slug: kafka-api-gateway
common:
- title: ''
  type: Website
  url: https://www.aklivity.io/
- title: ''
  type: Documentation
  url: https://docs.aklivity.io/zilla/latest/
- title: ''
  type: GettingStarted
  url: https://docs.aklivity.io/zilla/next/getting-started/quickstart/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aklivity
- title: ''
  type: GitHubRepository
  url: https://github.com/aklivity/zilla
- title: ''
  type: Pricing
  url: https://www.aklivity.io/pricing
created: '2026-01-02'
description: Aklivity provides the Zilla multi-protocol edge and service proxy for event-driven architectures, enabling seamless integration between web apps, IoT clients, and microservices with Apache Kafka via declaratively defined, stateless APIs. Zilla supports HTTP, gRPC, MQTT, SSE, and WebSocket protocols, translating them to and from Kafka without custom code or connectors. The Zilla Platform adds enterprise governance, observability, and self-service access management for Kafka deployments.
features:
- description: Translates HTTP REST, gRPC, MQTT, SSE, and WebSocket protocols directly to Kafka topics without custom code, connectors, or middleware.
  name: Multi-Protocol Kafka Access
- description: Define gateways and protocol mappings via YAML configuration or AsyncAPI specifications, then deploy with Docker, Helm, or native binaries.
  name: Declarative Configuration
- description: Built-in JWT token validation, TLS termination, and Kafka SASL support for securing API access to Kafka clusters.
  name: JWT Authentication and TLS
- description: SIMD-optimized runtime schema validation for JSON, Avro, and Protobuf via Confluent Schema Registry or AWS Glue Schema Registry.
  name: Schema Validation
- description: Metrics and logs exported to Prometheus and OpenTelemetry for unified visibility across Kafka API traffic.
  name: Observability
- description: Topic naming policies, runtime enforcement, schema compliance rules, and API data product versioning with rate limits via Zilla Platform.
  name: Kafka Governance
- description: API key and certificate management self-service portal for Kafka consumers and producers via Zilla Platform.
  name: Self-Service Developer Portal
- description: PII classification and field-level encryption for sensitive data in Kafka messages via Zilla Platform.
  name: Field-Level Encryption
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Core integration — Zilla acts as a multi-protocol proxy in front of any Kafka cluster
  name: Apache Kafka
- description: Managed Streaming for Apache Kafka integration with AWS-native security
  name: AWS MSK
- description: Schema validation and enforcement using Confluent Schema Registry
  name: Confluent Schema Registry
- description: Schema validation using AWS Glue Schema Registry
  name: AWS Glue Schema Registry
- description: Metrics export for monitoring Zilla gateway performance
  name: Prometheus
- description: Distributed tracing and observability via OpenTelemetry
  name: OpenTelemetry
- description: Secure credential management for Kafka and TLS configurations
  name: AWS Secrets Manager
jsonld:
- class_count: 2
  name: Aklivity Context
  property_count: 7
  slug: aklivity-context
layout: provider
modified: '2026-04-19'
name: Aklivity
rules:
- name: Aklivity API Rules
  rule_count: 11
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 2
  slug: aklivity-spectral-rules
skills: []
slug: aklivity
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aklivity\nname: Aklivity\ndescription: >-\n  Aklivity provides the Zilla multi-protocol edge and service proxy for\n  event-driven architectures, enabling seamless integration between web apps,\n  IoT clients, and microservices with Apache Kafka via declaratively defined,\n  stateless APIs. Zilla supports HTTP, gRPC, MQTT, SSE, and WebSocket\n  protocols, translating them to and from Kafka without custom code or\n  connectors. The Zilla Platform adds enterprise governance, observability, and\n  self-service access management for Kafka deployments.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Apache Kafka\n  - Event-Driven\n  - IoT\n  - Kafka Proxy\n  - Multi-Protocol\n  - Real-Time\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aklivity/refs/heads/main/apis.yml\ncreated: '2026-01-02'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: aklivity:zilla-gateway\n    name: Zilla Gateway\n    description: >-\n      Zilla is a stateless, cloud-native multi-protocol edge and service proxy\n      that enables seamless access to Apache Kafka through HTTP REST, gRPC, SSE,\n      MQTT, and WebSocket protocols. Zilla eliminates the need for Kafka Connect,\n      custom code, or separate MQTT brokers, translating client protocol requests\n      directly to Kafka operations declaratively via YAML configuration or\n      AsyncAPI specifications.\n    humanURL: https://www.aklivity.io/\n    tags:\n      - API Gateway\n      - Apache Kafka\n      - Event-Driven\n      - Kafka Proxy\n      - Multi-Protocol\n    properties:\n      - type: Documentation\n        url: https://docs.aklivity.io/zilla/latest/\n      - type: GettingStarted\n        url: https://docs.aklivity.io/zilla/latest/getting-started/quickstart/\n      - type: GitHubRepository\n        url: https://github.com/aklivity/zilla\n      - type: AsyncAPI\n   \
  \     url: https://docs.aklivity.io/zilla/latest/concepts/config/\n  - aid: aklivity:zilla-platform\n    name: Zilla Platform\n    description: >-\n      The Zilla Platform adds an enterprise management layer on top of Zilla\n      Gateway, providing API data products with versioning and rate limits, Kafka\n      governance policies, a self-service developer portal with API key and\n      certificate management, field-level encryption, PII classification, and\n      unified observability across Kafka deployments.\n    humanURL: https://www.aklivity.io/platform\n    tags:\n      - API Management\n      - Developer Portal\n      - Governance\n      - Kafka Management\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://docs.aklivity.io/\n      - type: GettingStarted\n        url: https://docs.aklivity.io/\n  - aid: aklivity:zillabase\n    name: ZillaBase\n    description: >-\n      ZillaBase is an event-driven backend framework for the next generation\
  \ of\n      web, mobile, and AI applications, built on top of Apache Kafka and Zilla\n      to enable real-time, event-sourced application development.\n    humanURL: https://github.com/aklivity/zillabase\n    tags:\n      - Backend Framework\n      - Event-Driven\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://docs.aklivity.io/\n      - type: GitHubRepository\n        url: https://github.com/aklivity/zillabase\ncommon:\n  - type: Website\n    url: https://www.aklivity.io/\n  - type: Documentation\n    url: https://docs.aklivity.io/zilla/latest/\n  - type: GettingStarted\n    url: https://docs.aklivity.io/zilla/next/getting-started/quickstart/\n  - type: GitHubOrganization\n    url: https://github.com/aklivity\n  - type: GitHubRepository\n    url: https://github.com/aklivity/zilla\n  - type: Pricing\n    url: https://www.aklivity.io/pricing\n  - type: Features\n    data:\n      - name: Multi-Protocol Kafka Access\n        description: >-\n       \
  \   Translates HTTP REST, gRPC, MQTT, SSE, and WebSocket protocols\n          directly to Kafka topics without custom code, connectors, or\n          middleware.\n      - name: Declarative Configuration\n        description: >-\n          Define gateways and protocol mappings via YAML configuration or\n          AsyncAPI specifications, then deploy with Docker, Helm, or native\n          binaries.\n      - name: JWT Authentication and TLS\n        description: >-\n          Built-in JWT token validation, TLS termination, and Kafka SASL\n          support for securing API access to Kafka clusters.\n      - name: Schema Validation\n        description: >-\n          SIMD-optimized runtime schema validation for JSON, Avro, and Protobuf\n          via Confluent Schema Registry or AWS Glue Schema Registry.\n      - name: Observability\n        description: >-\n          Metrics and logs exported to Prometheus and OpenTelemetry for unified\n          visibility across Kafka API traffic.\n  \
  \    - name: Kafka Governance\n        description: >-\n          Topic naming policies, runtime enforcement, schema compliance rules,\n          and API data product versioning with rate limits via Zilla Platform.\n      - name: Self-Service Developer Portal\n        description: >-\n          API key and certificate management self-service portal for Kafka\n          consumers and producers via Zilla Platform.\n      - name: Field-Level Encryption\n        description: >-\n          PII classification and field-level encryption for sensitive data\n          in Kafka messages via Zilla Platform.\n  - type: UseCases\n    data:\n      - name: HTTP to Kafka REST API\n        description: >-\n          Expose Kafka topics as REST API endpoints, allowing any HTTP client\n          to produce and consume Kafka messages without Kafka client libraries.\n      - name: IoT MQTT to Kafka\n        description: >-\n          Connect IoT devices using MQTT protocol directly to Kafka topics,\n     \
  \     eliminating the need for a separate MQTT broker.\n      - name: gRPC to Kafka\n        description: >-\n          Route gRPC calls from microservices to Kafka topics for event-driven\n          inter-service communication.\n      - name: Kafka Self-Service Platform\n        description: >-\n          Platform teams build internal developer portals for Kafka access with\n          governance, rate limiting, and self-service API key management.\n      - name: Event-Driven Partner Integration\n        description: >-\n          Enterprises expose Kafka event streams to external partners via\n          secured, rate-limited REST or SSE APIs.\n      - name: Financial Services Data Distribution\n        description: >-\n          Financial institutions distribute real-time market data and trade\n          events via secured Kafka API gateways.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: Core integration — Zilla acts as a multi-protocol proxy in\
  \ front of any Kafka cluster\n      - name: AWS MSK\n        description: Managed Streaming for Apache Kafka integration with AWS-native security\n      - name: Confluent Schema Registry\n        description: Schema validation and enforcement using Confluent Schema Registry\n      - name: AWS Glue Schema Registry\n        description: Schema validation using AWS Glue Schema Registry\n      - name: Prometheus\n        description: Metrics export for monitoring Zilla gateway performance\n      - name: OpenTelemetry\n        description: Distributed tracing and observability via OpenTelemetry\n      - name: AWS Secrets Manager\n        description: Secure credential management for Kafka and TLS configurations\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aklivity/refs/heads/main/apis.yml
tags:
- API Gateway
- Apache Kafka
- Event-Driven
- IoT
- Kafka Proxy
- Multi-Protocol
- Real-Time
url: https://raw.githubusercontent.com/api-evangelist/aklivity/refs/heads/main/apis.yml
use_cases:
- description: Expose Kafka topics as REST API endpoints, allowing any HTTP client to produce and consume Kafka messages without Kafka client libraries.
  name: HTTP to Kafka REST API
- description: Connect IoT devices using MQTT protocol directly to Kafka topics, eliminating the need for a separate MQTT broker.
  name: IoT MQTT to Kafka
- description: Route gRPC calls from microservices to Kafka topics for event-driven inter-service communication.
  name: gRPC to Kafka
- description: Platform teams build internal developer portals for Kafka access with governance, rate limiting, and self-service API key management.
  name: Kafka Self-Service Platform
- description: Enterprises expose Kafka event streams to external partners via secured, rate-limited REST or SSE APIs.
  name: Event-Driven Partner Integration
- description: Financial institutions distribute real-time market data and trade events via secured Kafka API gateways.
  name: Financial Services Data Distribution
---
