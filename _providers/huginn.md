---
api_count: 2
apis:
- description: The Huginn platform is a self-hosted Ruby on Rails application that orchestrates agents, scenarios, and events. Operators install and run their own instance and configure agents to consume and produce
  name: Huginn Platform
  slug: huginn-platform
- description: Each Huginn instance exposes a Web Requests endpoint that lets external systems POST or GET events into a configured Webhook Agent. The endpoint lives at /users/{user_id}/web_requests/{agent_id}/{secr
  name: Huginn Web Requests API
  slug: huginn-web-requests-api
common:
- title: ''
  type: Website
  url: https://github.com/huginn/huginn
- title: ''
  type: Documentation
  url: https://github.com/huginn/huginn/wiki
- title: ''
  type: GitHub Repository
  url: https://github.com/huginn/huginn
- title: ''
  type: License
  url: https://github.com/huginn/huginn/blob/master/LICENSE
- title: ''
  type: Issues
  url: https://github.com/huginn/huginn/issues
- title: ''
  type: Rules
  url: https://raw.githubusercontent.com/api-evangelist/huginn/refs/heads/main/huginn-rules.yml
created: '2026-03-27'
description: Huginn is an open-source system for building agents that perform automated tasks online. Self-hosted agents can monitor the web, send and receive events, and trigger workflows. Each Huginn instance exposes a JSON-based HTTP interface (the Web Requests API) that lets external systems trigger scenarios and post events into the platform.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Huginn
skills: []
slug: huginn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: huginn\nname: Huginn\ndescription: >-\n  Huginn is an open-source system for building agents that perform automated\n  tasks online. Self-hosted agents can monitor the web, send and receive\n  events, and trigger workflows. Each Huginn instance exposes a JSON-based\n  HTTP interface (the Web Requests API) that lets external systems trigger\n  scenarios and post events into the platform.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agents\n  - Automation\n  - Open Source\n  - Self-Hosted\n  - Workflow Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/huginn/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: huginn:huginn-platform\n    name: Huginn Platform\n    description: >-\n      The Huginn platform is a self-hosted Ruby on Rails application that\n      orchestrates agents, scenarios, and events. Operators install and\
  \ run\n      their own instance and configure agents to consume and produce events\n      across the web.\n    humanURL: https://github.com/huginn/huginn\n    tags:\n      - Agents\n      - Self-Hosted\n      - Workflow Automation\n    properties:\n      - type: Documentation\n        url: https://github.com/huginn/huginn/wiki\n      - type: GitHub Repository\n        url: https://github.com/huginn/huginn\n      - type: Installation Guide\n        url: https://github.com/huginn/huginn/blob/master/doc/manual/installation.md\n      - type: Docker\n        url: https://hub.docker.com/r/huginn/huginn\n  - aid: huginn:huginn-web-requests-api\n    name: Huginn Web Requests API\n    description: >-\n      Each Huginn instance exposes a Web Requests endpoint that lets external\n      systems POST or GET events into a configured Webhook Agent. The endpoint\n      lives at /users/{user_id}/web_requests/{agent_id}/{secret} on the\n      operator's installed instance and is the primary inbound integration\n\
  \      surface for Huginn.\n    humanURL: https://github.com/huginn/huginn/wiki\n    tags:\n      - Agents\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://github.com/huginn/huginn/wiki\n      - type: Webhook Agent\n        url: https://github.com/huginn/huginn/blob/master/app/models/agents/webhook_agent.rb\ncommon:\n  - type: Website\n    url: https://github.com/huginn/huginn\n  - type: Documentation\n    url: https://github.com/huginn/huginn/wiki\n  - type: GitHub Repository\n    url: https://github.com/huginn/huginn\n  - type: License\n    url: https://github.com/huginn/huginn/blob/master/LICENSE\n  - type: Issues\n    url: https://github.com/huginn/huginn/issues\n  - type: Rules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/huginn/refs/heads/main/huginn-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/huginn/refs/heads/main/apis.yml
tags:
- Agents
- Automation
- Open Source
- Self-Hosted
- Workflow Automation
url: https://raw.githubusercontent.com/api-evangelist/huginn/refs/heads/main/apis.yml
use_cases: []
---
