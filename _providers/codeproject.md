---
api_count: 2
api_specs:
- filename: codeproject-rest-api-openapi.yml
  format: yaml
  label: CodeProject REST API
  slug: codeproject-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/openapi/codeproject-rest-api-openapi.yml
- filename: codeproject-ai-server-openapi.yml
  format: yaml
  label: CodeProject.AI Server API
  slug: codeproject-ai-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/openapi/codeproject-ai-server-openapi.yml
apis:
- description: OAuth 2.0 protected REST API providing read access to CodeProject articles, forum messages, questions, and authenticated user data (answers, articles, blog posts, bookmarks, notifications, profile, re
  name: CodeProject REST API
  slug: codeproject-api
- description: Self-hosted AI service that exposes computer vision (object detection, scene, face, ALPR), image processing (background removal, cartoonise, portrait filter, super-resolution), audio classification, N
  name: CodeProject.AI Server API
  slug: codeproject-ai-server
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.codeproject.com/
- title: ''
  type: Documentation
  url: https://api.codeproject.com/Help
- title: ''
  type: Samples
  url: https://api.codeproject.com/Samples
- title: ''
  type: TermsOfService
  url: https://www.codeproject.com/Terms
- title: ''
  type: PrivacyPolicy
  url: https://www.codeproject.com/privacy
- title: ''
  type: Forum
  url: https://www.codeproject.com/Lounge.aspx
- title: ''
  type: Tutorials
  url: https://www.codeproject.com/KB/
- title: ''
  type: Support
  url: https://www.codeproject.com/Questions/
- title: ''
  type: Newsletter
  url: https://www.codeproject.com/newsletters
- title: ''
  type: Portal
  url: https://codeproject.ai/
- title: ''
  type: GitHub
  url: https://github.com/codeproject
- title: ''
  type: JSON-LD
  url: json-ld/codeproject-context.jsonld
- title: ''
  type: Spectral
  url: rules/codeproject-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/codeproject-capabilities.yml
created: '2025-01-01'
description: CodeProject is a long-running online community for software developers founded in 1999, hosting hundreds of thousands of developer-contributed articles, tutorials, code samples, tips, and a Q&A forum across a broad range of programming topics. It exposes a public REST API at api.codeproject.com (V1 Beta) for read access to articles, forum messages, questions, and authenticated user data, secured by OAuth 2.0 Bearer Tokens. CodeProject also operates CodeProject.AI Server, a free, open-source, self-hosted AI service that exposes object detection, face recognition, license-plate reading (ALPR), scene classification, image processing, audio classification, text analytics, and YOLOv5 training through a local HTTP REST API. CodeProject.AI is widely integrated with home-automation and surveillance platforms (Blue Iris, Home Assistant, Agent DVR).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Codeproject Context
  property_count: 7
  slug: codeproject-context
layout: provider
modified: '2026-04-26'
name: CodeProject
rules:
- name: CodeProject API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 3
  slug: codeproject-rules
skills: []
slug: codeproject
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: codeproject\nurl: https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/apis.yml\nname: CodeProject\ntags:\n  - AI\n  - Articles\n  - Community\n  - Computer Vision\n  - Developer Community\n  - Face Recognition\n  - Forum\n  - Knowledge Base\n  - License Plate Recognition\n  - Object Detection\n  - Q&A\n  - Software Development\n  - Tutorials\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2025-01-01'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  CodeProject is a long-running online community for software developers\n  founded in 1999, hosting hundreds of thousands of developer-contributed\n  articles, tutorials, code samples, tips, and a Q&A forum across a broad\n  range of programming topics. It exposes a public REST API at\n  api.codeproject.com (V1 Beta) for read access to articles, forum messages,\n  questions, and authenticated user\
  \ data, secured by OAuth 2.0 Bearer Tokens.\n  CodeProject also operates CodeProject.AI Server, a free, open-source,\n  self-hosted AI service that exposes object detection, face recognition,\n  license-plate reading (ALPR), scene classification, image processing,\n  audio classification, text analytics, and YOLOv5 training through a local\n  HTTP REST API. CodeProject.AI is widely integrated with home-automation\n  and surveillance platforms (Blue Iris, Home Assistant, Agent DVR).\napis:\n  - aid: codeproject:codeproject-api\n    name: CodeProject REST API\n    tags:\n      - Articles\n      - Community\n      - Forum\n      - OAuth2\n      - Q&A\n      - Read-Only\n    type: REST\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.codeproject.com\n    humanURL: https://api.codeproject.com/Help\n    description: >-\n      OAuth 2.0 protected REST API providing read access to CodeProject\n      articles, forum messages, questions,\
  \ and authenticated user data\n      (answers, articles, blog posts, bookmarks, notifications, profile,\n      reputation, tips). Supports Client Credentials, Authorization Code,\n      and Implicit Grant flows. Tokens are issued by the CodeProject\n      identity server and presented as Bearer tokens in the Authorization\n      header.\n    properties:\n      - url: https://api.codeproject.com/Help\n        name: API Documentation\n        type: Documentation\n      - url: https://api.codeproject.com/\n        name: API Base URL\n        type: BaseURL\n      - url: https://api.codeproject.com/Samples\n        name: API Samples\n        type: Samples\n      - url: https://www.codeproject.com/Articles/986918/The-CodeProject-API-Part\n        name: The CodeProject API - Part 1\n        type: Article\n      - url: https://www.codeproject.com/articles/989081/the-code-project-api-part-getting-some-rest\n        name: The CodeProject API - Part 2 Getting Some REST\n        type: Article\n  \
  \    - url: openapi/codeproject-rest-api-openapi.yml\n        type: OpenAPI\n    x-features:\n      - OAuth 2.0 Bearer Token authentication\n      - Client Credentials, Authorization Code, and Implicit Grant flows\n      - Read-only access to articles, forums, and Q&A\n      - My endpoints for authenticated user data\n      - Article rating filter (>= 3.0) on the public list\n    x-use-cases:\n      - Aggregating CodeProject articles into developer reading lists\n      - Surfacing CodeProject Q&A in IDE assistants\n      - Building user dashboards showing reputation and notifications\n      - Periodic content sync into knowledge bases\n\n  - aid: codeproject:codeproject-ai-server\n    name: CodeProject.AI Server API\n    tags:\n      - AI\n      - Audio\n      - Computer Vision\n      - Face Recognition\n      - Image Processing\n      - License Plate Recognition\n      - Object Detection\n      - On-Premise\n      - Self-Hosted\n      - Text\n      - Training\n    type: REST\n    image:\
  \ https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: http://localhost:32168\n    humanURL: https://www.codeproject.com/AI/\n    description: >-\n      Self-hosted AI service that exposes computer vision (object detection,\n      scene, face, ALPR), image processing (background removal, cartoonise,\n      portrait filter, super-resolution), audio classification, NLP\n      (sentiment, summarization), and YOLOv5 training endpoints through a\n      local HTTP REST API. All endpoints are POST and accept multipart\n      uploads. The server runs on Windows, macOS, Linux, Raspberry Pi,\n      Jetson, and OrangePi, plus Docker images, and integrates with Blue\n      Iris, Home Assistant, and Agent DVR for surveillance use cases.\n    properties:\n      - url: https://www.codeproject.com/AI/\n        name: CodeProject.AI Server Home\n        type: Portal\n      - url: https://codeproject.github.io/codeproject.ai/\n        name: Documentation\n        type:\
  \ Documentation\n      - url: https://codeproject.github.io/codeproject.ai/api/api_reference.html\n        name: API Reference\n        type: APIReference\n      - url: https://github.com/codeproject/CodeProject.AI-Server\n        name: GitHub Repository\n        type: SourceCode\n      - url: openapi/codeproject-ai-server-openapi.yml\n        type: OpenAPI\n    x-features:\n      - Local-only HTTP REST API (no internet dependency)\n      - YOLO-based object detection (80+ classes)\n      - Custom YOLOv5 model loading and training\n      - Face detection, registration, recognition, and matching\n      - Automatic License Plate Recognition (ALPR)\n      - Image background removal, cartoonise, portrait, super-resolution\n      - Sound classification and NLP (sentiment, summarization)\n      - Modular installer-based feature set\n      - Cross-platform (Windows, macOS, Linux, Pi, Jetson, OrangePi, Docker)\n    x-use-cases:\n      - On-premise CCTV/NVR object and person detection\n      -\
  \ License plate capture for parking and security\n      - Privacy-preserving face recognition for home automation\n      - Edge AI on Raspberry Pi and Jetson devices\n      - Local image moderation and content classification\ncommon:\n  - url: https://www.codeproject.com/\n    name: CodeProject Website\n    type: Website\n  - url: https://api.codeproject.com/Help\n    name: API Documentation\n    type: Documentation\n  - url: https://api.codeproject.com/Samples\n    name: API Samples\n    type: Samples\n  - url: https://www.codeproject.com/Terms\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://www.codeproject.com/privacy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.codeproject.com/Lounge.aspx\n    name: Community Forum\n    type: Forum\n  - url: https://www.codeproject.com/KB/\n    name: Articles and Tutorials\n    type: Tutorials\n  - url: https://www.codeproject.com/Questions/\n    name: Q&A\n    type: Support\n  - url: https://www.codeproject.com/newsletters\n\
  \    name: Newsletter\n    type: Newsletter\n  - url: https://codeproject.ai/\n    name: CodeProject.AI\n    type: Portal\n  - url: https://github.com/codeproject\n    name: GitHub Organization\n    type: GitHub\n  - url: json-ld/codeproject-context.jsonld\n    type: JSON-LD\n  - url: rules/codeproject-rules.yml\n    type: Spectral\n  - url: capabilities/codeproject-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/apis.yml
tags:
- AI
- Articles
- Community
- Computer Vision
- Developer Community
- Face Recognition
- Forum
- Knowledge Base
- License Plate Recognition
- Object Detection
- Q&A
- Software Development
- Tutorials
url: https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/apis.yml
use_cases: []
---
