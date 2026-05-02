---
api_count: 3
apis:
- description: 'Current REST API for Kanban Tool. Returns JSON responses, supports bulk task modifications, attachment operations, and uses a flat namespace with associated objects in single responses. Authenticated '
  name: Kanban Tool REST API v3
  slug: kanban-tool-rest-api-v3
- description: Legacy REST API for Kanban Tool. Supports both XML and JSON formats, uses a resource-oriented endpoint structure. Remains supported for existing integrations.
  name: Kanban Tool REST API v1
  slug: kanban-tool-rest-api-v1
- description: Browser-side SDK for customizing the Kanban Tool interface. Enables adding custom buttons to context menus, modifying styles, and extending UI behavior.
  name: Kanban Tool Browser SDK
  slug: kanban-tool-sdk
common:
- title: ''
  type: Website
  url: https://kanbantool.com
- title: ''
  type: Developer Portal
  url: https://kanbantool.com/developer
- title: ''
  type: Blog
  url: https://kanbantool.com/blog
- title: ''
  type: Pricing
  url: https://kanbantool.com/pricing
- title: ''
  type: Sign Up
  url: https://kanbantool.com/signup/new
- title: ''
  type: Support
  url: https://kanbantool.com/support/introduction
- title: ''
  type: Kanban Guide
  url: https://kanbantool.com/kanban-guide/introduction
created: '2024-01-15'
description: Kanban Tool is a visual project management platform for managing boards, tasks, and workflows using the Kanban methodology. It provides REST APIs (v1 and v3), browser SDK, and DevKit for programmatic access to boards, tasks, columns, comments, attachments, time tracking, and team members.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Kanban Tool
skills: []
slug: kanban
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kanban\nname: Kanban Tool\ndescription: >-\n  Kanban Tool is a visual project management platform for managing boards,\n  tasks, and workflows using the Kanban methodology. It provides REST APIs\n  (v1 and v3), browser SDK, and DevKit for programmatic access to boards,\n  tasks, columns, comments, attachments, time tracking, and team members.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agile\n  - Boards\n  - Kanban\n  - Project Management\n  - Task Management\n  - Time Tracking\n  - Workflow\nurl: https://raw.githubusercontent.com/api-evangelist/kanban/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kanban:kanban-tool-rest-api-v3\n    name: Kanban Tool REST API v3\n    description: >-\n      Current REST API for Kanban Tool. Returns JSON responses, supports\n      bulk task modifications, attachment operations, and uses a flat\n      namespace\
  \ with associated objects in single responses. Authenticated\n      via Bearer token.\n    humanURL: https://kanbantool.com/developer/api-v3\n    baseURL: https://YOUR_DOMAIN.kanbantool.com/api/v3\n    tags:\n      - Boards\n      - Cards\n      - Comments\n      - Attachments\n      - Tasks\n      - Subtasks\n      - Time Tracking\n      - Users\n    properties:\n      - type: Documentation\n        url: https://kanbantool.com/developer/api-v3\n      - type: Authentication\n        url: https://kanbantool.com/developer/api-v3\n  - aid: kanban:kanban-tool-rest-api-v1\n    name: Kanban Tool REST API v1\n    description: >-\n      Legacy REST API for Kanban Tool. Supports both XML and JSON formats,\n      uses a resource-oriented endpoint structure. Remains supported for\n      existing integrations.\n    humanURL: https://kanbantool.com/developer\n    tags:\n      - Boards\n      - Legacy\n      - Tasks\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://kanbantool.com/developer\n\
  \  - aid: kanban:kanban-tool-sdk\n    name: Kanban Tool Browser SDK\n    description: >-\n      Browser-side SDK for customizing the Kanban Tool interface. Enables\n      adding custom buttons to context menus, modifying styles, and\n      extending UI behavior.\n    humanURL: https://kanbantool.com/developer\n    tags:\n      - SDK\n      - Browser\n      - Customization\n    properties:\n      - type: Documentation\n        url: https://kanbantool.com/developer\ncommon:\n  - type: Website\n    url: https://kanbantool.com\n  - type: Developer Portal\n    url: https://kanbantool.com/developer\n  - type: Blog\n    url: https://kanbantool.com/blog\n  - type: Pricing\n    url: https://kanbantool.com/pricing\n  - type: Sign Up\n    url: https://kanbantool.com/signup/new\n  - type: Support\n    url: https://kanbantool.com/support/introduction\n  - type: Integrations\n    url: https://kanbantool.com/integrations\n  - type: Kanban Guide\n    url: https://kanbantool.com/kanban-guide/introduction\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kanban/refs/heads/main/apis.yml
tags:
- Agile
- Boards
- Kanban
- Project Management
- Task Management
- Time Tracking
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/kanban/refs/heads/main/apis.yml
use_cases: []
---
