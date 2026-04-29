---
api_count: 1
api_specs:
- filename: amqp-messaging.yml
  format: yaml
  label: AMQP Messaging API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/asyncapi/amqp-messaging.yml
apis:
- description: AsyncAPI specification for AMQP messaging patterns including publish/subscribe, request/reply, and point-to-point messaging via exchanges, queues, and bindings.
  name: AMQP Messaging API
  slug: ''
asyncapis:
- description: AsyncAPI specification for AMQP (Advanced Message Queuing Protocol) messaging patterns including publish/subscribe, request/reply, and point-to-point messaging. AMQP 0-9-1 defines exchanges, queues, a
  name: AMQP Messaging API
  slug: amqp-messaging
common:
- title: AMQP Message
  type: JSONSchema
  url: json-schema/amqp-message.json
- title: AMQP Message Properties
  type: JSONSchema
  url: json-schema/amqp-message-properties.json
- title: AMQP Exchange
  type: JSONSchema
  url: json-schema/amqp-exchange.json
- title: AMQP Queue
  type: JSONSchema
  url: json-schema/amqp-queue.json
- title: AMQP Binding
  type: JSONSchema
  url: json-schema/amqp-binding.json
- title: AMQP JSON-LD Context
  type: JSONLD
  url: json-ld/amqp-context.jsonld
- title: ''
  type: Portal
  url: https://www.amqp.org/
- title: ''
  type: Documentation
  url: https://www.amqp.org/resources/specifications
- title: ''
  type: GitHubOrganization
  url: https://github.com/amqp
- title: Apache Qpid
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: JSONStructure
  url: json-structure/amqp-message-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amqp-exchange-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amqp-queue-structure.json
- title: ''
  type: SpectralRules
  url: rules/amqp-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amqp-vocabulary.yaml
created: '2025'
description: AMQP (Advanced Message Queuing Protocol) is an open standard for message-oriented middleware governed by OASIS and standardized as ISO/IEC 19464. AMQP 1.0 enables interoperable, asynchronous communication between applications across different platforms and vendors. It defines a wire-level protocol supporting reliable queuing, flexible routing, publish/subscribe, and request/reply messaging patterns. Major implementations include Apache ActiveMQ/Artemis, RabbitMQ, Azure Service Bus, Red Hat AMQ, and Apache Qpid.
features:
- description: Guaranteed delivery with acknowledgment and persistence support.
  name: Reliable Messaging
- description: Exchange types (direct, fanout, topic, headers) for flexible message routing.
  name: Flexible Routing
- description: Fan-out delivery to multiple consumers via topic and fanout exchanges.
  name: Publish/Subscribe
- description: Synchronous RPC patterns over asynchronous messaging infrastructure.
  name: Request/Reply
- description: Transactional message publishing and acknowledgment for data consistency.
  name: Transaction Support
- description: SASL authentication and TLS encryption for secure message transport.
  name: Security
- description: Credit-based flow control preventing consumer overload (AMQP 1.0).
  name: Flow Control
- description: Wire-level protocol interoperability across different broker implementations.
  name: Multi-Vendor Interoperability
image: ''
integrations:
- description: Popular AMQP 0-9-1 compliant broker with extensive plugin ecosystem.
  name: RabbitMQ
- description: Java-based message broker supporting AMQP 1.0 and multiple protocols.
  name: Apache ActiveMQ
- description: Microsoft's cloud messaging service with AMQP 1.0 support.
  name: Azure Service Bus
- description: AMQP 1.0 implementation with broker and client library support.
  name: Apache Qpid
- description: Enterprise messaging platform based on ActiveMQ Artemis with AMQP 1.0.
  name: Red Hat AMQ
- description: Enterprise event broker supporting AMQP 1.0 among multiple protocols.
  name: Solace PubSub+
jsonld:
- class_count: 1
  name: Amqp Amqp Binding Context
  property_count: 5
  slug: amqp-amqp-binding-context
- class_count: 1
  name: Amqp Amqp Exchange Context
  property_count: 6
  slug: amqp-amqp-exchange-context
- class_count: 1
  name: Amqp Amqp Message Context
  property_count: 7
  slug: amqp-amqp-message-context
- class_count: 1
  name: Amqp Amqp Message Properties Context
  property_count: 14
  slug: amqp-amqp-message-properties-context
- class_count: 1
  name: Amqp Amqp Queue Context
  property_count: 5
  slug: amqp-amqp-queue-context
- class_count: 0
  name: Amqp Context
  property_count: 9
  slug: amqp-context
layout: provider
modified: '2026-04-19'
name: AMQP
rules:
- name: AMQP API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 5
  slug: amqp-spectral-rules
skills: []
slug: amqp
solutions: []
source_filename: apis.yml
source_yaml: "name: AMQP\ndescription: AMQP (Advanced Message Queuing Protocol) is an open standard for message-oriented middleware governed by OASIS and standardized as ISO/IEC 19464. AMQP 1.0 enables interoperable, \n  asynchronous communication between applications across different platforms and vendors. It defines a wire-level protocol supporting reliable queuing, flexible routing, publish/subscribe, and \n  request/reply messaging patterns. Major implementations include Apache ActiveMQ/Artemis, RabbitMQ, Azure Service Bus, Red Hat AMQ, and Apache Qpid.\nurl: https://www.amqp.org/\ntags:\n- AMQP\n- Asynchronous\n- Message Queue\n- Messaging\n- Middleware\n- Open Standard\n- Publish Subscribe\ncreated: '2025'\nmodified: '2026-04-19'\napis:\n- name: AMQP Messaging API\n  description: AsyncAPI specification for AMQP messaging patterns including publish/subscribe, request/reply, and point-to-point messaging via exchanges, queues, and bindings.\n  properties:\n  - type: AsyncAPI\n    url:\
  \ asyncapi/amqp-messaging.yml\n  tags:\n  - AMQP\n  - AsyncAPI\n  - Messaging\n  - Point to Point\n  - Publish Subscribe\n  - Request Reply\n  humanURL: https://www.amqp.org/\ncommon:\n- type: JSONSchema\n  title: AMQP Message\n  url: json-schema/amqp-message.json\n  description: JSON Schema describing the structure of an AMQP message including properties, headers, and payload body.\n- type: JSONSchema\n  title: AMQP Message Properties\n  url: json-schema/amqp-message-properties.json\n  description: JSON Schema describing the standard AMQP 0-9-1 Basic.Properties including content type, delivery mode, correlation ID, and reply-to.\n- type: JSONSchema\n  title: AMQP Exchange\n  url: json-schema/amqp-exchange.json\n  description: JSON Schema describing an AMQP exchange with type, durability, auto-delete, and argument configuration.\n- type: JSONSchema\n  title: AMQP Queue\n  url: json-schema/amqp-queue.json\n  description: JSON Schema describing an AMQP queue with support for TTL, dead-lettering,\
  \ priority, and overflow policies.\n- type: JSONSchema\n  title: AMQP Binding\n  url: json-schema/amqp-binding.json\n  description: JSON Schema describing an AMQP binding that links exchanges to queues or other exchanges using routing keys.\n- type: JSONLD\n  title: AMQP JSON-LD Context\n  url: json-ld/amqp-context.jsonld\n  description: JSON-LD context mapping AMQP concepts (messages, exchanges, queues, bindings, channels) to linked data vocabularies including Schema.org and Dublin Core.\n- type: Portal\n  url: https://www.amqp.org/\n- type: Documentation\n  url: https://www.amqp.org/resources/specifications\n- type: GitHubOrganization\n  url: https://github.com/amqp\n- type: GitHubOrganization\n  url: https://github.com/apache\n  title: Apache Qpid\n- type: Features\n  data:\n  - name: Reliable Messaging\n    description: Guaranteed delivery with acknowledgment and persistence support.\n  - name: Flexible Routing\n    description: Exchange types (direct, fanout, topic, headers) for flexible\
  \ message routing.\n  - name: Publish/Subscribe\n    description: Fan-out delivery to multiple consumers via topic and fanout exchanges.\n  - name: Request/Reply\n    description: Synchronous RPC patterns over asynchronous messaging infrastructure.\n  - name: Transaction Support\n    description: Transactional message publishing and acknowledgment for data consistency.\n  - name: Security\n    description: SASL authentication and TLS encryption for secure message transport.\n  - name: Flow Control\n    description: Credit-based flow control preventing consumer overload (AMQP 1.0).\n  - name: Multi-Vendor Interoperability\n    description: Wire-level protocol interoperability across different broker implementations.\n- type: UseCases\n  data:\n  - name: Microservices Communication\n    description: Decoupled inter-service messaging in microservices architectures.\n  - name: Event Streaming\n    description: Event-driven architecture with durable, ordered event delivery.\n  - name: Task\
  \ Queues\n    description: Distributed work queues for background job processing.\n  - name: IoT Messaging\n    description: Device-to-cloud and cloud-to-device messaging for IoT platforms.\n  - name: Financial Messaging\n    description: High-reliability financial transaction messaging with guaranteed delivery.\n  - name: Log Aggregation\n    description: Centralized log collection and routing from distributed systems.\n- type: Integrations\n  data:\n  - name: RabbitMQ\n    description: Popular AMQP 0-9-1 compliant broker with extensive plugin ecosystem.\n  - name: Apache ActiveMQ\n    description: Java-based message broker supporting AMQP 1.0 and multiple protocols.\n  - name: Azure Service Bus\n    description: Microsoft's cloud messaging service with AMQP 1.0 support.\n  - name: Apache Qpid\n    description: AMQP 1.0 implementation with broker and client library support.\n  - name: Red Hat AMQ\n    description: Enterprise messaging platform based on ActiveMQ Artemis with AMQP 1.0.\n\
  \  - name: Solace PubSub+\n    description: Enterprise event broker supporting AMQP 1.0 among multiple protocols.\n- type: JSONStructure\n  url: json-structure/amqp-message-structure.json\n- type: JSONStructure\n  url: json-structure/amqp-exchange-structure.json\n- type: JSONStructure\n  url: json-structure/amqp-queue-structure.json\n- type: SpectralRules\n  url: rules/amqp-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amqp-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amqp/refs/heads/main/apis.yml
tags:
- AMQP
- Asynchronous
- Message Queue
- Messaging
- Middleware
- Open Standard
- Publish Subscribe
url: https://www.amqp.org/
use_cases:
- description: Decoupled inter-service messaging in microservices architectures.
  name: Microservices Communication
- description: Event-driven architecture with durable, ordered event delivery.
  name: Event Streaming
- description: Distributed work queues for background job processing.
  name: Task Queues
- description: Device-to-cloud and cloud-to-device messaging for IoT platforms.
  name: IoT Messaging
- description: High-reliability financial transaction messaging with guaranteed delivery.
  name: Financial Messaging
- description: Centralized log collection and routing from distributed systems.
  name: Log Aggregation
---
