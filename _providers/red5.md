---
api_count: 8
api_specs:
- filename: red5-server-api-openapi.yml
  format: yaml
  label: Red5 Pro Server API
  slug: server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-server-api-openapi.yml
- filename: red5-stream-manager-2-openapi.yml
  format: yaml
  label: Red5 Pro Stream Manager 2.0 API
  slug: stream-manager-2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-stream-manager-2-openapi.yml
- filename: red5-brew-mixer-api-openapi.yml
  format: yaml
  label: Red5 Pro Brew Mixer API
  slug: brew-mixer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-brew-mixer-api-openapi.yml
- filename: red5-restreamer-api-openapi.yml
  format: yaml
  label: Red5 Pro Restreamer API
  slug: restreamer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/openapi/red5-restreamer-api-openapi.yml
- filename: red5-webrtc-streaming-asyncapi.yml
  format: yaml
  label: Red5 Pro WebRTC SDK
  slug: webrtc-sdk
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/asyncapi/red5-webrtc-streaming-asyncapi.yml
apis:
- description: The Red5 Pro Server API is an HTTP-based REST API for gathering server, application, client, and stream statistics from a running Red5 Pro instance. It exposes endpoints for server health checks, appl
  name: Red5 Pro Server API
  slug: server-api
- description: The Red5 Pro Stream Manager 2.0 API orchestrates autoscaling clusters of Red5 Pro streaming nodes across cloud infrastructure. It provides REST endpoints for managing live stream publishing and playba
  name: Red5 Pro Stream Manager 2.0 API
  slug: stream-manager-2-api
- description: The Red5 Pro Brew Mixer API is a REST interface for the Cauldron Media Engine that enables dynamic composition of multiple live video and audio streams into a single mixed output stream. It supports c
  name: Red5 Pro Brew Mixer API
  slug: brew-mixer-api
- description: The Red5 Pro Restreamer API controls live stream retransmission to external RTMP, RTMPS, SRT, and Zixi destinations including social media platforms like Facebook, YouTube, and Twitch. It accepts JSON
  name: Red5 Pro Restreamer API
  slug: restreamer-api
- description: The Red5 Pro WebRTC SDK is a JavaScript library for integrating low-latency live streaming publish and subscribe capabilities into web applications. It supports WHIP for WebRTC publishing and WHEP for
  name: Red5 Pro WebRTC SDK
  slug: webrtc-sdk
- description: 'The Red5 Core SDK is a native client library for building real-time streaming applications on Linux, Windows, and macOS desktop platforms. It offers interfaces for server connection management, media '
  name: Red5 Core SDK
  slug: core-sdk
- description: The Red5 Pro iOS Streaming SDK is a native iOS library for integrating real-time live streaming publish and subscribe capabilities into iOS applications. It supports H.264 video and AAC/Opus audio enc
  name: Red5 Pro iOS Streaming SDK
  slug: ios-sdk
- description: The Red5 Pro Android Streaming SDK is a native Android library for integrating real-time live streaming publish and subscribe capabilities into Android applications. It supports H.264/H.265 video enco
  name: Red5 Pro Android Streaming SDK
  slug: android-sdk
asyncapis:
- description: AsyncAPI specification for the Red5 Pro WebRTC streaming event system, covering WebSocket signaling messages exchanged during publish and subscribe sessions. Red5 Pro WebRTC uses WebSocket connections
  name: Red5 Pro WebRTC Streaming Events
  slug: red5-webrtc-streaming-asyncapi
capabilities:
- description: Unified capability for managing live streaming infrastructure on Red5 Pro. Combines the Server API for node-level stream monitoring and control with the Stream Manager 2.0 API for autoscaled cluster o
  name: Red5 Live Streaming Management
  slug: live-streaming
common:
- title: ''
  type: Website
  url: https://www.red5.net/
- title: ''
  type: Documentation
  url: https://www.red5.net/docs/red5-pro/
- title: ''
  type: GitHub Organization
  url: https://github.com/red5pro
- title: ''
  type: GitHub Organization
  url: https://github.com/Red5
- title: ''
  type: SDKs
  url: https://www.red5.net/live-streaming-sdks/
- title: ''
  type: Pricing
  url: https://www.red5.net/pricing/
- title: ''
  type: Blog
  url: https://www.red5.net/blog/
- title: ''
  type: Contact
  url: https://www.red5.net/contact/
- title: ''
  type: JSONLDContext
  url: json-ld/red5-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/red5-stream-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/red5-restream-provision-schema.json
- title: ''
  type: OpenAPI
  url: openapi/red5-server-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red5-stream-manager-2-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red5-brew-mixer-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red5-restreamer-api-openapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/red5-webrtc-streaming-asyncapi.yml
- title: ''
  type: JSONStructure
  url: json-structure/red5-stream-structure.json
- title: ''
  type: SpectralRuleset
  url: rules/red5-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/live-streaming.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/red5-vocabulary.yml
created: '2026-03-01'
description: Red5 provides real-time streaming infrastructure for live video and audio delivery at scale. The Red5 Pro platform includes a media server, Stream Manager 2.0 for autoscaling cloud deployments, the Brew Mixer for composite stream production, a Restreamer for pushing live streams to social media and RTMP destinations, and WebRTC and native SDKs for browser and mobile integration. Red5 APIs enable programmatic management of streams, mixers, restreaming, cluster orchestration, and node monitoring. Use cases include live events, sports broadcasting, interactive video, gaming, surveillance, and enterprise communications requiring ultra-low latency streaming.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Red5 Context
  property_count: 9
  slug: red5-context
layout: provider
modified: '2026-05-02'
name: Red5
rules:
- name: Red5 API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 8
  slug: red5-rules
skills: []
slug: red5
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: red5\nname: Red5\ndescription: >-\n  Red5 provides real-time streaming infrastructure for live video and audio\n  delivery at scale. The Red5 Pro platform includes a media server, Stream\n  Manager 2.0 for autoscaling cloud deployments, the Brew Mixer for composite\n  stream production, a Restreamer for pushing live streams to social media and\n  RTMP destinations, and WebRTC and native SDKs for browser and mobile\n  integration. Red5 APIs enable programmatic management of streams, mixers,\n  restreaming, cluster orchestration, and node monitoring. Use cases include\n  live events, sports broadcasting, interactive video, gaming, surveillance,\n  and enterprise communications requiring ultra-low latency streaming.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Live Streaming\n  - Media\n  - Real-Time\n  - RTMP\n  - Streaming\n  - Video\n  - WebRTC\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/apis.yml\n\
  created: '2026-03-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: red5:server-api\n    name: Red5 Pro Server API\n    description: >-\n      The Red5 Pro Server API is an HTTP-based REST API for gathering server,\n      application, client, and stream statistics from a running Red5 Pro instance.\n      It exposes endpoints for server health checks, application scope statistics,\n      active stream enumeration and control, connection management, and log access.\n      The API uses token-based authentication via the accessToken parameter and\n      is accessible at port 5080 on any Red5 Pro server deployment. Developers\n      can use it to monitor and manage live streaming infrastructure programmatically.\n    humanURL: https://www.red5.net/docs/red5-pro/development/api/server/red5-pro-server-api-overview/\n    baseURL: http://localhost:5080/api/v1\n    tags:\n      - Media\n      - Real-Time\n      - REST\n      - Server Management\n      - Streaming\n    properties:\n\
  \      - type: Documentation\n        url: https://www.red5.net/docs/red5-pro/development/api/server/red5-pro-server-api-overview/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/api/server/red5-pro-server-api/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/api/server/red5-pro-server-applications-api/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/api/server/red5-pro-server-streams-api/\n      - type: OpenAPI\n        url: openapi/red5-server-api-openapi.yml\n\n  - aid: red5:stream-manager-2-api\n    name: Red5 Pro Stream Manager 2.0 API\n    description: >-\n      The Red5 Pro Stream Manager 2.0 API orchestrates autoscaling clusters of\n      Red5 Pro streaming nodes across cloud infrastructure. It provides REST\n      endpoints for managing live stream publishing and playback sessions,\n      provisioning stream configurations, monitoring node metrics, managing\n\
  \      cluster node lifecycles, and proxying WHIP and WHEP WebRTC connections.\n      The API supports dynamic scaling of streaming capacity and is documented\n      with an interactive Swagger UI available on each Stream Manager deployment.\n    humanURL: https://www.red5.net/docs/red5-pro/development/api/stream-manager-2-0/\n    baseURL: https://streammanager.example.com/as/v1\n    tags:\n      - Autoscaling\n      - Cluster Management\n      - Media\n      - REST\n      - Streaming\n      - WebRTC\n      - WHEP\n      - WHIP\n    properties:\n      - type: Documentation\n        url: https://www.red5.net/docs/red5-pro/development/api/stream-manager-2-0/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/api/stream-manager-2-0/stream-manager-2-streams-api/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/api/stream-manager-2-0/stream-manager-2-admin-api/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/api/stream-manager-2-0/stream-manager-2-proxy-api/\n\
  \      - type: OpenAPI\n        url: openapi/red5-stream-manager-2-openapi.yml\n\n  - aid: red5:brew-mixer-api\n    name: Red5 Pro Brew Mixer API\n    description: >-\n      The Red5 Pro Brew Mixer API is a REST interface for the Cauldron Media\n      Engine that enables dynamic composition of multiple live video and audio\n      streams into a single mixed output stream. It supports creating and\n      managing mixers, controlling input sources and layout, configuring\n      composite output parameters, and producing mixed streams suitable for\n      broadcasting. The Brew Mixer is used for multi-presenter live events\n      and production-quality stream composition.\n    humanURL: https://www.red5.net/docs/red5-pro/development/api/mixer/brew-mixer-api/\n    baseURL: https://api.example.com/brewmixer/2.0\n    tags:\n      - Audio\n      - Composition\n      - Media\n      - Mixing\n      - REST\n      - Streaming\n      - Video\n    properties:\n      - type: Documentation\n        url:\
  \ https://www.red5.net/docs/red5-pro/development/api/mixer/brew-mixer-api/\n      - type: OpenAPI\n        url: openapi/red5-brew-mixer-api-openapi.yml\n\n  - aid: red5:restreamer-api\n    name: Red5 Pro Restreamer API\n    description: >-\n      The Red5 Pro Restreamer API controls live stream retransmission to external\n      RTMP, RTMPS, SRT, and Zixi destinations including social media platforms\n      like Facebook, YouTube, and Twitch. It accepts JSON-based provisions via\n      POST requests to configure push and pull restreaming sessions from a Red5\n      Pro server. The API supports file-based pseudo-live restreaming of FLV and\n      MP4 files as well as real-time forwarding of live ingest streams.\n    humanURL: https://www.red5.net/docs/red5-pro/development/api/restreamer/\n    baseURL: https://api.example.com\n    tags:\n      - Media\n      - REST\n      - Restreaming\n      - RTMP\n      - Social Media\n      - Streaming\n    properties:\n      - type: Documentation\n \
  \       url: https://www.red5.net/docs/red5-pro/development/api/restreamer/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/api/restreamer/red5-pro-restreamer-api-rtmp/\n      - type: OpenAPI\n        url: openapi/red5-restreamer-api-openapi.yml\n\n  - aid: red5:webrtc-sdk\n    name: Red5 Pro WebRTC SDK\n    description: >-\n      The Red5 Pro WebRTC SDK is a JavaScript library for integrating low-latency\n      live streaming publish and subscribe capabilities into web applications. It\n      supports WHIP for WebRTC publishing and WHEP for WebRTC playback, enabling\n      sub-second latency streaming directly in the browser without plugins. The\n      SDK provides APIs for managing stream sessions, configuring media constraints,\n      handling connection lifecycle events, and interacting with Stream Manager for\n      scalable deployments.\n    humanURL: https://www.red5.net/docs/red5-pro/development/sdks/red5-webrtc-sdk/\n    baseURL: https://api.example.com\n\
  \    tags:\n      - JavaScript\n      - Media\n      - SDK\n      - Streaming\n      - WebRTC\n      - WHEP\n      - WHIP\n    properties:\n      - type: Documentation\n        url: https://www.red5.net/docs/red5-pro/development/sdks/red5-webrtc-sdk/\n      - type: APIReference\n        url: https://www.red5.net/docs/red5-pro/development/sdks/red5-webrtc-sdk/red5-webrtc-sdk-api-documentation/\n      - type: GitHub\n        url: https://github.com/red5pro/red5pro-webrtc-sdk\n      - type: NPM\n        url: https://www.npmjs.com/package/red5pro-webrtc-sdk\n      - type: AsyncAPI\n        url: asyncapi/red5-webrtc-streaming-asyncapi.yml\n\n  - aid: red5:core-sdk\n    name: Red5 Core SDK\n    description: >-\n      The Red5 Core SDK is a native client library for building real-time\n      streaming applications on Linux, Windows, and macOS desktop platforms.\n      It offers interfaces for server connection management, media capture and\n      processing, audio and video source configuration,\
  \ renderer control, and\n      integration with Stream Manager for autoscaled deployments. Bindings are\n      available for C++, Python, and other native environments.\n    humanURL: https://www.red5.net/docs/red5-pro/development/sdks/red5-core-sdk/\n    baseURL: https://api.example.com\n    tags:\n      - Desktop\n      - Linux\n      - Media\n      - Native\n      - SDK\n      - Streaming\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://www.red5.net/docs/red5-pro/development/sdks/red5-core-sdk/\n      - type: SDKs\n        url: https://www.red5.net/live-streaming-sdks/\n\n  - aid: red5:ios-sdk\n    name: Red5 Pro iOS Streaming SDK\n    description: >-\n      The Red5 Pro iOS Streaming SDK is a native iOS library for integrating\n      real-time live streaming publish and subscribe capabilities into iOS\n      applications. It supports H.264 video and AAC/Opus audio encoding,\n      WebRTC-based streaming with WHIP/WHEP, and integration with Stream\
  \ Manager\n      for cluster-aware streaming deployments. Example code and testbeds are\n      available on GitHub.\n    humanURL: https://www.red5.net/docs/red5-pro/development/sdks/\n    baseURL: https://api.example.com\n    tags:\n      - iOS\n      - Media\n      - Mobile\n      - SDK\n      - Streaming\n      - Swift\n    properties:\n      - type: Documentation\n        url: https://www.red5.net/docs/red5-pro/development/sdks/\n      - type: GitHub\n        url: https://github.com/red5pro/streaming-ios\n\n  - aid: red5:android-sdk\n    name: Red5 Pro Android Streaming SDK\n    description: >-\n      The Red5 Pro Android Streaming SDK is a native Android library for\n      integrating real-time live streaming publish and subscribe capabilities\n      into Android applications. It supports H.264/H.265 video encoding, AAC\n      audio, WebRTC-based streaming, and adaptive bitrate control. SDK examples\n      and testbeds are available on GitHub for common streaming use cases.\n    humanURL:\
  \ https://www.red5.net/docs/red5-pro/development/sdks/\n    baseURL: https://api.example.com\n    tags:\n      - Android\n      - Java\n      - Media\n      - Mobile\n      - SDK\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://www.red5.net/docs/red5-pro/development/sdks/\n      - type: GitHub\n        url: https://github.com/red5pro/streaming-android\n\ncommon:\n  - type: Website\n    url: https://www.red5.net/\n  - type: Documentation\n    url: https://www.red5.net/docs/red5-pro/\n  - type: GitHub Organization\n    url: https://github.com/red5pro\n  - type: GitHub Organization\n    url: https://github.com/Red5\n  - type: SDKs\n    url: https://www.red5.net/live-streaming-sdks/\n  - type: Pricing\n    url: https://www.red5.net/pricing/\n  - type: Blog\n    url: https://www.red5.net/blog/\n  - type: Contact\n    url: https://www.red5.net/contact/\n  - type: JSONLDContext\n    url: json-ld/red5-context.jsonld\n  - type: JSONSchema\n    url: json-schema/red5-stream-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/red5-restream-provision-schema.json\n  - type: OpenAPI\n    url: openapi/red5-server-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/red5-stream-manager-2-openapi.yml\n  - type: OpenAPI\n    url: openapi/red5-brew-mixer-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/red5-restreamer-api-openapi.yml\n  - type: AsyncAPI\n    url: asyncapi/red5-webrtc-streaming-asyncapi.yml\n  - type: JSONStructure\n    url: json-structure/red5-stream-structure.json\n  - type: SpectralRuleset\n    url: rules/red5-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/live-streaming.yaml\n  - type: Vocabulary\n    url: vocabulary/red5-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/apis.yml
tags:
- Live Streaming
- Media
- Real-Time
- RTMP
- Streaming
- Video
- WebRTC
url: https://raw.githubusercontent.com/api-evangelist/red5/refs/heads/main/apis.yml
use_cases: []
---
