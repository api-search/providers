---
api_count: 13
api_specs:
- filename: postman-webhooks-asyncapi.yml
  format: yaml
  label: Postman
  slug: postman
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/asyncapi/postman-webhooks-asyncapi.yml
- filename: postman-collections-api-openapi.yml
  format: yaml
  label: Postman Collections API
  slug: collections-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-collections-api-openapi.yml
- filename: postman-workspaces-api-openapi.yml
  format: yaml
  label: Postman Workspaces API
  slug: workspaces-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-workspaces-api-openapi.yml
- filename: postman-environments-api-openapi.yml
  format: yaml
  label: Postman Environments API
  slug: environments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-environments-api-openapi.yml
- filename: postman-mock-servers-api-openapi.yml
  format: yaml
  label: Postman Mock Servers API
  slug: mock-servers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-mock-servers-api-openapi.yml
- filename: postman-monitors-api-openapi.yml
  format: yaml
  label: Postman Monitors API
  slug: monitors-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-monitors-api-openapi.yml
- filename: postman-apis-api-openapi.yml
  format: yaml
  label: Postman APIs API
  slug: apis-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-apis-api-openapi.yml
- filename: postman-private-api-network-api-openapi.yml
  format: yaml
  label: Postman Private API Network API
  slug: private-api-network-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-private-api-network-api-openapi.yml
- filename: postman-webhooks-api-openapi.yml
  format: yaml
  label: Postman Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-webhooks-api-openapi.yml
- filename: postman-collection-runs-api-openapi.yml
  format: yaml
  label: Postman Collection Runs API
  slug: collection-runs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-collection-runs-api-openapi.yml
- filename: postman-tags-api-openapi.yml
  format: yaml
  label: Postman Tags API
  slug: tags-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-tags-api-openapi.yml
- filename: postman-audit-logs-api-openapi.yml
  format: yaml
  label: Postman Audit Logs API
  slug: audit-logs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-audit-logs-api-openapi.yml
- filename: postman-secret-scanner-api-openapi.yml
  format: yaml
  label: Postman Secret Scanner API
  slug: secret-scanner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/openapi/postman-secret-scanner-api-openapi.yml
apis:
- description: Postman is your single platform for collaborative API development. Join 35+ million devs building great APIs together, across the entire API lifecycle.
  name: Postman
  slug: postman
- description: Use the Collections APIs to manage your Postman collections and simplify collection-related workflows, with endpoints to add, delete, or update your collections.
  name: Postman Collections API
  slug: collections-api
- description: Use the Workspaces APIs to manage your Postman workspaces, with endpoints that enable you to create, update, and delete workspaces programmatically.
  name: Postman Workspaces API
  slug: workspaces-api
- description: The Environments API enables you to programmatically manage your Postman environments and global variables, scoping your work to different environments.
  name: Postman Environments API
  slug: environments-api
- description: The Mock Servers API enables you to perform CRUD operations on mock servers and manage mock server responses for simulating API behavior during development.
  name: Postman Mock Servers API
  slug: mock-servers-api
- description: The Monitors API enables you to programmatically run collections on a schedule, manage webhooks, and access metrics for API monitoring instances.
  name: Postman Monitors API
  slug: monitors-api
- description: Use the APIs endpoints to manage your API definitions in Postman, including creating, updating, and managing API versions and specifications.
  name: Postman APIs API
  slug: apis-api
- description: The Private API Network API enables you to programmatically manage your private API network, automate management of internal documentation, and integrate with CI/CD pipelines.
  name: Postman Private API Network API
  slug: private-api-network-api
- description: The Webhooks API enables you to create webhooks that trigger collection runs with custom payloads. Webhooks provide a way to integrate Postman with external systems and automate workflows based on inc
  name: Postman Webhooks API
  slug: webhooks-api
- description: The Collection Runs API enables you to programmatically run collections, schedule runs, and retrieve results for continuous integration and delivery pipelines.
  name: Postman Collection Runs API
  slug: collection-runs-api
- description: The Tags API enables you to manage tags on APIs, collections, and workspaces for governance and organization. Tags help categorize and discover API assets across your team.
  name: Postman Tags API
  slug: tags-api
- description: The Audit Logs API provides access to team audit logs for compliance and governance. Track user actions, configuration changes, and security events across your Postman organization.
  name: Postman Audit Logs API
  slug: audit-logs-api
- description: The Secret Scanner API enables you to manage detected secrets and resolve leaked credentials found in your Postman collections, environments, and other API assets.
  name: Postman Secret Scanner API
  slug: secret-scanner-api
asyncapis:
- description: Postman Webhooks enable you to receive incoming HTTP POST requests that trigger collection runs. When an external system sends a POST request to a Postman webhook URL, the webhook triggers a collectio
  name: Postman Webhooks
  slug: postman-webhooks-asyncapi
common:
- title: ''
  type: VSCodeExtension
  url: https://marketplace.visualstudio.com/items?itemName=Postman.postman-for-vscode
- title: ''
  type: Youtube
  url: https://www.youtube.com/c/Postman
- title: ''
  type: Website
  url: https://www.postman.com/
- title: ''
  type: Pricing
  url: https://www.postman.com/pricing/
- title: ''
  type: Knowledgebase
  url: https://www.postman.com/learn/
- title: ''
  type: Blog
  url: https://blog.postman.com/
- title: ''
  type: Templates
  url: https://www.postman.com/templates/
- title: ''
  type: Support
  url: https://support.postman.com/hc/en-us
- title: ''
  type: ChangeLog
  url: https://www.postman.com/release-notes/
- title: ''
  type: Status
  url: https://status.postman.com/
- title: ''
  type: Events
  url: https://www.postman.com/events/
- title: ''
  type: CLI
  url: https://learning.postman.com/docs/postman-cli/postman-cli-installation/
- title: ''
  type: Partners
  url: https://www.postman.com/partner-program/
- title: ''
  type: Customers
  url: https://www.postman.com/case-studies/
- title: ''
  type: Customers
  url: https://www.postman.com/case-studies/
- title: ''
  type: TermsOfService
  url: https://www.postman.com/legal/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.postman.com/legal/privacy-policy/
- title: ''
  type: Trademark
  url: https://www.postman.com/legal/trademark-policy/
- title: ''
  type: Trust
  url: https://www.postman.com/trust/
- title: ''
  type: Newsletter
  url: https://www.postman.com/newsletter/
- title: ''
  type: GitHub
  url: https://github.com/postmanlabs
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/postman-platform
- title: ''
  type: Twitter
  url: https://twitter.com/getpostman
- title: ''
  type: Instagram
  url: https://www.instagram.com/getpostman/
- title: ''
  type: Discord
  url: https://discord.com/invite/bKjz3CXbB6
- title: ''
  type: Forum
  url: https://community.postman.com/
- title: ''
  type: Documentation
  url: https://learning.postman.com/
- title: ''
  type: GettingStarted
  url: https://learning.postman.com/docs/developer/postman-api/intro-api/
- title: ''
  type: Authentication
  url: https://learning.postman.com/docs/developer/postman-api/authentication/
- title: ''
  type: Downloads
  url: https://www.postman.com/downloads/
- title: ''
  type: APINetwork
  url: https://www.postman.com/explore
- title: ''
  type: Academy
  url: https://academy.postman.com/
- title: ''
  type: StudentProgram
  url: https://www.postman.com/student-program/
- title: ''
  type: About
  url: https://www.postman.com/company/about-postman/
- title: ''
  type: Careers
  url: https://www.postman.com/company/careers/
- title: ''
  type: ContactSales
  url: https://www.postman.com/company/contact-sales/
- title: ''
  type: Press
  url: https://www.postman.com/company/press-media/
- title: ''
  type: Security
  url: https://security.postman.com/
- title: ''
  type: Compliance
  url: https://www.postman.com/trust/compliance/
- title: ''
  type: SDK
  url: https://learning.postman.com/docs/developer/collection-sdk/
- title: ''
  type: CLI
  url: https://github.com/postmanlabs/newman
- title: ''
  type: AIAgentBuilder
  url: https://www.postman.com/product/ai-agent-builder/
- title: ''
  type: MCPServer
  url: https://learning.postman.com/docs/postman-ai-agent-builder/mcp-server-flows/mcp-server-flows/
- title: ''
  type: SignUp
  url: https://identity.getpostman.com/signup
- title: ''
  type: Workspaces
  url: https://www.postman.com/product/workspaces/
- title: ''
  type: Rate Limits
  url: https://learning.postman.com/docs/developer/postman-api/rate-limits/
- title: ''
  type: Governance
  url: https://www.postman.com/product/api-governance/
- title: ''
  type: Flows
  url: https://www.postman.com/product/flows/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/postman
- title: ''
  type: GitHub Organization
  url: https://github.com/postmanlabs
- title: ''
  type: Console
  url: https://go.postman.co/
- title: ''
  type: Login
  url: https://identity.getpostman.com/login
created: '2025-01-08T00:00:00.000Z'
description: Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.
features:
- name: 1 Day Collection Recovery
- name: 100 Packages
- name: 100,000 Mock Server Requests
- name: 25 Collection Runs
- name: 30 Day Collection Recovery
- name: 50 Free Activities in Postbot
- name: 90 Day Collection Recovery
- name: Access Management
- name: Access to Flows
- name: Advanced Role-Based Access Control
- name: API Admin
- name: API Editor
- name: API Governance Manager
- name: API Monitoring
- name: API Network Folder Manager
- name: API Network Manager
- name: API Viewer
- name: Audit Logs
- name: Basic Role-Based Access Control
- name: Cloud-Based Integrations
- name: Cloud-Based Integrations
- name: Collection Editor
- name: Collection Generation and Sync
- name: Collection Recovery
- name: Collection Viewer
- name: Commenting & Annotations
- name: Community Manager
- name: Custom Domains
- name: Customer Success
- name: Define Governance Rules
- name: Deployment Control
- name: Desktop and Web Appside Extension (vs Code)
- name: Element-Level Roles
- name: Environment Editor
- name: Environment Viewer
- name: Graphql Client
- name: Grpc Client
- name: HTTP Client
- name: Internal Workspaces
- name: Internal Workspaces (Private)
- name: Internal Workspaces (Private)
- name: Live Preview
- name: Mock Server Editor
- name: Mock Server Viewer
- name: Mock Servers
- name: Monitor Editor
- name: Monitor Viewer
- name: Mqtt Client
- name: Multi-Partner Workspaces
- name: Newman CLI
- name: Outline-Based Editing
- name: Package Library
- name: Partner (External)
- name: Partner Editor
- name: Partner Manager
- name: Partner Viewer
- name: Postman API Supportaudit Logs
- name: Postman CLI
- name: Postman Interceptor
- name: Postman Proxy
- name: Postman Public Docs
- name: Postman Vault
- name: Priority Email Support
- name: Private API Documentation
- name: Private API Network
- name: Private API Network
- name: Private APIs
- name: Public API Documentation
- name: Public API Network
- name: Reporting & Analytics
- name: Roles & Permissions
- name: Saml
- name: Secret Scanning
- name: Single & Multi-Partner Workspaces
- name: Single Partner Workspaces
- name: Single Sign-on (SSO)
- name: socket.io Client
- name: SSO, Scim, & Saml
- name: Super Admin Role
- name: Team-Level Roles
- name: Test Data Storage
- name: Unlimited Collaborators
- name: Unlimited Private & Public APIs
- name: User Groups
- name: User Groups
- name: User Level Reporting & Analytics
- name: User Provisioning (Scim)
- name: View Syntax Errors
- name: Websocket Client
- name: Workspace Admin
- name: Workspace Editor
- name: Workspace Themes
- name: Workspace Updates
- name: Workspace Viewer
- name: Workspace-Level Roles
image: https://www.postman.com/assets/logos/postman-logo-horizontal-orange.svg
integrations:
- Name: 1PASSWORD Vault
- Name: Aikido
- Name: Amazon API Gateway
- Name: Apigee
- Name: Apimatic
- Name: Apisec
- Name: Appmap
- Name: AWS Gateway for API Builder
- Name: AWS Secrets Manager
- Name: Azure API Management
- Name: Azure Apim for API Builder
- Name: Azure DevOps
- Name: Azure Key Vault
- Name: Bigpanda
- Name: Bitbucket
- Name: Bitbucket Pipelines
- Name: Circleci
- Name: Coralogix
- Name: Datadog
- Name: Dropbox
- Name: Github
- Name: Github Actions
- Name: Gitlab
- Name: Gitlab CI/CD
- Name: Hashicorp Vault
- Name: Helios
- Name: Ilert
- Name: Jenkins
- Name: Jira
- Name: Keen
- Name: Liblab
- Name: Microsoft Power Automate
- Name: Microsoft Teams
- Name: New Relic
- Name: Open API
- Name: Opsgenie
- Name: Pagerduty
- Name: Pynt
- Name: Readme
- Name: Slack
- Name: Snyk
- Name: Speedscale
- Name: Splunk
- Name: Splunk On-Call
- Name: Stainless
- Name: Statuspage
- Name: Travis CI
- Name: vs Code
- Name: Workato
layout: provider
modified: '2026-04-28'
name: Postman
skills: []
slug: postman
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: postman\nurl: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/apis.yml\napis:\n  - aid: postman:postman\n    name: Postman\n    tags:\n      - Automation\n      - Client\n      - Collections\n      - Discovery\n      - Mocking\n      - Network\n      - Platform\n      - Testing\n      - Workflows\n    humanURL: https://www.postman.com/\n    properties:\n      - url: https://www.postman.com/\n        type: Documentation\n      - url: https://learning.postman.com/docs/developer/postman-api/intro-api/\n        type: GettingStarted\n      - url: https://learning.postman.com/docs/developer/postman-api/authentication/\n        type: Authentication\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: PostmanCollection\n      - url: asyncapi/postman-webhooks-asyncapi.yml\n        type: AsyncAPI\n      - url: json-schema/postman-collection-schema.json\n        type: JSONSchema\n      - url:\
  \ json-schema/postman-environment-schema.json\n        type: JSONSchema\n      - url: json-schema/postman-workspace-schema.json\n        type: JSONSchema\n      - url: json-ld/postman-context.yml\n        type: JSON-LD\n    description: Postman is your single platform for collaborative API development. Join 35+ million devs building great APIs together, across the entire API lifecycle.\n  - aid: postman:collections-api\n    name: Postman Collections API\n    tags:\n      - API Management\n      - Automation\n      - Collections\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-collections-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: Use the Collections APIs to manage your Postman collections and simplify collection-related workflows,\
  \ with endpoints to add, delete, or update your collections.\n  - aid: postman:workspaces-api\n    name: Postman Workspaces API\n    tags:\n      - API Management\n      - Collaboration\n      - Workspaces\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-workspaces-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: Use the Workspaces APIs to manage your Postman workspaces, with endpoints that enable you to create, update, and delete workspaces programmatically.\n  - aid: postman:environments-api\n    name: Postman Environments API\n    tags:\n      - Configuration\n      - Environments\n      - Variables\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n  \
  \  properties:\n      - url: openapi/postman-environments-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: The Environments API enables you to programmatically manage your Postman environments and global variables, scoping your work to different environments.\n  - aid: postman:mock-servers-api\n    name: Postman Mock Servers API\n    tags:\n      - API Development\n      - Mocking\n      - Simulation\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-mock-servers-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: The Mock Servers API enables you to perform CRUD operations on mock servers and\
  \ manage mock server responses for simulating API behavior during development.\n  - aid: postman:monitors-api\n    name: Postman Monitors API\n    tags:\n      - Automation\n      - Monitoring\n      - Scheduling\n      - Testing\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-monitors-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: The Monitors API enables you to programmatically run collections on a schedule, manage webhooks, and access metrics for API monitoring instances.\n  - aid: postman:apis-api\n    name: Postman APIs API\n    tags:\n      - API Builder\n      - API Design\n      - Specifications\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n\
  \    properties:\n      - url: openapi/postman-apis-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: Use the APIs endpoints to manage your API definitions in Postman, including creating, updating, and managing API versions and specifications.\n  - aid: postman:private-api-network-api\n    name: Postman Private API Network API\n    tags:\n      - API Network\n      - Discovery\n      - Governance\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-private-api-network-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: The Private API Network API enables you to programmatically manage your private\
  \ API network, automate management of internal documentation, and integrate with CI/CD pipelines.\n  - aid: postman:webhooks-api\n    name: Postman Webhooks API\n    tags:\n      - Automation\n      - Events\n      - Integrations\n      - Webhooks\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-webhooks-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/postman-webhooks-asyncapi.yml\n        type: AsyncAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: >-\n      The Webhooks API enables you to create webhooks that trigger collection\n      runs with custom payloads. Webhooks provide a way to integrate Postman\n      with external systems and automate workflows based on incoming events.\n  - aid: postman:collection-runs-api\n    name: Postman Collection\
  \ Runs API\n    tags:\n      - Automation\n      - CI/CD\n      - Collection Runner\n      - Testing\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-collection-runs-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: >-\n      The Collection Runs API enables you to programmatically run collections,\n      schedule runs, and retrieve results for continuous integration and\n      delivery pipelines.\n  - aid: postman:tags-api\n    name: Postman Tags API\n    tags:\n      - Governance\n      - Metadata\n      - Organization\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-tags-api-openapi.yml\n        type: OpenAPI\n\
  \      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: >-\n      The Tags API enables you to manage tags on APIs, collections, and\n      workspaces for governance and organization. Tags help categorize and\n      discover API assets across your team.\n  - aid: postman:audit-logs-api\n    name: Postman Audit Logs API\n    tags:\n      - Audit Logs\n      - Compliance\n      - Governance\n      - Security\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-audit-logs-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: >-\n      The Audit Logs API provides access to team audit logs for compliance\n      and governance. Track user actions, configuration\
  \ changes, and security\n      events across your Postman organization.\n  - aid: postman:secret-scanner-api\n    name: Postman Secret Scanner API\n    tags:\n      - Compliance\n      - Governance\n      - Secret Scanning\n      - Security\n    humanURL: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    baseURL: https://api.getpostman.com\n    properties:\n      - url: openapi/postman-secret-scanner-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api\n        type: Documentation\n    description: >-\n      The Secret Scanner API enables you to manage detected secrets and resolve\n      leaked credentials found in your Postman collections, environments, and\n      other API assets.\nname: Postman\ntags:\n  - AI Agent Builder\n  - API Development\n  - API Documentation\n  - API Governance\n  - API Monitoring\n  - API Testing\n  - Automation\n  - Client\n  - Clients\n  - Collaboration\n\
  \  - Collections\n  - Discovery\n  - Environments\n  - MCP\n  - Mock Servers\n  - Mocking\n  - Network\n  - Platform\n  - Testing\n  - Workflows\n  - Workspaces\ntype: Index\nimage: https://www.postman.com/assets/logos/postman-logo-horizontal-orange.svg\naccess: 3rd-Party\ncommon:\n  - url: https://marketplace.visualstudio.com/items?itemName=Postman.postman-for-vscode\n    name: VSCode Extension\n    type: VSCodeExtension\n  - url: https://www.youtube.com/c/Postman\n    name: Youtube\n    type: Youtube\n  - url: https://www.postman.com/\n    name: Postman API Platform\n    type: Website\n    description: 'null'\n  - url: https://www.postman.com/pricing/\n    name: Plans & Pricing | Postman API Platform\n    type: Pricing\n    description: 'null'\n  - url: https://www.postman.com/learn/\n    name: Learn APIs with Postman | Docs, courses, guides, videos - all free.\n    type: Knowledgebase\n    description: 'null'\n  - url: https://blog.postman.com/\n    name: 'All Things API: News, Tutorials\
  \ & More | Postman Blog'\n    type: Blog\n    description: 'null'\n  - url: https://www.postman.com/templates/\n    name: Postman Templates | Postman\n    type: Templates\n    description: 'null'\n  - url: https://support.postman.com/hc/en-us\n    name: Postman\n    type: Support\n    description: 'null'\n  - url: https://www.postman.com/release-notes/\n    name: Release Notes | Postman\n    type: ChangeLog\n    description: 'null'\n  - url: https://status.postman.com/\n    name: Postman Status\n    type: Status\n    description: 'null'\n  - url: https://www.postman.com/events/\n    name: Postman Events | Postman\n    type: Events\n    description: 'null'\n  - url: https://learning.postman.com/docs/postman-cli/postman-cli-installation/\n    name: Install the Postman CLI | Postman Docs\n    type: CLI\n    description: 'null'\n  - url: https://www.postman.com/partner-program/\n    name: The Postman Partner Program\n    type: Partners\n    description: 'null'\n  - url: https://www.postman.com/case-studies/\n\
  \    name: API Case Studies | Postman API Platform\n    type: Customers\n    description: 'null'\n  - url: https://www.postman.com/case-studies/\n    name: API Case Studies | Postman API Platform\n    type: Customers\n    description: 'null'\n  - url: https://www.postman.com/legal/terms/\n    name: Terms of Service | Postman\n    type: TermsOfService\n    description: 'null'\n  - url: https://www.postman.com/legal/privacy-policy/\n    name: Privacy Policy | Postman\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://www.postman.com/legal/trademark-policy/\n    name: Trademark Policy | Postman\n    type: Trademark\n    description: 'null'\n  - url: https://www.postman.com/trust/\n    name: Trust Center | Postman\n    type: Trust\n    description: 'null'\n  - url: https://www.postman.com/use-cases/\n    data:\n      - name: API-first development\n      - name: Application development\n      - name: Developer onboarding\n      - name: Developer portals\n      - name: API Testing\n\
  \    name: Use Cases\n    type: UseCases\n  - data:\n      - name: 1 Day Collection Recovery\n      - name: 100 Packages\n      - name: 100,000 Mock Server Requests\n      - name: 25 Collection Runs\n      - name: 30 Day Collection Recovery\n      - name: 50 Free Activities in Postbot\n      - name: 90 Day Collection Recovery\n      - name: Access Management\n      - name: Access to Flows\n      - name: Advanced Role-Based Access Control\n      - name: API Admin\n      - name: API Editor\n      - name: API Governance Manager\n      - name: API Monitoring\n      - name: API Network Folder Manager\n      - name: API Network Manager\n      - name: API Viewer\n      - name: Audit Logs\n      - name: Basic Role-Based Access Control\n      - name: Cloud-Based Integrations\n      - name: Cloud-Based Integrations\n      - name: Collection Editor\n      - name: Collection Generation and Sync\n      - name: Collection Recovery\n      - name: Collection Viewer\n      - name: Commenting & Annotations\n\
  \      - name: Community Manager\n      - name: Custom Domains\n      - name: Customer Success\n      - name: Define Governance Rules\n      - name: Deployment Control\n      - name: Desktop and Web Appside Extension (vs Code)\n      - name: Element-Level Roles\n      - name: Environment Editor\n      - name: Environment Viewer\n      - name: Graphql Client\n      - name: Grpc Client\n      - name: HTTP Client\n      - name: Internal Workspaces\n      - name: Internal Workspaces (Private)\n      - name: Internal Workspaces (Private)\n      - name: Live Preview\n      - name: Mock Server Editor\n      - name: Mock Server Viewer\n      - name: Mock Servers\n      - name: Monitor Editor\n      - name: Monitor Viewer\n      - name: Mqtt Client\n      - name: Multi-Partner Workspaces\n      - name: Newman CLI\n      - name: Outline-Based Editing\n      - name: Package Library\n      - name: Partner (External)\n      - name: Partner Editor\n      - name: Partner Manager\n      - name: Partner\
  \ Viewer\n      - name: Postman API Supportaudit Logs\n      - name: Postman CLI\n      - name: Postman Interceptor\n      - name: Postman Proxy\n      - name: Postman Public Docs\n      - name: Postman Vault\n      - name: Priority Email Support\n      - name: Private API Documentation\n      - name: Private API Network\n      - name: Private API Network\n      - name: Private APIs\n      - name: Public API Documentation\n      - name: Public API Network\n      - name: Reporting & Analytics\n      - name: Roles & Permissions\n      - name: Saml\n      - name: Secret Scanning\n      - name: Single & Multi-Partner Workspaces\n      - name: Single Partner Workspaces\n      - name: Single Sign-on (SSO)\n      - name: socket.io Client\n      - name: SSO, Scim, & Saml\n      - name: Super Admin Role\n      - name: Team-Level Roles\n      - name: Test Data Storage\n      - name: Unlimited Collaborators\n      - name: Unlimited Private & Public APIs\n      - name: User Groups\n      - name: User\
  \ Groups\n      - name: User Level Reporting & Analytics\n      - name: User Provisioning (Scim)\n      - name: View Syntax Errors\n      - name: Websocket Client\n      - name: Workspace Admin\n      - name: Workspace Editor\n      - name: Workspace Themes\n      - name: Workspace Updates\n      - name: Workspace Viewer\n      - name: Workspace-Level Roles\n    name: Features\n    type: Features\n  - url: https://www.postman.com/product/integrations/\n    data:\n      - Name: 1PASSWORD Vault\n      - Name: Aikido\n      - Name: Amazon API Gateway\n      - Name: Apigee\n      - Name: Apimatic\n      - Name: Apisec\n      - Name: Appmap\n      - Name: AWS Gateway for API Builder\n      - Name: AWS Secrets Manager\n      - Name: Azure API Management\n      - Name: Azure Apim for API Builder\n      - Name: Azure DevOps\n      - Name: Azure Key Vault\n      - Name: Bigpanda\n      - Name: Bitbucket\n      - Name: Bitbucket Pipelines\n      - Name: Circleci\n      - Name: Coralogix\n      -\
  \ Name: Datadog\n      - Name: Dropbox\n      - Name: Github\n      - Name: Github Actions\n      - Name: Gitlab\n      - Name: Gitlab CI/CD\n      - Name: Hashicorp Vault\n      - Name: Helios\n      - Name: Ilert\n      - Name: Jenkins\n      - Name: Jira\n      - Name: Keen\n      - Name: Liblab\n      - Name: Microsoft Power Automate\n      - Name: Microsoft Teams\n      - Name: New Relic\n      - Name: Open API\n      - Name: Opsgenie\n      - Name: Pagerduty\n      - Name: Pynt\n      - Name: Readme\n      - Name: Slack\n      - Name: Snyk\n      - Name: Speedscale\n      - Name: Splunk\n      - Name: Splunk On-Call\n      - Name: Stainless\n      - Name: Statuspage\n      - Name: Travis CI\n      - Name: vs Code\n      - Name: Workato\n    name: Integrations\n    type: Integrations\n  - url: https://www.postman.com/newsletter/\n    type: Newsletter\n  - url: https://github.com/postmanlabs\n    type: GitHub\n  - url: https://www.linkedin.com/company/postman-platform\n    type: LinkedIn\n\
  \  - url: https://twitter.com/getpostman\n    type: Twitter\n  - url: https://www.instagram.com/getpostman/\n    type: Instagram\n  - url: https://discord.com/invite/bKjz3CXbB6\n    type: Discord\n  - url: https://community.postman.com/\n    name: Postman Community Forum\n    type: Forum\n  - url: https://learning.postman.com/\n    name: Postman Learning Center\n    type: Documentation\n  - url: https://learning.postman.com/docs/developer/postman-api/intro-api/\n    name: Postman API Developer Documentation\n    type: GettingStarted\n  - url: https://learning.postman.com/docs/developer/postman-api/authentication/\n    name: Postman API Authentication\n    type: Authentication\n  - url: https://www.postman.com/downloads/\n    name: Download Postman\n    type: Downloads\n  - url: https://www.postman.com/explore\n    name: Postman API Network\n    type: APINetwork\n  - url: https://academy.postman.com/\n    name: Postman Academy\n    type: Academy\n  - url: https://www.postman.com/student-program/\n\
  \    name: Postman Student Program\n    type: StudentProgram\n  - url: https://www.postman.com/company/about-postman/\n    name: About Postman\n    type: About\n  - url: https://www.postman.com/company/careers/\n    name: Careers at Postman\n    type: Careers\n  - url: https://www.postman.com/company/contact-sales/\n    name: Contact Sales\n    type: ContactSales\n  - url: https://www.postman.com/company/press-media/\n    name: Press & Media\n    type: Press\n  - url: https://security.postman.com/\n    name: Postman Customer Trust Portal\n    type: Security\n  - url: https://www.postman.com/trust/compliance/\n    name: Compliance Certifications\n    type: Compliance\n  - url: https://learning.postman.com/docs/developer/collection-sdk/\n    name: Postman Collection SDK\n    type: SDK\n  - url: https://github.com/postmanlabs/newman\n    name: Newman CLI Collection Runner\n    type: CLI\n  - url: https://www.postman.com/product/ai-agent-builder/\n    name: Postman AI Agent Builder\n    type:\
  \ AIAgentBuilder\n  - url: https://learning.postman.com/docs/postman-ai-agent-builder/mcp-server-flows/mcp-server-flows/\n    name: Postman MCP Server Flows\n    type: MCPServer\n  - url: https://identity.getpostman.com/signup\n    name: Sign Up for Postman\n    type: SignUp\n  - url: https://www.postman.com/product/workspaces/\n    name: Postman Workspaces\n    type: Workspaces\n  - url: https://learning.postman.com/docs/developer/postman-api/rate-limits/\n    type: Rate Limits\n  - url: https://www.postman.com/product/api-governance/\n    type: Governance\n  - url: https://www.postman.com/product/flows/\n    type: Flows\n  - url: https://stackoverflow.com/questions/tagged/postman\n    type: Stack Overflow\n  - url: https://github.com/postmanlabs\n    type: GitHub Organization\n  - url: https://go.postman.co/\n    type: Console\n  - url: https://identity.getpostman.com/login\n    type: Login\ncreated: '2025-01-08T00:00:00.000Z'\nmodified: '2026-04-28'\nposition: Consumer\nsegments:\n\
  \  - Clients\n  - Workflows\n  - Documentation\n  - Testing\n  - Monitoring\n  - Governance\ndescription: >-\n  Postman is an API platform for building and using APIs. Postman simplifies each\n  step of the API lifecycle and streamlines collaboration so you can create better\n  APIs—faster.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n  - name: Postman\n    email: help@postman.com\n    url: https://www.postman.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/apis.yml
tags:
- AI Agent Builder
- API Development
- API Documentation
- API Governance
- API Monitoring
- API Testing
- Automation
- Client
- Clients
- Collaboration
- Collections
- Discovery
- Environments
- MCP
- Mock Servers
- Mocking
- Network
- Platform
- Testing
- Workflows
- Workspaces
url: https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/apis.yml
use_cases:
- name: API-first development
- name: Application development
- name: Developer onboarding
- name: Developer portals
- name: API Testing
---
