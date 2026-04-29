---
api_count: 1
apis:
- description: 'The AWS App Runner API enables programmatic management of App Runner services, including creating and managing services, auto scaling configurations, custom domains, VPC connectors, and observability '
  name: Amazon App Runner API
  slug: ''
capabilities:
- description: Workflow for managing Amazon App Runner API resources.
  name: App Runner Management
  slug: app-runner-management
common:
- title: ''
  type: Portal
  url: https://console.aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/apprunner/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/apprunner/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
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
  type: Console
  url: https://console.aws.amazon.com/apprunner
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: Service Status
  url: https://status.aws.amazon.com/
- title: ''
  type: Knowledge Center
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-app-runner
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-app-runner-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/app-runner-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-app-runner-vocabulary.yaml
created: '2024-01-15'
description: AWS App Runner is a fully managed container application service that lets you build, deploy, and run containerized web applications and API services without prior infrastructure or container experience. Start with your source code or a container image.
features:
- description: Create, update, and delete App Runner services that deploy containerized or source-code-based web applications without managing infrastructure.
  name: Service Management
- description: Configure auto scaling policies to automatically scale App Runner services in and out based on traffic demand.
  name: Auto Scaling Configuration
- description: Associate custom domains with App Runner services for branded URLs with automatic SSL certificate provisioning.
  name: Custom Domain Support
- description: Connect App Runner services to VPC resources using VPC connectors for secure access to databases and internal services.
  name: VPC Connector Integration
- description: Configure automatic deployments triggered by source code changes or image push events for continuous delivery.
  name: Deployment Automation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy App Runner services directly from container images stored in Amazon ECR with automatic image updates.
  name: AWS ECR
- description: Use CodeBuild for source code building and integrate with App Runner for automated deployment pipelines.
  name: AWS CodeBuild
- description: Connect App Runner services to RDS databases using VPC connectors for secure private network access.
  name: Amazon RDS
- description: Monitor App Runner service metrics, request counts, and latency using CloudWatch dashboards and alarms.
  name: AWS CloudWatch
jsonld:
- class_count: 0
  name: Amazon App Runner Context
  property_count: 4
  slug: amazon-app-runner-context
layout: provider
modified: '2026-04-19'
name: Amazon App Runner
rules:
- name: Amazon App Runner API Rules
  rule_count: 3
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 0
  slug: amazon-app-runner-spectral-rules
skills: []
slug: amazon-app-runner
solutions: []
source_yaml: "aid: amazon-app-runner\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-app-runner/refs/heads/main/apis.yml\nname: Amazon App Runner\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  AWS App Runner is a fully managed container application service that lets\n  you build, deploy, and run containerized web applications and API services\n  without prior infrastructure or container experience. Start with your\n  source code or a container image.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n- AWS\n- CI/CD\n- Containers\n- Deployment\n- Managed Service\n- Serverless\n- Web Applications\napis:\n- name: Amazon App Runner API\n  description: >-\n    The AWS App Runner API enables programmatic management of App Runner\n    services, including creating and managing services, auto scaling\n    configurations, custom domains, VPC connectors, and observability\n    configurations\
  \ for containerized web applications.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/apprunner/\n  baseURL: https://apprunner.amazonaws.com\n  tags:\n  - Containers\n  - Deployment\n  - Serverless\n  - Web Applications\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html\n  - type: OpenAPI\n    url: openapi/amazon-app-runner-openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/apprunner/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/apprunner/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/apprunner/faqs/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html\n  - type: API Reference\n    url: https://docs.aws.amazon.com/apprunner/latest/api/Welcome.html\n  - type: CLI Reference\n    url: https://docs.aws.amazon.com/cli/latest/reference/apprunner/\n\
  \  - type: Security\n    url: https://docs.aws.amazon.com/apprunner/latest/dg/security.html\n  - type: JSONSchema\n    url: json-schema/amazon-app-runner-apprunnerresourcearn-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-runner-asconfigmaxconcurrency-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-runner-asconfigmaxsize-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-runner-asconfigminsize-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-runner-associatecustomdomainrequest-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-app-runner-apprunnerresourcearn-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-app-runner-asconfigmaxconcurrency-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-app-runner-asconfigmaxsize-structure.json\n  - type: JSONLD\n    url: json-ld/amazon-app-runner-context.jsonld\ncommon:\n- type: Portal\n  url: https://console.aws.amazon.com/\n\
  - type: Website\n  url: https://aws.amazon.com/apprunner/\n- type: Documentation\n  url: https://docs.aws.amazon.com/apprunner/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/containers/category/compute/aws-app-runner/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/apprunner\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Service Status\n  url: https://status.aws.amazon.com/\n- type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-app-runner\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n\
  - type: Security\n  url: https://aws.amazon.com/security/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-app-runner-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/app-runner-management.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-app-runner-vocabulary.yaml\n- type: Features\n  data:\n  - name: Service Management\n    description: Create, update, and delete App Runner services that deploy containerized or source-code-based web applications without managing infrastructure.\n  - name: Auto Scaling Configuration\n    description: Configure auto scaling policies to automatically scale App Runner services in and out based on traffic demand.\n  - name: Custom Domain Support\n    description: Associate custom domains with App Runner services for branded URLs with automatic SSL certificate provisioning.\n  - name: VPC Connector Integration\n    description: Connect App Runner services to VPC resources using VPC\
  \ connectors for secure access to databases and internal services.\n  - name: Deployment Automation\n    description: Configure automatic deployments triggered by source code changes or image push events for continuous delivery.\n- type: UseCases\n  data:\n  - name: Containerized API Deployment\n    description: Deploy REST APIs and microservices as containers on App Runner with automatic scaling and zero infrastructure management.\n  - name: Web Application Hosting\n    description: Host web applications built from source code or container images with built-in load balancing and HTTPS.\n  - name: CI/CD Integration\n    description: Integrate App Runner with CI/CD pipelines for automated service deployments triggered by repository changes.\n  - name: Startup Companies\n    description: Quickly launch and scale web backends without DevOps expertise using App Runner managed infrastructure.\n- type: Integrations\n  data:\n  - name: AWS ECR\n    description: Deploy App Runner services directly\
  \ from container images stored in Amazon ECR with automatic image updates.\n  - name: AWS CodeBuild\n    description: Use CodeBuild for source code building and integrate with App Runner for automated deployment pipelines.\n  - name: Amazon RDS\n    description: Connect App Runner services to RDS databases using VPC connectors for secure private network access.\n  - name: AWS CloudWatch\n    description: Monitor App Runner service metrics, request counts, and latency using CloudWatch dashboards and alarms.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-runner/refs/heads/main/apis.yml
tags:
- AWS
- CI/CD
- Containers
- Deployment
- Managed Service
- Serverless
- Web Applications
url: https://raw.githubusercontent.com/api-evangelist/amazon-app-runner/refs/heads/main/apis.yml
use_cases:
- description: Deploy REST APIs and microservices as containers on App Runner with automatic scaling and zero infrastructure management.
  name: Containerized API Deployment
- description: Host web applications built from source code or container images with built-in load balancing and HTTPS.
  name: Web Application Hosting
- description: Integrate App Runner with CI/CD pipelines for automated service deployments triggered by repository changes.
  name: CI/CD Integration
- description: Quickly launch and scale web backends without DevOps expertise using App Runner managed infrastructure.
  name: Startup Companies
---
