---
api_count: 1
api_specs:
- filename: aws-app-runner-openapi.yml
  format: yaml
  label: AWS App Runner
  slug: aws-app-runner
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-runner/refs/heads/main/openapi/aws-app-runner-openapi.yml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aws-app-runner\nname: AWS App Runner\ndescription: >-\n  AWS App Runner is a fully managed service that makes it easy to build, deploy,\n  and run containerized web applications and APIs at scale. It automatically\n  builds and deploys applications from container images or source code, load\n  balances traffic with encryption, and scales to meet traffic needs without\n  requiring infrastructure management. App Runner integrates with ECR, GitHub,\n  Bitbucket, VPC, IAM, and CloudWatch for complete application delivery.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - CI/CD\n  - Containers\n  - Deployment\n  - Microservices\n  - Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-app-runner/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-app-runner:aws-app-runner\n    name: AWS App Runner\n    description: >-\n\
  \      AWS App Runner is a fully managed service that makes it easy to build,\n      deploy, and run containerized web applications and APIs at scale. It\n      automatically builds and deploys applications, load balances traffic with\n      encryption, and scales to meet traffic needs without requiring\n      infrastructure management.\n    humanURL: https://aws.amazon.com/apprunner/\n    baseURL: https://apprunner.{region}.amazonaws.com\n    tags:\n      - AWS\n      - Containers\n      - Deployment\n      - Microservices\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/apprunner/latest/dg/getting-started.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/apprunner/latest/api/Welcome.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/apprunner/latest/dg/security-iam.html\n\
  \      - type: OpenAPI\n        url: openapi/aws-app-runner-openapi.yml\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/apprunner/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html\n  - type: Features\n    url: https://aws.amazon.com/apprunner/features/\n  - type: Pricing\n    url: https://aws.amazon.com/apprunner/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/apprunner/faqs/\n  - type: Customers\n    url: https://aws.amazon.com/apprunner/customers/\n  - type: Console\n    url: https://console.aws.amazon.com/apprunner/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/containers/category/compute/aws-app-runner/\n  - type: GitHubOrganization\n\
  \    url: https://github.com/aws\n  - type: SpectralRules\n    url: rules/aws-app-runner-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/aws-app-runner-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/app-deployment-workflow.yaml\n  - type: Features\n    data:\n      - name: Automatic Build and Deploy\n        description: Automatically builds container images from source code and deploys with zero configuration.\n      - name: Auto-Scaling\n        description: Scales automatically based on incoming request volume, with configurable min/max instances.\n      - name: Load Balancing\n        description: Built-in load balancing with HTTPS encryption for all traffic to deployed services.\n      - name: Custom Domains\n        description: Associate custom domain names with SSL/TLS certificates for branded endpoints.\n      - name: VPC Integration\n        description: Connect to private VPC resources like RDS, ElastiCache, and internal services.\n      -\
  \ name: Pause and Resume\n        description: Pause services to stop billing during idle periods and resume instantly when needed.\n      - name: Observability\n        description: Integration with CloudWatch and X-Ray for metrics, logs, and distributed tracing.\n      - name: GitHub and ECR Integration\n        description: Deploy directly from GitHub repositories or Amazon ECR container registries.\n  - type: UseCases\n    data:\n      - name: Web Application Deployment\n        description: Deploy containerized web applications without managing servers, load balancers, or scaling.\n      - name: API Backend Deployment\n        description: Host REST or GraphQL API backends with automatic scaling and HTTPS termination.\n      - name: Microservices Hosting\n        description: Deploy individual microservices with isolated scaling and custom domain routing.\n      - name: Development and Staging Environments\n        description: Quickly spin up and tear down environments using pause/resume\
  \ to minimize costs.\n  - type: Integrations\n    data:\n      - name: Amazon ECR\n        description: Pull container images from Amazon Elastic Container Registry for deployment.\n      - name: GitHub\n        description: Connect GitHub repositories for automatic builds and continuous deployment.\n      - name: AWS IAM\n        description: Control access to App Runner APIs and service resources using IAM policies.\n      - name: Amazon CloudWatch\n        description: Monitor service metrics, CPU usage, request counts, and response latency.\n      - name: AWS X-Ray\n        description: Enable distributed tracing for request flows through App Runner services.\n      - name: Amazon VPC\n        description: Access private VPC resources from App Runner services via VPC connectors.\n      - name: AWS Certificate Manager\n        description: Automatic SSL/TLS certificate provisioning for custom domain names.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-app-runner/refs/heads/main/apis.yml
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
