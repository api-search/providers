---
api_count: 1
apis:
- description: Azure Container Apps is a serverless container service for running microservices and containerized applications with built-in autoscaling, traffic splitting, and Dapr integration. It enables developer
  name: Azure Container Apps
  slug: azure-container-apps
capabilities:
- description: Workflow capability for managing containerized applications, environments, and jobs in Azure Container Apps. Used by platform engineers and DevOps teams.
  name: Azure Container Apps Management
  slug: container-apps-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/container-apps/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/azure/container-apps/get-started
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoft/azure-container-apps
- title: ''
  type: GitHubOrganization
  url: https://github.com/Azure
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/blog/appsonazureblog/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/container-apps/
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SignUp
  url: https://azure.microsoft.com/en-us/free/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: FAQ
  url: https://learn.microsoft.com/en-us/azure/container-apps/faq
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/rules/azure-container-apps-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/vocabulary/azure-container-apps-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/capabilities/shared/azure-container-apps.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/capabilities/container-apps-management.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-ld/azure-container-apps-context.jsonld
created: '2026-03-26'
description: Azure Container Apps is a serverless container service for running microservices and containerized applications with built-in autoscaling, traffic splitting, and Dapr integration. It enables developers to deploy containers without managing complex infrastructure while supporting event-driven architectures and microservices patterns.
features:
- description: Run containers without managing servers or Kubernetes cluster infrastructure.
  name: Serverless Containers
- description: Automatically scale based on HTTP traffic, event messages, or custom KEDA scalers.
  name: Built-in Autoscaling
- description: Gradually shift traffic between container revisions for canary deployments and A/B testing.
  name: Traffic Splitting
- description: Built-in support for the Dapr distributed application runtime for service discovery and state management.
  name: Dapr Integration
- description: Shared networking and logging infrastructure for groups of container apps.
  name: Managed Environments
- description: Secure, ephemeral code-interpreter and custom container sessions with data-plane REST APIs.
  name: Dynamic Sessions
- description: Schedule and run containerized batch jobs on demand or on a schedule.
  name: Jobs Support
- description: Deploy AI/ML workloads on GPU-enabled container instances.
  name: GPU Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Share underlying Kubernetes infrastructure while abstracting cluster management complexity.
  name: Azure Kubernetes Service
- description: Pull container images directly from private ACR registries with managed identity.
  name: Azure Container Registry
- description: Trigger container app scaling based on Service Bus queue depth.
  name: Azure Service Bus
- description: Process streaming data from Event Hubs with auto-scaling.
  name: Azure Event Hubs
- description: Deploy container apps directly from GitHub Actions CI/CD workflows.
  name: GitHub Actions
- description: Built-in Dapr runtime support for distributed systems patterns.
  name: Dapr
- description: Native integration with Azure Monitor and Log Analytics for observability.
  name: Azure Monitor
jsonld:
- class_count: 13
  name: Azure Container Apps Context
  property_count: 28
  slug: azure-container-apps-context
layout: provider
modified: '2026-04-19'
name: Azure Container Apps
rules:
- name: Azure Container Apps API Rules
  rule_count: 17
  severity_counts:
    error: 7
    hint: 0
    info: 2
    warn: 8
  slug: azure-container-apps-spectral-rules
skills: []
slug: azure-container-apps
solutions: []
source_yaml: "aid: azure-container-apps\nname: Azure Container Apps\ndescription: >-\n  Azure Container Apps is a serverless container service for running\n  microservices and containerized applications with built-in autoscaling,\n  traffic splitting, and Dapr integration. It enables developers to deploy\n  containers without managing complex infrastructure while supporting\n  event-driven architectures and microservices patterns.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Azure\n  - Containers\n  - Dapr\n  - Kubernetes\n  - Microservices\n  - Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: azure-container-apps:azure-container-apps\n    name: Azure Container Apps\n    description: >-\n      Azure Container Apps is a serverless container service for running\n     \
  \ microservices and containerized applications with built-in autoscaling,\n      traffic splitting, and Dapr integration. It enables developers to deploy\n      containers without managing complex infrastructure while supporting\n      event-driven architectures and microservices patterns.\n    humanURL: https://azure.microsoft.com/en-us/products/container-apps\n    tags:\n      - Azure\n      - Containers\n      - Kubernetes\n      - Microservices\n      - Serverless\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/openapi/azure-container-apps-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-schema/azure-container-apps-container-app-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-schema/azure-container-apps-managed-environment-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-schema/azure-container-apps-job-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-schema/azure-container-apps-revision-schema.json\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/container-apps/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/container-apps/get-started\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/resource-manager/containerapps/operation-groups\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/container-apps/authentication\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/container-apps/\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n\
  \  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/container-apps/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/azure/container-apps/get-started\n  - type: GitHubRepository\n    url: https://github.com/microsoft/azure-container-apps\n  - type: GitHubOrganization\n    url: https://github.com/Azure\n  - type: Blog\n    url: https://techcommunity.microsoft.com/blog/appsonazureblog/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/container-apps/\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: SignUp\n    url: https://azure.microsoft.com/en-us/free/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: FAQ\n    url: https://learn.microsoft.com/en-us/azure/container-apps/faq\n  - type: SpectralRules\n\
  \    url: >-\n      https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/rules/azure-container-apps-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/vocabulary/azure-container-apps-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/capabilities/shared/azure-container-apps.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/capabilities/container-apps-management.yaml\n  - type: JSONLD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-ld/azure-container-apps-context.jsonld\n  - type: Features\n    data:\n      - name: Serverless Containers\n        description: Run containers without managing servers or Kubernetes\
  \ cluster infrastructure.\n      - name: Built-in Autoscaling\n        description: Automatically scale based on HTTP traffic, event messages, or custom KEDA scalers.\n      - name: Traffic Splitting\n        description: Gradually shift traffic between container revisions for canary deployments and A/B testing.\n      - name: Dapr Integration\n        description: Built-in support for the Dapr distributed application runtime for service discovery and state management.\n      - name: Managed Environments\n        description: Shared networking and logging infrastructure for groups of container apps.\n      - name: Dynamic Sessions\n        description: Secure, ephemeral code-interpreter and custom container sessions with data-plane REST APIs.\n      - name: Jobs Support\n        description: Schedule and run containerized batch jobs on demand or on a schedule.\n      - name: GPU Support\n        description: Deploy AI/ML workloads on GPU-enabled container instances.\n  - type: UseCases\n\
  \    data:\n      - name: Microservices Architecture\n        description: Deploy and scale individual microservices independently with built-in service discovery.\n      - name: API Backend Deployment\n        description: Host REST APIs with automatic HTTPS, custom domains, and traffic management.\n      - name: Event-Driven Processing\n        description: Process messages from Service Bus, Event Hubs, and storage queues with KEDA-based scaling.\n      - name: AI and ML Workloads\n        description: Run AI inference workloads on GPU-enabled container instances with dynamic sessions.\n      - name: Background Jobs\n        description: Run scheduled and on-demand batch jobs without maintaining dedicated infrastructure.\n      - name: Dapr Microservices\n        description: Build microservices with Dapr for pub/sub messaging, service invocation, and state management.\n  - type: Integrations\n    data:\n      - name: Azure Kubernetes Service\n        description: Share underlying Kubernetes\
  \ infrastructure while abstracting cluster management complexity.\n      - name: Azure Container Registry\n        description: Pull container images directly from private ACR registries with managed identity.\n      - name: Azure Service Bus\n        description: Trigger container app scaling based on Service Bus queue depth.\n      - name: Azure Event Hubs\n        description: Process streaming data from Event Hubs with auto-scaling.\n      - name: GitHub Actions\n        description: Deploy container apps directly from GitHub Actions CI/CD workflows.\n      - name: Dapr\n        description: Built-in Dapr runtime support for distributed systems patterns.\n      - name: Azure Monitor\n        description: Native integration with Azure Monitor and Log Analytics for observability.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/apis.yml
tags:
- Azure
- Containers
- Dapr
- Kubernetes
- Microservices
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/apis.yml
use_cases:
- description: Deploy and scale individual microservices independently with built-in service discovery.
  name: Microservices Architecture
- description: Host REST APIs with automatic HTTPS, custom domains, and traffic management.
  name: API Backend Deployment
- description: Process messages from Service Bus, Event Hubs, and storage queues with KEDA-based scaling.
  name: Event-Driven Processing
- description: Run AI inference workloads on GPU-enabled container instances with dynamic sessions.
  name: AI and ML Workloads
- description: Run scheduled and on-demand batch jobs without maintaining dedicated infrastructure.
  name: Background Jobs
- description: Build microservices with Dapr for pub/sub messaging, service invocation, and state management.
  name: Dapr Microservices
---
