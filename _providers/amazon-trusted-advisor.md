---
api_count: 1
apis:
- description: The AWS Support API provides programmatic access to AWS Trusted Advisor checks, results, and recommendations. It enables retrieving check summaries, refreshing checks, and accessing detailed results f
  name: AWS Trusted Advisor API
  slug: aws-support-api
capabilities:
- description: ''
  name: Amazon Trusted Advisor Capability
  slug: amazon-trusted-advisor-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/premiumsupport/technology/trusted-advisor/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html
- title: ''
  type: Console
  url: https://console.aws.amazon.com/trustedadvisor/
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
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/rules/amazon-trusted-advisor-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/vocabulary/amazon-trusted-advisor-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/capabilities/amazon-trusted-advisor-capability.yaml
created: '2026-03-16'
description: AWS Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices. It inspects your AWS environment and makes recommendations for saving money, improving system performance and reliability, and closing security gaps across cost optimization, performance, security, fault tolerance, and service limits.
features:
- description: Automate operational tasks with Amazon Trusted Advisor.
  name: Automation
- description: Programmatic access to Amazon Trusted Advisor resources.
  name: API Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Trusted Advisor Context
  property_count: 0
  slug: amazon-trusted-advisor-context
layout: provider
modified: '2026-04-19'
name: Amazon Trusted Advisor
rules:
- name: Amazon Trusted Advisor API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-trusted-advisor-spectral-rules
skills: []
slug: amazon-trusted-advisor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-trusted-advisor\nname: Amazon Trusted Advisor\ndescription: >-\n  AWS Trusted Advisor provides real-time guidance to help you provision your\n  resources following AWS best practices. It inspects your AWS environment and\n  makes recommendations for saving money, improving system performance and\n  reliability, and closing security gaps across cost optimization, performance,\n  security, fault tolerance, and service limits.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Best Practices\n- Cloud Optimization\n- Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-trusted-advisor:aws-support-api\n  name: AWS Trusted Advisor API\n  description: >-\n    The AWS Support API provides programmatic access to AWS Trusted Advisor\n    checks, results,\
  \ and recommendations. It enables retrieving check summaries,\n    refreshing checks, and accessing detailed results for cost optimization,\n    performance, security, fault tolerance, and service limits.\n  humanURL: https://aws.amazon.com/premiumsupport/technology/trusted-advisor/\n  baseURL: https://support.us-east-1.amazonaws.com\n  tags:\n  - AWS\n  - Best Practices\n  - Cloud Optimization\n  - Security\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html\n  - type: APIReference\n    url: https://docs.aws.amazon.com/awssupport/latest/APIReference/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/awssupport/latest/user/get-started-with-aws-trusted-advisor.html\n  - type: Pricing\n    url: https://aws.amazon.com/premiumsupport/plans/\n  - type: FAQ\n    url: https://aws.amazon.com/premiumsupport/technology/trusted-advisor/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n\
  \  url: https://aws.amazon.com/premiumsupport/technology/trusted-advisor/\n- type: Documentation\n  url: https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html\n- type: Console\n  url: https://console.aws.amazon.com/trustedadvisor/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/rules/amazon-trusted-advisor-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/vocabulary/amazon-trusted-advisor-vocabulary.yaml\n\
  - type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/capabilities/amazon-trusted-advisor-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon Trusted Advisor.\n  - name: API Access\n    description: Programmatic access to Amazon Trusted Advisor resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Trusted Advisor to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/apis.yml
tags:
- Best Practices
- Cloud Optimization
- Security
url: https://raw.githubusercontent.com/api-evangelist/amazon-trusted-advisor/refs/heads/main/apis.yml
use_cases:
- description: Use Amazon Trusted Advisor to manage and automate cloud operations.
  name: Cloud Operations
---
