---
api_count: 1
apis:
- description: API for creating and managing CloudShell environments — browser-based terminal sessions for AWS resource management.
  name: Amazon CloudShell API
  slug: ''
capabilities:
- description: Workflow for cloud shell environment management using Amazon CloudShell for Cloud Administrator personas.
  name: Amazon CloudShell Cloud Shell Environment Management
  slug: shell-environment
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloudshell/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cloudshell/latest/userguide/
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
  url: https://aws.amazon.com/blogs/developer/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cloudshell/
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
  url: https://stackoverflow.com/questions/tagged/aws-cloudshell
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloudshell-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloudshell-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shell-environment.yaml
created: '2026-03-16'
description: AWS CloudShell is a browser-based terminal that enables users to manage and explore AWS resources directly from the AWS Management Console. Pre-authenticated, pre-installed with AWS CLI and dev tools, with 1 GB of persistent storage per region.
features:
- description: Sign in with AWS Console credentials — no additional authentication required.
  name: Pre-Authenticated Access
- description: Amazon Linux 2 environment with AWS CLI, SDKs, and development tools pre-installed.
  name: Pre-Installed Tools
- description: Up to 1 GB of persistent storage per AWS region for scripts and configurations.
  name: Persistent Storage
- description: Running commands in CloudShell incurs no extra charges beyond standard AWS service fees.
  name: No Additional Cost
- description: Upload and download files directly from the browser.
  name: File Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Launch directly from any AWS Console page with existing credentials.
  name: AWS Management Console
- description: Pre-installed and pre-configured AWS CLI for all service access.
  name: AWS CLI
- description: CloudShell inherits permissions from the signed-in IAM user or role.
  name: AWS IAM
- description: Upload files to and download files from S3 using CloudShell.
  name: Amazon S3
layout: provider
modified: '2026-04-19'
name: Amazon CloudShell
rules:
- name: Amazon CloudShell API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: amazon-cloudshell-spectral-rules
skills: []
slug: amazon-cloudshell
solutions: []
source_yaml: "aid: amazon-cloudshell\nname: Amazon CloudShell\ndescription: >-\n  AWS CloudShell is a browser-based terminal that enables users to manage and explore AWS resources directly from the AWS Management Console. Pre-authenticated, pre-installed with AWS CLI and dev tools,\n  with 1 GB of persistent storage per region.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- CloudShell\n- Terminal\n- CLI\n- Browser-Based\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cloudshell/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- name: Amazon CloudShell API\n  description: API for creating and managing CloudShell environments — browser-based terminal sessions for AWS resource management.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/cloudshell/\n  baseURL: https://cloudshell.us-east-1.amazonaws.com\n\
  \  tags:\n  - AWS\n  - CloudShell\n  - Terminal\n  - Development\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cloudshell/latest/userguide/\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudshell/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudshell/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudshell/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/cloudshell/latest/userguide/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudshell/\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/cloudshell/\n- type: Documentation\n  url: https://docs.aws.amazon.com/cloudshell/latest/userguide/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n\
  - type: Blog\n  url: https://aws.amazon.com/blogs/developer/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudshell/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-cloudshell\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-cloudshell-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloudshell-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shell-environment.yaml\n- type: Features\n  data:\n  - name: Pre-Authenticated Access\n    description: Sign in with AWS Console credentials — no additional authentication required.\n\
  \  - name: Pre-Installed Tools\n    description: Amazon Linux 2 environment with AWS CLI, SDKs, and development tools pre-installed.\n  - name: Persistent Storage\n    description: Up to 1 GB of persistent storage per AWS region for scripts and configurations.\n  - name: No Additional Cost\n    description: Running commands in CloudShell incurs no extra charges beyond standard AWS service fees.\n  - name: File Management\n    description: Upload and download files directly from the browser.\n- type: UseCases\n  data:\n  - name: Quick CLI Access\n    description: Execute AWS CLI commands from any browser without local setup.\n  - name: Script Execution\n    description: Run existing scripts with integrated AWS CLI documentation and auto-completion.\n  - name: Security Operations\n    description: Reduce incident response times with seamless console-authenticated terminal access.\n  - name: Training and Demos\n    description: Provide consistent, pre-configured AWS environments for training\
  \ and demonstrations.\n- type: Integrations\n  data:\n  - name: AWS Management Console\n    description: Launch directly from any AWS Console page with existing credentials.\n  - name: AWS CLI\n    description: Pre-installed and pre-configured AWS CLI for all service access.\n  - name: AWS IAM\n    description: CloudShell inherits permissions from the signed-in IAM user or role.\n  - name: Amazon S3\n    description: Upload files to and download files from S3 using CloudShell.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudshell/refs/heads/main/apis.yml
tags:
- AWS
- CloudShell
- Terminal
- CLI
- Browser-Based
url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudshell/refs/heads/main/apis.yml
use_cases:
- description: Execute AWS CLI commands from any browser without local setup.
  name: Quick CLI Access
- description: Run existing scripts with integrated AWS CLI documentation and auto-completion.
  name: Script Execution
- description: Reduce incident response times with seamless console-authenticated terminal access.
  name: Security Operations
- description: Provide consistent, pre-configured AWS environments for training and demonstrations.
  name: Training and Demos
---
