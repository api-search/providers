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
- description: The Stability AI Stable Image Generate API provides text-to-image generation capabilities powered by models including Stable Diffusion 3 and Stable Image Ultra. Developers can generate high-quality im
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
common:
- title: ''
  type: JSON-LD
  url: json-ld/stability-ai-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/stability-ai-image-generation-schema.json
created: ''
description: Stability AI is an AI company that develops open-source generative AI models for image, audio, video, and language, including the Stable Diffusion family of image generation models.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Stability Ai Context
  property_count: 8
  slug: stability-ai-context
layout: provider
modified: '2026-03-20'
name: stability-ai
skills: []
slug: stability-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stability-ai\nurl: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml\napis:\n  - aid: stability-ai:stable-image-generate\n    name: Stability AI Stable Image Generate API\n    tags:\n      - Generative AI\n      - Image Generation\n      - Stable Diffusion\n      - Text to Image\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/getting-started/stable-image\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-generate-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Stability AI Stable Image Generate API provides text-to-image generation\n      capabilities powered by models including Stable Diffusion 3 and Stable Image\n      Ultra. Developers can generate high-quality images from text prompts\
  \ with\n      control over style, dimensions, and output format. The API supports multiple\n      model tiers including Stable Image Core for fast and affordable generation and\n      Stable Image Ultra for state-of-the-art quality results.\n  - aid: stability-ai:stable-image-edit\n    name: Stability AI Stable Image Edit API\n    tags:\n      - Generative AI\n      - Image Editing\n      - Inpainting\n      - Outpainting\n      - Search and Replace\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-edit-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Stability AI Stable Image Edit API provides image editing capabilities\n      including inpainting, outpainting, object erasing,\
  \ background removal, and\n      search-and-replace functionality. Developers can use natural language prompts\n      to modify existing images, fill in masked regions, extend image boundaries,\n      or\n      replace specific objects within a scene. These tools enable advanced image\n      manipulation workflows without requiring traditional image editing expertise.\n  - aid: stability-ai:stable-image-upscale\n    name: Stability AI Stable Image Upscale API\n    tags:\n      - Generative AI\n      - Image Enhancement\n      - Image Upscaling\n      - Super Resolution\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-upscale-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Stability\
  \ AI Stable Image Upscale API enables developers to increase the\n      resolution of images using AI-powered upscaling models. The API offers both\n      conservative upscaling, which preserves the original image closely while\n      increasing resolution, and creative upscaling, which enhances and adds detail\n      to images during the upscaling process. These endpoints are useful for\n      improving image quality for print, display, or further processing workflows.\n  - aid: stability-ai:stable-image-control\n    name: Stability AI Stable Image Control API\n    tags:\n      - ControlNet\n      - Generative AI\n      - Image Generation\n      - Image to Image\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n        type: Documentation\n      - url: openapi/stability-ai-stable-image-control-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Stability AI Stable Image Control API provides image-to-image generation\n      guided by structural inputs such as sketches and reference structures. Using\n      ControlNet-based models, developers can generate new images that follow the\n      composition, edges, or layout of a source image while applying new styles or\n      content based on text prompts. The API supports sketch-to-image and\n      structure-guided generation workflows for precise creative control.\n  - aid: stability-ai:stable-video-diffusion\n    name: Stability AI Stable Video Diffusion API\n    tags:\n      - Generative AI\n      - Image to Video\n      - Stable Diffusion\n      - Video Generation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/getting-started/stable-video\n    properties:\n      - url: https://platform.stability.ai/docs/getting-started/stable-video-diffusion\n\
  \        type: Documentation\n      - url: openapi/stability-ai-stable-video-diffusion-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Stability AI Stable Video Diffusion API enables developers to generate\n      short video clips from a single input image. Powered by the Stable Video\n      Diffusion model, the API produces smooth animated sequences that bring static\n      images to life with realistic motion. This is useful for creating product\n      animations, visual effects previews, and dynamic content from existing image\n      assets.\n  - aid: stability-ai:stable-fast-3d\n    name: Stability AI Stable Fast 3D API\n    tags:\n      - 3D Generation\n      - Generative AI\n      - Image to 3D\n      - Mesh Generation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stability.ai\n    humanURL: https://platform.stability.ai/docs/api-reference\n    properties:\n      - url: https://platform.stability.ai/docs/api-reference\n\
  \        type: Documentation\n      - url: openapi/stability-ai-stable-fast-3d-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Stability AI Stable Fast 3D API generates textured 3D mesh assets from\n      single input images. The API rapidly produces 3D models suitable for use in\n      games, augmented reality, virtual reality, and product visualization\n      workflows. Developers can convert 2D images into fully textured 3D objects,\n      enabling rapid prototyping and asset creation without manual 3D modeling.\ncommon:\n  - type: JSON-LD\n    url: json-ld/stability-ai-context.jsonld\n  - type: JSONSchema\n    url: json-schema/stability-ai-image-generation-schema.json\nmodified: '2026-03-20'\ndescription: >-\n  Stability AI is an AI company that develops open-source generative AI models for\n  image, audio, video, and language, including the Stable Diffusion family of image\n  generation models.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml
use_cases: []
---
