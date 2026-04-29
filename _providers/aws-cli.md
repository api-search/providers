---
api_count: 1
apis:
- description: The AWS CLI v2 is the official command-line interface for Amazon Web Services, providing unified access to all AWS services from the terminal with auto-completion, AWS SSO support, and improved perfor
  name: AWS CLI
  slug: aws-cli
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/cli/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cli/
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
- title: ''
  type: GitHubRepository
  url: https://github.com/aws/aws-cli
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: ReleaseNotes
  url: https://github.com/aws/aws-cli/blob/v2/CHANGELOG.rst
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://github.com/aws/aws-cli/issues
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/awscli
created: '2026-03-25'
description: The AWS Command Line Interface (AWS CLI) is a unified tool to manage AWS services from the command line. With just one tool to download and configure, you can control multiple AWS services and automate them through scripts. AWS CLI v2 supports all AWS services with auto-completion, AWS SSO, and improved performance. It is open-source, available on Linux, macOS, and Windows, and is the official CLI for Amazon Web Services.
features:
- description: Control all AWS services from a single command-line tool with consistent syntax and output formatting.
  name: Unified AWS Service Access
- description: Shell auto-completion for commands, subcommands, options, and resource names in bash, zsh, and fish.
  name: Auto-Completion
- description: Native AWS IAM Identity Center (SSO) integration for credential management and multi-account access.
  name: AWS SSO Support
- description: Multiple output formats including JSON, YAML, text, and table, with JMESPath query filtering.
  name: Output Formatting
- description: Supports named profiles, environment variables, instance metadata, and credential process plugins.
  name: Credential Management
- description: Interactive step-by-step wizards for complex workflows like IAM role creation and DynamoDB table setup.
  name: Wizard Commands
- description: Built-in wait commands to poll until AWS resources reach desired states like running or available.
  name: Waiters
- description: Automatic pagination with configurable page size and support for --no-paginate and --page-size flags.
  name: Pagination Control
- description: Stream large binary outputs like EC2 console logs and Lambda function logs directly to stdout.
  name: Streaming Output
- description: Extensible plugin architecture for adding custom commands and credential providers.
  name: Plugin System
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native SSO integration for credential vending and multi-account access management.
  name: AWS IAM Identity Center
- description: Pre-installed in AWS CloudShell for browser-based CLI access without local installation.
  name: AWS CloudShell
- description: Available in CodeBuild build environments for CI/CD pipeline automation.
  name: AWS CodeBuild
- description: Used in GitHub Actions workflows via the configure-aws-credentials action.
  name: GitHub Actions
- description: Installable via Homebrew on macOS for easy installation and updates.
  name: Homebrew
- description: Available via winget for installation on Windows systems.
  name: Windows Package Manager
layout: provider
modified: '2026-04-19'
name: AWS CLI
skills: []
slug: aws-cli
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aws-cli\nname: AWS CLI\ndescription: >-\n  The AWS Command Line Interface (AWS CLI) is a unified tool to manage AWS\n  services from the command line. With just one tool to download and configure,\n  you can control multiple AWS services and automate them through scripts. AWS\n  CLI v2 supports all AWS services with auto-completion, AWS SSO, and improved\n  performance. It is open-source, available on Linux, macOS, and Windows, and\n  is the official CLI for Amazon Web Services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - CLI\n  - Cloud Computing\n  - Command Line Interface\n  - DevOps\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-cli/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-cli:aws-cli\n    name: AWS CLI\n    description: >-\n      The AWS CLI v2 is the official command-line interface\
  \ for Amazon Web\n      Services, providing unified access to all AWS services from the terminal\n      with auto-completion, AWS SSO support, and improved performance over v1.\n    humanURL: https://aws.amazon.com/cli/\n    tags:\n      - AWS\n      - CLI\n      - Command Line Interface\n      - DevOps\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cli/latest/userguide/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/cli/latest/reference/\n      - type: GitHubRepository\n        url: https://github.com/aws/aws-cli\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/cli/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cli/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html\n  - type: GitHubRepository\n\
  \    url: https://github.com/aws/aws-cli\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: ReleaseNotes\n    url: https://github.com/aws/aws-cli/blob/v2/CHANGELOG.rst\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://github.com/aws/aws-cli/issues\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/awscli\n  - type: Features\n    data:\n      - name: Unified AWS Service Access\n        description: Control all AWS services from a single command-line tool with consistent syntax and output formatting.\n      - name: Auto-Completion\n        description: Shell auto-completion for commands, subcommands, options, and resource names in bash, zsh, and fish.\n      - name: AWS SSO Support\n        description: Native AWS IAM Identity Center (SSO) integration for credential management and multi-account access.\n      - name:\
  \ Output Formatting\n        description: Multiple output formats including JSON, YAML, text, and table, with JMESPath query filtering.\n      - name: Credential Management\n        description: Supports named profiles, environment variables, instance metadata, and credential process plugins.\n      - name: Wizard Commands\n        description: Interactive step-by-step wizards for complex workflows like IAM role creation and DynamoDB table setup.\n      - name: Waiters\n        description: Built-in wait commands to poll until AWS resources reach desired states like running or available.\n      - name: Pagination Control\n        description: Automatic pagination with configurable page size and support for --no-paginate and --page-size flags.\n      - name: Streaming Output\n        description: Stream large binary outputs like EC2 console logs and Lambda function logs directly to stdout.\n      - name: Plugin System\n        description: Extensible plugin architecture for adding custom\
  \ commands and credential providers.\n  - type: UseCases\n    data:\n      - name: Infrastructure Automation\n        description: Automate AWS infrastructure provisioning, configuration, and teardown in CI/CD pipelines and scripts.\n      - name: Multi-Account Management\n        description: Manage multiple AWS accounts and regions using named profiles and AWS Organizations.\n      - name: Resource Querying\n        description: Query and filter AWS resource inventories with JMESPath expressions and output formatting.\n      - name: Batch Operations\n        description: Process multiple AWS resources in bulk using shell scripting loops and CLI output piping.\n      - name: Developer Workflows\n        description: Speed up development workflows with quick access to S3, Lambda, DynamoDB, and other services.\n  - type: Integrations\n    data:\n      - name: AWS IAM Identity Center\n        description: Native SSO integration for credential vending and multi-account access management.\n\
  \      - name: AWS CloudShell\n        description: Pre-installed in AWS CloudShell for browser-based CLI access without local installation.\n      - name: AWS CodeBuild\n        description: Available in CodeBuild build environments for CI/CD pipeline automation.\n      - name: GitHub Actions\n        description: Used in GitHub Actions workflows via the configure-aws-credentials action.\n      - name: Homebrew\n        description: Installable via Homebrew on macOS for easy installation and updates.\n      - name: Windows Package Manager\n        description: Available via winget for installation on Windows systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-cli/refs/heads/main/apis.yml
tags:
- AWS
- CLI
- Cloud Computing
- Command Line Interface
- DevOps
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/aws-cli/refs/heads/main/apis.yml
use_cases:
- description: Automate AWS infrastructure provisioning, configuration, and teardown in CI/CD pipelines and scripts.
  name: Infrastructure Automation
- description: Manage multiple AWS accounts and regions using named profiles and AWS Organizations.
  name: Multi-Account Management
- description: Query and filter AWS resource inventories with JMESPath expressions and output formatting.
  name: Resource Querying
- description: Process multiple AWS resources in bulk using shell scripting loops and CLI output piping.
  name: Batch Operations
- description: Speed up development workflows with quick access to S3, Lambda, DynamoDB, and other services.
  name: Developer Workflows
---
