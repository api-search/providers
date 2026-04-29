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
source_yaml: "aid: basecamp\nurl: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/apis.yml\nname: Basecamp\ntags:\n  - Collaboration\n  - Project Management\n  - REST\n  - SaaS\n  - Team Communication\nmodified: '2026-04-21'\ndescription: >-\n  Basecamp is a project management and team collaboration platform developed by 37signals.\n  The Basecamp REST API (bc3-api) provides programmatic access to projects, to-do lists,\n  messages, documents, schedules, and team members. OAuth2 authentication via the 37signals\n  Launchpad is required. The API returns JSON and is documented on GitHub at\n  github.com/basecamp/bc3-api.\napis:\n  - aid: basecamp:basecamp-api\n    name: Basecamp API\n    tags:\n      - Collaboration\n      - Project Management\n      - REST\n      - Team Communication\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://3.basecampapi.com\n    humanURL: https://github.com/basecamp/bc3-api\n  \
  \  properties:\n      - url: https://github.com/basecamp/bc3-api\n        type: Documentation\n      - url: openapi/basecamp-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Basecamp API is a REST API providing programmatic access to Basecamp's\n      project management platform. Manage projects, to-do lists, messages, documents,\n      schedules, and team members. Uses OAuth 2.0 for authentication and returns JSON.\n  - aid: basecamp:basecamp-webhooks\n    name: Basecamp Webhooks\n    tags:\n      - Events\n      - Notifications\n      - Project Management\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://3.basecampapi.com\n    humanURL: https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md\n    properties:\n      - url: https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md\n        type: Documentation\n      - url: asyncapi/basecamp-webhooks-asyncapi.yml\n\
  \        type: AsyncAPI\n    description: >-\n      Basecamp Webhooks deliver real-time HTTP notifications when events occur within\n      a project. Configure webhooks per project with an HTTPS payload URL and resource types.\n  - aid: basecamp:basecamp-oauth\n    name: Basecamp OAuth\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://launchpad.37signals.com\n    humanURL: https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md\n    properties:\n      - url: https://github.com/basecamp/bc3-api/blob/master/sections/authentication.md\n        type: Documentation\n      - url: openapi/basecamp-oauth-openapi.yml\n        type: OpenAPI\n    description: >-\n      OAuth 2.0 authentication for Basecamp API access via the 37signals Launchpad.\n      Register at launchpad.37signals.com for a client ID and secret, then implement\n\
  \      the authorization code flow to obtain access tokens.\ncommon:\n  - type: Website\n    url: https://basecamp.com/\n    name: Basecamp\n  - type: Documentation\n    url: https://github.com/basecamp/bc3-api\n    name: Basecamp API Documentation\n  - type: SignUp\n    url: https://launchpad.37signals.com/\n    name: 37signals Launchpad (App Registration)\n  - type: Blog\n    url: https://basecamp.com/blog\n    name: Basecamp Blog\n  - type: TermsOfService\n    url: https://basecamp.com/about/policies/terms\n    name: Terms of Service\n  - type: PrivacyPolicy\n    url: https://basecamp.com/about/policies/privacy\n    name: Privacy Policy\n  - type: SpectralRules\n    url: rules/basecamp-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/basecamp-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/project-management.yaml\n  - type: JSON-LD\n    url: json-ld/basecamp-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Project Management\n\
  \        description: Create and manage projects with team access controls.\n      - name: To-Do Lists\n        description: Hierarchical to-do lists with assignments, due dates, and completion tracking.\n      - name: Message Boards\n        description: Threaded message boards for team discussion and announcements.\n      - name: Campfire Chat\n        description: Real-time group chat within projects.\n      - name: Schedules\n        description: Project calendars with events and milestones.\n      - name: File Storage\n        description: Document and file storage with version history.\n      - name: Webhooks\n        description: Real-time event notifications for project activity.\n      - name: OAuth2 API\n        description: Full REST API with OAuth2 authentication for third-party integrations.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Software Development\n        description: Track sprints, bugs, and feature development with to-do lists.\n      - name:\
  \ Client Projects\n        description: Manage client deliverables, approvals, and communications.\n      - name: Remote Team Collaboration\n        description: Asynchronous team communication and project coordination.\n      - name: Project Automation\n        description: Automate project workflows and reporting via REST API.\n      - name: Agency Project Management\n        description: Multi-client project organization for agencies and consultancies.\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Zapier\n      - name: Make (Integromat)\n      - name: Slack\n      - name: GitHub\n      - name: Harvest\n      - name: Clockify\ncreated: '2024-01-01'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/apis.yml
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
