---
api_count: 4
api_specs:
- filename: api
  format: yaml
  label: Azure Pipelines REST API
  slug: ''
  spec_type: OpenAPI
  url: https://dev.azure.com/{organization}/_apis/public/api
apis:
- description: REST API for managing and interacting with Azure Pipelines including creating, listing, and getting pipelines, triggering and monitoring pipeline runs, and retrieving pipeline run logs. Provides progr
  name: Azure Pipelines REST API
  slug: ''
- description: REST API for managing build definitions, queuing builds, and retrieving build results, artifacts, tags, and logs. Supports the full lifecycle of continuous integration builds in Azure DevOps, includin
  name: Azure Pipelines Build REST API
  slug: ''
- description: REST API for managing release definitions, creating and tracking releases, and configuring deployment approvals. Enables programmatic control of the continuous delivery process including defining rele
  name: Azure Pipelines Release REST API
  slug: ''
- description: REST API for managing pipeline approvals and checks on resources such as environments, service connections, agent pools, variable groups, and secure files. Provides the ability to create and modify ch
  name: Azure Pipelines Approvals and Checks REST API
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines
- title: ''
  type: Portal
  url: https://dev.azure.com/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/
- title: ''
  type: Status
  url: https://status.dev.azure.com/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/devops/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/devops/pipelines/
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/devops
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/products/devops
- title: ''
  type: Login
  url: https://dev.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/devops/
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released
- title: ''
  type: Client Libraries
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries
- title: ''
  type: Community
  url: https://developercommunity.visualstudio.com/AzureDevOps
- title: ''
  type: GitHub Organization
  url: https://github.com/MicrosoftDocs
- title: ''
  type: GitHubRepository
  url: https://github.com/MicrosoftDocs/azure-devops-docs
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-devops
- title: ''
  type: Marketplace
  url: https://marketplace.visualstudio.com/azuredevops
- title: ''
  type: CLI
  url: https://github.com/Azure/azure-devops-cli-extension
- title: ''
  type: Task Reference
  url: https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/
created: '2024'
description: Azure Pipelines is a cloud service that you can use to automatically build and test your code project and make it available to other users. It works with just about any language or project type.
features: []
image: https://azure.microsoft.com/svghandler/devops/?width=600&height=315
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Pipelines
skills: []
slug: microsoft-azure-pipelines
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Pipelines\ndescription: Azure Pipelines is a cloud service that you can use to automatically build and test your code project and make it available to other users. It works with just about any language or project type.\nimage: https://azure.microsoft.com/svghandler/devops/?width=600&height=315\ntags:\n  - Automation\n  - Build\n  - CI/CD\n  - Deployment\n  - DevOps\n  - Pipelines\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\napis:\n  - name: Azure Pipelines REST API\n    description: >-\n      REST API for managing and interacting with Azure Pipelines including creating,\n      listing, and getting pipelines, triggering and monitoring pipeline runs, and\n      retrieving pipeline run logs. Provides programmatic access to the core CI/CD\n      pipeline orchestration capabilities in Azure DevOps.\n    image: https://azure.microsoft.com/svghandler/devops/?width=600&height=315\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/\n\
  \    baseURL: https://dev.azure.com/{organization}/{project}/_apis\n    tags:\n      - CI/CD\n      - Pipelines\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/\n      - type: OpenAPI\n        url: https://dev.azure.com/{organization}/_apis/public/api\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline\n      - type: Client Libraries\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries\n      - type: Change Log\n        url: https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released\n      - type: YAML Schema\n        url: https://learn.microsoft.com/en-us/azure/devops/pipelines/yaml-schema/\n    contact:\n\
  \      - type: Support\n        url: https://azure.microsoft.com/en-us/support/devops/\n      - type: Twitter\n        url: https://twitter.com/AzureDevOps\n  - name: Azure Pipelines Build REST API\n    description: >-\n      REST API for managing build definitions, queuing builds, and retrieving build\n      results, artifacts, tags, and logs. Supports the full lifecycle of continuous\n      integration builds in Azure DevOps, including creating and updating build\n      definitions from templates, listing and tagging builds, and downloading build\n      artifacts.\n    image: https://azure.microsoft.com/svghandler/devops/?width=600&height=315\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/build/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/build\n    tags:\n      - Artifacts\n      - Build\n      - Continuous Integration\n      - Definitions\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/build/\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\n  - name: Azure Pipelines Release REST API\n    description: >-\n      REST API for managing release definitions, creating and tracking releases, and\n      configuring deployment approvals. Enables programmatic control of the continuous\n      delivery process including defining release pipelines with multiple environments,\n      triggering deployments, and managing approval workflows.\n    image: https://azure.microsoft.com/svghandler/devops/?width=600&height=315\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/release/\n    baseURL: https://vsrm.dev.azure.com/{organization}/{project}/_apis/release\n    tags:\n      - Approvals\n      - Continuous Delivery\n      - Deployment\n      - Release\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/release/\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\n  - name: Azure Pipelines Approvals and Checks REST API\n    description: >-\n      REST API for managing pipeline approvals and checks on resources such as\n      environments, service connections, agent pools, variable groups, and secure\n      files. Provides the ability to create and modify check configurations, manage\n      approval workflows, query check evaluation details, and control pipeline\n      permissions for protected resources.\n    image: https://azure.microsoft.com/svghandler/devops/?width=600&height=315\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/pipelines\n    tags:\n      - Approvals\n      - Checks\n      - Governance\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\ncommon:\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines\n  - type: Portal\n    url: https://dev.azure.com/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/\n  - type: Status\n    url: https://status.dev.azure.com/\n  - type: Blog\n    url: https://devblogs.microsoft.com/devops/\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/devops/pipelines/\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/devops\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/products/devops\n\
  \  - type: Login\n    url: https://dev.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/devops/\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released\n  - type: Client Libraries\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries\n  - type: Community\n    url: https://developercommunity.visualstudio.com/AzureDevOps\n  - type: GitHub Organization\n    url: https://github.com/MicrosoftDocs\n  - type: GitHubRepository\n    url: https://github.com/MicrosoftDocs/azure-devops-docs\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-devops\n  - type: Marketplace\n    url: https://marketplace.visualstudio.com/azuredevops\n  - type: CLI\n    url: https://github.com/Azure/azure-devops-cli-extension\n  - type: Task Reference\n    url: https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\nendpoints:\n  pipelines:\n    - name: List Pipelines\n      method: GET\n      path: /pipelines\n      description: Get a list of pipelines\n    - name: Get Pipeline\n      method: GET\n      path: /pipelines/{pipelineId}\n      description: Gets a pipeline, optionally at the specified version\n    - name: Create Pipeline\n      method: POST\n      path: /pipelines\n      description: Create a pipeline\n  runs:\n    - name: List Runs\n      method: GET\n      path: /pipelines/{pipelineId}/runs\n      description: Gets top 10000 runs for a particular pipeline\n    - name: Get Run\n      method: GET\n      path: /pipelines/{pipelineId}/runs/{runId}\n      description: Gets a run for a particular pipeline\n    - name: Run Pipeline\n      method: POST\n      path: /pipelines/{pipelineId}/runs\n      description: Runs a pipeline\n  artifacts:\n    - name: List Artifacts\n      method: GET\n      path: /build/builds/{buildId}/artifacts\n \
  \     description: Get all artifacts for a build\n    - name: Get Artifact\n      method: GET\n      path: /build/builds/{buildId}/artifacts/{artifactName}\n      description: Get a specific artifact for a build\n  logs:\n    - name: Get Log\n      method: GET\n      path: /pipelines/{pipelineId}/runs/{runId}/logs/{logId}\n      description: Get a specific log from a pipeline run\n    - name: List Logs\n      method: GET\n      path: /pipelines/{pipelineId}/runs/{runId}/logs\n      description: Get a list of logs from a pipeline run\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-pipelines/refs/heads/main/apis.yml
tags:
- Automation
- Build
- CI/CD
- Deployment
- DevOps
- Pipelines
url: ''
use_cases: []
---
