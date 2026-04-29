---
api_count: 1
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
apis:
- description: API for creating and managing App Mesh service meshes, virtual services, virtual nodes, virtual routers, routes, and gateway routes. The service is based on Envoy proxy and provides service discovery,
  name: AWS App Mesh API
  slug: aws-app-mesh-api
capabilities:
- description: 'Workflow capability for platform engineers to manage App Mesh service meshes, virtual nodes, virtual services, and traffic routing. Note: AWS App Mesh is deprecated; Amazon ECS Service Connect is the '
  name: AWS App Mesh Service Mesh Workflow
  slug: service-mesh-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/app-mesh/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/app-mesh/
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/app-mesh/latest/userguide/getting_started.html
- title: ''
  type: Pricing
  url: https://aws.amazon.com/app-mesh/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/app-mesh/faqs/
- title: ''
  type: Authentication
  url: https://docs.aws.amazon.com/app-mesh/latest/userguide/security-iam.html
- title: ''
  type: Console
  url: https://console.aws.amazon.com/appmesh/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: SpectralRules
  url: rules/aws-app-mesh-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-app-mesh-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/service-mesh-workflow.yaml
created: '2026-03-16'
description: 'AWS App Mesh is a service mesh based on the Envoy proxy that provides application-level networking to make it easy for services to communicate with each other across multiple types of compute infrastructure including Amazon ECS, EKS, EC2, and Fargate. App Mesh standardizes service communication, giving end-to-end visibility and helping ensure high availability. Note: AWS App Mesh is deprecated; Amazon ECS Service Connect is the recommended replacement for new workloads.'
features:
- description: Create and manage service meshes spanning Amazon ECS, EKS, EC2, and Fargate compute environments.
  name: Service Mesh Management
- description: Define virtual nodes representing actual services with listener ports, health checks, and service discovery backends.
  name: Virtual Node Configuration
- description: Configure virtual routers and routes for weighted routing, retry policies, and timeout configurations.
  name: Traffic Routing
- description: Automatically injects and manages Envoy sidecar proxies for transparent service-to-service communication.
  name: Envoy Proxy Integration
- description: Export metrics, logs, and traces from Envoy proxies to AWS CloudWatch, X-Ray, and third-party tools.
  name: Observability
- description: Enable mutual TLS encryption between services within the mesh for zero-trust networking.
  name: mTLS Encryption
- description: Configure ingress traffic from outside the mesh to virtual services using gateway routes.
  name: Virtual Gateways
- description: Share service meshes across AWS accounts using AWS Resource Access Manager.
  name: Multi-Account Mesh Sharing
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Automatically inject Envoy sidecars into ECS task definitions.
  name: Amazon ECS
- description: Integrate with Kubernetes pod networking using the App Mesh controller for Kubernetes.
  name: Amazon EKS
- description: Export distributed traces from Envoy proxies to X-Ray for performance analysis.
  name: AWS X-Ray
- description: Send Envoy proxy metrics to CloudWatch for monitoring and alerting.
  name: Amazon CloudWatch
- description: Use Cloud Map for service discovery within the mesh.
  name: AWS Cloud Map
- description: Run Envoy sidecar proxies alongside EC2-hosted services.
  name: Amazon EC2
jsonld:
- class_count: 2
  name: Aws App Mesh Aws Context
  property_count: 6
  slug: aws-app-mesh-aws-context
- class_count: 14
  name: Aws App Mesh Create Context
  property_count: 17
  slug: aws-app-mesh-create-context
- class_count: 14
  name: Aws App Mesh Describe Context
  property_count: 7
  slug: aws-app-mesh-describe-context
- class_count: 1
  name: Aws App Mesh Egress Context
  property_count: 1
  slug: aws-app-mesh-egress-context
- class_count: 9
  name: Aws App Mesh Gateway Context
  property_count: 21
  slug: aws-app-mesh-gateway-context
- class_count: 14
  name: Aws App Mesh Grpc Context
  property_count: 25
  slug: aws-app-mesh-grpc-context
- class_count: 16
  name: Aws App Mesh Http Context
  property_count: 26
  slug: aws-app-mesh-http-context
- class_count: 16
  name: Aws App Mesh List Context
  property_count: 9
  slug: aws-app-mesh-list-context
- class_count: 9
  name: Aws App Mesh Listener Context
  property_count: 22
  slug: aws-app-mesh-listener-context
- class_count: 2
  name: Aws App Mesh Logging Context
  property_count: 3
  slug: aws-app-mesh-logging-context
- class_count: 6
  name: Aws App Mesh Mesh Context
  property_count: 12
  slug: aws-app-mesh-mesh-context
- class_count: 1
  name: Aws App Mesh Port Context
  property_count: 2
  slug: aws-app-mesh-port-context
- class_count: 5
  name: Aws App Mesh Route Context
  property_count: 16
  slug: aws-app-mesh-route-context
- class_count: 3
  name: Aws App Mesh Tag Context
  property_count: 3
  slug: aws-app-mesh-tag-context
- class_count: 4
  name: Aws App Mesh Tcp Context
  property_count: 6
  slug: aws-app-mesh-tcp-context
- class_count: 5
  name: Aws App Mesh Tls Context
  property_count: 8
  slug: aws-app-mesh-tls-context
- class_count: 2
  name: Aws App Mesh Untag Context
  property_count: 1
  slug: aws-app-mesh-untag-context
- class_count: 14
  name: Aws App Mesh Update Context
  property_count: 9
  slug: aws-app-mesh-update-context
- class_count: 53
  name: Aws App Mesh Virtual Context
  property_count: 57
  slug: aws-app-mesh-virtual-context
- class_count: 1
  name: Aws App Mesh Weighted Context
  property_count: 3
  slug: aws-app-mesh-weighted-context
layout: provider
modified: '2026-04-19'
name: AWS App Mesh
rules:
- name: AWS App Mesh API Rules
  rule_count: 19
  severity_counts:
    error: 11
    hint: 0
    info: 0
    warn: 8
  slug: aws-app-mesh-spectral-rules
skills: []
slug: aws-app-mesh
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aws-app-mesh\nname: AWS App Mesh\ndescription: >-\n  AWS App Mesh is a service mesh based on the Envoy proxy that provides\n  application-level networking to make it easy for services to communicate with\n  each other across multiple types of compute infrastructure including Amazon\n  ECS, EKS, EC2, and Fargate. App Mesh standardizes service communication,\n  giving end-to-end visibility and helping ensure high availability. Note: AWS\n  App Mesh is deprecated; Amazon ECS Service Connect is the recommended\n  replacement for new workloads.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Deprecated\n  - Envoy\n  - Microservices\n  - Networking\n  - Service Mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-app-mesh:aws-app-mesh-api\n    name: AWS App Mesh\
  \ API\n    description: >-\n      API for creating and managing App Mesh service meshes, virtual services,\n      virtual nodes, virtual routers, routes, and gateway routes. The service\n      is based on Envoy proxy and provides service discovery, traffic routing,\n      and observability for microservices.\n    humanURL: https://aws.amazon.com/app-mesh/\n    baseURL: https://appmesh.amazonaws.com\n    tags:\n      - Deprecated\n      - Envoy\n      - Microservices\n      - Networking\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/app-mesh/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/aws-app-mesh-openapi.yaml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/app-mesh/latest/APIReference/Welcome.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/app-mesh/latest/userguide/security-iam.html\n      - type: Quickstart\n        url: https://docs.aws.amazon.com/app-mesh/latest/userguide/getting-started-ecs.html\n\
  \      - type: Documentation\n        url: https://aws.amazon.com/blogs/containers/migrating-from-aws-app-mesh-to-amazon-ecs-service-connect/\n        title: Migration Guide to ECS Service Connect\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/app-mesh/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/app-mesh/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/app-mesh/latest/userguide/getting_started.html\n  - type: Pricing\n    url: https://aws.amazon.com/app-mesh/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/app-mesh/faqs/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/app-mesh/latest/userguide/security-iam.html\n  - type: Console\n    url: https://console.aws.amazon.com/appmesh/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: StatusPage\n    url:\
  \ https://health.aws.amazon.com/health/status\n  - type: SpectralRules\n    url: rules/aws-app-mesh-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/aws-app-mesh-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/service-mesh-workflow.yaml\n  - type: Features\n    data:\n      - name: Service Mesh Management\n        description: Create and manage service meshes spanning Amazon ECS, EKS, EC2, and Fargate compute environments.\n      - name: Virtual Node Configuration\n        description: Define virtual nodes representing actual services with listener ports, health checks, and service discovery backends.\n      - name: Traffic Routing\n        description: Configure virtual routers and routes for weighted routing, retry policies, and timeout configurations.\n      - name: Envoy Proxy Integration\n        description: Automatically injects and manages Envoy sidecar proxies for transparent service-to-service communication.\n      - name: Observability\n    \
  \    description: Export metrics, logs, and traces from Envoy proxies to AWS CloudWatch, X-Ray, and third-party tools.\n      - name: mTLS Encryption\n        description: Enable mutual TLS encryption between services within the mesh for zero-trust networking.\n      - name: Virtual Gateways\n        description: Configure ingress traffic from outside the mesh to virtual services using gateway routes.\n      - name: Multi-Account Mesh Sharing\n        description: Share service meshes across AWS accounts using AWS Resource Access Manager.\n  - type: UseCases\n    data:\n      - name: Microservices Communication\n        description: Standardize and control service-to-service networking for containerized microservices applications.\n      - name: Traffic Management\n        description: Implement canary deployments, A/B testing, and weighted routing without application code changes.\n      - name: Observability and Debugging\n        description: Capture end-to-end metrics and traces to\
  \ identify performance bottlenecks and service failures.\n      - name: Zero-Trust Networking\n        description: Enforce mTLS encryption between services for internal network security compliance.\n  - type: Integrations\n    data:\n      - name: Amazon ECS\n        description: Automatically inject Envoy sidecars into ECS task definitions.\n      - name: Amazon EKS\n        description: Integrate with Kubernetes pod networking using the App Mesh controller for Kubernetes.\n      - name: AWS X-Ray\n        description: Export distributed traces from Envoy proxies to X-Ray for performance analysis.\n      - name: Amazon CloudWatch\n        description: Send Envoy proxy metrics to CloudWatch for monitoring and alerting.\n      - name: AWS Cloud Map\n        description: Use Cloud Map for service discovery within the mesh.\n      - name: Amazon EC2\n        description: Run Envoy sidecar proxies alongside EC2-hosted services.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/apis.yml
tags:
- AWS
- Deprecated
- Envoy
- Microservices
- Networking
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/apis.yml
use_cases:
- description: Standardize and control service-to-service networking for containerized microservices applications.
  name: Microservices Communication
- description: Implement canary deployments, A/B testing, and weighted routing without application code changes.
  name: Traffic Management
- description: Capture end-to-end metrics and traces to identify performance bottlenecks and service failures.
  name: Observability and Debugging
- description: Enforce mTLS encryption between services for internal network security compliance.
  name: Zero-Trust Networking
---
