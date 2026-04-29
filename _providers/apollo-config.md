---
api_count: 1
apis:
- description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versi
  name: Apollo Config
  slug: apollo-config
common:
- title: ''
  type: Documentation
  url: https://www.apolloconfig.com/#/en/
- title: ''
  type: GettingStarted
  url: https://www.apolloconfig.com/#/en/deployment/quick-start
- title: ''
  type: GitHubRepository
  url: https://github.com/apolloconfig/apollo
- title: ''
  type: GitHubOrganization
  url: https://github.com/apolloconfig
- title: ''
  type: ReleaseNotes
  url: https://github.com/apolloconfig/apollo/releases
- title: ''
  type: Support
  url: https://github.com/apolloconfig/apollo/issues
- title: Java SDK
  type: SDK
  url: https://github.com/apolloconfig/apollo-java
- title: .NET SDK
  type: SDK
  url: https://github.com/apolloconfig/apollo.net
- title: Go SDK
  type: SDK
  url: https://github.com/apolloconfig/agollo
- title: Java Demo
  type: CodeExamples
  url: https://github.com/apolloconfig/apollo-demo-java
- title: Use Cases
  type: CodeExamples
  url: https://github.com/apolloconfig/apollo-use-cases
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-ld/apollo-config-open-api-context.jsonld
created: '2026-03-26'
description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. Originally developed by Ctrip, now maintained by the apolloconfig community under Apache 2.0 license.
features:
- description: Centralize configuration for all microservices in one place with real-time push updates.
  name: Centralized Configuration Management
- description: Push configuration changes to all clients instantly without application restarts.
  name: Real-Time Configuration Updates
- description: Manage configurations across DEV, FAT, UAT, and PRO environments independently.
  name: Multi-Environment Support
- description: Track configuration changes with full version history and rollback capability.
  name: Versioning and History
- description: Gradually roll out configuration changes to a subset of instances.
  name: Gray Release Support
- description: Organize configurations into namespaces supporting properties, JSON, YAML, XML, and text formats.
  name: Namespace Management
- description: Manage configuration at the cluster level for multi-cluster deployments.
  name: Cluster Management
- description: REST API for programmatic configuration management and automation.
  name: Open API
- description: Kubernetes Operator for automated Apollo deployment in container environments.
  name: Kubernetes Operator
- description: Official Helm chart for Kubernetes deployments.
  name: Helm Chart Deployment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Java client library via apollo-java SDK.
  name: Java
- description: Official .NET client library via apollo.net SDK.
  name: .NET
- description: Go client library via agollo SDK.
  name: Go
- description: Apollo Operator and Helm chart for Kubernetes deployment.
  name: Kubernetes
- description: Spring Boot integration via Java SDK for auto-configuration refresh.
  name: Spring Boot
jsonld:
- class_count: 6
  name: Apollo Config Open Api Context
  property_count: 22
  slug: apollo-config-open-api-context
layout: provider
modified: '2026-04-19'
name: Apollo Config
skills: []
slug: apollo-config
solutions: []
source_filename: apis.yml
source_yaml: "aid: apollo-config\nname: Apollo Config\ndescription: >-\n  Apollo is a reliable, open-source configuration management system suitable for\n  microservice configuration management scenarios, providing centralized\n  configuration management, real-time updates, versioning, and multi-environment\n  support. Originally developed by Ctrip, now maintained by the apolloconfig\n  community under Apache 2.0 license.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache 2.0\n  - Configuration Management\n  - Ctrip\n  - Distributed Systems\n  - Java\n  - Microservices\n  - Open Source\n  - Real-Time Configuration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apollo-config:apollo-config\n    name: Apollo Config\n    description: >-\n      Apollo is a reliable, open-source configuration\
  \ management system suitable\n      for microservice configuration management scenarios, providing centralized\n      configuration management, real-time updates, versioning, and\n      multi-environment support. The Open API provides programmatic access to\n      app management, namespace management, configuration publishing, and release\n      management including gray releases.\n    humanURL: https://www.apolloconfig.com/\n    tags:\n      - Apache 2.0\n      - Configuration Management\n      - Distributed Systems\n      - Java\n      - Microservices\n      - Open Source\n      - Real-Time Configuration\n    baseURL: http://localhost:8070\n    properties:\n      - type: Documentation\n        url: https://www.apolloconfig.com/#/en/portal/apollo-open-api-platform\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/openapi/apollo-open-api.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-schema/apollo-open-api-app-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-schema/apollo-open-api-cluster-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-schema/apollo-open-api-namespace-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-schema/apollo-open-api-item-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-schema/apollo-open-api-release-schema.json\ncommon:\n  - type: Documentation\n    url: https://www.apolloconfig.com/#/en/\n  - type: GettingStarted\n    url: https://www.apolloconfig.com/#/en/deployment/quick-start\n  - type: GitHubRepository\n    url: https://github.com/apolloconfig/apollo\n  - type: GitHubOrganization\n\
  \    url: https://github.com/apolloconfig\n  - type: ReleaseNotes\n    url: https://github.com/apolloconfig/apollo/releases\n  - type: Support\n    url: https://github.com/apolloconfig/apollo/issues\n  - type: SDK\n    url: https://github.com/apolloconfig/apollo-java\n    title: Java SDK\n  - type: SDK\n    url: https://github.com/apolloconfig/apollo.net\n    title: .NET SDK\n  - type: SDK\n    url: https://github.com/apolloconfig/agollo\n    title: Go SDK\n  - type: CodeExamples\n    url: https://github.com/apolloconfig/apollo-demo-java\n    title: Java Demo\n  - type: CodeExamples\n    url: https://github.com/apolloconfig/apollo-use-cases\n    title: Use Cases\n  - type: JSONLD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/json-ld/apollo-config-open-api-context.jsonld\n  - type: Features\n    data:\n      - name: Centralized Configuration Management\n        description: Centralize configuration for all microservices in one place with\
  \ real-time push updates.\n      - name: Real-Time Configuration Updates\n        description: Push configuration changes to all clients instantly without application restarts.\n      - name: Multi-Environment Support\n        description: Manage configurations across DEV, FAT, UAT, and PRO environments independently.\n      - name: Versioning and History\n        description: Track configuration changes with full version history and rollback capability.\n      - name: Gray Release Support\n        description: Gradually roll out configuration changes to a subset of instances.\n      - name: Namespace Management\n        description: Organize configurations into namespaces supporting properties, JSON, YAML, XML, and text formats.\n      - name: Cluster Management\n        description: Manage configuration at the cluster level for multi-cluster deployments.\n      - name: Open API\n        description: REST API for programmatic configuration management and automation.\n      - name: Kubernetes\
  \ Operator\n        description: Kubernetes Operator for automated Apollo deployment in container environments.\n      - name: Helm Chart Deployment\n        description: Official Helm chart for Kubernetes deployments.\n  - type: UseCases\n    data:\n      - name: Microservice Configuration\n        description: Manage centralized configuration for distributed microservice architectures.\n      - name: Multi-Environment Configuration\n        description: Maintain separate configurations for development, testing, staging, and production.\n      - name: Dynamic Configuration Updates\n        description: Update application configuration at runtime without redeployment.\n      - name: Configuration Audit\n        description: Track who changed what configuration and when with full audit trail.\n      - name: Kubernetes Configuration Management\n        description: Manage configuration for containerized applications deployed on Kubernetes.\n  - type: Integrations\n    data:\n      - name:\
  \ Java\n        description: Official Java client library via apollo-java SDK.\n      - name: .NET\n        description: Official .NET client library via apollo.net SDK.\n      - name: Go\n        description: Go client library via agollo SDK.\n      - name: Kubernetes\n        description: Apollo Operator and Helm chart for Kubernetes deployment.\n      - name: Spring Boot\n        description: Spring Boot integration via Java SDK for auto-configuration refresh.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/apis.yml
tags:
- Apache 2.0
- Configuration Management
- Ctrip
- Distributed Systems
- Java
- Microservices
- Open Source
- Real-Time Configuration
url: https://raw.githubusercontent.com/api-evangelist/apollo-config/refs/heads/main/apis.yml
use_cases:
- description: Manage centralized configuration for distributed microservice architectures.
  name: Microservice Configuration
- description: Maintain separate configurations for development, testing, staging, and production.
  name: Multi-Environment Configuration
- description: Update application configuration at runtime without redeployment.
  name: Dynamic Configuration Updates
- description: Track who changed what configuration and when with full audit trail.
  name: Configuration Audit
- description: Manage configuration for containerized applications deployed on Kubernetes.
  name: Kubernetes Configuration Management
---
