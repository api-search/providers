---
api_count: 1
api_specs:
- filename: amazon-waf-openapi.yml
  format: yaml
  label: Amazon WAF REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/openapi/amazon-waf-openapi.yml
apis:
- description: RESTful API for AWS WAF operations including web ACL management, rule groups, IP sets, regex pattern sets, and logging configurations for protecting web applications.
  name: Amazon WAF REST API
  slug: ''
capabilities:
- description: ''
  name: Amazon Waf Capability
  slug: amazon-waf-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/waf/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/waf/
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
  url: https://aws.amazon.com/blogs/security/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/wafv2/
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
  type: Knowledge Center
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/aws-waf
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/rules/amazon-waf-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/vocabulary/amazon-waf-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/capabilities/amazon-waf-capability.yaml
created: '2024-01-15'
description: AWS WAF is a web application firewall that helps protect web applications and APIs from common web exploits and bots that may affect availability, compromise security, or consume excessive resources.
features:
- description: Automate operational tasks with Amazon WAF.
  name: Automation
- description: Programmatic access to Amazon WAF resources.
  name: API Access
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 7
  name: Amazon Waf Context
  property_count: 5
  slug: amazon-waf-context
layout: provider
modified: '2026-04-19'
name: Amazon WAF
rules:
- name: Amazon WAF API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-waf-spectral-rules
skills: []
slug: amazon-waf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon WAF\ndescription: AWS WAF is a web application firewall that helps protect web applications and APIs from common web exploits and bots that may affect availability, compromise security, or consume \n  excessive resources.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/waf/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon WAF REST API\n  description: RESTful API for AWS WAF operations including web ACL management, rule groups, IP sets, regex pattern sets, and logging configurations for protecting web applications.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/waf/\n  baseURL: https://wafv2.amazonaws.com\n  tags:\n  - AWS\n  - Security\n  - WAF\n  - Web Application Firewall\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/waf/latest/APIReference/\n  - type: OpenAPI\n    url:\
  \ https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/openapi/amazon-waf-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/wafv2/2019-07-29/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-waf-web-acl-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-waf-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/waf/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/waf/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/waf/latest/APIReference/CommonParameters.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: FAQ\n    url: https://aws.amazon.com/waf/faqs/\n  - type: Service Level Agreement\n    url: https://aws.amazon.com/waf/sla/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html\n  - type: API Reference\n    url:\
  \ https://docs.aws.amazon.com/waf/latest/APIReference/Welcome.html\n  - type: Code Examples\n    url: https://docs.aws.amazon.com/waf/latest/developerguide/waf-examples.html\n  - type: Security\n    url: https://docs.aws.amazon.com/waf/latest/developerguide/security.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/waf/\n- type: Documentation\n  url: https://docs.aws.amazon.com/waf/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/security/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/wafv2/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n\
  - type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/aws-waf\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/rules/amazon-waf-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/vocabulary/amazon-waf-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/capabilities/amazon-waf-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon WAF.\n  - name: API Access\n    description: Programmatic access to Amazon WAF resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon\
  \ WAF to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Bot Management\n- Ddos Protection\n- Security\n- WAF\n- Web Application Firewall\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/apis.yml
tags:
- Bot Management
- Ddos Protection
- Security
- WAF
- Web Application Firewall
url: https://aws.amazon.com/waf/
use_cases:
- description: Use Amazon WAF to manage and automate cloud operations.
  name: Cloud Operations
---
