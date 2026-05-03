---
api_count: 3
apis:
- description: Core programmatic API for building message-driven microservice applications. Provides functional programming model with java.util.function.Function, Consumer and Supplier bindings, binding lifecycle m
  name: Spring Cloud Stream Core API
  slug: spring-cloud-stream-core
- description: Apache Kafka binder for Spring Cloud Stream providing Kafka producer and consumer binding configuration, Kafka Streams support, partitioning, transaction management, error handling, and dead-letter qu
  name: Spring Cloud Stream Kafka Binder
  slug: spring-cloud-stream-kafka-binder
- description: RabbitMQ binder for Spring Cloud Stream providing AMQP-based messaging with support for exchanges, queues, routing keys, dead-letter exchanges, consumer groups, and AMQP transaction management.
  name: Spring Cloud Stream RabbitMQ Binder
  slug: spring-cloud-stream-rabbitmq-binder
common:
- title: ''
  type: Website
  url: https://spring.io/projects/spring-cloud-stream
- title: ''
  type: Documentation
  url: https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/
- title: ''
  type: GitHub
  url: https://github.com/spring-cloud/spring-cloud-stream
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-cloud
- title: ''
  type: Blog
  url: https://spring.io/blog/category/cloud
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-cloud-stream
- title: ''
  type: Support
  url: https://spring.io/support
- title: ''
  type: Vocabulary
  url: vocabulary/spring-cloud-stream-vocabulary.yml
created: '2024-01-01'
description: Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persistent pub/sub semantics, consumer groups, and stateful partitions with Apache Kafka and RabbitMQ binders.
features: []
image: https://spring.io/img/projects/spring-cloud.svg
integrations: []
jsonld:
- class_count: 7
  name: Spring Cloud Stream Context
  property_count: 9
  slug: spring-cloud-stream-context
layout: provider
modified: '2026-05-02'
name: Spring Cloud Stream
skills: []
slug: spring-cloud-stream
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-cloud-stream\nname: Spring Cloud Stream\ndescription: >-\n  Spring Cloud Stream is a framework for building event-driven microservices connected\n  with shared messaging systems. It provides a flexible programming model built on\n  established Spring idioms and best practices, including support for persistent\n  pub/sub semantics, consumer groups, and stateful partitions with Apache Kafka and\n  RabbitMQ binders.\nimage: https://spring.io/img/projects/spring-cloud.svg\nurl: https://spring.io/projects/spring-cloud-stream\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Apache Kafka\n  - AsyncAPI\n  - Event-Driven\n  - Java\n  - Messaging\n  - Microservices\n  - RabbitMQ\n  - Spring Framework\n  - Stream Processing\napis:\n  - aid: spring-cloud-stream:spring-cloud-stream-core\n    name: Spring Cloud Stream Core API\n    description: >-\n      Core programmatic API for building message-driven microservice applications.\n    \
  \  Provides functional programming model with java.util.function.Function,\n      Consumer and Supplier bindings, binding lifecycle management, and integration\n      with Spring Integration for message transformation and routing.\n    humanURL: https://spring.io/projects/spring-cloud-stream\n    baseURL: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-stream\n    tags:\n      - Bindings\n      - Consumer Groups\n      - Event-Driven\n      - Functional Programming\n      - Messaging\n      - Microservices\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-cloud-stream/docs/current/api/\n      - type: Getting Started\n        url: https://spring.io/projects/spring-cloud-stream#learn\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-stream\n      - type: Maven Repository\n    \
  \    url: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-stream\n      - type: Samples\n        url: https://github.com/spring-cloud/spring-cloud-stream-samples\n      - type: Releases\n        url: https://github.com/spring-cloud/spring-cloud-stream/releases\n      - type: Issues\n        url: https://github.com/spring-cloud/spring-cloud-stream/issues\n      - type: JSONSchema\n        url: json-schema/spring-cloud-stream-binding-schema.json\n      - type: JSONStructure\n        url: json-structure/spring-cloud-stream-binding-structure.json\n      - type: JSONLDContext\n        url: json-ld/spring-cloud-stream-context.jsonld\n  - aid: spring-cloud-stream:spring-cloud-stream-kafka-binder\n    name: Spring Cloud Stream Kafka Binder\n    description: >-\n      Apache Kafka binder for Spring Cloud Stream providing Kafka producer and\n      consumer binding configuration, Kafka Streams support, partitioning,\n      transaction management, error handling, and dead-letter\
  \ queues.\n    humanURL: https://docs.spring.io/spring-cloud-stream-binder-kafka/docs/current/reference/html/\n    baseURL: https://kafka.apache.org\n    tags:\n      - Apache Kafka\n      - Binder\n      - Event Streaming\n      - Kafka Streams\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-stream-binder-kafka/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-stream-binder-kafka\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-stream-binder-kafka\n  - aid: spring-cloud-stream:spring-cloud-stream-rabbitmq-binder\n    name: Spring Cloud Stream RabbitMQ Binder\n    description: >-\n      RabbitMQ binder for Spring Cloud Stream providing AMQP-based messaging with\n      support for exchanges, queues, routing keys, dead-letter exchanges, consumer\n      groups, and AMQP transaction management.\n\
  \    humanURL: https://docs.spring.io/spring-cloud-stream-binder-rabbit/docs/current/reference/html/\n    baseURL: https://www.rabbitmq.com\n    tags:\n      - AMQP\n      - Binder\n      - Messaging\n      - RabbitMQ\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-stream-binder-rabbit/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-stream-binder-rabbit\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-stream-binder-rabbit\ncommon:\n  - type: Website\n    url: https://spring.io/projects/spring-cloud-stream\n  - type: Documentation\n    url: https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/\n  - type: GitHub\n    url: https://github.com/spring-cloud/spring-cloud-stream\n  - type: GitHub Organization\n    url: https://github.com/spring-cloud\n  - type: Blog\n    url: https://spring.io/blog/category/cloud\n\
  \  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-cloud-stream\n  - type: Support\n    url: https://spring.io/support\n  - type: Vocabulary\n    url: vocabulary/spring-cloud-stream-vocabulary.yml\nmaintainers:\n  - FN: VMware Tanzu (Spring Team)\n    email: spring-cloud@vmware.com\n    url: https://spring.io/team\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-stream/refs/heads/main/apis.yml
tags:
- Apache Kafka
- AsyncAPI
- Event-Driven
- Java
- Messaging
- Microservices
- RabbitMQ
- Spring Framework
- Stream Processing
url: https://spring.io/projects/spring-cloud-stream
use_cases: []
---
