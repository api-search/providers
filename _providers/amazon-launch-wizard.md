---
api_count: 1
apis:
- description: The AWS Launch Wizard API provides programmatic access to manage deployments, workload specs, and deployment events for guided enterprise application deployments on AWS.
  name: AWS Launch Wizard API
  slug: aws-launch-wizard-api
capabilities:
- description: Unified workflow capability for Amazon Launch Wizard combining resource management and operations.
  name: Amazon Launch Wizard Workflow
  slug: amazon-launch-wizard-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/launchwizard/
- title: ''
  type: Portal
  url: https://aws.amazon.com/launchwizard/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/launchwizard/
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
  url: https://aws.amazon.com/blogs/apn/tag/aws-launch-wizard/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/launchwizard/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-launch-wizard-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-launch-wizard-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-launch-wizard-vocabulary.yaml
created: '2026-03-16'
description: AWS Launch Wizard is a service that guides you through the sizing, configuration, and deployment of enterprise applications on AWS, such as Microsoft SQL Server Always On and HANA-based SAP systems, without the need to manually identify and provision individual AWS resources.
features:
- description: Step-by-step guidance to size, configure, and deploy enterprise applications on AWS.
  name: Guided Deployment
- description: Deploy SAP HANA and SAP NetWeaver on AWS with automated infrastructure sizing and setup.
  name: SAP Support
- description: Deploy Microsoft SQL Server on AWS with Always On availability groups and best practices.
  name: SQL Server Support
- description: Deploy Microsoft Active Directory on AWS with recommended configurations.
  name: Active Directory Support
- description: Estimate the cost of your deployment before provisioning resources.
  name: Cost Estimation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Launch Wizard generates CloudFormation templates for repeatable infrastructure deployments.
  name: AWS CloudFormation
- description: Provisions and configures EC2 instances with recommended sizes for enterprise workloads.
  name: Amazon EC2
- description: Attaches appropriately sized EBS volumes optimized for enterprise application performance.
  name: Amazon EBS
- description: Uses Systems Manager for configuration management and post-deployment tasks.
  name: AWS Systems Manager
jsonld:
- class_count: 1
  name: Amazon Launch Wizard Context
  property_count: 7
  slug: amazon-launch-wizard-context
layout: provider
modified: '2026-04-19'
name: Amazon Launch Wizard
rules:
- name: Amazon Launch Wizard API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-launch-wizard-spectral-rules
skills: []
slug: amazon-launch-wizard
solutions: []
source_yaml: "aid: amazon-launch-wizard\nname: Amazon Launch Wizard\ndescription: >-\n  AWS Launch Wizard is a service that guides you through the sizing, configuration,\n  and deployment of enterprise applications on AWS, such as Microsoft SQL Server\n  Always On and HANA-based SAP systems, without the need to manually identify\n  and provision individual AWS resources.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Deployment\n- Enterprise Applications\n- SAP\n- SQL Server\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-launch-wizard/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-launch-wizard:aws-launch-wizard-api\n  name: AWS Launch Wizard API\n  description: >-\n    The AWS Launch Wizard API provides programmatic access to manage\n    deployments, workload specs, and deployment events for guided enterprise\n    application\
  \ deployments on AWS.\n  humanURL: https://aws.amazon.com/launchwizard/\n  baseURL: https://launchwizard.amazonaws.com\n  tags:\n  - Automation\n  - Deployment\n  - Enterprise Applications\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/launchwizard/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/launchwizard/2018-05-10/openapi.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/launchwizard/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/launchwizard/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/launchwizard/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-launch-wizard-deployment-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-launch-wizard-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/launchwizard/\n- type: Portal\n  url: https://aws.amazon.com/launchwizard/\n- type: Documentation\n  url: https://docs.aws.amazon.com/launchwizard/\n\
  - type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/apn/tag/aws-launch-wizard/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/launchwizard/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Features\n  data:\n  - name: Guided Deployment\n    description: Step-by-step guidance to size, configure, and deploy enterprise applications on AWS.\n  - name: SAP Support\n    description: Deploy SAP HANA and SAP NetWeaver on AWS with automated infrastructure sizing and setup.\n  - name: SQL Server Support\n    description: Deploy Microsoft\
  \ SQL Server on AWS with Always On availability groups and best practices.\n  - name: Active Directory Support\n    description: Deploy Microsoft Active Directory on AWS with recommended configurations.\n  - name: Cost Estimation\n    description: Estimate the cost of your deployment before provisioning resources.\n- type: UseCases\n  data:\n  - name: SAP Migration\n    description: Migrate SAP workloads to AWS with guided deployment and AWS best practices.\n  - name: SQL Server HA\n    description: Deploy highly available SQL Server with Always On availability groups.\n  - name: Active Directory Setup\n    description: Deploy and configure Active Directory on AWS for enterprise identity management.\n- type: Integrations\n  data:\n  - name: AWS CloudFormation\n    description: Launch Wizard generates CloudFormation templates for repeatable infrastructure deployments.\n  - name: Amazon EC2\n    description: Provisions and configures EC2 instances with recommended sizes for enterprise workloads.\n\
  \  - name: Amazon EBS\n    description: Attaches appropriately sized EBS volumes optimized for enterprise application performance.\n  - name: AWS Systems Manager\n    description: Uses Systems Manager for configuration management and post-deployment tasks.\n- type: SpectralRules\n  url: rules/amazon-launch-wizard-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-launch-wizard-workflow.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-launch-wizard-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-launch-wizard/refs/heads/main/apis.yml
tags:
- AWS
- Deployment
- Enterprise Applications
- SAP
- SQL Server
url: https://raw.githubusercontent.com/api-evangelist/amazon-launch-wizard/refs/heads/main/apis.yml
use_cases:
- description: Migrate SAP workloads to AWS with guided deployment and AWS best practices.
  name: SAP Migration
- description: Deploy highly available SQL Server with Always On availability groups.
  name: SQL Server HA
- description: Deploy and configure Active Directory on AWS for enterprise identity management.
  name: Active Directory Setup
---
