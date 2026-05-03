---
api_count: 1
api_specs:
- filename: shutterstock-openapi.yml
  format: yaml
  label: Shutterstock API
  slug: shutterstock-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shutterstock/refs/heads/main/openapi/shutterstock-openapi.yml
apis:
- description: The Shutterstock REST API v2 provides access to 350M+ images, videos, audio tracks, sound effects, and editorial content. It supports searching by keyword, color, category, and visual similarity (comp
  name: Shutterstock API
  slug: shutterstock-api
capabilities:
- description: Workflow capability for discovering, evaluating, and licensing stock media from Shutterstock's library of 350M+ assets. Combines image search, video search, audio search, editorial content, computer v
  name: Shutterstock Media Search And Licensing
  slug: media-search-and-licensing
common: []
created: '2026-05-02'
description: Shutterstock is a leading global technology company providing high-quality images, videos, audio tracks, sound effects, and editorial content to businesses, individuals, and organizations worldwide. With a library of over 350 million assets, Shutterstock offers royalty-free creative content for marketing campaigns, website designs, social media, and more. The Shutterstock API provides programmatic access to search, browse, license, and download media assets, manage collections, access computer vision features, and handle OAuth 2.0 authentication. It also includes contributor profile management and user account operations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Shutterstock Context
  property_count: 20
  slug: shutterstock-context
layout: provider
modified: '2026-05-02'
name: Shutterstock
rules:
- name: Shutterstock API Rules
  rule_count: 10
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 3
  slug: shutterstock-rules
skills: []
slug: shutterstock
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shutterstock\nname: Shutterstock\ndescription: >-\n  Shutterstock is a leading global technology company providing high-quality\n  images, videos, audio tracks, sound effects, and editorial content to businesses,\n  individuals, and organizations worldwide. With a library of over 350 million\n  assets, Shutterstock offers royalty-free creative content for marketing campaigns,\n  website designs, social media, and more. The Shutterstock API provides programmatic\n  access to search, browse, license, and download media assets, manage collections,\n  access computer vision features, and handle OAuth 2.0 authentication. It also\n  includes contributor profile management and user account operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Images\n  - Media\n  - Photos\n  - Stock Images\n  - Videos\n  - Audio\n  - Licensing\n  - Creative Content\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/shutterstock/refs/heads/main/apis.yml\n\
  created: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: shutterstock:shutterstock-api\n    name: Shutterstock API\n    description: >-\n      The Shutterstock REST API v2 provides access to 350M+ images, videos,\n      audio tracks, sound effects, and editorial content. It supports searching\n      by keyword, color, category, and visual similarity (computer vision).\n      Licensing operations support subscription and on-demand purchase models.\n      Collections allow users to organize and save assets. OAuth 2.0 is required\n      for licensed content operations; Basic Auth is available for search and\n      browse endpoints.\n    humanURL: https://www.shutterstock.com/developers\n    baseURL: https://api.shutterstock.com\n    tags:\n      - Images\n      - Videos\n      - Audio\n      - Stock Media\n      - Licensing\n      - Creative Content\n      - Computer Vision\n      - Editorial\n    properties:\n      - type: Documentation\n        url: https://www.shutterstock.com/developers/documentation\n\
  \      - type: ApiReference\n        url: https://api-reference.shutterstock.com/\n      - type: GettingStarted\n        url: https://www.shutterstock.com/developers/documentation/getting-started\n      - type: Authentication\n        url: https://www.shutterstock.com/developers/documentation/authentication\n      - type: Tutorial\n        url: https://www.shutterstock.com/developers/documentation/tutorial\n      - type: Plans\n        url: https://www.shutterstock.com/api/pricing\n      - type: SDK\n        url: https://www.shutterstock.com/developers/documentation/javascript-sdk\n      - type: GitHubOrganization\n        url: https://github.com/shutterstock\n      - type: OpenAPI\n        url: openapi/shutterstock-openapi.yml\n      - type: JSONSchema\n        url: json-schema/shutterstock-image-schema.json\n      - type: JSONSchema\n        url: json-schema/shutterstock-video-schema.json\n      - type: JSONStructure\n        url: json-structure/shutterstock-image-structure.json\n  \
  \    - type: JSONLD\n        url: json-ld/shutterstock-context.jsonld\n      - type: SpectralRules\n        url: rules/shutterstock-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/media-search-and-licensing.yaml\n      - type: Vocabulary\n        url: vocabulary/shutterstock-vocabulary.yml\n    contact:\n      - FN: Shutterstock Developer Support\n        url: https://www.shutterstock.com/developers/contact-us\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shutterstock/refs/heads/main/apis.yml
tags:
- Images
- Media
- Photos
- Stock Images
- Videos
- Audio
- Licensing
- Creative Content
url: https://raw.githubusercontent.com/api-evangelist/shutterstock/refs/heads/main/apis.yml
use_cases: []
---
