---
api_count: 1
apis:
- description: AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications, load balances
  name: AWS App Runner
  slug: aws-app-runner
capabilities:
- description: Workflow for developers and platform engineers to deploy, manage, and monitor containerized web applications and APIs using AWS App Runner. Covers service lifecycle, deployments, auto-scaling, and VPC
  name: AWS App Runner Application Deployment Workflow
  slug: app-deployment-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/apprunner/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html
- title: ''
  type: Pricing
  url: https://aws.amazon.com/apprunner/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/apprunner/faqs/
- title: ''
  type: Customers
  url: https://aws.amazon.com/apprunner/customers/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/apprunner/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/containers/category/compute/aws-app-runner/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: rules/aws-app-runner-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-app-runner-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/app-deployment-workflow.yaml
created: '2026-03-26'
description: AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications from container images or source code, load balances traffic with encryption, and scales to meet traffic needs without requiring infrastructure management. App Runner integrates with ECR, GitHub, Bitbucket, VPC, IAM, and CloudWatch for complete application delivery.
features:
- description: Automatically builds container images from source code and deploys with zero configuration.
  name: Automatic Build and Deploy
- description: Scales automatically based on incoming request volume, with configurable min/max instances.
  name: Auto-Scaling
- description: Built-in load balancing with HTTPS encryption for all traffic to deployed services.
  name: Load Balancing
- description: Associate custom domain names with SSL/TLS certificates for branded endpoints.
  name: Custom Domains
- description: Connect to private VPC resources like RDS, ElastiCache, and internal services.
  name: VPC Integration
- description: Pause services to stop billing during idle periods and resume instantly when needed.
  name: Pause and Resume
- description: Integration with CloudWatch and X-Ray for metrics, logs, and distributed tracing.
  name: Observability
- description: Deploy directly from GitHub repositories or Amazon ECR container registries.
  name: GitHub and ECR Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Pull container images from Amazon Elastic Container Registry for deployment.
  name: Amazon ECR
- description: Connect GitHub repositories for automatic builds and continuous deployment.
  name: GitHub
- description: Control access to App Runner APIs and service resources using IAM policies.
  name: AWS IAM
- description: Monitor service metrics, CPU usage, request counts, and response latency.
  name: Amazon CloudWatch
- description: Enable distributed tracing for request flows through App Runner services.
  name: AWS X-Ray
- description: Access private VPC resources from App Runner services via VPC connectors.
  name: Amazon VPC
- description: Automatic SSL/TLS certificate provisioning for custom domain names.
  name: AWS Certificate Manager
jsonld:
- class_count: 12
  name: Aws App Runner Context
  property_count: 62
  slug: aws-app-runner-context
layout: provider
modified: '2026-04-19'
name: AWS App Runner
rules:
- name: AWS App Runner API Rules
  rule_count: 17
  severity_counts:
    error: 12
    hint: 0
    info: 0
    warn: 5
  slug: aws-app-runner-spectral-rules
skills: []
slug: aws-app-runner
solutions: []
tags:
- AWS
- CI/CD
- Containers
- Deployment
- Microservices
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/aws-app-runner/refs/heads/main/apis.yml
use_cases:
- description: Deploy containerized web applications without managing servers, load balancers, or scaling.
  name: Web Application Deployment
- description: Host REST or GraphQL API backends with automatic scaling and HTTPS termination.
  name: API Backend Deployment
- description: Deploy individual microservices with isolated scaling and custom domain routing.
  name: Microservices Hosting
- description: Quickly spin up and tear down environments using pause/resume to minimize costs.
  name: Development and Staging Environments
---
