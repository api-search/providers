---
api_count: 1
api_specs:
- filename: amazon-timestream-openapi.yml
  format: yaml
  label: Amazon Timestream API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/openapi/amazon-timestream-openapi.yml
apis:
- description: The Amazon Timestream API provides programmatic access to manage serverless time series databases. It enables developers to create and manage databases and tables, write time series data records, exec
  name: Amazon Timestream API
  slug: ''
capabilities:
- description: ''
  name: Amazon Timestream Capability
  slug: amazon-timestream-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/timestream/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/timestream/
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
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/timestream/
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
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/rules/amazon-timestream-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/vocabulary/amazon-timestream-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/capabilities/amazon-timestream-capability.yaml
created: '2024-01-15'
description: Amazon Timestream is a fast, scalable, and serverless time series database service designed for IoT and operational applications. It makes it easy to store and analyze trillions of events per day at a fraction of the cost of relational databases, with built-in time series analytics functions and automatic data lifecycle management.
features:
- description: Automate operational tasks with Amazon Timestream.
  name: Automation
- description: Programmatic access to Amazon Timestream resources.
  name: API Access
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 0
  name: Amazon Timestream Context
  property_count: 6
  slug: amazon-timestream-context
layout: provider
modified: '2026-04-19'
name: Amazon Timestream
rules:
- name: Amazon Timestream API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-timestream-spectral-rules
skills: []
slug: amazon-timestream
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Timestream\ndescription: Amazon Timestream is a fast, scalable, and serverless time series database service designed for IoT and operational applications. It makes it easy to store and analyze trillions of events\n  per day at a fraction of the cost of relational databases, with built-in time series analytics functions and automatic data lifecycle management.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/timestream/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Timestream API\n  description: >-\n    The Amazon Timestream API provides programmatic access to manage serverless\n    time series databases. It enables developers to create and manage databases\n    and tables, write time series data records, execute queries with built-in\n    time series analytics functions, and configure data retention policies for\n    automatic lifecycle management.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanURL: https://aws.amazon.com/timestream/\n  baseURL: https://ingest.timestream.amazonaws.com\n  tags:\n  - AWS\n  - Database\n  - IoT\n  - Time Series\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/timestream/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/openapi/amazon-timestream-openapi.yml\n  - type: Pricing\n    url: https://aws.amazon.com/timestream/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/timestream/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/timestream/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/timestream/\n- type: Documentation\n  url: https://docs.aws.amazon.com/timestream/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n\
  - type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/timestream/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/rules/amazon-timestream-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/vocabulary/amazon-timestream-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/capabilities/amazon-timestream-capability.yaml\n- type: Features\n  data:\n  - name: Automation\n    description: Automate operational tasks with Amazon Timestream.\n  - name:\
  \ API Access\n    description: Programmatic access to Amazon Timestream resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Timestream to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Database\n- Iot\n- Time Series\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-timestream/refs/heads/main/apis.yml
tags:
- Database
- Iot
- Time Series
url: https://aws.amazon.com/timestream/
use_cases:
- description: Use Amazon Timestream to manage and automate cloud operations.
  name: Cloud Operations
---
