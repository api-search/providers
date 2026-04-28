---
api_count: 10
apis:
- description: The Webex Meetings API enables scheduling, updating, deleting, and listing of Webex meetings. Endpoints support recurring meetings, meeting templates, and host delegation. Authentication uses OAuth 2.
  name: Webex Meetings API
  slug: meetings-api
- description: Manage invitee lists for scheduled Webex meetings. Endpoints support adding, updating, and removing meeting invitees and bulk-inviting attendees by email.
  name: Webex Meeting Invitees API
  slug: meeting-invitees-api
- description: List and update participants in active or completed Webex meetings. Supports admin-mute, lobby admit, and participant removal operations during in-progress meetings.
  name: Webex Meeting Participants API
  slug: meeting-participants-api
- description: Manage host meeting preferences including personal room URLs, audio defaults, scheduling templates, and site preferences.
  name: Webex Meeting Preferences API
  slug: meeting-preferences-api
- description: List and manage meeting recordings. Provides access to recording details, download links, and metadata, with separate endpoints for admin and compliance officer access.
  name: Webex Recordings API
  slug: recordings-api
- description: Retrieve and manage meeting transcripts including download endpoints for VTT and TXT transcript formats. Supports compliance officer access for governance workflows.
  name: Webex Meeting Transcripts API
  slug: meeting-transcripts-api
- description: Retrieve questions and answers from Webex meetings and webinars for engagement reporting and post-event follow-up workflows.
  name: Webex Meeting Q and A API
  slug: meeting-qa-api
- description: Retrieve polls and poll responses from Webex meetings and webinars for engagement analytics and post-event reporting.
  name: Webex Meeting Polls API
  slug: meeting-polls-api
- description: Retrieve chat transcripts from completed Webex meetings for compliance and post-meeting reporting.
  name: Webex Meeting Chats API
  slug: meeting-chats-api
- description: The Webex XML API is the legacy SOAP-style interface for deep integration with Webex Meetings. It supports site administration, user provisioning, and meeting management for scenarios that pre-date th
  name: Webex XML API
  slug: webex-xml-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer.webex.com/
- title: ''
  type: Documentation
  url: https://developer.webex.com/docs/meetings
- title: ''
  type: Getting Started
  url: https://developer.webex.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.webex.com/docs/integrations
- title: ''
  type: SDKs
  url: https://developer.webex.com/docs/sdks
- title: ''
  type: Webhooks
  url: https://developer.webex.com/docs/webhooks
- title: ''
  type: Rate Limits
  url: https://developer.webex.com/docs/api-rate-limits
- title: ''
  type: Change Log
  url: https://developer.webex.com/docs/api/changelog
- title: ''
  type: Status
  url: https://status.webex.com/
- title: ''
  type: Support
  url: https://developer.webex.com/support
- title: ''
  type: Blog
  url: https://developer.webex.com/blog
- title: ''
  type: Community
  url: https://community.cisco.com/t5/webex-developers/bd-p/4416j-disc-dev-webex
- title: ''
  type: Terms of Service
  url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: JSON-LD
  url: json-ld/cisco-webex-meetings-context.jsonld
- title: ''
  type: Spectral
  url: rules/cisco-webex-meetings-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cisco-webex-meetings-capabilities.yml
created: '2024-01-01'
description: Cisco Webex Meetings is the meetings-focused subset of the Webex collaboration platform, providing scheduling, hosting, recording, transcription, and meeting administration capabilities through the Webex REST API. Authentication uses OAuth 2.0 access tokens, personal access tokens, or service apps and all endpoints respond with JSON. The legacy XML API remains available for deep integrations and enterprise scenarios that pre-date the REST surface.
features: []
image: ''
integrations: []
jsonld:
- class_count: 18
  name: Cisco Webex Meetings Context
  property_count: 0
  slug: cisco-webex-meetings-context
layout: provider
modified: '2026-04-23'
name: Cisco Webex Meetings
rules:
- name: Cisco Webex Meetings API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: cisco-webex-meetings-rules
skills: []
slug: cisco-webex-meetings
solutions: []
tags:
- Collaboration
- Communications
- Enterprise
- Meetings
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/apis.yml
use_cases: []
---
