---
api_count: 2
apis:
- description: The Azure App Service / Web Apps REST API provides management operations for Azure Functions apps including creating and configuring function apps, managing deployment slots, application settings, hos
  name: Azure Functions Management API
  slug: azure-functions-management-api
- description: The Azure Functions host runtime provides HTTP endpoints for function invocation, admin operations, host status, function management, and key management. Includes endpoints for listing functions, gett
  name: Azure Functions Runtime API
  slug: azure-functions-runtime-api
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-get-started
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/azure-functions/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/functions/
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-versions
- title: ''
  type: GitHubOrganization
  url: https://github.com/Azure
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/azure-functions-host
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/azure-functions-core-tools
- title: .NET SDK
  type: SDK
  url: https://www.nuget.org/packages/Microsoft.Azure.Functions.Worker
- title: Python SDK
  type: SDK
  url: https://pypi.org/project/azure-functions/
- title: Node.js SDK
  type: SDK
  url: https://www.npmjs.com/package/@azure/functions
- title: Java SDK
  type: SDK
  url: https://central.sonatype.com/artifact/com.microsoft.azure.functions/azure-functions-java-library
- title: Azure Functions Core Tools
  type: CLI
  url: https://github.com/Azure/azure-functions-core-tools
- title: Azure CLI (az functionapp)
  type: CLI
  url: https://learn.microsoft.com/en-us/cli/azure/functionapp
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/paths/create-serverless-applications/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/azure-functions
- title: ''
  type: X
  url: https://x.com/AzureFunctions
created: '2024-01-01'
description: Azure Functions is a serverless compute platform from Microsoft Azure enabling event-driven code execution triggered by HTTP requests, timers, queues, blobs, and other Azure services. The Azure Functions management API provides programmatic access to function app lifecycle management, deployment, configuration, scaling, and monitoring through Azure Resource Manager.
features:
- description: Execute functions via HTTP requests with RESTful endpoint support and built-in authentication.
  name: HTTP Triggers
- description: Schedule function execution using CRON expressions for recurring tasks.
  name: Timer Triggers
- description: Process messages from Azure Storage Queues and Service Bus for async workloads.
  name: Queue Triggers
- description: React to blob storage changes for file processing and data pipeline automation.
  name: Blob Triggers
- description: Handle events from Azure Event Grid for event-driven architectures.
  name: Event Grid Triggers
- description: Process database changes in Azure Cosmos DB using the change feed.
  name: Cosmos DB Triggers
- description: Orchestrate complex stateful workflows with function chaining, fan-out/fan-in, and human interaction patterns.
  name: Durable Functions
- description: Manage staging and production slots for zero-downtime deployments and traffic splitting.
  name: Deployment Slots
- description: Run functions in any language by implementing a lightweight HTTP server.
  name: Custom Handlers
- description: Authenticate to Azure services without managing credentials using system or user-assigned identities.
  name: Managed Identity
- description: Automatic scaling from zero to thousands of instances based on event load.
  name: Scaling
- description: Pre-warmed instances, VNET integration, and unlimited execution duration for enterprise workloads.
  name: Premium Plan
image: /assets/icons/microsoft-azure-functions.png
integrations:
- description: Front Azure Functions with API Management for rate limiting, authentication, and developer portal.
  name: Azure API Management
- description: CI/CD pipeline integration for automated function deployment and testing.
  name: Azure DevOps
- description: Deploy Azure Functions directly from GitHub repositories with Actions workflows.
  name: GitHub Actions
- description: Full development experience with the Azure Functions VS Code extension.
  name: Visual Studio Code
- description: Application Insights integration for function monitoring, logging, and diagnostics.
  name: Azure Monitor
- description: Secure secrets management with Key Vault references in application settings.
  name: Azure Key Vault
- description: Infrastructure-as-code management of function apps with the AzureRM Terraform provider.
  name: Terraform
jsonld:
- class_count: 29
  name: Azure Functions Context
  property_count: 158
  slug: azure-functions-context
layout: provider
modified: '2026-04-17'
name: Microsoft Azure Functions
rules:
- name: Microsoft Azure Functions API Rules
  rule_count: 19
  severity_counts:
    error: 14
    hint: 0
    info: 3
    warn: 2
  slug: azure-functions-spectral-rules
skills: []
slug: microsoft-azure-functions
solutions:
- description: Pay-per-execution pricing with automatic scaling and 5-minute execution timeout.
  name: Consumption Plan
- description: Pre-warmed instances, VNET integration, unlimited duration, and larger instance sizes.
  name: Premium Plan
- description: Run functions on dedicated App Service plans for predictable pricing and always-on execution.
  name: Dedicated Plan
- description: Run containerized functions on Azure Container Apps for Kubernetes-based hosting.
  name: Container Apps
source_yaml: "aid: microsoft-azure-functions\nname: Microsoft Azure Functions\ndescription: >-\n  Azure Functions is a serverless compute platform from Microsoft Azure enabling\n  event-driven code execution triggered by HTTP requests, timers, queues, blobs,\n  and other Azure services. The Azure Functions management API provides programmatic\n  access to function app lifecycle management, deployment, configuration, scaling,\n  and monitoring through Azure Resource Manager.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-functions/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntags:\n  - Azure\n  - Cloud\n  - Compute\n  - Event-Driven\n  - Microsoft\n  - Serverless\napis:\n  - aid: microsoft-azure-functions:azure-functions-management-api\n    name: Azure Functions Management API\n    description: >-\n      The Azure\
  \ App Service / Web Apps REST API provides management operations for\n      Azure Functions apps including creating and configuring function apps, managing\n      deployment slots, application settings, host keys, function keys, scaling\n      configuration, and monitoring. Part of the Azure Resource Manager API surface.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/appservice/web-apps\n    baseURL: https://management.azure.com\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/appservice/web-apps\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-get-started\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/appservice/web-apps/get\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/azure/#register-your-client-application-with-azure-ad\n      - type: OpenAPI\n        url: openapi/azure-functions-management-api.json\n\
  \    tags:\n      - App Service\n      - Deployment\n      - Functions\n      - Management\n      - Resource Manager\n      - Serverless\n  - aid: microsoft-azure-functions:azure-functions-runtime-api\n    name: Azure Functions Runtime API\n    description: >-\n      The Azure Functions host runtime provides HTTP endpoints for function invocation,\n      admin operations, host status, function management, and key management. Includes\n      endpoints for listing functions, getting function status, managing host and\n      function keys, and triggering function execution.\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference\n    baseURL: https://{functionapp}.azurewebsites.net\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/azure-functions/create-first-function-cli-csharp\n      -\
  \ type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/azure-functions/security-concepts\n    tags:\n      - Event-Driven\n      - Functions\n      - HTTP Trigger\n      - Runtime\n      - Serverless\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-get-started\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/azure-functions/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/functions/\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/azure/azure-functions/functions-versions\n\
  \  - type: GitHubOrganization\n    url: https://github.com/Azure\n  - type: GitHubRepository\n    url: https://github.com/Azure/azure-functions-host\n  - type: GitHubRepository\n    url: https://github.com/Azure/azure-functions-core-tools\n  - type: SDK\n    url: https://www.nuget.org/packages/Microsoft.Azure.Functions.Worker\n    title: .NET SDK\n  - type: SDK\n    url: https://pypi.org/project/azure-functions/\n    title: Python SDK\n  - type: SDK\n    url: https://www.npmjs.com/package/@azure/functions\n    title: Node.js SDK\n  - type: SDK\n    url: https://central.sonatype.com/artifact/com.microsoft.azure.functions/azure-functions-java-library\n    title: Java SDK\n  - type: CLI\n    url: https://github.com/Azure/azure-functions-core-tools\n    title: Azure Functions Core Tools\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/cli/azure/functionapp\n    title: Azure CLI (az functionapp)\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/paths/create-serverless-applications/\n\
  \  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/azure-functions\n  - type: X\n    url: https://x.com/AzureFunctions\n  - type: Features\n    data:\n      - name: HTTP Triggers\n        description: Execute functions via HTTP requests with RESTful endpoint support and built-in authentication.\n      - name: Timer Triggers\n        description: Schedule function execution using CRON expressions for recurring tasks.\n      - name: Queue Triggers\n        description: Process messages from Azure Storage Queues and Service Bus for async workloads.\n      - name: Blob Triggers\n        description: React to blob storage changes for file processing and data pipeline automation.\n      - name: Event Grid Triggers\n        description: Handle events from Azure Event Grid for event-driven architectures.\n      - name: Cosmos DB Triggers\n        description: Process database changes in Azure Cosmos DB using the change feed.\n      - name: Durable Functions\n       \
  \ description: Orchestrate complex stateful workflows with function chaining, fan-out/fan-in, and human interaction patterns.\n      - name: Deployment Slots\n        description: Manage staging and production slots for zero-downtime deployments and traffic splitting.\n      - name: Custom Handlers\n        description: Run functions in any language by implementing a lightweight HTTP server.\n      - name: Managed Identity\n        description: Authenticate to Azure services without managing credentials using system or user-assigned identities.\n      - name: Scaling\n        description: Automatic scaling from zero to thousands of instances based on event load.\n      - name: Premium Plan\n        description: Pre-warmed instances, VNET integration, and unlimited execution duration for enterprise workloads.\n  - type: UseCases\n    data:\n      - name: API Backend\n        description: Build serverless REST APIs with HTTP-triggered functions and Azure API Management integration.\n   \
  \   - name: Event Processing\n        description: Process events from queues, topics, Event Grid, and IoT Hub for real-time data pipelines.\n      - name: Scheduled Tasks\n        description: Run scheduled jobs for data cleanup, report generation, and system maintenance.\n      - name: File Processing\n        description: Transform, validate, and process files uploaded to blob storage.\n      - name: Webhook Handling\n        description: Receive and process webhooks from third-party services and SaaS platforms.\n      - name: Microservices\n        description: Build lightweight microservices with independent scaling and deployment.\n      - name: Data Transformation\n        description: ETL workloads for transforming and loading data between Azure services.\n      - name: IoT Backend\n        description: Process IoT device telemetry and events with Event Hub and IoT Hub triggers.\n  - type: Integrations\n    data:\n      - name: Azure API Management\n        description: Front Azure\
  \ Functions with API Management for rate limiting, authentication, and developer portal.\n      - name: Azure DevOps\n        description: CI/CD pipeline integration for automated function deployment and testing.\n      - name: GitHub Actions\n        description: Deploy Azure Functions directly from GitHub repositories with Actions workflows.\n      - name: Visual Studio Code\n        description: Full development experience with the Azure Functions VS Code extension.\n      - name: Azure Monitor\n        description: Application Insights integration for function monitoring, logging, and diagnostics.\n      - name: Azure Key Vault\n        description: Secure secrets management with Key Vault references in application settings.\n      - name: Terraform\n        description: Infrastructure-as-code management of function apps with the AzureRM Terraform provider.\n  - type: Solutions\n    data:\n      - name: Consumption Plan\n        description: Pay-per-execution pricing with automatic\
  \ scaling and 5-minute execution timeout.\n      - name: Premium Plan\n        description: Pre-warmed instances, VNET integration, unlimited duration, and larger instance sizes.\n      - name: Dedicated Plan\n        description: Run functions on dedicated App Service plans for predictable pricing and always-on execution.\n      - name: Container Apps\n        description: Run containerized functions on Azure Container Apps for Kubernetes-based hosting.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-functions/refs/heads/main/apis.yml
tags:
- Azure
- Cloud
- Compute
- Event-Driven
- Microsoft
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-functions/refs/heads/main/apis.yml
use_cases:
- description: Build serverless REST APIs with HTTP-triggered functions and Azure API Management integration.
  name: API Backend
- description: Process events from queues, topics, Event Grid, and IoT Hub for real-time data pipelines.
  name: Event Processing
- description: Run scheduled jobs for data cleanup, report generation, and system maintenance.
  name: Scheduled Tasks
- description: Transform, validate, and process files uploaded to blob storage.
  name: File Processing
- description: Receive and process webhooks from third-party services and SaaS platforms.
  name: Webhook Handling
- description: Build lightweight microservices with independent scaling and deployment.
  name: Microservices
- description: ETL workloads for transforming and loading data between Azure services.
  name: Data Transformation
- description: Process IoT device telemetry and events with Event Hub and IoT Hub triggers.
  name: IoT Backend
---
