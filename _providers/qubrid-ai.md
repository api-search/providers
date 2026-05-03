---
api_count: 4
api_specs:
- filename: qubrid-ai-inference-openapi.yml
  format: yaml
  label: Qubrid AI Inference API
  slug: inference
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-inference-openapi.yml
- filename: qubrid-ai-compute-openapi.yml
  format: yaml
  label: Qubrid AI Compute API
  slug: compute
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-compute-openapi.yml
- filename: qubrid-ai-fine-tuning-openapi.yml
  format: yaml
  label: Qubrid AI Fine-Tuning API
  slug: fine-tuning
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-fine-tuning-openapi.yml
- filename: qubrid-ai-rag-openapi.yml
  format: yaml
  label: Qubrid AI RAG API
  slug: rag
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-rag-openapi.yml
apis:
- description: The Qubrid AI Inference API provides a single, OpenAI-compatible endpoint for orchestrating 40+ open-source models running on NVIDIA GPU infrastructure. By abstracting hardware orchestration through T
  name: Qubrid AI Inference API
  slug: inference
- description: The Qubrid AI Compute API provides programmatic access to GPU cloud infrastructure including NVIDIA H100, H200, and B200 accelerators. Developers can provision and manage GPU instances for AI and mach
  name: Qubrid AI Compute API
  slug: compute
- description: The Qubrid AI Fine-Tuning API enables developers and enterprises to customize open-source AI models using their own data. The API provides endpoints for uploading training datasets, configuring fine-t
  name: Qubrid AI Fine-Tuning API
  slug: fine-tuning
- description: The Qubrid AI RAG API provides retrieval-augmented generation capabilities that allow developers to upload departmental or enterprise data and query it using large language models. The API handles doc
  name: Qubrid AI RAG API
  slug: rag
common:
- title: ''
  type: Portal
  url: https://platform.qubrid.com
- title: ''
  type: Documentation
  url: https://docs.platform.qubrid.com
- title: ''
  type: Website
  url: https://qubrid.com
- title: ''
  type: Login
  url: https://platform.qubrid.com/login
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-ld/qubrid-ai-context.jsonld
created: '2026-03-24'
description: Qubrid AI is a cloud platform that provides GPU-accelerated infrastructure and AI services for enterprise developers. Their developer platform offers OpenAI-compatible inference endpoints, GPU compute provisioning, model fine-tuning, and retrieval-augmented generation capabilities, all running on NVIDIA GPU infrastructure.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Qubrid Ai Context
  property_count: 8
  slug: qubrid-ai-context
layout: provider
modified: '2026-04-28'
name: Qubrid AI
skills: []
slug: qubrid-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: qubrid-ai\nname: Qubrid AI\ndescription: >-\n  Qubrid AI is a cloud platform that provides GPU-accelerated infrastructure\n  and AI services for enterprise developers. Their developer platform offers\n  OpenAI-compatible inference endpoints, GPU compute provisioning, model\n  fine-tuning, and retrieval-augmented generation capabilities, all running on\n  NVIDIA GPU infrastructure.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artificial Intelligence\n  - Cloud Computing\n  - GPU\n  - Inference\n  - Large Language Models\n  - Machine Learning\n  - NVIDIA\n  - Serverless\nurl: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: qubrid-ai:inference\n    name: Qubrid AI Inference API\n    description: >-\n      The Qubrid AI Inference API provides\
  \ a single, OpenAI-compatible endpoint\n      for orchestrating 40+ open-source models running on NVIDIA GPU\n      infrastructure. By abstracting hardware orchestration through TensorRT-LLM\n      and Triton Inference Server, the API allows enterprise developers to run\n      inference on models without managing underlying infrastructure.\n    humanURL: https://docs.platform.qubrid.com\n    baseURL: https://platform.qubrid.com/api/v1\n    tags:\n      - Artificial Intelligence\n      - Inference\n      - Large Language Models\n      - Machine Learning\n      - NVIDIA\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.platform.qubrid.com\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-inference-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-inference-schema.json\n\
  \  - aid: qubrid-ai:compute\n    name: Qubrid AI Compute API\n    description: >-\n      The Qubrid AI Compute API provides programmatic access to GPU cloud\n      infrastructure including NVIDIA H100, H200, and B200 accelerators.\n      Developers can provision and manage GPU instances for AI and machine\n      learning workloads through API calls.\n    humanURL: https://docs.platform.qubrid.com\n    baseURL: https://platform.qubrid.com/api/v1\n    tags:\n      - Cloud Computing\n      - GPU\n      - NVIDIA\n      - Infrastructure\n    properties:\n      - type: Documentation\n        url: https://docs.platform.qubrid.com\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-compute-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-compute-schema.json\n  - aid: qubrid-ai:fine-tuning\n    name: Qubrid AI Fine-Tuning\
  \ API\n    description: >-\n      The Qubrid AI Fine-Tuning API enables developers and enterprises to\n      customize open-source AI models using their own data. The API provides\n      endpoints for uploading training datasets, configuring fine-tuning\n      parameters, launching training jobs on GPU infrastructure, and retrieving\n      fine-tuned model artifacts.\n    humanURL: https://docs.platform.qubrid.com\n    baseURL: https://platform.qubrid.com/api/v1\n    tags:\n      - Artificial Intelligence\n      - Fine-Tuning\n      - Machine Learning\n      - Model Training\n    properties:\n      - type: Documentation\n        url: https://docs.platform.qubrid.com\n      - type: Documentation\n        url: https://docs.platform.qubrid.com/Fine%20Tuning\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-fine-tuning-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-fine-tuning-schema.json\n\
  \  - aid: qubrid-ai:rag\n    name: Qubrid AI RAG API\n    description: >-\n      The Qubrid AI RAG API provides retrieval-augmented generation\n      capabilities that allow developers to upload departmental or enterprise\n      data and query it using large language models. The API handles document\n      ingestion, embedding generation, vector storage, and context-aware\n      retrieval to ground model responses in organizational knowledge.\n    humanURL: https://docs.platform.qubrid.com\n    baseURL: https://platform.qubrid.com/api/v1\n    tags:\n      - Artificial Intelligence\n      - RAG\n      - Retrieval Augmented Generation\n      - Search\n      - Knowledge Management\n    properties:\n      - type: Documentation\n        url: https://docs.platform.qubrid.com\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-rag-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-rag-schema.json\n\
  common:\n  - type: Portal\n    url: https://platform.qubrid.com\n  - type: Documentation\n    url: https://docs.platform.qubrid.com\n  - type: Website\n    url: https://qubrid.com\n  - type: Login\n    url: https://platform.qubrid.com/login\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-ld/qubrid-ai-context.jsonld\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Cloud Computing
- GPU
- Inference
- Large Language Models
- Machine Learning
- NVIDIA
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/apis.yml
use_cases: []
---
