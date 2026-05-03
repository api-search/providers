---
api_count: 5
api_specs:
- filename: runway-video-generation-openapi.yml
  format: yaml
  label: Runway Video Generation API
  slug: video-generation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/openapi/runway-video-generation-openapi.yml
- filename: runway-image-generation-openapi.yml
  format: yaml
  label: Runway Image Generation API
  slug: image-generation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/openapi/runway-image-generation-openapi.yml
- filename: runway-characters-openapi.yml
  format: yaml
  label: Runway Characters API
  slug: characters
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/openapi/runway-characters-openapi.yml
apis:
- description: The Runway Video Generation API allows developers to generate videos from text prompts, images, or existing videos using Gen-4, Gen-4 Turbo, Gen-4.5, Gen-4 Aleph, Veo 3.1, and Veo 3.1 Fast models. Sup
  name: Runway Video Generation API
  slug: video-generation
- description: The Runway Image Generation API provides text-to-image generation using the Gen-4 Image and Gemini 3 Pro Image models. Accepts text prompts up to 1000 characters and supports multiple aspect ratios. A
  name: Runway Image Generation API
  slug: image-generation
- description: The Runway Characters API enables developers to build real-time conversational avatars powered by GWM-1 (Runway's General World Model). Avatars are fully custom conversational video agents created fro
  name: Runway Characters API
  slug: characters
- description: The Runway Python SDK provides a convenient Python library for interacting with the Runway API. Supports Python 3.8+ with type annotations compatible with MyPy. Includes automatic retries, best-practi
  name: Runway Python SDK
  slug: python-sdk
- description: The Runway Node.js SDK provides a JavaScript and TypeScript library for integrating with the Runway API. Supports Node.js 18+ with TypeScript bindings, automatic retries, and best-practice error handl
  name: Runway Node.js SDK
  slug: nodejs-sdk
asyncapis:
- description: The Runway Characters realtime event interface describes the WebRTC-based communication protocol for live conversational avatar sessions powered by GWM-1. Once a realtime session is created via the RE
  name: Runway Characters Realtime Events
  slug: runway-characters-asyncapi
capabilities:
- description: Comprehensive generative media production capability for Runway. Enables creative professionals, developers, and AI workflows to generate videos from text or images, animate characters with motion cap
  name: Runway Generative Media Production
  slug: generative-media-production
common:
- title: ''
  type: Portal
  url: https://docs.dev.runwayml.com/
- title: ''
  type: Documentation
  url: https://docs.dev.runwayml.com/api/
- title: ''
  type: Website
  url: https://runwayml.com/
- title: ''
  type: Developer Portal
  url: https://dev.runwayml.com/
- title: ''
  type: Privacy Policy
  url: https://runwayml.com/privacy-policy
- title: ''
  type: Terms Of Service
  url: https://runwayml.com/terms-of-use
- title: ''
  type: Blog
  url: https://runwayml.com/blog
- title: ''
  type: Login
  url: https://app.runwayml.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/runwayml
- title: ''
  type: Changelog
  url: https://docs.dev.runwayml.com/api-details/api_changelog/
- title: ''
  type: Vocabulary
  url: vocabulary/runway-vocabulary.yml
- title: ''
  type: JSONLD
  url: json-ld/runway-context.jsonld
created: '2025-03-01'
description: Runway is an applied AI research company that builds generative AI tools for creative professionals. Their developer platform provides APIs for video generation, image generation, real-time conversational avatar experiences, media uploads, and audio synthesis powered by advanced generative models including Gen-4, Gen-4 Turbo, Gen-4.5, Gen-4 Aleph, Veo 3.1, Act Two, and GWM-1 (General World Model). The API uses asynchronous task processing with Bearer token authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Runway Context
  property_count: 7
  slug: runway-context
layout: provider
modified: '2026-05-02'
name: Runway
rules:
- name: Runway API Rules
  rule_count: 17
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 11
  slug: runway-rules
skills: []
slug: runway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: runway\nname: Runway\ndescription: >-\n  Runway is an applied AI research company that builds generative AI tools for creative\n  professionals. Their developer platform provides APIs for video generation, image\n  generation, real-time conversational avatar experiences, media uploads, and audio\n  synthesis powered by advanced generative models including Gen-4, Gen-4 Turbo, Gen-4.5,\n  Gen-4 Aleph, Veo 3.1, Act Two, and GWM-1 (General World Model). The API uses\n  asynchronous task processing with Bearer token authentication.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Video Generation\n  - Image Generation\n  - Artificial Intelligence\n  - Machine Learning\n  - Generative AI\n  - Avatars\n  - Characters\n  - WebRTC\n  - Creative Tools\nurl: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-05-02'\n\
  specificationVersion: '0.19'\napis:\n  - aid: runway:video-generation\n    name: Runway Video Generation API\n    description: >-\n      The Runway Video Generation API allows developers to generate videos from\n      text prompts, images, or existing videos using Gen-4, Gen-4 Turbo, Gen-4.5,\n      Gen-4 Aleph, Veo 3.1, and Veo 3.1 Fast models. Supports text-to-video,\n      image-to-video, video-to-video, character performance (Act Two), lip sync\n      (28+ languages), video upscale, frame interpolation, and sound effect generation.\n      Tasks are processed asynchronously with polling via task ID. Authentication via\n      Bearer token plus X-Runway-Version header set to 2024-11-06.\n    humanURL: https://docs.dev.runwayml.com/api/\n    baseURL: https://api.dev.runwayml.com/v1\n    tags:\n      - Video Generation\n      - Artificial Intelligence\n      - Machine Learning\n      - Text To Video\n      - Image To Video\n      - Generative AI\n      - Gen-4\n    properties:\n      -\
  \ type: Documentation\n        url: https://docs.dev.runwayml.com/api/\n      - type: OpenAPI\n        url: openapi/runway-video-generation-openapi.yml\n      - type: Spectral Rules\n        url: rules/runway-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/generative-media-production.yaml\n\n  - aid: runway:image-generation\n    name: Runway Image Generation API\n    description: >-\n      The Runway Image Generation API provides text-to-image generation using the\n      Gen-4 Image and Gemini 3 Pro Image models. Accepts text prompts up to 1000\n      characters and supports multiple aspect ratios. Also includes task status polling.\n      Uses the same asynchronous task pattern and Bearer token authentication as the\n      video API. As of April 2026, Gemini 3 Pro Image supports up to 5,500-character\n      prompts and 14 reference images.\n    humanURL: https://docs.dev.runwayml.com/api/\n    baseURL: https://api.dev.runwayml.com/v1\n    tags:\n      - Image Generation\n\
  \      - Artificial Intelligence\n      - Machine Learning\n      - Text To Image\n      - Generative AI\n      - Gen-4\n    properties:\n      - type: Documentation\n        url: https://docs.dev.runwayml.com/api/\n      - type: OpenAPI\n        url: openapi/runway-image-generation-openapi.yml\n      - type: Spectral Rules\n        url: rules/runway-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/generative-media-production.yaml\n\n  - aid: runway:characters\n    name: Runway Characters API\n    description: >-\n      The Runway Characters API enables developers to build real-time conversational\n      avatars powered by GWM-1 (Runway's General World Model). Avatars are fully custom\n      conversational video agents created from a single reference image with no fine-tuning.\n      Supports photorealistic or animated styles, human or non-human appearances. Manages\n      avatars, real-time WebRTC sessions (max 5 minutes), and knowledge documents (up to\n      50,000\
  \ tokens per avatar). Authentication via Bearer token.\n    humanURL: https://docs.dev.runwayml.com/characters/\n    baseURL: https://api.dev.runwayml.com/v1\n    tags:\n      - Avatars\n      - Characters\n      - Conversational AI\n      - Real Time\n      - WebRTC\n      - Video Agents\n      - Generative AI\n      - GWM-1\n    properties:\n      - type: Documentation\n        url: https://docs.dev.runwayml.com/characters/\n      - type: OpenAPI\n        url: openapi/runway-characters-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/runway-characters-asyncapi.yml\n      - type: NaftikoCapability\n        url: capabilities/generative-media-production.yaml\n      - type: Spectral Rules\n        url: rules/runway-rules.yml\n\n  - aid: runway:python-sdk\n    name: Runway Python SDK\n    description: >-\n      The Runway Python SDK provides a convenient Python library for interacting with\n      the Runway API. Supports Python 3.8+ with type annotations compatible with MyPy.\n\
  \      Includes automatic retries, best-practice error handling, and type safety to\n      simplify integration of Runway's video and image generation capabilities into\n      Python applications.\n    humanURL: https://docs.dev.runwayml.com/api-details/sdks/\n    tags:\n      - Python\n      - SDK\n      - Libraries\n      - Artificial Intelligence\n      - Video Generation\n    properties:\n      - type: Documentation\n        url: https://docs.dev.runwayml.com/api-details/sdks/\n      - type: GitHub Repository\n        url: https://github.com/runwayml/sdk-python\n\n  - aid: runway:nodejs-sdk\n    name: Runway Node.js SDK\n    description: >-\n      The Runway Node.js SDK provides a JavaScript and TypeScript library for\n      integrating with the Runway API. Supports Node.js 18+ with TypeScript bindings,\n      automatic retries, and best-practice error handling. Install via npm, yarn, or pnpm.\n    humanURL: https://docs.dev.runwayml.com/api-details/sdks/\n    tags:\n      - Node.js\n\
  \      - JavaScript\n      - TypeScript\n      - SDK\n      - Libraries\n      - Video Generation\n    properties:\n      - type: Documentation\n        url: https://docs.dev.runwayml.com/api-details/sdks/\n      - type: GitHub Repository\n        url: https://github.com/runwayml/sdk-node\n\ncommon:\n  - type: Portal\n    url: https://docs.dev.runwayml.com/\n  - type: Documentation\n    url: https://docs.dev.runwayml.com/api/\n  - type: Website\n    url: https://runwayml.com/\n  - type: Developer Portal\n    url: https://dev.runwayml.com/\n  - type: Privacy Policy\n    url: https://runwayml.com/privacy-policy\n  - type: Terms Of Service\n    url: https://runwayml.com/terms-of-use\n  - type: Blog\n    url: https://runwayml.com/blog\n  - type: Login\n    url: https://app.runwayml.com/\n  - type: GitHub Organization\n    url: https://github.com/runwayml\n  - type: Changelog\n    url: https://docs.dev.runwayml.com/api-details/api_changelog/\n  - type: Vocabulary\n    url: vocabulary/runway-vocabulary.yml\n\
  \  - type: JSONLD\n    url: json-ld/runway-context.jsonld\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/apis.yml
tags:
- Video Generation
- Image Generation
- Artificial Intelligence
- Machine Learning
- Generative AI
- Avatars
- Characters
- WebRTC
- Creative Tools
url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/apis.yml
use_cases: []
---
