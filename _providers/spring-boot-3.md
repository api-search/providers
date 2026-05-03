---
api_count: 5
api_specs:
- filename: spring-boot-3-actuator-openapi.yml
  format: yaml
  label: Spring Boot Actuator API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-boot-3/refs/heads/main/openapi/spring-boot-3-actuator-openapi.yml
apis:
- description: Production-ready features for monitoring and managing Spring Boot 3 applications. Provides over 50 built-in endpoints exposing health status, metrics (Micrometer), environment properties, loggers, thr
  name: Spring Boot Actuator API
  slug: ''
- description: Core Spring Boot 3 framework providing auto-configuration, embedded server support (Tomcat, Jetty, Undertow), externalized configuration, profiles, and conditional bean registration.
  name: Spring Boot Core Framework
  slug: ''
- description: Web MVC framework for building web applications and RESTful services with Spring Boot 3. Includes controllers, filters, interceptors, and content negotiation.
  name: Spring Web MVC API
  slug: ''
- description: Automatically expose Spring Data repositories as hypermedia-driven REST resources using HAL. Integrates with Spring Data JPA, MongoDB, Neo4j, and other stores.
  name: Spring Data REST API
  slug: ''
- description: Security framework for authentication and authorization in Spring Boot 3 applications. Supports OAuth2, OIDC, SAML2, JWT, and method-level security.
  name: Spring Security API
  slug: ''
capabilities:
- description: 'Workflow capability for monitoring and observing Spring Boot 3 applications using Actuator endpoints. Provides unified access to health status, JVM and application metrics, environment configuration, '
  name: Spring Boot 3 Application Observability
  slug: application-observability
common:
- title: ''
  type: Getting Started
  url: https://spring.io/guides/gs/spring-boot/
- title: ''
  type: GitHub Repository
  url: https://github.com/spring-projects/spring-boot
- title: ''
  type: Release Notes
  url: https://github.com/spring-projects/spring-boot/releases
- title: ''
  type: Migration Guide
  url: https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide
- title: ''
  type: Community
  url: https://spring.io/community
- title: ''
  type: Blog
  url: https://spring.io/blog
created: '2024-01-15'
description: Spring Boot 3 is the major release of the opinionated Spring application framework, now built on Spring Framework 6, requiring Java 17 baseline and Jakarta EE 10. It delivers native image support via GraalVM, improved observability with Micrometer tracing, and a modernized auto-configuration system. Spring Boot 3 simplifies the development of production-ready stand-alone Spring applications with embedded servers, health endpoints, and externalized configuration.
features: []
image: https://spring.io/img/spring-logo.svg
integrations: []
jsonld:
- class_count: 8
  name: Spring Boot 3 Context
  property_count: 24
  slug: spring-boot-3-context
layout: provider
modified: '2026-05-02'
name: Spring Boot 3
rules:
- name: Spring Boot 3 API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: spring-boot-3-rules
skills: []
slug: spring-boot-3
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Spring Boot 3\ndescription: >-\n  Spring Boot 3 is the major release of the opinionated Spring application\n  framework, now built on Spring Framework 6, requiring Java 17 baseline and\n  Jakarta EE 10. It delivers native image support via GraalVM, improved\n  observability with Micrometer tracing, and a modernized auto-configuration\n  system. Spring Boot 3 simplifies the development of production-ready\n  stand-alone Spring applications with embedded servers, health endpoints,\n  and externalized configuration.\nimage: https://spring.io/img/spring-logo.svg\nurl: https://spring.io/projects/spring-boot\ntype: opensource\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Enterprise\n  - Framework\n  - Java\n  - Microservices\n  - REST API\n  - Spring Boot\napis:\n  - name: Spring Boot Actuator API\n    description: >-\n      Production-ready features for monitoring and managing Spring Boot 3\n      applications. Provides over 50 built-in\
  \ endpoints exposing health status,\n      metrics (Micrometer), environment properties, loggers, thread dumps,\n      heap dumps, HTTP trace, and more via HTTP or JMX.\n    humanURL: https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/actuator.html\n    baseURL: http://localhost:8080/actuator\n    tags:\n      - Health Check\n      - Management\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/actuator.html\n      - type: API Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.2.x/actuator-api/htmlsingle/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-boot\n      - type: OpenAPI\n        url: openapi/spring-boot-3-actuator-openapi.yml\n      - type: Spectral Rules\n        url: rules/spring-boot-3-rules.yml\n  - name: Spring Boot Core Framework\n    description: >-\n      Core Spring Boot 3 framework providing\
  \ auto-configuration, embedded server\n      support (Tomcat, Jetty, Undertow), externalized configuration, profiles,\n      and conditional bean registration.\n    humanURL: https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/\n    baseURL: https://github.com/spring-projects/spring-boot\n    tags:\n      - Auto-Configuration\n      - Embedded Server\n      - Framework\n      - Java\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.2.x/reference/html/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-boot/docs/3.2.x/api/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-boot\n      - type: Getting Started\n        url: https://spring.io/guides/gs/spring-boot/\n      - type: Release Notes\n        url: https://github.com/spring-projects/spring-boot/releases\n      - type: Migration Guide\n        url: https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide\n\
  \      - type: Maven Central\n        url: https://mvnrepository.com/artifact/org.springframework.boot/spring-boot\n  - name: Spring Web MVC API\n    description: >-\n      Web MVC framework for building web applications and RESTful services with\n      Spring Boot 3. Includes controllers, filters, interceptors, and content\n      negotiation.\n    humanURL: https://docs.spring.io/spring-framework/docs/6.1.x/reference/html/web.html\n    baseURL: http://localhost:8080\n    tags:\n      - HTTP\n      - MVC\n      - REST\n      - Web\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/docs/6.1.x/reference/html/web.html\n      - type: Tutorial\n        url: https://spring.io/guides/gs/rest-service/\n  - name: Spring Data REST API\n    description: >-\n      Automatically expose Spring Data repositories as hypermedia-driven REST\n      resources using HAL. Integrates with Spring Data JPA, MongoDB, Neo4j,\n      and other stores.\n    humanURL:\
  \ https://docs.spring.io/spring-data/rest/docs/current/reference/html/\n    baseURL: http://localhost:8080/api\n    tags:\n      - CRUD\n      - Data\n      - HAL\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/rest/docs/current/reference/html/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-data/rest/docs/current/api/\n  - name: Spring Security API\n    description: >-\n      Security framework for authentication and authorization in Spring Boot 3\n      applications. Supports OAuth2, OIDC, SAML2, JWT, and method-level security.\n    humanURL: https://docs.spring.io/spring-security/reference/\n    baseURL: http://localhost:8080\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth2\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-security/reference/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-security/site/docs/6.2.x/api/\n\
  \      - type: OAuth2 Guide\n        url: https://spring.io/guides/tutorials/spring-boot-oauth2/\nmaintainers:\n  - name: VMware Tanzu (Broadcom)\n    email: spring-team@vmware.com\n    url: https://spring.io/team\ncommon:\n  - type: Getting Started\n    url: https://spring.io/guides/gs/spring-boot/\n  - type: GitHub Repository\n    url: https://github.com/spring-projects/spring-boot\n  - type: Release Notes\n    url: https://github.com/spring-projects/spring-boot/releases\n  - type: Migration Guide\n    url: https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide\n  - type: Community\n    url: https://spring.io/community\n  - type: Blog\n    url: https://spring.io/blog\ninclude:\n  - name: Spring Framework\n    url: https://spring.io/projects/spring-framework\n  - name: Spring Cloud\n    url: https://spring.io/projects/spring-cloud\n  - name: Spring Data\n    url: https://spring.io/projects/spring-data\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-boot-3/refs/heads/main/apis.yml
tags:
- Enterprise
- Framework
- Java
- Microservices
- REST API
- Spring Boot
url: https://spring.io/projects/spring-boot
use_cases: []
---
