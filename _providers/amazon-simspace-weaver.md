---
api_count: 1
api_specs:
- filename: amazon-simspace-weaver.yaml
  format: yaml
  label: AWS SimSpace Weaver API
  slug: aws-simspace-weaver-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-simspace-weaver/refs/heads/main/openapi/amazon-simspace-weaver.yaml
apis:
- description: The AWS SimSpace Weaver API provides programmatic access to create and manage simulations, simulation apps, snapshots, and clocks for running large-scale spatial simulations in the cloud.
  name: AWS SimSpace Weaver API
  slug: aws-simspace-weaver-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/simspaceweaver/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/simspaceweaver/latest/userguide/what-is.html
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
  url: https://aws.amazon.com/blogs/hpc/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/simspaceweaver/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-simspace-weaver-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-simspace-weaver-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-simspace-weaver.yaml
created: '2026-03-16'
description: AWS SimSpace Weaver is a managed service that helps you build and run large-scale spatial simulations in the AWS Cloud. It provides tools to run custom spatial simulation logic at scale and use simulation workloads for defense, urban planning, and other real-world system simulations.
features:
- description: Run spatial simulations at city or country scale with millions of agents.
  name: Large-scale Simulations
- description: Fully managed compute infrastructure for simulation workloads.
  name: Managed Infrastructure
- description: Deploy custom simulation apps that interact with the simulation world.
  name: App Framework
- description: Start, pause, stop, and control simulation time.
  name: Clock Control
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy SimSpace Weaver simulations using CloudFormation.
  name: AWS CloudFormation
- description: Store simulation schemas and output data in S3.
  name: Amazon S3
- description: Monitor simulation metrics and logs via CloudWatch.
  name: Amazon CloudWatch
jsonld:
- class_count: 43
  name: Amazon Simspace Weaver Context
  property_count: 38
  slug: amazon-simspace-weaver-context
layout: provider
modified: '2026-04-19'
name: Amazon SimSpace Weaver
rules:
- name: Amazon SimSpace Weaver API Rules
  rule_count: 19
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 7
  slug: amazon-simspace-weaver-spectral-rules
skills: []
slug: amazon-simspace-weaver
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-simspace-weaver\nname: Amazon SimSpace Weaver\ndescription: >-\n  AWS SimSpace Weaver is a managed service that helps you build and run\n  large-scale spatial simulations in the AWS Cloud. It provides tools to\n  run custom spatial simulation logic at scale and use simulation workloads\n  for defense, urban planning, and other real-world system simulations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Defense\n- Digital Twin\n- Simulation\n- Spatial Simulation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-simspace-weaver/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-simspace-weaver:aws-simspace-weaver-api\n  name: AWS SimSpace Weaver API\n  description: >-\n    The AWS SimSpace Weaver API provides programmatic access to create and\n    manage simulations, simulation apps, snapshots, and clocks for\
  \ running\n    large-scale spatial simulations in the cloud.\n  humanURL: https://aws.amazon.com/simspace-weaver/\n  baseURL: https://simspaceweaver.amazonaws.com\n  tags:\n  - Digital Twin\n  - Simulation\n  - Spatial Simulation\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/simspaceweaver/latest/userguide/what-is.html\n  - type: OpenAPI\n    url: openapi/amazon-simspace-weaver.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/simspaceweaver/\n  - type: Pricing\n    url: https://aws.amazon.com/simspaceweaver/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/simspaceweaver/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/simspaceweaver/\n- type: Documentation\n  url: https://docs.aws.amazon.com/simspaceweaver/latest/userguide/what-is.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n\
  - type: Blog\n  url: https://aws.amazon.com/blogs/hpc/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/simspaceweaver/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-simspace-weaver-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-simspace-weaver-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-simspace-weaver.yaml\n- type: Features\n  data:\n  - name: Large-scale Simulations\n    description: Run spatial simulations at city or country scale with millions of agents.\n  - name: Managed Infrastructure\n    description: Fully managed compute infrastructure for simulation workloads.\n  - name: App Framework\n    description: Deploy\
  \ custom simulation apps that interact with the simulation world.\n  - name: Clock Control\n    description: Start, pause, stop, and control simulation time.\n- type: UseCases\n  data:\n  - name: Urban Planning\n    description: Simulate traffic, pedestrian movement, and city infrastructure at scale.\n  - name: Emergency Response\n    description: Model disaster scenarios and evacuation plans.\n  - name: Defense Simulations\n    description: Run large-scale defense and logistics simulations.\n- type: Integrations\n  data:\n  - name: AWS CloudFormation\n    description: Deploy SimSpace Weaver simulations using CloudFormation.\n  - name: Amazon S3\n    description: Store simulation schemas and output data in S3.\n  - name: Amazon CloudWatch\n    description: Monitor simulation metrics and logs via CloudWatch.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nx-type: company\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-simspace-weaver/refs/heads/main/apis.yml
tags:
- Defense
- Digital Twin
- Simulation
- Spatial Simulation
url: https://raw.githubusercontent.com/api-evangelist/amazon-simspace-weaver/refs/heads/main/apis.yml
use_cases:
- description: Simulate traffic, pedestrian movement, and city infrastructure at scale.
  name: Urban Planning
- description: Model disaster scenarios and evacuation plans.
  name: Emergency Response
- description: Run large-scale defense and logistics simulations.
  name: Defense Simulations
---
