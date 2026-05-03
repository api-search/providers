---
api_count: 1
api_specs:
- filename: rundeck-openapi.yml
  format: yaml
  label: Rundeck API
  slug: rundeck-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/openapi/rundeck-openapi.yml
apis:
- description: The Rundeck REST API provides programmatic access to job execution, project management, node management, execution history, user management, ACL policies, system administration, cluster operations, an
  name: Rundeck API
  slug: rundeck-api
capabilities:
- description: Unified runbook automation capability for Rundeck. Enables DevOps engineers and IT operations teams to trigger automated runbooks, monitor execution status, manage infrastructure nodes, and administer
  name: Rundeck Runbook Automation
  slug: runbook-automation
common:
- title: ''
  type: Website
  url: https://www.rundeck.com
- title: ''
  type: Documentation
  url: https://docs.rundeck.com
- title: ''
  type: GitHub Organization
  url: https://github.com/rundeck
- title: ''
  type: GitHub Repository
  url: https://github.com/rundeck/rundeck
- title: ''
  type: Blog
  url: https://www.rundeck.com/blog
- title: ''
  type: Community
  url: https://community.rundeck.com
- title: ''
  type: Download
  url: https://www.rundeck.com/downloads
- title: ''
  type: Support
  url: https://www.rundeck.com/support
- title: ''
  type: Pricing
  url: https://www.rundeck.com/pricing
created: '2024-01-01'
description: Rundeck is an open source runbook automation service with a web console, command line tools, and a REST WebAPI. It enables IT teams to easily run automation tasks across a set of nodes, providing self-service operations, job scheduling, and execution history. Rundeck is developed by PagerDuty and supports enterprise runbook automation with role-based access control, multi-tenant project management, and integrations with popular DevOps tools including Jenkins, Ansible, Chef, and Puppet. The REST API is versioned and supports authentication via API tokens, password-based session tokens, and JWT (commercial).
features: []
image: https://www.rundeck.com/hubfs/Assets/Images/logos/rundeck-logo-black.png
integrations: []
jsonld:
- class_count: 0
  name: Rundeck Context
  property_count: 6
  slug: rundeck-context
layout: provider
modified: '2026-05-02'
name: Rundeck
rules:
- name: Rundeck API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 11
  slug: rundeck-rules
skills: []
slug: rundeck
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rundeck\nname: Rundeck\ndescription: >-\n  Rundeck is an open source runbook automation service with a web console, command line\n  tools, and a REST WebAPI. It enables IT teams to easily run automation tasks across a\n  set of nodes, providing self-service operations, job scheduling, and execution history.\n  Rundeck is developed by PagerDuty and supports enterprise runbook automation with role-based\n  access control, multi-tenant project management, and integrations with popular DevOps tools\n  including Jenkins, Ansible, Chef, and Puppet. The REST API is versioned and supports\n  authentication via API tokens, password-based session tokens, and JWT (commercial).\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://www.rundeck.com/hubfs/Assets/Images/logos/rundeck-logo-black.png\ntags:\n  - Automation\n  - DevOps\n  - Job Scheduling\n  - Orchestration\n  - Workflow\n  - Runbook\n  - Open Source\n  - IT Operations\nurl: https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/apis.yml\n\
  created: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rundeck:rundeck-api\n    name: Rundeck API\n    description: >-\n      The Rundeck REST API provides programmatic access to job execution, project management,\n      node management, execution history, user management, ACL policies, system administration,\n      cluster operations, and log storage. The current API version is 58, with a base URL of\n      $RUNDECK_SERVER_URL/api/58. Authentication is performed via X-Rundeck-Auth-Token header\n      or authtoken query parameter. The API returns JSON responses and supports webhook\n      integrations for event-driven automation workflows.\n    humanURL: https://docs.rundeck.com/docs/api/\n    baseURL: http://localhost:4440/api\n    tags:\n      - Automation\n      - DevOps\n      - Job Scheduling\n      - Orchestration\n      - Workflow\n      - Projects\n      - Executions\n      - Jobs\n      - Nodes\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.rundeck.com/docs/api/\n      - type: OpenAPI\n        url: openapi/rundeck-openapi.yml\n      - type: Authentication\n        url: https://docs.rundeck.com/docs/api/#authentication\n      - type: Versioning\n        url: https://docs.rundeck.com/docs/api/#api-versioning\n      - type: GitHub Repository\n        url: https://github.com/rundeck/rundeck-api-specs\n      - type: Spectral Rules\n        url: rules/rundeck-rules.yml\n      - type: Vocabulary\n        url: vocabulary/rundeck-vocabulary.yml\n      - type: JSONSchema\n        url: json-schema/rundeck-job-schema.json\n      - type: JSONStructure\n        url: json-structure/rundeck-job-structure.json\n      - type: JSONLD\n        url: json-ld/rundeck-context.jsonld\n      - type: NaftikoCapability\n        url: capabilities/runbook-automation.yaml\ncommon:\n  - type: Website\n    url: https://www.rundeck.com\n  - type: Documentation\n    url: https://docs.rundeck.com\n  - type: GitHub Organization\n \
  \   url: https://github.com/rundeck\n  - type: GitHub Repository\n    url: https://github.com/rundeck/rundeck\n  - type: Blog\n    url: https://www.rundeck.com/blog\n  - type: Community\n    url: https://community.rundeck.com\n  - type: Download\n    url: https://www.rundeck.com/downloads\n  - type: Support\n    url: https://www.rundeck.com/support\n  - type: Pricing\n    url: https://www.rundeck.com/pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/apis.yml
tags:
- Automation
- DevOps
- Job Scheduling
- Orchestration
- Workflow
- Runbook
- Open Source
- IT Operations
url: https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/apis.yml
use_cases: []
---
