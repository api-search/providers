---
api_count: 6
apis:
- description: Cloud Custodian provides rules-engine capabilities for managing cloud resources with security, compliance, and cost optimization policies.
  name: Cloud Custodian
  slug: cloud-custodian
- description: 'The Cloud Custodian AWS provider enables policy-as-code management of Amazon Web Services resources including EC2, S3, IAM, RDS, Lambda, and hundreds of other AWS service resource types. Policies can '
  name: Cloud Custodian AWS Provider
  slug: cloud-custodian-aws
- description: The Cloud Custodian Azure provider enables policy-as-code management of Microsoft Azure resources including virtual machines, storage accounts, network security groups, and other Azure services. Polic
  name: Cloud Custodian Azure Provider
  slug: cloud-custodian-azure
- description: The Cloud Custodian GCP provider enables policy-as-code management of Google Cloud Platform resources including Compute Engine instances, GCS buckets, Cloud SQL instances, and other GCP services. Poli
  name: Cloud Custodian GCP Provider
  slug: cloud-custodian-gcp
- description: 'c7n-org is a Cloud Custodian tool for running policies across multiple cloud accounts, projects, or subscriptions in parallel. It uses an accounts configuration file with assumed roles to orchestrate '
  name: Cloud Custodian C7n-Org
  slug: cloud-custodian-c7n-org
- description: c7n-mailer is a Cloud Custodian notification tool that subscribes to an SQS queue populated by policy actions and sends notifications via SES email, Slack messages, or integrations with DataDog and Sp
  name: Cloud Custodian C7n-Mailer
  slug: cloud-custodian-c7n-mailer
asyncapis:
- description: The Cloud Custodian c7n-mailer AsyncAPI defines the event-driven notification interface used by the Cloud Custodian policy engine to deliver policy violation alerts. When a policy's notify action fire
  name: Cloud Custodian c7n-mailer Notification Events
  slug: cloud-custodian-mailer-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://cloudcustodian.io/
- title: ''
  type: Documentation
  url: https://cloudcustodian.io/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/cloud-custodian/cloud-custodian
- title: ''
  type: Getting Started
  url: https://cloudcustodian.io/docs/quickstart/index.html
- title: ''
  type: Community
  url: https://cloudcustodian.io/community/
- title: ''
  type: GitHubRepository
  url: https://github.com/cloud-custodian/cloud-custodian
- title: ''
  type: Change Log
  url: https://github.com/cloud-custodian/cloud-custodian/releases
- title: ''
  type: JSONLDContext
  url: json-ld/cloud-custodian-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cloud-custodian-policy-schema.json
- title: ''
  type: AsyncAPI
  url: asyncapi/cloud-custodian-mailer-asyncapi.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloud-custodian-capabilities.yml
created: '2025-01-01'
description: Cloud Custodian is an open-source rules engine for cloud security, compliance, and cost-optimization governance now stewarded by Stacklet. Operators express policies as YAML files that select a cloud resource type, apply filters, and execute actions; the engine then runs those policies against AWS, Azure, and GCP via provider-specific plugins. Custodian does not expose a developer REST API of its own - integration is via the c7n CLI, the policy YAML schema, c7n-org for multi-account fan-out, and c7n-mailer for SQS-driven notifications.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloud Custodian Context
  property_count: 8
  slug: cloud-custodian-context
layout: provider
modified: '2026-04-27'
name: Cloud Custodian
skills: []
slug: cloud-custodian
solutions: []
tags:
- Cloud Security
- Compliance
- Cost Optimization
- Multi-Cloud
- Policy as Code
url: https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/apis.yml
use_cases: []
---
