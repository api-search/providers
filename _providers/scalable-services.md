---
api_count: 8
api_specs:
- filename: swagger.json
  format: json
  label: Kubernetes API
  slug: kubernetes
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json
apis:
- description: The Kubernetes API enables programmatic management of containerized workloads, including deployments, services, pods, config maps, and horizontal pod autoscalers. Core to running scalable microservice
  name: Kubernetes API
  slug: kubernetes
- description: Envoy Proxy's administration API for inspecting and modifying Envoy runtime configuration, stats, clusters, and listeners. Envoy is the foundational data plane for many service mesh and API gateway de
  name: Envoy Admin API
  slug: envoy-admin
- description: Istio's configuration APIs define traffic management, security policy, and observability for microservice meshes. Expressed as Kubernetes CRDs (VirtualService, DestinationRule, Gateway, etc.).
  name: Istio API
  slug: istio
- description: Amazon Web Services Lambda API for creating, managing, invoking, and monitoring serverless functions. Core to event-driven, auto-scaling architectures.
  name: AWS Lambda API
  slug: aws-lambda
- description: Kong Gateway's RESTful Admin API for managing services, routes, plugins, consumers, upstreams, and certificates. Kong is a widely deployed open-source API gateway for scalable API management.
  name: Kong Admin API
  slug: kong-admin
- description: Prometheus exposes an HTTP API for querying metrics, metadata, and alerting rules. Essential for observability and autoscaling decisions in scalable service architectures.
  name: Prometheus HTTP API
  slug: prometheus
- description: Knative provides Kubernetes-based platform APIs for deploying and scaling event-driven serverless workloads. Includes Knative Serving (scale-to-zero) and Knative Eventing (event sourcing and routing).
  name: Knative API
  slug: knative
- description: gRPC server reflection provides information about publicly-accessible gRPC services on a server, enabling discovery and dynamic invocation. gRPC is widely used for high-performance inter-service commu
  name: gRPC Reflection API
  slug: grpc
common:
- title: ''
  type: Documentation
  url: https://kubernetes.io/docs/concepts/architecture/
- title: ''
  type: Guide
  url: https://microservices.io/patterns/index.html
- title: ''
  type: Guide
  url: https://www.cncf.io/projects/
- title: ''
  type: Guide
  url: https://istio.io/latest/about/service-mesh/
- title: ''
  type: Guide
  url: https://www.envoyproxy.io/learn/service-mesh
- title: ''
  type: JSONSchema
  url: https://github.com/api-evangelist/scalable-services/blob/main/json-schema/scalable-services-service-schema.json
- title: ''
  type: JSONStructure
  url: https://github.com/api-evangelist/scalable-services/blob/main/json-structure/scalable-services-service-structure.json
- title: ''
  type: JSONLDContext
  url: https://github.com/api-evangelist/scalable-services/blob/main/json-ld/scalable-services-context.jsonld
- title: ''
  type: Vocabulary
  url: https://github.com/api-evangelist/scalable-services/blob/main/vocabulary/scalable-services-vocabulary.yml
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kubernetes-hpa-example.json
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kong-plugin-example.json
created: '2025-01-15'
description: A curated topic collection covering APIs, patterns, tools, and best practices for designing and operating scalable services. This includes cloud-native microservices, API gateways, load balancers, container orchestration, serverless platforms, service meshes, and the architectural patterns that enable services to scale horizontally and vertically. Relevant to platform engineers, cloud architects, and backend developers building high-traffic, distributed systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Scalable Services Context
  property_count: 0
  slug: scalable-services-context
layout: provider
modified: '2026-05-02'
name: Scalable Services
skills: []
slug: scalable-services
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scalable-services\nname: Scalable Services\ndescription: >-\n  A curated topic collection covering APIs, patterns, tools, and best practices\n  for designing and operating scalable services. This includes cloud-native\n  microservices, API gateways, load balancers, container orchestration,\n  serverless platforms, service meshes, and the architectural patterns that\n  enable services to scale horizontally and vertically. Relevant to platform\n  engineers, cloud architects, and backend developers building high-traffic,\n  distributed systems.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Cloud Native\n  - Containers\n  - Distributed Systems\n  - High Availability\n  - Kubernetes\n  - Load Balancing\n  - Microservices\n  - Scalable Architecture\n  - Serverless\n  - Service Mesh\ntype: Index\ncreated: '2025-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scalable-services:kubernetes\n\
  \    name: Kubernetes API\n    description: >-\n      The Kubernetes API enables programmatic management of containerized\n      workloads, including deployments, services, pods, config maps, and\n      horizontal pod autoscalers. Core to running scalable microservices\n      infrastructure.\n    tags:\n      - Containers\n      - Kubernetes\n      - Orchestration\n      - Scalable Architecture\n    humanURL: https://kubernetes.io/docs/reference/kubernetes-api/\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/reference/kubernetes-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json\n      - type: GettingStarted\n        url: https://kubernetes.io/docs/home/\n      - type: GitHub\n        url: https://github.com/kubernetes/kubernetes\n  - aid: scalable-services:envoy-admin\n    name: Envoy Admin API\n    description: >-\n      Envoy Proxy's administration API for inspecting\
  \ and modifying Envoy\n      runtime configuration, stats, clusters, and listeners. Envoy is the\n      foundational data plane for many service mesh and API gateway deployments.\n    tags:\n      - API Gateway\n      - Load Balancing\n      - Proxy\n      - Service Mesh\n    humanURL: https://www.envoyproxy.io/docs/envoy/latest/operations/admin\n    properties:\n      - type: Documentation\n        url: https://www.envoyproxy.io/docs/envoy/latest/operations/admin\n      - type: GitHub\n        url: https://github.com/envoyproxy/envoy\n  - aid: scalable-services:istio\n    name: Istio API\n    description: >-\n      Istio's configuration APIs define traffic management, security policy,\n      and observability for microservice meshes. Expressed as Kubernetes CRDs\n      (VirtualService, DestinationRule, Gateway, etc.).\n    tags:\n      - Kubernetes\n      - Microservices\n      - Observability\n      - Security\n      - Service Mesh\n    humanURL: https://istio.io/latest/docs/reference/config/\n\
  \    properties:\n      - type: Documentation\n        url: https://istio.io/latest/docs/reference/config/\n      - type: GitHub\n        url: https://github.com/istio/istio\n  - aid: scalable-services:aws-lambda\n    name: AWS Lambda API\n    description: >-\n      Amazon Web Services Lambda API for creating, managing, invoking, and\n      monitoring serverless functions. Core to event-driven, auto-scaling\n      architectures.\n    tags:\n      - AWS\n      - Cloud Native\n      - Event Driven\n      - Scalable Architecture\n      - Serverless\n    humanURL: https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html\n  - aid: scalable-services:kong-admin\n    name: Kong Admin API\n    description: >-\n      Kong Gateway's RESTful Admin API for managing services, routes, plugins,\n      consumers, upstreams, and certificates. Kong is a widely deployed\n\
  \      open-source API gateway for scalable API management.\n    tags:\n      - API Gateway\n      - Load Balancing\n      - Microservices\n      - Plugins\n    humanURL: https://docs.konghq.com/gateway/latest/admin-api/\n    properties:\n      - type: Documentation\n        url: https://docs.konghq.com/gateway/latest/admin-api/\n      - type: GitHub\n        url: https://github.com/Kong/kong\n  - aid: scalable-services:prometheus\n    name: Prometheus HTTP API\n    description: >-\n      Prometheus exposes an HTTP API for querying metrics, metadata, and\n      alerting rules. Essential for observability and autoscaling decisions\n      in scalable service architectures.\n    tags:\n      - Alerts\n      - Metrics\n      - Monitoring\n      - Observability\n    humanURL: https://prometheus.io/docs/prometheus/latest/querying/api/\n    properties:\n      - type: Documentation\n        url: https://prometheus.io/docs/prometheus/latest/querying/api/\n      - type: GitHub\n        url: https://github.com/prometheus/prometheus\n\
  \  - aid: scalable-services:knative\n    name: Knative API\n    description: >-\n      Knative provides Kubernetes-based platform APIs for deploying and scaling\n      event-driven serverless workloads. Includes Knative Serving (scale-to-zero)\n      and Knative Eventing (event sourcing and routing).\n    tags:\n      - Cloud Native\n      - Event Driven\n      - Kubernetes\n      - Scalable Architecture\n      - Serverless\n    humanURL: https://knative.dev/docs/\n    properties:\n      - type: Documentation\n        url: https://knative.dev/docs/\n      - type: GitHub\n        url: https://github.com/knative/serving\n  - aid: scalable-services:grpc\n    name: gRPC Reflection API\n    description: >-\n      gRPC server reflection provides information about publicly-accessible\n      gRPC services on a server, enabling discovery and dynamic invocation.\n      gRPC is widely used for high-performance inter-service communication\n      in scalable microservice architectures.\n    tags:\n\
  \      - High Performance\n      - Microservices\n      - Protocol Buffers\n      - RPC\n    humanURL: https://grpc.io/docs/\n    properties:\n      - type: Documentation\n        url: https://grpc.io/docs/\n      - type: GitHub\n        url: https://github.com/grpc/grpc\ncommon:\n  - type: Documentation\n    url: https://kubernetes.io/docs/concepts/architecture/\n    name: Kubernetes Architecture Concepts\n  - type: Guide\n    url: https://microservices.io/patterns/index.html\n    name: Microservices Patterns\n  - type: Guide\n    url: https://www.cncf.io/projects/\n    name: CNCF Landscape Projects\n  - type: Guide\n    url: https://istio.io/latest/about/service-mesh/\n    name: What is a Service Mesh?\n  - type: Guide\n    url: https://www.envoyproxy.io/learn/service-mesh\n    name: Envoy Service Mesh Guide\n  - type: JSONSchema\n    url: https://github.com/api-evangelist/scalable-services/blob/main/json-schema/scalable-services-service-schema.json\n    name: Scalable Service JSON Schema\n\
  \  - type: JSONStructure\n    url: https://github.com/api-evangelist/scalable-services/blob/main/json-structure/scalable-services-service-structure.json\n    name: Scalable Service JSON Structure\n  - type: JSONLDContext\n    url: https://github.com/api-evangelist/scalable-services/blob/main/json-ld/scalable-services-context.jsonld\n    name: Scalable Services JSON-LD Context\n  - type: Vocabulary\n    url: https://github.com/api-evangelist/scalable-services/blob/main/vocabulary/scalable-services-vocabulary.yml\n    name: Scalable Services Vocabulary\n  - type: Examples\n    url: https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kubernetes-hpa-example.json\n    name: Kubernetes HPA Example\n  - type: Examples\n    url: https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kong-plugin-example.json\n    name: Kong Rate Limiting Plugin Example\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url:\
  \ https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalable-services/refs/heads/main/apis.yml
tags:
- API Gateway
- Cloud Native
- Containers
- Distributed Systems
- High Availability
- Kubernetes
- Load Balancing
- Microservices
- Scalable Architecture
- Serverless
- Service Mesh
url: ''
use_cases: []
---
