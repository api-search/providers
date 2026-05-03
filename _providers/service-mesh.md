---
api_count: 5
api_specs:
- filename: virtual_service.proto
  format: yaml
  label: Istio API
  slug: istio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/istio/api/master/networking/v1alpha3/virtual_service.proto
- filename: swagger.json
  format: json
  label: Consul Connect / Service Mesh API
  slug: consul-api
  spec_type: OpenAPI
  url: https://github.com/hashicorp/consul/blob/main/api/openapi-spec/swagger.json
apis:
- description: Istio is the most widely deployed service mesh. Istio's control plane exposes APIs for traffic management (VirtualService, DestinationRule, Gateway), security (PeerAuthentication, AuthorizationPolicy)
  name: Istio API
  slug: istio-api
- description: Linkerd is a lightweight CNCF-graduated service mesh focused on simplicity and security. Linkerd exposes an admin API for metrics, health checks, and edge proxy management. It uses the SMI (Service Me
  name: Linkerd Admin API
  slug: linkerd-api
- description: HashiCorp Consul provides service discovery and a service mesh (Consul Connect) with mutual TLS, intentions-based access control, and multi-datacenter support. Consul exposes a REST API for service ca
  name: Consul Connect / Service Mesh API
  slug: consul-api
- description: AWS App Mesh is a managed service mesh that provides application-level networking for microservices on AWS. It integrates with ECS, EKS, EC2, and Fargate. The App Mesh API manages virtual services, vi
  name: AWS App Mesh API
  slug: aws-app-mesh-api
- description: SMI is a standard interface for service meshes on Kubernetes. It defines common APIs for traffic policy, traffic telemetry, and traffic management so that applications work with any SMI-compatible ser
  name: Service Mesh Interface (SMI)
  slug: service-mesh-interface
common:
- title: ''
  type: Website
  url: https://github.com/api-evangelist/service-mesh
- title: ''
  type: Documentation
  url: https://istio.io/latest/docs/
- title: ''
  type: Guide
  url: https://linkerd.io/2.14/getting-started/
- title: ''
  type: Standard
  url: https://smi-spec.io/
- title: ''
  type: CNCF
  url: https://landscape.cncf.io/guide#orchestration-management--service-mesh
- title: ''
  type: JSONSchema
  url: json-schema/service-mesh-configuration-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/service-mesh-traffic-policy-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/service-mesh-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/service-mesh-vocabulary.yml
created: '2026-03-27'
description: Service mesh is a dedicated infrastructure layer for handling service-to-service communication in microservices architectures. It provides traffic management, mutual TLS security, observability, policy enforcement, and resilience features without requiring changes to application code. Key implementations include Istio, Linkerd, Consul Connect, and AWS App Mesh. This index tracks service mesh specifications, implementations, and related APIs across the ecosystem.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 38
  name: Service Mesh Context
  property_count: 2
  slug: service-mesh-context
layout: provider
modified: '2026-05-02'
name: Service Mesh
skills: []
slug: service-mesh
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: service-mesh\nname: Service Mesh\ndescription: >-\n  Service mesh is a dedicated infrastructure layer for handling service-to-service\n  communication in microservices architectures. It provides traffic management,\n  mutual TLS security, observability, policy enforcement, and resilience features\n  without requiring changes to application code. Key implementations include Istio,\n  Linkerd, Consul Connect, and AWS App Mesh. This index tracks service mesh\n  specifications, implementations, and related APIs across the ecosystem.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Service Mesh\n  - Microservices\n  - Cloud Native\n  - Kubernetes\n  - Networking\n  - Observability\n  - Zero Trust\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/service-mesh/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: service-mesh:istio-api\n    name:\
  \ Istio API\n    description: >-\n      Istio is the most widely deployed service mesh. Istio's control plane\n      exposes APIs for traffic management (VirtualService, DestinationRule,\n      Gateway), security (PeerAuthentication, AuthorizationPolicy), and\n      telemetry configuration. The Istio API uses Kubernetes Custom Resource\n      Definitions (CRDs) as its primary interface.\n    humanURL: https://istio.io/latest/docs/reference/config/\n    tags:\n      - Service Mesh\n      - Istio\n      - Traffic Management\n      - Kubernetes\n      - mTLS\n    properties:\n      - type: Documentation\n        url: https://istio.io/latest/docs/reference/config/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/istio/api/master/networking/v1alpha3/virtual_service.proto\n\n  - aid: service-mesh:linkerd-api\n    name: Linkerd Admin API\n    description: >-\n      Linkerd is a lightweight CNCF-graduated service mesh focused on simplicity\n      and security. Linkerd exposes\
  \ an admin API for metrics, health checks, and\n      edge proxy management. It uses the SMI (Service Mesh Interface) API\n      specification for traffic policy.\n    humanURL: https://linkerd.io/2.14/reference/\n    tags:\n      - Service Mesh\n      - Linkerd\n      - CNCF\n      - Observability\n      - mTLS\n    properties:\n      - type: Documentation\n        url: https://linkerd.io/2.14/reference/\n      - type: GitHubOrganization\n        url: https://github.com/linkerd\n\n  - aid: service-mesh:consul-api\n    name: Consul Connect / Service Mesh API\n    description: >-\n      HashiCorp Consul provides service discovery and a service mesh (Consul\n      Connect) with mutual TLS, intentions-based access control, and\n      multi-datacenter support. Consul exposes a REST API for service catalog,\n      health checks, key-value store, and mesh configuration.\n    humanURL: https://developer.hashicorp.com/consul/api-docs\n    tags:\n      - Service Mesh\n      - Consul\n      - HashiCorp\n\
  \      - Service Discovery\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/consul/api-docs\n      - type: OpenAPI\n        url: https://github.com/hashicorp/consul/blob/main/api/openapi-spec/swagger.json\n\n  - aid: service-mesh:aws-app-mesh-api\n    name: AWS App Mesh API\n    description: >-\n      AWS App Mesh is a managed service mesh that provides application-level\n      networking for microservices on AWS. It integrates with ECS, EKS, EC2,\n      and Fargate. The App Mesh API manages virtual services, virtual routers,\n      virtual nodes, and routes.\n    humanURL: https://docs.aws.amazon.com/app-mesh/latest/APIReference/\n    tags:\n      - Service Mesh\n      - AWS\n      - Cloud\n      - EKS\n      - ECS\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/app-mesh/latest/APIReference/\n\n  - aid: service-mesh:service-mesh-interface\n    name: Service Mesh Interface (SMI)\n   \
  \ description: >-\n      SMI is a standard interface for service meshes on Kubernetes. It defines\n      common APIs for traffic policy, traffic telemetry, and traffic management\n      so that applications work with any SMI-compatible service mesh. SMI is\n      hosted by the CNCF.\n    humanURL: https://smi-spec.io/\n    tags:\n      - Service Mesh\n      - SMI\n      - Standard\n      - Kubernetes\n      - CNCF\n    properties:\n      - type: Documentation\n        url: https://smi-spec.io/\n      - type: GitHubOrganization\n        url: https://github.com/servicemeshinterface\n\ncommon:\n  - type: Website\n    url: https://github.com/api-evangelist/service-mesh\n  - type: Documentation\n    url: https://istio.io/latest/docs/\n  - type: Guide\n    url: https://linkerd.io/2.14/getting-started/\n  - type: Standard\n    url: https://smi-spec.io/\n  - type: CNCF\n    url: https://landscape.cncf.io/guide#orchestration-management--service-mesh\n  - type: JSONSchema\n    url: json-schema/service-mesh-configuration-schema.json\n\
  \  - type: JSONStructure\n    url: json-structure/service-mesh-traffic-policy-structure.json\n  - type: JSONLDContext\n    url: json-ld/service-mesh-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/service-mesh-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/service-mesh/refs/heads/main/apis.yml
tags:
- Service Mesh
- Microservices
- Cloud Native
- Kubernetes
- Networking
- Observability
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/service-mesh/refs/heads/main/apis.yml
use_cases: []
---
