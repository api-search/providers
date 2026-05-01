---
api_count: 1
api_specs:
- filename: amazon-cloudformation-openapi.yml
  format: yaml
  label: Amazon CloudFormation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/openapi/amazon-cloudformation-openapi.yml
apis:
- description: API for creating, updating, and managing CloudFormation stacks, stack sets, and change sets for infrastructure-as-code deployments across AWS accounts and regions.
  name: Amazon CloudFormation API
  slug: ''
capabilities:
- description: Workflow for infrastructure as code deployment using Amazon CloudFormation for DevOps Engineer personas.
  name: Amazon CloudFormation Infrastructure as Code Deployment
  slug: infrastructure-as-code
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloudformation/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/
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
  url: https://aws.amazon.com/blogs/devops/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cloudformation/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-cloudformation
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloudformation-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloudformation-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/infrastructure-as-code.yaml
created: '2024-01-01'
description: AWS CloudFormation is an infrastructure-as-code service that speeds up cloud provisioning by enabling developers to define and manage AWS resources programmatically through templates. Scale infrastructure globally and manage resources across all AWS accounts and regions through a single operation.
features:
- description: Define AWS resources in JSON or YAML templates for repeatable, version-controlled deployments.
  name: Infrastructure as Code
- description: Deploy stacks across multiple AWS accounts and regions with a single operation.
  name: Multi-Account Stack Sets
- description: Preview changes to running stacks before executing them to avoid unintended updates.
  name: Change Sets
- description: Detect when deployed infrastructure has drifted from the CloudFormation template definition.
  name: Drift Detection
- description: Extend CloudFormation to manage third-party and community resources through the Registry.
  name: Registry Extensions
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Automate CloudFormation deployments in CI/CD pipelines.
  name: AWS CodePipeline
- description: Track infrastructure changes and detect drift with Config integration.
  name: AWS Config
- description: Control who can create and update CloudFormation stacks.
  name: AWS IAM
- description: Publish approved CloudFormation templates as self-service products.
  name: AWS Service Catalog
- description: Receive stack event notifications via SNS topics.
  name: Amazon SNS
jsonld:
- class_count: 16
  name: Amazon Cloudformation Context
  property_count: 50
  slug: amazon-cloudformation-context
layout: provider
modified: '2026-04-19'
name: Amazon CloudFormation
rules:
- name: Amazon CloudFormation API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: amazon-cloudformation-spectral-rules
skills: []
slug: amazon-cloudformation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-cloudformation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/apis.yml\nname: Amazon CloudFormation\ntags:\n- AWS\n- CloudFormation\n- Infrastructure as Code\n- DevOps\n- IaC\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  AWS CloudFormation is an infrastructure-as-code service that speeds up cloud provisioning by enabling developers to define and manage AWS resources programmatically through templates. Scale infrastructure\n  globally and manage resources across all AWS accounts and regions through a single operation.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- name: Amazon CloudFormation API\n  description: API for creating, updating, and managing CloudFormation stacks, stack sets, and change sets for infrastructure-as-code deployments across AWS accounts and regions.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanURL: https://aws.amazon.com/cloudformation/\n  baseURL: https://cloudformation.us-east-1.amazonaws.com\n  tags:\n  - AWS\n  - CloudFormation\n  - Infrastructure as Code\n  - DevOps\n  properties:\n  - type: OpenAPI\n    url: openapi/amazon-cloudformation-openapi.yml\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudformation/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudformation/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudformation/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudformation/\n  - type: JSONSchema\n    url: json-schema/cloudformation-stack-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudformation-change-set-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudformation-stack-resource-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/cloudformation-parameter-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudformation-output-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-cloudformation-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/cloudformation/\n- type: Documentation\n  url: https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/devops/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudformation/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type:\
  \ YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-cloudformation\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-cloudformation-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloudformation-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/infrastructure-as-code.yaml\n- type: Features\n  data:\n  - name: Infrastructure as Code\n    description: Define AWS resources in JSON or YAML templates for repeatable, version-controlled deployments.\n  - name: Multi-Account Stack Sets\n    description: Deploy stacks across multiple AWS accounts and regions with a single operation.\n  - name: Change Sets\n    description: Preview changes to running stacks before executing them to avoid unintended updates.\n  - name: Drift Detection\n    description: Detect when\
  \ deployed infrastructure has drifted from the CloudFormation template definition.\n  - name: Registry Extensions\n    description: Extend CloudFormation to manage third-party and community resources through the Registry.\n- type: UseCases\n  data:\n  - name: DevOps Automation\n    description: Automate infrastructure testing and deployment through CI/CD pipelines.\n  - name: Multi-Region Deployment\n    description: Deploy consistent infrastructure across multiple AWS regions.\n  - name: Compliance Governance\n    description: Enforce organizational infrastructure standards through template guardrails.\n  - name: Disaster Recovery\n    description: Rapidly rebuild infrastructure from templates after failures.\n- type: Integrations\n  data:\n  - name: AWS CodePipeline\n    description: Automate CloudFormation deployments in CI/CD pipelines.\n  - name: AWS Config\n    description: Track infrastructure changes and detect drift with Config integration.\n  - name: AWS IAM\n    description:\
  \ Control who can create and update CloudFormation stacks.\n  - name: AWS Service Catalog\n    description: Publish approved CloudFormation templates as self-service products.\n  - name: Amazon SNS\n    description: Receive stack event notifications via SNS topics.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/apis.yml
tags:
- CloudFormation
- Infrastructure as Code
- DevOps
- IaC
url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudformation/refs/heads/main/apis.yml
use_cases:
- description: Automate infrastructure testing and deployment through CI/CD pipelines.
  name: DevOps Automation
- description: Deploy consistent infrastructure across multiple AWS regions.
  name: Multi-Region Deployment
- description: Enforce organizational infrastructure standards through template guardrails.
  name: Compliance Governance
- description: Rapidly rebuild infrastructure from templates after failures.
  name: Disaster Recovery
---
