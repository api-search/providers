---
api_count: 2
api_specs:
- filename: cloudformation-api.yml
  format: yaml
  label: AWS CloudFormation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudformation/refs/heads/main/openapi/cloudformation-api.yml
- filename: cloud-control-api.yml
  format: yaml
  label: AWS Cloud Control API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudformation/refs/heads/main/openapi/cloud-control-api.yml
apis:
- description: AWS CloudFormation gives you an easy way to model a collection of related AWS and third-party resources, provision them quickly and consistently, and manage them throughout their lifecycles. It uses t
  name: AWS CloudFormation API
  slug: ''
- description: 'AWS Cloud Control API provides a uniform CRUDL (create, read, update, delete, list) interface for managing AWS and third-party resources. It offers a standardized way to access and provision resource '
  name: AWS Cloud Control API
  slug: ''
capabilities:
- description: Unified workflow for AWS infrastructure provisioning combining CloudFormation stack management with Cloud Control API resource operations. Used by cloud engineers and platform teams to define, deploy,
  name: AWS Infrastructure Provisioning
  slug: infrastructure-provisioning
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/cloudformation/resources/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/cloudformation/getting-started/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/cloudformation/pricing/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/devops/category/management-tools/aws-cloudformation/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cloudformation/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws-cloudformation
- title: ''
  type: GitHubRepository
  url: https://github.com/aws-cloudformation/aws-cloudformation-templates
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-cloudformation
- title: Python SDK (Boto3)
  type: SDK
  url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html
- title: JavaScript SDK v3
  type: SDK
  url: https://docs.aws.amazon.com/sdk-for-javascript/v3/developer-guide/cloudformation-examples.html
- title: Java SDK
  type: SDK
  url: https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/examples-cloudformation.html
- title: Go SDK
  type: SDK
  url: https://docs.aws.amazon.com/sdk-for-go/api/service/cloudformation/
- title: AWS CLI - CloudFormation
  type: CLI
  url: https://docs.aws.amazon.com/cli/latest/reference/cloudformation/
- title: Rain - CloudFormation CLI
  type: CLI
  url: https://github.com/aws-cloudformation/rain
- title: Stack Schema
  type: JSONSchema
  url: json-schema/stack.json
- title: Template Schema
  type: JSONSchema
  url: json-schema/template.json
- title: Resource Schema
  type: JSONSchema
  url: json-schema/resource.json
- title: Change Set Schema
  type: JSONSchema
  url: json-schema/change-set.json
- title: Change Schema
  type: JSONSchema
  url: json-schema/cloudformation-change-schema.json
- title: Change Set Detail Schema
  type: JSONSchema
  url: json-schema/cloudformation-change-set-detail-schema.json
- title: Change Set Summary Schema
  type: JSONSchema
  url: json-schema/cloudformation-change-set-summary-schema.json
- title: Error Response Schema
  type: JSONSchema
  url: json-schema/cloudformation-error-response-schema.json
- title: Stack Detail Schema
  type: JSONSchema
  url: json-schema/cloudformation-stack-schema.json
- title: Stack Event Schema
  type: JSONSchema
  url: json-schema/cloudformation-stack-event-schema.json
- title: Stack Resource Schema
  type: JSONSchema
  url: json-schema/cloudformation-stack-resource-schema.json
- title: Stack Summary Schema
  type: JSONSchema
  url: json-schema/cloudformation-stack-summary-schema.json
- title: Tag Schema
  type: JSONSchema
  url: json-schema/cloudformation-tag-schema.json
- title: Cloud Control Progress Event Schema
  type: JSONSchema
  url: json-schema/cloud-control-progress-event-schema.json
- title: Cloud Control Resource Description Schema
  type: JSONSchema
  url: json-schema/cloud-control-resource-description-schema.json
- title: Cloud Control Error Response Schema
  type: JSONSchema
  url: json-schema/cloud-control-error-response-schema.json
- title: JSON-LD Context
  type: JSONLD
  url: json-ld/context.jsonld
- title: CloudFormation JSON-LD Context
  type: JSONLD
  url: json-ld/cloudformation-context.jsonld
- title: Cloud Control JSON-LD Context
  type: JSONLD
  url: json-ld/cloud-control-context.jsonld
- title: CloudFormation Vocabulary
  type: Vocabulary
  url: vocabulary/cloudformation-vocabulary.yaml
- title: Spectral Rules
  type: Rules
  url: rules/cloudformation-spectral-rules.yml
- title: Infrastructure Provisioning Workflow
  type: Capabilities
  url: capabilities/infrastructure-provisioning.yaml
- title: CloudFormation Shared Capability
  type: Capabilities
  url: capabilities/shared/cloudformation.yaml
- title: Cloud Control Shared Capability
  type: Capabilities
  url: capabilities/shared/cloud-control.yaml
created: '2024'
description: A collection of APIs provided by AWS for infrastructure as code provisioning and management of AWS and third-party resources using CloudFormation templates and the Cloud Control API.
features:
- description: Define and provision AWS infrastructure using declarative JSON/YAML templates
  name: Infrastructure As Code
- description: Create, update, and delete collections of AWS resources as a single unit
  name: Stack Management
- description: Preview changes before applying them to running stacks
  name: Change Sets
- description: Detect when stack resources have been modified outside of CloudFormation
  name: Drift Detection
- description: Deploy stacks across multiple accounts and regions simultaneously
  name: Stack Sets
- description: Uniform interface for managing any resource in the CloudFormation Registry
  name: Cloud Control CRUDL
image: https://aws.amazon.com/cloudformation/logo.png
integrations:
- description: Define cloud infrastructure using familiar programming languages that compile to CloudFormation
  name: AWS CDK
- description: Simplified syntax for serverless application deployment via CloudFormation
  name: AWS SAM
- description: Alternative IaC tool that can import/export CloudFormation templates
  name: Terraform
jsonld:
- class_count: 0
  name: Cloud Control Context
  property_count: 0
  slug: cloud-control-context
- class_count: 0
  name: Cloudformation Context
  property_count: 0
  slug: cloudformation-context
- class_count: 0
  name: context Context
  property_count: 8
  slug: context
layout: provider
modified: '2026-04-18'
name: AWS CloudFormation
rules:
- name: AWS CloudFormation API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: cloudformation-spectral-rules
skills: []
slug: cloudformation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: AWS CloudFormation\ndescription: >-\n  A collection of APIs provided by AWS for infrastructure as code provisioning\n  and management of AWS and third-party resources using CloudFormation templates\n  and the Cloud Control API.\nimage: https://aws.amazon.com/cloudformation/logo.png\ncreated: '2024'\nmodified: '2026-04-18'\nurl: https://docs.aws.amazon.com/cloudformation/\nspecificationVersion: '0.19'\ntags:\n  - Automation\n  - AWS\n  - Cloud Resources\n  - IaC\n  - Infrastructure As Code\n  - Stack Management\napis:\n  - name: AWS CloudFormation API\n    description: >-\n      AWS CloudFormation gives you an easy way to model a collection of related\n      AWS and third-party resources, provision them quickly and consistently, and\n      manage them throughout their lifecycles. It uses templates to define stacks\n      of resources and provides API operations for creating, updating, and deleting\n      stacks.\n    image: https://aws.amazon.com/cloudformation/logo.png\n\
  \    humanURL: https://aws.amazon.com/cloudformation/\n    baseURL: https://cloudformation.{region}.amazonaws.com\n    tags:\n      - Infrastructure\n      - Resources\n      - Stacks\n      - Templates\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cloudformation/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/cloudformation-api.yml\n      - type: Pricing\n        url: https://aws.amazon.com/cloudformation/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/cloudformation/getting-started/\n      - type: ChangeLog\n        url: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/document-history.html\n      - type: SDK\n        url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html\n        title: Python SDK (Boto3)\n    contact:\n      - FN: AWS Support\n\
  \        url: https://aws.amazon.com/contact-us/\n        email: ''\n  - name: AWS Cloud Control API\n    description: >-\n      AWS Cloud Control API provides a uniform CRUDL (create, read, update,\n      delete, list) interface for managing AWS and third-party resources. It\n      offers a standardized way to access and provision resource types available\n      in the CloudFormation Registry without needing to learn each individual\n      service API.\n    image: https://aws.amazon.com/cloudformation/logo.png\n    humanURL: https://aws.amazon.com/cloudcontrolapi/\n    baseURL: https://cloudcontrolapi.{region}.amazonaws.com\n    tags:\n      - Cloud Control\n      - CRUDL\n      - Provisioning\n      - Resources\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cloudcontrolapi/latest/userguide/what-is-cloudcontrolapi.html\n      - type: OpenAPI\n        url: openapi/cloud-control-api.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cloudcontrolapi/index.html\n\
  \    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n        email: ''\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/cloudformation/resources/\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudformation/getting-started/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudformation/pricing/\n  - type: TermsOfService\n    url: https://aws.amazon.com/terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/devops/category/management-tools/aws-cloudformation/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: Console\n    url: https://console.aws.amazon.com/cloudformation/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: GitHubOrganization\n    url: https://github.com/aws-cloudformation\n  - type:\
  \ GitHubRepository\n    url: https://github.com/aws-cloudformation/aws-cloudformation-templates\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/aws-cloudformation\n  - type: Features\n    data:\n      - name: Infrastructure As Code\n        description: Define and provision AWS infrastructure using declarative JSON/YAML templates\n      - name: Stack Management\n        description: Create, update, and delete collections of AWS resources as a single unit\n      - name: Change Sets\n        description: Preview changes before applying them to running stacks\n      - name: Drift Detection\n        description: Detect when stack resources have been modified outside of CloudFormation\n      - name: Stack Sets\n        description: Deploy stacks across multiple accounts and regions simultaneously\n      - name: Cloud Control CRUDL\n        description: Uniform interface for managing any resource in the CloudFormation Registry\n  - type: UseCases\n    data:\n  \
  \    - name: Multi-Account Deployment\n        description: Deploy consistent infrastructure across multiple AWS accounts with Stack Sets\n      - name: Environment Provisioning\n        description: Spin up identical dev, staging, and production environments from templates\n      - name: Compliance Auditing\n        description: Detect configuration drift and enforce infrastructure compliance\n  - type: Integrations\n    data:\n      - name: AWS CDK\n        description: Define cloud infrastructure using familiar programming languages that compile to CloudFormation\n      - name: AWS SAM\n        description: Simplified syntax for serverless application deployment via CloudFormation\n      - name: Terraform\n        description: Alternative IaC tool that can import/export CloudFormation templates\n  - type: SDK\n    url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudformation.html\n    title: Python SDK (Boto3)\n  - type: SDK\n    url: https://docs.aws.amazon.com/sdk-for-javascript/v3/developer-guide/cloudformation-examples.html\n\
  \    title: JavaScript SDK v3\n  - type: SDK\n    url: https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/examples-cloudformation.html\n    title: Java SDK\n  - type: SDK\n    url: https://docs.aws.amazon.com/sdk-for-go/api/service/cloudformation/\n    title: Go SDK\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudformation/\n    title: AWS CLI - CloudFormation\n  - type: CLI\n    url: https://github.com/aws-cloudformation/rain\n    title: Rain - CloudFormation CLI\n  - type: JSONSchema\n    url: json-schema/stack.json\n    title: Stack Schema\n  - type: JSONSchema\n    url: json-schema/template.json\n    title: Template Schema\n  - type: JSONSchema\n    url: json-schema/resource.json\n    title: Resource Schema\n  - type: JSONSchema\n    url: json-schema/change-set.json\n    title: Change Set Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-change-schema.json\n    title: Change Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-change-set-detail-schema.json\n\
  \    title: Change Set Detail Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-change-set-summary-schema.json\n    title: Change Set Summary Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-error-response-schema.json\n    title: Error Response Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-stack-schema.json\n    title: Stack Detail Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-stack-event-schema.json\n    title: Stack Event Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-stack-resource-schema.json\n    title: Stack Resource Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-stack-summary-schema.json\n    title: Stack Summary Schema\n  - type: JSONSchema\n    url: json-schema/cloudformation-tag-schema.json\n    title: Tag Schema\n  - type: JSONSchema\n    url: json-schema/cloud-control-progress-event-schema.json\n    title: Cloud Control Progress Event Schema\n  - type: JSONSchema\n\
  \    url: json-schema/cloud-control-resource-description-schema.json\n    title: Cloud Control Resource Description Schema\n  - type: JSONSchema\n    url: json-schema/cloud-control-error-response-schema.json\n    title: Cloud Control Error Response Schema\n  - type: JSONLD\n    url: json-ld/context.jsonld\n    title: JSON-LD Context\n  - type: JSONLD\n    url: json-ld/cloudformation-context.jsonld\n    title: CloudFormation JSON-LD Context\n  - type: JSONLD\n    url: json-ld/cloud-control-context.jsonld\n    title: Cloud Control JSON-LD Context\n  - type: Vocabulary\n    url: vocabulary/cloudformation-vocabulary.yaml\n    title: CloudFormation Vocabulary\n  - type: Rules\n    url: rules/cloudformation-spectral-rules.yml\n    title: Spectral Rules\n  - type: Capabilities\n    url: capabilities/infrastructure-provisioning.yaml\n    title: Infrastructure Provisioning Workflow\n  - type: Capabilities\n    url: capabilities/shared/cloudformation.yaml\n    title: CloudFormation Shared Capability\n\
  \  - type: Capabilities\n    url: capabilities/shared/cloud-control.yaml\n    title: Cloud Control Shared Capability\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudformation/refs/heads/main/apis.yml
tags:
- Automation
- AWS
- Cloud Resources
- IaC
- Infrastructure As Code
- Stack Management
url: https://docs.aws.amazon.com/cloudformation/
use_cases:
- description: Deploy consistent infrastructure across multiple AWS accounts with Stack Sets
  name: Multi-Account Deployment
- description: Spin up identical dev, staging, and production environments from templates
  name: Environment Provisioning
- description: Detect configuration drift and enforce infrastructure compliance
  name: Compliance Auditing
---
