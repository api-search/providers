---
api_count: 1
apis:
- description: Core API for creating and managing state machines and executions in AWS Step Functions, enabling serverless workflow orchestration for coordinating distributed applications and microservices.
  name: Amazon Step Functions API
  slug: ''
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/step-functions/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html
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
  url: https://aws.amazon.com/blogs/compute/category/application-services/aws-step-functions/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/states/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-step-functions-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-step-functions-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-step-functions.yaml
created: '2024-01-15'
description: Amazon Step Functions is a serverless workflow orchestration service that lets you coordinate distributed applications and microservices using visual workflows, enabling you to build and update state machines that react to events, manage retries, and orchestrate complex business processes.
features:
- description: Design and visualize workflows using Amazon States Language (ASL).
  name: Visual Workflow
- description: Orchestrate Lambda, ECS, Fargate, SNS, SQS, and 220+ AWS services.
  name: Serverless Orchestration
- description: Built-in retry and catch capabilities for fault-tolerant workflows.
  name: Error Handling
- description: High-throughput workflows for event processing at scale.
  name: Express Workflows
- description: Long-running durable workflows with exactly-once execution.
  name: Standard Workflows
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Invoke Lambda functions as workflow steps.
  name: AWS Lambda
- description: Run ECS/Fargate tasks as part of workflows.
  name: Amazon ECS
- description: Read and write DynamoDB tables directly from workflows.
  name: Amazon DynamoDB
- description: Publish SNS notifications from workflow steps.
  name: Amazon SNS
- description: Orchestrate ML training and inference pipelines.
  name: Amazon SageMaker
- description: Run Glue ETL jobs from workflow steps.
  name: AWS Glue
jsonld:
- class_count: 121
  name: Amazon Step Functions Context
  property_count: 118
  slug: amazon-step-functions-context
layout: provider
modified: '2026-04-19'
name: Amazon Step Functions
rules:
- name: Amazon Step Functions API Rules
  rule_count: 19
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 7
  slug: amazon-step-functions-spectral-rules
skills: []
slug: amazon-step-functions
solutions: []
source_yaml: "name: Amazon Step Functions\ndescription: Amazon Step Functions is a serverless workflow orchestration service that lets you coordinate distributed applications and microservices using visual workflows, enabling you to build and \n  update state machines that react to events, manage retries, and orchestrate complex business processes.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/step-functions/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Step Functions API\n  description: >-\n    Core API for creating and managing state machines and executions in AWS\n    Step Functions, enabling serverless workflow orchestration for\n    coordinating distributed applications and microservices.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/step-functions/\n  baseURL: https://states.amazonaws.com\n  tags:\n  - AWS\n  - Orchestration\n\
  \  - Serverless\n  - State Machine\n  - Workflow\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-step-functions.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/step-functions/\n  - type: Pricing\n    url: https://aws.amazon.com/step-functions/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/step-functions/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/step-functions/\n- type: Documentation\n  url: https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/category/application-services/aws-step-functions/\n- type: GitHubOrganization\n  url: https://github.com/aws\n\
  - type: Console\n  url: https://console.aws.amazon.com/states/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-step-functions-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-step-functions-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-step-functions.yaml\n- type: Features\n  data:\n  - name: Visual Workflow\n    description: Design and visualize workflows using Amazon States Language (ASL).\n  - name: Serverless Orchestration\n    description: Orchestrate Lambda, ECS, Fargate, SNS, SQS, and 220+ AWS services.\n  - name: Error Handling\n    description: Built-in retry and catch capabilities for fault-tolerant workflows.\n  - name: Express Workflows\n    description: High-throughput workflows\
  \ for event processing at scale.\n  - name: Standard Workflows\n    description: Long-running durable workflows with exactly-once execution.\n- type: UseCases\n  data:\n  - name: Microservice Orchestration\n    description: Coordinate multiple microservices into cohesive workflows.\n  - name: Data Processing Pipelines\n    description: Build ETL and data transformation pipelines with automatic retries.\n  - name: IT Automation\n    description: Automate IT and business processes with visual workflow design.\n  - name: ML Model Training Pipelines\n    description: Orchestrate SageMaker model training, evaluation, and deployment.\n- type: Integrations\n  data:\n  - name: AWS Lambda\n    description: Invoke Lambda functions as workflow steps.\n  - name: Amazon ECS\n    description: Run ECS/Fargate tasks as part of workflows.\n  - name: Amazon DynamoDB\n    description: Read and write DynamoDB tables directly from workflows.\n  - name: Amazon SNS\n    description: Publish SNS notifications\
  \ from workflow steps.\n  - name: Amazon SageMaker\n    description: Orchestrate ML training and inference pipelines.\n  - name: AWS Glue\n    description: Run Glue ETL jobs from workflow steps.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Orchestration\n- Serverless\n- State Machine\n- Workflow\nx-type: company\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-step-functions/refs/heads/main/apis.yml
tags:
- AWS
- Orchestration
- Serverless
- State Machine
- Workflow
url: https://aws.amazon.com/step-functions/
use_cases:
- description: Coordinate multiple microservices into cohesive workflows.
  name: Microservice Orchestration
- description: Build ETL and data transformation pipelines with automatic retries.
  name: Data Processing Pipelines
- description: Automate IT and business processes with visual workflow design.
  name: IT Automation
- description: Orchestrate SageMaker model training, evaluation, and deployment.
  name: ML Model Training Pipelines
---
