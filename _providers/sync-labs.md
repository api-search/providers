---
api_count: 3
api_specs:
- filename: sync-labs-openapi.yml
  format: yaml
  label: Sync Labs API
  slug: sync-labs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/openapi/sync-labs-openapi.yml
apis:
- description: The Sync Labs REST API provides programmatic access to AI lip-sync and visual dubbing capabilities. Submit video and audio inputs to generate studio-grade synchronized output videos. Supports single g
  name: Sync Labs API
  slug: sync-labs-api
- description: Official Python SDK for integrating the Sync Labs lip-sync API into Python applications. Supports Python 3.8+. Install via pip install syncsdk.
  name: Sync Labs Python SDK
  slug: sync-labs-python-sdk
- description: Official TypeScript/Node.js SDK for integrating the Sync Labs API. Supports Node.js 18+. Install via npm install @sync.so/sdk.
  name: Sync Labs TypeScript SDK
  slug: sync-labs-typescript-sdk
capabilities:
- description: Workflow capability for AI-powered video dubbing and content localization using Sync Labs. Enables single video generation, batch processing for large-scale dubbing, cost estimation before submission,
  name: Sync Labs Video Dubbing and Localization
  slug: video-dubbing
common:
- title: ''
  type: Website
  url: https://sync.so
- title: ''
  type: Documentation
  url: https://sync.so/docs/introduction
- title: ''
  type: Quickstart
  url: https://sync.so/docs/quickstart
- title: ''
  type: Pricing
  url: https://sync.so/pricing
- title: ''
  type: API Keys
  url: https://sync.so/settings/api-keys
- title: ''
  type: Sign Up
  url: https://sync.so/sign-up
- title: ''
  type: Contact
  url: mailto:hello@sync.so
- title: ''
  type: Y Combinator
  url: https://www.ycombinator.com/companies/sync-2
created: '2026-05-03'
description: Sync Labs (sync.so) provides a suite of studio-grade AI lip-sync and visual dubbing APIs. Their technology synchronizes video lip movements with any audio track using state-of-the-art models, enabling professional video dubbing, content localization, and personalized video generation at scale. Models include sync-3, lipsync-2-pro, lipsync-2, lipsync-1.9, and react-1, with support for batch processing (up to 500 videos), webhooks, Python and TypeScript SDKs, Adobe Premiere plugin, and ComfyUI integration. Backed by Y Combinator.
features: []
image: https://sync.so/favicon.ico
integrations: []
jsonld:
- class_count: 0
  name: Sync Labs Context
  property_count: 22
  slug: sync-labs-context
layout: provider
modified: '2026-05-03'
name: Sync Labs
rules:
- name: Sync Labs API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 1
    info: 1
    warn: 5
  slug: sync-labs-rules
skills: []
slug: sync-labs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sync-labs\nname: Sync Labs\ndescription: >-\n  Sync Labs (sync.so) provides a suite of studio-grade AI lip-sync and visual\n  dubbing APIs. Their technology synchronizes video lip movements with any audio\n  track using state-of-the-art models, enabling professional video dubbing,\n  content localization, and personalized video generation at scale. Models\n  include sync-3, lipsync-2-pro, lipsync-2, lipsync-1.9, and react-1, with\n  support for batch processing (up to 500 videos), webhooks, Python and\n  TypeScript SDKs, Adobe Premiere plugin, and ComfyUI integration. Backed by\n  Y Combinator.\nimage: https://sync.so/favicon.ico\ntags:\n  - Artificial Intelligence\n  - Content Localization\n  - Dubbing\n  - Lip Sync\n  - Media\n  - Video\n  - Visual AI\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: sync-labs:sync-labs-api\n    name: Sync Labs API\n    description: >-\n      The Sync Labs REST API provides programmatic access to AI lip-sync and\n      visual dubbing capabilities. Submit video and audio inputs to generate\n      studio-grade synchronized output videos. Supports single generation,\n      batch processing of up to 500 videos, asset management, cost estimation,\n      and webhook notifications. Rate limited to 60 requests/min for generation\n      endpoints.\n    humanURL: https://sync.so/api\n    baseURL: https://api.sync.so/v2\n    tags:\n      - Artificial Intelligence\n      - Batch Processing\n      - Dubbing\n      - Lip Sync\n      - Media Processing\n      - Video\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://sync.so/docs/introduction\n      - type: OpenAPI\n        url: openapi/sync-labs-openapi.yml\n      - type: Pricing\n        url: https://sync.so/pricing\n      - type: Quickstart\n        url: https://sync.so/docs/quickstart\n\
  \  - aid: sync-labs:sync-labs-python-sdk\n    name: Sync Labs Python SDK\n    description: >-\n      Official Python SDK for integrating the Sync Labs lip-sync API into\n      Python applications. Supports Python 3.8+. Install via pip install\n      syncsdk.\n    humanURL: https://sync.so/docs/introduction\n    tags:\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://sync.so/docs/introduction\n      - type: PyPI\n        url: https://pypi.org/project/syncsdk/\n  - aid: sync-labs:sync-labs-typescript-sdk\n    name: Sync Labs TypeScript SDK\n    description: >-\n      Official TypeScript/Node.js SDK for integrating the Sync Labs API.\n      Supports Node.js 18+. Install via npm install @sync.so/sdk.\n    humanURL: https://sync.so/docs/introduction\n    tags:\n      - JavaScript\n      - Node.js\n      - SDK\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://sync.so/docs/introduction\n      - type: NPM\n  \
  \      url: https://www.npmjs.com/package/@sync.so/sdk\ncommon:\n  - type: Website\n    url: https://sync.so\n  - type: Documentation\n    url: https://sync.so/docs/introduction\n  - type: Quickstart\n    url: https://sync.so/docs/quickstart\n  - type: Pricing\n    url: https://sync.so/pricing\n  - type: API Keys\n    url: https://sync.so/settings/api-keys\n  - type: Sign Up\n    url: https://sync.so/sign-up\n  - type: Contact\n    url: mailto:hello@sync.so\n  - type: Y Combinator\n    url: https://www.ycombinator.com/companies/sync-2\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Content Localization
- Dubbing
- Lip Sync
- Media
- Video
- Visual AI
url: https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/apis.yml
use_cases: []
---
