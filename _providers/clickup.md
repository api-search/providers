---
api_count: 12
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
tags: []
url: https://raw.githubusercontent.com/api-evangelist/clickup/refs/heads/main/apis.yml
use_cases: []
---
