---
api_count: 1
apis:
- description: The primary REST API for interacting with TeamCity server, allowing you to manage builds, projects, build configurations, agents, users, VCS roots, changes, tests, investigations, mutes, cloud infrast
  name: TeamCity REST API
  slug: ''
capabilities: []
common:
- title: ''
  type: GettingStarted
  url: https://www.jetbrains.com/help/teamcity/getting-started-with-teamcity.html
- title: ''
  type: Documentation
  url: https://www.jetbrains.com/help/teamcity/teamcity-documentation.html
- title: ''
  type: Pricing
  url: https://www.jetbrains.com/teamcity/buy/
- title: ''
  type: Blog
  url: https://blog.jetbrains.com/teamcity/
- title: ''
  type: X
  url: https://twitter.com/teamcity
- title: ''
  type: GitHubOrganization
  url: https://github.com/JetBrains
- title: ''
  type: GitHubRepository
  url: https://github.com/JetBrains/teamcity-rest-client
- title: ''
  type: StatusPage
  url: https://teamcity-support.jetbrains.com/hc/en-us/categories/200595559-Known-Issues
- title: ''
  type: Marketplace
  url: https://plugins.jetbrains.com/teamcity
- title: ''
  type: Support
  url: https://www.jetbrains.com/support/teamcity/
- title: ''
  type: ChangeLog
  url: https://www.jetbrains.com/help/teamcity/what-s-new-in-teamcity.html
- title: TeamCity CLI
  type: CLI
  url: https://github.com/JetBrains/teamcity-cli
- title: TeamCity REST Client (Kotlin)
  type: SDK
  url: https://github.com/JetBrains/teamcity-rest-client
- title: Terraform Provider for TeamCity
  type: SDK
  url: https://github.com/JetBrains/terraform-provider-teamcity
created: '2024-01-01'
description: JetBrains TeamCity is a powerful continuous integration and deployment server that helps development teams build, test, and deploy software efficiently. TeamCity provides a comprehensive REST API for automating CI/CD workflows, managing projects, build configurations, agents, and infrastructure.
features:
- description: Define multi-stage build pipelines with dependencies and parallel execution.
  name: Build Pipelines
- description: Create complex build chains with snapshot and artifact dependencies between configurations.
  name: Build Chains
- description: Automatically detect and build feature branches from VCS repositories.
  name: Branch Building
- description: Reusable build configuration templates for standardizing pipeline patterns.
  name: Build Templates
- description: Run builds with local code changes before committing to the repository.
  name: Personal Builds
- description: Dynamically provision build agents in the cloud for elastic scaling.
  name: Cloud Agents
- description: Define build configurations as code using Kotlin DSL.
  name: Kotlin DSL Configuration
- description: Track test history across builds and automatically detect flaky tests.
  name: Test History and Flaky Tests
- description: Assign responsibility for failing builds and tests to team members.
  name: Investigation Management
- description: Cache build dependencies and artifacts for faster subsequent builds.
  name: Build Cache
- description: Aggregate results from multiple build configurations into a single view.
  name: Composite Builds
- description: Complete audit logging of all administrative actions and configuration changes.
  name: Audit Trail
image: https://www.jetbrains.com/teamcity/img/teamcity-logo.svg
integrations:
- description: Pull request building, commit status publishing, and webhook triggers from GitHub.
  name: GitHub
- description: Integration with GitLab repositories for VCS operations and merge request builds.
  name: GitLab
- description: Bitbucket Cloud and Server integration for source code and pull request builds.
  name: Bitbucket
- description: Build and push Docker images as part of CI/CD pipelines.
  name: Docker
- description: Deploy to Kubernetes clusters and use Kubernetes pods as build agents.
  name: Kubernetes
- description: AWS S3 artifact storage, EC2/ECS cloud agents, and CodeDeploy integration.
  name: AWS
- description: Azure cloud agents, Azure DevOps integration, and Azure deployment targets.
  name: Azure
- description: Link builds to Jira issues and track deployments.
  name: Jira
- description: Build notifications and status updates via Slack channels.
  name: Slack
- description: Manage TeamCity infrastructure as code using the official Terraform provider.
  name: Terraform
- description: Secure secrets management integration with HashiCorp Vault.
  name: HashiCorp Vault
- description: Single sign-on authentication via SAML identity providers like Okta and OneLogin.
  name: SAML SSO
- description: NuGet package feed hosting and dependency resolution.
  name: NuGet
- description: Maven build runner and artifact repository integration.
  name: Maven
- description: Gradle build runner with build cache and configuration cache support.
  name: Gradle
- description: Bazel build system support via the TeamCity Bazel plugin.
  name: Bazel
jsonld:
- class_count: 0
  name: Teamcity Rest Api Context
  property_count: 9
  slug: teamcity-rest-api
layout: provider
modified: '2026-04-18'
name: TeamCity
skills: []
slug: teamcity
solutions: []
source_yaml: "name: TeamCity\ndescription: >-\n  JetBrains TeamCity is a powerful continuous integration and deployment server\n  that helps development teams build, test, and deploy software efficiently.\n  TeamCity provides a comprehensive REST API for automating CI/CD workflows,\n  managing projects, build configurations, agents, and infrastructure.\nimage: https://www.jetbrains.com/teamcity/img/teamcity-logo.svg\nurl: https://github.com/api-evangelist/teamcity\nhumanURL: https://www.jetbrains.com/teamcity/\nbaseURL: https://teamcity.example.com/app/rest\ntags:\n  - Build Automation\n  - CI/CD\n  - Continuous Integration\n  - Deployment\n  - DevOps\n  - Testing\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Index\naid: teamcity\naccess: 3rd-Party\napis:\n  - name: TeamCity REST API\n    description: >-\n      The primary REST API for interacting with TeamCity server, allowing you to\n      manage builds, projects, build configurations, agents, users,\
  \ VCS roots,\n      changes, tests, investigations, mutes, cloud infrastructure, and more.\n    image: https://www.jetbrains.com/teamcity/img/teamcity-logo.svg\n    humanURL: https://www.jetbrains.com/help/teamcity/rest-api.html\n    baseURL: https://teamcity.example.com/app/rest\n    tags:\n      - Agents\n      - Automation\n      - Builds\n      - CI/CD\n      - Projects\n      - REST\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://www.jetbrains.com/help/teamcity/rest-api.html\n      - type: APIReference\n        url: https://www.jetbrains.com/help/teamcity/rest-api-reference.html\n      - type: Authentication\n        url: https://www.jetbrains.com/help/teamcity/rest-api.html#REST+Authentication\n      - type: OpenAPI\n        url: openapi/teamcity-rest-api.yml\n      - type: JSONSchema\n        url: json-schema/teamcity-rest-api.json\n      - type: JSONLD\n        url: json-ld/teamcity-rest-api.jsonld\n    contact:\n      - type: Support\n    \
  \    url: https://www.jetbrains.com/support/teamcity/\ncommon:\n  - type: GettingStarted\n    url: https://www.jetbrains.com/help/teamcity/getting-started-with-teamcity.html\n  - type: Documentation\n    url: https://www.jetbrains.com/help/teamcity/teamcity-documentation.html\n  - type: Pricing\n    url: https://www.jetbrains.com/teamcity/buy/\n  - type: Blog\n    url: https://blog.jetbrains.com/teamcity/\n  - type: X\n    url: https://twitter.com/teamcity\n  - type: GitHubOrganization\n    url: https://github.com/JetBrains\n  - type: GitHubRepository\n    url: https://github.com/JetBrains/teamcity-rest-client\n  - type: StatusPage\n    url: https://teamcity-support.jetbrains.com/hc/en-us/categories/200595559-Known-Issues\n  - type: Marketplace\n    url: https://plugins.jetbrains.com/teamcity\n  - type: Support\n    url: https://www.jetbrains.com/support/teamcity/\n  - type: ChangeLog\n    url: https://www.jetbrains.com/help/teamcity/what-s-new-in-teamcity.html\n  - type: CLI\n    url:\
  \ https://github.com/JetBrains/teamcity-cli\n    title: TeamCity CLI\n    description: >-\n      Command-line interface for TeamCity. Manage builds, logs, agents,\n      agent terminals, and queues from the terminal.\n  - type: SDK\n    url: https://github.com/JetBrains/teamcity-rest-client\n    title: TeamCity REST Client (Kotlin)\n    description: Official Kotlin client library for the TeamCity REST API.\n  - type: SDK\n    url: https://github.com/JetBrains/terraform-provider-teamcity\n    title: Terraform Provider for TeamCity\n    description: Terraform provider to manage TeamCity resources as infrastructure as code.\n  - type: Features\n    data:\n      - name: Build Pipelines\n        description: Define multi-stage build pipelines with dependencies and parallel execution.\n      - name: Build Chains\n        description: Create complex build chains with snapshot and artifact dependencies between configurations.\n      - name: Branch Building\n        description: Automatically detect\
  \ and build feature branches from VCS repositories.\n      - name: Build Templates\n        description: Reusable build configuration templates for standardizing pipeline patterns.\n      - name: Personal Builds\n        description: Run builds with local code changes before committing to the repository.\n      - name: Cloud Agents\n        description: Dynamically provision build agents in the cloud for elastic scaling.\n      - name: Kotlin DSL Configuration\n        description: Define build configurations as code using Kotlin DSL.\n      - name: Test History and Flaky Tests\n        description: Track test history across builds and automatically detect flaky tests.\n      - name: Investigation Management\n        description: Assign responsibility for failing builds and tests to team members.\n      - name: Build Cache\n        description: Cache build dependencies and artifacts for faster subsequent builds.\n      - name: Composite Builds\n        description: Aggregate results from\
  \ multiple build configurations into a single view.\n      - name: Audit Trail\n        description: Complete audit logging of all administrative actions and configuration changes.\n  - type: UseCases\n    data:\n      - name: Continuous Integration\n        description: Automatically build and test code on every commit or pull request.\n      - name: Continuous Deployment\n        description: Deploy applications to staging and production environments automatically.\n      - name: Multi-Platform Builds\n        description: Build and test across Linux, Windows, and macOS using diverse agent pools.\n      - name: Monorepo CI\n        description: Manage CI/CD for monorepos with selective triggering based on changed paths.\n      - name: Microservices Pipelines\n        description: Orchestrate build and deploy pipelines for microservices architectures.\n      - name: Release Management\n        description: Manage release branches, versioning, and deployment gates.\n      - name: Infrastructure\
  \ as Code Testing\n        description: Validate Terraform, Kubernetes, and other IaC configurations in CI pipelines.\n      - name: Mobile App CI/CD\n        description: Build, test, and distribute mobile applications for iOS and Android.\n      - name: Compliance and Audit\n        description: Maintain audit trails and enforce build policies for regulatory compliance.\n  - type: Integrations\n    data:\n      - name: GitHub\n        description: Pull request building, commit status publishing, and webhook triggers from GitHub.\n      - name: GitLab\n        description: Integration with GitLab repositories for VCS operations and merge request builds.\n      - name: Bitbucket\n        description: Bitbucket Cloud and Server integration for source code and pull request builds.\n      - name: Docker\n        description: Build and push Docker images as part of CI/CD pipelines.\n      - name: Kubernetes\n        description: Deploy to Kubernetes clusters and use Kubernetes pods as build\
  \ agents.\n      - name: AWS\n        description: AWS S3 artifact storage, EC2/ECS cloud agents, and CodeDeploy integration.\n      - name: Azure\n        description: Azure cloud agents, Azure DevOps integration, and Azure deployment targets.\n      - name: Jira\n        description: Link builds to Jira issues and track deployments.\n      - name: Slack\n        description: Build notifications and status updates via Slack channels.\n      - name: Terraform\n        description: Manage TeamCity infrastructure as code using the official Terraform provider.\n      - name: HashiCorp Vault\n        description: Secure secrets management integration with HashiCorp Vault.\n      - name: SAML SSO\n        description: Single sign-on authentication via SAML identity providers like Okta and OneLogin.\n      - name: NuGet\n        description: NuGet package feed hosting and dependency resolution.\n      - name: Maven\n        description: Maven build runner and artifact repository integration.\n\
  \      - name: Gradle\n        description: Gradle build runner with build cache and configuration cache support.\n      - name: Bazel\n        description: Bazel build system support via the TeamCity Bazel plugin.\nmaintainers:\n  - FN: JetBrains\n    url: https://www.jetbrains.com\n    email: teamcity-support@jetbrains.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/teamcity/refs/heads/main/apis.yml
tags:
- Build Automation
- CI/CD
- Continuous Integration
- Deployment
- DevOps
- Testing
url: https://github.com/api-evangelist/teamcity
use_cases:
- description: Automatically build and test code on every commit or pull request.
  name: Continuous Integration
- description: Deploy applications to staging and production environments automatically.
  name: Continuous Deployment
- description: Build and test across Linux, Windows, and macOS using diverse agent pools.
  name: Multi-Platform Builds
- description: Manage CI/CD for monorepos with selective triggering based on changed paths.
  name: Monorepo CI
- description: Orchestrate build and deploy pipelines for microservices architectures.
  name: Microservices Pipelines
- description: Manage release branches, versioning, and deployment gates.
  name: Release Management
- description: Validate Terraform, Kubernetes, and other IaC configurations in CI pipelines.
  name: Infrastructure as Code Testing
- description: Build, test, and distribute mobile applications for iOS and Android.
  name: Mobile App CI/CD
- description: Maintain audit trails and enforce build policies for regulatory compliance.
  name: Compliance and Audit
---
