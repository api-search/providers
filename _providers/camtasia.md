---
api_count: 2
apis:
- description: 'Public oEmbed API for TechSmith Screencast (app.screencast.com), the cloud destination where Camtasia videos and images are shared. The oEmbed endpoint returns embed HTML, thumbnail, and metadata for '
  name: TechSmith Screencast oEmbed API
  slug: screencast-oembed-api
- description: A developer toolkit from TechSmith that lets developers embed reliable high-quality screen, webcam, and audio recording into their own applications. The SDK exposes APIs to configure, start, stop, and
  name: Camtasia Screen Recorder SDK
  slug: camtasia-screen-recorder-sdk
common:
- title: ''
  type: Website
  url: https://www.techsmith.com/camtasia.html
- title: ''
  type: Screencast
  url: https://www.techsmith.com/screencast/
- title: ''
  type: GettingStarted
  url: https://www.techsmith.com/learn/camtasia/
- title: ''
  type: Blog
  url: https://www.techsmith.com/blog/category/camtasia/
- title: ''
  type: Support
  url: https://support.techsmith.com
- title: ''
  type: PublicAPIRepository
  url: https://github.com/TechSmith/screencast-public-api-docs
- title: ''
  type: TermsOfService
  url: https://www.techsmith.com/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.techsmith.com/privacy.html
- title: ''
  type: JSON-LD
  url: json-ld/camtasia-context.jsonld
created: '2024-01-15'
description: Camtasia is a screen recording and video editing software by TechSmith that allows users to create professional videos, tutorials, and presentations with built-in editing tools, effects, and media assets. Camtasia itself does not publish a public REST API, but it integrates tightly with TechSmith Screencast for sharing, and TechSmith publishes a public Screencast oEmbed API plus the Camtasia Screen Recorder SDK for embedding recording capabilities into third-party applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Camtasia Context
  property_count: 7
  slug: camtasia-context
layout: provider
modified: '2026-04-23'
name: Camtasia
skills: []
slug: camtasia
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: camtasia\nname: Camtasia\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ntags:\n  - Screen Recording\n  - Video Editing\n  - Tutorial Creation\n  - E-Learning\n  - Screencast\n  - oEmbed\n  - SDK\naccess: 3rd-Party\ncreated: '2024-01-15'\nmodified: '2026-04-23'\nposition: Provider\nspecificationVersion: '0.19'\ndescription: >-\n  Camtasia is a screen recording and video editing software by TechSmith\n  that allows users to create professional videos, tutorials, and\n  presentations with built-in editing tools, effects, and media assets.\n  Camtasia itself does not publish a public REST API, but it integrates\n  tightly with TechSmith Screencast for sharing, and TechSmith publishes a\n  public Screencast oEmbed API plus the Camtasia Screen Recorder SDK for\n  embedding recording capabilities into third-party applications.\napis:\n\
  \  - aid: camtasia:screencast-oembed-api\n    name: TechSmith Screencast oEmbed API\n    description: >-\n      Public oEmbed API for TechSmith Screencast (app.screencast.com), the\n      cloud destination where Camtasia videos and images are shared. The\n      oEmbed endpoint returns embed HTML, thumbnail, and metadata for a\n      given Screencast content URL, letting content platforms and CMSes\n      render Screencast shares inline the same way they render YouTube or\n      Vimeo. Documentation is maintained in a public GitHub repository.\n    humanURL: https://github.com/TechSmith/screencast-public-api-docs\n    baseURL: https://app.screencast.com/services/oembed\n    tags:\n      - oEmbed\n      - Screencast\n      - Embedding\n      - Video\n    properties:\n      - type: Documentation\n        url: https://github.com/TechSmith/screencast-public-api-docs/blob/main/sections/oembed.md\n      - type: Repository\n        url: https://github.com/TechSmith/screencast-public-api-docs\n\
  \      - type: JSON-LD\n        url: json-ld/camtasia-context.jsonld\n  - aid: camtasia:camtasia-screen-recorder-sdk\n    name: Camtasia Screen Recorder SDK\n    description: >-\n      A developer toolkit from TechSmith that lets developers embed reliable\n      high-quality screen, webcam, and audio recording into their own\n      applications. The SDK exposes APIs to configure, start, stop, and\n      automate recording workflows, and to capture cursor and system audio\n      alongside the screen.\n    humanURL: https://www.techsmith.com/camtasia.html\n    tags:\n      - SDK\n      - Screen Recording\n      - Embedded\n    properties:\n      - type: ProductPage\n        url: https://www.techsmith.com/camtasia.html\ncommon:\n  - type: Website\n    url: https://www.techsmith.com/camtasia.html\n  - type: Screencast\n    url: https://www.techsmith.com/screencast/\n  - type: GettingStarted\n    url: https://www.techsmith.com/learn/camtasia/\n  - type: Blog\n    url: https://www.techsmith.com/blog/category/camtasia/\n\
  \  - type: Support\n    url: https://support.techsmith.com\n  - type: PublicAPIRepository\n    url: https://github.com/TechSmith/screencast-public-api-docs\n  - type: TermsOfService\n    url: https://www.techsmith.com/terms.html\n  - type: PrivacyPolicy\n    url: https://www.techsmith.com/privacy.html\n  - type: JSON-LD\n    url: json-ld/camtasia-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/apis.yml
tags:
- Screen Recording
- Video Editing
- Tutorial Creation
- E-Learning
- Screencast
- oEmbed
- SDK
url: https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/apis.yml
use_cases: []
---
