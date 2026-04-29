---
api_count: 1
api_specs:
- filename: conductor-conductor-openapi.yml
  format: yaml
  label: Conductor
  slug: conductor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/conductor/refs/heads/main/openapi/conductor-conductor-openapi.yml
apis:
- description: Conductor allows you to build a complex application using simple and granular tasks that do not need to be aware of or keep track of the state of your application's execution flow. Conductor keeps tra
  name: Conductor
  slug: conductor
asyncapis:
- description: 'Asynchronous event API for Conductor workflow orchestration platform. Conductor emits events when workflows and tasks change state, enabling reactive event-driven architectures. Event handlers can be '
  name: Conductor Events API
  slug: conductor-conductor-asyncapi
capabilities:
- description: Unified workflow for managing workflow definitions, task definitions, workflow executions, and event handlers. Used by backend developers and DevOps engineers.
  name: Conductor Workflow Orchestration
  slug: workflow-orchestration
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/conductor-oss/conductor
- title: ''
  type: SpectralRules
  url: rules/conductor-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/conductor-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/workflow-orchestration.yaml
created: '2025-01-08'
description: Conductor allows you to build a complex application using simple and granular tasks that do not need to be aware of or keep track of the state of your application's execution flow. Conductor keeps track of the state, calls tasks in the right order (sequentially or in parallel, as defined by you), retry calls if needed, handle failure scenarios gracefully, and outputs the final result.
features:
- description: Define and execute complex workflows with sequential and parallel task execution.
  name: Workflow Orchestration
- description: Register, poll, and update granular task definitions with timeout and retry policies.
  name: Task Management
- description: Create event handlers to trigger workflows or tasks based on external events.
  name: Event Handling
- description: Search and filter workflow executions by status, type, and custom parameters.
  name: Workflow Search
- description: Automatic retries, pause/resume, and graceful failure handling for long-running workflows.
  name: Fault Tolerance
- description: Pause, resume, restart, retry, and terminate workflows programmatically.
  name: Workflow Lifecycle Control
image: /assets/icons/conductor.png
integrations:
- description: Trigger workflows and tasks from Kafka events using event handler subscriptions.
  name: Apache Kafka
- description: Integrate with SQS for message-driven workflow initiation and task completion.
  name: Amazon SQS
- description: Run Conductor server and workers in containerized environments for scalable deployment.
  name: Docker
- description: Use managed Conductor service from Orkes for enterprise-grade orchestration without infrastructure management.
  name: Orkes Cloud
jsonld:
- class_count: 0
  name: Conductor Conductor Context
  property_count: 0
  slug: conductor-conductor-context
- class_count: 7
  name: Conductor Context
  property_count: 40
  slug: conductor-context
layout: provider
modified: '2026-04-18'
name: Conductor
rules:
- name: Conductor API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: conductor-spectral-rules
skills: []
slug: conductor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: conductor\nname: Conductor\ndescription: >-\n  Conductor allows you to build a complex application using simple and granular\n  tasks that do not need to be aware of or keep track of the state of your\n  application's execution flow. Conductor keeps track of the state, calls tasks\n  in the right order (sequentially or in parallel, as defined by you), retry\n  calls if needed, handle failure scenarios gracefully, and outputs the final\n  result.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/conductor/refs/heads/main/apis.yml\ntags:\n  - Automation\n  - Orchestration\n  - State\n  - Tasks\n  - Workflows\ntype: Contract\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\nposition: Consuming\napis:\n  - aid: conductor:conductor\n    name: Conductor\n    description: >-\n      Conductor allows you to build a complex application using\
  \ simple and\n      granular tasks that do not need to be aware of or keep track of the state\n      of your application's execution flow. Conductor keeps track of the state,\n      calls tasks in the right order (sequentially or in parallel, as defined by\n      you), retry calls if needed, handle failure scenarios gracefully, and\n      outputs the final result.\n    humanURL: https://conductor-oss.github.io/conductor/documentation/api/workflow.html\n    tags:\n      - Automation\n      - Orchestration\n      - State\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://conductor-oss.github.io/conductor/documentation/api/workflow.html\n      - type: OpenAPI\n        url: openapi/conductor-conductor-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/conductor-conductor-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/workflow-def.json\n      - type: JSONSchema\n        url: json-schema/task-def.json\n      - type: JSONSchema\n     \
  \   url: json-schema/workflow-execution.json\n      - type: JSONSchema\n        url: json-schema/event-handler.json\n      - type: JSONLD\n        url: json-ld/conductor-context.jsonld\n      - type: JSONLD\n        url: json-ld/conductor-conductor-context.jsonld\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/conductor-oss/conductor\n  - type: SpectralRules\n    url: rules/conductor-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/conductor-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/workflow-orchestration.yaml\n  - type: Features\n    data:\n      - name: Workflow Orchestration\n        description: Define and execute complex workflows with sequential and parallel task execution.\n      - name: Task Management\n        description: Register, poll, and update granular task definitions with timeout and retry policies.\n      - name: Event Handling\n        description: Create event handlers to trigger workflows or tasks based on external\
  \ events.\n      - name: Workflow Search\n        description: Search and filter workflow executions by status, type, and custom parameters.\n      - name: Fault Tolerance\n        description: Automatic retries, pause/resume, and graceful failure handling for long-running workflows.\n      - name: Workflow Lifecycle Control\n        description: Pause, resume, restart, retry, and terminate workflows programmatically.\n  - type: UseCases\n    data:\n      - name: Microservices Orchestration\n        description: Coordinate complex business processes across distributed microservices without tight coupling.\n      - name: Data Pipeline Automation\n        description: Build and manage ETL and data processing pipelines with dependency tracking and error recovery.\n      - name: Order Processing\n        description: Manage multi-step order fulfillment workflows including payment, inventory, and shipping.\n      - name: CI/CD Pipelines\n        description: Orchestrate build, test, and deployment\
  \ workflows with conditional logic and parallel execution.\n  - type: Integrations\n    data:\n      - name: Apache Kafka\n        description: Trigger workflows and tasks from Kafka events using event handler subscriptions.\n      - name: Amazon SQS\n        description: Integrate with SQS for message-driven workflow initiation and task completion.\n      - name: Docker\n        description: Run Conductor server and workers in containerized environments for scalable deployment.\n      - name: Orkes Cloud\n        description: Use managed Conductor service from Orkes for enterprise-grade orchestration without infrastructure management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/conductor/refs/heads/main/apis.yml
tags:
- Automation
- Orchestration
- State
- Tasks
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/conductor/refs/heads/main/apis.yml
use_cases:
- description: Coordinate complex business processes across distributed microservices without tight coupling.
  name: Microservices Orchestration
- description: Build and manage ETL and data processing pipelines with dependency tracking and error recovery.
  name: Data Pipeline Automation
- description: Manage multi-step order fulfillment workflows including payment, inventory, and shipping.
  name: Order Processing
- description: Orchestrate build, test, and deployment workflows with conditional logic and parallel execution.
  name: CI/CD Pipelines
---
