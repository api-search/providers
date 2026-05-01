---
api_count: 1
api_specs:
- filename: amazon-serverless-application-repository-openapi.yml
  format: yaml
  label: AWS Serverless Application Repository API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-serverless-application-repository/refs/heads/main/openapi/amazon-serverless-application-repository-openapi.yml
apis:
- description: 'The AWS Serverless Application Repository API provides programmatic access to create and manage serverless applications, application versions, and deployment configurations for publishing and sharing '
  name: AWS Serverless Application Repository API
  slug: ''
capabilities:
- description: Unified capability for publishing, discovering, and deploying serverless applications via the AWS Serverless Application Repository. Used by Serverless Developers and Platform Engineers.
  name: Amazon SAR Serverless App Management
  slug: serverless-app-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/serverless/serverlessrepo/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/serverless/serverlessrepo/getting-started/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/serverlessrepo/
- title: ''
  type: APIReference
  url: https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html
- title: ''
  type: Console
  url: https://console.aws.amazon.com/serverlessrepo/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Pricing
  url: https://aws.amazon.com/serverless/serverlessrepo/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/serverless/serverlessrepo/faqs/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/tag/serverless-application-repository/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/serverless-application-repository
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: SpectralRules
  url: rules/amazon-serverless-application-repository-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-serverless-application-repository-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/serverless-app-management.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-serverless-application-repository-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/amazon-serverless-application-repository-application-policy-statement-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-serverless-application-repository-application-summary-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-serverless-application-repository-application-policy-statement-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-serverless-application-repository-application-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-serverless-application-repository-application-summary-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-serverless-application-repository-version-summary-structure.json
- title: ''
  type: Example
  url: examples/amazon-serverless-application-repository-application-example.json
- title: ''
  type: Example
  url: examples/amazon-serverless-application-repository-application-policy-statement-example.json
- title: ''
  type: Example
  url: examples/amazon-serverless-application-repository-application-summary-example.json
- title: ''
  type: Example
  url: examples/amazon-serverless-application-repository-version-summary-example.json
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-serverless-application-repository.yaml
created: '2026-03-16'
description: The AWS Serverless Application Repository enables teams, organizations, and individual developers to find, deploy, and publish serverless applications. It enables you to quickly deploy code samples, components, and complete applications for common use cases such as web and mobile backends, data processing, and IoT applications using AWS SAM templates.
features:
- description: Deploy pre-built serverless applications with a single click from the SAR console.
  name: One-Click Deployment
- description: Publish applications as AWS SAM templates with full CloudFormation resource support.
  name: SAM Template Support
- description: Manage multiple application versions using semantic versioning for controlled updates.
  name: Semantic Versioning
- description: Share applications publicly to the entire AWS community or privately within your organization.
  name: Public and Private Sharing
- description: Compose complex serverless architectures using nested SAM application references.
  name: Nested Applications
- description: Control who can deploy your application using resource-based policies.
  name: Policy Sharing
- description: Attach open source licenses to applications using SPDX license identifiers.
  name: License Management
- description: Deploy applications through CloudFormation changesets for full infrastructure-as-code support.
  name: CloudFormation Integration
image: ''
integrations:
- description: Native integration with the AWS Serverless Application Model for packaging and publishing.
  name: AWS SAM
- description: Applications are deployed via CloudFormation change sets for full IaC integration.
  name: AWS CloudFormation
- description: The primary compute runtime for all SAR-deployed serverless applications.
  name: AWS Lambda
- description: Commonly bundled with SAR applications for HTTP API exposure.
  name: Amazon API Gateway
- description: Automate SAR application publishing as part of CI/CD pipelines.
  name: AWS CodePipeline
- description: Third-party Serverless Framework plugins support SAR publishing workflows.
  name: AWS Serverless Framework
- description: Frequently included as a data store in SAR application templates.
  name: Amazon DynamoDB
- description: Used for hosting static content and storing SAR application artifacts.
  name: Amazon S3
jsonld:
- class_count: 7
  name: Amazon Serverless Application Repository Context
  property_count: 13
  slug: amazon-serverless-application-repository-context
layout: provider
modified: '2026-04-19'
name: Amazon Serverless Application Repository
rules:
- name: Amazon Serverless Application Repository API Rules
  rule_count: 20
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 9
  slug: amazon-serverless-application-repository-spectral-rules
skills: []
slug: amazon-serverless-application-repository
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Serverless Application Repository\ndescription: >-\n  The AWS Serverless Application Repository enables teams, organizations, and\n  individual developers to find, deploy, and publish serverless applications.\n  It enables you to quickly deploy code samples, components, and complete\n  applications for common use cases such as web and mobile backends, data\n  processing, and IoT applications using AWS SAM templates.\nurl: https://aws.amazon.com/serverless/serverlessrepo/\nbaseURL: https://serverlessrepo.amazonaws.com\nx-type: company\ncreated: '2026-03-16'\nmodified: '2026-04-19'\n\ntags:\n- Application Repository\n- AWS\n- Lambda\n- SAM\n- Serverless\n\napis:\n\n- name: AWS Serverless Application Repository API\n  description: >-\n    The AWS Serverless Application Repository API provides programmatic\n    access to create and manage serverless applications, application versions,\n    and deployment configurations for publishing and sharing SAM applications.\n\
  \  humanURL: https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html\n  baseURL: https://serverlessrepo.{region}.amazonaws.com\n  tags:\n  - Application Repository\n  - Lambda\n  - Serverless\n  - SAM\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html\n  - type: OpenAPI\n    url: openapi/amazon-serverless-application-repository-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-serverless-application-repository-application-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-serverless-application-repository-version-summary-schema.json\n\ncommon:\n\n- type: Portal\n  url: https://aws.amazon.com/serverless/serverlessrepo/\n\n- type: GettingStarted\n  url: https://aws.amazon.com/serverless/serverlessrepo/getting-started/\n\n- type: Documentation\n  url: https://docs.aws.amazon.com/serverlessrepo/\n\n- type: APIReference\n  url: https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html\n\
  \n- type: Console\n  url: https://console.aws.amazon.com/serverlessrepo/\n\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n\n- type: Pricing\n  url: https://aws.amazon.com/serverless/serverlessrepo/pricing/\n\n- type: FAQ\n  url: https://aws.amazon.com/serverless/serverlessrepo/faqs/\n\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/tag/serverless-application-repository/\n\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n\n- type: GitHubOrganization\n  url: https://github.com/aws\n\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/serverless-application-repository\n\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n\
  \n- type: SpectralRules\n  url: rules/amazon-serverless-application-repository-spectral-rules.yml\n\n- type: Vocabulary\n  url: vocabulary/amazon-serverless-application-repository-vocabulary.yaml\n\n- type: NaftikoCapability\n  url: capabilities/serverless-app-management.yaml\n\n- type: Features\n  data:\n  - name: One-Click Deployment\n    description: Deploy pre-built serverless applications with a single click from the SAR console.\n  - name: SAM Template Support\n    description: Publish applications as AWS SAM templates with full CloudFormation resource support.\n  - name: Semantic Versioning\n    description: Manage multiple application versions using semantic versioning for controlled updates.\n  - name: Public and Private Sharing\n    description: Share applications publicly to the entire AWS community or privately within your organization.\n  - name: Nested Applications\n    description: Compose complex serverless architectures using nested SAM application references.\n  - name:\
  \ Policy Sharing\n    description: Control who can deploy your application using resource-based policies.\n  - name: License Management\n    description: Attach open source licenses to applications using SPDX license identifiers.\n  - name: CloudFormation Integration\n    description: Deploy applications through CloudFormation changesets for full infrastructure-as-code support.\n\n- type: UseCases\n  data:\n  - name: Rapid Prototyping\n    description: Quickly deploy serverless application templates for common patterns like APIs, data processing, and IoT.\n  - name: Internal Application Sharing\n    description: Share production-ready serverless building blocks across teams within your organization.\n  - name: Open Source Distribution\n    description: Publish open source serverless applications to the public SAR catalog.\n  - name: Partner Integration Patterns\n    description: Distribute serverless integration patterns to AWS partner customers.\n  - name: Microservice Templates\n   \
  \ description: Package and share reusable microservice patterns as deployable SAR applications.\n  - name: DevOps Automation\n    description: Automate deployment of pre-vetted serverless infrastructure patterns via CI/CD pipelines.\n\n- type: Integrations\n  data:\n  - name: AWS SAM\n    description: Native integration with the AWS Serverless Application Model for packaging and publishing.\n  - name: AWS CloudFormation\n    description: Applications are deployed via CloudFormation change sets for full IaC integration.\n  - name: AWS Lambda\n    description: The primary compute runtime for all SAR-deployed serverless applications.\n  - name: Amazon API Gateway\n    description: Commonly bundled with SAR applications for HTTP API exposure.\n  - name: AWS CodePipeline\n    description: Automate SAR application publishing as part of CI/CD pipelines.\n  - name: AWS Serverless Framework\n    description: Third-party Serverless Framework plugins support SAR publishing workflows.\n  - name: Amazon\
  \ DynamoDB\n    description: Frequently included as a data store in SAR application templates.\n  - name: Amazon S3\n    description: Used for hosting static content and storing SAR application artifacts.\n\n- type: JSON-LD\n  url: json-ld/amazon-serverless-application-repository-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-serverless-application-repository-application-policy-statement-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-serverless-application-repository-application-summary-schema.json\n- type: JSONStructure\n  url: json-structure/amazon-serverless-application-repository-application-policy-statement-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-serverless-application-repository-application-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-serverless-application-repository-application-summary-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-serverless-application-repository-version-summary-structure.json\n\
  - type: Example\n  url: examples/amazon-serverless-application-repository-application-example.json\n- type: Example\n  url: examples/amazon-serverless-application-repository-application-policy-statement-example.json\n- type: Example\n  url: examples/amazon-serverless-application-repository-application-summary-example.json\n- type: Example\n  url: examples/amazon-serverless-application-repository-version-summary-example.json\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-serverless-application-repository.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-serverless-application-repository/refs/heads/main/apis.yml
tags:
- Application Repository
- Lambda
- SAM
- Serverless
url: https://aws.amazon.com/serverless/serverlessrepo/
use_cases:
- description: Quickly deploy serverless application templates for common patterns like APIs, data processing, and IoT.
  name: Rapid Prototyping
- description: Share production-ready serverless building blocks across teams within your organization.
  name: Internal Application Sharing
- description: Publish open source serverless applications to the public SAR catalog.
  name: Open Source Distribution
- description: Distribute serverless integration patterns to AWS partner customers.
  name: Partner Integration Patterns
- description: Package and share reusable microservice patterns as deployable SAR applications.
  name: Microservice Templates
- description: Automate deployment of pre-vetted serverless infrastructure patterns via CI/CD pipelines.
  name: DevOps Automation
---
