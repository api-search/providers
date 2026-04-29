---
api_count: 1
apis:
- description: 'AWS Step Functions is a serverless orchestration service that lets you coordinate distributed applications and microservices using visual workflows, integrating with AWS services and supporting error '
  name: AWS Step Functions
  slug: aws-step-functions
capabilities:
- description: Workflow capability for managing state machines and executions with AWS Step Functions.
  name: AWS Step Functions Orchestration Workflow
  slug: orchestration-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/step-functions/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/step-functions/
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
  type: Pricing
  url: https://aws.amazon.com/step-functions/pricing/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/category/application-services/aws-step-functions/
- title: ''
  type: ChangeLog
  url: https://aws.amazon.com/releasenotes/aws-step-functions/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: SpectralRules
  url: rules/aws-step-functions-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-step-functions-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/orchestration-workflow.yaml
created: '2026-03-27'
description: AWS Step Functions is a serverless orchestration service that lets you coordinate distributed applications and microservices using visual workflows, integrating with AWS services and supporting error handling and retries.
features:
- description: Design and visualize workflows using the Workflow Studio drag-and-drop interface.
  name: Visual Workflow Design
- description: Define workflows in a JSON-based structured language with built-in error handling and retry logic.
  name: Amazon States Language
- description: Natively integrate with over 220 AWS services without writing custom code.
  name: AWS Service Integrations
- description: Long-running, durable workflows with exactly-once task execution semantics.
  name: Standard Workflows
- description: High-volume, short-duration workflows optimized for cost with at-least-once execution.
  name: Express Workflows
- description: Built-in retry logic and catch blocks for graceful error handling and fallback paths.
  name: Error Handling
- description: Run parallel branches simultaneously within the same state machine execution.
  name: Parallel Execution
- description: Process arrays of items in parallel using the Map state for dynamic fan-out.
  name: Map State
- description: Pause workflows waiting for external events using task tokens.
  name: Wait for Callback
- description: Built-in tracing via AWS X-Ray for end-to-end visibility into workflow executions.
  name: X-Ray Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Invoke Lambda functions as Task states in workflows.
  name: AWS Lambda
- description: Send and receive messages from SQS queues as part of workflows.
  name: Amazon SQS
- description: Read and write DynamoDB records directly from workflow states.
  name: Amazon DynamoDB
- description: Run ECS tasks and Fargate containers as workflow steps.
  name: Amazon ECS
- description: Orchestrate ML training, processing, and deployment workflows.
  name: Amazon SageMaker
- description: Trigger and monitor Glue ETL jobs from Step Functions workflows.
  name: AWS Glue
jsonld:
- class_count: 40
  name: Aws Step Functions Context
  property_count: 0
  slug: aws-step-functions-context
layout: provider
modified: '2026-04-19'
name: AWS Step Functions
rules:
- name: AWS Step Functions API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 3
  slug: aws-step-functions-spectral-rules
skills: []
slug: aws-step-functions
solutions: []
source_yaml: "aid: aws-step-functions\nname: AWS Step Functions\ndescription: >-\n  AWS Step Functions is a serverless orchestration service that lets you\n  coordinate distributed applications and microservices using visual workflows,\n  integrating with AWS services and supporting error handling and retries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - iPaaS\n  - Orchestration\n  - Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-step-functions/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-step-functions:aws-step-functions\n    name: AWS Step Functions\n    description: >-\n      AWS Step Functions is a serverless orchestration service that lets you\n      coordinate distributed applications and microservices using visual\n      workflows, integrating with AWS services and supporting error handling and\n      retries.\
  \ Define workflows in Amazon States Language with standard and\n      express workflow types.\n    humanURL: https://aws.amazon.com/step-functions/\n    baseURL: https://states.{region}.amazonaws.com\n    tags:\n      - iPaaS\n      - Orchestration\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/step-functions/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/step-functions/latest/dg/getting-started.html\n      - type: OpenAPI\n        url: openapi/aws-step-functions-openapi.json\n      - type: APIReference\n        url: https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/step-functions/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/step-functions/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n\
  \    url: https://aws.amazon.com/premiumsupport/\n  - type: Pricing\n    url: https://aws.amazon.com/step-functions/pricing/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/compute/category/application-services/aws-step-functions/\n  - type: ChangeLog\n    url: https://aws.amazon.com/releasenotes/aws-step-functions/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: SpectralRules\n    url: rules/aws-step-functions-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/aws-step-functions-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/orchestration-workflow.yaml\n  - type: Features\n    data:\n      - name: Visual Workflow Design\n        description: Design and visualize workflows using the Workflow Studio drag-and-drop interface.\n      - name: Amazon States Language\n        description: Define workflows in a JSON-based structured language with built-in error handling and retry logic.\n      - name: AWS Service Integrations\n\
  \        description: Natively integrate with over 220 AWS services without writing custom code.\n      - name: Standard Workflows\n        description: Long-running, durable workflows with exactly-once task execution semantics.\n      - name: Express Workflows\n        description: High-volume, short-duration workflows optimized for cost with at-least-once execution.\n      - name: Error Handling\n        description: Built-in retry logic and catch blocks for graceful error handling and fallback paths.\n      - name: Parallel Execution\n        description: Run parallel branches simultaneously within the same state machine execution.\n      - name: Map State\n        description: Process arrays of items in parallel using the Map state for dynamic fan-out.\n      - name: Wait for Callback\n        description: Pause workflows waiting for external events using task tokens.\n      - name: X-Ray Integration\n        description: Built-in tracing via AWS X-Ray for end-to-end visibility into\
  \ workflow executions.\n  - type: UseCases\n    data:\n      - name: Microservice Orchestration\n        description: Coordinate multiple microservices in a reliable, fault-tolerant workflow.\n      - name: Data Processing Pipelines\n        description: Build ETL pipelines that process data in parallel across multiple services.\n      - name: Human Approval Workflows\n        description: Implement approval workflows that wait for human decisions via task tokens.\n      - name: Event-Driven Automation\n        description: Automate complex multi-step processes triggered by events.\n      - name: Machine Learning Pipelines\n        description: Orchestrate ML model training, evaluation, and deployment using SageMaker integrations.\n  - type: Integrations\n    data:\n      - name: AWS Lambda\n        description: Invoke Lambda functions as Task states in workflows.\n      - name: Amazon SQS\n        description: Send and receive messages from SQS queues as part of workflows.\n      - name:\
  \ Amazon DynamoDB\n        description: Read and write DynamoDB records directly from workflow states.\n      - name: Amazon ECS\n        description: Run ECS tasks and Fargate containers as workflow steps.\n      - name: Amazon SageMaker\n        description: Orchestrate ML training, processing, and deployment workflows.\n      - name: AWS Glue\n        description: Trigger and monitor Glue ETL jobs from Step Functions workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-step-functions/refs/heads/main/apis.yml
tags:
- AWS
- iPaaS
- Orchestration
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/aws-step-functions/refs/heads/main/apis.yml
use_cases:
- description: Coordinate multiple microservices in a reliable, fault-tolerant workflow.
  name: Microservice Orchestration
- description: Build ETL pipelines that process data in parallel across multiple services.
  name: Data Processing Pipelines
- description: Implement approval workflows that wait for human decisions via task tokens.
  name: Human Approval Workflows
- description: Automate complex multi-step processes triggered by events.
  name: Event-Driven Automation
- description: Orchestrate ML model training, evaluation, and deployment using SageMaker integrations.
  name: Machine Learning Pipelines
---
