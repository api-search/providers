---
api_count: 1
apis:
- description: The OpenMeetings REST API provides endpoints for managing rooms, users, recordings, calendars, and file uploads, with SOAP API support for legacy integrations and plugin APIs for LMS integration (Mood
  name: Apache OpenMeetings REST API
  slug: apache-openmeetings-rest-api
capabilities:
- description: Unified workflow capability for managing web conferencing sessions, users, rooms, recordings, and calendars in Apache OpenMeetings.
  name: Apache OpenMeetings Conferencing Workflow
  slug: conferencing-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/openmeetings
- title: ''
  type: Documentation
  url: https://openmeetings.apache.org/
- title: ''
  type: GettingStarted
  url: https://openmeetings.apache.org/installation.html
- title: ''
  type: SpectralRules
  url: rules/apache-openmeetings-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-openmeetings-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/conferencing-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-openmeetings-context.jsonld
created: '2026-03-16'
description: Apache OpenMeetings is a web conferencing and collaboration tool that provides video conferencing, instant messaging, white board, collaborative document editing, and other groupware tools. It offers integration APIs for LMS platforms.
features:
- description: HTML5-based audio/video conferencing with multi-resolution camera support
  name: Video Conferencing
- description: Full screen sharing and recording capabilities
  name: Screen Sharing
- description: Multi-instance collaborative whiteboard with document import
  name: Whiteboard
- description: Advanced file explorer with drag-and-drop for private and public drives
  name: File Management
- description: Meeting planning with email invitations and secure hash links
  name: Calendar Integration
- description: Session recording to MP4 with audio and video capture
  name: Recording
- description: Full REST API for programmatic management of rooms, users, and recordings
  name: REST API
- description: Legacy SOAP API for integrations requiring XML-based communication
  name: SOAP API
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Moodle plugin for LMS integration
  name: Moodle
- description: Sakai CLE integration for academic conferencing
  name: Sakai
- description: Enterprise authentication via LDAP and ADS
  name: LDAP/Active Directory
- description: Social login via OAuth2 providers
  name: OAuth2
- description: VoIP integration via Asterisk for phone conferencing
  name: Asterisk/VoIP
- description: Calendar synchronization via CalDAV protocol
  name: CalDAV
- description: WebRTC media server for streaming and recording
  name: Kurento Media Server
jsonld:
- class_count: 32
  name: Apache Openmeetings Context
  property_count: 105
  slug: apache-openmeetings-context
layout: provider
modified: '2026-04-19'
name: Apache OpenMeetings
rules:
- name: Apache OpenMeetings API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 4
  slug: apache-openmeetings-spectral-rules
skills: []
slug: apache-openmeetings
solutions: []
tags:
- Collaboration
- Video Conferencing
- Web Conferencing
- Whiteboard
- Apache
- Open Source
- Conferencing
url: https://raw.githubusercontent.com/api-evangelist/apache-openmeetings/refs/heads/main/apis.yml
use_cases:
- description: Integrate OpenMeetings with Moodle, Sakai, and other LMS platforms
  name: LMS Integration
- description: Host virtual meetings and webinars for distributed teams
  name: Corporate Conferencing
- description: Deliver interactive online courses with whiteboard and screen sharing
  name: Remote Education
- description: Build branded conferencing portals using the REST API
  name: Custom Conferencing Portal
---
