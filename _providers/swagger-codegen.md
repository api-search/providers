---
api_count: 2
api_specs:
- filename: swagger-generator-openapi.yml
  format: yaml
  label: Swagger Generator API
  slug: swagger-generator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/openapi/swagger-generator-openapi.yml
apis:
- description: 'The Swagger Generator online API at generator3.swagger.io provides REST endpoints for generating client SDKs, server stubs, and documentation artifacts from OpenAPI V2 and V3 specifications. Supports '
  name: Swagger Generator API
  slug: swagger-generator-api
- description: The Swagger Codegen command-line interface for generating code artifacts locally. Available as a JAR file and Docker image. Supports the same generators as the online API with additional template cust
  name: Swagger Codegen CLI
  slug: swagger-codegen-cli
capabilities:
- description: Workflow capability for generating API client libraries, server stubs, and documentation from OpenAPI specifications using the Swagger Generator online service. Covers language discovery, option inspe
  name: Swagger Codegen Code Generation
  slug: code-generation
common:
- title: ''
  type: Portal
  url: https://swagger.io/tools/swagger-codegen/
- title: ''
  type: Documentation
  url: https://github.com/swagger-api/swagger-codegen/wiki
- title: ''
  type: Website
  url: https://swagger.io/
- title: ''
  type: GitHub Organization
  url: https://github.com/swagger-api
- title: ''
  type: GitHub Repository
  url: https://github.com/swagger-api/swagger-codegen
- title: ''
  type: Issues
  url: https://github.com/swagger-api/swagger-codegen/issues
- title: ''
  type: Releases
  url: https://github.com/swagger-api/swagger-codegen/releases
- title: ''
  type: License
  url: https://github.com/swagger-api/swagger-codegen/blob/master/LICENSE
- title: ''
  type: Docker
  url: https://hub.docker.com/r/swaggerapi/swagger-codegen-cli-v3
- title: ''
  type: Maven Plugin
  url: https://mvnrepository.com/artifact/io.swagger.codegen.v3/swagger-codegen-maven-plugin
- title: ''
  type: Gradle Plugin
  url: https://plugins.gradle.org/plugin/org.hidetake.swagger.generator
created: '2026-03-16'
description: Swagger Codegen is an open-source template-driven code generation tool that automatically generates client libraries, server stubs, and API documentation from OpenAPI Specification definitions. It supports 40+ client languages and 20+ server frameworks. Available as a CLI, Docker image, Maven/Gradle plugin, and online REST API at generator3.swagger.io.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Swagger Codegen Context
  property_count: 27
  slug: swagger-codegen-context
layout: provider
modified: '2026-05-02'
name: Swagger Codegen
rules:
- name: Swagger Codegen API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: swagger-codegen-rules
skills: []
slug: swagger-codegen
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: swagger-codegen\nname: Swagger Codegen\ndescription: >-\n  Swagger Codegen is an open-source template-driven code generation tool that\n  automatically generates client libraries, server stubs, and API documentation\n  from OpenAPI Specification definitions. It supports 40+ client languages and\n  20+ server frameworks. Available as a CLI, Docker image, Maven/Gradle plugin,\n  and online REST API at generator3.swagger.io.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Client Libraries\n  - Code Generation\n  - Open Source\n  - OpenAPI\n  - SDK\nurl: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: swagger-codegen:swagger-generator-api\n    name: Swagger Generator API\n    description: >-\n      The Swagger Generator online API at generator3.swagger.io provides REST\n      endpoints\
  \ for generating client SDKs, server stubs, and documentation\n      artifacts from OpenAPI V2 and V3 specifications. Supports 40+ client and\n      20+ server generator targets with configurable options.\n    humanURL: https://generator3.swagger.io/\n    baseURL: https://generator3.swagger.io\n    tags:\n      - Client Libraries\n      - Code Generation\n      - Generator\n      - OpenAPI\n      - SDK\n      - Server Stubs\n    properties:\n      - type: Documentation\n        url: https://github.com/swagger-api/swagger-codegen/wiki\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/openapi/swagger-generator-openapi.yml\n      - type: OpenAPI Source\n        url: https://generator3.swagger.io/openapi.json\n      - type: GitHub Repository\n        url: https://github.com/swagger-api/swagger-codegen\n\n  - aid: swagger-codegen:swagger-codegen-cli\n    name: Swagger Codegen CLI\n    description: >-\n      The Swagger Codegen\
  \ command-line interface for generating code artifacts\n      locally. Available as a JAR file and Docker image. Supports the same\n      generators as the online API with additional template customization.\n    humanURL: https://github.com/swagger-api/swagger-codegen#getting-started\n    tags:\n      - CLI\n      - Code Generation\n      - Command Line\n      - Docker\n    properties:\n      - type: Documentation\n        url: https://github.com/swagger-api/swagger-codegen/wiki\n      - type: Getting Started\n        url: https://github.com/swagger-api/swagger-codegen#getting-started\n      - type: Docker\n        url: https://hub.docker.com/r/swaggerapi/swagger-codegen-cli-v3\n      - type: Package\n        url: https://mvnrepository.com/artifact/io.swagger.codegen.v3/swagger-codegen-cli\n\ncommon:\n  - type: Portal\n    url: https://swagger.io/tools/swagger-codegen/\n  - type: Documentation\n    url: https://github.com/swagger-api/swagger-codegen/wiki\n  - type: Website\n    url: https://swagger.io/\n\
  \  - type: GitHub Organization\n    url: https://github.com/swagger-api\n  - type: GitHub Repository\n    url: https://github.com/swagger-api/swagger-codegen\n  - type: Issues\n    url: https://github.com/swagger-api/swagger-codegen/issues\n  - type: Releases\n    url: https://github.com/swagger-api/swagger-codegen/releases\n  - type: License\n    url: https://github.com/swagger-api/swagger-codegen/blob/master/LICENSE\n  - type: Docker\n    url: https://hub.docker.com/r/swaggerapi/swagger-codegen-cli-v3\n  - type: Maven Plugin\n    url: https://mvnrepository.com/artifact/io.swagger.codegen.v3/swagger-codegen-maven-plugin\n  - type: Gradle Plugin\n    url: https://plugins.gradle.org/plugin/org.hidetake.swagger.generator\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/apis.yml
tags:
- Client Libraries
- Code Generation
- Open Source
- OpenAPI
- SDK
url: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/apis.yml
use_cases: []
---
