---
api_count: 4
api_specs:
- filename: spring-initializr-openapi.yml
  format: yaml
  label: Spring Initializr API
  slug: spring-initializr
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-framework/refs/heads/main/openapi/spring-initializr-openapi.yml
apis:
- description: API for generating Spring Boot projects with customizable dependencies, build tool, language, and Java version. Provides metadata endpoints to discover available starters and configuration options.
  name: Spring Initializr API
  slug: spring-initializr
- description: Production-ready features for monitoring and managing Spring Boot applications. Exposes health checks, metrics, environment info, configuration properties, thread dumps, heap dumps, and logger configu
  name: Spring Boot Actuator API
  slug: spring-boot-actuator
- description: Model-View-Controller web framework built on the Servlet API. Supports annotation-driven controllers, content negotiation, validation, data binding, file uploads, CORS, and exception handling in a fle
  name: Spring MVC Web Framework
  slug: spring-mvc
- description: Reactive-stack web framework for building non-blocking, event-driven web applications on top of Project Reactor. Supports annotated controllers and functional endpoints with reactive programming model
  name: Spring WebFlux Reactive API
  slug: spring-webflux
capabilities:
- description: Workflow capability for discovering Spring Boot options and generating new Spring Boot projects. Combines Spring Initializr metadata discovery and project generation. Used by developers, DevOps teams,
  name: Spring Framework - Project Bootstrapping
  slug: project-bootstrapping
common:
- title: ''
  type: Website
  url: https://spring.io/projects/spring-framework
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-projects
- title: ''
  type: GitHub Repository
  url: https://github.com/spring-projects/spring-framework
- title: ''
  type: Blog
  url: https://spring.io/blog
- title: ''
  type: Guides
  url: https://spring.io/guides
- title: ''
  type: Quick Start
  url: https://spring.io/quickstart
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring
- title: ''
  type: Twitter
  url: https://twitter.com/springcentral
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/SpringSourceDev
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework/spring-framework
- title: ''
  type: Releases
  url: https://github.com/spring-projects/spring-framework/releases
- title: ''
  type: Documentation
  url: https://docs.spring.io/spring-framework/docs/current/reference/html/
created: '2024-01-01'
description: 'The Spring Framework provides a comprehensive programming and configuration model for modern Java-based enterprise applications on any kind of deployment platform. A key element of Spring is infrastructural support at the application level: Spring focuses on the "plumbing" of enterprise applications so that teams can focus on application-level business logic, without unnecessary ties to specific deployment environments. It includes modules for dependency injection, data access, web development, aspect-oriented programming, and more.'
features: []
image: https://spring.io/img/spring-logo.svg
integrations: []
jsonld:
- class_count: 10
  name: Spring Framework Context
  property_count: 14
  slug: spring-framework-context
layout: provider
modified: '2026-05-02'
name: Spring Framework
rules:
- name: Spring Framework API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 3
  slug: spring-framework-rules
skills: []
slug: spring-framework
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-framework\nname: Spring Framework\ndescription: >-\n  The Spring Framework provides a comprehensive programming and configuration\n  model for modern Java-based enterprise applications on any kind of deployment\n  platform. A key element of Spring is infrastructural support at the application\n  level: Spring focuses on the \"plumbing\" of enterprise applications so that teams\n  can focus on application-level business logic, without unnecessary ties to specific\n  deployment environments. It includes modules for dependency injection, data access,\n  web development, aspect-oriented programming, and more.\ntype: Index\nimage: https://spring.io/img/spring-logo.svg\nurl: https://spring.io/projects/spring-framework\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - AOP\n  - Dependency Injection\n  - Enterprise\n  - Framework\n  - IoC\n  - Java\n  - Microservices\n  - MVC\n  - Spring Boot\napis:\n  - aid: spring-framework:spring-initializr\n\
  \    name: Spring Initializr API\n    description: >-\n      API for generating Spring Boot projects with customizable dependencies,\n      build tool, language, and Java version. Provides metadata endpoints to\n      discover available starters and configuration options.\n    image: https://spring.io/img/spring-logo.svg\n    humanURL: https://start.spring.io\n    baseURL: https://start.spring.io\n    tags:\n      - Bootstrap\n      - Code Generation\n      - Configuration\n      - Project Generation\n    properties:\n      - type: Documentation\n        url: https://github.com/spring-io/start.spring.io\n      - type: API Endpoint\n        url: https://start.spring.io/\n      - type: OpenAPI\n        url: openapi/spring-initializr-openapi.yml\n  - aid: spring-framework:spring-boot-actuator\n    name: Spring Boot Actuator API\n    description: >-\n      Production-ready features for monitoring and managing Spring Boot applications.\n      Exposes health checks, metrics, environment info,\
  \ configuration properties,\n      thread dumps, heap dumps, and logger configuration via HTTP endpoints.\n    image: https://spring.io/img/spring-logo.svg\n    humanURL: https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html\n    baseURL: http://localhost:8080/actuator\n    tags:\n      - Health\n      - Management\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/docs/current/actuator-api/htmlsingle/\n      - type: Reference\n        url: https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html\n  - aid: spring-framework:spring-mvc\n    name: Spring MVC Web Framework\n    description: >-\n      Model-View-Controller web framework built on the Servlet API. Supports\n      annotation-driven controllers, content negotiation, validation, data binding,\n      file uploads, CORS, and exception handling in a flexible servlet container.\n    image: https://spring.io/img/spring-logo.svg\n\
  \    humanURL: https://docs.spring.io/spring-framework/docs/current/reference/html/web.html\n    baseURL: http://localhost:8080\n    tags:\n      - Annotations\n      - HTTP\n      - MVC\n      - REST\n      - Web\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/docs/current/reference/html/web.html\n      - type: API Reference\n        url: https://docs.spring.io/spring-framework/docs/current/javadoc-api/\n      - type: Getting Started\n        url: https://spring.io/guides/gs/serving-web-content/\n  - aid: spring-framework:spring-webflux\n    name: Spring WebFlux Reactive API\n    description: >-\n      Reactive-stack web framework for building non-blocking, event-driven\n      web applications on top of Project Reactor. Supports annotated controllers\n      and functional endpoints with reactive programming model.\n    image: https://spring.io/img/spring-logo.svg\n    humanURL: https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html\n\
  \    baseURL: http://localhost:8080\n    tags:\n      - Non-Blocking\n      - Reactive\n      - Reactor\n      - WebFlux\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html\n      - type: API Reference\n        url: https://docs.spring.io/spring-framework/docs/current/javadoc-api/\n      - type: Guide\n        url: https://spring.io/guides/gs/reactive-rest-service/\ncommon:\n  - type: Website\n    url: https://spring.io/projects/spring-framework\n  - type: GitHub Organization\n    url: https://github.com/spring-projects\n  - type: GitHub Repository\n    url: https://github.com/spring-projects/spring-framework\n  - type: Blog\n    url: https://spring.io/blog\n  - type: Guides\n    url: https://spring.io/guides\n  - type: Quick Start\n    url: https://spring.io/quickstart\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring\n  - type: Twitter\n    url: https://twitter.com/springcentral\n\
  \  - type: YouTube\n    url: https://www.youtube.com/user/SpringSourceDev\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework/spring-framework\n  - type: Releases\n    url: https://github.com/spring-projects/spring-framework/releases\n  - type: Documentation\n    url: https://docs.spring.io/spring-framework/docs/current/reference/html/\nmaintainers:\n  - FN: VMware Broadcom Spring Team\n    email: spring-projects@vmware.com\n    url: https://spring.io/team\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-framework/refs/heads/main/apis.yml
tags:
- AOP
- Dependency Injection
- Enterprise
- Framework
- IoC
- Java
- Microservices
- MVC
- Spring Boot
url: https://spring.io/projects/spring-framework
use_cases: []
---
