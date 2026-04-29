---
api_count: 10
apis:
- description: Manage virtual machines, containers, serverless functions, and Kubernetes clusters. Includes Azure Virtual Machines, Azure Kubernetes Service (AKS), Azure Container Apps, Azure Functions, and App Serv
  name: Azure Compute API
  slug: azure-compute-api
- description: Scalable cloud storage REST APIs for blobs, files, queues, and tables. Includes Blob Storage, Azure Files, Queue Storage, Table Storage, and Azure Data Lake Storage.
  name: Azure Storage API
  slug: azure-storage-api
- description: REST APIs for Azure networking resources including Virtual Networks, Load Balancers, Application Gateways, VPN Gateways, Azure Firewall, Front Door, and ExpressRoute.
  name: Azure Networking API
  slug: azure-networking-api
- description: Managed database REST APIs for Azure SQL Database, Azure Cosmos DB, Azure Database for PostgreSQL, Azure Database for MySQL, and Azure Cache for Redis.
  name: Azure Databases API
  slug: azure-databases-api
- description: REST APIs for Azure AI and Machine Learning services including Azure OpenAI Service, Azure Machine Learning, Azure AI Search, Computer Vision, Speech, and Document Intelligence.
  name: Azure AI Services API
  slug: azure-ai-api
- description: REST APIs for Azure security services including Microsoft Defender for Cloud, Key Vault, Microsoft Sentinel, and Web Application Firewall.
  name: Azure Security API
  slug: azure-security-api
- description: REST APIs for Azure integration services including Service Bus, Event Grid, Logic Apps, and API Management for building event-driven and workflow-based applications.
  name: Azure Integration API
  slug: azure-integration-api
- description: REST APIs for Azure analytics services including Synapse Analytics, Data Factory, Stream Analytics, Data Explorer, and Microsoft Fabric for big data and real-time analytics workloads.
  name: Azure Analytics API
  slug: azure-analytics-api
- description: REST APIs for Azure management and governance including Azure Resource Manager, Azure Monitor, Azure Policy, Cost Management, and Azure Advisor.
  name: Azure Management API
  slug: azure-management-api
- description: REST APIs for Azure IoT services including IoT Hub, IoT Central, IoT Edge, and Azure Digital Twins for connecting, monitoring, and managing IoT devices at scale.
  name: Azure IoT API
  slug: azure-iot-api
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/azure/developer/intro/azure-developer-overview
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/en-us/rest/api/azure/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/entra/identity-platform/v2-oauth2-client-creds-grant-flow
- title: ''
  type: StatusPage
  url: https://status.azure.com
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHubOrganization
  url: https://github.com/Azure
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/
- title: ''
  type: SignUp
  url: https://azure.microsoft.com/en-us/free/
- title: ''
  type: CLI
  url: https://learn.microsoft.com/en-us/cli/azure/
- title: ''
  type: SDK
  url: https://azure.github.io/azure-sdk/
created: '2024-01-01'
description: A comprehensive collection of Microsoft Azure cloud service APIs covering compute, storage, databases, AI, networking, security, and developer tools. Azure provides IaaS, PaaS, and SaaS delivery models through a global network of datacenters, with REST APIs secured by Microsoft Entra ID authentication.
features:
- description: Operates across 60+ regions worldwide with 99.99% SLA guarantees for most services.
  name: Global Infrastructure
- description: All REST APIs use OAuth 2.0 / Microsoft Entra ID for secure, standards-based authentication.
  name: Microsoft Entra ID Authentication
- description: Consistent management layer for deploying and managing all Azure resources via ARM templates and REST.
  name: Azure Resource Manager
- description: Long-running operations follow the async pattern with polling endpoints for status checks.
  name: Async Operations
- description: Per-subscription throttling with remaining request counts returned in response headers.
  name: Throttling and Rate Limits
- description: List operations return nextLink for cursor-based pagination across large result sets.
  name: Pagination
- description: Official SDKs available for .NET, Java, Python, JavaScript/TypeScript, Go, C++, and Rust.
  name: Multi-Language SDKs
- description: Azure Arc extends Azure management to on-premises and multi-cloud environments.
  name: Hybrid and Multi-Cloud
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with GitHub for source control, Actions CI/CD, and Azure deployment.
  name: GitHub
- description: Integration with Microsoft 365 services via Microsoft Graph API.
  name: Microsoft 365
- description: Azure Provider for Terraform enables infrastructure-as-code deployments.
  name: Terraform
- description: First-class Azure extension support in Visual Studio and Visual Studio Code.
  name: Visual Studio / VS Code
- description: Azure Kubernetes Service provides managed Kubernetes with deep Azure ecosystem integration.
  name: Kubernetes
- description: Native Datadog integration for monitoring Azure infrastructure and applications.
  name: Datadog
- description: Splunk Add-on for Microsoft Azure for security and operational analytics.
  name: Splunk
layout: provider
modified: '2026-04-19'
name: Microsoft Azure Cloud
skills: []
slug: azure-cloud
solutions: []
source_filename: apis.yml
source_yaml: "aid: azure-cloud\nname: Microsoft Azure Cloud\ndescription: >-\n  A comprehensive collection of Microsoft Azure cloud service APIs covering\n  compute, storage, databases, AI, networking, security, and developer tools.\n  Azure provides IaaS, PaaS, and SaaS delivery models through a global network\n  of datacenters, with REST APIs secured by Microsoft Entra ID authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Cloud Computing\n  - Databases\n  - IaaS\n  - Infrastructure\n  - Machine Learning\n  - Microsoft\n  - Networking\n  - PaaS\n  - Platform as a Service\n  - SaaS\n  - Storage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-cloud/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: azure-cloud:azure-compute-api\n    name: Azure Compute API\n    description: >-\n      Manage virtual machines, containers, serverless\
  \ functions, and Kubernetes\n      clusters. Includes Azure Virtual Machines, Azure Kubernetes Service (AKS),\n      Azure Container Apps, Azure Functions, and App Service APIs.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/compute/\n    baseURL: https://management.azure.com\n    tags:\n      - App Service\n      - Compute\n      - Containers\n      - Functions\n      - Kubernetes\n      - Serverless\n      - Virtual Machines\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/virtual-machines/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/compute/resource-manager/Microsoft.Compute/stable/2023-03-01/compute.json\n  - aid: azure-cloud:azure-storage-api\n    name: Azure Storage API\n    description: >-\n      Scalable cloud storage REST APIs for blobs, files, queues,\
  \ and tables.\n      Includes Blob Storage, Azure Files, Queue Storage, Table Storage, and\n      Azure Data Lake Storage.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/\n    baseURL: https://management.azure.com\n    tags:\n      - Blob Storage\n      - Cloud Storage\n      - File Storage\n      - Object Storage\n      - Queue Storage\n      - Storage\n      - Table Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/resource-manager/Microsoft.Storage/stable/2023-01-01/storage.json\n  - aid: azure-cloud:azure-networking-api\n    name: Azure Networking API\n    description: >-\n      REST APIs for Azure networking resources including Virtual Networks,\n      Load Balancers, Application Gateways, VPN Gateways, Azure Firewall,\n      Front Door, and ExpressRoute.\n\
  \    humanURL: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/\n    baseURL: https://management.azure.com\n    tags:\n      - ExpressRoute\n      - Firewall\n      - Load Balancer\n      - Networking\n      - Virtual Network\n      - VPN\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/virtualnetwork/\n  - aid: azure-cloud:azure-databases-api\n    name: Azure Databases API\n    description: >-\n      Managed database REST APIs for Azure SQL Database, Azure Cosmos DB,\n      Azure Database for PostgreSQL, Azure Database for MySQL, and\n      Azure Cache for Redis.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/sql/\n    baseURL: https://management.azure.com\n    tags:\n      - Cosmos DB\n      - Databases\n      - MySQL\n      - NoSQL\n      - PostgreSQL\n      - Redis\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/sql/\n  - aid: azure-cloud:azure-ai-api\n\
  \    name: Azure AI Services API\n    description: >-\n      REST APIs for Azure AI and Machine Learning services including\n      Azure OpenAI Service, Azure Machine Learning, Azure AI Search,\n      Computer Vision, Speech, and Document Intelligence.\n    humanURL: https://learn.microsoft.com/en-us/azure/ai-services/\n    baseURL: https://management.azure.com\n    tags:\n      - AI\n      - Artificial Intelligence\n      - Computer Vision\n      - Language\n      - Machine Learning\n      - OpenAI\n      - Speech\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/ai-services/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/cognitiveservices/\n  - aid: azure-cloud:azure-security-api\n    name: Azure Security API\n    description: >-\n      REST APIs for Azure security services including Microsoft Defender for\n      Cloud, Key Vault, Microsoft Sentinel, and Web Application Firewall.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/defenderforcloud/\n\
  \    baseURL: https://management.azure.com\n    tags:\n      - Defender\n      - Identity\n      - Key Vault\n      - Security\n      - Sentinel\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/defenderforcloud/\n  - aid: azure-cloud:azure-integration-api\n    name: Azure Integration API\n    description: >-\n      REST APIs for Azure integration services including Service Bus, Event\n      Grid, Logic Apps, and API Management for building event-driven and\n      workflow-based applications.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/servicebus/\n    baseURL: https://management.azure.com\n    tags:\n      - API Management\n      - Event Grid\n      - Integration\n      - Logic Apps\n      - Messaging\n      - Service Bus\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/servicebus/\n  - aid: azure-cloud:azure-analytics-api\n    name: Azure Analytics\
  \ API\n    description: >-\n      REST APIs for Azure analytics services including Synapse Analytics,\n      Data Factory, Stream Analytics, Data Explorer, and Microsoft Fabric\n      for big data and real-time analytics workloads.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/synapse/\n    baseURL: https://management.azure.com\n    tags:\n      - Analytics\n      - Big Data\n      - Data Factory\n      - ETL\n      - Stream Analytics\n      - Synapse\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/synapse/\n  - aid: azure-cloud:azure-management-api\n    name: Azure Management API\n    description: >-\n      REST APIs for Azure management and governance including Azure Resource\n      Manager, Azure Monitor, Azure Policy, Cost Management, and Azure Advisor.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/\n    baseURL: https://management.azure.com\n    tags:\n      - Cost Management\n      - Governance\n\
  \      - Management\n      - Monitor\n      - Policy\n      - Resource Manager\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/resources/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/azure/#register-your-client-application-with-microsoft-entra-id\n  - aid: azure-cloud:azure-iot-api\n    name: Azure IoT API\n    description: >-\n      REST APIs for Azure IoT services including IoT Hub, IoT Central,\n      IoT Edge, and Azure Digital Twins for connecting, monitoring, and\n      managing IoT devices at scale.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/iothub/\n    baseURL: https://management.azure.com\n    tags:\n      - Digital Twins\n      - IoT\n      - IoT Central\n      - IoT Edge\n      - IoT Hub\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/iothub/\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n  - type:\
  \ Documentation\n    url: https://learn.microsoft.com/en-us/azure/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/azure/developer/intro/azure-developer-overview\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/rest/api/azure/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/entra/identity-platform/v2-oauth2-client-creds-grant-flow\n  - type: StatusPage\n    url: https://status.azure.com\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GitHubOrganization\n    url: https://github.com/Azure\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/\n  - type: SignUp\n    url: https://azure.microsoft.com/en-us/free/\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/cli/azure/\n\
  \  - type: SDK\n    url: https://azure.github.io/azure-sdk/\n  - type: Features\n    data:\n      - name: Global Infrastructure\n        description: Operates across 60+ regions worldwide with 99.99% SLA guarantees for most services.\n      - name: Microsoft Entra ID Authentication\n        description: All REST APIs use OAuth 2.0 / Microsoft Entra ID for secure, standards-based authentication.\n      - name: Azure Resource Manager\n        description: Consistent management layer for deploying and managing all Azure resources via ARM templates and REST.\n      - name: Async Operations\n        description: Long-running operations follow the async pattern with polling endpoints for status checks.\n      - name: Throttling and Rate Limits\n        description: Per-subscription throttling with remaining request counts returned in response headers.\n      - name: Pagination\n        description: List operations return nextLink for cursor-based pagination across large result sets.\n      -\
  \ name: Multi-Language SDKs\n        description: Official SDKs available for .NET, Java, Python, JavaScript/TypeScript, Go, C++, and Rust.\n      - name: Hybrid and Multi-Cloud\n        description: Azure Arc extends Azure management to on-premises and multi-cloud environments.\n  - type: UseCases\n    data:\n      - name: Enterprise Cloud Migration\n        description: Migrate on-premises workloads to Azure using IaaS VMs or PaaS services with hybrid connectivity.\n      - name: Cloud-Native Application Development\n        description: Build microservices using Azure Kubernetes Service, Container Apps, and serverless Functions.\n      - name: AI and Machine Learning Workloads\n        description: Train and deploy ML models using Azure Machine Learning and Azure OpenAI Service.\n      - name: Data Analytics and Business Intelligence\n        description: Build data pipelines with Data Factory and analyze at scale with Synapse Analytics.\n      - name: DevOps and CI/CD Automation\n\
  \        description: Automate build, test, and deployment pipelines using Azure DevOps and GitHub Actions.\n      - name: IoT Device Management\n        description: Connect and manage millions of IoT devices with IoT Hub and IoT Central.\n      - name: Security and Compliance\n        description: Protect workloads and meet compliance requirements with Defender for Cloud and Sentinel.\n  - type: Integrations\n    data:\n      - name: GitHub\n        description: Native integration with GitHub for source control, Actions CI/CD, and Azure deployment.\n      - name: Microsoft 365\n        description: Integration with Microsoft 365 services via Microsoft Graph API.\n      - name: Terraform\n        description: Azure Provider for Terraform enables infrastructure-as-code deployments.\n      - name: Visual Studio / VS Code\n        description: First-class Azure extension support in Visual Studio and Visual Studio Code.\n      - name: Kubernetes\n        description: Azure Kubernetes Service\
  \ provides managed Kubernetes with deep Azure ecosystem integration.\n      - name: Datadog\n        description: Native Datadog integration for monitoring Azure infrastructure and applications.\n      - name: Splunk\n        description: Splunk Add-on for Microsoft Azure for security and operational analytics.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-cloud/refs/heads/main/apis.yml
tags:
- AI
- Cloud Computing
- Databases
- IaaS
- Infrastructure
- Machine Learning
- Microsoft
- Networking
- PaaS
- Platform as a Service
- SaaS
- Storage
url: https://raw.githubusercontent.com/api-evangelist/azure-cloud/refs/heads/main/apis.yml
use_cases:
- description: Migrate on-premises workloads to Azure using IaaS VMs or PaaS services with hybrid connectivity.
  name: Enterprise Cloud Migration
- description: Build microservices using Azure Kubernetes Service, Container Apps, and serverless Functions.
  name: Cloud-Native Application Development
- description: Train and deploy ML models using Azure Machine Learning and Azure OpenAI Service.
  name: AI and Machine Learning Workloads
- description: Build data pipelines with Data Factory and analyze at scale with Synapse Analytics.
  name: Data Analytics and Business Intelligence
- description: Automate build, test, and deployment pipelines using Azure DevOps and GitHub Actions.
  name: DevOps and CI/CD Automation
- description: Connect and manage millions of IoT devices with IoT Hub and IoT Central.
  name: IoT Device Management
- description: Protect workloads and meet compliance requirements with Defender for Cloud and Sentinel.
  name: Security and Compliance
---
