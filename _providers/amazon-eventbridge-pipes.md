---
api_count: 1
api_specs:
- filename: amazon-eventbridge-pipes-openapi.yml
  format: yaml
  label: Amazon EventBridge Pipes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-pipes/refs/heads/main/openapi/amazon-eventbridge-pipes-openapi.yml
apis:
- description: API for creating and managing pipes that connect event sources to targets with optional filtering, enrichment, and transformation capabilities.
  name: Amazon EventBridge Pipes API
  slug: ''
capabilities:
- description: Unified capability for managing Amazon EventBridge Pipes resources. Combines Amazon EventBridge Pipes APIs for Integration Engineer workflows in Event Processing.
  name: Amazon EventBridge Pipes Management
  slug: amazon-eventbridge-pipes-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/eventbridge/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/eventbridge/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/events/
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
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/eventbridge/faqs/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/eventbridge
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-eventbridge-pipes-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-eventbridge-pipes-capability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-eventbridge-pipes-vocabulary.yaml
created: '2024-01-15'
description: Amazon EventBridge Pipes helps you create point-to-point integrations between event producers and consumers with optional transform, filter, and enrich steps. It reduces the amount of integration code you need to write and maintain when building event-driven applications.
features:
- description: Connect event sources directly to targets with minimal code
  name: Point-to-Point Integration
- description: Filter events before processing to reduce costs and noise
  name: Event Filtering
- description: Enrich events with data from Lambda, Step Functions, or API destinations
  name: Event Enrichment
- description: Transform event payloads using input transformers
  name: Event Transformation
- description: Process events in batches for improved throughput
  name: Batching Support
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Use DynamoDB Streams as an event source
  name: Amazon DynamoDB Streams
- description: Connect SQS queues as event sources or targets
  name: Amazon SQS
- description: Process Kinesis data stream events
  name: Amazon Kinesis
- description: Use Lambda as enrichment or target for pipe events
  name: AWS Lambda
- description: Connect Apache Kafka and Amazon MSK as event sources
  name: Apache Kafka
jsonld:
- class_count: 83
  name: Amazon Eventbridge Pipes Context
  property_count: 130
  slug: amazon-eventbridge-pipes-context
layout: provider
modified: '2026-04-19'
name: Amazon EventBridge Pipes
rules:
- name: Amazon EventBridge Pipes API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-eventbridge-pipes-spectral-rules
skills: []
slug: amazon-eventbridge-pipes
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon EventBridge Pipes\ndescription: Amazon EventBridge Pipes helps you create point-to-point integrations between event producers and consumers with optional transform, filter, and enrich steps. It reduces the amount of \n  integration code you need to write and maintain when building event-driven applications.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/eventbridge/pipes/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Amazon Web Services\n- AWS\n- Event-Driven\n- Integration\n- Messaging\n- Serverless\napis:\n- name: Amazon EventBridge Pipes API\n  description: API for creating and managing pipes that connect event sources to targets with optional filtering, enrichment, and transformation capabilities.\n  humanURL: https://aws.amazon.com/eventbridge/pipes/\n  baseURL: https://pipes.amazonaws.com\n  tags:\n  - Event-Driven\n  - Integration\n  - Messaging\n \
  \ - Serverless\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes.html\n  - type: OpenAPI\n    url: openapi/amazon-eventbridge-pipes-openapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/eventbridge/latest/pipes-reference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/eventbridge/pipes/\n  - type: Pricing\n    url: https://aws.amazon.com/eventbridge/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/eventbridge/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-eventbridge-pipes-arn-or-json-path-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-eventbridge-pipes-arn-or-url-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-eventbridge-pipes-arn-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-eventbridge-pipes-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/eventbridge/\n\
  - type: Documentation\n  url: https://docs.aws.amazon.com/eventbridge/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/events/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: FAQ\n  url: https://aws.amazon.com/eventbridge/faqs/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/eventbridge\n- type: KnowledgeCenter\n\
  \  url: https://repost.aws/knowledge-center\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-eventbridge-pipes-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-eventbridge-pipes-capability.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/api.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-eventbridge-pipes-vocabulary.yaml\n- type: Features\n  data:\n  - name: Point-to-Point Integration\n    description: Connect event sources directly to targets with minimal code\n  - name: Event Filtering\n    description: Filter events before processing to reduce costs and noise\n  - name: Event Enrichment\n    description: Enrich events with data from Lambda, Step Functions, or API destinations\n  - name: Event Transformation\n    description: Transform event payloads using input transformers\n  - name: Batching Support\n    description: Process events in batches for improved throughput\n- type: UseCases\n \
  \ data:\n  - name: Database Change Data Capture\n    description: Stream DynamoDB or Aurora changes to downstream systems\n  - name: Queue Processing\n    description: Connect SQS queues to Lambda or Step Functions for message processing\n  - name: Stream Analytics\n    description: Process Kinesis or Kafka streams with filtering and enrichment\n  - name: SaaS Integration\n    description: Connect SaaS event sources to AWS targets without custom code\n- type: Integrations\n  data:\n  - name: Amazon DynamoDB Streams\n    description: Use DynamoDB Streams as an event source\n  - name: Amazon SQS\n    description: Connect SQS queues as event sources or targets\n  - name: Amazon Kinesis\n    description: Process Kinesis data stream events\n  - name: AWS Lambda\n    description: Use Lambda as enrichment or target for pipe events\n  - name: Apache Kafka\n    description: Connect Apache Kafka and Amazon MSK as event sources\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-pipes/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- AWS
- Event-Driven
- Integration
- Messaging
- Serverless
url: https://aws.amazon.com/eventbridge/pipes/
use_cases:
- description: Stream DynamoDB or Aurora changes to downstream systems
  name: Database Change Data Capture
- description: Connect SQS queues to Lambda or Step Functions for message processing
  name: Queue Processing
- description: Process Kinesis or Kafka streams with filtering and enrichment
  name: Stream Analytics
- description: Connect SaaS event sources to AWS targets without custom code
  name: SaaS Integration
---
