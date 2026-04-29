---
api_count: 2
apis:
- description: Platform engineering APIs for managing cloud-native services on the Allianz Future Cloud Platform. Provides capabilities for service registration, deployment management, observability configuration, a
  name: Allianz Future Cloud Platform Services API
  slug: platform-services-api
- description: 'Insurance policy microservice running on the Allianz Future Cloud Platform. Provides REST APIs for policy lifecycle management including creation, endorsements, renewals, and cancellations built with '
  name: Allianz Insurance Policy Microservice API
  slug: policy-microservice-api
capabilities:
- description: Workflow capability for platform engineering and DevOps teams operating the Allianz Future Cloud Platform, combining service management, deployment automation, observability, and infrastructure provis
  name: Allianz Cloud Platform Operations
  slug: cloud-platform-operations
common:
- title: ''
  type: Website
  url: https://www.allianz.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/allianz
- title: ''
  type: Documentation
  url: https://architecture.cncf.io/architectures/allianz/
- title: ''
  type: SpectralRules
  url: rules/allianz-future-cloud-platform-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/allianz-future-cloud-platform-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/cloud-platform-operations.yaml
created: '2024-01-15'
description: The Allianz Future Cloud Platform is an internal developer platform powering cloud-native insurance microservices at Allianz. Built on Kubernetes and AWS, it provides platform engineering capabilities including service deployment, infrastructure management, observability, and GitOps automation across Allianz's global insurance operations.
features:
- description: Internal developer platform built on Kubernetes (EKS) providing standardized deployment, scaling, and orchestration for insurance microservices.
  name: Kubernetes Platform Engineering
- description: ArgoCD and Tekton-based CI/CD pipelines enabling GitOps workflows for continuous delivery of insurance applications.
  name: GitOps Deployment
- description: Terraform and Crossplane-based infrastructure management enabling repeatable, auditable cloud resource provisioning.
  name: Infrastructure as Code
- description: Prometheus, Grafana, and OpenTelemetry based observability platform providing metrics, tracing, and alerting for platform services.
  name: Observability Stack
- description: Namespace-level multi-tenancy supporting multiple insurance product teams on shared Kubernetes infrastructure.
  name: Multi-tenant Architecture
- description: AWS MSK (Managed Kafka) for high-throughput event streaming between insurance microservices and downstream consumers.
  name: Event Streaming
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary cloud provider with EKS, MSK, ElastiCache Redis, and storage services powering the platform.
  name: Amazon Web Services
- description: GitOps continuous delivery for declarative application deployment and state synchronization.
  name: ArgoCD
- description: Infrastructure as code for cloud resource provisioning and management integrated with Atlantis for PR automation.
  name: Terraform
- description: Multi-cloud resource management extending Kubernetes for cloud-agnostic infrastructure provisioning.
  name: Crossplane
- description: Distributed tracing and metrics collection across microservices for observability and performance analysis.
  name: OpenTelemetry
- description: AWS MSK for event-driven communication between insurance microservices and downstream systems.
  name: Apache Kafka
jsonld:
- class_count: 12
  name: Allianz Future Cloud Platform Context
  property_count: 35
  slug: allianz-future-cloud-platform-context
layout: provider
modified: '2026-04-19'
name: Allianz Future Cloud Platform
rules:
- name: Allianz Future Cloud Platform API Rules
  rule_count: 24
  severity_counts:
    error: 15
    hint: 0
    info: 3
    warn: 6
  slug: allianz-future-cloud-platform-spectral-rules
skills: []
slug: allianz-future-cloud-platform
solutions: []
source_yaml: "aid: allianz-future-cloud-platform\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/allianz-future-cloud-platform/refs/heads/main/apis.yml\nname: Allianz Future Cloud Platform\ntags:\n  - Cloud Platform\n  - Enterprise\n  - Financial Services\n  - Insurance\n  - Platform Engineering\n  - Kubernetes\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  The Allianz Future Cloud Platform is an internal developer platform powering\n  cloud-native insurance microservices at Allianz. Built on Kubernetes and AWS,\n  it provides platform engineering capabilities including service deployment,\n  infrastructure management, observability, and GitOps automation across\n  Allianz's global insurance operations.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: allianz-future-cloud-platform:platform-services-api\n    name: Allianz Future Cloud Platform Services API\n    tags:\n\
  \      - Cloud Platform\n      - Platform Engineering\n      - Microservices\n      - DevOps\n    properties:\n      - url: https://architecture.cncf.io/architectures/allianz/\n        type: Documentation\n      - url: https://www.cncf.io/case-studies/allianz/\n        type: Documentation\n      - url: openapi/allianz-future-cloud-platform-services.yaml\n        type: OpenAPI\n      - url: json-schema/platform-services-service-schema.json\n        type: JSONSchema\n      - url: json-schema/platform-services-deployment-schema.json\n        type: JSONSchema\n      - url: json-structure/platform-services-service-structure.json\n        type: JSONStructure\n      - url: json-ld/allianz-future-cloud-platform-context.jsonld\n        type: JSONLD\n      - url: examples/platform-services-service-example.json\n        type: Example\n      - url: examples/platform-services-deployment-example.json\n        type: Example\n    description: >-\n      Platform engineering APIs for managing cloud-native\
  \ services on the\n      Allianz Future Cloud Platform. Provides capabilities for service\n      registration, deployment management, observability configuration, and\n      infrastructure provisioning across Kubernetes clusters.\n    humanURL: https://architecture.cncf.io/architectures/allianz/\n    baseURL: https://platform.allianz.com/api/v1\n\n  - aid: allianz-future-cloud-platform:policy-microservice-api\n    name: Allianz Insurance Policy Microservice API\n    tags:\n      - Insurance\n      - Policy Management\n      - Microservices\n    properties:\n      - url: https://www.allianz.com/en/about-us/technology.html\n        type: Documentation\n      - url: openapi/allianz-future-cloud-platform-policy.yaml\n        type: OpenAPI\n      - url: json-schema/platform-policy-policy-schema.json\n        type: JSONSchema\n      - url: json-structure/platform-policy-policy-structure.json\n        type: JSONStructure\n      - url: examples/platform-policy-policy-example.json\n        type:\
  \ Example\n    description: >-\n      Insurance policy microservice running on the Allianz Future Cloud Platform.\n      Provides REST APIs for policy lifecycle management including creation,\n      endorsements, renewals, and cancellations built with Kotlin and Java on\n      Kubernetes.\n    humanURL: https://www.allianz.com/en/about-us/technology.html\n    baseURL: https://platform.allianz.com/insurance/policy/v1\n\ncommon:\n  - url: https://www.allianz.com/\n    type: Website\n  - url: https://github.com/allianz\n    type: GitHubOrganization\n  - url: https://architecture.cncf.io/architectures/allianz/\n    type: Documentation\n  - url: rules/allianz-future-cloud-platform-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/allianz-future-cloud-platform-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/cloud-platform-operations.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Kubernetes Platform Engineering\n        description:\
  \ >-\n          Internal developer platform built on Kubernetes (EKS) providing\n          standardized deployment, scaling, and orchestration for insurance\n          microservices.\n      - name: GitOps Deployment\n        description: >-\n          ArgoCD and Tekton-based CI/CD pipelines enabling GitOps workflows\n          for continuous delivery of insurance applications.\n      - name: Infrastructure as Code\n        description: >-\n          Terraform and Crossplane-based infrastructure management enabling\n          repeatable, auditable cloud resource provisioning.\n      - name: Observability Stack\n        description: >-\n          Prometheus, Grafana, and OpenTelemetry based observability platform\n          providing metrics, tracing, and alerting for platform services.\n      - name: Multi-tenant Architecture\n        description: >-\n          Namespace-level multi-tenancy supporting multiple insurance product\n          teams on shared Kubernetes infrastructure.\n   \
  \   - name: Event Streaming\n        description: >-\n          AWS MSK (Managed Kafka) for high-throughput event streaming between\n          insurance microservices and downstream consumers.\n  - type: UseCases\n    data:\n      - name: Insurance Microservice Deployment\n        description: >-\n          Deploy and manage Kotlin and Java insurance microservices on the\n          platform with standardized CI/CD pipelines and GitOps workflows.\n      - name: Platform Onboarding\n        description: >-\n          Onboard new insurance product teams onto the shared Kubernetes\n          platform with pre-configured namespaces and RBAC policies.\n      - name: Observability and Monitoring\n        description: >-\n          Configure monitoring dashboards and alerting for insurance services\n          using the platform's built-in Prometheus and Grafana stack.\n      - name: Infrastructure Provisioning\n        description: >-\n          Provision cloud infrastructure resources using Terraform\
  \ and\n          Crossplane through the platform's infrastructure API.\n  - type: Integrations\n    data:\n      - name: Amazon Web Services\n        description: >-\n          Primary cloud provider with EKS, MSK, ElastiCache Redis, and\n          storage services powering the platform.\n      - name: ArgoCD\n        description: >-\n          GitOps continuous delivery for declarative application deployment\n          and state synchronization.\n      - name: Terraform\n        description: >-\n          Infrastructure as code for cloud resource provisioning and\n          management integrated with Atlantis for PR automation.\n      - name: Crossplane\n        description: >-\n          Multi-cloud resource management extending Kubernetes for\n          cloud-agnostic infrastructure provisioning.\n      - name: OpenTelemetry\n        description: >-\n          Distributed tracing and metrics collection across microservices\n          for observability and performance analysis.\n   \
  \   - name: Apache Kafka\n        description: >-\n          AWS MSK for event-driven communication between insurance\n          microservices and downstream systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/allianz-future-cloud-platform/refs/heads/main/apis.yml
tags:
- Cloud Platform
- Enterprise
- Financial Services
- Insurance
- Platform Engineering
- Kubernetes
url: https://raw.githubusercontent.com/api-evangelist/allianz-future-cloud-platform/refs/heads/main/apis.yml
use_cases:
- description: Deploy and manage Kotlin and Java insurance microservices on the platform with standardized CI/CD pipelines and GitOps workflows.
  name: Insurance Microservice Deployment
- description: Onboard new insurance product teams onto the shared Kubernetes platform with pre-configured namespaces and RBAC policies.
  name: Platform Onboarding
- description: Configure monitoring dashboards and alerting for insurance services using the platform's built-in Prometheus and Grafana stack.
  name: Observability and Monitoring
- description: Provision cloud infrastructure resources using Terraform and Crossplane through the platform's infrastructure API.
  name: Infrastructure Provisioning
---
