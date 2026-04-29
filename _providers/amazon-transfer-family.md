---
api_count: 1
apis:
- description: The AWS Transfer Family API provides programmatic access to create and manage SFTP, FTPS, and FTP file transfer servers. It enables managing users, SSH public keys, roles, and server configurations fo
  name: AWS Transfer Family API
  slug: amazon-transfer-family-api
capabilities:
- description: ''
  name: Amazon Transfer Family Capability
  slug: amazon-transfer-family-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/aws-transfer-family/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/transfer/latest/userguide/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/transfer/
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/rules/amazon-transfer-family-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/vocabulary/amazon-transfer-family-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/capabilities/amazon-transfer-family-capability.yaml
created: '2026-03-16'
description: AWS Transfer Family is a secure transfer service that enables you to transfer files into and out of AWS storage services. It supports SFTP, FTPS, and FTP protocols, providing a fully managed file transfer service with native integration to Amazon S3 and Amazon EFS.
features:
- description: Automate operational tasks with Amazon Transfer Family.
  name: Automation
- description: Programmatic access to Amazon Transfer Family resources.
  name: API Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Transfer Family Context
  property_count: 0
  slug: amazon-transfer-family-context
layout: provider
modified: '2026-04-19'
name: Amazon Transfer Family
rules:
- name: Amazon Transfer Family API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: amazon-transfer-family-spectral-rules
skills: []
slug: amazon-transfer-family
solutions: []
source_yaml: "aid: amazon-transfer-family\nname: Amazon Transfer Family\ndescription: >-\n  AWS Transfer Family is a secure transfer service that enables you to transfer\n  files into and out of AWS storage services. It supports SFTP, FTPS, and FTP\n  protocols, providing a fully managed file transfer service with native\n  integration to Amazon S3 and Amazon EFS.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- File Transfer\n- FTP\n- SFTP\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-transfer-family:amazon-transfer-family-api\n  name: AWS Transfer Family API\n  description: >-\n    The AWS Transfer Family API provides programmatic access to create and\n    manage SFTP, FTPS, and FTP file transfer servers. It enables managing\n    users, SSH public keys, roles, and\
  \ server configurations for secure\n    file transfer workflows integrated with Amazon S3 and EFS.\n  humanURL: https://aws.amazon.com/aws-transfer-family/\n  baseURL: https://transfer.amazonaws.com\n  tags:\n  - AWS\n  - File Transfer\n  - SFTP\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/transfer/latest/userguide/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/transfer/latest/userguide/API_Operations.html\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/transfer/latest/userguide/getting-started.html\n  - type: Pricing\n    url: https://aws.amazon.com/aws-transfer-family/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/aws-transfer-family/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/aws-transfer-family/\n- type: Documentation\n  url: https://docs.aws.amazon.com/transfer/latest/userguide/\n- type: Console\n  url: https://console.aws.amazon.com/transfer/\n\
  - type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/rules/amazon-transfer-family-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/vocabulary/amazon-transfer-family-vocabulary.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/capabilities/amazon-transfer-family-capability.yaml\n- type: Features\n  data:\n\
  \  - name: Automation\n    description: Automate operational tasks with Amazon Transfer Family.\n  - name: API Access\n    description: Programmatic access to Amazon Transfer Family resources.\n- type: UseCases\n  data:\n  - name: Cloud Operations\n    description: Use Amazon Transfer Family to manage and automate cloud operations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/apis.yml
tags:
- AWS
- File Transfer
- FTP
- SFTP
url: https://raw.githubusercontent.com/api-evangelist/amazon-transfer-family/refs/heads/main/apis.yml
use_cases:
- description: Use Amazon Transfer Family to manage and automate cloud operations.
  name: Cloud Operations
---
