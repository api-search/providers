---
api_count: 1
apis:
- description: The Amazon CodePipeline REST API.
  name: Amazon CodePipeline API
  slug: amazon-codepipeline-api
capabilities:
- description: Unified workflow for DevOps and release engineering teams to create and manage delivery pipelines, trigger pipeline executions, monitor pipeline status, and manage pipeline artifacts using Amazon Code
  name: Amazon CodePipeline Release Pipeline Automation
  slug: amazon-codepipeline-release-pipeline
common:
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/codepipeline
- title: ''
  type: Pricing
  url: https://aws.amazon.com/codepipeline/pricing/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/codepipeline/
- title: ''
  type: Portal
  url: https://aws.amazon.com/codepipeline/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/codepipeline/
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
  url: rules/amazon-codepipeline-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-codepipeline-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-codepipeline-release-pipeline.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-codepipeline-context.jsonld
created: '2026-03-16'
description: AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define.
features:
- description: Automate the entire release process from source code to production with customizable pipeline stages and actions.
  name: Pipeline Automation
- description: Run multiple actions in parallel within a pipeline stage to speed up your delivery workflows.
  name: Parallel Execution
- description: Add manual approval gates to pipelines for human review before promoting changes to production environments.
  name: Manual Approval Actions
- description: Define conditions that must be met for a pipeline to proceed, including CloudWatch alarms and custom conditions.
  name: Pipeline Conditions
- description: Deploy to multiple AWS accounts and regions from a single pipeline using cross-account roles and artifact stores.
  name: Cross-Account Deployments
- description: Create custom pipeline actions using Lambda functions or CodeBuild projects for specialized workflow steps.
  name: Custom Actions
- description: Track the full execution history of each pipeline run including status, timing, and artifact details for each action.
  name: Execution History
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use CodeBuild as the build and test stage in pipelines.
  name: AWS CodeBuild
- description: Use CodeDeploy as the deployment stage for EC2, Lambda, and ECS targets.
  name: AWS CodeDeploy
- description: Trigger pipelines automatically on CodeCommit repository changes.
  name: AWS CodeCommit
- description: Connect GitHub repositories as pipeline source stages with webhook triggers.
  name: GitHub
- description: Use S3 as a source stage or for storing pipeline artifacts between stages.
  name: Amazon S3
- description: Deploy infrastructure as code using CloudFormation actions in pipeline stages.
  name: AWS CloudFormation
- description: Deploy application updates to Elastic Beanstalk environments from pipelines.
  name: AWS Elastic Beanstalk
- description: Deploy container updates to ECS services as a pipeline deployment stage.
  name: Amazon ECS
- description: Trigger pipelines from EventBridge events for event-driven delivery workflows.
  name: Amazon EventBridge
jsonld:
- class_count: 9
  name: Amazon Codepipeline Context
  property_count: 23
  slug: amazon-codepipeline-context
layout: provider
modified: '2026-04-19'
name: Amazon CodePipeline
rules:
- name: Amazon CodePipeline API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 4
  slug: amazon-codepipeline-spectral-rules
skills: []
slug: amazon-codepipeline
solutions: []
source_yaml: "aid: amazon-codepipeline\nname: Amazon CodePipeline\ndescription: AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline \n  automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Amazon\n- AWS\n- CI/CD\n- Continuous Delivery\n- DevOps\n- Pipeline\n- Release Automation\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-codepipeline/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-codepipeline:amazon-codepipeline-api\n  name: Amazon CodePipeline API\n  description: The Amazon CodePipeline REST API.\n  humanURL: https://docs.aws.amazon.com/codepipeline/latest/APIReference/Welcome.html\n\
  \  baseURL: https://codepipeline.us-east-1.amazonaws.com\n  tags:\n  - Amazon\n  - AWS\n  - CI/CD\n  - Continuous Delivery\n  - DevOps\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/codepipeline/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/codepipeline/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-codepipeline-openapi-original.yaml\ncommon:\n- type: GettingStarted\n  url: https://docs.aws.amazon.com/codepipeline\n- type: Pricing\n  url: https://aws.amazon.com/codepipeline/pricing/\n- type: Console\n  url: https://console.aws.amazon.com/codepipeline/\n- type: Portal\n  url: https://aws.amazon.com/codepipeline/\n- type: Documentation\n  url: https://docs.aws.amazon.com/codepipeline/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Blog\n  url: https://aws.amazon.com/blogs/devops/\n\
  - type: SignUp\n  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: SpectralRules\n  url: rules/amazon-codepipeline-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-codepipeline-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-codepipeline-release-pipeline.yaml\n- type: JSONLD\n  url: json-ld/amazon-codepipeline-context.jsonld\n- type: Features\n  data:\n  - name: Pipeline Automation\n    description: Automate the entire release process from source code to production with customizable pipeline stages and actions.\n  - name: Parallel Execution\n    description: Run multiple actions in parallel within a pipeline stage to speed up your delivery workflows.\n  - name: Manual Approval Actions\n    description: Add manual approval gates to pipelines for human review before promoting changes to production environments.\n  - name: Pipeline Conditions\n    description:\
  \ Define conditions that must be met for a pipeline to proceed, including CloudWatch alarms and custom conditions.\n  - name: Cross-Account Deployments\n    description: Deploy to multiple AWS accounts and regions from a single pipeline using cross-account roles and artifact stores.\n  - name: Custom Actions\n    description: Create custom pipeline actions using Lambda functions or CodeBuild projects for specialized workflow steps.\n  - name: Execution History\n    description: Track the full execution history of each pipeline run including status, timing, and artifact details for each action.\n- type: UseCases\n  data:\n  - name: Continuous Delivery Pipeline\n    description: Automate the entire software delivery lifecycle from source commit through build, test, staging, and production deployment.\n  - name: Multi-Environment Promotion\n    description: Automatically promote changes through development, staging, and production environments with approval gates between stages.\n  - name:\
  \ Infrastructure as Code Deployment\n    description: Deploy CloudFormation stacks and Terraform configurations as pipeline stages for automated infrastructure provisioning.\n  - name: Microservices Delivery\n    description: Orchestrate independent delivery pipelines for multiple microservices, each triggered by its own source repository.\n  - name: Blue/Green Deployments\n    description: Use CodeDeploy actions in pipelines to implement zero-downtime blue/green deployments automatically.\n- type: Integrations\n  data:\n  - name: AWS CodeBuild\n    description: Use CodeBuild as the build and test stage in pipelines.\n  - name: AWS CodeDeploy\n    description: Use CodeDeploy as the deployment stage for EC2, Lambda, and ECS targets.\n  - name: AWS CodeCommit\n    description: Trigger pipelines automatically on CodeCommit repository changes.\n  - name: GitHub\n    description: Connect GitHub repositories as pipeline source stages with webhook triggers.\n  - name: Amazon S3\n    description:\
  \ Use S3 as a source stage or for storing pipeline artifacts between stages.\n  - name: AWS CloudFormation\n    description: Deploy infrastructure as code using CloudFormation actions in pipeline stages.\n  - name: AWS Elastic Beanstalk\n    description: Deploy application updates to Elastic Beanstalk environments from pipelines.\n  - name: Amazon ECS\n    description: Deploy container updates to ECS services as a pipeline deployment stage.\n  - name: Amazon EventBridge\n    description: Trigger pipelines from EventBridge events for event-driven delivery workflows.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-codepipeline/refs/heads/main/apis.yml
tags:
- Amazon
- AWS
- CI/CD
- Continuous Delivery
- DevOps
- Pipeline
- Release Automation
url: https://raw.githubusercontent.com/api-evangelist/amazon-codepipeline/refs/heads/main/apis.yml
use_cases:
- description: Automate the entire software delivery lifecycle from source commit through build, test, staging, and production deployment.
  name: Continuous Delivery Pipeline
- description: Automatically promote changes through development, staging, and production environments with approval gates between stages.
  name: Multi-Environment Promotion
- description: Deploy CloudFormation stacks and Terraform configurations as pipeline stages for automated infrastructure provisioning.
  name: Infrastructure as Code Deployment
- description: Orchestrate independent delivery pipelines for multiple microservices, each triggered by its own source repository.
  name: Microservices Delivery
- description: Use CodeDeploy actions in pipelines to implement zero-downtime blue/green deployments automatically.
  name: Blue/Green Deployments
---
