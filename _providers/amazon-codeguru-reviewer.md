---
api_count: 1
api_specs:
- filename: amazon-codeguru-reviewer-openapi-original.yaml
  format: yaml
  label: Amazon CodeGuru Reviewer API
  slug: amazon-codeguru-reviewer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/openapi/amazon-codeguru-reviewer-openapi-original.yaml
apis:
- description: The Amazon CodeGuru Reviewer REST API.
  name: Amazon CodeGuru Reviewer API
  slug: amazon-codeguru-reviewer-api
capabilities:
- description: Unified workflow for DevOps teams to manage repository associations, trigger code reviews, retrieve recommendations, and track code quality metrics using Amazon CodeGuru Reviewer.
  name: Amazon CodeGuru Reviewer Automated Code Review
  slug: amazon-codeguru-reviewer-code-review
common:
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/codeguru/reviewer
- title: ''
  type: Pricing
  url: https://aws.amazon.com/codegurureviewer/pricing/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/codegurureviewer/
- title: ''
  type: Portal
  url: https://aws.amazon.com/codegurureviewer/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/codegurureviewer/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/devops/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: rules/amazon-codeguru-reviewer-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-codeguru-reviewer-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-codeguru-reviewer-code-review.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-codeguru-reviewer-context.jsonld
created: '2026-03-16'
description: Amazon CodeGuru Reviewer is an automated code review service that uses machine learning and AWS best practices to identify security vulnerabilities, bugs, and hard-to-detect issues in your Java and Python code. It provides intelligent recommendations to help improve code quality and find defects that may be difficult to detect through manual code reviews.
features:
- description: Automatically analyze code changes in pull requests and provide recommendations for bugs, security vulnerabilities, and code quality issues.
  name: Automated Code Review
- description: Detect security vulnerabilities including OWASP Top 10, input validation issues, encryption problems, and AWS API security best practices.
  name: Security Analysis
- description: Analyze Java and Python code with language-specific recommendations based on AWS best practices.
  name: Java and Python Support
- description: Connect CodeGuru Reviewer to GitHub, GitHub Enterprise, Bitbucket, CodeCommit, and S3 repositories.
  name: Repository Association
- description: Automatically trigger code reviews on new pull requests and post recommendations as inline comments.
  name: Pull Request Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Associate GitHub repositories for automated code reviews on pull requests.
  name: GitHub
- description: Connect self-hosted GitHub Enterprise repositories for automated code review.
  name: GitHub Enterprise
- description: Integrate with Bitbucket repositories for pull request code reviews.
  name: Bitbucket
- description: Analyze CodeCommit repositories and pull requests natively.
  name: AWS CodeCommit
- description: Associate S3 buckets for one-time code analysis.
  name: Amazon S3
- description: Combine code review recommendations with profiling insights for comprehensive code quality.
  name: Amazon CodeGuru Profiler
jsonld:
- class_count: 40
  name: Amazon Codeguru Reviewer Context
  property_count: 78
  slug: amazon-codeguru-reviewer-context
layout: provider
modified: '2026-04-19'
name: Amazon CodeGuru Reviewer
rules:
- name: Amazon CodeGuru Reviewer API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 4
  slug: amazon-codeguru-reviewer-spectral-rules
skills: []
slug: amazon-codeguru-reviewer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-codeguru-reviewer\nname: Amazon CodeGuru Reviewer\ndescription: Amazon CodeGuru Reviewer is an automated code review service that uses machine learning and AWS best practices to identify security vulnerabilities, bugs, and hard-to-detect issues in \n  your Java and Python code. It provides intelligent recommendations to help improve code quality and find defects that may be difficult to detect through manual code reviews.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Amazon\n- AWS\n- Code Review\n- Security\n- DevOps\n- Machine Learning\n- Developer Tools\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-codeguru-reviewer:amazon-codeguru-reviewer-api\n  name: Amazon CodeGuru Reviewer API\n  description: The Amazon CodeGuru Reviewer REST API.\n  humanURL:\
  \ https://docs.aws.amazon.com/codeguru/latest/reviewer-api/Welcome.html\n  baseURL: https://codeguru-reviewer.us-east-1.amazonaws.com\n  tags:\n  - Amazon\n  - AWS\n  - Code Review\n  - Security\n  - DevOps\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/codegurureviewer/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/codeguru/latest/reviewer-api/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-codeguru-reviewer-openapi-original.yaml\ncommon:\n- type: GettingStarted\n  url: https://docs.aws.amazon.com/codeguru/reviewer\n- type: Pricing\n  url: https://aws.amazon.com/codegurureviewer/pricing/\n- type: Console\n  url: https://console.aws.amazon.com/codegurureviewer/\n- type: Portal\n  url: https://aws.amazon.com/codegurureviewer/\n- type: Documentation\n  url: https://docs.aws.amazon.com/codegurureviewer/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n\
  - type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Blog\n  url: https://aws.amazon.com/blogs/devops/\n- type: SignUp\n  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: rules/amazon-codeguru-reviewer-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-codeguru-reviewer-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-codeguru-reviewer-code-review.yaml\n- type: JSONLD\n  url: json-ld/amazon-codeguru-reviewer-context.jsonld\n- type: Features\n  data:\n  - name: Automated Code Review\n    description: Automatically analyze code changes in pull requests and provide recommendations for bugs, security vulnerabilities, and code quality issues.\n  - name: Security Analysis\n    description: Detect security vulnerabilities including OWASP Top 10, input validation issues, encryption problems, and AWS API security best\
  \ practices.\n  - name: Java and Python Support\n    description: Analyze Java and Python code with language-specific recommendations based on AWS best practices.\n  - name: Repository Association\n    description: Connect CodeGuru Reviewer to GitHub, GitHub Enterprise, Bitbucket, CodeCommit, and S3 repositories.\n  - name: Pull Request Integration\n    description: Automatically trigger code reviews on new pull requests and post recommendations as inline comments.\n- type: UseCases\n  data:\n  - name: Security Vulnerability Detection\n    description: Automatically detect security issues in code changes before they reach production, reducing security review burden on developers.\n  - name: Automated Code Quality Enforcement\n    description: Enforce code quality standards across the organization with consistent, automated review feedback on every pull request.\n  - name: Developer Productivity\n    description: Help developers identify and fix common coding errors and anti-patterns earlier\
  \ in the development cycle.\n- type: Integrations\n  data:\n  - name: GitHub\n    description: Associate GitHub repositories for automated code reviews on pull requests.\n  - name: GitHub Enterprise\n    description: Connect self-hosted GitHub Enterprise repositories for automated code review.\n  - name: Bitbucket\n    description: Integrate with Bitbucket repositories for pull request code reviews.\n  - name: AWS CodeCommit\n    description: Analyze CodeCommit repositories and pull requests natively.\n  - name: Amazon S3\n    description: Associate S3 buckets for one-time code analysis.\n  - name: Amazon CodeGuru Profiler\n    description: Combine code review recommendations with profiling insights for comprehensive code quality.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/apis.yml
tags:
- Amazon
- Code Review
- Security
- DevOps
- Machine Learning
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/apis.yml
use_cases:
- description: Automatically detect security issues in code changes before they reach production, reducing security review burden on developers.
  name: Security Vulnerability Detection
- description: Enforce code quality standards across the organization with consistent, automated review feedback on every pull request.
  name: Automated Code Quality Enforcement
- description: Help developers identify and fix common coding errors and anti-patterns earlier in the development cycle.
  name: Developer Productivity
---
