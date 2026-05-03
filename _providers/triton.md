---
api_count: 3
api_specs:
- filename: rest_api.yaml
  format: yaml
  label: Triton HTTP/REST API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/rest_api.yaml
- filename: triton-metrics-openapi.yml
  format: yaml
  label: Triton Metrics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/triton/refs/heads/main/openapi/triton-metrics-openapi.yml
apis:
- description: RESTful API for model inference, health checks, metadata queries, and server management.
  name: Triton HTTP/REST API
  slug: ''
- description: High-performance GRPC API for model inference with support for streaming and binary tensor data.
  name: Triton GRPC API
  slug: ''
- description: Prometheus-compatible metrics API for monitoring server and model performance.
  name: Triton Metrics API
  slug: ''
common:
- title: ''
  type: GitHub Repository
  url: https://github.com/triton-inference-server/server
- title: ''
  type: Documentation
  url: https://docs.nvidia.com/deeplearning/triton-inference-server/
- title: ''
  type: Getting Started
  url: https://github.com/triton-inference-server/server/blob/main/docs/getting_started/quickstart.md
- title: ''
  type: Client Libraries
  url: https://github.com/triton-inference-server/client
- title: ''
  type: Model Repository
  url: https://github.com/triton-inference-server/server/blob/main/docs/user_guide/model_repository.md
- title: ''
  type: Supported Backends
  url: https://github.com/triton-inference-server/backend
- title: ''
  type: Docker Images
  url: https://catalog.ngc.nvidia.com/orgs/nvidia/containers/tritonserver
- title: ''
  type: Community Forum
  url: https://github.com/triton-inference-server/server/discussions
- title: ''
  type: Release Notes
  url: https://github.com/triton-inference-server/server/releases
- title: ''
  type: JSON-LD
  url: json-ld/triton-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/triton-model-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/triton-inference-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/triton-inference-response-schema.json
created: '2024-01-15'
description: NVIDIA Triton Inference Server provides a cloud and edge inferencing solution optimized for both CPUs and GPUs. Triton supports an HTTP/REST and GRPC protocol that allows remote clients to request inferencing for any model being managed by the server.
features: []
image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Triton Context
  property_count: 9
  slug: triton-context
layout: provider
modified: '2026-03-16'
name: Triton Inference Server
skills: []
slug: triton
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Triton Inference Server\ndescription: NVIDIA Triton Inference Server provides a cloud and edge inferencing solution optimized for both CPUs and GPUs. Triton supports an HTTP/REST and GRPC protocol that allows remote clients to request inferencing for any model being managed by the server.\nimage: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\ntags:\n  - AI\n  - Deep Learning\n  - Inference\n  - Machine Learning\n  - Model Serving\ncreated: '2024-01-15'\nmodified: '2026-03-16'\nurl: https://github.com/triton-inference-server/server\nspecificationVersion: '0.18'\napis:\n  - name: Triton HTTP/REST API\n    description: >-\n      RESTful API for model inference, health checks, metadata queries, and server\n      management.\n    image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\n    humanURL: https://github.com/triton-inference-server/server/blob/main/docs/protocol/extension_binary_data.md\n    baseURL: http://localhost:8000\n\
  \    tags:\n      - HTTP\n      - Inference\n      - Model Management\n      - REST\n    properties:\n      - type: Documentation\n        url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/extension_binary_data.md\n      - type: OpenAPI\n        url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/rest_api.yaml\n      - type: Postman Collection\n        url: https://www.postman.com/nvidia-triton\n      - type: OpenAPI\n        url: openapi/triton-http-rest-openapi.yml\n    contact:\n      - FN: NVIDIA Triton Team\n        email: triton@nvidia.com\n  - name: Triton GRPC API\n    description: >-\n      High-performance GRPC API for model inference with support for streaming and\n      binary tensor data.\n    image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\n    humanURL: https://github.com/triton-inference-server/server/blob/main/docs/protocol/README.md\n    baseURL: grpc://localhost:8001\n    tags:\n \
  \     - GRPC\n      - High Performance\n      - Inference\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/README.md\n      - type: Protocol Buffers\n        url: https://github.com/triton-inference-server/common/blob/main/protobuf/grpc_service.proto\n      - type: Examples\n        url: https://github.com/triton-inference-server/client/tree/main/src/python/examples\n    contact:\n      - FN: NVIDIA Triton Team\n        email: triton@nvidia.com\n  - name: Triton Metrics API\n    description: >-\n      Prometheus-compatible metrics API for monitoring server and model performance.\n    image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\n    humanURL: https://github.com/triton-inference-server/server/blob/main/docs/user_guide/metrics.md\n    baseURL: http://localhost:8002/metrics\n    tags:\n      - Metrics\n      - Monitoring\n      - Observability\n      -\
  \ Prometheus\n    properties:\n      - type: Documentation\n        url: https://github.com/triton-inference-server/server/blob/main/docs/user_guide/metrics.md\n      - type: Metrics Format\n        url: https://prometheus.io/docs/instrumenting/exposition_formats/\n      - type: OpenAPI\n        url: openapi/triton-metrics-openapi.yml\n    contact:\n      - FN: NVIDIA Triton Team\n        email: triton@nvidia.com\ncommon:\n  - type: GitHub Repository\n    url: https://github.com/triton-inference-server/server\n  - type: Documentation\n    url: https://docs.nvidia.com/deeplearning/triton-inference-server/\n  - type: Getting Started\n    url: https://github.com/triton-inference-server/server/blob/main/docs/getting_started/quickstart.md\n  - type: Client Libraries\n    url: https://github.com/triton-inference-server/client\n  - type: Model Repository\n    url: https://github.com/triton-inference-server/server/blob/main/docs/user_guide/model_repository.md\n  - type: Supported Backends\n  \
  \  url: https://github.com/triton-inference-server/backend\n  - type: Docker Images\n    url: https://catalog.ngc.nvidia.com/orgs/nvidia/containers/tritonserver\n  - type: Community Forum\n    url: https://github.com/triton-inference-server/server/discussions\n  - type: Release Notes\n    url: https://github.com/triton-inference-server/server/releases\n  - type: JSON-LD\n    url: json-ld/triton-context.jsonld\n  - type: JSONSchema\n    url: json-schema/triton-model-schema.json\n  - type: JSONSchema\n    url: json-schema/triton-inference-request-schema.json\n  - type: JSONSchema\n    url: json-schema/triton-inference-response-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/triton/refs/heads/main/apis.yml
tags:
- AI
- Deep Learning
- Inference
- Machine Learning
- Model Serving
url: https://github.com/triton-inference-server/server
use_cases: []
---
