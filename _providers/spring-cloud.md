---
api_count: 7
api_specs:
- filename: spring-cloud-gateway-actuator-openapi.yml
  format: yaml
  label: Spring Cloud Gateway
  slug: spring-cloud-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-cloud/refs/heads/main/openapi/spring-cloud-gateway-actuator-openapi.yml
apis:
- description: Externalized configuration management backed by Git, providing server and client-side support for configuration in distributed systems with encryption, refresh, and multi-environment support.
  name: Spring Cloud Config
  slug: spring-cloud-config
- description: Service discovery using Netflix Eureka for registering and discovering microservices, providing self-registration, client-side discovery, heartbeat-based health checks, and zone-aware load balancing.
  name: Spring Cloud Netflix Eureka
  slug: spring-cloud-netflix-eureka
- description: Intelligent routing and filtering for microservices built on Spring WebFlux with predicates, filters, load balancing, circuit breaking, and rate limiting.
  name: Spring Cloud Gateway
  slug: spring-cloud-gateway
- description: Framework for building event-driven microservices connected with shared messaging systems including Apache Kafka and RabbitMQ with consumer groups and partitioning.
  name: Spring Cloud Stream
  slug: spring-cloud-stream
- description: Abstraction across different circuit breaker implementations including Resilience4J and Spring Retry, providing bulkhead, rate limiting, time limiting, and fallback patterns.
  name: Spring Cloud Circuit Breaker
  slug: spring-cloud-circuit-breaker
- description: Declarative REST client with support for Spring MVC annotations and HttpMessageConverters, providing load-balanced HTTP calls with Ribbon or Spring Cloud LoadBalancer integration.
  name: Spring Cloud OpenFeign
  slug: spring-cloud-openfeign
- description: Integration with Kubernetes providing service discovery via DNS and Kubernetes API, ConfigMap and Secret-backed property sources, and load balancing for Spring Boot applications deployed in Kubernetes
  name: Spring Cloud Kubernetes
  slug: spring-cloud-kubernetes
capabilities:
- description: Unified capability for managing a Spring Cloud microservice platform including API gateway routing, service discovery inspection, and circuit breaker monitoring. Designed for platform engineers and De
  name: Spring Cloud Microservice Platform
  slug: microservice-platform
common:
- title: ''
  type: Website
  url: https://spring.io/projects/spring-cloud
- title: ''
  type: Documentation
  url: https://docs.spring.io/spring-cloud/
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-cloud
- title: ''
  type: Blog
  url: https://spring.io/blog/category/cloud
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-cloud
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework.cloud
- title: ''
  type: Vocabulary
  url: vocabulary/spring-cloud-vocabulary.yml
created: '2024-01-15'
description: Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems including configuration management, service discovery, circuit breakers, intelligent routing, micro-proxy, control bus, and distributed tracing. It builds on the Spring Boot approach to simplify microservice development and operations across cloud environments.
features: []
image: https://spring.io/img/spring-cloud.svg
integrations: []
jsonld:
- class_count: 8
  name: Spring Cloud Context
  property_count: 9
  slug: spring-cloud-context
layout: provider
modified: '2026-05-02'
name: Spring Cloud
rules:
- name: Spring Cloud API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: spring-cloud-gateway-rules
skills: []
slug: spring-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-cloud\nname: Spring Cloud\ndescription: >-\n  Spring Cloud provides tools for developers to quickly build some of the common\n  patterns in distributed systems including configuration management, service discovery,\n  circuit breakers, intelligent routing, micro-proxy, control bus, and distributed\n  tracing. It builds on the Spring Boot approach to simplify microservice development\n  and operations across cloud environments.\nimage: https://spring.io/img/spring-cloud.svg\nurl: https://spring.io/projects/spring-cloud\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Circuit Breaker\n  - Cloud Native\n  - Distributed Systems\n  - Java\n  - Microservices\n  - Service Discovery\n  - Spring Framework\napis:\n  - aid: spring-cloud:spring-cloud-config\n    name: Spring Cloud Config\n    description: >-\n      Externalized configuration management backed by Git, providing server and\n      client-side support for configuration in\
  \ distributed systems with encryption,\n      refresh, and multi-environment support.\n    humanURL: https://spring.io/projects/spring-cloud-config\n    baseURL: http://localhost:8888\n    tags:\n      - Configuration\n      - Distributed Config\n      - Git\n      - Microservices\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-config/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-config\n      - type: JSONSchema\n        url: json-schema/spring-cloud-config-properties.json\n  - aid: spring-cloud:spring-cloud-netflix-eureka\n    name: Spring Cloud Netflix Eureka\n    description: >-\n      Service discovery using Netflix Eureka for registering and discovering microservices,\n      providing self-registration, client-side discovery, heartbeat-based health checks,\n      and zone-aware load balancing.\n    humanURL: https://spring.io/projects/spring-cloud-netflix\n    baseURL: http://localhost:8761\n\
  \    tags:\n      - Eureka\n      - Registry\n      - Service Discovery\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-netflix/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-netflix\n  - aid: spring-cloud:spring-cloud-gateway\n    name: Spring Cloud Gateway\n    description: >-\n      Intelligent routing and filtering for microservices built on Spring WebFlux with\n      predicates, filters, load balancing, circuit breaking, and rate limiting.\n    humanURL: https://spring.io/projects/spring-cloud-gateway\n    baseURL: http://localhost:8080\n    tags:\n      - API Gateway\n      - Filtering\n      - Load Balancing\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-gateway\n      - type: OpenAPI\n  \
  \      url: openapi/spring-cloud-gateway-actuator-openapi.yml\n      - type: JSONSchema\n        url: json-schema/spring-cloud-service-instance-schema.json\n      - type: JSONStructure\n        url: json-structure/spring-cloud-service-registry-structure.json\n      - type: JSONLDContext\n        url: json-ld/spring-cloud-context.jsonld\n      - type: SpectralRules\n        url: rules/spring-cloud-gateway-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/microservice-platform.yaml\n  - aid: spring-cloud:spring-cloud-stream\n    name: Spring Cloud Stream\n    description: >-\n      Framework for building event-driven microservices connected with shared messaging\n      systems including Apache Kafka and RabbitMQ with consumer groups and partitioning.\n    humanURL: https://spring.io/projects/spring-cloud-stream\n    baseURL: https://spring.io/projects/spring-cloud-stream\n    tags:\n      - Event-Driven\n      - Kafka\n      - Messaging\n      - RabbitMQ\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-stream\n      - type: Getting Started\n        url: https://spring.io/guides/gs/spring-cloud-stream/\n  - aid: spring-cloud:spring-cloud-circuit-breaker\n    name: Spring Cloud Circuit Breaker\n    description: >-\n      Abstraction across different circuit breaker implementations including Resilience4J\n      and Spring Retry, providing bulkhead, rate limiting, time limiting, and fallback patterns.\n    humanURL: https://spring.io/projects/spring-cloud-circuitbreaker\n    baseURL: https://spring.io/projects/spring-cloud-circuitbreaker\n    tags:\n      - Circuit Breaker\n      - Fault Tolerance\n      - Resilience\n      - Resilience4J\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-circuitbreaker/docs/current/reference/html/\n      - type: GitHub\n\
  \        url: https://github.com/spring-cloud/spring-cloud-circuitbreaker\n  - aid: spring-cloud:spring-cloud-openfeign\n    name: Spring Cloud OpenFeign\n    description: >-\n      Declarative REST client with support for Spring MVC annotations and HttpMessageConverters,\n      providing load-balanced HTTP calls with Ribbon or Spring Cloud LoadBalancer integration.\n    humanURL: https://spring.io/projects/spring-cloud-openfeign\n    baseURL: https://spring.io/projects/spring-cloud-openfeign\n    tags:\n      - Declarative Client\n      - Feign\n      - HTTP\n      - REST Client\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-openfeign/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-openfeign\n  - aid: spring-cloud:spring-cloud-kubernetes\n    name: Spring Cloud Kubernetes\n    description: >-\n      Integration with Kubernetes providing service discovery via DNS and Kubernetes\n\
  \      API, ConfigMap and Secret-backed property sources, and load balancing for\n      Spring Boot applications deployed in Kubernetes clusters.\n    humanURL: https://spring.io/projects/spring-cloud-kubernetes\n    baseURL: https://spring.io/projects/spring-cloud-kubernetes\n    tags:\n      - ConfigMap\n      - Container Orchestration\n      - Kubernetes\n      - Service Discovery\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-kubernetes/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-kubernetes\ncommon:\n  - type: Website\n    url: https://spring.io/projects/spring-cloud\n  - type: Documentation\n    url: https://docs.spring.io/spring-cloud/\n  - type: GitHub Organization\n    url: https://github.com/spring-cloud\n  - type: Blog\n    url: https://spring.io/blog/category/cloud\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-cloud\n  - type:\
  \ Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework.cloud\n  - type: Vocabulary\n    url: vocabulary/spring-cloud-vocabulary.yml\nmaintainers:\n  - FN: VMware Tanzu (Spring Team)\n    email: support@vmware.com\n    url: https://spring.io/team\ninclude:\n  - name: Spring Boot\n    url: https://spring.io/projects/spring-boot\n  - name: Spring Framework\n    url: https://spring.io/projects/spring-framework\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud/refs/heads/main/apis.yml
tags:
- Circuit Breaker
- Cloud Native
- Distributed Systems
- Java
- Microservices
- Service Discovery
- Spring Framework
url: https://spring.io/projects/spring-cloud
use_cases: []
---
