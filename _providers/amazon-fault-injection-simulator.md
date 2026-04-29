---
api_count: 1
api_specs:
- filename: amazon-fis-openapi.yml
  format: yaml
  label: AWS Fault Injection Simulator API
  slug: aws-fis-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-fault-injection-simulator/refs/heads/main/openapi/amazon-fis-openapi.yml
apis:
- description: The AWS Fault Injection Simulator API provides programmatic access to create and manage experiment templates, experiments, and actions for conducting chaos engineering experiments on AWS workloads.
  name: AWS Fault Injection Simulator API
  slug: aws-fis-api
capabilities:
- description: Workflow capability for executing chaos engineering experiments using AWS FIS. Enables resilience engineers and SREs to design, execute, and monitor fault injection experiments across AWS infrastructu
  name: AWS FIS Chaos Engineering
  slug: amazon-fis-chaos-engineering
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/fis/
- title: ''
  type: Website
  url: https://aws.amazon.com/fis/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/fis/
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
  url: https://aws.amazon.com/blogs/devops/tag/aws-fault-injection-simulator/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/fis/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-fis
- title: ''
  type: SpectralRules
  url: rules/amazon-fis-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/fis.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-fis-chaos-engineering.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-fis-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-fis-context.jsonld
created: '2026-03-16'
description: AWS Fault Injection Simulator (FIS) is a fully managed service for running fault injection experiments on AWS. It allows you to improve an application's performance, observability, and resiliency by identifying and fixing weaknesses through controlled chaos engineering experiments.
features:
- description: Fully managed service requiring no agent installation with pre-built fault injection actions for EC2, RDS, ECS, EKS, and more.
  name: Managed Fault Injection
- description: Ready-to-use resilience scenarios for AZ failures, power interruptions, network disruptions, and cross-region connectivity issues.
  name: Pre-built Scenarios
- description: CloudWatch alarm-based stop conditions and safety levers prevent unintended impact during live testing.
  name: Safety Controls
- description: Tag-based resource targeting scopes experiments to specific environments, applications, or resource subsets.
  name: Fine-grained Targeting
- description: Run experiments across multiple AWS accounts using target account configurations.
  name: Multi-account Support
- description: API and CLI access enables automated resilience testing in deployment pipelines.
  name: CI/CD Integration
- description: Console and API provide real-time status of executing actions, affected resources, and triggered stop conditions.
  name: Real-time Visibility
- description: Fine-grained IAM controls restrict which users can create, run, or view experiments and affected resources.
  name: IAM Security
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Stop conditions use CloudWatch alarms to automatically halt experiments.
  name: Amazon CloudWatch
- description: Task execution roles define which AWS resources experiments can affect.
  name: AWS IAM
- description: Stop instances, terminate instances, and inject CPU/memory stress on EC2.
  name: Amazon EC2
- description: Stop ECS tasks and inject faults into containerized workloads.
  name: Amazon ECS
- description: Terminate Kubernetes nodes and pods running on EKS.
  name: Amazon EKS
- description: Trigger RDS failovers, reboot instances, and pause cluster I/O.
  name: Amazon RDS
- description: Inject latency and errors into Lambda function invocations.
  name: AWS Lambda
- description: Pause DynamoDB replication between replicas.
  name: Amazon DynamoDB
jsonld:
- class_count: 13
  name: Amazon Fis Context
  property_count: 23
  slug: amazon-fis-context
layout: provider
modified: '2026-04-19'
name: Amazon Fault Injection Simulator
rules:
- name: Amazon Fault Injection Simulator API Rules
  rule_count: 28
  severity_counts:
    error: 10
    hint: 0
    info: 2
    warn: 16
  slug: amazon-fis-spectral-rules
skills: []
slug: amazon-fault-injection-simulator
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-fault-injection-simulator\nname: Amazon Fault Injection Simulator\ndescription: >-\n  AWS Fault Injection Simulator (FIS) is a fully managed service for running\n  fault injection experiments on AWS. It allows you to improve an application's\n  performance, observability, and resiliency by identifying and fixing weaknesses\n  through controlled chaos engineering experiments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Chaos Engineering\n- DevOps\n- Fault Injection\n- Resilience Testing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-fault-injection-simulator/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-fault-injection-simulator:aws-fis-api\n  name: AWS Fault Injection Simulator API\n  description: >-\n    The AWS Fault Injection Simulator API provides programmatic access to\n    create and manage experiment\
  \ templates, experiments, and actions for\n    conducting chaos engineering experiments on AWS workloads.\n  humanURL: https://aws.amazon.com/fis/\n  baseURL: https://fis.amazonaws.com\n  tags:\n  - Chaos Engineering\n  - Fault Injection\n  - Resilience Testing\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/fis/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-fis-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-fis-experiment-template-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fis-experiment-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fis-action-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fis-safety-lever-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-fis-experiment-template-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fis-experiment-structure.json\n  - type: Example\n    url: examples/amazon-fis-experiment-template-example.json\n\
  \  - type: Example\n    url: examples/amazon-fis-experiment-example.json\n  - type: GettingStarted\n    url: https://aws.amazon.com/fis/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/fis/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/fis/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/fis/latest/APIReference/Welcome.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/fis/\n- type: Website\n  url: https://aws.amazon.com/fis/\n- type: Documentation\n  url: https://docs.aws.amazon.com/fis/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/devops/tag/aws-fault-injection-simulator/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/fis/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n\
  - type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-fis\n- type: SpectralRules\n  url: rules/amazon-fis-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/fis.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-fis-chaos-engineering.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-fis-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/amazon-fis-context.jsonld\n- type: Features\n  data:\n  - name: Managed Fault Injection\n    description: Fully managed service requiring no agent installation with pre-built fault injection actions for EC2, RDS, ECS, EKS, and more.\n  - name: Pre-built Scenarios\n    description: Ready-to-use resilience scenarios for AZ failures, power interruptions, network disruptions, and cross-region connectivity issues.\n  - name: Safety Controls\n    description: CloudWatch\
  \ alarm-based stop conditions and safety levers prevent unintended impact during live testing.\n  - name: Fine-grained Targeting\n    description: Tag-based resource targeting scopes experiments to specific environments, applications, or resource subsets.\n  - name: Multi-account Support\n    description: Run experiments across multiple AWS accounts using target account configurations.\n  - name: CI/CD Integration\n    description: API and CLI access enables automated resilience testing in deployment pipelines.\n  - name: Real-time Visibility\n    description: Console and API provide real-time status of executing actions, affected resources, and triggered stop conditions.\n  - name: IAM Security\n    description: Fine-grained IAM controls restrict which users can create, run, or view experiments and affected resources.\n- type: UseCases\n  data:\n  - name: Application Resilience Testing\n    description: Validate application behavior under resource failures before they occur in production.\n\
  \  - name: Chaos Engineering\n    description: Run structured fault injection experiments following chaos engineering principles.\n  - name: Observability Validation\n    description: Verify that monitoring and alerting systems detect and respond to failures correctly.\n  - name: Game Days\n    description: Conduct planned game day exercises simulating failure scenarios for team readiness.\n  - name: Automated Pipeline Testing\n    description: Integrate resilience testing into CI/CD pipelines for continuous validation.\n  - name: Multi-region Failover Testing\n    description: Test cross-region failover mechanisms and recovery time objectives.\n- type: Integrations\n  data:\n  - name: Amazon CloudWatch\n    description: Stop conditions use CloudWatch alarms to automatically halt experiments.\n  - name: AWS IAM\n    description: Task execution roles define which AWS resources experiments can affect.\n  - name: Amazon EC2\n    description: Stop instances, terminate instances, and inject\
  \ CPU/memory stress on EC2.\n  - name: Amazon ECS\n    description: Stop ECS tasks and inject faults into containerized workloads.\n  - name: Amazon EKS\n    description: Terminate Kubernetes nodes and pods running on EKS.\n  - name: Amazon RDS\n    description: Trigger RDS failovers, reboot instances, and pause cluster I/O.\n  - name: AWS Lambda\n    description: Inject latency and errors into Lambda function invocations.\n  - name: Amazon DynamoDB\n    description: Pause DynamoDB replication between replicas.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-fault-injection-simulator/refs/heads/main/apis.yml
tags:
- AWS
- Chaos Engineering
- DevOps
- Fault Injection
- Resilience Testing
url: https://raw.githubusercontent.com/api-evangelist/amazon-fault-injection-simulator/refs/heads/main/apis.yml
use_cases:
- description: Validate application behavior under resource failures before they occur in production.
  name: Application Resilience Testing
- description: Run structured fault injection experiments following chaos engineering principles.
  name: Chaos Engineering
- description: Verify that monitoring and alerting systems detect and respond to failures correctly.
  name: Observability Validation
- description: Conduct planned game day exercises simulating failure scenarios for team readiness.
  name: Game Days
- description: Integrate resilience testing into CI/CD pipelines for continuous validation.
  name: Automated Pipeline Testing
- description: Test cross-region failover mechanisms and recovery time objectives.
  name: Multi-region Failover Testing
---
