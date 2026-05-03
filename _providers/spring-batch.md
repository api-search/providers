---
api_count: 3
api_specs:
- filename: spring-batch-openapi.yml
  format: yaml
  label: Spring Batch Core API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-batch/refs/heads/main/openapi/spring-batch-openapi.yml
apis:
- description: Core framework API for batch processing including job configuration, execution, step management, job repository, and monitoring. Includes support for chunk-oriented processing with configurable reader
  name: Spring Batch Core API
  slug: ''
- description: Spring Boot Actuator-based REST endpoints for monitoring Spring Batch applications. Provides health indicators, Micrometer metrics, and job execution visibility.
  name: Spring Batch Actuator API
  slug: ''
- description: Infrastructure components providing ItemReader, ItemWriter, and ItemProcessor implementations for various data sources and destinations.
  name: Spring Batch Infrastructure API
  slug: ''
capabilities:
- description: Workflow capability for monitoring and observing Spring Batch 5.1 job executions. Combines Actuator health, Micrometer metrics, and job execution history into a unified monitoring interface for platfo
  name: Spring Batch 5.1 Job Monitoring
  slug: batch-job-monitoring
common:
- title: ''
  type: Blog
  url: https://spring.io/blog/category/spring-batch
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-batch
- title: ''
  type: Chat
  url: https://gitter.im/spring-projects/spring-batch
- title: ''
  type: Issues
  url: https://github.com/spring-projects/spring-batch/issues
- title: ''
  type: Roadmap
  url: https://github.com/spring-projects/spring-batch/milestones
- title: ''
  type: License
  url: https://github.com/spring-projects/spring-batch/blob/main/LICENSE
- title: ''
  type: Contributing Guidelines
  url: https://github.com/spring-projects/spring-batch/blob/main/CONTRIBUTING.md
- title: ''
  type: Maven Central
  url: https://search.maven.org/search?q=g:org.springframework.batch
- title: ''
  type: Release Notes
  url: https://github.com/spring-projects/spring-batch/releases
- title: ''
  type: Security Policy
  url: https://github.com/spring-projects/spring-batch/security/policy
created: 2024-01-15 00:00:00+00:00
description: A lightweight, comprehensive batch framework designed to enable the development of robust batch applications vital for the daily operations of enterprise systems. Spring Batch provides reusable functions for processing large volumes of records including logging/tracing, transaction management, job processing statistics, job restart, skip, and resource management. It supports reading and writing from flat files, XML, JSON, databases (JDBC, JPA, Hibernate), message queues, and more.
features: []
image: https://spring.io/img/projects/spring-batch.svg
integrations: []
jsonld:
- class_count: 6
  name: Spring Batch Context
  property_count: 25
  slug: spring-batch-context
layout: provider
modified: '2026-05-02'
name: Spring Batch
rules:
- name: Spring Batch API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: spring-batch-rules
skills: []
slug: spring-batch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Spring Batch\ndescription: >-\n  A lightweight, comprehensive batch framework designed to enable the development\n  of robust batch applications vital for the daily operations of enterprise systems.\n  Spring Batch provides reusable functions for processing large volumes of records\n  including logging/tracing, transaction management, job processing statistics,\n  job restart, skip, and resource management. It supports reading and writing from\n  flat files, XML, JSON, databases (JDBC, JPA, Hibernate), message queues, and more.\nimage: https://spring.io/img/projects/spring-batch.svg\ncreated: 2024-01-15 00:00:00+00:00\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\nurl: https://spring.io/projects/spring-batch\ntype: opensource\ntags:\n  - Batch Processing\n  - Data Processing\n  - Enterprise\n  - ETL\n  - Java\n  - Job Scheduling\n  - Spring Framework\napis:\n  - name: Spring Batch Core API\n    description: >-\n      Core framework API for batch processing including\
  \ job configuration, execution,\n      step management, job repository, and monitoring. Includes support for chunk-oriented\n      processing with configurable readers, processors, and writers.\n    image: https://spring.io/img/projects/spring-batch.svg\n    humanURL: https://spring.io/projects/spring-batch\n    baseURL: https://github.com/spring-projects/spring-batch\n    tags:\n      - Batch Jobs\n      - Chunk Processing\n      - Job Repository\n      - Step Execution\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-batch/docs/current/reference/html/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-batch/docs/current/api/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-batch\n      - type: Getting Started Guide\n        url: https://spring.io/guides/gs/batch-processing/\n      - type: Reference Guide\n        url: https://docs.spring.io/spring-batch/docs/current/reference/html/index-single.html\n\
  \      - type: Samples\n        url: https://github.com/spring-projects/spring-batch/tree/main/spring-batch-samples\n      - type: OpenAPI\n        url: openapi/spring-batch-openapi.yml\n      - type: Spectral Rules\n        url: rules/spring-batch-rules.yml\n  - name: Spring Batch Actuator API\n    description: >-\n      Spring Boot Actuator-based REST endpoints for monitoring Spring Batch\n      applications. Provides health indicators, Micrometer metrics, and job\n      execution visibility.\n    humanURL: https://docs.spring.io/spring-batch/docs/current/reference/html/monitoring-and-metrics.html\n    baseURL: http://localhost:8080/actuator\n    tags:\n      - Actuator\n      - Health\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-batch/docs/current/reference/html/monitoring-and-metrics.html\n  - name: Spring Batch Infrastructure API\n    description: >-\n      Infrastructure components providing ItemReader,\
  \ ItemWriter, and ItemProcessor\n      implementations for various data sources and destinations.\n    humanURL: https://docs.spring.io/spring-batch/docs/current/reference/html/readersAndWriters.html\n    baseURL: https://github.com/spring-projects/spring-batch\n    tags:\n      - Item Readers\n      - Item Writers\n      - JDBC\n      - JPA\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-batch/docs/current/reference/html/readersAndWriters.html\n      - type: API Documentation\n        url: https://docs.spring.io/spring-batch/docs/current/api/org/springframework/batch/item/package-summary.html\nmaintainers:\n  - name: Spring Team\n    email: spring-batch@pivotal.io\n    url: https://spring.io/team\ninclude:\n  - name: Spring Framework\n    url: https://spring.io/projects/spring-framework\n  - name: Spring Boot\n    url: https://spring.io/projects/spring-boot\ncommon:\n  - type: Blog\n    url: https://spring.io/blog/category/spring-batch\n  - type:\
  \ Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-batch\n  - type: Chat\n    url: https://gitter.im/spring-projects/spring-batch\n  - type: Issues\n    url: https://github.com/spring-projects/spring-batch/issues\n  - type: Roadmap\n    url: https://github.com/spring-projects/spring-batch/milestones\n  - type: License\n    url: https://github.com/spring-projects/spring-batch/blob/main/LICENSE\n  - type: Contributing Guidelines\n    url: https://github.com/spring-projects/spring-batch/blob/main/CONTRIBUTING.md\n  - type: Maven Central\n    url: https://search.maven.org/search?q=g:org.springframework.batch\n  - type: Release Notes\n    url: https://github.com/spring-projects/spring-batch/releases\n  - type: Security Policy\n    url: https://github.com/spring-projects/spring-batch/security/policy\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-batch/refs/heads/main/apis.yml
tags:
- Batch Processing
- Data Processing
- Enterprise
- ETL
- Java
- Job Scheduling
- Spring Framework
url: https://spring.io/projects/spring-batch
use_cases: []
---
