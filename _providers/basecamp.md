---
api_count: 3
apis:
- description: The Basecamp API is a REST API providing programmatic access to Basecamp's project management platform. Manage projects, to-do lists, messages, documents, schedules, and team members. Uses OAuth 2.0 f
  name: Basecamp API
  slug: basecamp-api
- description: Basecamp Webhooks deliver real-time HTTP notifications when events occur within a project. Configure webhooks per project with an HTTPS payload URL and resource types.
  name: Basecamp Webhooks
  slug: basecamp-webhooks
- description: OAuth 2.0 authentication for Basecamp API access via the 37signals Launchpad. Register at launchpad.37signals.com for a client ID and secret, then implement the authorization code flow to obtain acces
  name: Basecamp OAuth
  slug: basecamp-oauth
asyncapis:
- description: 'The Basecamp webhook system delivers real-time HTTP notifications to registered HTTPS endpoints when events occur within a Basecamp project. Webhooks are configured per project with a payload URL and '
  name: Basecamp Webhook Events
  slug: basecamp-webhooks-asyncapi
capabilities:
- description: Basecamp project management workflow for teams, covering project creation, to-do management, messaging, scheduling, and team member management.
  name: Basecamp Project Management
  slug: project-management
common:
- title: ''
  type: Website
  url: https://basecamp.com/
- title: ''
  type: Documentation
  url: https://github.com/basecamp/bc3-api
- title: ''
  type: SignUp
  url: https://launchpad.37signals.com/
- title: ''
  type: Blog
  url: https://basecamp.com/blog
- title: ''
  type: TermsOfService
  url: https://basecamp.com/about/policies/terms
- title: ''
  type: PrivacyPolicy
  url: https://basecamp.com/about/policies/privacy
- title: ''
  type: SpectralRules
  url: rules/basecamp-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/basecamp-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/project-management.yaml
- title: ''
  type: JSON-LD
  url: json-ld/basecamp-context.jsonld
created: '2024-01-01'
description: Basecamp is a project management and team collaboration platform developed by 37signals. The Basecamp REST API (bc3-api) provides programmatic access to projects, to-do lists, messages, documents, schedules, and team members. OAuth2 authentication via the 37signals Launchpad is required. The API returns JSON and is documented on GitHub at github.com/basecamp/bc3-api.
features:
- description: Create and manage projects with team access controls.
  name: Project Management
- description: Hierarchical to-do lists with assignments, due dates, and completion tracking.
  name: To-Do Lists
- description: Threaded message boards for team discussion and announcements.
  name: Message Boards
- description: Real-time group chat within projects.
  name: Campfire Chat
- description: Project calendars with events and milestones.
  name: Schedules
- description: Document and file storage with version history.
  name: File Storage
- description: Real-time event notifications for project activity.
  name: Webhooks
- description: Full REST API with OAuth2 authentication for third-party integrations.
  name: OAuth2 API
image: ''
integrations:
- name: Zapier
- name: Make (Integromat)
- name: Slack
- name: GitHub
- name: Harvest
- name: Clockify
jsonld:
- class_count: 0
  name: Basecamp Context
  property_count: 124
  slug: basecamp-context
layout: provider
modified: '2026-04-21'
name: Basecamp
rules:
- name: Basecamp API Rules
  rule_count: 15
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 5
  slug: basecamp-spectral-rules
skills: []
slug: basecamp
solutions: []
tags:
- Collaboration
- Project Management
- REST
- SaaS
- Team Communication
url: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/apis.yml
use_cases:
- description: Track sprints, bugs, and feature development with to-do lists.
  name: Software Development
- description: Manage client deliverables, approvals, and communications.
  name: Client Projects
- description: Asynchronous team communication and project coordination.
  name: Remote Team Collaboration
- description: Automate project workflows and reporting via REST API.
  name: Project Automation
- description: Multi-client project organization for agencies and consultancies.
  name: Agency Project Management
---
