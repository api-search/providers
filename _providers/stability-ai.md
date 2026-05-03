---
api_count: 6
api_specs:
- filename: stability-ai-stable-image-generate-openapi.yml
  format: yaml
  label: Stability AI Stable Image Generate API
  slug: stable-image-generate
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-generate-openapi.yml
- filename: stability-ai-stable-image-edit-openapi.yml
  format: yaml
  label: Stability AI Stable Image Edit API
  slug: stable-image-edit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-edit-openapi.yml
- filename: stability-ai-stable-image-upscale-openapi.yml
  format: yaml
  label: Stability AI Stable Image Upscale API
  slug: stable-image-upscale
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-upscale-openapi.yml
- filename: stability-ai-stable-image-control-openapi.yml
  format: yaml
  label: Stability AI Stable Image Control API
  slug: stable-image-control
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-control-openapi.yml
- filename: stability-ai-stable-video-diffusion-openapi.yml
  format: yaml
  label: Stability AI Stable Video Diffusion API
  slug: stable-video-diffusion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-video-diffusion-openapi.yml
- filename: stability-ai-stable-fast-3d-openapi.yml
  format: yaml
  label: Stability AI Stable Fast 3D API
  slug: stable-fast-3d
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-fast-3d-openapi.yml
apis:
- description: 'The Stability AI Stable Image Generate API provides text-to-image generation capabilities powered by models including Stable Diffusion 3.5 and Stable Image Ultra. Developers can generate high-quality '
  name: Stability AI Stable Image Generate API
  slug: stable-image-generate
- description: The Stability AI Stable Image Edit API provides image editing capabilities including inpainting, outpainting, object erasing, background removal, and search-and-replace functionality. Developers can u
  name: Stability AI Stable Image Edit API
  slug: stable-image-edit
- description: The Stability AI Stable Image Upscale API enables developers to increase the resolution of images using AI-powered upscaling models. The API offers both conservative upscaling, which preserves the ori
  name: Stability AI Stable Image Upscale API
  slug: stable-image-upscale
- description: The Stability AI Stable Image Control API provides image-to-image generation guided by structural inputs such as sketches and reference structures. Using ControlNet-based models, developers can genera
  name: Stability AI Stable Image Control API
  slug: stable-image-control
- description: The Stability AI Stable Video Diffusion API enables developers to generate short video clips from a single input image. Powered by the Stable Video Diffusion model, the API produces smooth animated se
  name: Stability AI Stable Video Diffusion API
  slug: stable-video-diffusion
- description: The Stability AI Stable Fast 3D API generates textured 3D mesh assets from single input images. The API rapidly produces 3D models suitable for use in games, augmented reality, virtual reality, and pr
  name: Stability AI Stable Fast 3D API
  slug: stable-fast-3d
capabilities:
- description: 'Unified workflow for AI-powered image creation using Stability AI''s complete image generation and editing suite. Combines text-to-image generation across all model tiers (Ultra, Core, SD3) with image '
  name: Stability AI Image Creation
  slug: image-creation
common:
- title: ''
  type: Website
  url: https://stability.ai
- title: ''
  type: Documentation
  url: https://platform.stability.ai/docs/getting-started
- title: ''
  type: Portal
  url: https://platform.stability.ai
- title: ''
  type: Pricing
  url: https://stability.ai/api-pricing-update-25
- title: ''
  type: Terms of Service
  url: https://stability.ai/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://stability.ai/privacy-policy
- title: ''
  type: GitHub Org
  url: https://github.com/stability-ai
- title: ''
  type: JSON-LD
  url: json-ld/stability-ai-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/stability-ai-image-generation-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/stability-ai-image-generation-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/stability-ai-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/stability-ai-rules.yml
created: '2026-03-20'
description: Stability AI is an AI company that develops open-source generative AI models for image, audio, video, and language, including the Stable Diffusion family of image generation models. The Stability AI developer platform provides REST APIs for text-to-image generation, image editing, image upscaling, image structure control, video generation, and 3D asset creation. All APIs are accessible at api.stability.ai using bearer token authentication.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Stability Ai Context
  property_count: 8
  slug: stability-ai-context
layout: provider
modified: '2026-05-02'
name: Stability AI
rules:
- name: Stability AI API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 7
  slug: stability-ai-rules
skills: []
slug: stability-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stability-ai\nname: Stability AI\ndescription: >-\n  Stability AI is an AI company that develops open-source generative AI models\n  for image, audio, video, and language, including the Stable Diffusion family\n  of image generation models. The Stability AI developer platform provides REST\n  APIs for text-to-image generation, image editing, image upscaling, image\n  structure control, video generation, and 3D asset creation. All APIs are\n  accessible at api.stability.ai using bearer token authentication.\nurl: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml\ntags:\n  - 3D Generation\n  - AI\n  - Generative AI\n  - Image Generation\n  - Image Editing\n  - Machine Learning\n  - Stable Diffusion\n  - Text to Image\n  - Video Generation\ncreated: '2026-03-20'\nmodified: '2026-05-02'\napis:\n  - aid: stability-ai:stable-image-generate\n    name: Stability AI Stable Image Generate API\n    tags:\n      - Generative AI\n      - Image Generation\n\
  \      - Stable Diffusion\n      - Text to Image\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/getting-started/stable-image\n    description: >-\n      The Stability AI Stable Image Generate API provides text-to-image\n      generation capabilities powered by models including Stable Diffusion 3.5\n      and Stable Image Ultra. Developers can generate high-quality images from\n      text prompts with control over style, dimensions, and output format. The\n      API supports multiple model tiers including Stable Image Core for fast and\n      affordable generation and Stable Image Ultra for state-of-the-art quality\n      results.\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-generate-openapi.yml\n        type: OpenAPI\n  - aid: stability-ai:stable-image-edit\n\
  \    name: Stability AI Stable Image Edit API\n    tags:\n      - Generative AI\n      - Image Editing\n      - Inpainting\n      - Outpainting\n      - Search and Replace\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    description: >-\n      The Stability AI Stable Image Edit API provides image editing capabilities\n      including inpainting, outpainting, object erasing, background removal, and\n      search-and-replace functionality. Developers can use natural language\n      prompts to modify existing images, fill in masked regions, extend image\n      boundaries, or replace specific objects within a scene.\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-edit-openapi.yml\n        type: OpenAPI\n  - aid: stability-ai:stable-image-upscale\n\
  \    name: Stability AI Stable Image Upscale API\n    tags:\n      - Generative AI\n      - Image Enhancement\n      - Image Upscaling\n      - Super Resolution\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    description: >-\n      The Stability AI Stable Image Upscale API enables developers to increase\n      the resolution of images using AI-powered upscaling models. The API offers\n      both conservative upscaling, which preserves the original image closely\n      while increasing resolution, and creative upscaling, which enhances and\n      adds detail to images during the upscaling process.\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-upscale-openapi.yml\n        type: OpenAPI\n  - aid: stability-ai:stable-image-control\n   \
  \ name: Stability AI Stable Image Control API\n    tags:\n      - ControlNet\n      - Generative AI\n      - Image Generation\n      - Image to Image\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    description: >-\n      The Stability AI Stable Image Control API provides image-to-image\n      generation guided by structural inputs such as sketches and reference\n      structures. Using ControlNet-based models, developers can generate new\n      images that follow the composition, edges, or layout of a source image\n      while applying new styles or content based on text prompts.\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-control-openapi.yml\n        type: OpenAPI\n  - aid: stability-ai:stable-video-diffusion\n    name: Stability\
  \ AI Stable Video Diffusion API\n    tags:\n      - Generative AI\n      - Image to Video\n      - Stable Diffusion\n      - Video Generation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/getting-started/stable-video\n    description: >-\n      The Stability AI Stable Video Diffusion API enables developers to generate\n      short video clips from a single input image. Powered by the Stable Video\n      Diffusion model, the API produces smooth animated sequences that bring\n      static images to life with realistic motion.\n    properties:\n      - url: https://platform.stability.ai/docs/getting-started/stable-video-diffusion\n        type: Documentation\n      - url: openapi/stability-ai-stable-video-diffusion-openapi.yml\n        type: OpenAPI\n  - aid: stability-ai:stable-fast-3d\n    name: Stability AI Stable Fast 3D API\n    tags:\n      - 3D Generation\n\
  \      - Generative AI\n      - Image to 3D\n      - Mesh Generation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    description: >-\n      The Stability AI Stable Fast 3D API generates textured 3D mesh assets from\n      single input images. The API rapidly produces 3D models suitable for use in\n      games, augmented reality, virtual reality, and product visualization\n      workflows.\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-fast-3d-openapi.yml\n        type: OpenAPI\ncommon:\n  - type: Website\n    url: https://stability.ai\n  - type: Documentation\n    url: https://platform.stability.ai/docs/getting-started\n  - type: Portal\n    url: https://platform.stability.ai\n  - type: Pricing\n    url: https://stability.ai/api-pricing-update-25\n\
  \  - type: Terms of Service\n    url: https://stability.ai/terms-of-service\n  - type: Privacy Policy\n    url: https://stability.ai/privacy-policy\n  - type: GitHub Org\n    url: https://github.com/stability-ai\n  - type: JSON-LD\n    url: json-ld/stability-ai-context.jsonld\n  - type: JSONSchema\n    url: json-schema/stability-ai-image-generation-schema.json\n  - type: JSONStructure\n    url: json-structure/stability-ai-image-generation-structure.json\n  - type: Vocabulary\n    url: vocabulary/stability-ai-vocabulary.yml\n  - type: SpectralRules\n    url: rules/stability-ai-rules.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml
tags:
- 3D Generation
- AI
- Generative AI
- Image Generation
- Image Editing
- Machine Learning
- Stable Diffusion
- Text to Image
- Video Generation
url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml
use_cases: []
---
