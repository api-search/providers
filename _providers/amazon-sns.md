---
api_count: 1
api_specs:
- filename: amazon-sns-api-openapi.yml
  format: yaml
  label: Amazon SNS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-sns/refs/heads/main/openapi/amazon-sns-api-openapi.yml
apis:
- description: RESTful API for Amazon Simple Notification Service providing topic management, subscription lifecycle, message publishing, platform application management for mobile push, and SMS messaging operations
  name: Amazon SNS API
  slug: ''
asyncapis:
- description: 'Amazon Simple Notification Service (SNS) delivers notifications to subscribed endpoints when messages are published to topics. This AsyncAPI specification describes the notification messages that SNS '
  name: Amazon SNS Notifications
  slug: amazon-sns-notifications-asyncapi
capabilities:
- description: Pub/sub messaging workflow combining topic management, subscription lifecycle, message publishing, mobile push, and SMS operations. Used by developers and platform engineers for event-driven architect
  name: Amazon SNS Pub/Sub Messaging
  slug: pub-sub-messaging
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/messaging-and-targeting/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Console
  url: https://console.aws.amazon.com/sns/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/services-in-scope/
- title: ''
  type: Support
  url: https://console.aws.amazon.com/support/home
- title: ''
  type: KnowledgeCenter
  url: https://aws.amazon.com/premiumsupport/knowledge-center/#Amazon_Simple_Notification_Service
- title: ''
  type: Partners
  url: https://aws.amazon.com/sns/partners/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: GitHubRepository
  url: https://github.com/awsdocs/amazon-sns-developer-guide
created: '2024-01-01'
description: Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It enables pub/sub, SMS, email, and mobile push notifications.
features:
- description: Fan-out messages to multiple subscribers through topics supporting HTTP/S, email, SQS, Lambda, and SMS protocols.
  name: Pub/Sub Messaging
- description: Strict message ordering and exactly-once delivery for use cases requiring sequence-preserving fan-out.
  name: FIFO Topics
- description: Subscription filter policies enabling subscribers to receive only the messages relevant to them.
  name: Message Filtering
- description: Cross-platform mobile push via APNs, FCM, and other push services through platform applications.
  name: Mobile Push Notifications
- description: Direct SMS text messaging to phone numbers worldwide with support for transactional and promotional messages.
  name: SMS Messaging
- description: Capture undeliverable messages for analysis and reprocessing to ensure no messages are lost.
  name: Dead-Letter Queues
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Fan out SNS messages to SQS queues for reliable asynchronous processing across multiple consumers.
  name: Amazon SQS
- description: Invoke Lambda functions directly from SNS notifications for serverless event processing.
  name: AWS Lambda
- description: Route SNS events through EventBridge for complex event-driven routing and filtering.
  name: Amazon EventBridge
- description: Define and manage SNS topics and subscriptions as infrastructure-as-code resources.
  name: AWS CloudFormation
- description: Deliver SNS messages to data lakes and analytics services through Kinesis Data Firehose.
  name: Amazon Kinesis Data Firehose
jsonld:
- class_count: 0
  name: Amazon Sns Context
  property_count: 0
  slug: amazon-sns-context
layout: provider
modified: '2026-04-18'
name: Amazon SNS
rules:
- name: Amazon SNS API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: amazon-sns-spectral-rules
skills: []
slug: amazon-sns
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-sns\nname: Amazon SNS\ndescription: >-\n  Amazon Simple Notification Service (SNS) is a fully managed messaging service\n  for both application-to-application (A2A) and application-to-person (A2P)\n  communication. It enables pub/sub, SMS, email, and mobile push notifications.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-sns/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - AWS\n  - Email\n  - Messaging\n  - Notifications\n  - Pub/Sub\n  - Push Notifications\n  - SMS\napis:\n  - name: Amazon SNS API\n    description: >-\n      RESTful API for Amazon Simple Notification Service providing topic\n      management, subscription lifecycle, message publishing, platform\n      application management for mobile push, and SMS messaging operations.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \    humanURL: https://aws.amazon.com/sns/\n    baseURL: https://sns.{region}.amazonaws.com\n    tags:\n      - AWS\n      - Messaging\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/sns/\n      - type: OpenAPI\n        url: openapi/amazon-sns-api-openapi.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/sns/latest/api/welcome.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/sns/latest/dg/sns-getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/sns/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/sns/faqs/\n      - type: BestPractices\n        url: https://docs.aws.amazon.com/sns/latest/dg/sns-best-practices.html\n      - type: Features\n        url: https://aws.amazon.com/sns/features/\n      - type: Security\n        url: https://docs.aws.amazon.com/sns/latest/dg/sns-security.html\n      - type: RateLimits\n        url: https://docs.aws.amazon.com/sns/latest/dg/sns-quotas.html\n\
  \      - type: CodeExamples\n        url: https://github.com/awsdocs/aws-doc-sdk-examples\n      - type: SDK\n        url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html\n        title: Python SDK\n      - type: CLI\n        url: https://awscli.amazonaws.com/v2/documentation/api/latest/reference/sns/index.html\n    contact:\n      - FN: Amazon Web Services\n        url: https://aws.amazon.com/sns/\n        email: ''\ncommon:\n  - type: Blog\n    url: https://aws.amazon.com/blogs/messaging-and-targeting/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Console\n    url: https://console.aws.amazon.com/sns/\n  - type: Compliance\n    url: https://aws.amazon.com/compliance/services-in-scope/\n  - type: Support\n    url: https://console.aws.amazon.com/support/home\n  - type: KnowledgeCenter\n    url: https://aws.amazon.com/premiumsupport/knowledge-center/#Amazon_Simple_Notification_Service\n  - type: Partners\n    url:\
  \ https://aws.amazon.com/sns/partners/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: GitHubRepository\n    url: https://github.com/awsdocs/amazon-sns-developer-guide\n  - type: Features\n    data:\n      - name: Pub/Sub Messaging\n        description: Fan-out messages to multiple subscribers through topics supporting HTTP/S, email, SQS, Lambda, and SMS protocols.\n      - name: FIFO Topics\n        description: Strict message ordering and exactly-once delivery for use cases requiring sequence-preserving fan-out.\n      - name: Message Filtering\n        description: Subscription filter policies enabling subscribers to receive only the messages relevant to them.\n      - name: Mobile Push Notifications\n        description: Cross-platform mobile push via APNs, FCM, and other push services through platform applications.\n      - name: SMS Messaging\n        description: Direct SMS text\
  \ messaging to phone numbers worldwide with support for transactional and promotional messages.\n      - name: Dead-Letter Queues\n        description: Capture undeliverable messages for analysis and reprocessing to ensure no messages are lost.\n  - type: UseCases\n    data:\n      - name: Application Event Fan-Out\n        description: Broadcast application events to multiple microservices simultaneously using pub/sub topic subscriptions.\n      - name: Mobile Push Campaigns\n        description: Send targeted push notifications to mobile applications across iOS and Android platforms.\n      - name: Alert and Monitoring Systems\n        description: Deliver operational alerts via SMS, email, and HTTP endpoints for infrastructure monitoring.\n      - name: Order Confirmation Notifications\n        description: Send transactional notifications for order confirmations, shipping updates, and account activity.\n      - name: Cross-Account Event Distribution\n        description: Share events\
  \ across AWS accounts using SNS topic policies for multi-account architectures.\n  - type: Integrations\n    data:\n      - name: Amazon SQS\n        description: Fan out SNS messages to SQS queues for reliable asynchronous processing across multiple consumers.\n      - name: AWS Lambda\n        description: Invoke Lambda functions directly from SNS notifications for serverless event processing.\n      - name: Amazon EventBridge\n        description: Route SNS events through EventBridge for complex event-driven routing and filtering.\n      - name: AWS CloudFormation\n        description: Define and manage SNS topics and subscriptions as infrastructure-as-code resources.\n      - name: Amazon Kinesis Data Firehose\n        description: Deliver SNS messages to data lakes and analytics services through Kinesis Data Firehose.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-sns/refs/heads/main/apis.yml
tags:
- AWS
- Email
- Messaging
- Notifications
- Pub/Sub
- Push Notifications
- SMS
url: https://raw.githubusercontent.com/api-evangelist/amazon-sns/refs/heads/main/apis.yml
use_cases:
- description: Broadcast application events to multiple microservices simultaneously using pub/sub topic subscriptions.
  name: Application Event Fan-Out
- description: Send targeted push notifications to mobile applications across iOS and Android platforms.
  name: Mobile Push Campaigns
- description: Deliver operational alerts via SMS, email, and HTTP endpoints for infrastructure monitoring.
  name: Alert and Monitoring Systems
- description: Send transactional notifications for order confirmations, shipping updates, and account activity.
  name: Order Confirmation Notifications
- description: Share events across AWS accounts using SNS topic policies for multi-account architectures.
  name: Cross-Account Event Distribution
---
