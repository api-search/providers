---
api_count: 1
apis:
- description: 'The Amazon CodeDeploy REST API enables programmatic management of applications, deployment groups, deployment configurations, and deployments. Create and update deployment groups, trigger deployments '
  name: Amazon CodeDeploy API
  slug: amazon-codedeploy-api
capabilities:
- description: Unified workflow for DevOps teams to create deployment groups, deploy revisions to EC2, Lambda, and ECS targets, and monitor deployment status.
  name: Amazon CodeDeploy Deployment Automation
  slug: amazon-codedeploy-deployment-automation
common:
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/codedeploy/latest/userguide/getting-started-codedeploy.html
- title: ''
  type: Authentication
  url: https://docs.aws.amazon.com/codedeploy/latest/userguide/auth-and-access-control.html
- title: ''
  type: Pricing
  url: https://aws.amazon.com/codedeploy/pricing/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/codedeploy/
- title: ''
  type: Portal
  url: https://aws.amazon.com/codedeploy/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/codedeploy/latest/userguide/
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
  type: FAQ
  url: https://aws.amazon.com/codedeploy/faqs/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: rules/amazon-codedeploy-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-codedeploy-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-codedeploy-deployment-automation.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-codedeploy-context.jsonld
created: '2026-03-16'
description: AWS CodeDeploy is a fully managed deployment service that automates software deployments to various compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and on-premises servers. CodeDeploy makes it easier to rapidly release new features, helps avoid downtime during application deployment, and handles the complexity of updating your applications with in-place, blue/green, and canary deployment strategies.
features:
- description: Support for in-place, blue/green, and canary deployment strategies across EC2, Lambda, ECS, and on-premises targets to minimize downtime and risk.
  name: Multiple Deployment Strategies
- description: Automatically roll back deployments if a specified number of instances fail health checks or if CloudWatch alarms are triggered during deployment.
  name: Automated Rollbacks
- description: Define custom lifecycle event hooks (BeforeInstall, AfterInstall, ApplicationStart, etc.) using scripts or Lambda functions for fine-grained deployment control.
  name: Deployment Lifecycle Hooks
- description: Implement canary and linear traffic shifting for Lambda function updates and ECS service deployments with configurable traffic weights and bake times.
  name: Traffic Shifting for Lambda and ECS
- description: Organize deployment targets using deployment groups with EC2 instance tags, Auto Scaling groups, ECS clusters, or on-premises instance tags.
  name: Deployment Groups
- description: Install the CodeDeploy agent on EC2 or on-premises instances to enable deployment target registration and lifecycle hook execution.
  name: CodeDeploy Agent
- description: Integrate with Application Load Balancers and Network Load Balancers for blue/green deployments that shift traffic between original and replacement instances.
  name: Integration with AWS Load Balancers
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use CodeDeploy as the deployment stage in CodePipeline CD pipelines.
  name: AWS CodePipeline
- description: Trigger CodeDeploy deployments from build artifacts produced by CodeBuild.
  name: AWS CodeBuild
- description: Deploy Lambda function updates with traffic shifting strategies.
  name: AWS Lambda
- description: Deploy ECS service updates with blue/green deployments.
  name: Amazon ECS
- description: Trigger automatic rollbacks based on CloudWatch alarm states.
  name: AWS CloudWatch
- description: Integrate with ALB and NLB for blue/green traffic shifting.
  name: Elastic Load Balancing
- description: Deploy to Auto Scaling groups with automatic instance health checking.
  name: Amazon EC2 Auto Scaling
- description: Use SSM Run Command and State Manager for deployment automation.
  name: AWS Systems Manager
- description: Deploy application revisions stored in GitHub repositories.
  name: GitHub
- description: Store and retrieve application deployment bundles from S3.
  name: Amazon S3
jsonld:
- class_count: 16
  name: Amazon Codedeploy Context
  property_count: 29
  slug: amazon-codedeploy-context
layout: provider
modified: '2026-04-19'
name: Amazon CodeDeploy
rules:
- name: Amazon CodeDeploy API Rules
  rule_count: 9
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 3
  slug: amazon-codedeploy-spectral-rules
skills: []
slug: amazon-codedeploy
solutions: []
source_yaml: "aid: amazon-codedeploy\nname: Amazon CodeDeploy\ndescription: >-\n  AWS CodeDeploy is a fully managed deployment service that automates software deployments to various compute\n  services such as Amazon EC2, AWS Fargate, AWS Lambda, and on-premises servers. CodeDeploy makes it easier to\n  rapidly release new features, helps avoid downtime during application deployment, and handles the complexity of\n  updating your applications with in-place, blue/green, and canary deployment strategies.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon\n  - AWS\n  - Deployment\n  - DevOps\n  - CI/CD\n  - Release Management\n  - Blue/Green Deployment\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-codedeploy/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-codedeploy:amazon-codedeploy-api\n    name: Amazon CodeDeploy API\n    description:\
  \ >-\n      The Amazon CodeDeploy REST API enables programmatic management of applications, deployment groups, deployment\n      configurations, and deployments. Create and update deployment groups, trigger deployments to EC2, Lambda, ECS,\n      and on-premises targets, monitor deployment status, and manage deployment lifecycle hooks and rollback policies.\n    humanURL: https://docs.aws.amazon.com/codedeploy/latest/APIReference/Welcome.html\n    baseURL: https://codedeploy.us-east-1.amazonaws.com\n    tags:\n      - Amazon\n      - AWS\n      - Deployment\n      - DevOps\n      - CI/CD\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/codedeploy/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-codedeploy-openapi-original.yaml\ncommon:\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/codedeploy/latest/userguide/getting-started-codedeploy.html\n\
  \  - type: Authentication\n    url: https://docs.aws.amazon.com/codedeploy/latest/userguide/auth-and-access-control.html\n  - type: Pricing\n    url: https://aws.amazon.com/codedeploy/pricing/\n  - type: Console\n    url: https://console.aws.amazon.com/codedeploy/\n  - type: Portal\n    url: https://aws.amazon.com/codedeploy/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/codedeploy/latest/userguide/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Blog\n    url: https://aws.amazon.com/blogs/devops/\n  - type: FAQ\n    url: https://aws.amazon.com/codedeploy/faqs/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: SpectralRules\n    url: rules/amazon-codedeploy-spectral-rules.yml\n\
  \  - type: Vocabulary\n    url: vocabulary/amazon-codedeploy-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/amazon-codedeploy-deployment-automation.yaml\n  - type: JSONLD\n    url: json-ld/amazon-codedeploy-context.jsonld\n  - type: Features\n    data:\n      - name: Multiple Deployment Strategies\n        description: >-\n          Support for in-place, blue/green, and canary deployment strategies across EC2, Lambda, ECS, and\n          on-premises targets to minimize downtime and risk.\n      - name: Automated Rollbacks\n        description: >-\n          Automatically roll back deployments if a specified number of instances fail health checks or if\n          CloudWatch alarms are triggered during deployment.\n      - name: Deployment Lifecycle Hooks\n        description: >-\n          Define custom lifecycle event hooks (BeforeInstall, AfterInstall, ApplicationStart, etc.) using scripts\n          or Lambda functions for fine-grained deployment control.\n     \
  \ - name: Traffic Shifting for Lambda and ECS\n        description: >-\n          Implement canary and linear traffic shifting for Lambda function updates and ECS service deployments\n          with configurable traffic weights and bake times.\n      - name: Deployment Groups\n        description: >-\n          Organize deployment targets using deployment groups with EC2 instance tags, Auto Scaling groups, ECS\n          clusters, or on-premises instance tags.\n      - name: CodeDeploy Agent\n        description: >-\n          Install the CodeDeploy agent on EC2 or on-premises instances to enable deployment target registration\n          and lifecycle hook execution.\n      - name: Integration with AWS Load Balancers\n        description: >-\n          Integrate with Application Load Balancers and Network Load Balancers for blue/green deployments that\n          shift traffic between original and replacement instances.\n  - type: UseCases\n    data:\n      - name: Zero-Downtime Application\
  \ Updates\n        description: >-\n          Use blue/green deployments to update applications without downtime by routing traffic to a new\n          environment while keeping the original environment available for rollback.\n      - name: Lambda Function Updates\n        description: >-\n          Deploy new Lambda function versions with canary or linear traffic shifting to gradually migrate\n          traffic from the current version to the updated function version.\n      - name: ECS Service Deployment\n        description: >-\n          Deploy updated container tasks to ECS services with blue/green deployments and configurable traffic\n          shifting through an Application Load Balancer.\n      - name: On-Premises Application Deployment\n        description: >-\n          Extend cloud-based deployment automation to on-premises servers using the CodeDeploy agent and\n          on-premises instance registration.\n      - name: Multi-Stage CD Pipeline\n        description: >-\n\
  \          Use CodeDeploy as the deployment stage in an AWS CodePipeline for fully automated continuous delivery\n          from source code to production.\n  - type: Integrations\n    data:\n      - name: AWS CodePipeline\n        description: Use CodeDeploy as the deployment stage in CodePipeline CD pipelines.\n      - name: AWS CodeBuild\n        description: Trigger CodeDeploy deployments from build artifacts produced by CodeBuild.\n      - name: AWS Lambda\n        description: Deploy Lambda function updates with traffic shifting strategies.\n      - name: Amazon ECS\n        description: Deploy ECS service updates with blue/green deployments.\n      - name: AWS CloudWatch\n        description: Trigger automatic rollbacks based on CloudWatch alarm states.\n      - name: Elastic Load Balancing\n        description: Integrate with ALB and NLB for blue/green traffic shifting.\n      - name: Amazon EC2 Auto Scaling\n        description: Deploy to Auto Scaling groups with automatic instance\
  \ health checking.\n      - name: AWS Systems Manager\n        description: Use SSM Run Command and State Manager for deployment automation.\n      - name: GitHub\n        description: Deploy application revisions stored in GitHub repositories.\n      - name: Amazon S3\n        description: Store and retrieve application deployment bundles from S3.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-codedeploy/refs/heads/main/apis.yml
tags:
- Amazon
- AWS
- Deployment
- DevOps
- CI/CD
- Release Management
- Blue/Green Deployment
url: https://raw.githubusercontent.com/api-evangelist/amazon-codedeploy/refs/heads/main/apis.yml
use_cases:
- description: Use blue/green deployments to update applications without downtime by routing traffic to a new environment while keeping the original environment available for rollback.
  name: Zero-Downtime Application Updates
- description: Deploy new Lambda function versions with canary or linear traffic shifting to gradually migrate traffic from the current version to the updated function version.
  name: Lambda Function Updates
- description: Deploy updated container tasks to ECS services with blue/green deployments and configurable traffic shifting through an Application Load Balancer.
  name: ECS Service Deployment
- description: Extend cloud-based deployment automation to on-premises servers using the CodeDeploy agent and on-premises instance registration.
  name: On-Premises Application Deployment
- description: Use CodeDeploy as the deployment stage in an AWS CodePipeline for fully automated continuous delivery from source code to production.
  name: Multi-Stage CD Pipeline
---
