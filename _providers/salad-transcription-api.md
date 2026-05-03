---
api_count: 1
api_specs:
- filename: salad-transcription-api-openapi.yml
  format: yaml
  label: Salad Transcription API
  slug: salad-transcription-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salad-transcription-api/refs/heads/main/openapi/salad-transcription-api-openapi.yml
apis:
- description: Salad Transcription API converts speech to text using distributed GPU inference. Supports 97 languages, speaker diarization, word-level timestamps, and SRT caption generation for audio (AIFF, FLAC, M4
  name: Salad Transcription API
  slug: salad-transcription-api
capabilities:
- description: Workflow capability for speech-to-text transcription using Salad's distributed GPU inference network. Supports multi-language transcription, speaker diarization, word-level timestamps, and SRT caption
  name: Salad Speech-to-Text
  slug: speech-to-text
common:
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/salad-apis/salad/overview
- title: ''
  type: Pricing
  url: https://salad.com/pricing
- title: ''
  type: About
  url: https://salad.com/pricing
- title: ''
  type: Blog
  url: https://blog.salad.com/?_gl=1*wlg1yz*_gcl_au*NTI4MzE4NzY0LjE3MzU5MjAxNzc.
- title: ''
  type: Security
  url: https://salad.com/security
- title: ''
  type: PrivacyPolicy
  url: https://salad.com/privacy
- title: ''
  type: TermsOfService
  url: https://salad.com/terms
- title: ''
  type: PressReleases
  url: https://salad.com/press
- title: ''
  type: Trust
  url: https://trust.salad.com/?_gl=1*b0d9i*_gcl_au*NTI4MzE4NzY0LjE3MzU5MjAxNzc.
created: '2024-11-17'
description: Salad Transcription API is a powerful tool that allows users to convert speech into written text in a variety of languages. This API uses advanced algorithms to accurately transcribe audio files, making it a valuable tool for businesses looking to efficiently convert spoken content into text for documentation or analysis. Additionally, Salad Transcription API offers real-time transcription capabilities, allowing users to transcribe live conversations or presentations with ease.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Salad Transcription Api Context
  property_count: 19
  slug: salad-transcription-api-context
layout: provider
modified: '2026-05-02'
name: Salad Transcription API
rules:
- name: Salad Transcription API API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 2
  slug: salad-transcription-api-rules
skills: []
slug: salad-transcription-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: salad-transcription-api\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/salad-transcription-api/refs/heads/main/apis.yml\napis:\n  - aid: salad-transcription-api:salad-transcription-api\n    name: Salad Transcription API\n    description: >-\n      Salad Transcription API converts speech to text using distributed GPU inference.\n      Supports 97 languages, speaker diarization, word-level timestamps, and SRT\n      caption generation for audio (AIFF, FLAC, M4A, MP3, WAV) and video (MP4, MKV,\n      MOV, WEBM, WMA) files.\n    tags:\n      - Audio Files\n      - Audio Transcription\n      - Diarization\n      - Jobs\n      - Speech Recognition\n      - Transcriptions\n    humanURL: https://salad.com/transcription\n    properties:\n      - url: https://salad.com/transcription\n        type: Documentation\n      - url: openapi/salad-transcription-api-openapi.yml\n        type: OpenAPI\n      - type: JSONSchema\n        url: json-schema/salad-transcription-job-schema.json\n\
  \      - type: JSONLD\n        url: json-ld/salad-transcription-api-context.jsonld\n      - type: SpectralRules\n        url: rules/salad-transcription-api-rules.yml\n      - type: Capabilities\n        url: capabilities/speech-to-text.yaml\n      - type: Vocabulary\n        url: vocabulary/salad-transcription-api-vocabulary.yml\nname: Salad Transcription API\ndescription: >-\n  Salad Transcription API provides speech-to-text conversion powered by Salad's\n  distributed GPU cloud network. Designed for high-volume audio and video transcription\n  workloads with support for 97 languages, speaker diarization, and caption generation.\ntags:\n  - Audio Transcription\n  - Captions\n  - Diarization\n  - GPU\n  - Speech Recognition\n  - Transcription\n  - Video Processing\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.postman.com/salad-apis/salad/overview\n    name: Postman Workspace\n\
  \    type: PostmanWorkspace\n  - name: Salad GPU Cloud Pricing | Rent GPUs from $0.02/hr\n    description: 'null'\n    url: https://salad.com/pricing\n    type: Pricing\n  - name: Salad GPU Cloud Pricing | Rent GPUs from $0.02/hr\n    description: 'null'\n    url: https://salad.com/pricing\n    type: About\n  - name: Blog - SaladCloud Blog\n    description: 'null'\n    url: https://blog.salad.com/?_gl=1*wlg1yz*_gcl_au*NTI4MzE4NzY0LjE3MzU5MjAxNzc.\n    type: Blog\n  - name: Security | Salad\n    description: 'null'\n    url: https://salad.com/security\n    type: Security\n  - name: Privacy\n    description: 'null'\n    url: https://salad.com/privacy\n    type: PrivacyPolicy\n  - name: Terms | Salad\n    description: 'null'\n    url: https://salad.com/terms\n    type: TermsOfService\n  - name: Press About Salad\n    description: 'null'\n    url: https://salad.com/press\n    type: PressReleases\n  - name: Trust Center - Salad\n    description: 'null'\n    url: https://trust.salad.com/?_gl=1*b0d9i*_gcl_au*NTI4MzE4NzY0LjE3MzU5MjAxNzc.\n\
  \    type: Trust\ncreated: '2024-11-17'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  Salad Transcription API is a powerful tool that allows users to convert speech into\n  written text in a variety of languages. This API uses advanced algorithms to accurately\n  transcribe audio files, making it a valuable tool for businesses looking to efficiently\n  convert spoken content into text for documentation or analysis. Additionally, Salad\n  Transcription API offers real-time transcription capabilities, allowing users to\n  transcribe live conversations or presentations with ease.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salad-transcription-api/refs/heads/main/apis.yml
tags:
- Audio Transcription
- Captions
- Diarization
- GPU
- Speech Recognition
- Transcription
- Video Processing
url: https://raw.githubusercontent.com/api-evangelist/salad-transcription-api/refs/heads/main/apis.yml
use_cases: []
---
