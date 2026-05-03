---
api_count: 2
api_specs:
- filename: service-fabric-cluster-openapi.yml
  format: yaml
  label: Service Fabric Cluster Management API
  slug: service-fabric-cluster-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/openapi/service-fabric-cluster-openapi.yml
apis:
- description: The Service Fabric Cluster Management REST API enables management of Service Fabric clusters, nodes, applications, services, partitions, replicas, and health states. Provides operations for applicatio
  name: Service Fabric Cluster Management API
  slug: service-fabric-cluster-api
- description: Service Fabric SDK provides client libraries for .NET, Java, and Go for building Service Fabric services and interacting with the cluster. The SDK includes Reliable Collections, Reliable Actors, and t
  name: Service Fabric SDK
  slug: service-fabric-sdk
capabilities:
- description: Unified capability for managing Azure Service Fabric clusters, including application lifecycle, node management, service monitoring, and cluster health. Enables platform engineers and SREs to deploy a
  name: Service Fabric Cluster Management
  slug: cluster-management
common:
- title: ''
  type: Website
  url: https://docs.microsoft.com/en-us/azure/service-fabric/
- title: ''
  type: GitHub
  url: https://github.com/microsoft/service-fabric
- title: ''
  type: Documentation
  url: https://docs.microsoft.com/en-us/azure/service-fabric/
- title: ''
  type: GettingStarted
  url: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started
- title: ''
  type: Reference
  url: https://docs.microsoft.com/en-us/rest/api/servicefabric/
- title: ''
  type: ChangeLog
  url: https://github.com/microsoft/service-fabric/releases
- title: ''
  type: License
  url: https://github.com/microsoft/service-fabric/blob/master/LICENSE
- title: ''
  type: JSONSchema
  url: json-schema/service-fabric-application-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/service-fabric-application-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/service-fabric-context.jsonld
- title: ''
  type: Examples
  url: examples/service-fabric-create-application-example.json
- title: ''
  type: Examples
  url: examples/service-fabric-get-cluster-health-example.json
- title: ''
  type: Vocabulary
  url: vocabulary/service-fabric-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/service-fabric-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/cluster-management.yaml
created: '2026-05-02'
description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of services at scale including Azure SQL Database, Azure Cosmos DB, Skype for Business, and Cortana. Service Fabric provides a programming model for building stateful and stateless microservices, reliable collections, and actor-based services. The Service Fabric REST API enables cluster management, application lifecycle, and service configuration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Service Fabric Context
  property_count: 3
  slug: service-fabric-context
layout: provider
modified: '2026-05-02'
name: Service Fabric
rules:
- name: Service Fabric API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 3
  slug: service-fabric-rules
skills: []
slug: service-fabric
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: service-fabric\nname: Service Fabric\ndescription: >-\n  Azure Service Fabric is an open-source distributed systems platform for\n  packaging, deploying, and managing scalable and reliable microservices and\n  containers. Service Fabric powers many Microsoft Azure core services, and\n  thousands of services at scale including Azure SQL Database, Azure Cosmos DB,\n  Skype for Business, and Cortana. Service Fabric provides a programming model\n  for building stateful and stateless microservices, reliable collections, and\n  actor-based services. The Service Fabric REST API enables cluster management,\n  application lifecycle, and service configuration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Distributed Systems\n  - Microservices\n  - Containers\n  - Cloud Native\n  - Kubernetes\n  - Azure\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/apis.yml\n\
  created: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: service-fabric:service-fabric-cluster-api\n    name: Service Fabric Cluster Management API\n    description: >-\n      The Service Fabric Cluster Management REST API enables management of\n      Service Fabric clusters, nodes, applications, services, partitions,\n      replicas, and health states. Provides operations for application lifecycle\n      management (provision, create, upgrade, delete) and cluster health monitoring.\n    humanURL: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-rest-based-model\n    baseURL: http://{cluster-endpoint}:19080\n    tags:\n      - Distributed Systems\n      - Cluster Management\n      - Application Lifecycle\n      - Health Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-rest-based-model\n      - type: Reference\n        url: https://docs.microsoft.com/en-us/rest/api/servicefabric/\n\
  \      - type: GitHub\n        url: https://github.com/microsoft/service-fabric\n      - type: OpenAPI\n        url: openapi/service-fabric-cluster-openapi.yml\n      - type: JSONSchema\n        url: json-schema/service-fabric-application-schema.json\n      - type: JSONStructure\n        url: json-structure/service-fabric-application-structure.json\n      - type: SpectralRules\n        url: rules/service-fabric-rules.yml\n      - type: Capabilities\n        url: capabilities/cluster-management.yaml\n\n  - aid: service-fabric:service-fabric-sdk\n    name: Service Fabric SDK\n    description: >-\n      Service Fabric SDK provides client libraries for .NET, Java, and Go\n      for building Service Fabric services and interacting with the cluster.\n      The SDK includes Reliable Collections, Reliable Actors, and the Reliable\n      Services programming model.\n    humanURL: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started\n    tags:\n      - SDK\n      - .NET\n\
  \      - Java\n      - Microservices\n      - Reliable Collections\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started\n      - type: NuGet\n        url: https://www.nuget.org/packages/Microsoft.ServiceFabric/\n      - type: Maven\n        url: https://mvnrepository.com/artifact/com.microsoft.servicefabric/sf-actors\n\ncommon:\n  - type: Website\n    url: https://docs.microsoft.com/en-us/azure/service-fabric/\n  - type: GitHub\n    url: https://github.com/microsoft/service-fabric\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/azure/service-fabric/\n  - type: GettingStarted\n    url: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started\n  - type: Reference\n    url: https://docs.microsoft.com/en-us/rest/api/servicefabric/\n  - type: ChangeLog\n    url: https://github.com/microsoft/service-fabric/releases\n  - type: License\n    url: https://github.com/microsoft/service-fabric/blob/master/LICENSE\n\
  \  - type: JSONSchema\n    url: json-schema/service-fabric-application-schema.json\n  - type: JSONStructure\n    url: json-structure/service-fabric-application-structure.json\n  - type: JSONLDContext\n    url: json-ld/service-fabric-context.jsonld\n  - type: Examples\n    url: examples/service-fabric-create-application-example.json\n  - type: Examples\n    url: examples/service-fabric-get-cluster-health-example.json\n  - type: Vocabulary\n    url: vocabulary/service-fabric-vocabulary.yml\n  - type: SpectralRules\n    url: rules/service-fabric-rules.yml\n  - type: Capabilities\n    url: capabilities/cluster-management.yaml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/apis.yml
tags:
- Distributed Systems
- Microservices
- Containers
- Cloud Native
- Kubernetes
- Azure
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/apis.yml
use_cases: []
---
