---
api_count: 6
api_specs:
- filename: zoom-api.yaml
  format: yaml
  label: Zoom API
  slug: zoom-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/zoom/api/master/openapi/zoom-api.yaml
apis:
- description: The Zoom REST API provides access to Zoom meetings, webinars, users, cloud recordings, and phone services for building Zoom integrations.
  name: Zoom API
  slug: zoom-api
- description: Microsoft Graph API for Teams provides access to teams, channels, meetings, calls, and messaging in Microsoft Teams.
  name: Microsoft Teams API
  slug: microsoft-teams-api
- description: Google Meet REST API allows developers to create and manage Meet spaces and retrieve recording artifacts.
  name: Google Meet REST API
  slug: google-meet-api
- description: Cisco Webex REST API for meetings, messaging, calling, and device management. Supports webhooks for event-driven integrations.
  name: Cisco Webex API
  slug: cisco-webex-api
- description: Daily.co REST API for creating and managing video call rooms, recording, and participant management using WebRTC.
  name: Daily.co API
  slug: daily-co-api
- description: European-hosted video conferencing REST API for creating rooms, managing access, and embedding video calls. GDPR-compliant with data stored in Europe.
  name: Digital Samba Embedded API
  slug: digital-samba-api
common:
- title: ''
  type: Website
  url: https://en.wikipedia.org/wiki/Videotelephony
- title: ''
  type: JSONSchema
  url: json-schema/visioconference-meeting-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/visioconference-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/visioconference-vocabulary.yml
created: '2024-01-15'
description: Visioconference (video conferencing) is a category of communication technology enabling real-time visual and audio communication between remote participants. This repository profiles the video conferencing API ecosystem including leading providers such as Zoom, Microsoft Teams, Google Meet, Webex, Digital Samba, VideoSDK, Daily.co, and others offering REST APIs for embedding and managing video conferencing functionality. The term "visioconference" is commonly used in French-speaking contexts.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Visioconference Context
  property_count: 27
  slug: visioconference-context
layout: provider
modified: '2026-05-03'
name: Visioconference
skills: []
slug: visioconference
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: visioconference\nname: Visioconference\ndescription: >-\n  Visioconference (video conferencing) is a category of communication technology\n  enabling real-time visual and audio communication between remote participants.\n  This repository profiles the video conferencing API ecosystem including leading\n  providers such as Zoom, Microsoft Teams, Google Meet, Webex, Digital Samba,\n  VideoSDK, Daily.co, and others offering REST APIs for embedding and managing\n  video conferencing functionality. The term \"visioconference\" is commonly used\n  in French-speaking contexts.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Audio\n  - Chat\n  - Collaboration\n  - Communication\n  - Conferencing\n  - Live Streaming\n  - Real-Time\n  - Remote Work\n  - Screen Sharing\n  - Video\n  - WebRTC\ncreated: '2024-01-15'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/visioconference/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: visioconference:zoom-api\n    name: Zoom API\n    description: >-\n      The Zoom REST API provides access to Zoom meetings, webinars, users,\n      cloud recordings, and phone services for building Zoom integrations.\n    humanURL: https://developers.zoom.us/\n    tags:\n      - Video Conferencing\n      - Meetings\n      - Webinars\n    properties:\n      - type: Documentation\n        url: https://developers.zoom.us/docs/api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/zoom/api/master/openapi/zoom-api.yaml\n  - aid: visioconference:microsoft-teams-api\n    name: Microsoft Teams API\n    description: >-\n      Microsoft Graph API for Teams provides access to teams, channels, meetings,\n      calls, and messaging in Microsoft Teams.\n    humanURL: https://learn.microsoft.com/en-us/graph/teams-concept-overview\n    tags:\n      - Video Conferencing\n      - Meetings\n      - Collaboration\n      - Microsoft\n    properties:\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/teams-concept-overview\n  - aid: visioconference:google-meet-api\n    name: Google Meet REST API\n    description: >-\n      Google Meet REST API allows developers to create and manage Meet spaces\n      and retrieve recording artifacts.\n    humanURL: https://developers.google.com/meet/api\n    tags:\n      - Video Conferencing\n      - Meetings\n      - Google\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/meet/api\n  - aid: visioconference:cisco-webex-api\n    name: Cisco Webex API\n    description: >-\n      Cisco Webex REST API for meetings, messaging, calling, and device management.\n      Supports webhooks for event-driven integrations.\n    humanURL: https://developer.webex.com/\n    tags:\n      - Video Conferencing\n      - Meetings\n      - Cisco\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/getting-started\n\
  \  - aid: visioconference:daily-co-api\n    name: Daily.co API\n    description: >-\n      Daily.co REST API for creating and managing video call rooms, recording,\n      and participant management using WebRTC.\n    humanURL: https://docs.daily.co/reference\n    tags:\n      - Video Conferencing\n      - WebRTC\n      - Rooms\n    properties:\n      - type: Documentation\n        url: https://docs.daily.co/reference\n  - aid: visioconference:digital-samba-api\n    name: Digital Samba Embedded API\n    description: >-\n      European-hosted video conferencing REST API for creating rooms, managing\n      access, and embedding video calls. GDPR-compliant with data stored in Europe.\n    humanURL: https://digitalsamba.com/\n    tags:\n      - Video Conferencing\n      - WebRTC\n      - GDPR\n      - European\n    properties:\n      - type: Documentation\n        url: https://digitalsamba.com/video-api\ncommon:\n  - type: Website\n    url: https://en.wikipedia.org/wiki/Videotelephony\n  -\
  \ type: JSONSchema\n    url: json-schema/visioconference-meeting-schema.json\n  - type: JSON-LD\n    url: json-ld/visioconference-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/visioconference-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visioconference/refs/heads/main/apis.yml
tags:
- Audio
- Chat
- Collaboration
- Communication
- Conferencing
- Live Streaming
- Real-Time
- Remote Work
- Screen Sharing
- Video
- WebRTC
url: https://raw.githubusercontent.com/api-evangelist/visioconference/refs/heads/main/apis.yml
use_cases: []
---
