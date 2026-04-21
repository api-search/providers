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
