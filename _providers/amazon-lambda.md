---
api_count: 1
api_specs:
- filename: amazon-lambda-openapi.yml
  format: yaml
  label: Amazon Lambda API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lambda/refs/heads/main/openapi/amazon-lambda-openapi.yml
apis:
- description: Core API for managing AWS Lambda functions, event source mappings, layers, aliases, versions, and permissions. Enables creating and invoking serverless functions, configuring triggers from AWS service
  name: Amazon Lambda API
  slug: ''
capabilities:
- description: Unified workflow capability for Amazon Lambda combining resource management and operations.
  name: Amazon Lambda Workflow
  slug: amazon-lambda-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Portal
  url: https://aws.amazon.com/lambda/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/lambda/
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
  url: https://aws.amazon.com/blogs/compute/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/lambda/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Knowledge Center
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/aws-lambda
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/lambda/latest/dg/lambda-security.html
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-lambda-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-lambda-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-lambda-vocabulary.yaml
created: '2024-01-15'
description: AWS Lambda is a serverless compute service that lets you run code without provisioning or managing servers, automatically scaling and executing your code in response to events from over 200 AWS services and SaaS applications while you pay only for the compute time you consume.
features:
- description: Run code without provisioning or managing servers — Lambda handles all administration.
  name: Serverless Execution
- description: Automatically trigger code from over 200 AWS services and SaaS applications.
  name: Event-Driven Triggers
- description: Automatically scales to thousands of concurrent executions without configuration.
  name: Automatic Scaling
- description: Supports Node.js, Python, Java, Go, Ruby, .NET, and custom runtimes via Lambda layers.
  name: Multiple Runtimes
- description: Package and share code, libraries, and configurations across Lambda functions.
  name: Lambda Layers
- description: Deploy Lambda functions as container images up to 10 GB in size.
  name: Container Image Support
- description: Reduce cold starts for Java functions with Lambda SnapStart.
  name: SnapStart
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Build REST and WebSocket APIs backed by Lambda functions.
  name: Amazon API Gateway
- description: Trigger Lambda from DynamoDB Streams for real-time data processing.
  name: Amazon DynamoDB
- description: Trigger Lambda on S3 object events for serverless file processing.
  name: Amazon S3
- description: Process Kinesis data streams with Lambda for real-time analytics.
  name: Amazon Kinesis
- description: Orchestrate Lambda functions in serverless workflows.
  name: AWS Step Functions
- description: Process SQS messages with Lambda for decoupled event processing.
  name: Amazon SQS
jsonld:
- class_count: 2
  name: Amazon Lambda Context
  property_count: 7
  slug: amazon-lambda-context
layout: provider
modified: '2026-04-19'
name: Amazon Lambda
rules:
- name: Amazon Lambda API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-lambda-spectral-rules
skills: []
slug: amazon-lambda
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Lambda\ndescription: AWS Lambda is a serverless compute service that lets you run code without provisioning or managing servers, automatically scaling and executing your code in response to events from over \n  200 AWS services and SaaS applications while you pay only for the compute time you consume.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/lambda/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Lambda API\n  description: >-\n    Core API for managing AWS Lambda functions, event source mappings, layers,\n    aliases, versions, and permissions. Enables creating and invoking serverless\n    functions, configuring triggers from AWS services, and managing function\n    deployment packages and runtime configurations.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/lambda/\n  baseURL: https://lambda.amazonaws.com\n\
  \  tags:\n  - AWS\n  - Compute\n  - Event-Driven\n  - Functions\n  - Serverless\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/lambda/latest/dg/welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-lambda-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/lambda/2015-03-31/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-lambda-function-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-lambda-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/lambda/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/lambda/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/lambda/latest/dg/lambda-auth-and-access-control.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: Status\n    url: https://status.aws.amazon.com/\n  - type: Best Practices\n    url: https://docs.aws.amazon.com/lambda/latest/dg/best-practices.html\n  - type: FAQ\n\
  \    url: https://aws.amazon.com/lambda/faqs/\n  - type: Service Level Agreement\n    url: https://aws.amazon.com/lambda/sla/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/lambda/latest/dg/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/lambda/latest/api/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/lambda/\n  - type: Security\n    url: https://docs.aws.amazon.com/lambda/latest/dg/lambda-security.html\n  - type: JSONSchema\n    url: json-schema/amazon-lambda-event-source-mapping-schema.json\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Portal\n  url: https://aws.amazon.com/lambda/\n- type: Documentation\n  url: https://docs.aws.amazon.com/lambda/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/\n- type: GitHubOrganization\n\
  \  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/lambda/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/aws-lambda\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Security\n  url: https://docs.aws.amazon.com/lambda/latest/dg/lambda-security.html\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Features\n  data:\n  - name: Serverless Execution\n    description: Run code without provisioning or managing servers — Lambda handles all administration.\n  - name: Event-Driven Triggers\n    description: Automatically trigger code from over 200\
  \ AWS services and SaaS applications.\n  - name: Automatic Scaling\n    description: Automatically scales to thousands of concurrent executions without configuration.\n  - name: Multiple Runtimes\n    description: Supports Node.js, Python, Java, Go, Ruby, .NET, and custom runtimes via Lambda layers.\n  - name: Lambda Layers\n    description: Package and share code, libraries, and configurations across Lambda functions.\n  - name: Container Image Support\n    description: Deploy Lambda functions as container images up to 10 GB in size.\n  - name: SnapStart\n    description: Reduce cold starts for Java functions with Lambda SnapStart.\n- type: UseCases\n  data:\n  - name: API Backends\n    description: Build REST and GraphQL API backends with Lambda and API Gateway.\n  - name: Data Processing\n    description: Process S3 uploads, DynamoDB streams, and Kinesis records in real time.\n  - name: Event Automation\n    description: Automate operational tasks triggered by CloudWatch events or schedules.\n\
  \  - name: Machine Learning Inference\n    description: Run ML model inference on-demand without managing inference infrastructure.\n- type: Integrations\n  data:\n  - name: Amazon API Gateway\n    description: Build REST and WebSocket APIs backed by Lambda functions.\n  - name: Amazon DynamoDB\n    description: Trigger Lambda from DynamoDB Streams for real-time data processing.\n  - name: Amazon S3\n    description: Trigger Lambda on S3 object events for serverless file processing.\n  - name: Amazon Kinesis\n    description: Process Kinesis data streams with Lambda for real-time analytics.\n  - name: AWS Step Functions\n    description: Orchestrate Lambda functions in serverless workflows.\n  - name: Amazon SQS\n    description: Process SQS messages with Lambda for decoupled event processing.\n- type: SpectralRules\n  url: rules/amazon-lambda-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-lambda-workflow.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-lambda-vocabulary.yaml\n\
  maintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Compute\n- Event-Driven\n- FaaS\n- Functions\n- Serverless\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-lambda/refs/heads/main/apis.yml
tags:
- Compute
- Event-Driven
- FaaS
- Functions
- Serverless
url: https://aws.amazon.com/lambda/
use_cases:
- description: Build REST and GraphQL API backends with Lambda and API Gateway.
  name: API Backends
- description: Process S3 uploads, DynamoDB streams, and Kinesis records in real time.
  name: Data Processing
- description: Automate operational tasks triggered by CloudWatch events or schedules.
  name: Event Automation
- description: Run ML model inference on-demand without managing inference infrastructure.
  name: Machine Learning Inference
---
