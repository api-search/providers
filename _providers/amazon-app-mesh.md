---
api_count: 1
api_specs:
- filename: amazon-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-app-mesh/refs/heads/main/openapi/amazon-app-mesh-openapi.yaml
apis:
- description: 'The AWS App Mesh API provides programmatic access to configure and manage service mesh resources for microservices. It enables developers to create and manage meshes, virtual services, virtual nodes, '
  name: AWS App Mesh API
  slug: ''
capabilities:
- description: Workflow for managing Amazon App Mesh API resources.
  name: App Mesh Management
  slug: app-mesh-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/app-mesh/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/app-mesh/
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
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/appmesh/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-app-mesh-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/app-mesh-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-app-mesh-vocabulary.yaml
created: '2024-01-15'
description: AWS App Mesh is a service mesh that provides application-level networking to make it easy for your services to communicate with each other across multiple types of compute infrastructure.
features:
- description: Create and manage service meshes that define the logical boundary for network traffic between microservices.
  name: Service Mesh Management
- description: Define virtual services that act as logical routers for microservice traffic, abstracting the underlying routing logic.
  name: Virtual Service Configuration
- description: Configure virtual routers and routes to implement traffic management policies including weighted routing and retry policies.
  name: Traffic Routing Control
- description: Manage virtual nodes representing microservice task groups with service discovery and health check configurations.
  name: Virtual Node Management
- description: Configure access logs and tracing for end-to-end visibility of traffic flowing through the service mesh.
  name: Observability Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy App Mesh sidecar proxies alongside ECS tasks for automatic traffic interception and routing.
  name: AWS ECS
- description: Run App Mesh with Kubernetes via the App Mesh Controller for Kubernetes for native K8s integration.
  name: AWS EKS
- description: Use X-Ray for distributed tracing of requests flowing through the App Mesh service mesh.
  name: AWS X-Ray
- description: Integrate App Mesh with Cloud Map for service discovery across ECS, EKS, and EC2 compute.
  name: AWS Cloud Map
jsonld:
- class_count: 0
  name: Amazon App Mesh Context
  property_count: 1
  slug: amazon-app-mesh-context
layout: provider
modified: '2026-04-19'
name: Amazon App Mesh
rules:
- name: Amazon App Mesh API Rules
  rule_count: 3
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 0
  slug: amazon-app-mesh-spectral-rules
skills: []
slug: amazon-app-mesh
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-app-mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-app-mesh/refs/heads/main/apis.yml\nname: Amazon App Mesh\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  AWS App Mesh is a service mesh that provides application-level networking to\n  make it easy for your services to communicate with each other across multiple\n  types of compute infrastructure.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: AWS App Mesh API\n  description: >-\n    The AWS App Mesh API provides programmatic access to configure and manage\n    service mesh resources for microservices. It enables developers to create\n    and manage meshes, virtual services, virtual nodes, virtual routers, and\n    routes, providing fine-grained control over service-to-service communication,\n    traffic routing, and observability.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanURL: https://aws.amazon.com/app-mesh/\n  baseURL: https://appmesh.amazonaws.com\n  tags:\n  - AWS\n  - Microservices\n  - Networking\n  - Service Mesh\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/app-mesh/\n  - type: OpenAPI\n    url: openapi/amazon-app-mesh-openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/app-mesh/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/app-mesh/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/app-mesh/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-app-mesh-accesslog-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-mesh-accountid-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-mesh-arn-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-mesh-awscloudmapinstanceattribute-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-mesh-awscloudmapinstanceattributekey-schema.json\n  - type: JSONStructure\n\
  \    url: json-structure/amazon-app-mesh-accesslog-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-app-mesh-accountid-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-app-mesh-arn-structure.json\n  - type: JSONLD\n    url: json-ld/amazon-app-mesh-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/app-mesh/\n- type: Documentation\n  url: https://docs.aws.amazon.com/app-mesh/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/appmesh/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n\
  - type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-app-mesh-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/app-mesh-management.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-app-mesh-vocabulary.yaml\n- type: Features\n  data:\n  - name: Service Mesh Management\n    description: Create and manage service meshes that define the logical boundary for network traffic between microservices.\n  - name: Virtual Service Configuration\n    description: Define virtual services that act as logical routers for microservice traffic, abstracting the underlying routing logic.\n  - name: Traffic Routing Control\n    description: Configure virtual routers and routes to implement traffic management policies including weighted routing and retry policies.\n  - name: Virtual Node Management\n    description: Manage virtual nodes representing microservice task groups with service discovery and health check configurations.\n  - name:\
  \ Observability Integration\n    description: Configure access logs and tracing for end-to-end visibility of traffic flowing through the service mesh.\n- type: UseCases\n  data:\n  - name: Microservices Traffic Management\n    description: Control traffic routing between microservices with weighted routing, canary deployments, and circuit breaking.\n  - name: Service Discovery Integration\n    description: Integrate App Mesh with AWS Cloud Map for automatic service discovery across compute types.\n  - name: Multi-Cluster Networking\n    description: Connect services running on ECS, EKS, and EC2 instances within a unified service mesh for consistent networking policies.\n- type: Integrations\n  data:\n  - name: AWS ECS\n    description: Deploy App Mesh sidecar proxies alongside ECS tasks for automatic traffic interception and routing.\n  - name: AWS EKS\n    description: Run App Mesh with Kubernetes via the App Mesh Controller for Kubernetes for native K8s integration.\n  - name: AWS X-Ray\n\
  \    description: Use X-Ray for distributed tracing of requests flowing through the App Mesh service mesh.\n  - name: AWS Cloud Map\n    description: Integrate App Mesh with Cloud Map for service discovery across ECS, EKS, and EC2 compute.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Microservices\n- Networking\n- Service Mesh\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-mesh/refs/heads/main/apis.yml
tags:
- AWS
- Microservices
- Networking
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/amazon-app-mesh/refs/heads/main/apis.yml
use_cases:
- description: Control traffic routing between microservices with weighted routing, canary deployments, and circuit breaking.
  name: Microservices Traffic Management
- description: Integrate App Mesh with AWS Cloud Map for automatic service discovery across compute types.
  name: Service Discovery Integration
- description: Connect services running on ECS, EKS, and EC2 instances within a unified service mesh for consistent networking policies.
  name: Multi-Cluster Networking
---
