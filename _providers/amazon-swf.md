---
api_count: 1
apis:
- description: The Amazon SWF API provides programmatic access to manage workflows, activity tasks, decision tasks, and workflow execution history. It enables developers to coordinate distributed application compone
  name: Amazon Simple Workflow Service API
  slug: amazon-swf-api
capabilities:
- description: ''
  name: Amazon Swf Workflow Management
  slug: amazon-swf-workflow-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/swf/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/amazonswf/latest/developerguide/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/swf/
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/rules/amazon-swf-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/vocabulary/amazon-swf-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/capabilities/amazon-swf-workflow-management.yaml
created: '2026-03-16'
description: Amazon Simple Workflow Service (Amazon SWF) helps developers build, run, and scale background jobs that have parallel or sequential steps. It is a fully managed state tracker and task coordinator in the cloud that manages intertask dependencies, scheduling, and concurrency for application workflows.
features:
- description: Manages inter-task dependencies, scheduling, and concurrency for distributed workflows.
  name: Task Coordination
- description: Durably maintains application execution state throughout workflow lifecycle.
  name: State Tracking
- description: Supports workflows that run for up to 1 year with activity timeouts and retries.
  name: Long-Running Workflows
- description: Separates orchestration logic (deciders) from execution logic (activity workers).
  name: Decider and Activity Workers
- description: Supports multiple versions of workflow and activity types for safe deployments.
  name: Workflow Versioning
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Amazon Swf Context
  property_count: 0
  slug: amazon-swf-context
layout: provider
modified: '2026-04-19'
name: Amazon Simple Workflow Service
rules:
- name: Amazon Simple Workflow Service API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: amazon-swf-spectral-rules
skills: []
slug: amazon-swf
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-swf\nname: Amazon Simple Workflow Service\ndescription: >-\n  Amazon Simple Workflow Service (Amazon SWF) helps developers build, run, and\n  scale background jobs that have parallel or sequential steps. It is a fully\n  managed state tracker and task coordinator in the cloud that manages intertask\n  dependencies, scheduling, and concurrency for application workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Automation\n- AWS\n- Task Coordination\n- Workflow\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-swf:amazon-swf-api\n  name: Amazon Simple Workflow Service API\n  description: >-\n    The Amazon SWF API provides programmatic access to manage workflows,\n    activity tasks, decision tasks, and workflow execution history. It enables\n    developers\
  \ to coordinate distributed application components using\n    asynchronous task processing and state tracking.\n  humanURL: https://aws.amazon.com/swf/\n  baseURL: https://swf.amazonaws.com\n  tags:\n  - AWS\n  - Task Coordination\n  - Workflow\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazonswf/latest/developerguide/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/amazonswf/latest/apireference/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/amazonswf/latest/developerguide/swf-dg-intro-to-swf.html\n  - type: Pricing\n    url: https://aws.amazon.com/swf/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/swf/faqs/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/openapi/amazon-swf-openapi-original.yml\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/swf/\n- type: Documentation\n  url: https://docs.aws.amazon.com/amazonswf/latest/developerguide/\n\
  - type: Console\n  url: https://console.aws.amazon.com/swf/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Features\n  data:\n  - name: Task Coordination\n    description: Manages inter-task dependencies, scheduling, and concurrency for distributed workflows.\n  - name: State Tracking\n    description: Durably maintains application execution state throughout workflow lifecycle.\n  - name: Long-Running Workflows\n    description: Supports workflows that run for up to 1 year with activity timeouts and retries.\n  - name: Decider and Activity Workers\n    description:\
  \ Separates orchestration logic (deciders) from execution logic (activity workers).\n  - name: Workflow Versioning\n    description: Supports multiple versions of workflow and activity types for safe deployments.\n- type: UseCases\n  data:\n  - name: Media Processing Pipelines\n    description: Coordinate multi-step media encoding, transcoding, and publishing workflows.\n  - name: Order Processing\n    description: Orchestrate e-commerce order fulfillment with parallel and sequential steps.\n  - name: Data Analytics Workflows\n    description: Manage ETL pipelines and data processing jobs across distributed systems.\n  - name: Human Task Orchestration\n    description: Coordinate workflows that require human review or approval steps.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/rules/amazon-swf-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/vocabulary/amazon-swf-vocabulary.yaml\n\
  - type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/capabilities/amazon-swf-workflow-management.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/apis.yml
tags:
- Automation
- AWS
- Task Coordination
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/amazon-swf/refs/heads/main/apis.yml
use_cases:
- description: Coordinate multi-step media encoding, transcoding, and publishing workflows.
  name: Media Processing Pipelines
- description: Orchestrate e-commerce order fulfillment with parallel and sequential steps.
  name: Order Processing
- description: Manage ETL pipelines and data processing jobs across distributed systems.
  name: Data Analytics Workflows
- description: Coordinate workflows that require human review or approval steps.
  name: Human Task Orchestration
---
