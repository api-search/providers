---
api_count: 1
api_specs:
- filename: amazon-fargate-openapi.yml
  format: yaml
  label: Amazon Fargate API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-fargate/refs/heads/main/openapi/amazon-fargate-openapi.yml
apis:
- description: The Amazon Fargate API is accessed through Amazon ECS and enables you to run containers without managing servers or clusters. You can define tasks, configure networking and IAM policies, and deploy co
  name: Amazon Fargate API
  slug: ''
capabilities:
- description: Workflow capability for deploying and managing serverless container workloads on Amazon Fargate. Combines cluster management, task definitions, task execution, and service deployment for platform engi
  name: Amazon Fargate Container Orchestration
  slug: amazon-fargate-container-orchestration
common:
- title: ''
  type: Portal
  url: https://console.aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/fargate/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AmazonECS/latest/userguide/what-is-fargate.html
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
  url: https://aws.amazon.com/blogs/containers/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/ecs
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-fargate
- title: ''
  type: SpectralRules
  url: rules/amazon-fargate-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/fargate.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-fargate-container-orchestration.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-fargate-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-fargate-context.jsonld
created: '2024-01-15'
description: Amazon Fargate is a serverless compute engine for containers that works with both Amazon ECS and Amazon EKS. Fargate removes the need to provision and manage servers, letting you specify and pay for resources per application, and improves security through application isolation by design.
features:
- description: Run containers without provisioning or managing servers. Fargate handles capacity, OS updates, and scaling automatically.
  name: Serverless Compute
- description: Works seamlessly with both Amazon ECS task definitions and Amazon EKS pods.
  name: ECS and EKS Integration
- description: Each task runs in its own dedicated single-tenant compute environment for improved security.
  name: Workload Isolation
- description: Tasks receive ENIs with full VPC networking support including security groups and VPC Flow Logs.
  name: VPC Networking
- description: Supports Application Auto Scaling with target tracking, step scaling, and scheduled scaling.
  name: Auto Scaling
- description: Integration with Amazon EFS for stateful workloads requiring persistent storage.
  name: Persistent Storage
- description: HIPAA, PCI, FedRAMP, and GovCloud (US) region support for regulated workloads.
  name: Compliance Support
- description: Built-in Container Insights for metrics, logs, and observability.
  name: CloudWatch Integration
- description: Run workloads on AWS Graviton processors for improved price-performance.
  name: ARM64/Graviton Support
- description: Run fault-tolerant workloads on Fargate Spot for significant cost savings.
  name: Spot Instances
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Primary orchestration engine for running Fargate tasks and services.
  name: Amazon ECS
- description: Run Kubernetes pods serverlessly using Fargate profiles.
  name: Amazon EKS
- description: Fine-grained task-level IAM roles for container security and least privilege.
  name: AWS IAM
- description: Container Insights, metrics, logs, and alarms for Fargate workloads.
  name: Amazon CloudWatch
- description: Automatically scale Fargate services based on CloudWatch metrics.
  name: AWS Application Auto Scaling
- description: Persistent shared file storage for stateful Fargate workloads.
  name: Amazon EFS
- description: Run high-scale batch workloads using Fargate compute environments.
  name: AWS Batch
- description: Route HTTP/HTTPS traffic to Fargate services using ALB target groups.
  name: Application Load Balancer
- description: Inject secrets and configuration into Fargate task containers securely.
  name: AWS Secrets Manager
- description: Store and deploy container images from Amazon Elastic Container Registry.
  name: Amazon ECR
jsonld:
- class_count: 18
  name: Amazon Fargate Context
  property_count: 61
  slug: amazon-fargate-context
layout: provider
modified: '2026-04-19'
name: Amazon Fargate
rules:
- name: Amazon Fargate API Rules
  rule_count: 29
  severity_counts:
    error: 10
    hint: 0
    info: 4
    warn: 15
  slug: amazon-fargate-spectral-rules
skills: []
slug: amazon-fargate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Fargate\ndescription: >-\n  Amazon Fargate is a serverless compute engine for containers that works with\n  both Amazon ECS and Amazon EKS. Fargate removes the need to provision and\n  manage servers, letting you specify and pay for resources per application,\n  and improves security through application isolation by design.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/fargate/\ntype: Index\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n- AWS\n- Compute\n- Containers\n- ECS\n- EKS\n- Microservices\n- Serverless\napis:\n- name: Amazon Fargate API\n  description: >-\n    The Amazon Fargate API is accessed through Amazon ECS and enables you to\n    run containers without managing servers or clusters. You can define tasks,\n    configure networking and IAM policies, and deploy containerized\n    applications with serverless compute capacity.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanURL: https://aws.amazon.com/fargate/\n  baseURL: https://ecs.amazonaws.com\n  tags:\n  - Compute\n  - Containers\n  - Microservices\n  - Serverless\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AmazonECS/latest/userguide/what-is-fargate.html\n  - type: OpenAPI\n    url: openapi/amazon-fargate-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-fargate-cluster-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fargate-task-definition-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fargate-task-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fargate-service-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-fargate-cluster-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fargate-task-definition-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fargate-task-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fargate-service-structure.json\n\
  \  - type: Example\n    url: examples/amazon-fargate-cluster-example.json\n  - type: Example\n    url: examples/amazon-fargate-task-definition-example.json\n  - type: Example\n    url: examples/amazon-fargate-task-example.json\n  - type: Example\n    url: examples/amazon-fargate-service-example.json\n  - type: Pricing\n    url: https://aws.amazon.com/fargate/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/fargate/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/fargate/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/AmazonECS/latest/APIReference/Welcome.html\ncommon:\n- type: Portal\n  url: https://console.aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/fargate/\n- type: Documentation\n  url: https://docs.aws.amazon.com/AmazonECS/latest/userguide/what-is-fargate.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n\
  \  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/containers/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/ecs\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://status.aws.amazon.com/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-fargate\n- type: SpectralRules\n  url: rules/amazon-fargate-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/fargate.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-fargate-container-orchestration.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-fargate-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/amazon-fargate-context.jsonld\n- type: Features\n  data:\n  - name: Serverless Compute\n    description: Run containers without provisioning or managing\
  \ servers. Fargate handles capacity, OS updates, and scaling automatically.\n  - name: ECS and EKS Integration\n    description: Works seamlessly with both Amazon ECS task definitions and Amazon EKS pods.\n  - name: Workload Isolation\n    description: Each task runs in its own dedicated single-tenant compute environment for improved security.\n  - name: VPC Networking\n    description: Tasks receive ENIs with full VPC networking support including security groups and VPC Flow Logs.\n  - name: Auto Scaling\n    description: Supports Application Auto Scaling with target tracking, step scaling, and scheduled scaling.\n  - name: Persistent Storage\n    description: Integration with Amazon EFS for stateful workloads requiring persistent storage.\n  - name: Compliance Support\n    description: HIPAA, PCI, FedRAMP, and GovCloud (US) region support for regulated workloads.\n  - name: CloudWatch Integration\n    description: Built-in Container Insights for metrics, logs, and observability.\n  -\
  \ name: ARM64/Graviton Support\n    description: Run workloads on AWS Graviton processors for improved price-performance.\n  - name: Spot Instances\n    description: Run fault-tolerant workloads on Fargate Spot for significant cost savings.\n- type: UseCases\n  data:\n  - name: Web Applications and APIs\n    description: Deploy microservices-based web applications and REST APIs without infrastructure management.\n  - name: Batch Data Processing\n    description: Run parallel data processing jobs and ETL workloads using AWS Batch with Fargate.\n  - name: Application Modernization\n    description: Lift-and-shift containerized workloads to serverless infrastructure for reduced operational burden.\n  - name: AI/ML Workloads\n    description: Run training, inference, and data preparation containers in flexible serverless environments.\n  - name: CI/CD Pipelines\n    description: Execute build, test, and deployment pipelines as ephemeral Fargate tasks.\n  - name: Scheduled Jobs\n    description:\
  \ Run time-based container workloads using Amazon EventBridge and Fargate tasks.\n- type: Integrations\n  data:\n  - name: Amazon ECS\n    description: Primary orchestration engine for running Fargate tasks and services.\n  - name: Amazon EKS\n    description: Run Kubernetes pods serverlessly using Fargate profiles.\n  - name: AWS IAM\n    description: Fine-grained task-level IAM roles for container security and least privilege.\n  - name: Amazon CloudWatch\n    description: Container Insights, metrics, logs, and alarms for Fargate workloads.\n  - name: AWS Application Auto Scaling\n    description: Automatically scale Fargate services based on CloudWatch metrics.\n  - name: Amazon EFS\n    description: Persistent shared file storage for stateful Fargate workloads.\n  - name: AWS Batch\n    description: Run high-scale batch workloads using Fargate compute environments.\n  - name: Application Load Balancer\n    description: Route HTTP/HTTPS traffic to Fargate services using ALB target groups.\n\
  \  - name: AWS Secrets Manager\n    description: Inject secrets and configuration into Fargate task containers securely.\n  - name: Amazon ECR\n    description: Store and deploy container images from Amazon Elastic Container Registry.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-fargate/refs/heads/main/apis.yml
tags:
- Compute
- Containers
- ECS
- EKS
- Microservices
- Serverless
url: https://aws.amazon.com/fargate/
use_cases:
- description: Deploy microservices-based web applications and REST APIs without infrastructure management.
  name: Web Applications and APIs
- description: Run parallel data processing jobs and ETL workloads using AWS Batch with Fargate.
  name: Batch Data Processing
- description: Lift-and-shift containerized workloads to serverless infrastructure for reduced operational burden.
  name: Application Modernization
- description: Run training, inference, and data preparation containers in flexible serverless environments.
  name: AI/ML Workloads
- description: Execute build, test, and deployment pipelines as ephemeral Fargate tasks.
  name: CI/CD Pipelines
- description: Run time-based container workloads using Amazon EventBridge and Fargate tasks.
  name: Scheduled Jobs
---
