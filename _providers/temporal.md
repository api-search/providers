---
api_count: 2
api_specs:
- filename: cloud-ops-api.yml
  format: yaml
  label: Temporal Cloud Ops API
  slug: cloud-ops-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/temporal/refs/heads/main/openapi/cloud-ops-api.yml
apis:
- description: The Temporal Server Frontend API provides gRPC services for interacting with the Temporal Server, including WorkflowService for managing workflow executions, OperatorService for cluster operations, an
  name: Temporal Server Frontend API
  slug: server-frontend-api
- description: The Temporal Cloud Operations API is an open source, public HTTP API and gRPC API for programmatically managing Temporal Cloud control plane resources, including Namespaces, Users, Service Accounts, A
  name: Temporal Cloud Ops API
  slug: cloud-ops-api
capabilities:
- description: Unified workflow for platform administrators to manage Temporal Cloud infrastructure including namespaces, users, service accounts, API keys, and regions.
  name: Temporal Cloud Operations
  slug: cloud-operations
common:
- title: ''
  type: Portal
  url: https://temporal.io/
- title: ''
  type: Documentation
  url: https://docs.temporal.io/
- title: ''
  type: GettingStarted
  url: https://docs.temporal.io/cloud/get-started
- title: ''
  type: Quickstart
  url: https://docs.temporal.io/quickstarts
- title: ''
  type: SDK
  url: https://docs.temporal.io/develop
- title: ''
  type: CLI
  url: https://docs.temporal.io/cli
- title: ''
  type: Pricing
  url: https://temporal.io/pricing
- title: ''
  type: Blog
  url: https://temporal.io/blog
- title: ''
  type: ChangeLog
  url: https://temporal.io/change-log
- title: ''
  type: StatusPage
  url: https://status.temporal.io
- title: ''
  type: Security
  url: https://temporal.io/security
- title: ''
  type: TermsOfService
  url: https://temporal.io/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://temporal.io/global-privacy-policy
- title: ''
  type: Login
  url: https://cloud.temporal.io/login
- title: ''
  type: SignUp
  url: https://docs.temporal.io/cloud/get-started
- title: ''
  type: GitHubOrganization
  url: https://github.com/temporalio
- title: ''
  type: Training
  url: https://learn.temporal.io/
- title: ''
  type: NaftikoCapability
  url: capabilities/cloud-operations.yaml
created: '2026-03-03'
description: Temporal is an open-source durable execution platform for building reliable long-running distributed workflows and microservices.
features:
- description: Automatically persists workflow state and resumes execution after failures, ensuring long-running processes complete reliably.
  name: Durable Execution
- description: Create and manage isolated namespaces for organizing workflows with independent retention policies and access controls.
  name: Namespace Management
- description: Manage users, service accounts, and API keys for fine-grained access control to Temporal Cloud resources.
  name: User and Access Management
- description: Deploy workflows across multiple cloud regions for low-latency execution and disaster recovery.
  name: Multi-Region Deployment
- description: Safely deploy workflow code changes with built-in versioning that prevents breaking running executions.
  name: Workflow Versioning
- description: Query and filter workflow executions using custom search attributes for operational visibility and debugging.
  name: Visibility and Search
- description: Secure namespace communication with mutual TLS certificate-based authentication and codec server encryption.
  name: mTLS Authentication
- description: Track the status of long-running control plane operations like namespace creation and configuration changes.
  name: Async Operations
image: /assets/icons/temporal.png
integrations:
- description: Native Go client library for building Temporal workflows and activities with full type safety.
  name: Go SDK
- description: TypeScript/JavaScript SDK for building Temporal workflows in Node.js with async/await patterns.
  name: TypeScript SDK
- description: Python SDK for building Temporal workflows with native async support and type hints.
  name: Python SDK
- description: Java SDK for building Temporal workflows with annotation-based workflow and activity definitions.
  name: Java SDK
- description: .NET SDK for building Temporal workflows in C# with strong typing and async patterns.
  name: .NET SDK
jsonld:
- class_count: 0
  name: Cloud Ops Context
  property_count: 0
  slug: cloud-ops-context
layout: provider
modified: '2026-04-19'
name: Temporal
rules:
- name: Temporal API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: temporal-spectral-rules
skills: []
slug: temporal
solutions: []
source_filename: apis.yml
source_yaml: "aid: temporal\nname: Temporal\nsegments:\n  - ProCode_API_Composition\n  - Workflows\ndescription: >-\n  Temporal is an open-source durable execution platform for building reliable long-running distributed workflows and microservices.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ProCode_API_Composition\n  - Workflows\ncreated: '2026-03-03'\nmodified: '2026-04-19'\nurl: https://raw.githubusercontent.com/api-evangelist/temporal/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: temporal:server-frontend-api\n    name: Temporal Server Frontend API\n    description: >-\n      The Temporal Server Frontend API provides gRPC services for interacting\n      with the Temporal Server, including WorkflowService for managing workflow\n      executions, OperatorService for cluster operations, and HealthService for\n      health checks. Client SDKs and the Temporal CLI\
  \ use these gRPC services\n      under the hood.\n    humanURL: https://docs.temporal.io/self-hosted-guide/server-frontend-api-reference\n    tags:\n      - Durable Execution\n      - gRPC\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.temporal.io/self-hosted-guide/server-frontend-api-reference\n      - type: GitHubRepository\n        url: https://github.com/temporalio/api\n  - aid: temporal:cloud-ops-api\n    name: Temporal Cloud Ops API\n    description: >-\n      The Temporal Cloud Operations API is an open source, public HTTP API and\n      gRPC API for programmatically managing Temporal Cloud control plane\n      resources, including Namespaces, Users, Service Accounts, API keys, and\n      other infrastructure components.\n    humanURL: https://docs.temporal.io/ops\n    tags:\n      - Cloud\n      - Operations\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.temporal.io/ops\n      - type: APIReference\n\
  \        url: https://saas-api.tmprl.cloud/docs/httpapi.html\n      - type: GitHubRepository\n        url: https://github.com/temporalio/cloud-api\n      - type: OpenAPI\n        url: openapi/cloud-ops-api.yml\ncommon:\n  - type: Portal\n    url: https://temporal.io/\n  - type: Documentation\n    url: https://docs.temporal.io/\n  - type: GettingStarted\n    url: https://docs.temporal.io/cloud/get-started\n  - type: Quickstart\n    url: https://docs.temporal.io/quickstarts\n  - type: SDK\n    url: https://docs.temporal.io/develop\n  - type: CLI\n    url: https://docs.temporal.io/cli\n  - type: Pricing\n    url: https://temporal.io/pricing\n  - type: Blog\n    url: https://temporal.io/blog\n  - type: ChangeLog\n    url: https://temporal.io/change-log\n  - type: StatusPage\n    url: https://status.temporal.io\n  - type: Security\n    url: https://temporal.io/security\n  - type: TermsOfService\n    url: https://temporal.io/terms-of-service\n  - type: PrivacyPolicy\n    url: https://temporal.io/global-privacy-policy\n\
  \  - type: Login\n    url: https://cloud.temporal.io/login\n  - type: SignUp\n    url: https://docs.temporal.io/cloud/get-started\n  - type: GitHubOrganization\n    url: https://github.com/temporalio\n  - type: Training\n    url: https://learn.temporal.io/\n  - type: Features\n    data:\n      - name: Durable Execution\n        description: Automatically persists workflow state and resumes execution after failures, ensuring long-running processes complete reliably.\n      - name: Namespace Management\n        description: Create and manage isolated namespaces for organizing workflows with independent retention policies and access controls.\n      - name: User and Access Management\n        description: Manage users, service accounts, and API keys for fine-grained access control to Temporal Cloud resources.\n      - name: Multi-Region Deployment\n        description: Deploy workflows across multiple cloud regions for low-latency execution and disaster recovery.\n      - name: Workflow Versioning\n\
  \        description: Safely deploy workflow code changes with built-in versioning that prevents breaking running executions.\n      - name: Visibility and Search\n        description: Query and filter workflow executions using custom search attributes for operational visibility and debugging.\n      - name: mTLS Authentication\n        description: Secure namespace communication with mutual TLS certificate-based authentication and codec server encryption.\n      - name: Async Operations\n        description: Track the status of long-running control plane operations like namespace creation and configuration changes.\n  - type: UseCases\n    data:\n      - name: Microservice Orchestration\n        description: Coordinate complex multi-service transactions with automatic retries, compensation logic, and timeout handling.\n      - name: Data Pipeline Processing\n        description: Build reliable ETL and data processing pipelines that handle failures gracefully and resume from the last checkpoint.\n\
  \      - name: Order Fulfillment Workflows\n        description: Automate end-to-end order processing including payment, inventory, shipping, and notification steps with guaranteed completion.\n      - name: Infrastructure Provisioning\n        description: Orchestrate cloud infrastructure deployment and configuration management with durable state tracking.\n      - name: Subscription and Billing Management\n        description: Manage recurring billing cycles, subscription renewals, and payment processing with long-running timer-based workflows.\n  - type: Integrations\n    data:\n      - name: Go SDK\n        description: Native Go client library for building Temporal workflows and activities with full type safety.\n      - name: TypeScript SDK\n        description: TypeScript/JavaScript SDK for building Temporal workflows in Node.js with async/await patterns.\n      - name: Python SDK\n        description: Python SDK for building Temporal workflows with native async support and type\
  \ hints.\n      - name: Java SDK\n        description: Java SDK for building Temporal workflows with annotation-based workflow and activity definitions.\n      - name: .NET SDK\n        description: .NET SDK for building Temporal workflows in C# with strong typing and async patterns.\n  - type: NaftikoCapability\n    url: capabilities/cloud-operations.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/temporal/refs/heads/main/apis.yml
tags:
- ProCode_API_Composition
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/temporal/refs/heads/main/apis.yml
use_cases:
- description: Coordinate complex multi-service transactions with automatic retries, compensation logic, and timeout handling.
  name: Microservice Orchestration
- description: Build reliable ETL and data processing pipelines that handle failures gracefully and resume from the last checkpoint.
  name: Data Pipeline Processing
- description: Automate end-to-end order processing including payment, inventory, shipping, and notification steps with guaranteed completion.
  name: Order Fulfillment Workflows
- description: Orchestrate cloud infrastructure deployment and configuration management with durable state tracking.
  name: Infrastructure Provisioning
- description: Manage recurring billing cycles, subscription renewals, and payment processing with long-running timer-based workflows.
  name: Subscription and Billing Management
---
