---
api_count: 4
api_specs:
- filename: spring-boot-actuator-openapi.yml
  format: yaml
  label: Spring Boot Actuator API
  slug: spring-boot-actuator
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-boot/refs/heads/main/openapi/spring-boot-actuator-openapi.yml
apis:
- description: Production-ready management and monitoring endpoints for Spring Boot applications. Provides health checks, metrics, environment info, configuration properties, thread dumps, heap dumps, logger configu
  name: Spring Boot Actuator API
  slug: spring-boot-actuator
- description: RESTful web services built with Spring Boot using Spring MVC or Spring WebFlux. Supports JSON, XML, and hypermedia responses with full content negotiation, validation, error handling, and CORS configu
  name: Spring Boot REST API
  slug: spring-boot-rest-api
- description: Exposes Spring Data repositories as hypermedia-driven RESTful resources automatically. Supports HAL, collection+json media types, sorting, pagination, projections, and custom event handlers.
  name: Spring Data REST API
  slug: spring-data-rest
- description: Admin UI and monitoring tool for Spring Boot applications providing registration, health monitoring, log level management, JMX bean access, and notification capabilities for multiple application insta
  name: Spring Boot Admin API
  slug: spring-boot-admin
capabilities:
- description: Unified capability for monitoring and managing Spring Boot applications using Actuator endpoints. Enables health checks, metrics collection, log level management, and cache operations for DevOps and S
  name: Spring Boot Application Monitoring
  slug: application-monitoring
common:
- title: ''
  type: Documentation
  url: https://docs.spring.io/spring-boot/
- title: ''
  type: Website
  url: https://spring.io/projects/spring-boot
- title: ''
  type: GitHub
  url: https://github.com/spring-projects/spring-boot
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-projects
- title: ''
  type: Issues
  url: https://github.com/spring-projects/spring-boot/issues
- title: ''
  type: Releases
  url: https://github.com/spring-projects/spring-boot/releases
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-boot
- title: ''
  type: Blog
  url: https://spring.io/blog/category/spring-boot
- title: ''
  type: Guides
  url: https://spring.io/guides
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework.boot/spring-boot
- title: ''
  type: Maven Central
  url: https://search.maven.org/artifact/org.springframework.boot/spring-boot
- title: ''
  type: Spring Initializr
  url: https://start.spring.io/
- title: ''
  type: Vocabulary
  url: vocabulary/spring-boot-vocabulary.yml
created: '2024-01-01'
description: Spring Boot is an open source Java-based framework used to create stand-alone, production-grade Spring-based applications with minimal configuration. It provides auto-configuration, embedded server support, opinionated defaults, and production-ready features including health checks, metrics, and externalized configuration management.
features: []
image: https://spring.io/img/spring-boot-logo.png
integrations: []
jsonld:
- class_count: 12
  name: Spring Boot Context
  property_count: 13
  slug: spring-boot-context
layout: provider
modified: '2026-05-02'
name: Spring Boot
rules:
- name: Spring Boot API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: spring-boot-actuator-rules
skills: []
slug: spring-boot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-boot\nname: Spring Boot\ndescription: >-\n  Spring Boot is an open source Java-based framework used to create stand-alone,\n  production-grade Spring-based applications with minimal configuration. It provides\n  auto-configuration, embedded server support, opinionated defaults, and production-ready\n  features including health checks, metrics, and externalized configuration management.\nimage: https://spring.io/img/spring-boot-logo.png\nurl: https://spring.io/projects/spring-boot\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Auto Configuration\n  - Embedded Server\n  - Framework\n  - Java\n  - Microservices\n  - REST API\n  - Spring\n  - Web Development\napis:\n  - aid: spring-boot:spring-boot-actuator\n    name: Spring Boot Actuator API\n    description: >-\n      Production-ready management and monitoring endpoints for Spring Boot applications.\n      Provides health checks, metrics, environment info, configuration properties,\n\
  \      thread dumps, heap dumps, logger configuration, cache management, and graceful shutdown.\n    image: https://spring.io/img/spring-boot-logo.png\n    humanURL: https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html\n    baseURL: http://localhost:8080/actuator\n    tags:\n      - Actuator\n      - Health Check\n      - Management\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/current/actuator-api/htmlsingle/\n      - type: OpenAPI\n        url: openapi/spring-boot-actuator-openapi.yml\n      - type: JSONSchema\n        url: json-schema/spring-boot-actuator-health-schema.json\n      - type: JSONSchema\n        url: json-schema/spring-boot-actuator-metric-schema.json\n      - type: JSONStructure\n        url: json-structure/spring-boot-actuator-structure.json\n      - type: JSONLDContext\n        url: json-ld/spring-boot-context.jsonld\n      - type: SpectralRules\n      \
  \  url: rules/spring-boot-actuator-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/application-monitoring.yaml\n  - aid: spring-boot:spring-boot-rest-api\n    name: Spring Boot REST API\n    description: >-\n      RESTful web services built with Spring Boot using Spring MVC or Spring WebFlux.\n      Supports JSON, XML, and hypermedia responses with full content negotiation,\n      validation, error handling, and CORS configuration.\n    humanURL: https://spring.io/guides/gs/rest-service/\n    baseURL: http://localhost:8080/api\n    tags:\n      - HTTP\n      - JSON\n      - REST\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/current/reference/html/web.html\n      - type: Getting Started Guide\n        url: https://spring.io/guides/gs/rest-service/\n      - type: Tutorial\n        url: https://spring.io/guides/tutorials/rest/\n  - aid: spring-boot:spring-data-rest\n    name: Spring Data REST\
  \ API\n    description: >-\n      Exposes Spring Data repositories as hypermedia-driven RESTful resources automatically.\n      Supports HAL, collection+json media types, sorting, pagination, projections,\n      and custom event handlers.\n    humanURL: https://spring.io/projects/spring-data-rest\n    baseURL: http://localhost:8080/\n    tags:\n      - Database\n      - HATEOAS\n      - Repository\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/rest/docs/current/reference/html/\n      - type: API Guide\n        url: https://docs.spring.io/spring-data/rest/docs/current/api/\n      - type: Getting Started\n        url: https://spring.io/guides/gs/accessing-data-rest/\n  - aid: spring-boot:spring-boot-admin\n    name: Spring Boot Admin API\n    description: >-\n      Admin UI and monitoring tool for Spring Boot applications providing registration,\n      health monitoring, log level management, JMX bean access, and notification\n\
  \      capabilities for multiple application instances.\n    humanURL: https://github.com/codecentric/spring-boot-admin\n    baseURL: http://localhost:8080/admin\n    tags:\n      - Administration\n      - Dashboard\n      - Management\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://codecentric.github.io/spring-boot-admin/current/\n      - type: GitHub Repository\n        url: https://github.com/codecentric/spring-boot-admin\n      - type: Getting Started\n        url: https://codecentric.github.io/spring-boot-admin/current/#getting-started\ncommon:\n  - type: Documentation\n    url: https://docs.spring.io/spring-boot/\n  - type: Website\n    url: https://spring.io/projects/spring-boot\n  - type: GitHub\n    url: https://github.com/spring-projects/spring-boot\n  - type: GitHub Organization\n    url: https://github.com/spring-projects\n  - type: Issues\n    url: https://github.com/spring-projects/spring-boot/issues\n  - type: Releases\n    url: https://github.com/spring-projects/spring-boot/releases\n\
  \  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-boot\n  - type: Blog\n    url: https://spring.io/blog/category/spring-boot\n  - type: Guides\n    url: https://spring.io/guides\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework.boot/spring-boot\n  - type: Maven Central\n    url: https://search.maven.org/artifact/org.springframework.boot/spring-boot\n  - type: Spring Initializr\n    url: https://start.spring.io/\n  - type: Vocabulary\n    url: vocabulary/spring-boot-vocabulary.yml\nmaintainers:\n  - FN: VMware Tanzu (Spring Team)\n    email: spring-boot@vmware.com\n    url: https://spring.io/team\ninclude:\n  - name: Spring Framework\n    url: https://spring.io/projects/spring-framework\n  - name: Spring Cloud\n    url: https://spring.io/projects/spring-cloud\n  - name: Spring Data\n    url: https://spring.io/projects/spring-data\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-boot/refs/heads/main/apis.yml
tags:
- Auto Configuration
- Embedded Server
- Framework
- Java
- Microservices
- REST API
- Spring
- Web Development
url: https://spring.io/projects/spring-boot
use_cases: []
---
