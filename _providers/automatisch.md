---
api_count: 1
apis:
- description: Automatisch exposes a REST API used by its web application for managing flows (automated workflows), connections (service credentials), users, and integrations. The API supports webhook trigger endpoi
  name: Automatisch REST API
  slug: automatisch-rest-api
common:
- title: ''
  type: Website
  url: https://automatisch.io
- title: ''
  type: Documentation
  url: https://automatisch.io/docs
- title: ''
  type: GitHubOrganization
  url: https://github.com/automatisch
- title: ''
  type: GitHubRepository
  url: https://github.com/automatisch/automatisch
- title: ''
  type: GettingStarted
  url: https://automatisch.io/docs/installation/docker
- title: ''
  type: ReleaseNotes
  url: https://github.com/automatisch/automatisch/releases
created: '2026-03-27'
description: Automatisch is an open source business automation tool and self-hosted alternative to Zapier that connects different services to automate workflows without programming knowledge. Built with JavaScript/Node.js, it supports 100+ integrations including Slack, GitHub, Gmail, PostgreSQL, and AI services. Licensed under AGPL-3.0 for the community edition, with an enterprise edition for commercial deployments.
features:
- description: Automatisch ships with over 100 pre-built connectors for popular services including Slack, Discord, GitHub, GitLab, Gmail, Google Sheets, Airtable, Notion, Trello, OpenAI, Anthropic, PostgreSQL, and many more.
  name: 100+ Built-In Integrations
- description: Deploy Automatisch on your own infrastructure using Docker Compose, keeping all workflow data and credentials under your control with no data sent to third-party cloud services.
  name: Self-Hosted Deployment
- description: Built-in webhook trigger support allows external services to trigger Automatisch flows via HTTP POST, enabling event-driven automation from any service that supports outbound webhooks.
  name: Webhook Triggers
- description: A visual drag-and-drop interface for building multi-step automation workflows connecting triggers from one service to actions in another without writing code.
  name: No-Code Workflow Builder
- description: The community edition is licensed under AGPL-3.0, allowing free use, modification, and distribution. An enterprise edition with additional features is available for commercial deployments.
  name: AGPL-3.0 Open Source
- description: Extend Automatisch by developing custom app integrations using the JavaScript SDK. Custom apps follow the same trigger/action pattern as built-in integrations.
  name: Custom App Development
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Send messages, create channels, and respond to Slack events in automated flows.
  name: Slack
- description: Trigger flows from GitHub events and create issues, PRs, and comments programmatically.
  name: GitHub
- description: Send emails and trigger flows from incoming Gmail messages.
  name: Gmail
- description: Read and write rows in Google Sheets as steps in automated workflows.
  name: Google Sheets
- description: Call OpenAI APIs (GPT, DALL-E, Whisper) as steps within Automatisch automation flows.
  name: OpenAI
- description: Query and write to PostgreSQL databases as steps in automation flows.
  name: PostgreSQL
layout: provider
modified: '2026-04-19'
name: Automatisch
skills: []
slug: automatisch
solutions: []
source_filename: apis.yml
source_yaml: "aid: automatisch\nname: Automatisch\ndescription: >-\n  Automatisch is an open source business automation tool and self-hosted alternative\n  to Zapier that connects different services to automate workflows without programming\n  knowledge. Built with JavaScript/Node.js, it supports 100+ integrations including\n  Slack, GitHub, Gmail, PostgreSQL, and AI services. Licensed under AGPL-3.0 for\n  the community edition, with an enterprise edition for commercial deployments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Workflow Automation\n  - Self-Hosted\n  - Open Source\n  - Zapier Alternative\n  - No-Code\n  - JavaScript\n  - Node.js\n  - AGPL\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/automatisch/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: automatisch:automatisch-rest-api\n    name: Automatisch REST API\n    description: >-\n\
  \      Automatisch exposes a REST API used by its web application for managing\n      flows (automated workflows), connections (service credentials), users, and\n      integrations. The API supports webhook trigger endpoints for receiving\n      events from external services and provides the backend for the Automatisch\n      UI. The API follows standard REST conventions with JSON request and response\n      bodies.\n    humanURL: https://github.com/automatisch/automatisch\n    tags:\n      - Workflow Automation\n      - Flows\n      - Connections\n      - Webhooks\n      - REST\n    properties:\n      - type: Documentation\n        url: https://automatisch.io/docs\n      - type: GettingStarted\n        url: https://automatisch.io/docs/installation/docker\n      - type: GitHubRepository\n        url: https://github.com/automatisch/automatisch\n\ncommon:\n  - type: Website\n    url: https://automatisch.io\n  - type: Documentation\n    url: https://automatisch.io/docs\n  - type: GitHubOrganization\n\
  \    url: https://github.com/automatisch\n  - type: GitHubRepository\n    url: https://github.com/automatisch/automatisch\n  - type: GettingStarted\n    url: https://automatisch.io/docs/installation/docker\n  - type: ReleaseNotes\n    url: https://github.com/automatisch/automatisch/releases\n  - type: Features\n    data:\n      - name: 100+ Built-In Integrations\n        description: >-\n          Automatisch ships with over 100 pre-built connectors for popular services\n          including Slack, Discord, GitHub, GitLab, Gmail, Google Sheets, Airtable,\n          Notion, Trello, OpenAI, Anthropic, PostgreSQL, and many more.\n      - name: Self-Hosted Deployment\n        description: >-\n          Deploy Automatisch on your own infrastructure using Docker Compose,\n          keeping all workflow data and credentials under your control with no\n          data sent to third-party cloud services.\n      - name: Webhook Triggers\n        description: >-\n          Built-in webhook trigger\
  \ support allows external services to trigger\n          Automatisch flows via HTTP POST, enabling event-driven automation\n          from any service that supports outbound webhooks.\n      - name: No-Code Workflow Builder\n        description: >-\n          A visual drag-and-drop interface for building multi-step automation\n          workflows connecting triggers from one service to actions in another\n          without writing code.\n      - name: AGPL-3.0 Open Source\n        description: >-\n          The community edition is licensed under AGPL-3.0, allowing free use,\n          modification, and distribution. An enterprise edition with additional\n          features is available for commercial deployments.\n      - name: Custom App Development\n        description: >-\n          Extend Automatisch by developing custom app integrations using the\n          JavaScript SDK. Custom apps follow the same trigger/action pattern\n          as built-in integrations.\n  - type: UseCases\n\
  \    data:\n      - name: Business Process Automation\n        description: >-\n          Automate repetitive business processes such as lead routing, support\n          ticket triage, and data synchronization between SaaS tools without\n          relying on cloud automation vendors.\n      - name: Data Privacy Compliance\n        description: >-\n          Self-host workflow automation to keep sensitive business data on-premises\n          or in private cloud infrastructure, meeting GDPR and data residency requirements.\n      - name: Developer Workflow Automation\n        description: >-\n          Automate developer workflows including GitHub issue-to-Slack notifications,\n          CI/CD status updates, and pull request review reminders.\n      - name: CRM and Marketing Automation\n        description: >-\n          Connect CRM tools with marketing platforms to automate lead nurturing,\n          email sequences, and customer data synchronization across tools.\n  - type: Integrations\n\
  \    data:\n      - name: Slack\n        description: Send messages, create channels, and respond to Slack events in automated flows.\n      - name: GitHub\n        description: Trigger flows from GitHub events and create issues, PRs, and comments programmatically.\n      - name: Gmail\n        description: Send emails and trigger flows from incoming Gmail messages.\n      - name: Google Sheets\n        description: Read and write rows in Google Sheets as steps in automated workflows.\n      - name: OpenAI\n        description: Call OpenAI APIs (GPT, DALL-E, Whisper) as steps within Automatisch automation flows.\n      - name: PostgreSQL\n        description: Query and write to PostgreSQL databases as steps in automation flows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/automatisch/refs/heads/main/apis.yml
tags:
- Workflow Automation
- Self-Hosted
- Open Source
- Zapier Alternative
- No-Code
- JavaScript
- Node.js
- AGPL
url: https://raw.githubusercontent.com/api-evangelist/automatisch/refs/heads/main/apis.yml
use_cases:
- description: Automate repetitive business processes such as lead routing, support ticket triage, and data synchronization between SaaS tools without relying on cloud automation vendors.
  name: Business Process Automation
- description: Self-host workflow automation to keep sensitive business data on-premises or in private cloud infrastructure, meeting GDPR and data residency requirements.
  name: Data Privacy Compliance
- description: Automate developer workflows including GitHub issue-to-Slack notifications, CI/CD status updates, and pull request review reminders.
  name: Developer Workflow Automation
- description: Connect CRM tools with marketing platforms to automate lead nurturing, email sequences, and customer data synchronization across tools.
  name: CRM and Marketing Automation
---
