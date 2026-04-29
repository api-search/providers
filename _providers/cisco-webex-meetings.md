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
source_filename: apis.yml
source_yaml: "aid: cisco-webex-meetings\nname: Cisco Webex Meetings\nurl: https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Collaboration\n  - Communications\n  - Enterprise\n  - Meetings\n  - Video Conferencing\ndescription: >-\n  Cisco Webex Meetings is the meetings-focused subset of the Webex\n  collaboration platform, providing scheduling, hosting, recording,\n  transcription, and meeting administration capabilities through the\n  Webex REST API. Authentication uses OAuth 2.0 access tokens, personal\n  access tokens, or service apps and all endpoints respond with JSON.\n  The legacy XML API remains available for deep integrations and\n  enterprise scenarios that pre-date the REST surface.\napis:\n  - aid: cisco-webex-meetings:meetings-api\n    name: Webex Meetings API\n    tags:\n      - Conferencing\n\
  \      - Meetings\n      - Scheduling\n      - Video\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/meetings\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meetings\n        type: Documentation\n      - url: https://developer.webex.com/docs/getting-started#accounts-and-authentication\n        type: Authentication\n    description: >-\n      The Webex Meetings API enables scheduling, updating, deleting, and\n      listing of Webex meetings. Endpoints support recurring meetings,\n      meeting templates, and host delegation. Authentication uses OAuth\n      2.0 bearer tokens or personal access tokens.\n  - aid: cisco-webex-meetings:meeting-invitees-api\n    name: Webex Meeting Invitees API\n    tags:\n      - Attendees\n      - Invitees\n      - Meetings\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/meeting-invitees\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meeting-invitees\n        type: Documentation\n    description: >-\n      Manage invitee lists for scheduled Webex meetings. Endpoints\n      support adding, updating, and removing meeting invitees and\n      bulk-inviting attendees by email.\n  - aid: cisco-webex-meetings:meeting-participants-api\n    name: Webex Meeting Participants API\n    tags:\n      - Attendees\n      - Participants\n      - Real-Time\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/meeting-participants\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meeting-participants\n        type: Documentation\n    description: >-\n      List and update participants in active or completed Webex\n\
  \      meetings. Supports admin-mute, lobby admit, and participant\n      removal operations during in-progress meetings.\n  - aid: cisco-webex-meetings:meeting-preferences-api\n    name: Webex Meeting Preferences API\n    tags:\n      - Personal Room\n      - Preferences\n      - Settings\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/meeting-preferences\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meeting-preferences\n        type: Documentation\n    description: >-\n      Manage host meeting preferences including personal room URLs,\n      audio defaults, scheduling templates, and site preferences.\n  - aid: cisco-webex-meetings:recordings-api\n    name: Webex Recordings API\n    tags:\n      - Compliance\n      - Media\n      - Recordings\n      - Storage\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/recordings\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/recordings\n        type: Documentation\n    description: >-\n      List and manage meeting recordings. Provides access to recording\n      details, download links, and metadata, with separate endpoints\n      for admin and compliance officer access.\n  - aid: cisco-webex-meetings:meeting-transcripts-api\n    name: Webex Meeting Transcripts API\n    tags:\n      - Accessibility\n      - AI\n      - Captions\n      - Transcripts\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/meeting-transcripts\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meeting-transcripts\n        type: Documentation\n    description: >-\n      Retrieve and manage meeting transcripts including\
  \ download\n      endpoints for VTT and TXT transcript formats. Supports compliance\n      officer access for governance workflows.\n  - aid: cisco-webex-meetings:meeting-qa-api\n    name: Webex Meeting Q and A API\n    tags:\n      - Engagement\n      - Q and A\n      - Webinars\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/meeting-qanda\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meeting-qanda\n        type: Documentation\n    description: >-\n      Retrieve questions and answers from Webex meetings and webinars\n      for engagement reporting and post-event follow-up workflows.\n  - aid: cisco-webex-meetings:meeting-polls-api\n    name: Webex Meeting Polls API\n    tags:\n      - Engagement\n      - Polls\n      - Surveys\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://webexapis.com/v1\n\
  \    humanURL: https://developer.webex.com/docs/api/v1/meeting-polls\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meeting-polls\n        type: Documentation\n    description: >-\n      Retrieve polls and poll responses from Webex meetings and\n      webinars for engagement analytics and post-event reporting.\n  - aid: cisco-webex-meetings:meeting-chats-api\n    name: Webex Meeting Chats API\n    tags:\n      - Chat\n      - Compliance\n      - Meetings\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://webexapis.com/v1\n    humanURL: https://developer.webex.com/docs/api/v1/meeting-chats\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/meeting-chats\n        type: Documentation\n    description: >-\n      Retrieve chat transcripts from completed Webex meetings for\n      compliance and post-meeting reporting.\n  - aid: cisco-webex-meetings:webex-xml-api\n    name: Webex XML API\n  \
  \  tags:\n      - Enterprise\n      - Legacy\n      - SOAP\n      - XML\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/docs/webex-xml-api-reference-guide/\n    properties:\n      - url: https://developer.cisco.com/docs/webex-xml-api-reference-guide/\n        type: Documentation\n    description: >-\n      The Webex XML API is the legacy SOAP-style interface for deep\n      integration with Webex Meetings. It supports site administration,\n      user provisioning, and meeting management for scenarios that\n      pre-date the REST API.\ncommon:\n  - type: Portal\n    url: https://developer.webex.com/\n  - type: Documentation\n    url: https://developer.webex.com/docs/meetings\n  - type: Getting Started\n    url: https://developer.webex.com/docs/getting-started\n  - type: Authentication\n    url: https://developer.webex.com/docs/integrations\n  - type: SDKs\n    url: https://developer.webex.com/docs/sdks\n\
  \  - type: Webhooks\n    url: https://developer.webex.com/docs/webhooks\n  - type: Rate Limits\n    url: https://developer.webex.com/docs/api-rate-limits\n  - type: Change Log\n    url: https://developer.webex.com/docs/api/changelog\n  - type: Status\n    url: https://status.webex.com/\n  - type: Support\n    url: https://developer.webex.com/support\n  - type: Blog\n    url: https://developer.webex.com/blog\n  - type: Community\n    url: https://community.cisco.com/t5/webex-developers/bd-p/4416j-disc-dev-webex\n  - type: Terms of Service\n    url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html\n  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: JSON-LD\n    url: json-ld/cisco-webex-meetings-context.jsonld\n  - type: Spectral\n    url: rules/cisco-webex-meetings-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cisco-webex-meetings-capabilities.yml\nmaintainers:\n  - FN: Kin\
  \ Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/apis.yml
tags:
- Collaboration
- Communications
- Enterprise
- Meetings
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/apis.yml
use_cases: []
---
