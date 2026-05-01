---
api_count: 6
api_specs:
- filename: azure-devops-work-items-openapi.yml
  format: yaml
  label: Azure DevOps Work Item Tracking API
  slug: azure-devops-work-item-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/openapi/azure-devops-work-items-openapi.yml
- filename: azure-devops-pipelines-openapi.yml
  format: yaml
  label: Azure DevOps Pipelines API
  slug: azure-devops-pipelines-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/openapi/azure-devops-pipelines-openapi.yml
apis:
- description: 'The Azure DevOps Work Item Tracking API provides REST endpoints for creating, updating, querying, and managing work items including bugs, tasks, user stories, epics, and features across Azure Boards. '
  name: Azure DevOps Work Item Tracking API
  slug: azure-devops-work-item-tracking-api
- description: The Azure DevOps Git Repositories API provides REST endpoints for managing Git repositories, branches, commits, pull requests, and code reviews. APIs enable automation of repository management, pull r
  name: Azure DevOps Git Repositories API
  slug: azure-devops-git-api
- description: The Azure DevOps Pipelines API provides REST endpoints for managing CI/CD build and release pipelines. APIs support pipeline creation, triggering builds, retrieving build results, managing release def
  name: Azure DevOps Pipelines API
  slug: azure-devops-pipelines-api
- description: The Azure DevOps Artifacts API provides REST endpoints for managing package feeds including NuGet, npm, Maven, Python, and Universal Packages. APIs support feed creation, package publishing, version m
  name: Azure DevOps Artifacts API
  slug: azure-devops-artifacts-api
- description: 'The Azure DevOps Test Plans API provides REST endpoints for managing test plans, test suites, test cases, and test runs. APIs support automated test management, test result reporting, and integration '
  name: Azure DevOps Test Plans API
  slug: azure-devops-test-plans-api
- description: The Azure DevOps Release API provides REST endpoints for managing release pipelines, deployments, and environments. APIs support release definition management, deployment approvals, environment config
  name: Azure DevOps Release API
  slug: azure-devops-release-api
asyncapis:
- description: Azure DevOps Service Hooks deliver event notifications for work item changes, build completions, pull request events, code pushes, and release deployments. Service hooks are configured in Azure DevOps
  name: Azure DevOps Service Hooks (Webhooks)
  slug: azure-devops-hooks-asyncapi
capabilities:
- description: Unified workflow for managing Azure DevOps projects combining work item tracking and CI/CD pipeline operations. Used by development teams, project managers, and DevOps engineers to plan work, track pr
  name: Azure DevOps Project Management
  slug: devops-project-management
common:
- title: ''
  type: Documentation
  url: https://azure.microsoft.com/en-us/products/devops
- title: ''
  type: Portal
  url: https://learn.microsoft.com/en-us/rest/api/azure/devops/
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/en-us/rest/api/azure/devops/?view=azure-devops-rest-7.2
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops
- title: ''
  type: RateLimits
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits?view=azure-devops
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/devops/dev-resources/?view=azure-devops
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoft
- title: Node.js SDK
  type: SDK
  url: https://github.com/microsoft/azure-devops-node-api
- title: Python SDK
  type: SDK
  url: https://github.com/microsoft/azure-devops-python-api
- title: Go SDK
  type: SDK
  url: https://github.com/microsoft/azure-devops-go-api
- title: Java SDK
  type: SDK
  url: https://github.com/microsoft/azure-devops-java-api
- title: Azure DevOps CLI Extension
  type: CLI
  url: https://github.com/Azure/azure-devops-cli-extension
- title: ''
  type: OpenAPI
  url: openapi/azure-devops-work-items-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/azure-devops-pipelines-openapi.yml
- title: Create Pipeline Request Schema
  type: JSONSchema
  url: json-schema/azure-devops-pipelines-create-pipeline-request-schema.json
- title: Pipelines Error Schema
  type: JSONSchema
  url: json-schema/azure-devops-pipelines-error-schema.json
- title: Pipeline Run Schema
  type: JSONSchema
  url: json-schema/azure-devops-pipelines-pipeline-run-schema.json
- title: Pipeline Schema
  type: JSONSchema
  url: json-schema/azure-devops-pipelines-pipeline-schema.json
- title: Run Pipeline Request Schema
  type: JSONSchema
  url: json-schema/azure-devops-pipelines-run-pipeline-request-schema.json
- title: Work Items Error Schema
  type: JSONSchema
  url: json-schema/azure-devops-work-items-error-schema.json
- title: JSON Patch Operation Schema
  type: JSONSchema
  url: json-schema/azure-devops-work-items-json-patch-operation-schema.json
- title: WIQL Result Schema
  type: JSONSchema
  url: json-schema/azure-devops-work-items-wiql-result-schema.json
- title: Work Item Field Schema
  type: JSONSchema
  url: json-schema/azure-devops-work-items-work-item-field-schema.json
- title: Work Item Relation Schema
  type: JSONSchema
  url: json-schema/azure-devops-work-items-work-item-relation-schema.json
- title: Work Item Schema
  type: JSONSchema
  url: json-schema/azure-devops-work-items-work-item-schema.json
- title: Work Item Schema (Legacy)
  type: JSONSchema
  url: json-schema/azure-devops-workitem-schema.json
- title: Azure DevOps JSON-LD Context
  type: JSONLD
  url: json-ld/azure-devops-context.jsonld
- title: Pipelines JSON-LD Context
  type: JSONLD
  url: json-ld/azure-devops-pipelines-context.jsonld
- title: Work Items JSON-LD Context
  type: JSONLD
  url: json-ld/azure-devops-work-items-context.jsonld
- title: Azure DevOps Vocabulary
  type: Vocabulary
  url: vocabulary/azure-devops-vocabulary.yaml
- title: Spectral Rules
  type: Rules
  url: rules/azure-devops-spectral-rules.yml
- title: DevOps Project Management Workflow
  type: Capabilities
  url: capabilities/devops-project-management.yaml
- title: Work Items Shared Capability
  type: Capabilities
  url: capabilities/shared/work-items.yaml
- title: Pipelines Shared Capability
  type: Capabilities
  url: capabilities/shared/pipelines.yaml
created: '2024-01-01'
description: Learn the basic patterns for using the REST APIs for Azure DevOps Services and Azure DevOps Server.
features:
- description: Create, update, query, and manage work items across Azure Boards
  name: Work Item Tracking
- description: Build, test, and deploy with YAML-based and classic pipelines
  name: CI/CD Pipelines
- description: Host and manage Git repositories with branch policies and pull requests
  name: Git Repositories
- description: Package management for NuGet, npm, Maven, Python, and Universal Packages
  name: Artifacts
- description: Comprehensive test management with automated and manual testing
  name: Test Plans
- description: Multi-stage deployment pipelines with approval workflows
  name: Release Management
image: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png
integrations:
- description: Import repositories and trigger pipelines from GitHub events
  name: GitHub
- description: Notifications for pipeline runs and work item updates
  name: Slack
- description: Bidirectional sync of work items with Jira issues
  name: Jira
jsonld:
- class_count: 0
  name: Azure Devops Context
  property_count: 4
  slug: azure-devops-context
- class_count: 0
  name: Azure Devops Pipelines Context
  property_count: 0
  slug: azure-devops-pipelines-context
- class_count: 0
  name: Azure Devops Work Items Context
  property_count: 0
  slug: azure-devops-work-items-context
layout: provider
modified: '2026-04-18'
name: Azure DevOps
rules:
- name: Azure DevOps API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: azure-devops-spectral-rules
skills: []
slug: azure-devops
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: azure-devops\nname: Azure DevOps\ndescription: >-\n  Learn the basic patterns for using the REST APIs for Azure DevOps Services and Azure\n  DevOps Server.\nurl: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/apis.yml\nimage: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png\ntags:\n  - Azure\n  - CI/CD\n  - DevOps\n  - Pipelines\n  - Work Items\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: azure-devops:azure-devops-work-item-tracking-api\n    name: Azure DevOps Work Item Tracking API\n    tags:\n      - Azure\n      - CI/CD\n      - DevOps\n      - Project Management\n      - Work Items\n    image: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    baseURL: https://dev.azure.com/{organization}\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/?view=azure-devops-rest-7.2\n\
  \        type: APIReference\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops\n        type: GettingStarted\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/openapi/azure-devops-work-items-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Azure DevOps Work Item Tracking API provides REST endpoints for creating,\n      updating, querying, and managing work items including bugs, tasks, user stories,\n      epics, and features across Azure Boards. APIs support custom fields, area paths,\n      iteration paths, and link types for Agile, Scrum, and CMMI process templates.\n\n  - aid: azure-devops:azure-devops-git-api\n    name: Azure DevOps Git Repositories API\n    tags:\n      - Azure\n      - CI/CD\n  \
  \    - DevOps\n      - Git\n      - Pull Requests\n      - Version Control\n    image: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    baseURL: https://dev.azure.com/{organization}\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-7.2\n        type: APIReference\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops\n        type: GettingStarted\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops\n        type: Authentication\n    description: >-\n      The Azure DevOps Git Repositories API provides REST endpoints for managing Git\n      repositories, branches, commits, pull requests, and code reviews. APIs enable\n      automation of repository management, pull request\
  \ workflows, branch policies,\n      and code review processes within Azure Repos.\n\n  - aid: azure-devops:azure-devops-pipelines-api\n    name: Azure DevOps Pipelines API\n    tags:\n      - Azure\n      - Build\n      - CI/CD\n      - DevOps\n      - Pipelines\n      - Release\n    image: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    baseURL: https://dev.azure.com/{organization}\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/?view=azure-devops-rest-7.2\n        type: APIReference\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops\n        type: GettingStarted\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/openapi/azure-devops-pipelines-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Azure DevOps Pipelines API provides REST endpoints for managing CI/CD build\n      and release pipelines. APIs support pipeline creation, triggering builds, retrieving\n      build results, managing release definitions, and automating deployment workflows\n      across Azure DevOps organizations.\n\n  - aid: azure-devops:azure-devops-artifacts-api\n    name: Azure DevOps Artifacts API\n    tags:\n      - Artifacts\n      - Azure\n      - CI/CD\n      - DevOps\n      - Npm\n      - NuGet\n      - Package Management\n    image: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    baseURL: https://pkgs.dev.azure.com/{organization}\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/artifacts/?view=azure-devops-rest-7.2\n        type: APIReference\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops\n\
  \        type: GettingStarted\n    description: >-\n      The Azure DevOps Artifacts API provides REST endpoints for managing package\n      feeds including NuGet, npm, Maven, Python, and Universal Packages. APIs support\n      feed creation, package publishing, version management, and upstream source configuration\n      for artifact management in DevOps workflows.\n\n  - aid: azure-devops:azure-devops-test-plans-api\n    name: Azure DevOps Test Plans API\n    tags:\n      - Azure\n      - CI/CD\n      - DevOps\n      - Test Plans\n      - Testing\n    image: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    baseURL: https://dev.azure.com/{organization}\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/?view=azure-devops-rest-7.2\n        type: APIReference\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops\n\
  \        type: GettingStarted\n    description: >-\n      The Azure DevOps Test Plans API provides REST endpoints for managing test plans,\n      test suites, test cases, and test runs. APIs support automated test management,\n      test result reporting, and integration with CI/CD pipelines for comprehensive\n      quality assurance workflows.\n\n  - aid: azure-devops:azure-devops-release-api\n    name: Azure DevOps Release API\n    tags:\n      - Azure\n      - CI/CD\n      - Deployment\n      - DevOps\n      - Release Management\n    image: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/image.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    baseURL: https://vsrm.dev.azure.com/{organization}\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/release/?view=azure-devops-rest-7.1\n        type: APIReference\n      - url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops\n\
  \        type: GettingStarted\n    description: >-\n      The Azure DevOps Release API provides REST endpoints for managing release pipelines,\n      deployments, and environments. APIs support release definition management, deployment\n      approvals, environment configuration, and release history tracking for continuous\n      delivery workflows.\n\ncommon:\n  - url: https://azure.microsoft.com/en-us/products/devops\n    type: Documentation\n  - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    type: Portal\n  - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/?view=azure-devops-rest-7.2\n    type: APIReference\n  - url: https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops\n    type: GettingStarted\n  - url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops\n    type: Authentication\n  - url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits?view=azure-devops\n\
  \    type: RateLimits\n  - url: https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released\n    type: ChangeLog\n  - url: https://learn.microsoft.com/en-us/azure/devops/dev-resources/?view=azure-devops\n    type: Documentation\n  - type: Features\n    data:\n      - name: Work Item Tracking\n        description: Create, update, query, and manage work items across Azure Boards\n      - name: CI/CD Pipelines\n        description: Build, test, and deploy with YAML-based and classic pipelines\n      - name: Git Repositories\n        description: Host and manage Git repositories with branch policies and pull requests\n      - name: Artifacts\n        description: Package management for NuGet, npm, Maven, Python, and Universal Packages\n      - name: Test Plans\n        description: Comprehensive test management with automated and manual testing\n      - name: Release Management\n        description: Multi-stage deployment pipelines with approval workflows\n  - type:\
  \ UseCases\n    data:\n      - name: Agile Project Management\n        description: Track work items, sprints, and backlogs for Agile development teams\n      - name: CI/CD Automation\n        description: Automate build, test, and deployment workflows across environments\n      - name: Code Review\n        description: Enforce branch policies and manage pull request workflows\n  - type: Integrations\n    data:\n      - name: GitHub\n        description: Import repositories and trigger pipelines from GitHub events\n      - name: Slack\n        description: Notifications for pipeline runs and work item updates\n      - name: Jira\n        description: Bidirectional sync of work items with Jira issues\n  - type: GitHubOrganization\n    url: https://github.com/microsoft\n  - type: SDK\n    url: https://github.com/microsoft/azure-devops-node-api\n    title: Node.js SDK\n  - type: SDK\n    url: https://github.com/microsoft/azure-devops-python-api\n    title: Python SDK\n  - type: SDK\n    url:\
  \ https://github.com/microsoft/azure-devops-go-api\n    title: Go SDK\n  - type: SDK\n    url: https://github.com/microsoft/azure-devops-java-api\n    title: Java SDK\n  - type: CLI\n    url: https://github.com/Azure/azure-devops-cli-extension\n    title: Azure DevOps CLI Extension\n  - type: OpenAPI\n    url: openapi/azure-devops-work-items-openapi.yml\n  - type: OpenAPI\n    url: openapi/azure-devops-pipelines-openapi.yml\n  - type: JSONSchema\n    url: json-schema/azure-devops-pipelines-create-pipeline-request-schema.json\n    title: Create Pipeline Request Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-pipelines-error-schema.json\n    title: Pipelines Error Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-pipelines-pipeline-run-schema.json\n    title: Pipeline Run Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-pipelines-pipeline-schema.json\n    title: Pipeline Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-pipelines-run-pipeline-request-schema.json\n\
  \    title: Run Pipeline Request Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-work-items-error-schema.json\n    title: Work Items Error Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-work-items-json-patch-operation-schema.json\n    title: JSON Patch Operation Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-work-items-wiql-result-schema.json\n    title: WIQL Result Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-work-items-work-item-field-schema.json\n    title: Work Item Field Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-work-items-work-item-relation-schema.json\n    title: Work Item Relation Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-work-items-work-item-schema.json\n    title: Work Item Schema\n  - type: JSONSchema\n    url: json-schema/azure-devops-workitem-schema.json\n    title: Work Item Schema (Legacy)\n  - type: JSONLD\n    url: json-ld/azure-devops-context.jsonld\n    title:\
  \ Azure DevOps JSON-LD Context\n  - type: JSONLD\n    url: json-ld/azure-devops-pipelines-context.jsonld\n    title: Pipelines JSON-LD Context\n  - type: JSONLD\n    url: json-ld/azure-devops-work-items-context.jsonld\n    title: Work Items JSON-LD Context\n  - type: Vocabulary\n    url: vocabulary/azure-devops-vocabulary.yaml\n    title: Azure DevOps Vocabulary\n  - type: Rules\n    url: rules/azure-devops-spectral-rules.yml\n    title: Spectral Rules\n  - type: Capabilities\n    url: capabilities/devops-project-management.yaml\n    title: DevOps Project Management Workflow\n  - type: Capabilities\n    url: capabilities/shared/work-items.yaml\n    title: Work Items Shared Capability\n  - type: Capabilities\n    url: capabilities/shared/pipelines.yaml\n    title: Pipelines Shared Capability\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/apis.yml
tags:
- Azure
- CI/CD
- DevOps
- Pipelines
- Work Items
url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/apis.yml
use_cases:
- description: Track work items, sprints, and backlogs for Agile development teams
  name: Agile Project Management
- description: Automate build, test, and deployment workflows across environments
  name: CI/CD Automation
- description: Enforce branch policies and manage pull request workflows
  name: Code Review
---
