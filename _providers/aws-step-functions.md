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
