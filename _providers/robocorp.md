---
api_count: 2
api_specs:
- filename: openapi.json
  format: json
  label: Robocorp Control Room API
  slug: control-room-api
  spec_type: OpenAPI
  url: https://robocorp.com/api/openapi.json
apis:
- description: The Robocorp Control Room API provides programmatic access to the orchestration platform for RPA automations. It supports workspace management, worker lifecycle, worker group organization, process def
  name: Robocorp Control Room API
  slug: control-room-api
- description: The RPA Framework is an open-source collection of Python libraries for robotic process automation designed for use with Robot Framework and Python. It includes libraries for browser automation, deskto
  name: RPA Framework
  slug: rpa-framework
capabilities:
- description: Unified workflow capability for RPA automation orchestration using the Robocorp Control Room API. Combines worker management, process execution, work item queuing, secret management, asset storage, we
  name: Robocorp Automation Orchestration
  slug: automation-orchestration
common:
- title: ''
  type: Website
  url: https://robocorp.com
- title: ''
  type: Documentation
  url: https://robocorp.com/docs
- title: ''
  type: GitHub
  url: https://github.com/robocorp
- title: ''
  type: PyPI
  url: https://pypi.org/project/robocorp/
- title: ''
  type: Blog
  url: https://robocorp.com/blog
- title: ''
  type: PrivacyPolicy
  url: https://robocorp.com/privacy-policy
- title: ''
  type: TermsOfService
  url: https://robocorp.com/terms-of-service
- title: ''
  type: Status
  url: https://status.robocorp.com
- title: ''
  type: Changelog
  url: https://robocorp.com/docs/changelog
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-ld/robocorp-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/vocabulary/robocorp-vocabulary.yml
created: '2026-03-27'
description: Robocorp is an open source RPA and workflow automation platform for building Python-based automation bots. The platform provides the Control Room API for managing workspaces, workers, processes, work items, assets, vaults, webhooks, and task packages. Robocorp also provides the RPA Framework, an open-source collection of Python libraries for robotic process automation including browser, desktop, email, Excel, PDF, and cloud service automation. The platform has evolved toward Sema4 AI for AI-powered automation actions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 34
  name: Robocorp Context
  property_count: 0
  slug: robocorp-context
layout: provider
modified: '2026-05-02'
name: Robocorp
rules:
- name: Robocorp API Rules
  rule_count: 13
  severity_counts:
    error: 2
    hint: 0
    info: 4
    warn: 7
  slug: robocorp-control-room-rules
skills: []
slug: robocorp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: robocorp\nname: Robocorp\ndescription: >-\n  Robocorp is an open source RPA and workflow automation platform for building\n  Python-based automation bots. The platform provides the Control Room API for\n  managing workspaces, workers, processes, work items, assets, vaults,\n  webhooks, and task packages. Robocorp also provides the RPA Framework, an\n  open-source collection of Python libraries for robotic process automation\n  including browser, desktop, email, Excel, PDF, and cloud service automation.\n  The platform has evolved toward Sema4 AI for AI-powered automation actions.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - RPA\n  - Workflow Automation\n  - Python\n  - Open Source\n  - Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: robocorp:control-room-api\n\
  \    name: Robocorp Control Room API\n    description: >-\n      The Robocorp Control Room API provides programmatic access to the\n      orchestration platform for RPA automations. It supports workspace\n      management, worker lifecycle, worker group organization, process\n      definition and execution, process run monitoring, step run outputs,\n      work item management, asset storage, vault secrets, webhook\n      configuration, and task package deployment. Authentication uses\n      API keys with the RC-WSKEY prefix.\n    humanURL: https://robocorp.com/api\n    baseURL: https://cloud.robocorp.com/api/v1\n    tags:\n      - RPA\n      - Automation\n      - Orchestration\n      - Workflow\n      - Workers\n    properties:\n      - url: https://robocorp.com/api\n        type: Documentation\n      - url: https://robocorp.com/docs/control-room/apis-and-webhooks\n        type: Guide\n      - url: https://robocorp.com/api/openapi.json\n        type: OpenAPI\n      - url: >-\n        \
  \  https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/openapi/robocorp-control-room-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/rules/robocorp-control-room-rules.yml\n        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/capabilities/automation-orchestration.yaml\n        type: NaftikoCapabilities\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-schema/robocorp-process-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-schema/robocorp-work-item-schema.json\n        type: JSONSchema\n    contact:\n      - FN: Robocorp Support\n        url: https://robocorp.com/docs\n    features:\n      - Workspace Management\n      - Worker Management\n      - Worker\
  \ Group Management\n      - Process Definition\n      - Process Execution\n      - Process Run Monitoring\n      - Step Run Outputs\n      - Work Item Management\n      - Asset Storage\n      - Vault Secrets\n      - Webhook Configuration\n      - Task Package Deployment\n      - Link Token Generation\n    useCases:\n      - RPA bot orchestration\n      - Automation workflow scheduling\n      - Work item queue management\n      - Secret credential management\n      - Process monitoring and debugging\n      - CI/CD pipeline integration\n    solutions:\n      - RPA Orchestration\n      - Workflow Automation\n      - Bot Management\n\n  - aid: robocorp:rpa-framework\n    name: RPA Framework\n    description: >-\n      The RPA Framework is an open-source collection of Python libraries for\n      robotic process automation designed for use with Robot Framework and\n      Python. It includes libraries for browser automation, desktop automation,\n      Excel, email, PDF, Windows UI, cloud service\
  \ integrations, and more.\n    humanURL: https://rpaframework.org/\n    tags:\n      - RPA\n      - Python\n      - Open Source\n      - Libraries\n    properties:\n      - url: https://rpaframework.org/\n        type: Documentation\n      - url: https://github.com/robocorp/rpaframework\n        type: GitHub\n\ncommon:\n  - type: Website\n    url: https://robocorp.com\n  - type: Documentation\n    url: https://robocorp.com/docs\n  - type: GitHub\n    url: https://github.com/robocorp\n  - type: PyPI\n    url: https://pypi.org/project/robocorp/\n  - type: Blog\n    url: https://robocorp.com/blog\n  - type: PrivacyPolicy\n    url: https://robocorp.com/privacy-policy\n  - type: TermsOfService\n    url: https://robocorp.com/terms-of-service\n  - type: Status\n    url: https://status.robocorp.com\n  - type: Changelog\n    url: https://robocorp.com/docs/changelog\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-ld/robocorp-context.jsonld\n\
  \  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/vocabulary/robocorp-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/apis.yml
tags:
- RPA
- Workflow Automation
- Python
- Open Source
- Automation
url: https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/apis.yml
use_cases: []
---
