---
api_count: 1
api_specs:
- filename: spring-cloud-config-server-api.yml
  format: yaml
  label: Spring Cloud Config Server API
  slug: spring-cloud-config-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-config/refs/heads/main/openapi/spring-cloud-config-server-api.yml
apis:
- description: HTTP resource-based API for external configuration management. Serves property sources organized by application name, profile, and label (git branch/tag). Supports JSON, YAML, and Java properties form
  name: Spring Cloud Config Server API
  slug: spring-cloud-config-server
capabilities:
- description: Unified capability for centralized configuration management across distributed microservices. Enables retrieving externalized configuration, managing encryption, and triggering runtime refresh for Dev
  name: Spring Cloud Config Configuration Management
  slug: configuration-management
common:
- title: ''
  type: Website
  url: https://spring.io/projects/spring-cloud-config
- title: ''
  type: Documentation
  url: https://docs.spring.io/spring-cloud-config/reference/
- title: ''
  type: Getting Started
  url: https://spring.io/guides/gs/centralized-configuration/
- title: ''
  type: GitHub
  url: https://github.com/spring-cloud/spring-cloud-config
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-cloud
- title: ''
  type: Issues
  url: https://github.com/spring-cloud/spring-cloud-config/issues
- title: ''
  type: Releases
  url: https://github.com/spring-cloud/spring-cloud-config/releases
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-cloud-config
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-config-server
- title: ''
  type: Vocabulary
  url: vocabulary/spring-cloud-config-vocabulary.yml
created: '2026-03-26'
description: Spring Cloud Config provides server-side and client-side support for externalized configuration in a distributed system. It offers a central place to manage external properties for applications across all environments, backed by Git, SVN, or filesystem repositories with support for encryption, decryption, and runtime refresh.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Spring Cloud Config Context
  property_count: 9
  slug: spring-cloud-config-context
layout: provider
modified: '2026-05-02'
name: Spring Cloud Config
rules:
- name: Spring Cloud Config API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: spring-cloud-config-rules
skills: []
slug: spring-cloud-config
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-cloud-config\nname: Spring Cloud Config\ndescription: >-\n  Spring Cloud Config provides server-side and client-side support for externalized\n  configuration in a distributed system. It offers a central place to manage external\n  properties for applications across all environments, backed by Git, SVN, or filesystem\n  repositories with support for encryption, decryption, and runtime refresh.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://spring.io/projects/spring-cloud-config\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Configuration Management\n  - Distributed Systems\n  - Externalized Configuration\n  - Git\n  - Java\n  - Microservices\n  - Spring\n  - Spring Cloud\napis:\n  - aid: spring-cloud-config:spring-cloud-config-server\n    name: Spring Cloud Config Server API\n    description: >-\n      HTTP resource-based API for external configuration management. Serves property\n\
  \      sources organized by application name, profile, and label (git branch/tag).\n      Supports JSON, YAML, and Java properties formats plus encryption/decryption\n      and webhook-triggered refresh notifications.\n    humanURL: https://spring.io/projects/spring-cloud-config\n    baseURL: http://localhost:8888\n    tags:\n      - Configuration\n      - Configuration Management\n      - Distributed Systems\n      - Encryption\n      - Externalized Configuration\n      - Git\n      - Microservices\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-cloud-config/reference/server/environment-repository.html\n      - type: OpenAPI\n        url: openapi/spring-cloud-config-server-api.yml\n      - type: JSONSchema\n        url: json-schema/spring-cloud-config-environment-schema.json\n      - type: JSONSchema\n        url: json-schema/spring-cloud-config-server-configuration-schema.json\n      - type: JSONStructure\n        url: json-structure/spring-cloud-config-environment-structure.json\n\
  \      - type: JSONLDContext\n        url: json-ld/spring-cloud-config-context.jsonld\n      - type: SpectralRules\n        url: rules/spring-cloud-config-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/configuration-management.yaml\ncommon:\n  - type: Website\n    url: https://spring.io/projects/spring-cloud-config\n  - type: Documentation\n    url: https://docs.spring.io/spring-cloud-config/reference/\n  - type: Getting Started\n    url: https://spring.io/guides/gs/centralized-configuration/\n  - type: GitHub\n    url: https://github.com/spring-cloud/spring-cloud-config\n  - type: GitHub Organization\n    url: https://github.com/spring-cloud\n  - type: Issues\n    url: https://github.com/spring-cloud/spring-cloud-config/issues\n  - type: Releases\n    url: https://github.com/spring-cloud/spring-cloud-config/releases\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-cloud-config\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-config-server\n\
  \  - type: Vocabulary\n    url: vocabulary/spring-cloud-config-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-cloud-config/refs/heads/main/apis.yml
tags:
- Configuration Management
- Distributed Systems
- Externalized Configuration
- Git
- Java
- Microservices
- Spring
- Spring Cloud
url: https://spring.io/projects/spring-cloud-config
use_cases: []
---
