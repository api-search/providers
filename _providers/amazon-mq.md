---
api_count: 1
apis:
- description: Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it easy to set up and operate message brokers in the cloud, enabling you to migrate to a message broker withou
  name: Amazon MQ API
  slug: mq-api
capabilities:
- description: Workflow capability for Amazon MQ media processing operations for broadcast engineers and media developers.
  name: Amazon MQ Workflow
  slug: amazon-mq-media-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/mq/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/mq/
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
  url: https://aws.amazon.com/blogs/media/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/mq/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-mq-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-mq-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-mq-media-workflow.yaml
created: '2026-03-16'
description: Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it easy to set up and operate message brokers in the cloud, enabling you to migrate to a message broker without writing the code that typically enables interoperability with existing applications.
features:
- description: Fully managed Apache ActiveMQ and RabbitMQ brokers with automated provisioning and maintenance.
  name: Managed Message Brokers
- description: Supports AMQP, MQTT, OpenWire, STOMP, and WebSocket protocols for broad compatibility.
  name: Protocol Support
- description: Active/standby configurations with automatic failover for high availability.
  name: High Availability
- description: Create networks of brokers for distributed messaging across regions and availability zones.
  name: Network of Brokers
- description: Programmatically create, configure, and manage brokers and configurations.
  name: Broker Management API
- description: Encryption at rest and in transit, VPC isolation, and IAM integration.
  name: Security
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy brokers within a VPC for network isolation and security.
  name: Amazon VPC
- description: Monitor broker metrics, queue depths, and consumer lag.
  name: Amazon CloudWatch
- description: Encrypt broker data at rest using AWS KMS keys.
  name: AWS KMS
- description: Control access to Amazon MQ resources with IAM policies.
  name: AWS IAM
- description: Provision and manage brokers using CloudFormation templates.
  name: Amazon CloudFormation
jsonld:
- class_count: 76
  name: Amazon Mq Mq Api Context
  property_count: 84
  slug: amazon-mq-mq-api-context
layout: provider
modified: '2026-04-19'
name: Amazon MQ
rules:
- name: Amazon MQ API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 7
  slug: amazon-mq-spectral-rules
skills: []
slug: amazon-mq
solutions: []
source_yaml: "aid: amazon-mq\nname: Amazon MQ\ndescription: Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it easy to set up and operate message brokers in the cloud, enabling you to migrate to a message \n  broker without writing the code that typically enables interoperability with existing applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Broadcasting\n- Media Processing\n- Media\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-mq/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-mq:mq-api\n  name: Amazon MQ API\n  description: Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it easy to set up and operate message brokers in the cloud, enabling you to migrate to a \n    message broker without writing the code that typically enables interoperability\
  \ with existing applications.\n  humanURL: https://aws.amazon.com/mq/\n  baseURL: http://mq.{region}.amazonaws.com\n  tags:\n  - Broadcasting\n  - Media Processing\n  - Media\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/mq/\n  - type: OpenAPI\n    url: openapi/amazon-mq-openapi-original.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/mq/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/mq/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/mq/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/mq/\n- type: Documentation\n  url: https://docs.aws.amazon.com/mq/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/media/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/mq/\n\
  - type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-mq-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-mq-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-mq-media-workflow.yaml\n- type: Features\n  data:\n  - name: Managed Message Brokers\n    description: Fully managed Apache ActiveMQ and RabbitMQ brokers with automated provisioning and maintenance.\n  - name: Protocol Support\n    description: Supports AMQP, MQTT, OpenWire, STOMP, and WebSocket protocols for broad compatibility.\n  - name: High Availability\n    description: Active/standby configurations with automatic failover for high availability.\n  - name: Network of Brokers\n    description: Create networks of brokers for distributed messaging across regions and availability zones.\n  - name: Broker\
  \ Management API\n    description: Programmatically create, configure, and manage brokers and configurations.\n  - name: Security\n    description: Encryption at rest and in transit, VPC isolation, and IAM integration.\n- type: UseCases\n  data:\n  - name: Application Migration\n    description: Migrate on-premises ActiveMQ or RabbitMQ workloads to AWS without code changes.\n  - name: Microservices Decoupling\n    description: Use message queues to decouple microservices for improved reliability and scalability.\n  - name: Enterprise Integration\n    description: Connect enterprise applications using standard messaging protocols.\n  - name: Event-Driven Architecture\n    description: Build event-driven applications with reliable message delivery.\n- type: Integrations\n  data:\n  - name: Amazon VPC\n    description: Deploy brokers within a VPC for network isolation and security.\n  - name: Amazon CloudWatch\n    description: Monitor broker metrics, queue depths, and consumer lag.\n  -\
  \ name: AWS KMS\n    description: Encrypt broker data at rest using AWS KMS keys.\n  - name: AWS IAM\n    description: Control access to Amazon MQ resources with IAM policies.\n  - name: Amazon CloudFormation\n    description: Provision and manage brokers using CloudFormation templates.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-mq/refs/heads/main/apis.yml
tags:
- AWS
- Broadcasting
- Media Processing
- Media
url: https://raw.githubusercontent.com/api-evangelist/amazon-mq/refs/heads/main/apis.yml
use_cases:
- description: Migrate on-premises ActiveMQ or RabbitMQ workloads to AWS without code changes.
  name: Application Migration
- description: Use message queues to decouple microservices for improved reliability and scalability.
  name: Microservices Decoupling
- description: Connect enterprise applications using standard messaging protocols.
  name: Enterprise Integration
- description: Build event-driven applications with reliable message delivery.
  name: Event-Driven Architecture
---
