---
api_count: 8
api_specs:
- filename: openapi.json
  format: json
  label: Spring Cloud Config
  slug: ''
  spec_type: OpenAPI
  url: https://example.com/spring-cloud-config/openapi.json
- filename: spring-cloud-gateway-actuator-openapi.yml
  format: yaml
  label: Spring Cloud Gateway
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-cloud/refs/heads/main/openapi/spring-cloud-gateway-actuator-openapi.yml
apis:
- description: Externalized configuration management backed by Git, providing server and client-side support for configuration in distributed systems.
  name: Spring Cloud Config
  slug: ''
- description: Service discovery using Netflix Eureka for registering and discovering microservices.
  name: Spring Cloud Netflix Eureka
  slug: ''
- description: Intelligent routing and filtering for microservices built on Spring WebFlux.
  name: Spring Cloud Gateway
  slug: ''
- description: Framework for building event-driven microservices connected with shared messaging systems.
  name: Spring Cloud Stream
  slug: ''
- description: Distributed tracing solution for Spring Cloud applications with support for Zipkin and other tracing systems.
  name: Spring Cloud Sleuth
  slug: ''
- description: Abstraction across different circuit breaker implementations like Resilience4J and Spring Retry.
  name: Spring Cloud Circuit Breaker
  slug: ''
- description: Declarative REST client with support for Spring MVC annotations and HttpMessageConverters.
  name: Spring Cloud OpenFeign
  slug: ''
- description: Integration with Kubernetes providing service discovery, configuration, and load balancing.
  name: Spring Cloud Kubernetes
  slug: ''
common: []
created: '2024-01-15'
description: A collection of APIs and services provided by Spring Cloud for building cloud-native applications.
features: []
image: https://spring.io/img/spring-cloud.svg
integrations: []
layout: provider
modified: '2026-03-16'
name: Spring Cloud
skills: []
slug: spring-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Spring Cloud\ndescription: >-\n  A collection of APIs and services provided by Spring Cloud for building cloud-native\n  applications.\nimage: https://spring.io/img/spring-cloud.svg\nurl: https://spring.io/projects/spring-cloud\ncreated: '2024-01-15'\nmodified: '2026-03-16'\nspecificationVersion: '0.16'\ntags:\n  - Cloud\n  - Distributed Systems\n  - Java\n  - Microservices\n  - Spring Framework\napis:\n  - name: Spring Cloud Config\n    description: >-\n      Externalized configuration management backed by Git, providing server and client-side\n      support for configuration in distributed systems.\n    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-config\n    baseURL: http://localhost:8888\n    tags:\n      - Configuration\n      - Distributed Config\n      - Git\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-config/docs/current/reference/html/\n      -\
  \ type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-config\n      - type: OpenAPI\n        url: https://example.com/spring-cloud-config/openapi.json\n      - type: JSONSchema\n        url: json-schema/spring-cloud-config-properties.json\n    contact:\n      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\n        X-twitter: springcloud\n  - name: Spring Cloud Netflix Eureka\n    description: >-\n      Service discovery using Netflix Eureka for registering and discovering microservices.\n    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-netflix\n    baseURL: http://localhost:8761\n    tags:\n      - Eureka\n      - Registry\n      - Service Discovery\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-netflix/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-netflix\n      - type: API\
  \ Endpoint\n        url: http://localhost:8761/eureka/apps\n    contact:\n      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\n  - name: Spring Cloud Gateway\n    description: >-\n      Intelligent routing and filtering for microservices built on Spring WebFlux.\n    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-gateway\n    baseURL: http://localhost:8080\n    tags:\n      - Api Gateway\n      - Filtering\n      - Load Balancing\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-gateway\n      - type: Actuator Endpoints\n        url: http://localhost:8080/actuator/gateway\n      - type: OpenAPI\n        url: openapi/spring-cloud-gateway-actuator-openapi.yml\n    contact:\n      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\n\
  \  - name: Spring Cloud Stream\n    description: >-\n      Framework for building event-driven microservices connected with shared messaging\n      systems.\n    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-stream\n    baseURL: https://spring.io/projects/spring-cloud-stream\n    tags:\n      - Event-Driven\n      - Kafka\n      - Messaging\n      - Rabbitmq\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-stream\n      - type: Getting Started\n        url: https://spring.io/guides/gs/spring-cloud-stream/\n    contact:\n      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\n  - name: Spring Cloud Sleuth\n    description: >-\n      Distributed tracing solution for Spring Cloud applications with support for\n      Zipkin and other tracing systems.\n\
  \    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-sleuth\n    baseURL: https://spring.io/projects/spring-cloud-sleuth\n    tags:\n      - Distributed Tracing\n      - Observability\n      - Tracing\n      - Zipkin\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-sleuth/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-sleuth\n    contact:\n      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\n  - name: Spring Cloud Circuit Breaker\n    description: >-\n      Abstraction across different circuit breaker implementations like Resilience4J\n      and Spring Retry.\n    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-circuitbreaker\n    baseURL: https://spring.io/projects/spring-cloud-circuitbreaker\n    tags:\n      - Circuit Breaker\n      -\
  \ Fault Tolerance\n      - Resilience\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-circuitbreaker/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-circuitbreaker\n    contact:\n      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\n  - name: Spring Cloud OpenFeign\n    description: >-\n      Declarative REST client with support for Spring MVC annotations and HttpMessageConverters.\n    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-openfeign\n    baseURL: https://spring.io/projects/spring-cloud-openfeign\n    tags:\n      - Feign\n      - Http\n      - Rest Client\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-openfeign/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-openfeign\n    contact:\n\
  \      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\n  - name: Spring Cloud Kubernetes\n    description: >-\n      Integration with Kubernetes providing service discovery, configuration, and\n      load balancing.\n    image: https://spring.io/img/projects/spring-cloud.svg\n    humanURL: https://spring.io/projects/spring-cloud-kubernetes\n    baseURL: https://spring.io/projects/spring-cloud-kubernetes\n    tags:\n      - Container Orchestration\n      - Kubernetes\n      - Service Discovery\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-kubernetes/docs/current/reference/html/\n      - type: GitHub\n        url: https://github.com/spring-cloud/spring-cloud-kubernetes\n    contact:\n      - FN: Spring Cloud Team\n        email: spring-cloud@pivotal.io\nmaintainers:\n  - FN: VMware Tanzu\n    email: support@vmware.com\n    X-twitter: springcloud\n    X-github: spring-cloud\ninclude:\n  - name: Spring Boot APIs\n    url: https://example.com/apis/spring-boot-apis.json\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud/refs/heads/main/apis.yml
tags:
- Cloud
- Distributed Systems
- Java
- Microservices
- Spring Framework
url: https://spring.io/projects/spring-cloud
use_cases: []
---
