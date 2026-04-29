---
api_count: 3
apis:
- description: The api.video Video On Demand API enables uploading, encoding, and streaming videos with automatic format conversion, thumbnail generation, and global CDN delivery. Supports resumable uploads and prog
  name: api.video Video On Demand API
  slug: video-on-demand
- description: The api.video Live Streaming API enables low-latency live video broadcasts with RTMP ingest, automatic recording, and global CDN delivery for audiences worldwide.
  name: api.video Live Streaming API
  slug: live-streaming
- description: The api.video Analytics API provides viewer engagement metrics, playback statistics, and performance data for both video on demand and live streaming content.
  name: api.video Analytics API
  slug: analytics
common:
- title: ''
  type: Website
  url: https://api.video/
- title: ''
  type: Documentation
  url: https://docs.api.video/
- title: ''
  type: GettingStarted
  url: https://docs.api.video/get-started/start-building
- title: ''
  type: StatusPage
  url: https://status.api.video
- title: ''
  type: GitHubOrganization
  url: https://github.com/ApiVideo
- title: ''
  type: Pricing
  url: https://api.video/pricing
created: '2025-03-01'
description: api.video is a video infrastructure platform offering APIs for video on demand, live streaming, analytics, and AI-powered features including transcription and summarization. It provides lightning-fast encoding, 99.999% uptime, 140+ global points of presence, and SDKs in 20+ languages for integrating video into websites, apps, and software.
features:
- description: Video encoding with 0.02s playback speed using global infrastructure.
  name: Lightning-Fast Video Encoding
- description: Enterprise-grade reliability with 99.999% uptime guarantee backed by SLA.
  name: 99.999% Uptime SLA
- description: Global CDN with 140+ PoPs and 1 Petabyte monthly traffic capacity for worldwide delivery.
  name: 140+ Global Points of Presence
- description: Automatic video transcription powered by AI for searchable captions and accessibility.
  name: AI Transcription
- description: AI-generated video summaries to help viewers navigate long-form content.
  name: AI Video Summarization
- description: Official SDKs for iOS, Android, Flutter, Java, Python, Node.js, PHP, C#, React Native, and more.
  name: 20+ SDKs
- description: Flexible usage-based pricing with volume discounts scaling with consumption.
  name: Usage-Based Pricing
- description: Reliable large file uploads with resumable upload support for videos of any size.
  name: Resumable Uploads
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: WordPress plugin for embedding and managing api.video content in WordPress sites.
  name: WordPress
- description: Integration with Contentful CMS for video asset management in headless content workflows.
  name: Contentful
- description: No-code integration with Bubble for adding video capabilities to Bubble applications.
  name: Bubble
layout: provider
modified: '2026-04-19'
name: API.Video
skills: []
slug: api-video
solutions: []
source_filename: apis.yml
source_yaml: "aid: api-video\nname: API.Video\ndescription: >-\n  api.video is a video infrastructure platform offering APIs for video on\n  demand, live streaming, analytics, and AI-powered features including\n  transcription and summarization. It provides lightning-fast encoding,\n  99.999% uptime, 140+ global points of presence, and SDKs in 20+ languages\n  for integrating video into websites, apps, and software.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Analytics\n  - CDN\n  - Encoding\n  - Live Streaming\n  - Transcription\n  - Video\n  - Video on Demand\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/api-video/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: api-video:video-on-demand\n    name: api.video Video On Demand API\n    description: >-\n      The api.video Video On Demand API enables uploading, encoding, and\n      streaming\
  \ videos with automatic format conversion, thumbnail generation,\n      and global CDN delivery. Supports resumable uploads and programmatic\n      video management.\n    humanURL: https://docs.api.video/reference\n    tags:\n      - Encoding\n      - On Demand\n      - Streaming\n      - Video\n    properties:\n      - type: Documentation\n        url: https://docs.api.video/reference\n      - type: GettingStarted\n        url: https://docs.api.video/get-started/start-building\n  - aid: api-video:live-streaming\n    name: api.video Live Streaming API\n    description: >-\n      The api.video Live Streaming API enables low-latency live video broadcasts\n      with RTMP ingest, automatic recording, and global CDN delivery for\n      audiences worldwide.\n    humanURL: https://docs.api.video/reference\n    tags:\n      - Broadcasting\n      - Live Streaming\n      - RTMP\n      - Video\n    properties:\n      - type: Documentation\n        url: https://docs.api.video/reference\n  - aid:\
  \ api-video:analytics\n    name: api.video Analytics API\n    description: >-\n      The api.video Analytics API provides viewer engagement metrics, playback\n      statistics, and performance data for both video on demand and live\n      streaming content.\n    humanURL: https://docs.api.video/reference\n    tags:\n      - Analytics\n      - Engagement\n      - Metrics\n      - Video\n    properties:\n      - type: Documentation\n        url: https://docs.api.video/reference\ncommon:\n  - type: Website\n    url: https://api.video/\n  - type: Documentation\n    url: https://docs.api.video/\n  - type: GettingStarted\n    url: https://docs.api.video/get-started/start-building\n  - type: StatusPage\n    url: https://status.api.video\n  - type: GitHubOrganization\n    url: https://github.com/ApiVideo\n  - type: Pricing\n    url: https://api.video/pricing\n  - type: Features\n    data:\n      - name: Lightning-Fast Video Encoding\n        description: Video encoding with 0.02s playback speed\
  \ using global infrastructure.\n      - name: 99.999% Uptime SLA\n        description: Enterprise-grade reliability with 99.999% uptime guarantee backed by SLA.\n      - name: 140+ Global Points of Presence\n        description: Global CDN with 140+ PoPs and 1 Petabyte monthly traffic capacity for worldwide delivery.\n      - name: AI Transcription\n        description: Automatic video transcription powered by AI for searchable captions and accessibility.\n      - name: AI Video Summarization\n        description: AI-generated video summaries to help viewers navigate long-form content.\n      - name: 20+ SDKs\n        description: Official SDKs for iOS, Android, Flutter, Java, Python, Node.js, PHP, C#, React Native, and more.\n      - name: Usage-Based Pricing\n        description: Flexible usage-based pricing with volume discounts scaling with consumption.\n      - name: Resumable Uploads\n        description: Reliable large file uploads with resumable upload support for videos of any\
  \ size.\n  - type: UseCases\n    data:\n      - name: Online Learning and Corporate Training\n        description: Host and deliver training videos with analytics to track learner engagement and completion.\n      - name: Short-Form Video Platforms\n        description: Build TikTok-style or short-form video applications with fast encoding and global delivery.\n      - name: E-Commerce Video\n        description: Add product videos and live shopping streams to e-commerce and marketplace applications.\n      - name: Communication Tools\n        description: Integrate video messaging and user-generated content into communication platforms.\n      - name: Generative AI Video Hosting\n        description: Host and stream AI-generated video content at scale with reliable infrastructure.\n  - type: Integrations\n    data:\n      - name: WordPress\n        description: WordPress plugin for embedding and managing api.video content in WordPress sites.\n      - name: Contentful\n        description:\
  \ Integration with Contentful CMS for video asset management in headless content workflows.\n      - name: Bubble\n        description: No-code integration with Bubble for adding video capabilities to Bubble applications.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/api-video/refs/heads/main/apis.yml
tags:
- AI
- Analytics
- CDN
- Encoding
- Live Streaming
- Transcription
- Video
- Video on Demand
url: https://raw.githubusercontent.com/api-evangelist/api-video/refs/heads/main/apis.yml
use_cases:
- description: Host and deliver training videos with analytics to track learner engagement and completion.
  name: Online Learning and Corporate Training
- description: Build TikTok-style or short-form video applications with fast encoding and global delivery.
  name: Short-Form Video Platforms
- description: Add product videos and live shopping streams to e-commerce and marketplace applications.
  name: E-Commerce Video
- description: Integrate video messaging and user-generated content into communication platforms.
  name: Communication Tools
- description: Host and stream AI-generated video content at scale with reliable infrastructure.
  name: Generative AI Video Hosting
---
