---
api_count: 19
apis:
- description: Enables scheduling, managing, and controlling Webex meetings programmatically. Provides endpoints for creating meetings, managing attendees, preferences, and retrieving meeting details.
  name: Webex Meetings API
  slug: webex-meetings-api
- description: Send and receive messages, manage spaces and teams, and share files within the Webex messaging platform. Supports rich text, file attachments, and adaptive cards.
  name: Webex Messaging API
  slug: webex-messaging-api
- description: Access user profile information, manage contacts, and administer user accounts within an organization. Supports listing, creating, updating, and deleting people records.
  name: Webex People API
  slug: webex-people-api
- description: Create and manage teams and team memberships within Webex. Teams group people and spaces together for organized collaboration across projects and departments.
  name: Webex Teams API
  slug: webex-teams-api
- description: Create and manage Webex spaces (rooms) for collaboration. Rooms are virtual meeting places where people post messages and collaborate, and can be organized within teams.
  name: Webex Rooms API
  slug: webex-rooms-api
- description: Register webhooks to receive real-time HTTP callbacks when specific events occur in Webex. Supports filtering by resource type, event type, and other criteria for efficient event-driven integrations.
  name: Webex Webhooks API
  slug: webex-webhooks-api
- description: Manage and control Webex devices and room systems. Provides endpoints for listing, creating, and managing device configurations, activations, and workspace assignments.
  name: Webex Devices API
  slug: webex-devices-api
- description: Manage room memberships representing a person's relationship to a room. Use this API to list members of any room, create memberships to invite users, and update or remove memberships.
  name: Webex Memberships API
  slug: webex-memberships-api
- description: Manage team memberships representing a person's relationship to a team. Use this API to add and remove people from teams and manage team membership roles.
  name: Webex Team Memberships API
  slug: webex-team-memberships-api
- description: Access events representing activities within a Webex organization such as message posts, file shares, and membership changes. Provides a historical log of activities for compliance and auditing purpos
  name: Webex Events API
  slug: webex-events-api
- description: List and manage meeting recordings. Provides access to recording details, download links, and metadata. Includes separate endpoints for admin and compliance officer access with extended filtering capa
  name: Webex Recordings API
  slug: webex-recordings-api
- description: Control active calls in Webex Calling including dial, answer, hold, transfer, and pickup operations. Supports third-party call control for building custom calling experiences and integrations.
  name: Webex Call Controls API
  slug: webex-call-controls-api
- description: Create and retrieve attachment actions for adaptive card interactions. Used with Buttons and Cards to capture user input from interactive card elements submitted in Webex messaging spaces.
  name: Webex Attachment Actions API
  slug: webex-attachment-actions-api
- description: Retrieve organization details for Webex administration. Provides access to organization-level information and settings, available only to organization administrators.
  name: Webex Organizations API
  slug: webex-organizations-api
- description: Manage and retrieve Webex licenses for an organization. Provides endpoints to list available licenses, view license details, and assign or modify license allocations for users.
  name: Webex Licenses API
  slug: webex-licenses-api
- description: Retrieve roles available within a Webex organization. Roles define the level of access and permissions granted to users, such as full administrator or read-only administrator.
  name: Webex Roles API
  slug: webex-roles-api
- description: Manage workspaces representing physical locations with Webex devices. Provides endpoints to create, list, update, and delete workspaces and manage their associated device configurations.
  name: Webex Workspaces API
  slug: webex-workspaces-api
- description: Access admin audit events for tracking administrative actions performed in Webex Control Hub. Available to full administrators for compliance monitoring and security auditing purposes.
  name: Webex Admin Audit Events API
  slug: webex-admin-audit-events-api
- description: Access converged recording capabilities across Webex Meetings and Webex Calling. Provides unified endpoints for listing, retrieving, and managing recordings from multiple Webex services.
  name: Webex Converged Recordings API
  slug: webex-converged-recordings-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer.webex.com
- title: ''
  type: Documentation
  url: https://developer.webex.com/docs/basics
- title: ''
  type: Getting Started
  url: https://developer.webex.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.webex.com/docs/getting-started#authentication
- title: ''
  type: SDKs
  url: https://developer.webex.com/docs/sdks
- title: ''
  type: Change Log
  url: https://developer.webex.com/docs/api/changelog
- title: ''
  type: Blog
  url: https://developer.webex.com/blog
- title: ''
  type: Support
  url: https://developer.webex.com/support
- title: ''
  type: Status
  url: https://status.webex.com
- title: ''
  type: Rate Limits
  url: https://developer.webex.com/docs/api-rate-limits
- title: ''
  type: Community
  url: https://community.cisco.com/t5/webex-developers/bd-p/4416j-disc-dev-webex
- title: ''
  type: Terms of Service
  url: https://developer.webex.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: GitHub Organization
  url: https://github.com/webex
- title: ''
  type: Website
  url: https://www.webex.com
- title: ''
  type: Login
  url: https://developer.webex.com/login
- title: ''
  type: Sign Up
  url: https://developer.webex.com/signup
- title: ''
  type: JSON-LD Context
  url: json-ld/cisco-webex-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/
- title: ''
  type: Spectral
  url: rules/cisco-webex-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cisco-webex-capabilities.yml
created: '2024-01-01'
description: Cisco Webex is a comprehensive collaboration platform that provides video conferencing, team messaging, file sharing, and calling capabilities for businesses and teams. The Webex developer platform offers REST APIs, SDKs, and integrations for extending and automating collaboration workflows across meetings, messaging, calling, devices, administration, and contact center scenarios. Authentication uses OAuth 2.0 access tokens, personal access tokens, or service apps and all endpoints are served from the webexapis.com base.
features: []
image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Cisco Webex Context
  property_count: 14
  slug: cisco-webex-context
layout: provider
modified: '2026-04-23'
name: Cisco Webex
rules:
- name: Cisco Webex API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: cisco-webex-rules
skills: []
slug: cisco-webex
solutions: []
tags:
- Collaboration
- Communications
- Meetings
- Messaging
- Teams
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/apis.yml
use_cases: []
---
