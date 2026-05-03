---
api_count: 1
api_specs:
- filename: warner-bros-discovery-content-partner-openapi.yml
  format: yaml
  label: Warner Bros. Discovery Content Partner API
  slug: wbd-content-partner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/warner-bros-discovery/refs/heads/main/openapi/warner-bros-discovery-content-partner-openapi.yml
apis:
- description: 'The Warner Bros. Discovery Content Partner Hub provides technical specifications and APIs for content partners to deliver media assets to WBD''s supply chain. Supports Automated Content Delivery (ACD) '
  name: Warner Bros. Discovery Content Partner API
  slug: wbd-content-partner-api
capabilities:
- description: Unified workflow for Warner Bros. Discovery content delivery operations. Enables content partners to submit media deliveries, validate metadata against MMC specifications, track delivery status, and m
  name: WBD Content Delivery Workflow
  slug: content-delivery
common:
- title: ''
  type: Website
  url: https://www.wbd.com/
- title: ''
  type: Portal
  url: https://partnerhub.warnermedia.com/
- title: ''
  type: Documentation
  url: https://partnerhub.warnermedia.com/specifications-and-guides
- title: ''
  type: GitHubOrganization
  url: https://github.com/WarnerMedia
- title: ''
  type: GitHubOrganization
  url: https://github.com/warnerbros
- title: ''
  type: Website
  url: https://www.max.com/
- title: ''
  type: Portal
  url: https://developer.wbd.com/
created: '2026-03-21'
description: Warner Bros. Discovery is a leading global media and entertainment company that creates and distributes the world's most differentiated and complete portfolio of branded content across television, film, and streaming. WBD operates the Max streaming platform, Warner Bros. film studio, HBO, CNN, Discovery, TNT, TBS, and many other brands. The company provides content partner APIs for media supply chain integration and maintains open source projects through its engineering teams.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Warner Bros Discovery Context
  property_count: 11
  slug: warner-bros-discovery-context
layout: provider
modified: '2026-05-03'
name: Warner Bros. Discovery
rules:
- name: Warner Bros. Discovery API Rules
  rule_count: 10
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 4
  slug: warner-bros-discovery-rules
skills: []
slug: warner-bros-discovery
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: warner-bros-discovery\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/warner-bros-discovery/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nname: Warner Bros. Discovery\ntags:\n  - Entertainment\n  - Media\n  - Streaming\n  - Content\n  - Television\n  - Film\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consumer\ndescription: >-\n  Warner Bros. Discovery is a leading global media and entertainment company\n  that creates and distributes the world's most differentiated and complete\n  portfolio of branded content across television, film, and streaming.\n  WBD operates the Max streaming platform, Warner Bros. film studio, HBO,\n  CNN, Discovery, TNT, TBS, and many other brands. The company provides\n  content partner APIs for media supply chain integration and maintains\n  open source projects through its engineering teams.\napis:\n  - aid: warner-bros-discovery:wbd-content-partner-api\n\
  \    name: Warner Bros. Discovery Content Partner API\n    tags:\n      - Content Delivery\n      - Media Supply Chain\n      - Metadata\n      - Media Ingest\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://partnerhub.warnermedia.com\n    humanURL: https://partnerhub.warnermedia.com/specifications-and-guides\n    properties:\n      - url: https://partnerhub.warnermedia.com/specifications-and-guides\n        type: Documentation\n      - url: openapi/warner-bros-discovery-content-partner-openapi.yml\n        type: OpenAPI\n      - url: rules/warner-bros-discovery-rules.yml\n        type: SpectralRules\n      - url: capabilities/content-delivery.yaml\n        type: NaftikoCapabilities\n      - url: json-schema/warner-bros-discovery-content-schema.json\n        type: JSONSchema\n      - url: json-ld/warner-bros-discovery-context.jsonld\n        type: JSONLDContext\n      - url: vocabulary/warner-bros-discovery-vocabulary.yml\n  \
  \      type: Vocabulary\n    description: >-\n      The Warner Bros. Discovery Content Partner Hub provides technical\n      specifications and APIs for content partners to deliver media assets\n      to WBD's supply chain. Supports Automated Content Delivery (ACD) via\n      Aspera P2P and MovieLabs Media Manifest Core (MMC) for technical and\n      configuration metadata delivery.\ncommon:\n  - url: https://www.wbd.com/\n    name: Warner Bros. Discovery\n    type: Website\n  - url: https://partnerhub.warnermedia.com/\n    name: Content Partner Hub\n    type: Portal\n  - url: https://partnerhub.warnermedia.com/specifications-and-guides\n    name: Technical Specifications and Guides\n    type: Documentation\n  - url: https://github.com/WarnerMedia\n    name: WarnerMedia Open Source GitHub\n    type: GitHubOrganization\n  - url: https://github.com/warnerbros\n    name: Warner Bros. GitHub Organization\n    type: GitHubOrganization\n  - url: https://www.max.com/\n    name: Max Streaming\
  \ Service\n    type: Website\n  - url: https://developer.wbd.com/\n    name: Warner Bros. Discovery Developer Portal\n    type: Portal\nintegrations:\n  - AWS\n  - Aspera (IBM)\n  - Google Vertex AI\n  - Mux\n  - MovieLabs Digital Distribution Framework\n  - BCP-47 Language Tags\nsolutions:\n  - Content Delivery and Media Supply Chain\n  - Streaming Platform (Max)\n  - Content Metadata Management\n  - Media Ingest and Distribution\nopenSource:\n  - name: gimme-aws-creds\n    description: Python CLI tool to obtain AWS credentials from Okta\n    url: https://github.com/WarnerMedia/gimme-aws-creds\n  - name: antiope-aws-module\n    description: AWS inventory and security tooling\n    url: https://github.com/WarnerMedia/antiope-aws-module\n  - name: react-static\n    description: Static site generator for React\n    url: https://github.com/warnerbros/react-static\n  - name: mux.js\n    description: JavaScript library for video segment parsing\n    url: https://github.com/warnerbros/mux.js\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/warner-bros-discovery/refs/heads/main/apis.yml
tags:
- Entertainment
- Media
- Streaming
- Content
- Television
- Film
url: https://raw.githubusercontent.com/api-evangelist/warner-bros-discovery/refs/heads/main/apis.yml
use_cases: []
---
