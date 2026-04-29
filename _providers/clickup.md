---
api_count: 12
api_specs:
- filename: clickup-tasks-openapi.yml
  format: yaml
  label: ClickUp Tasks API
  slug: tasks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-tasks-openapi.yml
- filename: clickup-spaces-openapi.yml
  format: yaml
  label: ClickUp Spaces API
  slug: spaces-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-spaces-openapi.yml
- filename: clickup-lists-openapi.yml
  format: yaml
  label: ClickUp Lists API
  slug: lists-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-lists-openapi.yml
- filename: clickup-folders-openapi.yml
  format: yaml
  label: ClickUp Folders API
  slug: folders-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-folders-openapi.yml
- filename: clickup-goals-openapi.yml
  format: yaml
  label: ClickUp Goals API
  slug: goals-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-goals-openapi.yml
- filename: clickup-comments-openapi.yml
  format: yaml
  label: ClickUp Comments API
  slug: comments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-comments-openapi.yml
- filename: clickup-teams-openapi.yml
  format: yaml
  label: ClickUp Teams (Workspaces) API
  slug: teams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-teams-openapi.yml
- filename: clickup-webhooks-openapi.yml
  format: yaml
  label: ClickUp Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-webhooks-openapi.yml
- filename: clickup-custom-fields-openapi.yml
  format: yaml
  label: ClickUp Custom Fields API
  slug: custom-fields-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-custom-fields-openapi.yml
- filename: clickup-time-tracking-openapi.yml
  format: yaml
  label: ClickUp Time Tracking API
  slug: time-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-time-tracking-openapi.yml
- filename: clickup-views-openapi.yml
  format: yaml
  label: ClickUp Views API
  slug: views-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-views-openapi.yml
- filename: clickup-oauth-openapi.yml
  format: yaml
  label: ClickUp OAuth API
  slug: oauth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/openapi/clickup-oauth-openapi.yml
apis:
- description: The ClickUp Tasks API allows developers to create, read, update, and delete tasks within ClickUp workspaces. Tasks are the core unit of work in ClickUp and can include custom fields, assignees, due da
  name: ClickUp Tasks API
  slug: tasks-api
- description: The ClickUp Spaces API provides endpoints for managing Spaces, which are the top-level organizational containers within a ClickUp Workspace. Spaces contain Folders and Lists that organize tasks into l
  name: ClickUp Spaces API
  slug: spaces-api
- description: 'The ClickUp Lists API enables developers to manage Lists, which are containers that hold tasks within a Space or Folder. Lists define the workflow statuses available to tasks and serve as the primary '
  name: ClickUp Lists API
  slug: lists-api
- description: The ClickUp Folders API provides endpoints for managing Folders, which are optional organizational containers that sit between Spaces and Lists in the ClickUp hierarchy. Folders group related Lists to
  name: ClickUp Folders API
  slug: folders-api
- description: The ClickUp Goals API allows developers to create and manage goals within a Workspace. Goals can track progress toward objectives using targets based on numbers, currency, percentages, or task complet
  name: ClickUp Goals API
  slug: goals-api
- description: The ClickUp Comments API provides endpoints for creating and retrieving comments on tasks, views, and lists. Comments support rich text formatting, mentions, and attachments. Developers can use this A
  name: ClickUp Comments API
  slug: comments-api
- description: The ClickUp Teams API provides access to Workspace-level information and membership. In the ClickUp API, Teams correspond to Workspaces, which are the top-level organizational unit. The API allows dev
  name: ClickUp Teams (Workspaces) API
  slug: teams-api
- description: The ClickUp Webhooks API enables developers to subscribe to real-time events within a Workspace. When subscribed events occur, ClickUp sends HTTP POST requests to a specified endpoint URL with event d
  name: ClickUp Webhooks API
  slug: webhooks-api
- description: The ClickUp Custom Fields API allows developers to retrieve available custom fields for a list and set or update custom field values on tasks. Custom fields extend the default task data model with use
  name: ClickUp Custom Fields API
  slug: custom-fields-api
- description: The ClickUp Time Tracking API provides endpoints for recording and retrieving time entries associated with tasks. Developers can create manual time entries, start and stop timers, and query time entri
  name: ClickUp Time Tracking API
  slug: time-tracking-api
- description: The ClickUp Views API enables developers to create and manage views at the team, space, folder, and list levels. Views define how tasks are displayed and filtered, supporting formats such as list, boa
  name: ClickUp Views API
  slug: views-api
- description: The ClickUp OAuth API implements the authorization code grant type, allowing third-party applications to authenticate users and access their ClickUp Workspaces. Workspace owners or admins can create O
  name: ClickUp OAuth API
  slug: oauth-api
asyncapis:
- description: The ClickUp Webhooks event system delivers real-time notifications when changes occur within a ClickUp Workspace. When subscribed events happen, ClickUp sends HTTP POST requests to a registered endpoi
  name: ClickUp Webhooks Events
  slug: clickup-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/clickup-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/clickup-task-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/clickup-webhook-payload-schema.json
created: ''
description: Work with tasks using the ClickUp API.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Clickup Context
  property_count: 11
  slug: clickup-context
layout: provider
modified: '2026-03-20'
name: clickup
skills: []
slug: clickup
solutions: []
source_filename: apis.yml
source_yaml: "aid: clickup\nurl: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/apis.yml\nmodified: '2026-03-20'\napis:\n  - aid: clickup:tasks-api\n    name: ClickUp Tasks API\n    tags:\n      - Collaboration\n      - Productivity\n      - Project Management\n      - Tasks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/docs/tasks\n    properties:\n      - url: https://developer.clickup.com/docs/tasks\n        type: Documentation\n      - url: openapi/clickup-tasks-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Tasks API allows developers to create, read, update, and\n      delete tasks within ClickUp workspaces. Tasks are the core unit of work\n      in ClickUp and can include custom fields, assignees, due dates, tags,\n      priorities, and attachments. The API supports filtering tasks by list,\n      space, or\
  \ project, and enables bulk operations for managing large\n      numbers of tasks programmatically.\n  - aid: clickup:spaces-api\n    name: ClickUp Spaces API\n    tags:\n      - Organization\n      - Project Management\n      - Workspaces\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-spaces\n    properties:\n      - url: https://developer.clickup.com/reference/get-spaces\n        type: Documentation\n      - url: openapi/clickup-spaces-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Spaces API provides endpoints for managing Spaces, which\n      are the top-level organizational containers within a ClickUp Workspace.\n      Spaces contain Folders and Lists that organize tasks into logical\n      groupings. Developers can create, update, and delete Spaces, as well\n      as retrieve Space details and configure Space-level settings\
  \ such as\n      enabled features and statuses.\n  - aid: clickup:lists-api\n    name: ClickUp Lists API\n    tags:\n      - Lists\n      - Project Management\n      - Task Organization\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-lists\n    properties:\n      - url: https://developer.clickup.com/reference/get-lists\n        type: Documentation\n      - url: openapi/clickup-lists-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Lists API enables developers to manage Lists, which are\n      containers that hold tasks within a Space or Folder. Lists define the\n      workflow statuses available to tasks and serve as the primary grouping\n      mechanism for related work items. The API supports creating, updating,\n      and deleting Lists, as well as retrieving List details and the tasks\n      they contain.\n  - aid: clickup:folders-api\n\
  \    name: ClickUp Folders API\n    tags:\n      - Folders\n      - Organization\n      - Project Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-folders\n    properties:\n      - url: https://developer.clickup.com/reference/get-folders\n        type: Documentation\n      - url: openapi/clickup-folders-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Folders API provides endpoints for managing Folders, which\n      are optional organizational containers that sit between Spaces and\n      Lists in the ClickUp hierarchy. Folders group related Lists together\n      and can be used to organize projects or workstreams within a Space.\n      Developers can create, update, delete, and retrieve Folders and their\n      associated Lists.\n  - aid: clickup:goals-api\n    name: ClickUp Goals API\n    tags:\n      - Goals\n   \
  \   - OKR\n      - Project Management\n      - Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-goals\n    properties:\n      - url: https://developer.clickup.com/reference/get-goals\n        type: Documentation\n      - url: openapi/clickup-goals-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Goals API allows developers to create and manage goals\n      within a Workspace. Goals can track progress toward objectives using\n      targets based on numbers, currency, percentages, or task completion.\n      The API supports creating goals, adding key results and targets,\n      updating progress, and retrieving goal details. This is useful for\n      building OKR tracking and reporting integrations.\n  - aid: clickup:comments-api\n    name: ClickUp Comments API\n    tags:\n      - Collaboration\n      - Comments\n      -\
  \ Project Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-task-comments\n    properties:\n      - url: https://developer.clickup.com/reference/get-task-comments\n        type: Documentation\n      - url: openapi/clickup-comments-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Comments API provides endpoints for creating and retrieving\n      comments on tasks, views, and lists. Comments support rich text\n      formatting, mentions, and attachments. Developers can use this API to\n      build integrations that synchronize discussions between ClickUp and\n      other collaboration tools, or to programmatically add status updates\n      and notes to tasks.\n  - aid: clickup:teams-api\n    name: ClickUp Teams (Workspaces) API\n    tags:\n      - Project Management\n      - Teams\n      - Users\n      - Workspaces\n  \
  \  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-teams\n    properties:\n      - url: https://developer.clickup.com/reference/get-teams\n        type: Documentation\n      - url: openapi/clickup-teams-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Teams API provides access to Workspace-level information\n      and membership. In the ClickUp API, Teams correspond to Workspaces,\n      which are the top-level organizational unit. The API allows developers\n      to retrieve a list of Workspaces the authenticated user belongs to,\n      along with member details and roles. This is typically the starting\n      point for navigating the ClickUp hierarchy.\n  - aid: clickup:webhooks-api\n    name: ClickUp Webhooks API\n    tags:\n      - Events\n      - Project Management\n      - Real-Time\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/docs/webhooks\n    properties:\n      - url: https://developer.clickup.com/docs/webhooks\n        type: Documentation\n      - url: openapi/clickup-webhooks-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/clickup-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The ClickUp Webhooks API enables developers to subscribe to real-time\n      events within a Workspace. When subscribed events occur, ClickUp sends\n      HTTP POST requests to a specified endpoint URL with event details.\n      Webhooks support events for tasks, lists, folders, spaces, and goals.\n      Each webhook payload is signed with a shared secret for verification,\n      ensuring the event originated from ClickUp.\n  - aid: clickup:custom-fields-api\n    name: ClickUp Custom Fields API\n    tags:\n      - Custom Fields\n      - Metadata\n      - Project Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-accessible-custom-fields\n    properties:\n      - url: https://developer.clickup.com/reference/get-accessible-custom-fields\n        type: Documentation\n      - url: openapi/clickup-custom-fields-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Custom Fields API allows developers to retrieve available\n      custom fields for a list and set or update custom field values on\n      tasks. Custom fields extend the default task data model with\n      user-defined attributes such as dropdowns, labels, numbers, dates,\n      and relationships. This API is essential for integrations that need\n      to read or write structured metadata beyond the standard task fields.\n  - aid: clickup:time-tracking-api\n    name: ClickUp Time Tracking API\n    tags:\n      - Productivity\n      - Project Management\n      - Reporting\n      - Time Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/reference/get-time-entries-within-a-date-range\n    properties:\n      - url: https://developer.clickup.com/reference/get-time-entries-within-a-date-range\n        type: Documentation\n      - url: openapi/clickup-time-tracking-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Time Tracking API provides endpoints for recording and\n      retrieving time entries associated with tasks. Developers can create\n      manual time entries, start and stop timers, and query time entries\n      within date ranges and across team members. This API supports building\n      time reporting dashboards, invoicing integrations, and productivity\n      analysis tools.\n  - aid: clickup:views-api\n    name: ClickUp Views API\n    tags:\n      - Dashboards\n      - Project Management\n      - Views\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n\
  \    humanURL: https://developer.clickup.com/reference/get-views\n    properties:\n      - url: https://developer.clickup.com/reference/get-views\n        type: Documentation\n      - url: openapi/clickup-views-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp Views API enables developers to create and manage views\n      at the team, space, folder, and list levels. Views define how tasks\n      are displayed and filtered, supporting formats such as list, board,\n      calendar, gantt, and table. The API allows programmatic creation of\n      saved views with specific filters, groupings, and sort configurations.\n  - aid: clickup:oauth-api\n    name: ClickUp OAuth API\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth\n      - Project Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.clickup.com\n    humanURL: https://developer.clickup.com/docs/authentication\n    properties:\n\
  \      - url: https://developer.clickup.com/docs/authentication\n        type: Documentation\n      - url: openapi/clickup-oauth-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClickUp OAuth API implements the authorization code grant type,\n      allowing third-party applications to authenticate users and access\n      their ClickUp Workspaces. Workspace owners or admins can create OAuth\n      apps, and users authorize access by granting permissions to specific\n      Workspaces. The API provides endpoints for obtaining authorization\n      codes, exchanging them for access tokens, and retrieving the\n      authenticated user's information.\ncommon:\n  - type: JSON-LD\n    url: json-ld/clickup-context.jsonld\n  - type: JSONSchema\n    url: json-schema/clickup-task-schema.json\n  - type: JSONSchema\n    url: json-schema/clickup-webhook-payload-schema.json\ndescription: >-\n  Work with tasks using the ClickUp API.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/apis.yml
use_cases: []
---
