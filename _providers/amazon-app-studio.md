---
api_count: 1
api_specs:
- filename: amazon-app-studio-openapi.yaml
  format: yaml
  label: Amazon App Studio API
  slug: app-studio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/openapi/amazon-app-studio-openapi.yaml
apis:
- description: The Amazon App Studio API provides programmatic access to App Studio application management, enabling automation of low-code application lifecycle operations including listing and retrieving applicati
  name: Amazon App Studio API
  slug: app-studio-api
capabilities:
- description: Workflow for managing App Studio low-code applications.
  name: Amazon App Studio Application Management
  slug: app-studio-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/app-studio/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/app-studio/
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
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://us-east-1.console.aws.amazon.com/appstudio/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: SpectralRules
  url: rules/amazon-app-studio-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/app-studio-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-app-studio-vocabulary.yaml
created: '2026-03-16'
description: Amazon App Studio is a generative AI-powered low-code application builder that enables business users to create internal applications without requiring extensive coding knowledge. Built on AWS infrastructure, App Studio integrates with AWS data sources and services to enable rapid development of enterprise business tools.
features:
- description: Use natural language prompts to generate application layouts, data models, and logic with Amazon Q assistance.
  name: Generative AI Application Builder
- description: Build internal business applications using drag-and-drop components without writing code.
  name: No-Code Application Development
- description: Connect applications to AWS DynamoDB, Aurora, S3, and other data sources with built-in connectors.
  name: AWS Data Source Integration
- description: Configure fine-grained access permissions for application users using AWS IAM Identity Center.
  name: Role-Based Access Control
- description: Deploy internal applications with a single click and share with team members using AWS access controls.
  name: One-Click Deployment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Connect App Studio applications to DynamoDB for serverless NoSQL data storage and retrieval.
  name: Amazon DynamoDB
- description: Use Aurora as a relational database backend for App Studio applications requiring structured data.
  name: Amazon Aurora
- description: Manage user access to App Studio applications using IAM Identity Center for single sign-on.
  name: AWS IAM Identity Center
- description: Leverage Amazon Q generative AI capabilities within App Studio for AI-assisted application development.
  name: Amazon Q
jsonld:
- class_count: 0
  name: Amazon App Studio Context
  property_count: 6
  slug: amazon-app-studio-context
layout: provider
modified: '2026-04-19'
name: Amazon App Studio
rules:
- name: Amazon App Studio API Rules
  rule_count: 3
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 0
  slug: amazon-app-studio-spectral-rules
skills: []
slug: amazon-app-studio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-app-studio\nname: Amazon App Studio\ndescription: >-\n  Amazon App Studio is a generative AI-powered low-code application builder that enables business users to create internal applications without requiring extensive coding knowledge. Built on AWS infrastructure,\n  App Studio integrates with AWS data sources and services to enable rapid development of enterprise business tools.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Generative AI\n- Internal Tools\n- Low-Code\n- No-Code\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-app-studio:app-studio-api\n  name: Amazon App Studio API\n  description: The Amazon App Studio API provides programmatic access to App Studio application management, enabling automation of low-code application lifecycle operations\
  \ including listing and \n    retrieving application details.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/app-studio/\n  baseURL: https://appstudio.amazonaws.com\n  tags:\n  - AWS\n  - Low-Code\n  - No-Code\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/app-studio/\n  - type: OpenAPI\n    url: openapi/amazon-app-studio-openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-app-studio-app-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-studio-appsummary-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-app-studio-listappsresponse-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-app-studio-app-structure.json\n  - type: JSONLD\n    url: json-ld/amazon-app-studio-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/app-studio/pricing/\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type:\
  \ Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/app-studio/\n- type: Documentation\n  url: https://docs.aws.amazon.com/app-studio/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://us-east-1.console.aws.amazon.com/appstudio/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: SpectralRules\n  url: rules/amazon-app-studio-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/app-studio-management.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-app-studio-vocabulary.yaml\n- type: Features\n  data:\n  - name: Generative AI Application Builder\n\
  \    description: Use natural language prompts to generate application layouts, data models, and logic with Amazon Q assistance.\n  - name: No-Code Application Development\n    description: Build internal business applications using drag-and-drop components without writing code.\n  - name: AWS Data Source Integration\n    description: Connect applications to AWS DynamoDB, Aurora, S3, and other data sources with built-in connectors.\n  - name: Role-Based Access Control\n    description: Configure fine-grained access permissions for application users using AWS IAM Identity Center.\n  - name: One-Click Deployment\n    description: Deploy internal applications with a single click and share with team members using AWS access controls.\n- type: UseCases\n  data:\n  - name: Internal Business Tools\n    description: Build inventory management, employee onboarding, and operational dashboards for internal business use.\n  - name: Data Entry Applications\n    description: Create forms and data entry\
  \ tools connected to existing databases for field operations and back-office teams.\n  - name: Workflow Automation\n    description: Automate approval workflows, task management, and process tracking with connected business logic.\n  - name: IT Self-Service Portals\n    description: Build IT request portals, asset management tools, and helpdesk applications for internal teams.\n- type: Integrations\n  data:\n  - name: Amazon DynamoDB\n    description: Connect App Studio applications to DynamoDB for serverless NoSQL data storage and retrieval.\n  - name: Amazon Aurora\n    description: Use Aurora as a relational database backend for App Studio applications requiring structured data.\n  - name: AWS IAM Identity Center\n    description: Manage user access to App Studio applications using IAM Identity Center for single sign-on.\n  - name: Amazon Q\n    description: Leverage Amazon Q generative AI capabilities within App Studio for AI-assisted application development.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/apis.yml
tags:
- Generative AI
- Internal Tools
- Low-Code
- No-Code
url: https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/apis.yml
use_cases:
- description: Build inventory management, employee onboarding, and operational dashboards for internal business use.
  name: Internal Business Tools
- description: Create forms and data entry tools connected to existing databases for field operations and back-office teams.
  name: Data Entry Applications
- description: Automate approval workflows, task management, and process tracking with connected business logic.
  name: Workflow Automation
- description: Build IT request portals, asset management tools, and helpdesk applications for internal teams.
  name: IT Self-Service Portals
---
