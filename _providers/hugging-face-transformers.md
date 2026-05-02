---
api_count: 5
apis:
- description: Open-source Python library that provides pretrained models, tokenizers, and pipelines for inference and fine-tuning across NLP, vision, audio, and multimodal tasks. The high-level pipeline API gives d
  name: Hugging Face Transformers Library
  slug: transformers-library
- description: Serverless inference API for running predictions against thousands of models hosted on the Hugging Face Hub. Supports NLP, computer vision, audio, and multimodal tasks through a unified HTTP interface
  name: Hugging Face Inference API
  slug: inference-api
- description: REST API for interacting with the Hugging Face Hub - upload, download, and manage models, datasets, and spaces programmatically.
  name: Hugging Face Hub API
  slug: hub-api
- description: API for deploying and managing machine learning applications and demos using Gradio, Streamlit, or Docker on Hugging Face Spaces.
  name: Hugging Face Spaces API
  slug: spaces-api
- description: High-performance inference server for large language models with continuous batching, token streaming, tensor parallelism, and OpenAI-compatible chat completions endpoints.
  name: Text Generation Inference (TGI)
  slug: text-generation-inference
common:
- title: ''
  type: Website
  url: https://huggingface.co
- title: ''
  type: Blog
  url: https://huggingface.co/blog
- title: ''
  type: Documentation
  url: https://huggingface.co/docs
- title: ''
  type: Discord
  url: https://discord.gg/hugging-face
- title: ''
  type: GitHub Organization
  url: https://github.com/huggingface
- title: ''
  type: Twitter
  url: https://twitter.com/huggingface
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/huggingface
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/HuggingFace
- title: ''
  type: Terms of Service
  url: https://huggingface.co/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://huggingface.co/privacy
- title: ''
  type: Sign Up
  url: https://huggingface.co/join
- title: ''
  type: Rules
  url: https://raw.githubusercontent.com/api-evangelist/hugging-face-transformers/refs/heads/main/hugging-face-transformers-rules.yml
created: '2024'
description: Hugging Face Transformers is an open-source machine learning library providing thousands of pretrained models and pipelines for Natural Language Processing, Computer Vision, Audio, and multimodal tasks. This index covers the Transformers library and the surrounding Hugging Face APIs that developers use to run inference, manage models, deploy demos, and serve LLMs at scale.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Hugging Face Transformers
skills: []
slug: hugging-face-transformers
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hugging-face-transformers\nname: Hugging Face Transformers\ndescription: >-\n  Hugging Face Transformers is an open-source machine learning library\n  providing thousands of pretrained models and pipelines for Natural\n  Language Processing, Computer Vision, Audio, and multimodal tasks.\n  This index covers the Transformers library and the surrounding\n  Hugging Face APIs that developers use to run inference, manage models,\n  deploy demos, and serve LLMs at scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artificial Intelligence\n  - Computer Vision\n  - Deep Learning\n  - Machine Learning\n  - Natural Language Processing\n  - Open Source\n  - Transformers\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/hugging-face-transformers/refs/heads/main/apis.yml\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: hugging-face-transformers:transformers-library\n   \
  \ name: Hugging Face Transformers Library\n    description: >-\n      Open-source Python library that provides pretrained models, tokenizers,\n      and pipelines for inference and fine-tuning across NLP, vision, audio,\n      and multimodal tasks. The high-level pipeline API gives drop-in\n      access to text generation, classification, translation, summarization,\n      speech recognition, and many other tasks.\n    humanURL: https://huggingface.co/docs/transformers/index\n    tags:\n      - Library\n      - Open Source\n      - Pipelines\n      - Python\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/transformers/index\n      - type: GitHub Repository\n        url: https://github.com/huggingface/transformers\n      - type: Quick Tour\n        url: https://huggingface.co/docs/transformers/quicktour\n      - type: Task Guide\n        url: https://huggingface.co/docs/transformers/task_summary\n      - type: PyPI Package\n        url: https://pypi.org/project/transformers/\n\
  \      - type: Issues\n        url: https://github.com/huggingface/transformers/issues\n  - aid: hugging-face-transformers:inference-api\n    name: Hugging Face Inference API\n    description: >-\n      Serverless inference API for running predictions against thousands of\n      models hosted on the Hugging Face Hub. Supports NLP, computer vision,\n      audio, and multimodal tasks through a unified HTTP interface.\n    humanURL: https://huggingface.co/docs/api-inference/index\n    baseURL: https://api-inference.huggingface.co\n    tags:\n      - Inference\n      - Predictions\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/api-inference/index\n      - type: Authentication\n        url: https://huggingface.co/docs/api-inference/quicktour#authentication\n      - type: Pricing\n        url: https://huggingface.co/pricing\n  - aid: hugging-face-transformers:hub-api\n    name: Hugging Face Hub API\n    description: >-\n      REST\
  \ API for interacting with the Hugging Face Hub - upload, download,\n      and manage models, datasets, and spaces programmatically.\n    humanURL: https://huggingface.co/docs/hub/api\n    baseURL: https://huggingface.co/api\n    tags:\n      - Datasets\n      - Hub\n      - Models\n      - Repositories\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/huggingface_hub/index\n      - type: Python Client\n        url: https://huggingface.co/docs/huggingface_hub/package_reference/overview\n      - type: JavaScript Client\n        url: https://huggingface.co/docs/huggingface.js/index\n      - type: API Reference\n        url: https://huggingface.co/docs/hub/api\n      - type: GitHub\n        url: https://github.com/huggingface/huggingface_hub\n  - aid: hugging-face-transformers:spaces-api\n    name: Hugging Face Spaces API\n    description: >-\n      API for deploying and managing machine learning applications and demos\n      using Gradio, Streamlit,\
  \ or Docker on Hugging Face Spaces.\n    humanURL: https://huggingface.co/spaces\n    baseURL: https://huggingface.co/api/spaces\n    tags:\n      - Demos\n      - Deployment\n      - Gradio\n      - Spaces\n      - Streamlit\n    properties:\n      - type: Documentation\n        url: https://huggingface.co/docs/hub/spaces-overview\n      - type: Gradio Documentation\n        url: https://gradio.app/docs/\n      - type: Examples\n        url: https://huggingface.co/spaces\n  - aid: hugging-face-transformers:text-generation-inference\n    name: Text Generation Inference (TGI)\n    description: >-\n      High-performance inference server for large language models with\n      continuous batching, token streaming, tensor parallelism, and\n      OpenAI-compatible chat completions endpoints.\n    humanURL: https://huggingface.co/docs/text-generation-inference/index\n    tags:\n      - Inference Server\n      - LLM\n      - Streaming\n      - Text Generation\n    properties:\n      - type: Documentation\n\
  \        url: https://huggingface.co/docs/text-generation-inference/index\n      - type: GitHub Repository\n        url: https://github.com/huggingface/text-generation-inference\n      - type: API Reference\n        url: https://huggingface.co/docs/text-generation-inference/basic_tutorials/consuming_tgi\n      - type: Supported Models\n        url: https://huggingface.co/docs/text-generation-inference/supported_models\ncommon:\n  - type: Website\n    url: https://huggingface.co\n  - type: Blog\n    url: https://huggingface.co/blog\n  - type: Documentation\n    url: https://huggingface.co/docs\n  - type: Discord\n    url: https://discord.gg/hugging-face\n  - type: GitHub Organization\n    url: https://github.com/huggingface\n  - type: Twitter\n    url: https://twitter.com/huggingface\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/huggingface\n  - type: YouTube\n    url: https://www.youtube.com/c/HuggingFace\n  - type: Terms of Service\n    url: https://huggingface.co/terms-of-service\n\
  \  - type: Privacy Policy\n    url: https://huggingface.co/privacy\n  - type: Sign Up\n    url: https://huggingface.co/join\n  - type: Rules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/hugging-face-transformers/refs/heads/main/hugging-face-transformers-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hugging-face-transformers/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Computer Vision
- Deep Learning
- Machine Learning
- Natural Language Processing
- Open Source
- Transformers
url: https://raw.githubusercontent.com/api-evangelist/hugging-face-transformers/refs/heads/main/apis.yml
use_cases: []
---
