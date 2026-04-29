---
api_count: 1
api_specs:
- filename: amazon-sqs-openapi.yml
  format: yaml
  label: Amazon SQS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-sqs/refs/heads/main/openapi/amazon-sqs-openapi.yml
apis:
- description: RESTful API for Amazon Simple Queue Service operations including queue management, message sending and receiving, batch operations, dead-letter queues, and access control.
  name: Amazon SQS API
  slug: ''
asyncapis:
- description: AsyncAPI specification for Amazon SQS event-driven messaging patterns. Amazon SQS provides reliable, highly-scalable hosted queues for storing messages as they travel between applications or microserv
  name: Amazon Simple Queue Service (SQS) Event Source Mapping
  slug: amazon-sqs-asyncapi
capabilities:
- description: Message queuing workflow for managing SQS queues, sending and receiving messages, batch operations, dead-letter queue management, and access control. Used by developers and DevOps engineers for micros
  name: Amazon SQS Message Queuing
  slug: message-queuing
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/sqs/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://console.aws.amazon.com/support/home
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: CodeExamples
  url: https://docs.aws.amazon.com/code-library/latest/ug/sqs_code_examples.html
- title: ''
  type: GitHubRepository
  url: https://github.com/awsdocs/aws-doc-sdk-examples
created: '2024-01-01'
description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
features:
- description: Maximum throughput, best-effort ordering, and at-least-once delivery for high-volume messaging workloads.
  name: Standard Queues
- description: Exactly-once processing and strict ordering guarantees for applications requiring message sequence preservation.
  name: FIFO Queues
- description: Automatic routing of failed messages to dead-letter queues for debugging and reprocessing.
  name: Dead-Letter Queues
- description: Bulk movement of messages between queues for reprocessing dead-letter queue contents.
  name: Message Move Tasks
- description: Automatic encryption of messages at rest using AWS KMS keys for data protection.
  name: Server-Side Encryption
- description: Reduced API costs and latency by allowing consumers to wait for messages to arrive before responding.
  name: Long Polling
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Automatically invoke Lambda functions when messages arrive in SQS queues for serverless processing.
  name: AWS Lambda
- description: Fan out SNS notifications to multiple SQS queues for parallel processing of published messages.
  name: Amazon SNS
- description: Route events from EventBridge to SQS queues for reliable event-driven architectures.
  name: Amazon EventBridge
- description: Provision and manage SQS queues as infrastructure-as-code using CloudFormation templates.
  name: AWS CloudFormation
- description: Create and manage SQS resources using HashiCorp Terraform infrastructure-as-code provider.
  name: Terraform
jsonld:
- class_count: 0
  name: Amazon Sqs Context
  property_count: 0
  slug: amazon-sqs-context
layout: provider
modified: '2026-04-18'
name: Amazon SQS
rules:
- name: Amazon SQS API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: amazon-sqs-spectral-rules
skills: []
slug: amazon-sqs
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-sqs\nname: Amazon SQS\ndescription: >-\n  Amazon Simple Queue Service (SQS) is a fully managed message queuing service\n  that enables you to decouple and scale microservices, distributed systems, and\n  serverless applications.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-sqs/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - AWS\n  - Cloud\n  - Distributed Systems\n  - Messaging\n  - Microservices\n  - Queue\napis:\n  - name: Amazon SQS API\n    description: >-\n      RESTful API for Amazon Simple Queue Service operations including queue\n      management, message sending and receiving, batch operations, dead-letter\n      queues, and access control.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/sqs/\n    baseURL:\
  \ https://sqs.{region}.amazonaws.com/\n    tags:\n      - AWS\n      - Messaging\n      - Queue\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/sqs/\n      - type: OpenAPI\n        url: openapi/amazon-sqs-openapi.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/APIReference/\n      - type: GettingStarted\n        url: https://aws.amazon.com/sqs/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/sqs/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/sqs/faqs/\n      - type: BestPractices\n        url: https://docs.aws.amazon.com/sqs/latest/dg/best-practices.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n      - type: Tutorials\n        url: https://docs.aws.amazon.com/sqs/latest/dg/sqs-tutorials.html\n      - type: Features\n        url: https://aws.amazon.com/sqs/features/\n      - type: Security\n        url: https://docs.aws.amazon.com/sqs/latest/dg/sqs-security.html\n\
  \      - type: Compliance\n        url: https://aws.amazon.com/compliance/services-in-scope/\n      - type: CLI\n        url: https://docs.aws.amazon.com/cli/latest/reference/sqs/\n      - type: CodeExamples\n        url: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/service_code_examples.html\n      - type: RateLimits\n        url: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-quotas.html\n      - type: Regions\n        url: https://docs.aws.amazon.com/general/latest/gr/sqs-service.html\n      - type: ReleaseNotes\n        url: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-release-notes.html\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n        email: ''\ncommon:\n  - type: Blog\n    url: https://aws.amazon.com/blogs/compute/\n  - type: Console\n    url: https://console.aws.amazon.com/sqs/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n\
  \  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://console.aws.amazon.com/support/home\n  - type: KnowledgeCenter\n    url: https://repost.aws/knowledge-center\n  - type: CodeExamples\n    url: https://docs.aws.amazon.com/code-library/latest/ug/sqs_code_examples.html\n  - type: GitHubRepository\n    url: https://github.com/awsdocs/aws-doc-sdk-examples\n  - type: Features\n    data:\n      - name: Standard Queues\n        description: Maximum throughput, best-effort ordering, and at-least-once delivery for high-volume messaging workloads.\n      - name: FIFO Queues\n        description: Exactly-once processing and strict ordering guarantees for applications requiring message sequence preservation.\n      - name: Dead-Letter Queues\n        description: Automatic routing of failed messages to dead-letter queues for debugging and reprocessing.\n      - name: Message\
  \ Move Tasks\n        description: Bulk movement of messages between queues for reprocessing dead-letter queue contents.\n      - name: Server-Side Encryption\n        description: Automatic encryption of messages at rest using AWS KMS keys for data protection.\n      - name: Long Polling\n        description: Reduced API costs and latency by allowing consumers to wait for messages to arrive before responding.\n  - type: UseCases\n    data:\n      - name: Microservices Decoupling\n        description: Decouple microservices by using SQS queues as asynchronous communication buffers between services.\n      - name: Serverless Event Processing\n        description: Trigger AWS Lambda functions from SQS messages for event-driven serverless architectures.\n      - name: Order Processing Pipelines\n        description: Use FIFO queues to ensure ordered processing of e-commerce orders and financial transactions.\n      - name: Work Queue Distribution\n        description: Distribute compute-intensive\
  \ tasks across multiple workers using standard queues for parallel processing.\n      - name: Batch Job Orchestration\n        description: Queue batch processing jobs and manage their execution across distributed compute resources.\n  - type: Integrations\n    data:\n      - name: AWS Lambda\n        description: Automatically invoke Lambda functions when messages arrive in SQS queues for serverless processing.\n      - name: Amazon SNS\n        description: Fan out SNS notifications to multiple SQS queues for parallel processing of published messages.\n      - name: Amazon EventBridge\n        description: Route events from EventBridge to SQS queues for reliable event-driven architectures.\n      - name: AWS CloudFormation\n        description: Provision and manage SQS queues as infrastructure-as-code using CloudFormation templates.\n      - name: Terraform\n        description: Create and manage SQS resources using HashiCorp Terraform infrastructure-as-code provider.\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-sqs/refs/heads/main/apis.yml
tags:
- AWS
- Cloud
- Distributed Systems
- Messaging
- Microservices
- Queue
url: https://raw.githubusercontent.com/api-evangelist/amazon-sqs/refs/heads/main/apis.yml
use_cases:
- description: Decouple microservices by using SQS queues as asynchronous communication buffers between services.
  name: Microservices Decoupling
- description: Trigger AWS Lambda functions from SQS messages for event-driven serverless architectures.
  name: Serverless Event Processing
- description: Use FIFO queues to ensure ordered processing of e-commerce orders and financial transactions.
  name: Order Processing Pipelines
- description: Distribute compute-intensive tasks across multiple workers using standard queues for parallel processing.
  name: Work Queue Distribution
- description: Queue batch processing jobs and manage their execution across distributed compute resources.
  name: Batch Job Orchestration
---
