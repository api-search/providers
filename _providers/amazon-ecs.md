---
api_count: 4
api_specs:
- filename: amazon-ecs-openapi.yml
  format: yaml
  label: Amazon ECS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ecs/refs/heads/main/openapi/amazon-ecs-openapi.yml
apis:
- description: The Amazon ECS API provides programmatic access to manage containerized applications using Docker containers.
  name: Amazon ECS API
  slug: ''
- description: Amazon ECS Service Connect provides management of service-to-service communication as Amazon ECS configuration, building both service discovery and a service mesh for connecting services within and ac
  name: Amazon ECS Service Connect API
  slug: ''
- description: Amazon ECS Anywhere extends Amazon ECS to support registering external instances such as on-premises servers or virtual machines to your Amazon ECS cluster, allowing you to run and manage containerize
  name: Amazon ECS Anywhere API
  slug: ''
- description: AWS Copilot is an open source command line interface that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS and AWS Fargate, providing common clou
  name: AWS Copilot CLI
  slug: ''
capabilities:
- description: Container orchestration workflow for DevOps engineers and platform teams to manage ECS clusters, deploy services, run tasks, and monitor container workloads.
  name: Amazon ECS Container Orchestration
  slug: container-orchestration
common:
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/ecs/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/ecs/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/ecs/faqs/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/ecs/getting-started/
- title: ''
  type: Resources
  url: https://aws.amazon.com/ecs/resources/
- title: ''
  type: Partners
  url: https://aws.amazon.com/ecs/partners/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/aws/category/compute/amazon-elastic-container-service/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: CLI
  url: https://docs.aws.amazon.com/cli/latest/reference/ecs/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security.html
- title: ''
  type: Compliance
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security-compliance.html
- title: ''
  type: BestPractices
  url: https://docs.aws.amazon.com/AmazonECS/latest/bestpracticesguide/intro.html
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-quotas.html
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-logging-monitoring.html
- title: ''
  type: Troubleshooting
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/troubleshooting.html
- title: ''
  type: Console
  url: https://console.aws.amazon.com/ecs/home
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/tags/TAd-wgX2x3QgSxyelEN6raFg/amazon-elastic-container-service
- title: ''
  type: ChangeLog
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/document_history.html
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/platform-versions-changelog.html
- title: ''
  type: GitHubRepository
  url: https://github.com/aws/amazon-ecs-agent/releases
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
created: '2024'
description: Amazon Elastic Container Service (ECS) is a fully managed container orchestration service that makes it easy to deploy, manage, and scale containerized applications.
features:
- description: Run and manage Docker containers at scale without managing the underlying infrastructure or control plane.
  name: Fully Managed Container Orchestration
- description: Run containers serverlessly without provisioning or managing EC2 instances using AWS Fargate launch type.
  name: AWS Fargate Integration
- description: Automatically scale container workloads based on CloudWatch metrics, target tracking, or step scaling policies.
  name: Service Auto Scaling
- description: Built-in service discovery and service mesh for connecting containerized services within and across clusters.
  name: Service Connect
- description: Extend ECS to on-premises and edge infrastructure to run containers on your own servers and virtual machines.
  name: ECS Anywhere
- description: Manage compute capacity with capacity provider strategies for optimal resource allocation across EC2 and Fargate.
  name: Capacity Providers
- description: Define containerized applications as task definitions with CPU, memory, networking, and IAM role configurations.
  name: Task Definitions
- description: Monitor container performance metrics and logs with CloudWatch Container Insights for operational visibility.
  name: Container Insights
image: /assets/icons/amazon-ecs.png
integrations:
- description: Serverless compute engine for running containers without managing underlying EC2 instances.
  name: AWS Fargate
- description: Private container registry for storing, managing, and deploying Docker container images.
  name: Amazon ECR
- description: Infrastructure as code for provisioning and managing ECS clusters, services, and task definitions.
  name: AWS CloudFormation
- description: Distribute traffic across containers with Application Load Balancer and Network Load Balancer integration.
  name: Elastic Load Balancing
- description: Monitor container metrics, logs, and alarms with CloudWatch and Container Insights.
  name: Amazon CloudWatch
- description: Fine-grained access control for ECS tasks and services using IAM roles and policies.
  name: AWS IAM
jsonld:
- class_count: 0
  name: Amazon Ecs Context
  property_count: 0
  slug: amazon-ecs-context
layout: provider
modified: '2026-04-18'
name: Amazon ECS
rules:
- name: Amazon ECS API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: amazon-ecs-spectral-rules
skills: []
slug: amazon-ecs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon ECS\ndescription: Amazon Elastic Container Service (ECS) is a fully managed container orchestration service that makes it easy to deploy, manage, and scale containerized applications.\nurl: https://aws.amazon.com/ecs/\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\napis:\n  - name: Amazon ECS API\n    description: The Amazon ECS API provides programmatic access to manage containerized applications using Docker containers.\n    image: https://aws.amazon.com/favicon.ico\n    humanURL: https://aws.amazon.com/ecs/\n    baseURL: https://ecs.amazonaws.com\n    tags:\n      - Cloud\n      - Containers\n      - Docker\n      - Microservices\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/ecs/\n      - type: OpenAPI\n        url: openapi/amazon-ecs-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/ecs/2014-11-13/openapi.yaml\n      - type: JSONSchema\n\
  \        url: json-schema/amazon-ecs-task-definition-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-ecs-context.jsonld\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AmazonECS/latest/APIReference/Welcome.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/ecs/pricing/\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n      - type: CLI\n        url: https://docs.aws.amazon.com/cli/latest/reference/ecs/\n      - type: FAQ\n        url: https://aws.amazon.com/ecs/faqs/\n      - type: BestPractices\n        url: https://docs.aws.amazon.com/AmazonECS/latest/bestpracticesguide/intro.html\n      - type: StatusPage\n        url: https://status.aws.amazon.com/\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/APIReference/API_Operations.html\n      - type: Documentation\n\
  \        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html\n      - type: Features\n        url: https://aws.amazon.com/ecs/features/\n      - type: Security\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security.html\n      - type: Troubleshooting\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/troubleshooting.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-quotas.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-logging-monitoring.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/cloudwatch-metrics.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/cloudwatch-container-insights.html\n      - type: ChangeLog\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/document_history.html\n\
  \      - type: Partners\n        url: https://aws.amazon.com/ecs/partners/\n      - type: Resources\n        url: https://aws.amazon.com/ecs/resources/\n      - type: Blog\n        url: https://aws.amazon.com/blogs/aws/category/compute/amazon-elastic-container-service/\n      - type: KnowledgeCenter\n        url: https://repost.aws/knowledge-center/ecs-troubleshoot-failed-deployments\n      - type: Compliance\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security-compliance.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/general/latest/gr/ecs-service.html\n  - name: Amazon ECS Service Connect API\n    description: Amazon ECS Service Connect provides management of service-to-service communication as Amazon ECS configuration, building both service discovery and a service mesh for connecting services within and across clusters and VPCs.\n    image: https://aws.amazon.com/favicon.ico\n    humanURL: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-connect.html\n\
  \    baseURL: https://ecs.amazonaws.com\n    tags:\n      - Containers\n      - Microservices\n      - Networking\n      - Service-Discovery\n      - Service-Mesh\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-connect.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AmazonECS/latest/APIReference/API_ServiceConnectConfiguration.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-connect-concepts.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-connect-concepts-deploy.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/create-service-connect.html\n      - type: Blog\n        url: https://aws.amazon.com/blogs/aws/new-amazon-ecs-service-connect-enabling-easy-communication-between-microservices/\n    \
  \  - type: GitHubRepository\n        url: https://github.com/aws/amazon-ecs-service-connect-agent\n  - name: Amazon ECS Anywhere API\n    description: Amazon ECS Anywhere extends Amazon ECS to support registering external instances such as on-premises servers or virtual machines to your Amazon ECS cluster, allowing you to run and manage containerized workloads on your own infrastructure.\n    image: https://aws.amazon.com/favicon.ico\n    humanURL: https://aws.amazon.com/ecs/anywhere/\n    baseURL: https://ecs.amazonaws.com\n    tags:\n      - Containers\n      - Edge\n      - Hybrid-Cloud\n      - On-Premises\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-anywhere.html\n      - type: GettingStarted\n        url: https://aws.amazon.com/ecs/anywhere/getting-started/\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/launch-type-external.html\n\
  \      - type: Troubleshooting\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-anywhere-troubleshooting.html\n      - type: FAQ\n        url: https://aws.amazon.com/ecs/anywhere/faqs/\n      - type: Tutorials\n        url: https://github.com/aws-containers/ecs-anywhere-tutorial\n  - name: AWS Copilot CLI\n    description: AWS Copilot is an open source command line interface that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS and AWS Fargate, providing common cloud architectures and workflows.\n    image: https://aws.amazon.com/favicon.ico\n    humanURL: https://aws.amazon.com/containers/copilot/\n    baseURL: https://ecs.amazonaws.com\n    tags:\n      - Cli\n      - Containers\n      - Deployment\n      - Devops\n      - Fargate\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Copilot.html\n      - type: Documentation\n     \
  \   url: https://aws.github.io/copilot-cli/\n      - type: GitHubRepository\n        url: https://github.com/aws/copilot-cli\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/getting-started-aws-copilot-cli.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/copilot-install.html\n      - type: Documentation\n        url: https://aws.github.io/copilot-cli/docs/overview/\ncommon:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/ecs/\n  - type: Pricing\n    url: https://aws.amazon.com/ecs/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/ecs/faqs/\n  - type: Features\n    url: https://aws.amazon.com/ecs/features/\n  - type: GettingStarted\n    url: https://aws.amazon.com/ecs/getting-started/\n  - type: Resources\n    url: https://aws.amazon.com/ecs/resources/\n  - type: Partners\n    url: https://aws.amazon.com/ecs/partners/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/aws/category/compute/amazon-elastic-container-service/\n\
  \  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: SDK\n    url: https://aws.amazon.com/tools/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/ecs/\n  - type: Security\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security.html\n  - type: Compliance\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security-compliance.html\n  - type: BestPractices\n    url: https://docs.aws.amazon.com/AmazonECS/latest/bestpracticesguide/intro.html\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-quotas.html\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-logging-monitoring.html\n  - type: Troubleshooting\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/troubleshooting.html\n  - type: Console\n    url: https://console.aws.amazon.com/ecs/home\n  - type: KnowledgeCenter\n    url: https://repost.aws/tags/TAd-wgX2x3QgSxyelEN6raFg/amazon-elastic-container-service\n\
  \  - type: ChangeLog\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/document_history.html\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/platform-versions-changelog.html\n  - type: GitHubRepository\n    url: https://github.com/aws/amazon-ecs-agent/releases\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Features\n    data:\n      - name: Fully Managed Container Orchestration\n        description: Run and manage Docker containers at scale without managing the underlying infrastructure or control plane.\n      - name: AWS Fargate Integration\n        description: Run containers serverlessly without provisioning or managing EC2 instances using AWS Fargate launch type.\n      - name: Service Auto Scaling\n        description: Automatically scale container workloads based on CloudWatch\
  \ metrics, target tracking, or step scaling policies.\n      - name: Service Connect\n        description: Built-in service discovery and service mesh for connecting containerized services within and across clusters.\n      - name: ECS Anywhere\n        description: Extend ECS to on-premises and edge infrastructure to run containers on your own servers and virtual machines.\n      - name: Capacity Providers\n        description: Manage compute capacity with capacity provider strategies for optimal resource allocation across EC2 and Fargate.\n      - name: Task Definitions\n        description: Define containerized applications as task definitions with CPU, memory, networking, and IAM role configurations.\n      - name: Container Insights\n        description: Monitor container performance metrics and logs with CloudWatch Container Insights for operational visibility.\n  - type: UseCases\n    data:\n      - name: Microservices Architecture\n        description: Deploy and manage microservices\
  \ with independent scaling, deployment, and lifecycle management per service.\n      - name: Batch Processing\n        description: Run batch computing workloads using ECS tasks with automatic scaling and job scheduling.\n      - name: CI/CD Pipeline Deployment\n        description: Integrate with AWS CodePipeline and CodeDeploy for automated blue/green and rolling deployments of containerized applications.\n      - name: Hybrid Cloud Workloads\n        description: Run containerized workloads across AWS cloud and on-premises environments using ECS Anywhere.\n      - name: Machine Learning Inference\n        description: Deploy ML models as containerized inference endpoints with auto-scaling based on demand.\n  - type: Integrations\n    data:\n      - name: AWS Fargate\n        description: Serverless compute engine for running containers without managing underlying EC2 instances.\n      - name: Amazon ECR\n        description: Private container registry for storing, managing, and deploying\
  \ Docker container images.\n      - name: AWS CloudFormation\n        description: Infrastructure as code for provisioning and managing ECS clusters, services, and task definitions.\n      - name: Elastic Load Balancing\n        description: Distribute traffic across containers with Application Load Balancer and Network Load Balancer integration.\n      - name: Amazon CloudWatch\n        description: Monitor container metrics, logs, and alarms with CloudWatch and Container Insights.\n      - name: AWS IAM\n        description: Fine-grained access control for ECS tasks and services using IAM roles and policies.\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n  - name: Amazon Web Services\n    email: support@aws.amazon.com\n    url: https://aws.amazon.com\ntags:\n  - Amazon\n  - Aws\n  - Containers\n  - Docker\n  - Ecs\n  - Orchestration\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-ecs/refs/heads/main/apis.yml
tags:
- Amazon
- Aws
- Containers
- Docker
- Ecs
- Orchestration
url: https://aws.amazon.com/ecs/
use_cases:
- description: Deploy and manage microservices with independent scaling, deployment, and lifecycle management per service.
  name: Microservices Architecture
- description: Run batch computing workloads using ECS tasks with automatic scaling and job scheduling.
  name: Batch Processing
- description: Integrate with AWS CodePipeline and CodeDeploy for automated blue/green and rolling deployments of containerized applications.
  name: CI/CD Pipeline Deployment
- description: Run containerized workloads across AWS cloud and on-premises environments using ECS Anywhere.
  name: Hybrid Cloud Workloads
- description: Deploy ML models as containerized inference endpoints with auto-scaling based on demand.
  name: Machine Learning Inference
---
