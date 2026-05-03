---
api_count: 4
api_specs:
- filename: spring-integration-http-openapi.yml
  format: yaml
  label: Spring Integration HTTP Adapter API
  slug: spring-integration-http
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-integration/refs/heads/main/openapi/spring-integration-http-openapi.yml
- filename: spring-integration-management-openapi.yml
  format: yaml
  label: Spring Integration Management API
  slug: spring-integration-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-integration/refs/heads/main/openapi/spring-integration-management-openapi.yml
apis:
- description: HTTP inbound and outbound channel adapters for Spring Integration. Provides HTTP request-response messaging, REST template integration, and configurable URL mapping for inbound HTTP gateways.
  name: Spring Integration HTTP Adapter API
  slug: spring-integration-http
- description: Management and monitoring REST API for Spring Integration. Exposes channel statistics, handler metrics, component lifecycle control (start/stop), and message history configuration via HTTP endpoints.
  name: Spring Integration Management API
  slug: spring-integration-management
- description: AMQP channel adapters and gateways for Spring Integration. Provides RabbitMQ message-driven and polling inbound adapters, outbound channel adapters, and request/reply gateways.
  name: Spring Integration AMQP Adapter
  slug: spring-integration-amqp
- description: Kafka channel adapters for Spring Integration. Provides message-driven inbound adapters, outbound channel adapters, and request/reply gateways for Apache Kafka integration.
  name: Spring Integration Kafka Adapter
  slug: spring-integration-kafka
capabilities:
- description: Workflow capability for monitoring and managing Spring Integration message flows at runtime. Provides channel statistics, handler metrics, adapter lifecycle control, and integration flow graph visuali
  name: Spring Integration - Integration Monitoring
  slug: integration-monitoring
common:
- title: ''
  type: Website
  url: https://spring.io/projects/spring-integration
- title: ''
  type: Documentation
  url: https://docs.spring.io/spring-integration/reference/
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-projects/spring-integration
- title: ''
  type: Getting Started
  url: https://spring.io/guides/gs/integration
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-integration
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework.integration
- title: ''
  type: Releases
  url: https://github.com/spring-projects/spring-integration/releases
- title: ''
  type: Blog
  url: https://spring.io/blog/category/integration
- title: ''
  type: Sample Projects
  url: https://github.com/spring-projects/spring-integration-samples
created: '2026-03-27'
description: Spring Integration extends the Spring programming model to support enterprise integration patterns (EIP), providing lightweight messaging within Spring-based applications and integration with external systems via declarative adapters. It supports message channels, filters, transformers, routers, aggregators, and a wide range of inbound/outbound adapters for HTTP, JMS, AMQP, TCP, FTP, JDBC, email, and many more.
features: []
image: https://spring.io/img/projects/spring-integration.svg
integrations: []
jsonld:
- class_count: 3
  name: Spring Integration Context
  property_count: 21
  slug: spring-integration-context
layout: provider
modified: '2026-05-02'
name: Spring Integration
rules:
- name: Spring Integration API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 3
  slug: spring-integration-rules
skills: []
slug: spring-integration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-integration\nname: Spring Integration\ndescription: >-\n  Spring Integration extends the Spring programming model to support enterprise\n  integration patterns (EIP), providing lightweight messaging within Spring-based\n  applications and integration with external systems via declarative adapters.\n  It supports message channels, filters, transformers, routers, aggregators,\n  and a wide range of inbound/outbound adapters for HTTP, JMS, AMQP, TCP, FTP,\n  JDBC, email, and many more.\ntype: Index\nimage: https://spring.io/img/projects/spring-integration.svg\nurl: https://spring.io/projects/spring-integration\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - AMQP\n  - Enterprise Integration\n  - Event-Driven\n  - Integration Patterns\n  - Java\n  - Messaging\n  - Spring\napis:\n  - aid: spring-integration:spring-integration-http\n    name: Spring Integration HTTP Adapter API\n    description: >-\n      HTTP inbound and outbound\
  \ channel adapters for Spring Integration.\n      Provides HTTP request-response messaging, REST template integration,\n      and configurable URL mapping for inbound HTTP gateways.\n    humanURL: https://docs.spring.io/spring-integration/docs/current/reference/html/http.html\n    baseURL: http://localhost:8080\n    tags:\n      - HTTP\n      - Inbound\n      - Messaging\n      - Outbound\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-integration/docs/current/reference/html/http.html\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-integration\n      - type: OpenAPI\n        url: openapi/spring-integration-http-openapi.yml\n  - aid: spring-integration:spring-integration-management\n    name: Spring Integration Management API\n    description: >-\n      Management and monitoring REST API for Spring Integration. Exposes channel\n      statistics, handler metrics, component lifecycle control (start/stop),\
  \ and\n      message history configuration via HTTP endpoints.\n    humanURL: https://docs.spring.io/spring-integration/docs/current/reference/html/management.html\n    baseURL: http://localhost:8080/api\n    tags:\n      - Management\n      - Messaging\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-integration/docs/current/reference/html/management.html\n      - type: OpenAPI\n        url: openapi/spring-integration-management-openapi.yml\n  - aid: spring-integration:spring-integration-amqp\n    name: Spring Integration AMQP Adapter\n    description: >-\n      AMQP channel adapters and gateways for Spring Integration. Provides\n      RabbitMQ message-driven and polling inbound adapters, outbound channel\n      adapters, and request/reply gateways.\n    humanURL: https://docs.spring.io/spring-integration/docs/current/reference/html/amqp.html\n    tags:\n      - AMQP\n      - Messaging\n      - RabbitMQ\n  \
  \  properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-integration/docs/current/reference/html/amqp.html\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.integration/spring-integration-amqp\n  - aid: spring-integration:spring-integration-kafka\n    name: Spring Integration Kafka Adapter\n    description: >-\n      Kafka channel adapters for Spring Integration. Provides message-driven\n      inbound adapters, outbound channel adapters, and request/reply gateways\n      for Apache Kafka integration.\n    humanURL: https://docs.spring.io/spring-integration/docs/current/reference/html/kafka.html\n    tags:\n      - Event Streaming\n      - Kafka\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-integration/docs/current/reference/html/kafka.html\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.integration/spring-integration-kafka\n\
  common:\n  - type: Website\n    url: https://spring.io/projects/spring-integration\n  - type: Documentation\n    url: https://docs.spring.io/spring-integration/reference/\n  - type: GitHub Organization\n    url: https://github.com/spring-projects/spring-integration\n  - type: Getting Started\n    url: https://spring.io/guides/gs/integration\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-integration\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework.integration\n  - type: Releases\n    url: https://github.com/spring-projects/spring-integration/releases\n  - type: Blog\n    url: https://spring.io/blog/category/integration\n  - type: Sample Projects\n    url: https://github.com/spring-projects/spring-integration-samples\nmaintainers:\n  - FN: Spring Team\n    email: spring-projects@vmware.com\n    url: https://spring.io/team\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-integration/refs/heads/main/apis.yml
tags:
- AMQP
- Enterprise Integration
- Event-Driven
- Integration Patterns
- Java
- Messaging
- Spring
url: https://spring.io/projects/spring-integration
use_cases: []
---
