---
api_count: 2
api_specs:
- filename: trigger-dev-management-openapi.yml
  format: yaml
  label: Trigger.dev Management API
  slug: trigger-dev-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/openapi/trigger-dev-management-openapi.yml
apis:
- description: The Trigger.dev Management API provides comprehensive REST endpoints for managing workflow runs, tasks, schedules, deployments, queues, environment variables, batches, and waitpoints. Enables programm
  name: Trigger.dev Management API
  slug: trigger-dev-management
- description: The Trigger.dev Realtime API provides streaming updates and React hooks for monitoring workflow run status in real-time. Includes useRealtimeRun, useRealtimeRunsWithTag, and useRealtimeStream hooks fo
  name: Trigger.dev Realtime API
  slug: trigger-dev-realtime
capabilities:
- description: 'Unified workflow automation capability combining task triggering, run monitoring, schedule management, queue control, and waitpoint orchestration. Powers AI agent pipelines, background job platforms, '
  name: Trigger.dev Workflow Automation
  slug: workflow-automation
common:
- title: ''
  type: Website
  url: https://trigger.dev
- title: ''
  type: Documentation
  url: https://trigger.dev/docs
- title: ''
  type: GettingStarted
  url: https://trigger.dev/docs/introduction
- title: ''
  type: GitHub
  url: https://github.com/triggerdotdev/trigger.dev
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@trigger.dev/sdk
- title: ''
  type: CLI
  url: https://www.npmjs.com/package/trigger.dev
- title: ''
  type: SignUp
  url: https://cloud.trigger.dev/login
- title: ''
  type: Pricing
  url: https://trigger.dev/pricing
- title: ''
  type: Blog
  url: https://trigger.dev/blog
- title: ''
  type: Changelog
  url: https://trigger.dev/changelog
created: '2026-03-27'
description: Trigger.dev is an open source background jobs and workflow automation platform for TypeScript developers. It enables building and deploying fully-managed AI agents and background workflows with real-time observability, scheduled tasks, durable execution, and an extensive management API. Tasks are written in plain async TypeScript and can be triggered via REST API, SDK, or on a schedule. Supports cloud-hosted and self-hosted deployments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Trigger Dev Context
  property_count: 29
  slug: trigger-dev-context
layout: provider
modified: '2026-05-03'
name: Trigger.dev
rules:
- name: Trigger.dev API Rules
  rule_count: 11
  severity_counts:
    error: 4
    hint: 2
    info: 0
    warn: 5
  slug: trigger-dev-rules
skills: []
slug: trigger-dev
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trigger-dev\nname: Trigger.dev\ndescription: >-\n  Trigger.dev is an open source background jobs and workflow automation platform for\n  TypeScript developers. It enables building and deploying fully-managed AI agents and\n  background workflows with real-time observability, scheduled tasks, durable execution,\n  and an extensive management API. Tasks are written in plain async TypeScript and can\n  be triggered via REST API, SDK, or on a schedule. Supports cloud-hosted and self-hosted\n  deployments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer-First\n  - Workflow Automation\n  - Background Jobs\n  - TypeScript\n  - AI Agents\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trigger-dev:trigger-dev-management\n    name: Trigger.dev Management\
  \ API\n    description: >-\n      The Trigger.dev Management API provides comprehensive REST endpoints for managing\n      workflow runs, tasks, schedules, deployments, queues, environment variables,\n      batches, and waitpoints. Enables programmatic control over the full lifecycle\n      of background job workflows including triggering, monitoring, cancellation,\n      and observability. Authenticated via bearer token (secret API key).\n    humanURL: https://trigger.dev/docs/management/overview\n    tags:\n      - Workflow Automation\n      - Background Jobs\n      - Task Management\n      - Scheduling\n      - Deployments\n      - Queue Management\n    properties:\n      - type: Documentation\n        url: https://trigger.dev/docs/management/overview\n      - type: GettingStarted\n        url: https://trigger.dev/docs/introduction\n      - type: OpenAPI\n        url: openapi/trigger-dev-management-openapi.yml\n      - type: SDK\n        url: https://www.npmjs.com/package/@trigger.dev/sdk\n\
  \n  - aid: trigger-dev:trigger-dev-realtime\n    name: Trigger.dev Realtime API\n    description: >-\n      The Trigger.dev Realtime API provides streaming updates and React hooks for\n      monitoring workflow run status in real-time. Includes useRealtimeRun,\n      useRealtimeRunsWithTag, and useRealtimeStream hooks for frontend integration.\n      Supports AI streaming responses and live run status updates.\n    humanURL: https://trigger.dev/docs/realtime/overview\n    tags:\n      - Realtime\n      - Streaming\n      - React\n      - WebSockets\n      - AI Streaming\n    properties:\n      - type: Documentation\n        url: https://trigger.dev/docs/realtime/overview\n\nfeatures:\n  - Durable background task execution with automatic retries\n  - Scheduled tasks with cron expressions and timezone support\n  - AI agent workflow orchestration\n  - Realtime run monitoring with React hooks\n  - Queue management with concurrency controls\n  - Environment variable management per project\n\
  \  - Deployment management with version promotion\n  - Waitpoint tokens for human-in-the-loop workflows\n  - Batch task triggering\n  - Comprehensive observability with traces and spans\nuseCases:\n  - Background job processing for TypeScript/Node.js applications\n  - AI agent task orchestration with durable execution\n  - Scheduled data processing and reporting jobs\n  - Long-running workflow automation\n  - Email and notification delivery pipelines\n  - Data synchronization and ETL workflows\n  - Human-in-the-loop approval workflows\nintegrations:\n  - TypeScript/Node.js via @trigger.dev/sdk\n  - React via @trigger.dev/react-hooks\n  - CLI via trigger.dev/cli\n  - Next.js, Remix, and other full-stack frameworks\n  - Self-hosted deployment via Docker\nsolutions:\n  - TypeScript developers needing reliable background jobs\n  - Teams building AI agent workflows requiring durable execution\n  - Applications requiring scheduled task automation\n  - Platforms needing human-in-the-loop approval\
  \ workflows\ngithub:\n  - name: trigger.dev\n    url: https://github.com/triggerdotdev/trigger.dev\n    description: Main Trigger.dev monorepo - platform, SDK, and CLI\n    language: TypeScript\n    stars: 14763\n  - name: api-reference\n    url: https://github.com/triggerdotdev/api-reference\n    description: Job code samples for SDK and REST API integrations\n    language: TypeScript\ncommon:\n  - type: Website\n    url: https://trigger.dev\n  - type: Documentation\n    url: https://trigger.dev/docs\n  - type: GettingStarted\n    url: https://trigger.dev/docs/introduction\n  - type: GitHub\n    url: https://github.com/triggerdotdev/trigger.dev\n  - type: SDK\n    url: https://www.npmjs.com/package/@trigger.dev/sdk\n  - type: CLI\n    url: https://www.npmjs.com/package/trigger.dev\n  - type: SignUp\n    url: https://cloud.trigger.dev/login\n  - type: Pricing\n    url: https://trigger.dev/pricing\n  - type: Blog\n    url: https://trigger.dev/blog\n  - type: Changelog\n    url: https://trigger.dev/changelog\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/apis.yml
tags:
- Developer-First
- Workflow Automation
- Background Jobs
- TypeScript
- AI Agents
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/apis.yml
use_cases: []
---
