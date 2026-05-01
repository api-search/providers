---
api_count: 1
api_specs:
- filename: amazon-eventbridge-openapi.yml
  format: yaml
  label: Amazon EventBridge API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge/refs/heads/main/openapi/amazon-eventbridge-openapi.yml
apis:
- description: API for creating and managing event buses, rules, targets, and connections for routing events across applications, microservices, and SaaS integrations.
  name: Amazon EventBridge API
  slug: ''
asyncapis:
- description: Amazon EventBridge delivers events from event sources to targets based on rules you define. This AsyncAPI specification documents the event channels and message schemas for events delivered by EventBr
  name: Amazon EventBridge Event Delivery
  slug: amazon-eventbridge-asyncapi
capabilities:
- description: Unified capability for managing Amazon EventBridge resources. Combines Amazon EventBridge APIs for Integration Engineer workflows in Event-Driven Architecture.
  name: Amazon EventBridge Management
  slug: amazon-eventbridge-capability
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
  url: rules/amazon-eventbridge-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-eventbridge-capability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-eventbridge-vocabulary.yaml
created: '2024-01-15'
description: Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources. EventBridge delivers a stream of real-time data from your own applications, SaaS applications, and AWS services and routes that data to targets such as Lambda, SNS, SQS, and more.
features:
- description: Central event bus for routing events between AWS services and applications
  name: Event Bus
- description: Create rules to filter and route events to specific targets
  name: Event Rules
- description: Discover, create, and manage event schemas with code binding generation
  name: Schema Registry
- description: Receive events from SaaS partners like Zendesk, Datadog, and PagerDuty
  name: SaaS Integrations
- description: Send events to external HTTP endpoints via API Destinations
  name: API Destinations
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Invoke Lambda functions in response to events
  name: AWS Lambda
- description: Fan out events to multiple subscribers via SNS topics
  name: Amazon SNS
- description: Queue events for reliable processing with SQS
  name: Amazon SQS
- description: Start state machine executions in response to events
  name: AWS Step Functions
- description: Receive Zendesk support ticket and activity events
  name: Zendesk
jsonld:
- class_count: 5
  name: Amazon Eventbridge Context
  property_count: 9
  slug: amazon-eventbridge-context
layout: provider
modified: '2026-04-19'
name: Amazon EventBridge
rules:
- name: Amazon EventBridge API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-eventbridge-spectral-rules
skills: []
slug: amazon-eventbridge
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon EventBridge\ndescription: Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources. EventBridge delivers a stream of real-time data \n  from your own applications, SaaS applications, and AWS services and routes that data to targets such as Lambda, SNS, SQS, and more.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/eventbridge/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Amazon Web Services\n- AWS\n- Event Bus\n- Event-Driven\n- Events\n- Integration\n- Serverless\napis:\n- name: Amazon EventBridge API\n  description: API for creating and managing event buses, rules, targets, and connections for routing events across applications, microservices, and SaaS integrations.\n  humanURL: https://aws.amazon.com/eventbridge/\n  baseURL: https://events.amazonaws.com\n  tags:\n  - Event Bus\n\
  \  - Event-Driven\n  - Events\n  - Serverless\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/eventbridge/latest/userguide/\n  - type: OpenAPI\n    url: openapi/amazon-eventbridge-openapi.yml\n  - type: AsyncAPI\n    url: asyncapi/amazon-eventbridge-asyncapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/eventbridge/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/eventbridge/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/eventbridge/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/eventbridge/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-eventbridge-create-archive-request-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-eventbridge-create-archive-response-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-eventbridge-create-event-bus-request-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-eventbridge-context.jsonld\ncommon:\n- type:\
  \ Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/eventbridge/\n- type: Documentation\n  url: https://docs.aws.amazon.com/eventbridge/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/events/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: FAQ\n  url: https://aws.amazon.com/eventbridge/faqs/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n\
  - type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/eventbridge\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-eventbridge-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-eventbridge-capability.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/api.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-eventbridge-vocabulary.yaml\n- type: Features\n  data:\n  - name: Event Bus\n    description: Central event bus for routing events between AWS services and applications\n  - name: Event Rules\n    description: Create rules to filter and route events to specific targets\n  - name: Schema Registry\n    description: Discover, create, and manage event schemas with code binding generation\n  - name: SaaS Integrations\n    description: Receive events from SaaS partners like Zendesk, Datadog, and PagerDuty\n  - name: API\
  \ Destinations\n    description: Send events to external HTTP endpoints via API Destinations\n- type: UseCases\n  data:\n  - name: Microservices Decoupling\n    description: Decouple microservices by routing events through a central event bus\n  - name: Application Monitoring\n    description: React to CloudWatch alarms and AWS service events in real time\n  - name: SaaS Event Processing\n    description: Receive and process events from SaaS applications without polling\n  - name: Multi-Account Event Routing\n    description: Route events across AWS accounts and regions for enterprise architectures\n- type: Integrations\n  data:\n  - name: AWS Lambda\n    description: Invoke Lambda functions in response to events\n  - name: Amazon SNS\n    description: Fan out events to multiple subscribers via SNS topics\n  - name: Amazon SQS\n    description: Queue events for reliable processing with SQS\n  - name: AWS Step Functions\n    description: Start state machine executions in response to events\n\
  \  - name: Zendesk\n    description: Receive Zendesk support ticket and activity events\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- Event Bus
- Event-Driven
- Events
- Integration
- Serverless
url: https://aws.amazon.com/eventbridge/
use_cases:
- description: Decouple microservices by routing events through a central event bus
  name: Microservices Decoupling
- description: React to CloudWatch alarms and AWS service events in real time
  name: Application Monitoring
- description: Receive and process events from SaaS applications without polling
  name: SaaS Event Processing
- description: Route events across AWS accounts and regions for enterprise architectures
  name: Multi-Account Event Routing
---
