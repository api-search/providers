---
api_count: 2
apis:
- description: The Flowable Process Engine API is the primary programmatic interface for interacting with Flowable. From a configured ProcessEngine, applications obtain a set of services that cover the full BPM life
  name: Flowable Process Engine API
  slug: process-engine-api
- description: 'Flowable also ships a packaged REST API webapp that exposes the Process Engine services over HTTP. The REST API covers process definitions and deployments, process instances and variables, user tasks '
  name: Flowable REST API
  slug: rest-api
common:
- title: ''
  type: Website
  url: https://www.flowable.com/
- title: ''
  type: Documentation
  url: https://www.flowable.com/open-source/docs/
- title: ''
  type: GitHubRepository
  url: https://github.com/flowable/flowable-engine
- title: ''
  type: GitHubOrganization
  url: https://github.com/flowable
- title: ''
  type: Blog
  url: https://blog.flowable.org/
created: '2024-11-07'
description: Flowable connects systems, data, and people for faster and smarter process automation, drawing on a long heritage of open source BPM. Flowable provides a model-driven, low-code platform for end-to-end automation of BPMN, CMMN, and DMN processes, delivered through a programmatic Java Process Engine API and a packaged REST API. The Process Engine exposes RepositoryService, RuntimeService, TaskService, IdentityService, HistoryService, ManagementService, FormService, and DynamicBpmnService for managing process definitions, instances, tasks, history, and runtime behavior.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Flowable
skills: []
slug: flowable-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flowable-api\nname: Flowable\ndescription: >-\n  Flowable connects systems, data, and people for faster and smarter process\n  automation, drawing on a long heritage of open source BPM. Flowable\n  provides a model-driven, low-code platform for end-to-end automation of\n  BPMN, CMMN, and DMN processes, delivered through a programmatic Java\n  Process Engine API and a packaged REST API. The Process Engine exposes\n  RepositoryService, RuntimeService, TaskService, IdentityService,\n  HistoryService, ManagementService, FormService, and DynamicBpmnService for\n  managing process definitions, instances, tasks, history, and runtime\n  behavior.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-07'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - Automation\n  - BPM\n  - BPMN\n  - Business Process\n  - CMMN\n  - DMN\n  - Workflows\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/flowable-api/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: flowable-api:process-engine-api\n    name: Flowable Process Engine API\n    description: >-\n      The Flowable Process Engine API is the primary programmatic interface\n      for interacting with Flowable. From a configured ProcessEngine,\n      applications obtain a set of services that cover the full BPM\n      lifecycle: RepositoryService for deploying and managing process\n      definitions, RuntimeService for starting and signaling process\n      instances, TaskService for human task assignment and completion,\n      IdentityService for users and groups, HistoryService for audit and\n      reporting queries, ManagementService for jobs and engine metadata,\n      FormService for start and task forms, and DynamicBpmnService for\n      runtime modifications. The API supports both fluent typesafe queries\n      and native SQL queries.\n    humanURL: https://www.flowable.com/open-source/docs/bpmn/ch04-API\n    baseURL: https://www.flowable.com/open-source/docs/bpmn/\n\
  \    tags:\n      - BPM\n      - BPMN\n      - Process Engine\n      - Workflows\n    properties:\n      - url: https://www.flowable.com/open-source/docs/bpmn/ch04-API\n        type: Documentation\n      - url: https://www.flowable.com/open-source/docs/\n        type: DocumentationPortal\n  - aid: flowable-api:rest-api\n    name: Flowable REST API\n    description: >-\n      Flowable also ships a packaged REST API webapp that exposes the\n      Process Engine services over HTTP. The REST API covers process\n      definitions and deployments, process instances and variables, user\n      tasks and forms, history, identity, and engine management, allowing\n      non-Java clients to drive BPMN, CMMN, and DMN processes from any\n      platform.\n    humanURL: https://www.flowable.com/open-source/docs/bpmn/\n    baseURL: https://www.flowable.com/open-source/docs/bpmn/\n    tags:\n      - BPM\n      - REST\n      - Workflows\n    properties:\n      - url: https://www.flowable.com/open-source/docs/\n\
  \        type: Documentation\n      - url: https://github.com/flowable/flowable-engine\n        type: GitHubRepository\ncommon:\n  - type: Website\n    url: https://www.flowable.com/\n  - type: Documentation\n    url: https://www.flowable.com/open-source/docs/\n  - type: GitHubRepository\n    url: https://github.com/flowable/flowable-engine\n  - type: GitHubOrganization\n    url: https://github.com/flowable\n  - type: Blog\n    url: https://blog.flowable.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flowable-api/refs/heads/main/apis.yml
tags:
- Automation
- BPM
- BPMN
- Business Process
- CMMN
- DMN
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/flowable-api/refs/heads/main/apis.yml
use_cases: []
---
