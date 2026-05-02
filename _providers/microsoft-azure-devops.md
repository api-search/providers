---
api_count: 40
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Azure DevOps Services REST API
  slug: ''
  spec_type: OpenAPI
  url: https://learn.microsoft.com/en-us/rest/api/azure/devops/
- filename: azure-devops-work-items-api-openapi.yml
  format: yaml
  label: Azure DevOps Boards API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-work-items-api-openapi.yml
- filename: azure-devops-git-api-openapi.yml
  format: yaml
  label: Azure DevOps Repos API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-git-api-openapi.yml
- filename: azure-devops-pipelines-api-openapi.yml
  format: yaml
  label: Azure DevOps Pipelines API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-pipelines-api-openapi.yml
- filename: azure-devops-builds-api-openapi.yml
  format: yaml
  label: Azure DevOps Build API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-builds-api-openapi.yml
- filename: azure-devops-releases-api-openapi.yml
  format: yaml
  label: Azure DevOps Release API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-releases-api-openapi.yml
- filename: azure-devops-test-plans-api-openapi.yml
  format: yaml
  label: Azure DevOps Test Plans API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-test-plans-api-openapi.yml
- filename: azure-devops-artifacts-api-openapi.yml
  format: yaml
  label: Azure DevOps Artifacts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-artifacts-api-openapi.yml
- filename: azure-devops-service-hooks-api-openapi.yml
  format: yaml
  label: Azure DevOps Service Hooks API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-service-hooks-api-openapi.yml
- filename: azure-devops-wiki-api-openapi.yml
  format: yaml
  label: Azure DevOps Wiki API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-wiki-api-openapi.yml
apis:
- description: REST API for Azure DevOps Services providing programmatic access to work items, builds, releases, repositories, and more.
  name: Azure DevOps Services REST API
  slug: ''
- description: API for managing work items, boards, backlogs, sprints, and queries in Azure Boards. Enables programmatic access to agile planning and tracking resources.
  name: Azure DevOps Boards API
  slug: ''
- description: API for managing Git repositories, pull requests, commits, branches, and pushes in Azure Repos. Supports full programmatic control over source code hosted in Azure DevOps.
  name: Azure DevOps Repos API
  slug: ''
- description: API for managing build and release pipelines, pipeline runs, and pipeline artifacts. Provides programmatic access to create, trigger, and monitor CI/CD pipelines.
  name: Azure DevOps Pipelines API
  slug: ''
- description: API for managing build definitions, queuing builds, and accessing build results and logs. Supports the full lifecycle of continuous integration builds in Azure DevOps.
  name: Azure DevOps Build API
  slug: ''
- description: API for managing release definitions, deployments, and approvals in Azure Pipelines. Enables programmatic control over continuous delivery and release orchestration.
  name: Azure DevOps Release API
  slug: ''
- description: API for managing test plans, test suites, test cases, and test runs in Azure Test Plans. Provides programmatic access to quality assurance and testing workflows.
  name: Azure DevOps Test Plans API
  slug: ''
- description: API for managing packages, feeds, and artifact dependencies in Azure Artifacts. Supports NuGet, npm, Maven, Python, and Universal packages in private or public feeds.
  name: Azure DevOps Artifacts API
  slug: ''
- description: API for managing users, groups, and memberships within an Azure DevOps organization. Enables programmatic administration of identities and group membership.
  name: Azure DevOps Graph API
  slug: ''
- description: API for managing Azure DevOps projects, teams, and team members. Provides foundational access to the organizational structure of an Azure DevOps organization.
  name: Azure DevOps Core API
  slug: ''
- description: API for managing security namespaces, access control lists, and access control entries in Azure DevOps. Used to programmatically set and evaluate permissions on resources.
  name: Azure DevOps Security API
  slug: ''
- description: API for managing service hook subscriptions, publishers, and consumers. Enables event-driven integrations by configuring webhooks and other notification mechanisms when Azure DevOps events occur.
  name: Azure DevOps Service Hooks API
  slug: ''
- description: API for managing notification subscriptions for users and teams. Enables programmatic creation and management of email and other notification channels for Azure DevOps events such as work item changes
  name: Azure DevOps Notifications API
  slug: ''
- description: API for querying and downloading the Azure DevOps audit log. Provides access to auditable events within an organization for security reviews and compliance reporting.
  name: Azure DevOps Audit API
  slug: ''
- description: API for searching code, work items, and wiki pages across all projects and repositories within an Azure DevOps organization. Supports full-text and filtered search results.
  name: Azure DevOps Search API
  slug: ''
- description: API for managing code policy configurations and policy types in Azure Repos. Used to define and enforce branch policies such as required reviewers, status checks, and merge strategies.
  name: Azure DevOps Policy API
  slug: ''
- description: API for managing the pipeline agent infrastructure including agent pools, queues, agents, environments, deployment groups, and task groups. Provides programmatic control over the compute resources use
  name: Azure DevOps Distributed Task API
  slug: ''
- description: OData-based API providing access to the Azure DevOps Analytics service for reporting and querying historical and real-time project data. Supports queries across work items, pipelines, and test plans f
  name: Azure DevOps Analytics OData API
  slug: ''
- description: API for creating and managing wikis and wiki pages within Azure DevOps projects. Every wiki is backed by a Git repository and supports creating, reading, updating, and deleting wikis and pages program
  name: Azure DevOps Wiki API
  slug: ''
- description: API for managing extensions installed in an Azure DevOps organization. Enables programmatic listing, installing, updating, and removing of Marketplace extensions, as well as reading extension data and
  name: Azure DevOps Extension Management API
  slug: ''
- description: API for managing service connections that connect Azure DevOps pipelines to external services such as GitHub, Docker, Azure, and other third-party providers. Supports creating, updating, and sharing s
  name: Azure DevOps Service Endpoint API
  slug: ''
- description: API for accessing Team Foundation Version Control (TFVC) repositories within Azure DevOps. Provides programmatic access to TFVC items, changesets, shelvesets, labels, and branches for organizations us
  name: Azure DevOps TFVC API
  slug: ''
- description: API for organization administrators to retrieve and revoke OAuth authorizations including personal access tokens and session tokens for users in their organizations. Enables centralized token governan
  name: Azure DevOps Token Administration API
  slug: ''
- description: API for listing the Azure DevOps organizations that the authenticated user has access to. Each person using Azure DevOps Services has access to one or more organization accounts.
  name: Azure DevOps Accounts API
  slug: ''
- description: API for managing pipeline approvals and checks on resources such as environments, service connections, agent pools, variable groups, and secure files. Enables programmatic creation and modification of
  name: Azure DevOps Approvals and Checks API
  slug: ''
- description: API for managing specific package types within Azure Artifacts feeds including NuGet, npm, Maven, Python, and Universal Packages. Provides package-type-specific operations beyond the general Artifacts
  name: Azure DevOps Artifacts Package Types API
  slug: ''
- description: API for creating and managing team dashboards and widgets in Azure DevOps. Each team can have one or more dashboards, and each dashboard contains a set of configurable widgets with multi-user concurre
  name: Azure DevOps Dashboard API
  slug: ''
- description: API for managing user favorites in Azure DevOps. Enables programmatic creation, retrieval, and deletion of favorite items such as queries, builds, repositories, and other artifacts scoped to individua
  name: Azure DevOps Favorites API
  slug: ''
- description: API for finding legacy identity descriptors for users and groups in Azure DevOps. Identities can be searched by name, email, ID, identity descriptor, and subject descriptor. Legacy identity descriptor
  name: Azure DevOps Identities API
  slug: ''
- description: API for managing member entitlements in Azure DevOps organizations. A member is a user or group added to an account. Enables programmatic management of licenses, extensions, and project or team member
  name: Azure DevOps Member Entitlement Management API
  slug: ''
- description: API for generating and downloading permissions reports that help administrators determine the effective permissions of users and groups on securable resources in Azure DevOps. Reports list effective p
  name: Azure DevOps Permissions Report API
  slug: ''
- description: API for retrieving the authenticated user's profile information in Azure DevOps. Each person using Azure DevOps Services has a profile containing their identity and preference data.
  name: Azure DevOps Profile API
  slug: ''
- description: API for managing security role definitions and role assignments on Azure DevOps resources. Enables listing role definitions, assigning roles to identities on specific resources, removing role assignme
  name: Azure DevOps Security Roles API
  slug: ''
- description: API for querying the health and status of Azure DevOps services. Provides the ability to query status information for Azure DevOps all-up, or scoped to a specific service and geography. Results are ca
  name: Azure DevOps Status API
  slug: ''
- description: API for working with the Azure DevOps managed Symbol Service. Supports creating and managing symbol requests, updating debug entries, querying symbols via the Microsoft SymSrv protocol, and checking s
  name: Azure DevOps Symbol API
  slug: ''
- description: API for managing modern test plans, test suites, test cases, test points, and test configurations in Azure DevOps. Provides programmatic access to test plan management operations including cloning, re
  name: Azure DevOps Test Plan API
  slug: ''
- description: API for managing test results, code coverage data, test run logs, and test result metrics in Azure DevOps. Supports publishing test result documents, querying results by build or pipeline, and retriev
  name: Azure DevOps Test Results API
  slug: ''
- description: 'API for users to manage the lifecycle of their own personal access tokens (PATs) in Azure DevOps. Supports creating, listing, updating, and revoking PATs programmatically. Requires authorization with '
  name: Azure DevOps Token Lifecycle Management API
  slug: ''
- description: 'API for managing board configurations, team settings, iterations, capacities, and process configuration in Azure Boards. Provides programmatic access to board columns, rows, card styling rules, chart '
  name: Azure DevOps Work API
  slug: ''
- description: API for managing work item tracking process customizations in Azure DevOps. Enables programmatic management of inherited processes, work item types, fields, states, rules, behaviors, layouts, and pick
  name: Azure DevOps Work Item Tracking Process API
  slug: ''
asyncapis:
- description: AsyncAPI specification for Azure DevOps Service Hooks (webhooks and event subscriptions). Azure DevOps delivers event notifications via HTTP POST requests to subscriber endpoints when events occur suc
  name: Azure DevOps Service Hooks AsyncAPI
  slug: azure-devops-service-hooks-asyncapi
common:
- title: ''
  type: Portal
  url: https://dev.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/devops/?view=azure-devops
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance
- title: ''
  type: Client Libraries
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops
- title: ''
  type: Rate Limits
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits
- title: ''
  type: Status
  url: https://status.dev.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/devops/
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
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/services/devops/
- title: ''
  type: Community
  url: https://developercommunity.visualstudio.com/AzureDevOps
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-devops
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/azure/devops/release-notes/
- title: ''
  type: Marketplace
  url: https://marketplace.visualstudio.com/azuredevops
- title: ''
  type: Extensions
  url: https://learn.microsoft.com/en-us/azure/devops/extend/overview?view=azure-devops
- title: ''
  type: CLI
  url: https://learn.microsoft.com/en-us/azure/devops/cli/?view=azure-devops
- title: ''
  type: Versioning
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rest-api-versioning?view=azure-devops
- title: ''
  type: Samples
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/rest/samples?view=azure-devops
- title: ''
  type: Best Practices
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/integration-bestpractices?view=azure-devops
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoft
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoft/azure-devops-python-api
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoft/azure-devops-node-api
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoft/azure-devops-extension-sdk
- title: ''
  type: JSONSchema
  url: json-schema/azure-devops-work-item-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/azure-devops-pipeline-run-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/azure-devops-context.jsonld
created: '2024-01-01'
description: Azure DevOps provides developer services for support teams to plan work, collaborate on code development, and build and deploy applications.
features: []
image: https://azure.microsoft.com/svghandler/devops/
integrations: []
jsonld:
- class_count: 0
  name: Azure Devops Context
  property_count: 15
  slug: azure-devops-context
layout: provider
modified: '2026-04-28'
name: Azure DevOps
skills: []
slug: microsoft-azure-devops
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure DevOps\ndescription: Azure DevOps provides developer services for support teams to plan work, collaborate on code development, and build and deploy applications.\nimage: https://azure.microsoft.com/svghandler/devops/\ntags:\n  - Agile\n  - CI/CD\n  - DevOps\n  - Project Management\n  - Version Control\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: https://dev.azure.com\nspecificationVersion: '0.18'\napis:\n  - name: Azure DevOps Services REST API\n    description: REST API for Azure DevOps Services providing programmatic access to work items, builds, releases, repositories, and more.\n    image: https://azure.microsoft.com/svghandler/devops/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n    baseURL: https://dev.azure.com/{organization}\n    tags:\n      - DevOps\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n      - type: OpenAPI\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\n      - type: Client Libraries\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/devops/\n  - name: Azure DevOps Boards API\n    description: API for managing work items, boards, backlogs, sprints, and queries in Azure Boards. Enables programmatic access to agile planning and tracking resources.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/wit\n    tags:\n      - Agile\n      - Boards\n      - Work Items\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/\n      - type: OpenAPI\n        url: openapi/azure-devops-work-items-api-openapi.yml\n\
  \  - name: Azure DevOps Repos API\n    description: API for managing Git repositories, pull requests, commits, branches, and pushes in Azure Repos. Supports full programmatic control over source code hosted in Azure DevOps.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/git/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/git\n    tags:\n      - Git\n      - Repositories\n      - Source Control\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/git/\n      - type: OpenAPI\n        url: openapi/azure-devops-git-api-openapi.yml\n  - name: Azure DevOps Pipelines API\n    description: API for managing build and release pipelines, pipeline runs, and pipeline artifacts. Provides programmatic access to create, trigger, and monitor CI/CD pipelines.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/pipelines\n\
  \    tags:\n      - Builds\n      - CI/CD\n      - Releases\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/\n      - type: OpenAPI\n        url: openapi/azure-devops-pipelines-api-openapi.yml\n  - name: Azure DevOps Build API\n    description: API for managing build definitions, queuing builds, and accessing build results and logs. Supports the full lifecycle of continuous integration builds in Azure DevOps.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/build/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/build\n    tags:\n      - Automation\n      - Build\n      - CI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/build/\n      - type: OpenAPI\n        url: openapi/azure-devops-builds-api-openapi.yml\n  - name: Azure DevOps Release API\n    description: API for managing release definitions, deployments,\
  \ and approvals in Azure Pipelines. Enables programmatic control over continuous delivery and release orchestration.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/release/\n    baseURL: https://vsrm.dev.azure.com/{organization}/{project}/_apis/release\n    tags:\n      - CD\n      - Deployment\n      - Release\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/release/\n      - type: OpenAPI\n        url: openapi/azure-devops-releases-api-openapi.yml\n  - name: Azure DevOps Test Plans API\n    description: API for managing test plans, test suites, test cases, and test runs in Azure Test Plans. Provides programmatic access to quality assurance and testing workflows.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/test/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/test\n    tags:\n      - QA\n      - Test Plans\n      - Testing\n    properties:\n      - type:\
  \ Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/test/\n      - type: OpenAPI\n        url: openapi/azure-devops-test-plans-api-openapi.yml\n  - name: Azure DevOps Artifacts API\n    description: API for managing packages, feeds, and artifact dependencies in Azure Artifacts. Supports NuGet, npm, Maven, Python, and Universal packages in private or public feeds.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/artifacts/\n    baseURL: https://feeds.dev.azure.com/{organization}/_apis/packaging\n    tags:\n      - Artifacts\n      - Dependencies\n      - Packages\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/artifacts/\n      - type: OpenAPI\n        url: openapi/azure-devops-artifacts-api-openapi.yml\n  - name: Azure DevOps Graph API\n    description: API for managing users, groups, and memberships within an Azure DevOps organization. Enables programmatic administration\
  \ of identities and group membership.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/graph/\n    baseURL: https://vssps.dev.azure.com/{organization}/_apis/graph\n    tags:\n      - Groups\n      - Permissions\n      - Users\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/graph/\n  - name: Azure DevOps Core API\n    description: API for managing Azure DevOps projects, teams, and team members. Provides foundational access to the organizational structure of an Azure DevOps organization.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/core/\n    baseURL: https://dev.azure.com/{organization}/_apis\n    tags:\n      - Organization\n      - Projects\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/core/\n  - name: Azure DevOps Security API\n    description: API for managing security namespaces, access\
  \ control lists, and access control entries in Azure DevOps. Used to programmatically set and evaluate permissions on resources.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/security/\n    baseURL: https://dev.azure.com/{organization}/_apis/accesscontrollists\n    tags:\n      - Access Control\n      - Permissions\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/security/\n  - name: Azure DevOps Service Hooks API\n    description: API for managing service hook subscriptions, publishers, and consumers. Enables event-driven integrations by configuring webhooks and other notification mechanisms when Azure DevOps events occur.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/hooks/\n    baseURL: https://dev.azure.com/{organization}/_apis/hooks\n    tags:\n      - Events\n      - Integrations\n      - Webhooks\n    properties:\n      - type: Documentation\n  \
  \      url: https://learn.microsoft.com/en-us/rest/api/azure/devops/hooks/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/devops/service-hooks/overview?view=azure-devops\n      - type: OpenAPI\n        url: openapi/azure-devops-service-hooks-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/azure-devops-service-hooks-asyncapi.yml\n  - name: Azure DevOps Notifications API\n    description: API for managing notification subscriptions for users and teams. Enables programmatic creation and management of email and other notification channels for Azure DevOps events such as work item changes, build results, and pull requests.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/notification/\n    baseURL: https://dev.azure.com/{organization}/_apis/notification\n    tags:\n      - Alerts\n      - Notifications\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/notification/\n\
  \  - name: Azure DevOps Audit API\n    description: API for querying and downloading the Azure DevOps audit log. Provides access to auditable events within an organization for security reviews and compliance reporting.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/audit/\n    baseURL: https://auditservice.dev.azure.com/{organization}/_apis/audit\n    tags:\n      - Audit\n      - Compliance\n      - Security\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/audit/\n  - name: Azure DevOps Search API\n    description: API for searching code, work items, and wiki pages across all projects and repositories within an Azure DevOps organization. Supports full-text and filtered search results.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/search/\n    baseURL: https://almsearch.dev.azure.com/{organization}/_apis/search\n    tags:\n      - Code\n      - Search\n      - Work Items\n\
  \    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/search/\n  - name: Azure DevOps Policy API\n    description: API for managing code policy configurations and policy types in Azure Repos. Used to define and enforce branch policies such as required reviewers, status checks, and merge strategies.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/policy/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/policy\n    tags:\n      - Branch Protection\n      - Code Review\n      - Policy\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/policy/\n  - name: Azure DevOps Distributed Task API\n    description: API for managing the pipeline agent infrastructure including agent pools, queues, agents, environments, deployment groups, and task groups. Provides programmatic control over the compute resources used to run pipelines.\n \
  \   humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/distributedtask/\n    baseURL: https://dev.azure.com/{organization}/_apis/distributedtask\n    tags:\n      - Agents\n      - Pipelines\n      - Pools\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/distributedtask/\n  - name: Azure DevOps Analytics OData API\n    description: OData-based API providing access to the Azure DevOps Analytics service for reporting and querying historical and real-time project data. Supports queries across work items, pipelines, and test plans for Power BI and custom reporting scenarios.\n    humanURL: https://learn.microsoft.com/en-us/azure/devops/report/extend-analytics/quick-ref?view=azure-devops\n    baseURL: https://analytics.dev.azure.com/{organization}/{project}/_odata\n    tags:\n      - Analytics\n      - OData\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/devops/report/extend-analytics/quick-ref?view=azure-devops\n\
  \      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/devops/report/extend-analytics/odata-api-version?view=azure-devops\n  - name: Azure DevOps Wiki API\n    description: API for creating and managing wikis and wiki pages within Azure DevOps projects. Every wiki is backed by a Git repository and supports creating, reading, updating, and deleting wikis and pages programmatically.\n    image: https://azure.microsoft.com/svghandler/devops/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/wiki/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/wiki\n    tags:\n      - Documentation\n      - Pages\n      - Wiki\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/wiki/\n      - type: OpenAPI\n        url: openapi/azure-devops-wiki-api-openapi.yml\n  - name: Azure DevOps Extension Management API\n    description: API for managing extensions installed in an Azure DevOps\
  \ organization. Enables programmatic listing, installing, updating, and removing of Marketplace extensions, as well as reading extension data and settings.\n    image: https://azure.microsoft.com/svghandler/devops/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/extensionmanagement/\n    baseURL: https://extmgmt.dev.azure.com/{organization}/_apis/extensionmanagement\n    tags:\n      - Extensions\n      - Marketplace\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/extensionmanagement/\n  - name: Azure DevOps Service Endpoint API\n    description: API for managing service connections that connect Azure DevOps pipelines to external services such as GitHub, Docker, Azure, and other third-party providers. Supports creating, updating, and sharing service endpoints across projects.\n    image: https://azure.microsoft.com/svghandler/devops/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/\n\
  \    baseURL: https://dev.azure.com/{organization}/{project}/_apis/serviceendpoint\n    tags:\n      - Integrations\n      - Pipelines\n      - Service Connections\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/serviceendpoint/\n  - name: Azure DevOps TFVC API\n    description: API for accessing Team Foundation Version Control (TFVC) repositories within Azure DevOps. Provides programmatic access to TFVC items, changesets, shelvesets, labels, and branches for organizations using centralized version control.\n    image: https://azure.microsoft.com/svghandler/devops/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/tfvc/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/tfvc\n    tags:\n      - Source Control\n      - TFVC\n      - Version Control\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/tfvc/\n  - name: Azure\
  \ DevOps Token Administration API\n    description: API for organization administrators to retrieve and revoke OAuth authorizations including personal access tokens and session tokens for users in their organizations. Enables centralized token governance and security oversight.\n    image: https://azure.microsoft.com/svghandler/devops/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/tokenadmin/\n    baseURL: https://vssps.dev.azure.com/{organization}/_apis/tokenadmin\n    tags:\n      - Access Control\n      - Security\n      - Token Administration\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/tokenadmin/\n  - name: Azure DevOps Accounts API\n    description: API for listing the Azure DevOps organizations that the authenticated user has access to. Each person using Azure DevOps Services has access to one or more organization accounts.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/account/\n\
  \    baseURL: https://app.vssps.visualstudio.com/_apis/accounts\n    tags:\n      - Accounts\n      - Administration\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/account/\n  - name: Azure DevOps Approvals and Checks API\n    description: API for managing pipeline approvals and checks on resources such as environments, service connections, agent pools, variable groups, and secure files. Enables programmatic creation and modification of checks, management of approvals, and querying of check evaluation details.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/pipelines/checks\n    tags:\n      - Approvals\n      - Checks\n      - Pipelines\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/\n  - name: Azure\
  \ DevOps Artifacts Package Types API\n    description: API for managing specific package types within Azure Artifacts feeds including NuGet, npm, Maven, Python, and Universal Packages. Provides package-type-specific operations beyond the general Artifacts feed management API.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/artifactspackagetypes/\n    baseURL: https://pkgs.dev.azure.com/{organization}/_apis/packaging\n    tags:\n      - Maven\n      - Npm\n      - NuGet\n      - Packages\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/artifactspackagetypes/\n  - name: Azure DevOps Dashboard API\n    description: API for creating and managing team dashboards and widgets in Azure DevOps. Each team can have one or more dashboards, and each dashboard contains a set of configurable widgets with multi-user concurrency support via eTag versioning.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/dashboard/\n\
  \    baseURL: https://dev.azure.com/{organization}/{project}/{team}/_apis/dashboard\n    tags:\n      - Dashboards\n      - Reporting\n      - Widgets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/dashboard/\n  - name: Azure DevOps Favorites API\n    description: API for managing user favorites in Azure DevOps. Enables programmatic creation, retrieval, and deletion of favorite items such as queries, builds, repositories, and other artifacts scoped to individual users or teams.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/favorite/\n    baseURL: https://dev.azure.com/{organization}/_apis/favorite\n    tags:\n      - Bookmarks\n      - Favorites\n      - User Preferences\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/favorite/\n  - name: Azure DevOps Identities API\n    description: API for finding legacy identity descriptors\
  \ for users and groups in Azure DevOps. Identities can be searched by name, email, ID, identity descriptor, and subject descriptor. Legacy identity descriptors are used by systems that rely on the identity management service, such as the security APIs for permissions management.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/ims/\n    baseURL: https://vssps.dev.azure.com/{organization}/_apis/identities\n    tags:\n      - Groups\n      - Identities\n      - Users\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/ims/\n  - name: Azure DevOps Member Entitlement Management API\n    description: API for managing member entitlements in Azure DevOps organizations. A member is a user or group added to an account. Enables programmatic management of licenses, extensions, and project or team memberships for users and groups.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/memberentitlementmanagement/\n\
  \    baseURL: https://vsaex.dev.azure.com/{organization}/_apis/userentitlements\n    tags:\n      - Entitlements\n      - Licensing\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/memberentitlementmanagement/\n  - name: Azure DevOps Permissions Report API\n    description: API for generating and downloading permissions reports that help administrators determine the effective permissions of users and groups on securable resources in Azure DevOps. Reports list effective permissions for each user and group in the organization, accounting for directly assigned, group hierarchy inherited, and resource hierarchy inherited permissions.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/permissionsreport/\n    baseURL: https://dev.azure.com/{organization}/_apis/permissionsreport\n    tags:\n      - Compliance\n      - Permissions\n      - Reports\n    properties:\n      - type: Documentation\n\
  \        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/permissionsreport/\n  - name: Azure DevOps Profile API\n    description: API for retrieving the authenticated user's profile information in Azure DevOps. Each person using Azure DevOps Services has a profile containing their identity and preference data.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/profile/\n    baseURL: https://app.vssps.visualstudio.com/_apis/profile/profiles\n    tags:\n      - Identity\n      - Profile\n      - Users\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/profile/\n  - name: Azure DevOps Security Roles API\n    description: API for managing security role definitions and role assignments on Azure DevOps resources. Enables listing role definitions, assigning roles to identities on specific resources, removing role assignments, and managing permission inheritance.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/securityroles/\n\
  \    baseURL: https://dev.azure.com/{organization}/_apis/securityroles\n    tags:\n      - Access Control\n      - Role Assignments\n      - Security Roles\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/securityroles/\n  - name: Azure DevOps Status API\n    description: API for querying the health and status of Azure DevOps services. Provides the ability to query status information for Azure DevOps all-up, or scoped to a specific service and geography. Results are cached for 60 seconds.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/status/\n    baseURL: https://status.dev.azure.com/_apis/status\n    tags:\n      - Health\n      - Monitoring\n      - Status\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/status/\n  - name: Azure DevOps Symbol API\n    description: API for working with the Azure DevOps managed Symbol Service. Supports\
  \ creating and managing symbol requests, updating debug entries, querying symbols via the Microsoft SymSrv protocol, and checking service availability. Used to publish and consume debug symbols for builds.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/symbol/\n    baseURL: https://artifacts.dev.azure.com/{organization}/_apis/symbol\n    tags:\n      - Artifacts\n      - Debugging\n      - Symbols\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/symbol/\n  - name: Azure DevOps Test Plan API\n    description: API for managing modern test plans, test suites, test cases, test points, and test configurations in Azure DevOps. Provides programmatic access to test plan management operations including cloning, recycle bin operations, and test suite organization.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/testplan\n\
  \    tags:\n      - Test Cases\n      - Test Plans\n      - Test Suites\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/\n  - name: Azure DevOps Test Results API\n    description: API for managing test results, code coverage data, test run logs, and test result metrics in Azure DevOps. Supports publishing test result documents, querying results by build or pipeline, and retrieving detailed test result group information.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/testresults/\n    baseURL: https://vstmr.dev.azure.com/{organization}/{project}/_apis/testresults\n    tags:\n      - Code Coverage\n      - Test Results\n      - Test Runs\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/testresults/\n  - name: Azure DevOps Token Lifecycle Management API\n    description: API for users to manage the lifecycle of their own personal\
  \ access tokens (PATs) in Azure DevOps. Supports creating, listing, updating, and revoking PATs programmatically. Requires authorization with Microsoft Entra ID access tokens.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/tokens/\n    baseURL: https://vssps.dev.azure.com/{organization}/_apis/tokens\n    tags:\n      - Authentication\n      - Personal Access Tokens\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/tokens/\n  - name: Azure DevOps Work API\n    description: API for managing board configurations, team settings, iterations, capacities, and process configuration in Azure Boards. Provides programmatic access to board columns, rows, card styling rules, chart settings, team field values, backlog settings, and sprint capacity planning.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/work/\n    baseURL: https://dev.azure.com/{organization}/{project}/{team}/_apis/work\n\
  \    tags:\n      - Boards\n      - Capacity\n      - Sprints\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/work/\n  - name: Azure DevOps Work Item Tracking Process API\n    description: API for managing work item tracking process customizations in Azure DevOps. Enables programmatic management of inherited processes, work item types, fields, states, rules, behaviors, layouts, and picklist values for customizing Azure Boards experiences.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/processes/\n    baseURL: https://dev.azure.com/{organization}/_apis/work/processes\n    tags:\n      - Customization\n      - Processes\n      - Work Item Types\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/processes/\ncommon:\n  - type: Portal\n    url: https://dev.azure.com\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/devops/?view=azure-devops\n\
  \  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\n  - type: Client Libraries\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops\n  - type: Rate Limits\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits\n  - type: Status\n    url: https://status.dev.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/devops/\n  - type: Blog\n    url: https://devblogs.microsoft.com/devops/\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/\n  - type: Sign Up\n\
  \    url: https://azure.microsoft.com/en-us/services/devops/\n  - type: Community\n    url: https://developercommunity.visualstudio.com/AzureDevOps\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-devops\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/azure/devops/release-notes/\n  - type: Marketplace\n    url: https://marketplace.visualstudio.com/azuredevops\n  - type: Extensions\n    url: https://learn.microsoft.com/en-us/azure/devops/extend/overview?view=azure-devops\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/azure/devops/cli/?view=azure-devops\n  - type: Versioning\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rest-api-versioning?view=azure-devops\n  - type: Samples\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/rest/samples?view=azure-devops\n  - type: Best Practices\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/integration-bestpractices?view=azure-devops\n\
  \  - type: GitHub Organization\n    url: https://github.com/microsoft\n  - type: GitHubRepository\n    url: https://github.com/microsoft/azure-devops-python-api\n  - type: GitHubRepository\n    url: https://github.com/microsoft/azure-devops-node-api\n  - type: GitHubRepository\n    url: https://github.com/microsoft/azure-devops-extension-sdk\n  - type: JSONSchema\n    url: json-schema/azure-devops-work-item-schema.json\n  - type: JSONSchema\n    url: json-schema/azure-devops-pipeline-run-schema.json\n  - type: JSON-LD\n    url: json-ld/azure-devops-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/apis.yml
tags:
- Agile
- CI/CD
- DevOps
- Project Management
- Version Control
url: https://dev.azure.com
use_cases: []
---
