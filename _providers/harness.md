---
api_count: 13
apis:
- description: The Harness Platform API provides access to core platform resources including projects, organizations, connectors, secrets, users, roles, resource groups, service accounts, variables, pipelines, trigg
  name: Harness Platform API
  slug: platform-api
- description: The Harness CI module helps build faster with features including code building, testing, dependency management, artifact uploads, and build monitoring with AI-powered Test Intelligence.
  name: Harness Continuous Integration API
  slug: ci-api
- description: The Harness CD and GitOps module automates all steps necessary to get changes into production with APIs for pipelines, execution, input sets, triggers, and approvals supporting multi-cloud deployments
  name: Harness Continuous Delivery and GitOps API
  slug: cd-api
- description: APIs to create and manage feature flags, targets, target groups, and tags for feature release management, performance monitoring, and A/B testing.
  name: Harness Feature Management and Experimentation API
  slug: feature-flags-api
- description: Cloud cost management APIs for cost recommendations, AutoStopping rules, commitment orchestration, cost categories, anomaly detection, asset governance, and BI dashboards.
  name: Harness Cloud Cost Management API
  slug: ccm-api
- description: APIs for chaos engineering, load testing, and disaster recovery testing including chaos experiments, probes, actions, faults, and resilience scoring.
  name: Harness Chaos Engineering API
  slug: chaos-api
- description: APIs for security vulnerability detection with over 40 scanner integrations for running scans, viewing results, and enforcing security policies across the software delivery lifecycle.
  name: Harness Security Testing Orchestration API
  slug: sto-api
- description: Backstage-powered Internal Developer Portal APIs for software catalog management, self-service workflows, scorecards, and developer experience.
  name: Harness Internal Developer Portal API
  slug: idp-api
- description: Source control management APIs for repositories, collaboration tools, pull requests, and pipeline integration.
  name: Harness Code Repository API
  slug: code-repo-api
- description: APIs for managing service level objectives, monitored services, and service dashboards for balancing feature velocity with reliability.
  name: Harness Service Reliability Management API
  slug: srm-api
- description: APIs for defining, deploying, and managing infrastructure across environments with Terraform and IaC tool integration.
  name: Harness Infrastructure as Code Management API
  slug: iacm-api
- description: APIs for SBOM generation, artifact integrity verification, and policy enforcement for software supply chain security and compliance.
  name: Harness Supply Chain Security API
  slug: ssca-api
- description: APIs for accessing engineering metrics and analytics data to improve engineering productivity, efficiency, and alignment.
  name: Harness Software Engineering Insights API
  slug: sei-api
common:
- title: ''
  type: Portal
  url: https://developer.harness.io/docs/
- title: ''
  type: Documentation
  url: https://apidocs.harness.io
- title: ''
  type: GettingStarted
  url: https://developer.harness.io/docs/platform/automation/api/api-quickstart/
- title: ''
  type: Authentication
  url: https://developer.harness.io/docs/platform/automation/api/add-and-manage-api-keys/
- title: ''
  type: Pricing
  url: https://www.harness.io/pricing
- title: ''
  type: SignUp
  url: https://app.harness.io/auth/
- title: ''
  type: Blog
  url: https://www.harness.io/blog
- title: ''
  type: Support
  url: https://www.harness.io/support
- title: ''
  type: StatusPage
  url: https://status.harness.io
- title: ''
  type: ChangeLog
  url: https://developer.harness.io/release-notes/
- title: ''
  type: TermsOfService
  url: https://www.harness.io/legal/website-terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.harness.io/legal/privacy
- title: ''
  type: GitHubOrganization
  url: https://github.com/harness
- title: ''
  type: Training
  url: https://developer.harness.io/university/
- title: ''
  type: Security
  url: https://www.harness.io/security
created: '2026-01-02'
description: Harness is an AI-powered software delivery platform that automates and accelerates the entire software development lifecycle from code to production. The platform provides intelligent automation across DevOps, testing and resilience, security and compliance, and cost optimization, helping engineering teams ship code faster, safer, and smarter as they scale.
features:
- description: Intelligent automation with Harness AI for test intelligence, deployment verification, and cost optimization.
  name: AI-Powered Automation
- description: Visual pipeline builder with conditional logic, parallel execution, and approval gates.
  name: Pipeline Orchestration
- description: Declarative GitOps deployments with Argo CD integration for Kubernetes workloads.
  name: GitOps Deployments
- description: Progressive feature rollouts with targeting, experimentation, and A/B testing capabilities.
  name: Feature Flag Management
- description: FinOps capabilities including AutoStopping, commitment orchestration, and cost anomaly detection.
  name: Cloud Cost Optimization
- description: Resilience testing with chaos experiments, load testing, and disaster recovery validation.
  name: Chaos Engineering
- description: Automated security scanning with 40+ scanner integrations and policy enforcement.
  name: Security Testing Orchestration
- description: Backstage-powered developer portal for software catalog, self-service workflows, and scorecards.
  name: Internal Developer Portal
image: /assets/icons/harness.png
integrations:
- description: Source code management, GitHub Actions, and GitHub App integration for CI/CD workflows.
  name: GitHub
- description: Native Kubernetes deployment support with Helm, Kustomize, and GitOps.
  name: Kubernetes
- description: Multi-service AWS integration including ECS, EKS, Lambda, S3, and CloudFormation.
  name: AWS
- description: Azure DevOps, AKS, Azure Functions, and Azure Resource Manager integration.
  name: Azure
- description: Google Cloud integration with GKE, Cloud Run, Cloud Functions, and Cloud Build.
  name: GCP
- description: Infrastructure as Code management with Terraform plan, apply, and state management.
  name: Terraform
- description: Issue tracking integration for deployment approvals, change management, and traceability.
  name: Jira
- description: Notifications and approval workflows within Slack channels.
  name: Slack
jsonld:
- class_count: 4
  name: Harness Context
  property_count: 7
  slug: harness-context
layout: provider
modified: '2026-04-18'
name: Harness
rules:
- name: Harness API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 3
  slug: harness-spectral-rules
skills: []
slug: harness
solutions: []
source_filename: apis.yml
source_yaml: "aid: harness\nname: Harness\ndescription: >-\n  Harness is an AI-powered software delivery platform that automates and accelerates\n  the entire software development lifecycle from code to production. The platform\n  provides intelligent automation across DevOps, testing and resilience, security\n  and compliance, and cost optimization, helping engineering teams ship code faster,\n  safer, and smarter as they scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/apis.yml\naccess: 3rd-Party\nposition: Consuming\ncreated: '2026-01-02'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - DevOps\n  - GitOps\n  - Internal Developer Portal\n  - Lifecycle\n  - Software Delivery\nsegments:\n  - FinOps\napis:\n  - aid: harness:platform-api\n    name: Harness Platform API\n    description: >-\n      The Harness Platform API provides access\
  \ to core platform resources\n      including projects, organizations, connectors, secrets, users, roles,\n      resource groups, service accounts, variables, pipelines, triggers, input\n      sets, approvals, and pipeline execution.\n    humanURL: https://apidocs.harness.io\n    tags:\n      - Access Management\n      - Accounts\n      - Administration\n      - Organizations\n      - Platform\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://apidocs.harness.io\n      - type: APIReference\n        url: https://developer.harness.io/docs/category/api/\n      - type: GettingStarted\n        url: https://developer.harness.io/docs/platform/automation/api/api-quickstart/\n  - aid: harness:ci-api\n    name: Harness Continuous Integration API\n    description: >-\n      The Harness CI module helps build faster with features including code\n      building, testing, dependency management, artifact uploads, and build\n      monitoring with AI-powered Test Intelligence.\n\
  \    humanURL: https://developer.harness.io/docs/continuous-integration\n    tags:\n      - Builds\n      - CI\n      - Continuous Integration\n      - Pipelines\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/continuous-integration\n      - type: APIReference\n        url: https://apidocs.harness.io/pipeline\n  - aid: harness:cd-api\n    name: Harness Continuous Delivery and GitOps API\n    description: >-\n      The Harness CD and GitOps module automates all steps necessary to get\n      changes into production with APIs for pipelines, execution, input sets,\n      triggers, and approvals supporting multi-cloud deployments.\n    humanURL: https://developer.harness.io/docs/continuous-delivery\n    tags:\n      - CD\n      - Continuous Delivery\n      - Deployments\n      - GitOps\n      - Pipelines\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/continuous-delivery\n      - type: APIReference\n\
  \        url: https://apidocs.harness.io/pipeline\n  - aid: harness:feature-flags-api\n    name: Harness Feature Management and Experimentation API\n    description: >-\n      APIs to create and manage feature flags, targets, target groups, and tags\n      for feature release management, performance monitoring, and A/B testing.\n    humanURL: https://developer.harness.io/docs/feature-management-experimentation\n    tags:\n      - A/B Testing\n      - Experimentation\n      - Feature Flags\n      - Feature Management\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/feature-management-experimentation\n      - type: APIReference\n        url: https://apidocs.harness.io/feature-flags\n  - aid: harness:ccm-api\n    name: Harness Cloud Cost Management API\n    description: >-\n      Cloud cost management APIs for cost recommendations, AutoStopping rules,\n      commitment orchestration, cost categories, anomaly detection, asset\n      governance,\
  \ and BI dashboards.\n    humanURL: https://developer.harness.io/docs/cloud-cost-management\n    tags:\n      - CCM\n      - Cloud Cost Management\n      - Cost Optimization\n      - FinOps\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/cloud-cost-management\n      - type: APIReference\n        url: https://apidocs.harness.io/costs\n  - aid: harness:chaos-api\n    name: Harness Chaos Engineering API\n    description: >-\n      APIs for chaos engineering, load testing, and disaster recovery testing\n      including chaos experiments, probes, actions, faults, and resilience scoring.\n    humanURL: https://developer.harness.io/docs/resilience-testing\n    tags:\n      - Chaos Engineering\n      - Reliability\n      - Resilience Testing\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/resilience-testing\n      - type: APIReference\n        url: https://apidocs.harness.io/chaos.html\n  - aid: harness:sto-api\n\
  \    name: Harness Security Testing Orchestration API\n    description: >-\n      APIs for security vulnerability detection with over 40 scanner\n      integrations for running scans, viewing results, and enforcing security\n      policies across the software delivery lifecycle.\n    humanURL: https://developer.harness.io/docs/security-testing-orchestration\n    tags:\n      - DevSecOps\n      - Security Testing\n      - STO\n      - Vulnerability Scanning\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/security-testing-orchestration\n  - aid: harness:idp-api\n    name: Harness Internal Developer Portal API\n    description: >-\n      Backstage-powered Internal Developer Portal APIs for software catalog\n      management, self-service workflows, scorecards, and developer experience.\n    humanURL: https://developer.harness.io/docs/internal-developer-portal\n    tags:\n      - Backstage\n      - Developer Experience\n      - IDP\n      - Software\
  \ Catalog\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/internal-developer-portal\n      - type: APIReference\n        url: https://developer.harness.io/docs/internal-developer-portal/api-refernces/overview/\n  - aid: harness:code-repo-api\n    name: Harness Code Repository API\n    description: >-\n      Source control management APIs for repositories, collaboration tools,\n      pull requests, and pipeline integration.\n    humanURL: https://developer.harness.io/docs/code-repository\n    tags:\n      - Code Repository\n      - Git\n      - Source Control\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/code-repository\n  - aid: harness:srm-api\n    name: Harness Service Reliability Management API\n    description: >-\n      APIs for managing service level objectives, monitored services, and\n      service dashboards for balancing feature velocity with reliability.\n    humanURL: https://developer.harness.io/docs/service-reliability-management\n\
  \    tags:\n      - Monitoring\n      - Service Reliability\n      - SLO\n      - SRM\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/service-reliability-management\n  - aid: harness:iacm-api\n    name: Harness Infrastructure as Code Management API\n    description: >-\n      APIs for defining, deploying, and managing infrastructure across environments\n      with Terraform and IaC tool integration.\n    humanURL: https://developer.harness.io/docs/infrastructure-as-code-management\n    tags:\n      - IaCM\n      - Infrastructure as Code\n      - Provisioning\n      - Terraform\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/infrastructure-as-code-management\n  - aid: harness:ssca-api\n    name: Harness Supply Chain Security API\n    description: >-\n      APIs for SBOM generation, artifact integrity verification, and policy\n      enforcement for software supply chain security and compliance.\n\
  \    humanURL: https://developer.harness.io/docs/software-supply-chain-assurance\n    tags:\n      - Compliance\n      - SBOM\n      - Software Supply Chain\n      - Supply Chain Security\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/software-supply-chain-assurance\n  - aid: harness:sei-api\n    name: Harness Software Engineering Insights API\n    description: >-\n      APIs for accessing engineering metrics and analytics data to improve\n      engineering productivity, efficiency, and alignment.\n    humanURL: https://developer.harness.io/docs/software-engineering-insights\n    tags:\n      - Analytics\n      - Engineering Productivity\n      - SEI\n    properties:\n      - type: Documentation\n        url: https://developer.harness.io/docs/software-engineering-insights\n      - type: APIReference\n        url: https://developer.harness.io/docs/software-engineering-insights/propelo-sei/sei-administration/sei-api-reference/sei-api-guide/\n\
  common:\n  - type: Portal\n    url: https://developer.harness.io/docs/\n  - type: Documentation\n    url: https://apidocs.harness.io\n  - type: GettingStarted\n    url: https://developer.harness.io/docs/platform/automation/api/api-quickstart/\n  - type: Authentication\n    url: https://developer.harness.io/docs/platform/automation/api/add-and-manage-api-keys/\n  - type: Pricing\n    url: https://www.harness.io/pricing\n  - type: SignUp\n    url: https://app.harness.io/auth/\n  - type: Blog\n    url: https://www.harness.io/blog\n  - type: Support\n    url: https://www.harness.io/support\n  - type: StatusPage\n    url: https://status.harness.io\n  - type: ChangeLog\n    url: https://developer.harness.io/release-notes/\n  - type: TermsOfService\n    url: https://www.harness.io/legal/website-terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.harness.io/legal/privacy\n  - type: GitHubOrganization\n    url: https://github.com/harness\n  - type: Training\n    url: https://developer.harness.io/university/\n\
  \  - type: Security\n    url: https://www.harness.io/security\n  - type: Features\n    data:\n      - name: AI-Powered Automation\n        description: Intelligent automation with Harness AI for test intelligence, deployment verification, and cost optimization.\n      - name: Pipeline Orchestration\n        description: Visual pipeline builder with conditional logic, parallel execution, and approval gates.\n      - name: GitOps Deployments\n        description: Declarative GitOps deployments with Argo CD integration for Kubernetes workloads.\n      - name: Feature Flag Management\n        description: Progressive feature rollouts with targeting, experimentation, and A/B testing capabilities.\n      - name: Cloud Cost Optimization\n        description: FinOps capabilities including AutoStopping, commitment orchestration, and cost anomaly detection.\n      - name: Chaos Engineering\n        description: Resilience testing with chaos experiments, load testing, and disaster recovery validation.\n\
  \      - name: Security Testing Orchestration\n        description: Automated security scanning with 40+ scanner integrations and policy enforcement.\n      - name: Internal Developer Portal\n        description: Backstage-powered developer portal for software catalog, self-service workflows, and scorecards.\n  - type: UseCases\n    data:\n      - name: CI/CD Pipeline Automation\n        description: Automate build, test, and deploy workflows across multi-cloud and hybrid environments.\n      - name: Progressive Feature Delivery\n        description: Roll out features progressively with feature flags, canary deployments, and blue-green strategies.\n      - name: Cloud Cost Management\n        description: Optimize cloud spend with automated cost recommendations, idle resource detection, and budget alerts.\n      - name: Security Compliance\n        description: Enforce security policies with automated scanning, SBOM generation, and supply chain verification.\n      - name: Platform Engineering\n\
  \        description: Build internal developer platforms with self-service workflows, templates, and software catalogs.\n      - name: SRE and Reliability\n        description: Manage SLOs, monitor service health, and validate resilience with chaos engineering.\n  - type: Integrations\n    data:\n      - name: GitHub\n        description: Source code management, GitHub Actions, and GitHub App integration for CI/CD workflows.\n      - name: Kubernetes\n        description: Native Kubernetes deployment support with Helm, Kustomize, and GitOps.\n      - name: AWS\n        description: Multi-service AWS integration including ECS, EKS, Lambda, S3, and CloudFormation.\n      - name: Azure\n        description: Azure DevOps, AKS, Azure Functions, and Azure Resource Manager integration.\n      - name: GCP\n        description: Google Cloud integration with GKE, Cloud Run, Cloud Functions, and Cloud Build.\n      - name: Terraform\n        description: Infrastructure as Code management with Terraform\
  \ plan, apply, and state management.\n      - name: Jira\n        description: Issue tracking integration for deployment approvals, change management, and traceability.\n      - name: Slack\n        description: Notifications and approval workflows within Slack channels.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/apis.yml
tags:
- DevOps
- GitOps
- Internal Developer Portal
- Lifecycle
- Software Delivery
url: https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/apis.yml
use_cases:
- description: Automate build, test, and deploy workflows across multi-cloud and hybrid environments.
  name: CI/CD Pipeline Automation
- description: Roll out features progressively with feature flags, canary deployments, and blue-green strategies.
  name: Progressive Feature Delivery
- description: Optimize cloud spend with automated cost recommendations, idle resource detection, and budget alerts.
  name: Cloud Cost Management
- description: Enforce security policies with automated scanning, SBOM generation, and supply chain verification.
  name: Security Compliance
- description: Build internal developer platforms with self-service workflows, templates, and software catalogs.
  name: Platform Engineering
- description: Manage SLOs, monitor service health, and validate resilience with chaos engineering.
  name: SRE and Reliability
---
