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
source_yaml: "aid: cloud-custodian\nurl: https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/apis.yml\nname: Cloud Custodian\ntags:\n  - Cloud Security\n  - Compliance\n  - Cost Optimization\n  - Multi-Cloud\n  - Policy as Code\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: Open Source\ncreated: '2025-01-01'\nmodified: '2026-04-27'\nposition: Consumer\nx-type: opensource\ndescription: >-\n  Cloud Custodian is an open-source rules engine for cloud security,\n  compliance, and cost-optimization governance now stewarded by Stacklet.\n  Operators express policies as YAML files that select a cloud resource\n  type, apply filters, and execute actions; the engine then runs those\n  policies against AWS, Azure, and GCP via provider-specific plugins.\n  Custodian does not expose a developer REST API of its own - integration\n  is via the c7n CLI, the policy YAML schema, c7n-org for multi-account\n  fan-out, and\
  \ c7n-mailer for SQS-driven notifications.\napis:\n  - aid: cloud-custodian:cloud-custodian\n    name: Cloud Custodian\n    tags:\n      - Cloud Security\n      - Policy as Code\n    humanURL: https://cloudcustodian.io/\n    properties:\n      - url: https://cloudcustodian.io/docs/\n        type: Documentation\n      - url: https://cloudcustodian.io/docs/quickstart/index.html\n        type: Getting Started\n      - url: https://cloudcustodian.io/docs/overview/capabilities.html\n        type: Reference\n      - url: https://github.com/cloud-custodian/cloud-custodian\n        type: GitHubRepository\n      - type: JSONSchema\n        url: json-schema/cloud-custodian-policy-schema.json\n    description: >-\n      Cloud Custodian provides rules-engine capabilities for managing cloud\n      resources with security, compliance, and cost optimization policies.\n  - aid: cloud-custodian:cloud-custodian-aws\n    name: Cloud Custodian AWS Provider\n    description: >-\n      The Cloud Custodian AWS\
  \ provider enables policy-as-code management of\n      Amazon Web Services resources including EC2, S3, IAM, RDS, Lambda, and\n      hundreds of other AWS service resource types. Policies can be run in\n      multiple execution modes including serverless Lambda functions, AWS Config\n      rules, and scheduled CloudWatch Events.\n    humanURL: https://cloudcustodian.io/docs/aws/gettingstarted.html\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - url: https://cloudcustodian.io/docs/aws/gettingstarted.html\n        type: Getting Started\n      - url: https://cloudcustodian.io/docs/aws/resources/index.html\n        type: Reference\n      - url: https://cloudcustodian.io/docs/aws/examples/index.html\n        type: Documentation\n    tags:\n      - AWS\n      - Cloud Security\n      - Compliance\n      - Policy as Code\n  - aid: cloud-custodian:cloud-custodian-azure\n    name: Cloud Custodian Azure Provider\n    description: >-\n\
  \      The Cloud Custodian Azure provider enables policy-as-code management of\n      Microsoft Azure resources including virtual machines, storage accounts,\n      network security groups, and other Azure services. Policies can enforce\n      security requirements, tagging standards, and cost controls across Azure\n      subscriptions.\n    humanURL: https://cloudcustodian.io/docs/azure/gettingstarted.html\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - url: https://cloudcustodian.io/docs/azure/gettingstarted.html\n        type: Getting Started\n      - url: https://cloudcustodian.io/docs/azure/policy/resources/index.html\n        type: Reference\n    tags:\n      - Azure\n      - Cloud Security\n      - Compliance\n      - Policy as Code\n  - aid: cloud-custodian:cloud-custodian-gcp\n    name: Cloud Custodian GCP Provider\n    description: >-\n      The Cloud Custodian GCP provider enables policy-as-code management of\n\
  \      Google Cloud Platform resources including Compute Engine instances, GCS\n      buckets, Cloud SQL instances, and other GCP services. Policies can be\n      used to enforce security, compliance, and cost governance standards across\n      GCP projects.\n    humanURL: https://cloudcustodian.io/docs/gcp/gettingstarted.html\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - url: https://cloudcustodian.io/docs/gcp/gettingstarted.html\n        type: Getting Started\n      - url: https://cloudcustodian.io/docs/gcp/resources/index.html\n        type: Reference\n    tags:\n      - Cloud Security\n      - Compliance\n      - GCP\n      - Policy as Code\n  - aid: cloud-custodian:cloud-custodian-c7n-org\n    name: Cloud Custodian C7n-Org\n    description: >-\n      c7n-org is a Cloud Custodian tool for running policies across multiple\n      cloud accounts, projects, or subscriptions in parallel. It uses an\n      accounts configuration\
  \ file with assumed roles to orchestrate Custodian\n      execution at scale across AWS Organizations, Azure subscriptions, or GCP\n      projects.\n    humanURL: https://cloudcustodian.io/docs/tools/c7n-org.html\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - url: https://cloudcustodian.io/docs/tools/c7n-org.html\n        type: Documentation\n    tags:\n      - Cloud Security\n      - Multi-Account\n      - Orchestration\n  - aid: cloud-custodian:cloud-custodian-c7n-mailer\n    name: Cloud Custodian C7n-Mailer\n    description: >-\n      c7n-mailer is a Cloud Custodian notification tool that subscribes to an\n      SQS queue populated by policy actions and sends notifications via SES\n      email, Slack messages, or integrations with DataDog and Splunk. It\n      enables teams to alert resource owners when Custodian policies detect\n      policy violations.\n    humanURL: https://cloudcustodian.io/docs/tools/c7n-mailer.html\n\
  \    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - url: https://cloudcustodian.io/docs/tools/c7n-mailer.html\n        type: Documentation\n      - type: AsyncAPI\n        url: asyncapi/cloud-custodian-mailer-asyncapi.yml\n    tags:\n      - Alerting\n      - Email\n      - Notifications\n      - Slack\ncommon:\n  - type: Website\n    url: https://cloudcustodian.io/\n  - type: Documentation\n    url: https://cloudcustodian.io/docs/\n  - type: GitHub Organization\n    url: https://github.com/cloud-custodian/cloud-custodian\n  - type: Getting Started\n    url: https://cloudcustodian.io/docs/quickstart/index.html\n  - type: Community\n    url: https://cloudcustodian.io/community/\n  - type: GitHubRepository\n    url: https://github.com/cloud-custodian/cloud-custodian\n  - type: Change Log\n    url: https://github.com/cloud-custodian/cloud-custodian/releases\n  - type: JSONLDContext\n    url: json-ld/cloud-custodian-context.jsonld\n\
  \  - type: JSONSchema\n    url: json-schema/cloud-custodian-policy-schema.json\n  - type: AsyncAPI\n    url: asyncapi/cloud-custodian-mailer-asyncapi.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloud-custodian-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/apis.yml
tags:
- Cloud Security
- Compliance
- Cost Optimization
- Multi-Cloud
- Policy as Code
url: https://raw.githubusercontent.com/api-evangelist/cloud-custodian/refs/heads/main/apis.yml
use_cases: []
---
