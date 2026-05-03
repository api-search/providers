---
api_count: 3
api_specs:
- filename: todoist-openapi.yml
  format: yaml
  label: Todoist API
  slug: todoist-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/openapi/todoist-openapi.yml
apis:
- description: The Todoist API v1 provides programmatic access to Todoist task management, projects, sections, labels, reminders, comments, workspaces, and more. Supports OAuth 2.0 and personal API tokens for authen
  name: Todoist API
  slug: todoist-api
- description: The Todoist REST API v2 is the legacy recommended API for external integrations, providing access to tasks, projects, sections, labels, comments, and filters. Uses Bearer token authentication with OAu
  name: Todoist REST API v2
  slug: todoist-rest-api
- description: The Todoist Sync API is designed for clients maintaining a local representation of user data, allowing incremental synchronization of projects, tasks, labels, filters, and reminders. Supports batch co
  name: Todoist Sync API v9
  slug: todoist-sync-api
capabilities:
- description: Unified capability for managing tasks, projects, sections, labels, and comments in Todoist. Enables AI agents and workflow automation to create, update, organize, and complete tasks programmatically.
  name: Todoist Task Management
  slug: task-management
common:
- title: ''
  type: Website
  url: https://todoist.com/
- title: ''
  type: Developer Portal
  url: https://developer.todoist.com/
- title: ''
  type: Documentation
  url: https://developer.todoist.com/api/v1/
- title: ''
  type: Sign Up
  url: https://todoist.com/users/showregister
- title: ''
  type: Login
  url: https://todoist.com/auth/login
- title: ''
  type: Authentication
  url: https://developer.todoist.com/guides/#oauth
- title: ''
  type: Webhooks
  url: https://developer.todoist.com/api/v1/#webhooks
- title: ''
  type: SDKs
  url: https://developer.todoist.com/guides/#sdks
- title: ''
  type: Python SDK
  url: https://github.com/Doist/todoist-api-python
- title: ''
  type: TypeScript SDK
  url: https://github.com/Doist/todoist-sdk-typescript
- title: ''
  type: MCP Server
  url: https://github.com/doist/todoist-ai
- title: ''
  type: GitHub Organization
  url: https://github.com/Doist
- title: ''
  type: Blog
  url: https://doist.com/blog/
- title: ''
  type: Pricing
  url: https://todoist.com/pricing
- title: ''
  type: Terms of Service
  url: https://doist.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://doist.com/privacy-policy
created: '2025-01-08'
description: Todoist is a productivity platform providing task management APIs for developers. The Todoist API v1 unifies the Sync and REST APIs into a single interface, offering programmatic access to tasks, projects, sections, labels, reminders, comments, workspaces, and webhooks. SDKs are available in Python and TypeScript.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Todoist Context
  property_count: 7
  slug: todoist-context
layout: provider
modified: '2026-05-03'
name: Todoist
rules:
- name: Todoist API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: todoist-rules
skills: []
slug: todoist
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: todoist\nname: Todoist\ndescription: >-\n  Todoist is a productivity platform providing task management APIs for developers.\n  The Todoist API v1 unifies the Sync and REST APIs into a single interface, offering\n  programmatic access to tasks, projects, sections, labels, reminders, comments,\n  workspaces, and webhooks. SDKs are available in Python and TypeScript.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Productivity\n  - Tasks\n  - To-Do\n  - Task Management\n  - Collaboration\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: todoist:todoist-api\n    name: Todoist API\n    description: >-\n      The Todoist API v1 provides programmatic access to Todoist task management,\n      projects, sections, labels, reminders, comments, workspaces,\
  \ and more.\n      Supports OAuth 2.0 and personal API tokens for authentication. Includes\n      incremental sync via the /sync endpoint for efficient client-server data\n      synchronization.\n    humanURL: https://developer.todoist.com/api/v1/\n    baseURL: https://api.todoist.com/api/v1\n    tags:\n      - Productivity\n      - Tasks\n      - Projects\n      - Task Management\n    properties:\n      - type: Documentation\n        url: https://developer.todoist.com/api/v1/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/openapi/todoist-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/json-schema/todoist-task-schema.json\n      - type: NaftikoCapabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/capabilities/task-management.yaml\n      - type: SpectralRules\n \
  \       url: >-\n          https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/rules/todoist-rules.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/vocabulary/todoist-vocabulary.yml\n    contact:\n      - FN: Todoist Developer Support\n        url: https://developer.todoist.com/\n  - aid: todoist:todoist-rest-api\n    name: Todoist REST API v2\n    description: >-\n      The Todoist REST API v2 is the legacy recommended API for external integrations,\n      providing access to tasks, projects, sections, labels, comments, and filters.\n      Uses Bearer token authentication with OAuth 2.0 support.\n    humanURL: https://developer.todoist.com/rest/v2/\n    baseURL: https://api.todoist.com/rest/v2\n    tags:\n      - Productivity\n      - Tasks\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.todoist.com/rest/v2/\n  - aid: todoist:todoist-sync-api\n\
  \    name: Todoist Sync API v9\n    description: >-\n      The Todoist Sync API is designed for clients maintaining a local representation\n      of user data, allowing incremental synchronization of projects, tasks, labels,\n      filters, and reminders. Supports batch commands for efficient updates.\n    humanURL: https://developer.todoist.com/sync/v9/\n    baseURL: https://api.todoist.com/sync/v9\n    tags:\n      - Sync\n      - Productivity\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://developer.todoist.com/sync/v9/\n      - type: Reference\n        url: https://developer.todoist.com/sync/v9/\ncommon:\n  - type: Website\n    url: https://todoist.com/\n  - type: Developer Portal\n    url: https://developer.todoist.com/\n  - type: Documentation\n    url: https://developer.todoist.com/api/v1/\n  - type: Sign Up\n    url: https://todoist.com/users/showregister\n  - type: Login\n    url: https://todoist.com/auth/login\n  - type: Authentication\n   \
  \ url: https://developer.todoist.com/guides/#oauth\n  - type: Webhooks\n    url: https://developer.todoist.com/api/v1/#webhooks\n  - type: SDKs\n    url: https://developer.todoist.com/guides/#sdks\n  - type: Python SDK\n    url: https://github.com/Doist/todoist-api-python\n  - type: TypeScript SDK\n    url: https://github.com/Doist/todoist-sdk-typescript\n  - type: MCP Server\n    url: https://github.com/doist/todoist-ai\n  - type: GitHub Organization\n    url: https://github.com/Doist\n  - type: Blog\n    url: https://doist.com/blog/\n  - type: Pricing\n    url: https://todoist.com/pricing\n  - type: Terms of Service\n    url: https://doist.com/terms-of-service\n  - type: Privacy Policy\n    url: https://doist.com/privacy-policy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/apis.yml
tags:
- Productivity
- Tasks
- To-Do
- Task Management
- Collaboration
url: https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/apis.yml
use_cases: []
---
