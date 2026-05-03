---
api_count: 2
api_specs:
- filename: spring-batch-51-openapi.yml
  format: yaml
  label: Spring Batch 5.1 Core API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-batch-51/refs/heads/main/openapi/spring-batch-51-openapi.yml
apis:
- description: Core API for Spring Batch 5.1 providing batch processing capabilities including job and step configuration, chunk-oriented processing, job repository persistence, and fault tolerance.
  name: Spring Batch 5.1 Core API
  slug: ''
- description: Spring Boot Actuator-based monitoring endpoints for Spring Batch 5.1 applications providing job health, execution status, and Micrometer metrics visibility.
  name: Spring Batch 5.1 Actuator Monitoring
  slug: ''
capabilities:
- description: Workflow capability for monitoring and observing Spring Batch 5.1 job executions. Combines Actuator health, Micrometer metrics, and job execution history into a unified monitoring interface for platfo
  name: Spring Batch 5.1 Job Monitoring
  slug: batch-job-monitoring
common:
- title: ''
  type: Blog
  url: https://spring.io/blog/category/batch
- title: ''
  type: Support
  url: https://spring.io/support
- title: ''
  type: Forum
  url: https://stackoverflow.com/questions/tagged/spring-batch
- title: ''
  type: GitHub Issues
  url: https://github.com/spring-projects/spring-batch/issues
- title: ''
  type: Maven Central
  url: https://search.maven.org/search?q=g:org.springframework.batch
created: '2024-01-15'
description: Spring Batch 5.1 is the latest enterprise batch processing framework release for the Spring ecosystem. Designed to enable development of robust batch applications vital for daily operations of enterprise systems. Version 5.1 delivers Micrometer metrics, virtual thread support (Java 21), and enhanced chunk-oriented processing with retry, skip, and restart capabilities.
features: []
image: https://spring.io/img/projects/spring-batch.svg
integrations: []
jsonld:
- class_count: 6
  name: Spring Batch 51 Context
  property_count: 25
  slug: spring-batch-51-context
layout: provider
modified: '2026-05-02'
name: Spring Batch 5.1
rules:
- name: Spring Batch 5.1 API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: spring-batch-51-rules
skills: []
slug: spring-batch-51
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Spring Batch 5.1\ndescription: >-\n  Spring Batch 5.1 is the latest enterprise batch processing framework release\n  for the Spring ecosystem. Designed to enable development of robust batch\n  applications vital for daily operations of enterprise systems. Version 5.1\n  delivers Micrometer metrics, virtual thread support (Java 21), and enhanced\n  chunk-oriented processing with retry, skip, and restart capabilities.\nimage: https://spring.io/img/projects/spring-batch.svg\nurl: https://spring.io/projects/spring-batch\ntype: opensource\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Batch Processing\n  - Data Processing\n  - Enterprise\n  - ETL\n  - Java\n  - Job Scheduling\n  - Spring Framework\napis:\n  - name: Spring Batch 5.1 Core API\n    description: >-\n      Core API for Spring Batch 5.1 providing batch processing capabilities\n      including job and step configuration, chunk-oriented processing, job\n      repository persistence,\
  \ and fault tolerance.\n    image: https://spring.io/img/projects/spring-batch.svg\n    humanURL: https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/\n    baseURL: https://github.com/spring-projects/spring-batch\n    tags:\n      - Batch Jobs\n      - Chunk Processing\n      - Job Repository\n      - Step Execution\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/\n      - type: API Documentation\n        url: https://docs.spring.io/spring-batch/docs/5.1.x/api/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-batch\n      - type: Getting Started Guide\n        url: https://spring.io/guides/gs/batch-processing/\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.batch/spring-batch-core/5.1.0\n      - type: Stack Overflow\n        url: https://stackoverflow.com/questions/tagged/spring-batch\n      - type: License\n  \
  \      url: https://github.com/spring-projects/spring-batch/blob/main/LICENSE.txt\n      - type: Issues\n        url: https://github.com/spring-projects/spring-batch/issues\n      - type: Sample Projects\n        url: https://github.com/spring-projects/spring-batch/tree/main/spring-batch-samples\n      - type: Release Notes\n        url: https://github.com/spring-projects/spring-batch/releases\n      - type: OpenAPI\n        url: openapi/spring-batch-51-openapi.yml\n      - type: Spectral Rules\n        url: rules/spring-batch-51-rules.yml\n  - name: Spring Batch 5.1 Actuator Monitoring\n    description: >-\n      Spring Boot Actuator-based monitoring endpoints for Spring Batch 5.1\n      applications providing job health, execution status, and Micrometer\n      metrics visibility.\n    humanURL: https://docs.spring.io/spring-boot/docs/3.2.x/actuator-api/htmlsingle/\n    baseURL: http://localhost:8080/actuator\n    tags:\n      - Actuator\n      - Health\n      - Metrics\n      - Monitoring\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/monitoring-and-metrics.html\nmaintainers:\n  - FN: Spring Team\n    email: spring-batch@vmware.com\n    X-twitter: springcentral\n    X-github: spring-projects\ninclude:\n  - name: Spring Batch Integration\n    url: https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/spring-batch-integration.html\n  - name: Spring Batch Test\n    url: https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/testing.html\ncommon:\n  - type: Blog\n    url: https://spring.io/blog/category/batch\n  - type: Support\n    url: https://spring.io/support\n  - type: Forum\n    url: https://stackoverflow.com/questions/tagged/spring-batch\n  - type: GitHub Issues\n    url: https://github.com/spring-projects/spring-batch/issues\n  - type: Maven Central\n    url: https://search.maven.org/search?q=g:org.springframework.batch\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-batch-51/refs/heads/main/apis.yml
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
