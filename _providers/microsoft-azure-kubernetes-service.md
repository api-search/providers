---
api_count: 8
api_specs:
- filename: azure-kubernetes-service-openapi.yml
  format: yaml
  label: Azure Kubernetes Service REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-kubernetes-service/refs/heads/main/openapi/azure-kubernetes-service-openapi.yml
- filename: azure-kubernetes-service-openapi.yml
  format: yaml
  label: Azure Kubernetes Service Managed Clusters API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-kubernetes-service/refs/heads/main/openapi/azure-kubernetes-service-openapi.yml
- filename: azure-kubernetes-service-openapi.yml
  format: yaml
  label: Azure Kubernetes Service Agent Pools API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-kubernetes-service/refs/heads/main/openapi/azure-kubernetes-service-openapi.yml
apis:
- description: REST API for managing Azure Kubernetes Service clusters.
  name: Azure Kubernetes Service REST API
  slug: ''
- description: REST API for creating, updating, deleting, and managing AKS managed clusters including cluster configuration, upgrades, credentials, and run commands.
  name: Azure Kubernetes Service Managed Clusters API
  slug: ''
- description: REST API for creating, updating, deleting, and managing agent pools (node pools) within AKS managed clusters, including scaling and configuration.
  name: Azure Kubernetes Service Agent Pools API
  slug: ''
- description: REST API for managing planned maintenance configurations, used to configure when updates can be deployed to an AKS managed cluster.
  name: Azure Kubernetes Service Maintenance Configurations API
  slug: ''
- description: REST API for creating, updating, deleting, and managing node pool snapshots in AKS, including listing snapshots by resource group.
  name: Azure Kubernetes Service Snapshots API
  slug: ''
- description: REST API for managing private endpoint connections for AKS clusters, enabling secure private network access to the cluster API server.
  name: Azure Kubernetes Service Private Endpoint Connections API
  slug: ''
- description: REST API for managing trusted access role bindings that give Azure services secure access to AKS API server using system-assigned managed identities.
  name: Azure Kubernetes Service Trusted Access Role Bindings API
  slug: ''
- description: Kubernetes API accessible via kubectl for cluster operations.
  name: Azure Kubernetes Service kubectl API
  slug: ''
capabilities:
- description: Workflow for managing AKS clusters and agent pools including lifecycle operations, upgrades, scaling, and credentials. Used by DevOps engineers and platform administrators.
  name: Azure Kubernetes Service Cluster Management
  slug: cluster-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal
- title: ''
  type: CLI
  url: https://learn.microsoft.com/en-us/cli/azure/aks
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/topics/kubernetes/
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/AKS
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/azure-aks
- title: ''
  type: Security
  url: https://learn.microsoft.com/en-us/azure/aks/concepts-security
- title: ''
  type: Compliance
  url: https://learn.microsoft.com/en-us/azure/aks/concepts-security#azure-policy
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/aks/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/
- title: ''
  type: SignUp
  url: https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account
- title: ''
  type: Login
  url: https://portal.azure.com/
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: ChangeLog
  url: https://github.com/Azure/AKS/blob/master/CHANGELOG.md
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/azure/aks/release-tracker
- title: ''
  type: FAQ
  url: https://learn.microsoft.com/en-us/azure/aks/faq
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/modules/intro-to-azure-kubernetes-service/
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/MicrosoftAzure
- title: ''
  type: SpectralRules
  url: rules/azure-kubernetes-service-spectral-rules.yml
- title: AKS REST API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/aks-rest.yaml
- title: Cluster Management Workflow
  type: NaftikoCapability
  url: capabilities/cluster-management.yaml
created: '2024-01-15'
description: Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance.
features:
- description: Create, update, delete, start, and stop AKS managed clusters with full lifecycle management.
  name: Managed Cluster Lifecycle
- description: Create and manage node pools with configurable VM sizes, scaling, and upgrade policies.
  name: Agent Pool Management
- description: Upgrade Kubernetes versions and node images with controlled rollout and upgrade profiles.
  name: Cluster Upgrades
- description: Retrieve admin, user, and monitoring credentials for cluster access and authentication.
  name: Credential Management
- description: Deploy private AKS clusters with private endpoint connections for secure API server access.
  name: Private Clusters
- description: Configure planned maintenance windows to control when updates are applied to clusters.
  name: Maintenance Windows
- description: Create and manage snapshots of node pools for backup and recovery scenarios.
  name: Node Pool Snapshots
- description: Grant Azure services secure access to AKS API server using managed identities and role bindings.
  name: Trusted Access
- description: Execute commands on cluster nodes remotely through the AKS API without direct SSH access.
  name: Run Commands
- description: Automatically scale node pools based on workload demands with configurable auto-scaler profiles.
  name: Auto-Scaling
image: https://azure.microsoft.com/images/aks-icon.png
integrations:
- description: Pull container images from Azure Container Registry with managed identity authentication.
  name: Azure Container Registry
- description: Monitor cluster health, performance, and logs with Azure Monitor and Container Insights.
  name: Azure Monitor
- description: Enforce organizational standards and compliance with Azure Policy for Kubernetes.
  name: Azure Policy
- description: Integrate with Azure AD for cluster authentication and role-based access control.
  name: Azure Active Directory
- description: Automate deployments to AKS using Azure Pipelines with native Kubernetes tasks.
  name: Azure DevOps
jsonld:
- class_count: 0
  name: Azure Kubernetes Service Context
  property_count: 0
  slug: azure-kubernetes-service-context
layout: provider
modified: '2026-04-28'
name: Azure Kubernetes Service
rules:
- name: Azure Kubernetes Service API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: azure-kubernetes-service-spectral-rules
skills: []
slug: microsoft-azure-kubernetes-service
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Kubernetes Service\ndescription: Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance.\nimage: https://azure.microsoft.com/images/aks-icon.png\nurl: https://azure.microsoft.com/en-us/services/kubernetes-service/\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Azure\n  - Cloud\n  - Containers\n  - DevOps\n  - Kubernetes\n  - Orchestration\napis:\n  - name: Azure Kubernetes Service REST API\n    description: >-\n      REST API for managing Azure Kubernetes Service clusters.\n    image: https://azure.microsoft.com/images/aks-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/aks/\n    baseURL: https://management.azure.com\n    tags:\n      - Containers\n      - Kubernetes\n      - Management\n    properties:\n      - type: Documentation\n\
  \        url: https://learn.microsoft.com/en-us/azure/aks/\n      - type: OpenAPI\n        url: openapi/azure-kubernetes-service-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-kubernetes-service-cluster-schema.json\n      - type: JSONLD\n        url: json-ld/azure-kubernetes-service-context.jsonld\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/concepts-identity\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/\n      - type: RateLimits\n        url: https://learn.microsoft.com/en-us/azure/aks/quotas-skus-regions\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal\n      - type: ChangeLog\n        url: https://github.com/Azure/AKS/blob/master/CHANGELOG.md\n      - type: ReleaseNotes\n        url: https://learn.microsoft.com/en-us/azure/aks/release-tracker\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/python/api/overview/azure/mgmt-containerservice-readme\n\
  \        title: Python SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/javascript/api/overview/azure/container-service\n        title: JavaScript SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/dotnet/api/overview/azure/resourcemanager.containerservice-readme\n        title: .NET SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/java/api/overview/azure/resourcemanager-containerservice-readme\n        title: Java SDK\n      - type: SDK\n        url: https://pkg.go.dev/github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/containerservice/armcontainerservice/v6\n        title: Go SDK\n  - name: Azure Kubernetes Service Managed Clusters API\n    description: REST API for creating, updating, deleting, and managing AKS managed clusters including cluster configuration, upgrades, credentials, and run commands.\n    image: https://azure.microsoft.com/images/aks-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters\n\
  \    baseURL: https://management.azure.com\n    tags:\n      - Clusters\n      - Kubernetes\n      - Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/aks/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/aks/managed-clusters\n      - type: OpenAPI\n        url: openapi/azure-kubernetes-service-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-kubernetes-service-cluster-schema.json\n      - type: JSONLD\n        url: json-ld/azure-kubernetes-service-context.jsonld\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/concepts-identity\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-cli\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/\n  - name: Azure Kubernetes Service Agent Pools API\n    description: REST API\
  \ for creating, updating, deleting, and managing agent pools (node pools) within AKS managed clusters, including scaling and configuration.\n    image: https://azure.microsoft.com/images/aks-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/aks/agent-pools\n    baseURL: https://management.azure.com\n    tags:\n      - Agent Pools\n      - Kubernetes\n      - Node Pools\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/aks/create-node-pools\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/aks/agent-pools\n      - type: OpenAPI\n        url: openapi/azure-kubernetes-service-openapi.yml\n      - type: JSONSchema\n        url: json-schema/azure-kubernetes-service-cluster-schema.json\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/concepts-identity\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/aks/create-node-pools\n\
  \  - name: Azure Kubernetes Service Maintenance Configurations API\n    description: REST API for managing planned maintenance configurations, used to configure when updates can be deployed to an AKS managed cluster.\n    image: https://azure.microsoft.com/images/aks-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations\n    baseURL: https://management.azure.com\n    tags:\n      - Configuration\n      - Kubernetes\n      - Maintenance\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/aks/planned-maintenance\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/aks/maintenance-configurations\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/concepts-identity\n  - name: Azure Kubernetes Service Snapshots API\n    description: REST API for creating, updating, deleting, and managing node pool snapshots in AKS, including listing\
  \ snapshots by resource group.\n    image: https://azure.microsoft.com/images/aks-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/aks/snapshots\n    baseURL: https://management.azure.com\n    tags:\n      - Backup\n      - Kubernetes\n      - Snapshots\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/aks/node-pool-snapshot\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/aks/snapshots\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/concepts-identity\n  - name: Azure Kubernetes Service Private Endpoint Connections API\n    description: REST API for managing private endpoint connections for AKS clusters, enabling secure private network access to the cluster API server.\n    image: https://azure.microsoft.com/images/aks-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections\n    baseURL: https://management.azure.com\n\
  \    tags:\n      - Kubernetes\n      - Networking\n      - Private Endpoints\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/aks/private-clusters\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/aks/private-endpoint-connections\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/concepts-identity\n  - name: Azure Kubernetes Service Trusted Access Role Bindings API\n    description: REST API for managing trusted access role bindings that give Azure services secure access to AKS API server using system-assigned managed identities.\n    image: https://azure.microsoft.com/images/aks-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings\n    baseURL: https://management.azure.com\n    tags:\n      - Kubernetes\n      - Security\n      - Trusted Access\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/aks/trusted-access-feature\n\
  \      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/aks/trusted-access-role-bindings\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/concepts-identity\n  - name: Azure Kubernetes Service kubectl API\n    description: >-\n      Kubernetes API accessible via kubectl for cluster operations.\n    humanURL: https://kubernetes.io/docs/reference/\n    baseURL: https://{cluster-name}.{region}.azmk8s.io\n    tags:\n      - Cluster Management\n      - Kubectl\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/aks/kubernetes-walkthrough\n      - type: APIReference\n        url: https://kubernetes.io/docs/reference/kubernetes-api/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/aks/control-kubeconfig-access\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/aks/tutorial-kubernetes-deploy-cluster\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-portal\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/cli/azure/aks\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/topics/kubernetes/\n  - type: GitHubRepository\n    url: https://github.com/Azure/AKS\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/azure-aks\n  - type: Security\n    url: https://learn.microsoft.com/en-us/azure/aks/concepts-security\n  - type: Compliance\n    url: https://learn.microsoft.com/en-us/azure/aks/concepts-security#azure-policy\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/aks/\n  - type: Pricing\n    url:\
  \ https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/\n  - type: SignUp\n    url: https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account\n  - type: Login\n    url: https://portal.azure.com/\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: ChangeLog\n    url: https://github.com/Azure/AKS/blob/master/CHANGELOG.md\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/azure/aks/release-tracker\n  - type: FAQ\n    url: https://learn.microsoft.com/en-us/azure/aks/faq\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/modules/intro-to-azure-kubernetes-service/\n  - type: YouTube\n    url: https://www.youtube.com/c/MicrosoftAzure\n  - type: SpectralRules\n    url: rules/azure-kubernetes-service-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/aks-rest.yaml\n   \
  \ title: AKS REST API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/cluster-management.yaml\n    title: Cluster Management Workflow\n  - type: Features\n    data:\n      - name: Managed Cluster Lifecycle\n        description: Create, update, delete, start, and stop AKS managed clusters with full lifecycle management.\n      - name: Agent Pool Management\n        description: Create and manage node pools with configurable VM sizes, scaling, and upgrade policies.\n      - name: Cluster Upgrades\n        description: Upgrade Kubernetes versions and node images with controlled rollout and upgrade profiles.\n      - name: Credential Management\n        description: Retrieve admin, user, and monitoring credentials for cluster access and authentication.\n      - name: Private Clusters\n        description: Deploy private AKS clusters with private endpoint connections for secure API server access.\n      - name: Maintenance Windows\n        description: Configure planned\
  \ maintenance windows to control when updates are applied to clusters.\n      - name: Node Pool Snapshots\n        description: Create and manage snapshots of node pools for backup and recovery scenarios.\n      - name: Trusted Access\n        description: Grant Azure services secure access to AKS API server using managed identities and role bindings.\n      - name: Run Commands\n        description: Execute commands on cluster nodes remotely through the AKS API without direct SSH access.\n      - name: Auto-Scaling\n        description: Automatically scale node pools based on workload demands with configurable auto-scaler profiles.\n  - type: UseCases\n    data:\n      - name: Microservices Deployment\n        description: Deploy and manage microservices architectures with container orchestration and service mesh capabilities.\n      - name: CI/CD Pipelines\n        description: Integrate AKS with Azure DevOps and GitHub Actions for automated build, test, and deployment workflows.\n \
  \     - name: Hybrid Cloud\n        description: Run Kubernetes workloads across on-premises and Azure environments with Azure Arc integration.\n      - name: Machine Learning\n        description: Deploy and scale ML model serving infrastructure using AKS with GPU-enabled node pools.\n      - name: Edge Computing\n        description: Deploy containerized workloads to edge locations using AKS Edge Essentials and Azure IoT.\n  - type: Integrations\n    data:\n      - name: Azure Container Registry\n        description: Pull container images from Azure Container Registry with managed identity authentication.\n      - name: Azure Monitor\n        description: Monitor cluster health, performance, and logs with Azure Monitor and Container Insights.\n      - name: Azure Policy\n        description: Enforce organizational standards and compliance with Azure Policy for Kubernetes.\n      - name: Azure Active Directory\n        description: Integrate with Azure AD for cluster authentication and\
  \ role-based access control.\n      - name: Azure DevOps\n        description: Automate deployments to AKS using Azure Pipelines with native Kubernetes tasks.\ninclude:\n  - name: Azure Container Registry APIs\n    url: https://apis.io/apis/azure-container-registry\n  - name: Azure Monitor APIs\n    url: https://apis.io/apis/azure-monitor\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-kubernetes-service/refs/heads/main/apis.yml
tags:
- Azure
- Cloud
- Containers
- DevOps
- Kubernetes
- Orchestration
url: https://azure.microsoft.com/en-us/services/kubernetes-service/
use_cases:
- description: Deploy and manage microservices architectures with container orchestration and service mesh capabilities.
  name: Microservices Deployment
- description: Integrate AKS with Azure DevOps and GitHub Actions for automated build, test, and deployment workflows.
  name: CI/CD Pipelines
- description: Run Kubernetes workloads across on-premises and Azure environments with Azure Arc integration.
  name: Hybrid Cloud
- description: Deploy and scale ML model serving infrastructure using AKS with GPU-enabled node pools.
  name: Machine Learning
- description: Deploy containerized workloads to edge locations using AKS Edge Essentials and Azure IoT.
  name: Edge Computing
---
