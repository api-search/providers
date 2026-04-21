---
api_count: 1
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
