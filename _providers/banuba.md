---
api_count: 3
apis:
- description: The Banuba Face AR SDK provides AR face effects, beauty filters, and face tracking for mobile (iOS/Android), web, and desktop applications. The SDK includes real-time face detection, 3D face tracking,
  name: Banuba Face AR SDK
  slug: face-ar-sdk
- description: Banuba Video Editor SDK is a complete white-label video and photo editing solution for iOS and Android with AI features including auto-clipping, captions, beauty filters, AR effects, and music integra
  name: Banuba Video Editor SDK
  slug: video-editor-sdk
- description: Banuba Face Liveness SDK provides anti-spoofing technology that verifies a face is real and present in real time, used for identity verification and access control.
  name: Banuba Face Liveness SDK
  slug: face-liveness-sdk
capabilities:
- description: ''
  name: Face Ar
  slug: face-ar
common:
- title: ''
  type: Website
  url: https://www.banuba.com/
- title: ''
  type: Documentation
  url: https://docs.banuba.com/
- title: ''
  type: Documentation
  url: https://docs.banuba.com/far-sdk/
- title: ''
  type: GitHub
  url: https://github.com/Banuba
- title: ''
  type: Blog
  url: https://www.banuba.com/blog
- title: ''
  type: PrivacyPolicy
  url: https://www.banuba.com/privacy-policy
- title: ''
  type: SpectralRules
  url: rules/banuba-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/banuba-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/face-ar.yaml
- title: ''
  type: JSON-LD
  url: json-ld/banuba-context.jsonld
created: '2024-12-16'
description: Banuba is an AR and AI technology company providing the Face AR SDK for augmented reality face effects, beauty filters, and virtual try-on experiences. The SDK supports iOS, Android, Web (HTML5), Windows, macOS, Unity, Flutter, and React Native. Use cases include live streaming beauty filters, video conferencing face effects, selfie editing, virtual makeup try-on, and face tracking for interactive applications.
features:
- description: Real-time AR face masks, filters, and accessories for live and recorded video.
  name: Face AR Effects
- description: Skin smoothing, face reshaping, eye enlargement, and makeup filters.
  name: Beauty Filters
- description: Precise 3D face landmark tracking for accurate AR effect placement.
  name: 3D Face Tracking
- description: Real-time background removal and replacement for video calls.
  name: Background Segmentation
- description: Virtual makeup, glasses, hair color, and accessory try-on experiences.
  name: Virtual Try-On
- description: ML-powered face detection with age, gender, and emotion analysis.
  name: AI Face Detection
- description: Native SDKs for iOS, Android, Web, Windows, macOS, Unity, Flutter, and React Native.
  name: Cross-Platform SDK
- description: Banuba Effect Player for creating custom AR effects without coding.
  name: Custom Effects Builder
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Banuba Context
  property_count: 14
  slug: banuba-context
layout: provider
modified: '2026-04-21'
name: Banuba
rules:
- name: Banuba API Rules
  rule_count: 7
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 1
  slug: banuba-spectral-rules
skills: []
slug: banuba
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: banuba\nurl: https://raw.githubusercontent.com/api-evangelist/banuba/refs/heads/main/apis.yml\nname: Banuba\ntags:\n  - AR\n  - Augmented Reality\n  - Beauty\n  - Face Recognition\n  - Facial\n  - SDK\n  - Video\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-16'\nmodified: '2026-04-21'\nposition: Consuming\ndescription: >-\n  Banuba is an AR and AI technology company providing the Face AR SDK for augmented reality\n  face effects, beauty filters, and virtual try-on experiences. The SDK supports iOS, Android,\n  Web (HTML5), Windows, macOS, Unity, Flutter, and React Native. Use cases include live\n  streaming beauty filters, video conferencing face effects, selfie editing, virtual makeup\n  try-on, and face tracking for interactive applications.\napis:\n  - aid: banuba:face-ar-sdk\n    name: Banuba Face AR SDK\n    tags:\n      - AR\n      - Augmented Reality\n      - Beauty Filters\n\
  \      - Face Effects\n      - Face Tracking\n      - Virtual Try-On\n    humanURL: https://docs.banuba.com/far-sdk/\n    properties:\n      - url: https://docs.banuba.com/far-sdk/\n        type: Documentation\n      - url: https://www.banuba.com/augmented-reality-sdk\n        type: Website\n      - url: https://github.com/Banuba\n        type: GitHub\n    description: >-\n      The Banuba Face AR SDK provides AR face effects, beauty filters, and face tracking\n      for mobile (iOS/Android), web, and desktop applications. The SDK includes real-time\n      face detection, 3D face tracking, background segmentation, and a library of\n      customizable AR effects and beauty filters. Integration is via native SDK rather\n      than REST API. Tracks up to 9 faces simultaneously.\n  - aid: banuba:video-editor-sdk\n    name: Banuba Video Editor SDK\n    tags:\n      - Video Editing\n      - AI\n      - White-Label\n      - SDK\n    humanURL: https://www.banuba.com/video-editor-sdk\n    properties:\n\
  \      - url: https://docs.banuba.com/ve-sdk/\n        type: Documentation\n      - url: https://www.banuba.com/video-editor-sdk\n        type: Website\n    description: >-\n      Banuba Video Editor SDK is a complete white-label video and photo editing solution\n      for iOS and Android with AI features including auto-clipping, captions, beauty\n      filters, AR effects, and music integration.\n  - aid: banuba:face-liveness-sdk\n    name: Banuba Face Liveness SDK\n    tags:\n      - Liveness Detection\n      - Biometrics\n      - Security\n      - Identity Verification\n    humanURL: https://www.banuba.com/face-liveness\n    properties:\n      - url: https://docs.banuba.com/face-liveness/\n        type: Documentation\n      - url: https://www.banuba.com/face-liveness\n        type: Website\n    description: >-\n      Banuba Face Liveness SDK provides anti-spoofing technology that verifies a face\n      is real and present in real time, used for identity verification and access control.\n\
  common:\n  - type: Website\n    url: https://www.banuba.com/\n    name: Banuba\n  - type: Documentation\n    url: https://docs.banuba.com/\n    name: Banuba SDK Documentation\n  - type: Documentation\n    url: https://docs.banuba.com/far-sdk/\n    name: Face AR SDK Docs\n  - type: GitHub\n    url: https://github.com/Banuba\n    name: Banuba GitHub\n  - type: Blog\n    url: https://www.banuba.com/blog\n    name: Banuba Blog\n  - type: PrivacyPolicy\n    url: https://www.banuba.com/privacy-policy\n    name: Privacy Policy\n  - type: SpectralRules\n    url: rules/banuba-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/banuba-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/face-ar.yaml\n  - type: JSON-LD\n    url: json-ld/banuba-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Face AR Effects\n        description: Real-time AR face masks, filters, and accessories for live and recorded video.\n      - name: Beauty Filters\n  \
  \      description: Skin smoothing, face reshaping, eye enlargement, and makeup filters.\n      - name: 3D Face Tracking\n        description: Precise 3D face landmark tracking for accurate AR effect placement.\n      - name: Background Segmentation\n        description: Real-time background removal and replacement for video calls.\n      - name: Virtual Try-On\n        description: Virtual makeup, glasses, hair color, and accessory try-on experiences.\n      - name: AI Face Detection\n        description: ML-powered face detection with age, gender, and emotion analysis.\n      - name: Cross-Platform SDK\n        description: Native SDKs for iOS, Android, Web, Windows, macOS, Unity, Flutter, and React Native.\n      - name: Custom Effects Builder\n        description: Banuba Effect Player for creating custom AR effects without coding.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Live Streaming Beauty Filters\n        description: Real-time beauty and AR filters for\
  \ live streaming platforms.\n      - name: Video Conferencing\n        description: Face effects and background segmentation for video call applications.\n      - name: Selfie and Photo Editing\n        description: Beauty retouching and AR effects for mobile photo editing apps.\n      - name: Virtual Makeup Try-On\n        description: AI-powered virtual makeup try-on for beauty e-commerce.\n      - name: Face Authentication\n        description: Face-based liveness detection and verification for security applications.\n      - name: Gaming and Entertainment\n        description: Face-tracked AR avatars and character animation for games.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/banuba/refs/heads/main/apis.yml
tags:
- AR
- Augmented Reality
- Beauty
- Face Recognition
- Facial
- SDK
- Video
url: https://raw.githubusercontent.com/api-evangelist/banuba/refs/heads/main/apis.yml
use_cases:
- description: Real-time beauty and AR filters for live streaming platforms.
  name: Live Streaming Beauty Filters
- description: Face effects and background segmentation for video call applications.
  name: Video Conferencing
- description: Beauty retouching and AR effects for mobile photo editing apps.
  name: Selfie and Photo Editing
- description: AI-powered virtual makeup try-on for beauty e-commerce.
  name: Virtual Makeup Try-On
- description: Face-based liveness detection and verification for security applications.
  name: Face Authentication
- description: Face-tracked AR avatars and character animation for games.
  name: Gaming and Entertainment
---
