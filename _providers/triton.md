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
- description: RESTful API implementing the KServe V2 inference protocol for model inference, health checks, metadata queries, model repository management, statistics, tracing, and logging.
  name: Triton HTTP/REST API
  slug: ''
- description: High-performance gRPC API for model inference with support for streaming and binary tensor data.
  name: Triton GRPC API
  slug: ''
- description: Prometheus-compatible metrics API for monitoring server and model performance including inference request counts, latencies, GPU utilization, and memory usage.
  name: Triton Metrics API
  slug: ''
capabilities:
- description: Workflow capability for deploying, managing, and running inference against machine learning models on NVIDIA Triton Inference Server. Enables model lifecycle management including loading, health check
  name: Triton Model Inference and Management
  slug: model-inference
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
  type: PyTriton
  url: https://github.com/triton-inference-server/pytriton
- title: ''
  type: Model Analyzer
  url: https://github.com/triton-inference-server/model_analyzer
- title: ''
  type: Triton CLI
  url: https://github.com/triton-inference-server/triton_cli
- title: ''
  type: OpenAPI
  url: openapi/triton-http-rest-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/triton-metrics-openapi.yml
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
- title: ''
  type: JSON Structure
  url: json-structure/triton-model-structure.json
- title: ''
  type: Spectral Rules
  url: rules/triton-rules.yml
- title: ''
  type: Naftiko Capability
  url: capabilities/model-inference.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/triton-vocabulary.yml
- title: ''
  type: x-profiled
  url: 2026-05
created: '2024-01-15'
description: NVIDIA Triton Inference Server provides a cloud and edge inferencing solution optimized for both CPUs and GPUs. Triton supports an HTTP/REST and gRPC protocol that allows remote clients to request inferencing for any model being managed by the server. Open source and part of the broader NVIDIA AI ecosystem, Triton implements the KServe V2 inference protocol supporting TensorRT, TensorFlow, PyTorch, ONNX Runtime, Python, and more backends.
features: []
image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Triton Context
  property_count: 9
  slug: triton-context
layout: provider
modified: '2026-05-03'
name: Triton Inference Server
rules:
- name: Triton Inference Server API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 5
  slug: triton-rules
skills: []
slug: triton
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Triton Inference Server\ndescription: >-\n  NVIDIA Triton Inference Server provides a cloud and edge inferencing solution optimized\n  for both CPUs and GPUs. Triton supports an HTTP/REST and gRPC protocol that allows remote\n  clients to request inferencing for any model being managed by the server. Open source and\n  part of the broader NVIDIA AI ecosystem, Triton implements the KServe V2 inference protocol\n  supporting TensorRT, TensorFlow, PyTorch, ONNX Runtime, Python, and more backends.\nimage: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\ntags:\n  - AI\n  - Deep Learning\n  - Inference\n  - Machine Learning\n  - Model Serving\n  - NVIDIA\n  - Open Source\ncreated: '2024-01-15'\nmodified: '2026-05-03'\nurl: https://github.com/triton-inference-server/server\nspecificationVersion: '0.18'\napis:\n  - name: Triton HTTP/REST API\n    description: >-\n      RESTful API implementing the KServe V2 inference protocol for model inference, health\n\
  \      checks, metadata queries, model repository management, statistics, tracing, and logging.\n    image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\n    humanURL: https://github.com/triton-inference-server/server/blob/main/docs/protocol/extension_binary_data.md\n    baseURL: http://localhost:8000\n    tags:\n      - HTTP\n      - Inference\n      - Model Management\n      - REST\n      - KServe\n    properties:\n      - type: Documentation\n        url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/extension_binary_data.md\n      - type: OpenAPI\n        url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/rest_api.yaml\n      - type: Postman Collection\n        url: https://www.postman.com/nvidia-triton\n      - type: OpenAPI\n        url: openapi/triton-http-rest-openapi.yml\n    contact:\n      - FN: NVIDIA Triton Team\n        email: triton@nvidia.com\n\n  - name: Triton GRPC API\n    description:\
  \ >-\n      High-performance gRPC API for model inference with support for streaming and\n      binary tensor data.\n    image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\n    humanURL: https://github.com/triton-inference-server/server/blob/main/docs/protocol/README.md\n    baseURL: grpc://localhost:8001\n    tags:\n      - GRPC\n      - High Performance\n      - Inference\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/README.md\n      - type: Protocol Buffers\n        url: https://github.com/triton-inference-server/common/blob/main/protobuf/grpc_service.proto\n      - type: Examples\n        url: https://github.com/triton-inference-server/client/tree/main/src/python/examples\n    contact:\n      - FN: NVIDIA Triton Team\n        email: triton@nvidia.com\n\n  - name: Triton Metrics API\n    description: >-\n      Prometheus-compatible metrics API for monitoring\
  \ server and model performance including\n      inference request counts, latencies, GPU utilization, and memory usage.\n    image: https://developer.nvidia.com/sites/default/files/akamai/triton-logo.png\n    humanURL: https://github.com/triton-inference-server/server/blob/main/docs/user_guide/metrics.md\n    baseURL: http://localhost:8002/metrics\n    tags:\n      - Metrics\n      - Monitoring\n      - Observability\n      - Prometheus\n    properties:\n      - type: Documentation\n        url: https://github.com/triton-inference-server/server/blob/main/docs/user_guide/metrics.md\n      - type: Metrics Format\n        url: https://prometheus.io/docs/instrumenting/exposition_formats/\n      - type: OpenAPI\n        url: openapi/triton-metrics-openapi.yml\n    contact:\n      - FN: NVIDIA Triton Team\n        email: triton@nvidia.com\n\ncommon:\n  - type: GitHub Repository\n    url: https://github.com/triton-inference-server/server\n  - type: Documentation\n    url: https://docs.nvidia.com/deeplearning/triton-inference-server/\n\
  \  - type: Getting Started\n    url: https://github.com/triton-inference-server/server/blob/main/docs/getting_started/quickstart.md\n  - type: Client Libraries\n    url: https://github.com/triton-inference-server/client\n  - type: Model Repository\n    url: https://github.com/triton-inference-server/server/blob/main/docs/user_guide/model_repository.md\n  - type: Supported Backends\n    url: https://github.com/triton-inference-server/backend\n  - type: Docker Images\n    url: https://catalog.ngc.nvidia.com/orgs/nvidia/containers/tritonserver\n  - type: Community Forum\n    url: https://github.com/triton-inference-server/server/discussions\n  - type: Release Notes\n    url: https://github.com/triton-inference-server/server/releases\n  - type: PyTriton\n    url: https://github.com/triton-inference-server/pytriton\n  - type: Model Analyzer\n    url: https://github.com/triton-inference-server/model_analyzer\n  - type: Triton CLI\n    url: https://github.com/triton-inference-server/triton_cli\n\
  \  - type: OpenAPI\n    url: openapi/triton-http-rest-openapi.yml\n  - type: OpenAPI\n    url: openapi/triton-metrics-openapi.yml\n  - type: JSON-LD\n    url: json-ld/triton-context.jsonld\n  - type: JSONSchema\n    url: json-schema/triton-model-schema.json\n  - type: JSONSchema\n    url: json-schema/triton-inference-request-schema.json\n  - type: JSONSchema\n    url: json-schema/triton-inference-response-schema.json\n  - type: JSON Structure\n    url: json-structure/triton-model-structure.json\n  - type: Spectral Rules\n    url: rules/triton-rules.yml\n  - type: Naftiko Capability\n    url: capabilities/model-inference.yaml\n  - type: Vocabulary\n    url: vocabulary/triton-vocabulary.yml\n  - type: x-profiled\n    url: '2026-05'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/triton/refs/heads/main/apis.yml
tags:
- AI
- Deep Learning
- Inference
- Machine Learning
- Model Serving
- NVIDIA
- Open Source
url: https://github.com/triton-inference-server/server
use_cases: []
---
