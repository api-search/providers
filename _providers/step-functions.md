---
api_count: 1
api_specs:
- filename: step-functions-openapi.yml
  format: yaml
  label: AWS Step Functions API
  slug: step-functions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/openapi/step-functions-openapi.yml
apis:
- description: The AWS Step Functions API enables creating, managing, and executing state machines and activities. Key operations include creating and deleting state machines, starting and stopping executions, listi
  name: AWS Step Functions API
  slug: step-functions
capabilities:
- description: Workflow orchestration capabilities using AWS Step Functions for building, deploying, and monitoring state machine-based distributed applications. Covers the full lifecycle from state machine creation
  name: AWS Step Functions Workflow Orchestration
  slug: workflow-orchestration
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/step-functions/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/step-functions/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/states/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/step-functions/pricing/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/category/compute/aws-step-functions/
created: '2026-03-27'
description: AWS Step Functions is a serverless orchestration service that enables developers to compose distributed applications and APIs using visual workflows called state machines. It supports Standard and Express workflows, activities, parallel execution, error handling, and integrates with over 200 AWS services. Step Functions uses the Amazon States Language (ASL) for defining workflow logic as JSON-based state machine definitions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 16
  name: Step Functions Context
  property_count: 8
  slug: step-functions-context
layout: provider
modified: '2026-05-02'
name: AWS Step Functions
rules:
- name: AWS Step Functions API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: step-functions-rules
skills: []
slug: step-functions
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: step-functions\nname: AWS Step Functions\ndescription: >-\n  AWS Step Functions is a serverless orchestration service that enables\n  developers to compose distributed applications and APIs using visual\n  workflows called state machines. It supports Standard and Express workflows,\n  activities, parallel execution, error handling, and integrates with over\n  200 AWS services. Step Functions uses the Amazon States Language (ASL)\n  for defining workflow logic as JSON-based state machine definitions.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Composition\n  - Serverless Orchestration\n  - Workflow\n  - AWS\n  - State Machine\n  - Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: step-functions:step-functions\n    name: AWS Step Functions API\n    description:\
  \ >-\n      The AWS Step Functions API enables creating, managing, and executing\n      state machines and activities. Key operations include creating and\n      deleting state machines, starting and stopping executions, listing\n      execution history, managing state machine versions and aliases,\n      tagging resources, and sending task heartbeats from activity workers.\n      The API uses AWS Signature Version 4 (SigV4) authentication.\n    humanURL: https://aws.amazon.com/step-functions/\n    baseURL: https://states.{region}.amazonaws.com\n    tags:\n      - Serverless\n      - Workflow\n      - State Machine\n      - Orchestration\n      - AWS\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/step-functions/\n      - type: Reference\n        url: https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html\n      - type: Getting Started\n        url: https://docs.aws.amazon.com/step-functions/latest/dg/getting-started.html\n \
  \     - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/openapi/step-functions-openapi.yml\n      - type: Pricing\n        url: https://aws.amazon.com/step-functions/pricing/\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/step-functions/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/step-functions/\n  - type: GitHub Organization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/states/\n  - type: Pricing\n    url: https://aws.amazon.com/step-functions/pricing/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/compute/category/compute/aws-step-functions/\nfeatures:\n  - name: Standard Workflows\n    description: Long-running, durable state machines with exactly-once execution semantics\n  - name: Express Workflows\n    description: High-volume, event-driven workflows with at-least-once execution\n  - name: State Machine Versioning\n   \
  \ description: Publish, manage, and deploy versioned state machine definitions\n  - name: State Machine Aliases\n    description: Create aliases (e.g., PROD, STAGING) pointing to specific state machine versions\n  - name: Activity Workers\n    description: Poll for and process work items from Step Functions activity queues\n  - name: AWS Service Integrations\n    description: Direct integrations with 200+ AWS services via optimized and SDK integrations\n  - name: Map State\n    description: Parallel iteration over input arrays with distributed map for large-scale processing\n  - name: X-Ray Tracing\n    description: Built-in AWS X-Ray integration for distributed tracing of workflow executions\n  - name: CloudWatch Logging\n    description: Configurable execution history logging to CloudWatch Logs\n  - name: KMS Encryption\n    description: Customer-managed KMS key encryption for state machine definitions and execution history\nuseCases:\n  - name: Microservice Orchestration\n    description:\
  \ Coordinate calls across multiple microservices with error handling and retries\n  - name: Data Processing Pipelines\n    description: Build ETL and ML data pipelines with parallel processing and error recovery\n  - name: Human Approval Workflows\n    description: Pause state machine execution waiting for human approval via callback tokens\n  - name: Event-Driven Automation\n    description: React to AWS events and automate operational workflows\n  - name: API Gateway Integration\n    description: Expose Step Functions workflows as REST APIs via API Gateway integration\nintegrations:\n  - name: AWS Lambda\n    description: Invoke Lambda functions as tasks in workflow state machines\n  - name: Amazon SQS\n    description: Send and receive messages from SQS queues in workflows\n  - name: Amazon SNS\n    description: Publish notifications to SNS topics from state machines\n  - name: Amazon DynamoDB\n    description: Read and write DynamoDB items directly from state machines\n  - name: Amazon\
  \ ECS/Fargate\n    description: Run containerized tasks as workflow steps\n  - name: AWS Glue\n    description: Trigger Glue ETL jobs from state machine executions\n  - name: Amazon SageMaker\n    description: Train and deploy ML models via SageMaker integrations\n  - name: Amazon API Gateway\n    description: Expose Step Functions as HTTP REST APIs\nsolutions:\n  - name: Serverless Orchestration\n    description: Coordinate serverless function chains without managing servers\n  - name: Workflow Automation\n    description: Automate complex business processes with visual workflow design\n  - name: Distributed Systems Coordination\n    description: Manage distributed application state with built-in error handling\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/apis.yml
tags:
- API Composition
- Serverless Orchestration
- Workflow
- State Machine
- Automation
url: https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/apis.yml
use_cases: []
---
