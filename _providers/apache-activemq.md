---
api_count: 3
api_specs:
- filename: apache-activemq-rest-openapi.yaml
  format: yaml
  label: Apache ActiveMQ REST API
  slug: apache-activemq-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-activemq/refs/heads/main/openapi/apache-activemq-rest-openapi.yaml
apis:
- description: The ActiveMQ REST API provides HTTP-based access to messaging operations, allowing clients to produce and consume messages from queues and topics without a native JMS client. It supports sending messa
  name: Apache ActiveMQ REST API
  slug: apache-activemq-rest-api
- description: The Jolokia JMX-HTTP bridge API provides HTTP access to JMX metrics and management operations for the ActiveMQ broker, enabling monitoring of broker health, queue depths, consumer counts, and other op
  name: Apache ActiveMQ Jolokia Management API
  slug: apache-activemq-jolokia-api
- description: The ActiveMQ Classic broker provides high-performance asynchronous messaging through multiple protocol interfaces including OpenWire, AMQP, STOMP, and MQTT. It includes a web-based management console,
  name: Apache ActiveMQ Broker
  slug: apache-activemq-broker
capabilities:
- description: Unified capability for Apache ActiveMQ messaging operations and broker management. Used by application developers and platform operators to send/receive messages and monitor broker health.
  name: Apache ActiveMQ Messaging Workflow
  slug: activemq-messaging
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/activemq
- title: ''
  type: Documentation
  url: https://activemq.apache.org/
- title: ''
  type: GettingStarted
  url: https://activemq.apache.org/components/classic/documentation/getting-started
- title: ''
  type: FAQ
  url: https://activemq.apache.org/faq
- title: ''
  type: Support
  url: https://activemq.apache.org/support
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: ChangeLog
  url: https://activemq.apache.org/components/classic/download
- title: ''
  type: OpenAPI
  url: openapi/apache-activemq-rest-openapi.yaml
- title: ''
  type: SpectralRules
  url: rules/apache-activemq-spectral-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/rest-jolokia-response-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rest-jolokia-error-schema.json
- title: ''
  type: JSONLD
  url: json-ld/apache-activemq-rest-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/apache-activemq-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/activemq-messaging.yaml
created: '2026-03-16'
description: Apache ActiveMQ is an open-source, high-performance message broker written in Java, developed by the Apache Software Foundation. It implements the Jakarta Messaging (JMS) API and supports multiple messaging protocols including AMQP, STOMP, MQTT, OpenWire, and HTTP/WebSocket, enabling reliable asynchronous messaging between distributed applications and microservices. ActiveMQ provides features such as network of brokers, message persistence (KahaDB, JDBC), high availability, message scheduling, and a web console with REST and Jolokia management APIs.
features:
- description: Supports AMQP, STOMP, MQTT, OpenWire, JMS, Jakarta Messaging, HTTP, and WebSocket protocols for broad client compatibility.
  name: Multi-Protocol Support
- description: Provides KahaDB and JDBC-based message persistence options to ensure message durability across broker restarts.
  name: Message Persistence
- description: Enables distributed messaging topologies by linking multiple brokers in a network for load balancing and failover.
  name: Network of Brokers
- description: Supports shared storage and master-slave configurations for high availability deployments.
  name: High Availability
- description: Built-in message scheduling capabilities allow delayed or recurring message delivery.
  name: Message Scheduling
- description: HTTP-based REST API for producing and consuming messages from queues and topics without native JMS clients.
  name: REST Messaging API
- description: JMX-over-HTTP bridge via Jolokia for broker monitoring and management.
  name: Jolokia Management API
- description: HTML5 web-based management console accessible at /admin for queue and topic management, subscriber monitoring, and message browsing.
  name: Web Console
- description: Official Docker image apache/activemq-classic available on Docker Hub for containerized deployments.
  name: Docker Support
- description: ActiveMQ can be embedded directly into Java applications for in-process messaging.
  name: Embeddable Broker
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deep integration with Spring and Spring Boot via spring-boot-starter-activemq.
  name: Spring Framework
- description: Native Apache Camel ActiveMQ component for enterprise integration patterns.
  name: Apache Camel
- description: Official Docker Hub image apache/activemq-classic for containerized deployments.
  name: Docker
- description: Deployable on Kubernetes using the official Docker image and StatefulSets.
  name: Kubernetes
- description: HTML5 management console integration via hawtio for advanced broker management.
  name: Hawtio
- description: Operational monitoring integration with RHQ for enterprise monitoring.
  name: RHQ
- description: OSGi integration with Apache Karaf for modular enterprise deployments.
  name: Apache Karaf
jsonld:
- class_count: 2
  name: Apache Activemq Rest Context
  property_count: 6
  slug: apache-activemq-rest-context
layout: provider
modified: '2026-04-19'
name: Apache ActiveMQ
rules:
- name: Apache ActiveMQ API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 2
    warn: 9
  slug: apache-activemq-spectral-rules
skills: []
slug: apache-activemq
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-activemq\nname: Apache ActiveMQ\ndescription: >-\n  Apache ActiveMQ is an open-source, high-performance message broker written in Java, developed by the Apache Software Foundation. It implements the Jakarta Messaging (JMS) API and supports multiple messaging protocols including AMQP, STOMP, MQTT, OpenWire, and HTTP/WebSocket, enabling reliable asynchronous messaging between distributed applications and microservices. ActiveMQ provides features such as network of brokers, message persistence (KahaDB, JDBC), high availability, message scheduling, and a web console with REST and Jolokia management APIs.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AMQP\n  - Apache\n  - Java\n  - JMS\n  - Message Broker\n  - Messaging\n  - MQTT\n  - Open Source\n  - STOMP\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-activemq/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-activemq:apache-activemq-rest-api\n    name: Apache ActiveMQ REST API\n    description: >-\n      The ActiveMQ REST API provides HTTP-based access to messaging operations, allowing clients to produce and consume messages from queues and topics without a native JMS client. It supports sending messages via POST, receiving via GET, and subscribing with client IDs for persistent consumption.\n    humanURL: https://activemq.apache.org/components/classic/documentation/rest\n    baseURL: http://localhost:8161/api/message\n    tags:\n      - Messaging\n      - REST\n    properties:\n      - type: Documentation\n        url: https://activemq.apache.org/components/classic/documentation/rest\n      - type: OpenAPI\n        url: openapi/apache-activemq-rest-openapi.yaml\n  - aid: apache-activemq:apache-activemq-jolokia-api\n    name: Apache ActiveMQ Jolokia Management API\n    description: >-\n      The Jolokia JMX-HTTP bridge API provides HTTP\
  \ access to JMX metrics and management operations for the ActiveMQ broker, enabling monitoring of broker health, queue depths, consumer counts, and other operational metrics without requiring a JMX client.\n    humanURL: https://activemq.apache.org/components/classic/documentation/web-console\n    baseURL: http://localhost:8161/api/jolokia\n    tags:\n      - Management\n      - Monitoring\n      - JMX\n    properties:\n      - type: Documentation\n        url: https://activemq.apache.org/components/classic/documentation/web-console\n  - aid: apache-activemq:apache-activemq-broker\n    name: Apache ActiveMQ Broker\n    description: >-\n      The ActiveMQ Classic broker provides high-performance asynchronous messaging through multiple protocol interfaces including OpenWire, AMQP, STOMP, and MQTT. It includes a web-based management console, message persistence, network of brokers for load distribution, and high availability configurations.\n    humanURL: https://activemq.apache.org/components/classic/documentation\n\
  \    tags:\n      - Broker\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://activemq.apache.org/components/classic/documentation\n      - type: GettingStarted\n        url: https://activemq.apache.org/components/classic/documentation/getting-started\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/activemq\n  - type: Documentation\n    url: https://activemq.apache.org/\n  - type: GettingStarted\n    url: https://activemq.apache.org/components/classic/documentation/getting-started\n  - type: FAQ\n    url: https://activemq.apache.org/faq\n  - type: Support\n    url: https://activemq.apache.org/support\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: ChangeLog\n    url: https://activemq.apache.org/components/classic/download\n  - type: Features\n    data:\n      - name: Multi-Protocol Support\n        description: Supports AMQP, STOMP,\
  \ MQTT, OpenWire, JMS, Jakarta Messaging, HTTP, and WebSocket protocols for broad client compatibility.\n      - name: Message Persistence\n        description: Provides KahaDB and JDBC-based message persistence options to ensure message durability across broker restarts.\n      - name: Network of Brokers\n        description: Enables distributed messaging topologies by linking multiple brokers in a network for load balancing and failover.\n      - name: High Availability\n        description: Supports shared storage and master-slave configurations for high availability deployments.\n      - name: Message Scheduling\n        description: Built-in message scheduling capabilities allow delayed or recurring message delivery.\n      - name: REST Messaging API\n        description: HTTP-based REST API for producing and consuming messages from queues and topics without native JMS clients.\n      - name: Jolokia Management API\n        description: JMX-over-HTTP bridge via Jolokia for broker\
  \ monitoring and management.\n      - name: Web Console\n        description: HTML5 web-based management console accessible at /admin for queue and topic management, subscriber monitoring, and message browsing.\n      - name: Docker Support\n        description: Official Docker image apache/activemq-classic available on Docker Hub for containerized deployments.\n      - name: Embeddable Broker\n        description: ActiveMQ can be embedded directly into Java applications for in-process messaging.\n  - type: UseCases\n    data:\n      - name: Microservices Messaging\n        description: Decouple microservices using asynchronous message queues and topics for event-driven architectures.\n      - name: Enterprise Integration\n        description: Connect disparate enterprise systems and applications using standard messaging protocols.\n      - name: IoT Messaging\n        description: Use MQTT protocol support for IoT device communication and telemetry data pipelines.\n      - name: Workload\
  \ Distribution\n        description: Distribute work items across consumer pools using competing consumers on queues.\n      - name: Event Streaming\n        description: Publish events to topics and fan out to multiple subscriber applications.\n      - name: Legacy JMS Integration\n        description: Bridge legacy JMS-based applications with modern services using OpenWire and JMS API support.\n  - type: Integrations\n    data:\n      - name: Spring Framework\n        description: Deep integration with Spring and Spring Boot via spring-boot-starter-activemq.\n      - name: Apache Camel\n        description: Native Apache Camel ActiveMQ component for enterprise integration patterns.\n      - name: Docker\n        description: Official Docker Hub image apache/activemq-classic for containerized deployments.\n      - name: Kubernetes\n        description: Deployable on Kubernetes using the official Docker image and StatefulSets.\n      - name: Hawtio\n        description: HTML5 management\
  \ console integration via hawtio for advanced broker management.\n      - name: RHQ\n        description: Operational monitoring integration with RHQ for enterprise monitoring.\n      - name: Apache Karaf\n        description: OSGi integration with Apache Karaf for modular enterprise deployments.\n  - type: OpenAPI\n    url: openapi/apache-activemq-rest-openapi.yaml\n  - type: SpectralRules\n    url: rules/apache-activemq-spectral-rules.yml\n  - type: JSONSchema\n    url: json-schema/rest-jolokia-response-schema.json\n  - type: JSONSchema\n    url: json-schema/rest-jolokia-error-schema.json\n  - type: JSONLD\n    url: json-ld/apache-activemq-rest-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/apache-activemq-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/activemq-messaging.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-activemq/refs/heads/main/apis.yml
tags:
- AMQP
- Apache
- Java
- JMS
- Message Broker
- Messaging
- MQTT
- Open Source
- STOMP
url: https://raw.githubusercontent.com/api-evangelist/apache-activemq/refs/heads/main/apis.yml
use_cases:
- description: Decouple microservices using asynchronous message queues and topics for event-driven architectures.
  name: Microservices Messaging
- description: Connect disparate enterprise systems and applications using standard messaging protocols.
  name: Enterprise Integration
- description: Use MQTT protocol support for IoT device communication and telemetry data pipelines.
  name: IoT Messaging
- description: Distribute work items across consumer pools using competing consumers on queues.
  name: Workload Distribution
- description: Publish events to topics and fan out to multiple subscriber applications.
  name: Event Streaming
- description: Bridge legacy JMS-based applications with modern services using OpenWire and JMS API support.
  name: Legacy JMS Integration
---
