---
api_count: 2
api_specs:
- filename: flux-image-generation-openapi.yml
  format: yaml
  label: Flux Image Generation API
  slug: flux-image-generation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/openapi/flux-image-generation-openapi.yml
- filename: flux-image-editing-openapi.yml
  format: yaml
  label: Flux Image Editing API
  slug: flux-image-editing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/openapi/flux-image-editing-openapi.yml
apis:
- description: REST API for generating images from text prompts using Black Forest Labs' FLUX models, including FLUX.1 [pro], FLUX.1 [dev], FLUX.1 [schnell], and FLUX.2 variants. The API follows an asynchronous patt
  name: Flux Image Generation API
  slug: flux-image-generation-api
- description: REST API for editing and transforming existing images using the FLUX.1 Kontext models. Accepts an input image and a text prompt describing desired edits, and returns a modified image. Supports context
  name: Flux Image Editing API
  slug: flux-image-editing-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/flux-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/flux-generation-request-schema.json
- title: ''
  type: Website
  url: https://bfl.ai/
- title: ''
  type: Documentation
  url: https://docs.bfl.ai/
- title: ''
  type: Getting Started
  url: https://docs.bfl.ml/quick_start/generating_images
- title: ''
  type: GitHub Organization
  url: https://github.com/black-forest-labs
- title: ''
  type: GitHubRepository
  url: https://github.com/black-forest-labs/flux
- title: ''
  type: Blog
  url: https://bfl.ai/blog
- title: ''
  type: Change Log
  url: https://docs.bfl.ai/release-notes
- title: ''
  type: Terms of Service
  url: https://bfl.ai/legal/flux-api-service-terms
- title: ''
  type: Privacy Policy
  url: https://bfl.ai/legal/privacy-policy
- title: ''
  type: Sign Up
  url: https://auth.bfl.ai/register
created: '2025-01-01'
description: An open-source text-to-image AI model developed by Black Forest Labs that generates high-quality images from text prompts with improved prompt following and visual quality.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Flux Context
  property_count: 5
  slug: flux-context
layout: provider
modified: '2026-04-28'
name: Flux
skills: []
slug: flux
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flux\nname: Flux\ndescription: An open-source text-to-image AI model developed by Black Forest Labs that generates high-quality images from text prompts with improved prompt following and visual quality.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - AI\n  - Image Generation\n  - Machine Learning\n  - Open Source\n  - Text to Image\napis:\n  - aid: flux:flux-image-generation-api\n    name: Flux Image Generation API\n    description: >-\n      REST API for generating images from text prompts using Black Forest Labs'\n      FLUX models, including FLUX.1 [pro], FLUX.1 [dev], FLUX.1 [schnell], and\n      FLUX.2 variants. The API follows an asynchronous pattern where requests\n      return a polling URL to retrieve the completed image result.\n    humanURL:\
  \ https://docs.bfl.ai/\n    baseURL: https://api.bfl.ai/v1\n    tags:\n      - AI\n      - Image Generation\n      - Machine Learning\n      - Text to Image\n    properties:\n      - type: Documentation\n        url: https://docs.bfl.ai/\n      - type: Getting Started\n        url: https://docs.bfl.ml/quick_start/generating_images\n      - type: Authentication\n        url: https://docs.bfl.ai/\n      - type: OpenAPI\n        url: openapi/flux-image-generation-openapi.yml\n      - type: JSONSchema\n        url: json-schema/flux-generation-request-schema.json\n  - aid: flux:flux-image-editing-api\n    name: Flux Image Editing API\n    description: >-\n      REST API for editing and transforming existing images using the FLUX.1\n      Kontext models. Accepts an input image and a text prompt describing\n      desired edits, and returns a modified image. Supports context-aware\n      in-painting, style transfer, and image-to-image transformations.\n    humanURL: https://docs.bfl.ml/kontext/kontext_image_editing\n\
  \    baseURL: https://api.bfl.ai/v1\n    tags:\n      - AI\n      - Image Editing\n      - Image to Image\n      - Kontext\n    properties:\n      - type: Documentation\n        url: https://docs.bfl.ml/kontext/kontext_image_editing\n      - type: OpenAPI\n        url: openapi/flux-image-editing-openapi.yml\ncommon:\n  - type: JSON-LD\n    url: json-ld/flux-context.jsonld\n  - type: JSONSchema\n    url: json-schema/flux-generation-request-schema.json\n  - type: Website\n    url: https://bfl.ai/\n  - type: Documentation\n    url: https://docs.bfl.ai/\n  - type: Getting Started\n    url: https://docs.bfl.ml/quick_start/generating_images\n  - type: GitHub Organization\n    url: https://github.com/black-forest-labs\n  - type: GitHubRepository\n    url: https://github.com/black-forest-labs/flux\n  - type: Blog\n    url: https://bfl.ai/blog\n  - type: Change Log\n    url: https://docs.bfl.ai/release-notes\n  - type: Terms of Service\n    url: https://bfl.ai/legal/flux-api-service-terms\n  -\
  \ type: Privacy Policy\n    url: https://bfl.ai/legal/privacy-policy\n  - type: Sign Up\n    url: https://auth.bfl.ai/register\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/apis.yml
tags:
- AI
- Image Generation
- Machine Learning
- Open Source
- Text to Image
url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/apis.yml
use_cases: []
---
