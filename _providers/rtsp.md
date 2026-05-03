---
api_count: 2
apis:
- description: The Real-Time Streaming Protocol (RTSP) is a stateful protocol defined in RFC 2326 (1.0) and RFC 7826 (2.0). It defines methods including OPTIONS, DESCRIBE, SETUP, PLAY, PAUSE, RECORD, ANNOUNCE, GET_P
  name: RTSP Protocol
  slug: rtsp-protocol
- description: Common open-source RTSP server and client implementations used in production. MediaMTX (formerly rtsp-simple-server) is a ready-to-use media server supporting RTSP/RTMP/WebRTC with an HTTP API for man
  name: RTSP Implementations
  slug: rtsp-implementations
common:
- title: ''
  type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc7826
- title: ''
  type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc2326
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/Real-Time_Streaming_Protocol
created: '2025-01-01'
description: Real-Time Streaming Protocol (RTSP) is an application-level network protocol designed for controlling streaming media servers. Defined by IETF RFC 2326 (RTSP 1.0) and RFC 7826 (RTSP 2.0), it acts as a network remote control for multimedia servers, enabling on-demand delivery of real-time audio and video data. RTSP controls sessions between endpoints but relies on RTP (Real-time Transport Protocol) for actual media transport. It is widely used in IP cameras, DVR systems, media servers, and live streaming platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Rtsp Context
  property_count: 8
  slug: rtsp-context
layout: provider
modified: '2026-05-02'
name: RTSP
skills: []
slug: rtsp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rtsp\nname: RTSP\ndescription: >-\n  Real-Time Streaming Protocol (RTSP) is an application-level network protocol\n  designed for controlling streaming media servers. Defined by IETF RFC 2326\n  (RTSP 1.0) and RFC 7826 (RTSP 2.0), it acts as a network remote control\n  for multimedia servers, enabling on-demand delivery of real-time audio and\n  video data. RTSP controls sessions between endpoints but relies on RTP\n  (Real-time Transport Protocol) for actual media transport. It is widely\n  used in IP cameras, DVR systems, media servers, and live streaming platforms.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Streaming\n  - Video\n  - Media\n  - Protocol\n  - Real-Time\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/rtsp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: rtsp:rtsp-protocol\n \
  \   name: RTSP Protocol\n    description: >-\n      The Real-Time Streaming Protocol (RTSP) is a stateful protocol defined\n      in RFC 2326 (1.0) and RFC 7826 (2.0). It defines methods including\n      OPTIONS, DESCRIBE, SETUP, PLAY, PAUSE, RECORD, ANNOUNCE, GET_PARAMETER,\n      SET_PARAMETER, and TEARDOWN for controlling streaming media sessions.\n      RTSP URLs follow the rtsp:// scheme. Sessions are established before\n      streaming begins and media is transmitted via RTP/RTCP on separate channels.\n    humanURL: https://datatracker.ietf.org/doc/html/rfc7826\n    baseURL: rtsp://\n    tags:\n      - Streaming\n      - Video\n      - Media\n      - Protocol\n      - IETF\n      - RFC\n    properties:\n      - type: Documentation\n        url: https://datatracker.ietf.org/doc/html/rfc7826\n      - type: Specification\n        url: https://datatracker.ietf.org/doc/html/rfc2326\n      - type: Specification\n        url: https://datatracker.ietf.org/doc/html/rfc7826\n  - aid: rtsp:rtsp-implementations\n\
  \    name: RTSP Implementations\n    description: >-\n      Common open-source RTSP server and client implementations used in\n      production. MediaMTX (formerly rtsp-simple-server) is a ready-to-use\n      media server supporting RTSP/RTMP/WebRTC with an HTTP API for\n      management. GStreamer and FFmpeg provide RTSP client/server libraries.\n      IP camera manufacturers (Axis, Hikvision, Dahua) expose RTSP streams\n      at standard paths like rtsp://{host}:554/live or rtsp://{host}/stream.\n    humanURL: https://github.com/bluenviron/mediamtx\n    tags:\n      - Streaming\n      - Video\n      - IP Camera\n      - Open Source\n      - MediaMTX\n    properties:\n      - type: Documentation\n        url: https://github.com/bluenviron/mediamtx\ncommon:\n  - type: Specification\n    url: https://datatracker.ietf.org/doc/html/rfc7826\n  - type: Specification\n    url: https://datatracker.ietf.org/doc/html/rfc2326\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/Real-Time_Streaming_Protocol\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rtsp/refs/heads/main/apis.yml
tags:
- Streaming
- Video
- Media
- Protocol
- Real-Time
url: https://raw.githubusercontent.com/api-evangelist/rtsp/refs/heads/main/apis.yml
use_cases: []
---
