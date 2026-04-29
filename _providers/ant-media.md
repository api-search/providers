---
api_count: 1
apis:
- description: The Ant Media Server REST API provides programmatic access to all streaming server management functions including stream management, broadcast configuration, recording control, token authentication, c
  name: Ant Media Server REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://antmedia.io
- title: ''
  type: Documentation
  url: https://antmedia.io/docs/
- title: ''
  type: GettingStarted
  url: https://antmedia.io/docs/guides/getting-started/quick-start/
- title: ''
  type: Pricing
  url: https://antmedia.io/pricing/
- title: ''
  type: Blog
  url: https://antmedia.io/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/ant-media
- title: ''
  type: GitHubRepository
  url: https://github.com/ant-media/Ant-Media-Server
- title: ''
  type: Support
  url: https://antmedia.io/support/
- title: ''
  type: TermsOfService
  url: https://antmedia.io/terms/
- title: ''
  type: PrivacyPolicy
  url: https://antmedia.io/privacy-policy/
- title: Broadcast Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/json-schema/ant-media-broadcast-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/vocabulary/ant-media-vocabulary.yaml
created: '2025-03-01'
description: Ant Media Server is a scalable, open-source media server for ultra-low latency live streaming and WebRTC-based video applications. It supports WebRTC, RTMP, RTSP, SRT, HLS, and CMAF protocols, enabling developers to build real-time video applications with sub-second latency. Available in Community (open-source) and Enterprise editions with adaptive bitrate streaming, cloud auto-scaling, video recording, and REST API management.
features:
- description: Achieve sub-500ms latency with WebRTC-based publish and play, enabling real-time interactive video applications like auctions, gaming, and telehealth.
  name: Ultra-Low Latency WebRTC Streaming
- description: Ingest and deliver streams via RTMP, RTSP, SRT, WebRTC, HLS, CMAF, and LL-HLS, supporting a wide range of encoders and players.
  name: Multi-Protocol Support
- description: Automatically transcode streams to multiple bitrate/resolution ladders and deliver the optimal quality based on viewer bandwidth.
  name: Adaptive Bitrate Streaming
- description: Record live streams to MP4 or HLS on local disk or cloud storage, creating video-on-demand assets from live broadcasts automatically.
  name: Video Recording and VoD
- description: Deploy Ant Media Server in horizontal cluster mode with auto-scaling on AWS, Azure, GCP, and Alibaba Cloud for high-concurrency events.
  name: Cluster and Auto-Scaling
- description: Full programmatic control of streams, broadcasts, conferences, and server settings via a comprehensive REST API.
  name: REST API Management
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Ingest live streams from OBS Studio via RTMP for broadcast to WebRTC, HLS, or RTSP viewers through Ant Media Server.
  name: OBS Studio
- description: Deploy Ant Media Server clusters with auto-scaling on major cloud platforms using marketplace images and SDK integrations.
  name: AWS / Azure / GCP
- description: Integrate Zoom meetings and webinars with Ant Media Server for re-broadcasting to larger streaming audiences.
  name: Zoom
jsonld:
- class_count: 3
  name: Ant Media Context
  property_count: 14
  slug: ant-media-context
layout: provider
modified: '2026-04-19'
name: Ant Media
skills: []
slug: ant-media
solutions: []
source_filename: apis.yml
source_yaml: "name: Ant Media\ndescription: >-\n  Ant Media Server is a scalable, open-source media server for ultra-low latency\n  live streaming and WebRTC-based video applications. It supports WebRTC, RTMP,\n  RTSP, SRT, HLS, and CMAF protocols, enabling developers to build real-time\n  video applications with sub-second latency. Available in Community (open-source)\n  and Enterprise editions with adaptive bitrate streaming, cloud auto-scaling,\n  video recording, and REST API management.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/apis.yml\ncreated: \"2025-03-01\"\nmodified: \"2026-04-19\"\nspecificationVersion: '0.16'\ntags:\n  - Broadcasting\n  - Live Streaming\n  - Media\n  - Streaming\n  - Video\n  - WebRTC\napis:\n  - name: Ant Media Server REST API\n    description: >-\n      The Ant Media Server REST API provides programmatic access to all\n      streaming server\
  \ management functions including stream management,\n      broadcast configuration, recording control, token authentication,\n      cluster management, and server settings. Supports RTMP ingest, WebRTC\n      publish/play, HLS delivery, and adaptive bitrate configuration.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://antmedia.io/rest/\n    baseURL: https://your-ant-media-server:5080/WebRTCAppEE/rest/v2/\n    tags:\n      - Broadcasting\n      - HLS\n      - Live Streaming\n      - Media Server\n      - RTMP\n      - Streaming\n      - Video\n      - WebRTC\n    properties:\n      - type: Documentation\n        url: https://antmedia.io/rest/\n      - type: GettingStarted\n        url: https://antmedia.io/docs/guides/getting-started/quick-start/\n      - type: Authentication\n        url: https://antmedia.io/docs/guides/developer-sdk-and-api/rest-api-guide/\n      - type: GitHubRepository\n        url: https://github.com/ant-media/Ant-Media-Server\n\
  \      - type: SDK\n        url: https://antmedia.io/docs/guides/developer-sdk-and-api/sdk-integration/\n        title: JavaScript SDK\n      - type: SDK\n        url: https://antmedia.io/docs/guides/developer-sdk-and-api/sdk-integration/\n        title: Android SDK\n      - type: SDK\n        url: https://antmedia.io/docs/guides/developer-sdk-and-api/sdk-integration/\n        title: iOS SDK\n    contact:\n      - FN: Ant Media Support\n        url: https://antmedia.io/contact/\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n    X: apievangelist\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://antmedia.io\n  - type: Documentation\n    url: https://antmedia.io/docs/\n  - type: GettingStarted\n    url: https://antmedia.io/docs/guides/getting-started/quick-start/\n  - type: Pricing\n    url: https://antmedia.io/pricing/\n  - type: Blog\n    url: https://antmedia.io/blog/\n  - type: GitHubOrganization\n    url: https://github.com/ant-media\n\
  \  - type: GitHubRepository\n    url: https://github.com/ant-media/Ant-Media-Server\n  - type: Support\n    url: https://antmedia.io/support/\n  - type: TermsOfService\n    url: https://antmedia.io/terms/\n  - type: PrivacyPolicy\n    url: https://antmedia.io/privacy-policy/\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/json-schema/ant-media-broadcast-schema.json\n    title: Broadcast Schema\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/vocabulary/ant-media-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Ultra-Low Latency WebRTC Streaming\n        description: >-\n          Achieve sub-500ms latency with WebRTC-based publish and play,\n          enabling real-time interactive video applications like auctions,\n          gaming, and telehealth.\n      - name: Multi-Protocol Support\n        description: >-\n          Ingest and deliver streams via RTMP,\
  \ RTSP, SRT, WebRTC, HLS,\n          CMAF, and LL-HLS, supporting a wide range of encoders and players.\n      - name: Adaptive Bitrate Streaming\n        description: >-\n          Automatically transcode streams to multiple bitrate/resolution\n          ladders and deliver the optimal quality based on viewer bandwidth.\n      - name: Video Recording and VoD\n        description: >-\n          Record live streams to MP4 or HLS on local disk or cloud storage,\n          creating video-on-demand assets from live broadcasts automatically.\n      - name: Cluster and Auto-Scaling\n        description: >-\n          Deploy Ant Media Server in horizontal cluster mode with auto-scaling\n          on AWS, Azure, GCP, and Alibaba Cloud for high-concurrency events.\n      - name: REST API Management\n        description: >-\n          Full programmatic control of streams, broadcasts, conferences, and\n          server settings via a comprehensive REST API.\n  - type: UseCases\n    data:\n      -\
  \ name: Telehealth and Remote Consultations\n        description: >-\n          Enable HIPAA-compliant real-time video consultations between patients\n          and healthcare providers with sub-second latency.\n      - name: Live E-Commerce and Auctions\n        description: >-\n          Power interactive live shopping experiences and real-time bidding\n          platforms with low-latency video and chat.\n      - name: E-Learning and Virtual Classrooms\n        description: >-\n          Deliver interactive live lectures, webinars, and virtual classrooms\n          with two-way video and screen sharing.\n      - name: Gaming and Esports Broadcasting\n        description: >-\n          Broadcast gaming sessions and esports events with RTMP ingest from\n          OBS and HLS/WebRTC delivery to viewers at scale.\n      - name: Video Surveillance\n        description: >-\n          Ingest RTSP streams from IP cameras and provide browser-based\n          WebRTC viewing with recording and\
  \ motion detection.\n  - type: Integrations\n    data:\n      - name: OBS Studio\n        description: >-\n          Ingest live streams from OBS Studio via RTMP for broadcast to\n          WebRTC, HLS, or RTSP viewers through Ant Media Server.\n      - name: AWS / Azure / GCP\n        description: >-\n          Deploy Ant Media Server clusters with auto-scaling on major cloud\n          platforms using marketplace images and SDK integrations.\n      - name: Zoom\n        description: >-\n          Integrate Zoom meetings and webinars with Ant Media Server for\n          re-broadcasting to larger streaming audiences.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/apis.yml
tags:
- Broadcasting
- Live Streaming
- Media
- Streaming
- Video
- WebRTC
url: https://raw.githubusercontent.com/api-evangelist/ant-media/refs/heads/main/apis.yml
use_cases:
- description: Enable HIPAA-compliant real-time video consultations between patients and healthcare providers with sub-second latency.
  name: Telehealth and Remote Consultations
- description: Power interactive live shopping experiences and real-time bidding platforms with low-latency video and chat.
  name: Live E-Commerce and Auctions
- description: Deliver interactive live lectures, webinars, and virtual classrooms with two-way video and screen sharing.
  name: E-Learning and Virtual Classrooms
- description: Broadcast gaming sessions and esports events with RTMP ingest from OBS and HLS/WebRTC delivery to viewers at scale.
  name: Gaming and Esports Broadcasting
- description: Ingest RTSP streams from IP cameras and provide browser-based WebRTC viewing with recording and motion detection.
  name: Video Surveillance
---
